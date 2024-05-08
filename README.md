# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy library using import statement.
2.From scipy package import lu().
3.Get input from user and pass it as an array.
4.Get P, L U martix using lu().
5.print L and U matrix.

## Program:
(i) To find the L and U matrix
```
/*
# Program to find the L and U matrix.
# Developed by: DILLIARASU M
# RegisterNumber: 212223230049
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
# Program to find the LU Decomposition of a matrix.
# Developed by: DILLIARASU M
# RegisterNumber: 212223230049
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu, piv = lu_factor(A)
x= lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![Screenshot 2024-05-09 001449](https://github.com/Dilliarasu0105/LU-Decomposition/assets/144979593/adcc73db-b90a-4a80-8aed-9d63ce5780e1)

![Screenshot 2024-05-09 001509](https://github.com/Dilliarasu0105/LU-Decomposition/assets/144979593/42fa47c3-8e44-4895-bd1e-49400a95749a)

![Screenshot 2024-05-09 001527](https://github.com/Dilliarasu0105/LU-Decomposition/assets/144979593/1e9edb90-d191-4c23-a811-63b6242976e9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

