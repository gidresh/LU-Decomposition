# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program 
2.Import the necessary libraries(numpy,scipy.linalg) 
3.Define the matrix using numpy 
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:idrish 
RegisterNumber:26019128 
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,L,U=lu(a)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:idrish 
RegisterNumber:26019128 
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1404" height="486" alt="{531B1BEC-E69D-4AAE-BA86-956016AC8D75}" src="https://github.com/user-attachments/assets/d6f9946b-cfb5-4503-8ccb-d27b8260dd6d" />
<img width="1273" height="567" alt="{8B3C77D4-736C-4275-8EBD-E1F10C3C86EB}" src="https://github.com/user-attachments/assets/27b2807a-0d6d-4e32-a8d6-389662300e01" />
<img width="1396" height="816" alt="{4FBEF786-6034-43EB-B0FB-31E02C386531}" src="https://github.com/user-attachments/assets/37a17705-928a-492a-ab25-6ff1ad452e64" />
<img width="1286" height="356" alt="{6EE7914B-97FD-42F3-89BB-07D0C3383705}" src="https://github.com/user-attachments/assets/f2159465-1df9-4ce2-b2b8-c545e1b2c4b6" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

