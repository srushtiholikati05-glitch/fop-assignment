/*Write a program in C to simulate a simple calculator that performs basic arithmetic operations such as addition, subtraction,
multiplication, and division. The calculator should also perform special operations like computing xʸ (power) and x! (factorial).
*/
#include<stdio.h>
#include<math.h>

int main(){
    printf("\n--- menu of operation ---\n");
    printf("1.addition of numbers \n");
    printf("2.subtraction of numbers \n");
    printf("3.multipication of numbers \n");
    printf("4.divison of numbers \n");
    printf("5.x power y \n");
    printf("6.factorial \n");
    int n;
    printf("Enter the number of operation in given in menu :");
    scanf("%d",&n);
    if(n==1){
        int a,b;
        printf("ENter the two numebrs :");
        scanf("%d %d",&a,&b);
        printf("Addition of two numbers is %d",a+b);
    }else if(n==2){
        int a,b;
        printf("ENter the two numbers :");
        scanf("%d %d",&a,&b);
        printf("subtraction between two numbers is %d \n",a-b);
    }else if(n==3){
        int a,b;
        printf("Enter the two numbers :");
        scanf("%d %d",&a,&b);
        printf("Multpication of two numbers is %d\n",a*b);
    }else if(n==4){
        float a,b;
        printf("ENter the two numbers :");
        scanf("%f %f",&a,&b);
        printf("Division of two numbers is %.2f\n",a/b);
    }else if(n==5){
        int x,y;
        printf("ENter the number :");
        scanf("%d",&x);
        printf("Enter the prefix:");
        scanf("%d",&y);
        int v=pow(x,y);
        printf("%d to the power %d is %d \n",x,y,v);
    }else if(n==6){
        int n;
        int a=1;
        printf("ENter the number :");
        scanf("%d",&n);
        for(int i=1;i<n+1;i++){
            a=a*i;
        }
        printf("Factorial of %d is %d \n",n,a);
    }
    return 0;
}
