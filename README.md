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
<pre>
Pattern 6

*         
* *       
*   *     
*     *   
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
    for(i=1;i<=9;i++){
        for(j=1;j<=5;j++){
            if(j==1||i==j||i+j==10)
            printf("* ");
            else
            printf("  ");
            
        }printf("\n");
    }
    return 0;
}

</pre>
<pre>
Pattern 7

13579
35791
57913
79135
91357
</pre>
<pre>
Answer:

#include <stdio.h>

int main() {
    int i,j,k,l;
    
    for(i=1;i<=5;i++){
        k=(2*i)-1;
        l=1;
        for(j=1;j<=5;j++){
            if(i+j<=6){
                printf("%d",k);
                k=k+2;
               
                }
                else if(i+j>6){
                printf("%d",l);
                l=l+2;
                }
                
                
            }printf("\n");
        }
    return 0;
}

</pre>
<pre>
Pattern 8

1 3 5 7 9 
3 5 7 9 1 
5 7 9 3 1 
7 9 5 3 1 
9 7 5 3 1 
</pre>

<pre>
Answer:

int main() {
    int i, j,k=1,l;
    for(i=1;i<=5;i++){
        k=(2*i)-1;
        l=2*(i-1)-1;
        for(j=1;j<=5;j++){
            if(i+j<=6){
                printf("%d ",k);
                k=k+2;
            }
                else if(i+j>6){
                printf("%d ",l);
                l=l-2;}
                
            }printf("\n");
        }
}

</pre>
<pre>
Pattern 9

1 2 3 4 5 
2 3 4 5 1 
3 4 5 2 1 
4 5 3 2 1 
5 4 3 2 1 

</pre>
<pre>
Answer

#include <stdio.h>

int main() {
    int i ,j,k,l;
    
    for (i=1;i<=5;i++){
        k=i;
        l=i-1;
        for (j=1;j<=5;j++){
            if(i+j<=6){
                printf("%d ",k++);
            }else{
                printf("%d ",l--);
            }
        }printf("\n");
    }
    return 0;
}</pre>
<pre>
Pattern 10

1 2 3 4 5 
 2 4 6 8 
  3 6 9 
   4 8 
    5 
</pre>

<pre>
Answer:

#include <stdio.h>

int main() {
    int i,j,k;
    for(i=1;i<=5;i++){
        k=i;
        for(j=1;j<=5;j++){
            if(j < i){
                printf(" ");
            }else{
                printf("%d ",k);
                k=k+i;
            }
        }printf("\n");
    }

    return 0;
}

</pre>

<pre></pre>
<pre></pre>
<pre></pre>
<pre></pre>
