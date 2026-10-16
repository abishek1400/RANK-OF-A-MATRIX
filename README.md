# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:End of the program
## Program:
```import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
r=np.linalg.matrix_rank(A)
print(r)
```
## Output:
<img width="1470" height="716" alt="image" src="https://github.com/user-attachments/assets/b3afbdc7-d7b2-458b-af72-053c28f7f01c" />
<img width="1278" height="280" alt="image" src="https://github.com/user-attachments/assets/2bc5c1ec-f9b4-4a19-a9f1-3d8a55e0de26" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

