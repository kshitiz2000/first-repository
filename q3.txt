#include<stdio.h>
void circum(float);
void area(float);
int main() {
float r;
printf("enter the radius of circle\n");
scanf("%f",&r);
circum(r);
area(r);
return 0;
}
void circum(float r){
float c;
c= 2*3.14*r;
printf("Circumference= %f\n",c);}
void area(float r){

float d = 3.14*r*r;
printf("Area = %f",d);
}