## 6. Tangents and Normals

## Some Important Theorems

**THEOREM 1** Prove that the equation of a tangent to a curve $y=f(x)$ at a point $P(x_{1}, y_{1})$ is given by $\frac{y-y_{1}}{x-x_{1}}=\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}$, where $\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}$ denotes the value of $\frac{d y}{d x}$ at $x=x_{1}$ and $y=y_{1}$, and the equation of the normal at $P(x_{1}, y_{1})$ is given by

$$
\frac{y-y_{1}}{x-x_{1}}=\frac{-1}{\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}} .
$$

**PROOF** We know that the slope of the tangent to the curve $y=f(x)$ at a point $P(x_{1}, y_{1})$ is $\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}$.
Thus, the tangent to the given curve at a point $P$ is a line passing through $(x_{1}, y_{1})$ with a slope of $\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}$.
So, the equation of the tangent at $P$ is $\frac{y-y_{1}}{x-x_{1}}=\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}$.
Again, the normal to the given curve at $P$ is a line perpendicular to the tangent at $P$.
So, the slope of the normal is $\frac{-1}{\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}}$.
Also, the normal at $P$ passes through $(x_{1}, y_{1})$.
So, the equation of the normal at $P$ is $\frac{y-y_{1}}{x-x_{1}}=\frac{-1}{\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}}$.

**THEOREM 2** The tangent to a curve $y=f(x)$ at a point $P(x_{1}, y_{1})$ is parallel to the $x$-axis if and only if $\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=0$.

**PROOF** The tangent is parallel to the $x$-axis $\Leftrightarrow$ its slope is 0

$$
\Leftrightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=0 .
$$

**THEOREM 3** The tangent to a curve $y=f(x)$ at a point $P(x_{1}, y_{1})$ is parallel to the $y$-axis if and only if $\left(\frac{d x}{d y}\right)_{\left(x_{1}, y_{1}\right)}=0$.

**PROOF** The tangent is parallel to the $y$-axis

$$
\Leftrightarrow \text { its slope is } 90^{\circ} \Leftrightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\tan 90^{\circ}=\infty \Leftrightarrow\left(\frac{d x}{d y}\right)_{\left(x_{1}, y_{1}\right)}=0 .
$$

**REMARK** If $x=f(t)$ and $y=g(t)$, where $f^{\prime}(t) \neq 0$ then
- (i) equation of the tangent at '$t$' is $\frac{y-g(t)}{x-f(t)}=\frac{g^{\prime}(t)}{f^{\prime}(t)}$
- and, (ii) equation of the normal at '$t$' is $\frac{y-g(t)}{x-f(t)}=-\frac{f^{\prime}(t)}{g^{\prime}(t)}$.

---
## SOLVED EXAMPLES

### Example: 1

Find the equations of the tangent and the normal to the curve

$$
y=x^{4}-6 x^{3}+13 x^{2}-10 x+5 \text { at the point }(1,3) .
$$

#### Solution:

The equation of the given curve is $y=x^{4}-6 x^{3}+13 x^{2}-10 x+5$.
$\therefore \frac{d y}{d x}=4 x^{3}-18 x^{2}+26 x-10$.
So, $\left(\frac{d y}{d x}\right)_{(1,3)}=(4 \times 1^{3}-18 \times 1^{2}+26 \times 1-10)=2$.
$\therefore$ the required equation of the tangent is

$$
\frac{y-3}{x-1}=2 \text { or } 2 x-y+1=0 .
$$

And, the required equation of the normal is

$$
\frac{y-3}{x-1}=\frac{-1}{2} \text { or } x+2 y-7=0 .
$$

---
### Example: 2

Find the equations of the tangent and the normal to the curve $y=x^{2}+4 x+1$ at the point where $x=3$.

#### Solution:

When $x=3$, we have $y=(3^{2}+4 \times 3+1)=22$.
So, the point of contact is $(3,22)$.
Now, $y=x^{2}+4 x+1 \Rightarrow \frac{d y}{d x}=2 x+4 \Rightarrow\left(\frac{d y}{d x}\right)_{(3,22)}=(2 \times 3+4)=10$.
Equation of the tangent is $\frac{y-22}{x-30}=10 \Rightarrow 10 x-y-278=0$.
And, equation of the normal is $\frac{y-22}{x-3}=\frac{-1}{10} \Rightarrow x+10 y-223=0$.

