# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
### Step 1: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matri
## Program:
```
#porgram to find eigenvalues and eigenvectors
#program developed by: Kathiresan K
#Register Number:212223110021
```
```
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,-0],[0,0,3]])
eigval,eigvect=np.linalg.eig(matrix)
print("Eigen values are",eigval,"and Eigen Vectors are",eigvect)
```
## Output:
![image](https://github.com/Kathiresan-23013376/EIGENVALUES-AND-EIGENVECTORS/assets/150008375/8acfae95-7518-45cb-9036-b71285ab42fb)

![image](https://github.com/Kathiresan-23013376/EIGENVALUES-AND-EIGENVECTORS/assets/150008375/5de71a1c-beea-4398-ac75-ed0d2d54f597)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
