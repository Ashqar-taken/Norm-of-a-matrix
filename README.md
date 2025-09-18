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
# Register No: 212224240018
# Developed By: Ashqar Ahamed S.T
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="776" height="814" alt="image" src="https://github.com/user-attachments/assets/919a4dad-064f-4af1-a04b-4a73578bf4de" />

### 2-Norm of a Matrix

<img width="746" height="893" alt="image" src="https://github.com/user-attachments/assets/94ee93e0-b1b2-4c33-86d9-a72ddb41bfc0" />

### Infinity Norm of a Matrix

<img width="656" height="780" alt="image" src="https://github.com/user-attachments/assets/b67270bc-6cbe-421c-aae6-aa2e563205b1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
