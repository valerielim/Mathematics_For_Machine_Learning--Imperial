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
* [Python Lab: Reflecting Bear](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week4/W4%20%E2%80%93%20ReflectingBear.ipynb)
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

* [Lecture](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week5/W5%20%E2%80%93%20Lecture.md)
* [Practice Assignment: Selecting eigenvectors by inspection](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week5/W5%20%E2%80%93%20Assignment%20%E2%80%93%20Selecting%20eigenvectors%20by%20inspection.md) 
* [Practice Assignment: Characteristic polynomials, eigenvalues and eigenvectors](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week5/W5%20%E2%80%93%20Assignment%20%E2%80%93%20Characteristic%20polynomials%2C%20eigenvalues%20and%20eigenvectors.md)
* [Practice Assignment: Diagonalisation and applications](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week5/W5%20%E2%80%93%20Assignment%20%E2%80%93%20Diagonalisation%20and%20applications.md) 
* [Python Lab: PageRank](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week5/PageRank.ipynb)
* [Graded Assignment: Eigenvalues and eigenvectors](https://github.com/valerielim/Mathematics_For_Machine_Learning--Imperial/blob/main/week5/W5%20%E2%80%93%20Graded%20Assignment%20%E2%80%93%20Eigenvalues%20and%20Eigenvectors.md) 

Concepts

* Derive eigenvectors and eigenvalues from a matrix, if it exists (this process is waay too long to write, please see lecture notes) 
* Scaling up multiplication of a matrix $v$ by a transformation vector $T$, to find $T^n.v$
* Apply diagonalisation and eigenvectors to solve above using formula $$T^n = CD^nC^{-1}$$
* Application of diagonalisation to write pagerank formula, where $n$ represents the number of elements, $L$ represents the probability matrix of each element connecting to another, $d$ represents the damping factor and $J$ is the $nxn$ matrix where every element is one.

$$M = d L + {{1-d}\over{n}} J$$

### Conclusion

Prof David Dye and Prof Samuel Coooper did a really good job teaching the material. They were clear, included worked examples to demonstrate the concepts, and there's a handful of visualisation aids on matrices and matrix transformation to really cement the idea in. One minor thing I would change is that in Week 5's lecture "Changing to the Eigenbasis", I would elaborate on how we use gaussian elimination further, from the homogenous system of linear equations to the eigenvector itself. I think some steps were skipped in the video in the interest of time but it would be helpful to include this (or link to additional material). I really liked each python lab and found them useful, although they could be much more challenging. They could also introduce more linear algebra python functions.

Personally, I took this course to brush up on linear algebra and cover a topic I didn't formally learn in undergrad. I was wondering if there's something I've missed all these years of working in data analytics and data science. Sadly I do think the day-to-day applications of this course in practice are limited, since I don't think anyone requires data scientists to derive eigenvectors by hand or perform matrix multiplication by hand - I've always used python and modern compute resources are incredibly fast and efficient. Perhaps understanding how matrices can skew an image may be helpful when working on OCR/ FR tasks but you can also just eyeball it by hand. So if I had to rank this course as "Not useful", "Optional", or "Essential Must-Have", I would probably rank it in the middle as "Optional". 

Overall, like Prof David Dye said in the conclusion, the main takeaway is to know the technical terms around linear algebra to phrase your business problem into a proper question, rather than calculating these formulas by hand. I think this course succeeds at that goal. 

