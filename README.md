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
Developed by: Darius Rijin I
RegisterNumber:212223230037
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Darius Rijin I
RegisterNumber:212223230037
import numpy as np
from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

*/
```

## Output:
![maths 1](https://github.com/DariusRijin07/LU-Decomposition/assets/138849120/c1e53500-dd2e-4638-af2b-0c8799e3976f)

![maths 2](https://github.com/DariusRijin07/LU-Decomposition/assets/138849120/1260a48b-544f-4590-bc05-0338d5214396)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

