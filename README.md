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
#Developed by:SREEKUMAR S 
#RegisterNumber:23008070
import numpy 
a_martix=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
b_martix=[-9,4,-1]
c=numpy.linalg.solve(a_martix,b_martix)
print(c)
```

## Output:
![out](https://github.com/guru14789/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151705853/fb2f4b3b-31fe-4a84-b06a-5638ff32eff6)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

