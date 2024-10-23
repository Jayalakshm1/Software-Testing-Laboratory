# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 
                                                                    
### REGISTER NUMBER : 212221040066

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### a) do.while
```
def display(): 
    start=input("Enter a positive value for START: ") 
    end=input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start) 
            end=int(end) 
            print(start,end=' ')
            if start<end: 
                start+=1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.")
display() 
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 >>> 
= RESTART: C:\Users\Home\Documents\STL\Pro1.py
 Enter a positive value for START: 1
 Enter a positive value for END: 4
 1 2 3 4 
>>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: -10
 Enter a positive value for END: 5
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: hello
 Enter a positive value for END: y
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: 
 Enter a positive value for END: 
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: 5.85
 Enter a positive value for END: 29.34
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: 0
 Enter a positive value for END: 
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: 
 Enter a positive value for END: 0
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: ^
 Enter a positive value for END: &
 Enter a valid positive number.
 >>> 
================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: 54
 Enter a positive value for END: adf
 Enter a valid positive number.
 ================= RESTART: C:\Users\Home\Documents\STL\Pro1.py =================
 Enter a positive value for START: 1
 Enter a positive value for END: -5
 Enter a valid positive number.
```
### b) while
```
start=input("Enter a positive value for START: ")
 end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric():
 start=int(start)
 end=int(end)
 while start<end:
 print(start,end = ' ')
 start+=1 
else:
 print("Enter a valid positive number.") 
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 >>> 
= RESTART: C:/Users/Home/Documents/STL/Pro2.py
 Enter a positive value for START: 1
 Enter a positive value for END: 4
 1 2 3 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: -10
 Enter a positive value for END: 5
 Enter a valid positive number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: afd 
 Enter a positive value for END: sjdvbhsd
 Enter a valid positive number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: 
 Enter a positive value for END: 
 Enter a valid positive number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: 0
 Enter a positive value for END: 0
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: adn
 Enter a positive value for END: 200
 Enter a valid positive number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: 1
 Enter a positive value for END: 0
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: 0
 Enter a positive value for END: 1
 0 
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: qed
 Enter a positive value for END: 5
 Enter a valid positive number.
 ================= RESTART: C:/Users/Home/Documents/STL/Pro2.py =================
 Enter a positive value for START: 29
 Enter a positive value for END: snjnjd
 Enter a valid positive number.
```
### c) if..else
```
def compare():
    a=input("Enter a value for A: ")
    b=input("Enter a value for B: ")
    try:
        a=int(a)
        b=int(b)
        if a>b:
            print("A is greater than B")
        elif a<b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    except ValueError:
        print("Enter a valid number.")
 compare()
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 = RESTART: C:/Users/Home/Documents/STL/Pro4.py
 Enter a value for A: 1
 Enter a value for B: 1
 A is equal to B
 ================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: 2
 Enter a value for B: 1
 A is greater than B
 ================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: 1
 Enter a value for B: 2
 B is greater than A
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: -10
 Enter a value for B: 5
 B is greater than A
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: -9
 Enter a value for B: 3
 B is greater than A
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: 10
 Enter a value for B: -5
 A is greater than B
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: hello
 Enter a value for B: y
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A:   
 A is equal to B
 Enter a value for B: Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
 Enter a value for A: 5
 Enter a value for B: sdf
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro4.py =================
Enter a value for A: 5
Enter a value for B: 
Enter a valid number.
```
### d) switch
```
def switch():
    switcher={
        0:"even",
        1:"odd"
        }
    n=input('Enter a value for N: ')
    try:
        n=int(n)
        print(switcher[n%2])
    except ValueError:
        print("Enter a valid number.") 
switch()
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 ================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: 1
 odd
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: -10
 even
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: afc
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: 0
 even
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: 
Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: 6.354
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: 10e5
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: &
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N:    
0/1
 Enter a valid number.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro3.py =================
 Enter a value for N: A
 Enter a valid number.
```
### e) for
```
def iterate():
 string=input("Enter a string: ")
 for i in string:
 print(ord(i),end=" ") 
iterate() 
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 >>> 
= RESTART: C:/Users/Home/Documents/STL/Pro5.py
 Enter a string: say
 115 97 121 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: 1153
 49 49 53 51 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: ^&*
 94 38 42 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: 0
 48 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: 
45 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: ndfviuddkv
 110 100 102 118 105 117 100 100 107 118 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: xsj   Scs
 120 115 106 32 32 32 83 99 115 
>>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro5.py =================
 Enter a string: dn  inn
 100 110 32 32 105 110 110
```

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


