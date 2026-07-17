## Angle Between a Line and a Plane

The angle between a line and a plane is the complement of the angle between the line and normal to the plane.

## Vector Form

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Threedimensional-Geometry/The-Plane/class-12-Ch-28-G-BooK-001.jpg)

**Theorem 1:** If $\phi$ is the angle between the line $\vec{r}=\vec{a}+\lambda \vec{b}$ and the plane $\vec{r} \cdot \vec{n}=q$, then prove that

$$
\sin \phi=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|}
$$

**Proof:** We know that the line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to $\vec{b}$.
And, the plane $\vec{r} \cdot \vec{n}=q$ is normal to $\vec{n}$.
Let $\theta$ be the angle between the line and the normal to the plane. Then,

$$
\cos \theta=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|}
$$

Let $\phi$ be the angle between the line and the plane
Then, $\phi=90^{\circ}-\theta \Rightarrow \theta=90^{\circ}-\phi$.

$$
\therefore \quad \cos \left(90^{\circ}-\phi\right)=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|} \Rightarrow \sin \phi=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|}
$$

---

## Two Important Results

1.  **Condition for a given line to be perpendicular to a given plane**
    > The line $\vec{r}=\vec{a}+\lambda \vec{b}$ is perpendicular to the plane $\vec{r} \cdot \vec{n}=q$
    > $\Leftrightarrow \vec{b}$ is perpendicular to the plane $\vec{r} \cdot \vec{n}=q$
    > $\Leftrightarrow \vec{b}$ is parallel to the normal $\vec{n}$ to the plane
    > $\Leftrightarrow \vec{b}=t \vec{n}$, for some scalar $t$.

2.  **Condition for a given line to be parallel to a given plane**
    > The line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to the plane $\vec{r} \cdot \vec{n}=q$
    > $\Leftrightarrow \vec{b}$ is parallel to the plane $\vec{r} \cdot \vec{n}=q$
    > $\Leftrightarrow \vec{b}$ is perpendicular to the normal $\vec{n}$ to the plane
    > $\Leftrightarrow \vec{b} \cdot \vec{n}=0$.

---

## Cartesian Form

**Theorem 2:** If $\phi$ is the angle between the line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ and the plane

$$
\begin{aligned}
a_{2} x+b_{2} y+c_{2} z+d & =0, \text { then } \\
\sin \phi & =\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left\{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right\}\left\{\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right\}}
\end{aligned}
$$

**Proof:** The direction ratios of the given line are $a_{1}, b_{1}, c_{1}$.
So, the given line is parallel to $\vec{b}=\left(a_{1} \hat{i}+b_{1} \hat{j}+c_{1} \hat{k}\right)$.
The normal to the given plane is parallel to $\vec{n}=a_{2} \hat{i}+b_{2} \hat{j}+c_{2} \hat{k}$.
Let $\phi$ be the angle between the line and the plane. Then,

$$
\sin \phi=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|}
$$

$$
\begin{aligned}
& =\frac{\left|\left(a_{1} \hat{i}+b_{1} \hat{j}+c_{1} \hat{k}\right) \cdot\left(a_{2} \hat{i}+b_{2} \hat{j}+c_{2} \hat{k}\right)\right|}{\mid\left(a_{1} \hat{i}+b_{1} \hat{j}+c_{1} \hat{k}| |\left(a_{2} \hat{i}+b_{2} \hat{j}+c_{2} \hat{k} \mid\right.\right.} \\
& =\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left\{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right\}\left\{\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right\}} .
\end{aligned}
$$

---

## Important Results

1.  **Condition for the given line to be perpendicular to the given plane**
    The line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ is perpendicular to the plane $a_{2} x+b_{2} y+c_{2} z+d=0$
    > $\Leftrightarrow$ the line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ is parallel to the normal to the plane $a_{2} x+b_{2} y+c_{2} z+d=0$
    > $\Leftrightarrow \quad \frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.

2.  **Condition for the given line to be parallel to the given plane**
    The line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ is parallel to the plane $a_{2} x+b_{2} y+c_{2} z+d=0$
    > $\Leftrightarrow$ the line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ is perpendicular to the normal to the plane $a_{2} x+b_{2} y+c_{2} z+d=0$
    > $\Leftrightarrow a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}=0$.

