memory fixed partitioning technique program:
-------------------------------------------------------------------------
-----
#include<stdio.h>
int main()
{
int tm,om,n,i,block_size,internal_frag;
printf("Enter total memory size,memory of OS and no of processes:\n");
scanf("%d%d%d",&tm,&om,&n);
int process[n];
tm = tm - om;
block_size = tm / n;
for (i = 0; i < n; ++i)
{
printf("Enter process %d size :\n",i+1);
scanf("%d",&process[i]);
if(process[i] <= block_size){
internal_frag = internal_frag + block_size - process[i];
printf("Allocated memory to process :%d\n",i+1);
}else{
printf("Process %d is blocked\n",i+1);
}
}
printf("Fragmentation is %d.\n",internal_frag);
return 0;
}
