## Ellipse

An **ellipse** is the path traced by a point which moves in a plane in such a way that the sum of its distance from two fixed points in the plane is a constant.

The two fixed points are called the **foci** of the ellipse.

> **Note:** The plural of focus is foci.

In the given figure, $F_{1}$ and $F_{2}$ are two fixed points and $P$ is a point which moves in such a way that $P F_{1}+P F_{2}=\text{constant}$. The path traced by the point $P$ is called an ellipse, and the points $F_{1}$ and $F_{2}$ are called its foci.

---

## Some More Terms Related to an Ellipse

### Centre of the Ellipse
The midpoint of the line segment joining the foci is called the **centre** of the ellipse. In the given figure, $F_{1}$ and $F_{2}$ are the foci of the ellipse and $O$ is its centre, where $O F_{1}=O F_{2}$.

### Axes of the Ellipse
- **Major Axis**: The line segment through the foci of the ellipse with its end points on the ellipse is called its **major axis**. In the given figure, $AB$ is the major axis of the ellipse.
- **Minor Axis**: The line segment through the centre and perpendicular to the major axis with its end points on the ellipse is called its **minor axis**. In the given figure, $CD$ is the minor axis of the ellipse.

### Vertices of an Ellipse
The end points of the major axis of an ellipse are called its **vertices**. In the given figure, $A$ and $B$ are the vertices of the ellipse.

> **An Important Note:** In an ellipse, we take:
> - Length of the **major axis** $= AB = 2a$.
> - Length of the **minor axis** $= CD = 2b$.
> - Distance between the **foci** $= F_{1} F_{2} = 2c$.
> - Length of the **semi-major axis** $= a$.
> - Length of the **semi-minor axis** $= b$.

### Eccentricity of an Ellipse
The ratio $\frac{c}{a}$ is always constant and it is denoted by $e$, called the **eccentricity** of the ellipse. For an ellipse, we have $0 < e < 1$ since $c < a \Leftrightarrow e = \frac{c}{a} < 1$.

---

## An Important Result

In the given ellipse, it is being given that $AB=2a$, $CD=2b$ and $F_{1} F_{2}=2c$.
**Prove that:** $a^{2}-c^{2} = b^{2}$.

**Proof:**
Clearly, $COD$ is the perpendicular bisector of $F_{1} F_{2}$. Join $F_{1} C$ and $F_{2} C$.
Now, $F_{1} O=c, O C=b \Rightarrow F_{1} C=\sqrt{c^{2}+b^{2}}$.
And, $O F_{2}=c, O C=b \Rightarrow F_{2} C=\sqrt{c^{2}+b^{2}}$.
Since $B$ and $C$ both lie on the given ellipse, we have:

$$
\begin{aligned}
& F_{1} B+F_{2} B=F_{1} C+F_{2} C=\text{constant} \quad [\text{by the definition of an ellipse}] \\
\Rightarrow \quad & \left(F_{1} O+O B\right)+\left(O B-O F_{2}\right)=F_{1} C+F_{2} C \\
\Rightarrow \quad & (c+a)+(a-c)=2 \sqrt{c^{2}+b^{2}} \quad \left[\because F_{1} O=c, O F_{2}=c, O B=a \text{ and } F_{1} C=F_{2} C=\sqrt{c^{2}+b^{2}}\right] \\
\Rightarrow \quad & 2a = 2\sqrt{c^{2}+b^{2}} \\
\Rightarrow \quad & a=\sqrt{c^{2}+b^{2}} \Rightarrow a^{2}=\left(c^{2}+b^{2}\right) \Rightarrow\left(a^{2}-c^{2}\right)=b^{2}
\end{aligned}
$$

Hence, $a^{2}-c^{2}=b^{2}$.

---

## Standard Equation of an Ellipse

### Theorem
*Prove that the standard equation of an ellipse is*

$$
\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1
$$

*where $a$ and $b$ are the lengths of the semi-major axis and the semi-minor axis respectively and $a>b$.*

