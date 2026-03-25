# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```python
#Reg No.: 212222060262
#Name: SUJAN S B

import collections
n1=int(input())
n2=int(input())
n3=int(input())
de=collections.deque([n1, n2, n3])
de.popleft()
print("The deque after deleting is : ")
print(de)
```

### OUTPUT
<img width="813" height="299" alt="image" src="https://github.com/user-attachments/assets/db2b3055-722b-4c60-b171-b7bd517d1824" />

### RESULT
Thus Python program to delete elements at FRONT END of deque using a collection built-in function is implemented and executed successfully.
