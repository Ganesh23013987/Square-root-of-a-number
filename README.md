# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# step 1:
Define a function.
# step 2:
Assign number_iters = 100 in the function to perform 100 iteratios.
# step 3:
Set i = 0.
# step 4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
# step 5:
Return number
# step 6:
End program.

## Program:
```
#Program to find the square root for the given number(newton's method) using function.
#Developed by: Ganesh D
#RegisterNumber: 23013987
def squareroot(num1,iternum):
    num2=float(num1)
    for i in range (iternum):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
num1=int(input())
iternum=100
squareroot(num1,iternum)
```

## Output:
<img width="643" alt="Sqrt of numbers" src="https://github.com/Ganesh23013987/Square-root-of-a-number/assets/147473768/454d40de-85e1-4010-85ae-5673a7034931">


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming. 
And the program code is successfully executed.
