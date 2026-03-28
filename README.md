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
# Register No:212225220121
# Developed By:vishal sb
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1163" height="833" alt="image" src="https://github.com/user-attachments/assets/db784dfe-e718-4707-9f69-773fd208dc7f" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1273" height="816" alt="Screenshot 2026-03-28 132732" src="https://github.com/user-attachments/assets/5288ebda-54f7-4124-b128-7f85f86952a7" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1238" height="829" alt="Screenshot 2026-03-28 132800" src="https://github.com/user-attachments/assets/819e2bec-6695-41f6-bc00-2e8a0ff21c50" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
