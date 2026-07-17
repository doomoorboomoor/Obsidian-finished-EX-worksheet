## PLANE PASSING THROUGH THE INTERSECTION OF TWO PLANES

**THEOREM 1** The equation of a plane passing through the intersection of two planes

$$
\vec{r} \cdot \overrightarrow{n_{1}}=q_{1} \text { and } \vec{r} \cdot \overrightarrow{n_{2}}=q_{2} \text { is given by } \vec{r} \cdot\left(\overrightarrow{n_{1}}+\lambda \overrightarrow{n_{2}}\right)=\left(q_{1}+\lambda q_{2}\right) .
$$

**PROOF** Let $\pi_{1}$ and $\pi_{2}$ be the two given planes with equations $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ respectivley.
Let $\vec{t}$ be the position vector of any point on their line of intersection.
Then, it must satisfy both the equations.
$\therefore \quad \vec{t} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{t} \cdot \overrightarrow{n_{2}}=q_{2}$

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-113.jpg?height=221&width=508&top_left_y=489&top_left_x=699)

$\Rightarrow \vec{t} \cdot\left(\overrightarrow{n_{1}}+\lambda \overrightarrow{n_{2}}\right)=\left(q_{1}+\lambda q_{2}\right)$ for every real value $\lambda$.
Since $\vec{t}$ is arbitrary, the required equation of a plane $\pi_{3}$ passing through the intersection of the given planes, is given by

$$
\vec{r} \cdot\left(\overrightarrow{n_{1}}+\lambda \overrightarrow{n_{2}}\right)=\left(q_{1}+\lambda q_{2}\right) .
$$

---

**THEOREM 2** The equation of a plane passing through the intersection of two planes

$$
\begin{aligned}
a_{1} x+b_{1} y+c_{1} z & =d_{1} \text { and } a_{2} x+b_{2} y+c_{2} z=d_{2} \text { is given by } \\
& \left(a_{1} x+b_{1} y+c_{1} z-d_{1}\right)+\lambda\left(a_{2} x+b_{2} y+c_{2} z-d_{z}\right)=0
\end{aligned}
$$

**PROOF** Taking $\overrightarrow{n_{1}}=\left(a_{1} \hat{i}+b_{1} \hat{j}+c_{1} \hat{k}\right)$, $\overrightarrow{n_{2}}=\left(a_{2} \hat{i}+b_{2} \hat{j}+c_{3} \hat{k}\right)$, $q_{1}=d_{1}$, $q_{2}=d_{2}$
and $\vec{r}=(x \hat{i}+y \hat{j}+z \hat{k})$, we may write the above vector equation as

$$
(x \hat{i}+y \hat{j}+z \hat{k}) \cdot\left[\left(a_{1} \hat{i}+b_{1} \hat{j}+c_{1} \hat{k}\right)+\lambda\left(a_{2} \hat{i}+b_{2} \hat{j}+c_{2} \hat{k}\right)=\left(d_{1}+\lambda d_{2}\right)\right]
$$

$$
\Rightarrow \quad\left(a_{1} x+b_{1} y+c_{1} z=d_{1}\right)+\lambda\left(a_{2} x+b_{2} y+c_{2} z-d_{z}\right)=0,
$$

which is the required Cartesian form of the equation of the plane passing through the intersection of the given planes for each value of $\lambda$.

---

## SUMMARY

1.  The vector equation of a plane passing through the intersection of two planes $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$ is given by
    
    $$
    \vec{r} \cdot\left(\overrightarrow{n_{1}}+\lambda \overrightarrow{n_{2}}\right)=\left(q_{1}+\lambda q_{2}\right) .
    $$
    
