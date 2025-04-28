# payable-amount
a program that calculates the payable amounts of dicounts provided
#include<stdio.h>
int main()
{
   float bill amount,discount,discounted amount;
   printf("enter bill amount/n");
   scanf("%f",&bill amount);
   if (amount>5000)
   {
       printf("15%");
   }
    else
    {
        printf("10%");
    }
    discounted amount=bill amount-(bill amount*discount);
    printf("discounted amount/n");
    return 0;

}
