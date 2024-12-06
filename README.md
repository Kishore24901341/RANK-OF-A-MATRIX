# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program
## Program:
```
import numpy as np

a = np.array([[1, 2, 3], [3, 6, 9]])

solution = np.linalg.matrix_rank(a)

print(solution)
```
## Output:
![image](https://github.com/user-attachments/assets/ec78ac69-05d8-4443-ac61-8445a39bd68a)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