---
### Example: 3

Show that the equation of the tangent to the ellipse

$$
\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \text { at }\left(x_{1}, y_{1}\right) \text { is } \frac{x x_{1}}{a^{2}}+\frac{y y_{1}}{b^{2}}=1 .
$$

#### Solution:

$\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \Rightarrow \frac{2 x}{a^{2}}+\frac{2 y}{b^{2}} \cdot \frac{d y}{d x}=0$ [on differentiating w.r.t. $x$]

$$
\frac{d y}{d x}=\frac{-b^{2} x}{a^{2} y} \Rightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\frac{-b^{2} x_{1}}{a^{2} y_{1}} .
$$

So, the equation of the tangent at $(x_{1}, y_{1})$ is

$$
\frac{y-y_{1}}{x-x_{1}}=\frac{-b^{2} x_{1}}{a^{2} y_{1}} \Rightarrow b^{2} x x_{1}+a^{2} y y_{1}=b^{2} x_{1}^{2}+a^{2} y_{1}^{2} .
$$

On dividing throughout by $a^{2} b^{2}$, we get $\frac{x x_{1}}{a^{2}}+\frac{y y_{1}}{b^{2}}=\frac{x_{1}^{2}}{a^{2}}+\frac{y_{1}^{2}}{b^{2}}$, i.e., $\frac{x x_{1}}{a^{2}}+\frac{y y_{1}}{b^{2}}=1$ $[\because(x_{1}, y_{1})$ lies on $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \Rightarrow \frac{x_{1}^{2}}{a^{2}}+\frac{y_{1}^{2}}{b^{2}}=1]$.

---
### Example: 4

Find the equation of the tangent to the curve $y=\sqrt{5 x-3}-2$, which is parallel to the line $4 x-2 y+3=0$.
[CBSE 2005, '13C]

#### Solution:

The given line is $4 x-2 y+3=0$ or $y=2 x+\frac{3}{2}$.
$\therefore$ slope of the given line $=2$
So, the slope of the tangent $=2$.
Let the point of contact be $(x_{1}, y_{1})$.
Now, $y=\sqrt{5 x-3}-2 \Rightarrow \frac{d y}{d x}=\frac{5}{2 \cdot \sqrt{5 x-3}}$

$$
\Rightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\frac{5}{2 \cdot \sqrt{5 x_{1}-3}} .
$$

$\therefore \frac{5}{2 \cdot \sqrt{5 x_{1}-3}}=2 \Rightarrow \frac{25}{4(5 x_{1}-3)}=4$, i.e., $x_{1}=\frac{73}{80}$.
$\therefore y_{1}=\sqrt{5 x_{1}-3}-2=\sqrt{(5 \times \frac{73}{80}-3)}-2=\frac{-3}{4}$.
So, the point of contact is $(\frac{73}{80}, \frac{-3}{4})$.
Hence, the required equation of the tangent is $\frac{(y+\frac{3}{4})}{(x-\frac{73}{80})}=2$,
i.e., $80 x-40 y-103=0$.

---
### Example: 5

Find the equations of the normals to the curve $3 x^{2}-y^{2}=8$, parallel to the line $x+3 y=4$.

#### Solution:

The given line is $x+3 y=4$ or $y=-\frac{1}{3} x+\frac{4}{3}$.
$\therefore$ slope of the given line $=-\frac{1}{3}$
So, the slope of the required normal $=-\frac{1}{3}$

Let the point of contact be $(x_{1}, y_{1})$.

Now, $3 x^{2}-y^{2}=8 \Rightarrow 6 x-2 y \cdot \frac{d y}{d x}=0$ [on differentiating w.r.t. $x$]

$$
\Rightarrow \frac{d y}{d x}=\frac{3 x}{y} \Rightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\frac{3 x_{1}}{y_{1}} . \tag{ii}
$$

$\therefore$ slope of the normal $=\frac{-1}{\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}}=\frac{-y_{1}}{3 x_{1}}$

