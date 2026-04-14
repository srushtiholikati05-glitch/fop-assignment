//To accept the number of terms and find the sum of the sine series
#include<stdio.h>
#include<math.h>
int fact(int i){
    if(i==0 || i==1){
        return i;
    }else{
        return i* fact(i-1);
    }
}

int main(){
    int n;
    float x;
    printf("Enter the value of x(in radian):");
    scanf("%f",&x);
    printf("ENter the number of terms :");
    scanf("%d",&n);
    float sum=0;
    for(int i=0;i<n;i++){
        double term=pow(x,2*i+1)/ fact(2*i+1);
        if(i%2==0){
            sum+=term;
        }else{
            sum-=term;
        }
    }
    printf("sum of sine series is %f",+sum);
    return 0;
    
}
