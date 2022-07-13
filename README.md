# table.c
//for printing table
#include<stdio.h>
#include<conio.h>
main()
{
int num,div;
printf("enter a number for whom table will be there");
scanf("%d",&num);
printf("till how many number you want");
scanf("%d",&div);
for(int x=0; x<=div;x++)
   printf("%d * %d = %d \n",num,x,x * num); }

