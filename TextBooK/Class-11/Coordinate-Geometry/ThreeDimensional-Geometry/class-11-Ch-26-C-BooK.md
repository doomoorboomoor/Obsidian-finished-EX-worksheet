## Section Formulae

### Theorem 2 (Section Formula)
Let $P(x_1, y_1, z_1)$ and $Q(x_2, y_2, z_2)$ be two points and let $R(x, y, z)$ be a point on $PQ$ dividing it in the ratio $m:n$. Prove that

$$
x=\frac{m x_{2}+n x_{1}}{m+n}, y=\frac{m y_{2}+n y_{1}}{m+n} \text{ and } z=\frac{m z_{2}+n z_{1}}{m+n}.
$$

#### Proof
From $P, Q$ and $R$, draw perpendiculars $PL, QM$ and $RN$ on the $xy$-plane. Also, draw $PS \perp QM$, meeting $QM$ and $RN$ at $S$ and $T$ respectively. From similar triangles $PRT$ and $PQS$, we have

$$
\begin{aligned}
& \frac{RT}{QS}=\frac{PR}{PQ} \\
\Rightarrow & \frac{RN-TN}{QM-SM}=\frac{m}{m+n} \\
\Rightarrow & \frac{RN-PL}{QM-PL}=\frac{m}{m+n} \\
\Rightarrow & \frac{z-z_1}{z_2-z_1}=\frac{m}{m+n} \\
\Rightarrow & z=\frac{m z_2+n z_1}{m+n}
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_2ca3791f7309a267d86eg-07.jpg?height=382&width=436&top_left_y=676&top_left_x=761)

Similarly, $x=\frac{m x_2+n x_1}{m+n}$ and $y=\frac{m y_2+n y_1}{m+n}$.

Hence, $x=\frac{m x_2+n x_1}{m+n}, y=\frac{m y_2+n y_1}{m+n}, z=\frac{m z_2+n z_1}{m+n}$.

### Corollary 1
The coordinates of the **midpoint** of the join of $P(x_1, y_1, z_1)$ and $Q(x_2, y_2, z_2)$ are

$$
\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}, \frac{z_1+z_2}{2}\right).
$$

#### Proof
Let $R$ be the midpoint of $PQ$.
Putting $m=n=1$ in the above result, we find that the coordinates of $R$ are

$$
\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}, \frac{z_1+z_2}{2}\right).
$$

### Corollary 2
The coordinates of a point $R$ which divides the join of $P(x_1, y_1, z_1)$ and $Q(x_2, y_2, z_2)$ **externally** in the ratio $m:n$ are

$$
\left(\frac{m x_2-n x_1}{m-n}, \frac{m y_2-n y_1}{m-n}, \frac{m z_2-n z_1}{m-n}\right).
$$

#### Proof
Replacing $n$ by $-n$ in Theorem 2, we find that the coordinates of $R$ are

$$
\left(\frac{m x_2-n x_1}{m-n}, \frac{m y_2-n y_1}{m-n}, \frac{m z_2-n z_1}{m-n}\right).
$$

---

## Centroid of a Triangle

### Theorem 3
Show that the **centroid** of the triangle with vertices $A(x_1, y_1, z_1)$, $B(x_2, y_2, z_2)$ and $C(x_3, y_3, z_3)$ is

$$
\left(\frac{x_1+x_2+x_3}{3}, \frac{y_1+y_2+y_3}{3}, \frac{z_1+z_2+z_3}{3}\right).
$$

#### Proof
Let $D$ be the midpoint of $BC$. Join $A$ and $D$.
Then, the coordinates of $D$ are

$$
\left(\frac{x_2+x_3}{2}, \frac{y_2+y_3}{2}, \frac{z_2+z_3}{2}\right).
$$

Let $G$ be the centroid of triangle $ABC$. Then, $G$ lies on $AD$ and divides it in the ratio $2:1$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2ca3791f7309a267d86eg-08.jpg?height=266&width=458&top_left_y=616&top_left_x=737)

$\therefore$ the coordinates of $G$ are

$$
\left[\frac{2 \cdot\left(\frac{x_2+x_3}{2}\right)+1 \cdot x_1}{2+1}, \frac{2 \cdot\left(\frac{y_2+y_3}{2}\right)+1 \cdot y_1}{2+1}, \frac{2 \cdot\left(\frac{z_2+z_3}{2}\right)+1 \cdot z_1}{2+1}\right]
$$

