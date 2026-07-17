## 18. Differential Equations and Their Formation

### Differential Equation

An equation containing an **independent variable**, a **dependent variable** and the **derivatives** of the dependent variable is called a **differential equation**.

**Examples:** Each of the following equations is a differential equation:

1.  $\frac{d y}{d x}+5 y=e^{x}$
2.  $\frac{d^{2} y}{d x^{2}}-2 \frac{d y}{d x}+3 y=\sin x$
3.  $\frac{d y}{d x}=\frac{x^{3}-y^{3}}{x y^{2}-x^{2} y}$
4.  $x^{2} d x+y^{2} d y=0$

### Order of a Differential Equation

The order of the **highest-order derivative** occurring in a differential equation is called the **order** of the differential equation.

### Degree of a Differential Equation

The **power** of the **highest-order derivative** occurring in a differential equation, after it is made **free from radicals and fractions**, is called the **degree** of the differential equation.

---

### Example 1

Write the order and the degree of the differential equation $\frac{d^{2} y}{d x^{2}}+5 \frac{d y}{d x}+3 y=0$.

#### Solution:

In the given equation, the highest-order derivative is $\frac{d^{2} y}{d x^{2}}$ and its power is $1$.
$\therefore$ its **order $= 2$** and **degree $= 1$**.

---

### Example 2

Write the order and the degree of the differential equation

$$
x\left(\frac{d^{3} y}{d x^{3}}\right)^{2}+\left(\frac{d y}{d x}\right)^{4}+y^{2}=0
$$

#### Solution:

In the given equation, the highest-order derivative is $\frac{d^{3} y}{d x^{3}}$ and its power is $2$.
$\therefore$ its **order $= 3$** and **degree $= 2$**.

---

### Example 3

Write the order and the degree of the differential equation

$$
y=x \frac{d y}{d x}+\sqrt{1+\left(\frac{d y}{d x}\right)^{2}}
$$

#### Solution:

The given equation may be written as

$$
\begin{aligned}
& \sqrt{1+\left(\frac{d y}{d x}\right)^{2}}=\left(y-x \frac{d y}{d x}\right) \\
\Rightarrow & 1+\left(\frac{d y}{d x}\right)^{2}=\left(y-x \frac{d y}{d x}\right)^{2} \quad \text { [on squaring both sides] } \\
\Rightarrow & 1+\left(\frac{d y}{d x}\right)^{2}=y^{2}+x^{2}\left(\frac{d y}{d x}\right)^{2}-2 x y \frac{d y}{d x} \\
\Rightarrow & \left(1-x^{2}\right)\left(\frac{d y}{d x}\right)^{2}+2 x y \frac{d y}{d x}+\left(1-y^{2}\right)=0 .
\end{aligned}
$$

Clearly, it is a differential equation of **order $= 1$** and **degree $= 2$**.

---

### Example 4

Write the order and degree of the differential equation

$$
\left\{1+\left(\frac{d y}{d x}\right)^{2}\right\}^{3 / 2}=k\left(\frac{d^{2} y}{d x^{2}}\right)
$$

#### Solution:

On squaring both sides, we get

$$
\left\{1+\left(\frac{d y}{d x}\right)^{2}\right\}^{3}=k^{2}\left(\frac{d^{2} y}{d x^{2}}\right)^{2}
$$

In this equation, the highest-order derivative is $\frac{d^{2} y}{d x^{2}}$ whose power is $2$.
$\therefore$ its **order $= 2$** and **degree $= 2$**.

---

### Example 5

Find the order and the degree of the differential equation

$$
y=p x+\sqrt{a^{2} p^{2}+b^{2}}, \text { where } p=\frac{d y}{d x} .
$$

#### Solution:

$$
\begin{aligned}
& y=p x+\sqrt{a^{2} p^{2}+b^{2}} \\
\Rightarrow & y-p x=\sqrt{a^{2} p^{2}+b^{2}} \\
\Rightarrow & (y-p x)^{2}=a^{2} p^{2}+b^{2} \quad \text { [on squaring both sides] } \\
\Rightarrow & y^{2}+x^{2} p^{2}-2 x y p=a^{2} p^{2}+b^{2} \\
\Rightarrow & \left(x^{2}-a^{2}\right) p^{2}-2 x y p+\left(y^{2}-b^{2}\right)=0 \\
\Rightarrow & \left(x^{2}-a^{2}\right)\left(\frac{d y}{d x}\right)^{2}-2 x y \cdot\left(\frac{d y}{d x}\right)+\left(y^{2}-b^{2}\right)=0 .
\end{aligned}
$$

