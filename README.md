# c-programming-p8
program 8
/* A C program to read two numbers and perform arithmetic operations using switch case*/
#include<stdio.h>
int main()
{
int a,b;
int op;
printf("1.Addition\n 2.Substraction\n 3.Multiplication\n 4.Divison\n");
printf("Enter the values of a&b:");
scanf("%d%d",&a,&b);
printf("Enter your choice:");
scanf("%d",&op);
switch(op)
{
case 1:
printf("Sum of%d and %d is:%d\n",a,b,a+b);
break;
case 2 :
printf("Difference of %d and %d is: %d\n",a,b,a-b);
break;
case 3:
printf("Multiplication of %d and %d is: %d\n",a,b,a*b);
break;
case 4:
printf("Division of %d and is %d:\n",a,b,a/b);
break;
default:
printf("Enter your correct choice.");
break;
}
return 0;
}
output:
1.Addition
 2.Substraction
 3.Multiplication
 4.Divison
Enter the values of a&b:33
20
Enter your choice:3
Multiplication of 33 and 20 is: 660
