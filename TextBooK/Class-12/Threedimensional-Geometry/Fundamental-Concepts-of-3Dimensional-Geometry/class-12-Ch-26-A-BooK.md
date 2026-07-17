## 26. Fundamental Concepts of 3-Dimensional Geometry

This chapter consists of some important concepts of three-dimensional geometry. Though we have studied these in Class 11, yet we shall review here these fundamental concepts for ready reference.

### Coordinates of a Point in Space

Let $O$ be the origin, and let $O X, O Y$ and $O Z$ be three mutually perpendicular lines, taken as the $x$-axis, $y$-axis and $z$-axis respectively in such a way that they form a right-handed system.

The planes $YOZ$, $ZOX$ and $XOY$ are respectively known as the **yz-plane**, the **zx-plane** and the **xy-plane**.

These planes, known as the **coordinate planes**, divide the space into eight parts called **octants**.

Let $P$ be a point in space. Through $P$, draw three planes $PLAN$, $PNBM$ and $PLCM$ parallel to the $y z$-plane, the $z x$-plane and the $x y$-plane respectively, and meeting the $x$-axis, $y$-axis and $z$-axis at the points $A, B, C$ respectively. Complete the parallelepiped whose coterminous edges are $O A, O B$ and $O C$.

Let $O A=x, O B=y$ and $O C=z$. We say that the coordinates of $P$ are $(x, y, z)$.

It is clear from the figure alongside that:
- $x=$ distance of $P$ from the $y z$-plane
- $y=$ distance of $P$ from the $z x$-plane
- $z=$ distance of $P$ from the $x y$-plane.

Also, we can say that:
- The equation of the **xy-plane** is $z=0$.
- The equation of the **xz-plane** is $y=0$.
![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-001.jpg?height=356&width=455&top_left_y=998&top_left_x=758)
- The equation of the **yz-plane** is $x=0$.
![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-001.jpg?height=362&width=459&top_left_y=1377&top_left_x=750)

#### Position Vector of a Point in Space

Let $\hat{i}, \hat{j}, \hat{k}$ be unit vectors along $O X, O Y$ and $O Z$ respectively.

If $P(a, b, c)$ is a point in space, we say that the **position vector** (or, p.v.) of $P$ is $(a \hat{i}+b \hat{j}+c \hat{k})$.

### Some Results on Points in Space

#### 1. Distance Between Two Points

The distance between two points $P\left(x_{1}, y_{1}, z_{1}\right)$ and $Q\left(x_{2}, y_{2}, z_{2}\right)$ is given by $P Q=\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}+\left(z_{2}-z_{1}\right)^{2}}$.

#### 2. Section Formulae

- (i) If $P(x, y, z)$ divides the join of $A\left(x_{1}, y_{1}, z_{1}\right)$ and $B\left(x_{2}, y_{2}, z_{2}\right)$ in the ratio $m: n$ then
  $$
  x=\frac{\left(m x_{2}+n x_{1}\right)}{(m+n)}, y=\frac{\left(m y_{2}+n y_{1}\right)}{(m+n)}, z=\frac{\left(m z_{2}+n z_{1}\right)}{(m+n)} .
  $$

- (ii) The **mid-point** of the line joining $A\left(x_{1}, y_{1}, z_{1}\right)$ and $B\left(x_{2}, y_{2}, z_{2}\right)$ is given by
  $$
  M\left(\frac{x_{1}+x_{2}}{2}, \frac{y_{1}+y_{2}}{2}, \frac{z_{1}+z_{2}}{2}\right) .
  $$

- (iii) The **centroid** of $\triangle A B C$ with vertices $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by
  $$
  G\left(\frac{x_{1}+x_{2}+x_{3}}{3}, \frac{y_{1}+y_{2}+y_{3}}{3}, \frac{z_{1}+z_{2}+z_{3}}{3}\right) .
  $$

### Some Results on Lines in Space

#### 1. Direction Cosines of a Line

If a line makes angles $\alpha, \beta, \gamma$ with the $x$-axis, $y$-axis and $z$-axis respectively then
$$
l=\cos \alpha, m=\cos \beta, n=\cos \gamma
$$
are called the **direction cosines** (or, **d.c.'s**) of the line.

We always have $l^{2}+m^{2}+n^{2}=1$.

**Remarks:**
- (i) d.c.'s of the **x-axis** are $1,0,0$.
- (ii) d.c.'s of the **y-axis** are $0,1,0$.
- (iii) d.c.'s of the **z-axis** are $0,0,1$.

#### 2. Direction Ratios of a Line

Any three numbers $a, b, c$, proportional to the direction cosines $l, m, n$ respectively of a line, are called the **direction ratios** of the line.

Clearly, we have $\frac{l}{a}=\frac{m}{b}=\frac{n}{c}$.

### Some Important Facts

- (i) If $a, b, c$ are the **direction ratios** of a line then its **direction cosines** are
  $$
  l=\frac{a}{\sqrt{a^{2}+b^{2}+c^{2}}}, m=\frac{b}{\sqrt{a^{2}+b^{2}+c^{2}}}, n=\frac{c}{\sqrt{a^{2}+b^{2}+c^{2}}} .
  $$

- (ii) If $\vec{r}=a \hat{i}+b \hat{j}+c \hat{k}$ then the direction ratios of $\vec{r}$ are $a, b, c$.

- (iii) Let $P Q$ be a line joining $P\left(x_{1}, y_{1}, z_{1}\right)$ and $Q\left(x_{2}, y_{2}, z_{2}\right)$. Then, the direction ratios of the line $P Q$ are $\left(x_{2}-x_{1}\right),\left(y_{2}-y_{1}\right),\left(z_{2}-z_{1}\right)$.

#### 3. Angle Between Two Lines

If $\theta$ is the angle between two lines $L_{1}$ and $L_{2}$ whose d.c.'s are $l_{1}, m_{1}, n_{1}$, and $l_{2}, m_{2}, n_{2}$ then the following hold true.
- (i) $\cos \theta=l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}$
- (ii) $\sin \theta=\sqrt{\Sigma\left(m_{1} n_{2}-m_{2} n_{1}\right)^{2}}$
- (iii) Lines $L_{1}$ and $L_{2}$ are **perpendicular** $\Leftrightarrow l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}=0$
- (iv) Lines $L_{1}$ and $L_{2}$ are **parallel** $\Leftrightarrow \frac{l_{1}}{l_{2}}=\frac{m_{1}}{m_{2}}=\frac{n_{1}}{n_{2}}$.

