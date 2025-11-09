# Lab 1: Linear Transformations
by Nataliia Vytska

---

**1. What are linear transformations?**

A linear transformation is a transformation T: Ln -> Lm, which satisfies two properties:  
1) Additivity: T(u + v) = T(u) + T(v)
2) Homogeneity: T(cv) = cT(v)

Geometrically, such transformation can change shape's position, rotation, or scale but keeps straight lines straight and the origin fixed.


**2. What is a linear transformation matrix and how can it be interpreted?**

A linear transformation matrix is a matrix that describes a geometric transformation of a vector space, such as scaling, shearing, or rotation, by representing the transformation as a matrix multiplication.

Transforming space using matrices, or applying specific transformation matrices can serve as am interpretation.

**3. What features and properties does a rotation matrix have?**

1) Orthogonality
2) Inverse matrix equals Transpose matrix
3) Det(R) = +1

**4. Suppose some arbitrary linear transformation has been performed; how do you find the linear transformation matrix that will return everything to its original form? 
Is it always possible to perform an inverse transformation?**

To reverse a linear transformation, you need the inverse matrix A<sup>-1</sup>. If such inverse matrix exists, applying it restores every vector to its original position:

***x = A<sup>-1</sup>(xA)***

It’s only possible when the det(A) &ne; 0. 

**5. The absolute value of the determinant of a transformation matrix is less than 1, what conclusions can be drawn about this transformation (how does space change under this transformation)? 
What if it is greater than 1? Equal to 1? Equal to 0?**

1) If the absolute value of the determinant is less than 1 the transformation compresses space.
2) If it is greater then 1, the transformation expands space.
3) If it is equal to 1, the transformation preserves volume or area (as in rotations or reflections).
4) If it is equal to 0, it means the space collapses into a lower dimension, making the transformation non-invertible.


---

Sources:

[1] https://textbooks.math.gatech.edu/ila/linear-transformations.html

[2] https://www.youtube.com/watch?v=kYB8IZa5AuE

[3] https://robotacademy.net.au/lesson/describing-rotation-in-2d/

[4]