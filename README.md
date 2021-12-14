# sum-and-digit-of-number-using-function

#include<stdio.h>

int sum(int n)
{
   int add = 0;
   for(int i=1; i<=n; i++)
   {
     add += i;
   }
   return add;
}

int main()
{
   int range, result;
   printf("you want to find sum: ");
   scanf("%d", &range);
   result = sum(range);
}
