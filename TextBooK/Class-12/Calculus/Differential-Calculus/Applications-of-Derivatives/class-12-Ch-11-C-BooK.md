## 3. Rolle's and Lagrange's Theorems

## Rolle's Theorem

Let $f$ be a real-valued function, defined in the closed interval $[a, b]$ such that:
- (i) $f$ is continuous on $[a, b]$;
- (ii) $f$ is differentiable on $] a, b[$;
- (iii) $f(a)=f(b)$.

Then, there exists a real number $c$ in the open interval $] a, b[$ such that $f^{\prime}(c)=0$.

**PROOF** If $f(x)=c$, where $c$ is a constant then $f^{\prime}(x)=0$ for all $x \in] a, b[$.
So, in this case, the theorem follows.

Now, consider the case, when $f$ is not a constant function. Since $f(a)=f(b)$, the function should either increase or decrease, when $x$ takes values slightly greater than $a$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Calculus/Applications-of-Derivatives/class-12-Ch-11-C-BooK-001.jpg)
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Calculus/Applications-of-Derivatives/class-12-Ch-11-C-BooK-002.jpg)

Let $f(x)$ be increasing at $x>a$.
Since $f(b)=f(a)$, $f(x)$ must cease to increase and begin to decrease at some point $x=c \in] a$, $b[$.
Clearly, at such a point, the function has a maximum value. Thus, for a very small and positive value of $h$, we have

$$
\begin{array}{ll} 
& f(c+h)-f(c)<0 \text { and } f(c-h)-f(c)<0 . \\
\therefore & \frac{f(c+h)-f(c)}{h}<0 \text { and } \frac{f(c-h)-f(c)}{-h}>0 . \\
\text { So, } & \lim _{h \rightarrow 0} \frac{f(c+h)-f(c)}{h} \leq 0 \text { and } \lim _{h \rightarrow 0} \frac{f(c-h)-f(c)}{-h} \geq 0 .
\end{array}
$$

But, if $\lim _{h \rightarrow 0} \frac{f(c+h)-f(c)}{h} \neq \lim _{h \rightarrow 0} \frac{f(c-h)-f(c)}{-h}$ then $R f^{\prime}(c) \neq L f^{\prime}(c)$ and this would imply that $f(x)$ is not differentiable at $x=c$, contradicting the given hypothesis.

$$
\therefore \quad \lim _{h \rightarrow 0} \frac{f(c+h)-f(c)}{h}=\lim _{h \rightarrow 0} \frac{f(c-h)-f(c)}{-h}=0 .
$$

Hence, $f^{\prime}(c)=0$, where $a<c<b$.
Similarly, the theorem can be proved for the case when $f(x)$ is initially decreasing for values of $x>a$, and it ceases to decrease at $x=c$.
Hence, there exists $c \in] a, b\left[\right.$ such that $f^{\prime}(c)=0$.

### Remark

Rolle's theorem is applicable to a function only when all the three properties above listed are satisfied by it. If even a single property is violated, we say that the theorem is not applicable on such a function.

### Geometrical Significance of Rolle's Theorem

Let $f$ be a real function defined on $[a, b]$ and let Rolle's theorem be applicable on it. Then, $f$ being continuous on $[a, b]$, it follows that we can draw a graph of $f(x)$ between the values $x=a$ and $x=b$.

Also, $f(x)$ being differentiable in $] a, b[$, it follows that the graph of $f(x)$ has a tangent at each point of $] a, b[$.

Now, the existence of a real number $c \in] a, b\left[\right.$ such that $f^{\prime}(c)=0$ shows that the tangent to the curve at $x=c$ has a slope 0 , i.e., it is parallel to the $x$-axis.

---
## SOLVED EXAMPLES

### Example 1
Verify Rolle's theorem for the function $f(x)=x^{3}-6 x^{2}+11 x-6$ in the interval $[1, 3]$.

#### Solution:

Here, we observe that
- (i) $f(x)$ being a polynomial function of $x$, is continuous on the interval $[1,3]$.
- (ii) $f^{\prime}(x)=3 x^{2}-12 x+11$, which clearly exists for all values of $x \in[1,3]$. So, $f(x)$ is differentiable on the open interval $] 1,3[$.
- (iii) $f(1)=\left(1^{3}-6 \times 1^{2}+11 \times 1-6\right)=0$ and $f(3)=\left(3^{3}-6 \times 3^{2}+11 \times 3-6\right)=0$. $\therefore \quad f(1)=f(3)$.

Thus, all the conditions of Rolle's theorem are satisfied. So, there must exist some $c \in] 1,3\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Rightarrow 3 c^{2}-12 c+11=0$

$$
\Rightarrow c=\frac{12 \pm \sqrt{144-132}}{6} \Rightarrow c=\left(2 \pm \frac{1}{\sqrt{3}}\right) .
$$

Clearly, both the values of $c$ lie in the interval $] 1,3[$.
Hence, Rolle's theorem is verified.

---
### Example 2
Verify Rolle's theorem for the function $f(x)=x(x-1)^{2}$ in the interval $[0,1]$.

#### Solution:

We have $f(x)=x^{3}-2 x^{2}+x$.
We observe here that
- (i) $f(x)$ being a polynomial function, is continuous on $[0,1]$.
- (ii) $f^{\prime}(x)=\left(3 x^{2}-4 x+1\right)$, which clearly exists for all values of $x \in[0,1]$. So, $f(x)$ is differentiable on the interval $] 0,1[$.
- (iii) $f(0)=0$ and $f(1)=0$. $\therefore f(0)=f(1)$.

Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist a real number $c \in] 0,1\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Rightarrow 3 c^{2}-4 c+1=0 \Rightarrow(c-1)(3 c-1)=0$

