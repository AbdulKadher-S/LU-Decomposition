# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program. 

2.Read the input matrix A and (if required) matrix B.

3. Perform LU decomposition on matrix A to obtain L and U, and use them to solve AX = B.

4. Display the matrices L, U and the solution matrix X, then stop.

## Program:
(i) To find the L and U matrix
```python
Developed by: Abdul Kadher S                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              
RegisterNumber: 212225230002
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python

Developed by: Abdul Kadher S
RegisterNumber: 212225230002


import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

```

## Output:
<img width="1289" height="752" alt="AdobeExpressPhotos_b1efc63f63254483be8c0dda3331b615_CopyEdited" src="https://github.com/user-attachments/assets/b7816853-a460-4572-aab9-f987d9274779" />
<img width="1295" height="559" alt="AdobeExpressPhotos_379a4d12cdfa4235b073710a6824f747_CopyEdited" src="https://github.com/user-attachments/assets/b362ab9c-1820-4300-8d81-f73dc5d1c1a0" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