3.  **Distance between a line and a plane, parallel to each other**
    If the line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to the plane $\vec{r} \cdot \vec{n}=q$ then the distance between them is $\frac{|\vec{a} \cdot \vec{n}-q|}{|\vec{n}|}$, which is the same as the distance of a point from the plane.

4.  **Length of perpendicular from $P\left(x_{1}, y_{1}, z_{1}\right)$ to the plane $a x+b y+c z=d$ is**
    $$
    \frac{\left|a x_{1}+b y_{1}+c z_{1}-d\right|}{\sqrt{a^{2}+b^{2}+c^{2}}} .
    $$

---

## Summary

1.  If $\phi$ is the angle between the line $\vec{r}=\vec{a}+\lambda \vec{b}$ and the plane $\vec{r} \cdot \vec{n}=q$ then
    $$
    \sin \phi=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|}
    $$

2.  The line $\vec{r}=\vec{a}+\lambda \vec{b}$ is perpendicular to the plane $\vec{r} \cdot \vec{n}=q$ only when $\vec{b}=t \vec{n}$ for some scalar $t$.

3.  (i) The line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to the plane $\vec{r} \cdot \vec{n}=q$ only when $\overrightarrow{\boldsymbol{b}} \cdot \overrightarrow{\boldsymbol{n}}=\mathbf{0}$.
    (ii) If the line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to the plane $\vec{r} \cdot \vec{n}=q$ then the distance between them is
    $$
    \frac{|\vec{a} \cdot \vec{n}-q|}{|\vec{n}|}
    $$

4.  If $\phi$ is the angle between the line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ and the plane $a_{2} x+b_{2} y+c_{2} z+d=0$ then
    $$
    \sin \phi=\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left(\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right)\left(\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right)} .
    $$

5.  The line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ is perpendicular to the plane $a_{2} x+b_{2} y+c_{2} z+d=0$ only if $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.

6.  The line $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$ is parallel to the plane $a_{2} x+b_{2} y+c_{2} z+d=0$ only if $\boldsymbol{a}_{\mathbf{1}} \boldsymbol{a}_{\mathbf{2}}+\boldsymbol{b}_{\mathbf{1}} \boldsymbol{b}_{\mathbf{2}}+\boldsymbol{c}_{\mathbf{1}} \boldsymbol{c}_{\mathbf{2}}=\mathbf{0}$.

---

## Solved Examples

### Example 1:

Find the angle between the line $\vec{r}=(\hat{i}+\hat{j}-3 \hat{k})+\lambda(2 \hat{i}+2 \hat{j}+\hat{k})$ and the plane $\vec{r} \cdot(6 \hat{i}-3 \hat{j}+2 \hat{k})=5$.

#### Solution:

We know that the angle $\phi$ between the line $\vec{r}=\vec{a}+\lambda \vec{b}$ and the
plane $\vec{r} \cdot \vec{n}=q$ is given by

$$
\sin \phi=\frac{|\vec{b} \cdot \vec{n}|}{|\vec{b}||\vec{n}|}
$$

Here, $\vec{b}=(2 \hat{i}+2 \hat{j}+\hat{k})$ and $\vec{n}=(6 \hat{i}-3 \hat{j}+2 \hat{k})$.
$\therefore \quad \sin \phi=\frac{|(2 \hat{i}+2 \hat{j}+\hat{k}) \cdot(6 \hat{i}-3 \hat{j}+2 \hat{k})|}{\left\{\sqrt{2^{2}+2^{2}+1^{2}}\right\}\left\{\sqrt{6^{2}+(-3)^{2}+2^{2}}\right\}}$

$$
=\frac{|(12-6+2)|}{\{\sqrt{9} \times \sqrt{49}\}}=\frac{8}{3 \times 7}=\frac{8}{21}
$$

$\Rightarrow \phi=\sin ^{-1}\left(\frac{8}{21}\right)$.
Hence, the angle between the given line and the given plane is $\sin ^{-1}\left(\frac{8}{21}\right)$.

