## 5. Increasing and Decreasing Functions

**Increasing Function**
A function $f(x)$ defined on $] a, b[$ is said to be **increasing** if $x_{1}<x_{2} \Rightarrow f\left(x_{1}\right) \leq f\left(x_{2}\right)$ for all $\left.x_{1}, x_{2} \in\right] a, b[$
or

$$
\left.x_{1}>x_{2} \Rightarrow f\left(x_{1}\right) \geq f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[.
$$

**Strictly Increasing Function**
A function $f(x)$ defined on $] a, b[$ is said to be **strictly increasing** if

$$
\left.x_{1}<x_{2} \Rightarrow f\left(x_{1}\right)<f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[
$$

or

$$
\left.x_{1}>x_{2} \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[.
$$

**Decreasing Function**
A function $f(x)$ defined on $] a, b[$ is said to be **decreasing** if

$$
\left.x_{1}<x_{2} \Rightarrow f\left(x_{1}\right) \geq f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[
$$

or

$$
\left.x_{1}>x_{2} \Rightarrow f\left(x_{1}\right) \leq f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[.
$$

**Strictly Decreasing Function**
A function $f(x)$ defined on $] a, b[$ is said to be **strictly decreasing** if

$$
\left.x_{1}<x_{2} \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[
$$

or

$$
\left.x_{1}>x_{2} \Rightarrow f\left(x_{1}\right)<f\left(x_{2}\right) \text { for all } x_{1}, x_{2} \in\right] a, b[.
$$

---

### Example 1:

Show that $f(x)=3 x+5$ is a strictly increasing function on $R$.

#### Solution:

Let $x_{1}, x_{2} \in R$ such that $x_{1}<x_{2}$. Then,

$$
\begin{aligned}
x_{1}<x_{2} & \Rightarrow 3 x_{1}<3 x_{2} \\
& \Rightarrow 3 x_{1}+5<3 x_{2}+5 \\
& \Rightarrow f\left(x_{1}\right)<f\left(x_{2}\right) .
\end{aligned}
$$

Thus, $x_{1}<x_{2} \Rightarrow f\left(x_{1}\right)<f\left(x_{2}\right)$ for all $x_{1}, x_{2} \in R$.
Hence, $f(x)$ is strictly increasing on $R$.

---

### Example 2:

Show that the function $f(x)=e^{x}$ is strictly increasing on $R$.

#### Solution:

Let $x_{1}, x_{2} \in R$ such that $x_{1}>x_{2}$. Then,

$$
\begin{aligned}
x_{1}>x_{2} & \Rightarrow e^{x_{1}}>e^{x_{2}} \quad\left[\because e>1 \text { and } x_{1}>x_{2} \Rightarrow e^{x_{1}}>e^{x_{2}}\right] \\
& \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right) .
\end{aligned}
$$

Thus, $x_{1}>x_{2} \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right)$ for all $x_{1}, x_{2} \in R$.
Hence, $f(x)$ is strictly increasing on $R$.

---

### Example 3:

Show that $f(x)=e^{-x}$ is a strictly decreasing function on $R$.

#### Solution:

Let $x_{1}, x_{2} \in R$ such that $x_{1}>x_{2}$. Then,

$$
\begin{aligned}
x_{1}>x_{2} & \Rightarrow e^{x_{1}}>e^{x_{2}} \quad\left[\because \quad e>1 \text { and } x_{1}>x_{2} \Rightarrow e^{x_{1}}>e^{x_{2}}\right] \\
& \Rightarrow \frac{1}{e^{x_{1}}}<\frac{1}{e^{x_{2}}} \\
& \Rightarrow e^{-x_{1}}<e^{-x_{2}}
\end{aligned}
$$

Thus, $x_{1}>x_{2} \Rightarrow e^{-x_{1}}<e^{-x_{2}}$ for all $x_{1}, x_{2} \in R$.
Hence, $f(x)=e^{-x}$ is strictly decreasing on $R$.

---

### Example 4:

If $a$ is a real number greater than 1, show that the function $f(x)=a^{x}$ is strictly increasing on $R$.

#### Solution:

Let $x_{1}, x_{2} \in R$ such that $x_{1}>x_{2}$. Then,

$$
\begin{aligned}
x_{1}>x_{2} & \Rightarrow a^{x_{1}}>a^{x_{2}} \quad\left[\because a>1 \text { and } x_{1}>x_{2} \Rightarrow a^{x_{1}}>a^{x_{2}}\right] \\
& \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right) .
\end{aligned}
$$

Thus, $x_{1}>x_{2} \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right)$ for all $x_{1}, x_{2} \in R$.
Hence, $f(x)$ is strictly increasing on $R$.

---

### Example 5:

If $a$ is a real number such that $0<a<1$, show that the function $f(x)=a^{x}$ is strictly decreasing on $R$.

#### Solution:

Let $x_{1}, x_{2} \in R$ such that $x_{1}<x_{2}$. Then,

$$
\begin{aligned}
x_{1}<x_{2} & \Rightarrow a^{x_{1}}>a^{x_{2}}\left[\because 0<a<1 \text { and } x_{1}<x_{2} \Rightarrow a^{x_{1}}>a^{x_{2}}\right] \\
& \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right) .
\end{aligned}
$$

Thus, $x_{1}<x_{2} \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right)$ for all $x_{1}, x_{2} \in R$.
Hence, $f(x)$ is strictly decreasing on $R$.

---

### Theorem 1

Let $f(x)$ be a function continuous on $[a, b]$ and differentiable on $] a, b[$. Then,

$$
\left.f^{\prime}(x)>0 \text { for all } x \in\right] a, b[\Rightarrow f(x) \text { is increasing on }] a, b[\text {. }
$$

#### Proof:

Let $f^{\prime}(x)>0$ for all $\left.x \in\right] a, b[$.
Let $\left.x_{1}, x_{2} \in\right] a, b\left[\right.$ such that $x_{1}<x_{2}$.
Then, clearly $f(x)$ is continuous on $\left[x_{1}, x_{2}\right]$ and differentiable on $] x_{1}, x_{2}[$.
So, by the mean-value theorem, there exists a real number $c \in] x_{1}, x_{2}[$ such that $\quad f^{\prime}(c)=\frac{f\left(x_{2}\right)-f\left(x_{1}\right)}{\left(x_{2}-x_{1}\right)}$.

Since $f^{\prime}(x)>0$ for all $\left.x \in\right] a, b\left[\right.$, in particular, $f^{\prime}(c)>0$.
Now, $\quad f^{\prime}(c)>0 \Rightarrow \frac{f\left(x_{2}\right)-f\left(x_{1}\right)}{\left(x_{2}-x_{1}\right)}>0$

$$
\begin{aligned}
& \Rightarrow f\left(x_{2}\right)-f\left(x_{1}\right)>0 \quad\left[\because x_{2}-x_{1}>0 \text { when } x_{1}<x_{2}\right] \\
& \Rightarrow f\left(x_{2}\right)>f\left(x_{1}\right) \Rightarrow f\left(x_{1}\right)<f\left(x_{2}\right) .
\end{aligned}
$$

Thus, $x_{1}<x_{2} \Rightarrow f\left(x_{1}\right)<f\left(x_{2}\right)$.
Hence, $f(x)$ is an increasing function on $] a, b[$.

---

### Theorem 2

Let $f(x)$ be a function, continuous on $[a, b]$ and differentiable on $] a, b[$. Then, $f^{\prime}(x)<0$ for all $\left.x \in\right] a, b[\Rightarrow f(x)$ is decreasing on $] a, b[$.

#### Proof:

Let it be given that $f^{\prime}(x)<0$ for all $\left.x \in\right] a, b[$.
Let $\left.x_{1}, x_{2} \in\right] a, b\left[\right.$ such that $x_{1}<x_{2}$.
Then, $f(x)$ is continuous on $\left[x_{1}, x_{2}\right]$ and differentiable on $] x_{1}, x_{2}[$.
So, by the mean-value theorem, there exists a real number $c \in] x_{1}, x_{2}[$ such that $\quad f^{\prime}(c)=\frac{f\left(x_{2}\right)-f\left(x_{1}\right)}{\left(x_{2}-x_{1}\right)}$.

Since, $f^{\prime}(x)<0$ for all $\left.x \in\right] a, b\left[\right.$, in particular, $f^{\prime}(c)<0$.
Now, $\quad f^{\prime}(c)<0 \Rightarrow \frac{f\left(x_{2}\right)-f\left(x_{1}\right)}{\left(x_{2}-x_{1}\right)}<0$

$$
\begin{aligned}
& \Rightarrow f\left(x_{2}\right)-f\left(x_{1}\right)<0\left[\because \quad x_{2}-x_{1}>0 \text { when } x_{1}<x_{2}\right] \\
& \Rightarrow f\left(x_{2}\right)<f\left(x_{1}\right) \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right) .
\end{aligned}
$$

