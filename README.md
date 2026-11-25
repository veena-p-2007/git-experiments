#include <stdio.h>

int main() {
    int num1, num2, sum;

    // Ask the user for input
    printf("Enter two integers: ");
    
    // Read and store the two integers
    scanf("%d %d", &num1, &num2);

    // Perform addition
    sum = num1 + num2;

    // Display the result
    printf("%d + %d = %d\n", num1, num2, sum);

    return 0;
}