#### Proof:
Let $X'OX$ and $YOY'$ be the coordinate axes. Let us consider an ellipse in which $a$ and $b$ are the lengths of the semi-major axis and semi-minor axis respectively.

Choose a real number $c$ such that $c^{2}=a^{2}-b^{2}$. Let $F_{1}(-c, 0)$ and $F_{2}(c, 0)$ be the two fixed points and let $P(x, y)$ be an arbitrary point on the given ellipse, moving on it in such a way that $P F_{1}+P F_{2}=2 a$. Then,

$$
\begin{aligned}
& P F_{1}+P F_{2}=2 a \\
\Rightarrow \quad & \sqrt{(x+c)^{2}+y^{2}}+\sqrt{(x-c)^{2}+y^{2}}=2 a \\
\Rightarrow \quad & \sqrt{(x+c)^{2}+y^{2}}=2 a-\sqrt{(x-c)^{2}+y^{2}} \\
\Rightarrow \quad & (x+c)^{2}+y^{2}=4 a^{2}+(x-c)^{2}+y^{2}-4 a \sqrt{(x-c)^{2}+y^{2}} \quad \text{[on squaring both sides]} \\
\Rightarrow \quad & (x+c)^{2}-(x-c)^{2}-4 a^{2}=-4 a \sqrt{(x-c)^{2}+y^{2}} \\
\Rightarrow \quad & 4 c x-4 a^{2}=-4 a \sqrt{(x-c)^{2}+y^{2}} \\
\Rightarrow \quad & \sqrt{(x-c)^{2}+y^{2}}=a-\frac{c x}{a} \quad \text{[on dividing both sides by } -4a] \\
\Rightarrow \quad & (x-c)^{2}+y^{2}=a^{2}-2 c x+\frac{c^{2} x^{2}}{a^{2}} \quad \text{[on squaring both sides]} \\
\Rightarrow \quad & x^{2}-\frac{c^{2} x^{2}}{a^{2}}+y^{2}=\left(a^{2}-c^{2}\right) \\
\Rightarrow \quad & x^{2}\left(1-\frac{c^{2}}{a^{2}}\right)+y^{2}=\left(a^{2}-c^{2}\right) \\
\Rightarrow \quad & \frac{x^{2}\left(a^{2}-c^{2}\right)}{a^{2}}+y^{2}=\left(a^{2}-c^{2}\right) \\
\Rightarrow \quad & \frac{x^{2}}{a^{2}}+\frac{y^{2}}{\left(a^{2}-c^{2}\right)}=1 \quad \text{[on dividing both sides by } (a^2-c^2)] \\
\Rightarrow \quad & \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \quad \left[\because a^{2}-c^{2}=b^{2}\right]
\end{aligned}
$$

Thus, every point on the ellipse satisfies the equation $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$.

**Conversely**, let the equation of the given curve be $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ and let $P(x, y)$ be an arbitrary point on this curve.
Then, $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \Rightarrow y^{2}=b^{2}\left(1-\frac{x^{2}}{a^{2}}\right)$

$$
\Rightarrow \quad y^{2}=\frac{b^{2}\left(a^{2}-x^{2}\right)}{a^{2}} \quad (i)
$$

Also, let $a^{2}-b^{2}=c^{2}$. Let $F_{1}(-c, 0)$ and $F_{2}(c, 0)$ be two fixed points on the $x$-axis. Then,

$$
\begin{align*}
P F_{1} & =\sqrt{(x+c)^{2}+y^{2}} \\
& =\sqrt{(x+c)^{2}+\frac{b^{2}\left(a^{2}-x^{2}\right)}{a^{2}}} \quad [\text{from (i)}]\\
& =\sqrt{(x+c)^{2}+\frac{\left(a^{2}-c^{2}\right)\left(a^{2}-x^{2}\right)}{a^{2}}} \quad [\because b^2 = a^2 - c^2] \\
& =\sqrt{a^{2}+2 c x+\frac{c^{2} x^{2}}{a^{2}}}=\sqrt{\left(a+\frac{c x}{a}\right)^{2}}=\left(a+\frac{c x}{a}\right)
\end{align*}
$$