$$
\Rightarrow \quad c=1 \quad \text { or } \quad c=\frac{1}{3} .
$$

Out of these two values, clearly $\left.\frac{1}{3} \in\right] 0,1[$.
Thus, $\left.c=\frac{1}{3} \in\right] 0,1\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is satisfied.

---
### Example 3
Verify Rolle's theorem for the function $f(x)=(x-a)^{m}(x-b)^{n}$ in the interval $[a, b]$, where $m$ and $n$ are positive integers.

#### Solution:

Let $f(x)=(x-a)^{m}(x-b)^{n}$, where $a \leq x \leq b$.
On expanding $(x-a)^{m}$ and $(x-b)^{n}$ by the binomial theorem and then taking the product, we find that $f(x)$ is a polynomial of degree $(m+n)$. But, a polynomial function being continuous everywhere, it follows that $f(x)$ is continuous in $[a, b]$.
Also, $f^{\prime}(x)=m(x-a)^{m-1}(x-b)^{n}+n(x-a)^{m}(x-b)^{n-1}$

$$
=(x-a)^{m-1}(x-b)^{n-1} \cdot[m(x-b)+n(x-a)],
$$

which clearly exists for all $x \in] a, b[$.
$\therefore \quad f(x)$ is differentiable on $] a, b[$.
Also, $f(a)=f(b)=0$.
Thus, all the conditions of Rolle's theorem are satisfied. Consequently, there must exist some $c \in] a, b\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow(c-a)^{m-1}(c-b)^{n-1}[m(c-b)+n(c-a)]=0$

$$
\begin{aligned}
& \Leftrightarrow \quad(c-a)=0 \text { or }(c-b)=0 \text { or } m(c-b)+n(c-a)=0 \\
& \Leftrightarrow \quad c=a \text { or } \quad c=b \text { or } \quad c=\left(\frac{m b+n a}{m+n}\right)
\end{aligned}
$$

Clearly, $\left.c=\left(\frac{m b+n a}{m+n}\right) \in\right] a, b\left[\right.$ such that $f^{\prime}(c)=0$

$$
\left\{\because\left(\frac{m b+n a}{m+n}\right) \text { divides }\right] a, b[\text { in the ratio } m: n\}
$$

Hence, Rolle's theorem is verified.

---
### Example 4
Verify Rolle's theorem for each of the following functions:
- (i) $f(x)=\sin 2 x$ in $\left[0, \frac{\pi}{2}\right]$
- (ii) $f(x)=(\sin x+\cos x)$ in $\left[0, \frac{\pi}{2}\right]$ [CBSE 2006]
- (iii) $f(x)=\cos 2\left(x-\frac{\pi}{4}\right)$ in $\left[0, \frac{\pi}{2}\right]$
- (iv) $f(x)=(\sin x-\sin 2 x)$ in $[0, \pi]$

#### Solution:

(i) Consider $f(x)=\sin 2 x$ in $\left[0, \frac{\pi}{2}\right]$.
Since the sine function is continuous at each $x \in R$, it follows that $f(x)=\sin 2 x$ is continuous on $\left[0, \frac{\pi}{2}\right]$.
Also, $f^{\prime}(x)=2 \cos 2 x$, which clearly exists for all $x \in\left[0, \frac{\pi}{2}\right]$.

So, $f(x)$ is differentiable on $] 0, \frac{\pi}{2}[$.
Also, $f(0)=f\left(\frac{\pi}{2}\right)=0$.
Thus, all the conditions of Rolle's theorem are satisfied. So, there must exist a real number $c \in] 0, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow 2 \cos 2 c=0 \Leftrightarrow \cos 2 c=0$

$$
\Leftrightarrow \quad 2 c=\frac{\pi}{2}, \quad \text { i.e., } \quad c=\frac{\pi}{4} .
$$

Thus, $\left.c=\frac{\pi}{4} \in\right] 0, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

