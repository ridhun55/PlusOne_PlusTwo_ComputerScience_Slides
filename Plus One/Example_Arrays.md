# C++ Examples Documentation
# RIDHUN DEV

C++ Examples Codes Run In Dav C++ IDE </br>
Download Dev C++ Software : https://sourceforge.net/projects/orwelldevcpp/

# Example 1 : Enter the name of 10 students

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);">
    <span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
    <span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;string&gt;</span></span>
    <span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;

    <span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
    </span>{
    
		<span class="hljs-keyword" style="font-weight: 700;">char</span> name[<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>][<span class="hljs-number" style="color: rgb(136, 0, 0);">25</span>];

	    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter the Names:"</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
	
	    <span class="hljs-keyword" style="font-weight: 700;">for</span> (<span class="hljs-keyword" style="font-weight: 700;">int</span> i = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;=<span class="hljs-number" style="color: rgb(136, 0, 0);">9</span>; i++)
	    {
	     	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Name"</span>&lt;&lt;i+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">": "</span>;
	     	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;name[i]; 
	    }
	
	    <span class="hljs-keyword" style="font-weight: 700;">for</span> (<span class="hljs-keyword" style="font-weight: 700;">int</span> j=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;j&lt;=<span class="hljs-number" style="color: rgb(136, 0, 0);">9</span>;j++)
	    {
	     	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;name[j]&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>; 
	    }
	
	    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;

    }

</pre>
 
# Example 1 : Traversal 

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);">    <span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span> <span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span>  </span>
    <span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;  
    <span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>  
    </span>{  
     <span class="hljs-keyword" style="font-weight: 700;">int</span> item[<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>]={<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">20</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>, <span class="hljs-number" style="color: rgb(136, 0, 0);">30</span>};    
           <span class="hljs-keyword" style="font-weight: 700;">for</span> (<span class="hljs-keyword" style="font-weight: 700;">int</span> i: item)     
            {    
                <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;i&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;    
            }    
    }  </pre>

# Example 2 : Selection Sorting

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> array_size; 
	<span class="hljs-keyword" style="font-weight: 700;">int</span> array_element[<span class="hljs-number" style="color: rgb(136, 0, 0);">50</span>];
	<span class="hljs-keyword" style="font-weight: 700;">int</span> i, j, temp, check, index;
	<span class="hljs-keyword" style="font-weight: 700;">int</span> smallest_array_element;
    
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter the Size of Array: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;array_size;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter "</span>&lt;&lt;array_size&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" Array Elements: "</span>;
    
	<span class="hljs-comment" style="color: rgb(136, 136, 136);">//==== To collect Array elements =================================</span>
	
	<span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt; array_size; i++)
	{
		<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;array_element[i];
	}
        
    
	<span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;(array_size<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>); i++)
    {
        check=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
        smallest_array_element = array_element[i];
        
		<span class="hljs-keyword" style="font-weight: 700;">for</span>(j=(i+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>); j&lt;array_size; j++)
        {
            <span class="hljs-keyword" style="font-weight: 700;">if</span>(smallest_array_element&gt;array_element[j])
            {
                smallest_array_element = array_element[j];
                check++;
                index = j;
            }
        }
        
        <span class="hljs-keyword" style="font-weight: 700;">if</span>(check!=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>)
        {
            temp = array_element[i];
            array_element[i] = smallest_array_element;
            array_element[index] = temp;
        }
    }
    

	<span class="hljs-comment" style="color: rgb(136, 136, 136);">// ===== To Print sorted Array</span>
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nSorted Array is:\n"</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;array_size; i++)
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;array_element[i]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>

# Example 3 : Bubble Sorting

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> array_size;
	<span class="hljs-keyword" style="font-weight: 700;">int</span> array_element[<span class="hljs-number" style="color: rgb(136, 0, 0);">50</span>], i, j, temp;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter the Size (max. 50): "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;array_size;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter "</span>&lt;&lt;array_size&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" Numbers: "</span>;
	<span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;array_size; i++)
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;array_element[i];
    

	<span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;(array_size<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>); i++)
    {
        <span class="hljs-keyword" style="font-weight: 700;">for</span>(j=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; j&lt;(array_size-i<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>); j++)
        {
            <span class="hljs-keyword" style="font-weight: 700;">if</span>(array_element[j]&gt;array_element[j+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>])
            {
                temp = array_element[j];
                array_element[j] = array_element[j+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>];
                array_element[j+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>] = temp;
            }
        }
    }
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nArray Sorted Successfully!\n"</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;array_size; i++)
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;array_element[i]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>


