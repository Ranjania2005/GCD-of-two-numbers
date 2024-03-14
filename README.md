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
def gcd():
    a=int(input())
    b=int(input())
    while b!=0:
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```

## Output:
![Screenshot (142)](https://github.com/Ranjania2005/GCD-of-two-numbers/assets/151624950/4ad01a4b-83ca-49d8-bd1f-cdedc86b5196)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
