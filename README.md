# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : 

Import the numpy library.

Step 2: 

Create the matrix a.

Step 3: 

Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4: 

Print the eigenvalues and eigenvectors nicely.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Saravana Kumar S
#RegisterNumber:212224220090

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="866" height="246" alt="Screenshot 2025-08-14 221141" src="https://github.com/user-attachments/assets/4e14a9e5-08df-436c-b91b-df3d8a809b2a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
