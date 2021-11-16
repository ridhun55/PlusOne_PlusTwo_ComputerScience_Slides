# Example 1 : Structure 
```c++
struct student
{
  int roll;
  float m1,m2,m3,t;
};

imt main()
{
  student s;
  cout << "Enter 3 marks";
  cin >> s.m1;
  cin >> s.m2;
  cin >> s.m3;
  s.t = s.m1 + s.m2 + s.m3;
  cout <<"Sum = " << s.t;
}

```

# Example 2 : Structure Array 
```c++
#include <iostream>
using namespace std;

struct student
{
	char name[50];
	int roll;
	float mark;
};

int main()
{
  student s[3];
  cout<<"Enter students information\n" ;
  for(int i=0;i<3;i++)
  {
  	s[i].roll = i+1;
  	cout<<"\n Name : ";
  	cin>>s[i].name;
  	cout<<"\n Mark : ";
  	cin>>s[i].mark;
  }
  cout<<"\n\n students information\n" ;
  cout<<"================================\n" ;
  for(int i=0;i<3;i++)
  {
  	cout<<s[i].roll; 
	cout<<":"; cout<<s[i].name; 
	cout<<":"; cout<<s[i].mark;
  	cout<<"\n";
  }
}
```

# Example 3 : Nested Structure [def 1] 
```c++
#include <iostream>
using namespace std;

struct date
{
	int day;
	int month;
	int year;
};

struct student
{
	int roll;
	char name[50];
	date dob;
};

int main()
{
  student s;
  cout<<"Enter Information\n" ;
  cout<<"\n Roll No : ";
  cin>> s.roll ;
  cout<<"\n Name : ";
  cin>>s.name;
  cout<<"\n Date Of Birth : ";
  cout<<"\n Day : ";cin>>s.dob.day;
  cout<<"\n Month : ";cin>>s.dob.month;
  cout<<"\n Year : ";cin>>s.dob.year;

  cout<<"\n\n students information\n" ;
  cout<<"================================\n" ;
  cout<<s.roll; 
  cout<<" : "; cout<<s.name; 
  cout<<" : "; cout<<s.dob.day;cout<<"/";cout<<s.dob.month;cout<<"/";cout<<s.dob.year;
  cout<<"\n";
}
```

# Example 4 : Nested Structure [def 2] 
```c++
#include <iostream>
using namespace std;

struct student
{
	int roll;
	char name[50];
	struct date
	{
		int day;
		int month;
		int year;
	}dob;
};

int main()
{
  student s;
  cout<<"Enter Information\n" ;
  cout<<"\n Roll No : ";
  cin>> s.roll ;
  cout<<"\n Name : ";
  cin>>s.name;
  cout<<"\n Date Of Birth : ";
  cout<<"\n Day : ";cin>>s.dob.day;
  cout<<"\n Month : ";cin>>s.dob.month;
  cout<<"\n Year : ";cin>>s.dob.year;

  cout<<"\n\n students information\n" ;
  cout<<"================================\n" ;
  cout<<s.roll; 
  cout<<" : "; cout<<s.name; 
  cout<<" : "; cout<<s.dob.day;cout<<"/";cout<<s.dob.month;cout<<"/";cout<<s.dob.year;
  cout<<"\n";
}
```
</br>
<h1>Pointer</h1>
</br>

# Example 5 : & -Address of operator * -Dereference operators
```c++
#include <iostream>
using namespace std;

int main()
{
  int x = 25;
  int *ptr = &x;
  cout<< &x; cout<<" --> &x\n";
  cout<< ptr; cout<<" --> ptr\n";
  cout<< *ptr; cout<<" --> *ptr\n";
  cout<< &ptr; cout<<" --> &ptr\n";
  cout<< x; cout<<" --> x\n";
}
```


# Example 6 : Write a program to addtwo numbers using pointer
```c++
#include <iostream>
using namespace std;

int main()
{
  int x, y;
  int *ptr1, *ptr2;
  ptr1 = &x;
  ptr2 = &y;
  cout<< "Enter 1st Number : ";
  cin>> *ptr1;
  cout<< "\nEnter 2nd Number : ";
  cin>> *ptr2;
  cout<< "\n Sum = " << *ptr1 + *ptr2;
}
```

# Example 7 : new & delete Operator [Dynamic]
```c++
#include <iostream>
using namespace std;

int main()
{
  int *ptr;
  ptr = new int;
  cout<< "Enter a Number : ";
  cin>> *ptr;
  cout<< "\n Number is : "<< *ptr;
  delete ptr;
}
```

# Example 8 : Pointer Array [ shows first data only ]
```c++
#include <iostream>
using namespace std;

int main()
{
  int data[5] = {10, 5, 7, 8};
  int *ptr = &data[0];
  cout<< "\n &data : " <<&data;
  cout<< " -- ptr : "<< ptr;
}
```

# Example 9 : Pointer Array
```c++
#include <iostream>
using namespace std;

int main()
{
  int data[5] = {10, 5, 7, 8};
  
  for(int i=0;i<5;i++)
  {
  	cout<<*(data + i)<<"\n";
  }
}
```

#  Example 10 : Pointer Array
```c++
#include <iostream>
using namespace std;

int main()
{
  int data[5];
  cout<<"Enter 5 Number";
  for(int i=0;i<5;i++)
  {
  	cin>>*(data + i);
  }
  
  cout<<"\nNumbers are\n";
  for(int i=0;i<5;i++)
  {
  	cout<<*(data + i)<<"\n";
  }
}
```

# Example 11 : pointer string array

```c++
#include <iostream>
using namespace std;

int main()
{
  char *name[4] = {"appu", "raju", "vishnu", "vivek"};
  
  cout<<"Strings are : \n";
  for(int i=0;i<4;i++)
  {
  	cout<< name[i] <<"\n";
  }
}
```
