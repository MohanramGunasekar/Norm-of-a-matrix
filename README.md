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
# Register No:212223240095
# Developed By:Mohanram Gunasekar
# 1-Norm of a Matrix
'''
Program to find the 1-norm of a matrix.
Developed by:Mohanram Gunasekar
RegisterNumber:212223240095
'''
import numpy as np

matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:Mohanram Gunasekar
RegisterNumber: 212223240095
'''
import numpy as np

matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))





# Infinity Norm of a Matrix
'''
Program to find infinity-norm of a matrix
Developed by:Mohanram Gunasekar
RegisterNumber:212223240095
'''
import numpy as np

matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 112209](https://github.com/MohanramGunasekar/Norm-of-a-matrix/assets/139841812/1f9905dc-1a20-4a4b-b068-cd2a0bc7f8da)


### 2-Norm of a Matrix
![Screenshot 2024-04-23 112222](https://github.com/MohanramGunasekar/Norm-of-a-matrix/assets/139841812/8129e126-07a9-46b7-9796-f9ebd483eff4)


### Infinity Norm of a Matrix
![Screenshot 2024-04-23 112240](https://github.com/MohanramGunasekar/Norm-of-a-matrix/assets/139841812/223a4d58-51c3-4ea1-bf05-b99535bc7b7a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
