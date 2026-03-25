#include <stdio.h>
int main() {
    int n, sum = 0, a[100];
    printf("Enter number of elements: ");
    scanf("%d", &n);

    for(int i = 0; i < n; i++) {
        scanf("%d", &a[i]);
    }

    for(int i = 1; i < n; i += 2) {
        sum += a[i];
    }

    printf("Sum of even position elements = %d", sum);
    return 0;
}
