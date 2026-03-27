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
# Register No: Naresh J
# Developed By: 212225230195
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
<br><img width="1221" height="815" alt="Screenshot 2026-03-27 142838" src="https://github.com/user-attachments/assets/4d438b87-a337-42ab-8fae-706aba9722f4" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1185" height="862" alt="Screenshot 2026-03-27 143339" src="https://github.com/user-attachments/assets/c45a8a0c-fc61-4151-aea9-01c5140a47bd" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="998" height="784" alt="image" src="https://github.com/user-attachments/assets/ffd0120f-6590-4773-bdc5-393c8d85ebdb" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
