## 28. The Plane

**Plane:** A plane is a surface such that a line segment joining any two points on it lies wholly on it.

**Normal to a Plane:** A straight line which is perpendicular to every line lying on a plane is called a normal to the plane.

All the normals to a plane are parallel to each other.

---

## General Equation of a Plane in the Cartesian Form

### Theorem 1
> Every equation $ax +b y+c z+d=0$ of the first degree in $x, y, z$ always represents a plane. Also, $a, b, c$ are the direction ratios of the normal to this plane.

**Proof:**
Let us consider a surface represented by the equation

$$
\begin{equation*}
a x+b y+c z+d=0 \tag{i}
\end{equation*}
$$

Let $A\left(x_{1}, y_{1}, z_{1}\right)$ and $B\left(x_{2}, y_{2}, z_{2}\right)$ be any two points on the surface represented by (i). Then,

$$
\begin{gather*}
a x_{1}+b y_{1}+c z_{1}+d=0  \tag{ii}\\
\text { and, } a x_{2}+b y_{2}+c z_{2}+d=0 . \tag{iii}
\end{gather*}
$$

Multiplying (iii) by $\lambda$ and adding it to (ii), we get

$$
\begin{aligned}
& a\left(\lambda x_{2}+x_{1}\right)+b\left(\lambda y_{2}+y_{1}\right)+c\left(\lambda z_{2}+z_{1}\right)+d(\lambda+1)=0 \\
\Rightarrow & a\left(\frac{\lambda x_{2}+x_{1}}{\lambda+1}\right)+b\left(\frac{\lambda y_{2}+y_{1}}{\lambda+1}\right)+c\left(\frac{\lambda z_{2}+z_{1}}{\lambda+1}\right)+d=0 \\
\Rightarrow & \left(\frac{\lambda x_{2}+x_{1}}{\lambda+1}, \frac{\lambda y_{2}+y_{1}}{\lambda+1}, \frac{\lambda z_{2}+z_{1}}{\lambda+1}\right) \text { lies on surface (i), when } \lambda \neq-1 .
\end{aligned}
$$

But, these are the general coordinates of a point which divides $A B$ in the ratio $\lambda: 1$.

Since $\lambda$ may take any real value other than -1 , it follows that every point of $A B$ lies on (i).
Hence, $a x+b y+c z+d=0$ represents a plane.

### To Show that $a, b, c$ are the Direction Ratios of the Normal to the Plane

Subtracting (ii) from (iii), we get

$$
a\left(x_{2}-x_{1}\right)+b\left(y_{2}-y_{1}\right)+c\left(z_{2}-z_{1}\right)=0
$$

$\Rightarrow$ a line with direction ratios $a, b, c$ is perpendicular to an arbitrary line $A B$ taken on plane (i) $\left[\because \quad\left(x_{2}-x_{1}\right),\left(y_{2}-y_{1}\right),\left(z_{2}-z_{1}\right)\right.$ are d.r.'s of $\left.A B\right]$
$\Rightarrow$ a line with d.r.'s $a, b, c$ is perpendicular to the plane (i)
$\Rightarrow a, b, c$ are the direction ratios of the normal to the plane (i).
Hence, $a x+b y+c z+d=0$ represents a plane, and $a, b, c$ are the direction ratios of the normal to this plane.

---

## Equation of a Plane Passing through a Given Point

### Theorem 2
> The equation of a plane passing through a point $P\left(x_{1}, y_{1}, z_{1}\right)$ is
> $$
> a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0, \text { where } a, b, c \text { are constants. }
> $$

**Proof:**
The general equation of a plane is

$$
\begin{equation*}
a x+b y+c z+d=0 . \tag{i}
\end{equation*}
$$

If this plane passes through the point $P\left(x_{1}, y_{1}, z_{1}\right)$ then

$$
\begin{equation*}
a x_{1}+b y_{1}+c z_{1}+d=0 . \tag{ii}
\end{equation*}
$$

Subtracting (ii) from (i), we get

$$
a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0 .
$$

This is the general equation of a plane passing through the point $P\left(x_{1}, y_{1}, z_{1}\right)$.

---

## Equation of a Plane in the Intercept Form

### Theorem 3
> If a plane makes intercepts of lengths $a, b, c$ with the $x$-axis, $y$-axis and $z$-axis respectively, the equation of the plane is $\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1$.
> [CBSE 2004C]

**Proof:**
Let $O$ be the origin, and let the plane meet the coordinate axes at $A, B, C$ respectively such that

$$
O A=a, O B=b \text { and } O C=c
$$

So, the coordinates of these points are $A(a, 0,0), B(0, b, 0)$ and $C(0,0, c)$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c1fbe4b06552ea878a34g-075.jpg?height=456&width=469&top_left_y=1395&top_left_x=738)

