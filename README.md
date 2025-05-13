# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 :import the numpy module to use the built-in functions for calculation.
### Step 2:Assign np.array()
### Step 3:Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:end the program

## Program:
``` python
#Program to find the eigen values and eigen vectors.
#Developed by: JOTHIMANI P
#RegisterNumber:212224230108
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:

![image](https://github.com/user-attachments/assets/0cdf9225-9daf-40af-9d44-c73d996cb77f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
