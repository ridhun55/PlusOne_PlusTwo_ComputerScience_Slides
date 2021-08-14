# C++ Examples Documentation
# RIDHUN DEV

C++ Examples Codes Run In Dav C++ IDE </br>
Download Dev C++ Software : https://sourceforge.net/projects/orwelldevcpp/

# Example 1 : String array

<pre class="hljs"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword">using</span> <span class="hljs-keyword">namespace</span> <span class="hljs-built_in">std</span>;
<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword">char</span> var[<span class="hljs-number">6</span>]= {<span class="hljs-string">'H'</span>,<span class="hljs-string">'e'</span>,<span class="hljs-string">'l'</span>,<span class="hljs-string">'l'</span>,<span class="hljs-string">'o'</span>,<span class="hljs-string">'\0'</span>};
    <span class="hljs-built_in">cout</span> &lt;&lt; <span class="hljs-string">"Output Is : \n"</span>;
    <span class="hljs-built_in">cout</span> &lt;&lt; var &lt;&lt; <span class="hljs-built_in">endl</span>;
}</pre>

# Example 2 : String Array

<pre class="hljs"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword">using</span> <span class="hljs-keyword">namespace</span> <span class="hljs-built_in">std</span>;
<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword">char</span> var[<span class="hljs-number">50</span>]  = <span class="hljs-string">"Hello"</span>;
    <span class="hljs-built_in">cout</span> &lt;&lt; <span class="hljs-string">"Output Is : \n"</span>;
    <span class="hljs-built_in">cout</span> &lt;&lt; var &lt;&lt; <span class="hljs-built_in">endl</span>;
}</pre>

# Example 3 : program to input a string

<pre class="hljs"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-keyword">using</span> <span class="hljs-keyword">namespace</span> <span class="hljs-built_in">std</span>;

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword">char</span> str[<span class="hljs-number">50</span>];

    <span class="hljs-built_in">cout</span> &lt;&lt; <span class="hljs-string">"Enter a string: "</span>;
    <span class="hljs-built_in">cin</span> &gt;&gt; str;
    
    <span class="hljs-built_in">cout</span> &lt;&lt; <span class="hljs-string">"Output : "</span>;
    <span class="hljs-built_in">cout</span> &lt;&lt; str;
}</pre>

# Example 4 : gets() and space

<pre class="hljs"><span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;iostream&gt;</span></span>
<span class="hljs-meta">#<span class="hljs-meta-keyword">include</span> <span class="hljs-meta-string">&lt;cstdio&gt;</span></span>
<span class="hljs-keyword">using</span> <span class="hljs-keyword">namespace</span> <span class="hljs-built_in">std</span>;

<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword">char</span> str[<span class="hljs-number">50</span>];
    <span class="hljs-built_in">cout</span> &lt;&lt; <span class="hljs-string">"Enter a string: "</span>;
    gets(str);
    <span class="hljs-built_in">cout</span> &lt;&lt; <span class="hljs-string">"Output: "</span> &lt;&lt; str;
}</pre>

# Strings Input / Output Functions 

# Example 5 : getchar()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstdio&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> var;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a character : "</span>; 
  var = getchar();
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output : "</span>; 
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt; var;
}</pre>

# Example 6 : getch()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;conio.h&gt;</span> </span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>; 

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>  
</span>{  
    <span class="hljs-keyword" style="font-weight: 700;">char</span> var;  
    <span class="hljs-keyword" style="font-weight: 700;">int</span> x;  
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">printf</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a character = "</span>);  
	var = getch();  
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;var;  
}  </pre>

# Example 7 : getch() - hidden password

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;conio.h&gt;</span> </span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>; 

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>  
</span>{  
    <span class="hljs-keyword" style="font-weight: 700;">char</span> pw[<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>];  
    <span class="hljs-keyword" style="font-weight: 700;">int</span> x;  
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">printf</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">" Enter password (5) = "</span>);  
    
	<span class="hljs-keyword" style="font-weight: 700;">for</span> (x = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; x &lt; <span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>; x++)  
    { 
        pw[x] = getch();  
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"_"</span>;  
    } 
	 
    pw[x] = <span class="hljs-string" style="color: rgb(136, 0, 0);">'\0'</span>;  
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">printf</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n password is = "</span>);  
    
	<span class="hljs-keyword" style="font-weight: 700;">for</span> (x = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; pw[x] != <span class="hljs-string" style="color: rgb(136, 0, 0);">'\0'</span>; x++)  
    {  
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;pw[x];  
	}
}  </pre>

# Example 8 : getche() 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;conio.h&gt;</span> </span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>; 

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>  
</span>{  
    <span class="hljs-keyword" style="font-weight: 700;">char</span> var;  
    <span class="hljs-keyword" style="font-weight: 700;">int</span> x;  
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">printf</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a character = "</span>);  
	var = getche();  
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;var;  
}  </pre>

# Example 9 : putchar()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;conio.h&gt;</span> </span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>; 

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>  
</span>{  
    <span class="hljs-keyword" style="font-weight: 700;">char</span> var;   
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a character = "</span>;  
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;var;  
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">putchar</span>(var);  
}  </pre>

# Example 10 : putch()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-comment" style="color: rgb(136, 136, 136);">/* putchar example: printing the alphabet */</span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;stdio.h&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span> <span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> var = <span class="hljs-string" style="color: rgb(136, 0, 0);">'c'</span>;
  
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">putchar</span> (var);  	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">putchar</span> (var + <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>);  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">putchar</span> (var + <span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>);  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;
}</pre>

# Stream Functions

# Example 11 : get()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;stdio.h&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span> <span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> var;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a Character = "</span>;
  var = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>.get();
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;var;
}</pre>

# Example 12 : getline() 


#include <iostream>
using namespace std;

int main ()
{
  char var[10];
  cout<<"Enter a Character = ";
  cin.getline(var,4);		// end with 4th character (only 3 character stored)
  cout<<"\n Output = ";
  cout<<var;
}
	
# Example 13 : getline(var, len, delimit )

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span> <span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> var[<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>];
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a Character = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>.getline(var, <span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>, <span class="hljs-string" style="color: rgb(136, 0, 0);">'s'</span> );		<span class="hljs-comment" style="color: rgb(136, 136, 136);">// end with 4th character (only 3 character stored)</span>
  							<span class="hljs-comment" style="color: rgb(136, 136, 136);">// 's' act as delimiter</span>
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;var;
}</pre>
	
# Example 14 : put()
	
<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span> <span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> var;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a Character = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;var;		
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>.put(var);
}</pre>

# Example 15 : write(var, len)
	
<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span> <span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> var[<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>];
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter a Character = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;var;		
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n Output = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>.write(var, <span class="hljs-number" style="color: rgb(136, 0, 0);">4</span>);
}</pre>

# Example 26 : write("string", len)
	
<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span> <span class="hljs-params">()</span>
</span>{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>.write(<span class="hljs-string" style="color: rgb(136, 0, 0);">"hello"</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">3</span>);
}</pre>
