# DATE:
# Exp 05: Find the square root of a number

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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: SREE NIVEDITAA SARAVANAN
RegisterNumber: 212223230213  
*/
```
```
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))
```

## Output:

![Screenshot 2024-10-08 094929](https://github.com/user-attachments/assets/13f3c4bb-fc89-4ba4-89dc-729e075f834b)

![Screenshot 2024-10-08 094938](https://github.com/user-attachments/assets/7830e5db-81db-4cc6-a6b4-c55fc1c36cd7)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
