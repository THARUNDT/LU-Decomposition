# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy model to use the built in functions for calculation
2. Prepare the list from each linear euation and assign in np.array()
3. Using the scipy.linalg and import lu_factor and lu_solve we get the value 
4. End the program

## Program:
(i) To find the L and U matrix
# Program to find L and U matrix using LU decomposition.
# Developed by:  THARUN D 
# RegisterNumber: 23013993
~~~
import numpy as np
import scipy
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
~~~
(ii) To find the LU Decomposition of a matrix
# Program to solve a matrix using LU decomposition.
# Developed by: THARUN D
# RegisterNumber: 23013993 
~~~
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
~~~
## Output:
![Screenshot 2024-01-01 114220](https://github.com/THARUNDT/LU-Decomposition/assets/144871537/b8e634d2-91f7-4a38-8bc3-f5e5dfed0b5d)
![Screenshot 2024-01-01 114236](https://github.com/THARUNDT/LU-Decomposition/assets/144871537/8f7604e4-92cb-4866-bfbc-48043ba628e0)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