Let the equation of the given plane be

$$
\begin{equation*}
A x+B y+C z+D=0 \tag{i}
\end{equation*}
$$

Since the given plane does not pass through $O(0,0,0), D \neq 0$.
Also, since (i) passes through $A(a, 0,0), B(0, b, 0)$ and $C(0,0, c)$, we have

$$
\begin{aligned}
& A a+D=0 \Rightarrow A=\frac{-D}{a} \\
& B b+D=0 \Rightarrow B=\frac{-D}{b} \\
& C c+D=0 \Rightarrow C=\frac{-D}{c}
\end{aligned}
$$

Putting these values in (i), we get

$$
\begin{aligned}
& \frac{-D x}{a}-\frac{D y}{b}-\frac{D z}{c}+D=0 \\
\Rightarrow \quad & \frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1 \quad[\text { on dividing throughout by }-D] .
\end{aligned}
$$

This is the required equation of the plane in the intercept form.

---

## Equation of a Plane Passing through Three Given Points

Suppose that a plane passes through the points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$.

We know that the equation of a plane passing through the point $A\left(x_{1}, y_{1}, z_{1}\right)$ is given by

$$
\begin{equation*}
a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0 . \tag{i}
\end{equation*}
$$

If this plane passes through the points $B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$, we have

$$
\begin{align*}
a\left(x_{2}-x_{1}\right)+b\left(y_{2}-y_{1}\right)+c\left(z_{2}-z_{1}\right) & =0  \tag{ii}\\
\text { and } a\left(x_{3}-x_{1}\right)+b\left(y_{3}-y_{1}\right)+c\left(z_{3}-z_{1}\right) & =0 . \tag{iii}
\end{align*}
$$

On eliminating $a, b, c$ from (i), (ii) and (iii), we get

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0 .
$$

This is the required equation of the plane passing through three points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $\left(x_{3}, y_{3}, z_{3}\right)$.

---

## Summary of the Results

1.  The general equation of a plane is $a x+b y+c z+d=0$. The d.r.'s of the normal to the plane are $a, b, c$.
2.  The equation of the plane passing through the point $P\left(x_{1}, y_{1}, z_{1}\right)$ is $a\left(x-x_{1}\right)+b\left(y-y_{1}\right)+c\left(z-z_{1}\right)=0$.
3.  If a plane makes intercepts $a, b$ and $c$ with the $x$-axis, $y$-axis and $z$-axis respectively, then its equation is
    $$
    \frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1 .
    $$
4.  The equation of a plane passing through three points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by
    $$
    \left|\begin{array}{ccc}
    x-x_{1} & y-y_{1} & z-z_{1} \\
    x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
    x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
    \end{array}\right|=0 .
    $$

---

## Solved Examples

### Example 1:

Find the equation of the plane passing through the points $A(2,5,-3)$, $B(-2,-3,5)$ and $C(5,3,-3)$.

#### Solution:

The equation of the plane passing through the point $A(2,5,-3)$ is given by

$$
\begin{equation*}
a(x-2)+b(y-5)+c(z+3)=0 . \tag{i}
\end{equation*}
$$

If this plane passes through the points $B(-2,-3,5)$ and $C(5,3,-3)$, then we have