Similarly, $P F_{2}=\left(a-\frac{c x}{a}\right)$.
$\therefore P F_{1}+P F_{2}=\left(a+\frac{c x}{a}+a-\frac{c x}{a}\right) \Leftrightarrow P F_{1}+P F_{2}=2 a$.

This shows that the given curve is an ellipse. Hence, the equation of the ellipse is $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$.

> **An Important Note:** The foci of an ellipse always lie on the major axis.

---

## Horizontal Ellipse

In the given equation of an ellipse, if the coefficient of $x^{2}$ has the **larger denominator** then its major axis lies along the $x$-axis. Such an ellipse is called a **horizontal ellipse**.

Thus, $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ is a horizontal ellipse, if $a^{2}>b^{2}$.

For example, $\frac{x^{2}}{16}+\frac{y^{2}}{9}=1$ is a horizontal ellipse.

### Latus Rectum of a Horizontal Ellipse

The **latus rectum** of an ellipse is a line segment perpendicular to the major axis, passing through any of the foci with end points lying on the ellipse.

**To Find the Length of Latus Rectum of the Ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1, a>b$**

Let $X'OX$ and $YOY'$ be the coordinate axes. Let $F_{1}(-c, 0)$ and $F_{2}(c, 0)$ be the foci of the given ellipse, where $c^{2}=a^{2}-b^{2}$. Let $LF_{1}M$ and $PF_{2}Q$ be the latus rectums. Let $PF_{2}=l$. Then, the coordinates of $P$ are $P(c, l)$.

Since $P(c, l)$ lies on the ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, we have

$$
\begin{aligned}
\frac{c^{2}}{a^{2}}+\frac{l^{2}}{b^{2}}=1 & \Rightarrow \frac{l^{2}}{b^{2}}=\left(1-\frac{c^{2}}{a^{2}}\right) \\
& \Rightarrow l^{2}=b^{2}\left(1-\frac{c^{2}}{a^{2}}\right)=b^{2}\left[1-\frac{\left(a^{2}-b^{2}\right)}{a^{2}}\right] \quad\left[\because c^{2}=\left(a^{2}-b^{2}\right)\right] \\
& \Rightarrow l^{2}=\frac{b^{4}}{a^{2}} \Rightarrow l=\frac{b^{2}}{a}
\end{aligned}
$$

$\therefore PF_{2}=l=\frac{b^{2}}{a} \Leftrightarrow PF_{2}Q=2l=\frac{2b^{2}}{a}$.
Similarly, $LF_{1}M=2l=\frac{2b^{2}}{a}$.
Hence, the length of the latus rectum is $\frac{2 b^{2}}{a}$.

### Results on Horizontal Ellipse

1.  **Standard Equation:** $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $0<b<a$.
2.  **Centre:** $O(0,0)$.
3.  **Vertices:** $A(-a, 0)$ and $B(a, 0)$.
4.  **Foci:** $F_{1}(-c, 0)$ and $F_{2}(c, 0)$, where $c^{2}=a^{2}-b^{2}$.
5.  **Length of Major Axis:** $2a$.
6.  **Length of Minor Axis:** $2b$.
7.  **Equation of Major Axis:** $y=0$.
8.  **Equation of Minor Axis:** $x=0$.
9.  **Length of Latus Rectum:** $\frac{2 b^{2}}{a}$.
10. **Eccentricity:** $e=\frac{c}{a}=\frac{\sqrt{a^{2}-b^{2}}}{a}$.

---

## Vertical Ellipse

In the given equation of an ellipse, if the coefficient of $y^{2}$ has the **larger denominator**, then its major axis lies along the $y$-axis. Such an ellipse is called a **vertical ellipse**.

### Results on Vertical Ellipse

