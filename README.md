# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

# 1-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Gowtham V
RegisterNumber: 212223100009 
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Gowtham V
RegisterNumber: 212223100009 
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```
# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Gowtham V
RegisterNumber: 212223100009 
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Gowtham-jk/Norm-of-a-matrix/assets/149857834/6f7cbda1-77ca-44fa-bf97-244e6d8ad278)


### 2-Norm of a Matrix
![image](https://github.com/Gowtham-jk/Norm-of-a-matrix/assets/149857834/8cd47939-9d8c-45d0-bb5b-1a51c08777a5)


### Infinity Norm of a Matrix
![image](https://github.com/Gowtham-jk/Norm-of-a-matrix/assets/149857834/fc95103e-c439-4d22-bdc5-55dd0542eeb1)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
