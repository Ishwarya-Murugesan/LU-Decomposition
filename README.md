# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Input the Matrix (A, B)
2. Perform LU Decomposition
3. Factorization for Solving
4. Solve the System

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:ISHWARYA M 
RegisterNumber: 212225230107
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: ISHWARYA M
RegisterNumber: 212225230107
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy .linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
```

## Output:
![alt text](<Screenshot 2026-02-14 105345.png>)
![alt text](<Screenshot 2026-02-14 105405.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

