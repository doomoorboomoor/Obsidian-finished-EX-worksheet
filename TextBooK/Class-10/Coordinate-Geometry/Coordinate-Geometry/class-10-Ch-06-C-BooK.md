## Area of a Triangle

**THEOREM 1** The area of a $\triangle ABC$ with vertices $A(x_1, y_1)$, $B(x_2, y_2)$ and $C(x_3, y_3)$ is given by

$$
\text{area}(\triangle ABC) = \left|\frac{1}{2}\left\{x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right\}\right|
$$

**PROOF** Let $A(x_1, y_1)$, $B(x_2, y_2)$ and $C(x_3, y_3)$ be the vertices of the given $\triangle ABC$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-001.jpg)

Draw $AL$, $BM$ and $CN$ perpendiculars to the $x$-axis.
Then, $ML = (x_1 - x_2)$, $LN = (x_3 - x_1)$ and $MN = (x_3 - x_2)$.

$\therefore \quad$ area of $\triangle ABC$

$$
\begin{aligned}
&= \text{ar}(\text{trap. BMLA}) + \text{ar}(\text{trap. ALNC}) - \text{ar}(\text{trap. BMNC}) \\
&= \left\{\frac{1}{2}(AL + BM) \times ML\right\} + \left\{\frac{1}{2}(AL + CN) \times LN\right\} - \left\{\frac{1}{2}(BM + CN) \times MN\right\} \\
&= \frac{1}{2}(y_1 + y_2)(x_1 - x_2) + \frac{1}{2}(y_1 + y_3)(x_3 - x_1) - \frac{1}{2}(y_2 + y_3)(x_3 - x_2) \\
&= \frac{1}{2}\left[x_1(y_1 + y_2 - y_1 - y_3) + x_2(y_2 + y_3 - y_1 - y_2) + x_3(y_1 + y_3 - y_2 - y_3)\right] \\
&= \frac{1}{2}\left[x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right]
\end{aligned}
$$

Since the area is never negative, we have

$$
\text{area}(\triangle ABC) = \frac{1}{2}\left|\left[x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right]\right|.
$$

---

## Condition for Collinearity of Three Points

Let the given points be $A(x_1, y_1)$, $B(x_2, y_2)$ and $C(x_3, y_3)$.
Then, $A, B$ and $C$ are **collinear**

$$
\begin{aligned}
& \Rightarrow \text{area of } \triangle ABC = 0 \\
& \Rightarrow \frac{1}{2} \cdot [x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)] = 0 \\
& \Rightarrow x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) = 0
\end{aligned}
$$

---

## Summary of the Results

1.  Area of $\triangle ABC$ with vertices $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$ is given by
    $$
    \text{ar}(\triangle ABC) = \frac{1}{2}\left|\left[x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right]\right|.
    $$

2.  Three points $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$ are **collinear** only when $x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) = 0$.

---

## Solved Examples

### Example 1:

Find the area of $\triangle ABC$ whose vertices are $A(2, 7)$, $B(3, -1)$ and $C(-5, 6)$.

#### Solution:

The coordinates of the vertices of the given triangle are $A(x_1=2, y_1=7)$, $B(x_2=3, y_2=-1)$ and $C(x_3=-5, y_3=6)$.

$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ABC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|2 \cdot (-1-6) + 3 \cdot (6-7) - 5 \cdot (7+1)| \\
&= \frac{1}{2}|2 \times (-7) + 3 \times (-1) - 5 \times 8| \\
&= \frac{1}{2}|-14-3-40| = \frac{1}{2}|-57| = \frac{57}{2} = 28.5 \text{ sq units.}
\end{aligned}
$$

Hence, the area of the given triangle is **28.5 sq units**.

---

### Example 2:

Find the values of $k$ so that the area of the triangle with vertices $(1, -1)$, $(-4, 2k)$ and $(-k, -5)$ is 24 square units. [CBSE 2015]

#### Solution:

Let $A(1, -1)$, $B(-4, 2k)$ and $C(-k, -5)$ be the vertices of the given $\triangle ABC$.
Then, $A(x_1=1, y_1=-1)$, $B(x_2=-4, y_2=2k)$, and $C(x_3=-k, y_3=-5)$.

