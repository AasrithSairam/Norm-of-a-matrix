# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm, and infinity norm of the matrix and display the result in two decimal places.
## Equipments required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 1,2 or infinity norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 23007809
# Developed By: ponguru aasrith sairam

# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,1)
ans="{:.2f}".format(norm)
print(ans)


# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,2)
ans="{:.2f}".format(norm)
print(ans)


# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,np.inf)
ans="{:.2f}".format(norm)
print(ans)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/AasrithSairam/Norm-of-a-matrix/assets/139331438/16104500-8e90-4549-8a84-983ad73486f9)


### 2-Norm of a Matrix
![image](https://github.com/AasrithSairam/Norm-of-a-matrix/assets/139331438/c5fa4ff6-31ed-4303-a861-b7fcd29a6697)


### Infinity Norm of a Matrix
![image](https://github.com/AasrithSairam/Norm-of-a-matrix/assets/139331438/9f11b00a-a747-4c20-836a-88e2a8cca319)


## Result
Thus the program for 1-norm, 2-norm, and Infinity norm of a matrix are written and verified.
