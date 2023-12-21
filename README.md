# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
1st import numpy as np
### Step 2: 
assign matrix to A.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the vectors.
## Program:
```
#Program to find the eigen values and eigen vectors.

#Developed by: YENDLURI CHANDANA

#RegisterNumber:23011258

import numpy as np

A=[[2,2],[1,3]]

values,vectors=np.linalg.eig(A)

print("Eigen values are",values,"and Eigen Vectors are",vectors)

```
## Output:
![image](https://github.com/23011258/EIGENVALUES-AND-EIGENVECTORS/assets/139842204/a36eaafd-545e-44ef-8f07-908a8b39f9a2)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