$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ABC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|1 \cdot (2k+5) - 4 \cdot (-5+1) - k(-1-2k)| \\
&= \frac{1}{2}|2k+5+16+k+2k^2| \\
&= \frac{1}{2}|2k^2+3k+21| \text{ sq units.}
\end{aligned}
$$

But, it is given that $\text{ar}(\triangle ABC) = 24$ sq units.

$$
\therefore \quad \frac{1}{2}|2k^2+3k+21| = 24 \Rightarrow \left|k^2+\frac{3}{2}k+\frac{21}{2}\right| = 24. \quad \text{(i)}
$$

But $\left\{k^2 + \frac{3}{2}k + \frac{21}{2}\right\} = \left(k^2 + \frac{3}{2}k + \frac{9}{16}\right) + \left(\frac{21}{2} - \frac{9}{16}\right) = \left\{\left(k+\frac{3}{4}\right)^2 + \frac{159}{16}\right\} > 0$.

So, we may write (i) as
$$
\begin{aligned}
& k^2+\frac{3}{2}k+\frac{21}{2} = 24 \Rightarrow 2k^2+3k+21 = 48 \\
\Rightarrow & 2k^2+3k-27 = 0 \Rightarrow 2k^2+9k-6k-27 = 0 \\
\Rightarrow & k(2k+9)-3(2k+9) = 0 \Rightarrow (2k+9)(k-3) = 0 \\
\Rightarrow & k-3=0 \text{ or } 2k+9=0 \Rightarrow k=3 \text{ or } k=-\frac{9}{2}
\end{aligned}
$$

Hence, $k=3$ or $k=-\frac{9}{2}$.

---

### Example 3:

If $A(4, -6)$, $B(3, -2)$ and $C(5, 2)$ are the vertices of a $\triangle ABC$ and $AD$ is its median. Prove that the median $AD$ divides $\triangle ABC$ into two triangles of equal areas. [CBSE 2014]

#### Solution:

It is being given that $A(4, -6)$, $B(3, -2)$ and $C(5, 2)$ are the vertices of a $\triangle ABC$ and $AD$ is its median. Clearly, $D$ is the midpoint of $BC$.
$\therefore$ the coordinates of $D$ are
$$
\left(\frac{3+5}{2}, \frac{-2+2}{2}\right) = (4, 0).
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-002.jpg)

For $\triangle ABD$, we have $A(x_1=4, y_1=-6)$, $B(x_2=3, y_2=-2)$ and $D(x_3=4, y_3=0)$.
$$
\begin{aligned}
\text{ar}(\triangle ABD) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|4 \cdot (-2-0) + 3 \cdot (0+6) + 4 \cdot (-6+2)| \\
&= \frac{1}{2}|4 \times (-2) + 3 \times 6 + 4 \times (-4)| \\
&= \frac{1}{2}|-8+18-16| = \frac{1}{2}|-6| \\
&= \left(\frac{1}{2} \times 6\right) = 3 \text{ sq units.}
\end{aligned}
$$

For $\triangle ADC$, we have $(x_1=4, y_1=-6)$, $(x_2=4, y_2=0)$ and $(x_3=5, y_3=2)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ADC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|4 \cdot (0-2) + 4 \cdot (2+6) + 5 \cdot (-6-0)| \\
&= \frac{1}{2}|4 \times (-2) + 4 \times 8 + 5 \times (-6)| \\
&= \frac{1}{2}|-8+32-30| = \frac{1}{2}|-6| \\
&= \left(\frac{1}{2} \times 6\right) = 3 \text{ sq units.}
\end{aligned}
$$
$\therefore \quad \text{ar}(\triangle ABD) = \text{ar}(\triangle ADC)$.

Hence, the median $AD$ divides $\triangle ABC$ into two triangles of equal areas.

---

### Example 4:

Find the area of the triangle formed by joining the midpoints of the sides of the triangle whose vertices are $A(2, 2)$, $B(4, 4)$ and $C(2, 6)$. [CBSE 2009C]

#### Solution:

Let $A(2, 2)$, $B(4, 4)$ and $C(2, 6)$ be the vertices of the given $\triangle ABC$. Let $D, E$ and $F$ be the midpoints of $AB, BC$ and $CA$ respectively.
Then, the coordinates of $D, E$ and $F$ are
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-003.jpg)
$$
D\left(\frac{2+4}{2}, \frac{2+4}{2}\right), E\left(\frac{4+2}{2}, \frac{4+6}{2}\right) \text{ and } F\left(\frac{2+2}{2}, \frac{2+6}{2}\right),
$$
i.e., $D(3, 3)$, $E(3, 5)$ and $F(2, 4)$.

For $\triangle DEF$, we have $(x_1=3, y_1=3)$, $(x_2=3, y_2=5)$ and $(x_3=2, y_3=4)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle DEF) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|3 \cdot (5-4) + 3 \cdot (4-3) + 2 \cdot (3-5)| \\
&= \frac{1}{2}|(3 \times 1) + (3 \times 1) + 2 \times (-2)| \\
&= \frac{1}{2}|3+3-4| = \left(\frac{1}{2} \times 2\right) = 1 \text{ sq unit.}
\end{aligned}
$$

Hence, the area of $\triangle DEF$ is **1 sq unit**.

---

### Example 5:

Find the area of a quadrilateral $ABCD$ whose vertices are $A(-4, 8)$, $B(-3, -4)$, $C(0, -5)$ and $D(5, 6)$. [CBSE 2015]

#### Solution:

Area of quad. $ABCD = \text{ar}(\triangle ABC) + \text{ar}(\triangle ACD)$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-004.jpg)

For $\triangle ABC$, we have $(x_1=-4, y_1=8)$, $(x_2=-3, y_2=-4)$ and $(x_3=0, y_3=-5)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ABC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|(-4) \cdot (-4+5) + (-3) \cdot (-5-8) + 0 \cdot (8+4)| \\
&= \frac{1}{2}|(-4) \times 1 + (-3) \times (-13) + 0| \\
&= \frac{1}{2}|-4+39+0| = \frac{35}{2} \text{ sq units.}
\end{aligned}
$$

For $\triangle ACD$, we have $(x_1=-4, y_1=8)$, $(x_2=0, y_2=-5)$ and $(x_3=5, y_3=6)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ACD) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|(-4) \cdot (-5-6) + 0 \cdot (6-8) + 5 \cdot (8+5)| \\
&= \frac{1}{2}|(-4) \times (-11) + 0 \times (-2) + 5 \times 13| \\
&= \frac{1}{2}|44+0+65| = \frac{109}{2} \text{ sq unit.}
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad \text{ar}(\text{quad. } ABCD) &= \text{ar}(\triangle ABC) + \text{ar}(\triangle ACD) \\
&= \left(\frac{35}{2} + \frac{109}{2}\right) \text{ sq units} = \frac{144}{2} \text{ sq units} \\
&= 72 \text{ sq units.}
\end{aligned}
$$

Hence, the area of the given quadrilateral $ABCD$ is **72 sq units**.

---

### Example 6:

Find the area of a parallelogram $ABCD$ if three of its vertices are $A(2, 4)$, $B(2+\sqrt{3}, 5)$ and $C(2, 6)$. [CBSE 2013]

#### Solution:

Let $ABCD$ be the given parallelogram, three of whose vertices are $A(2, 4)$, $B(2+\sqrt{3}, 5)$ and $C(2, 6)$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-005.jpg)

In $\triangle ABC$, we have $(x_1=2, y_1=4)$, $(x_2=2+\sqrt{3}, y_2=5)$, $(x_3=2, y_3=6)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ABC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|2(5-6) + (2+\sqrt{3})(6-4) + 2(4-5)| \\
&= \frac{1}{2}|2 \times (-1) + (4+2\sqrt{3}) - 2| \\
&= \frac{1}{2}(2\sqrt{3}) = \sqrt{3} \text{ sq unit}
\end{aligned}
$$
$$
\begin{aligned}
\Rightarrow \quad \text{ar}(\| \text{gm } ABCD) &= 2 \times \text{ar}(\triangle ABC) = (2 \times \sqrt{3}) \text{ sq units} \\
&= (2\sqrt{3}) \text{ sq units.}
\end{aligned}
$$

Hence, the area of the given parallelogram is $2\sqrt{3}$ sq units.

