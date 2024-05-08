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
```Python
# Register No: 212223230034
# Developed By:CHANDRU SM
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")



# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")



# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-05-09 000533](https://github.com/Chandru0711/Norm-of-a-matrix/assets/144979368/f25e9327-2265-40c4-b8bd-6c3615c2f8a4)

### 2-Norm of a Matrix

![Screenshot 2024-05-09 000645](https://github.com/Chandru0711/Norm-of-a-matrix/assets/144979368/7f1caede-ac79-4197-8097-f5e5839af67e)

### Infinity Norm of a Matrix

![Screenshot 2024-05-09 000659](https://github.com/Chandru0711/Norm-of-a-matrix/assets/144979368/6282e1e5-994a-4086-b2c9-90deae498d82)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
