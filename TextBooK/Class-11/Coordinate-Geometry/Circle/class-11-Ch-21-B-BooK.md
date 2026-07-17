## General Equation of a Circle

**THEOREM** The general equation of a circle is of the form $x^{2}+y^{2}+2 g x+2 f y+c=0$. Also, every equation of the form $x^{2}+y^{2}+2 g x+2 f y+c=0$ represents a circle if $(g^{2}+f^{2}-c)>0$.

**PROOF** We know that the equation of a circle with centre $(h, k)$ and radius $r$ is given by

$$
(x-h)^{2}+(y-k)^{2}=r^{2}
$$

$$
\Rightarrow x^{2}+y^{2}-2 h x-2 k y+\left(h^{2}+k^{2}-r^{2}\right)=0
$$

$$
\Rightarrow x^{2}+y^{2}+2 g x+2 f y+c=0, \text{ where } -h=g, -k=f \text{ and } \left(h^{2}+k^{2}-r^{2}\right)=c.
$$

Hence, the general equation of a circle is of the form

$$
x^{2}+y^{2}+2 g x+2 f y+c=0 .
$$

Conversely, let $x^{2}+y^{2}+2 g x+2 f y+c=0$ be the given equation. Then,

$$
x^{2}+y^{2}+2 g x+2 f y+c=0
$$

$$
\Rightarrow\left(x^{2}+2 g x+g^{2}\right)+\left(y^{2}+2 f y+f^{2}\right)=\left(g^{2}+f^{2}-c\right)
$$

$$
\Rightarrow(x+g)^{2}+(y+f)^{2}=\left(\sqrt{g^{2}+f^{2}-c}\right)^{2}
$$

$$
\Rightarrow\{x-(-g)\}^{2}+\{y-(-f)\}^{2}=\left(\sqrt{g^{2}+f^{2}-c}\right)^{2}
$$

$$
\Rightarrow(x-h)^{2}+(y-k)^{2}=r^{2}, \text{ where } h=-g, k=-f \text{ and } r=\sqrt{g^{2}+f^{2}-c}.
$$

Clearly, this equation will represent a circle if $(g^{2}+f^{2}-c)>0$.
The **centre** of this circle is $(-g,-f)$ and its **radius** is $\sqrt{g^{2}+f^{2}-c}$.

**NOTE**
1. If $(g^{2}+f^{2}-c)=0$ then the above equation represents a **point circle**.
2. If $(g^{2}+f^{2}-c)<0$ then the above equation does not represent a circle.

**REMARK** The equation of a circle has the following properties:
1. It is a second-degree equation in $x$ and $y$.
2. It contains no term of $xy$.
3. Coefficient of $x^{2}$ = coefficient of $y^{2}$.

Thus, the equation $a x^{2}+b y^{2}+2 h x y+2 g x+2 f y+c=0$ will represent a circle only when $a=b$ and $h=0$.

---

## Summary

The general equation of a circle is

$$
x^{2}+y^{2}+2 g x+2 f y+c=0
$$

Its **centre** is $(-g,-f)$ and **radius** $=\sqrt{g^{2}+f^{2}-c}$.

---

## Solved Examples

### Example 1

Show that the equation $x^{2}+y^{2}-6 x+4 y-36=0$ represents a circle.
Also, find its centre and radius.

#### Solution

The given equation is $x^{2}+y^{2}-6 x+4 y-36=0$.

This is of the form $x^{2}+y^{2}+2 g x+2 f y+c=0$, where $2 g=-6$, $2 f=4$ and $c=-36$.

$\therefore g=-3$, $f=2$ and $c=-36$.

Hence, the given equation represents a circle.
**Centre** of the circle $=(-g,-f)=(3,-2)$.
**Radius** of the circle $=\sqrt{g^{2}+f^{2}-c}=\sqrt{3^{2}+(-2)^{2}+36}=\sqrt{49}=7$ units.

---

### Example 2

Show that the equation $3 x^{2}+3 y^{2}+12 x-18 y-11=0$ represents a circle. Also, find its centre and radius.

#### Solution