---

### Example 2:

Find the value of $m$ for which the line $\vec{r}=(\hat{i}+2 \hat{j}-\hat{k})+\lambda(2 \hat{i}+\hat{j}+2 \hat{k})$ is parallel to the plane $\vec{r} \cdot(3 \hat{i}-2 \hat{j}+m \hat{k})=12$.

#### Solution:

We know that the line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to the plane

$$
\vec{r} \cdot \vec{n}=q \text { only when } \vec{b} \cdot \vec{n}=0
$$

Here, $\vec{b}=(2 \hat{i}+\hat{j}+2 \hat{k})$ and $\vec{n}=(3 \hat{i}-2 \hat{j}+m \hat{k})$.
So, the given line is parallel to the given plane
> $\Leftrightarrow \vec{b} \cdot \vec{n}=0$
> $\Leftrightarrow(2 \hat{i}+\hat{j}+2 \hat{k}) \cdot(3 \hat{i}-2 \hat{j}+m \hat{k})=0$
> $\Leftrightarrow \quad(2 \times 3)+1 \times(-2)+2 \times m=0$
> $\Leftrightarrow 2 m=-4 \Leftrightarrow m=-2$.

Hence, the required value of $m$ is -2 .

---

### Example 3:

Show that the line $\vec{r}=(2 \hat{i}-2 \hat{j}+3 \hat{k})+\lambda(\hat{i}-\hat{j}+4 \hat{k})$ is parallel to
the plane $\vec{r} \cdot(\hat{i}+5 \hat{j}+\hat{k})=5$.
Also, find the distance between the given line and the given plane.
[CBSE 2010]

#### Solution:

The given line is in the form $\vec{r}=\vec{a}+\lambda \vec{b}$ and the given plane is in the form $\vec{r} \cdot \vec{n}=q$, where

$$
\vec{a}=(2 \hat{i}-2 \hat{j}+3 \hat{k}), \vec{b}=(\hat{i}-\hat{j}+4 \hat{k}), \vec{n}=(\hat{i}+5 \hat{j}+\hat{k}) \text { and } q=5
$$

We know that the line $\vec{r}=\vec{a}+\lambda \vec{b}$ is parallel to the plane $\vec{r} \cdot \vec{n}=q$ only when $\vec{b} \cdot \vec{n}=0$.

Here, $\vec{b} \cdot \vec{n}=(\hat{i}-\hat{j}+4 \hat{k}) \cdot(\hat{i}+5 \hat{j}+\hat{k})$

$$
=(1 \times 1)+(-1) \times 5+4 \times 1=0
$$

Hence, the given line is parallel to the given plane.
Distance between the given line and the given plane

$$
\begin{aligned}
& =\frac{|\vec{a} \cdot \vec{n}-q|}{|\vec{n}|}=\frac{|(2 \hat{i}-2 \hat{j}+3 \hat{k}) \cdot(\hat{i}+5 \hat{j}+\hat{k})-5|}{|\hat{i}+5 \hat{j}+\hat{k}|} \\
& =\frac{|(2 \times 1)+(-2) \times 5+(3 \times 1)-5|}{\sqrt{1^{2}+5^{2}+1^{2}}} \\
& =\frac{|2-10+3-5|}{\sqrt{27}}=\frac{10}{3 \sqrt{3}} \text { units. }
\end{aligned}
$$

Hence, the distance between the given line and the given plane is $\frac{10}{3 \sqrt{3}}$ units.

---

### Example 4:

Find the vector equation of a line passing through the point $A(1,-1,2)$ and perpendicular to the plane $\vec{r} \cdot(2 \hat{i}-\hat{j}+3 \hat{k})=5$.

#### Solution:

The position vector of the given point is $\vec{a}=(\hat{i}-\hat{j}+2 \hat{k})$.
The given plane is $\vec{r} \cdot \vec{n}=q$; where $\vec{n}=(2 \hat{i}-\hat{j}+3 \hat{k})$ and $q=5$.
Since the required line is perpendicular to the given plane, so it must be parallel to its normal $\vec{n}$.
Thus, we need a line which passes through a point having position vector $\vec{a}$ and which is parallel to vector $\vec{n}$.
So, its vector equation is

