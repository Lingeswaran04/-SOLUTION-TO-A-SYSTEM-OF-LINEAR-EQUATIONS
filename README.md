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
```
#Program to find the solution for the given linear equations.
#Developed by: LINGESWARAN K
#RegisterNumber:212222110022
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
soln=np.linalg.solve(a,b)
print(soln)
```

## Output:
![image](https://github.com/Lingeswaran04/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119103865/2ac898a2-cff9-4cbc-8808-49454d4f1cb6)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

