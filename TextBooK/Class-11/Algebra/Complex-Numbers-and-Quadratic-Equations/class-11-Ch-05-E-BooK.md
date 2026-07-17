## Quadratic Equations (With Complex Roots)

---

## Fundamental Theorem of Algebra

A polynomial equation of degree $n$ has at the most $n$ roots.

---

## Solving a Quadratic Equation

Let the given equation be $ax^{2}+bx+c=0$, where $a, b, c \in R$ and $a \neq 0$.

Then, for $ax^{2}+bx+c=0$, $a \neq 0$:
$$
\begin{aligned}
& \Rightarrow \quad a x^{2}+b x=-c \\
& \Rightarrow \quad x^{2}+\frac{b}{a} \cdot x=\frac{-c}{a} \\
& \Rightarrow \quad x^{2}+\frac{b}{a} \cdot x+\left(\frac{b}{2 a}\right)^{2}=\frac{-c}{a}+\left(\frac{b}{2 a}\right)^{2} \quad\left[\text{adding}\left(\frac{b}{2 a}\right)^{2} \text{on both sides}\right] \\
& \Rightarrow \quad\left(x+\frac{b}{2 a}\right)^{2}=\frac{\left(b^{2}-4 a c\right)}{4 a^{2}} \\
& \Rightarrow \quad x+\frac{b}{2 a}= \pm \frac{\sqrt{b^{2}-4 a c}}{2 a} \\
& \Rightarrow \quad x=-\frac{b}{2 a} \pm \frac{\sqrt{b^{2}-4 a c}}{2 a} \\
& \Rightarrow x=\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a}
\end{aligned}
$$
Hence, the roots of the equation $ax^{2}+bx+c=0, a \neq 0$ are:
$$
\frac{-b+\sqrt{b^{2}-4 a c}}{2 a} \text{ and } \frac{-b-\sqrt{b^{2}-4 a c}}{2 a}
$$
The expression $(b^{2}-4ac)$ is called the **discriminant**.

If $(b^{2}-4ac) < 0$, the given quadratic equation will have **complex roots**. Here, we shall consider only the quadratic equations having complex roots.

---

## Solved Examples

### Example 1:

Solve: $x^{2}+3=0$.

#### Solution:

We have:
$$
x^{2}+3=0 \Rightarrow x^{2}=-3 \Rightarrow x= \pm \sqrt{-3}= \pm i \sqrt{3}
$$
$\therefore$ solution set $= \{i \sqrt{3}, -i \sqrt{3}\}$.

---

### Example 2:

Solve: $x^{2}+3x+9=0$.

#### Solution:

The given equation is $x^{2}+3x+9=0$. This is of the form $ax^{2}+bx+c=0$, where $a=1$, $b=3$ and $c=9$.
$$
\therefore \quad (b^{2}-4ac) = (3^{2}-4 \times 1 \times 9) = (9-36)=-27 < 0
$$
So, the given equation has **complex roots**. These roots are given by:
$$
\begin{aligned}
\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a} & =\frac{-3 \pm \sqrt{-27}}{2 \times 1} \quad\left[\because b^{2}-4 a c=-27\right] \\
& =\frac{-3 \pm i \sqrt{27}}{2}=\frac{-3 \pm i 3 \sqrt{3}}{2}
\end{aligned}
$$
$$
\therefore \quad \text{solution set} = \left\{\frac{-3+i 3 \sqrt{3}}{2}, \frac{-3-i 3 \sqrt{3}}{2}\right\} = \left\{\frac{-3}{2}+\frac{3 \sqrt{3}}{2} i, \frac{-3}{2}-\frac{3 \sqrt{3}}{2} i\right\}
$$

---

### Example 3:

Solve: $9x^{2}+10x+3=0$.

#### Solution:

The given equation is $9x^{2}+10x+3=0$. This is of the form $ax^{2}+bx+c=0$, where $a=9$, $b=10$ and $c=3$.
$$
\therefore \quad (b^{2}-4ac) = \{(10)^{2}-4 \times 9 \times 3\} = (100-108) = -8 < 0
$$
So, the given equation has **complex roots**. These roots are given by:
$$
\begin{aligned}
\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a} & =\frac{-10 \pm \sqrt{-8}}{2 \times 9} \quad\left[\because\left(b^{2}-4 a c\right)=-8\right] \\
& =\frac{-10 \pm i 2 \sqrt{2}}{18}=\frac{-5 \pm i \sqrt{2}}{9}
\end{aligned}
$$
$$
\therefore \quad \text{solution set} = \left\{\frac{-5+i \sqrt{2}}{9}, \frac{-5-i \sqrt{2}}{9}\right\} = \left\{\frac{-5}{9}+\frac{\sqrt{2}}{9} i, \frac{-5}{9}-\frac{\sqrt{2}}{9} i\right\}
$$

