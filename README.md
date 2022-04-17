# test4_17.c
//Little practice.











































































#include <stdio.h>
int NUM(int num)
{
    if(num==1)
    {
         return 1;
    }
    else
    {
         return 0;
    }
}
int main()
{
    int num=0;
    printf("Please input num:>");
    scanf("%d",&num);
    int h=NUM(num);
    if(h)
    {
         printf("Hello world!"); 
         
    }
    else
    {
         printf("See you next day!");
    }
    return 0;
}
