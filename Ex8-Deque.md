# Ex8 Deque
## DATE:14.5.25
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1.	Start
2.	Define a function count() that takes an array arr as input.
3.	Initialize a counter c to track the number of non-zero elements.
4.	Loop through the array from index 0 to MAX-1.
5.	For each element, check if it's non-zero.
6.	If the element is non-zero, increment the counter c.
7.	Return the final count of non-zero elements in the array.
8.	End   
  

## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: MONISH R
RegisterNumber:  212223220061
*/
int count(int *arr) {
  int c = 0, i;

  for (i = 0; i < MAX; i++) {
    if (arr[i] != 0)
      c++;
  }
  return c;
}
```

## Output:

![Screenshot 2025-05-14 200410](https://github.com/user-attachments/assets/29991d80-0f09-4e57-989f-66980dec0b15)


## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
