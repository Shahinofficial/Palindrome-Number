#include <stdio.h>

#include <stdlib.h>

int main()
{
    int num,rem, reverse = 0, temp;
    
    printf("Enter the value of n: ");
    
    scanf("%d",&num);


    temp = num;

    while (num !=0)
    {
        rem = num%10;
        
        reverse = reverse * 10 + rem;
        
        num = num/10;
        
    }
    
    if (temp == reverse)
    
    {
    
        printf("Yes");
        
    }
    
    else
    
    {
    
        printf("No");
        
    }

    return 0;
}