(ii) Consider $f(x)=(\sin x+\cos x)$ in $\left[0, \frac{\pi}{2}\right]$.

By the continuity of the sine function, the cosine function and the sum of continuous functions, it follows that $f(x)$ is continuous on $\left[0, \frac{\pi}{2}\right]$.
Also, $f^{\prime}(x)=(\cos x-\sin x)$, which clearly exists for all values of $x \in\left[0, \frac{\pi}{2}\right]$.
So, $f(x)$ is differentiable on $] 0, \frac{\pi}{2}\left[\right.$. Also, $f(0)=f\left(\frac{\pi}{2}\right)=1$.
Thus, all the conditions of Rolle's theorem are satisfied. So, there must exist some $c \in] 0, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.

Now, $f^{\prime}(c)=0 \Leftrightarrow \cos c-\sin c=0 \Leftrightarrow \cos c=\sin c \Leftrightarrow c=\frac{\pi}{4}$.
Thus, $\left.c=\frac{\pi}{4} \in\right] 0, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

(iii) Consider $f(x)=\cos 2\left(x-\frac{\pi}{4}\right)$ in $\left[0, \frac{\pi}{2}\right]$.

Since the cosine function is continuous everywhere, it follows that $f(x)=\cos 2\left(x-\frac{\pi}{4}\right)$ is continuous on $\left[0, \frac{\pi}{2}\right]$.

Also, $f^{\prime}(x)=-2 \sin \left(2 x-\frac{\pi}{2}\right)=2 \cos 2 x$, which clearly exists for all $x \in] 0, \frac{\pi}{2}[$.
$\therefore f(x)$ is differentiable on $] 0, \frac{\pi}{2}[$.
Further, $f(0)=\cos 2\left(-\frac{\pi}{4}\right)=\cos \frac{\pi}{2}=0$.
And, $f\left(\frac{\pi}{2}\right)=\cos 2\left(\frac{\pi}{2}-\frac{\pi}{4}\right)=\cos \frac{\pi}{2}=0$.
$\therefore \quad f(0)=f\left(\frac{\pi}{2}\right)=0$.
Thus, all the conditions of Rolle's theorem are satisfied. So, there must exist $c \in] 0, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow 2 \cos 2 c=0 \Leftrightarrow 2 c=\frac{\pi}{2} \Rightarrow c=\frac{\pi}{4}$.
Thus, $\left.c=\frac{\pi}{4} \in\right] 0, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

