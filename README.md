# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm: 
Algorithm: To Find the 1-Norm of a Matrix

Step 1:
Import the required modules os and numpy, and set the environment variable to limit thread usage.

Step 2:
Read the input matrix from the user and convert it into a NumPy array using np.array().

Step 3:
Compute the 1-norm of the matrix using np.linalg.norm(a, 1).

Step 4:
Display the result in formatted output with 2 decimal places.

Algorithm: To Find the 2-Norm of a Matrix

Step 1: Import the required libraries (os and numpy) and set the environment variable to limit thread usage.

Step 2: Read the input from the user and convert it into a NumPy array using np.array().

Step 3: Compute the 2-norm (Euclidean norm) of the array using np.linalg.norm(a, 2).

Step 4: Format and print the result up to 2 decimal places.


Algorithm: To Find the Infinity-Norm of a Matrix


Step 1: Import the required libraries (os and numpy) and set the environment variable to control thread usage.

Step 2: Accept the matrix input from the user and convert it into a NumPy array using np.array().

Step 3: Compute the infinity norm of the matrix using np.linalg.norm(mat, np.inf) (maximum row sum).

Step 4: Format the result to 2 decimal places and print the infinity norm of the matrix.



	
## Program:
Python
# Register No:212225230169

# Developed By:MARY AKSHARA S

# 1-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,1):2f}") 
```



# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,2):2f}") 
```




# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix) 
```





## Output:
### 1-Norm of a Matrix
<img width="1912" height="1074" alt="Screenshot 2026-03-27 190110" src="https://github.com/user-attachments/assets/1cce8eea-50f2-41da-874e-7bd7f157e6c0" />


### 2-Norm of a Matrix
<img width="1919" height="1079" alt="Screenshot 2026-03-27 190128" src="https://github.com/user-attachments/assets/93bb5f7f-27de-406e-8608-a68997e54e31" />


### Infinity Norm of a Matrix
<img width="1917" height="1079" alt="Screenshot 2026-03-27 190153" src="https://github.com/user-attachments/assets/71aa79a2-c93d-49a2-a0f8-c343a47ca642" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
