/*Write a C program that accepts a string from the user and performs the following string operations:
i) Calculate length of string
 ii) String reversal 
 iii) Equality check of two strings 
 iv) Check palindrome 
 v) Check substring.*/

 #include<stdio.h>
#include<string.h>
int main(){
    char st[100],st2[100];
    
    printf("Enter the string: ");
    scanf("%s", st);
    printf("ENter another string for equality check:");
    scanf("%s",st2);
    int c=0;
  
    // to get length
    for(int i = 0; i < 100; i++){
        if(st[i] == '\0'){
            break;
        } else {
            c++;
        }
    }
    
    // to print reverse 
    printf("length of string is %d\n",c);
    for(int i=c-1;i>=0;i--){
        printf("%c",st[i]);
    }
    
    // to check equality
    if(strcmp(st,st2)==0){
        printf(" \nstring are equal ");
    }else{
        printf("\nString are not equal");
    }
    
    // to check palindrome
    char cpy_rev[100];
    for(int i=c-1;i>=0;i--){
        cpy_rev[c-1-i]=st[i];
    }
    cpy_rev[c]='\0';
    
    if(strcmp(cpy_rev,st)==0){
        printf("\nString is palindrome");
    }else{
        printf("\nString is not palindrome");
    }
    
    // to check substring
    if(strstr(st,st2)!=NULL){
        printf("\nsubstring is  found in main string");
    }else{
        printf("\nSubstring is not found in main string");
    }
     return 0;
 }
