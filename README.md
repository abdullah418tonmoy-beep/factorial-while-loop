#include<stdio.h>
int main()
{
    int i=1,num,fact=1;
    printf("Enter a positive num to define factorial: ");
    scanf("%d",&num);

   while(i<=num)
    {
        fact=fact*i;
        i++;
    }
   printf("your factorial number is: %d",fact);

    return 0;
}
