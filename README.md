# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import library NumPy as np
### Step 2: Define the 3×3 array A with the given values.
### Step 3: Compute the inverse using np.linalg.inv().
### Step 4: Display the output value of inverse matrix.

## Program:

#Program to find the inverse of a matrix.

#Developed by: A.Jayachandran

#RegisterNumber: 25015034

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])
              
A_inv = np.linalg.inv(A)

print(A_inv)

## Output:
<img width="912" height="766" alt="image" src="https://github.com/user-attachments/assets/82f43c39-d7eb-4416-8c43-448a95944e37" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

