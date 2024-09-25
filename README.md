# EX-05-LU Decomposition 
# DATE:
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 
 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: G LEKA SRI
RegisterNumber: 212223100025

'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
*/
```


(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: G LEKA SRI
RegisterNumber: 212223100025
'''
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
![Screenshot 2024-09-25 193825](https://github.com/user-attachments/assets/83a47547-8d91-48c9-a2a0-3c0814d4ed71)

![Screenshot 2024-09-25 193844](https://github.com/user-attachments/assets/c73b17ef-01c7-41b1-99e1-25e3fc53d646)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

