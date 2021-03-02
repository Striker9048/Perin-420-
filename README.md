#include<stdio.h>

int main()
{
int a,b,r,c,p,d,f;
int factorial(int);
printf("\n enter the number in form P(a,r) = ");
scanf("%d %d",&a, &r);
b =factorial(a);
c =factorial(a-r);
d =factorial(r);
printf("\n b =%d",b);
printf("\n c =%d",c);
p=b/c;
f=p/d;
printf("\n Permutation 😂😂😆 of given number  =%d",p);
printf("\n Combination of given number  =%d",f);
return 0;
}
int factorial(int x)
{int y = 1;
for(;x>0;x--){
y =y*x;
}
return y;
}
