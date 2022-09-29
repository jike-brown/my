#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int Add(int a, int b)
{
    int c = a + b;
    return c;
}

int Mul(int a, int b)
{
    int d = a * b;
    return d;
}

int main()
{
    int a, b;
    printf("please enter a b:");
    scanf("%d%d/n",&a,&b);
    //c = a + b;
    printf("%d\n",Add(a,b));
    //d = a * b;
    printf("%d\n",Mul(a,b));
    return 0;
}

