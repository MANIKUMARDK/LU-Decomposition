# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'


## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: manikumar d.k
RegisterNumber: 212223230121

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
Developed by: manikumar d.k
RegisterNumber: 212223230121

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

# To print X matrix (solution to the equations)
import numpy as np



# To print X matrix (solution to the equations)
import numpy as np


```

## Output:
![Screenshot 2024-04-07 110438](https://github.com/MANIKUMARDK/LU-Decomposition/assets/147215581/2089f136-1d42-45ff-9ae3-073eef509f08)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

