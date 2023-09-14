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
Developed by: SARAVANA KUMAR M
RegisterNumber:212222230133  
*/
def gcd():
    a=int(input())
    b=int(input())
    if a<b:
        c=a
    else:
        c=b
    for i in range(1,c+1):
        if a%i==0 and b%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)  
```

## Output:
![Screenshot 2023-09-14 222116](https://github.com/Saravana-kumar369/GCD-of-two-numbers/assets/117925254/781639cd-fb80-41a1-8b2c-744f42978c2a)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
