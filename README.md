# trigo1 (normal)
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

# trigo2 (another one)
#include <stdio.h>
#include <math.h>

float Trigo(int,int);
int square(int);

int main()
{
    int a,b;
    float c;
    printf("Please input 2 adjacent sides of the right triangle");
    scanf("%d %d",&a,&b);
    c=Trigo(a,b);
    printf("The third side is %.2f",c);

    return 0;
}

float Trigo(int x,int y){
    float z=sqrt(square(x)+square(y));
    return z;
}

int square(int x){
    return x*x;
}

