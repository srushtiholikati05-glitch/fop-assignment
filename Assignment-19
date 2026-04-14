/*Create Structure EMPLOYEE for storing details (Name, Designation, gender, Date of Joining and Salary). Define function members to
compute a) total number of employees in an organization b) count of male and female employee c) Employee with salary more than 
10,000 d) Employee with designation “Asst Manager”
*/
#include<stdio.h>
#include<string.h>

struct EMPLOYEE {
    char n[100]; // name
    char d[100]; // designation 
    char g[100]; // gender
    int date, month, year;
    int s; // salary
};

int main(){
    struct EMPLOYEE A[100];
    int c;

    printf("Enter number of employees: ");
    scanf("%d", &c);

    printf("Enter name, designation, gender, date (dd-mm-yyyy), salary:\n");

    for(int i = 0; i < c; i++){
        printf("Employee %d:\n", i+1);

        scanf("%s %s %s %d-%d-%d %d",
              A[i].n, A[i].d, A[i].g,
              &A[i].date, &A[i].month, &A[i].year,
              &A[i].s);
    }

    printf("\nTotal employees = %d\n", c);

    int m = 0, f = 0;

    for(int i = 0; i < c; i++){
        if(strcmp(A[i].g, "Male") == 0){
            m++;
        } else {
            f++;
        }
    }

    printf("Male = %d\nFemale = %d\n", m, f);

    printf("\nEmployees with salary > 10000:\n");
    for(int i = 0; i < c; i++){
        if(A[i].s > 10000){
            printf("%s\n", A[i].n);
        }
    }

    printf("\nEmployees with designation AsstManager:\n");
    for(int i = 0; i < c; i++){
        if(strcmp(A[i].d, "AsstManager") == 0){
            printf("%s\n", A[i].n);
        }
    }

    return 0;
}
