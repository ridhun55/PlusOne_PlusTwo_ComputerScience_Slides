# C++ Examples Documentation
# RIDHUN DEV

C++ Examples Codes Run In Dav C++ IDE </br>
Download Dev C++ Software : https://sourceforge.net/projects/orwelldevcpp/

# Example 1 : Functions

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">void</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">myFunction</span><span class="hljs-params">()</span> 
</span>{
     <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"i am a fuction"</span>;
}

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"hello world \n"</span>;
    myFunction(); 
}</pre>


# String Functions
# Example 2 : strlen()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"length the of string = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strlen</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">"welcome"</span>);
}
</pre>

# Example 3 : strlen()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> </span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> arr[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"welcome"</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"length the of string = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strlen</span>(arr);
}
</pre>

# Example 4 : strcpy()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> str1[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"Hello world"</span>;
  <span class="hljs-keyword" style="font-weight: 700;">char</span> str2[<span class="hljs-number" style="color: rgb(136, 0, 0);">20</span>];   
  
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strcpy</span>(str2, str1);
  
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"str1 : "</span> &lt;&lt;str1;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"str2 : "</span> &lt;&lt;str2;
}</pre>

# Example 5 :strcpy()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> arr[<span class="hljs-number" style="color: rgb(136, 0, 0);">20</span>];   
  
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strcpy</span>(arr, <span class="hljs-string" style="color: rgb(136, 0, 0);">"hello world"</span>);
  
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"arr : "</span> &lt;&lt;arr;
}</pre>

# Example 7 : strcat()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">char</span> str1[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"Hello "</span>;

    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strcat</span>(str1, <span class="hljs-string" style="color: rgb(136, 0, 0);">"World"</span>);
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"str1 = "</span> &lt;&lt;str1 ;

}</pre>

# Example 7 : strcat()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">char</span> str1[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"Hello "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">char</span> str2[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">" world!"</span>;

    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strcat</span>(str1, str2);
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"str1 = "</span> &lt;&lt;str1 ;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"str2 = "</span> &lt;&lt;str2 ;

}</pre>

# Example 8 : strcmp()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">char</span> str1[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"Hello "</span>;

    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">strcat</span>(str1, <span class="hljs-string" style="color: rgb(136, 0, 0);">"World"</span>);
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"str1 = "</span> &lt;&lt;str1 ;

}</pre>

# Example 9 : strcmpi()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{ 
  <span class="hljs-keyword" style="font-weight: 700;">int</span> result;
  <span class="hljs-keyword" style="font-weight: 700;">char</span> str1[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"hello"</span>;
  <span class="hljs-keyword" style="font-weight: 700;">char</span> str2[] = <span class="hljs-string" style="color: rgb(136, 0, 0);">"Hello"</span>;

  result = strcmpi(str1, str2);
  
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; result;
}</pre>


# Mathematical Functions
# Example 10 : abs()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstdlib&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">abs</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">-5</span>);
}</pre>

# Example 11 : sqrt()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cmath&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"Square root of 25 = "</span>;
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">sqrt</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">25</span>);
}</pre>

# Example 12 : pow()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cmath&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> </span>{
  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">pow</span>(<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">3</span>);
}
</pre>

# Example 13 : sin()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cmath&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">int</span> x = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"sin(x) = "</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">sin</span>(x);
}

</pre>

# Example 14 : cos()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cmath&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">int</span> x = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-string" style="color: rgb(136, 0, 0);">"cos(x) = "</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cos</span>(x);
}

</pre>

# Example 15 : isupper()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">isupper</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'H'</span>);
}</pre>

# Example 16 : islower()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">islower</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'H'</span>);
}</pre>

# Example 17 : isalpha()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">isalpha</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'3'</span>);
}</pre>

# Example 18 : isdigit()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">isdigit</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'3'</span>);
}</pre>

# Example 19 : isalnum()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cstring&gt;</span></span>

<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
   <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; <span class="hljs-built_in" style="color: rgb(57, 115, 0);">isalnum</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'@'</span>);
}</pre>

# Example 20 : toupper()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> ch = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">toupper</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'a'</span>);

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; ch;
}
</pre>

# Example 21 : islower()

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;cctype&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span> 
</span>{
  <span class="hljs-keyword" style="font-weight: 700;">char</span> ch = <span class="hljs-built_in" style="color: rgb(57, 115, 0);">tolower</span>(<span class="hljs-string" style="color: rgb(136, 0, 0);">'H'</span>);

  <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span> &lt;&lt; ch;
}
</pre>

# Conversion functions
# Example 22 : 