1.  **Standard Equation:** $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $0<b<a$.
2.  **Centre:** $O(0,0)$.
3.  **Vertices:** $A(0,-a)$ and $B(0, a)$.
4.  **Foci:** $F_{1}(0,-c)$ and $F_{2}(0, c)$, where $c^{2}=a^{2}-b^{2}$. So, $F_{1}(0,-ae)$ and $F_{2}(0, ae)$.
5.  **Length of Major Axis:** $2a$.
6.  **Length of Minor Axis:** $2b$.
7.  **Equation of Major Axis:** $x=0$.
8.  **Equation of Minor Axis:** $y=0$.
9.  **Length of Latus Rectum:** $\frac{2 b^{2}}{a}$.
10. **Eccentricity:** $e=\frac{c}{a}=\frac{\sqrt{a^{2}-b^{2}}}{a}$.

---

## Summary

| Properties | Horizontal Ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$ <br> $0<b<a$ and $c^{2}=a^{2}-b^{2}$ | Vertical Ellipse $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$ <br> $0<b<a$ and $c^{2}=a^{2}-b^{2}$ |
| :--- | :--- | :--- |
| **(i) Centre** | $(0,0)$ | $(0,0)$ |
| **(ii) Vertices** | $A(-a, 0), B(a, 0)$ | $A(0,-a)$ and $B(0, a)$ |
| **(iii) Foci** | $F_{1}(-c, 0)$ and $F_{2}(c, 0)$ or $(-ae, 0)$ and $(ae, 0)$ | $F_{1}(0,-c)$ and $F_{2}(0, c)$ or $(0,-ae)$ and $(0, ae)$ |
| **(iv) Length of the major axis** | $2a$ | $2a$ |
| **(v) Length of the minor axis** | $2b$ | $2b$ |
| **(vi) Equation of the major axis** | $y=0$ | $x=0$ |
| **(vii) Equation of the minor axis** | $x=0$ | $y=0$ |
| **(viii) Length of the latus rectum** | $\frac{2 b^{2}}{a}$ | $\frac{2 b^{2}}{a}$ |
| **(ix) Eccentricity** | $e=\frac{c}{a}=\frac{\sqrt{a^{2}-b^{2}}}{a}$ | $e=\frac{c}{a}=\frac{\sqrt{a^{2}-b^{2}}}{a}$ |

---

## Solved Examples

### Example 1:

Find the lengths of the major and minor axes; coordinates of the vertices and the foci, the eccentricity and length of the latus rectum of the ellipse:
$$
\frac{x^{2}}{16}+\frac{y^{2}}{9}=1
$$

#### Solution:

The given equation is $\frac{x^{2}}{16}+\frac{y^{2}}{9}=1$. This is of the form $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $a^{2}>b^{2}$. So, it is an equation of a **horizontal ellipse**.

Now, $a^{2}=16$ and $b^{2}=9 \Rightarrow a=4$ and $b=3$.
$\therefore c=\sqrt{a^{2}-b^{2}}=\sqrt{16-9}=\sqrt{7}$.
Thus, $a=4, b=3$ and $c=\sqrt{7}$.

1.  **Length of the major axis** $=2a = (2 \times 4) = 8$ units.
    **Length of the minor axis** $=2b = (2 \times 3) = 6$ units.
2.  **Coordinates of the vertices** are $A(-a, 0)$ and $B(a, 0)$, i.e., $A(-4,0)$ and $B(4,0)$.
3.  **Coordinates of the foci** are $F_{1}(-c, 0)$ and $F_{2}(c, 0)$, i.e., $F_{1}(-\sqrt{7}, 0)$ and $F_{2}(\sqrt{7}, 0)$.
4.  **Eccentricity**, $e=\frac{c}{a}=\frac{\sqrt{7}}{4}$.
5.  **Length of the latus rectum** $=\frac{2 b^{2}}{a}=\frac{2 \times 9}{4}=\frac{9}{2}$ units.

---

### Example 2:

Find the lengths of the major and minor axes; coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the ellipse: $4 x^{2}+9 y^{2}=144$.

#### Solution:

The given equation may be written as $\frac{x^{2}}{36}+\frac{y^{2}}{16}=1$.
This is of the form $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $a^{2}>b^{2}$. So, it is an equation of a **horizontal ellipse**.

