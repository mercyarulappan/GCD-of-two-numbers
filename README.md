# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: MERCY A
RegisterNumber:  212223110027
*/

def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:

![Screenshot 2024-03-12 184052](https://github.com/mercyarulappan/GCD-of-two-numbers/assets/149233730/a94bfbb0-cde1-4a79-93b9-c5a090fbe75c)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
