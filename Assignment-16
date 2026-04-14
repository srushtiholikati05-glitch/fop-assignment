/*: To accept a list of N integers and partition the list into two sublists containing even and odd numbers.*/
#include<stdio.h>

int main() {
    int n;
    printf("Enter number of elements: ");
    scanf("%d", &n);

    int r[n], e[n], o[n];
    int ec = 0, oc = 0;  // counters

    printf("Enter the numbers:\n");
    for(int i = 0; i < n; i++) {
        scanf("%d", &r[i]);

        if(r[i] % 2 == 0) {
            e[ec] = r[i];   // store even
            ec++;
            
        } else {
            o[oc] = r[i];   // store odd
            oc++;
        }
    }

    printf("Even numbers: ");
    for(int i = 0; i < ec; i++) {
        printf("%d\t", e[i]);
    }

    printf("\nOdd numbers: ");
    for(int i = 0; i < oc; i++) {
        printf("%d\t", o[i]);
    }

    return 0;
}