(iv) Consider $f(x)=(\sin x-\sin 2 x)$ in $[0, \pi]$.

Since the sine function is continuous, it follows that $g(x)=\sin x$ and $h(x)=\sin 2 x$ are both continuous and so their difference is also continuous.

Consequently, $f(x)=g(x)-h(x)$ is differentiable on $[0, \pi]$.
Also, $f^{\prime}(x)=(\cos x-2 \cos 2 x)$, which clearly exists for all $x \in[0, \pi]$.
$\therefore \quad f(x)$ is differentiable on $] 0, \pi[$.
And, $f(0)=f(\pi)=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist a real number $c \in] 0$, $\pi\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow \cos c-2 \cos 2 c=0$

$$
\begin{aligned}
& \Leftrightarrow \cos c-2\left(2 \cos ^{2} c-1\right)=0 \\
& \Leftrightarrow 4 \cos ^{2} c-\cos c-2=0 \\
& \Leftrightarrow \cos c=\frac{1 \pm \sqrt{33}}{8}=0.8431 \text { or }-0.5931 \\
& \Leftrightarrow \cos c=0.8431 \text { or } \cos \left(180^{\circ}-c\right)=0.5931 \\
& \Leftrightarrow c=32^{\circ} \cdot 32^{\prime} \text { or } c=126^{\circ} 23^{\prime}
\end{aligned}
$$

Thus, $c \in] 0, \pi\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is satisfied.
---

### Example 5
Verify Rolle's theorem for each of the following functions:
- (i) $f(x)=\sin ^{2} x$ in $0 \leq x \leq \pi$
- (ii) $f(x)=e^{x} \cos x$ in $-\frac{\pi}{2} \leq x \leq \frac{\pi}{2}$
- (iii) $f(x)=\frac{\sin x}{e^{x}}$ in $0 \leq x \leq \pi$

(i) Consider $f(x)=\sin ^{2} x$ in $[0, \pi]$.

Let $g(x)=\sin x$ and $h(x)=x^{2}$.
Then, the sine function being continuous for all $x \in R$ and every polynomial function being continuous for all $x \in R$, it follows that $g$ and $h$ are both continuous for all $x \in R$.
But the composite of continuous functions is continuous.
$\therefore \quad(h \circ g)(x)=f(x)=\sin ^{2} x$ is continuous on $[0, \pi]$.
Also, $f^{\prime}(x)=2 \sin x \cos x=\sin 2 x$, which clearly exists for all $x \in] 0, \pi[$.
So, $f(x)$ is differentiable on $] 0, \pi[$.
Also, $f(0)=f(\pi)=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist $c \in] 0, \pi\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow \sin 2 c=0 \Leftrightarrow 2 c=\pi \Leftrightarrow c=\frac{\pi}{2}$.
Thus, $\left.c=\frac{\pi}{2} \in\right] 0, \pi\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

(ii) Consider $f(x)=e^{x} \cos x$ in $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.

Let $g(x)=e^{x}$ and $h(x)=\cos x$.
Then, the exponential function as well as the cosine function being continuous, it follows that $g(x) \cdot h(x)=f(x)$ is continuous on $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
Also, $\quad f^{\prime}(x)=-e^{x} \sin x+e^{x} \cos x=e^{x}(\cos x-\sin x)$, which clearly exists for all $x \in]-\frac{\pi}{2}, \frac{\pi}{2}[$.
So, $f(x)$ is differentiable on $]-\frac{\pi}{2}, \frac{\pi}{2}[$.
Also, $f\left(-\frac{\pi}{2}\right)=e^{-\pi / 2} \cos \left(-\frac{\pi}{2}\right)=0$. And, $f\left(\frac{\pi}{2}\right)=e^{\pi / 2} \cos \frac{\pi}{2}=0$.
$\therefore f\left(-\frac{\pi}{2}\right)=f\left(\frac{\pi}{2}\right)=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist some $c \in]-\frac{\pi}{2}, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.

