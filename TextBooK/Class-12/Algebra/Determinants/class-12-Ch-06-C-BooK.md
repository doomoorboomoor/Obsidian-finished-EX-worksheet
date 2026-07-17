## Applications of Determinants

### Area of a Triangle in Determinant Form

We know that the area of a triangle whose vertices are $\left(x_{1}, y_{1}\right)$, $\left(x_{2}, y_{2}\right)$ and $\left(x_{3}, y_{3}\right)$ is given by

$$
\begin{aligned}
\Delta & =\frac{1}{2}\left[x_{1}\left(y_{2}-y_{3}\right)-x_{2}\left(y_{1}-y_{3}\right)+x_{3}\left(y_{1}-y_{2}\right)\right] \\
& =\frac{1}{2}\left|\begin{array}{lll}
x_{1} & y_{1} & 1 \\
x_{2} & y_{2} & 1 \\
x_{3} & y_{3} & 1
\end{array}\right| \quad \text { (in determinant form) }
\end{aligned}
$$

**REMARK 1.** Since area is a positive quantity, we always take the absolute value of the above determinant for the area.

**REMARK 2.** If three points $A, B, C$ are collinear then $\operatorname{ar}(\triangle A B C)=0$.

---

### Condition for Collinearity of Three Points

Let $A\left(x_{1}, y_{1}\right)$, $B\left(x_{2}, y_{2}\right)$ and $C\left(x_{3}, y_{3}\right)$ be three given points.
Then, $A, B, C$ are collinear

$$
\begin{aligned}
& \Leftrightarrow \operatorname{ar}(\triangle A B C)=0 \\
& \Leftrightarrow \frac{1}{2}\left|\begin{array}{lll}
x_{1} & y_{1} & 1 \\
x_{2} & y_{2} & 1 \\
x_{3} & y_{3} & 1
\end{array}\right|=0 \Leftrightarrow\left|\begin{array}{lll}
x_{1} & y_{1} & 1 \\
x_{2} & y_{2} & 1 \\
x_{3} & y_{3} & 1
\end{array}\right|=0 \\
& \Leftrightarrow x_{1}\left(y_{2}-y_{3}\right)+x_{2}\left(y_{3}-y_{1}\right)+x_{3}\left(y_{1}-y_{2}\right)=0 .
\end{aligned}
$$

$\therefore A, B, C$ are collinear $\Leftrightarrow x_{1}\left(y_{2}-y_{3}\right)+x_{2}\left(y_{3}-y_{1}\right)+x_{3}\left(y_{1}-y_{2}\right)=0$.

---

## Solved Examples

### Example 1

Find the area of a triangle whose vertices are $A(-2,-3)$, $B(3,2)$ and $C(-1,-8)$.

#### Solution:

Here, $\left(x_{1}=-2, y_{1}=-3\right)$, $\left(x_{2}=3, y_{2}=2\right)$ and $\left(x_{3}=-1, y_{3}=-8\right)$.

$$
\begin{aligned}
\therefore \frac{1}{2}\left|\begin{array}{lll}
x_{1} & y_{1} & 1 \\
x_{2} & y_{2} & 1 \\
x_{3} & y_{3} & 1
\end{array}\right| & =\frac{1}{2} \cdot\left|\begin{array}{rrr}
-2 & -3 & 1 \\
3 & 2 & 1 \\
-1 & -8 & 1
\end{array}\right| \\
= & \frac{1}{2} \cdot\left|\begin{array}{rrr}
-2 & -3 & 1 \\
5 & 5 & 0 \\
1 & -5 & 0
\end{array}\right| \\
& {\left[R_{2} \rightarrow\left(R_{2}-R_{1}\right) \text { and } R_{3} \rightarrow\left(R_{3}-R_{1}\right)\right] } \\
= & \frac{1}{2} \cdot 1 \cdot\left|\begin{array}{rr}
5 & 5 \\
1 & -5
\end{array}\right|=\frac{1}{2} \times(-25-5)=-15 .
\end{aligned}
$$

Hence, $\operatorname{ar}(\triangle A B C)=|-15|=15$ square units.

---

### Example 2

Show that the points $A(a, b+c)$, $B(b, c+a)$ and $C(c, a+b)$ are collinear.

#### Solution:

Points $A, B, C$ are collinear $\Leftrightarrow \operatorname{ar}(\triangle A B C)=0$.

$$
\text { Now, } \begin{aligned}
\operatorname{ar}(\triangle A B C) & =\frac{1}{2} \cdot\left|\begin{array}{lll}
a & b+c & 1 \\
b & c+a & 1 \\
c & a+b & 1
\end{array}\right| \\
& =\frac{1}{2} \cdot\left|\begin{array}{lll}
a & a+b+c & 1 \\
b & a+b+c & 1 \\
c & a+b+c & 1
\end{array}\right| \quad\left[C_{2} \rightarrow\left(C_{2}+C_{1}\right)\right] \\
& =\frac{1}{2}(a+b+c) \cdot\left|\begin{array}{lll}
a & 1 & 1 \\
b & 1 & 1 \\
c & 1 & 1
\end{array}\right| \\
& =\frac{1}{2}(a+b+c) \times 0=0 \quad\left[\because C_{2} \text { and } C_{3} \text { are identical }\right] .
\end{aligned}
$$

