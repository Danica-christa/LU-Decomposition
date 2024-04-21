# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Take values fron user
3. Write the code without any error
4. End the program


## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:Danica Christa
RegisterNumber:212223240022

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
Developed by:Danica Christa 
RegisterNumber:212223240022

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

```

## Output:

![alt text](<Screenshot 2024-04-21 183632.png>)

![alt text](<Screenshot 2024-04-21 183601.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

