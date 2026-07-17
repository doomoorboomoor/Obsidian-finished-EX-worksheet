## Equations of a Plane in Various Forms

## Equation of a Plane in the Normal Form

### Vector Form

**Theorem 1:** If $\hat{n}$ is a unit vector normal to a given plane, directed from the origin to the plane, and $p$ is the length of the perpendicular drawn from the origin to the plane then the vector equation of the plane is $\vec{r} \cdot \hat{n}=p$.

**Proof:** Let $O$ be the origin, and let $ON$ be the perpendicular drawn from $O$ to the given plane. Let $ON=p$.

Let $\hat{n}$ be a unit vector along $\overrightarrow{ON}$.
Then, $\overrightarrow{ON}=p \hat{n}$.

Let $P$ be an arbitrary point on the plane, and let the position vector of $P$ be $\vec{r}$.
Then, $\overrightarrow{OP}=\vec{r}$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-081.jpg?height=277&width=300&top_left_y=1174&top_left_x=907)

Since $\overrightarrow{NP}$ lies on the plane, $\overrightarrow{NP}$ is perpendicular to $\hat{n}$.
$\therefore \quad \overrightarrow{NP} \cdot \hat{n}=0$
$\Rightarrow \quad(\overrightarrow{OP}-\overrightarrow{ON}) \cdot \hat{n}=0 \Rightarrow(\vec{r}-\hat{p n}) \cdot \hat{n}=0$
$\Rightarrow \quad \vec{r} \cdot \hat{n}-p \hat{n} \cdot \hat{n}=0 \Rightarrow \vec{r} \cdot \hat{n}=p$.
Hence, the required equation of the plane is $\vec{r} \cdot \vec{n}=p$.

**Remark:** The equation of a plane which is at a distance $p$ from the origin and which is perpendicular to $\hat{n}$ is $\vec{r} \cdot \hat{n}=p$.

**Corollary:** If $\vec{n}$ is a vector normal to a given plane then $\vec{r} \cdot \hat{n}=q$ represents a plane.

**Proof:** $\vec{r} \cdot \vec{n}=q \Rightarrow \vec{r} \cdot \frac{\vec{n}}{|\vec{n}|}=\frac{q}{|\vec{n}|} \Rightarrow \vec{r} \cdot \hat{n}=p$, where $\frac{q}{|\vec{n}|}=p$.
But, $\vec{r} \cdot \hat{n}=p$ represents a plane.
Hence, $\vec{r} \cdot \vec{n}=q$ also represents a plane.

### Cartesian Forms

**(i) Normal Form:**

Let $l, m, n$ be the d.c.'s of $\hat{n}$ and $P(x, y, z)$ be the given point.
Then, $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}$ and $\hat{n}=l \hat{i}+m \hat{j}+n \hat{k}$.
On substituting these values in $\vec{r} \cdot \hat{n}=p$, we get

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k}) \cdot(l \hat{i}+m \hat{j}+n \hat{k})=p \\
\Rightarrow \quad & l x+m y+n z=p
\end{aligned}
$$

This is known as the **normal form** of the Cartesian equation of a plane.

**(ii) General Form:**

Let $a, b, c$ be the d.r.'s of $\vec{n}$ and $P(x, y, z)$ be the given point.
Then, $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}$ and $\vec{n}=a \hat{i}+b \hat{j}+c \hat{k}$.
On substituting these values $\vec{r} \cdot \vec{n}=q$, we get

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k}) \cdot(a \hat{i}+b \hat{j}+c \hat{k})=q \\
\Rightarrow \quad & a x+b y+c z=q \Rightarrow a x+b y+c z+d=0, \text { where } d=-q .
\end{aligned}
$$

The equation $a x+b y+c z+d=0$ is called the **General Form** of the Cartesian equation of a plane.

---

## Equation of a Plane Passing through a Given Point and Perpendicular to a Given Vector

### Vector Form

**Theorem 1:** The vector equation of a plane passing through a point $A$ with position vector $\vec{a}$ and perpendicular to a given vector $\vec{n}$ is $(\vec{r}-\vec{a}) \cdot \vec{n}=0$.

**Proof:** Let $O$ be the origin, and let $\pi$ be the given plane.
Let $A$ be a given point on the plane with position vector $\vec{a}$.
Let $P$ be an arbitrary point on the plane with position vector $\vec{r}$.

Then, $\overrightarrow{O A}=\vec{a}$, and $\overrightarrow{O P}=\vec{r}$.
$\therefore \quad \overrightarrow{A P}=(\overrightarrow{O P}-\overrightarrow{O A})=(\vec{r}-\vec{a})$.
Let $\overrightarrow{O N}=\vec{n}$ be normal to the plane.
Now, $\overrightarrow{A P}$ lies in the plane and $\vec{n}$ is normal to

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-083.jpg?height=260&width=300&top_left_y=159&top_left_x=905)

