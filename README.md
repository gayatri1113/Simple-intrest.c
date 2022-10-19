//# Simple-intrest.c//
#include<stdio.h>
int main()
{
   int p,n;
   float r,si;
   printf("enter principle");
   scanf("%d",&p);
   printf("enter number of year");
   scanf("%d",&n);
   printf("enter rate of interest");
   scanf("%f",&r);
   si=(p*n*r)/100;
   printf("simple interest=%f",si);
   return 0;
}
