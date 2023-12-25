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

### 1-Norm of a Matrix
```
#Python program to find the 1-Norm of a matrix and display the results in two decimal places.
#Developed by:Bhuvanesh.S.R
#Reg no:212223240017
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```
### 2-Norm of a Matrix
```
#Python program to find 2-norm of a matrix and display the result in two decimal places.
#Developed by:Bhuvanesh.S.R
#Reg no:212223240017
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```
### Infinity Norm of a Matrix
```
#Python program to find the Infinity of a matrix and display the result in two decimal places.
#Developed by:Bhuvanesh.S.R
#Reg no:212223240017
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![1 norm of matric SS](https://github.com/Bhuvanesh-Suresh/Norm-of-a-matrix/assets/145742661/0ae626a7-2813-46ff-8433-4f71568561fe)

### 2-Norm of a Matrix
![2 norm of matric SS](https://github.com/Bhuvanesh-Suresh/Norm-of-a-matrix/assets/145742661/016247cc-4e9e-4beb-90c3-5a6490119305)

### Infinity Norm of a Matrix
![infinity norm of matric SS](https://github.com/Bhuvanesh-Suresh/Norm-of-a-matrix/assets/145742661/501327cd-b5f8-4f01-8023-69301dcf5b05)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
