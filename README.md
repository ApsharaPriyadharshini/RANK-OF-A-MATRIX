# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library.
### Step 2: Create and store the given matrix using np.array().
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the rank of the matrix.
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[1, 2, 3],
              [3, 6, 9]])

rank = np.linalg.matrix_rank(A)

print(rank)
## Output:
<img width="1289" height="302" alt="image" src="https://github.com/user-attachments/assets/88f3479c-8e9f-47e1-a1f6-9bfb7ad616a8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

