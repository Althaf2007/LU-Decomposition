# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1:
Import lu(),lu_factor() and lu_solve() from scipy.linalg library
### Step 2:
Use lu() method to find lower and upper matrix.
### Step 3:
Use lu_factor() and lu_solve to solve the two matrixes.
### Step 4:
End the program.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: K.Mohamed Althaf
RegisterNumber: 212224240089
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: K.Mohamed Althaf
RegisterNumber: 212224240089
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print (x)
```
## Output:
(i) To find the L and U matrix
![Screenshot 2025-04-12 133034](https://github.com/user-attachments/assets/3b556a21-9e97-4677-99ea-d89367cb4a68)
(ii) To find the LU Decomposition of a matrix
![Screenshot 2025-04-22 080054](https://github.com/user-attachments/assets/98ee8180-d439-48fc-9865-b110b93664df)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