the plane.
$\therefore \quad \overrightarrow{A P} \perp \vec{n} \Rightarrow \overrightarrow{A P} \cdot \vec{n}=0 \Rightarrow(\vec{r}-\vec{a}) \cdot \vec{n}=0$.
Hence, the equation of the plane passing through the point with position vector $\vec{a}$ and perpendicular to $\vec{n}$ is $(\vec{r}-\vec{a}) \cdot \vec{n}=0$.

**Corollary:** The vector equation of the plane passing through the origin and perpendicular to $\vec{n}$ is $\vec{r} \cdot \vec{n}=0$.

### Cartesian Form

**Theorem 2:** The Cartesian equation of a plane passing through a point $A\left(x_{1}, y_{1}, z_{1}\right)$ and perpendicular to a line having d.r.'s $a, b, c$ is

$$
a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0 .
$$

**Proof:** Let $\vec{r}=x \hat{i}+y \hat{j}+z \hat{k}, \vec{a}=x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}$ and $\vec{n}=A \hat{i}+B \hat{j}+C \hat{k}$.
Substituting these values in $(\vec{r}-\vec{a}) \cdot \vec{n}=0$, we get

$$
\begin{aligned}
& \left\{\left(x-x_{1}\right) \hat{i}+\left(y-y_{1}\right) \hat{j}+\left(z-z_{1}\right) \hat{k}\right\} \cdot(A \hat{i}+B \hat{j}+C \hat{k})=0 \\
\Rightarrow \quad & a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0 .
\end{aligned}
$$

This is known as the equation of a plane in **one-point form**.

---

## Summary

1.  (i) Let a plane be at a distance $p$ form the origin and $\hat{n}$ be a unit vector perpendicular to the plane.
    Then, equation of the plane is $\vec{r} \cdot \hat{n}=p$.
    (ii) The Cartesian form of equation of this plane is $l x+m y+n z=p$, where $l, m, n$ are the d.c.'s of normal to the plane.
    (iii) The general equation of a plane is $\vec{r} \cdot \vec{n}=q$.
    (iv) Its Cartesian form is $a x+b y+c z+d=0$, where $a, b, c$ are the d.r.'s of $\vec{n}$.
2.  (i) The vector equation of a plane passing through a point $A$ with position vector $\vec{a}$ and perpendicular to $\vec{n}$ is $(\vec{r}-\vec{a}) \cdot \vec{n}=0$.
    (ii) The Cartesian equation of a plane passing through a point $A\left(x_{1}, y_{1}, z_{1}\right)$ and perpendicular to a line having d.r.'s $a, b, c$ is $a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0$.

---

## Solved Examples

### Example 1:

Find the vector equation of a plane which is at a distance of 5 units from the origin and which has $\hat{j}$ as the unit vector normal to it.

#### Solution:

Clearly, the required equation of the plane is $\vec{r} \cdot \hat{j}=5$.

---

### Example 2:

Find the vector equation of a plane which is at a distance of 6 units from the origin and which is normal to the vector $(\hat{i}+2 \hat{j}-2 \hat{k})$.

#### Solution:

Here $\vec{n}=(\hat{i}+2 \hat{j}-2 \hat{k})$ and $p=6$.

$$
\therefore \quad \hat{n}=\frac{(\hat{i}+2 \hat{j}-2 \hat{k})}{\sqrt{1^{2}+2^{2}+(-2)^{2}}}=\left(\frac{1}{3} \hat{i}+\frac{2}{3} \hat{j}-\frac{2}{3} \hat{k}\right) .
$$

So, the vector equation of the plane is

$$
\begin{aligned}
\vec{r} \cdot \hat{n}=p & \Rightarrow \vec{r} \cdot\left(\frac{1}{3} \hat{i}+\frac{2}{3} \hat{j}-\frac{2}{3} \hat{k}\right)=6 \\
& \Rightarrow \vec{r}=(\hat{i}+2 \hat{j}-2 \hat{k})=18
\end{aligned}
$$

Hence, the required vector equation of the plane is

$$
\vec{r} \cdot(\hat{i}+2 \hat{j}-2 \hat{k})=18
$$

---

### Example 3:

Find the vector equation of a plane passing through a point having position vector $(2 i-j+k)$ and perpendicular to the vector $\wedge \wedge \wedge$ ( $4 i+2 j-3 k$ ). Also reduce it to Cartesian form.

#### Solution:

Here $\vec{a}=(2 \hat{i}-\hat{j}+\hat{k})$ and $\vec{n}=(4 \hat{i}+2 \hat{j}-3 \hat{k})$.
Clearly, the required vector equation is $(\vec{r}-\vec{a}) \cdot \vec{n}=0$

$$
\begin{aligned}
\Rightarrow \vec{r} \cdot \vec{n}=\vec{a} \cdot \vec{n} & \\
\Rightarrow \vec{r} \cdot(4 \hat{i}+2 \hat{j}-3 \hat{k}) & =(2 \hat{i}-\hat{j}+\hat{k}) \cdot(4 \hat{i}+2 \hat{j}-3 \hat{k}) \\
& =(8-2-3)=3
\end{aligned}
$$

Hence, the vector equation of the given plane is

$$
\begin{equation*}
\vec{r} \cdot(4 \hat{i}+2 \hat{j}-3 \hat{k})=3 \tag{i}
\end{equation*}
$$

