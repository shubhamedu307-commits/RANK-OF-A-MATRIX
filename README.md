# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:


#Program to find the rank of a matrix.
#Developed by: SHUBHAM KUMAR
#RegisterNumber:26013866

import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[5, -3, -10],[2, 2, -3],[-3, -1, 5]])

r=np.linalg.matrix_rank(A)

print(r)

<img width="1465" height="623" alt="EXP 2 rank of a matrix" src="https://github.com/user-attachments/assets/b118aec8-d051-46fa-ae0d-7970a7f1b6c7" />

## Output:<img width="1342" height="180" alt="EXP 2 RANK OF MATRIX RESULT" src="https://github.com/user-attachments/assets/9f756232-915c-45c1-b7db-72545b036d73" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

