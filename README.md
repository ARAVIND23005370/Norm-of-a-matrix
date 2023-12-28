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
# Register No:ARAVIND R
# Developed By:23005370

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-28 214645](https://github.com/ARAVIND23005370/Norm-of-a-matrix/assets/148514836/807776cd-a36b-4939-adde-19e7dbf12010)


### 2-Norm of a Matrix

![Screenshot 2023-12-28 214653](https://github.com/ARAVIND23005370/Norm-of-a-matrix/assets/148514836/f4f71818-951a-4577-aad7-4bce4baeed49)

### Infinity Norm of a Matrix
![Screenshot 2023-12-28 214701](https://github.com/ARAVIND23005370/Norm-of-a-matrix/assets/148514836/e8467a5e-2a08-4b80-8c49-4c2a6a1d2822)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
