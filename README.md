# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.  Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create thevariable as 'X' include the package in that variable.
4.  print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: selva kumar A
RegisterNumber: 22009007

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: selva Kumar
RegisterNumber: 2200900
To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
file:///home/sec/Pictures/Screefile:///home/sec/Pictures/Screenshots/Screenshot%20from%202023-01-12%2021-56-57.png![image](https://user-images.githubusercontent.com/120643262/212226478-51322ff2-e9f0-4537-a8d5-2d9c63b35d33.png)
nshots/Screenshot%20from%202023-01-12%2021-56-25.png![image](https://user-images.githubusercontent.com/120643262/212226382-e67314cb-6295-45aa-ad61-1fa84733a9e0.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

