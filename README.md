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
# 1-Norm of a Matrix
```Python
# Register No: 22006204
# Developed By: SATHISH R
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```


# 2-Norm of a Matrix
```python
# Register No: 22006204
# Developed By: SATHISH R
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```python
# Register No: 22006204
# Developed By: SATHISH R
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![norm1](https://user-images.githubusercontent.com/118787261/213279238-5786d233-1f94-40fd-aacd-2b2d607de38d.png)






### 2-Norm of a Matrix
![norm2](https://user-images.githubusercontent.com/118787261/213279259-e39a20e2-f71a-459f-ac49-8a756106c522.png)


### Infinity Norm of a Matrix
![norm3](https://user-images.githubusercontent.com/118787261/213279279-bddb1085-1f0b-4601-adf2-58b4b80827ea.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
