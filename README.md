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
#program to find the 1-Norm of a matrix and display the results in two decimal places.
#Developed by: Chandrasekar S
#Register Number: 212222230025

import numpy as np

mat= np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```



# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Chandrasekar S
RegisterNumber: 212222230025
'''
import numpy as np
mat= np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```



# Infinity Norm of a Matrix
```
#program to find the Infinity of a matrix and display the result in two decimal places.
#Developed by: Chandrasekar S
#Register No: 212222230025


import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
## 1-Norm of a Matrix
![image](https://github.com/ChandrasekarS22008273/Norm-of-a-matrix/assets/119643845/b8416d83-4c17-4a73-bfed-a76031eca32a)


## 2-Norm of a Matrix
![image](https://github.com/ChandrasekarS22008273/Norm-of-a-matrix/assets/119643845/8b144189-3c3f-4c96-a81b-81cce6a22a7a)

## Infinity Norm of a Matrix
![image](https://github.com/ChandrasekarS22008273/Norm-of-a-matrix/assets/119643845/17b1723f-31bc-423d-be71-ab91dee2b86a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
