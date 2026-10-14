# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module to use the built in function for calculations
### Step 2: Prepare the given matrix and assign it to np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the EigenValues and EigenVectors and end the program

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: Kamalesh.P

#RegisterNumber:26014307

import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors = np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:<img width="1359" height="681" alt="Screenshot 2026-10-14 111020" src="https://github.com/user-attachments/assets/16de901b-c5c8-486c-91d3-62de416c023a" />
<img width="1418" height="381" alt="Screenshot 2026-10-14 111045" src="https://github.com/user-attachments/assets/b80846bb-cb2d-4b1d-ad3f-3808c00c8a41" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
