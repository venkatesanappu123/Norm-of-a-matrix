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
# Register No:
# Developed By:
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
a="{:.2f}".format(ans)
print(a)
```


# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
a="{:.2f}".format(ans)
print(a)
```






## Output:
### 1-Norm of a Matrix ![Screenshot 2024-12-11 163752](https://github.com/user-attachments/assets/af3f73f0-86d6-4453-9a32-52b8a0e1ced5)

<br>
<br>
<br>

### 2-Norm of a Matrix ![Screenshot 2024-12-11 163917](https://github.com/user-attachments/assets/b168f1cc-6093-41ef-835a-573543a8f12f)

<br>
<br>
<br>

### Infinity Norm of a Matrix ![Screenshot 2024-12-11 163952](https://github.com/user-attachments/assets/c9edcc82-4559-49bf-b38e-b80f2e0db142)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
