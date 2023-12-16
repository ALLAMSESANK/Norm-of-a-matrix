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
# Register No:23009543
# Developed By:A.Sesank
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat ,1)
norm_of_matrix ="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: A.Sesank
RegisterNumber: 23009543
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat ,2)
norm_of_matrix ="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix ="{:.2f}".format(ans)
print(norm_of_matrix)





```


### 1-Norm of a Matrix
![image](https://github.com/ALLAMSESANK/Norm-of-a-matrix/assets/147120920/d73b8f1e-bb70-488c-adf3-1c0b92a457a0)

### 2-Norm of a Matrix
![image](https://github.com/ALLAMSESANK/Norm-of-a-matrix/assets/147120920/748ef468-bc76-47fb-a24e-a65aee029e3a)

### Infinity Norm of a Matrix
![image](https://github.com/ALLAMSESANK/Norm-of-a-matrix/assets/147120920/f14ea6f9-4012-4478-888d-26aeceec23c0)

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