#### Reduction to Cartesian Form:

Putting $\vec{r}=(x \hat{i}+y \hat{j}+z \hat{k})$, we get

$$
(x \hat{i}+y \hat{j}+z \hat{k}) \cdot(4 \hat{i}+2 \hat{j}-3 \hat{k})=3 \Rightarrow 4 x+2 y-3 z=3
$$

Hence, the equation of the given plane in Cartesian form is $4 x+2 y-3 z=3$.

---

### Example 4:

Find a unit vector normal to the plane $\vec{r} \cdot(2 \hat{i}-3 \hat{j}+6 \hat{k})+14=0$.

#### Solution:

The equation of the given plane is

$$
\begin{aligned}
& \vec{r} \cdot(2 \hat{i}-3 \hat{j}+6 \hat{k})+14=0 \\
\Leftrightarrow & \vec{r} \cdot(2 \hat{i}-3 \hat{j}+6 \hat{k})=-14 \Rightarrow \vec{r} \cdot(-2 \hat{i}+3 \hat{j}-6 \hat{k})=14 \\
\Rightarrow & \vec{r} \cdot \vec{n}=14, \text { where } \vec{n}=(-2 \hat{i}+3 \hat{j}-6 \hat{k}) \\
\Rightarrow & \vec{r} \cdot \frac{\vec{n}}{|\vec{n}|}=\frac{14}{|\vec{n}|}, \text { where }|\vec{n}|=\sqrt{(-2)^{2}+3^{2}+(-6)^{2}}=7 \\
\Rightarrow & \vec{r} \cdot \frac{(-2 \hat{i}+3 \hat{j}-6 \hat{k})}{7}=\frac{14}{7} \Rightarrow \vec{r} \cdot\left(-\frac{2}{7} \hat{i}+\frac{3}{7} \hat{j}-\frac{6}{7} \hat{k}\right)=2 .
\end{aligned}
$$

Hence, the unit vector normal to the given plane is

$$
\hat{n}=\left(-\frac{2}{7} \hat{i}+\frac{3}{7} \hat{j}-\frac{6}{7} \hat{k}\right)
$$

---

### Example 5:

Find the direction cosines of the perpendicular from the origin to the plane $\vec{r} \cdot(6 \hat{i}-3 \hat{j}-2 \hat{k})+3=0$.

#### Solution:

Clearly, we have to find the direction cosines of the normal to the given plane.
The given equation may be written as

$$
\begin{aligned}
& \vec{r} \cdot(6 \hat{i}-3 \hat{j}-2 \hat{k})=-3 \Rightarrow \vec{r} \cdot(-6 \hat{i}+3 \hat{j}+2 \hat{k})=3 \\
\Rightarrow & \vec{r} \cdot \vec{n}=3, \text { where } \vec{n}=(-6 \hat{i}+3 \hat{j}+2 \hat{k}) \\
\Rightarrow & \vec{r} \cdot \frac{\vec{n}}{|\vec{n}|}=\frac{3}{|\vec{n}|}, \text { where }|\vec{n}|=\sqrt{(-6)^{2}+3^{2}+2^{2}}=7 \\
\Rightarrow & \vec{r} \cdot \frac{(-6 \hat{i}+3 \hat{j}+2 \hat{k})}{7}=\frac{3}{7} \Rightarrow \vec{r} \cdot\left(-\frac{6}{7} \hat{i}+\frac{3}{7} \hat{j}+\frac{2}{7} \hat{k}\right)=\frac{3}{7} .
\end{aligned}
$$

Hence, the direction cosines of the normal to the given plane are

$$
\left(-\frac{6}{7}, \frac{3}{7}, \frac{2}{7}\right) .
$$

---

### Example 6:

Find the Cartesian equation of a plane whose vector equation is $\vec{r} \cdot(2 \hat{i}+5 \hat{j}-4 \hat{k})=3$.

#### Solution:

We have

$$
\begin{aligned}
& \vec{r} \cdot(2 \hat{i}+5 \hat{j}-4 \hat{k})=3 \Leftrightarrow(x \hat{i}+y \hat{j}+z \hat{k}) \cdot(2 \hat{i}+5 \hat{j}-4 \hat{k})=3 \\
\Leftrightarrow & 2 x+5 y-4 z=3
\end{aligned}
$$

Hence, the required equation is $2 x+5 y-4 z=3$.

---

### Example 7:

Find the vectors equation of a plane whose Cartesian equation is $2 x-3 y+4 z+6=0$.
Find the direction cosines of the normal to the plane and its distance from the origin.

#### Solution:

The given equation of the plane is

$$
\begin{equation*}
2 x-3 y+4 z=-6 \Rightarrow-2 x+3 y-4 z=6 \tag{i}
\end{equation*}
$$

If $\vec{r}$ is the position vector of any point $P(x, y, z)$ on plane (i), then we may write it as