Thus, $\quad x_{1}<x_{2} \Rightarrow f\left(x_{1}\right)>f\left(x_{2}\right)$.
This shows that $f(x)$ is decreasing on $] a, b[$.

---

## Summary

1.  If $f^{\prime}(x)>0$ for all $\left.x \in\right] a, b[$ then $f(x)$ is increasing on $] a, b[$.
2.  If $f^{\prime}(x)<0$ for all $\left.x \in\right] a, b[$ then $f(x)$ is decreasing on $] a, b[$.

---

### Corollary 1

If $f^{\prime}(x)>0$ for all $\left.x \in\right] a, b[$, except for a finite number of points where $f^{\prime}(x)=0$ then the function is increasing on $] a, b[$.

#### Proof:

Let $f^{\prime}(x)>0$ for all $\left.x \in\right] a, b\left[\right.$ except at one point $c$, where $f^{\prime}(c)=0$.
Then, $f^{\prime}(x)>0$ for all $\left.x \in\right] a, c\left[\right.$ and $f^{\prime}(x)>0$ for all $\left.x \in\right] c, b[$.
Thus, $f(x)$ is increasing on $] a, c[$ as well as on $] c, b[$.

Hence, $f(x)$ is increasing on $] a, b[$.
The result may now be extended to the case when $f^{\prime}(x)=0$ at a finite number of points.

---

### Corollary 2

If $f^{\prime}(x)<0$ for all $\left.x \in\right] a, b[$, except for a finite number of points where $f^{\prime}(x)=0$, then $f(x)$ is decreasing on $] a, b[$.

#### Proof:

It is similar to that of Corollary 1.

---

## Two Important Results

- **I.**
    - (i) If $f^{\prime}(x) \geq 0$ for all $\left.x \in\right] a, b[$ then $f(x)$ is increasing on $[a, b]$.
    - (ii) If $f^{\prime}(x)>0$ for all $\left.x \in\right] a, b[$ then $f(x)$ is strictly increasing on $[a, b]$.
- **II.**
    - (i) If $f^{\prime}(x) \leq 0$ for all $\left.x \in\right] a, b[$ then $f(x)$ is decreasing on $[a, b]$.
    - (ii) If $f^{\prime}(x)<0$ for all $\left.x \in\right] a, b[$ then $f(x)$ is strictly decreasing on $[a, b]$.

---

## Solved Examples

### Example 1:

Show that the function $f(x)=\left(x^{3}-6 x^{2}+12 x-18\right)$ is an increasing function on $R$.
[CBSE 2002C]

#### Solution:

$f(x)=\left(x^{3}-6 x^{2}+12 x-18\right)$

$$
\begin{aligned}
\Rightarrow f^{\prime}(x) & =3 x^{2}-12 x+12 \\
& =3\left(x^{2}-4 x+4\right)=3(x-2)^{2} \geq 0 \text { for all } x \in R
\end{aligned}
$$

Thus, $f^{\prime}(x) \geq 0$ for all $x \in R$.
Hence, $f(x)$ is an increasing function on $R$.

---

### Example 2:

Show that the function $f(x)=e^{x}$ is strictly increasing on $R$.

#### Solution:

$f(x)=e^{x} \Rightarrow f^{\prime}(x)=e^{x}$

**Case I: When $x>0$**
In this case, $e^{x}=\left(1+x+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\ldots\right)>1$

$$
\begin{aligned}
& \Rightarrow e^{x}>0 \text { for all } x>0 \\
& \Rightarrow f^{\prime}(x)>0 \text { for all } x>0
\end{aligned}
$$

**Case II: When $x=0$**
In this case, $e^{x}=e^{0}=1>0$

$$
\Rightarrow \quad f^{\prime}(x)>0 \text { when } x=0
$$

**Case III: When $x<0$**
Let $x=-y$, where $y$ is positive.

Then, $e^{x}=e^{-y}=\frac{1}{e^{y}}=\frac{1}{(\mathrm{a}+\mathrm{ve} \text { quantity })}>0$.
So, $f^{\prime}(x)>0$ when $x<0$.
Thus, from all the cases, we have $f^{\prime}(x)>0$ for all $x \in R$.
Hence, $f(x)$ is strictly increasing for all $x \in R$.

---

### Example 3:

Show that $f(x)=e^{1 / x}$ is a strictly decreasing function for all $x>0$.

#### Solution:

$f(x)=e^{1 / x} \Rightarrow f^{\prime}(x)=-\frac{1}{x^{2}} e^{1 / x}<0$ for all $x>0$

$$
\left[\because \quad x^{2}>0 \text { and } e^{1 / x}>0 \text { when } x>0\right] .
$$

Thus, $f^{\prime}(x)<0$ for all $x>0$.
Hence, $f(x)$ is strictly decreasing for all $x>0$.

---

### Example 4:

Show that $f(x)=(x-1) e^{x}+1$ is a strictly increasing function for all $x>0$.

#### Solution:

$$
\begin{aligned}
f(x)=(x-1) e^{x}+1 \Rightarrow & f^{\prime}(x)=(x-1) e^{x}+e^{x} \\
\Rightarrow & f^{\prime}(x)=x e^{x}>0 \text { for all } x>0 \\
& \quad\left[\because x>0 \text { and } e^{x}>0 \text { when } x>0\right] .
\end{aligned}
$$

Thus, $f^{\prime}(x)>0$ for all $x>0$.
Hence, $f(x)$ is a strictly increasing function for all $x>0$.

---

### Example 5:

Show that the function $f(x)=(x-\sin x)$ is increasing for all $x \in R$.

#### Solution:

$$
\begin{aligned}
& f(x)=(x-\sin x) \\
\Rightarrow & f^{\prime}(x)=(1-\cos x) \geq 0 \text { for all } x \in R \quad[\because \quad-1 \leq \cos x \leq 1] \\
\Rightarrow & f^{\prime}(x) \geq 0 \text { for all } x \in R .
\end{aligned}
$$

Hence, $f(x)=(x-\sin x)$ is increasing for all $x \in R$.

---

### Example 6:

Show that the function $f(x)=\cos ^{2} x$ is strictly decreasing on $] 0, \frac{\pi}{2}[$.

#### Solution:

$$
\begin{aligned}
& f(x)=\cos ^{2} x \\
\Rightarrow & \left.f^{\prime}(x)=-2 \cos x \sin x=-(\sin 2 x)<0 \text { in }\right] 0, \frac{\pi}{2}[ \\
& {[\because \sin 2 x>0 \text { in the } 1 \text { st quadrant }] } \\
\Rightarrow & \left.f^{\prime}(x)<0 \text { for all } x \in\right] 0, \frac{\pi}{2}[.
\end{aligned}
$$

Hence, $f(x)=\cos ^{2} x$ is strictly decreasing on $] 0, \frac{\pi}{2}[$.

---

### Example 7:

Show that $f(x)=\log \sin x$ is (a) strictly increasing on $] 0, \frac{\pi}{2}[$ and (b) strictly decreasing on $] \frac{\pi}{2}, \pi[$.

#### Solution:

$$
\begin{align*}
& f(x)=\log \sin x \\
\Rightarrow \quad & f^{\prime}(x)=\frac{1}{\sin x} \cdot \cos x \Rightarrow f^{\prime}(x)=\cot x \tag{i}
\end{align*}
$$

- (a) We know that for each $x \in] 0, \frac{\pi}{2}[$,

$$
f^{\prime}(x)=\cot x>0
$$

$\therefore f(x)$ is strictly increasing in $] 0, \frac{\pi}{2}[$.

- (b) We know that for each $x \in] \frac{\pi}{2}, \pi[$,

$$
f^{\prime}(x)=\cot x<0
$$

$\therefore f(x)$ is strictly decreasing in $] \frac{\pi}{2}, \pi[$.

---

### Example 8:

Show that the function $f(x)=\sin x$ is
(a) strictly increasing on $] 0, \frac{\pi}{2}[$
(b) strictly decreasing on $] \frac{\pi}{2}, \pi[$
(c) neither increasing nor decreasing on $] 0, \pi[$

#### Solution:

$f(x)=\sin x \Rightarrow f^{\prime}(x)=\cos x$.

- (a) We know that for each $x \in] 0, \frac{\pi}{2}[, \cos x>0$.
$\therefore f^{\prime}(x)>0$ for all $\left.x \in\right] 0, \frac{\pi}{2}[$.
Hence, $f(x)$ is increasing on $] 0, \frac{\pi}{2}[$.

- (b) We know that for each $x \in] \frac{\pi}{2}, \pi[, \cos x<0$.
$\therefore \quad f^{\prime}(x)<0$ for all $\left.x \in\right] \frac{\pi}{2}, \pi[$.
Hence, $f(x)$ is decreasing on $] \frac{\pi}{2}, \pi[$.

- (c) It follows from the above two results that $f(x)=\sin x$ is increasing on $] 0, \frac{\pi}{2}[$ and decreasing on $] \frac{\pi}{2}, \pi[$.
So, it is neither increasing nor decreasing on $] 0, \pi[$.

---

### Example 9:

Show that the function $f(x)=\left(x^{2}-x+1\right)$ is neither increasing nor decreasing on $] 0,1[$.

#### Solution:

$f(x)=\left(x^{2}-x+1\right) \Rightarrow f^{\prime}(x)=(2 x-1)$.

Now, $f^{\prime}(x)>0 \Leftrightarrow(2 x-1)>0 \Leftrightarrow x>\frac{1}{2}$.
$\therefore f(x)$ is increasing when $x \in] \frac{1}{2}, 1[$.
And, $f^{\prime}(x)<0 \quad \Leftrightarrow \quad(2 x-1)<0 \quad \Leftrightarrow \quad x<\frac{1}{2}$.
$\therefore f(x)$ is decreasing when $x \in] 0, \frac{1}{2}[$.
Hence, the given function is neither increasing nor decreasing on ]0, 1 [.

---

### Example 10:

Prove that the function $f(x)=10^{x}$ is strictly increasing on $R$.

#### Solution:

$f(x)=10^{x} \Rightarrow f^{\prime}(x)=\left(10^{x}\right)(\log 10)>0$ for all $x \in R$.
Hence, $f(x)=10^{x}$ is strictly increasing on $R$.

---

### Example 11:

Show that $f(x)=\tan ^{-1}(\cos x+\sin x)$ is a strictly increasing function on the interval $\left(0, \frac{\pi}{4}\right)$.
[CBSE 2007]

#### Solution:

$f(x)=\tan ^{-1}(\cos x+\sin x)$

$$
\begin{aligned}
\Rightarrow f^{\prime}(x) & =\frac{1}{1+(\cos x+\sin x)^{2}} \cdot \frac{d}{d x}(\cos x+\sin x) \\
& =\frac{(-\sin x+\cos x)}{\left(1+\cos ^{2} x+\sin ^{2} x+2 \sin x \cos x\right)} \\
& =\frac{(\cos x-\sin x)}{(2+\sin 2 x)}
\end{aligned}
$$

Now, when $0<x<\frac{\pi}{4}$, we have $\cos x>\sin x$ and $\sin 2 x>0$.
$\therefore \quad(\cos x-\sin x)>0$ and $(2+\sin 2 x)>0$.
$\therefore f^{\prime}(x)>0$ for all $x$ when $0<x<\frac{\pi}{4}$.
Hence, $f(x)$ is strictly increasing in $\left(0, \frac{\pi}{4}\right)$.

---

### Example 12:

Find the intervals on which the function $f(x)=10-6 x-2 x^{2}$ is
(a) strictly increasing (b) strictly decreasing.

#### Solution:

$$
\begin{align*}
& f(x)=10-6 x-2 x^{2} \\
\Rightarrow & f^{\prime}(x)=-6-4 x=-2(3+2 x)=-4\left(x+\frac{3}{2}\right) \tag{i}
\end{align*}
$$

- (a) $f(x)$ is strictly increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x)>0 \\
& \Leftrightarrow \quad-4\left(x+\frac{3}{2}\right)>0 \quad[\text { from (i) }]
\end{aligned}
$$

