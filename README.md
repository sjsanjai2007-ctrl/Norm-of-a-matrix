# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```Python
# Register No:
# Developed By:
# Register No: 212225040365
# Developed By: SANJAI S J
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SANJAI S J
RegisterNumber: 212225040365
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SANJAI S J
RegisterNumber: 212225040365
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="627" height="197" alt="image" src="https://github.com/user-attachments/assets/4c81e893-db14-4cc2-af01-fcc018078851" />

### 2-Norm of a Matrix

<img width="628" height="243" alt="image" src="https://github.com/user-attachments/assets/29df9555-2134-4931-b62a-2a562f0a0700" />


### Infinity Norm of a Matrix

<img width="755" height="187" alt="image" src="https://github.com/user-attachments/assets/d680acd2-0fef-4d0d-8467-246a4b035921" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
