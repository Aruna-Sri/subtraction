# subtraction
#include <stdio.h>

void main()
{


int number1,number2,number3;

printf("Enter the first number:");
if(scanf("%d",&number1)==1)
{
        printf("Enter the second number:");
        if(scanf("%d",&number2)==1)
        {
                number3=number1-number2;
                printf("The subtraction is :%d",number3);
        }
        else
        {
                printf("Error,enter correct value");
        }
}
else
{
        printf("Error,enter correct value");
}
}
