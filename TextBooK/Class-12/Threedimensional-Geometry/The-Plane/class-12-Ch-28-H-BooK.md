## Equation of a Plane Passing through a Given Point and Parallel to Two Given Lines

## Vector Form

> **THEOREM 1** The vector equation of a plane passing through a given point with position vector $\vec{a}$ and parallel to two given vectors $\vec{b}$ and $\vec{c}$ is $(\vec{r}-\vec{a}) \cdot(\vec{b} \times \vec{c})=0$.

#### Proof:

The required plane is parallel to vectors $\vec{b}$ and $\vec{c}$.
So, the vector $\vec{n}=(\vec{b} \times \vec{c})$ is **perpendicular** to this plane.
Thus, we have to find the equation of a plane passing through the point with position vector $\vec{a}$ and perpendicular to the vector $\vec{n}$.
So, its equation is

$$
(\vec{r}-\vec{a}) \cdot \vec{n}=0 \text {, i.e., }(\vec{r}-\vec{a}) \cdot(\vec{b} \times \vec{c})=0 \text {. }
$$

Hence, the required equation of the plane is $(\vec{r}-\vec{a}) \cdot(\vec{b} \times \vec{c})=0$.

---

## Cartesian Form

> **THEOREM 2** The equation of the plane passing through a given point $A\left(x_{1}, y_{1}, z_{1}\right)$ and parallel to two given lines having direction ratios $b_{1}, b_{2}, b_{3}$ and $c_{1}, c_{2}, c_{3}$ is
>
> $$
> \left|\begin{array}{ccc}
> x-x_{1} & y-y_{1} & z-z_{1} \\
> b_{1} & b_{2} & b_{3} \\
> c_{1} & c_{2} & c_{3}
> \end{array}\right|=0 .
> $$

#### Proof:

Let us consider a plane passing through a given point $A\left(x_{1}, y_{1}, z_{1}\right)$ and parallel to two given lines having direction ratios $b_{1}, b_{2}, b_{3}$ and $c_{1}, c_{2}, c_{3}$.

Let $P(x, y, z)$ be an arbitrary point on the plane. Then,

$$
\begin{aligned}
\overrightarrow{A P} & =(\text { p.v. of } P)-(\text { p.v. of } A) \\
& =(x \hat{i}+y \hat{j}+z \hat{k})-\left(x_{1} \hat{i}+y_{1} \hat{j}+z_{1} \hat{k}\right) \\
& =\left(x-x_{1}\right) \hat{i}+\left(y-y_{1}\right) \hat{j}+\left(z-z_{1}\right) \hat{k}
\end{aligned}
$$

It is given that the plane is parallel to two lines having direction ratios $b_{1}, b_{2}, b_{3}$ and $c_{1}, c_{2}, c_{3}$.
So, the given plane is parallel to each of the vectors

$$
\vec{b}=b_{1} \hat{i}+b_{2} \hat{j}+b_{3} \hat{k} \text { and } \vec{c}=c_{1} \hat{i}+c_{2} \hat{j}+c_{3} \hat{k}
$$

$\therefore \overrightarrow{A P}, \vec{b}$ and $\vec{c}$ are **coplanar**, and therefore their **scalar triple product** must be zero.

$$
\left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
b_{1} & b_{2} & b_{3} \\
c_{1} & c_{2} & c_{3}
\end{array}\right|=0,
$$

which is the required equation.

---

## Summary of the Results

1.  The vector equation of a plane passing through a point having position vector $\vec{a}$ and parallel to vectors $\vec{b}$ and $\vec{c}$, is given by

    $$
    (\vec{r}-\vec{a}) \cdot(\vec{b} \times \vec{c})=0
    $$

2.  The Cartesian equation of a plane passing through a point $A\left(x_{1}, y_{1}, z_{1}\right)$ and parallel to two nonparallel lines having d.r.'s $b_{1}, b_{2}, b_{3}$ and $c_{1}, c_{2}, c_{3}$ is given by

    $$
    \left|\begin{array}{ccc}
    x-x_{1} & y-y_{1} & z-z_{1} \\
    b_{1} & b_{2} & b_{3} \\
    c_{1} & c_{2} & c_{3}
    \end{array}\right|=0 .
    $$

---

## Solved Examples

### Example 1:

Find the vector and Cartesian equations of the plane passing through the point $(1, 2, -4)$ and parallel to the lines