# Example 4 : Linear Search

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arr[<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>];
	<span class="hljs-keyword" style="font-weight: 700;">int</span> i, num, index;
    
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter 5 Numbers: "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arr[i];
		}
		
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter a Number to Search: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;num;
    
	<span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>; i++)
    {
        <span class="hljs-keyword" style="font-weight: 700;">if</span>(arr[i]==num)
        {
            index = i;
            <span class="hljs-keyword" style="font-weight: 700;">break</span>;
        }
    }
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nFound at Index No."</span>&lt;&lt;index;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>


# Example 5 : Binary search


<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> i, arr[<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>];
	<span class="hljs-keyword" style="font-weight: 700;">int</span> num, first_index, last_index, middle;
	
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter 10 Elements (in ascending order): "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>; i++)
    {
    	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arr[i];	
	}
        
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter Element to be Search: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;num;
    
    first_index = <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
    last_index = <span class="hljs-number" style="color: rgb(136, 0, 0);">9</span>;
    
	middle = (first_index + last_index) / <span class="hljs-number" style="color: rgb(136, 0, 0);">2</span>;
	
    <span class="hljs-keyword" style="font-weight: 700;">while</span>(first_index &lt;= last_index)
    {
        <span class="hljs-keyword" style="font-weight: 700;">if</span>(arr[middle]&lt;num)
        {
        	first_index = middle + <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>;
		}      
        <span class="hljs-keyword" style="font-weight: 700;">else</span> <span class="hljs-keyword" style="font-weight: 700;">if</span>(arr[middle]==num)
        {
            <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nThe number, "</span>&lt;&lt;num&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" found at Position "</span>&lt;&lt;middle + <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>;
            <span class="hljs-keyword" style="font-weight: 700;">break</span>;
        }
        <span class="hljs-keyword" style="font-weight: 700;">else</span>
		{
			last_index = middle - <span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>;
		}
        middle = (first_index + last_index) / <span class="hljs-number" style="color: rgb(136, 0, 0);">2</span>;
    }
    
    <span class="hljs-keyword" style="font-weight: 700;">if</span>(first_index &gt; last_index)
    {
    	 <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nThe number, "</span>&lt;&lt;num&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" is not found in given Array"</span>;
	}
       
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>

# Example 5 : Insertion

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arr[<span class="hljs-number" style="color: rgb(136, 0, 0);">6</span>];
    <span class="hljs-keyword" style="font-weight: 700;">int</span> i, data;
	
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter 5 Array Elements: "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>; i++)
        {
            <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arr[i];
	}
		
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter Element to Insert: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;data;
    
    arr[i] = data;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nThe New Array is:\n"</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;<span class="hljs-number" style="color: rgb(136, 0, 0);">6</span>; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;arr[i]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"  "</span>;
	}
		
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>

<h2>Insert a specific position</h2>

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arr[<span class="hljs-number" style="color: rgb(136, 0, 0);">50</span>];
    <span class="hljs-keyword" style="font-weight: 700;">int</span> i, data, position, size;
	
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter the Size for Array: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;size;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter "</span>&lt;&lt;size&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" Array Elements: "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;size; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arr[i];
	}
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter Element to Insert: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;data;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"At What Position ? "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;position;
    
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=size; i&gt;=position; i--)
        {
        	arr[i] = arr[i<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>];
	}
		
    arr[i] = data;
    size++;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nThe New Array is:\n"</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;size; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;arr[i]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"  "</span>;
	}
		
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>


