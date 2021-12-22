# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. To start the program.
2. import the numpy as np
3. Using the scipy.linalg lu
4. Enter the elements of the given matrix.
5. Display the output of the program.

## Program1:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Mothesh M
RegisterNumber: 21006007
*/
```
import numpy as np

from scipy.linalg import lu

#import scipy

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

## Program2:
```
/*
Program to find the LU Decomposition of a matrix.

Developed by: Mothesh M

RegisterNumber: 21006007
*/
```
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,pivot=lu_factor(A)

x=lu_solve((lu,pivot),B)

print(x)

## Output1:
![lu1](https://user-images.githubusercontent.com/94170892/147044793-5851e370-42c7-4e0d-b564-f2da9103e61b.png)

## Output2:
![lu2](https://user-images.githubusercontent.com/94170892/147044978-0ade3486-8f94-4b7f-8933-b9fa4c6442ad.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

