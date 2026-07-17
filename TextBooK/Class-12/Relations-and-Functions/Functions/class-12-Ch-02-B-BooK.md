## Composition of Functions

Let $f: A \rightarrow B$ and $g: B \rightarrow C$ be two given functions. Then, the **composition** of $f$ and $g$, denoted by **$g$ o $f$**, is the function, defined by

$$
(g \circ f): A \rightarrow C:(g \circ f)(x)=g\{f(x)\} \forall x \in A .
$$

Clearly, $\operatorname{dom}(g \circ f)=\operatorname{dom}(f)$.
Also, **$g$ o $f$** is defined only when $\text{range}(f) \subseteq \operatorname{dom}(g)$.

**Remark:** **$(f \circ g)$** is defined only when $\text{range}(g) \subseteq \operatorname{dom}(f)$.

$$
\text { And, } \operatorname{dom}(f \text { o } g)=\operatorname{dom}(g) \text { . }
$$

---

## Solved Examples

### Example: 1

Let $f:\{1,3,4\} \rightarrow\{1,2,5\}$ and $g:\{1,2,5\} \rightarrow\{1,3\}$ be defined as $f=\{(1,2),(3,5),(4,1)\}$ and $g=\{(1,3),(2,3),(5,1)\}$. Find **$(g \circ f)$** and **$(f \circ g)$**.

#### Solution:

Here $\text{range}(f)=\{1,2,5\}$ and $\operatorname{dom}(g)=\{1,2,5\}$.
Clearly, $\text{range}(f) \subseteq \operatorname{dom}(g)$.

$\therefore \quad **(g \circ f)$** is defined and $\operatorname{dom}(g \circ f)=\operatorname{dom}(f)=\{1,3,4\}$.

Now,
$(g \circ f)(1)=g\{f(1)\}=g(2)=3$;
$(g \circ f)(3)=g\{f(3)\}=g(5)=1$;
$(g \circ f)(4)=g\{f(4)\}=g(1)=3$.

Hence, **$(g \circ f)=\{(1,3),(3,1),(4,3)\}$**.

Again, $\text{range}(g)=\{1,3\}$ and $\operatorname{dom}(f)=\{1,3,4\}$.
Clearly, $\text{range}(g) \subseteq \operatorname{dom}(f)$.

$\therefore \quad **(f \circ g)$** is defined and $\operatorname{dom}(f \circ g)=\operatorname{dom}(g)=\{1,2,5\}$.

Now,
$(f \circ g)(1)=f\{g(1)\}=f(3)=5$;
$(f \circ g)(2)=f\{g(2)\}=f(3)=5$;
$(f \circ g)(5)=f\{g(5)\}=f(1)=2$.

Hence, **$(f \circ g)=\{(1,5),(2,5),(5,2)\}$**.

---

### Example: 2

Let $R$ be the set of all real numbers. Let $f: R \rightarrow R: f(x)=\cos x$ and let $g: R \rightarrow R: g(x)=3 x^{2}$. Show that **$(g \circ f) \neq(f \circ g)$**.

#### Solution:

Let $x$ be an arbitrary real number. Then,

$$
\begin{aligned}
& (g \circ f)(x)=g\{f(x)\}=g(\cos x)=3(\cos x)^{2}=3 \cos ^{2} x . \\
& (f \circ g)(x)=f\{g(x)\}=f\left(3 x^{2}\right)=\cos \left(3 x^{2}\right) .
\end{aligned}
$$

Taking $x=0$, we have

$$
\begin{aligned}
(g \circ f)(0) & =3 \cos ^{2} 0=(3 \times 1)=3 . \\
\therefore \quad(f \circ g)(0) & =\cos (3 \times 0)=\cos 0=1 . \\
\therefore \quad(g \circ f)(0) & \neq(f \circ g)(0) .
\end{aligned}
$$

Hence, **$g \circ f \neq f \circ g$**.

---

### Example: 3

Let $R$ be the set of all real numbers. Let $f: R \rightarrow R: f(x)=\sin x$ and $g: R \rightarrow R: g(x)=x^{2}$. Prove that **$g$ o $f \neq f$ o $g$**.

#### Solution:

Let $x$ be an arbitrary real number. Then,