**Remarks:**
In fact, there are two angles $\theta$ and $(\pi-\theta)$ between two lines.

---

## Solved Examples

### Example 1:

Find the direction cosines of a line whose direction ratios are $2,-6,3$.

#### Solution:

Here, $a=2, b=-6, c=3$.
$$
\begin{aligned}
\therefore \quad \sqrt{a^{2}+b^{2}+c^{2}} & =\sqrt{2^{2}+(-6)^{2}+3^{2}} \\
& =\sqrt{4+36+9}=\sqrt{49}=7 .
\end{aligned}
$$
Hence, the direction cosines of the given line are $\frac{2}{7}, \frac{-6}{7}, \frac{3}{7}$.

---

### Example 2:

Find the direction cosines of each of the following vectors:
- (i) $2 \hat{i}+\hat{j}-2 \hat{k}$
- (ii) $-\hat{i}-\hat{k}$
- (iii) $-\hat{j}$

#### Solution:

(i) Direction ratios of the vector $(2 \hat{i}+\hat{j}-2 \hat{k})$ are $2,1,-2$.

And, $\sqrt{2^{2}+1^{2}+(-2)^{2}}=\sqrt{4+1+4}=\sqrt{9}=3$.
$\therefore \quad$ d.c.'s of the given vector are $\frac{2}{3}, \frac{1}{3}, \frac{-2}{3}$.

(ii) Direction ratios of the vector $(-\hat{i}-\hat{k})$ are $-1,0,-1$.

And, $\sqrt{(-1)^{2}+0^{2}+(-1)^{2}}=\sqrt{1+0+1}=\sqrt{2}$.
$\therefore \quad$ d.c.'s of the given vector are $\frac{-1}{\sqrt{2}}, 0, \frac{-1}{\sqrt{2}}$.

(iii) Direction ratios of the vector $-\hat{j}$ are $0,-1,0$.

And, $\sqrt{0^{2}+(-1)^{2}+0^{2}}=\sqrt{1}=1$.
$\therefore$ d.c.'s of the given vector are $0,-1,0$.

---

### Example 3:

Find the direction cosines of a line which makes angles $90^{\circ}, 135^{\circ}$ and $45^{\circ}$ with the positive directions of the $x$-, $y$-, and $z$-axis respectively.

#### Solution:

The direction cosines of the given line are
$$
\cos 90^{\circ}, \cos 135^{\circ}, \cos 45^{\circ} \text {, i.e., } 0, \frac{-1}{\sqrt{2}}, \frac{1}{\sqrt{2}} .
$$

---

### Example 4:

If a line makes angles $\alpha, \beta$ and $\gamma$ with the coordinate axes, prove that
$$
\left(\sin ^{2} \alpha+\sin ^{2} \beta+\sin ^{2} \gamma\right)=2 .
$$

#### Solution:

Let the direction cosines of the given line be $l, m, n$. Then,
$$
\begin{aligned}
\quad l=\cos \alpha, m=\cos \beta & \text { and } n=\cos \gamma . \\
\therefore \quad\left(l^{2}+m^{2}+n^{2}\right)=1 & \Rightarrow \cos ^{2} \alpha+\cos ^{2} \beta+\cos ^{2} \gamma=1 \\
& \Rightarrow\left(1-\sin ^{2} \alpha\right)+\left(1-\sin ^{2} \beta\right)+\left(1-\sin ^{2} \gamma\right)=1 \\
& \Rightarrow \sin ^{2} \alpha+\sin ^{2} \beta+\sin ^{2} \gamma=2 .
\end{aligned}
$$
Hence, $\left(\sin ^{2} \alpha+\sin ^{2} \beta+\sin ^{2} \gamma\right)=2$.

---

### Example 5:

If a line makes angles $\alpha, \beta$ and $\gamma$ with the coordinate axes, prove that $(\cos 2 \alpha+\cos 2 \beta+\cos 2 \gamma)=-1$.

#### Solution:

Let the direction cosines of the given line be $l, m, n$. Then,
$$
\begin{aligned}
\quad l=\cos \alpha, m=\cos \beta \text { and } n=\cos \gamma & \\
\therefore \quad\left(l^{2}+m^{2}+n^{2}\right)=1 & \Rightarrow \cos ^{2} \alpha+\cos ^{2} \beta+\cos ^{2} \gamma=1 \\
& \Rightarrow 2 \cos ^{2} \alpha+2 \cos ^{2} \beta+2 \cos ^{2} \gamma=2 \\
& \Rightarrow(1+\cos 2 \alpha)+(1+\cos 2 \beta)+(1+\cos 2 \gamma)=2 \\
& \Rightarrow(\cos 2 \alpha+\cos 2 \beta+\cos 2 \gamma)=-1 .
\end{aligned}
$$
Hence, $(\cos 2 \alpha+\cos 2 \beta+\cos 2 \gamma)=-1$.

---

### Example 6:

Find the direction cosines of a line that makes equal angles with the coordinate axes. [CBSE 2011]

#### Solution:

Let the given line make angle $\alpha$ with each of the coordinate axes and let the direction cosines of this line be $l, m, n$. Then,
$$
\begin{aligned}
\quad l=m=n=\cos \alpha & . \\
\therefore \quad\left(l^{2}+m^{2}+n^{2}\right)=1 & \Rightarrow \cos ^{2} \alpha+\cos ^{2} \alpha+\cos ^{2} \alpha=1 \\
& \Rightarrow 3 \cos ^{2} \alpha=1 \Rightarrow \cos ^{2}=\frac{1}{3} \\
& \Rightarrow \cos \alpha= \pm \frac{1}{\sqrt{3}} .
\end{aligned}
$$
Hence, the d.c.'s of the given line are
$$
\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}} \text { or } \frac{-1}{\sqrt{3}}, \frac{-1}{\sqrt{3}}, \frac{-1}{\sqrt{3}} .
$$

---

### Example 7:

A line makes angle $60^{\circ}$ and $45^{\circ}$ with the positive direction of $x$-axis and $y$-axis respectively. What acute angle does it make with the z-axis?

#### Solution:

Let the given line make an angle $\gamma$ with the $z$-axis. Then,
$$
\begin{aligned}
& \cos ^{2} 60^{\circ}+\cos ^{2} 45^{\circ}+\cos ^{2} \gamma=1 \\
\Rightarrow & \left(\frac{1}{2}\right)^{2}+\left(\frac{1}{\sqrt{2}}\right)^{2}+\cos ^{2} \gamma=1 \\
\Rightarrow & \left(\frac{1}{4}+\frac{1}{2}\right)+\cos ^{2} \gamma=1 \Rightarrow \cos ^{2} \gamma=\left(1-\frac{3}{4}\right)=\frac{1}{4} \\
\Rightarrow & \cos \gamma= \pm \frac{1}{2} \\
\Rightarrow & \gamma=60^{\circ} \text { or } 120^{\circ}
\end{aligned}
$$
Hence, the acute angle which the given line makes with the $z$-axis is $60^{\circ}$.

---

### Example 8:

Find the direction cosines of the vector $\vec{r}=(6 \hat{i}+2 \hat{j}-3 \hat{k})$.

#### Solution:

The direction ratios of $\vec{r}$ are $6,2,-3$.

And, $\sqrt{6^{2}+2^{2}+(-3)^{2}}=\sqrt{36+4+9}=\sqrt{49}=7$.

Hence, the direction cosines of $\vec{r}$ are $\frac{6}{7}, \frac{2}{7}, \frac{-3}{7}$.

---

### Example 9:

Find the direction cosines of the line segment joining the points $A(7,-5,9)$ and $B(5,-3,8)$.

#### Solution:

D.r.'s of $A B$ are $(5-7)$, $(-3+5)$, $(8-9)$, i.e., $-2,2,-1$.

$|A B|=\sqrt{(-2)^{2}+2^{2}+(-1)^{2}}=\sqrt{4+4+1}=\sqrt{9}=3$.

Hence, the d.c.'s of the line $A B$ are $\frac{-2}{3}, \frac{2}{3}, \frac{-1}{3}$.

---

### Example 10:

Find the angles made by the vector $\vec{r}=(\hat{i}+\hat{j}-\hat{k})$ with the coordinate axes.

#### Solution:

D.r.'s of the given vector $\vec{r}$ are $1,1,-1$.
$$
\begin{aligned}
& |\vec{r}|=\sqrt{1^{2}+1^{2}+(-1)^{2}}=\sqrt{3} . \\
\therefore \quad & \text { d.c.'s of } \vec{r} \text { are } \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{-1}{\sqrt{3}} .
\end{aligned}
$$
Let $\vec{r}$ make angles $\alpha, \beta$ and $\gamma$ with the $x$-axis, $y$-axis and $z$-axis respectively. Then, d.c.'s of the $x$-axis are $1,0,0$.
$$
\begin{aligned}
\therefore \quad \cos \alpha &=\left\{\left(\frac{1}{\sqrt{3}} \times 1\right)+\left(\frac{1}{\sqrt{3}} \times 0\right)+\left(\frac{1}{\sqrt{3}} \times 0\right)\right\}=\frac{1}{\sqrt{3}} \\
\Rightarrow \quad \alpha &=\cos ^{-1}\left(\frac{1}{\sqrt{3}}\right).
\end{aligned}
$$
Similarly, $\cos \beta=\frac{1}{\sqrt{3}} \Rightarrow \beta=\cos ^{-1}\left(\frac{1}{\sqrt{3}}\right)$.

And, $\cos \gamma=\frac{-1}{\sqrt{3}} \Rightarrow \gamma=\cos ^{-1}\left(\frac{-1}{\sqrt{3}}\right)$.

Hence, the angles made by the given vector $\vec{r}$ with the $x$-axis, $y$-axis and $z$-axis are $\cos ^{-1}\left(\frac{1}{\sqrt{3}}\right), \cos ^{-1}\left(\frac{1}{\sqrt{3}}\right)$ and $\cos ^{-1}\left(\frac{-1}{\sqrt{3}}\right)$ respectively.

---

### Example 11:

Find the angle between the lines whose direction ratios are $3,2,-6$ and $1,2,2$.

#### Solution:

Let the given lines be $L_{1}$ and $L_{2}$ respectively. Then,
D.r.'s of $L_{1}$ are $3,2,-6$.

And, $\sqrt{3^{2}+2^{2}+(-6)^{2}}=\sqrt{9+4+36}=\sqrt{49}=7$.
$\therefore \quad$ d.c.'s of $L_{1}$ are $\frac{3}{7}, \frac{2}{7}, \frac{-6}{7}$.

D.r.'s of $L_{2}$ are $1,2,2$.

And, $\sqrt{1^{2}+2^{2}+2^{2}}=\sqrt{9}=3$.
$\therefore \quad$ d.c.'s of $L_{2}$ are $\frac{1}{3}, \frac{2}{3}, \frac{2}{3}$.

Let $\theta$ be the angle between $L_{1}$ and $L_{2}$. Then,
$$
\begin{aligned}
\cos \theta & =\left|l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}\right| \\
& =\left|\left(\frac{3}{7} \times \frac{1}{3}\right)+\left(\frac{2}{7} \times \frac{2}{3}\right)+\left(\frac{-6}{7} \times \frac{2}{3}\right)\right| \\
& =\left|\frac{1}{7}+\frac{4}{21}-\frac{4}{7}\right|=\left|\frac{-5}{21}\right|=\frac{5}{21} . \\
\therefore \quad \theta & =\cos ^{-1}\left(\frac{5}{21}\right) .
\end{aligned}
$$

---

### Example 12:

Find the angle between the vector $\vec{r}_{1}=(4 \hat{i}-3 \hat{j}+5 \hat{k})$ and $\vec{r}_{2}=(3 \hat{i}+4 \hat{j}+5 \hat{k})$.

#### Solution:

Let $\theta$ be the angle between $\vec{r}_{1}$ and $\vec{r}_{2}$. Then,
$$
\cos \theta=\frac{\vec{r}_{1} \cdot \vec{r}_{2}}{\left|\vec{r}_{1}\right|\left|\vec{r}_{2}\right|}=\frac{(4 \hat{i}-3 \hat{j}+5 \hat{k}) \cdot(3 \hat{i}+4 \hat{j}+5 \hat{k})}{\left\{\sqrt{4^{2}+(-3)^{2}+5^{2}}\right\}\left\{\sqrt{3^{2}+4^{2}+5^{2}}\right\}}
$$
$$
\begin{aligned}
& =\frac{(12-12+25)}{\{\sqrt{16+9+25}\}\{\sqrt{9+16+25}\}}=\frac{25}{\{\sqrt{50} \times \sqrt{50}\}}=\frac{25}{50}=\frac{1}{2} . \\
\therefore \quad \theta & =\cos ^{-1}\left(\frac{1}{2}\right)=\frac{\pi}{3} .
\end{aligned}
$$
Hence, the angle between the given vectors is $\frac{\pi}{3}$.

---

### Example 13:

Find the direction cosines of the line which is perpendicular to each of the lines having direction ratios 1, - 2, - 2 and 0, 2, 1 respectively.

#### Solution:

Let the direction ratios of the required line be $a, b, c$. Then, it being perpendicular to each of the lines having d.r.'s $1,-2,-2$ and $0,2,1$ we have
$$
\begin{align*}
& a-2 b-2 c=0  \tag{i}\\
& 0 a+2 b+c=0 . \tag{ii}
\end{align*}
$$
On solving (i) and (ii) by cross multiplication, we have
$$
\frac{a}{(-2+4)}=\frac{b}{(0-1)}=\frac{c}{(2-0)} \Rightarrow \frac{a}{2}=\frac{b}{-1}=\frac{c}{2} .
$$
$\therefore \quad$ d.r.'s of the required line are $2,-1,2$.

And, $\sqrt{2^{2}+(-1)^{2}+2^{2}}=\sqrt{9}=3$.

$\therefore \quad$ d.c.'s of the required line are $\frac{2}{3}, \frac{-1}{3}, \frac{2}{3}$.

---

### Example 14:

If $A(8,2,0), B(4,6,-7), C(-3,1,2)$ and $D(-9,-2,4)$ are four given point then find the angle between $\overrightarrow{A B}$ and $\overrightarrow{C D}$.

#### Solution:

D.r.'s of $\overrightarrow{A B}$ are $(4-8)$, $(6-2)$, $(-7-0)$, i.e., $-4,4,-7$.

$|\overrightarrow{A B}|=\sqrt{(-4)^{2}+4^{2}+(-7)^{2}}=\sqrt{16+16+49}=\sqrt{81}=9$.
$\therefore \quad$ d.c.'s of $\overrightarrow{A B}$ are $\frac{-4}{9}, \frac{4}{9}, \frac{-7}{9}$.

D.r.'s of $\overrightarrow{C D}$ are $(-9+3),(-2-1),(4-2)$, i.e., $-6,-3,2$.

$|\overrightarrow{C D}|=\sqrt{(-6)^{2}+(-3)^{2}+2^{2}}=\sqrt{36+9+4}=\sqrt{49}=7$.
$\therefore \quad$ d.c.'s of $\overrightarrow{C D}$ are $\frac{-6}{7}, \frac{-3}{7}, \frac{2}{7}$.

Let $\theta$ be the acute angle between $\overrightarrow{A B}$ and $\overrightarrow{C D}$. Then,
$$
\cos \theta=\left|\left(\frac{-4}{9}\right) \times\left(\frac{-6}{7}\right)+\left(\frac{4}{9}\right) \times\left(\frac{-3}{7}\right)+\left(\frac{-7}{9}\right) \times\left(\frac{2}{7}\right)\right|
$$
$$
=\left|\frac{24}{63}-\frac{12}{63}-\frac{14}{63}\right|=\left|\frac{-2}{63}\right|=\frac{2}{63} .
$$
$\therefore \quad \theta=\cos ^{-1}\left(\frac{2}{63}\right)$.

Hence, the required angle between $\overrightarrow{A B}$ and $\overrightarrow{C D}$ is $\cos ^{-1}\left(\frac{2}{63}\right)$.

---

### Example 15:

Find the angles of $\triangle A B C$ whose vertices are $A(-1,3,2), B(2,3,5)$ and $C(3,5,-2)$.

#### Solution:

D.r.'s of $A B$ are $(2+1)$, $(3-3)$, $(5-2)$, i.e. $3,0,3$.

D.r.'s of $A C$ are $(3+1),(5-3),(-2-2)$, i.e., $4,2,-4$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-008.jpg?height=247&width=306&top_left_y=518&top_left_x=899)

$$
\therefore \quad \cos A=\frac{\{3 \times 4+0 \times 2+3 \times(-4)\}}{\left\{\sqrt{3^{2}+0^{2}+3^{2}}\right\} \cdot\left\{\sqrt{4^{2}+2^{2}+(-4)^{2}}\right\}}=0 .
$$
$\therefore \quad \angle A=\frac{\pi}{2}$.

D.r.'s of $B A$ are $(-1-2),(3-3)$, $(2-5)$, i.e., $-3,0,-3$.

D.r.'s of $B C$ are $(3-2),(5-3),(-2-5)$, i.e., $1,2,-7$.
$$
\therefore \quad \cos B=\frac{\{(-3) \times 1+0 \times 2+(-3) \times(-7)\}}{\left\{\sqrt{(-3)^{2}+0^{2}+(-3)^{2}}\right\} \cdot\left\{\sqrt{1^{2}+2^{2}+(-7)^{2}}\right\}}
$$
$$
=\frac{18}{\sqrt{18} \times \sqrt{54}}=\frac{1}{\sqrt{3}} .
$$
$\therefore \quad \angle B=\cos ^{-1}\left(\frac{1}{\sqrt{3}}\right)$.

D.r.'s of $C B$ are $(2-3)$, $(3-5)$, $(5+2)$, i.e., $-1,-2,7$.

D.r.'s of $C A$ are $(-1-3)$, $(3-5)$, $(2+2)$, i.e., $-4,-2,4$.
$$
\therefore \quad \cos C=\frac{\{(-1) \times(-4)+(-2) \times(-2)+7 \times 4\}}{\left\{\sqrt{(-1)^{2}+(-2)^{2}+7^{2}}\right\} \cdot\left\{\sqrt{(-4)^{2}+(-2)^{2}+4^{2}}\right\}}
$$
$$
=\frac{36}{\sqrt{54} \times \sqrt{36}}=\frac{\sqrt{36}}{\sqrt{54}}=\sqrt{\frac{36}{54}}=\sqrt{\frac{2}{3}} .
$$
$\therefore \quad C=\cos ^{-1}\left(\sqrt{\frac{2}{5}}\right)$.

