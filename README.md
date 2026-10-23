# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
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
RegisterNumber: 26019128
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
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
~~~
## Output:
<img width="1426" height="538" alt="{DD240866-601E-43A9-A4F5-A43FC9F3166E}" src="https://github.com/user-attachments/assets/15be7d91-b959-467d-b872-78e881d116c3" />
<img width="1438" height="550" alt="{2D83A9E1-05F2-40EE-B8D0-C7D2AFB298A2}" src="https://github.com/user-attachments/assets/00830dfe-f4a5-49f6-9b24-ee241b1e20f1" />
<img width="1394" height="532" alt="{B77944EE-077D-4356-8887-3380367F8787}" src="https://github.com/user-attachments/assets/763aee1a-38cc-4eee-a046-d58a10726662" />
<img width="1096" height="328" alt="{2F41D71F-8AEB-4FF5-9A03-CA103E201AA9}" src="https://github.com/user-attachments/assets/ce03b5e0-53c6-4fc8-8746-f79da7704957" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