$$
\begin{aligned}
& (x \hat{i}+y \hat{j}+z \hat{k}) \cdot(-2 \hat{i}+3 \hat{j}-4 \hat{k})=6 \\
\Rightarrow & \vec{r} \cdot(-2 \hat{i}+3 \hat{j}-4 \hat{k})=6 \\
\Rightarrow & \vec{r} \cdot \vec{n}=6, \text { where } \vec{n}=(-2 \hat{i}+3 \hat{j}-4 \hat{k}) \\
\Rightarrow & \vec{r} \cdot \frac{\vec{n}}{|\vec{n}|}=\frac{6}{|\vec{n}|}, \text { where }|\vec{n}|=\sqrt{(-2)^{2}+3^{2}+(-4)^{2}}=\sqrt{29} \\
\Rightarrow & \vec{r} \cdot\left(\frac{-2}{\sqrt{29}} \hat{i}+\frac{3}{\sqrt{29}} \hat{j}-\frac{4}{\sqrt{29}} \hat{k}\right)=\frac{6}{\sqrt{29}} \cdot
\end{aligned}
$$

$\therefore$ d.c.'s of normal to the given plane are $\frac{-2}{\sqrt{29}}, \frac{3}{\sqrt{29}}, \frac{-4}{\sqrt{29}}$, and its distance from the origin is $\frac{6}{\sqrt{29}}$.

---

### Example 8:

Find the vector equation of the plane whose Cartesian equation is $5 y+8=0$.
Find the direction cosines of the normal to the plane and its distance from the origin.

#### Solution:

The given equation of the plane is

$$
\begin{equation*}
5 y=-8 \Rightarrow-5 y=8 \Rightarrow 0 \cdot x-5 y+0 z=8 . \tag{i}
\end{equation*}
$$

Let $\vec{r}$ be the position vector of any point $P(x, y, z)$ on plane (i). Then, the above equation may be written as

$$
\begin{aligned}
& \vec{r} \cdot(0 \hat{i}-5 \hat{j}+0 \hat{k})=8 \Rightarrow \vec{r} \cdot \vec{n}=8, \text { where } \vec{n}=0 \hat{i}-5 \hat{j}+0 \hat{k} \\
\Rightarrow & \vec{r} \cdot \frac{\vec{n}}{|\vec{n}|}=\frac{8}{|\vec{n}|}, \text { where }|\vec{n}|=\sqrt{0^{2}+(-5)^{2}+0^{2}}=5 \\
\Rightarrow & \vec{r} \cdot\left(\frac{0}{5} \hat{i}-\frac{5}{5} \hat{j}+\frac{0}{5} \hat{k}\right)=\frac{8}{5} \Rightarrow \vec{r} \cdot(0 \hat{i}-\hat{j}+0 \hat{k})=\frac{8}{5} .
\end{aligned}
$$

$\therefore$ d.c.'s of the normal to the plane are $0,-1,0$ and its distance from the origin is $\frac{8}{5}$ units.

---

### Example 9:

Find the Cartesian form of the equation of the plane

$$
\vec{r}=(s-2 t) \hat{i}+(3-t) \hat{j}+(2 s+t) \hat{k}
$$

#### Solution:

We have

$$
\begin{aligned}
& \vec{r}=(s-2 t) \hat{i}+(3-t) \hat{j}+(2 s+t) \hat{k} \\
\Leftrightarrow & (x \hat{i}+y \hat{j}+z \hat{k})=(s-2 t) \hat{i}+(3-t) \hat{j}+(2 s+t) \hat{k} \\
\Leftrightarrow & x=s-2 t, y=3-t \text { and } z=2 s+t \\
\Leftrightarrow & x-2 y=(s-6) \text { and } y+z=(3+2 s) \quad \text { [eliminating } t \text { ] } \\
\Leftrightarrow & x-2 y+6=\frac{1}{2}(y+z-3) \quad[\text { equating the values of } s] \\
\Leftrightarrow & 2 x-4 y+12=y+z-3 \Leftrightarrow 2 x-5 y-z+15=0 .
\end{aligned}
$$

This is the required Cartesian form of the equation of the given plane.

---

### Example 10:

Find the vector and Cartesian equations of the plane which passes through the point $(5,2,-4)$ and perpendicular to the line with direction ratios $2,3,-1$.

#### Solution:

The plane passes through the point $A(5,2,-4)$ whose position vector is $\vec{a}=(5 \hat{i}+2 \hat{j}-4 \hat{k})$ and the normal vector $\vec{n}$ perpendicular to the plane is $\vec{n}=(2 \hat{i}+3 \hat{j}-\hat{k})$.
So, the vector equation of the plane is

$$
\begin{aligned}
\vec{r} \cdot \vec{n}=\vec{a} \cdot \vec{n} & \\
\Rightarrow \quad \vec{r} \cdot(2 \hat{i}+3 \hat{j}-\hat{k}) & =(5 \hat{i}+2 \hat{j}-4 \hat{k}) \cdot(2 \hat{i}+3 \hat{j}-\hat{k}) \\
& =(10+6+4)=20 .
\end{aligned}
$$

Hence, the required vector equation of the plane is

$$
\begin{equation*}
\vec{r}=(2 \hat{i}+3 \hat{j}-\hat{k})=20 . \tag{i}
\end{equation*}
$$