Thus, from (i) and (ii) we get $\frac{-y_{1}}{3 x_{1}}=-\frac{1}{3} \Rightarrow y_{1}=x_{1}$.
Also, since $(x_{1}, y_{1})$ lies on the given curve, we have

$$
3 x_{1}^{2}-y_{1}^{2}=8 \text { or } 3 x_{1}^{2}-x_{1}^{2}=8 \quad[\because \quad y_{1}=x_{1}]
$$

or $x_{1}^{2}=4$ or $x_{1}= \pm 2$
$\therefore y_{1}= \pm 2 \quad[\because y_{1}=x_{1}]$.
Thus, the points of contact are $(2,2)$ and $(-2,-2)$.
So, the equation of the required normal at $(2,2)$ is $\frac{y-2}{x-2}=\frac{-1}{3}$, i.e., $x+3 y-8=0$.
The equation of the required normal at $(-2,-2)$ is $\frac{y+2}{x+2}=\frac{-1}{3}$, i.e., $x+3 y+8=0$.

---
### Example: 6

Prove that the curve $(\frac{x}{a})^{n}+(\frac{y}{b})^{n}=2$ touches the straight line $\frac{x}{a}+\frac{y}{b}=2$ at the point $(a, b)$, whatever be the value of $n$.
[CBSE 2007C]

#### Solution:

The equation of the curve is $(\frac{x}{a})^{n}+(\frac{y}{b})^{n}=2$.
On differentiating w.r.t. $x$, we get $n \cdot(\frac{x}{a})^{n-1} \cdot \frac{1}{a}+n \cdot(\frac{y}{b})^{n-1} \cdot \frac{1}{b} \cdot \frac{d y}{d x}=0$
$\Rightarrow \frac{n x^{n-1}}{a^{n}}+\frac{n y^{n-1}}{b^{n}} \cdot \frac{d y}{d x}=0 \Rightarrow \frac{d y}{d x}=-\frac{b^{n} x^{n-1}}{a^{n} y^{n-1}}$.
$\therefore\left(\frac{d y}{d x}\right)_{(a, b)}=\frac{-b^{n} a^{n-1}}{a^{n} b^{n-1}}=-\frac{b}{a}$.
So, the equation of the tangent at $(a, b)$ is $\frac{y-b}{x-a}=\frac{-b}{a}$,
i.e., $a y+b x=2 a b$.
$\therefore \frac{x}{a}+\frac{y}{b}=2$, which is independent of $n$.

---
### Example: 7

At what points will the tangent to the curve $y=2 x^{3}-15 x^{2}+36 x-21$ be parallel to the $x$-axis? Also, find the equations of tangents to the curve at these points.
[CBSE 2008]

#### Solution:

Let the required point be $P(x_{1}, y_{1})$.
Then, $\left[\frac{d y}{d x}\right]_{\left(x_{1}, y_{1}\right)}=0$.
Now, $y=2 x^{3}-15 x^{2}+36 x-21$
$\Rightarrow \frac{d y}{d x}=6 x^{2}-30 x+36=6(x^{2}-5 x+6)$
$\Rightarrow\left[\frac{d y}{d x}\right]_{\left(x_{1}, y_{1}\right)}=6(x_{1}^{2}-5 x_{1}+6)$.
$\therefore\left[\frac{d y}{d x}\right]_{\left(x_{1}, y_{1}\right)}=0 \Rightarrow 6(x_{1}^{2}-5 x_{1}+6)=0$
$\Rightarrow x_{1}^{2}-5 x_{1}+6=0$
$\Rightarrow(x_{1}-2)(x_{1}-3)=0 \Rightarrow x_{1}=2$ or $x_{1}=3$.
Since $P(x_{1}, y_{1})$ lies on the given curve, we have

$$
y_{1}=2 x_{1}^{3}-15 x_{1}^{2}+36 x_{1}-21 .
$$

$$
\therefore \begin{aligned}
& x_{1}=2 \Rightarrow y_{1}=(2 \times 8-15 \times 4+36 \times 2-21)=7 . \\
& x_{1}=3 \Rightarrow y_{1}=(2 \times 27-15 \times 9+36 \times 3-21)=6 .
\end{aligned}
$$

