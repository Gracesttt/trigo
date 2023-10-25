# trigo
#include <stdio.h>
#include <math.h>

float trigo(int,int);

int main()
{
    float a;
    a=trigo(3.0,4.0);
    printf("a=%.2f\n",a);
    return 0;
}

float trigo(int x,int y){
    float a;
    float in;
    in=((x*x)+(y*y));
    a = sqrt(in);
    return a;
}