#### Cartesian Form:

Taking $\vec{r}=(x \hat{i}+y \hat{j}+z \hat{k})$, equation (i) may be written as

$$
(x \hat{i}+y \hat{j}+z \hat{k}) \cdot(2 \hat{i}+3 \hat{j}-\hat{k})=20 \Rightarrow 2 x+3 y-z=20 .
$$

Hence, the required Cartesian equation is $2 x+3 y-z=20$.

---

### Example 11:

The foot of the perpendicular drawn from the origin to a plane is $(4,-2,-5)$. Find the equation of the plane in (i) vector form, (ii) Cartesian form. \[CBSE 2007]

#### Solution:

Let $O(0,0,0)$ be the origin and $P(4,-2,-5)$ be the foot of the perpendicular drawn from $O$ to the given plane.
(i) Clearly, the required plane passes through the point $P$ and it is perpendicular to $O P$.

$$
\therefore \quad \vec{a}=(4 \hat{i}-2 \hat{j}-5 \hat{k}) \text { and } \vec{n}=\overrightarrow{O P}(4 \hat{i}-2 \hat{j}-5 \hat{k}) .
$$

So, the required equation of the plane is

$$
\begin{aligned}
\vec{r} & \cdot \vec{n}=\vec{a} \cdot \vec{n} \\
\Rightarrow \quad \vec{r} & =(4 \hat{i}-2 \hat{j}-5 \hat{k}) \\
& =(4 \hat{i}-2 \hat{j}-5 \hat{k}) \cdot(4 \hat{i}-2 \hat{j}-5 \hat{k}) \\
& =(16+4+25)=45
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-088.jpg?height=251&width=298&top_left_y=247&top_left_x=911)

Hence, the vector equation of the plane is

$$
\begin{equation*}
\vec{r} \cdot(4 \hat{i}-2 \hat{j}-5 \hat{k})=45 \tag{i}
\end{equation*}
$$

(ii) Putting $\vec{r}=(x \hat{i}+y \hat{j}+z \hat{k})$ in (i), we get

$$
(x \hat{i}+y \hat{j}+z \hat{k}) \cdot(4 \hat{i}-2 \hat{j}-5 \hat{k})=45
$$

$\Rightarrow 4 x-2 y-5 z=45$, which is the required equation of the plane in Cartesian form.

---

### Example 12:

Find the coordinates of the foot of the perpendicular drawn from the origin to the plane $3 y+4 z-6=0$.

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
0 x+3 y+4 z-6=0 \tag{i}
\end{equation*}
$$

D.r.'s of normal to the given plane are $0,3,4$.

The equation of the line through the origin $O$ and perpendicular to the plane (i) is given by

$$
\begin{equation*}
\frac{x}{0}=\frac{y}{3}=\frac{z}{4}=\lambda \text { (say). } \tag{ii}
\end{equation*}
$$

The general point on (ii) is given by $N(0,3 \lambda, 4 \lambda)$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-088.jpg?height=282&width=404&top_left_y=1080&top_left_x=803)

If this point lies on plane (i), we have

$$
(0 \times 0)+(3 \times 3 \lambda)+(4 \times 4 \lambda)=6 \Rightarrow 25 \lambda=6 \Rightarrow \lambda=\frac{6}{25}
$$

Hence, the foot of the perpendicular drawn from the origin to the given plane is $N\left(0, \frac{18}{25}, \frac{24}{25}\right)$.

---

### Example 13:

Find the coordinates of the point where the line $\frac{x+1}{2}=\frac{y+2}{3}=\frac{z+3}{4}$ meets the plane $x+y+4 z=6$.
[CBSE 2006, '08]

#### Solution:

The equation of the given line is

$$
\begin{equation*}
\frac{x+1}{2}=\frac{y+2}{3}=\frac{z+3}{4}=\lambda \text { (say). } \tag{i}
\end{equation*}
$$

The equation of the given plane is

$$
\begin{equation*}
x+y+4 z=6 \tag{ii}
\end{equation*}
$$

The general point on the line (i) is ( $2 \lambda-1,3 \lambda-2,4 \lambda-3$ ).
Let the given line (i) meet the given plane (ii) at the point $P(2 \lambda-1,3 \lambda-2,4 \lambda-3)$ for some value of $\lambda$.
Then, $(2 \lambda-1)+(3 \lambda-2)+4(4 \lambda-3)=6 \Rightarrow 21 \lambda=21 \Rightarrow \lambda=1$.
Hence, the required point of intersection of the given line (i) and the given plane (ii) is $P(2 \times 1-1,3 \times 1-2,4 \times 1-3)$, i.e. $P(1,1,1)$.

---

### Example 14:

Find the coordinates of the point where the line through the points $A(3,4,1)$ and $B(5,1,6)$ crosses the XY-plane.
[CBSE 2012]

#### Solution:

The equation of the line through the points $A(3,4,1)$ and $B(5,1,6)$ is given by

$$
\begin{equation*}
\frac{x-3}{(5-3)}=\frac{y-4}{(1-4)}=\frac{z-1}{(6-1)} \Rightarrow \frac{x-3}{2}=\frac{y-4}{-3}=\frac{z-1}{5} . \tag{i}
\end{equation*}
$$

The equation of the $X Y$-plane is $z=0$.
Since the line (i) meets the $X Y$-plane, we have

$$
\begin{aligned}
& \frac{x-3}{2}=\frac{y-4}{-3}=\frac{0-1}{5} \Rightarrow \frac{x-3}{2}=\frac{-1}{5} \text { and } \frac{y-4}{-3}=\frac{-1}{5} \\
\Rightarrow & x=\left(3-\frac{2}{5}\right)=\frac{13}{5}, y=\left(4+\frac{3}{5}\right)=\frac{23}{5} \text { and } z=0 .
\end{aligned}
$$

Hence, the given line crosses the $X Y$-plane at the point

$$
P\left(\frac{13}{5}, \frac{23}{5}, 0\right) .
$$

---

### Example 15:

Find the distance of the point $P(-1,-5,-10)$ from the point of intersection of the line joining the points $A(2,-1,2)$ and $B(5,3,4)$ with the plane $x-y+z=5$.
[CBSE 2014]

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
x-y+z=5 \tag{i}
\end{equation*}
$$

The equation of the line $A B$ is

$$
\begin{equation*}
\frac{x-2}{(5-2)}=\frac{y+1}{(3+1)}=\frac{z-2}{(4-2)} \Rightarrow \frac{x-2}{3}=\frac{y+1}{4}=\frac{z-2}{2}=\lambda \text { (say).... } \tag{ii}
\end{equation*}
$$

For some value of $\lambda$, let the point $Q(3 \lambda+2,4 \lambda-1,2 \lambda+2)$ be the point of intersection of the plane (i) and the line (ii).
Then, $(3 \lambda+2)-(4 \lambda-1)+(2 \lambda+2)=5 \Rightarrow \lambda=0$.
So, the required point $Q$ is $Q(2,-1,2)$.

$$
\begin{aligned}
\therefore P Q & =\sqrt{(2+1)^{2}+(-1+5)^{2}+(2+10)^{2}} \\
& =\sqrt{3^{2}+4^{2}+(12)^{2}}=\sqrt{9+16+144} \\
& =\sqrt{169}=13 \text { units. }
\end{aligned}
$$

Hence, the required distance is 13 units.

---

### Example 16:

Find the coordinates of the point where the line through $(3,-4,-5)$ and $(2,-3,1)$ crosses the plane passing through the points $(2,2,1),(3,0,1)$ and $(4,-1,0)$.
[CBSE 2013]

#### Solution:

We know that the equation of a plane passing through the points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0 .
$$

$\therefore$ the equation of the plane passing through the points $A(2,2,1)$, $B(3,0,1)$ and $C(4,-1,0)$ is given by

$$
\Rightarrow\left|\begin{array}{ccc}x-2 & y-2 & z-1 \\ 3-2 & 0-2 & 1-1 \\ 4-2 & -1-2 & 0-1\end{array}\right|=0 \Rightarrow\left|\begin{array}{ccc}x-2 & y-2 & z-1 \\ 1 & -2 & 0 \\ 2 & -3 & -1\end{array}\right|=0
$$

$\Rightarrow \quad(x-2)(2-0)-(y-2)(-1-0)+(z-1)(-3+4)=0$

$$
\begin{equation*}
\Rightarrow \quad 2(x-2)+1 \cdot(y-2)+1 \cdot(z-1)=0 \Rightarrow 2 x+y+z=7 \text . \tag{i}
\end{equation*}
$$

The equation of the line passing through the points $P(3,-4,-5)$ and $Q(2,-3,1)$ is given by

$$
\frac{x-3}{(2-3)}=\frac{y+4}{(-3+4)}=\frac{z+5}{(1+5)} \Rightarrow \frac{x-3}{-1}=\frac{y+4}{1}=\frac{z+5}{6}=\lambda \text { (say). }
$$

Any general point on line $P Q$ is given as $(-\lambda+3, \lambda-4,6 \lambda-5)$.
For some value of $\lambda$, let the point $R(-\lambda+3, \lambda-4,6 \lambda-5)$ lie on the plane (i). Then,

$$
2(-\lambda+3)+(\lambda-4)+(6 \lambda-5)=7 \Rightarrow 5 \lambda=10 \Rightarrow \lambda=2 .
$$

Putting $\lambda=2$, we get the point of intersection of the given line and the given plane as $R(-2+3,2-4,12-5)$, i.e., $R(1,-2,7)$.

---

### Example 17:

Find the distance of the point $(1,-2,3)$ from the plane $x-y+z=5$ measured parallel to the line $\frac{x-1}{2}=\frac{y-3}{3}=\frac{z+2}{-6}$.
[CBSE 2013C]

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
x-y+z=5 \tag{i}
\end{equation*}
$$

The equation of the given line is

$$
\begin{equation*}
\frac{x-1}{2}=\frac{y-3}{3}=\frac{z+2}{-6} . \tag{ii}
\end{equation*}
$$

The equation of the line passing through the point $P(1,-2,3)$ and parallel to line

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-090.jpg?height=264&width=290&top_left_y=1471&top_left_x=917)

