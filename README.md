# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Initialize matrices:
Let 
𝐴
A be the given square matrix of order 
𝑛
×
𝑛
n×n. Initialize 
𝐿
L as an identity matrix and 
𝑈
U as a zero matrix.

Decomposition:
For each row 
𝑖
i from 0 to 
𝑛
−
1
n−1:

For each column 
𝑗
j from 
𝑖
i to 
𝑛
−
1
n−1:
Compute 
𝑈
[
𝑖
]
[
𝑗
]
=
𝐴
[
𝑖
]
[
𝑗
]
−
∑
𝑘
=
0
𝑖
−
1
𝐿
[
𝑖
]
[
𝑘
]
⋅
𝑈
[
𝑘
]
[
𝑗
]
U[i][j]=A[i][j]−∑
k=0
i−1
	​

L[i][k]⋅U[k][j]

For each row 
𝑗
j from 
𝑖
+
1
i+1 to 
𝑛
−
1
n−1:
Compute 
𝐿
[
𝑗
]
[
𝑖
]
=
𝐴
[
𝑗
]
[
𝑖
]
−
∑
𝑘
=
0
𝑖
−
1
𝐿
[
𝑗
]
[
𝑘
]
⋅
𝑈
[
𝑘
]
[
𝑖
]
𝑈
[
𝑖
]
[
𝑖
]
L[j][i]=
U[i][i]
A[j][i]−∑
k=0
i−1
	​

L[j][k]⋅U[k][i]
	​


Repeat for all rows to fill all elements of 
𝐿
L and 
𝑈
U.

Output:
Print 
𝐿
L and 
𝑈
U matrices
. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