$$
\vec{r}=\vec{a}+\lambda \vec{n}, \text { i.e., } \vec{r}=(\hat{i}-\hat{j}+2 \hat{k})+\lambda(2 \hat{i}-\hat{j}+3 \hat{k})
$$

for some scalar $\lambda$.

---

### Example 5:

Find the angle between the line $\frac{x-2}{-1}=\frac{y+3}{2}=\frac{z+4}{3}$ and the plane $2 x-3 y+z=5$.

#### Solution:

The given line is $\frac{x-x_{1}}{a_{1}}=\frac{y-y_{1}}{b_{1}}=\frac{z-z_{1}}{c_{1}}$, where $a_{1}=-1, b_{1}=2, c_{1}=3$.
The given plane is $a_{2} x+b_{2} y+c_{2} z+d=0$, where $a_{2}=2, b_{2}=-3$, $c_{2}=1, d=-5$.
Let the required angle be $\phi$. Then

$$
\begin{aligned}
\sin \phi & =\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left\{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right\} \cdot\left\{\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right\}} \\
& =\frac{|(-1) \times 2+2 \times(-3)+3 \times 1|}{\left\{\sqrt{(-1)^{2}+2^{2}+3^{2}}\right\} \cdot\left\{\sqrt{2^{2}+(-3)^{2}+1^{2}}\right\}} \\
& =\frac{|-2-6+3|}{\{\sqrt{14} \times \sqrt{14}\}}=\frac{|-5|}{14}=\frac{5}{14} \\
\Rightarrow \quad \phi & =\sin ^{-1}\left(\frac{5}{14}\right)
\end{aligned}
$$

Hence, the angle between the given line and and the given plane is $\sin ^{-1}\left(\frac{5}{14}\right)$.

---

### Example 6:

Find the equation of the line passing through the point $(3,0,1)$ and parallel to the planes $x+2 y=0$ and $3 y-z=0$.
[CBSE 2012]

#### Solution:

Let the direction ratios of the required line be $a, b, c$.
Then, its equation is given by

$$
\begin{equation*}
\frac{x-3}{a}=\frac{y-0}{b}=\frac{z-1}{c} \tag{i}
\end{equation*}
$$

Since the line (i) is parallel to each of the planes $x+2 y+0 z=0$ and $0 x+3 y-z=0$, so it must be perpendicular to the normal of each of these planes.

$$
\begin{align*}
& \therefore \quad a \times 1+b \times 2+c \times 0=0 \Rightarrow a+2 b+0 c=0  \tag{ii}\\
& \text { and } a \times 0+b \times 3+c \times(-1)=0 \Rightarrow 0 a+3 b-c=0 \tag{iii}
\end{align*}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
& \frac{a}{(-2-0)}=\frac{b}{(0+1)}=\frac{c}{(3-0)} \\
\Rightarrow \quad & \frac{a}{-2}=\frac{b}{1}=\frac{c}{3}=\lambda(\text { say }) \Rightarrow a=-2 \lambda, b=\lambda \text { and } c=3 \lambda
\end{aligned}
$$

Putting these values of $a, b, c$ in (i), we get

$$
\frac{x-3}{-2 \lambda}=\frac{y-0}{\lambda}=\frac{z-1}{3 \lambda} \Rightarrow \frac{x-3}{-2}=\frac{y}{1}=\frac{z-1}{3} .
$$

Hence, the required equation of the line is $\frac{x-3}{-2}=\frac{y}{1}=\frac{z-1}{3}$.

---

### Example 7:

