# C-7
sum of n natural numbers
#include<stdio.h>
int main()
{
	int n, sum=0;
	printf("enter a number:\n");
	scanf("%d",&n);
	for(int i=0;i<=n;i++)
	{
		sum=sum+i;
    }
    printf("sum %d",sum);
    return 0;
}
