# Subtraction-of-two-numbers-
Subtracting small value from given large value using if and else conditions 
hello c
#include<stdio.h>
void main()
{
 int a,b,c;
 printf ("enter a value\n");
 scanf("%d",&a);
 printf("enter b value\n");
 scanf("%d",&b);
  if(a>b)
  {
   (c=a-b);
   printf("on subtracting small value from big value we get %d\n",c);
  }
  else
  {
   (c=b-a);
   printf ("on subtracting the small value from big value we get %d \n",c);
  }
 
}
