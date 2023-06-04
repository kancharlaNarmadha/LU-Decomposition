# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm


1. Import the numpy module to use the built-in functions for calculation

2. Prepare the lists from each linear equations and assign in np.array()

3. Using the np.linalg.solve(), we can find the solutions.

4. End the program

## Program:
# (i) To find the L and U matrix


# Program to find L and U matrix using LU decomposition.

Developed by: KANCHARLA NARMADHA

RegisterNumber: 212222110016

```
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
# (ii) To find the LU Decomposition of a matrix

# Program to find the LU Decomposition of a matrix.

Developed by: KANCHARLA NARMADHA

RegisterNumber: 21222110016

```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:

![mat ouput 5 1](https://github.com/kancharlaNarmadha/LU-Decomposition/assets/119559316/f37771df-8b49-4df3-8e2b-b2ed4f4d7a56)

![mat output 5 2](https://github.com/kancharlaNarmadha/LU-Decomposition/assets/119559316/4a350378-bbce-4489-a0bf-61b00a886a83)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

