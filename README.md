# swapping
//Swapping value of two variables without using third variable
#include<stdio.h>    
 int main()    
{    
int a=10, b=20;      
printf("Before swap a=%d b=%d",a,b);       
a=a*b;
b=a/b;  
a=a/b;   
printf("swap a=%d b=%d",a,b);
}
