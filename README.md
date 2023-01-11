#include <stdio.h>

int main()
{
    /*WAP to print array in reverse order*/
   int arr[5];
   int i;
   printf("Enter the values:");
   for(i=0;i<5;i++)
   {
       scanf("%d",&arr[i]);}
       printf("array in reverse order:\n");
   
     for(i=4;i>=0;i--)
     {
         printf("%d\n",arr[i]);
     }
       

    return 0;
}