$$
3 x^{2}+3 y^{2}+12 x-18 y-11=0
$$

$$
\Rightarrow \quad x^{2}+y^{2}+4 x-6 y-\frac{11}{3}=0 . \tag{i}
$$

This is of the form $x^{2}+y^{2}+2 g x+2 f y+c=0$, where $2 g=4$, $2 f=-6$ and $c=-\frac{11}{3}$.

$\therefore g=2$, $f=-3$ and $c=-\frac{11}{3}$.

Hence, the given equation represents a circle.
**Centre** of the circle $=(-g,-f)=(-2,3)$.
**Radius** of the circle $=\sqrt{g^{2}+f^{2}-c} = \sqrt{(-2)^{2}+3^{2}+\frac{11}{3}}=\sqrt{\frac{50}{3}}$ units.

---

### Example 3

Find the equation of a circle passing through the points $(5, 7)$, $(6, 6)$ and $(2,-2)$. Find its centre and radius.

#### Solution

Let the required equation of the circle be

$$
x^{2}+y^{2}+2 g x+2 f y+c=0 . \tag{i}
$$

Since it passes through each of the points $(5,7)$, $(6,6)$ and $(2,-2)$, each one of these points must satisfy (i).

$$
\begin{align*}
\therefore \quad 25+49+10 g+14 f+c=0 & \Rightarrow 10 g+14 f+c+74=0  \tag{ii}\\
36+36+12 g+12 f+c=0 & \Rightarrow 12 g+12 f+c+72=0  \tag{iii}\\
4+4+4 g-4 f+c=0 & \Rightarrow 4 g-4 f+c+8=0 \tag{iv}
\end{align*}
$$

Subtracting (ii) from (iii), we get

$$
2 g-2 f-2=0 \Rightarrow g-f=1 \tag{v}
$$

Subtracting (iv) from (iii), we get

$$
8 g+16 f+64=0 \Rightarrow g+2 f=-8 \tag{vi}
$$

Solving (v) and (vi), we get $g=-2$ and $f=-3$.

Putting $g=-2$ and $f=-3$ in (ii), we get $c=-12$.

Putting $g=-2$, $f=-3$ and $c=-12$ in (i), we get

$$
x^{2}+y^{2}-4 x-6 y-12=0
$$

which is the required equation of the circle.

**Centre** of this circle $=(-g,-f)=(2,3)$.
And, its **radius** $=\sqrt{g^{2}+f^{2}-c}=\sqrt{4+9+12}=\sqrt{25}=5$ units.

---

### Example 4

Find the equation of the circle passing through the vertices of a triangle whose sides are represented by the equations $x+y=2,3 x-4 y=6$ and $x-y=0$.

#### Solution

Let the sides $AB, BC$ and $CA$ of $\triangle ABC$ be represented by the equations $x+y=2, 3x-4y=6$ and $x-y=0$ respectively.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Circle/class-11-Ch-21-B-BooK-001.jpg)

Solving $x+y=2$ and $3x-4y=6$, we get $B(2,0)$.
Solving $3x-4y=6$ and $x-y=0$, we get $C(-6,-6)$.
Solving $x+y=2$ and $x-y=0$, we get $A(1,1)$.

Let the required equation of the circle be

$$
x^{2}+y^{2}+2 g x+2 f y+c=0 . \tag{i}
$$

Since it passes through $A(1,1)$, $B(2,0)$ and $C(-6,-6)$, each of these points must satisfy (i).

$$
\begin{array}{ll}
\therefore & 1^{2}+1^{2}+2 g+2 f+c=0 \Rightarrow 2 g+2 f+c+2=0 \tag{ii} \\
& 2^{2}+0^{2}+4 g+c=0 \Rightarrow 4 g+c+4=0 \tag{iii} \\
& (-6)^{2}+(-6)^{2}-12 g-12 f+c=0 \Rightarrow -12 g-12 f+c+72=0 \tag{iv}
\end{array}
$$

Subtracting (ii) from (iii), we get

$$
2 g-2 f+2=0 \Leftrightarrow g-f=-1 . \tag{v}
$$

Subtracting (iv) from (iii), we get

