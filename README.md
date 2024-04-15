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
# Register No: 212223230020
# Developed By: ARJUN N S
# 1-Norm of a Matrix:
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(two_matrix))

# 2-Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix:

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(two_matrix))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/NSArjun/Norm-of-a-matrix/assets/148233801/4d670d27-aed6-4dea-8122-251c7e37e7ef)


### 2-Norm of a Matrix
![image](https://github.com/NSArjun/Norm-of-a-matrix/assets/148233801/0efde007-00c7-419a-b0de-4e09473df728)



### Infinity Norm of a Matrix:

![image](https://github.com/NSArjun/Norm-of-a-matrix/assets/148233801/b842df42-824e-40c4-8e4c-8c429ca5e644)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
