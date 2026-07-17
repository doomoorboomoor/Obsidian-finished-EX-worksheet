# Collinearity of Three Given Points

## When the coordinates of Three Points are Given

**THEOREM 1** The condition for three given points $A\left(x_{1}, y_{1}, z_{1}\right)$, $B\left(x_{2}, y_{2}, z_{2}\right)$ and $C\left(x_{3}, y_{3}, z_{3}\right)$ to be collinear is that

$$
\frac{x_{3}-x_{1}}{x_{2}-x_{1}}=\frac{y_{3}-y_{1}}{y_{2}-y_{1}}=\frac{z_{3}-z_{1}}{z_{2}-z_{1}} .
$$

**PROOF** The equations of the line $A B$ are

$$
\begin{equation*}
\frac{x-x_{1}}{x_{2}-x_{1}}=\frac{y-y_{1}}{y_{2}-y_{1}}=\frac{z-z_{1}}{z_{2}-z_{1}} . \tag{i}
\end{equation*}
$$

Clearly, $A, B, C$ will be collinear only when $C$ lies on the line $A B$. This happens when $C\left(x_{3}, y_{3}, z_{3}\right)$ lies on (i).

$$
\therefore \quad \frac{x_{3}-x_{1}}{x_{2}-x_{1}}=\frac{y_{3}-y_{1}}{y_{2}-y_{1}}=\frac{z_{3}-z_{1}}{z_{2}-z_{1}} .
$$

---

## When Position Vectors of Three Points are Given

**THEOREM 2** Three points $A$, $B$ and $C$ with position vectors $\vec{a}$, $\vec{b}$ and $\vec{c}$ respectively are collinear if and only if there exist scalars $d_{1}$, $d_{2}$, $d_{3}$ not all zero such that

$$
d_{1} \vec{a}+d_{2} \vec{b}+d_{3} \vec{c}=\overrightarrow{0} \text { and } d_{1}+d_{2}+d_{3}=0
$$

**PROOF** Let $A$, $B$ and $C$ be three collinear points having position vectors $\vec{a}$, $\vec{b}$ and $\vec{c}$ respectively.

Then, the vector equation of line $\overrightarrow{A B}$ is

$$
\vec{r}=\vec{a}+\lambda(\vec{b}-\vec{a}) \text { for some scalar } \lambda
$$

$\Rightarrow \quad \vec{c}=\vec{a}+\lambda(\vec{b}-\vec{a}) \quad[\because A, B$ and $C$ being collinear, $C$ lies on $A B]$

$\Rightarrow \quad(1-\lambda) \vec{a}+\lambda \vec{b}-\vec{c}=\overrightarrow{0}$

$\Rightarrow \quad d_{1} \vec{a}+d_{2} \vec{b}+d_{3} \vec{c}=\overrightarrow{0}$, where $d_{3}=-1 \neq 0$ and

$$
d_{1}+d_{2}+d_{3}=(1-\lambda)+\lambda-1=0 .
$$

**Conversely,** let $A, B$, and $C$ be the given points having position vectors $\vec{a}$, $\vec{b}$ and $\vec{c}$ respectively and let $d_{1}$, $d_{2}$, $d_{3}$ be scalars, not all zero such that $d_{1} \vec{a}+d_{2} \vec{b}+d_{3} \vec{c}=\overrightarrow{0}$, and $d_{1}+d_{2}+d_{3}=0$.

Let $d_{3} \neq 0$. Then,

$$
\begin{aligned}
& d_{1} \vec{a}+d_{2} \vec{b}+d_{3} \vec{c}=0, \text { and } d_{1}+d_{2}+d_{3}=0 \\
\Rightarrow & \left(\frac{d_{1}}{d_{3}}\right) \vec{a}+\left(\frac{d_{2}}{d_{3}}\right) \vec{b}+\vec{c}=\overrightarrow{0} \text { and }\left(\frac{d_{1}}{d_{3}}\right)+\left(\frac{d_{2}}{d_{3}}\right)+1=0 \\
\Rightarrow & \left(\frac{d_{1}}{d_{3}}\right) \vec{a}-\lambda \vec{b}+\vec{c}=\overrightarrow{0} \text { and }\left(\frac{d_{1}}{d_{3}}\right)-\lambda+1=0, \text { where }\left(\frac{d_{2}}{d_{3}}\right)=-\lambda \\
\Rightarrow & (\lambda-1) \vec{a}-\lambda \vec{b}+\vec{c}=\overrightarrow{0}\left[\because\left(\frac{d_{1}}{d_{3}}\right)=(\lambda-1)\right] \\
\Rightarrow & \vec{c}=(1-\lambda) \vec{a}+\lambda \vec{b}
\end{aligned}
$$

$\Rightarrow \quad$ the point $C$ lies on the line $\overrightarrow{A B}$

$\Rightarrow \quad$ the points $A, B$ and $C$ are collinear.

---

## Solved Examples

### Example 1:

Show that the points $A(2,0,3)$, $B(3,2,-1)$ and $C(1,-2,-5)$ are collinear.

