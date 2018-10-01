#include<stdio.h>
int main()
{ 
    int a,b; //two integer type variables whose difference is to be performed 
    int diff=0; //the variable for storing the difference of the two integers 
    printf("Enter the first number:"); 
    scanf("%d",&a); 
    printf("Enter the second number:");
    scanf("%d",&b);
    diff=a-b; //sum of the two numbers performed 
    printf("The sum of the two numbers is: %d",diff); //difference gets printed 
    return 0; 
}
