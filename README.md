# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Import the numpy module to use the built-in functions for calculation
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:kamalesh v 
#RegisterNumber:212222240042
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector))
```
## Output:
![Screenshot (4)](https://user-images.githubusercontent.com/119477328/229989565-eb586dd6-8d6d-4ee5-972c-76fe88966f11.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
