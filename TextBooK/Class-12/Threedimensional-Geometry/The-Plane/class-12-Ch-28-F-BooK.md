## Equation of a Plane Passing through Three Noncollinear Points

### Vector Form

**THEOREM 1**
The vector equation of a plane passing through three noncollinear points with position vectors $\vec{a}, \vec{b}, \vec{c}$ is

$$
(\vec{r}-\vec{a}) \cdot[(\vec{b}-\vec{a}) \times(\vec{c}-\vec{a})]=0
$$

**PROOF**
Let $A, B, C$ be three given noncollinear points having position vectors $\vec{a}, \vec{b}, \vec{c}$ respectively.
Let $P$ be an arbitrary point on the plane passing through the points $A, B, C$, and let $\vec{r}$ be the position vector of $P$. Then,

$$
\begin{aligned}
& \overrightarrow{A P}=(\text { p.v. of } P)-(\text { p.v. of } A)=(\vec{r}-\vec{a}), \\
& \overrightarrow{A B}=(\text { p.v. of } B)-(\text { p.v. of } A)=(\vec{b}-\vec{a}), \\
& \overrightarrow{A C}=(\text { p.v. of } C)-(\text { p.v. of } A)=(\vec{c}-\vec{a}),
\end{aligned}
$$

Since the points $A, B, C, P$ lie on the plane, the vectors $\overrightarrow{A P}, \overrightarrow{A B}, \overrightarrow{A C}$ are coplanar.
So, the scalar triple product of these vectors is 0.

$$
\begin{array}{ll}
\therefore & {[\overrightarrow{A P} \overrightarrow{A B} \overrightarrow{A C}]=0} \\
\Rightarrow & \overrightarrow{A P} \cdot(\overrightarrow{A B} \times \overrightarrow{A C})=0 \\
\Rightarrow & (\vec{r}-\vec{a}) \cdot[(\vec{b}-\vec{a}) \times(\vec{c}-\vec{a})]=0,
\end{array}
$$

which is the required equation of the plane.

### Cartesian Form

**THEOREM 2**
The equation of a plane passing through three given noncollinear points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0
$$

**PROOF**
Let $P(x, y, z)$ be an arbitrary point on the given plane. Then,

$$
\begin{aligned}
\overrightarrow{A P} & =(\text { p.v. of } P)-(\text { p.v. of } A) \\
& =(x \hat{i}+y \hat{j}+z \hat{k})-\left(x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}\right) \\
& =\left(x-x_{1}\right) \hat{i}+\left(y-y_{1}\right) \hat{j}+\left(z-z_{1}\right) \hat{k}
\end{aligned}
$$

Similarly, we have

$$
\overrightarrow{A B}=\left(x_{2}-x_{1}\right) \hat{i}+\left(y_{2}-y_{1}\right) \hat{j}+\left(z_{2}-z_{1}\right) \hat{k}
$$

and $\overrightarrow{A C}=\left(x_{3}-x_{1}\right) \hat{i}+\left(y_{3}-y_{1}\right) \hat{j}+\left(z_{3}-z_{1}\right) \hat{k}$.
Since $\overrightarrow{A P}, \overrightarrow{A B}$ and $\overrightarrow{A C}$ are coplanar, we have

$$
[\overrightarrow{A P}, \overrightarrow{A B}, \overrightarrow{A C}]=0
$$

Hence, the required equation of the plane passing through three given points $A, B, C$ is given by

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0.
$$

### Summary

(i) The vector equation of a plane passing through three noncollinear points having position vectors $\vec{a}, \vec{b}, \vec{c}$ is given by

$$
(\vec{r}-\vec{a}) \cdot[(\vec{b}-\vec{a}) \times(\vec{c}-\vec{a})]=0
$$

(ii) The Cartesian equation of a plane passing through three noncollinear points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0
$$

---

### Solved Examples

**EXAMPLE 1**
Find the vector equation of a plane passing through the points $A(2,5,-3), B(-2,-3,5)$ and $C(5,3,-3)$.

**SOLUTION**
The position vectors of the given points $A, B$, and $C$ are $\vec{a}=(2 \hat{i}+5 \hat{j}-3 \hat{k}), \vec{b}=(-2 \hat{i}-3 \hat{j}+5 \hat{k})$ and $\vec{c}=(5 \hat{i}+3 \hat{j}-3 \hat{k})$ respectively.
Then, the vector equation of the required plane is

