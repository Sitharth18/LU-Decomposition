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
Developed by: Sitharth.B.S
RegisterNumber:212224110048
import numpy as np
from scipy.linalg import lu

A=eval(input())

P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Sitharth.B.S
RegisterNumber: 212224110048
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu, pivot =lu_factor(A)
result = lu_solve((lu,pivot),B)
print(result)
*/
```

## Output:
(i) To find the L and U matrix
<img width="1317" height="893" alt="image" src="https://github.com/user-attachments/assets/fd70a4e6-30e4-4407-bfb9-d335126d9f3c" />
<img width="1500" height="853" alt="image" src="https://github.com/user-attachments/assets/2973abb4-6cf4-4b62-a3b9-fec8c6532fb9" />


(ii) To find the LU Decomposition of a matrix
<img width="1511" height="952" alt="Screenshot 2025-09-22 143342" src="https://github.com/user-attachments/assets/60fe9574-ee1e-41b2-84a1-6099efd3a06a" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

