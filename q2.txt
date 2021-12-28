#include<stdio.h>
void vol(float a, float b,float c);
int main() {
float a;
float b;
float c;
printf("enter the dimensions of cuboid\n");
scanf("%f %f %f", &a,&b,&c);
vol(a,b,c);
return 0;
}

void vol(float a, float b,float c){
float d;
d= a*b*c;
printf("volume of cuboid is %f",d);
}

