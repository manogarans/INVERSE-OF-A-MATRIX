# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the lists from each linear equation and assign in np.array()
### Step 3: 
Using yhe np.linalg.inv(),we can find the inverse of a matrix. 
### Step 4: 
End the program.
## Program:
```python
#Program to find the inverse of a matrix.
#Developed by:MANOGARAN S
#RegisterNumber:23004448
import numpy as np
ques=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result=np.linalg.inv(ques)
print(result)
```
## Output:
![output](/inverse.png.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

