# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1. Start the program.
2. Declare a 2D array and variables for rows and columns.
3. Read the number of rows and columns, then input all elements of the array.
4. Traverse the array and check if each element is odd using element % 2 != 0.
5. Print only the odd elements and end the program.

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>

int main() {
    int arr[10][10], rows, cols, i, j;
    scanf("%d%d", &rows, &cols);

    for(i = 0; i < rows; i++) {
        for(j = 0; j < cols; j++) {
            scanf("%d", &arr[i][j]);
        }
    }

    printf("Odd elements in the array:\n");
    for(i = 0; i < rows; i++) {
        for(j = 0; j < cols; j++) {
            if(arr[i][j] % 2 != 0) {
                printf("%d ", arr[i][j]);
            }
        }
    }
    printf("\n");
    return 0;
}
*/
```

## Output:
![444989031-02655874-7731-4828-8156-d2fbe01db48c](https://github.com/user-attachments/assets/0951f81d-9db1-4cb6-bf7b-e79575a8b6c9)



## Result:
Thus the program was executed and the output was verified successfully.