So, the required points are $P(2,7)$ and $P^{\prime}(3,6)$.
The equations of tangents at these points are $y=7$ and $y=6$ respectively.

---
### Example: 8

Prove that all points of the curve $y^{2}=4 a[x+a \sin \frac{x}{a}]$ at which the tangent is parallel to the axis of $x$, lie on a parabola.

#### Solution:

Let the required point be $(x_{1}, y_{1})$.
Then, we must have $\left(\frac{d y}{d x}\right)_{(x_{1}, y_{1})}=0$.
Now, $y^{2}=4 a[x+a \sin \frac{x}{a}] \Rightarrow 2 y \cdot \frac{d y}{d x}=4 a[1+\cos \frac{x}{a}]$

$$
\Rightarrow \frac{d y}{d x}=\frac{2 a[1+\cos \frac{x}{a}]}{y} \Rightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\frac{2 a[1+\cos \frac{x_{1}}{a}]}{y_{1}} .
$$

$\therefore\left(\frac{d y}{d x}\right)_{(x_{1}, y_{1})}=0 \Rightarrow \frac{2 a[1+\cos \frac{x_{1}}{a}]}{y_{1}}=0 \Rightarrow[1+\cos \frac{x_{1}}{a}]=0$

$$
\Rightarrow \cos \frac{x_{1}}{a}=-1 \Rightarrow \sin \frac{x_{1}}{a}=\sqrt{1-\cos ^{2} \frac{x_{1}}{a}}=0 .
$$

But, $(x_{1}, y_{1})$ lies on the given curve.
$\therefore y_{1}^{2}=4 a[x_{1}+a \sin \frac{x_{1}}{a}] \Rightarrow y_{1}^{2}=4 a x_{1} \quad[\because \sin \frac{x_{1}}{a}=0]$.
This shows that $(x_{1}, y_{1})$ lies on the parabola $y^{2}=4 a x$.

---
### Example: 9

Tangents are drawn from the origin to the curve $y=\sin x$. Prove that their points of contact lie on the curve $x^{2} y^{2}=(x^{2}-y^{2})$.

#### Solution:

Let the point of contact be $(x_{1}, y_{1})$.
Now, $y=\sin x \Rightarrow \frac{d y}{d x}=\cos x \Rightarrow\left(\frac{d y}{d x}\right)_{(x_{1}, y_{1})}=\cos x_{1}$.
$\therefore$ the equation of the tangent at $(x_{1}, y_{1})$ is $\frac{y-y_{1}}{x-x_{1}}=\cos x_{1}$.
Since the tangent passes through the origin, we have $\frac{-y_{1}}{-x_{1}}=\cos x_{1}$,
i.e., $\frac{y_{1}}{x_{1}}=\cos x_{1}$ (i)

But, $(x_{1}, y_{1})$ lies on the curve $y=\sin x$.

$$
\therefore \quad y_{1}=\sin x_{1} \tag{ii}
$$

Squaring (i) and (ii) and adding, we get

$$
\begin{aligned}
\frac{y_{1}^{2}}{x_{1}^{2}}+y_{1}^{2}=1 & \Rightarrow y_{1}^{2}+x_{1}^{2} y_{1}^{2}=x_{1}^{2} \\
& \Rightarrow x_{1}^{2} y_{1}^{2}=(x_{1}^{2}-y_{1}^{2})
\end{aligned}
$$

This shows that $(x_{1}, y_{1})$ lies on the curve $x^{2} y^{2}=(x^{2}-y^{2})$.

---
### Example: 10

Determine the points on the curve $2 y=(3-x^{2})$ at which the tangent is parallel to the line $x+y=0$.

#### Solution:

Let the required point be $(x_{1}, y_{1})$.
Then, slope of the tangent at $\left(\begin{array}{ll}x_{1} & y_{1}\end{array}\right)=$ slope of the given line.
$\therefore\left(\frac{d y}{d x}\right)_{(x_{1}, y_{1})}=-1 \quad[\because x+y=0 \Rightarrow y=-x]$.
Now, $2 y=(3-x^{2}) \Rightarrow 2 \cdot \frac{d y}{d x}=-2 x \Rightarrow \frac{d y}{d x}=-x \Rightarrow\left(\frac{d y}{d x}\right)_{(x_{1}, y_{1})}=-x_{1}$.
$\therefore-x_{1}=-1 \Rightarrow x_{1}=1$.
Since $(x_{1}, y_{1})$ lies on the curve $2 y=(3-x^{2})$, we have $2 y_{1}=(3-x_{1}^{2})$.
When $x_{1}=1$, we have $y_{1}=(\frac{3-1^{2}}{2})=1$.
Hence, the required point is $(1,1)$.

