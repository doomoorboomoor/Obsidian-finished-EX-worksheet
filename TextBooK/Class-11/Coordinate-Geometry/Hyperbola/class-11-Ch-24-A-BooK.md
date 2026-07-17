## Hyperbola

A **hyperbola** is the set of all points in a plane, the difference of whose distances from two fixed points in the plane is a constant.

The two fixed points are called the **foci** of the hyperbola.

---

## Some More Terms Related to a Hyperbola

### Centre of the Hyperbola

The midpoint of the line segment joining the foci is called the **centre** of the hyperbola.

In the given figure, $F_{1}$ and $F_{2}$ are the foci of the hyperbola and $O$ is its centre, where $OF_{1} = OF_{2}$.

![](https://cdn.mathpix.com/cropped/2025_09_25_17a30c345e7a77900ce3g-01.jpg?height=345&width=515&top_left_y=936&top_left_x=392)

### Axes of the Hyperbola

- **Transverse Axis**: The line through the foci of the hyperbola is called its transverse axis. In the given figure, $X'OX$ is the transverse axis of the hyperbola.

- **Conjugate Axis**: The line through the centre and perpendicular to the transverse axis of the hyperbola is called its conjugate axis. Thus, $COD$ is the conjugate axis of the hyperbola in the given figure.

### Vertices of the Hyperbola

The points at which the hyperbola intersects the transverse axis are called its **vertices**. In the given figure, $A$ and $B$ are the vertices of the hyperbola.

### Length of Transverse Axis

The distance between the two vertices of a hyperbola is called the length of its **transverse axis**. In the given hyperbola, length of the transverse axis $= AB$.

> **An Important Note**
> In a hyperbola, we take:
> - Length of the transverse axis $= AB = 2a$.
> - Distance between the foci $= F_{1}F_{2} = 2c$, where $c > a$.
> - Length of the conjugate axis $= 2b$, where $b^{2} = (c^{2} - a^{2})$.

### Eccentricity of a Hyperbola

The ratio $\frac{c}{a}$ is always constant, called the **eccentricity** of the hyperbola and it is denoted by $e$.

Here, $c > a \Leftrightarrow \frac{c}{a} > 1 \Leftrightarrow e > 1$.

---

## Standard Equation of a Hyperbola

**Theorem:** Prove that the standard equation of a hyperbola is
$$
\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1
$$

**Proof:** Let $X'OX$ and $YOY'$ be the coordinate axes.

Let us consider a hyperbola with centre at $O(0,0)$ and its foci at $F_{1}(-c, 0)$ and $F_{2}(c, 0)$.

![](https://cdn.mathpix.com/cropped/2025_09_25_17a30c345e7a77900ce3g-02.jpg?height=345&width=513&top_left_y=978&top_left_x=392)

Let $P(x, y)$ be an arbitrary point on the hyperbola such that $PF_{1} - PF_{2} = 2a$. Then,
$PF_{1} - PF_{2} = 2a$
$\Rightarrow \sqrt{(x+c)^{2}+y^{2}}-\sqrt{(x-c)^{2}+y^{2}}=2a$
$\Rightarrow \sqrt{(x+c)^{2}+y^{2}}=2a+\sqrt{(x-c)^{2}+y^{2}}$
$\Rightarrow (x+c)^{2}+y^{2}=4a^{2}+(x-c)^{2}+y^{2}+4a\sqrt{(x-c)^{2}+y^{2}}$
$\Rightarrow (x+c)^{2}-(x-c)^{2}-4a^{2}=4a\sqrt{(x-c)^{2}+y^{2}}$
$\Rightarrow 4cx-4a^{2}=4a\sqrt{(x-c)^{2}+y^{2}}$
$\Rightarrow \left(\frac{cx}{a}-a\right)=\sqrt{(x-c)^{2}+y^{2}}$
$\Rightarrow \left(\frac{cx}{a}-a\right)^{2}=(x-c)^{2}+y^{2}$
$\Rightarrow \frac{c^{2}x^{2}}{a^{2}}+a^{2}=x^{2}+c^{2}+y^{2}$
$\Rightarrow x^{2}\left(\frac{c^{2}}{a^{2}}-1\right)-y^{2}=(c^{2}-a^{2})$
$\Rightarrow x^{2}(c^{2}-a^{2})-a^{2}y^{2}=a^{2}(c^{2}-a^{2})$
$\Rightarrow \frac{x^{2}}{a^{2}}-\frac{y^{2}}{(c^{2}-a^{2})}=1$
$\Rightarrow \frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$, where $(c^{2}-a^{2})=b^{2}$.

Thus, every point on the given hyperbola satisfies the equation
$$
\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1
$$
Conversely, let the equation of the given curve be $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$ and let $P(x, y)$ be an arbitrary point on it. Then,
$$
\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1 \Rightarrow y^{2}=b^{2}\left(\frac{x^{2}}{a^{2}}-1\right) \Rightarrow y^{2}=\frac{b^{2}(x^{2}-a^{2})}{a^{2}} \tag{i}
$$
Let $c^{2}=(a^{2}+b^{2})$. Let $F_{1}(-c, 0)$ and $F_{2}(c, 0)$ be two fixed points on the x-axis. Then,
$$
\begin{align*}
PF_{1} & =\sqrt{(x+c)^{2}+y^{2}} \\
& =\sqrt{(x+c)^{2}+\frac{b^{2}(x^{2}-a^{2})}{a^{2}}} \quad \text{[Using (i)]} \\
& =\sqrt{(x+c)^{2}+\frac{(c^{2}-a^{2})(x^{2}-a^{2})}{a^{2}}} \\
& =\sqrt{(x^{2}+c^{2}+2cx)+\frac{(c^{2}x^{2}-c^{2}a^{2}-a^{2}x^{2}+a^{4})}{a^{2}}} \\
& =\sqrt{(x^{2}+c^{2}+2cx)+\frac{c^{2}x^{2}}{a^{2}}-c^{2}-x^{2}+a^{2}} \\
& =\sqrt{\frac{c^{2}x^{2}}{a^{2}}+a^{2}+2cx}=\sqrt{\left(\frac{cx}{a}+a\right)^{2}}=\left(\frac{cx}{a}+a\right)
\end{align*}
$$
Similarly, $PF_{2}=\left(\frac{cx}{a}-a\right)$, since $x \geq a$ and $c \geq a \Rightarrow \frac{x}{a} \geq 1$ and $c \geq a \Rightarrow \frac{cx}{a} \geq a$.

$\therefore PF_{1}-PF_{2}=\left(\frac{cx}{a}+a\right)-\left(\frac{cx}{a}-a\right)=2a$.

This shows that $P$ lies on the hyperbola. Thus, every point that satisfies $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$, lies on the hyperbola.

Hence, the equation of a hyperbola with origin $(0,0)$ and transverse axis along the x-axis is given by
$$
\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1
$$

**Remark:** A hyperbola in which $a=b$ is called an **equilateral hyperbola**.

---

## Latus Rectum of a Hyperbola

The **latus rectum** of a hyperbola is a line segment perpendicular to the transverse axis, through any of the foci with its end points lying on the hyperbola.

### To Find the Length of the Latus Rectum of the Hyperbola $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$

Let $X'OX$ and $YOY'$ be the coordinate axes. Let $F_{1}(-c, 0)$ and $F_{2}(c, 0)$ be the foci of the given hyperbola, where $c^{2}=(a^{2}+b^{2})$.

Let $LF_{1}M$ and $PF_{2}Q$ be the latus rectums.

Let $PF_{2}=l$. Then, the coordinates of $P$ are $P(c, l)$.

Since $P(c, l)$ lies on the hyperbola $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$, we have
$$
\frac{c^{2}}{a^{2}}-\frac{l^{2}}{b^{2}}=1 \Rightarrow \frac{l^{2}}{b^{2}}=\left(\frac{c^{2}}{a^{2}}-1\right)
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_17a30c345e7a77900ce3g-04.jpg?height=345&width=507&top_left_y=890&top_left_x=688)
$$
\begin{aligned}
& \Rightarrow l^{2}=b^{2}\left(\frac{c^{2}}{a^{2}}-1\right)=b^{2} \cdot\left\{\frac{(a^{2}+b^{2})}{a^{2}}-1\right\} && [\because c^{2}=(a^{2}+b^{2})] \\
& \Rightarrow l^{2}=\frac{b^{4}}{a^{2}} \\
& \Rightarrow l=\frac{b^{2}}{a}
\end{aligned}
$$
$\therefore PF_{2}=l=\frac{b^{2}}{a} \Leftrightarrow PF_{2}Q=2l=\frac{2b^{2}}{a}$.

Similarly, $LF_{1}M=2l=\frac{2b^{2}}{a}$.

Hence, the length of the latus rectum is $\frac{2b^{2}}{a}$.

---

## Summary of Results on Horizontal Hyperbola

![](https://cdn.mathpix.com/cropped/2025_09_25_17a30c345e7a77900ce3g-05.jpg?height=343&width=557&top_left_y=201&top_left_x=372)

- **Equation**: The standard equation of a horizontal hyperbola is $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.
- **Centre**: Its centre is $O(0,0)$.
- **Axes**: $X'OX$ is the transverse axis and $YOY'$ is the conjugate axis.
- **Foci**: Its foci are $F_{1}(-c, 0)$ and $F_{2}(c, 0)$, i.e., $F_{1}(-ae, 0)$ and $F_{2}(ae, 0)$.
- **Vertices**: Its vertices are $A(-a, 0)$ and $B(a, 0)$.
- **Eccentricity**: Its eccentricity is $e=\frac{c}{a}=\frac{\sqrt{a^{2}+b^{2}}}{a}$.
- **Transverse Axis**: Length of the transverse axis $= 2a$ and its equation is $y=0$.
- **Conjugate Axis**: Length of the conjugate axis $= 2b$ and its equation is $x=0$.
- **Latus Rectum**: Length of its latus rectum $= \frac{2b^{2}}{a}$.

---

## Summary of Results on Vertical Hyperbola

![](https://cdn.mathpix.com/cropped/2025_09_25_17a30c345e7a77900ce3g-05.jpg?height=561&width=354&top_left_y=1143&top_left_x=841)

- **Equation**: The standard equation of a vertical hyperbola is $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$.
- **Centre**: Its centre is $O(0,0)$.
- **Axes**: $YOY'$ is the transverse axis and $X'OX$ is the conjugate axis.
- **Foci**: Its foci are $F_{1}(0,-c)$ and $F_{2}(0, c)$, i.e., $F_{1}(0,-ae)$ and $F_{2}(0, ae)$.
- **Vertices**: Its vertices are $A(0,-a)$ and $B(0, a)$.
- **Eccentricity**: Its eccentricity is $e=\frac{c}{a}=\frac{\sqrt{a^{2}+b^{2}}}{a}$.
- **Transverse Axis**: Length of the transverse axis $= 2a$ and its equation is $x=0$.
- **Conjugate Axis**: Length of the conjugate axis $= 2b$ and its equation is $y=0$.
- **Latus Rectum**: Length of its latus rectum $= \frac{2b^{2}}{a}$.

---

## Solved Examples

### Example: 1

Find the lengths of the axes; the coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the hyperbola $\frac{x^{2}}{36}-\frac{y^{2}}{64}=1$.

#### Solution:

The equation of the given hyperbola is $\frac{x^{2}}{36}-\frac{y^{2}}{64}=1$.
Comparing the given equation with $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$, we get $a^{2}=36$ and $b^{2}=64$.

$\therefore a=6, b=8$ and $c=\sqrt{a^{2}+b^{2}}=\sqrt{36+64}=\sqrt{100}=10$.

- **Lengths of axes**:
    - Length of the transverse axis $= 2a = (2 \times 6) = 12$ units.
    - Length of the conjugate axis $= 2b = (2 \times 8) = 16$ units.
- **Vertices**: The coordinates of the vertices are $A(-a, 0)$ and $B(a, 0)$, i.e., $A(-6,0)$ and $B(6,0)$.
- **Foci**: The coordinates of the foci are $F_{1}(-c, 0)$ and $F_{2}(c, 0)$, i.e., $F_{1}(-10,0)$ and $F_{2}(10,0)$.
- **Eccentricity**: $e=\frac{c}{a}=\frac{10}{6}=\frac{5}{3}$.
- **Latus Rectum**: Length of the latus rectum $=\frac{2b^{2}}{a}=\frac{2 \times 64}{6} = \frac{64}{3}$ units.

---

### Example: 2

Find the lengths of the axes; the coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the hyperbola $9x^{2}-16y^{2}=144$.

#### Solution:

The given equation is $9x^{2}-16y^{2}=144 \Rightarrow \frac{x^{2}}{16}-\frac{y^{2}}{9}=1$.
Comparing this equation with $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$, we get $a^{2}=16$ and $b^{2}=9$.

$\therefore a=4, b=3$ and $c=\sqrt{a^{2}+b^{2}}=\sqrt{16+9}=\sqrt{25}=5$.

- **Lengths of axes**:
    - Length of the transverse axis $= 2a = (2 \times 4) = 8$ units.
    - Length of the conjugate axis $= 2b = (2 \times 3) = 6$ units.
- **Vertices**: The coordinates of the vertices are $A(-a, 0)$ and $B(a, 0)$, i.e., $A(-4,0)$ and $B(4,0)$.
- **Foci**: The coordinates of the foci are $F_{1}(-c, 0)$ and $F_{2}(c, 0)$, i.e., $F_{1}(-5,0)$ and $F_{2}(5,0)$.
- **Eccentricity**: $e=\frac{c}{a}=\frac{5}{4}$.
- **Latus Rectum**: Length of the latus rectum $=\frac{2b^{2}}{a}=\frac{2 \times 9}{4} = \frac{9}{2}$ units.

---

### Example: 3

Find the equation of the hyperbola whose vertices are $(\pm 2,0)$ and the foci are $(\pm 3,0)$.

#### Solution:

Since the vertices are of the form $(\pm a, 0)$, it is a horizontal hyperbola.
Let the required equation be $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.

The vertices are given as $(\pm 2,0)$, so $a=2$.
The foci are given as $(\pm 3,0)$, so $c=3$.

Now, we find $b^{2}$:
$b^{2}=(c^{2}-a^{2})=(3^{2}-2^{2})=(9-4)=5$.

Thus, $a^{2}=2^{2}=4$ and $b^{2}=5$.
Hence, the required equation is $\frac{x^{2}}{4}-\frac{y^{2}}{5}=1$.

---

### Example: 4

Find the equation of the hyperbola whose foci are $(\pm 5,0)$ and the transverse axis is of length 8.

#### Solution:

Since the foci are of the form $(\pm c, 0)$, it is a horizontal hyperbola.
Let the required equation be $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.

Length of its transverse axis $= 2a$.
Given $2a=8 \Leftrightarrow a=4 \Leftrightarrow a^{2}=16$.

The foci are given as $(\pm 5,0)$, so $c=5$.

Now, we find $b^{2}$:
$b^{2}=(c^{2}-a^{2})=(5^{2}-4^{2})=(25-16)=9$.

Thus, $a^{2}=16$ and $b^{2}=9$.
Hence, the required equation is $\frac{x^{2}}{16}-\frac{y^{2}}{9}=1$.

---

### Example: 5

Find the equation of the hyperbola whose foci are $(\pm 4,0)$ and the length of the latus rectum is 12 units.

#### Solution:

Since the foci are of the form $(\pm c, 0)$, it is a horizontal hyperbola.
Let the required equation be $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.

The foci are given as $(\pm 4,0)$, so $c=4$.
Now, $c=4 \Leftrightarrow c^{2}=16 \Leftrightarrow a^{2}+b^{2}=16$. (i)

Length of the latus rectum $= 12 \Leftrightarrow \frac{2b^{2}}{a}=12 \Leftrightarrow b^{2}=6a$. (ii)

From (i) and (ii), we get:
$a^{2}+6a=16 \Leftrightarrow a^{2}+6a-16=0$
$\Leftrightarrow (a+8)(a-2)=0$
$\Leftrightarrow a=2$ [$\because a$ cannot be negative].

Putting $a=2$ in (ii), we get $b^{2}=(6 \times 2)=12$.
Thus, $a^{2}=2^{2}=4$ and $b^{2}=12$.
Hence, the required equation is $\frac{x^{2}}{4}-\frac{y^{2}}{12}=1$.

---

### Example: 6

Find the equation of the hyperbola whose vertices are $(\pm 7,0)$ and the eccentricity is $\frac{4}{3}$.

#### Solution:

Since the vertices are of the form $(\pm a, 0)$, it is a horizontal hyperbola.
Let the required equation be $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.

The vertices are $(\pm 7,0)$, so $a=7 \Leftrightarrow a^{2}=49$.
Also, $e=\frac{c}{a} \Leftrightarrow c=ae=(7 \times \frac{4}{3})=\frac{28}{3}$.

Now, $c^{2}=(a^{2}+b^{2}) \Leftrightarrow b^{2}=(c^{2}-a^{2})=\left[\left(\frac{28}{3}\right)^{2}-49\right]=\frac{784}{9}-49 = \frac{784-441}{9}=\frac{343}{9}$.

Thus, $a^{2}=49$ and $b^{2}=\frac{343}{9}$.
The required equation is $\frac{x^{2}}{49}-\frac{y^{2}}{(343/9)}=1 \Leftrightarrow \frac{x^{2}}{49}-\frac{9y^{2}}{343}=1 \Leftrightarrow 7x^{2}-9y^{2}=343$.

---

### Example: 7

Find the equation of the hyperbola whose eccentricity is $\frac{3}{2}$ and whose foci are $(\pm 2,0)$.

#### Solution:

Since the foci are of the form $(\pm c, 0)$, it is a horizontal hyperbola.
Let the required equation be $\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$.

The foci are $(\pm 2,0)$, so $c=2$.
Given $e=\frac{c}{a} \Leftrightarrow a=\frac{c}{e}=\frac{2}{(3/2)}=\frac{4}{3}$.

And, $c^{2}=(a^{2}+b^{2}) \Leftrightarrow b^{2}=(c^{2}-a^{2})=(4-\frac{16}{9})=\frac{36-16}{9}=\frac{20}{9}$.

Thus, $a^{2}=\frac{16}{9}$ and $b^{2}=\frac{20}{9}$.
Hence, the required equation is $\frac{x^{2}}{(16/9)}-\frac{y^{2}}{(20/9)}=1 \Leftrightarrow \frac{9x^{2}}{16}-\frac{9y^{2}}{20}=1 \Leftrightarrow 45x^{2}-36y^{2}=80$.

---

### Example: 8

Find the lengths of the axes; the coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the hyperbola $\frac{y^{2}}{4}-\frac{x^{2}}{9}=1$.

#### Solution:

The given equation is $\frac{y^{2}}{4}-\frac{x^{2}}{9}=1$. This represents a vertical hyperbola.
Comparing with $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$, we get $a^{2}=4$ and $b^{2}=9$, so $a=2$ and $b=3$.

$\therefore c=\sqrt{a^{2}+b^{2}}=\sqrt{4+9}=\sqrt{13}$.

- **Lengths of axes**:
    - Length of the transverse axis $= 2a = (2 \times 2) = 4$ units.
    - Length of the conjugate axis $= 2b = (2 \times 3) = 6$ units.
- **Vertices**: The coordinates of the vertices are $A(0,-a)$ and $B(0, a)$, i.e., $A(0,-2)$ and $B(0,2)$.
- **Foci**: The coordinates of the foci are $F_{1}(0,-c)$ and $F_{2}(0, c)$, i.e., $F_{1}(0,-\sqrt{13})$ and $F_{2}(0, \sqrt{13})$.
- **Eccentricity**: $e=\frac{c}{a}=\frac{\sqrt{13}}{2}$.
- **Latus Rectum**: Length of the latus rectum $=\frac{2b^{2}}{a}=\frac{2 \times 9}{2} = 9$ units.

---

### Example: 9

Find the lengths of the axes; the coordinates of the vertices and the foci; the eccentricity and length of the latus rectum of the hyperbola $y^{2}-16x^{2}=16$.

#### Solution:

The equation is $y^{2}-16x^{2}=16 \Rightarrow \frac{y^{2}}{16}-\frac{x^{2}}{1}=1$. This represents a vertical hyperbola.
Comparing with $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$, we get $a^{2}=16$ and $b^{2}=1$, so $a=4$ and $b=1$.

$\therefore c=\sqrt{a^{2}+b^{2}}=\sqrt{16+1}=\sqrt{17}$.

- **Lengths of axes**:
    - Length of the transverse axis $= 2a = (2 \times 4) = 8$ units.
    - Length of the conjugate axis $= 2b = (2 \times 1) = 2$ units.
- **Vertices**: The coordinates of the vertices are $A(0,-a)$ and $B(0, a)$, i.e., $A(0,-4)$ and $B(0,4)$.
- **Foci**: The coordinates of the foci are $F_{1}(0,-c)$ and $F_{2}(0, c)$, i.e., $F_{1}(0,-\sqrt{17})$ and $F_{2}(0, \sqrt{17})$.
- **Eccentricity**: $e=\frac{c}{a}=\frac{\sqrt{17}}{4}$.
- **Latus Rectum**: Length of the latus rectum $=\frac{2b^{2}}{a}=\frac{2 \times 1}{4} = \frac{1}{2}$ unit.

---

### Example: 10

Find the equation of the hyperbola whose vertices are $(0, \pm 3)$ and the foci are $(0, \pm 5)$.

#### Solution:

Since the vertices are of the form $(0, \pm a)$, it is a vertical hyperbola.
Let the required equation be $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$.

The vertices are $(0, \pm 3)$, so $a=3$.
The foci are $(0, \pm 5)$, so $c=5$.

Now, we find $b^{2}$:
$b^{2}=(c^{2}-a^{2})=(5^{2}-3^{2})=(25-9)=16$.

Thus, $a^{2}=3^{2}=9$ and $b^{2}=16$.
Hence, the required equation is $\frac{y^{2}}{9}-\frac{x^{2}}{16}=1$.

---

### Example: 11

Find the equation of the hyperbola whose eccentricity is $\frac{5}{3}$ and whose vertices are $(0, \pm 6)$. Also, find the coordinates of its foci.

#### Solution:

Since the vertices are of the form $(0, \pm a)$, it is a vertical hyperbola.
Let the required equation be $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$.

The vertices are $(0, \pm 6)$, so $a=6$.
Given $e=\frac{5}{3}$.

Now, $\frac{c}{a}=e \Rightarrow c=ae=(6 \times \frac{5}{3})=10$.
And, $c^{2}=(a^{2}+b^{2}) \Leftrightarrow b^{2}=(c^{2}-a^{2})=(10^{2}-6^{2})=(100-36)=64$.

Thus, $a^{2}=6^{2}=36$ and $b^{2}=64$.
Hence, the required equation is $\frac{y^{2}}{36}-\frac{x^{2}}{64}=1$.
The coordinates of its foci are $(0, \pm c)$, i.e., $(0, \pm 10)$.

---

### Example: 12

Find the equation of the hyperbola whose foci are $(0, \pm 12)$ and the length of whose latus rectum is 36.

#### Solution:

Since the foci are of the form $(0, \pm c)$, it is a vertical hyperbola.
Let the required equation be $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$.

The foci are $(0, \pm 12)$, so $c=12$.
Length of the latus rectum $= 36 \Leftrightarrow \frac{2b^{2}}{a}=36 \Leftrightarrow b^{2}=18a$.

Now, $c^{2}=(a^{2}+b^{2}) \Leftrightarrow 144 = a^2 + 18a$
$\Leftrightarrow a^{2}+18a-144=0$
$\Leftrightarrow (a+24)(a-6)=0$
$\Leftrightarrow a=6$ [$\because a$ is non-negative].

Thus, $a^{2}=6^{2}=36$ and $b^{2}=18a=(18 \times 6)=108$.
Hence, the required equation is $\frac{y^{2}}{36}-\frac{x^{2}}{108}=1$.

---

### Example: 13

Find the equation of the hyperbola with centre at the origin, length of the transverse axis 6 and one focus at $(0, 4)$.

#### Solution:

Since one focus is at $(0, 4)$, the foci are of the form $(0, \pm c)$, so it is a vertical hyperbola.
Let its equation be $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$.

From the focus $(0, 4)$, we have $c=4$.
Length of the transverse axis $= 6 \Leftrightarrow 2a=6 \Leftrightarrow a=3$.

Also, $c^{2}=(a^{2}+b^{2}) \Leftrightarrow b^{2}=(c^{2}-a^{2})=(4^{2}-3^{2})=(16-9)=7$.
Thus, $a^{2}=3^{2}=9$ and $b^{2}=7$.
Hence, the required equation is $\frac{y^{2}}{9}-\frac{x^{2}}{7}=1$.

---

### Example: 14

Find the equation of the hyperbola whose foci are at $(0, \pm 6)$ and the length of whose conjugate axis is $2\sqrt{11}$.

#### Solution:

Since the foci are of the form $(0, \pm c)$, it is a vertical hyperbola.
Let its equation be $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$.

The foci are at $(0, \pm 6)$, so $c=6$.
Length of the conjugate axis $= 2\sqrt{11} \Leftrightarrow 2b=2\sqrt{11} \Leftrightarrow b=\sqrt{11} \Leftrightarrow b^{2}=11$.

Also, $c^{2}=(a^{2}+b^{2}) \Leftrightarrow a^{2}=(c^{2}-b^{2})=(36-11)=25$.
Thus, $a^{2}=25$ and $b^{2}=11$.
Hence, the required equation is $\frac{y^{2}}{25}-\frac{x^{2}}{11}=1$.

---

### Example: 15

Find the equation of the hyperbola whose foci are at $(0, \pm \sqrt{10})$ and which passes through the point $(2,3)$.

#### Solution:

Since the foci are of the form $(0, \pm c)$, it is a vertical hyperbola.
Let its equation be $\frac{y^{2}}{a^{2}}-\frac{x^{2}}{b^{2}}=1$. (i)

The foci are $(0, \pm \sqrt{10})$, so $c=\sqrt{10} \Leftrightarrow c^{2}=10 \Leftrightarrow a^{2}+b^{2}=10$. (ii)

Since the hyperbola (i) passes through $(2,3)$, we have:
$\frac{9}{a^{2}}-\frac{4}{b^{2}}=1$.

From (ii), $b^2 = 10 - a^2$. Substituting this into the equation above:
$\frac{9}{a^{2}}-\frac{4}{(10-a^{2})}=1$
$\Leftrightarrow 9(10-a^{2})-4a^{2}=a^{2}(10-a^{2})$
$\Leftrightarrow 90 - 9a^2 - 4a^2 = 10a^2 - a^4$
$\Leftrightarrow a^{4}-23a^{2}+90=0$
$\Leftrightarrow (a^{2}-18)(a^{2}-5)=0$
$\Leftrightarrow a^{2}=5$ or $a^{2}=18$.

If $a^{2}=18$, then $b^{2}=10-18=-8$, which is not possible.
Therefore, we must have $a^{2}=5$.
If $a^{2}=5$, then $b^{2}=10-5=5$.

Hence, the required equation is $\frac{y^{2}}{5}-\frac{x^{2}}{5}=1$, i.e., $y^{2}-x^{2}=5$.

---