Hence, the given points are collinear.

---

### Example 3

If the points $(a, b)$, $\left(a^{\prime}, b^{\prime}\right)$ and $\left(a-a^{\prime}, b-b^{\prime}\right)$ are collinear, show that $a b^{\prime}=a^{\prime} b$.

#### Solution:

The given points are collinear

$$
\begin{aligned}
& \Leftrightarrow\left|\begin{array}{ccc}
a & b & 1 \\
a^{\prime} & b^{\prime} & 1 \\
a-a^{\prime} & b-b^{\prime} & 1
\end{array}\right|=0 \\
& \Leftrightarrow\left|\begin{array}{ccc}
a & b & 1 \\
a^{\prime}-a & b^{\prime}-b & 0 \\
-a^{\prime} & -b^{\prime} & 0
\end{array}\right|=0 \quad\left[R_{2} \rightarrow R_{2}-R_{1} \text { and } R_{3} \rightarrow R_{3}-R_{1}\right] \\
& \Leftrightarrow 1 \cdot\left[\left(a^{\prime}-a\right)\left(-b^{\prime}\right)+a^{\prime}\left(b^{\prime}-b\right)\right]=0 \quad\left[\text { expanding by } C_{3}\right] \\
& \Leftrightarrow a b^{\prime}-a^{\prime} b=0 \\
& \Leftrightarrow a b^{\prime}=a^{\prime} b
\end{aligned}
$$

---

### Example 4

Find the value of $k$ in order that the points $(5,5)$, $(k, 1)$ and $(10,7)$ are collinear.

#### Solution:

The given points are collinear

$$
\begin{aligned}
& \Leftrightarrow\left|\begin{array}{crr}
5 & 5 & 1 \\
k & 1 & 1 \\
10 & 7 & 1
\end{array}\right|=0 \\
& \Leftrightarrow\left|\begin{array}{crr}
5 & 5 & 1 \\
k-5 & -4 & 0 \\
5 & 2 & 0
\end{array}\right|=0 \quad\left[R_{2} \rightarrow R_{2}-R_{1} \text { and } R_{3} \rightarrow R_{3}-R_{1}\right]
\end{aligned}
$$

$$
\begin{aligned}
& \Leftrightarrow 1 \cdot[2(k-5)+20]=0 \\
& \Leftrightarrow 2 k+10=0 \Leftrightarrow k=-5 .
\end{aligned}
$$

Hence, $k=-5$.

---

### Example 5

Let $A(1,3)$, $B(0,0)$ and $C(k, 0)$ be three points such that $\operatorname{ar}(\triangle A B C)=3$ sq units. Find the value of $k$.

#### Solution:

We have

$$
\begin{aligned}
& \operatorname{ar}(\triangle A B C)=3 \text { sq units } \\
\Leftrightarrow & \frac{1}{2} \cdot\left|\begin{array}{lll}
1 & 3 & 1 \\
0 & 0 & 1 \\
k & 0 & 1
\end{array}\right|= \pm 3 \Leftrightarrow\left|\begin{array}{lll}
1 & 3 & 1 \\
0 & 0 & 1 \\
k & 0 & 1
\end{array}\right|= \pm 6 \\
\Leftrightarrow & (-1) \cdot\left|\begin{array}{ll}
1 & 3 \\
k & 0
\end{array}\right|= \pm 6 \Leftrightarrow 3 k= \pm 6 \Leftrightarrow k= \pm 2 .
\end{aligned}
$$

Hence, $k= \pm 2$.

---

### Example 6

Find the equation of the line joining the points $A(1,2)$ and $B(3,6)$, using determinants.

#### Solution:

Let $P(x, y)$ be a point on $A B$.
Then, the points $A, P$ and $B$ are collinear.
$\therefore \operatorname{ar}(\triangle A P B)=0$
$\Rightarrow \frac{1}{2} \cdot\left|\begin{array}{lll}1 & 2 & 1 \\ x & y & 1 \\ 3 & 6 & 1\end{array}\right|=0 \Rightarrow\left|\begin{array}{lll}1 & 2 & 1 \\ x & y & 1 \\ 3 & 6 & 1\end{array}\right|=0$
$\Rightarrow\left|\begin{array}{rrr}1 & 2 & 1 \\ x & y & 1 \\ 0 & 0 & -2\end{array}\right|=0 \quad\left[R_{3} \rightarrow R_{3}-3 R_{1}\right]$
$\Rightarrow(-2) \cdot\left|\begin{array}{ll}1 & 2 \\ x & y\end{array}\right|=0 \Rightarrow(y-2 x)=0 \Rightarrow y=2 x$.
Hence, the required equation is $y=2 x$.

---
