# Mathematics_For_Machine_Learning--Imperial

### Week 1 

* [Introduction](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week1/W1%20%E2%80%93%20Intro.md)
* [Practice Assignment: Exploring parameter space](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week1/W1%20%E2%80%93%20Assignment%20%E2%80%93%20Exploring%20Parameter%20Space%20.md)
* [Practice Assignment: Solving simultaneous equations](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week1/W1%20%E2%80%93%20Assignment%20%E2%80%93%20Simultaneous%20Equations.md) 
* [Practice Assignment: Doing vector operations](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week1/W1%20%E2%80%93%20Assignment%20%E2%80%93%20Doing%20vector%20operations.md)

Concepts

* Vector addition `[a, b] + [c, d] = [a+c, b+d]`
* Vector subtraction `[a, b] - [c, d] = [a-c, b-d]`
* Identifying the right vector in a 2d space [x, y]

### Week 2 

* [Lecture](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week2/W2%20%E2%80%93%20Lecture.md) 
* [Practice Assignment: Dot product of vectors](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week2/W2%20%E2%80%93%20Assignment%20%E2%80%93%20Dot%20Product%20of%20Vectors.md)
* [Practice Assignment: Changing Basis](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week2/W2%20%E2%80%93%20Assignment%20%E2%80%93%20Changing%20Basis.md)
* [Practice Assignment: Linear Dependency](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week2/W2%20%E2%80%93%20Assigment%20%E2%80%93%20Linear%20Dependency%20of%20a%20set%20of%20vectors%20.md) 
* [Assignment: Vector Operations Assessment](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week2/W2%20%E2%80%93%20Graded%20Assignment%20%E2%80%93%20Vector%20Operations%20Assessment.md) 

Concepts

* Calculating the dot product of one vector with another (e.g., `r.s`) 
* Calculating the length of vector through modulus, or dot product with itself (e.g., length of `r = r.r` 
* Applying the cosine rule to test for orthogonality, $r.s = |r||s|\cos\theta$, and if $r.s = 0$ then they are indeed at 90" to each other 
* Calculating the scalar projection of one vector onto another, and give the answer as a number (ratio, fraction, percentage) representing the partial length of the second vector: ${r.s\}over{|r|}$
* Calculating the vector projection of one vector onto another, and give the answer as a new vector $r{r.s}\over{r.r}$
* Changing the basis vectors to represent an existing vector as a function of new unit vectors

### Week 3

* [Lecture](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week3/W3%20%E2%80%93%20Lecture.md) 
* [Practice Assignment: Solving linear equations using the inverse matrix](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week3/W3%20%E2%80%93%20Assignment%20%E2%80%93%20Solving%20linear%20equations%20using%20inverse%20matrix%20.md) 
* [Practice Assignment: Using matrices to make transformations](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week3/W3%20%E2%80%93%20Assignment%20%E2%80%93%20Using%20matrices%20to%20make%20transformations.md) 
* [Graded Assignment: Identifying Special Matrices (Jupyter)](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week3/W3%20%E2%80%93%20Graded%20Assignment%20%E2%80%93%20IdentifyingSpecialMatrices.ipynb) 

Concepts

* Matrix **clockwise** rotation by angle $\theta\$ using the formula: 

$$\begin{bmatrix} \cos\theta & \sin\theta \\\ 
-\sin\theta/ & \cos\theta\end{bmatrix}
\begin{bmatrix} x \\\ y\end{bmatrix}$$

* Solving simultaneous equations by elimination, substitution. Find the inverse of a matrix through performing these operations on the identity matrix. 
* Recap: Area of parallelogram is `ad-bc` 
* Understanding that we should check ALL basis vectors are **linearly independent** else we will not be able to calculate its inverse or its determinant 

### Week 4 
 
* [Lecture](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week4/W4%20%E2%80%93%20Lecture.md) 
* [Practice Assignment: Non-square matrix multiplication](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week4/W4%20%E2%80%93%20Assignment%20%E2%80%93%20Non-square%20Matrix%20Multiplication.md) 
* [Graded Programming Assignment: Gram-Schmidt Process](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week4/W4%20%E2%80%93%20GramSchmidtProcess.ipynb) 
* [Graded Programming Assignment: Reflecting Bear](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week4/W4%20%E2%80%93%20ReflectingBear.ipynb)
* [Special Assignment: Using non-square matrices to do a projection](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week4/W4%20%E2%80%93%20Matrix%20Multiplication%20Special%20Assignment.md) –– This is probably the highlight

Concepts

* Einstein's summation notation: 

$$ab_{23} = a_{21}b_{13} + a_{22}b_{23} + ... + a_{2n}b_{n3}$$

$$ab_{ik} = \sum_{j} a_{ij}b_{jk} = a_{ij}b_{jk}$$

* Recap: Finding the determinant of a matrix

$$D = \begin{bmatrix} a & b \\\ c & d \end{bmatrix}$$

$$D^{-1} = {1\over(ad-bc)}\begin{bmatrix} d & -b \\\ -c & a \end{bmatrix}$$

* Finding the new vector $r'$ of a given vector $r$ in a changed basis, where the changed basis vectors in our coordinates are $D$, and its inverse is $D^{-1}$: 

$$r' = D^{-1}r$$

* Finding the new vector $v'$ of a given vector $v$ in a changed basis, where the changed basis vectors in our coordinates are $B$, and its inverse is $B^{-1}$, and its new rotation or transformation vector is given by $R$: (important: the order matters!)

$$B^{-1} . R . B . v$$

* Recap: Transposing a matrix means changing all its rows into columns, and vice versa 
* Recap: Multiplying a matrix by its transposed self, if the matrix is also orthorgonal, would give the identity matrix 
* Conducting the Gram-Schmidt process to transform a set of vectors into orthorgonal unit vectors for subsequent use: 

First plane -- $$e_1 = {v_1\over{|v_1|}}$$

Second plane -- $$u_2 = v_2 - (v_2 . e_1)e_1$$

$$v_2 = (v_2.e_1){e_1\over|e_1|} + u_2$$

$$e_2 = {u_2\over{|u_2|}}$$

Third plane -- $$u_3 = v_3 - (v_3 . e_1)e_1 - (v_3 . e_2)e_2$$

$$e_3 = {u_3\over{|u_3|}}$$

### Week 5

* Lecture
* [Practice Assignment: Non-square matrix multiplication] 