$$
\begin{aligned}
& (g \circ f)(x)=g\{f(x)\}=g(\sin x)=(\sin x)^{2} . \\
& (f \circ g)(x)=f\{g(x)\}=f\left(x^{2}\right)=\sin x^{2} .
\end{aligned}
$$

Clearly, $(\sin x)^{2} \neq \sin x^{2}$.
Hence, **$g$ o $f \neq f$ o $g$**.

---

### Example: 4

Let $f: R \rightarrow R: f(x)=8 x^{3}$ and $g: R \rightarrow R: g(x)=x^{1 / 3}$. Find **$(g \circ f)$** and **$(f \circ g)$** and show that **$g \circ f \neq f \circ g$**.

#### Solution:

Let $x \in R$. Then, we have

$$
\begin{array}{ll} 
& (g \circ f)(x)=g\{f(x)\}=g\left(8 x^{3}\right)=\left(8 x^{3}\right)^{1 / 3}=2 x . \\
& (f \circ g)(x)=f\{g(x)\}=f\left(x^{1 / 3}\right)=8\left(x^{1 / 3}\right)^{3}=8 x . \\
\therefore & g \circ f \neq f \circ g .
\end{array}
$$

---

### Example: 5

Let $f: R \rightarrow R: f(x)=\left(x^{2}-3 x+2\right)$, find **$(f \circ f)(x)$**.

#### Solution:

We have

$$
\begin{aligned}
(f \circ f)(x) & =f\{f(x)\}=f\left(x^{2}-3 x+2\right)=f(y), \text { where } y=\left(x^{2}-3 x+2\right) \\
& =\left(y^{2}-3 y+2\right) \\
& =\left(x^{2}-3 x+2\right)^{2}-3\left(x^{2}-3 x+2\right)+2 \\
& =\left(x^{4}-6 x^{3}+10 x^{2}-3 x\right)
\end{aligned}
$$

---

### Example: 6

If $f: R \rightarrow R: f(x)=\left(3-x^{3}\right)^{1 / 3}$, show that **$(f \circ f)(x)=x$**.

#### Solution:

We have

$$
\begin{aligned}
(f \circ f)(x) & =f\{f(x)\}=f\left(3-x^{3}\right)^{1 / 3} \\
& =f(y), \quad \text { where } y=\left(3-x^{3}\right)^{1 / 3} \\
& =\left(3-y^{3}\right)^{1 / 3}=\left[3-\left(3-x^{3}\right)\right]^{1 / 3} \quad\left[\because \quad y^{3}=\left(3-x^{3}\right)\right] \\
& =\left(x^{3}\right)^{1 / 3}=x .
\end{aligned}
$$

Hence, **$(f \circ f)(x)=x$**.

---

### Example: 7

Let $f: A \rightarrow B$, and let $I_{A}$ and $I_{B}$ be identity functions on $A$ and $B$ respectively. Prove that **$\left(f \circ I_{A}\right)=f$** and **$\left(I_{B} \circ f\right)=f$**.

#### Solution:

Let $x \in A$ and let $f(x)=y$. Then,

$$
\begin{array}{ll} 
& \left(f \circ I_{A}\right)(x)=f\left\{I_{A}(x)\right\}=f(x) \quad\left[\because \quad I_{A}(x)=x\right] \\
\therefore \quad & \left(f \circ I_{A}\right)=f .
\end{array}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Relations-and-Functions/Functions/class-12-Ch-02-B-BooK-001.jpg)

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Relations-and-Functions/Functions/class-12-Ch-02-B-BooK-002.jpg)

$$
\text { And, } \begin{array}{rlrl}
\left(I_{B} \circ f\right)(x) & =I_{B}\{f(x)\} & & \\
& =I_{B}(y) & {[\because} & f(x)=y] \\
& =y & {[\because} & \left.I_{B}(y)=y\right] \\
& =f(x) & & {[\because} \\
\because & y=f(x)] .
\end{array}
$$

$\therefore \quad\left(I_{B} \circ f\right)=f$.

Hence, **$\left(f \circ I_{A}\right)=f$** and **$\left(I_{B} \circ f\right)=f$**.

---

### Example: 8 (Associativity)

Let $f: A \rightarrow B, g: B \rightarrow C$ and $h: C \rightarrow D$. Then, prove that **$(h \circ g) \circ f=h \circ(g \circ f)$**.

