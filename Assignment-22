/*: Write a menu driven program in C to perform various string operations using in-built functions.
*/
#include<stdio.h>
#include<string.h>
int main(){
    char str1[100],str2[100];
    printf("ENter the first string :");
    scanf("%s",str1);
    printf("Enter the second string:");
    scanf("%s",str2);
    printf("\n____Menu_____\n");
    printf("1.To compare\n");
    printf("2.copy\n");
    printf("3.join both string\n");
    printf("4.length\n");
    int a;
    printf("Enter the number operation :");
    scanf("%d",&a);
    if(a==1){
        if(strcmp(str1,str2)==0){
            printf("STrings are equal\n");
        }else if(strcmp(str1,str2)<0){
            printf("first string is greater than second\n");
        }else{
            printf("SEcond string is greater than first\n");
        }
    }else if(a==2){
        char str3[100];
        printf("String copy successfully\n");
        strcpy(str3,str1);
        printf("%s\n",str3);
    }else if(a==3){
        strcat(str1,str2);
        printf("Finally string :\n");
        printf("%s",str1);
    }else if(a==4){
        printf("%d\n",strlen(str1));
        printf("%d\n",strlen(str2));
    }
    return 0;
}
