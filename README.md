# cs39003-assignment-1--annotating-assembly-solved
**TO GET THIS SOLUTION VISIT:** [CS39003 Assignment 1- Annotating Assembly Solved](https://www.ankitcodinghub.com/product/cs39003-assignment-1-annotating-assembly-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92872&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39003 Assignment 1- Annotating Assembly&nbsp;Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1. Translate the following C program using GCC/Linux to the assembly language program of x86-64 (Intel 64-bit processor) without optimization.

<pre>                         cc -Wall -S ass1.c
</pre>
C Program: ass1.c

<pre>     /*
     * ass1.c Generate assembly code of x86-64 and comment
     */
</pre>
<pre>     #include &lt;stdio.h&gt;
     #define MAXSIZE 100
</pre>
<pre>     void inst_sort(int num[],int n);
     int bsearch(int num[],int n,int item);
</pre>
int main() {

<pre>         int n, a[MAXSIZE], item, i, loc;
</pre>
<pre>         printf("Enter how many elements you want:\n");
         scanf("%d", &amp;n);
</pre>
<pre>         printf("Enter the %d elements:\n", n);
         for(i = 0; i &lt; n; i++) scanf("%d", &amp;a[i]);
</pre>
<pre>         inst_sort(a,n);
</pre>
<pre>         printf("\nEnter the item to search\n");
         scanf("%d", &amp;item);
         loc=bsearch(a,n,item);
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<pre>if (item == a[loc]) {
          printf("\n%d found in position: %d\n", item, loc + 1);
</pre>
<pre>      } else {
          printf("\nItem is not present in the list.\n");
</pre>
}

return 0; }

<pre>  void inst_sort(int num[],int n)
  {
</pre>
int i,j,k;

<pre>      for(j=1;j&lt;n;j++) {
          k=num[j];
</pre>
<pre>          for(i=j-1;i&gt;=0 &amp;&amp; k&lt;num[i];i--) num[i+1]=num[i];
              num[i+1]=k;
</pre>
} }

<pre>  int bsearch(int a[],int n,int item)
  {
</pre>
<pre>      int mid, top, bottom;
</pre>
<pre>      bottom = 1;
      top = n;
      do {
</pre>
<pre>          mid = (bottom + top) / 2;
          if (item &lt; a[mid])
</pre>
<pre>              top = mid - 1;
          else if (item &gt; a[mid])
</pre>
<pre>              bottom = mid + 1;
      } while (item != a[mid] &amp;&amp; bottom &lt;= top);
      return mid;
</pre>
}

2. Rename the generated assembly file as ass1 roll.s (where roll is your roll number). Add comments for each of the assembly language instruction. Your comment should explain the functionality of the instruction and the connection to the original C program. Please make sure that your commented file can be compiled to generate executable file. Upload your file (ass1 roll.s) in Moodle server.

Note: Comments without connection to C program will get partial marks.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
