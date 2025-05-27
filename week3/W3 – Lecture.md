# Week 3 

* Suppose we have matrix `A` and vector `r`
* If we multiply them by some scalar value `n`, we get `A (nr) = nr'` where the vector `r` has been changed 
* We can prove and apply this rule further that suppose `r` and `s` are both vectors; `A(r+s) = Ar + As`

### Types of matrix transformation for skew

![Lecture 3](imgs/w3_lect1.png)

* No transformation:

$$\begin{bmatrix} 1 & 0\\\ 0&1\end{bmatrix} 
\begin{bmatrix} x\\\ y\end{bmatrix} = 
\begin{bmatrix} x\\\ y\end{bmatrix}$$

* Suppose we want to scale it unevenly (ie., shear): 

$$\begin{bmatrix} 3 & 0\\\ 0 & 2\end{bmatrix}
\begin{bmatrix} x\\\ y\end{bmatrix} = 
\begin{bmatrix} 3x\\\ 2y\end{bmatrix}$$

* Suppose we want to invert it along the horizontal plane, such that left becomes right and so on: 

$$\begin{bmatrix} -1 & 0\\\ 0 & 1\end{bmatrix}
\begin{bmatrix} x\\\ y\end{bmatrix} = 
\begin{bmatrix} -x\\\ y\end{bmatrix}$$

* Suppose we want to invert it along the vertical plane, such that top becomes bottom and so on: 

$$\begin{bmatrix} 1 & 0 \\\ 0 & -1\end{bmatrix}
\begin{bmatrix} x \\\ y\end{bmatrix} = 
\begin{bmatrix} x \\\ -y\end{bmatrix}$$

* Suppose we want to flip the image along a 45" plane (ie., the 2.30pm clock hand):

$$\begin{bmatrix} 0 & 1 \\\ 1 & 0\end{bmatrix}
\begin{bmatrix} x \\\ y\end{bmatrix} = 
\begin{bmatrix} y \\\ x\end{bmatrix}$$

* Suppose we want to flip the image along a 225" plane (ie., the 8.30pm clock hand):

$$\begin{bmatrix} 0 & -1 \\\ -1 & 0\end{bmatrix}
\begin{bmatrix} x \\\ y\end{bmatrix} = 
\begin{bmatrix} -y \\\ -x\end{bmatrix}$$

* Suppose we want to rotate it anti-clockwise by 90": 

$$\begin{bmatrix} 0 & -1 \\\ 1 & 0\end{bmatrix}
\begin{bmatrix} x \\\ y\end{bmatrix} = 
\begin{bmatrix} -y \\\ x\end{bmatrix}$$

* Suppose we want to rotate it clockwise by `n` degrees; we can use trigonometry in matrices to do so. Let $\theta$ be the designed clockwise angle: (so if you want it to rotate by -90", or anticlockwise 90", put that in as $\theta$. Using the previous example, 
$\sin\theta = \sin 90 = -1$. 

$$\begin{bmatrix} \cos\theta & \sin\theta \\\ 
-\sin\theta/ & \cos\theta\end{bmatrix}
\begin{bmatrix} x \\\ y\end{bmatrix}$$

* Application: Image transformation occassionally (eg., to detect and fix skew in OCR or FR projects). 


