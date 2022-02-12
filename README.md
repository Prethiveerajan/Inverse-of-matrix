# Inverse-of-matrix

## AIM:
To fingd the inverse of matrix using numpy

## ALGORITHM:
### Step 1:
Import Numpy module as np.

### Step 2:Import Numpy module as np.
Create empty lists.

### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Use nested lists to append list.


## PROGRAM:
#Prethiveerajan P
#21500340
import numpy as np
l1 , l2 =[],[]
r,c = int(input()),int(input())
for i in range(r):
    for j in range(c):
        num = int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse=np.linalg.inv(value1)
print(inverse)

## OUTPUT:
![OUTPUT](pd.png)


## RESULT:
Thus a program is written to find the inverse of the matrix.
