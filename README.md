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
Program to find the square root for the given number(newton's method) using function.
Developed by: SOWMYA V
RegisterNumber: 22005551 
def squareroot(x,iternum):
    b=float(x)
    for i in range(iternum):
         x=0.5*(x+b/x)
    print("Square root of the number:",x)
x=int(input())
iternum=15
squareroot(x,iternum)
```

## Output:
![image](https://user-images.githubusercontent.com/119475775/211491122-5be2d880-584d-4d66-ad99-31a364d5b602.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
