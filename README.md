# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
## step1:
Import numpy and scipy packages
## step2:
Read the input matrix as two dimensional array
## step3:
Call the Built in function lu()to decompose the array
## step4:
print the output

## Program:
#  To find l and u matrix
# Developed by : SIVAMOHANASUNDARAM. V
# Register number : 22004168
~~~py
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
~~~
# To find LU Decompostiton of a matrix
# Developed by : SIVAMOHANASUNDARM.V
# Register number : 22004168
~~~py
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
~~~

## Output:
![landu](/l%20and%20u.png)
![l and u](/got%20l%20and%20u.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

