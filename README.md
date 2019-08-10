#include<stdio.h>
int main()
{
int X,P,NEW_X=0;
scanf("%d%d",&X,&P);
while(P!=0)
{
NEW_X=(P/100)*X;
P=NEW_X;
}
printf("%d",P);
return 0;
}
