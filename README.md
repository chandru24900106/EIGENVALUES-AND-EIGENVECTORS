# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the NumPy library.
### Step 2: Set the environment variable OPENBLAS_NUM_THREADS to 1 to limit the number of OpenBLAS threads.
### Step 3: Create a 3×3 matrix a with the given elements and calculate its eigenvalues and eigenvectors using np.linalg.eig(a). Store them in values and vectors.
### Step 4: Display the eigenvalues and eigenvectors using the format() function and Stop.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: chandru v
#RegisterNumber:212224230043
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:

<img width="1253" height="177" alt="image" src="https://github.com/user-attachments/assets/61b94f3f-00d1-4664-b174-e767206419c9" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
