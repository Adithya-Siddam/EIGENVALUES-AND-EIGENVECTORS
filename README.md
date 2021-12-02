# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Create s python program to cslculate the eigen values and vectors of a given matrix
### Step 2: 
Use numpy as np and enter the elements of the matrix in array.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the output and end the program.
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: S Adithya Chowdary
#RegisterNumber: 21001700
import numpy as np
a=np.array ([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
~~~
## Output:
![OUTPUT](/IMAGES/img3.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
