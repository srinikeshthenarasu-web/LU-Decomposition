# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: srinikeshh t
RegisterNumber: 212225040427
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)
```

'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1221" height="568" alt="image" src="https://github.com/user-attachments/assets/4d8ab8d6-4d14-45b1-b7cd-77a6eb2ce25a" />
<img width="1218" height="327" alt="image" src="https://github.com/user-attachments/assets/592a104b-70a3-4df0-bf5a-bb71d51f2010" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

