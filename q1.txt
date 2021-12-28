#include <stdio.h>
#include <stdlib.h>
void swap(char,char);

int main()
{ char a,b;
    printf("Enter two characters\n");
    scanf("%c %c",&a,&b);
    printf("Before swap : a = %c b = %c\n ", a,b);
    swap(a,b);

    return 0;
}
void swap(char a,char b){

a= a+b;
b=a-b;
a=a-b;
printf("After swap : a = %c  b = %c\n",a,b);


}
