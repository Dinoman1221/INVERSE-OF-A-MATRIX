# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from the matrix and assign in np.array()

Step 3:
Use the np.linalg.inv() fun

Step 4:
End the program. 

## Program:

#Program to find the inverse of a matrix.

#Developed by: Ashish S

#RegisterNumber: 212224240017

```
import numpy as np
A = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])
try:
    A_inv = np.linalg.inv(A)
    print(A_inv)
except np.linalg.LinAlgError:
    print("Matrix is singular and cannot be inverted.")
```
## Output:
![image](https://github.com/user-attachments/assets/82450931-09c1-4ab7-a518-b3e923b97aad)

## Result:
Thus the inverse of given matrix is successfully solved using python program

