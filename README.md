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
# Register No: 212222240117
# Developed By: Yamunaasri T S
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,1)
print("%.2f"%sol)


# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,2)
print("%.2f"%sol)



# Infinity Norm of a Matrix


import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,np.inf)
print("%.2f"%sol)


```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-06-03 114609](https://github.com/Yamunaasri/Norm-of-a-matrix/assets/115707860/04502744-30d3-48e5-b8dd-7761af00f213)


### 2-Norm of a Matrix

![Screenshot 2023-06-03 114641](https://github.com/Yamunaasri/Norm-of-a-matrix/assets/115707860/74067214-85c6-4f15-9c61-ac6f2e6afb03)


### Infinity Norm of a Matrix

![Screenshot 2023-06-03 114710](https://github.com/Yamunaasri/Norm-of-a-matrix/assets/115707860/e6f5c1f2-6dd6-4d4f-8854-e129d97018de)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