$$
16 g+12 f-68=0 \Leftrightarrow 4 g+3 f=17 . \tag{vi}
$$

Solving (v) and (vi), we get $g=2$ and $f=3$.

Putting $g=2$ in (iii), we get $c=-12$.

Hence, the required equation is

$$
x^{2}+y^{2}+4 x+6 y-12=0
$$

---

### Example 5

Show that the points $(5,5)$, $(6,4)$, $(-2,4)$ and $(7,1)$ are concyclic, i.e., all lie on the same circle. Find the equation, centre and radius of this circle.

#### Solution

Let the equation of the circle passing through the points $(5,5)$, $(6,4)$ and $(7,1)$ be given by

$$
x^{2}+y^{2}+2 g x+2 f y+c=0 . \tag{i}
$$

Then, each of these points must satisfy (i).

$$
\begin{align*}
& 25+25+10 g+10 f+c=0 \Rightarrow 10 g+10 f+c=-50  \tag{ii}\\
& 36+16+12 g+8 f+c=0 \Rightarrow 12 g+8 f+c=-52  \tag{iii}\\
& 49+1+14 g+2 f+c=0 \Rightarrow 14 g+2 f+c=-50 \tag{iv}
\end{align*}
$$

Subtracting (ii) from (iv), we get

$$
4 g-8 f=0 \Rightarrow g-2 f=0 \tag{v}
$$

Subtracting (iii) from (iv), we get

$$
2 g-6 f=2 \Rightarrow g-3 f=1 \tag{vi}
$$

Solving (v) and (vi), we get $g=-2$ and $f=-1$.

Putting these values in (ii), we get $c=-20$.

Putting $g=-2, f=-1$ and $c=-20$ in (i), we get

$$
x^{2}+y^{2}-4 x-2 y-20=0 \tag{vii}
$$

This is the equation of the circle passing through the points $(5,5)$, $(6,4)$ and $(7,1)$.

Putting $x=-2$ and $y=4$ in (vii), we get

$$
\text{LHS} = 4+16+8-8-20=0 = \text{RHS}.
$$

This shows that the point $(-2,4)$ also lies on (vii).
Hence, the points $(5,5)$, $(6,4)$, $(-2,4)$ and $(7,1)$ all lie on the same circle, given by (vii).

**Centre** of this circle $=(-g,-f)=(2,1)$.

$$
\begin{aligned}
\text{Radius of this circle } & =\sqrt{g^{2}+f^{2}-c}=\sqrt{(-2)^{2}+(-1)^{2}+20} \\
& =\sqrt{25}=5 \text{ units}
\end{aligned}
$$

---

### Example 6

Find the equation of the circle which passes through the centre of the circle $x^{2}+y^{2}+8 x+10 y-7=0$ and is concentric with the circle $2 x^{2}+2 y^{2}-8 x-12 y-9=0$.

#### Solution

We have $2 x^{2}+2 y^{2}-8 x-12 y-9=0$

$$
\Rightarrow x^{2}+y^{2}-4 x-6 y-\frac{9}{2}=0 \Rightarrow x^{2}+y^{2}+2 g x+2 f y+c=0
$$

where $g=-2$, $f=-3$ and $c=\frac{-9}{2}$.

Centre of this circle $=(-g,-f)=(2,3)$.

$\therefore$ the centre of the required circle $= C(2,3)$.

Again, $x^{2}+y^{2}+8 x+10 y-7=0$
$\Rightarrow x^{2}+y^{2}+2 g x+2 f y+c=0$, where $g=4$, $f=5$ and $c=-7$.
Centre of this circle $=(-g,-f)=(-4,-5)$.

So, the required circle passes through the point $P(-4,-5)$.

Radius of the required circle $= CP = \sqrt{(2+4)^{2}+(3+5)^{2}} = \sqrt{36+64}=\sqrt{100}=10$.

Hence, the required equation of the circle is

$$
(x-2)^{2}+(y-3)^{2}=(10)^{2} \Rightarrow x^{2}+y^{2}-4 x-6 y-87=0 .
$$

---

### Example 7