$$
\Leftrightarrow \quad\left(x+\frac{3}{2}\right)<0 \Leftrightarrow x<\frac{-3}{2} .
$$

$\therefore f(x)$ is strictly increasing on the interval $]-\infty, \frac{-3}{2}[$.

- (b) $f(x)$ is strictly decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x)<0 \\
& \Leftrightarrow \quad-4\left(x+\frac{3}{2}\right)<0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad\left(x+\frac{3}{2}\right)>0 \\
& \Leftrightarrow \quad x>\frac{-3}{2} .
\end{aligned}
$$

$\therefore f(x)$ is strictly decreasing on the interval $] \frac{-3}{2}, \infty[$.
Hence, $f(x)$ is strictly increasing on the interval $]-\infty, \frac{-3}{2}[$ and strictly decreasing on $] \frac{-3}{2}, \infty[$.

---

### Example 13:

Find the intervals on which the function $f(x)=-2 x^{3}-9 x^{2}-12 x+1$ is (a) strictly increasing (b) strictly decreasing.

#### Solution:

$$
\begin{align*}
& f(x)=-2 x^{3}-9 x^{2}-12 x+1 \\
\Rightarrow & f^{\prime}(x)=-6 x^{2}-18 x-12=-6\left(x^{2}+3 x+2\right)=-6(x+2)(x+1) \tag{i}
\end{align*}
$$

- (a) $f(x)$ is strictly increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x)>0 \\
& \Leftrightarrow \quad-6(x+2)(x+1)>0 \quad[\text { from }(i)] \\
& \Leftrightarrow \quad(x+2)(x+1)<0 \\
& \Leftrightarrow \quad-2<x<-1 \\
& \Leftrightarrow \quad x \in]-2,-1[.
\end{aligned}
$$

$\therefore f(x)$ is strictly increasing on the interval $]-2,-1[$.

- (b) $f(x)$ is strictly decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x)<0 \\
& \Leftrightarrow \quad-6(x+2)(x+1)<0 \quad \quad[\text { from }(\mathrm{i})] \\
& \Leftrightarrow \quad(x+2)(x+1)>0 \\
& \Leftrightarrow \quad[(x+2)>0 \text { and }(x+1)>0] \\
& \quad \text { or }[(x+2)<0 \text { and }(x+1)<0] \\
& \Leftrightarrow \quad(x>-2 \text { and } x>-1) \text { or }(x<-2 \text { and } x<-1) \\
& \Leftrightarrow \quad(x>-1) \text { or }(x<-2) \\
& \Leftrightarrow \quad x \in]-1, \infty[\text { or } x \in]-\infty,-2[ \\
& \Leftrightarrow \quad x \in]-\infty,-2[\cup]-1, \infty[.
\end{aligned}
$$

$\therefore f(x)$ is strictly decreasing on $]-\infty,-2[\cup]-1, \infty[$.

---

### Example 14:

Find the intervals on which the function $f(x)=2 x^{3}-15 x^{2}+36 x+6$ is (a) increasing (b) decreasing.
[CBSE 2004C, '05, '09C]

#### Solution:

$$
\begin{align*}
& f(x)=2 x^{3}-15 x^{2}+36 x+6 \\
\Rightarrow & f^{\prime}(x)=6 x^{2}-30 x+36=6\left(x^{2}-5 x+6\right)=6(x-3)(x-2) \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad 6(x-3)(x-2) \geq 0 \quad \quad[\text { from (i) }] \\
& \Leftrightarrow \quad(x-3)(x-2) \geq 0 \\
& \Leftrightarrow \quad[(x-3) \geq 0 \text { and }(x-2) \geq 0] \\
& \text { or } \quad[(x-3) \leq 0 \text { and }(x-2) \leq 0] \\
& \Leftrightarrow \quad[x \geq 3 \text { and } x \geq 2] \text { or }[x \leq 3 \text { and } x \leq 2] \\
& \Leftrightarrow \quad[x \geq 3] \text { or }[x \leq 2] \\
& \Leftrightarrow \quad x \in[3, \infty[\text { or } x \in]-\infty, 2] \\
& \Leftrightarrow \quad x \in]-\infty, 2] \cup[3, \infty] . \\
& \therefore f(x) \text { is increasing on }]-\infty, 2] \cup[3, \infty[.
\end{aligned}
$$

(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \leq 0 \\
& \Leftrightarrow \quad 6(x-3)(x-2) \leq 0 \quad[\text { from }(\mathrm{i})] \\
& \Leftrightarrow \quad(x-3)(x-2) \leq 0 \\
& \Leftrightarrow \quad 2 \leq x \leq 3 \\
& \Leftrightarrow \quad x \in[2,3] .
\end{aligned}
$$

$\therefore f(x)$ is decreasing on $[2,3]$.
Hence, $f(x)$ is increasing on $]-\infty, 2] \cup[3, \infty[$ and decreasing on $[2, 3]$.

---

### Example 15:

Find the intervals on which the function $f(x)=x^{3}+2 x^{2}-1$ is
(a) increasing (b) decreasing.

#### Solution:

$$
\begin{align*}
& f(x)=x^{3}+2 x^{2}-1 \\
\Rightarrow \quad & f^{\prime}(x)=3 x^{2}+4 x=3 x\left(x+\frac{4}{3}\right) \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad 3 x\left(x+\frac{4}{3}\right) \geq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad x\left(x+\frac{4}{3}\right) \geq 0 \\
& \Leftrightarrow \quad\left[x \geq 0 \text { and }\left(x+\frac{4}{3}\right) \geq 0\right] \text { or }\left[x \leq 0 \text { and }\left(x+\frac{4}{3}\right) \leq 0\right] \\
& \Leftrightarrow \quad\left[x \geq 0 \text { and } x \geq-\frac{4}{3}\right] \text { or }\left[x \leq 0 \text { and } x \leq-\frac{4}{3}\right] \\
& \Leftrightarrow \quad(x \geq 0) \text { or }\left(x \geq-\frac{4}{3}\right)
\end{aligned}
$$

$$
\begin{gathered}
\Leftrightarrow x \in\left[0, \infty[\text { or } x \in]-\infty,-\frac{4}{3}\right] \\
\left.\Leftrightarrow x \in]-\infty,-\frac{4}{3}\right] \cup[0, \infty[. \\
\left.\therefore f(x) \text { is increasing on }]-\infty,-\frac{4}{3}\right] \cup[0, \infty[.
\end{gathered}
$$

(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \leq 0 \\
& \Leftrightarrow \quad 3 x\left(x+\frac{4}{3}\right) \leq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad x\left(x+\frac{4}{3}\right) \leq 0 \\
& \Leftrightarrow \quad-\frac{4}{3} \leq x \leq 0 \\
& \Leftrightarrow \quad x \in\left[-\frac{4}{3}, 0\right] .
\end{aligned}
$$

$\therefore f(x)$ is decreasing on $\left[-\frac{4}{3}, 0\right]$.
Hence, $f(x)$ is increasing on $\left.]-\infty,-\frac{4}{3}\right] \cup[0, \infty[$ and decreasing on $\left[-\frac{4}{3}, 0\right]$.

---

### Example 16:

Find the intervals on which the function $f(x)=x^{3}+3 x^{2}-105 x+25$ is (a) increasing (b) decreasing.

#### Solution:

$$
\begin{align*}
& f(x)=x^{3}+3 x^{2}-105 x+25 \\
\Rightarrow & f^{\prime}(x)=3 x^{2}+6 x-105=3\left(x^{2}+2 x-35\right)=3(x+7)(x-5) \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad 3(x+7)(x-5) \geq 0 \quad \quad[\text { from (i) }] \\
& \Leftrightarrow \quad(x+7)(x-5) \geq 0 \\
& \Leftrightarrow \quad[(x+7) \geq 0 \text { and }(x-5) \geq 0] \text { or }[(x+7) \leq 0 \text { and }(x-5) \leq 0] \\
& \Leftrightarrow \quad[x \geq-7 \text { and } x \geq 5] \text { or }[x \leq-7 \text { and } x \leq 5] \\
& \Leftrightarrow \quad(x \geq 5) \text { or }(x \leq-7) \\
& \Leftrightarrow \quad x \in[5, \infty[\text { or } x \in]-\infty,-7] \\
& \Leftrightarrow \quad x \in]-\infty,-7] \cup[5, \infty[. \\
& \therefore f(x) \text { is increasing on }]-\infty,-7] \cup[5, \infty[.
\end{aligned}
$$

(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \leq 0 \\
& \Leftrightarrow \quad 3(x+7)(x-5) \leq 0 \quad[\text { from }(\mathrm{i})] \\
& \Leftrightarrow \quad(x+7)(x-5) \leq 0 \\
& \Leftrightarrow \quad-7 \leq x \leq 5 \\
& \Leftrightarrow \quad x \in[-7,5] .
\end{aligned}
$$

$\therefore f(x)$ is decreasing on $[-7,5]$.
Hence, $f(x)$ is increasing on $]-\infty,-7] \cup[5, \infty[$ and decreasing on $[-7,5]$.

---

### Example 17:

Find the intervals on which the function $f(x)=5+36 x+3 x^{2}-2 x^{3}$ is (a) increasing (b) decreasing.

#### Solution:

$$
\begin{align*}
& f(x)=5+36 x+3 x^{2}-2 x^{3} \\
\Rightarrow \quad & f^{\prime}(x)=36+6 x-6 x^{2}=-6\left(x^{2}-x-6\right)=-6(x+2)(x-3) \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad-6(x+2)(x-3) \geq 0 \quad[\text { from }(\mathrm{i})] \\
& \Leftrightarrow \quad(x+2)(x-3) \leq 0 \\
& \Leftrightarrow \quad-2 \leq x \leq 3 \\
& \Leftrightarrow \quad x \in[-2,3] .
\end{aligned}
$$

$\therefore f(x)$ is increasing on $[-2,3]$.
(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \leq 0 \\
& \Leftrightarrow \quad-6(x+2)(x-3) \leq 0 \quad \quad[\text { from }(\mathrm{i})] \\
& \Leftrightarrow \quad(x+2)(x-3) \leq 0 \\
& \Leftrightarrow \quad[(x+2) \geq 0 \text { and }(x-3) \geq 0] \text { or }[(x+2) \leq 0 \text { and }(x-3) \leq 0] \\
& \Leftrightarrow \quad[x \geq-2 \text { and } x \geq 3] \text { or }[x \leq-2 \text { and } x \leq 3] \\
& \Leftrightarrow \quad(x \geq 3) \text { or }(x \leq-2) \\
& \Leftrightarrow \quad x \in[3, \infty[\text { or } x \in]-\infty,-2] \\
& \Leftrightarrow \quad x \in]-\infty,-2] \cup[3, \infty[.
\end{aligned}
$$

$\therefore f(x)$ is decreasing on $]-\infty,-2] \cup[3, \infty[$.
Hence, $f(x)$ is increasing on $[-2,3]$ and decreasing on $]-\infty,-2] \cup[3, \infty[$.

---

### Example 18:

Find the intervals on which the function $f(x)=(x+1)^{3}(x-3)^{3}$ is
(a) increasing (b) decreasing.
[CBSE 2001C]

#### Solution:

$$
\begin{align*}
f(x) & =(x+1)^{3}(x-3)^{3} \\
\Rightarrow \quad f^{\prime}(x) & =(x+1)^{3} \cdot \frac{d}{d x}(x-3)^{3}+(x-3)^{3} \cdot \frac{d}{d x}(x+1)^{3} \\
& =(x+1)^{3} \cdot 3(x-3)^{2}+(x-3)^{3} \cdot 3(x+1)^{2} \\
& =3(x+1)^{2}(x-3)^{2}[(x+1)+(x-3)] \\
& =6(x+1)^{2}(x-3)^{2}(x-1) \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad 6(x+1)^{2}(x-3)^{2}(x-1) \geq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad(x-1) \geq 0 \\
& \Leftrightarrow \quad x \geq 1 \\
& \Leftrightarrow \quad x \in[1, \infty[.
\end{aligned}
$$

$\therefore f(x)$ is increasing on $[1, \infty[$.
(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow f^{\prime}(x) \leq 0 \\
& \Leftrightarrow 6(x+1)^{2}(x-3)^{2}(x-1) \leq 0 \quad \text { [from (i)] } \\
& \Leftrightarrow \quad(x-1) \leq 0 \quad \Leftrightarrow \quad x \leq 1 \\
& \Leftrightarrow \quad x \in]-\infty, 1]
\end{aligned}
$$

$\therefore f(x)$ is decreasing on $]-\infty, 1]$.
Hence, $f(x)$ is increasing on $[1, \infty[$ and decreasing on $]-\infty, 1]$.

---

### Example 19:

Find the intervals on which the function $f(x)=\frac{4 x^{2}+1}{x},(x \neq 0)$ is
(a) increasing (b) decreasing.
[CBSE 2004]

#### Solution:

$f(x)=\frac{4 x^{2}+1}{x}, x \neq 0$
$\Rightarrow f(x)=\left(4 x+\frac{1}{x}\right), x \neq 0$
$\Rightarrow \quad f^{\prime}(x)=\left(4-\frac{1}{x^{2}}\right)$

$$
\begin{equation*}
\Rightarrow f^{\prime}(x)=\frac{\left(4 x^{2}-1\right)}{x^{2}} \tag{i}
\end{equation*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow f^{\prime}(x) \geq 0 \Leftrightarrow \frac{\left(4 x^{2}-1\right)}{x^{2}} \geq 0 \quad \text { [from (i)] } \\
& \Leftrightarrow \quad\left(4 x^{2}-1\right) \geq 0 \quad\left[\because x^{2}>0\right] \\
& \Leftrightarrow \quad(2 x-1)(2 x+1) \geq 0 \Leftrightarrow 2\left(x-\frac{1}{2}\right) \cdot 2\left(x+\frac{1}{2}\right) \geq 0 \\
& \Leftrightarrow \quad\left(x-\frac{1}{2}\right)\left(x+\frac{1}{2}\right) \geq 0 \\
& \Leftrightarrow\left[\left(x-\frac{1}{2}\right) \geq 0 \text { and }\left(x+\frac{1}{2}\right) \geq 0\right] \\
& \text { or }\left[\left(x-\frac{1}{2}\right) \leq 0 \text { and }\left(x+\frac{1}{2}\right) \leq 0\right] \\
& \Leftrightarrow\left[x \geq \frac{1}{2} \text { and } x \geq-\frac{1}{2}\right] \text { or }\left[x \leq \frac{1}{2} \text { and } x \leq-\frac{1}{2}\right] \\
& \Leftrightarrow\left(x \geq \frac{1}{2}\right) \text { or }\left(x \leq-\frac{1}{2}\right) \\
& \Leftrightarrow x \in\left[\frac{1}{2}, \infty[\text { or } x \in]-\infty,-\frac{1}{2}\right] \\
& \left.\Leftrightarrow x \in]-\infty,-\frac{1}{2}\right] \cup\left[\frac{1}{2}, \infty[.\right. \\
& \left.\therefore f(x) \text { is increasing on }]-\infty,-\frac{1}{2}\right] \cup\left[\frac{1}{2}, \infty[.\right.
\end{aligned}
$$

(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow f^{\prime}(x) \leq 0 \Leftrightarrow \frac{\left(4 x^{2}-1\right)}{x^{2}} \leq 0 \quad \quad[\text { from (i) }] \\
& \Leftrightarrow \quad\left(4 x^{2}-1\right) \leq 0 \quad\left[\because x^{2}>0\right] \\
& \Leftrightarrow \quad(2 x-1)(2 x+1) \leq 0 \Leftrightarrow 2\left(x-\frac{1}{2}\right) \cdot 2\left(x+\frac{1}{2}\right) \leq 0 \\
& \Leftrightarrow \quad\left(x-\frac{1}{2}\right)\left(x+\frac{1}{2}\right) \leq 0 \\
& \Leftrightarrow \quad-\frac{1}{2} \leq x \leq \frac{1}{2} \\
& \Leftrightarrow \quad x \in\left[-\frac{1}{2}, \frac{1}{2}\right] . \\
& \therefore f(x) \text { is decreasing on }\left[-\frac{1}{2}, \frac{1}{2}\right] .
\end{aligned}
$$

Hence, $f(x)$ is increasing on $\left.]-\infty,-\frac{1}{2}\right] \cup\left[\frac{1}{2}, \infty[\right.$ and decreasing on $\left[-\frac{1}{2}, \frac{1}{2}\right]$.

---

### Example 20:

Find the intervals on which the function $f(x)=\frac{x}{\left(x^{2}+1\right)}$ is
(a) increasing
(b) decreasing.
[CBSE 2003]

#### Solution:

$$
\begin{align*}
& f(x)=\frac{x}{\left(x^{2}+1\right)} \\
\Rightarrow & f^{\prime}(x)=\frac{\left(x^{2}+1\right) \cdot \frac{d}{d x}(x)-x \cdot \frac{d}{d x}\left(x^{2}+1\right)}{\left(x^{2}+1\right)^{2}}=\frac{\left(x^{2}+1\right) \cdot 1-x \cdot 2 x}{\left(x^{2}+1\right)^{2}} \\
\Rightarrow & f^{\prime}(x)=\frac{\left(1-x^{2}\right)}{\left(x^{2}+1\right)^{2}} \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{array}{ll}
\Leftrightarrow & f^{\prime}(x) \geq 0 \\
\Leftrightarrow & \frac{\left(1-x^{2}\right)}{\left(x^{2}+1\right)^{2}} \geq 0 \quad[\text { from (i) }] \\
\Leftrightarrow & \left(1-x^{2}\right) \geq 0 \quad\left[\because\left(x^{2}+1\right)^{2}>0\right] \\
\Leftrightarrow & -\left(1-x^{2}\right) \leq 0 \Leftrightarrow\left(x^{2}-1\right) \leq 0 \\
\Leftrightarrow & (x-1)(x+1) \leq 0 \\
\Leftrightarrow & -1 \leq x \leq 1 \\
\Leftrightarrow & x \in[-1,1] .
\end{array}
$$

$\therefore f(x)$ is increasing on $[-1,1]$.
(b) $f(x)$ is decreasing

$$
\Leftrightarrow \quad f^{\prime}(x) \leq 0
$$

$$
\begin{aligned}
& \Leftrightarrow \quad \frac{\left(1-x^{2}\right)}{\left(x^{2}+1\right)^{2}} \leq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad\left(1-x^{2}\right) \leq 0 \quad\left[\because\left(x^{2}+1\right)^{2}>0\right] \\
& \Leftrightarrow-\left(1-x^{2}\right) \geq 0 \\
& \Leftrightarrow \quad\left(x^{2}-1\right) \leq 0 \quad \Leftrightarrow \quad(x-1)(x+1) \geq 0 \\
& \Leftrightarrow \quad[(x-1) \geq 0 \text { and }(x+1) \geq 0] \text { or }[(x-1) \leq 0 \text { and }(x+1) \leq 0] \\
& \Leftrightarrow \quad[x \geq 1 \text { and } x \geq-1] \text { or }[x \leq 1 \text { and } x \leq-1] \\
& \Leftrightarrow \quad(x \geq 1) \text { or }(x \leq-1) \\
& \Leftrightarrow \quad x \in[1, \infty[\text { or } x \in]-\infty,-1] \\
& \Leftrightarrow \quad x \in]-\infty,-1] \cup[1, \infty[. \\
& \therefore f(x) \text { is decreasing on }]-\infty,-1] \cup[1, \infty[.
\end{aligned}
$$

Hence, $f(x)$ is increasing on $[-1,1]$ and decreasing on $]-\infty,-1] \cup[1, \infty[$.

---

### Example 21:

Find the intervals on which the function $f(x)=(x+2) e^{-x}$ is
(a) increasing
(b) decreasing.
[CBSE 2000C]

#### Solution:

$$
\begin{align*}
& f(x)=(x+2) e^{-x} \\
\Rightarrow & f^{\prime}(x)=-(x+2) e^{-x}+e^{-x} \cdot 1 \\
\Rightarrow & f^{\prime}(x)=-(x+1) e^{-x} \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad-(x+1) e^{-x} \geq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad(x+1) e^{-x} \leq 0 \\
& \Leftrightarrow \quad(x+1) \leq 0 \quad\left[\because e^{-x}>0\right] \\
& \Leftrightarrow \quad x \leq-1 \quad \Leftrightarrow \quad x \in]-\infty,-1]
\end{aligned}
$$

$\therefore f(x)$ is increasing on $]-\infty,-1]$.
(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \leq 0 \\
& \Leftrightarrow \quad-(x+1) e^{-x} \leq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad(x+1) e^{-x} \geq 0 \\
& \Leftrightarrow \quad(x+1) \geq 0 \\
& \Leftrightarrow \quad x \geq-1 \\
& \Leftrightarrow \quad x \in[-1, \infty[. \\
& \therefore \quad f(x) \text { is decreasing on }[-1, \infty[.
\end{aligned}
$$

Hence, $f(x)$ is increasing on $]-\infty,-1]$ and decreasing on $[-1, \infty[$.

---

### Example 22:

Find the intervals on which the function $f(x)=\log (1+x)-\frac{x}{(1+x)}$ is
(a) increasing
(b) decreasing.
[CBSE 2000C]

#### Solution:

$f(x)=\log (1+x)-\frac{x}{(1+x)}$

$$
\begin{align*}
\Rightarrow f^{\prime}(x) & =\left\{\frac{1}{(1+x)}-\frac{(1+x) \cdot 1-x \cdot 1}{(1+x)^{2}}\right\} \\
& =\left\{\frac{1}{(1+x)}-\frac{1}{(1+x)^{2}}\right\}=\frac{(1+x-1)}{(1+x)^{2}} \\
\Rightarrow f^{\prime}(x) & =\frac{x}{(1+x)^{2}} \tag{i}
\end{align*}
$$

(a) $f(x)$ is increasing

$$
\begin{array}{ll}
\Leftrightarrow & f^{\prime}(x) \geq 0 \\
\Leftrightarrow & \frac{x}{(1+x)^{2}} \geq 0 \\
\Leftrightarrow & \quad[\text { from (i) }] \\
\Leftrightarrow & \quad\left[\because(1+x)^{2} \geq 0\right] \\
\Leftrightarrow & x \in[0, \infty[.
\end{array}
$$

(b) $f(x)$ is decreasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \leq 0 \\
& \Leftrightarrow \quad \frac{x}{(1+x)^{2}} \leq 0 \quad \quad \text { [from (i)] } \\
& \Leftrightarrow \quad x \leq 0 \\
& \Leftrightarrow \quad x \in]-\infty, 0]
\end{aligned}
$$

Hence, $f(x)$ is increasing on $[0, \infty[$ and decreasing on $]-\infty, 0]$.

---

### Example 23:

Find the intervals on which the function $f(x)=(\sin x-\cos x)$,
$0<x<2 \pi$, is
(a) increasing
(b) decreasing.
[CBSE 2000C, '09, '11]

#### Solution:

$$
\begin{align*}
& f(x)=(\sin x-\cos x), 0<x<2 \pi \\
\Rightarrow & f^{\prime}(x)=(\cos x+\sin x)=\sqrt{2}\left(\frac{1}{\sqrt{2}} \cos x+\frac{1}{\sqrt{2}} \sin x\right) \\
\Rightarrow & f^{\prime}(x)=\sqrt{2}\left(\sin \frac{\pi}{4} \cos x+\cos \frac{\pi}{4} \sin x\right) \\
\Rightarrow & f^{\prime}(x)=\sqrt{2} \sin \left(\frac{\pi}{4}+x\right) \tag{i}
\end{align*}
$$

Now, $0<x<2 \pi \Rightarrow \frac{\pi}{4}<\left(\frac{\pi}{4}+x\right)<\left(\frac{\pi}{4}+2 \pi\right)$

$$
\begin{equation*}
\Rightarrow \frac{\pi}{4}<\left(\frac{\pi}{4}+x\right)<\frac{9 \pi}{4} \tag{ii}
\end{equation*}
$$

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow \quad f^{\prime}(x) \geq 0 \\
& \Leftrightarrow \quad \sqrt{2} \sin \left(\frac{\pi}{4}+x\right) \geq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \quad \sin \left(\frac{\pi}{4}+x\right) \geq 0
\end{aligned}
$$

$\Leftrightarrow\left\{\frac{\pi}{4}<\left(\frac{\pi}{4}+x\right) \leq \pi\right\}$ or $\left\{2 \pi \leq\left(\frac{\pi}{4}+x\right)<\frac{9 \pi}{4}\right\}$
$\Leftrightarrow\left\{0<x \leq \frac{3 \pi}{4}\right\}$ or $\left\{\frac{7 \pi}{4} \leq x<2 \pi\right\}$
$\left.\Leftrightarrow \quad x \in] 0, \frac{3 \pi}{4}\right]$ or $x \in\left[\frac{7 \pi}{4}, 2 \pi[\right.$
$\left.\Leftrightarrow \quad x \in] 0, \frac{3 \pi}{4}\right] \cup\left[\frac{7 \pi}{4}, 2 \pi[\right.$.
$\therefore f(x)$ is increasing on $\left.] 0, \frac{3 \pi}{4}\right] \cup\left[\frac{7 \pi}{4}, 2 \pi[\right.$.

(b) $f(x)$ is decreasing
$\Leftrightarrow \quad f^{\prime}(x) \leq 0$
$\Leftrightarrow \sqrt{2} \sin \left(\frac{\pi}{4}+x\right) \leq 0 \quad$ [from (i)]
$\Leftrightarrow \quad \sin \left(\frac{\pi}{4}+x\right) \leq 0$
$\Leftrightarrow \quad \pi \leq\left(\frac{\pi}{4}+x\right) \leq 2 \pi$
$\Leftrightarrow \quad \frac{3 \pi}{4} \leq x \leq \frac{7 \pi}{4}$
$\Leftrightarrow x \in\left[\frac{3 \pi}{4}, \frac{7 \pi}{4}\right]$.
$\therefore f(x)$ is decreasing on $\left[\frac{3 \pi}{4}, \frac{7 \pi}{4}\right]$.

---

### Example 24:

Separate the interval $\left[0, \frac{\pi}{2}\right]$ into subintervals in which
$f(x)=\left(\sin ^{4} x+\cos ^{4} x\right)$ is (a) increasing (b) decreasing. [CBSE 2000C]

#### Solution:

$f(x)=\left(\sin ^{4} x+\cos ^{4} x\right)$

$$
\begin{align*}
\Rightarrow f^{\prime}(x) & =4 \sin ^{3} x \cos x-4 \cos ^{3} x \sin x \\
& =-4 \sin x \cos x\left(\cos ^{2} x-\sin ^{2} x\right) \\
& =-2 \sin 2 x \cos 2 x=-\sin 4 x \tag{i}
\end{align*}
$$

Also, $0 \leq x \leq \frac{\pi}{2} \Leftrightarrow 0 \leq 4 x \leq 2 \pi$.

(a) $f(x)$ is increasing

$$
\begin{aligned}
& \Leftrightarrow f^{\prime}(x) \geq 0 \\
& \Leftrightarrow-\sin 4 x \geq 0 \quad[\text { from (i) }] \\
& \Leftrightarrow \sin 4 x \leq 0 \\
& \Leftrightarrow \pi \leq 4 x \leq 2 \pi \\
& \Leftrightarrow \frac{\pi}{4} \leq x \leq \frac{\pi}{2}
\end{aligned}
$$

$\Leftrightarrow x \in\left[\frac{\pi}{4}, \frac{\pi}{2}\right]$.
$\therefore f(x)$ is increasing on $\left[\frac{\pi}{4}, \frac{\pi}{2}\right]$.

(b) $f(x)$ is decreasing
$\Leftrightarrow f^{\prime}(x) \leq 0 \quad$ [from (i)]
$\Leftrightarrow-\sin 4 x \leq 0$
$\Leftrightarrow \sin 4 x \geq 0$
$\Leftrightarrow 0 \leq 4 x \leq \pi$
$\Leftrightarrow 0 \leq x \leq \frac{\pi}{4}$
$\Leftrightarrow x \in\left[0, \frac{\pi}{4}\right]$.
$\therefore f(x)$ is decreasing on $\left[0, \frac{\pi}{4}\right]$.
Hence, $f(x)$ is increasing on $\left[\frac{\pi}{4}, \frac{\pi}{2}\right]$ and decreasing on $\left[0, \frac{\pi}{4}\right]$.

---

### Example 25:

Separate $\left[0, \frac{\pi}{2}\right]$ into subintervals in which $f(x)=\sin 3 x$ is
(a) increasing (b) decreasing.

#### Solution:

$f(x)=\sin 3 x \Rightarrow f^{\prime}(x)=3 \cos 3 x$

Also, $0 \leq x \leq \frac{\pi}{2} \Leftrightarrow 0 \leq 3 x \leq \frac{3 \pi}{2}$
(a) $f(x)$ is increasing
$\Leftrightarrow f^{\prime}(x) \geq 0$
$\Leftrightarrow 3 \cos 3 x \geq 0 \Leftrightarrow \cos 3 x \geq 0 \quad$ [from (i)]
$\Leftrightarrow 0 \leq 3 x \leq \frac{\pi}{2}$
$\Leftrightarrow 0 \leq x \leq \frac{\pi}{6}$
$\Leftrightarrow x \in\left[0, \frac{\pi}{6}\right]$.
$\therefore f(x)$ is increasing on $\left[0, \frac{\pi}{6}\right]$.

(b) $f(x)$ is decreasing
$\Leftrightarrow f^{\prime}(x) \leq 0$
$\Leftrightarrow 3 \cos 3 x \leq 0 \Leftrightarrow \cos 3 x \geq 0 \quad$ [from (i)]
$\Leftrightarrow \frac{\pi}{2} \leq 3 x \leq \frac{3 \pi}{2}$
$\Leftrightarrow \frac{\pi}{6} \leq x \leq \frac{\pi}{2}$
$\Leftrightarrow x \in\left[\frac{\pi}{6}, \frac{\pi}{2}\right]$.
$\therefore f(x)$ is decreasing on $\left[\frac{\pi}{6}, \frac{\pi}{2}\right]$.
Hence, $f(x)$ is increasing on $\left[0, \frac{\pi}{6}\right]$ and decreasing on $\left[\frac{\pi}{6}, \frac{\pi}{2}\right]$.

---