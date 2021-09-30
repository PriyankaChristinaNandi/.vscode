#include<stdio.h>

int main()
{
    int a, b, c;
    char ch;
    //a=5;   
    //b=6;

    ch = 'A';

    ch = ch+1;
    printf("the character is = %c", ch);

    printf("\n Enter the value of a : ");
    scanf("%d",&a);

    printf("\n Enter the value of b : ");
    scanf("%d",&b);

    c=a+b;
    printf("The sum of a and b = %d \n", c);
}
