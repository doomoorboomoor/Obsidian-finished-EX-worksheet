# Straight Lines

## Introduction

A systematic study of geometry by using algebra was first carried out by French mathematician $R$ Descartes in 1637. This subject is now known as **Coordinate Geometry**.

In earlier classes, we have studied about coordinate axis, coordinate plane, points in a plane, distance between two points and section formulae.

Here, we give, in brief, the results derived so far.

1.  **Distance** between the points $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ is given by
    
    $$
    A B=\sqrt{(x_{2}-x_{1})^{2}+(y_{2}-y_{1})^{2}}
    $$

2.  **Area** of $\triangle A B C$ whose vertices are $A(x_{1}, y_{1})$, $B(x_{2}, y_{2})$ and $C(x_{3}, y_{3})$ is given by
    
    $$
    \Delta=\frac{1}{2} \cdot\left|x_{1}(y_{2}-y_{3})+x_{2}(y_{3}-y_{1})+x_{3}(y_{1}-y_{2})\right| \text{ sq units.}
    $$
    
    *Remark:* The points $A, B, C$ are **collinear** $\Leftrightarrow$ area of $\triangle A B C=0$.

3.  **Section Formula**:
    
    -   (i) If the point $P(x, y)$ divides the join of $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ in the ratio $m: n$ then
        
        $$
        x=\frac{m x_{2}+n x_{1}}{m+n} \quad \text{ and } \quad y=\frac{m y_{2}+n y_{1}}{m+n}
        $$
    
    -   (ii) If $P(x, y)$ is the **midpoint** of the line segment joining $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ then
        
        $$
        x=\frac{1}{2}(x_{1}+x_{2}) \quad \text{ and } \quad y=\frac{1}{2}(y_{1}+y_{2})
        $$

---

## Solved Examples

### Example 1
Find the distance between the points $(2, -3)$ and $(-6, 3)$.

#### Solution
Let $A(2, -3)$ and $B(-6, 3)$ be the given points. Then,

$$
\begin{aligned}
A B &=\sqrt{(-6-2)^{2}+\{3-(-3)\}^{2}} \\
&=\sqrt{(-8)^{2}+(3+3)^{2}} \\
&=\sqrt{(-8)^{2}+6^{2}} \\
&=\sqrt{64+36} \\
&=\sqrt{100}=10 \text{ units.}
\end{aligned}
$$

---

### Example 2
Using the distance formula, prove that the points $A(-2, 3)$, $B(1, 2)$ and $C(7, 0)$ are collinear.

#### Solution
We have

$$
\begin{align*}
A B &=\sqrt{(1+2)^{2}+(2-3)^{2}}=\sqrt{3^{2}+(-1)^{2}}=\sqrt{10} \text{ units;} \\
B C &=\sqrt{(7-1)^{2}+(0-2)^{2}}=\sqrt{6^{2}+(-2)^{2}}=\sqrt{40}=2 \sqrt{10} \text{ units;} \\
A C &=\sqrt{(7+2)^{2}+(0-3)^{2}}=\sqrt{9^{2}+(-3)^{2}}=\sqrt{90}=3 \sqrt{10} \text{ units.}
\end{align*}
$$

$\therefore \quad A B+B C=(\sqrt{10}+2 \sqrt{10}) \text{ units }=3 \sqrt{10} \text{ units }=A C$

Thus, $A B+B C=A C$, showing that the points $A, B, C$ are **collinear**.

---

## Some Important Results

A quadrilateral is a:
- (i) **rectangle**, if its opposite sides are equal and the diagonals are equal;
- (ii) **square**, if its all sides are equal and the diagonals are equal;
- (iii) a **parallelogram** but not a rectangle, if its opposite sides are equal but the diagonals are not equal;
- (iv) a **rhombus** but not a square, if its all sides are equal but the diagonals are not equal.

---

### Example 3
Prove that the points $(0, 5)$, $(-2, -2)$, $(5, 0)$ and $(7, 7)$ are the vertices of a rhombus.

#### Solution
Let the given points be $A(0, 5)$, $B(-2, -2)$, $C(5, 0)$ and $D(7, 7)$. Then, $A B C D$ is a quadrilateral in which:

$A B=\sqrt{(-2-0)^{2}+(-2-5)^{2}}=\sqrt{(-2)^{2}+(-7)^{2}}=\sqrt{4+49}=\sqrt{53}$ units;
$B C=\sqrt{(5+2)^{2}+(0+2)^{2}}=\sqrt{7^{2}+2^{2}}=\sqrt{49+4}=\sqrt{53}$ units;
$C D=\sqrt{(7-5)^{2}+(7-0)^{2}}=\sqrt{2^{2}+7^{2}}=\sqrt{4+49}=\sqrt{53}$ units;
$D A=\sqrt{(7-0)^{2}+(7-5)^{2}}=\sqrt{7^{2}+2^{2}}=\sqrt{49+4}=\sqrt{53}$ units.

Thus, $A B=B C=C D=D A=\sqrt{53}$ units.

Also, the diagonals are:
$A C=\sqrt{(5-0)^{2}+(0-5)^{2}}=\sqrt{5^{2}+(-5)^{2}}=\sqrt{50}=5 \sqrt{2}$ units
And, $B D=\sqrt{(7+2)^{2}+(7+2)^{2}}=\sqrt{9^{2}+9^{2}}=\sqrt{81+81}=\sqrt{162}=9 \sqrt{2}$ units.

$\therefore \quad A C \neq B D$.

Thus, $A B C D$ is a quadrilateral all of whose sides are equal but its diagonals are not equal.
Hence, $A B C D$ is a **rhombus**.

---

### Example 4
Find the area of the triangle whose vertices are $A(4, 4)$, $B(3, -16)$ and $C(3, -2)$.

#### Solution
Let $(x_{1}=4, y_{1}=4)$; $(x_{2}=3, y_{2}=-16)$ and $(x_{3}=3, y_{3}=-2)$.

Then, area of $\triangle A B C$ is given by

$$
\begin{aligned}
\Delta &=\frac{1}{2} \cdot\left|x_{1}(y_{2}-y_{3})+x_{2}(y_{3}-y_{1})+x_{3}(y_{1}-y_{2})\right| \\
&=\frac{1}{2} \cdot|4(-16+2)+3(-2-4)+3(4+16)| \\
&=\frac{1}{2} \cdot|-56-18+60| \\
&=\frac{1}{2} \cdot|-14| \\
&=\left(\frac{1}{2} \times 14\right)=7 \text{ sq units.}
\end{aligned}
$$

Hence, the area of the given triangle is **7 sq units**.

---

### Example 5
Find the coordinates of the point which divides the line segment joining the points $A(5, -2)$ and $B(9, 6)$ in the ratio $3: 1$.

#### Solution
Here $(x_{1}=5, y_{1}=-2)$ and $(x_{2}=9, y_{2}=6)$. Also, $m=3$ and $n=1$.
Let the required point be $P(x, y)$. Then,

$$
x=\frac{(m x_{2}+n x_{1})}{(m+n)}=\frac{(3 \times 9)+(1 \times 5)}{(3+1)}=\frac{32}{4}=8
$$

$$
y=\frac{(m y_{2}+n y_{1})}{(m+n)}=\frac{(3 \times 6)+\{1 \times(-2)\}}{(3+1)}=\frac{(18-2)}{4}=\frac{16}{4}=4
$$

Hence, the required point is $(8, 4)$.

---

### Example 6
Find the coordinates of the midpoint of the line segment joining the points $A(-2, -5)$ and $B(3, -1)$.

#### Solution
Let the required point be $P(x, y)$. Then,

$$
x=\frac{(-2+3)}{2}=\frac{1}{2}, \quad y=\frac{-5+(-1)}{2}=-3
$$

Hence, the required point is $\left(\frac{1}{2},-3\right)$.

---

### Example 7
In what ratio is the line joining $A(-1, 1)$ and $B(5, 7)$ divided by the line $x+y=4$?

#### Solution
Let the given line divide $A B$ in the ratio $m: 1$.
Then, the point of division is $C\left(\frac{5 m-1}{m+1}, \frac{7 m+1}{m+1}\right)$.
This point $C$ must lie on the line $x+y=4$.

$$
\begin{aligned}
\therefore \quad \frac{5 m-1}{m+1}+\frac{7 m+1}{m+1}=4 & \Leftrightarrow(5 m-1)+(7 m+1)=4(m+1) \\
& \Leftrightarrow 12m = 4m + 4 \\
& \Leftrightarrow 8 m=4 \\
& \Leftrightarrow m=\frac{1}{2}
\end{aligned}
$$

So, the required ratio is $\frac{1}{2}: 1$, i.e., $1: 2$.

---

