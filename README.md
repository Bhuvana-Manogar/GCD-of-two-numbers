# DATE:
# EX-4 Find the GCD of two numbers

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
#Developed by: Bhuvaneshwari M
#Register no: 212223230033
def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller=n2
    else:
        samller=n1
    for i in range(1,smaller+1):
        if n1%i==0 and n2%i==0:
            gcd1=i
    print(f"GCD of two numbers is: {gcd1}")
```

## Output:
![Screenshot 2024-08-29 083924](https://github.com/user-attachments/assets/305940de-420c-4044-bf96-7946c28fcc2a)

![Screenshot 2024-08-29 083937](https://github.com/user-attachments/assets/b981a00f-0c54-4c58-a31f-cd499f93c76e)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
