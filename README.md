# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and read the elements of the square matrix.
### Step 2: Import the NumPy library and create the matrix using numpy.array().
### Step 3: Using np.linalg.eig(), obtain two results: the eigenvalues and the corresponding eigenvectors of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors and stop the program.

## Program:
```
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:

<img width="1920" height="1080" alt="Screenshot (143)" src="https://github.com/user-attachments/assets/14fa7baa-3bc4-4e6b-a2ab-2b463fbda136" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
