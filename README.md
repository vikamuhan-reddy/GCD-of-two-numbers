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
Developed by: vikamuhan.n
RegisterNumber: 23012418

def gcd():
    n1=int(input())
    n2=int(input())
    ln1=[]
    ln2=[]
    lnmax=[]
    for i in range(1,n1):
        if n1%i==0:
            ln1.append(i)
    for j in range(1,n2):
        if n2%j==0:
            ln2.append(j)
    m1=len(ln1)
    m2=len(ln2)
    if m1>=m2:
        for i in range(m1):
            if ln1[i] in ln2:
                lnmax.append(ln1[i])
    else:
        for i in range(m2):
            if ln2[i] in ln1:
                lnmax.append(ln2[i])
    maxnumber=max(lnmax)
    print("GCD of two numbers is:",maxnumber)
                
            
*/
```

## Output:
![gcd of two number](gcd.png)
![output](./gcd.png.jpg)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
