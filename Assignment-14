//: Write a C program to input a binary number from the user and convert it into a decimal number.
#include<stdio.h>
#include<math.h>
int main(){
   int v;
   printf("ENter the number bites :");
   scanf("%d",&v);
   int n,t;
   int total=0;
   int ar[v];
   printf("Enter the number :");
   scanf("%d",&n);
   t=n;
   for(int i=0;i<v;i++){
       ar[i]=t%10;
       t=t/10;
   }
   for(int i=0;i<v;i++){
       if(ar[i]==1){
           int j=pow(2,i);
           total=total+j;
       }
   }
   printf("Decimal number is %d",total);
    return 0;
}
