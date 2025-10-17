# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2.  Prepare the lists from each linear equations and assign in np.array(
3. Using the np.linalg.lu(), we get two results (first is L and second is
 U) of the given matrix.
4. Using the np.linalg.lu_factor() and np.linalg.lu_solve(), we get the solution
5. End the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: import numpy as np
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
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
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
<img width="1191" height="437" alt="Screenshot 2025-10-17 103053" src="https://github.com/user-attachments/assets/ccaabfc1-a4b8-4044-9ace-43f3b06282d4" />

<img width="878" height="188" alt="Screenshot 2025-10-17 103136" src="https://github.com/user-attachments/assets/f79a5c1e-cb1f-4353-9298-2cbb0ee5f0d1" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

