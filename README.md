# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
import numpy as np

a=[[1,3],[2,5]]

b=np.array([5,-3])

c=np.linalg.solve(a,b)

print(c)


<img width="778" height="393" alt="Screenshot 2026-03-20 104903" src="https://github.com/user-attachments/assets/f0050a75-baa4-46d4-8fad-ce8511d60b03" />


## Output:

<img width="581" height="169" alt="Screenshot 2026-03-20 104912" src="https://github.com/user-attachments/assets/e5c74db6-7daf-4c2c-84a6-e0890ac6a00a" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