$$
\begin{align*}
& a(-2-2)+b(-3-5)+c(5+3)=0 \Rightarrow-4 a-8 b+8 c=0  \tag{ii}\\
& a(5-2)+b(3-5)+c(-3+3)=0 \Rightarrow 3 a-2 b+0 c=0 . \tag{iii}
\end{align*}
$$

On solving (ii) and (iii) by cross multiplication, we get

$$
\begin{aligned}
& \frac{a}{(0+16)}=\frac{b}{(24-0)}=\frac{c}{(8+24)} \Rightarrow \frac{a}{16}=\frac{b}{24}=\frac{c}{32} \\
\Rightarrow & \frac{a}{2}=\frac{b}{3}=\frac{c}{4}=k(\mathrm{say}) \Rightarrow a=2 k, b=3 k \text { and } c=4 k
\end{aligned}
$$

Putting these values of $a, b$ and $c$ in (i), we get

$$
\begin{aligned}
& 2 k(x-2)+3 k(y-5)+4 k(z+3)=0 \\
\Rightarrow & 2(x-2)+3(y-5)+4(z+3)=0 \\
\Rightarrow & 2 x+3 y+4 z-7=0
\end{aligned}
$$

Hence, the required equation of the plane is $2 x+3 y+4 z-7=0$.

#### Alternate method:

We know that equation of the plane passing through the points $A\left(x_{1}, y_{1}, z_{1}\right)$, $B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0 .
$$

Here,

$$
\begin{aligned}
& \left(x_{1}=2, y_{1}=5, z_{1}=-3\right),\left(x_{2}=-2, y_{2}=-3, z_{2}=5\right) \text { and } \\
& \left(x_{3}=5, y_{3}=3, z_{3}=-3\right)
\end{aligned}
$$

$\therefore$ the required equation of the plane is

$$
\begin{aligned}
& \left|\begin{array}{ccc}
x-2 & y-5 & z+3 \\
-2-2 & -3-5 & 5+3 \\
5-2 & 3-5 & -3+3
\end{array}\right|=0 \Rightarrow\left|\begin{array}{rrc}
x-2 & y-5 & z+3 \\
-4 & -8 & 8 \\
3 & -2 & 0
\end{array}\right|=0 . \\
\Rightarrow & (x-2)(0+16)-(y-5)(0-24)+(z+3)(8+24)=0 \\
\Rightarrow & 16(x-2)+24(y-5)+32(z+3)=0 \Rightarrow 16 x+24 y+32 z-56=0 \\
\Rightarrow & 2 x+3 y+4 z-7=0 .
\end{aligned}
$$

Hence, the required equation of the plane is $2 x+3 y+4 z-7=0$.

---

### Example 2:

Show that the four points $A(1,-1,1), B(2,3,1), C(1,2,3)$ and $D(0,-2,3)$ are coplanar. Find the equation of the plane containing them.

#### Solution:

We know that the equation of the plane passing through the points $A\left(x_{1}, y_{1}, z_{1}\right), B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ is given by

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
x_{2}-x_{1} & y_{2}-y_{1} & z_{2}-z_{1} \\
x_{3}-x_{1} & y_{3}-y_{1} & z_{3}-z_{1}
\end{array}\right|=0
$$

Here,

$$
\begin{aligned}
& \left(x_{1}=1, y_{1}=-1, z_{1}=1\right),\left(x_{2}=2, y_{2}=3, z_{2}=1\right) \text { and } \\
& \left(x_{3}=1, y_{3}=2, z_{3}=3\right)
\end{aligned}
$$

$\therefore$ the equation of the plane passing through the points $A, B$ and $C$ is given by

$$
\begin{align*}
& \left|\begin{array}{ccc}
x-1 & y+1 & z-1 \\
2-1 & 3+1 & 1-1 \\
1-1 & 2+1 & 3-1
\end{array}\right|=0 \Rightarrow\left|\begin{array}{ccc}
x-1 & y+1 & z-1 \\
1 & 4 & 0 \\
0 & 3 & 2
\end{array}\right|=0 \\
\Rightarrow & (x-1)(8-0)-(y+1)(2-0)+(z-1)(3-0)=0 \\
\Rightarrow & 8(x-1)-2(y+1)+3(z-1)=0 \Rightarrow 8 x-2 y+3 z=13 . \tag{i}
\end{align*}
$$

