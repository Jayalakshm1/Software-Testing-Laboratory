# Ex.No: 6 To check whether the string is Palindrome and generate test cases.
                                                                         
### REGISTER NUMBER : 212221040066
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome.
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
def Palindrome(string): 
    for i in range(0, int(len(string) / 2)): 
        if string[i] != string[len(string) - i - 1]: 
            return False 
    return True 
s = input("Enter a string: ") 
c = 1 
for i in s: 
    if not i.isalpha():  
        c = 0 
        break
 if c == 0: 
    print("Enter a valid string")  
else:
    answer = Palindrome(s)  
    if answer: 
        print("The given string is a palindrome") 
    else: 
        print("The given string is not a palindrome")
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: S010S
 Enter a valid string
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: 12321
 Enter a valid string
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: madam
 The given string is a palindrome
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: abcd
 The given string is not a palindrome
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: &%&
 Enter a valid string
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: A1B2A1
 Enter a valid string
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: 1234321
 Enter a valid string
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: world
 The given string is not a palindrome
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: *(&)
 Enter a valid string
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Pro6.py =================
 Enter a string: madam!
 Enter a valid string
```
### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
