# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Define the square matrix 𝐴, A using np.array().
### Step 2: Apply np.linalg.eig(A) to compute eigenvalues and eigenvectors.
### Step 3: Assign the output to two variables: one for eigenvalues, one for eigenvectors.
### Step 4: Print the eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: N V Chetan Satwik
#RegisterNumber: 212224240100
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
 <img width="1245" height="162" alt="image" src="https://github.com/user-attachments/assets/fa320260-fc80-4af9-84d3-fc997dce556b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