i.e.,

$$
\left(\frac{x_1+x_2+x_3}{3}, \frac{y_1+y_2+y_3}{3}, \frac{z_1+z_2+z_3}{3}\right).
$$

---

## Solved Examples

### Example 1
Find the coordinates of the point which divides the join of the points $P(5,4,2)$ and $Q(-1,-2,4)$ in the ratio $2:3$.

#### Solution
Let $R(x, y, z)$ be the required point. Then,

$$
x=\frac{2(-1)+3 \times 5}{2+3}, y=\frac{2(-2)+3 \times 4}{2+3}, z=\frac{2 \times 4+3 \times 2}{2+3}
$$

or $x=\frac{13}{5}, y=\frac{8}{5}$ and $z=\frac{14}{5}$.

So, the required point is $R\left(\frac{13}{5}, \frac{8}{5}, \frac{14}{5}\right)$.

---

### Example 2
Find the coordinates of the point which divides the join of the points $A(2,-1,3)$ and $B(4,3,1)$ externally in the ratio $3:4$.

#### Solution
Let $C(x, y, z)$ be the required point. Then,

$$
x=\frac{3 \times 4-4 \times 2}{3-4}, y=\frac{3 \times 3-4(-1)}{3-4}, z=\frac{3 \times 1-4 \times 3}{3-4}
$$

or $x=-4, y=-13$ and $z=9$.

$\therefore$ the required point is $C(-4,-13,9)$.

---

### Example 3
Find the ratio in which the join of the points $P(2,-1,3)$ and $Q(4,3,1)$ is divided by the point $\left(\frac{20}{7}, \frac{5}{7}, \frac{15}{7}\right)$.

#### Solution
Let the required ratio be $\lambda:1$. Then, the coordinates of $R$ are

$$
\left(\frac{4 \lambda+2}{\lambda+1}, \frac{3 \lambda-1}{\lambda+1}, \frac{\lambda+3}{\lambda+1}\right)
$$

But, the coordinates of $R$ are $\left(\frac{20}{7}, \frac{5}{7}, \frac{15}{7}\right)$.

$\therefore \frac{4 \lambda+2}{\lambda+1}=\frac{20}{7}$ or $\lambda=\frac{3}{4}$.

So, the required ratio is $\frac{3}{4}:1$, i.e., $3:4$.

---

### Example 4
Find the ratio in which the line segment, joining the points $P(2,3,4)$ and $Q(-3,5,-4)$ is divided by the $yz$-plane. Also, find the point of intersection.

#### Solution
Let $PQ$ be the divided by the $yz$-plane at a point $R$ in the ratio $\lambda:1$. Then, the coordinates of $R$ are

$$
\left(\frac{-3 \lambda+2}{\lambda+1}, \frac{5 \lambda+3}{\lambda+1}, \frac{-4 \lambda+4}{\lambda+1}\right) \tag{i}
$$

Since $R$ lies on the $yz$-plane, the $x$-coordinate of $R$ is therefore $0$.

$\therefore \frac{-3 \lambda+2}{\lambda+1}=0$, or $\lambda=\frac{2}{3}$.

So, the required ratio is $\frac{2}{3}:1$, i.e., $2:3$.

Putting $\lambda=\frac{2}{3}$ in (i), the point of intersection of the line segment $PQ$ and the $yz$-plane is $\left(0, \frac{19}{5}, \frac{4}{5}\right)$.

---

### Example 5
Find the ratio in which the join of $A(2,1,5)$ and $B(3,4,3)$ is divided by the plane $2x+2y-2z=1$. Also, find the coordinates of the point of division.

#### Solution
Suppose the given plane intersects $AB$ at a point $C$ and let the required ratio be $\lambda:1$.
Then, the coordinates of $C$ are

$$
\left(\frac{3 \lambda+2}{\lambda+1}, \frac{4 \lambda+1}{\lambda+1}, \frac{3 \lambda+5}{\lambda+1}\right) \tag{i}
$$

Since $C$ lies on the plane $2x+2y-2z=1$, this point must satisfy the equation of the plane.