$$
(\vec{r}-\vec{a}) \cdot[(\vec{b}-\vec{a}) \times(\vec{c}-\vec{a})]=0
$$

$\operatorname{Now}(\vec{b}-\vec{a})=(-2-2) \hat{i}+(-3-5) \hat{j}+(5+3) \hat{k}=(-4 \hat{i}-8 \hat{j}+8 \hat{k})$.
and $(\vec{c}-\vec{a})=(5-2) \hat{i}+(3-5) \hat{j}+(-3+3) \hat{k}=(3 \hat{i}-2 \hat{j}+0 \hat{k})$.

$$
\begin{aligned}
\therefore \quad(\vec{b}-\vec{a}) \times(\vec{c}-\vec{a}) & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
-4 & -8 & 8 \\
3 & -2 & 0
\end{array}\right| \\
& =(0+16) \hat{i}-(0-24) \hat{j}+(8+24) \hat{k} \\
& =(16 \hat{i}+24 \hat{j}+32 \hat{k}) .
\end{aligned}
$$

$\therefore$ the required vector equation is

$$
\begin{aligned}
(\vec{r}-\vec{a}) \cdot(16 \hat{i}+24 \hat{j}+ & 32 \hat{k})=0 \\
\Rightarrow \quad \vec{r} \cdot(16 \hat{i}+24 \hat{j}+32 \hat{k}) & =\vec{a} \cdot(16 \hat{i}+24 \hat{j}+32 \hat{k}) \\
& =(2 \hat{i}+5 \hat{j}-3 \hat{k}) \cdot(16 \hat{i}+24 \hat{j}+32 \hat{k}) \\
& =(32+120-96)=56 .
\end{aligned}
$$

Hence, the required vector equation of the plane is

$$
\vec{r} \cdot(16 \hat{i}+24 \hat{j}+32 \hat{k})=56 \Rightarrow \vec{r} \cdot(2 \hat{i}+3 \hat{j}+4 \hat{k})=7 .
$$

---

**EXAMPLE 2**
Find the equation of the plane passing through the points $A(1,1,0)$, $B(1,2,1)$ and $C(-2,2,-1)$.

**SOLUTION**
Here

$$
\left(x_{1}=1, y_{1}=1, z_{1}=0\right),\left(x_{2}=1, y_{2}=2, z_{2}=1\right)
$$

and ( $x_{3}=-2, y_{3}=2, z_{3}=-1$ ).
Hence, the required equation of the plane is

$$
\begin{aligned}
& \Rightarrow\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0 \\
& \Rightarrow\left|\begin{array}{ccc}
x-1 & y-1 & z-0 \\
1-1 & 2-1 & 1-0 \\
-2-1 & 2-1 & -1-0
\end{array}\right|=0 \\
& \Rightarrow\left|\begin{array}{ccc}
x-1 & y-1 & z \\
0 & 1 & 1 \\
-3 & 1 & -1
\end{array}\right|=0 \\
& \Rightarrow(x-1)(-1-1)-(y-1)(0+3)+z(0+3)=0 \\
& \Rightarrow(-2)(x-1)-3(y-1)+3 z=0 \\
& \Rightarrow-2 x-3 y+3 z+5=0 \Rightarrow 2 x+3 y-3 z-5=0
\end{aligned}
$$

Hence, the required equation of the plane is $2 x+3 y-3 z-5=0$.

---

## Angle Between Two Planes

The angle between two given planes is the angle between their normals.
If $\theta$ is an angle between two planes, then $\left(180^{\circ}-\theta\right)$ is also an angle between them.

**An Important Note:** We shall take the acute angle as the angle between two planes.

### Vector Form

Let $\theta$ be the angle between two planes whose vector equations are

$$
\vec{r} \cdot \overrightarrow{n_{1}}=q_{1} \text { and } \vec{r} \cdot \overrightarrow{n_{2}}=q_{2}
$$

Then, $\theta$ is the angle between their normals $\overrightarrow{n_{1}}$ and $\overrightarrow{n_{2}}$.

$$
\therefore \quad \cos \theta=\frac{\left|\overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}\right|}{\left|\overrightarrow{n_{1}}\right|\left|\overrightarrow{n_{2}}\right|}
$$

**Two Important Results**

1.  **Condition for two planes to be perpendicular to each other**
    Two planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ are perpendicular to each other

    $$
    \Leftrightarrow \overrightarrow{n_{1}} \perp \overrightarrow{n_{2}} \Leftrightarrow \overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}=0
    $$

