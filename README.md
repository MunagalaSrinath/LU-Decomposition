# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scripy package import lu_factor() and lu_solve().
3. Get two inputs from user andpasss it as matrix array.
4. Find lu and pivot value of first matrix using lu_factor().
5.Find solution of thematrix by using lu_solve() by passing lu.pivot values as first argument and second matrix as second argument.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:M Srinath 
RegisterNumber:22000990 
'''
import numpy as np
from scipy.linalg import lu
array=eval(input())
A=np.array(array)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: M Srinath
RegisterNumber: 22000990
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)

```

## Output:
![Screenshot from 2023-01-25 23-26-47](https://user-images.githubusercontent.com/118678482/214644373-8906ee16-75ed-4062-94f7-6b734f4daae6.png)


![Screenshot from 2023-01-25 23-27-52](https://user-images.githubusercontent.com/118678482/214644575-67fa32b2-e1de-4f33-9848-54bd16992dbc.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

