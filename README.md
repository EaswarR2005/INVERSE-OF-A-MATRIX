# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
 In first step,we import Numpy library and alias it as 'np'.
### Step 2: 
we define 3x3 matrix 'a' using a nested list.
### Step 3: 
we use the np.linalg.inv function to calculate the inverse of a matrix'a'.Store the result in a variable 'b'.
### Step 4: 
We print the inverse matrix 'b' to the console.
### Step 5:
End the program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: EASWAR R
#RegisterNumber: 212223230053
import numpy as np
matrix=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(matrix)
print(result)
```
## Output:
![image](https://github.com/EaswarR2005/INVERSE-OF-A-MATRIX/assets/146931525/81f3b68d-ac10-426b-9bbb-8d3685a7bdac)
![image](https://github.com/EaswarR2005/INVERSE-OF-A-MATRIX/assets/146931525/e37916ff-550f-4eab-b71d-46a4cb7c90f3)

## Result:
Thus the inverse of given matrix is successfully solved using python program