Hence, $\angle A=\frac{\pi}{2}, \angle B=\cos ^{-1}\left(\frac{1}{\sqrt{3}}\right)$ and $\angle C=\cos ^{-1}\left(\sqrt{\frac{2}{3}}\right)$.

---

### Example 16:

Show that the points $A(2,3,-4), B(1,-2,3)$ and $C(3,8,-11)$ are collinear.

#### Solution:

D.r.'s of the line $A B$ are $(1-2)$, $(-2-3)$, $(3+4)$, i.e., $-1,-5,7$.

D.r.'s of the $A C$ are $(3-2),(8-3),(-11+4)$, i.e., $1,5,-7$, i.e., $-1,-5,7$.

$\therefore$ d.r.'s of $A B$ and $A C$ are the same and so they are parallel.

But, the lines $A B$ and $A C$ have a common point $A$.

Hence, the points $A, B$ and $C$ are collinear.

---

### Example 17:

Find the coordinates of the foot of the perpendicular drawn from the point $A(1,2,1)$ to the line joining $B(1,4,6)$ and $C(5,4,4)$.

#### Solution:

Draw $A N \perp B C$.

Let $N$ divide $B C$ in the ratio $k: 1$.

Then, the coordinates of $N$ are
$$
\left(\frac{5 k+1}{k+1}, \frac{4 k+4}{k+1}, \frac{4 k+6}{k+1}\right) .
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-009.jpg?height=235&width=506&top_left_y=856&top_left_x=408)

$\therefore \quad$ d.r.'s of $A N$ are
$$
\left(\frac{5 k+1}{k+1}-1, \frac{4 k+4}{k+1}-2, \frac{4 k+6}{k+1}-1\right), \text { i.e., }\left(\frac{4 k}{k+1}, \frac{2 k+2}{k+1}, \frac{3 k+5}{k+1}\right)
$$
And, the d.r.'s of $B C$ are $(5-1)$, $(4-4)$, $(4-6)$, i.e., $4,0,-2$.

Since $A N \perp B C$, we have
$$
\begin{array}{r}
\left(4 \times \frac{4 k}{k+1}\right)+\left(0 \times \frac{2 k+2}{k+1}\right)-\left(2 \times \frac{3 k+5}{k+1}\right)=0 \\
\Rightarrow \quad 16 k+0-6 k-10=0 \Rightarrow 10 k=10 \Rightarrow k=1 .
\end{array}
$$
Putting $k=1$, we get the coordinates of $N$ as $N(3,4,5)$.

---

### Example 18:

If $l_{1}, m_{1}, n_{1}$ and $l_{2}, m_{2}, n_{2}$ be the direction ratios of two lines then show that the direction ratios of a line which is perpendicular to each of the given lines are: $\left(m_{1} n_{2}-m_{2} n_{1}\right),\left(n_{1} l_{2}-n_{2} l_{1}\right),\left(l_{1} m_{2}-l_{2} m_{1}\right)$.

#### Solution:

Let $a, b, c$ be the direction ratios of the required line.

Then, this line being perpendicular to each of the given two lines, we have:
$$
\begin{align*}
& l_{1} a+m_{1} b+n_{1} c=0  \tag{i}\\
& l_{2} a+m_{2} b+n_{2} c=0 . \tag{ii}
\end{align*}
$$
On solving (i) and (ii) for $a, b, c$ by cross multiplication, we have
$$
\frac{a}{\left(m_{1} n_{2}-m_{2} n_{1}\right)}=\frac{b}{\left(n_{1} l_{2}-n_{2} l_{1}\right)}=\frac{c}{\left(l_{1} m_{2}-l_{2} m_{1}\right)} .
$$
Hence, the d.r.'s. of the required line are
$$
\left(m_{1} n_{2}-m_{2} n_{1}\right),\left(n_{1} l_{2}-n_{2} l_{1}\right),\left(l_{1} m_{2}-l_{2} m_{1}\right) .
$$

---

### Example 19:

Find the angle between the two lines whose direction cosines are connected by the relations $l+m+n=0$ and $l^{2}+m^{2}-n^{2}=0$.

#### Solution:

The given relations are
$$
\begin{align*}
& l+m+n=0  \tag{i}\\
& l^{2}+m^{2}-n^{2}=0 . \tag{ii}
\end{align*}
$$
From (i), we get $l=-(m+n)$.

Putting $l=-(m+n)$ in (ii), we get
$$
\begin{aligned}
\{-(m+n)\}^{2}+m^{2}-n^{2}=0 & \Rightarrow 2 m^{2}+2 m n=0 \\
& \Rightarrow 2 m(m+n)=0 \\
& \Rightarrow m=0 \text { or }(m+n)=0 \\
& \Rightarrow m=0 \text { or } m=-n
\end{aligned}
$$
Putting $m=0$ in (i), we get $l=-n$.

Putting $m=-n$ in (i), we get $l=0$.

$\therefore$ d.r.'s of these lines are $-n, 0, n$ and $0,-n, n$, i.e., $-1,0,1$ and $0,-1,1$.

If $\theta$ is the acute angle between these lines, we have
$$
\begin{aligned}
& \quad \cos \theta=\frac{|(-1) \times 0+0 \times(-1)+1 \times 1|}{\left\{\sqrt{(-1)^{2}+0^{2}+1^{2}}\right\} \cdot\left\{\sqrt{0^{2}+(-1)^{2}+1^{2}}\right\}}=\frac{1}{(\sqrt{2} \times \sqrt{2})}=\frac{1}{2} . \\
& \therefore \quad \theta=\frac{\pi}{3} .
\end{aligned}
$$
Hence, the angle between the given lines is $\frac{\pi}{3}$.

---

### Example 20:

Find the direction cosines of the lines which are connected by the relations $l-5 m+3 n=0$ and $7 l^{2}+5 m^{2}-3 n^{2}=0$.

#### Solution:

The given equations are
$$
\begin{align*}
& l-5 m+3 n=0  \tag{i}\\
& 7 l^{2}+5 m^{2}-3 n^{2}=0 . \tag{ii}
\end{align*}
$$
Putting $l=(5 m-3 n)$ from (i) in (ii), we get
$$
\begin{aligned}
& 7(5 m-3 n)^{2}+5 m^{2}-3 n^{2}=0 \\
\Rightarrow & 6 m^{2}-7 m n+2 n^{2}=0
\end{aligned}
$$
$\Rightarrow 6\left(\frac{m}{n}\right)^{2}-7\left(\frac{m}{n}\right)+2=0 \Rightarrow 6 p^{2}-7 p+2=0$, where $\frac{m}{n}=p$

$\Rightarrow \quad(3 p-2)(2 p-1)=0$

$\Rightarrow \quad p=\frac{2}{3}$ or $p=\frac{1}{2} \Rightarrow \frac{m}{n}=\frac{2}{3}$ or $\frac{m}{n}=\frac{1}{2}$.

Now, $\frac{m}{n}=\frac{2}{3} \Rightarrow \frac{m}{2}=\frac{n}{3}=\frac{5 m-3 n}{5 \times 2-3 \times 3}=\frac{l}{1}$

$\Rightarrow \frac{l}{1}=\frac{m}{2}=\frac{n}{3}=\frac{\sqrt{l^{2}+m^{2}+n^{2}}}{\sqrt{1^{2}+2^{2}+3^{2}}}=\frac{1}{\sqrt{14}}$

$\Rightarrow \quad l=\frac{1}{\sqrt{14}}, m=\frac{2}{\sqrt{14}}, n=\frac{3}{\sqrt{14}}$.

Again, $\frac{m}{n}=\frac{1}{2} \Rightarrow \frac{m}{1}=\frac{n}{2}=\frac{5 m-3 n}{5 \times 1-3 \times 2}=\frac{l}{-1}$
$$
\begin{aligned}
& \Rightarrow \frac{l}{-1}=\frac{m}{1}=\frac{n}{2}=\frac{\sqrt{l^{2}+m^{2}+n^{2}}}{\sqrt{(-1)^{2}+1^{2}+2^{2}}}=\frac{1}{\sqrt{6}} \\
& \Rightarrow l=\frac{-1}{\sqrt{6}}, m=\frac{1}{\sqrt{6}}, n=\frac{2}{\sqrt{6}}
\end{aligned}
$$
Hence, the direction cosines of the lines are
$$
\left(\frac{1}{\sqrt{14}}, \frac{2}{\sqrt{14}}, \frac{3}{\sqrt{14}}\right) \text { and }\left(\frac{-1}{\sqrt{6}}, \frac{1}{\sqrt{6}}, \frac{2}{\sqrt{6}}\right) .
$$

---

### Example 21:

If a variable line in two adjacent positions has direction cosines $(l, m, n)$ and $(l+\delta l, m+\delta m, n+\delta n)$, show that the small angle $\delta \theta$ between the two positions is given by
$$
(\delta \theta)^{2}=(\delta l)^{2}+(\delta m)^{2}+(\delta n)^{2} .
$$

#### Solution:

Clearly, we have
$$
\begin{align*}
& \quad l^{2}+m^{2}+n^{2}=1  \tag{i}\\
& \text { and }(l+\delta l)^{2}+(m+\delta m)^{2}+(n+\delta n)^{2}=1 \tag{ii}
\end{align*}
$$
Subtracting (i) from (ii), we get
$$
\begin{align*}
\quad(l+\delta l)^{2}+(m+\delta m)^{2}+(n+\delta n)^{2}-\left(l^{2}+m^{2}+n^{2}\right)=0 \\
\Rightarrow \quad(\delta l)^{2}+(\delta m)^{2}+(\delta n)^{2}=-2(l \cdot \delta l+m \cdot \delta m+n \cdot \delta n)  \tag{iii}\\
\therefore \quad \cos \delta \theta=l \cdot(l+\delta l)+m \cdot(m+\delta m)+n \cdot(n+\delta n) \\
\quad=\left(l^{2}+m^{2}+n^{2}\right)+(l \cdot \delta l+m \cdot \delta m+n \cdot \delta n) \\
\quad=1-\frac{1}{2}\left\{(\delta l)^{2}+(\delta m)^{2}+(\delta n)^{2}\right\} \quad[\text { using (i) and (iii)]. }
\end{align*}
$$
$$
\begin{aligned}
& \begin{aligned}
\therefore \quad(\delta l)^{2}+(\delta m)^{2}+(\delta n)^{2}= & 2(1-\cos \delta \theta) \\
= & 4 \sin ^{2} \frac{\delta \theta}{2}=4 \cdot\left(\frac{\delta \theta}{2}\right)^{2} \\
& \quad\left[\because \frac{\delta \theta}{2} \text { being small, } \sin \frac{\delta \theta}{2}=\frac{\delta \theta}{2}\right] \\
= & (\delta \theta)^{2} .
\end{aligned} \\
& \text { Hence, }(\delta \theta)^{2}=(\delta l)^{2}+(\delta m)^{2}+(\delta n)^{2} .
\end{aligned}
$$

---

### Example 22:

Prove that the straight lines whose direction cosines are given by the relations $a l+b m+c n=0$ and $f m n+g n l+h l m=0$ are
- perpendicular to each other if $\frac{f}{a}+\frac{g}{b}+\frac{h}{c}=0$, and
- parallel if $a^{2} f^{2}+b^{2} g^{2}+c^{2} h^{2}-2 b c g h-2 c a h f-2 a b f g=0$.

#### Solution:

The given equations are
$$
\begin{align*}
& a l+b m+c n=0  \tag{i}\\
& f m n+g n l+h l m=0 . \tag{ii}
\end{align*}
$$
Putting $n=\frac{-(a l+b m)}{c}$ from (i) in (ii), we get
$$
\begin{align*}
& f m \cdot\left\{\frac{-(a l+b m)}{c}\right\}+g l \cdot\left\{\frac{-(a l+b m)}{c}\right\}+h l m=0 \\
\Rightarrow & a g l^{2}+(a f+b g-c h) l m+b f m^{2}=0 \\
\Rightarrow & a g\left(\frac{l}{m}\right)^{2}+(a f+b g-c h) \cdot\left(\frac{l}{m}\right)+b f=0 \tag{iii}
\end{align*}
$$
Now, equation (iii), being a quadratic equation in $\left(\frac{l}{m}\right)$, will have two roots, say $\left(\frac{l_{1}}{m_{1}}\right)$ and $\left(\frac{l_{2}}{m_{2}}\right)$.
$$
\begin{aligned}
& \therefore \quad \frac{l_{1}}{m_{1}} \times \frac{l_{2}}{m_{2}}=\frac{b f}{a g} \\
& \Rightarrow \frac{l_{1} l_{2}}{b f}=\frac{m_{1} m_{2}}{a g} \\
& \Rightarrow \frac{l_{1} l_{2}}{\left(\frac{f}{a}\right)}=\frac{m_{1} m_{2}}{\left(\frac{g}{b}\right)}=\frac{n_{1} n_{2}}{\left(\frac{h}{c}\right)}=k \quad \text { [by symmetry]. } \\
& \therefore \quad l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}=k\left(\frac{f}{a}+\frac{g}{b}+\frac{h}{c}\right) .
\end{aligned}
$$
Thus, the given lines will be perpendicular to each other
$\Leftrightarrow l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}=0 \Leftrightarrow \frac{f}{a}+\frac{g}{b}+\frac{h}{c}=0$.

The lines will be parallel only when the roots of (iii) are equal.
$\therefore \quad(a f+b g-c h)^{2}-4 a b g f=0$
$\Leftrightarrow a^{2} f^{2}+b^{2} g^{2}+c^{2} h^{2}-2 b c g h-2 c a h f-2 a b f g=0$.

---

### Example 23:

Show that the straight lines whose direction cosines are given by the equations $a l+b m+c n=0$ and $u l^{2}+v m^{2}+w n^{2}=0$ are mutually perpendicular if $a^{2}(v+w)+b^{2}(u+w)+c^{2}(u+v)=0$, and parallel if $\frac{a^{2}}{u}+\frac{b^{2}}{v}+\frac{c^{2}}{w}=0$.

#### Solution:

The given equations are
$$
\begin{align*}
& a l+b m+c n=0  \tag{i}\\
& u l^{2}+v m^{2}+w n^{2}=0 . \tag{ii}
\end{align*}
$$
Putting $l=\frac{-(b m+c n)}{a}$ from (i) in (ii), we get
$$
\begin{align*}
& \frac{u(b m+c n)^{2}}{a^{2}}+v m^{2}+w n^{2}=0 \\
\Rightarrow & \left(b^{2} u+a^{2} v\right) m^{2}+2 u b c m n+\left(c^{2} u+a^{2} w\right) n^{2}=0 \\
\Rightarrow & \left(b^{2} u+a^{2} v\right)\left(\frac{m}{n}\right)^{2}+2 u b c\left(\frac{m}{n}\right)+\left(c^{2} u+a^{2} w\right)=0 . \tag{iii}
\end{align*}
$$
Let $\frac{m_{1}}{n_{1}}$ and $\frac{m_{2}}{n_{2}}$ be the roots of (iii).

Then, $\frac{m_{1}}{n_{1}} \cdot \frac{m_{2}}{n_{2}}=\frac{c^{2} u+a^{2} w}{b^{2} u+a^{2} v}$

$\Rightarrow \quad \frac{m_{1} m_{2}}{c^{2} u+a^{2} w}=\frac{n_{1} n_{2}}{b^{2} u+a^{2} v}=\frac{l_{1} l_{2}}{b^{2} w+c^{2} v}=k \quad$ [by symmetry].

$\therefore \quad l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}=k\left(b^{2} w+c^{2} v+c^{2} u+a^{2} w+b^{2} u+a^{2} v\right)$.

The given lines are mutually perpendicular
$\Leftrightarrow l_{1} l_{2}+m_{1} m_{2}+n_{1} n_{2}=0$
$\Leftrightarrow \quad a^{2}(v+w)+b^{2}(w+u)+c^{2}(u+v)=0$.

For the given lines to be parallel, the direction cosines must be equal.

$\therefore \quad$ the roots of (iii) must be equal.

$\therefore \quad 4 u^{2} b^{2} c^{2}-4\left(b^{2} u+a^{2} v\right)\left(c^{2} u+a^{2} w\right)=0 \Leftrightarrow \frac{a^{2}}{u}+\frac{b^{2}}{v}+\frac{c^{2}}{w}=0$.

---

### Example 24:

If the edges of a rectangular parallelepiped are $a, b, c$, prove that the angles between the four diagonals are given by $\cos ^{-1}\left(\frac{ \pm a^{2} \pm b^{2} \pm c^{2}}{a^{2}+b^{2}+c^{2}}\right)$.

#### Solution:

Let $O A, O B, O C$ be the coterminous edges of the parallelepiped, taken along the axes in such a way that $O A=a, O B=b$ and $O C=c$. Then, the coordinates of the vertices are
$$
\begin{aligned}
& O(0,0,0), A(a, 0,0), B(0, b, 0), \\
& C(0,0, c), P(a, b, c), L(0, b, c), \\
& M(a, 0, c) \text { and } N(a, b, 0) .
\end{aligned}
$$
The direction ratios of the diagonals $O P, A L, B M$ and $C N$ are $(a, b, c),(-a, b, c),(a,-b, c)$ and $(a, b,-c)$ respectively.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-014.jpg?height=322&width=512&top_left_y=561&top_left_x=404)

$\therefore$ the direction cosines of $O P, A L, B M$ and $C N$ are
$$
\begin{aligned}
& \left(\frac{a}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{b}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{c}{\sqrt{a^{2}+b^{2}+c^{2}}}\right), \\
& \left(\frac{-a}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{b}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{c}{\sqrt{a^{2}+b^{2}+c^{2}}}\right), \\
& \left(\frac{a}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{-b}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{c}{\sqrt{a^{2}+b^{2}+c^{2}}}\right), \\
& \left(\frac{a}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{b}{\sqrt{a^{2}+b^{2}+c^{2}}}, \frac{-c}{\sqrt{a^{2}+b^{2}+c^{2}}}\right) \text { respectively. }
\end{aligned}
$$
Let $\theta_{1}$ be the angle between $O P$ and $A L$. Then,
$$
\cos \theta_{1}=\frac{\left(-a^{2}+b^{2}+c^{2}\right)}{\left(a^{2}+b^{2}+c^{2}\right)} \quad \text { or } \quad \theta_{1}=\cos ^{-1}\left(\frac{-a^{2}+b^{2}+c^{2}}{a^{2}+b^{2}+c^{2}}\right) .
$$
Again, let $\theta_{2}$ be the angle between $O P$ and $B M$. Then,
$$
\cos \theta_{2}=\frac{\left(a^{2}-b^{2}+c^{2}\right)}{\left(a^{2}+b^{2}+c^{2}\right)} \quad \text { or } \quad \theta_{2}=\cos ^{-1}\left(\frac{a^{2}-b^{2}+c^{2}}{a^{2}+b^{2}+c^{2}}\right) .
$$
Similarly, the angles between the other pairs of diagonals can be obtained.