2.  **Condition for two planes to be parallel to each other**
    Two planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ are parallel to each other

    $$
    \begin{aligned}
    & \Leftrightarrow \overrightarrow{n_{1}} \| \overrightarrow{n_{2}} \\
    & \Leftrightarrow \overrightarrow{n_{1}}=\lambda \overrightarrow{n_{2}} \text { for some scalar } \lambda .
    \end{aligned}
    $$

> **REMARK 1** Any plane parallel to $\vec{r} \cdot \vec{n}=q$ is $\vec{r} \cdot \vec{n}=q_{1}$.
> **REMARK 2** The equation of the plane parallel to the plane $\vec{r} \cdot \vec{n}=q$ and passing through the point with position vector $\vec{a}$ is $(\vec{r}-\vec{a}) \cdot \vec{n}=0$.

### Cartesian Form

Let $\theta$ be the acute angle between the planes:

$$
a_{1} x+b_{1} y+c_{1} z+d_{1}=0 \text { and } a_{2} x+b_{2} y+c_{2} z+d_{2}=0
$$

Then, $\theta$ is the angle between their normals.
D.r.'s of the normals to the given planes are
$a_{1}, b_{1}, c_{1}$ and $a_{2}, b_{2}, c_{2}$.
$\therefore \quad \cos \theta=\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left\{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right\}\left\{\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right\}}$.

**Two Important Results**

1.  **Condition for two planes to be perpendicular to each other**
    Two planes $a_{1} x+b_{1} y+c_{1} z+d_{1}=0$ and $a_{2} x+b_{2} y+c_{2} z+d_{2}=0$ are perpendicular to each other
    $\Leftrightarrow$ their normals are perpendicular to each other
    $\Leftrightarrow$ lines with direction ratios $a_{1}, b_{1}, c_{1}$, and $a_{2}, b_{2}, c_{2}$ are perpendicular to each other
    $\Leftrightarrow a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}=0$.

2.  **Condition for two planes to be parallel to each other**
    Two planes $a_{1} x+b_{1} y+c_{1} z+d_{1}=0$ and $a_{2} x+b_{2} y+c_{2} z+d_{2}=0$ are parallel to each other
    $\Leftrightarrow$ their normals are parallel to each other
    $\Leftrightarrow$ lines with direction ratios $a_{1}, b_{1}, c_{1}$, and $a_{2}, b_{2}, c_{2}$ are parallel to each other
    $\Leftrightarrow \frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.

> **REMARK 1** The equation of any plane parallel to the plane $a x+b y+c z+d=0$ is $a x+b y+c z+\lambda=0$.
> **REMARK 2** The equation of a plane passing through $\left(x_{1}, y_{1}, z_{1}\right)$ and parallel to the plane $a x+b y+c z+d=0$ is given by
> $$
> a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0.
> $$
> **REMARK 3** The equation of any plane parallel to the $x y$-plane is $z=\lambda$.
> This plane is perpendicular to the $z$-axis.
> The equation of any plane parallel to the $x z$-plane is $y=\lambda$.
> $x z$-plane is perpendiuclar to the $y$-axis.
> The equation of any plane parallel to the $y z$-plane is $x=\lambda$.
> $y z$-plane is perpendicular to the $x$-axis.

### Summary of the Results

1.  The acute angle $\theta$ between the planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ is given by

    $$
    \cos \theta=\frac{\left|\overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}\right|}{\left|\overrightarrow{n_{1}}\right|\left|\overrightarrow{n_{2}}\right|}
    $$

    (i) Two planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ are perpendicular to each other
    $$
    \Leftrightarrow \overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}=0 .
    $$
    (ii) Two planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ are perpendicular to each other $\Leftrightarrow \overrightarrow{n_{1}}=\lambda \overrightarrow{n_{2}}$ for some scalar $\lambda$.
    (iii) Any plane parallel to the plane $\vec{r} \cdot \vec{n}=q$ is $\vec{r} \cdot \vec{n}=q_{1}$.
    (iv) Any plane parallel to $\vec{r} \cdot \vec{n}=q$ and passing through a point with p.v. $\vec{a}$ is $(\vec{r}-\vec{a}) \cdot \vec{n}=0$.

