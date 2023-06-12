# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Import numpy library using import statement.

### Step 2:
From scipy package import lu().

### Step 3:
Get input from user and pass it as an array.

### Step 4:
Get P, L, U matrix using lu()

### Step 5:
Print L and U matrix

## Program:
```
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: JAVITH M 
RegisterNumber: 212222110014
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
```
Program to solve a matrix using LU decomposition.
Developed by: JAVITH M 
RegisterNumber: 212222110014
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
![1](https://github.com/JavithMohamad/LU-Decomposition/assets/121215951/8119f224-8c4d-498e-aaa7-1a84614194b2)
![2](https://github.com/JavithMohamad/LU-Decomposition/assets/121215951/96af596d-59b8-4744-bf44-b826345b3d41)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