#### Solution:

Let $x \in A$. Then,

$$
\begin{aligned}
\{(h \circ g) \circ f\}(x) & =(h \circ g)\{f(x)\} \\
& =h[g\{f(x)\}] \\
& =h[(g \circ f)(x)] \\
& =\{h \circ(g \circ f)\}(x) .
\end{aligned}
$$

$\therefore \quad **(h \circ g) \circ f=h \circ(g \circ f)$**.

---

### Example: 9

Let $f: Z \rightarrow Z: f(n)=3 n$ and let $g: Z \rightarrow Z$, defined by

$$
g(n)= \begin{cases}\frac{n}{3}, & \text { if } n \text { is a multiple of } 3 \\ 0, & \text { if } n \text { is not a multiple of } 3 .\end{cases}
$$

Show that **$g$ o $f=I_{Z}$** and **$f$ o $g \neq I_{Z}$**.

#### Solution:

Let $n$ be an arbitrary element of $Z$. Then,

$$
\begin{aligned}
(g \circ f)(n) & =g\{f(n)\} \\
& =g(3 n)=\frac{3 n}{3}=n \\
& =I_{Z}(n)
\end{aligned}
$$

$\therefore \quad **(g \circ f)=I_{Z}$**.

Also, we have

$$
\begin{aligned}
(f \circ g)(1) & =f\{g(1)\} \\
& =f(0) \quad[\because \quad g(1)=0] \\
& =(3 \times 0)=0 \quad[\because \quad f(n)=3 n]
\end{aligned}
$$

$$
I_{Z}(1)=1\left[\because \quad I_{Z}(x)=x \forall x \in Z\right] .
$$

$\therefore **f$ o $g \neq I_{Z}$**.

---

### Example: 10

Let $A=R-\left\{\frac{3}{5}\right\}$ and $B=R-\left\{\frac{7}{5}\right\}$.
Let $f: A \rightarrow B: f(x)=\frac{7 x+4}{5 x-3}$ and $g: B \rightarrow A: g(y)=\frac{3 y+4}{5 y-7}$.
Show that **$(g \circ f)=I_{A}$** and **$(f \circ g)=I_{B}$**.

#### Solution:

Let $x \in A$. Then,

$$
\begin{align*}
&(g \circ f)(x)=g[f(x)] \\
&=g\left(\frac{7 x+4}{5 x-3}\right) \\
&=g(y), \text { where } y=\frac{7 x+4}{5 x-3}  \tag{i}\\
&=\frac{3 y+4}{5 y-7}=\frac{3\left(\frac{7 x+4}{5 x-3}\right)+4}{5\left(\frac{7 x+4}{5 x-3}\right)-7} \quad[\text { using }(\mathrm{i})] \\
&=\frac{(21 x+12+20 x-12)}{(5 x-3)} \times \frac{(5 x-3)}{(35 x+20-35 x+21)} \\
&=\frac{41 x}{41}=x=I_{A}(x) . \\
& \therefore \quad **(g \circ f)=I_{A}$** .
\end{align*}
$$

Again, let $y \in B$. Then,

$$
\begin{align*}
(f \circ g)(y) & =f[g(y)] \\
& =f\left(\frac{3 y+4}{5 y-7}\right) \\
& =f(z), \text { where } z=\frac{3 y+4}{5 y-7}  \tag{ii}\\
& =\frac{7 z+4}{5 z-3}=\frac{7\left(\frac{3 y+4}{5 y-7}\right)+4}{5\left(\frac{3 y+4}{5 y-7}\right)-3} \\
& =\frac{(21 y+28+20 y-28)}{(5 y-7)} \times \frac{(5 y-7)}{(15 y+20-15 y+21)} \\
& =\frac{41 y}{41}=y=I_{B}(y)
\end{align*}
$$

$\therefore \quad **(f \circ g)=I_{B}$**.

Hence, **$(g \circ f)=I_{A}$** and **$(f \circ g)=I_{B}$**.

---

### Example: 11

Let $f: A \rightarrow B$ and $g: B \rightarrow A$ such that **$(g \circ f)=I_{A}$**. Show that $f$ is **one-one** and $g$ is **onto**.

#### Solution:

