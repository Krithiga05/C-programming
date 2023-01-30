#include<stdio.h>
int leapyear(int year) {
	int leap;
    if(year%400==0)
	    leap=1;
	else if(year%100==0)
	    leap=0;
	else if(year%4==0)
	    leap=1;
	else{
		leap=0;
	}
	return leap;
}
main()
{
	int leap,year,i;
	printf("Enter a year : ");
	scanf("%d",&year);
	leap=leapyear(year);
	if(leap==1)
	    {printf("%d is a leap year \n",year);
	    printf("%d is the next leap year",year+4);}
	else
	    {printf("%d is not a leap year \n",year);}
	    for(i=1;i<=4;i++)
	        {year=year-1;
	        leap=leapyear(year);
	        if(leap==1)
	            printf("%d is the previous leap year",year);
			}
}
