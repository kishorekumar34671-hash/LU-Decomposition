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
Developed by: KISHORE KUMAR B 
RegisterNumber: 25007664
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
Developed by: KISHORE KUMAR B
RegisterNumber: 25007664 
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
<img width="1356" height="686" alt="image" src="https://github.com/user-attachments/assets/a2b8e6b2-d4f8-4171-8c75-85620168dac4" />
<img width="1157" height="726" alt="image" src="https://github.com/user-attachments/assets/29a9036f-794b-4a48-8f67-dccb1a6f8248" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

