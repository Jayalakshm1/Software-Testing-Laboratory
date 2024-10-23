# Ex.No: 5 To perform binary search and inspect for failures.
                                                                            
### REGISTER NUMBER : 212221040066
### AIM: 
Write a python program for Binary Search and inspect for failures. 
 
### Algorithm:
1. Start the program. 
2. Get the list from the user 
3. Get the element to be searched 
4. Compare the mid element with the key, if same return the index 
5. If key is greater, search it in the right side, else search it in the left side. 
6. If not found return -1 
7. Stop the program. 

### Program:
```
def binary_search(arr, x):
    low = 0 
    high = len(arr) - 1
    mid = 0 
    while low <= high:
        mid = (high + low) // 2
        if arr[mid] < x:
            low = mid + 1
        elif arr[mid] > x:
            high = mid - 1
        else:
            return mid
    return -1 
 
arr = [ 2, 3, 4, 10,40 ] 
x = input("Enter the element to be searched: ") 
try: 
    x = int(x) 
    result = binary_search(arr, x)  
    if result != -1: 
          print("Element is present at index",str(result)) 
    else: 
          print("Element is not present in array") 
except: 
    print("Enter a valid input!")
```
### Output:
```
Python 3.12.3 (tags/v3.12.3:f6650f9, Apr  9 2024, 14:05:25) [MSC v.1938 64 bit 
(AMD64)] on win32
 Type "help", "copyright", "credits" or "license()" for more information.
 >>> 
= RESTART: C:/Users/Home/Documents/STL/Exp5.py
 Enter the element to be searched: 10
 Element is present at index 3
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: -5
 Element is not present in array
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: 
Enter a valid input!
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: abc
 Enter a valid input!
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: 20
 Element is not present in array
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: 3 4 
Enter a valid input!
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: 5.6
 Enter a valid input!
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: !@
 Enter a valid input!
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: -10
 Element is not present in array
 >>> 
================= RESTART: C:/Users/Home/Documents/STL/Exp5.py =================
 Enter the element to be searched: 22/7
 Enter a valid input!
```
### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