---
### Example: 11

Find the points on the curve $4 x^{2}+9 y^{2}=1$, where the tangents are perpendicular to the line $2 y+x=0$.

#### Solution:

The equation of the given line is $y=-\frac{1}{2} x$.

$$
\therefore \quad \text { slope of this line }=-\frac{1}{2} \tag{i}
$$

Let the required point be $(x_{1}, y_{1})$.

Now, $4 x^{2}+9 y^{2}=1 \Rightarrow 8 x+18 y \cdot \frac{d y}{d x}=0$

$$
\Rightarrow \frac{d y}{d x}=\left(\frac{-4 x}{9 y}\right) \Rightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\frac{-4 x_{1}}{9 y_{1}} . \tag{ii}
$$

$\therefore$ slope of the tangent at $(x_{1}, y_{1})=\frac{-4 x_{1}}{9 y_{1}}$

From (i) and (ii), we have $\frac{-4 x_{1}}{9 y_{1}} \times(-\frac{1}{2})=-1$ or $y_{1}=-\frac{2}{9} x_{1}$ (iii)

Since $(x_{1}, y_{1})$ lies on the curve $4 x^{2}+9 y^{2}=1$, we have

$$
4 x_{1}^{2}+9 y_{1}^{2}=1 \Rightarrow 4 x_{1}^{2}+9 \times \frac{4}{81} x_{1}^{2}=1 \quad[\text { using (iii) }]
$$

$\therefore x_{1}^{2}=\frac{9}{40}$ or $x_{1}= \pm \frac{3}{2 \sqrt{10}}$.
So, $y_{1}= \pm \frac{2}{9} \times \frac{3}{2 \sqrt{10}}= \pm \frac{1}{3 \sqrt{10}}$.
Hence, the required points are

$$
\left(\frac{3}{2 \sqrt{10}}, \frac{1}{3 \sqrt{10}}\right) \text { and }\left(\frac{-3}{2 \sqrt{10}}, \frac{-1}{3 \sqrt{10}}\right) .
$$

---

### Example: 12

Find the coordinates of the points on the curve $y=x^{2}+3 x+4$, the tangents at which pass through the origin.

#### Solution:

Let the required point be $(x_{1}, y_{1})$.
Now, $y=x^{2}+3 x+4 \Rightarrow \frac{d y}{d x}=2 x+3 \Rightarrow\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=(2 x_{1}+3)$.
So, the equation of the tangent at $(x_{1}, y_{1})$ is $\frac{y-y_{1}}{x-x_{1}}=(2 x_{1}+3)$.
Since the tangent passes through the origin, we have

$$
\begin{align*}
\frac{-y_{1}}{-x_{1}} & =(2 x_{1}+3) \\
\Rightarrow y_{1} & =(2 x_{1}^{2}+3 x_{1}) \tag{i}
\end{align*}
$$

But, $(x_{1}, y_{1})$ lies on the given curve. So, $y_{1}=x_{1}^{2}+3 x_{1}+4$ (ii)

From (i) and (ii), we get

$$
2 x_{1}^{2}+3 x_{1}=x_{1}^{2}+3 x_{1}+4 \text { or } x_{1}^{2}=4 \text { or } x_{1}= \pm 2 .
$$

Now, $x_{1}=2 \Rightarrow y_{1}=(2^{2}+3 \times 2+4)=14$.
And, $x_{1}=-2 \Rightarrow y_{1}=[(-2)^{2}+3 \times(-2)+4]=2$.
Hence, the required points are $(2,14)$ and $(-2,2)$.

---
### Example: 13

If the straight line $x \cos \alpha+y \sin \alpha=p$ touches the ellipse $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$, prove that $p^{2}=a^{2} \cos ^{2} \alpha+b^{2} \sin ^{2} \alpha$.

