# Program-that-displays-all-the-numbers-from-X-and-Y-that-are-divisible-by-a-and-b
# include<stdio.h>
void main()
{
int X,Y,a,b,i;
printf(" enter the value of X,Y,a,b : ");
scanf("%d%d%d%d",&X,&Y,&a,&b);
for(i=X;i<=Y;i++)
{
printf("\n numbers from X to Y that divisible by a and b are ");
if(i%a==0&&i%b==0)
printf("\n %d",i);
}
}
