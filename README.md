# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: lakshmi mounika
RegisterNumber:  23004124
*/
n=int(input())
approx=0.5*n
for i in range(1,10):
    a=0.5*(approx+n/approx)
    approx=a
print("Square root of the number:",a)


```

## Output:

![Screenshot 2023-11-28 212513](https://github.com/mounika2005/Square-root-of-a-number/assets/145633112/7ed96df9-eb7a-47a9-a3fc-f52884453172)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
