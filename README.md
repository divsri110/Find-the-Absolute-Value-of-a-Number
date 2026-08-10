# Find-the-Absolute-Value-of-a-Number
This program takes an integer as input from the user. It checks whether the number is negative, and if so, converts it to positive by negating it. The result — the absolute value — is then printed.

#include <stdio.h>

int main (){

    int x, sq;

    printf("Enter the value");
    scanf("%d", &x);

    if(x<0)
     x= (-x);
    printf("The absolute value is %d", x);

   
    return 0;
}