(ii) is given by

$$
\begin{equation*}
\frac{x-1}{2}=\frac{y+2}{3}=\frac{z-3}{-6}=\lambda \text { (say). } \tag{iii}
\end{equation*}
$$

The general point on line (iii) is ( $2 \lambda+1,3 \lambda-2,6 \lambda+3$ ).

For some value of $\lambda$, let the point $Q(2 \lambda+1,3 \lambda-2,-6 \lambda+3)$ lie on plane (i). Then, we have

$$
(2 \lambda+1)-(3 \lambda-2)+(-6 \lambda+3)=5 \Rightarrow-7 \lambda=-1 \Rightarrow \lambda=\frac{1}{7}
$$

So, the coordinates of $Q$ are

$$
\begin{aligned}
Q\left(\frac{2}{7}+1,\right. & \left.\frac{3}{7}-2, \frac{-6}{7}+3\right), \text { i.e., } Q\left(\frac{9}{7}, \frac{-11}{7}, \frac{15}{7}\right) \\
\text { Distance } P Q & =\sqrt{\left(\frac{9}{7}-1\right)^{2}+\left(\frac{-11}{7}+2\right)^{2}+\left(\frac{15}{7}-3\right)^{2}} \\
& =\sqrt{\left(\frac{2}{7}\right)^{2}+\left(\frac{3}{7}\right)^{2}+\left(\frac{-6}{7}\right)^{2}}=\frac{1}{7} \sqrt{4+9+36} \\
& =\frac{1}{7} \times \sqrt{49}=\left(\frac{1}{7} \times 7\right)=1 \text { unit. }
\end{aligned}
$$

Hence, the required distance is 1 unit.

---

### Example 18:

Find the distance of the point ( $3,4,5$ ) from the plane $x+y+z=2$, measured parallel to the line $2 x=y=z$.
[CBSE 2012C]

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
x+y+z=2 \tag{i}
\end{equation*}
$$

The equation of the given line is

$$
\begin{equation*}
2 x=y=z \Rightarrow \frac{x}{1}=\frac{y}{2}=\frac{z}{2} . \tag{ii}
\end{equation*}
$$

The equation of the line passing through the point $P(3,4,5)$ and parallel to the

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-091.jpg?height=263&width=302&top_left_y=1007&top_left_x=905)

given line (ii) is

$$
\begin{equation*}
\frac{x-3}{1}=\frac{y-4}{2}=\frac{z-5}{2}=\lambda(\text { say }) . \tag{iii}
\end{equation*}
$$

The general point on line (iii) is $(\lambda+3,2 \lambda+4,2 \lambda+5)$.
For some value of $\lambda$, let the point $Q(\lambda+3,2 \lambda+4,2 \lambda+5)$ lie on the plane (i). Then,

$$
\begin{aligned}
& (\lambda+3)+(2 \lambda+4)+(2 \lambda+5)=2 \\
\Rightarrow \quad & 5 \lambda=-10 \Rightarrow \lambda=-2 .
\end{aligned}
$$

$\therefore \quad$ coordinates of $Q$ are $Q(-2+3,-4+4,-4+5)$, i.e., $Q(1,0,1)$.
Distance $P Q=\sqrt{(3-1)^{2}+(4-0)^{2}+(5-1)^{2}}$

$$
\begin{aligned}
& =\sqrt{2^{2}+4^{2}+4^{2}}=\sqrt{4+16+16} \\
& =\sqrt{36}=6 \text { units. }
\end{aligned}
$$

Hence, the required distance is 6 units.

---

### Example 19:

Find the distance of the point ( $-2,3,-4$ ) from the line $\frac{x+2}{3}=\frac{2 y+3}{4}=\frac{3 z+4}{5}, \quad$ measured parallel to the plane $4 x+12 y-3 z+1=0$.
[CBSE 2008]

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
4 x+12 y-3 z+1=0 \tag{i}
\end{equation*}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-092.jpg?height=264&width=490&top_left_y=420&top_left_x=416)

Let $P(-2,3,-4)$ be the given point.
Let $l$ be the given line whose equation is

$$
\begin{equation*}
\frac{x+2}{3}=\frac{2 y+3}{4}=\frac{3 z+4}{5}=\lambda \text { (say). } \tag{ii}
\end{equation*}
$$

The general point on this line is $\left(3 \lambda-2, \frac{4 \lambda-3}{2}, \frac{5 \lambda-4}{3}\right)$.
For some value of $\lambda$, let the point $Q\left(3 \lambda-2, \frac{4 \lambda-3}{2}, \frac{5 \lambda-4}{3}\right)$ lie on the line (ii) such that $P Q$ is parallel to the given plane (i).
D.r.'s of $P Q$ are $(3 \lambda-2+2),\left(\frac{4 \lambda-3}{2}-3\right),\left(\frac{5 \lambda-4}{3}+4\right)$, i.e., $3 \lambda, \frac{4 \lambda-9}{2}, \frac{5 \lambda+8}{3}$.
D.r.'s of the normal to the given plane are $4,12,-3$.

