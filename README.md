# Inferance-54_first
This is my first git repository.
<br> author- Adnan Hossain
//Write a C program to enter length in centimeter and convert it into meter and kilometer.
#include<stdio.h>
int main(){
float a;
printf("\nEnter the length in centimeter :");
scanf("%f",&a);
printf("\nLength in Centimeter:%f",a);

float m;
m=a/100;
printf("\nLength in meter:%f",m);

float km;
km=a/100000;
printf("\nLength in Kilometer:%f",km);

return 0;
}


