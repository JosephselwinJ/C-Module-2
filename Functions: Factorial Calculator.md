## Functions: Factorial Calculator in C (Using Function)
## Aim
To write a C program that calculates the factorial of a given number using a user-defined function.

## Algorithm
Start the program.

Declare the function fact().

In the main() function, call the fact() function.

In the fact() function:

a. Declare variables i, N, and fact (initialized to 1).

b. Read an integer N from the user.

c. Use a for loop from 1 to N:

Multiply fact by i in each iteration.

d. After the loop, print the factorial value.

End the program.

## Program
```
#include <stdio.h>
void fact()
{
    int i, N;
    unsigned long long factorial = 1;
    printf("Enter a positive integer: ");
    scanf("%d", &N);
    if (N < 0)
    {
        printf("Factorial is not defined for negative numbers.\n");
        return;
    }
    for (i = 1; i <= N; i++) {
        factorial *= i;
    }
    printf("Factorial of %d is %llu\n", N, factorial);
}

int main() 
{
    fact();
    return 0;
}
```

## Output
![image](https://github.com/user-attachments/assets/1038cbda-3b7f-4208-a0ca-ac664f3ac56b)

## Result
C program that calculates the factorial of a given number using a user-defined function is written.
