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
# Register No:212225230245
# Developed By:SANJAI K
# 1-Norm of a Matrix
'''
Program to find 1 norm
Developed BY: SANJAI K
Register Number:212225230245
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=eval(input())
norm=np.linalg.norm(A,1)
print(norm)



# 2-Norm of a Matrix


'''
Program to find 2-norm of a matrix.
Developed by: SANJAI K
RegisterNumber: 212225230245
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")

# Infinity Norm of a Matrix
'''
Program to find infinity norm
Developed by:SANJAI K
Register Number: 212225230245
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm)




```
## Output:
### 1-Norm of a Matrix
[output](Screenshot%202026-03-23%20153117.png)

### 2-Norm of a Matrix

[output](Screenshot%202026-03-23%20153133.png)
### Infinity Norm of a Matrix

[output](Screenshot%202026-03-23%20153234.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
