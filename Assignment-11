/*Write a program in C to accept a number from the user and compute the following:
a)	Square root of the number
b)	Square of the number
c)	Cube of the number
d)	Check whether the number is prime
e)	Factorial of the number
f)	Prime factors of the number
*/
#include<stdio.h>
#include<math.h>

int main(){
    int a;
    printf("ENter the number :");
    scanf("%d",&a);

    // square root
    int v=sqrt(a);
    printf("Square root of %d is %d\n",a,v);

    // square 
    printf("Square of number %d is %d\n",a,a*a);

    // cube
    printf("Cube of number %d is %d\n",a,a*a*a);

    // prime
    if(a%2==0){
        printf("Given number is prime\n ");
    }else{
        printf("Given number is not prime\n ");
    }

    // factorial 
    int n=1;
    for(int i=1;i<a+1;i++){
        n=n*i;
    }
    printf("FActorial of number %d is %d\n",a,n);

    // prime factor
    printf("Prime factor :");
     for (int i = 2; i <= a; i++) {
        while (a % i == 0) {
            printf("%d ", i);
            a = a / i;
        }
    }
    return 0;
}