#### Solution:

Let the point of contact be $(x_{1}, y_{1})$.
Then, the equation of the tangent at $(x_{1}, y_{1})$ is $\frac{x x_{1}}{a^{2}}+\frac{y y_{1}}{b^{2}}=1$ (i)

This is identical with $x \cos \alpha+y \sin \alpha=p$ (ii)

Comparing coefficients, we have $\frac{(x_{1} / a^{2})}{\cos \alpha}=\frac{(y_{1} / b^{2})}{\sin \alpha}=\frac{1}{p}$

$$
\Rightarrow \quad \frac{(x_{1} / a)}{a \cos \alpha}=\frac{(y_{1} / b)}{b \sin \alpha}=\frac{1}{p} .
$$

$\therefore \frac{x_{1}}{a}=\frac{a \cos \alpha}{p}$ and $\frac{y_{1}}{b}=\frac{b \sin \alpha}{p}$.
Squaring and adding, we get $\frac{x_{1}^{2}}{a^{2}}+\frac{y_{1}^{2}}{b^{2}}=\frac{a^{2} \cos ^{2} \alpha+b^{2} \sin ^{2} \alpha}{p^{2}}$

$$
\begin{aligned}
& \Rightarrow \quad \frac{a^{2} \cos ^{2} \alpha+b^{2} \sin ^{2} \alpha}{p^{2}}=1\left[\because \frac{x_{1}^{2}}{a^{2}}+\frac{y_{1}^{2}}{b^{2}}=1\right] \\
& \Rightarrow \quad a^{2} \cos ^{2} \alpha+b^{2} \sin ^{2} \alpha=p^{2} .
\end{aligned}
$$

---
### Example: 14

If $x \cos \alpha+y \sin \alpha=p$ touches the curve $x^{m} y^{n}=a^{m+n}$, prove that

$$
p^{m+n} \cdot m^{m} \cdot n^{n}=(m+n)^{m+n} \cos ^{m} \alpha \sin ^{n} \alpha .
$$

#### Solution:

Let the point of contact be $(x_{1}, y_{1})$.
The equation of the given curve is $x^{m} y^{n}=a^{m+n}$.
This, on differentiation, gives

$$
\begin{aligned}
& \quad m x^{m-1} y^{n}+x^{m} \cdot n y^{n-1} \cdot \frac{d y}{d x}=0 \Rightarrow \frac{d y}{d x}=\frac{-m y}{n x} . \\
& \therefore\left(\frac{d y}{d x}\right)_{\left(x_{1}, y_{1}\right)}=\frac{-m y_{1}}{n x_{1}} .
\end{aligned}
$$

So, the equation of the tangent at $(x_{1}, y_{1})$ is $\frac{y-y_{1}}{x-x_{1}}=\frac{-m y_{1}}{n x_{1}}$,
i.e., $m y_{1} x+n x_{1} y=(m+n) x_{1} y_{1}$ (i)

This is identical with $x \cos \alpha+y \sin \alpha=p$ (ii)

Comparing coefficients, we get $\frac{m y_{1}}{\cos \alpha}=\frac{n x_{1}}{\sin \alpha}=\frac{(m+n) x_{1} y_{1}}{p}$.
$\therefore x_{1}=\frac{p m}{(m+n) \cos \alpha}$ and $y_{1}=\frac{p n}{(m+n) \sin \alpha}$.
Since $(x_{1}, y_{1})$ lies on the given curve, $x_{1}^{m} y_{1}^{n}=a^{m+n}$.
$\therefore\left\{\frac{p m}{(m+n) \cos \alpha}\right\}^{m} \cdot\left\{\frac{p n}{(m+n) \sin \alpha}\right\}^{n}=a^{m+n}$
or $p^{m+n} \cdot m^{m} \cdot n^{n}=(m+n)^{m+n} \cdot a^{m+n} \cos ^{m} \alpha \sin ^{n} \alpha$.

---
### Example: 15

Find the equation of the normal to the curve $y=2 \sin ^{2} 3 x$ at $x=\frac{\pi}{6}$.

#### Solution:

When $x=\frac{\pi}{6}$, we have $y=2 \sin ^{2}(\frac{3 \pi}{6})=2$.
So, the point of contact is $(\frac{\pi}{6}, 2)$.
Now, $y=2 \sin ^{2} 3 x \Rightarrow \frac{d y}{d x}=(4 \sin 3 x) \times 3 \times(\cos 3 x)$

$$
\Rightarrow \frac{d y}{d x}=12 \sin 3 x \cos 3 x=6 \sin 6 x .
$$

$\therefore\left(\frac{d y}{d x}\right)$ at $(x=\frac{\pi}{6})=6 \sin (6 \times \frac{\pi}{6})=6 \sin \pi=0$.
So, the tangent is parallel to the $x$-axis.
Thus, the normal is parallel to the $y$-axis and passes through the point $(\frac{\pi}{6}, 2)$.

So, the equation of the normal is $x=\frac{\pi}{6}$.

---
### Example: 16

Find the equations of the tangent and the normal to the curve $y(x-2)(x-3)-x+7=0$ at the point where it cuts the $x$-axis.
[CBSE 2010]

#### Solution:

The curve cuts the $x$-axis, where $y=0$.
Putting $y=0$ in the given equation, we get $x=7$.
$\therefore$ the point of contact is $(7,0)$.
Now, $y(x-2)(x-3)-x+7=0 \Rightarrow y(x^{2}-5 x+6)-x+7=0$
$\Rightarrow(x^{2}-5 x+6) \cdot \frac{d y}{d x}+y(2 x-5)-1=0 \Rightarrow \frac{d y}{d x}=\frac{1+5 y-2 x y}{x^{2}-5 x+6}$.
$\therefore\left(\frac{d y}{d x}\right)_{(7,0)}=(\frac{1+5 \times 0-2 \times 7 \times 0}{49-35+6})=\frac{1}{20}$.
So, the equation of the tangent is $\frac{y-0}{x-7}=\frac{1}{20}$ or $x-20 y-7=0$.
Also, the equation of the normal is $\frac{y-0}{x-7}=-20$ or $20 x+y-140=0$.

---
### Example: 17

