#include<stdio.h>
//To use realloc in our program
#include<stdlib.h>
int main()
{
int *ptr,i;
int n;
printf("enter no of elements:");
scanf("%d",&n);
//allocating memory for only 1 integer
ptr = malloc(sizeof(int));
//realloc memory size to store 3 integers
ptr = realloc(ptr, 3 * sizeof(int));
printf(" enter elements in array:");
for(i=0;i<n;i++){
scanf("%d",&ptr[i]);
}
//printing values
for(i = 0; i < n; i++)
printf("elements of array using realloc():%d\n",ptr[i]);
return 0;
}
