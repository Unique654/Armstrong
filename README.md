# reverse

#include <stdio.h>
//reverse
int main()
{int r;
int n=123;
do{
r= n%10;
n=n/10;

if (r%2!=0){
    
    printf("%d \n ",r);
    
}}
while(n>0);
return 0 ;
}
