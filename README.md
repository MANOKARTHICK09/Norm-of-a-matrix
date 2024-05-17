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
# Register No: 212222230077
# Developed By: MANO KARTHICK S
# 1-Norm of a Matrix



Program to find 1-norm of a matrix.
Developed by: MANOKARTHICK S
RegisterNumber: 212222230077
```
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: MANOKARTHICK S
RegisterNumber: 212222230077
```
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# Infinity Norm of a Matrix
'''
Program to find Infinity norm of a matrix.
Developed by: MANOKARTHICK S
RegisterNumber: 212222230077
'''
```
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/MANOKARTHICK09/Norm-of-a-matrix/assets/121785458/ff438b5d-538d-4edb-a1f0-5a053be8006d)


### 2-Norm of a Matrix
![image](https://github.com/MANOKARTHICK09/Norm-of-a-matrix/assets/121785458/d4ebd053-a795-4a6b-9cf8-3ca4ca9fd737)

### Infinity Norm of a Matrix
![image](https://github.com/MANOKARTHICK09/Norm-of-a-matrix/assets/121785458/4bf0cde4-2ab0-467a-bcdf-4292ebccb4c7)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
