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
Developed by: Antony Abishek K
RegisterNumber: 212223240009
*/
def gcd():
    num1,num2=int(input()),int(input())
    if num1<num2:
        smaller=num1
    else:
        smaller=num2
    for i in range (1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)
```

## Output:
![Screenshot 2024-05-17 230451](https://github.com/Antonyabishek2004/GCD-of-two-numbers/assets/138849620/d82200a4-b0b8-4231-b6cb-a86069ce6f7a)
![Screenshot 2024-05-17 230502](https://github.com/Antonyabishek2004/GCD-of-two-numbers/assets/138849620/b54e8b61-8ae4-441e-bcf2-dcbffd790420)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
