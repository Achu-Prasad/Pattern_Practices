# Pattern_Practices

This Repository Containes all the patterns i practiced

<pre>
Pattern1

*    
**   
***  
**** 
*****
**** 
***  
**   
*    
</pre>

<pre>

Answer: 

#include <stdio.h>

int main() {

    int i,j;

    for (i=1;i<=9;i++){
        for (j=1;j<=5;j++){
            if(j-i<=0 && i+j<=10){
                printf("*");
            }else{
                printf(" ");
            }
        }printf("\n");
    }
    return 0;
}
</pre>

<pre>
Pattern 2

      A       
    A B A     
  A B C B A   
A B C D C B A 

</pre>

<pre>

Answer:

#include <stdio.h>


    int main() {
    int i,j;
    char k;
    for(i=1;i<=4;i++){
        k='A';
        for(j=1;j<=7;j++){
            if(j>=5-i&&j<=3+i){
                 printf("%c ",k);
                 j>=4?k-- : k++ ;
            }
            else
            printf("  ");

            }printf("\n");
        }
    }

</pre>
<pre>
Pattern 3

* * * * * * * * 
  *           * 
    *         * 
      *       * 
        *     * 
          *   * 
            * * 
              * 
</pre>
<pre>

Answer:

#include <stdio.h>

int main() {
    int i,j;
    for(i=1;i<=8;i++){
        for(j=1;j<=8;j++){
            
            if(i==1||j==8)
            printf("* ");
            
            else if(i==j)
            printf("* ");
            
            else
            printf("  ");
            
        }printf("\n");
    }
    return 0;
}

</pre>

<pre>
Pattern 4

* * * * * * * * 
*           *   
*         *     
*       *       
*     *         
*   *           
* *             
*    
</pre>
<pre>

Answer:

int main() {
    int i,j;
    for(i=1;i<=8;i++){
        for(j=1;j<=8;j++){
            
            if(i==1||j==1)
            printf("* ");
            
            else if(j==8-(i-1))
            printf("* ");
            
            else
            printf("  ");
            
        }printf("\n");
    }
    return 0;
}

</pre>
<pre>
Pattern 5

* * * * * * * 
* *       * * 
*   *   *   * 
*     *     * 
*   *   *   * 
* *       * * 
* * * * * * * 

</pre>
<pre>
Answer:

#include <stdio.h>

int main() {
    int i,j;
    for(i=1;i<=7;i++){
        for(j=1;j<=7;j++){
            
            if(i==1||j==7 || i==7 || j==1)
            printf("* ");
            else if(i+j==8 || i==j)
            printf("* ");
            else
            printf("  ");
        }printf("\n");
    }
    return 0;
}
</pre>
<!-- <pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre> -->
