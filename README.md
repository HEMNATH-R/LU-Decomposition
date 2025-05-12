# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the 
 package in that variable
4. print the variable 'X'


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: HEMNATH R
RegisterNumber: 212224240057
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u) 

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: HEMNATH R 
RegisterNumber: 212224240057
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
piv,lu=lu_factor(a)
result=lu_solve((piv,lu),b)
print(result) 

```

## Output:


![alt text](<Screenshot 2025-05-12 203637.png>)
![alt text](<Screenshot 2025-05-12 203655.png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

