# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
import numpy as np

Step 2:
get input as a=np.array(eval(input()))

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
print the eigenvectors and eigen values by the print statement

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Alfred A.B.
#RegisterNumber:212222110002
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```

## Output:
![image](https://github.com/Alfredsec/EIGENVALUES-AND-EIGENVECTORS/assets/120621608/269b6f00-f01e-4647-b526-a62456be5aa0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