Now, $\quad f^{\prime}(c)=0 \Leftrightarrow e^{c}(\cos c-\sin c)=0 \Leftrightarrow \cos c-\sin c=0$

$$
\Leftrightarrow \sin c=\cos c \Leftrightarrow c=\frac{\pi}{4} .
$$

Thus, $\left.c=\frac{\pi}{4} \in\right]-\frac{\pi}{2}, \frac{\pi}{2}\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

(iii) Consider $f(x)=\frac{\sin x}{e^{x}}$ in $[0, \pi]$.

Since $e^{x} \neq 0$ for any $x \in[0, \pi]$ and $f(x)$ is the quotient of two continuous functions, it follows that $f(x)$ is continuous on $[0, \pi]$.
Also, $f^{\prime}(x)=\frac{e^{x} \cos x-e^{x} \sin x}{e^{2 x}}=\frac{(\cos x-\sin x)}{e^{x}}$, which clearly exists for all $x \in] 0, \pi[$.
So, $f(x)$ is differentiable on $] 0, \pi[$. Also, $f(0)=f(\pi)=0$.
So, all the conditions of Rolle's theorem are satisfied.
$\therefore$ there must exist $c \in] 0, \pi\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow \frac{(\cos c-\sin c)}{e^{c}}=0$

$$
\Leftrightarrow \cos c-\sin c=0 \Leftrightarrow \sin c=\cos c \Leftrightarrow c=\frac{\pi}{4} .
$$

Thus, $\left.c=\frac{\pi}{4} \in\right] 0, \pi\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

---
### Example 6
Verify Rolle's theorem for the function $f(x)=x(x+3) e^{-(x / 2)}$ in $[-3,0]$.

#### Solution:

Since a polynomial function as well as an exponential function is continuous and the product of two continuous functions is continuous, it follows that $f(x)$ is continuous on the given interval $[-3,0]$.
Now, $f^{\prime}(x)=(2 x+3) e^{-(x / 2)}-\frac{1}{2} e^{-(x / 2)}\left(x^{2}+3 x\right)$

$$
=e^{-(x / 2)}\left(\frac{x+6-x^{2}}{2}\right),
$$

which is clearly finite for all values of $x$ in $]-3,0[$.
So, $f(x)$ is differentiable on $]-3$, 0 [. Also, $f(-3)=f(0)=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist $c \in]-3,0\left[\right.$ such that $f^{\prime}(c)=0$.

$$
\text { But, } \begin{aligned}
f^{\prime}(c)=0 & \Leftrightarrow e^{-(c / 2)}\left(\frac{c+6-c^{2}}{2}\right)=0 \Leftrightarrow c+6-c^{2}=0 \\
& \Leftrightarrow(3-c)(c+2)=0 \Leftrightarrow c=3 \text { or } c=-2 .
\end{aligned}
$$

Thus, $c=-2 \in]-3,0\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

---
### Example 7
Verify Rolle's theorem for the function $f(x)=\left\{\log \left(x^{2}+2\right)-\log 3\right\}$ on $[-1,1]$.

#### Solution:

