# EX 7 C Program to Print a right triangle star Pattern

## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1.Start the program.

2.Declare an integer variable for the number of rows.

3.Read the number of rows from the user.

4.Use nested loops to print stars (*) in a right triangle pattern.

5.End the program.

## Program:
```
/*
Program to Print a right triangle star Pattern

*/

#include <stdio.h>

int main()
{
    int rows, i, j;

    printf("Enter number of rows: ");
    scanf("%d", &rows);

    for(i = 1; i <= rows; i++)
    {
        for(j = 1; j <= i; j++)
        {
            printf("*");
        }
        printf("\n");
    }

    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/2a2385fe-b774-49c9-bd07-c3181706abb3)



## Result:
Thus the program was executed and the output was verified successfully.