# Example 6 : Deletion

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arr[<span class="hljs-number" style="color: rgb(136, 0, 0);">10</span>];
    <span class="hljs-keyword" style="font-weight: 700;">int</span> size=<span class="hljs-number" style="color: rgb(136, 0, 0);">5</span>;
    <span class="hljs-keyword" style="font-weight: 700;">int</span> found=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
    <span class="hljs-keyword" style="font-weight: 700;">int</span> i, data, j;
	
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter 5 Array Elements: "</span>;
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;size; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arr[i];
	}
		
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter Element to Delete: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;data;
    
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;size; i++)
    {
        <span class="hljs-keyword" style="font-weight: 700;">if</span>(arr[i]==data)
        {
            <span class="hljs-keyword" style="font-weight: 700;">for</span>(j=i; j&lt;(size<span class="hljs-number" style="color: rgb(136, 0, 0);">-1</span>); j++)
                {
                	arr[j] = arr[j+<span class="hljs-number" style="color: rgb(136, 0, 0);">1</span>];
		}
            found++;
            i--;
            size--;
        }
    }
    <span class="hljs-keyword" style="font-weight: 700;">if</span>(found==<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nElement doesn't found in the Array!"</span>;
	}
    <span class="hljs-keyword" style="font-weight: 700;">else</span>
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nElement Deleted Successfully!"</span>;
	}
	
	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\n"</span>;	
	<span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;size; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;arr[i];
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" "</span>;
	}
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>

# Example 7 : Merging

<pre class="hljs" style="display: block; overflow-x: auto; padding: 0.5em; background: rgb(240, 240, 240) none repeat scroll 0% 0%; color: rgb(68, 68, 68);"><span class="hljs-meta" style="color: rgb(31, 113, 153);">#<span class="hljs-meta-keyword" style="font-weight: 700;">include</span><span class="hljs-meta-string" style="color: rgb(77, 153, 191);">&lt;iostream&gt;</span></span>
<span class="hljs-keyword" style="font-weight: 700;">using</span> <span class="hljs-keyword" style="font-weight: 700;">namespace</span> <span class="hljs-built_in" style="color: rgb(57, 115, 0);">std</span>;
<span class="hljs-function"><span class="hljs-keyword" style="font-weight: 700;">int</span> <span class="hljs-title" style="color: rgb(136, 0, 0); font-weight: 700;">main</span><span class="hljs-params">()</span>
</span>{
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arrOne[<span class="hljs-number" style="color: rgb(136, 0, 0);">50</span>];
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arrTwo[<span class="hljs-number" style="color: rgb(136, 0, 0);">50</span>];
    <span class="hljs-keyword" style="font-weight: 700;">int</span> arrMerge[<span class="hljs-number" style="color: rgb(136, 0, 0);">100</span>];
	
    <span class="hljs-keyword" style="font-weight: 700;">int</span> sizeOne, sizeTwo, i, k;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter the Size for First Array: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;sizeOne;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter "</span>&lt;&lt;sizeOne&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" Elements for First Array: "</span>;
    
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;sizeOne; i++)
    {
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arrOne[i];
        arrMerge[i] = arrOne[i];
    }
    k = i;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nEnter the Size for Second Array: "</span>;
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;sizeTwo;
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"Enter "</span>&lt;&lt;sizeTwo&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" Elements for Second Array: "</span>;
    
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;sizeTwo; i++)
    {
        <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cin</span>&gt;&gt;arrTwo[i];
        arrMerge[k] = arrTwo[i];
        k++;
    }
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">"\nThe New Array (Merged Array):\n"</span>;
    
    <span class="hljs-keyword" style="font-weight: 700;">for</span>(i=<span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>; i&lt;k; i++)
        {
        	<span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;arrMerge[i]&lt;&lt;<span class="hljs-string" style="color: rgb(136, 0, 0);">" "</span>;
	}
    
    <span class="hljs-built_in" style="color: rgb(57, 115, 0);">cout</span>&lt;&lt;<span class="hljs-built_in" style="color: rgb(57, 115, 0);">endl</span>;
    <span class="hljs-keyword" style="font-weight: 700;">return</span> <span class="hljs-number" style="color: rgb(136, 0, 0);">0</span>;
}</pre>