Putting $x=0, y=-2$ and $z=3$ in (i), we get

$$
\text { LHS }=(8 \times 0)-2 \times(-2)+3 \times 3=(0+4+9)=13=\text { RHS } .
$$

Thus, the point $D(0,-2,3)$ lies on the plane (i).
Hence, the given four points are coplanar and the equation of the plane containing them is $8 x=2 y+3 z=13$.

---

### Example 3:

Find the equation of the plane which cuts off intercepts 3, 6 and -4 from the axes of coordinates.

#### Solution:

We know that the equation of a plane which cuts off intercepts $a, b, c$ from the $x$-axis, $y$-axis and $z$-axis respectively, is

$$
\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1 .
$$

Here $a=3, b=6$ and $c=-4$.
Hence, the required equation of the plane is

$$
\frac{x}{3}+\frac{y}{6}+\frac{z}{-4}=1 \Rightarrow 4 x+2 y-3 z=12
$$

---

### Example 4:

Reduce the equation of the plane $2 x-3 y+z=6$ to intercept form and find its intercepts on the coordinate axes.

#### Solution:

We have

$$
2 x-3 y+z=6 \Rightarrow \frac{2 x}{6}-\frac{3 y}{6}+\frac{z}{6}=1 \Rightarrow \frac{x}{3}+\frac{y}{-2}+\frac{z}{6}=1 .
$$

Hence, the equation of the given plane in intercept form is $\frac{x}{3}+\frac{y}{-2}+\frac{z}{6}=1$.

The intercepts of the given plane on $x$-axis, $y$-axis and $z$-axis are $3,-2$ and 6 respectively.

---

### Example 5:

A plane meets the coordinate axes in $A, B, C$ such that the centroid of $\triangle A B C$ is $(p, q, r)$. Show that the equation of the plane is $\frac{x}{p}+\frac{y}{q}+\frac{z}{r}=3$.

#### Solution:

Let the required equation of the plane be $\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1$.

Then, clearly the plane meets the coordinate axis at $A(a, 0,0)$, $B(0, b, 0)$ and $C(0,0, c)$.
Since the centroid of $\triangle A B C$ is $G(p, q, r)$, we have

$$
\frac{a+0+0}{3}=p, \frac{0+b+0}{3}=q \text { and } \frac{0+0+c}{3}=r
$$

$\Rightarrow \quad a=3 p, b=3 q$ and $c=3 r$.
Putting these values of $a, b, c$ in (i) we get

$$
\frac{x}{3 p}+\frac{y}{3 q}+\frac{z}{3 r}=1 \Rightarrow \frac{x}{p}+\frac{y}{q}+\frac{z}{r}=3 .
$$

Hence, the required equation of the plane is $\frac{x}{p}+\frac{y}{q}+\frac{z}{r}=3$.

---

### Example 6:

A variable plane moves in such a way that the sum of the reciprocals of its intercepts on the coordinate axes is constant. Show that the plane passes through a fixed point.

#### Solution:

Let the equation of the variable plane be

$$
\begin{equation*}
\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1 . \tag{i}
\end{equation*}
$$

Then, it makes intercepts $a, b, c$ with the coordinate axes.
$\therefore \quad \frac{1}{a}+\frac{1}{b}+\frac{1}{c}=k$, where $k$ is a constant (given)
$\Rightarrow \frac{1}{k a}+\frac{1}{k b}+\frac{1}{k c}=1 \Rightarrow \frac{1}{a}\left(\frac{1}{k}\right)+\frac{1}{b}\left(\frac{1}{k}\right)+\frac{1}{c}\left(\frac{1}{k}\right)=1$
$\Rightarrow\left(\frac{1}{k}, \frac{1}{k}, \frac{1}{k}\right)$ satisfies (i).
Hence, the given plane passes through a fixed point $\left(\frac{1}{k}, \frac{1}{k}, \frac{1}{k}\right)$.

---