We have

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow g\left\{f\left(x_{1}\right)\right\}=g\left\{f\left(x_{2}\right)\right\} \\
& \Rightarrow(g \circ f)\left(x_{1}\right)=(g \circ f)\left(x_{2}\right) \\
& \Rightarrow I_{A}\left(x_{1}\right)=I_{A}\left(x_{2}\right) \\
& \Rightarrow x_{1}=x_{2} .
\end{aligned}
$$

$\therefore \quad f$ is **one-one**.

In order to show that $g$ is onto, let $a \in A$ and let $f(a)=b \in B$.
Then, $g(b)=g[f(a)]=(g \circ f)(a)$

$$
=I_{A}(a) \quad\left[\because \quad g \circ f=I_{A}\right] .
$$

Thus, for each $a \in A$, there exists $b \in B$ such that $g(b)=a$.
$\therefore g$ is **onto**.

---

## Exercise 2B

1.  Let $A=\{1,2,3,4\}$. Let $f: A \rightarrow A$ and $g: A \rightarrow A$, defined by $f=\{(1,4),(2,1),(3,3),(4,2)\}$ and

$$
g=\{(1,3),(2,1),(3,2),(4,4)\} .
$$

Find (i) **$g \circ f$** $\quad$ (ii) **$f \circ g$** $\quad$ (iii) **$f \circ f$**.

2.  Let $f:\{3,9,12\} \rightarrow\{1,3,4\}$ and $g:\{1,3,4,5\} \rightarrow\{3,9\}$ be
    defined as $f=\{(3,1),(9,3),(12,4)\}$ and

$$
g=\{(1,3),(3,3),(4,9),(5,9)\} .
$$

Find (i) **$(g \circ f)$** $\quad$ (ii) **$(f \circ g)$**.

3.  Let $f: R \rightarrow R: f(x)=x^{2}$ and $g: R \rightarrow R: g(x)=(x+1)$.

Show that **$(g \circ f) \neq(f \circ g)$**.

4.  Let $f: R \rightarrow R: f(x)=(2 x+1)$ and $g: R \rightarrow R: g(x)=\left(x^{2}-2\right)$.

Write down the formulae for:
- (i) **$(g \circ f)$**
- (ii) **$(f \circ g)$**
- (iii) **$(f \circ f)$**
- (iv) **$(g \circ g)$**.

5.  Let $f: R \rightarrow R: f(x)=\left(x^{2}+3 x+1\right)$ and $g: R \rightarrow R: g(x)=(2 x-3)$. Write down the formulae for:
- (i) **$g \circ f$**
- (ii) **$f \circ g$**
- (iii) **$g \circ g$**.

6.  Let $f: R \rightarrow R: f(x)=|x|$, prove that **$f$ o $f=f$**.

7.  Let $f: R \rightarrow R: f(x)=x^{2}, g: R \rightarrow R: g(x)=\tan x$
    and $h: R \rightarrow R: h(x)=\log x$.
    Find a formula for **$h \circ(g \circ f)$**.
    Show that **$[h \circ(g \circ f)] \sqrt{\frac{\pi}{4}}=0$**.

8.  Let $f: R \rightarrow R: f(x)=(2 x-3)$ and $g: R \rightarrow R: g(x)=\frac{1}{2}(x+3)$.

Show that **$(f \circ g)=I_{R}=(g \circ f)$**.

9.  Let $f: Z \rightarrow Z: f(x)=2 x$. Find $g: Z \rightarrow Z: **g$ o $f=I_{Z}$**.

10. Let $f: N \rightarrow N: f(x)=2 x, g: N \rightarrow N: g(y)=3 y+4$
    and $h: N \rightarrow N: h(z)=\sin z$.
    Show that **$h \circ(g \circ f)=(h \circ g) \circ f$**.

11. If $f$ be a **greatest integer function** and $g$ be an **absolute value function**, find the value of **$(f \circ g)\left(\frac{-3}{2}\right)+(g \circ f)\left(\frac{4}{3}\right)$**.
    [CBSE 2007]

12. Let $f: R \rightarrow R: f(x)=x^{2}+2$ and $g: R \rightarrow R: g(x)=\frac{x}{x-1}, x \neq 1$. Find **$f$ o $g$** and **$g \circ f$** and hence find **$(f \circ g)(2)$** and

---
