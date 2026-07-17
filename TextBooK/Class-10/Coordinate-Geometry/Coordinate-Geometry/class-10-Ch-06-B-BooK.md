# Section Formula

**THEOREM 2 (Section formula)** The coordinates of the point $P(x, y)$ which divides the line segment joining $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ internally in the ratio $m: n$ are given by

$$
x = \frac{m x_{2} + n x_{1}}{m+n}, y = \frac{m y_{2} + n y_{1}}{m+n}
$$

---

## Proof

Let $X'OX$ and $YOY'$ be the coordinate axes.
Let $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ be the end points of the given line segment $AB$.
Let $P(x, y)$ be the point which divides $AB$ in the ratio $m: n$.

![](https://cdn.mathpix.com/cropped/2025_09_25_836ee4d67995a4306a0cg-15.jpg?height=444&width=547&top_left_y=1041&top_left_x=374)

Then, $\frac{AP}{PB} = \frac{m}{n}$.
Draw $AL \perp OX$; $BM \perp OX$; $PN \perp OX$; $AR \perp PN$; and $PS \perp BM$.
Now, $AR = LN = ON - OL = (x-x_{1})$;
$PS = NM = OM - ON = (x_{2}-x)$;
$PR = PN - RN = PN - AL = (y-y_{1})$;
$BS = BM - SM = BM - PN = (y_{2}-y)$.

Clearly, $\triangle ARP$ and $\triangle PSB$ are similar and, therefore, their sides are proportional.

$$
\therefore \frac{AP}{PB} = \frac{AR}{PS} = \frac{PR}{BS}
$$

$$
\Rightarrow \frac{m}{n} = \frac{x-x_{1}}{x_{2}-x} = \frac{y-y_{1}}{y_{2}-y}
$$

$$
\Rightarrow \frac{m}{n} = \frac{x-x_{1}}{x_{2}-x} \quad \text{and} \quad \frac{m}{n} = \frac{y-y_{1}}{y_{2}-y}
$$

$$
\Rightarrow mx_{2} - mx = nx - nx_{1} \quad \text{and} \quad my_{2} - my = ny - ny_{1}
$$

$$
\Rightarrow (m+n)x = (mx_{2} + nx_{1}) \quad \text{and} \quad (m+n)y = (my_{2} + ny_{1})
$$

$$
\Rightarrow x = \frac{mx_{2} + nx_{1}}{m+n}, \quad y = \frac{my_{2} + ny_{1}}{m+n}
$$

Hence, the coordinates of $P$ are $\left(\frac{mx_{2} + nx_{1}}{m+n}, \frac{my_{2} + ny_{1}}{m+n}\right)$.

---

## Corollary: Midpoint Formula

The coordinates of the midpoint $M$ of a line segment $AB$ with end points $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ are $M\left(\frac{x_{1}+x_{2}}{2}, \frac{y_{1}+y_{2}}{2}\right)$.

## Proof

Let $M$ be the midpoint of the line segment joining the points $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$.
Then, $M$ divides $AB$ in the ratio **1:1**.
So, by the section formula, the coordinates of $M$ are

$$
\left(\frac{1 \cdot x_{2} + 1 \cdot x_{1}}{1+1}, \frac{1 \cdot y_{2} + 1 \cdot y_{1}}{1+1}\right) \text{, i.e., } \left(\frac{x_{1}+x_{2}}{2}, \frac{y_{1}+y_{2}}{2}\right)
$$

Hence, the coordinates of the midpoint of $AB$ are

$$
\left(\frac{x_{1}+x_{2}}{2}, \frac{y_{1}+y_{2}}{2}\right)
$$

---

# Summary

1.  If $P(x, y)$ divides the join of $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ in the ratio $m:n$ then
    $$
    x = \frac{(mx_{2} + nx_{1})}{(m+n)} \quad \text{and} \quad y = \frac{(my_{2} + ny_{1})}{(m+n)}
    $$

2.  The midpoint of the join of $A(x_{1}, y_{1})$ and $B(x_{2}, y_{2})$ is given by
    $$
    M\left(\frac{x_{1}+x_{2}}{2}, \frac{y_{1}+y_{2}}{2}\right)
    $$

---

# Solved Examples

### Example: 1

Find the coordinates of the point which divides the line segment joining the points $A(4, -3)$ and $B(9, 7)$ in the ratio $3:2$.

#### Solution:

The end points of $AB$ are $A(4, -3)$ and $B(9, 7)$.
$\therefore (x_{1} = 4, y_{1} = -3)$ and $(x_{2} = 9, y_{2} = 7)$.
Also, $m=3$ and $n=2$.

Let the required point be $P(x, y)$.
By the **section formula**, we have

$$
x = \frac{(mx_{2} + nx_{1})}{(m+n)}, \quad y = \frac{(my_{2} + ny_{1})}{(m+n)}
$$

$$
\Rightarrow x = \frac{(3 \times 9 + 2 \times 4)}{(3+2)}, \quad y = \frac{[3 \times 7 + 2 \times (-3)]}{(3+2)}
$$

$$
\Rightarrow x = 7, y = 3
$$

Hence, the required point is $P(7, 3)$.

---

### Example: 2

Find the coordinates of the midpoint of the line segment joining the points $A(-5, 4)$ and $B(7, -8)$.

#### Solution:

Let $M(x, y)$ be the midpoint of $AB$. Then,

$$
x = \frac{[(-5) + 7]}{2} = 1 \quad \text{and} \quad y = \frac{[4 + (-8)]}{2} = -2
$$

Hence, the required point is $M(1, -2)$.

---

### Example: 3

Find the coordinates of the points of trisection of the line segment joining the points $A(-5, 6)$ and $B(4, -3)$.

#### Solution:

Let $P$ and $Q$ be the points of trisection of $AB$.
Then, $P$ divides $AB$ in the ratio **1:2**.
So, the coordinates of $P$ are

$$
P\left(\frac{1 \times 4 + 2 \times (-5)}{1+2}, \frac{1 \times (-3) + 2 \times 6}{1+2}\right) \text{, i.e., } P(-2, 3)
$$

Also, $Q$ divides $AB$ in the ratio **2:1**.
So, the coordinates of $Q$ are

$$
Q\left(\frac{2 \times 4 + 1 \times (-5)}{2+1}, \frac{2 \times (-3) + 1 \times 6}{2+1}\right) \text{, i.e., } Q(1, 0)
$$

Hence, the points of trisection of $AB$ are $P(-2, 3)$ and $Q(1, 0)$.

---

### Example: 4

Find the coordinates of a point $P$ on the line segment joining $A(1, 2)$ and $B(6, 7)$ such that $AP = \frac{2}{5} AB$.

#### Solution:

Given $AP = \frac{2}{5} AB \Rightarrow \frac{AP}{AB} = \frac{2}{5}$.

$$
\Rightarrow \frac{AP}{AP+PB} = \frac{2}{5} \Rightarrow 5AP = 2AP + 2PB
$$

$$
\Rightarrow 3AP = 2PB \Rightarrow \frac{AP}{PB} = \frac{2}{3} \Rightarrow AP:PB = 2:3
$$

So, $P$ divides $AB$ in the ratio **2:3**.
$\therefore$ coordinates of $P$ are

$$
\left(\frac{2 \times 6 + 3 \times 1}{2+3}, \frac{2 \times 7 + 3 \times 2}{2+3}\right) = \left(\frac{15}{5}, \frac{20}{5}\right) = (3, 4)
$$

---

### Example: 5

Point $P$ divides the line segment joining the points $A(2, 1)$ and $B(5, -8)$ such that $\frac{AP}{AB} = \frac{1}{3}$. If $P$ lies on the line $2x - y + k = 0$, find the value of $k$.

#### Solution:

Given $\frac{AP}{AB} = \frac{1}{3} \Rightarrow \frac{AP}{AP+PB} = \frac{1}{3}$.

$$
\Rightarrow 3AP = AP + PB \Rightarrow 2AP = PB
$$

$$
\Rightarrow \frac{AP}{PB} = \frac{1}{2} \Rightarrow AP:PB = 1:2
$$

So, $P$ divides $AB$ in the ratio **1:2**.
$\therefore$ coordinates of $P$ are

$$
\left(\frac{1 \times 5 + 2 \times 2}{1+2}, \frac{1 \times (-8) + 2 \times 1}{1+2}\right) = \left(\frac{9}{3}, \frac{-6}{3}\right) = (3, -2)
$$

Since $P(3, -2)$ lies on $2x - y + k = 0$, we have

$$
2 \times 3 - (-2) + k = 0 \Rightarrow 6+2+k=0 \Rightarrow k = -8
$$

Hence, the required value of $k$ is **-8**.

---

### Example: 6

In what ratio does the point $P(2, -5)$ divide the line segment joining $A(-3, 5)$ and $B(4, -9)$?

#### Solution:

Let the required ratio be $k:1$.
Then, by the section formula, the coordinates of $P$ are

$$
P\left(\frac{4k - 3}{k+1}, \frac{-9k + 5}{k+1}\right)
$$

Since $P(2, -5)$ is given:

$$
\frac{4k - 3}{k+1} = 2 \quad \text{and} \quad \frac{-9k + 5}{k+1} = -5
$$

$$
\Rightarrow 4k - 3 = 2k + 2 \quad \text{and} \quad -9k + 5 = -5k - 5
$$

$$
\Rightarrow 2k = 5 \quad \text{and} \quad 4k = 10
$$

$$
\Rightarrow k = \frac{5}{2} \text{ in each case.}
$$

So, the required ratio is $\frac{5}{2}:1$, which is **5:2**.
Hence, $P$ divides $AB$ in the ratio **5:2**.

---

### Example: 7

Find the ratio in which the point $P(x, 2)$ divides the line segment joining the points $A(12, 5)$ and $B(4, -3)$. Also, find the value of $x$.

#### Solution:

Let the required ratio be $k:1$.
Then, by section formula, the coordinates of $P$ are

$$
P\left(\frac{4k+12}{k+1}, \frac{-3k+5}{k+1}\right)
$$

But, this point is given as $P(x, 2)$.

$$
\therefore \frac{-3k+5}{k+1} = 2 \Rightarrow -3k+5 = 2k+2 \Rightarrow 5k=3 \Rightarrow k=\frac{3}{5}
$$

So, the required ratio is **3:5**.
Putting $k=\frac{3}{5}$ in the x-coordinate of $P$, we get

$$
x = \frac{4 \times \frac{3}{5} + 12}{\frac{3}{5} + 1} = \frac{\frac{12+60}{5}}{\frac{8}{5}} = \frac{72}{8} = 9
$$

Hence, **x = 9**.

---

### Example: 8

Find the ratio in which the point $P(11, y)$ divides the line segment joining the points $A(15, 5)$ and $B(9, 20)$. Also, find the value of $y$.

#### Solution:

Let the required ratio be $k:1$.
Then, by the section formula, the coordinates of $P$ are

$$
P\left(\frac{9k+15}{k+1}, \frac{20k+5}{k+1}\right)
$$

But, this point is given as $P(11, y)$.

$$
\therefore \frac{9k+15}{k+1} = 11 \Rightarrow 9k+15 = 11k+11 \Rightarrow 2k=4 \Rightarrow k=2
$$

So, the required ratio is **2:1**.
Putting $k=2$ in the y-coordinate of $P$, we get

$$
y = \frac{20 \times 2 + 5}{(2+1)} = \frac{45}{3} = 15
$$

Hence, **y = 15**.

---

### Example: 9

If the point $P(-1, 2)$ divides the line segment joining the points $A(2, 5)$ and $B$ in the ratio $3:4$, find the coordinates of $B$.

#### Solution:

Let the coordinates of $B$ be $(x_{1}, y_{1})$.
Then, $P$ divides the join of $A(2, 5)$ and $B(x_{1}, y_{1})$ in the ratio **3:4**.
So, by the section formula, the coordinates of $P$ are

$$
P\left(\frac{3x_{1} + 4 \times 2}{3+4}, \frac{3y_{1} + 4 \times 5}{3+4}\right) \text{, i.e., } P\left(\frac{3x_{1}+8}{7}, \frac{3y_{1}+20}{7}\right)
$$

But, the coordinates of $P$ are $(-1, 2)$.

$$
\therefore \frac{3x_{1}+8}{7} = -1 \quad \text{and} \quad \frac{3y_{1}+20}{7} = 2
$$

$$
\Rightarrow 3x_{1}+8 = -7 \quad \text{and} \quad 3y_{1}+20 = 14
$$

$$
\Rightarrow 3x_{1} = -15 \quad \text{and} \quad 3y_{1} = -6
$$

$$
\Rightarrow x_{1} = -5 \quad \text{and} \quad y_{1} = -2
$$

Hence, the coordinates of $B$ are **(-5, -2)**.

---

### Example: 10

Find the lengths of the medians $AD$ and $BE$ of $\triangle ABC$ whose vertices are $A(7, -3)$, $B(5, 3)$ and $C(3, -1)$.

#### Solution:

Since $D$ and $E$ are the midpoints of $BC$ and $AC$ respectively, their coordinates are:

$$
D\left(\frac{5+3}{2}, \frac{3+(-1)}{2}\right) \text{, i.e., } D(4, 1)
$$

$$
E\left(\frac{7+3}{2}, \frac{-3-1}{2}\right) \text{, i.e., } E(5, -2)
$$

Length of median $AD$:

$$
AD = \sqrt{(7-4)^{2} + (-3-1)^{2}} = \sqrt{3^{2} + (-4)^{2}} = \sqrt{9+16} = \sqrt{25} = 5 \text{ units.}
$$

Length of median $BE$:

$$
BE = \sqrt{(5-5)^{2} + (3 - (-2))^{2}} = \sqrt{0^{2} + 5^{2}} = \sqrt{25} = 5 \text{ units.}
$$

---

### Example: 11

The three vertices of a parallelogram $ABCD$ taken in order are $A(3, -4)$, $B(-1, -3)$ and $C(-6, 2)$. Find the coordinates of the fourth vertex $D$.

#### Solution:

Let $A(3, -4)$, $B(-1, -3)$, and $C(-6, 2)$ be the three given vertices of parallelogram $ABCD$ and let its fourth vertex be $D(a, b)$.
We know that the diagonals of a parallelogram bisect each other. So, the midpoint of $AC$ is the same as the midpoint of $BD$.

Midpoint of $AC$ is $\left(\frac{3+(-6)}{2}, \frac{-4+2}{2}\right)$, i.e., $O\left(\frac{-3}{2}, -1\right)$.
Midpoint of $BD$ is $O\left(\frac{-1+a}{2}, \frac{-3+b}{2}\right)$.

Equating the coordinates:

$$
\frac{-1+a}{2} = \frac{-3}{2} \Rightarrow -1+a = -3 \Rightarrow a = -2
$$

$$
\frac{-3+b}{2} = -1 \Rightarrow -3+b = -2 \Rightarrow b = 1
$$

Hence, the fourth vertex of parallelogram $ABCD$ is $D(-2, 1)$.

---

### Example: 12

If $(3, 3), (6, y), (x, 7)$ and $(5, 6)$ are the vertices of a parallelogram taken in order, find the values of $x$ and $y$.

#### Solution:

Let $A(3, 3)$, $B(6, y)$, $C(x, 7)$ and $D(5, 6)$ be the vertices of a parallelogram $ABCD$.
The diagonals of a parallelogram bisect each other. Therefore, the midpoint of $AC$ is the same as the midpoint of $BD$.

Midpoint of $AC$ is $\left(\frac{x+3}{2}, \frac{7+3}{2}\right)$, i.e., $\left(\frac{x+3}{2}, 5\right)$.
Midpoint of $BD$ is $\left(\frac{5+6}{2}, \frac{6+y}{2}\right)$, i.e., $\left(\frac{11}{2}, \frac{6+y}{2}\right)$.

Equating the coordinates:

$$
\frac{x+3}{2} = \frac{11}{2} \Rightarrow x+3=11 \Rightarrow x=8
$$

$$
\frac{6+y}{2} = 5 \Rightarrow 6+y=10 \Rightarrow y=4
$$

Hence, $x=8$ and $y=4$.

---

### Example: 13

Let $D(3, -2)$, $E(-3, 1)$ and $F(4, -3)$ be the midpoints of the sides $BC$, $CA$ and $AB$ respectively of $\triangle ABC$. Then, find the coordinates of the vertices $A$, $B$ and $C$.

#### Solution:

Let $A(x_{1}, y_{1})$, $B(x_{2}, y_{2})$ and $C(x_{3}, y_{3})$ be the vertices of $\triangle ABC$.

$D(3, -2)$ is the midpoint of $BC$:
$\frac{x_{2}+x_{3}}{2} = 3 \Rightarrow x_{2}+x_{3} = 6$ (i)
$\frac{y_{2}+y_{3}}{2} = -2 \Rightarrow y_{2}+y_{3} = -4$ (ii)

$E(-3, 1)$ is the midpoint of $CA$:
$\frac{x_{1}+x_{3}}{2} = -3 \Rightarrow x_{1}+x_{3} = -6$ (iii)
$\frac{y_{1}+y_{3}}{2} = 1 \Rightarrow y_{1}+y_{3} = 2$ (iv)

$F(4, -3)$ is the midpoint of $AB$:
$\frac{x_{1}+x_{2}}{2} = 4 \Rightarrow x_{1}+x_{2} = 8$ (v)
$\frac{y_{1}+y_{2}}{2} = -3 \Rightarrow y_{1}+y_{2} = -6$ (vi)

Adding (i), (iii), and (v):
$2(x_{1}+x_{2}+x_{3}) = 6 - 6 + 8 = 8 \Rightarrow x_{1}+x_{2}+x_{3} = 4$ (vii)

From (vii) - (i): $x_{1} = 4 - 6 = -2$.
From (vii) - (iii): $x_{2} = 4 - (-6) = 10$.
From (vii) - (v): $x_{3} = 4 - 8 = -4$.

Adding (ii), (iv), and (vi):
$2(y_{1}+y_{2}+y_{3}) = -4 + 2 - 6 = -8 \Rightarrow y_{1}+y_{2}+y_{3} = -4$ (viii)

From (viii) - (ii): $y_{1} = -4 - (-4) = 0$.
From (viii) - (iv): $y_{2} = -4 - 2 = -6$.
From (viii) - (vi): $y_{3} = -4 - (-6) = 2$.

Hence, the vertices of $\triangle ABC$ are $A(-2, 0)$, $B(10, -6)$ and $C(-4, 2)$.

---

### Example: 14

The coordinates of one end point of a diameter $AB$ of a circle are $A(4, -1)$ and the coordinates of the centre of the circle are $C(1, -3)$. Find the coordinates of $B$.

#### Solution:

Let $C(1, -3)$ be the centre of the circle and let $A(4, -1)$ and $B(a, b)$ be the two end points of the diameter $AB$.
The centre $C$ is the midpoint of the diameter $AB$.
$\therefore$ the coordinates of $C$ are $\left(\frac{4+a}{2}, \frac{-1+b}{2}\right)$.

But, the coordinates of $C$ are given as $(1, -3)$.

$$
\therefore \frac{4+a}{2} = 1 \Rightarrow 4+a = 2 \Rightarrow a=-2
$$

$$
\text{and } \frac{-1+b}{2} = -3 \Rightarrow -1+b = -6 \Rightarrow b=-5
$$

Hence, the coordinates of $B$ are $B(-2, -5)$.

---

# Centroid of a Triangle

The **centroid** of a triangle is the point of intersection of its medians.

## To Find the Coordinates of the Centroid of a Triangle

Let $A(x_{1}, y_{1})$, $B(x_{2}, y_{2})$ and $C(x_{3}, y_{3})$ be the vertices of a $\triangle ABC$.
Let $D$ be the midpoint of $BC$.
Then, the coordinates of $D$ are $D\left(\frac{x_{2}+x_{3}}{2}, \frac{y_{2}+y_{3}}{2}\right)$.
Let $G(x, y)$ be the centroid of $\triangle ABC$.

The centroid $G$ divides the median $AD$ in the ratio **2:1**.
Using the section formula:

$$
x = \frac{2\left(\frac{x_{2}+x_{3}}{2}\right) + 1 \cdot x_{1}}{2+1} = \frac{x_{2}+x_{3}+x_{1}}{3} = \frac{x_{1}+x_{2}+x_{3}}{3}
$$

$$
y = \frac{2\left(\frac{y_{2}+y_{3}}{2}\right) + 1 \cdot y_{1}}{2+1} = \frac{y_{2}+y_{3}+y_{1}}{3} = \frac{y_{1}+y_{2}+y_{3}}{3}
$$

$\therefore$ the coordinates of the centroid $G$ are $G\left(\frac{x_{1}+x_{2}+x_{3}}{3}, \frac{y_{1}+y_{2}+y_{3}}{3}\right)$.

---

### Example: 15

Find the centroid of $\triangle ABC$ whose vertices are $A(-3, 0)$, $B(5, -2)$ and $C(-8, 5)$.

#### Solution:

Here, $(x_{1}=-3, y_{1}=0)$, $(x_{2}=5, y_{2}=-2)$ and $(x_{3}=-8, y_{3}=5)$.
Let $G(x, y)$ be the centroid of $\triangle ABC$. Then,

$$
x = \frac{1}{3}(x_{1}+x_{2}+x_{3}) = \frac{1}{3}(-3+5-8) = \frac{-6}{3} = -2
$$

$$
y = \frac{1}{3}(y_{1}+y_{2}+y_{3}) = \frac{1}{3}(0-2+5) = \frac{3}{3} = 1
$$

Hence, the centroid of $\triangle ABC$ is $G(-2, 1)$.

---

### Example: 16

Two vertices of a $\triangle ABC$ are given by $A(6, 4)$ and $B(-2, 2)$, and its centroid is $G(3, 4)$. Find the coordinates of the third vertex $C$ of $\triangle ABC$.

#### Solution:

Given two vertices of $\triangle ABC$ are $A(6, 4)$ and $B(-2, 2)$. Let the third vertex be $C(x, y)$.
The coordinates of the centroid of $\triangle ABC$ are

$$
G\left(\frac{6+(-2)+x}{3}, \frac{4+2+y}{3}\right) \text{, i.e., } G\left(\frac{4+x}{3}, \frac{6+y}{3}\right)
$$

But, it is given that the centroid of $\triangle ABC$ is $G(3, 4)$.

$$
\therefore \frac{4+x}{3} = 3 \Rightarrow 4+x = 9 \Rightarrow x=5
$$

$$
\text{and } \frac{6+y}{3} = 4 \Rightarrow 6+y = 12 \Rightarrow y=6
$$

Hence, the coordinates of the third vertex are $C(5, 6)$.

---

