# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library.
### Step 2: Create and store the matrix using a NumPy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: display the eigenvalues and the eigenvectors.

## Program:

'''Program to find the eigen values and eigen vectors.
Developed by: POOJA A
RegisterNumber: 212225040300'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eig_values,eig_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))

## Output:
<img width="1253" height="283" alt="image" src="https://github.com/user-attachments/assets/83634c33-9605-423d-99ad-9aea5fdf7333" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