Clearly, the angles between the four diagonals can be given by
$$
\cos ^{-1}\left(\frac{ \pm a^{2} \pm b^{2} \pm c^{2}}{a^{2}+b^{2}+c^{2}}\right) .
$$

---

### Example 25:

Show that the angle between any two diagonals of a cube is $\cos ^{-1}\left(\frac{1}{3}\right)$.

#### Solution:

Let $O A, O B, O C$ be the coterminous edges of a cube, taken along the axes in such a way that $O A=O B=O C=a$. Then, the coordinates of the vertices of the cube are
$$
\begin{aligned}
& O(0,0,0), A(a, 0,0,), B(0, a, 0), \\
& C(0,0, a), P(a, a, a,), L(0, a, a), \\
& M(a, 0, a) \text { and } N(a, a, 0) .
\end{aligned}
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-015.jpg?height=321&width=351&top_left_y=440&top_left_x=856)

The direction ratios of the diagonals $O P, A L, B M$ and $C N$ are $(a, a, a),(-a, a, a),(a,-a, a)$ and $(a, a,-a)$ respectively.

Thus, direction cosines of $O P, A L, B M$ and $C N$ are
$$
\begin{aligned}
& \left(\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}\right),\left(\frac{-1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}\right),\left(\frac{1}{\sqrt{3}}, \frac{-1}{\sqrt{3}}, \frac{1}{\sqrt{3}}\right) \text { and } \\
& \left(\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{-1}{\sqrt{3}}\right) \text { respectively. }
\end{aligned}
$$
If $\theta_{1}$ be the angle between $O P$ and $A L$ then
$$
\cos \theta_{1}=\left\{\frac{1}{\sqrt{3}} \cdot\left(\frac{-1}{\sqrt{3}}\right)+\frac{1}{\sqrt{3}} \cdot \frac{1}{\sqrt{3}}+\frac{1}{\sqrt{3}} \cdot \frac{1}{\sqrt{3}}\right\}=\frac{1}{3}
$$
$\Rightarrow \quad \theta_{1}=\cos ^{-1}\left(\frac{1}{3}\right)$.

Similarly, the angle between each one of the other pairs is $\cos ^{-1}\left(\frac{1}{3}\right)$.

Hence, the angle between any two diagonals of the cube is $\cos ^{-1}\left(\frac{1}{3}\right)$.

---

### Example 26:

A line makes angles $\alpha, \beta, \gamma, \delta$ with the four diagonals of a cube. Prove that
$$
\cos ^{2} \alpha+\cos ^{2} \beta+\cos ^{2} \gamma+\cos ^{2} \delta=\frac{4}{3} .
$$
[CBSE 2007]

#### Solution:

Let $O A, O B, O C$ be the coterminous edges of a cube, taken along the axes in such a way that $O A=O B=O C=a$.

Then, the coordinates of the vertices of the cube are $O(0,0,0), A(a, 0,0)$,
$$
\begin{aligned}
& B(0, a, 0), C(0,0, a), P(a, a, a) \\
& L(0, a, a), M(a, 0, a) \text { and } N(a, a, 0)
\end{aligned}
$$
The direction ratios of the diagonals $O P, A L, B M$ and $C N$ are
$(a, a, a),(-a, a, a),(a,-a, a)$ and $(a, a,-a)$ respectively.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-016.jpg?height=319&width=355&top_left_y=157&top_left_x=852)

$\therefore \quad$ the direction cosines of $O P, A L, B M$ and $C N$ are
$$
\begin{aligned}
& \left(\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}\right),\left(\frac{-1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}\right),\left(\frac{1}{\sqrt{3}}, \frac{-1}{\sqrt{3}}, \frac{1}{\sqrt{3}}\right) \text { and } \\
& \left(\frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3}}, \frac{-1}{\sqrt{3}}\right) \text { respectively. }
\endaligned}
$$
Let $(l, m, n)$ be the direction cosines of a line which makes angles $\alpha, \beta, \gamma, \delta$ with the four diagonals of the cube. Then,
$$
\begin{aligned}
& \cos \alpha=\left(l \cdot \frac{1}{\sqrt{3}}+m \cdot \frac{1}{\sqrt{3}}+n \cdot \frac{1}{\sqrt{3}}\right)=\frac{(l+m+n)}{\sqrt{3}}, \\
& \cos \beta=\left\{l \cdot\left(\frac{-1}{\sqrt{3}}\right)+m \cdot \frac{1}{\sqrt{3}}+n \cdot \frac{1}{\sqrt{3}}\right\}=\frac{(-l+m+n)}{\sqrt{3}}, \\
& \cos \gamma=\left\{l \cdot \frac{1}{\sqrt{3}}+m \cdot\left(\frac{-1}{\sqrt{3}}\right)+n \cdot \frac{1}{\sqrt{3}}\right\}=\frac{(l-m+n)}{\sqrt{3}}, \\
& \cos \delta=\left\{l \cdot \frac{1}{\sqrt{3}}+m \cdot \frac{1}{\sqrt{3}}+n \cdot\left(\frac{-1}{\sqrt{3}}\right)\right\}=\frac{(l+m-n)}{\sqrt{3}},
\end{aligned}
$$
On squaring and adding, we get
$$
\begin{aligned}
\cos ^{2} \alpha & \alpha+\cos ^{2} \beta+\cos ^{2} \gamma+\cos ^{2} \delta \\
& =\frac{1}{3} \cdot\left\{(l+m+n)^{2}+(-l+m+n)^{2}+(l-m+n)^{2}+(l+m-n)^{2}\right\} \\
& =\frac{4}{3} .
\end{aligned}
$$

---

