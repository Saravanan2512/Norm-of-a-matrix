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
#Register No:23005445
#Develop By: SARAVANAN G
#1-Norm of a Matrix 
import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
# Type your code here



# Infinity Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Saravanan2512/Norm-of-a-matrix/assets/144979117/2285449a-ca9e-4633-b735-458b43378048)


### 2-Norm of a Matrix
![image](https://github.com/Saravanan2512/Norm-of-a-matrix/assets/144979117/8cc88581-d4da-4637-aafc-ac9914b6db6c)


### Infinity Norm of a Matrix
![image](https://github.com/Saravanan2512/Norm-of-a-matrix/assets/144979117/16d4f21d-c815-4fa9-b005-97fa966ad03f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
