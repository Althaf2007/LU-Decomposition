# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program

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

![Screenshot 2025-04-12 133056](https://github.com/user-attachments/assets/ba57ac2b-3b6c-4ac1-904d-42d20cc882e9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

