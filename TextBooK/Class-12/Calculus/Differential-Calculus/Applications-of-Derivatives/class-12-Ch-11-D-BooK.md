## Lagrange's Mean-Value Theorem

Let $f$ be a real function such that:
1.  $f(x)$ is **continuous** on $[a, b]$,
2.  $f(x)$ is **differentiable** on $] a, b[$.

**Then, there exists a real number $c \in] a, b\left[\right.$ such that $f^{\prime}(c)=\frac{f(b)-f(a)}{(b-a)}$.**

---

### Proof:

Let $F(x)=f(x)+A x$, where $A$ is a constant to be chosen in such a way that $F(a)=F(b)$.

Now, $F(a)=F(b) \Leftrightarrow f(a)+A a=f(b)+A b \Leftrightarrow A=\frac{f(b)-f(a)}{(a-b)}$.

$$
\therefore \quad F(x)=f(x)+\frac{f(b)-f(a)}{(a-b)} \cdot x \tag{i}
$$

Now, $f(x)$ is **continuous** on $[a, b]$, and $\left\{\frac{f(b)-f(a)}{(a-b)} \cdot x\right\}$ being a polynomial function, is **continuous** on $[a, b]$.

And, the sum of two continuous functions being continuous, it follows from (i) that $F(x)$ is **continuous**.

Also, $f(x)$ is **differentiable** on $] a, b[$, and since the polynomial function $\frac{f(b)-f(a)}{(a-b)} x$ is **differentiable** on $] a, b[$, it follows that $F(x)$ is **differentiable** on $] a, b[$.

Also, $F(a)=F(b)$.

Thus, all the conditions of **Rolle's theorem** are satisfied by $F(x)$.
So, there must exist some $c \in] a, b\left[\right.$ such that $F^{\prime}(c)=0$.

Now, $F(x)=f(x)+\frac{f(b)-f(a)}{(a-b)} \cdot x \Rightarrow F^{\prime}(x)=f^{\prime}(x)+\frac{f(b)-f(a)}{(a-b)}$.

$\therefore \quad F^{\prime}(c)=0 \Leftrightarrow f^{\prime}(c)+\frac{f(b)-f(a)}{(a-b)}=0 \Leftrightarrow f^{\prime}(c)=\frac{f(b)-f(a)}{(b-a)}$.

---

### Geometrical Significance of the Mean-Value Theorem

Let $y=f(x)$ be a given function defined on $[a, b]$, which is **continuous** on $[a, b]$ and **differentiable** on $] a, b[$.

Then, by **Lagrange's mean-value theorem**, there exists some $c \in] a, b[$ such that

$$
f^{\prime}(c)=\frac{f(b)-f(a)}{(b-a)} \tag{i}
$$

Now, if we draw the curve $y=f(x)$ and take the points $A[a, f(a)]$ and $B[b, f(b)]$ on the curve then

$$
\text { slope of chord } A B=\frac{f(b)-f(a)}{(b-a)} \tag{ii}
$$

Thus, from (i) and (ii), we have

$$
f^{\prime}(c)=\text { slope of chord } A B .
$$

This shows that the tangent to the curve $y=f(x)$ at the point $x=c$ is parallel to the chord $A B$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Calculus/Applications-of-Derivatives/class-12-Ch-11-D-BooK-001.jpg)

---

### Physical Significance of the Mean-Value Theorem

Let a particle be moving in a straight line and let $f(a)$ and $f(b)$ be its positions from the starting point, at the times $a$ and $b$ respectively.

Then, **average speed** of the particle $=\frac{f(b)-f(a)}{(b-a)}$.

We also know that $f^{\prime}(c)$ denotes the **instantaneous speed** of the particle at time $c$.

Now, by the **mean-value theorem**, $f^{\prime}(c)=\frac{f(b)-f(a)}{(b-a)}$.

So, the mean-value theorem says that at some time $c$ between $a$ and $b$, the **instantaneous speed** of the particle would be equal to the **average speed**.

---

## Solved Examples

### Example 1: Verify Lagrange's mean-value theorem for the following functions:

1.  $f(x)=x(2-x)$ in $[0,1]$
2.  $f(x)=x(x+4)^{2}$ in $[0,4]$
3.  $f(x)=x+\frac{1}{x}$ in $[1,3]$
4.  $f(x)=(x-1)(x-2)(x-3)$ in $[0,4]$
5.  $f(x)=\sqrt{x^{2}-4}$ **[CBSE 2002]**

#### Solution:

1.  **Consider $f(x)=x(2-x)$ in $[0,1]$.**
    
    The given function is $f(x)=2 x-x^{2}$.
    It, being a polynomial function, is **continuous** on $[0,1]$.
    Also, $f^{\prime}(x)=2-2 x$, which exists for all $x$ in $[0,1]$.
    So, $f(x)$ is **differentiable** on $] 0,1[$.
    
    Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
    So, there must exist some $c \in] 0,1[$ such that
    
    $$
    f^{\prime}(c)=\frac{f(1)-f(0)}{(1-0)}=1
    $$
    
    Now, $\left.f^{\prime}(c)=1 \Leftrightarrow 2-2 c=1 \Leftrightarrow c=\frac{1}{2} \in\right] 0,1[$.
    Thus, $\left.c=\frac{1}{2} \in\right] 0,1\left[\right.$ such that $f^{\prime}(c)=\frac{f(1)-f(0)}{1-0}$.
    
    Hence, **Lagrange's mean-value theorem** is verified.

2.  **Consider $f(x)=x(x+4)^{2}$ in $[0,4]$.**
    
    The given function is $f(x)=x^{3}+8 x^{2}+16 x$.
    It, being a polynomial function, is **continuous** on $[0,4]$.
    Also, $f^{\prime}(x)=\left(3 x^{2}+16 x+16\right)$, which exists for all $\left.x \in\right] 0,4[$.
    So, $f(x)$ is **differentiable** on $] 0,4[$.
    
    Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
    So, there must exist some $c \in] 0,4[$ such that
    
    $$
    f^{\prime}(c)=\frac{f(4)-f(0)}{(4-0)}=\left(\frac{256-0}{4}\right)=64 .
    $$
    
    Now, $f^{\prime}(c)=64 \Leftrightarrow 3 c^{2}+16 c+16=64$
    
    $$
    \Leftrightarrow 3 c^{2}+16 c-48=0 \Leftrightarrow c=\frac{-8 \pm 4 \sqrt{13}}{3}
    $$
    
    Clearly, $\left.\quad c=\frac{-8+4 \sqrt{13}}{3}=2.13 \in\right] 0,4[$.
    Hence, **Lagrange's mean-value theorem** is verified.

3.  **Consider $f(x)=x+\frac{1}{x}$ in $[1,3]$.**
    
    The given function is
    
    $$
    f(x)=\frac{x^{2}+1}{x}
    $$
    
    Since it is a rational function such that $x \neq 0$, it is **continuous** in $[1, 3]$.
    Also, $f^{\prime}(x)=\left(1-\frac{1}{x^{2}}\right)=\left(\frac{x^{2}-1}{x^{2}}\right)$, which clearly exists for all values of $x$ in $]1, 3[$.
    So, $f(x)$ is **differentiable** on $]1, 3[$.
    
    Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
    So, there must exist some $c \in] 1$, 3[ such that
    
    $$
    f^{\prime}(c)=\frac{f(3)-f(1)}{(3-1)}=\frac{\left(\frac{10}{3}-2\right)}{2}=\frac{2}{3} .
    $$
    
    Now, $\left.\quad f^{\prime}(c)=\frac{2}{3} \Leftrightarrow \frac{c^{2}-1}{c^{2}}=\frac{2}{3} \Leftrightarrow c=\sqrt{3} \in\right] 1,3[$.
    Thus, $c=\sqrt{3} \in] 1,3\left[\right.$ such that $f^{\prime}(c)=\frac{f(3)-f(1)}{(3-1)}$.
    Hence, **Lagrange's mean-value theorem** is verified.

4.  **Consider $f(x)=(x-1)(x-2)(x-3)$ in $[0,4]$.**
    
    The given function is $f(x)=x^{3}-6 x^{2}+11 x-6$.
    Being a polynomial function, it is **continuous** on $[0,4]$.
    Also, $f^{\prime}(x)=\left(3 x^{2}-12 x+11\right)$, which exists for all $\left.x \in\right] 0,4[$.
    So, $f(x)$ is **differentiable** on $] 0,4[$.
    
    Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
    So, there exists some $c \in] 0,4[$ such that
    
    $$
    f^{\prime}(c)=\frac{f(4)-f(0)}{(4-0)}=\frac{6-(-6)}{4}=3 .
    $$
    
    Now, $f^{\prime}(c)=3 \Leftrightarrow 3 c^{2}-12 c+11=3 \Leftrightarrow 3 c^{2}-12 c+8=0$
    
    $$
    \begin{aligned}
    & \Leftrightarrow c=\frac{12 \pm \sqrt{144-96}}{6}=\frac{6 \pm 2 \sqrt{3}}{3} . \\
    & \Leftrightarrow c=3.155 \text { or } c=0.845[\because \sqrt{3}=1.732] .
    \end{aligned}
    $$
    
    Clearly, both these values of $c$ lie in $] 0,4[$.
    Hence, **Lagrange's mean-value theorem** is verified.

5.  **Consider $f(x)=\sqrt{x^{2}-4}$ in $[2,4]$.**
    
    Clearly, $f(x)$ has a definite and unique value for each $x \in[2,4]$. So, at every point $[2,4]$, the value of $f(x)$ is equal to the limit of $f(x)$.
    
    So, $f(x)$ is **continuous** on $[2,4]$.
    Also, $f^{\prime}(x)=\frac{x}{\sqrt{x^{2}-4}}$, which exists for all $\left.x \in\right] 2,4[$.
    So, $f(x)$ is **differentiable** on $] 2,4[$.
    
    So, there must exist some $c \in] 2,4[$ such that
    
    $$
    f^{\prime}(c)=\frac{f(4)-f(2)}{(4-2)}=\frac{\sqrt{12}-0}{2}=\sqrt{3} .
    $$
    
    Now,
    
    $$
    f^{\prime}(c)=\sqrt{3} \Leftrightarrow \frac{c}{\sqrt{c^{2}-4}}=\sqrt{3} \Leftrightarrow c^{2}=3\left(c^{2}-4\right) \Leftrightarrow c= \pm \sqrt{6} .
    $$
    
    Clearly, $c=\sqrt{6} \in] 2,4\left[\right.$ such that $f^{\prime}(c)=\frac{f(4)-f(2)}{(4-2)}$.
    Hence, **Lagrange's mean-value theorem** is verified.

---

### Example 2: Verify the hypothesis and conclusion of Lagrange's mean-value theorem for the function $f(x)=\frac{1}{(4 x-1)}, 1 \leq x \leq 4$.

#### Solution:

Clearly, for each $x \in[1,4], f(x)$ has a definite and unique value.
So, $f(x)$ is **continuous** on $[1,4]$.

Also, $f^{\prime}(x)=\frac{-4}{(4 x-1)^{2}}$, which exists for all $\left.x \in\right] 1,4[$.
So, $f(x)$ is **differentiable** on $] 1,4[$.

Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
So, there must exist some $c \in] 1,4[$ such that

$$
f^{\prime}(c)=\frac{f(4)-f(1)}{(4-1)}=\frac{1}{3}\left(\frac{1}{15}-\frac{1}{3}\right)=\frac{-4}{45} .
$$

Now, $f^{\prime}(c)=\frac{-4}{45} \Leftrightarrow \frac{-4}{(4 c-1)^{2}}=\frac{-4}{45} \Leftrightarrow(4 c-1)^{2}=45$

$$
\Leftrightarrow(4 c-1)= \pm 3 \sqrt{5} \Leftrightarrow c=\left(\frac{1 \pm 3 \sqrt{5}}{4}\right) .
$$

Clearly, $\left.c=\frac{1+3 \sqrt{5}}{4}=\left(\frac{1+3 \times 2.23}{4}\right)=1.92 \in\right] 1,4[$.
Hence, **Lagrange's mean-value theorem** is verified.

---

### Example 3: Find '$c$' of the mean-value theorem for the functions:

1.  $f(x)=2 x^{2}-10 x+29$ in $[2,7]$
2.  $f(x)=x(x-1)(x-2)$ in $\left[0, \frac{1}{2}\right]$

#### Solution:

1.  $f(x)=2 x^{2}-10 x+29 \Leftrightarrow f^{\prime}(x)=4 x-10$.
    
    Now, $\quad f^{\prime}(c)=\frac{f(7)-f(2)}{(7-2)} \Leftrightarrow(4 c-10)=\frac{(57-17)}{5}$
    
    $$
    \Leftrightarrow 4 c=18 \Leftrightarrow c=4.5 \in] 2,7[.
    $$
    
    $\therefore \quad c=4.5$.

2.  The given function is $f(x)=x^{3}-3 x^{2}+2 x$.
    $\therefore f^{\prime}(x)=3 x^{2}-6 x+2$.
    
    Now,
    
    $$
    \begin{aligned}
    f^{\prime}(c)=\frac{f\left(\frac{1}{2}\right)-f(0)}{\left(\frac{1}{2}-0\right)} & \Leftrightarrow 3 c^{2}-6 c+2=\frac{\left(\frac{3}{8}-0\right)}{\left(\frac{1}{2}\right)} \\
    & \Leftrightarrow 12 c^{2}-24 c+5=0 \\
    & \Leftrightarrow c=\frac{24 \pm \sqrt{576-240}}{24}=\frac{6 \pm \sqrt{21}}{6} .
    \end{aligned}
    $$
    
    Clearly, $c=\frac{6-\sqrt{21}}{6}=\frac{6-4.58}{6}=0.24 \in\left[0, \frac{1}{2}\right]$.
    Hence, $\quad c=0.24$.

---

### Example 4: Using Lagrange's mean-value theorem, find a point on the curve $y=\sqrt{x-2}$, defined in the interval $[2,3]$, where the tangent is parallel to the chord joining the end points of the curve.

Let $f(x)=\sqrt{x-2}$.

Clearly, for each $x \in[2,3]$, the function $f(x)$ has a definite and unique value.
So, $f(x)$ is **continuous** on $[2,3]$.

Also, $f^{\prime}(x)=\frac{1}{2 \sqrt{x-2}}$, which exists for all $x$ in $] 2,3[$.
So, $f(x)$ is **differentiable** on $] 2,3[$.

Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
So, there must exist some $c \in] 2,3\left[\right.$ such that $f^{\prime}(c)=\frac{f(3)-f(2)}{(3-2)}=1$.

Now, $f^{\prime}(c)=1 \Leftrightarrow \frac{1}{2 \sqrt{c-2}}=1 \Leftrightarrow c-2=\frac{1}{4}$, i.e., $\left.c=\frac{9}{4} \in\right] 2$, 3[.

Now, $x=\frac{9}{4}$ and $y=\sqrt{x-2} \Leftrightarrow y=\sqrt{\left(\frac{9}{4}-2\right)}=\frac{1}{2}$.

$\therefore$ the tangent to the given curve at the point $\left(\frac{9}{4}, \frac{1}{2}\right)$ is parallel to the chord joining the end points of the curve.

---

### Example 5: Find a point on the parabola $y=(x-3)^{2}$, where the tangent is parallel to the chord joining $(3,0)$ and $(4,1)$. **[CBSE 2000C]**

#### Solution:

Let us apply **Lagrange's mean-value theorem** for the function $f(x)=(x-3)^{2}$ in the interval $[3, 4]$.

Now, $f(x)$ being a polynomial function, it is **continuous** on $[3,4]$.
Also, $f^{\prime}(x)=2(x-3)$, which exists for all $\left.x \in\right] 3,4[$.
So, $f(x)$ is **differentiable** on $] 3,4[$.

Thus, both the conditions of **Lagrange's mean-value theorem** are satisfied.
So, there must exist a point $c \in] 3,4[$ such that

$$
f^{\prime}(c)=\frac{f(4)-f(3)}{(4-3)}=1
$$

Now, $\left.f^{\prime}(c)=1 \Leftrightarrow 2(c-3)=1 \Leftrightarrow c=\frac{7}{2} \in\right] 3,4[$.

Now, $x=\frac{7}{2}$ and $y=(x-3)^{2} \Leftrightarrow y=\frac{1}{4}$.

Thus, at the point $\left(\frac{7}{2}, \frac{1}{4}\right)$ on the given curve the tangent is parallel to the chord joining $(3,0)$ and $(4,1)$.

---