$$
\begin{aligned}
\vec{r} & =(\hat{i}+2 \hat{j}+\hat{k})-\lambda(2 \hat{i}+3 \hat{j}+6 \hat{k}) \\
\text { and } \vec{r} & =(\hat{i}-3 \hat{j}+5 \hat{k})+\mu(\hat{i}+\hat{j}-\hat{k})
\end{aligned}
$$

#### Solution:

We know that the vector equation of a plane passing through a point $\vec{a}$ and parallel to $\vec{b}$ and $\vec{c}$ is given by $(\vec{r} \cdot \vec{a}) \cdot(\vec{b} \times \vec{c})=0$.

Here $\vec{a}=(\hat{i}+2 \hat{j}-4 \hat{k}), \vec{b}=(2 \hat{i}+3 \hat{j}+6 \hat{k})$
and $\vec{c}=(\hat{i}+\hat{j}-\hat{k})$.

$$
\begin{aligned}
\therefore \vec{b} \times \vec{c} & =\left|\begin{array}{ccc}
\hat{i} & \hat{j} & \hat{k} \\
2 & 3 & 6 \\
1 & 1 & -1
\end{array}\right| \\
& =(-3-6) \hat{i}-(-2-6) \hat{j}+(2-3) \hat{k}=(-9 \hat{i}+8 \hat{j}-\hat{k}) .
\end{aligned}
$$

So, the required vector equation is

$$
\begin{aligned}
& \vec{r} \cdot(\vec{b} \times \vec{c})=\vec{a} \cdot(\vec{b} \times \vec{c}) \\
\Rightarrow & \vec{r} \cdot(-9 \hat{i}+8 \hat{j}-\hat{k})=(\hat{i}+2 \hat{j}-4 \hat{k}) \cdot(-9 \hat{i}+8 \hat{j}-\hat{k}) \\
& =(-9+16+4)=11 \\
\Rightarrow & \vec{r} \cdot(-9 \hat{i}+8 \hat{j}-\hat{k})-11=0 \\
\Rightarrow & \vec{r} \cdot(9 \hat{i}-8 \hat{j}+\hat{k})+11=0 .
\end{aligned}
$$

Hence, the required **vector equation** of the plane is

$$
\vec{r} \cdot(9 \hat{i}-8 \hat{j}+\hat{k})+11=0 .
$$

Clearly, the required **Cartesian equation** of the plane is

$$
9 x-8 y+z+11=0 .
$$

---

### Example 2:

Find the Cartesian and vector equation of the plane passing through the point $(2, 0, -1)$ and parallel to the lines

$$
\frac{x}{-3}=\frac{y-2}{4}=z+1 \text { and } x-4=\frac{1-y}{2}=2 z .
$$

#### Solution:

The given lines are

$$
\begin{array}{r}
\frac{x}{-3}=\frac{y-2}{4}=\frac{z+1}{1} \text { and } \frac{x-4}{1}=\frac{y-1}{-2}=\frac{z}{\frac{1}{2}}, \\
\text { i.e., } \frac{x}{-3}=\frac{y-2}{4}=\frac{z+1}{1} \text { and } \frac{x-4}{2}=\frac{y-1}{-4}=\frac{z}{1} .
\end{array}
$$

So, the required plane passes through the point $A(2,0,-1)$ and it is parallel to the lines having direction ratios $-3, 4, 1$ and $2, -4, 1$.
Here $\left(x_{1}=2, y_{1}=0, z_{1}=-1\right),\left(a_{1}=-3, b_{1}=4, c_{1}=1\right)$
and $\left(a_{2}=2, b_{2}=-4, c_{2}=1\right)$.
The required equation of the plane is

$$
\begin{aligned}
& \left|\begin{array}{ccc}
x-x_{1} & y-y_{1} & z-z_{1} \\
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2}
\ends_array}\right|=0 \\
\Rightarrow & \left|\begin{array}{ccc}
x-2 & y-0 & z+1 \\
-3 & 4 & 1 \\
2 & -4 & 1
\end{array}\right|=0 \\
\Rightarrow & (x-2)(4+4)-y(-3-2)+(z+1)(12-8)=0 \\
\Rightarrow & 8(x-2)+5 y+4(z+1)=0 \\
\Rightarrow & 8 x+5 y+4 z-12=0
\end{aligned}
$$

Hence, the required **Cartesian equation** of the plane is $8 x+5 y+4 z=12$ and its corresponding **vector equation** is $\vec{r} \cdot(8 \hat{i}+5 \hat{j}+4 \hat{k})=12$.

---