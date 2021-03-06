# maths-machine-learning-linear-algebra
# 1.
# Identifying special matrices
## Instructions
In this assignment, you shall write a function that will test if a 4×4 matrix is singular, i.e. to determine if an inverse exists, before calculating it.

You shall use the method of converting a matrix to echelon form, and testing if this fails by leaving zeros that can’t be removed on the leading diagonal.

Don't worry if you've not coded before, a framework for the function has already been written.
Look through the code, and you'll be instructed where to make changes.
We'll do the first two rows, and you can use this as a guide to do the last two.

### Matrices in Python
In the *numpy* package in Python, matrices are indexed using zero for the top-most column and left-most row.
I.e., the matrix structure looks like this:
```python
A[0, 0]  A[0, 1]  A[0, 2]  A[0, 3]
A[1, 0]  A[1, 1]  A[1, 2]  A[1, 3]
A[2, 0]  A[2, 1]  A[2, 2]  A[2, 3]
A[3, 0]  A[3, 1]  A[3, 2]  A[3, 3]
```
You can access the value of each element individually using,
```python
A[n, m]
```
which will give the n'th row and m'th column (starting with zero).
You can also access a whole row at a time using,
```python
A[n]
```
Which you will see will be useful when calculating linear combinations of rows.

A final note - Python is sensitive to indentation.
All the code you should complete will be at the same level of indentation as the instruction comment.