2.  The acute angle $\theta$ between the planes

    $$
    a_{1} x+b_{1} y+c_{1} z+d_{1}=0 \text { and } a_{2} x+b_{2} y+c_{2} z+d_{2}=0
    $$

    is given by

    $$
    \cos \theta=\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left\{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right\}\left\{\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right\}}
    $$

    (i) Two planes $a_{1} x+b_{1} y+c_{1} z+d_{1}=0$ and $a_{2} x+b_{2} y+c_{2} z+d_{2}=0$ are perpendicular $\Leftrightarrow a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}=0$.
    (ii) Two planes $a_{1} x+b_{1} y+c_{1} z+d_{1}=0$ and $a_{2} x+b_{2} y+c_{2} z+d_{2}=0$ are parallel $\Leftrightarrow \frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.
    (iii) The equation of a plane parallel to the plane $a x+b y+c z+d=0$ is $a x+b y+c z+\lambda=0$.
    (iv) The equation of a plane passing through the point ( $x_{1}, y_{1}, z_{1}$ ) and parallel to the plane $a x+b y+c z+d=0$ is given by
    $$
    a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0 .
    $$
    (v) Any plane parallel to the $y z$-plane is $x=\lambda$.
    Any plane parallel to the $x z$-plane is $y=\lambda$.
    Any plane parallel to the $x y$-plane is $z=\lambda$.

---

### Solved Examples

**EXAMPLE 1**
Find the angle between the planes

$$
\vec{r} \cdot(\hat{i}+\hat{j}+2 \hat{k})=5 \text { and } \vec{r} \cdot(2 \hat{i}-\hat{j}+\hat{k})=8 .
$$

**SOLUTION**
We know that the angle between the planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ is given by

$$
\cos \theta=\frac{\left|\overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}\right|}{\left|\overrightarrow{n_{1}}\right|\left|\overrightarrow{n_{2}}\right|} .
$$

Here, $\overrightarrow{n_{1}}=(\hat{i}+\hat{j}+2 \hat{k})$ and $\overrightarrow{n_{2}}=(2 \hat{i}-\hat{j}+\hat{k})$.

$$
\begin{aligned}
\therefore \quad \cos \theta & =\frac{|(\hat{i}+\hat{j}+2 \hat{k}) \cdot(2 \hat{i}-\hat{j}+\hat{k})|}{|\hat{i}+\hat{j}+2 \hat{k}||2 \hat{i}-\hat{j}+\hat{k}|} \\
& =\frac{|1 \times 2+1 \times(-1)+2 \times 1|}{\left\{\sqrt{1^{2}+1^{2}+2^{2}}\right\}\left\{\sqrt{2^{2}+(-1)^{2}+1^{2}}\right\}}=\frac{3}{6}=\frac{1}{2} \\
\Rightarrow \quad \theta=\frac{\pi}{3} &
\end{aligned}
$$

Hence, the angle between the given planes is $\left(\frac{\pi}{3}\right)$.

---

**EXAMPLE 2**
Find the angle between the planes whose vector equations are

$$
\vec{r} \cdot(2 \hat{i}+2 \hat{j}-3 \hat{k})=5 \text { and } \vec{r} \cdot(3 \hat{i}-3 \hat{j}+5 \hat{k})=3 \text {. }
$$

**SOLUTION**
We know that the acute angle $\theta$ between the planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ is given by

$$
\cos \theta=\frac{\left|\overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}\right|}{\left|\overrightarrow{n_{1}}\right|\left|\overrightarrow{n_{2}}\right|}
$$

Here, $\overrightarrow{n_{1}}=(2 \hat{i}+2 \hat{j}-3 \hat{k})$ and $\overrightarrow{n_{2}}=(3 \hat{i}-3 \hat{j}+5 \hat{k})$.

$$
\begin{aligned}
\therefore \quad \cos \theta & =\frac{\mid 2 \hat{i}+2 \hat{j}-3 \hat{k}) \cdot(3 \hat{i}-3 \hat{j}+5 \hat{k}) \mid}{|2 \hat{i}+2 \hat{j}-3 \hat{k}||3 \hat{i}-3 \hat{j}+5 \hat{k}|} \\
& =\frac{|2 \times 3+2 \times(-3)+(-3) \times 5|}{\left\{\sqrt{2^{2}+2^{2}+(-3)^{2}}\right\}\left\{\sqrt{3^{2}+(-3)^{2}+5^{2}}\right\}} \\
& =\frac{|-15|}{(\sqrt{17})(\sqrt{43})}=\frac{15}{\sqrt{731}}
\end{aligned}
$$