#### Solution:

The equations of the line $A B$ are

$$
\begin{equation*}
\frac{x-2}{3-2}=\frac{y-0}{2-0}=\frac{z-3}{-1-3} \Rightarrow \frac{x-2}{1}=\frac{y}{2}=\frac{z-3}{-4} \tag{i}
\end{equation*}
$$

Putting $x=1, y=-2$ and $z=-5$ in (i), we get

$$
\frac{1-2}{1}=\frac{-2}{2}=\frac{-5-3}{-4}, \text { which is clearly true. }
$$

Thus, the point $C(1,-2,-5)$ satisfies the equation of line $A B$.

$\therefore \quad C$ lies on line $A B$.

Hence, the given points $A, B$ and $C$ are collinear.

---

### Example 2:

Find the value of $\lambda$ for which the points $A(-1,3,2)$, $B(-4,2,-2)$ and $C(5,5, \lambda)$ are collinear.

#### Solution:

The equations of the line $A B$ are

$$
\frac{x+1}{-4+1}=\frac{y-3}{2-3}=\frac{z-2}{-2-2}
$$

$$
\begin{equation*}
\Rightarrow \quad \frac{x+1}{-3}=\frac{y-3}{-1}=\frac{z-2}{-4} . \tag{i}
\end{equation*}
$$

Since the points $A, B$ and $C$ are collinear, so the point $C(5,5, \lambda)$ lies on (i).

$\therefore \quad \frac{5+1}{-3}=\frac{5-3}{-1}=\frac{\lambda-2}{-4} \Rightarrow \frac{\lambda-2}{-4}=-2 \Rightarrow \lambda-2=8 \Rightarrow \lambda=10$.

Hence, the required value of $\lambda$ is 10 .

---

### Example 3:

Show that the points whose position vectors are $(-2 \hat{i}+3 \hat{j}+5 \hat{k})$, $(\hat{i}+2 \hat{j}+3 \hat{k})$ and $(7 \hat{i}-\hat{k})$ are collinear.

#### Solution:

The coordinates of the given points are $A(-2,3,5), B(1,2,3)$ and $C(7,0,-1)$.
The equations of line $A B$ are

$$
\begin{equation*}
\frac{x+2}{1+2}=\frac{y-3}{2-3}=\frac{z-5}{3-5} \Rightarrow \frac{x+2}{3}=\frac{y-3}{-1}=\frac{z-5}{-2} . \tag{i}
\end{equation*}
$$

Putting $x=7, y=0$ and $z=-1$ in (i), we get

$$
\frac{7+2}{3}=\frac{0-3}{-1}=\frac{-1-5}{-2}, \text { which is clearly true. }
$$

Thus, the point $C(7,0,-1)$ satisfies the equation of line $A B$.

$\therefore \quad C$ lies on line $A B$.

Hence, the given points $A, B$ and $C$ are collinear.

---

### Example 4:

Using the vector method, find the values of $\lambda$ and $\mu$ for which the points $A(3, \lambda, \mu), B(2,0,-3)$ and $C(1,-2,-5)$ are collinear.

#### Solution:

Let $\vec{a}, \vec{b}$ and $\vec{c}$ be the position vectors of the given points $A, B$ and $C$ respectively. Then,

$$
\vec{a}=3 \hat{i}+\lambda \hat{j}+\mu \hat{k}, \vec{b}=2 \hat{i}-3 \hat{k} \text { and } \vec{c}=\hat{i}-2 \hat{j}-5 \hat{k} .
$$

Now, the vector equation of the line $B C$ is given by

$$
\begin{aligned}
& \vec{r}=\vec{b}+\alpha(\vec{c}-\vec{b}) \text { for some scalar } \alpha \\
\Rightarrow & \vec{r}=(1-\alpha) \vec{b}+\alpha \vec{c} \\
\Rightarrow & \vec{r}=(1-\alpha)(2 \hat{i}-3 \hat{k})+\alpha(\hat{i}-2 \hat{j}-5 \hat{k}) \\
\Rightarrow & \vec{r}=(2-2 \alpha+\alpha) \hat{i}-2 \alpha \hat{j}+(-3+3 \alpha-5 \alpha) \hat{k} \\
\Rightarrow & \vec{r}=(2-\alpha) \hat{i}-2 \alpha \hat{j}+(-3-2 \alpha) \hat{k} .
\end{aligned}
$$

If this line passes through the point $A$ then we must have

$$
\begin{aligned}
& 3 \hat{i}+\lambda \hat{j}+\mu \hat{k}=(2-\alpha) \hat{i}-2 \alpha \hat{j}+(-3-2 \alpha) \hat{k} \\
\Leftrightarrow & 2-\alpha=3,-2 \alpha=\lambda \text { and }-3-2 \alpha=\mu \\
\Leftrightarrow & \alpha=-1, \lambda=2 \text { and } \mu=(-3+2)=-1
\end{aligned}
$$

Hence, $\lambda=2$ and $\mu=-1$.

---