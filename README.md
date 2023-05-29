# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## To find L and U matrix
1. Import numpy as np.
2. Import lu from scipy.linalg.
3. Declare the array as A.
4. Assign P,L,U (Pivot matrix,L matrix and U matrix) to lu of A.
5. Print L and U
## To find the LU Decomposition of a matrix
1. Import numpy as np.
2. Import lu_factor and lu_solve from scipy.linalg.
3. Get the input of A and B matrix.
4. Assign lu and piv (lu and Pivot matrix) to lu_factor of A.
5. Assign x to lu_solve of lu and piv with B and print x. 

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: ABINAYA S
RegisterNumber: 212222230002
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
Developed by: ABINAYA S
RegisterNumber: 212222230002
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input()) 
b=eval(input())
lu, piv = lu_factor(A)
x = lu_solve((lu,piv), b)
print(x)


```

## Output:
![L and U matrix](https://github.com/abinayasangeetha/LU-Decomposition/assets/119393675/ebe52402-cd96-4eb0-91f7-d7009d272b92)
![LU matrix](https://github.com/abinayasangeetha/LU-Decomposition/assets/119393675/a394e2fb-c1bd-40a6-be94-2f70763777ae)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