Clearly, $f(x)=\left\{\log \left(x^{2}+2\right)-\log 3\right\}$ has a unique and definite value for each $x \in[-1,1]$. So, at each point of $[-1,1]$, the limit of the function is equal to the value of the function.
So, $f(x)$ is continuous on $[-1,1]$.
Also, $f^{\prime(x)}=\frac{2 x}{\left(x^{2}+2\right)}$, which is clearly finite for each $x \in[-1,1]$.
So, $f(x)$ is differentiable on $]-1,1[$.
Also, $f(-1)=f(1)=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist $c \in]-1,1\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $f^{\prime}(c)=0 \Leftrightarrow \frac{2 c}{\left(c^{2}+2\right)}=0 \Leftrightarrow 2 c=0$, i.e., $c=0$.
Thus, $c=0 \in]-1,1$ [ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

---
### Example 8
Verify Rolle's theorem for the following functions:
- (i) $f(x)=\sqrt{4-x^{2}}$ in $[-2,2]$
- (ii) $f(x)=\log \left(\frac{x^{2}+a b}{(a+b) x}\right]$ in $[a, b]$, where $0<a<b$

#### Solution:

(i) Consider $f(x)=\sqrt{4-x^{2}}$ in $[-2,2]$.
Clearly, $f(x)=\sqrt{4-x^{2}}$ has a unique and definite value for each $x \in[-2,2]$. So, at each point of $[-2,2]$, the limit is equal to the value of the function.
$\therefore \quad f(x)$ is continuous on $[-2,2]$.
Also, $f^{\prime}(x)=\frac{-x}{\sqrt{4-x^{2}}}$, which clearly exists for each $x \in[-2,2]$.
So, $f(x)$ is differentiable on $]-2,2[$.
Also, $f(-2)=f(2)=0$.
Thus, all the conditions of Rolle's theorem are satisfied. So, there must exist $c \in]-2,2\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $\quad f^{\prime}(c)=0 \Leftrightarrow \frac{-c}{\sqrt{4-c^{2}}}=0 \Leftrightarrow c=0$.
Thus, $\quad c=0 \Leftrightarrow]-2,2\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

(ii) Consider

$$
f(x)=\log \left[\frac{x^{2}+a b}{(a+b) x}\right]=\log \left(x^{2}+a b\right)-\log (a+b)-\log x
$$

