# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a triangular star pattern using loops.

### ALGORITHM

1. Begin the program.
2. Read an integer input from the user and store it in `r`.
3. Initialize `m = r + 1`.
4. Use a `for` loop to iterate `i` from 0 to `m-1`.

   * Print `"  " * (r-1)` to create left spacing.
   * Print `" " * i + "* " * (m-i)` to display the stars with proper spacing.
5. Terminate the program.

### PROGRAM
```
#Reg.No: 212223060266
#Name: Snega G

r=int(input())
m=r+1
for i in range(0,m):
    print("  "*(r-1),end="")
    print(" "*i+"* "*(m-i))
    
```

### OUTPUT
<img width="899" height="653" alt="{EF49FCA3-EC18-4CC2-A53A-C63534F9995B}" src="https://github.com/user-attachments/assets/83a6a1b7-e383-45b8-bcba-ae17ff27f758" />

### RESULT
Thus a Python program to print a triangular star pattern using loops was executed and implemented successfully.
