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
``````
#Program to find the solution for the given linear equations.
#Developed by: GAYATHRI.K
#RegisterNumber:23013439
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)
``````
## Output:
![Screenshot 2023-12-14 105957](https://github.com/GAYATHRI-K06/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145742742/0b8a6423-7c7e-4b61-b29c-7f6ba609357c)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

