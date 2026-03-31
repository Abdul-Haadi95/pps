#include<stdio.h>
#include<conio.h>
void main()
{
       int n,i,j,count;
       clrscr();
       printf(“\n prime number ofseries \n”);
       printf(“\n Enter any number \n”);
       scanf(“%d”,&n);
       printf(“\n The prime number is between 1 to %d\n”,n);
       for(i=1;i<=n;i++)
       {
             count=0;
             for(j=1;j<=i;j++)
                    if(i%j==0)
                    {
                      count++;
                    }
                 if(count==2)
                 {
                     
                      printf(“%d\t”,i);
                }
             }
       getch();
}
Output:
Prime number ofseries
Enter any number
30
The prime number is between 1 to 30
2 3 5 7 11 13 17 19 23 29
