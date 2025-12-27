# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Start with a square matrix 
𝐴
A:
LU decomposition only works for square matrices (same number of rows and columns).

Initialize L and U matrices:

𝐿
L (Lower triangular) is initialized as an identity matrix (1’s on the diagonal, 0’s elsewhere).

𝑈
U (Upper triangular) is initialized as a zero matrix.

Compute elements of U (upper triangular matrix):
For each row 
𝑖
i and column 
𝑗
j such that 
𝑗
≥
𝑖
j≥i:

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
U[i][j]=A[i][j]−
k=0
∑
i−1
	​

L[i][k]⋅U[k][j]

This subtracts the effect of the previous rows from the current element.

Compute elements of L (lower triangular matrix):
For each row 
𝑗
j such that 
𝑗
>
𝑖
j>i:

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


This ensures 
𝐿
L has 1’s on the diagonal and the proper values below the diagonal.

Repeat for all rows:
Continue step 3 and 4 for all rows from 0 to 
𝑛
−
1
n−1 until the whole matrix is decomposed into L and U.

Print the results:
After the loop, 
𝐿
L will contain the lower triangular values, and 
𝑈
U will contain the upper triangular values such that:

𝐴
=
𝐿
⋅
𝑈
A=L⋅U
## Program:

Developed by: G.MUTHU MANIKKAM
RegisterNumber:25016274 
*/
```
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.

<img width="1362" height="812" alt="image" src="https://github.com/user-attachments/assets/ae68b913-7db5-455a-8120-f0c8662cb852" />

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:G.MUTHU MAIKKAM 
RegisterNumber:25016274 
*/
```
<img width="1157" height="761" alt="image" src="https://github.com/user-attachments/assets/c6cedea3-e5f2-41a9-81f3-86a8b6071bc2" />


## Output:
![lu decomposition]()
i)<img width="1178" height="670" alt="image" src="https://github.com/user-attachments/assets/9186bd0d-4bd6-4cfa-926c-2e1b4ea4d324" />
ii)<img width="1142" height="482" alt="image" src="https://github.com/user-attachments/assets/6a5dfaa8-f0e3-49ec-81cb-4629804b7da2" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

