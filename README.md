# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module to use the build - in functions for calculation
2. prepare the list from each equation and assign the array
3. using the equation , we get two results of the given matrix
4. End The Program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S DEEPIKA
RegisterNumber: 23002257
*/
import numpy as np
from scipy.linalg import lu
A = np.array (eval(input()))
P , L , U = lu(A)
print (L)
print (U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S DEEPIKA
RegisterNumber: 23002257
*/
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A = np.array (eval(input()))
b = np.array (eval(input()))
lu , piv = lu_factor(A)
x = lu_solve((lu , piv), b)
print (x)

```

## Output:
![lu decomposition]()
![image](https://github.com/Deepikasuresh05/LU-Decomposition/assets/148514509/580f332f-405a-4105-a301-5c641d8a8e40)
![image](https://github.com/Deepikasuresh05/LU-Decomposition/assets/148514509/60ba467e-1d3e-4a0f-b625-773163c6c186)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

