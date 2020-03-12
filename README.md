# reverse-of-number-in-c
Through this program you can calculate the reverse of entered digit.
#include <stdio.h>

int main() {
    int n,sum=0,rem;
    
    printf("enter the no. to be reversed:\n");
    scanf("%d", &n);
    
    while(n!=0){
        rem = n%10;
        sum = sum*10+rem;
        n = n/10;
        
     }
     printf("reverse of the num=%d",sum);
     
     return 0;
        
}
