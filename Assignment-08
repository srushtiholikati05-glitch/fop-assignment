/*Write a program in C to accept marks of five courses of a student and compute the result. A student is considered PASS if he/she
scores 40 marks or more in each course. If the student passes, calculate the aggregate percentage and assign the grade as follows:
•	Aggregate ≥ 75% : Distinction

•	Aggregate ≥ 60% and < 75% : First Division

•	Aggregate ≥ 50% and < 60% : Second Division

•	Aggregate ≥ 40% and < 50% : Third Division
*/

#include<stdio.h>

int main(){
    int a=0;
    int s[5];
    for(int i=0;i<5;i++){
        printf("ENter the marks of each subject :");
        scanf("%d",&s[i]);
    }
    for(int i=0;i<5;i++){
        a=a+s[i];
    }
    int sum=a/5;
    for(int i=0;i<5;i++){
        if(s[i]<40){
            printf("You are falied !!!");
        }
    }
    if(sum>=75){
        printf("your grade is Distinction ");
    }else if(sum>=60 && sum<75){
        printf("Your grade is first division");
    }else if(sum >=50 && sum<60){
        printf("Your grade is second division");
    }else if(sum >=40 && sum<50){
        printf("Your grade is third division");
    }
    return 0;
}
