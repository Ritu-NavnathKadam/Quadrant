# Quadrant
#include<stdio.h>
void main()
{
int x,y;
printf("Enter 'x' coordinate:");
scanf("%d",&x);

printf("Enter 'y' coordinate:");
scanf("%d",&y);

if(x>0 && y>0)
printf("coordinate lies in first quadrant");
 else if(x<0 && y>0)
printf("coordinate lies in second quadrant");
else if(x<0 && y<0)
printf("coordinate lies in third quadrant");
else
printf("coordinate lies in forth quadrant");
}








