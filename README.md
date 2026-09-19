# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the numpy module to use the built-in functions for calculation

## Step 2:
Prepare the lists from each linear equations and assign in np.array()

## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4:
End the program

## Program:<img width="1317" height="232" alt="image" src="https://github.com/user-attachments/assets/f8070b21-408f-44c0-90ed-4d243ecba238" />

```
#Program to find the eigen values and eigen vectors.
#Developed by: Rathish R 
#RegisterNumber:212224240132
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix = np.array([[2,-3,0],[2,-5,0],[0,0,3] ])
eigenValue,eigenVector=np.linalg.eig(matrix)
print("Eigen values are",eigenValue,"and Eigen Vectors are",eigenVector)
```

## Output:
<img width="1317" height="232" alt="image" src="https://github.com/user-attachments/assets/d957589d-0431-445c-b3fa-5a08694a3518" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
