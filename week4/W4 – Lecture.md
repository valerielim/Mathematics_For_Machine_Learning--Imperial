# Week 4 

### Einstein's notation

This is how to write out a matrix: 

$$\begin{bmatrix} a_{11} & a_{12} & ... & a_{1n}\\\ 
a_{21} & a_{22} & ... & a_{2n}\\\
... & ... &... &... &\\\ 
a_{n1} & a_{n2} & ... & a_{nn}\end{bmatrix}$$

We can write out the summation of any given row multiplied with any given column like this: 

$$\begin{bmatrix} b_{11} & b_{12} & ... & b_{1n}\\\ 
b_{21} & b_{22} & ... & b_{2n}\\\
... & ... &... &... &\\\ 
b_{n1} & b_{n2} & ... & b_{nn}\end{bmatrix} = 
\begin{bmatrix} A & B \end{bmatrix}$$

In other words:

$$ab_{23} = a_{21}b_{13} + a_{22}b_{23} + ... + a_{2n}b_{n3}$$

Or formally:

$$(ab)_{ik} = \sum_{j} a_{ij}b_{jk} = a_{ij}b_{jk}$$

### Dot projection

* What if we multiplied any given vector, R, by one of its unit vectors (eg., the x-axis)? 
	* We would get the length of the vector ALONG the x-axis, aka, the dot projection of that vector along another vector
* Using einstein's notation, we can show that the dot product, or when multiplying any given vector by another, would give the projection of the first vector along the second vector.  


![Lecture 2](imgs/w2_lecture_1.png) 