Find the equation of the circle whose centre lies on the line $x-4 y=1$ and which passes through the points $(3,7)$ and $(5,5)$.

#### Solution

Let the required equation of the circle be

$$
x^{2}+y^{2}+2 g x+2 f y+c=0 \tag{i}
$$

Its centre is $(-g,-f)$, which lies on the line $x-4 y=1$.

$$
\therefore \quad -g+4 f=1 . \tag{ii}
$$

Also, it is given that (i) passes through the points $(3,7)$ and $(5,5)$.

$$
\begin{array}{ll}
\therefore \quad & 3^{2}+7^{2}+6 g+14 f+c=0 \Rightarrow 6 g+14 f+c=-58 . \tag{iii} \\
\quad & 5^{2}+5^{2}+10 g+10 f+c=0 \Rightarrow 10 g+10 f+c=-50 . \tag{iv}
\end{array}
$$

Subtracting (iii) from (iv), we get

$$
4 g-4 f=8 \Leftrightarrow g-f=2 . \tag{v}
$$

Solving (ii) and (v), we get $g=3$ and $f=1$.

Putting $g=3$ and $f=1$ in (iii), we get $c=-90$.

$\therefore g=3, f=1$ and $c=-90$.

Putting these values in (i), we get the required equation as

$$
x^{2}+y^{2}+6 x+2 y-90=0
$$

---

### Example 8

Find the equation of a circle concentric with the circle $2 x^{2}+2 y^{2}-6 x+8 y+1=0$ and of double its area.

#### Solution

The given equation of the circle is

$$
2 x^{2}+2 y^{2}-6 x+8 y+1=0
$$

$$
\Rightarrow x^{2}+y^{2}-3 x+4 y+\frac{1}{2}=0 \Rightarrow x^{2}+y^{2}+2 g x+2 f y+c=0
$$

where $g=\frac{-3}{2}$, $f=2$ and $c=\frac{1}{2}$.

Centre of this circle $=(-g,-f)=\left(\frac{3}{2},-2\right)$.
Radius of this circle $=\sqrt{g^{2}+f^{2}-c} = \sqrt{\frac{9}{4}+4-\frac{1}{2}}=\frac{\sqrt{23}}{2}$.

$\therefore$ the centre of the required circle $=\left(\frac{3}{2},-2\right)$.

Let $r_{1}$ be the radius of the required circle. Then,
$\pi r_{1}^{2}=2\left\{\pi \times\left(\frac{\sqrt{23}}{2}\right)^{2}\right\} \Rightarrow r_{1}^{2}=\frac{23}{2}$.

Hence, the equation of the required circle is

$$
\begin{aligned}
& \left(x-\frac{3}{2}\right)^{2}+(y+2)^{2}=\frac{23}{2} \\
\Rightarrow & x^{2}+y^{2}-3 x+4 y-\frac{21}{4}=0 \\
\Rightarrow & 4 x^{2}+4 y^{2}-12 x+16 y-21=0
\end{aligned}
$$

---

### Example 9

Find the equation of a circle which passes through the origin and cuts off intercepts -2 and 3 from the $x$-axis and the $y$-axis respectively.

#### Solution

Let the required equation of the circle be

$$
x^{2}+y^{2}+2 g x+2 f y+c=0 \tag{i}
$$

Clearly, the circle passes through the points $O(0,0)$, $A(-2,0)$ and $B(0,3)$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Coordinate-Geometry/Circle/class-11-Ch-21-B-BooK-002.jpg)

Putting $x=0$ and $y=0$ in (i), we get $c=0$.

Thus, (i) becomes

$$
x^{2}+y^{2}+2 g x+2 f y=0 \tag{ii}
$$

Putting $x=-2$ and $y=0$ in (ii), we get

$$
4g = 4 \Leftrightarrow g=1.
$$

Putting $x=0$ and $y=3$ in (ii), we get

$$
6 f=-9 \Leftrightarrow f=\frac{-3}{2}
$$

Putting $g=1$ and $f=\frac{-3}{2}$ in (ii), we get $x^{2}+y^{2}+2 x-3 y=0$, which is the required equation of the circle.

---

