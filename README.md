# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen vectors.
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors, then end the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: S Santhosh
#RegisterNumber: 22009296
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result=np.linalg.inv(A)
print(result)
```
## Output:
!['output'](/eigen.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
