# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Take the given list and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print and End the program
## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy

a=numpy.array([[2,-3,0],[2,-5,0],[0,0,3]])

b,c=numpy.linalg.eig(a)

print(f"Eigen values are {b} and Eigen Vectors are {c}")
## Output:
<img width="998" height="777" alt="image" src="https://github.com/user-attachments/assets/ce3433b0-5c12-425a-bfca-9cc497fec659" />
<img width="1287" height="266" alt="image" src="https://github.com/user-attachments/assets/7a773815-4cdf-4caf-8b78-ea9cdb3806a4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