Now, $a^{2}=36$ and $b^{2}=16 \Rightarrow a=6$ and $b=4$.
$\therefore c=\sqrt{a^{2}-b^{2}}=\sqrt{36-16}=\sqrt{20}=2 \sqrt{5}$.
Thus, $a=6, b=4$ and $c=2 \sqrt{5}$.

1.  **Length of the major axis** $=2a = (2 \times 6) = 12$ units.
    **Length of the minor axis** $=2b = (2 \times 4) = 8$ units.
2.  **Coordinates of the vertices** are $A(-a, 0)$ and $B(a, 0)$, i.e., $A(-6,0)$ and $B(6,0)$.
3.  **Coordinates of the foci** are $F_{1}(-c, 0)$ and $F_{2}(c, 0)$, i.e., $F_{1}(-2 \sqrt{5}, 0)$ and $F_{2}(2 \sqrt{5}, 0)$.
4.  **Eccentricity**, $e=\frac{c}{a}=\frac{2 \sqrt{5}}{6}=\frac{\sqrt{5}}{3}$.
5.  **Length of the latus rectum** $=\frac{2 b^{2}}{a}=\frac{2 \times 16}{6}=\frac{16}{3}$ units.

---

### Example 3:

Find the lengths of the major and minor axes; coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the ellipse:
$$
\frac{x^{2}}{4}+\frac{y^{2}}{36}=1
$$

#### Solution:

The given equation is $\frac{x^{2}}{4}+\frac{y^{2}}{36}=1$. This is of the form $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $a^{2}>b^{2}$. So, it is an equation of a **vertical ellipse**.

Now, $b^{2}=4$ and $a^{2}=36 \Rightarrow b=2$ and $a=6$.
$\therefore c=\sqrt{a^{2}-b^{2}}=\sqrt{36-4}=\sqrt{32}=4 \sqrt{2}$.
Thus, $a=6, b=2$ and $c=4 \sqrt{2}$.

1.  **Length of the major axis** $=2a = (2 \times 6) = 12$ units.
    **Length of the minor axis** $=2b = (2 \times 2) = 4$ units.
2.  **Coordinates of its vertices** are $A(0, -a)$ and $B(0, a)$, i.e., $A(0,-6)$ and $B(0,6)$.
3.  **Coordinates of its foci** are $F_{1}(0, -c)$ and $F_{2}(0, c)$, i.e., $F_{1}(0, -4 \sqrt{2})$ and $F_{2}(0, 4 \sqrt{2})$.
4.  **Eccentricity**, $e=\frac{c}{a}=\frac{4 \sqrt{2}}{6}=\frac{2 \sqrt{2}}{3}$.
5.  **Length of the latus rectum** $=\frac{2 b^{2}}{a}=\frac{2 \times 4}{6}=\frac{4}{3}$ units.

---

### Example 4:

Find the lengths of the major and minor axes; coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the ellipse: $4 x^{2}+y^{2}=100$.

#### Solution:

The given equation of the ellipse may be written as $\frac{x^{2}}{25}+\frac{y^{2}}{100}=1$.
This is of the form $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $a^{2}>b^{2}$. So, it is an equation of a **vertical ellipse**.

Now, $b^{2}=25$ and $a^{2}=100 \Rightarrow b=5$ and $a=10$.
$\therefore c=\sqrt{a^{2}-b^{2}}=\sqrt{100-25}=\sqrt{75}=5 \sqrt{3}$.
Thus, $a=10, b=5$ and $c=5 \sqrt{3}$.

1.  **Length of the major axis** $=2a = (2 \times 10) = 20$ units.
    **Length of the minor axis** $=2b = (2 \times 5) = 10$ units.
2.  **Coordinates of the vertices** are $A(0, -a)$ and $B(0, a)$, i.e., $A(0,-10)$ and $B(0,10)$.
3.  **Coordinates of the foci** are $F_{1}(0, -c)$ and $F_{2}(0, c)$, i.e., $F_{1}(0, -5 \sqrt{3})$ and $F_{2}(0, 5 \sqrt{3})$.
4.  **Eccentricity**, $e=\frac{c}{a}=\frac{5 \sqrt{3}}{10}=\frac{\sqrt{3}}{2}$.
5.  **Length of the latus rectum** $=\frac{2 b^{2}}{a}=\frac{2 \times 25}{10}=5$ units.

