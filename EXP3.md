# Ex.No: 3 To check the number is prime or not and inspect for failures.
                                                                            
### REGISTER NUMBER : 212221040066
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
num = input() 
flag = 0 
if num.isnumeric(): 
    z = int(num) 
    if (z ==2): 
        flag = 1 
    if(z > 2): 
        for i in range(2,z//2): 
            if z%i ==0: 
                flag = 0 
                break  
            else: 
                flag = 1 
    if(flag == 1): 
        print("Prime Number") 
    else: 
        print("Not a Prime Number") 
else: 
    print("Enter a Positive Number")
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 >>> 
= RESTART: C:\Users\Home\Documents\STL\Exp3.py
 10
 Not a Prime Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 2
 Prime Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 abc
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================-5
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 A
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 !@
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 1.5
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 b5f
 Enter a Positive Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 5
 Not a Prime Number
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Exp3.py =================
 22/7
 Enter a Positive Number
```
### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
