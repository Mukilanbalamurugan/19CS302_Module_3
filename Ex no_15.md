# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start the program.
2. Read the size of the array and the array elements.
3. Traverse the array using a loop.
4. If an element is even (element % 2 == 0), print 'E'; otherwise, print the element itself.
5. End the program.

## Program:
```
/*
Program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>

#include <stdio.h>

int main() {
    int arr[100], n, i;

    printf("Enter the number of elements: ");
    scanf("%d", &n);

    printf("Enter the elements:\n");
    for(i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    printf("Modified array:\n");
    for(i = 0; i < n; i++) {
        if(arr[i] % 2 == 0)
            printf("E ");
        else
            printf("%d ", arr[i]);
    }

    printf("\n");
    return 0;
}
*/
```

## Output:

![444991150-b35cda82-5020-45d1-9ea2-a5d17fed44aa](https://github.com/user-attachments/assets/3d16743d-8764-4abe-814f-8f99151e14f9)


## Result:
Thus the program was executed and the output was verified successfully.