---

### Example 4:

Solve: $\sqrt{2} x^{2}+x+\sqrt{2}=0$.

#### Solution:

The given equation is $\sqrt{2} x^{2}+x+\sqrt{2}=0$. This is of the form $ax^{2}+bx+c=0$, where $a=\sqrt{2}$, $b=1$ and $c=\sqrt{2}$.
$$
\therefore \quad (b^{2}-4ac) = (1^{2}-4 \times \sqrt{2} \times \sqrt{2}) = (1-8) = -7 < 0
$$
So, the given equation has **complex roots**. These roots are given by:
$$
\begin{aligned}
\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a} & =\frac{-1 \pm \sqrt{-7}}{2 \sqrt{2}} \\
& =\frac{-1 \pm i \sqrt{7}}{2 \sqrt{2}}
\end{aligned}
$$
$$
\therefore \quad \text{solution set} = \left\{\frac{-1+i \sqrt{7}}{2 \sqrt{2}}, \frac{-1-i \sqrt{7}}{2 \sqrt{2}}\right\} = \left\{\frac{-1}{2 \sqrt{2}}+\frac{\sqrt{7}}{2 \sqrt{2}} i, \frac{-1}{2 \sqrt{2}}-\frac{\sqrt{7}}{2 \sqrt{2}} i\right\}
$$

---

### Example 5:

Solve: $\sqrt{3} x^{2}-\sqrt{2} x+3 \sqrt{3}=0$.

#### Solution:

The given equation is $\sqrt{3} x^{2}-\sqrt{2} x+3 \sqrt{3}=0$. This is of the form $ax^{2}+bx+c=0$, where $a=\sqrt{3}$, $b=-\sqrt{2}$ and $c=3 \sqrt{3}$.
$$
\therefore \quad (b^{2}-4ac) = \{(-\sqrt{2})^{2}-4 \times \sqrt{3} \times 3 \sqrt{3}\} = (2-36) = -34 < 0
$$
So, the given equation has **complex roots**. These roots are given by:
$$
\begin{aligned}
\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a} & =\frac{\sqrt{2} \pm \sqrt{-34}}{2 \times \sqrt{3}} \\
& =\frac{\sqrt{2} \pm i \sqrt{34}}{2 \sqrt{3}}
\end{aligned}
$$
$$
\therefore \quad \text{solution set} = \left\{\frac{\sqrt{2}+i \sqrt{34}}{2 \sqrt{3}}, \frac{\sqrt{2}-i \sqrt{34}}{2 \sqrt{3}}\right\} = \left\{\frac{1}{\sqrt{6}}+\frac{\sqrt{34}}{2 \sqrt{3}} i, \frac{1}{\sqrt{6}}-\frac{\sqrt{34}}{2 \sqrt{3}} i\right\}
$$

---

### Example 6:

Solve: $3x^{2}+8ix+3=0$.

#### Solution:

The given equation is $3x^{2}+8ix+3=0$. This is of the form $ax^{2}+bx+c=0$, where $a=3$, $b=8i$ and $c=3$.
$$
\therefore \quad (b^{2}-4ac) = \{(8i)^{2}-4 \times 3 \times 3\} = (-64-36) = -100 < 0
$$
So, the given equation has **complex roots**. These roots are given by:
$$
\begin{aligned}
\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a} & =\frac{-8 i \pm \sqrt{-100}}{2 \times 3} \quad\left[\because b^{2}-4 a c=-100\right] \\
& =\frac{-8 i \pm 10 i}{6}=\frac{-4 i \pm 5 i}{3}
\end{aligned}
$$
Thus, the roots of the given equation are:
$$
\frac{-4 i+5 i}{3}=\frac{i}{3} \text{ and } \frac{-4 i-5 i}{3}=\frac{-9 i}{3}=-3 i
$$
$$
\therefore \quad \text{solution set} = \left\{\frac{i}{3},-3 i\right\}
$$

---