Clearly, $f(x)$ has a unique and definite value for each $x \in[a, b]$, where $0<a<x<b$.
So, the value of the function is equal to the limit of the function at each point of $[a, b]$.
$\therefore \quad f(x)$ is continuous on $[a, b]$.
Also, $f^{\prime}(x)=\left[\frac{2 x}{\left(x^{2}+a b\right)}-\frac{1}{x}\right]$, which is clearly definite and finite for all values of $x$ in $] a, b[$.
So, $f(x)$ is differentiable on $] a, b[$. Moreover, $f(a)=f(b)=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist $c \in] a, b\left[\right.$ such that $f^{\prime}(c)=0$.
But, $f^{\prime}(c)=0 \Leftrightarrow \frac{2 c}{\left(c^{2}+a b\right)}-\frac{1}{c}=0$

$$
\Leftrightarrow \frac{\left(c^{2}-a b\right)}{c\left(c^{2}+a b\right)}=0 \Leftrightarrow c^{2}-a b=0 \Leftrightarrow c=\sqrt{a b} .
$$

Now, $c$ being the geometric mean of $a$ and $b$, it follows that $a<c<b$.
Thus, $c \in] a, b\left[\right.$ such that $f^{\prime}(c)=0$.
Hence, Rolle's theorem is verified.

---
### Example 9
Verify Rolle's theorem for the function $f(x)=2 x^{3}+x^{2}-4 x-2$.

#### Solution:

Since a polynomial function is everywhere continuous and differentiable, the given function is continuous as well as differentiable on every interval.
To identify the interval, we solve the equation $f(x)=0$.
Now, $f(x)=0 \Leftrightarrow 2 x^{3}+x^{2}-4 x-2=0$

$$
\begin{aligned}
& \Leftrightarrow\left(x^{2}-2\right)(2 x+1)=0 \Leftrightarrow x^{2}=2 \text { or } x=-\frac{1}{2} \\
& \Leftrightarrow x=\sqrt{2} \text { or } x=-\sqrt{2} \text { or } x=-\frac{1}{2} .
\end{aligned}
$$

So, we consider the given function in $[-\sqrt{2}, \sqrt{2}]$.
Clearly, $f(-\sqrt{2})=f(\sqrt{2})=0$.
Thus, all the conditions of Rolle's theorem are satisfied.
So, there must exist $c \in]-\sqrt{2}, \sqrt{2}\left[\right.$ such that $f^{\prime}(c)=0$.
But, $f^{\prime}(x)=\left(6 x^{2}+2 x-4\right)$.
$\therefore \quad f^{\prime}(c)=0 \Leftrightarrow 6 c^{2}+2 c-4=0 \Leftrightarrow 2(3 c-2)(c+1)=0$

$$
\Leftrightarrow \quad c=2 / 3 \text { or } c=-1 .
$$

Clearly, both these points lie in $[-\sqrt{2}, \sqrt{2}]$.
Hence, Rolle's theorem is verified.

---
### Example 10
Discuss the applicability of Rolle's theorem to the functions:
- (i) $f(x)=x^{2}$ in $[1,2]$
- (ii) $f(x)=x^{2 / 3}$ in $[-1,1]$ [CBSE 1999]

(i) Consider $f(x)=x^{2}$ in $[1,2]$.

Since a polynomial function is continuous and differentiable everywhere, the first two conditions of Rolle's theorem are satisfied.
But, $f(1)=1^{2}=1$ and $f(2)=2^{2}=4$. So, $f(1) \neq f(2)$.
And, therefore, the condition $f(a)=f(b)$ is violated.
Hence, Rolle's theorem is not applicable for $f(x)=x^{2}$ in [1,2].

(ii) Consider $f(x)=x^{2 / 3}$ in $[-1,1]$.

We have
$R f^{\prime}(0)=\lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h}=\lim _{h \rightarrow 0} \frac{h^{2 / 3}-0}{h}=\lim _{h \rightarrow 0} \frac{1}{h^{1 / 3}}=\infty$.
$L f^{\prime}(0)=\lim _{h \rightarrow 0} \frac{f(0-h)-f(0)}{-h}=\lim _{h \rightarrow 0} \frac{(-h)^{2 / 3}-0}{-h}=\lim _{h \rightarrow 0} \frac{-1}{(h)^{1 / 3}}=-\infty$.
$\therefore \quad R f^{\prime}(0) \neq L f^{\prime}(0)$, i.e., $f^{\prime}(0)$ does not exist.
Thus, $f(x)$ is not differentiable at $x=0 \in]-1,1[$.
So, the condition of differentiability at each point of the given interval is not satisfied.
Hence, Rolle's theorem is not applicable to $f(x)=x^{2 / 3}$ in $[-1,1]$.

---
### Example 11
Discuss the applicability of Rolle's theorem on:
- (i) $f(x)=|x|$ in $[-1,1]$
- (ii) $f(x)=\tan x$ in $[0, \pi]$

(i) Consider $f(x)=|x|$ in $[-1,1]$.

We may express it as
$$
f(x)=\left\{\begin{array}{rrr}
-x & \text { when } & -1 \leq x<0 \\
x & \text { when } & 0 \leq x \leq 1
\end{array}\right.
$$
Clearly, $f(-1)=f(1)=1$.
But, $R f^{\prime}(0)=\lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h}=\lim _{h \rightarrow 0} \frac{|h|}{h}=\lim _{h \rightarrow 0} \frac{h}{h}=1$.
And,

$$
L f^{\prime}(0)=\lim _{h \rightarrow 0} \frac{f(0-h)-f(0)}{-h}=\lim _{h \rightarrow 0} \frac{|-h|}{-h}=\lim _{h \rightarrow 0} \frac{h}{-h}=-1 .
$$

$\therefore \quad R f^{\prime}(0) \neq L f^{\prime}(0)$.
This shows that $f(x)$ is not differentiable at $x=0$.
Thus, the condition of differentiability at each point of the given interval is not satisfied.

(ii) Consider $f(x)=\tan x$ in $[0, \pi]$.

Clearly, $f(0)=f(\pi)=0$. But, $\tan \frac{\pi}{2}$ does not have a definite value.

So, $f(x)=\tan x$ is not continuous at $x=\frac{\pi}{2}$.
Hence, the condition of continuity at each point of the given interval is violated.

---
### Example 12
Discuss the applicability of Rolle's theorem on the function

$$
f(x)=\left\{\begin{array}{l}
\left(x^{2}+1\right), \text { when } 0 \leq x \leq 1 \\
(3-x), \text { when } 1<x \leq 2 .
\end{array}\right.
$$

#### Solution:

The given function has been defined in [ 0,2 ].
And, $\quad f(0)=f(2)=1$.
Now, we consider the differentiability of $f(x)$ at $x=1$.
$R f^{\prime}(1)=\lim _{h \rightarrow 0} \frac{f(1+h)-f(1)}{h}=\lim _{h \rightarrow 0} \frac{[3-(1+h)]-2}{h}=\lim _{h \rightarrow 0} \frac{-h}{h}=-1$.
$L f^{\prime}(1)=\lim _{h \rightarrow 0} \frac{f(1-h)-f(1)}{-h}=\lim _{h \rightarrow 0} \frac{(1-h)^{2}+1-2}{-h}=\lim _{h \rightarrow 0}(2-h)=2$.
Thus, $\quad R f^{\prime}(1) \neq L f^{\prime}(1)$.
So, $f(x)$ is not differentiable at $x=1 \in] 0,2[$.
Thus, the condition of differentiability at each point of the given interval is not satisfied.

---
### Example 13
If Rolle's theorem holds for the function $f(x)=x^{3}+b x^{2}+a x+5$ on $[1,3]$ with $c=\left(2+\frac{1}{\sqrt{3}}\right)$, find the values of $a$ and $b$.

#### Solution:

We have, $f^{\prime}(x)=3 x^{2}+2 b x+a$.

$$
\begin{aligned}
\therefore \quad f^{\prime}(c)=0 & \Leftrightarrow 3 c^{2}+2 b c+a=0 \\
& \Leftrightarrow c=\frac{-2 b \pm \sqrt{4 b^{2}-12 a}}{6}=\frac{-b \pm \sqrt{b^{2}-3 a}}{3} .
\end{aligned}
$$

Now, $c=\left(2+\frac{1}{\sqrt{3}}\right) \Leftrightarrow \frac{-b+\sqrt{b^{2}-3 a}}{3}=\left(2+\frac{1}{\sqrt{3}}\right)$

$$
\begin{aligned}
& \Leftrightarrow \frac{-b}{3}=2 \text { and } \frac{\sqrt{b^{2}-3 a}}{3}=\frac{1}{\sqrt{3}} \\
& \Leftrightarrow b=-6 \text { and } b^{2}-3 a=3 \Leftrightarrow b=-6 \text { and } a=11 .
\end{aligned}
$$

Hence, $a=11$ and $b=-6$.

---
### Example 14
At what points on the curve $y=(\cos x-1)$ in $[0,2 \pi]$, is the tangent parallel to the $x$-axis?

#### Solution:

Consider $f(x)=(\cos x-1)$ in $[0,2 \pi]$.
Now, the cosine function being continuous and the constant function being continuous, it follows that their difference ( $\cos x-1$ ) is continuous. So, $f(x)$ is continuous on $[0,2 \pi]$.
$f^{\prime}(x)=-\sin x$, which exists for all $\left.x \in\right] 0,2 \pi[$.
$\therefore f(x)$ is differentiable on $] 0,2 \pi[$.
Also, $f(0)=f(2 \pi)=0$.
So, all the conditions of Rolle's theorem are satisfied.
So, there must exist some $c \in] 0,2 \pi\left[\right.$ such that $f^{\prime}(c)=0$.
Now, $\quad f^{\prime}(c)=0 \Leftrightarrow-\sin c=0 \Leftrightarrow \sin c=0$

$$
\Leftrightarrow c=0 \text { or } c=\pi \text { or } c=2 \pi .
$$

Thus, the tangent to the curve is parallel to the $x$-axis at each of the points $x=0, x=\pi$ and $x=2 \pi$.
Now, $x=0$ and $y=\cos x-1 \Rightarrow y=0$;
$x=\pi$ and $y=\cos x-1 \Rightarrow y=-2 ;$
$x=2 \pi$ and $y=\cos x-1 \Rightarrow y=0$.
$\therefore \quad$ the required points are $(0,0),(\pi,-2)$ and $(2 \pi, 0)$.
---