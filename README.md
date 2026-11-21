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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A = np.array(eval(input()))
norm1= np.linalg.norm(A,1)
norm= "{:.2f}".format (norm1)
print(norm)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Ashwanth Bala SB
RegisterNumber: 26008307
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A= np.array(eval(input()))
norm1=np.linalg.norm(A,2)
norm="{:.2f}".format(norm1)
print(norm)


# Infinity Norm of a Matrix


'''
Program to find 2-norm of a matrix.
Developed by: Ashwanth Bala SB
RegisterNumber: 26008307
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A= np.array(eval(input()))
norm1=np.linalg.norm(A,2)
norm="{:.2f}".format(norm1)
print(norm)


```
## Output:
### 1-Norm of a Matrix
<img width="1427" height="802" alt="Screenshot 2026-11-21 081125" src="https://github.com/user-attachments/assets/63e418e7-ea21-4009-b209-0a139574c62e" />

### 2-Norm of a Matrix
<img width="1442" height="860" alt="Screenshot 2026-11-21 081147" src="https://github.com/user-attachments/assets/6cf2ea79-fe07-47f7-a4f8-835b7d7e9713" />

### Infinity Norm of a Matrix
<img width="1398" height="847" alt="Screenshot 2026-11-21 081202" src="https://github.com/user-attachments/assets/e17c0e79-d61d-4e6e-b35f-34e81caedbe8" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