Find the equation of the plane passing through the point $A(1,2,1)$ and perpendicular to the line joining the points $P(1,4,2)$ and $Q(2,3,5)$. Also find the distance of this plane from the line $\frac{x+3}{2}=\frac{y-5}{-1}=\frac{z-7}{-1}$.
[CBSE 2010C, '11]

The general equation of a plane passing through the point $A(1,2,1)$ is given by

$$
\begin{equation*}
a(x-1)+b(y-2)+c(z-1)=0 \tag{i}
\end{equation*}
$$

D.r.'s of noraml to the plane (i) are $a, b, c$.
D.r.'s of line $P Q$ are ( $2-1$ ), ( $3-4$ ), ( $5-2$ ), i.e., $1,-1,3$.

Since the required plane is perpendicular to line $P Q$, so the normal to this plane must be parallel to $P Q$.
$\therefore \quad \frac{a}{1}=\frac{b}{-1}=\frac{c}{3}=\lambda$ (say) $\Rightarrow a=\lambda, b=-\lambda$ and $c=3 \lambda$.
Putting these values in (i), we get the required equation of the plane as $\lambda(x-1)-\lambda(y-2)+3 \lambda(z-1)=0$

$$
\begin{equation*}
\Rightarrow \quad(x-1)-(y-2)+3(z-1)=0 \Rightarrow x-y+3 z=2 \tag{ii}
\end{equation*}
$$

Hence, the required equation of the plane is $x-y+3 z=2$.
The given line is $\frac{x+3}{2}=\frac{y-5}{-1}=\frac{z-7}{-1}$.

This line passes through the point ( $-3,5,7$ ).
Distance between the plane (ii) and the line (iii)
= Distance of any point on this line from the plane
= Length of perpendicular from ( $-3,5,7$ ) on plane (ii)
$$
=\frac{|-3-5+21-2|}{\sqrt{1^{2}+(-1)^{2}+3^{2}}}=\frac{11}{\sqrt{11}}=\sqrt{11} \text { units. }
$$

Hence, the distance between the desired plane and the given line is $\sqrt{11}$ units.

---

### Example 8:

Find the equation of the plane passing through the points $(0,0,0)$ and
$(3,-1,2)$ and parallel to the line $\frac{x-4}{1}=\frac{y+3}{-4}=\frac{z+1}{7}$.
[CBSE 2011]

#### Solution:

The general equation of the plane passing through the point $(3,-1,2)$ is given by

$$
\begin{equation*}
a(x-3)+b(y+1)+c(z-2)=0 . \tag{i}
\end{equation*}
$$

If this plane passes through the point $(0,0,0)$, we have

$$
\begin{equation*}
a(0-3)+b(0+1)+c(0-2)=0 \Rightarrow-3 a+b-2 c=0 . \tag{ii}
\end{equation*}
$$

D.r.'s of the normal to the plane (i) are $a, b, c$.
D.r.'s of the line $\frac{x-4}{1}=\frac{y+3}{-4}=\frac{z+1}{7}$ are $1,-4,7$.

The required plane is parallel to the given line only when the normal to this plane is perpendicular to this line.

$$
\begin{equation*}
\therefore \quad(a \times 1)+b \times(-4)+c \times 7=0 \Rightarrow a-4 b+7 c=0 . \tag{iii}
\end{equation*}
$$

On solving (ii) and (iii) by cross multiplication, we get:

$$
\begin{aligned}
& \frac{a}{(7-8)}=\frac{b}{(-2+21)}=\frac{c}{(12-1)} \\
\Rightarrow \quad & \frac{a}{-1}=\frac{b}{19}=\frac{c}{11}=\lambda(\text { say }) \Rightarrow a=-\lambda, b=19 \lambda \text { and } c=11 \lambda .
\end{aligned}
$$

Putting these values of $a, b, c$ in (i), we get:

$$
\begin{aligned}
& -\lambda(x-3)+19 \lambda(y+1)+11 \lambda(z-2)=0 \\
\Rightarrow & (x-3)-19(y+1)-11(z-2)=0 \\
\Rightarrow & x-19 y-11 z=0 .
\end{aligned}
$$

Hence, the required equation of the plane is **$x-19 y-11 z=0$**.

---

### Example 9:

Find the equation of the plane which passes through the point $(4,-1,2)$ and which is parallel to each of the lines $\frac{x-1}{1}=\frac{y-3}{2}=\frac{z-4}{3}$ and $\frac{x+2}{3}=\frac{y-2}{-1}=\frac{z+1}{2}$.

#### Solution:

The general equation of a plane passing through the point $A(4,-1,2)$ is given by

$$
\begin{equation*}
a(x-4)+b(y+1)+c(z-2)=0 \tag{i}
\end{equation*}
$$

This plane will be parallel to each of the given lines only when the normal to the plane is perpendicular to each of the given lines.

$$
\begin{array}{ll}
\therefore \quad & (1 \times a)+(2 \times b)+(3 \times c)=0 \Rightarrow a+2 b+3 c=0 . \\
& (3 \times a)+(-1) \times b+(2 \times c)=0 \Rightarrow 3 a-b+2 c=0 \tag{iii}
\end{array}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
& \frac{a}{(4+3)}=\frac{b}{(9-2)}=\frac{c}{(-1-6)} \\
\Rightarrow & \frac{a}{7}=\frac{b}{7}=\frac{c}{-7} \Rightarrow \frac{a}{1}=\frac{b}{1}=\frac{c}{-1}=\lambda \text { (say) } \\
\Rightarrow & a=\lambda, b=\lambda \text { and } c=-\lambda
\end{aligned}
$$

Putting these values of $a, b, c$ in (i), we get

$$
\begin{aligned}
& \lambda(x-4)+\lambda(y+1)-\lambda(z-2)=0 \\
\Rightarrow \quad & (x-4)+(y+1)-(z-2)=0 \Rightarrow x+y-z=1 .
\end{aligned}
$$

Hence, the required equation of the plane is **$x+y-z=1$**.

---

### Example 10:

Find the equation of the plane passing through $(2,3,-4)$ and $(1,-1,3)$ and parallel to the $x$-axis.

#### Solution:

The general equation of the plane passing through the point $A(2,3,-4)$ is given by

$$
\begin{equation*}
a(x-2)+b(y-3)+c(z+4)=0 . \tag{i}
\end{equation*}
$$

Since it passes through the point $B(1,-1,3)$, we have

$$
\begin{equation*}
a(1-2)+b(-1-3)+c(3+4)=0 \Rightarrow-a-4 b+7 c=0 . \tag{ii}
\end{equation*}
$$

If this plane is parallel to $x$-axis, then the normal to the plane is perpendicular to the $x$-axis.
D.r.'s of normal to plane (i) are $a, b, c$ and d.r.'s of the $x$-axis are $1, 0,0$.
$\therefore \quad a \times 1+b \times 0+c \times 0=0 \Rightarrow a=0$.
Putting $a=0$ in (ii), we get $7 c-4 b=0$.
Let $b=\lambda$. Then, $7 c=4 \lambda \Rightarrow c=\frac{4 \lambda}{7}$.
Putting $a=0, b=\lambda$ and $c=\frac{4 \lambda}{7}$ in (i), we get

$$
0 \times(x-2)+\lambda(y-3)+\frac{4 \lambda}{7}(z+4)=0
$$

$\Rightarrow \quad(y-3)+\frac{4}{7}(z+4)=0 \Rightarrow 7 y-21+4 z+16=0$
$\Rightarrow 7 y+4 z-5=0$.
Hence, the required equation of the plane is **$7 y+4 z-5=0$**.

---

### Example 11:

Find the equation of the plane passing through the point $(0,7,-7)$ and containing the line $\frac{x+1}{-3}=\frac{y-3}{2}=\frac{z+2}{1}$.

#### Solution:

The general equation of the plane passing through the point $(0,7,-7)$ is given by

$$
\begin{equation*}
a(x-0)+b(y-7)+c(z+7)=0 . \tag{i}
\end{equation*}
$$

If (i) contains the given line, then it must pass through the point $(-1,3,-2)$ and must be parallel to the given line.
If (i) passes through the point $(-1,3,-2)$, we have

$$
\begin{equation*}
a(-1-0)+b(3-7)+c(-2+7)=0 \Rightarrow a+4 b-5 c=0 . \tag{ii}
\end{equation*}
$$

If (i) is parallel to the given line, then its normal should be perpendicular to this line.

$$
\begin{equation*}
\therefore \quad(-3) a+2 b+1 \times c=0 \Rightarrow-3 a+2 b+c=0 . \tag{iii}
\end{equation*}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
& \frac{a}{(4+10)}=\frac{b}{(15-1)}=\frac{c}{(2+12)} \Rightarrow \frac{a}{14}=\frac{b}{14}=\frac{c}{14} \\
\Rightarrow & \frac{a}{1}=\frac{b}{1}=\frac{c}{1}=\lambda \text { (say). }
\end{aligned}
$$

Then $a=\lambda, b=\lambda$ and $c=\lambda$.

Putting $a=\lambda, b=\lambda$ and $c=\lambda$ in, we get

$$
\begin{aligned}
& \lambda x+\lambda(y-7)+\lambda(z+7)=0 \Rightarrow x+(y-7)+(z+7)=0 \\
\Rightarrow & x+y+z=0 .
\end{aligned}
$$

Hence, the required equation of the plane is **$x+y+z=0$**.

---

### Example 12:

Find the equation of the plane passing through the line of intersection of the planes $2 x+y-z=3$ and $5 x-3 y+4 z+9=0$ and parallel to the line

$$
\frac{x-1}{2}=\frac{y-3}{4}=\frac{z-5}{5} .
$$
[CBSE 2011]

#### Solution:

The equation of a plane passing through the intersection of the given planes is given by

$$
\begin{array}{rlr} 
& (2 x+y-z-3)+\lambda(5 x-3 y+4 z+9)=0 \text { for some real number } \lambda \\
\Rightarrow & (2+5 \lambda) x+(1-3 \lambda) y+(4 \lambda-1) z+(9 \lambda-3)=0 \tag{i}
\end{array}
$$

If this plane is parallel to the line $\frac{x-1}{2}=\frac{y-3}{4}=\frac{z-5}{5}$, then the normal to the plane is perpendicular to this line.
$\therefore \quad 2(2+5 \lambda)+4(1-3 \lambda)+5(4 \lambda-1)=0$
$\Rightarrow \quad(10 \lambda-12 \lambda+20 \lambda)+(4+4-5)=0$
$\Rightarrow 18 \lambda=-3 \Rightarrow \lambda=\frac{-3}{18}=\frac{-1}{6}$.
Putting $\lambda=\frac{-1}{6}$ in (i), we get

$$
\begin{aligned}
& \left(2-\frac{5}{6}\right) x+\left(1+\frac{3}{6}\right) y+\left(\frac{-4}{6}-1\right) z+\left(\frac{-9}{6}-3\right)=0 \\
\Rightarrow & 7 x+9 y-10 z-27=0 .
\end{aligned}
$$

Hence, the required equation of the plane is **$7 x+9 y-10 z-27=0$**.

---

### Example 13:

Show that the equation $by+c z+d=0$ represents a plane parallel to the $x$-axis. Find the equation of a plane which is parallel to the $x$-axis and passes through the points $A(2,3,1)$ and $B(4 .-5,3)$.

#### Solution:

The given equation is $0 \cdot x+b y+c z+d=0$, which is of the form $a x+b y+c z+d=0$.
Hence, the given equation represents a plane.
D.r.'s of the normal to this plane are $0, b, c$.
D.r.'s of the $x$-axis are $1,0,0$.

Now $0 \times 1+b \times 0+c \times 0=0$.
This shows that the given plane is parallel to the $x$-axis.
Thus, the equation of a plane parallel to the $x$-axis is

$$
\begin{equation*}
b y+c z+d=0 \tag{i}
\end{equation*}
$$

If it passes through the points $A(2,3,1)$ and $B(4,-5,3)$, we have

$$
\begin{align*}
& 3 b+c+d=0  \tag{ii}\\
& -5 b+3 c+d=0 \tag{ii}
\end{align*}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
& \frac{b}{(1-3)}=\frac{c}{(-5-3)}=\frac{d}{(9+5)} \\
\Rightarrow & \frac{b}{-2}=\frac{c}{-8}=\frac{d}{14} \Rightarrow \frac{b}{1}=\frac{c}{4}=\frac{d}{-7}=k(\text { say }) \\
\Rightarrow & b=k, c=4 k \text { and } d=-7 k .
\end...