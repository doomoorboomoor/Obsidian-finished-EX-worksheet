## Distance Formula

### Theorem 1: Distance Formula

Prove that the distance between the points $P(x_{1}, y_{1}, z_{1})$ and $Q(x_{2}, y_{2}, z_{2})$ is given by

$$
PQ = \sqrt{(x_{2}-x_{1})^{2} + (y_{2}-y_{1})^{2} + (z_{2}-z_{1})^{2}}
$$

#### Proof:

Let $O$ be the origin, and let $P(x_{1}, y_{1}, z_{1})$ and $Q(x_{2}, y_{2}, z_{2})$ be the given points. From $P$ and $Q$, draw perpendiculars $PM$ and $QN$ respectively on the *xy*-plane.

Then, the coordinates of *M* and *N* are $M(x_{1}, y_{1}, 0)$ and $N(x_{2}, y_{2}, 0)$.

The two-dimensional coordinates of *M* and *N* referred to $OX$ and $OY$ are $M(x_{1}, y_{1})$ and $N(x_{2}, y_{2})$.

$$
\therefore MN^{2} = (x_{2}-x_{1})^{2} + (y_{2}-y_{1})^{2}
$$

Now, from *P* draw $PR \perp QN$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2ca3791f7309a267d86eg-03.jpg?height=385&width=442&top_left_y=495&top_left_x=757)

Then, $PR$ is parallel and equal to $MN$. Now, in right triangle $PRQ$, we have:

$$
\begin{aligned}
PQ^{2} & = PR^{2} + RQ^{2} \\
& = MN^{2} + (QN - RN)^{2} \\
& = MN^{2} + (QN - PM)^{2} \\
& = (x_{2}-x_{1})^{2} + (y_{2}-y_{1})^{2} + (z_{2}-z_{1})^{2} \quad [\because PM=z_{1} \text{ and } QN=z_{2}] \\
\therefore PQ & = \sqrt{(x_{2}-x_{1})^{2} + (y_{2}-y_{1})^{2} + (z_{2}-z_{1})^{2}}
\end{aligned}
$$

---

### Corollary

The distance of the point $P(x, y, z)$ from the origin $O(0,0,0)$ is

$$
OP = \sqrt{(x-0)^{2} + (y-0)^{2} + (z-0)^{2}} = \sqrt{x^{2} + y^{2} + z^{2}}
$$

---

### Example 1:

Find the distance between the points $A(-2,1,-3)$ and $B(4,3,-6)$.

#### Solution:

We have

$$
\begin{aligned}
AB & = \sqrt{\{[4-(-2)]^{2} + (3-1)^{2} + [-6-(-3)]^{2}\}} \\
& = \sqrt{\{6^{2} + 2^{2} + (-3)^{2}\}} = \sqrt{49} = 7 \text{ units.}
\end{aligned}
$$

---

### Example 2:

Show that the points $A(0,7,10)$, $B(-1,6,6)$ and $C(-4,9,6)$ form an **isosceles right-angled triangle**.

#### Solution:

We have

$$
\begin{aligned}
& AB = \sqrt{(-1-0)^{2} + (6-7)^{2} + (6-10)^{2}} = \sqrt{18} = 3\sqrt{2} \\
& BC = \sqrt{(-4+1)^{2} + (9-6)^{2} + (6-6)^{2}} = \sqrt{18} = 3\sqrt{2}
\end{aligned}
$$

and $AC = \sqrt{(-4-0)^{2} + (9-7)^{2} + (6-10)^{2}} = \sqrt{36} = 6$.

Clearly, $AB = BC$ and $AB^{2} + BC^{2} = (18+18) = 36 = AC^{2}$.
Hence, triangle $ABC$ is an isosceles right-angled triangle.

---

### Example 3:

Prove that the points $A(3,-2,4)$, $B(1,1,1)$ and $C(-1,4,-2)$ are **collinear**.

#### Solution:

We have

$$
\begin{aligned}
AB & = \sqrt{(1-3)^{2} + (1+2)^{2} + (1-4)^{2}} = \sqrt{4+9+9} = \sqrt{22} \\
BC & = \sqrt{(-1-1)^{2} + (4-1)^{2} + (-2-1)^{2}} = \sqrt{4+9+9} = \sqrt{22} \\
\text{and } AC & = \sqrt{(-1-3)^{2} + (4+2)^{2} + (-2-4)^{2}} = \sqrt{16+36+36} \\
& = \sqrt{88} = 2\sqrt{22}. \\
\therefore AB & + BC = AC.
\end{aligned}
$$

This shows that the given points are collinear.

---

### Example 4:

Find the equation of the curve formed by the set of all points whose distances from the points $(3,4,-5)$ and $(-2,1,4)$ are equal.

#### Solution:

Let $P(x, y, z)$ be any point on the given curve, and let $A(3,4,-5)$ and $B(-2,1,4)$ be the given points.

Then, $PA = PB$
$\Rightarrow PA^{2} = PB^{2}$
$\Rightarrow (x-3)^{2} + (y-4)^{2} + (z+5)^{2} = (x+2)^{2} + (y-1)^{2} + (z-4)^{2}$
$\Rightarrow 10x + 6y - 18z - 29 = 0$.

Hence, the required curve is $10x + 6y - 18z - 29 = 0$.

---

### Example 5:

Find the equation of the curve formed by the set of all those points the sum of whose distances from the points $A(4,0,0)$ and $B(-4,0,0)$ is 10 units.

#### Solution:

Let $P(x, y, z)$ be an arbitrary point on the given curve. Then,

$$
\begin{align*}
& PA + PB = 10 \\
\Rightarrow & \sqrt{(x-4)^{2}+y^{2}+z^{2}} + \sqrt{(x+4)^{2}+y^{2}+z^{2}} = 10 \\
\Rightarrow & \sqrt{(x+4)^{2}+y^{2}+z^{2}} = 10 - \sqrt{(x-4)^{2}+y^{2}+z^{2}} \tag{i} \\
\Rightarrow & (x+4)^{2}+y^{2}+z^{2} = 100 + (x-4)^{2}+y^{2}+z^{2} - 20 \sqrt{(x-4)^{2}+y^{2}+z^{2}} \\
\end{align*}
$$

[on squaring both sides of (i)]

$$
\begin{align*}
\Rightarrow & \quad 16x = 100 - 20 \sqrt{(x-4)^{2}+y^{2}+z^{2}} \\
\Rightarrow & 5 \sqrt{(x-4)^{2}+y^{2}+z^{2}} = (25-4x) \\
\Rightarrow & 25[(x-4)^{2}+y^{2}+z^{2}] = 625 + 16x^{2} - 200x \\
\Rightarrow & 9x^{2} + 25y^{2} + 25z^{2} - 225 = 0.
\end{align*}
$$

Hence, the required equation of the curve is

$$
9x^{2} + 25y^{2} + 25z^{2} - 225 = 0
$$

---

## Some Useful Results

A quadrilateral $ABCD$ is a:
1. **parallelogram**, if $AB=CD$ and $BC=DA$;
2. **rectangle**, if $AB=CD$, $BC=DA$ and $AC=BD$;
3. **rhombus**, if $AB=BC=CD=DA$ but $AC \neq BD$;
4. **square**, if $AB=BC=CD=DA$ and $AC=BD$.

![](https://cdn.mathpix.com/cropped/2025_09_25_2ca3791f7309a267d86eg-05.jpg?height=213&width=273&top_left_y=281&top_left_x=926)

---

