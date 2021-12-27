# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1
 Define a function.
### Step 2
Assign number_iters = 100 in the function to perform 100 iteratios.
### Step 3 
Set i = 0.
### Step 4
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
### Step 5
Return number

## Program:
```
def newtonmethod(num,num_iter=100):
    a=float(num)
    for i in range(num_iter):
        num=0.5*(num+a/num)
    return num
num=int(input())
print("Square root of the number:",newtonmethod(num))
```

## Output:
![gcd of two number](output.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
