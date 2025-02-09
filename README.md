#include<stdio.h>
int min(int *a, int *b){
return (*a<*b) ? *a:*b;
}
int main()
{
    int num1,num2,mini;
    printf("Enter 2 nos:\n ");
    scanf("%d %d",&num1,&num2);
    mini=min(&num1, &num2);
    printf("The minimum value is %d",mini);
    return 0;
}
