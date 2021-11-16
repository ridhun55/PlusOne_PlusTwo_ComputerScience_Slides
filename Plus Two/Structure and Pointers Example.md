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

# Example 3 : Nested Structure [def 2] 
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
