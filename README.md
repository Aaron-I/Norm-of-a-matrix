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
# 1-Norm of a 
# Developed by: AARON I
# RegisterNumber: 23002289

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
# 2-Norm of a Matrix
# Developed by: AARON I
# RegisterNumber: 23002289

import numpy as np

# Type your code here
import numpy as np
n=np.array(eval(input()))
mat=np.linalg.norm(n,2)
ans="{:.2f}".format(mat)
print(ans)
```
```
# Infinity Norm of a Matrix
# Developed by:AARON I
# Register number:23002289

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
![output](/Screenshot%202023-07-26%20212603.png)
![output](/Screenshot%202023-07-26%20212823.png)
![output](/Screenshot%202023-07-26%20213031.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