---

### Example 5:

Find the equation of an ellipse whose vertices are at $(\pm 5,0)$ and foci at $(\pm 4,0)$.

#### Solution:

Since the vertices of the given ellipse are on the $x$-axis, it is a **horizontal ellipse**. Let the equation of the ellipse be $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $a^{2}>b^{2}$.

Its vertices are $(\pm a, 0)$, and therefore, $a=5$.
Its foci are $(\pm c, 0)$, and therefore, $c=4$.

$\therefore c^{2}=a^{2}-b^{2} \Rightarrow b^{2}=a^{2}-c^{2}=25-16=9$.
Thus, $a^{2}=5^{2}=25$ and $b^{2}=9$.
Hence, the required equation is $\frac{x^{2}}{25}+\frac{y^{2}}{9}=1$.

---

### Example 6:

Find the equation of an ellipse whose foci are $(\pm 4,0)$ and the eccentricity is $\frac{1}{3}$.

#### Solution:

Since the foci of the given ellipse are on the $x$-axis, it is a **horizontal ellipse**.
Let the required equation of the ellipse be $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $a^{2}>b^{2}$.

Let its foci be $(\pm c, 0)$. Then, $c=4$.
Also, $e=\frac{c}{a} \Leftrightarrow a=\frac{c}{e}=\frac{4}{(1 / 3)}=12$.
Now, $c^{2}=a^{2}-b^{2} \Rightarrow b^{2}=a^{2}-c^{2}=144-16=128$.
$\therefore a^{2}=12^{2}=144$ and $b^{2}=128$.
Hence, the required equation is $\frac{x^{2}}{144}+\frac{y^{2}}{128}=1$.

---

### Example 7:

Find the equation of an ellipse whose major axis lies on the $x$-axis and which passes through the points $(4,3)$ and $(6,2)$.

#### Solution:

Since the major axis of the ellipse lies on the $x$-axis, it is a **horizontal ellipse**.
Let the required equation of the ellipse be:
$$
\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \quad (\text{where } a^{2}>b^{2}) \quad (i)
$$
Since $(4,3)$ lies on (i), we have $\frac{16}{a^{2}}+\frac{9}{b^{2}}=1 \quad (ii)$.
Also, since $(6,2)$ lies on (i), we have $\frac{36}{a^{2}}+\frac{4}{b^{2}}=1 \quad (iii)$.

Putting $\frac{1}{a^{2}}=u$ and $\frac{1}{b^{2}}=v$ in (ii) and (iii), we get:
$$
\begin{align*}
& 16u + 9v = 1 \quad &(iv)\\
& 36u + 4v = 1 \quad &(v)
\end{align*}
$$
On multiplying (iv) by 4 and (v) by 9, we can subtract them. A different approach: multiplying (iv) by 9 and (v) by 4 and subtracting:
$9 \times (16u + 9v) - 4 \times (36u+4v) = 9 \times 1 - 4 \times 1$
$144u + 81v - (144u + 16v) = 5$
$65v = 5 \Leftrightarrow v=\frac{1}{13} \Leftrightarrow \frac{1}{b^{2}}=\frac{1}{13} \Leftrightarrow b^{2}=13$.

Putting $v=\frac{1}{13}$ in (iv), we get:
$16 u + 9(\frac{1}{13}) = 1 \Leftrightarrow 16 u=1-\frac{9}{13} \Leftrightarrow 16 u=\frac{4}{13} \Leftrightarrow u=\frac{4}{13 \times 16}=\frac{1}{52}$.
$\Leftrightarrow \frac{1}{a^{2}}=\frac{1}{52} \Leftrightarrow a^{2}=52$.

Thus, $a^{2}=52$ and $b^{2}=13$.
Hence, the required equation is $\frac{x^{2}}{52}+\frac{y^{2}}{13}=1$.

