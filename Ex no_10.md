
# EX 10 C program to find the factorial of a given number using a function with arguments and return type.

## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1.Start the program and declare a function factorial(int) with return type.

2.Read a number from the user.

3.Call the factorial function with the number as an argument.

4.Compute factorial in the function using a loop and return result.

5.Display the result in main.

## Program:
```


#include <stdio.h>

// Function to calculate factorial
int factorial(int n)
{
    int i, fact = 1;
    for(i = 1; i <= n; i++)
    {
        fact *= i;
    }
    return fact;
}

int main() {
    int num, result;
    
    printf("Enter a number: ");
    scanf("%d", &num);
    
    result = factorial(num);
    printf("Factorial of %d = %d\n", num, result);
    
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/e2e1f1e8-5e69-4a83-b364-6cd622f63802)



## Result:
Thus the program was executed and the output was verified successfully.
