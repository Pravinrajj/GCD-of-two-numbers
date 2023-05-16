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
Developed by: G.K Pravinrajj
RegisterNumber:  212222240080
*/

def gcd():
    a=int(input())
    b=int(input())
    if a<b:
        s=a
    else:
        s=b
    for i in range(1,s//2):
        if(a%i==0 and b%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)        
```

## Output:
![image](https://github.com/Pravinrajj/GCD-of-two-numbers/assets/117917674/71a30cd5-784d-4ead-a6ba-db15fd4678c3)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
