# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy library 
### Step 2: Define the square matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the result

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: Niwash.K
#RegisterNumber:25014908

import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
~~~
<img width="1306" height="844" alt="Screenshot 2025-11-19 130153" src="https://github.com/user-attachments/assets/b032422f-a45c-47b2-bd52-5f41a6e0817d" />

## Output:
<img width="1279" height="360" alt="Screenshot 2025-11-19 130206" src="https://github.com/user-attachments/assets/1af5f02d-067c-4c65-8db5-2ee6267ddcba" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
