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
# Register No:212225240038
# Developed By:DWIJESH RAJ SINHA Y
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:.2f}".format(ans)
print(n)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
n="{:.2f}".format(ans)
print(n)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
n="{:.2f}".format(ans)
print(n)

```
## Output:
### 1-Norm of a Matrix
<img width="972" height="326" alt="image" src="https://github.com/user-attachments/assets/d8ed24c2-c6b1-4077-8f4a-905d0096f2bd" />

### 2-Norm of a Matrix
<img width="959" height="344" alt="image" src="https://github.com/user-attachments/assets/1d2392b2-6a8f-48de-8a3f-d4d5729954f3" />

### Infinity Norm of a Matrix
<img width="934" height="267" alt="image" src="https://github.com/user-attachments/assets/823bd675-e584-456b-ae01-ba3fb38dc2d5" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
