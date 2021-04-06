# C-Arrays
#include<stdio.h>

int main()
{//funtions
    int i, sum, n, mark[10];
    
 //getting the size
    printf("INPUT SIZE: ");
    scanf("%d", &n);
    
 //identifying the size
    if(n>10 || n<5)
    {
    printf("Size exceeded the the Maximum/Minimum");
    }
    else if(n<=10)
    {
 //arrays
    for(i=0; i<n; i++)
    {
        printf("%d array: ",i+1);
        scanf("%d",&mark[i]);
    }
 //adding the all element
      for(i=0; i<n; i++)
    {
        sum = sum+mark[i];    
    }   
        printf("sum of all arrays: %d", sum);
    }
    return 0;
    
}
