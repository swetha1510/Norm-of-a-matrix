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
```
# Register No:22008542
# Developed By:SWETHA P

# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![norm1mat](https://user-images.githubusercontent.com/120623583/215278248-98ba578d-c845-4d0e-b9fc-c60669802b06.png)


### 2-Norm of a Matrix
![norm2mat](https://user-images.githubusercontent.com/120623583/215278252-aa74b7a5-4753-4c36-81d7-638e356598a9.png)


### Infinity Norm of a Matrix
![norminfmat](https://user-images.githubusercontent.com/120623583/215278256-b611a2e9-9684-45f1-9f00-78eb68abb81a.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
