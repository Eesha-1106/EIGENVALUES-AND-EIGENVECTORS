# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy library to perform matrix operations.
### Step 2: 
Define the matrix a using np.array() with given elements.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the Eigenvalues and Eigenvectors using print().

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Eesha Ranka
#RegisterNumber:212224240040

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

```

## Output:
![image](https://github.com/user-attachments/assets/1d52fc15-f2c1-4751-beee-7d5e299e4258)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
