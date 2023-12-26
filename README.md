# Norm of a matrix
## Aim:
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1.Get the input matrix using np.array()  

2.Find the 2-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.
      
## Program:

```Python
# Register No:23013389
# Developed By:N Kannan

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:

### 1-Norm of a Matrix
![Screenshot 2023-12-26 182145](https://github.com/kannan-nagaraju/Norm-of-a-matrix/assets/145742755/2ed1682f-57eb-4f50-94f7-89c80829705a)
### 2-Norm of a Matrix
![image](https://github.com/kannan-nagaraju/Norm-of-a-matrix/assets/145742755/415902b4-0a70-4a45-8afb-e5109f70ebba)
### Infinity Norm of a Matrix
![Screenshot 2023-12-26 182827](https://github.com/kannan-nagaraju/Norm-of-a-matrix/assets/145742755/e6af6586-4906-4195-b537-78acf527eb76)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
