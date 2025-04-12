# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 Step 1.
import numpy as np

Step 2:
from scipy package import lu

Step 3:
get input from the user

Step 4:
print result 


## Program:
(i) To find the L and U matrix
```
'''
Program to find L and U matrix using LU decomposition.
Developed by: Gokul S
RegisterNumber: 212224240044
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: Gokul S
RegisterNumber: 212224240044
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)

```

## Output:
![lu decomposition]()
![Screenshot 2025-04-12 134251](https://github.com/user-attachments/assets/8247fd0d-f34e-456b-b104-b41ac1736090)
![Screenshot 2025-04-12 134314](https://github.com/user-attachments/assets/4bd4b951-865a-4f6b-981f-55ebfa1983ac)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

