# Week 2 

### Modulus & Inner Product 

* Vectors have two things:
	* Size of a vector (aka the length of a vector) 
	* Dot product (aka inner scalar or projection product) 
* We need to learn to calculate the length and direction   

### Length 

![Lecture 2](imgs/w2_lecture_1.png)

* If a vector is constructed out of two orthorgonal vectors (ie., they are at a right angle), we can find the length using pythagoras's theorem 

$Vector r = ai + bj$

$Length of r = |r| = \sqrt{a^2 + b^2}$

* Another way to get the size of a vector is simply by taking the dot product of the vector with itself: 

$r.r = |r|^2$

### Dot product 

![Lecture 2](imgs/w2_lecture_2.png)

The dot product is just a number, found by multiplying the components of both vectors together, and adding them up. There are three properties:

* Commutative: The order of multiplication doesnt matter which comes first:

$r . s = (r_i s_i) + (r_j s_j)$

* Distributive over addition:

$r . (s+t) = r.s + r.t$

* Associative over scalar multiplication too: 

$r.(As) = A(r.s)$ 

### Cosine Rule

![Lecture 2](imgs/w2_lecture_3.png)

* Suppose we have a triangle with three sides, a, b, c 
* The cosine rule states that: 

$c^2 = a^2 b^2 - 2ab\cos\theta$ 

* We can rewrite one of the sides, c, as a-b 
* Rename the sides to s, r, t 
* We can say `t = r-s`
* Therefore rewriting it in the cosine rule... 

$|r-s|^2 = |r|^2 + |s|^2 - 2|r||s|\cos\theta$

--> $r.s = |r||s|\cos\theta$ 

* Recall
	* When $\theta = 0$ then $\cos\theta = 1$
	* When $\theta = 90$ then $\cos\theta = 0$
	* When $\theta = 180$ then $\cos\theta = -1$
* This means when the angle between the two vectors is zero (aka they are going in the exact same direction) then $r.s = |r||s|\cos\theta\ = |r||s|$.  
* This also means when the angle between the two vectors is 90 (aka they are going in a perpendicular direction) then $r.s = |r||s|\cos\theta\ = 0$.
* This also means when the angle between the two vectors is -180 (aka they are going in opposite directions) then $r.s = |r||s|\cos\theta\ = -|r||s|$.

### Vector Projection

![Lecture 2](imgs/w2_lecture_4.png)

* If we want to get the length of the projection of s onto r, we can apply the cosine rule in this formula:

$r.s = |r||s|\cos\theta$
$r.s = |r|(Scalar value representing the Projection of S onto R)$
${r.s\over|r|} = {|s|\cos\theta}$

This will give a number representing the scalar projection of S onto R. 

If we want a vector projection instead, representing the larger/ smaller vector R, we can multiply the scalar projection above by the unit vector R: 

$r{r.s\over|r||r|} = r{r.s\over r.r}$

### Changing Basis

