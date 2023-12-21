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
Developed by: Sanjay siavaraamkrishnan M
RegisterNumber:23013798  
*/
```
def gcd():<br>
     x = int(input())<br> 
     y = int(input())<br>
     sum=0<br>
     for i in range(1,x+1):<br>
         if(x%i==0 and y%i==0):<br>
          sum=i<br>
     print(f"GCD of two numbers is: {sum}")<br>
      
    

## Output:
![image](https://github.com/sanjaysivaramakrishnan/GCD-of-two-numbers/assets/151629616/0ab8a756-267d-4199-859a-0f2af1556dcf)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
