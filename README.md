# prime-number-or-not
program
#include<stdio.h>
int main()
{
int a,count=0,i;
printf("Enter a number:");
scanf("%d",&a);
for(i=1;i<=a;i++)
{
if(a%i==0)
{
count=count+1;
}
}
if(count==2)
printf("%d is a prime number");
else
printf("%d" is not a prime number);
return 0;
}
