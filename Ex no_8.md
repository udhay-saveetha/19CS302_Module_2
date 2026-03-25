
# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1.Start the program and declare two functions for multiplication and division.

2.Define functions that take no arguments and return no value.

3.Read two numbers from the user.

4.Call the functions to perform multiplication and division.

5.Display the results. 

## Program:
```
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).

*/

#include <stdio.h>

void multiply()
{
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);
    printf("Multiplication = %d\n", a * b);
}

void divide()
{
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);
    if(b != 0)
    {
        printf("Division = %.2f\n", (float)a / b);
    }
    else
    {
        printf("Division by zero is not allowed.\n");
    }
}

int main()
{
    multiply();
    divide();
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/a7fc5884-af18-497a-af27-03fcafd0288a)



## Result:
Thus the program was executed and the output was verified successfully.