---

### Example 8:

Find the equation of the ellipse, the ends of whose major axis are $(\pm 3,0)$ and the ends of whose minor axis are $(0, \pm 2)$.

#### Solution:

Clearly, the major axis of the given ellipse lies on the $x$-axis. So, it is a **horizontal ellipse**. Let the required equation be $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $a^{2}>b^{2}$.

Its vertices are $(\pm a, 0)$, and therefore, $a=3$ [$\because$ ends of the major axis are the vertices].
Ends of the minor axis are $C(0,-2)$ and $D(0,2)$.
$\therefore CD=4$, i.e., length of the minor axis $=4$ units.
$\therefore 2b=4 \Leftrightarrow b=2$.
Now, $a=3$ and $b=2 \Rightarrow a^{2}=9$ and $b^{2}=4$.
Hence, the required equation is $\frac{x^{2}}{9}+\frac{y^{2}}{4}=1$.

---

### Example 9:

Find the equation of the ellipse whose centre lies at the origin, major axis lies on the $x$-axis, the eccentricity is $\frac{2}{3}$ and the length of the latus rectum is 5 units.

#### Solution:

Since the major axis of the ellipse lies on the $x$-axis, it is a **horizontal ellipse**. Let the required equation be $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, where $a^{2}>b^{2}$.

Length of its latus rectum $=\frac{2b^{2}}{a}$.
$$
\begin{aligned}
& \therefore \quad \frac{2 b^{2}}{a}=5 \Leftrightarrow \frac{2 a^{2}\left(1-e^{2}\right)}{a}=5 \quad \left[\because b^{2}=a^{2}\left(1-e^{2}\right)\right] \\
& \Leftrightarrow \quad 2a(1-e^2) = 5 \\
& \Leftrightarrow \quad a=\frac{5}{2\left(1-e^{2}\right)}=\frac{5}{2\left(1-\frac{4}{9}\right)}=\frac{5}{2\left(\frac{5}{9}\right)}=\left(\frac{5}{2} \times \frac{9}{5}\right)=\frac{9}{2}.
\end{aligned}
$$
Also, $b^{2}=a^{2}\left(1-e^{2}\right)=\frac{81}{4} \times\left(1-\frac{4}{9}\right)=\left(\frac{81}{4} \times \frac{5}{9}\right)=\frac{45}{4}$.
$\therefore a^{2}=\left(\frac{9}{2}\right)^{2}=\frac{81}{4}$ and $b^{2}=\frac{45}{4}$.
Hence, the required equation is:
$$
\frac{x^{2}}{(81 / 4)}+\frac{y^{2}}{(45 / 4)}=1 \Leftrightarrow \frac{4 x^{2}}{81}+\frac{4 y^{2}}{45}=1 \Leftrightarrow 20 x^{2}+36 y^{2}=405 .
$$

---

### Example 10:

Find the equation of an ellipse whose vertices are $(0, \pm 13)$ and the foci are $(0, \pm 5)$.

#### Solution:

Since the vertices of the ellipse lie on the $y$-axis, it is a **vertical ellipse**. Let the required equation be $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $a^{2}>b^{2}$.

Its vertices are $(0, \pm a)$ and therefore, $a=13$.
Let its foci be $(0, \pm c)$. Then, $c=5$.
$\therefore b^{2}=a^{2}-c^{2} = 169-25=144$.
Thus, $b^{2}=144$ and $a^{2}=13^{2}=169$.
Hence, the required equation is $\frac{x^{2}}{144}+\frac{y^{2}}{169}=1$.

---

### Example 11:

Find the equation of the ellipse whose foci are $(0, \pm 6)$ and the length of whose minor axis is 16.

#### Solution:

Since the foci of the given ellipse lie on the $y$-axis, it is a **vertical ellipse**. Let the required equation be $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $a^{2}>b^{2}$.

