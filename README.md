# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:End of the program 
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
r=np.linalg.matrix_rank(A)
print(r)
```
## Output:
<img width="1316" height="831" alt="image" src="https://github.com/user-attachments/assets/a5be27a8-8ef9-4ff1-b0d7-323c6082e06c" />
<img width="1281" height="295" alt="image" src="https://github.com/user-attachments/assets/07476e0b-0957-40e1-b9ec-0d7f197e1205" />

## Result:

Thus the rank for the given matrix is successfully solved by  using a python program.

