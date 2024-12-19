# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array() 
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the progaram


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Latchaya priyan S
#RegisterNumber:24900388
import numpy as np
A=np.array([[4,2],[2,4]])
result1,result2=np.linalg.eig(A)
print(f"Eigen values are {result1} and Eigen Vectors are {result2}")
```

## Output:
![Screenshot 2024-12-20 002314](https://github.com/user-attachments/assets/8536a730-97f3-4e75-b014-e22a80d13ac4)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
