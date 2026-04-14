/*Write a C Program to calculate the salary of an employee given his basic pay (taken as input from the user). Calculate gross
 salary of employee. Let HRA be 10 % of basic pay and TA be 5% of basic pay. Let employees pay professional tax as 2% of  total
  salary. Calculate net salary payable after deductions.*/
  #include<stdio.h>
  int main(){
    float basic,gs,hra,ta,pt,net;
    printf("ENter the amount of basic pay :");
    scanf("%f",&basic);
    hra=0.10*basic;
    ta=0.05*basic;
    gs=hra+ta+basic;
    pt=0.02*gs;
    net=gs-pt;
    printf("Net salary payable after deductions is %.2f",net);
    return 0;
  }
