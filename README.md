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

<img width="745" height="331" alt="image" src="https://github.com/user-attachments/assets/01313e8c-905a-45d2-b99a-ab6ac25cf6a2" />

```
'''Program to find L and U matrix using LU decomposition.
Developed by: Mohamed Asad S
RegisterNumber: 212225040238
'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix

<img width="633" height="221" alt="image" src="https://github.com/user-attachments/assets/3c22d992-6a0f-4ea9-8448-a91e25582696" />

```
'''Program to solve a matrix using LU decomposition.
Developed by: Mohamed Asad S
RegisterNumber: 212225040238
'''

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,p=lu_factor(A)
x=lu_solve((lu,p),B)
print(x)

```

## Output:

(i)

<img width="1191" height="451" alt="image" src="https://github.com/user-attachments/assets/3cd47130-64d5-42a5-9abb-3ea0c693aa7c" />


(ii)

<img width="930" height="181" alt="image" src="https://github.com/user-attachments/assets/29fce789-1fad-4c40-a406-23d754dfe925" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