$\therefore 2\left(\frac{3 \lambda+2}{\lambda+1}\right)+2\left(\frac{4 \lambda+1}{\lambda+1}\right)-2\left(\frac{3 \lambda+5}{\lambda+1}\right)=1$ or $\lambda=\frac{5}{7}$.

So, the required ratio is $\frac{5}{7}:1$, i.e., $5:7$.

Putting $\lambda=\frac{5}{7}$ in (i), the required point of division is $C\left(\frac{29}{12}, \frac{9}{4}, \frac{25}{6}\right)$.

---

### Example 6
Three vertices of a parallelogram $ABCD$ are $A(3,-1,2), B(1,2,-4)$ and $C(-1,1,2)$. Find the coordinates of the fourth vertex $D$.

#### Solution
Let $D(x, y, z)$ be the required point. Then, the midpoint of diagonal $BD$ is

$$
\left(\frac{x+1}{2}, \frac{y+2}{2}, \frac{z-4}{2}\right)
$$

And, the midpoint of diagonal $AC$ is

$$
\left(\frac{3-1}{2}, \frac{-1+1}{2}, \frac{2+2}{2}\right), \text{ i.e., } (1,0,2).
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_2ca3791f7309a267d86eg-10.jpg?height=212&width=326&top_left_y=894&top_left_x=873)

But, the midpoints of the diagonals of a parallelogram always coincide.

$\therefore \frac{x+1}{2}=1, \frac{y+2}{2}=0$ and $\frac{z-4}{2}=2$.

So, $x=1, y=-2$ and $z=8$.

Hence, the required point is $D(1,-2,8)$.

---

### Example 7
The midpoints of the sides of a triangle are $(1,5,-1), (0,4,-2)$ and $(2,3,4)$. Find its vertices.

#### Solution
Let $A(x_1, y_1, z_1), B(x_2, y_2, z_2)$ and $C(x_3, y_3, z_3)$ be the vertices of the given triangle, and let $D(1,5,-1), E(0,4,-2)$ and $F(2,3,4)$ be the midpoints of the sides $BC, CA$ and $AB$ respectively. Then,

$\frac{x_2+x_3}{2}=1; \frac{y_2+y_3}{2}=5; \frac{z_2+z_3}{2}=-1;$
$\frac{x_3+x_1}{2}=0; \frac{y_3+y_1}{2}=4; \frac{z_3+z_1}{2}=-2;$
$\frac{x_1+x_2}{2}=2; \frac{y_1+y_2}{2}=3$ and $\frac{z_1+z_2}{2}=4$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2ca3791f7309a267d86eg-10.jpg?height=235&width=410&top_left_y=1580&top_left_x=789)

Thus,
$x_2+x_3=2; x_3+x_1=0; x_1+x_2=4$
$y_2+y_3=10; y_3+y_1=8; y_1+y_2=6$
$z_2+z_3=-2; z_3+z_1=-4; z_1+z_2=8$

Adding first three equations, we get
$2(x_1+x_2+x_3)=6$ or $x_1+x_2+x_3=3$.
Thus, $x_1=1, x_2=3$ and $x_3=-1$.

Adding next three equations, we get
$2(y_1+y_2+y_3)=24$ or $y_1+y_2+y_3=12$.
$\therefore y_1=2; y_2=4$ and $y_3=6$.

Adding last three equations, we get
$2(z_1+z_2+z_3)=2$ or $z_1+z_2+z_3=1$.
$\therefore z_1=3, z_2=5$ and $z_3=-7$.

Hence, the vertices of the given triangle are $A(1,2,3); B(3,4,5)$ and $C(-1,6,-7)$.

---

### Example 8
Using the section formula, prove that the three points $A(-2,3,5), B(1,2,3)$ and $C(7,0,-1)$ are collinear.

#### Solution
Suppose $C$ divides $AB$ in the ratio $\lambda:1$.
Then, $\frac{\lambda-2}{\lambda+1}=7, \frac{2 \lambda+3}{\lambda+1}=0$ and $\frac{3 \lambda+5}{\lambda+1}=-1$.

From each of these equations, we get $\lambda=\frac{-3}{2}$.
This shows that $C$ divides $AB$ externally in the ratio $3:2$.
So, $C$ lies on the line joining $A$ and $B$.

Hence, the given points $A, B, C$ are collinear.

---

