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
Python
# Register No: 212224230231
# Developed By: RITHIKA L
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
# Program to find 2-norm of a matrix.
# Developed by: Rithika L
# RegisterNumber: 21222423023
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
# Program to find 2-norm of a matrix.
# Developed by: Rithika L
# RegisterNumber: 21222423023
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/5a1f0cc1-331e-45c9-a4c2-30b8e7c57a43)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/38b5ffcc-dfc6-47a4-9e7c-ca712fee7e56)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/8f2b7bf7-7593-4d24-b7d1-f0400737f266)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