2.  The equation of a plane passing through the intersection of two planes $a_{1} x+b_{1} y+c_{1} z=d_{1}$ and $a_{2} x+b_{2} y+c_{2} z=d_{2}$ is given by $\left(a_{1} x+b_{1} y+c_{1} z-d_{1}+\lambda\left(a_{2} x+b_{2} y+c_{2} z-d_{2}\right)=0\right.$.

---

## SOLVED EXAMPLES

### Example 1

Find the equation of the plane through the intersection of the planes $3 x-y+2 z=4$ and $x+y+z=2$ and passing through the point $(2,2,1)$.

#### Solution:

Let the required equation of the plane be

$$
\begin{align*}
& (3 x-y+2 z-4)+\lambda(x+y+z-2)=0 \text { for some real value of } \lambda \\
\Rightarrow \quad & (3+\lambda) x+(-1+\lambda) y+(2+\lambda) z-(4+2 \lambda)=0 . \tag{i}
\end{align*}
$$

It is given that the point $A(2,2,1)$ lies on (i).

$$
\begin{align*}
\therefore \quad &(3+\lambda) \times 2+(-1+\lambda) \times 2+(2+\lambda) \times 1-(4+2 \lambda)=0 \\
\Rightarrow &(6+2 \lambda)+(-2+2 \lambda)+(2+\lambda)-4-2 \lambda=0 \\
\Rightarrow \quad &3 \lambda=-2 \Rightarrow \lambda=\frac{-2}{3}.
\end{align*}
$$

Putting $\lambda=\frac{-2}{3}$ in (i), we get

$$
\begin{aligned}
& \left(3-\frac{2}{3}\right) x+\left(-1-\frac{2}{3}\right) y+\left(2-\frac{2}{3}\right) z-4+\frac{4}{3}=0 \\
\Rightarrow & \frac{7 x}{3}-\frac{5 y}{3}+\frac{4 z}{3}-\frac{8}{3}=0 \Rightarrow 7 x-5 y+4 z-8=0 .
\end{aligned}
$$

Hence, the required equation of the plane is $7 x-5 y+4 z-8=0$.

---

### Example 2

Find the equation of the plane through the line of intersection of the planes $x+y+z=1$ and $2 x+3 y+4 z=5$, which is perpendicular to the plane $x-y+z=0$. Also find the distance of the plane so obtained from the origin.
**[CBSE 2014]**

#### Solution:

Let the required equation of the plane be

$$
(x+y+z-1)+\lambda(2 x+3 y+4 z-5)=0
$$

for some real value of $\lambda$

$$
\begin{equation*}
\Rightarrow \quad(1+2 \lambda) x+(1+3 \lambda) y+(1+4 \lambda) z-(1+5 \lambda)=0 . \tag{i}
\end{equation*}
$$

Since this plane is perpendicular to the plane $x-y+z=0$, we have

$$
\begin{aligned}
& (1+2 \lambda) \times 1+(1+3 \lambda) \times(-1)+(1+4 \lambda) \times 1=0 \\
\Rightarrow & (1+2 \lambda)-(1+3 \lambda)+(1+4 \lambda)=0 \Rightarrow 3 \lambda=-1 \Rightarrow \lambda=\frac{-1}{3} .
\end{aligned}
$$

Putting $\lambda=\frac{-1}{3}$ in (i), we get

$$
\begin{aligned}
& \left(1-\frac{2}{3}\right) x+(1-1) y+\left(1-\frac{4}{3}\right) z-1+\frac{5}{3}=0 \\
\Rightarrow & \frac{1}{3} x-\frac{1}{3} z+\frac{2}{3}=0 \Rightarrow x-z+2=0 .
\end{aligned}
$$

Hence, the required equation of the plane is $x-z+2=0$.

Distance of the plane from the origin
$=$ Length of perpendicular from the origin to the plane

$$
=\frac{|0-0+2|}{\sqrt{1^{2}+0^{2}+(-1)^{2}}}=\frac{2}{\sqrt{2}}=\sqrt{2} .
$$

---

### Example 3

Find the equation of the plane passing through the line of intersection of the planes $2 x+y-z=3$ and $5 x-3 y+4 z+9=0$ and parallel to the line

$$
\frac{x-1}{2}=\frac{y-3}{4}=\frac{z-5}{5} .
$$

**[CBSE 2011]**

#### Solution:

Let the required equation of the plane be

$$
\begin{align*}
& (2 x+y-z-3)+\lambda(5 x-3 y+4 z+9)=0 \\
\Rightarrow \quad & (2+5 \lambda) x+(1-3 \lambda) y+(-1+4 \lambda) z-3+9 \lambda=0 . \tag{i}
\end{align*}
$$

The plane given by (i) is parallel to the line

$$
\begin{equation*}
\frac{x-1}{2}=\frac{y-3}{4}=\frac{z-5}{5} . \tag{ii}
\end{equation*}
$$

So, the normal to the plane (i) is perpendicular to the line (ii).

$$
\begin{align*}
\therefore \quad &2(2+5 \lambda)+4(1-3 \lambda)+5(-1+4 \lambda)=0 \\
\Rightarrow \quad &(4+10 \lambda)+(4-12 \lambda)+(-5+20 \lambda)=0 \\
\Rightarrow \quad &18 \lambda=-3 \Rightarrow \lambda=\frac{-3}{18} \Rightarrow \lambda=\frac{-1}{6}.
\end{align*}
$$

Putting $\lambda=\frac{-1}{6}$ in (i), we get

$$
\begin{aligned}
& \left(2-\frac{5}{6}\right) x+\left(1+\frac{3}{6}\right) y+\left(-1-\frac{4}{6} z\right)-9 \times \frac{1}{6}=0 \\
\Rightarrow & \frac{7 x}{6}+\frac{9 y}{6}-\frac{10 z}{6}-\frac{27}{6}=0 \\
\Rightarrow & 7 x+9 y-10 z-27=0 .
\end{aligned}
$$

Hence, the required equation of the plane is $7 x+9 y-10 z-27=0$.

---

### Example 4

Find the equation of the plane passing through the intersection of the planes $\vec{r} \cdot(\hat{i}+\hat{j}+\hat{k})=1$ and $\vec{r} \cdot(2 \hat{i}+3 \hat{j}-\hat{k})+4=0$ and parallel to the $x$-axis.
**[CBSE 2011]**

#### Solution:

Converting the given equations of the planes in Cartesian form, we get

$$
\begin{align*}
\vec{r} \cdot(\hat{i}+\hat{j}+\hat{k})=1 & \Rightarrow(x \hat{i}+y \hat{j}+z \hat{k}) \cdot(\hat{i}+\hat{j}+\hat{k})=1 \\
& \Rightarrow x+y+z-1=0,  \tag{i}\\
\vec{r} \cdot(2 \hat{i}+3 \hat{j}-\hat{k})+4=0 & \Rightarrow(x \hat{i}+y \hat{j}+z \hat{k}) \cdot(2 \hat{i}+3 \hat{j}-\hat{k})+4=0 \\
& \Rightarrow 2 x+3 y-z+4=0 . \tag{ii}
\end{align*}
$$

Now, the equation of a plane passing through the intersection of the planes (i) and (ii) is given by

$$
\begin{align*}
& (x+y+z-1)+\lambda(2 x+3 y-z+4)=0 \text { for some real value of } \lambda \\
\Rightarrow \quad & (1+2 \lambda) x+(1+3 \lambda) y+(1-\lambda) z+(-1+4 \lambda)=0 . \tag{iii}
\end{align*}
$$

D.r.'s of the normal to the plane are $(1+2 \lambda),(1+3 \lambda),(1-\lambda)$.
D.r.'s of the $x$-axis are $1,0,0$.

Plane (iii) is parallel to the $x$-axis means that the normal to this plane is perpendicular to the $x$-axis.
$\therefore \quad 1 \times(1+2 \lambda)+0 \times(1+3 \lambda)+0 \times(1-\lambda)=0 \Rightarrow 1+2 \lambda=0 \Rightarrow \lambda=\frac{-1}{2}$.

Putting $\lambda=\frac{-1}{2}$ in (iii), we get the required equation of the plane as

$$
\begin{aligned}
& (1-1) x+\left(1-\frac{3}{2}\right) y+\left(1+\frac{1}{2}\right) z+(-1-2)=0 \\
\Rightarrow & \frac{-y}{2}+\frac{3 z}{2}-3=0 \Rightarrow y-3 z+6=0
\end{aligned}
$$

Hence, the required equation of the plane is $y-3 z+6=0$.

---

### Example 5

Find the equation of the plane passing through the line of intersection of the planes $\vec{r} \cdot(\hat{i}+3 \hat{j})-6=0$ and $\vec{r} \cdot(3 \hat{i}-\hat{j}-4 \hat{k})=0$, whose perpendicular distance from the origin is unity.
**[CBSE 2013]**

#### Solution:

Taking $\vec{r}=(x \hat{i}+y \hat{j}+z \hat{k})$, the equations of the given planes are

$$
\begin{align*}
& (x \hat{i}+y \hat{j}+z \hat{k}) \cdot(\hat{i}+3 \hat{j})-6=0 \Rightarrow x+3 y-6=0  \tag{i}\\
& (x \hat{i}+y \hat{j}+z \hat{k}) \cdot(3 \hat{i}-\hat{j}-4 \hat{k})=0 \Rightarrow 3 x-y-4 z=0 \tag{ii}
\end{align*}
$$

The equation of any plane passing through the line of intersection of the given planes is given by

$$
\begin{align*}
& (x+3 y-6)+\lambda(3 x-y-4 z) \text { for some real number } \lambda . \\
\Rightarrow \quad & (1+3 \lambda) x+(3-\lambda) y-4 \lambda z-6=0 . \tag{iii}
\end{align*}
$$

Length of perpendicular from origin to plane (iii) is given as 1 .

$$
\begin{array}{ll}
\therefore & \frac{|0+0-0-6|}{\sqrt{(1+3 \lambda)^{2}+(3-\lambda)^{2}+(-4 \lambda)^{2}}}=1 \\
\Rightarrow & (1+3 \lambda)^{2}+(3-\lambda)^{2}+(-4 \lambda)^{2}=36 \\
\Rightarrow & 26 \lambda^{2}=26 \Rightarrow \lambda^{2}=1 \Rightarrow \lambda= \pm 1 .
\end{array}
$$

Putting $\lambda=1$ in (iii), we get

$$
4 x+2 y-4 z-6=0 \Rightarrow 2 x+y-2 z-3=0
$$

Putting $\lambda=-1$ in (iii), we get

$$
-2 x+4 y+4 z-6=0 \Rightarrow x-2 y-2 z+3=0 .
$$

Hence, the required equations of the plane are

$$
2 x+y-2 z-3=0 \text { and } x-2 y-2 z+3=0
$$

**Note:** The vector equations of these planes are

$$
\vec{r} \cdot(2 \hat{i}+\hat{j}-2 \hat{k})=3 \text { and } \vec{r} \cdot(\hat{i}-2 \hat{j}-2 \hat{k})+3=0
$$

---

### Example 6

Find the vector equation of the plane passing through the intersection of the planes $\vec{r} \cdot(2 \hat{i}+2 \hat{j}-3 \hat{k})=7$ and $\vec{r} \cdot(2 \hat{i}+5 \hat{j}+3 \hat{k})=9$ and passing through the point $(2,1,3)$.

#### Solution:

The equations of the given planes are $\vec{r} \cdot(2 \hat{i}+2 \hat{j}-3 \hat{k})=7$ and $\vec{r} \cdot(2 \hat{i}+5 \hat{j}+3 \hat{k})=9$.

These are of the form $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$, where

$$
\overrightarrow{n_{1}}=(2 \hat{i}+2 \hat{j}-3 \hat{k}), \overrightarrow{n_{2}}=(2 \hat{i}+5 \hat{j}+3 \hat{k}), q_{1}=7 \text { and } q_{2}=9 .
$$

The equation of the plane through the intersection of the given planes is given by

$$
\begin{align*}
& \vec{r} \cdot\left(\overrightarrow{n_{1}}+\lambda \overrightarrow{n_{2}}\right)=\left(q_{1}+\lambda q_{2}\right) \text { for some real number } \lambda \\
\Rightarrow & \vec{r} \cdot[(2 \hat{i}+2 \hat{j}-3 \hat{k})+\lambda(2 \hat{i}+5 \hat{j}+3 \hat{k})](7+9 \lambda) \\
\Rightarrow & \vec{r} \cdot[(2+2 \lambda) \hat{i}(2+5 \lambda) \hat{j}+(-3+3 \lambda) \hat{k}]=(7+9 \lambda) \tag{i}
\end{align*}
$$

If the plane (i) passes through the point $A(2,1,3)$, then

$$
\begin{array}{ll} 
& \vec{r}=(2 \hat{i}+\hat{j}+3 \hat{k}) \text { must satisfy it. } \\
\therefore & (2 \hat{i}+\hat{j}+3 \hat{k}) \cdot[(2+2 \lambda) \hat{i}+(2+5 \lambda) \hat{j}+(-3+3 \lambda) \hat{k}]=(7+9 \lambda) \\
\Rightarrow & 2(2+2 \lambda)+1 \cdot(2+5 \lambda)+3(-3+3 \lambda)=7+9 \lambda \\
\Rightarrow & (4+4 \lambda)+(2+5 \lambda)+(-9+9 \lambda)=7+9 \lambda \Rightarrow 9 \lambda=10 \Rightarrow \lambda=\frac{10}{9} .
\end{array}
$$

Putting $\lambda=\frac{10}{9}$ in (i), we get the required equation of the plane as

$$
\begin{aligned}
& \vec{r} \cdot\left[\left(2+\frac{20}{9}\right) \hat{i}+\left(2+\frac{50}{9}\right) \hat{j}+\left(-3+\frac{30}{9}\right) \hat{k}\right]=(7+10) \\
\Rightarrow & \vec{r} \cdot(38 \hat{i}+68 \hat{j}+3 \hat{k})=153 .
\end{aligned}
$$

Hence, the required equation of the plane is

$$
\vec{r} \cdot(38 \hat{i}+68 \hat{j}+3 \hat{k})=153 .
$$

---

### Example 7

Find the vector equation of the plane through the line of intersection of the planes $\vec{r} \cdot(\hat{i}+2 \hat{j}+3 \hat{k})-4=0$ and $\vec{r} \cdot(2 \hat{i}+\hat{j}-\hat{k})+5=0$ and perpendicular to the plane $\vec{r} \cdot(5 \hat{i}+3 \hat{j}-6 \hat{k})+8=0$.
**[CBSE 2011]**

#### Solution:

The equations of the given planes are

$$
\vec{r} \cdot(\hat{i}+2 \hat{j}+3 \hat{k})=4 \text { and } \vec{r} \cdot(-2 \hat{i}-\hat{j}+\hat{k})=5 .
$$

These equations are of the form $\vec{r} \cdot \overrightarrow{n_{1}}=q_{1}$ and $\vec{r} \cdot \overrightarrow{n_{2}}=q_{2}$, where

$$
\overrightarrow{n_{1}}=(\hat{i}+2 \hat{j}+3 \hat{k}), \overrightarrow{n_{2}}=(-2 \hat{i}-\hat{j}+\hat{k}), q_{1}=4 \text { and } q_{2}=5 .
$$

The equation of the plane through the intersection of the given planes is given by

$$
\begin{align*}
& \vec{r} \cdot\left(\overrightarrow{n_{1}}+\lambda \overrightarrow{n_{2}}\right)=\left(q_{1}+\lambda q_{2}\right) \text { for some real number } \lambda \\
\Rightarrow & \vec{r} \cdot[(\hat{i}+2 \hat{j}+3 \hat{k})+\lambda(-2 \hat{i}-\hat{j}+\hat{k})]=(4+5 \lambda) \\
\Rightarrow & \vec{r} \cdot[(1-2 \lambda) \hat{i}+(2-\lambda) \hat{j}+(3+\lambda) \hat{k}]=(4+5 \lambda) \tag{i}
\end{align*}
$$

This plane (i) is perpendicular to the plane $\vec{r} \cdot(-5 \hat{i}-3 \hat{j}+6 \hat{k})=8$, so we have

$$
\begin{aligned}
& (1-2 \lambda) \times(-5)+(2-\lambda) \times(-3)+(3+\lambda) \times 6=0 \\
\Rightarrow & (-5+10 \lambda)+(-6+3 \lambda)+(18+6 \lambda)=0 \\
\Rightarrow & 19 \lambda=-7 \Rightarrow \lambda=\frac{-7}{19}
\end{aligned}
$$

Putting $\lambda=\frac{-7}{19}$ in (i), we get

$$
\begin{aligned}
& \vec{r} \cdot\left[\left(1+\frac{14}{19}\right) \hat{i}+\left(2+\frac{7}{19}\right) \hat{j}+\left(3-\frac{7}{19}\right) \hat{k}\right]=\left(4-\frac{35}{19}\right) \\
\Rightarrow & \vec{r} \cdot(33 \hat{i}+45 \hat{j}+50 \hat{k})=41 .
\end{aligned}
$$

Hence, the required equation of the plane is

$$
\vec{r} \cdot(33 \hat{i}+45 \hat{j}+50 \hat{k})=41 .
$$

---