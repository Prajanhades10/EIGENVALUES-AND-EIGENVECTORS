# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step2 : Prepare the lists from the matrix and assign in prj.array()
### Step3 : Using the prj.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step4 : End the program.  

## Program:
#Program to find the eigen values and eigen vectors.
```
#Developed by: prajan.ss  
#RegisterNumber: 212224230201
import numpy as prj
A = prj.array([[4,2],[2,4]])
values,vectors = prj.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
<img width="1387" height="981" alt="Screenshot 2025-08-19 100157" src="https://github.com/user-attachments/assets/54c22929-cbe7-4dc3-b1d1-daa3b8ddc78f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