Clearly, it is a differential equation of **order $1$** and **degree $2$**.

---

> **An Important Note**
> In case of differential equations involving one or more terms of the form $e^{(d y / d x)}$, $\log \left(\frac{d y}{d x}\right)$, $\sin \left(\frac{d y}{d x}\right)$, $\cos \left(\frac{d y}{d x}\right)$, etc., the **degree is not defined**.
>
> However, the degree of the differential equation containing terms like $e^{x}$, $e^{y}$, $\log x$, $\log y$, $\tan x$, $\tan y$, etc., is defined as usual.

---

### Example 6

Find the order and degree (if any) of each of the differential equations given below:

1.  $\frac{d y}{d x}-\tan x=0$
2.  $\left(\frac{d y}{d x}\right)^{2}+y=e^{x}$
3.  $\frac{d^{2} y}{d x^{2}}=\sin 3 x+\cos 3 x$
4.  $\left(y^{\prime \prime}\right)^{2}+\cos y^{\prime}=0$
5.  $y^{\prime \prime}+2 y^{\prime}+\sin y=0$
6.  $\frac{d^{4} y}{d x^{4}}+\sin \left(\frac{d^{3} y}{d x^{3}}\right)=0$
7.  $y^{\prime \prime \prime}+y^{2}+e^{y^{\prime}}=0$
8.  $3 \frac{d^{2} y}{d x^{2}}+5\left(\frac{d y}{d x}\right)^{2}=\log x$

#### Solution:

1.  The given equation is $\frac{d y}{d x}-\tan x=0$.
    In this equation, the highest-order derivative is $\frac{d y}{d x}$ whose power is $1$.
    $\therefore$ its **order $= 1$** and **degree $= 1$**.

2.  The given equation is $\left(\frac{d y}{d x}\right)^{2}+y=e^{x}$.
    In this equation, the highest-order derivative is $\frac{d y}{d x}$ whose power is $2$.
    $\therefore$ its **order $= 1$** and **degree $= 2$**.

3.  The given equation is $\frac{d^{2} y}{d x^{2}}=\sin 3 x+\cos 3 x$.
    In this equation, the highest-order derivative is $\frac{d^{2} y}{d x^{2}}$ and its power is $1$.
    $\therefore$ its **order $= 2$** and **degree $= 1$**.

4.  The given equation is $\left(\frac{d^{2} y}{d x^{2}}\right)^{2}+\cos \left(\frac{d y}{d x}\right)=0$.
    In this equation, the highest-order derivative is $\frac{d^{2} y}{d x^{2}}$, so its **order is $2$**.
    It has a term $\cos \left(\frac{d y}{d x}\right)$, so its **degree is not defined**.

5.  The given equation is $\frac{d^{2} y}{d x^{2}}+2 \frac{d y}{d x}+\sin y=0$.
    In this equation, the highest-order derivative is $\frac{d^{2} y}{d x^{2}}$ and its power is $1$.
    $\therefore$ its **order $= 2$** and **degree $= 1$**.

6.  The given equation is $\frac{d^{4} y}{d x^{4}}+\sin \left(\frac{d^{3} y}{d x^{3}}\right)=0$.
    In this equation, the highest-order derivative is $\frac{d^{4} y}{d x^{4}}$, so its **order is $4$**.
    It has a term $\sin \left(\frac{d^{3} y}{d x^{3}}\right)$, so its **degree is not defined**.

7.  The given equation is $\frac{d^{3} y}{d x^{3}}+y^{2}+e^{(d y / d x)}=0$.
    In this equation, the highest-order derivative is $\frac{d^{3} y}{d x^{3}}$, so its **order is $3$**.
    It has a term $e^{(d y / d x)}$, so its **degree is not defined**.

8.  The given equation is $3 \frac{d^{2} y}{d x^{2}}+5\left(\frac{d y}{d x}\right)^{2}=\log x$.
    In this equation, the highest-order derivative is $\frac{d^{2} y}{d x^{2}}$ and its power is $1$.
    $\therefore$ its **order $= 2$** and **degree $= 1$**.

---