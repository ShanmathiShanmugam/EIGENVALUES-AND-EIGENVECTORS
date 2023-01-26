# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: get input as a=np.array(eval(input()))
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigenvectors and eigen values by the print statement

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: S.Shanmathi
#RegisterNumber:22003171
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://user-images.githubusercontent.com/121243595/214853272-ce5a83f0-e256-4465-bd80-060b909e0d75.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
