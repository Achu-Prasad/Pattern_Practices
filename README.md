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
<code>
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
</code>
