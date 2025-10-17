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
# Register No: 25005647
# Developed By: Denesh Raj B
# 1-Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,1)
print("{:.2f}".format(ans))





# 2-Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,2)
print("{:.2f}".format(ans))


# Infinity Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
print ("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="611" height="264" alt="{5E5C4327-BB37-4632-A58F-F72988BA932C}" src="https://github.com/user-attachments/assets/6208dc9a-cb53-4ca9-94a4-f363bc127472" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="529" height="298" alt="{0D7187A1-DE14-4EB2-90F1-5BBC28645892}" src="https://github.com/user-attachments/assets/5bc2f387-512f-459c-b5dc-909d2efe2c7b" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="698" height="268" alt="{69C1909E-C4DE-4159-A9E7-D73BF5408BA3}" src="https://github.com/user-attachments/assets/0b6fa8ce-180b-40e5-8e45-fad618b78f37" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
