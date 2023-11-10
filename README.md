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
#Program to find the square root for the given number(newton's method)using function
#Developed by: KOUSALYA A.
#Register number: 212222230068
def sqrt(n):
    a=float(n)
    for i in range(100):
        n=0.5*(n+a/n)
    return n
a=int(input())
print("Square root of the number:",sqrt(a)) 
*/
```

## Output:
![image](https://github.com/Kousalya22008930/Square-root-of-a-number/assets/119389108/3e854995-9704-4120-8a0b-2270a0eb9ab6)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