Show that $\frac{x}{a}+\frac{y}{b}=1$ touches the curve $y=b e^{-x / a}$ at the point where the curve crosses the axis of $y$.
[CBSE 2005C, '07C]

#### Solution:

The equation of the curve is $y=b e^{-x / a}$.
It crosses the $y$-axis at the point where $x=0$.
Putting $x=0$ in the equation of the curve, we get $y=b$.
So, the point of contact is $(0, b)$.
Now, $y=b e^{-x / a} \Rightarrow \frac{d y}{d x}=\frac{-b e^{-x / a}}{a}$.
$\therefore \left(\frac{d y}{d x}\right)_{(0, b)}=-\frac{b}{a}$.
So, the equation of the tangent is

$$
\frac{y-b}{x-0}=\frac{-b}{a} \Rightarrow b x+a y=a b \Rightarrow \frac{x}{a}+\frac{y}{b}=1
$$

Hence, $\frac{x}{a}+\frac{y}{b}=1$ touches the curve $y=b e^{-x / a}$ at $(0, b)$.

---
### Example: 18

Find the equations of the tangent and the normal at the point '$t$' on the curve $x=a \sin ^{3} t, y=b \cos ^{3} t$.
[CBSE 2009C, '14]

#### Solution:

We have $\frac{d x}{d t}=3 a \sin ^{2} t \cos t$ and $\frac{d y}{d t}=-3 b \cos ^{2} t \sin t$.
$\therefore \frac{d y}{d x}=\frac{d y / d t}{d x / d t}=\frac{-3 b \cos ^{2} t \sin t}{3 a \sin ^{2} t \cos t}=\frac{-b \cos t}{a \sin t}$.
$\therefore$ the equation of the tangent at the point '$t$' is

$$
\frac{y-b \cos ^{3} t}{x-a \sin ^{3} t}=\frac{-b \cos t}{a \sin t}
$$

$\Rightarrow a y \sin t+b x \cos t=a b \sin t \cos t$
$\Rightarrow \frac{x}{a \sin t}+\frac{y}{b \cos t}=1$ [on dividing throughout by $a b \sin t \cos t$].
Also, the equation of the normal at the point '$t$' is

$$
\begin{aligned}
& \frac{y-b \cos ^{3} t}{x-a \sin ^{3} t}=\frac{a \sin t}{b \cos t} \\
\Rightarrow & a x \sin t-b y \cos t=(a^{2} \sin ^{4} t-b^{2} \cos ^{4} t)
\end{aligned}
$$

---
### Example: 19

Find the equations of the tangent and normal to the curve

$$
x=a \sin 3 t, y=\cos 2 t a t t=\frac{\pi}{4} .
$$

[CBSE 2008]

#### Solution:

We have
$x=\sin 3 t \Rightarrow \frac{d x}{d t}=3 \cos 3 t$
and $y=\cos 2 t \Rightarrow \frac{d y}{d t}=-2 \sin 2 t$
$\therefore \frac{d y}{d x}=\frac{(d y / d t)}{(d x / d t)}=\frac{-2 \sin 2 t}{3 \cos 3 t}$
$\Rightarrow \left[\frac{d y}{d x}\right]_{t=\frac{\pi}{4}}=\frac{-2 \sin (2 \times \frac{\pi}{4})}{3 \cos (3 \times \frac{\pi}{4})}=\frac{-2 \sin (\pi / 2)}{-3 \cos (\pi / 4)}=\frac{2 \sqrt{2}}{3}$.

When $t=\frac{\pi}{4}$, we have $x=\sin \frac{3 \pi}{4}=\sin (\pi-\frac{\pi}{4})=\sin \frac{\pi}{4}=\frac{1}{\sqrt{2}}$
and $y=\cos \frac{2 \pi}{4}=\cos \frac{\pi}{2}=0$.

$\therefore$ point of contact is $P(\frac{1}{\sqrt{2}}, 0)$.
Equation of the tangent at the point $P$ is given by

$$
\begin{aligned}
& \frac{y-0}{x-\frac{1}{\sqrt{2}}}=\frac{2 \sqrt{2}}{3} \\
\Rightarrow & \frac{\sqrt{2} y}{\sqrt{2} x-1}=\frac{2 \sqrt{2}}{3} \\
\Rightarrow & 3 \sqrt{2} y=4 x-2 \sqrt{2} \\
\Rightarrow & 2 \sqrt{2} x-3 y-2=0
\end{aligned}
$$

Equation of the normal at the point $P$ is given by

$$
\begin{aligned}
& \frac{y-0}{x-\frac{1}{\sqrt{2}}}=\frac{-3}{2 \sqrt{2}} \Rightarrow \frac{\sqrt{2} y}{\sqrt{2} x-1}=\frac{-3}{2 \sqrt{2}} \\
\Rightarrow & 4 y=-3 \sqrt{2} x+3 \Rightarrow 3 \sqrt{2} x+4 y-3=0 .
\end{aligned}
$$

---
### Example: 20

For the curve $y=4 x^{3}-2 x^{5}$, find all the points on the curve at which the tangent passes through the origin.
[CBSE 2013C]

#### Solution:

The equation of the given curve is

$$
y=4 x^{3}-2 x^{5} . \tag{i}
$$

On differentiating (i) w.r.t. $x$, we get

$$
\frac{d y}{d x}=12 x^{2}-10 x^{4}
$$

Let the required point be $P(x, y)$.
The equation of tangent to the given curve at $P(x, y)$ is given by

$$
Y-y=(12 x^{2}-10 x^{4})(X-x) \tag{ii}
$$

If it passes through $(0,0)$ then, we have

$$
\begins
& y=(12 x^{2}-10 x^{4}) x \\
\Rightarrow & 4 x^{3}-2 x^{5}=12 x^{3}-10 x^{5} \quad [\text { using (i)}] \\
\Rightarrow & 8 x^{3}-8 x^{5}=0 \Rightarrow 8 x^{3}(1-x^{2})=0 \\
\Rightarrow & x=0 \text { or } x=1 \text { or } x=-1
\ends
$$

Putting $x=0$ in (i), we get $y=0$.
Putting $x=1$ in (i), we get $y=2$.
Putting $x=-1$ in (i), we get $y=-2$.
So, the required points are $(0,0),(1,2)$ and $(-1,-2)$.

---