---

### Example 7:

If the points $A(1, -2)$, $B(2, 3)$, $C(-3, 2)$ and $D(-4, -3)$ are the vertices of a parallelogram $ABCD$ then taking $AB$ as the base, find the height of the parallelogram. [CBSE 2013]

#### Solution:

Let $A(1, -2)$, $B(2, 3)$, $C(-3, 2)$ and $D(-4, -3)$ be the vertices of the given parallelogram $ABCD$. Join $AC$. Then,
$$
\text{ar}(\| \text{gm } ABCD) = 2 \times \text{ar}(\triangle ABC).
$$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-006.jpg)

In $\triangle ABC$, we have $(x_1=1, y_1=-2)$, $(x_2=2, y_2=3)$ and $(x_3=-3, y_3=2)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ABC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|1 \cdot (3-2) + 2 \cdot (2+2) - 3 \cdot (-2-3)| \\
&= \frac{1}{2}|1+8+15| = 12 \text{ sq units.}
\end{aligned}
$$

$\therefore \quad \text{ar}(\| \text{gm } ABCD) = 2 \times \text{ar}(\triangle ABC) = 2 \times 12 = 24$ sq units.

Base $AB = \sqrt{(2-1)^2 + (3+2)^2} = \sqrt{1^2 + 5^2} = \sqrt{26}$ units.
Let $h$ be the height of the $\| \text{gm } ABCD$. Then,
$$
\text{ar}(\| \text{gm } ABCD) = (\text{base} \times \text{height}) = (\sqrt{26} \times h) \text{ sq units.}
$$
$$
\begin{aligned}
\therefore \quad \sqrt{26} \times h = 24 &\Rightarrow h = \left\{\frac{24}{\sqrt{26}} \times \frac{\sqrt{26}}{\sqrt{26}}\right\} = \left(\frac{24}{26} \times \sqrt{26}\right) \text{ units} \\
\Rightarrow h &= \left(\frac{12}{13} \times 5.09\right) = \frac{61.08}{13} = 4.69 \text{ units.}
\end{aligned}
$$

Hence, the height of the parallelogram is **4.69 units**.

---

### Example 8:

Show that the points $A(-1, 1)$, $B(5, 7)$ and $C(8, 10)$ are collinear.

#### Solution:

Let $A(-1, 1)$, $B(5, 7)$ and $C(8, 10)$ be the given points. Then, $(x_1=-1, y_1=1)$, $(x_2=5, y_2=7)$ and $(x_3=8, y_3=10)$.
$$
\begin{aligned}
\therefore \quad & x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \\
& = (-1)(7-10) + 5(10-1) + 8(1-7) \\
& = (3 + 45 - 48) = 0
\end{aligned}
$$

Hence, the given points are **collinear**.

---

### Example 9:

Show that the points $A(a, b+c)$, $B(b, c+a)$ and $C(c, a+b)$ are collinear. [CBSE 2010]

#### Solution:

Let $A(a, b+c)$, $B(b, c+a)$ and $C(c, a+b)$ be the given points. Then, $(x_1=a, y_1=b+c)$, $(x_2=b, y_2=c+a)$ and $(x_3=c, y_3=a+b)$.
$$
\begin{aligned}
\therefore \quad & x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \\
& = a(c+a-a-b) + b(a+b-b-c) + c(b+c-c-a) \\
& = a(c-b) + b(a-c) + c(b-a) = 0.
\end{aligned}
$$

Hence, the given points are **collinear**.

---

### Example 10:

If the area of $\triangle ABC$ with vertices $A(x, y)$, $B(1, 2)$ and $C(2, 1)$ is 6 sq units then prove that $x+y=15$ or $x+y+9=0$. [CBSE 2013]

#### Solution:

The vertices of $\triangle ABC$ are $A(x, y)$, $B(1, 2)$ and $C(2, 1)$.
Here, $(x_1=x, y_1=y)$, $(x_2=1, y_2=2)$ and $(x_3=2, y_3=1)$.
$$
\begin{aligned}
\therefore \quad \text{ar}(\triangle ABC) &= \frac{1}{2}\left|x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)\right| \\
&= \frac{1}{2}|x \cdot (2-1) + 1 \cdot (1-y) + 2 \cdot (y-2)| \\
&= \frac{1}{2}|x+1-y+2y-4| = \frac{1}{2}|x+y-3|
\end{aligned}
$$

