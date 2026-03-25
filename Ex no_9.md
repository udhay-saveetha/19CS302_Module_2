
# EX 9 C program to find the sum of odd digits using do while loop.

## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1.Start the program and declare a variable for the number and sum of odd digits.

2.Read the number from the user.

3.Use a do-while loop to extract each digit of the number.

4.If the digit is odd, add it to the sum.

5.Display the sum of odd digits.

## Program:
```
/*
Program to find the sum of odd digits using do while loop.

*/

#include <stdio.h>

int main()
{
    int num, sum = 0, digit;

    printf("Enter a number: ");
    scanf("%d", &num);

    do
    {
        digit = num % 10;
        if(digit % 2 != 0)
        {
            sum += digit;
        }
        num /= 10;
    } while(num != 0);

    printf("Sum of odd digits = %d\n", sum);

    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/bc56a5e3-5b34-4002-b828-19e229bc371f)



## Result:
Thus the program was executed and the output was verified successfully.

