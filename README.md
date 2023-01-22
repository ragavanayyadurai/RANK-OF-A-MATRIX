# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import numpy as np
### Step 2:
Assignin np.array() in rank of matrix.
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Print the value and end the program. 
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Ragavendran A
#RegisterNumber: 22008885
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(a)
print(rank)
```
## Output:
![output](output.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