$$
\begin{gathered}
\therefore \quad \frac{1}{2}|x+y-3| = 6 \Rightarrow |x+y-3| = 12 \\
\Rightarrow x+y-3=12 \text{ or } x+y-3=-12 \\
\Rightarrow x+y=15 \text{ or } x+y+9=0
\end{gathered}
$$

Hence, $x+y=15$ or $x+y+9=0$.

---

### Example 11:

Find the value of $k$ for which the points $A(k+1, 2k)$, $B(3k, 2k+3)$ and $C(5k-1, 5k)$ are collinear. [CBSE 2015, '17]

#### Solution:

The given points are $A(k+1, 2k)$, $B(3k, 2k+3)$ and $C(5k-1, 5k)$.
Here, $(x_1=k+1, y_1=2k)$, $(x_2=3k, y_2=2k+3)$ and $(x_3=5k-1, y_3=5k)$.
Let the given points be collinear. Then,
$$
x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) = 0
$$
$$
\begin{aligned}
\Rightarrow & (k+1)(2k+3-5k) + 3k(5k-2k) + (5k-1)[2k-(2k+3)] = 0 \\
\Rightarrow & (k+1)(3-3k) + 3k \times 3k + (5k-1) \times (-3) = 0 \\
\Rightarrow & 3-3k^2+9k^2-15k+3 = 0 \Rightarrow 6k^2-15k+6 = 0 \\
\Rightarrow & 2k^2-5k+2 = 0 \Rightarrow 2k^2-4k-k+2 = 0 \\
\Rightarrow & 2k(k-2)-(k-2) = 0 \Rightarrow (k-2)(2k-1) = 0 \\
\Rightarrow & k-2=0 \text{ or } 2k-1=0 \Rightarrow k=2 \text{ or } k=\frac{1}{2}.
\end{aligned}
$$

Hence, $k=2$ or $k=\frac{1}{2}$.

---

### Example 12:

If the points $A(-1, -4)$, $B(b, c)$ and $C(5, -1)$ are collinear and $2b+c=4$, find the values of $b$ and $c$. [CBSE 2014]

#### Solution:

Let $A(x_1=-1, y_1=-4)$, $B(x_2=b, y_2=c)$ and $C(x_3=5, y_3=-1)$ be the given points.
Since these points $A, B$ and $C$ are collinear, we have
$$
\begin{align*}
& x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) = 0 \\
\Rightarrow & (-1) \cdot (c+1) + b \cdot (-1+4) + 5 \cdot (-4-c) = 0 \\
\Rightarrow & -c-1+3b-20-5c = 0 \\
\Rightarrow & 3b-6c = 21 \Rightarrow b-2c = 7. \quad \text{(i)}
\end{align*}
$$

Also, it is given that $2b+c=4$. (ii)

On solving (i) and (ii), we get $b=3$ and $c=-2$.
Hence, $b=3$ and $c=-2$.

---

### Example 13:

If $R(x, y)$ is a point on the line segment joining the points $P(a, b)$ and $Q(b, a)$ then prove that $x+y=a+b$. [CBSE 2010]

#### Solution:

It is being given that the points $P(a, b)$, $R(x, y)$ and $Q(b, a)$ lie on the same line segment and, therefore, these points are collinear.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Coordinate-Geometry/Coordinate-Geometry/class-10-Ch-06-C-BooK-007.jpg)

Let $P(x_1=a, y_1=b)$, $R(x_2=x, y_2=y)$ and $Q(x_3=b, y_3=a)$ be the given collinear points. Then,
$$
\begin{aligned}
& x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) = 0 \\
\Rightarrow & a(y-a) + x(a-b) + b(b-y) = 0 \\
\Rightarrow & ay - a^2 + ax - bx + b^2 - by = 0 \\
\Rightarrow & (a-b)y - (a^2-b^2) + (a-b)x = 0 \\
\Rightarrow & y-(a+b)+x=0 \Rightarrow x+y=a+b
\end{aligned}
$$

Hence, $x+y=a+b$.

---

