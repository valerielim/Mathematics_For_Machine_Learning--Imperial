# Week2 - Dot Project of Vectors

Practice assignment walkthrough. 

### Q1: What is the size of the vector **s** = [1, 3, 4, 2]?

|s| = $$1^2 + 3^2 + 4^2 + 2^2$$

|s| = $$1 + 9 + 16 + 4$$

|s| = $$30$$ 

### Q2: What is the dot product of vectors **r** = [-5, 3, 2, 8] and **s** = [1, 2, -1, 0]?

r . s = $$(-5)(1) + 3(2) + 2(-1) + 8(0)$$

r . s = $$-5+6-2+0$$

r . s = $$-1$$ 

### Q3: What is the scalar projection of **s** onto **r**, where **r** = [3, -4, 0] and **s** = [10, 5, -6]? 

Formula for scalar projection = $${r.s \over |r|} $$

r . s = $$3(10) + 5(-4) + 0(-6)$$

r . s = $$30 - 20 + 0$$

r . s = $$10$$

|r| = $$\sqrt{3^2 + (-4)^2 + 0^2}$$

|r| = $$\sqrt{9 + 16 + 0}$$

|r| = $$\sqrt{25}$$

|r| = $$5$$

Putting it together: $${r.s \over |r|} = {10 \over 5} = 2$$

### Q4: What is the vector projection of **s** onto **r**, where **r** = [3, -4, 0] and **s** = [10, 5, -6]? 

Formula for vector projection = $${{r.s \over |r||r|}r}$$

$|r||r| = {\sqrt{3^2 + (-4)^2 + 0^2}}^2$

$|r||r| = {9 + 16 + 0}$

$|r||r| = 25$

From Q3, we know that: $$r.s = 10$$

Therefore

$${{r.s \over |r||r|}r} = {10 \over 25} \begin{pmatrix} 3 \\\ -4 \\\ 0 \\\ \end{pmatrix} = \begin{pmatrix} 6/5 \\\ -8/5 \\\ 0 \\\ \end{pmatrix}$$

### Q5: Let **a** = [3, 0, 4] and **b** = [0, 5, 12]. Which is larger, $$|a + b|$$ or $$|a| + |b|$$? 

$|a + b| = \sqrt{ (3+0)^2 + (0+5)^2 + (4+12)^2 }$

$|a + b| = \sqrt{9 + 25 + 16}$

$|a + b| = \sqrt{50}$

$|a + b| = 7.07...$

.

$|a|= \sqrt{3^2 + 0^2 + 4^2}$

$|a|= \sqrt{9+16}$

$|a|= \sqrt{25}$

$|a|= 5$

.

$|b|= \sqrt{0^2 + 5^2 + 12^2}$

$|b|= \sqrt{0 + 25 + 144}$

$|b|= \sqrt{159}$

$|b|= 12.6...$

Therefore $|a + b| < |a| + |b|$.

### Q6: Which of the following statements about dot products are correct? 

* The size of a vector is equal to the square root of the dot product of the vector with the vector itself. ==[TRUE]==

* The order fo the vector in a dot product is important, so that s . r =/= r.s. ==[FALSE]==

* We can find the angle between two vectors using the dot product. ==[TRUE - covered in trigonometry section]==

* The vector projection of S onto R is equal to the scalar projection of S onto R multiplied by a vector of unit length that points in the same direction as R. ==[TRUE - this is the formula for vector projection]==

* The scalar projection of S onto R is always the same as the scalar projection of R onto S. ==[FALSE - see diagrams]==