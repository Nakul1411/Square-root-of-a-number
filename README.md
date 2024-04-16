# Find the square root of a number

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
#Program for finding the square root for the given number(newton's method) using function.
#Developed by : NAKUL R
#Reg no:212223240102
n=int(input())
approx=0.5*n
for i in range(1,10):
    a=0.5*(approx+n/approx)
    approx=a
print("Square root of the number:",a)
## Output:
![Screenshot 2024-04-16 213827](https://github.com/Nakul1411/Square-root-of-a-number/assets/138849780/be2b6dac-a440-44bd-8d1e-7ae003443992)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
