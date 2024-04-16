# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# 1.Define the package as scipy.linalg import lu.
# 2.Get input from user and print L and U matrix by 'print' . 
# 3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
# 4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SANTHOSH KUMAR R
RegisterNumber: 212223240153 
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:SANTHOSH KUMAR R
RegisterNumber: 212223240153
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![Screenshot 2024-04-16 191807 ma](https://github.com/23000966/LU-Decomposition/assets/153983364/eaf1c2ab-8913-48a9-a9dc-87ffb74f8d35)

![image](https://github.com/23000966/LU-Decomposition/assets/153983364/c7a2fc4e-de1f-4650-aec9-a7eff3db84d2)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

