# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Santhan Kumar 
#RegisterNumber: 23004568
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
<img width="623" alt="rank" src="https://github.com/SANTHAN-2006/RANK-OF-A-MATRIX/assets/80164014/761fddbf-3110-4f65-bbd3-29c4af7c964d">

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

