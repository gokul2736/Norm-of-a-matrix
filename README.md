![image](https://github.com/user-attachments/assets/9a0b2b61-0ce3-41e5-a8d9-af89cd2972f8)# Norm of a matrix
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
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
norm="{:.2f}".format(sol)
print(norm)

# 2-Norm of a Matrix

import numpy as np
a=([[1,2],[3,4]])
b=([[-1, 3],[3, -4],[1, 7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,2)
norm="{:.2f}".format(sol)
print(norm)

# Infinity Norm of a Matrix

import numpy as np
arr=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(sol)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e31fd9c2-38b9-4265-89c0-6e03237fb156)

<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/5c1c12f1-060c-47af-9fbb-498bb7ff557c)

<br>
<br>
<br>

### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/c5d42ee6-e4bb-4a3e-baf2-3801b57dca4d)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
