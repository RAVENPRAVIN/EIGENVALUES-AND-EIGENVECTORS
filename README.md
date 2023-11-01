# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module as np
### Step 2: 
Use array the built in function to enter values
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program 
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: PRAVIN KUMAR A.
#RegisterNumber: 23007430
import numpy as np
a=np.array([[4,2],[2,4]])
values,vector=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vector))
```
## Output:
![output](https://github.com/RAVENPRAVIN/EIGENVALUES-AND-EIGENVECTORS/assets/146820534/397761e0-04fb-4e48-83b0-0b05c1d3efbd)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