$\Rightarrow \quad \theta=\cos ^{-1}\left(\frac{15}{\sqrt{731}}\right)$.
Hence, the angle between the given planes is $\cos ^{-1}\left(\frac{15}{\sqrt{731}}\right)$.

---

**EXAMPLE 3**
Find the value of $\lambda$ for which the planes

$$
\vec{r} \cdot(\hat{i}+2 \hat{j}+3 \hat{k})=13 \text { and } \vec{r} \cdot(\lambda \hat{i}+2 \hat{j}-7 \hat{k})=9
$$

are perpendicular to each other.

**SOLUTION**
We know that the planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ are perpendicular to each other only when $\overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}=0$.
Here, $\overrightarrow{n_{1}}=(\hat{i}+2 \hat{j}+3 \hat{k})$ and $\overrightarrow{n_{2}}=(\lambda \hat{i}+2 \hat{j}-7 \hat{k})$.
$\therefore \quad$ the given planes are perpendicular to each other
$\Leftrightarrow \overrightarrow{n_{1}} \cdot \overrightarrow{n_{2}}=0$
$\Leftrightarrow(\hat{i}+2 \hat{j}+3 \hat{k}) \cdot(\lambda \hat{i}+2 \hat{j}-7 \hat{k})=0$
$\Leftrightarrow 1 \times \lambda+2 \times 2+3 \times(-7)=0 \Leftrightarrow \lambda=17$.
Hence, the required value of $\lambda$ is 17 .

---

**EXAMPLE 4**
Find the angle between the planes whose Cartesian equations are $7 x+5 y+6 z+30=0$ and $3 x-y-10 z+4=0$.

**SOLUTION**
We know that the acute angle between the planes $a_{1} x+b_{1} y+c_{1} z+d_{1}=0$ and $a_{2} x+b_{2} y+c_{2} z+d_{2}=0$ is given by

$$
\cos \theta=\frac{\left|a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}\right|}{\left\{\sqrt{a_{1}^{2}+b_{1}^{2}+c_{1}^{2}}\right\}\left\{\sqrt{a_{2}^{2}+b_{2}^{2}+c_{2}^{2}}\right\}}
$$

Here $a_{1}=7, b_{1}=5, c_{1}=6$ and $a_{2}=3, b_{2}=-1 . c_{2}=-10$.

$$
\begin{aligned}
& \therefore \quad \cos \theta=\frac{|7 \times 3+5 \times(-1)+6(-10)|}{\left\{\sqrt{7^{2}+5^{2}=6^{2}}\right\}\left\{\sqrt{3^{2}+(-1)^{2}+(-10)^{2}}\right\}} \\
&=\frac{|21-5-60|}{\{\sqrt{49+25+36}\}\{\sqrt{9+1+100}\}} \\
&=\frac{44}{\{\sqrt{110} \times \sqrt{110}\}}=\frac{44}{110}=\frac{2}{5} \\
& \Rightarrow \quad \theta=\cos ^{-1}\left(\frac{2}{5}\right)
\end{aligned}
$$

Hence, the acute angle between the given planes is $\cos ^{-1}\left(\frac{2}{5}\right)$.

---

**EXAMPLE 5**
Find the value of $\lambda$ for which the planes $2 x-4 y+3 z=7$ and $x+2 y+\lambda z=18$ are perpendicular to each other.

**SOLUTION**
The equations of the given planes are

$$
2 x-4 y+3 z-7=0 \text { and } x+2 y+\lambda z-18=0
$$

They are of the form

$$
a_{1} x+b_{1} y+c_{1} z+d_{1}=0 \text { and } a_{2} x+b_{2} y+c_{2} z+d_{2}=0
$$

where $a_{1}=2, b_{1}=-4, c_{1}=3, d_{1}=-7$, and

$$
a_{2}=1, b_{2}=2, c_{2}=\lambda, d_{2}=-18 .
$$

The given planes are perpendicular to each other

$$
\begin{aligned}
& \Leftrightarrow \quad a_{1} a_{2}+b_{1} b_{2}+c_{1} c_{2}=0 \\
& \Leftrightarrow \quad 2 \times 1+(-4) \times 2+3 \times \lambda=0 \\
& \Leftrightarrow \quad 3 \lambda=6 \Leftrightarrow \lambda=2
\end{aligned}
$$

Hence, the required value of $\lambda$ is 2 .

---