Now, $P Q$ is parallel to the given plane (i).
$\Rightarrow \quad P Q$ is perpendicular to the normal to the the plane (i).
$\Rightarrow \quad(4 \times 3 \lambda)+12 \times \frac{(4 \lambda-9)}{2}-3 \times \frac{(5 \lambda-8)}{3}=0$
$\Rightarrow 12 \lambda+(24 \lambda-54)-(5 \lambda-8)=0 \Rightarrow 31 \lambda=62 \Rightarrow \lambda=2$.
$\therefore \quad$ coordinates of $Q$ are $Q\left(4, \frac{5}{2}, 2\right)$

$$
\begin{aligned}
\Rightarrow P Q & =\sqrt{(4+2)^{2}+\left(\frac{5}{2}-3\right)^{2}+(2+4)^{2}}=\sqrt{6^{2}+\left(\frac{-1}{2}\right)^{2}+6^{2}} \\
& =\sqrt{72+\frac{1}{4}}=\sqrt{\frac{289}{4}}=\frac{17}{2} \text { units }=8.5 \text { units. }
\end{aligned}
$$

Hence, the required distance of the given point from the given line is 8.5 units.

---

### Example 20:

Find the length and the foot of the perpendicular from the point $P(7,14,5)$ to the plane $2 x+4 y-z=2$. Also, find the image of the point $P$ in the plane.
[CBSE 2012]

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
2 x+4 y-z=2 \tag{i}
\end{equation*}
$$

The d.r.'s of the normal to this plane are $2,4,-1$.
The equation of the line passing through the point $P(7,14,5)$ and perpendicular to the given plane (i) is given by

$$
\frac{x-7}{2}=\frac{y-14}{4}=\frac{z-5}{-1}=\lambda \text { (say) }
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-093.jpg?height=367&width=300&top_left_y=290&top_left_x=907)

A general point on this line is $(2 \lambda+7,4 \lambda+14,-\lambda+5)$.
For some value of $\lambda$, let the point $Q(2 \lambda+7,4 \lambda+14,-\lambda+5)$ lie on the plane (i). Then,

$$
2(2 \lambda+7)+4(4 \lambda+14)-(-\lambda+5)=2 \Rightarrow 21 \lambda=-63 \Rightarrow \lambda=-3 .
$$

$\therefore$ the coordinates of the foot of the perpendicular $P Q$ are

$$
\begin{aligned}
Q[2 & \times(-3)+7,4 \times(-3)+14,-(-3)+5], \text { i.e., } Q(1,2,8) . \\
\therefore \quad P Q & =\sqrt{(7-1)^{2}+(14-2)^{2}+(5-8)^{2}} \\
& =\sqrt{6^{2}+(12)^{2}+(-3)^{2}}=\sqrt{36+144+9} \\
& =\sqrt{189}=3 \sqrt{21} \text { units. }
\endAs

Let $R(x, y, z)$ be the image of $P$ in the plane (i).
Then, $Q$ is the midpoint of $P R$.
$\therefore \quad \frac{7+x}{2}=1, \frac{14+y}{2}=2$ and $\frac{5+z}{2}=8 \Rightarrow x=-5, y=-10, z=11$.
Hence, the image of $P(7,14,5)$ in the given plane is $R(-5,-10,11)$.

---

### Example 21:

Find the image of the point ( $1,2,3$ ) in the plane $x+2 y+4 z=38$.

#### Solution:

The equation of the given plane is

$$
\begin{equation*}
x+2 y+4 z=38 . \tag{i}
\endE_SS_S

The d.r.'s of the normal to this plane are $1,2,4$.
The equation of the line passing through the point $P(1,2,3)$ and perpendicular to the given plane (i) is given by

$$
\frac{(x-1)}{1}=\frac{(y-2)}{2}=\frac{(z-3)}{4}=\lambda \text { (say). }
$$

A general point on this line is

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-093.jpg?height=352&width=298&top_left_y=1442&top_left_x=911)

$(\lambda+1,2 \lambda+2,4 \lambda+3)$.
For some value of $\lambda$, let the point $Q(\lambda+1,2 \lambda+2,4 \lambda+3)$ lie on the plane (i). Then,

$$
(\lambda+1)+2(2 \lambda+2)+4(4 \lambda+3)=38 \Rightarrow 21 \lambda=21 \Rightarrow \lambda=1 .
$$

$\therefore$ the coordinates of the foot of the perpendicular $P Q$ are

$$
Q(1+1,2+2,4+3) \text {, i.e., } Q(2,4,7) \text .
$$

Let $R(x, y, z)$ be the image of $P(1,2,3)$ in the given plane.
Then, $Q$ is the midpoint of $P R$.

$$
\therefore \quad \frac{1+x}{2}=2, \frac{2+y}{2}=4 \text { and } \frac{3+z}{2}=7 \Rightarrow x=3, y=6, z=11 .
$$

Hence, the image of $P(1,2,3)$ in the given plane is $R(3,6,11)$.

---