# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program.
### Step 2: Create the matrix with the given numbers.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the answers and stop.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: mehul narayanan v
#RegisterNumber:212225040231
#Program to find the eigen values and eigen vectors.
#Developed by: Mehul Narayanan V
#RegisterNumber: 25018961

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

# Define the matrix
matrix = np.array([[2, 2], [1, 3]])

# Calculate eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(matrix)

# Print the result matching the expected format exactly
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```
## Output:
<img width="1347" height="262" alt="image" src="https://github.com/user-attachments/assets/e732fac2-e795-4bbd-a911-209e2f7ae139" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