**EXAMPLE 6**
Find the equation of the plane passing through the point $(-1,3,2)$ and perpendicular to each of the planes $x+2 y+3 z=5$ and $3 x+3 y+z=0$.
[CBSE 2009, '11]

**SOLUTION**
Any plane passing through the point ( $-1,3,2$ ) is given by

$$
\begin{equation*}
a(x+1)+b(y-3)+c(z-2)=0 . \tag{i}
\end{equation*}
$$

Now, (i) being perpendicular to each of the planes

$$
x+2 y+3 z-5=0 \text { and } 3 x+3 y+z=0
$$

we have,

$$
\begin{align*}
& (a \times 1)+(b \times 2)+(c \times 3)=0 \Rightarrow a+2 b+3 c=0  \tag{ii}\\
& (a \times 3)+(b \times 3)+(c \times 1)=0 \Rightarrow 3 a+3 b+c=0 . \tag{iii}
\end{align*}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
& \frac{a}{(2-9)}=\frac{b}{(9-1)}=\frac{c}{(3-6)} \\
\Rightarrow & \frac{a}{-7}=\frac{b}{8}=\frac{c}{-3} \Rightarrow \frac{a}{7}=\frac{b}{-8}=\frac{c}{3}=\lambda \text { (say) } \\
\Rightarrow & a=7 \lambda, b=-8 \lambda \text { and } c=3 \lambda
\end{aligned}
$$

Putting $a=7 \lambda, b=-8 \lambda$ and $c=3 \lambda$ in (i), we get

$$
\begin{aligned}
& 7 \lambda(x+1)-8 \lambda(y-3)+3 \lambda(z-2)=0 \\
\Rightarrow & 7(x+1)-8(y-3)+3(z-2)=0 \\
\Rightarrow & 7 x-8 y+3 z+25=0
\end{aligned}
$$

which is the required equation of the plane.

---

**EXAMPLE 7**
Find the vector equation of the plane through the points $(2,1,-1)$ and ( $-1,3,4$ ) and perpendicular to the plane $x-2 y+4 z=10$.
[CBSE 2013]

The general equation of a plane passing through the point $A(2,1,-1)$ is given by

$$
\begin{equation*}
a(x-2)+b(y-1)+c(z+1)=0 \tag{i}
\end{equation*}
$$

If the point $B(-1,3,4)$ lies on plane (i), then we have

$$
\begin{align*}
& a(-1-2)+b(3-1)+c(4+1)=0 \\
\Rightarrow \quad & -3 a+2 b+5 c=0 \tag{ii}
\end{align*}
$$

If the plane (i) is perpendicular to the plane $x-2 y+4 z=10$, then we have

$$
\begin{align*}
& (1 \times a)-(2 \times b)+(4 \times c)=0 \\
\Rightarrow \quad & a-2 b+4 c=0 \tag{iii}
\end{align*}
$$

On solving (ii) and (iii) by cross multiplication, we have

$$
\begin{aligned}
& \frac{a}{(8+10)}=\frac{b}{(5+12)}=\frac{c}{(6-2)} \\
\Rightarrow & \frac{a}{18}=\frac{b}{17}=\frac{c}{4}=\lambda(\text { say }) \\
\Rightarrow & a=18 \lambda, b=17 \lambda \text { and } c=4 \lambda
\end{aligned}
$$

Substituting these values of $a, b$ and $c$ in (i), we get

$$
\begin{aligned}
& 18 \lambda(x-2)+17 \lambda(y-1)+4 \lambda(z+1)=0 \\
\Rightarrow & 18(x-2)+17(y-1)+4(z+1)=0 \\
\Rightarrow & 18 x+17 y+4 z=49
\end{aligned}
$$

Required equation of the plane in vector form is given by

$$
\vec{r} \cdot(18 \hat{i}+17 \hat{j}+4 \hat{k})=49 .
$$

---

**EXAMPLE 8**
Find the equation of the plane passing through the point $(1,3,2)$ and parallel to the plane $3 x-2 y+2 z+33=0$.

**SOLUTION**
The equation of a plane parallel to the given plane is of the form

$$
\begin{equation*}
3 x-2 y+2 z=k \text { for some scalar } k \tag{i}
\end{equation*}
$$

Since it passes through the point $A(1,3,2)$, we have

$$
(3 \times 1)-(2 \times 3)+(2 \times 2)=k \Rightarrow k=(3-6+4)=1 .
$$

Hence, the required equation of the plane is

$$
3 x-2 y+2 z-1=0
$$