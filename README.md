# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner



## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: M Himavath
RegisterNumber: 23010121
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: M Himavath
RegisterNumber:23010121 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
X=lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
1)
  ![image](https://github.com/Himavath08/LU-Decomposition/assets/139110631/d15e8c35-0e65-41d8-a695-ff181c2ef11f)

2)
   ![Screenshot 2023-12-13 135953](https://github.com/Himavath08/LU-Decomposition/assets/139110631/2e2482b1-80d8-4c1e-a6ca-8c96d5d38cad)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