Let $c^{2}=a^{2}-b^{2}$. Then, its foci are $(0, \pm c)$ and therefore, $c=6$.
Also, length of the minor axis is $2b=16$, so $b=8$.
$\therefore a^{2}=c^{2}+b^{2}=36+64=100$.
Thus, $b^{2}=64$ and $a^{2}=100$.
Hence, the required equation is $\frac{x^{2}}{64}+\frac{y^{2}}{100}=1$.

---

### Example 12:

Find the equation of the ellipse whose foci are $(0, \pm 5)$ and the length of whose major axis is 20.

#### Solution:

Since the foci of the ellipse lie on the $y$-axis, it is a **vertical ellipse**. Let the required equation be $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $a^{2}>b^{2}$.

Let $c^{2}=a^{2}-b^{2}$. Its foci are $(0, \pm c)$ and therefore, $c=5$.
Also, length of the major axis is $2a=20$, so $a=10$.
Now, $c^{2}=a^{2}-b^{2} \Leftrightarrow b^{2}=a^{2}-c^{2}=100-25=75$.
Thus, $a^{2}=10^{2}=100$ and $b^{2}=75$.
Hence, the required equation is $\frac{x^{2}}{75}+\frac{y^{2}}{100}=1$.

---

### Example 13:

Find the equation of the ellipse for which $e=\frac{4}{5}$ and whose vertices are $(0, \pm 10)$.

#### Solution:

Since the vertices of the ellipse lie on the $y$-axis, it is a **vertical ellipse**. Let the required equation be $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1$, where $a^{2}>b^{2}$.

Its vertices are $(0, \pm a)$ and therefore, $a=10$.
Let $c^{2}=a^{2}-b^{2}$.
Then, $e=\frac{c}{a} \Rightarrow c=ae=\left(10 \times \frac{4}{5}\right)=8$.
Now, $c^{2}=a^{2}-b^{2} \Leftrightarrow b^{2}=a^{2}-c^{2}=100-64=36$.
$\therefore a^{2}=10^{2}=100$ and $b^{2}=36$.
Hence, the required equation is $\frac{x^{2}}{36}+\frac{y^{2}}{100}=1$.

---

### Example 14:

Find the equation of the ellipse with centre at the origin, major-axis on the $y$-axis and passing through the points $(3,2)$ and $(1,6)$.

#### Solution:

Since the major axis of the ellipse lies on the $y$-axis, it is a **vertical ellipse**.
Let the required equation be $\frac{x^{2}}{b^{2}}+\frac{y^{2}}{a^{2}}=1 \quad(\text{where } a^{2}>b^{2}) \quad (i)$.

Since $(3,2)$ lies on (i), we have $\frac{9}{b^{2}}+\frac{4}{a^{2}}=1 \quad (ii)$.
Also, since $(1,6)$ lies on (i), we have $\frac{1}{b^{2}}+\frac{36}{a^{2}}=1 \quad (iii)$.

Putting $\frac{1}{b^{2}}=u$ and $\frac{1}{a^{2}}=v$, these equations become:
$$
\begin{align*}
& 9u + 4v = 1 \quad &(iv)\\
& u + 36v = 1 \quad &(v)
\end{align*}
$$
On multiplying (v) by 9 and subtracting (iv) from it, we get:
$9(u+36v) - (9u+4v) = 9(1) - 1$
$9u + 324v - 9u - 4v = 8$
$320v = 8 \Leftrightarrow v=\frac{8}{320}=\frac{1}{40} \Leftrightarrow \frac{1}{a^{2}}=\frac{1}{40} \Leftrightarrow a^{2}=40$.

Putting $v=\frac{1}{40}$ in (v), we get:
$u + 36\left(\frac{1}{40}\right)=1 \Leftrightarrow u=1-\frac{36}{40}=1-\frac{9}{10}=\frac{1}{10}$.
$\Leftrightarrow \frac{1}{b^{2}}=\frac{1}{10} \Leftrightarrow b^{2}=10$.

Thus, $b^{2}=10$ and $a^{2}=40$.
Hence, the required equation is $\frac{x^{2}}{10}+\frac{y^{2}}{40}=1$.

---

