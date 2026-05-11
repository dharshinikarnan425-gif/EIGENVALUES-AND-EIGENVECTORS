# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import the NumPy library using import numpy as np.
Step 2:
Read the order and elements of the matrix from the user and create the matrix using np.array().
Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4:
Display the Eigenvalues and Eigenvectors of the matrix. 
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Dharshini K
#RegisterNumber: 212225240034
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[4,2],[2,4]])
eig_values,eig_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vector))
```

## Output:
<img width="1205" height="760" alt="image" src="https://github.com/user-attachments/assets/feb1fa01-99c5-4a9c-8c85-e1d6f5d09deb" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
