//# c-9
//sum of whole numbers
#include <stdio.h>
int main()
{
    int n, sum=0;
    printf("enter the number:");
    scanf("%d",&n);
    for(int i=0;i<=n;i++)
    {
        sum+=i;
    }
    printf("sum=%d",sum);
    return 0;
}
