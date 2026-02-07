# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Mahema A
RegisterNumber: 25015417
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Mahema A
RegisterNumber: 25015417
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

```

## Output:

<img width="1920" height="1080" alt="Screenshot (156)" src="https://github.com/user-attachments/assets/f60b3a97-3c83-4556-b9b8-deb9608764db" />
<img width="1920" height="1080" alt="Screenshot (157)" src="https://github.com/user-attachments/assets/4e5e51d5-b132-4f90-8ce4-bb3d2e7bca43" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

