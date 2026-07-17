## Trigonometric Equations

**Trigonometric equations** are equations that involve trigonometric functions of unknown angles. For example, $\sin x=\frac{1}{2}$, $\tan x=-\sqrt{3}$, $\cos x=\sin 2 x$, etc.

A **solution** of a trigonometric equation is the value of the unknown angle that satisfies the equation. A trigonometric equation may have an infinite number of solutions.

The **principal solutions** of a trigonometric equation are the solutions for which $0 \leq x \leq 2 \pi$.

The **general solution** of a trigonometric equation is a solution generalized by means of periodicity.

*Remark: We shall use '$I$' to denote the set of all integers.*

---

## General Solutions of Trigonometric Equations

### Theorem 1

- (i) **$\sin \theta=0 \Leftrightarrow \theta=n \pi, n \in I$**
- (ii) **$\cos \theta=0 \Leftrightarrow \theta=(2 n+1) \frac{\pi}{2}, n \in I$**
- (iii) **$\tan \theta=0 \Leftrightarrow \theta=n \pi, n \in I$**

#### Proof

(i) $\sin \theta=0 \Leftrightarrow \theta=0, \pm \pi, \pm 2 \pi, \pm 3 \pi, \ldots$
$$
\Leftrightarrow \theta=n \pi, n \in I .
$$
(ii) $\cos \theta=0 \Leftrightarrow \theta=0, \pm \frac{\pi}{2}, \pm \frac{3 \pi}{2}, \pm \frac{5 \pi}{2}, \ldots$
$$
\Leftrightarrow \theta=(2 n+1) \frac{\pi}{2}, n \in I .
$$
(iii) $\tan \theta=0 \Leftrightarrow \frac{\sin \theta}{\cos \theta}=0$
$$
\begin{aligned}
& \Leftrightarrow \sin \theta=0 \\
& \Leftrightarrow \theta=0, \pm \pi, \pm 2 \pi, \pm 3 \pi, \ldots \\
& \Leftrightarrow \theta=n \pi, n \in I .
\end{aligned}
$$

---

### Example:

Find the general solution of each of the following equations:
(i) $\sin 2 x=0$
(ii) $\sin 3 x=0$
(iii) $\sin \frac{x}{2}=0$
(iv) $\sin \left(x-\frac{\pi}{4}\right)=0$
(v) $\cos 2 x=0$
(vi) $\cos \left(x+\frac{\pi}{10}\right)=0$
(vii) $\tan 3 x=0$
(viii) $\tan \left(2 x+\frac{\pi}{8}\right)=0$
(ix) $\tan \left(4 x+\frac{\pi}{6}\right)=0$

#### Solution:

(i) $\sin 2 x=0 \Rightarrow 2 x=n \pi \Rightarrow x=\frac{n \pi}{2}$, where $n \in I$.
(ii) $\sin 3 x=0 \Rightarrow 3 x=n \pi \Rightarrow x=\frac{n \pi}{3}$, where $n \in I$.
(iii) $\sin \frac{x}{2}=0 \Rightarrow \frac{x}{2}=n \pi \Rightarrow x=2 n \pi$, where $n \in I$.
(iv) $\sin \left(x-\frac{\pi}{4}\right)=0 \Rightarrow\left(x-\frac{\pi}{4}\right)=n \pi \Rightarrow x=\left(n \pi+\frac{\pi}{4}\right)$, where $n \in I$.
(v) $\cos 2 x=0 \Rightarrow 2 x=(2 n+1) \frac{\pi}{2} \Rightarrow x=(2 n+1) \frac{\pi}{4}$, where $n \in I$.
(vi) $\cos \left(x+\frac{\pi}{10}\right)=0 \Rightarrow\left(x+\frac{\pi}{10}\right)=(2 n+1) \frac{\pi}{2} \Rightarrow x=\left\{(2 n+1) \frac{\pi}{2}-\frac{\pi}{10}\right\}$, where $n \in I$.
(vii) $\tan 3 x=0 \Rightarrow 3 x=n \pi \Rightarrow x=\frac{n \pi}{3}$, where $n \in I$.
(viii) $\tan \left(2 x+\frac{\pi}{8}\right)=0 \Rightarrow\left(2 x+\frac{\pi}{8}\right)=n \pi \Rightarrow x=\frac{1}{2}\left(n \pi-\frac{\pi}{8}\right)$, where $n \in I$.
(ix) $\tan \left(4 x+\frac{\pi}{6}\right)=0 \Rightarrow\left(4 x+\frac{\pi}{6}\right)=n \pi \Rightarrow x=\frac{1}{4}\left(n \pi-\frac{\pi}{6}\right)$, where $n \in I$.

---

### Theorem 2

**$\sin \theta=\sin \alpha \Rightarrow \theta=n \pi+(-1)^{n} \alpha$, where $n \in I$.**

#### Proof

We have
$$
\begin{aligned}
\sin \theta=\sin \alpha & \Rightarrow \sin \theta-\sin \alpha=0 \\
& \Rightarrow 2 \cos \frac{(\theta+\alpha)}{2} \sin \frac{(\theta-\alpha)}{2}=0 \\
& \Rightarrow \cos \frac{(\theta+\alpha)}{2}=0 \text{ or } \sin \frac{(\theta-\alpha)}{2}=0 \\
& \Rightarrow \frac{(\theta+\alpha)}{2}=(2 n+1) \frac{\pi}{2} \text{ or } \frac{(\theta-\alpha)}{2}=n \pi \\
& \Rightarrow (\theta+\alpha)=(2 n+1) \pi \text{ or } (\theta-\alpha)=2 n \pi \\
& \Rightarrow \theta=[(2 n+1) \pi-\alpha] \text{ or } \theta=(2 n \pi+\alpha) \\
& \Rightarrow \theta=[(\text{an odd multiple of } \pi)-\alpha] \text{ or } \theta=[(\text{an even multiple of } \pi)+\alpha] \\
& \Rightarrow \theta=n \pi+(-1)^{n} \alpha, \text{ where } n \in I . \\
\therefore \quad \sin \theta=\sin \alpha & \Rightarrow \theta=n \pi+(-1)^{n} \alpha, \text{ where } n \in I .
\end{aligned}
$$

---

### Theorem 3

**$\cos \theta=\cos \alpha \Rightarrow \theta=2 n \pi \pm \alpha$, where $n \in I$.**

#### Proof

We have
$$
\begin{aligned}
\cos \theta=\cos \alpha & \Rightarrow \cos \theta-\cos \alpha=0 \\
& \Rightarrow -2 \sin \frac{(\theta+\alpha)}{2} \sin \frac{(\theta-\alpha)}{2}=0 \\
& \Rightarrow \sin \frac{(\theta+\alpha)}{2}=0 \text{ or } \sin \frac{(\theta-\alpha)}{2}=0 \\
& \Rightarrow \frac{(\theta+\alpha)}{2}=n \pi \text{ or } \frac{(\theta-\alpha)}{2}=n \pi \\
& \Rightarrow (\theta+\alpha)=2 n \pi \text{ or } (\theta-\alpha)=2 n \pi \\
& \Rightarrow \theta=(2 n \pi-\alpha) \text{ or } \theta=(2 n \pi+\alpha) \\
& \Rightarrow \theta=(2 n \pi \pm \alpha) . \\
\therefore \quad \cos \theta=\cos \alpha & \Rightarrow \theta=(2 n \pi \pm \alpha), \text{ where } n \in I .
\end{aligned}
$$

---

### Theorem 4

If $\theta$ and $\alpha$ are not odd multiples of $\frac{\pi}{2}$ then
**$\tan \theta=\tan \alpha \Rightarrow \theta=n \pi+\alpha$, where $n \in I$.**

#### Proof

We have
$$
\begin{aligned}
\tan \theta=\tan \alpha & \Rightarrow \frac{\sin \theta}{\cos \theta}=\frac{\sin \alpha}{\cos \alpha} \\
& \Rightarrow \sin \theta \cos \alpha-\cos \theta \sin \alpha=0 \\
& \Rightarrow \sin (\theta-\alpha)=0 \\
& \Rightarrow (\theta-\alpha)=n \pi, \text{ where } n \in I \\
& \Rightarrow \theta=(n \pi+\alpha), \text{ where } n \in I \\
\therefore \quad \tan \theta=\tan \alpha & \Rightarrow \theta=(n \pi+\alpha), \text{ where } n \in I .
\end{aligned}
$$

---

### Theorem 5

- (i) **$\sin ^{2} \theta=\sin ^{2} \alpha \Leftrightarrow \theta=n \pi \pm \alpha$**
- (ii) **$\cos ^{2} \theta=\cos ^{2} \alpha \Leftrightarrow \theta=n \pi \pm \alpha$**
- (iii) **$\tan ^{2} \theta=\tan ^{2} \alpha \Leftrightarrow \theta=n \pi \pm \alpha$**

#### Proof

(i) $\sin ^{2} \theta=\sin ^{2} \alpha$
$$
\begin{aligned}
&\Rightarrow \quad \frac{(1-\cos 2 \theta)}{2}=\frac{(1-\cos 2 \alpha)}{2} \\
&\Rightarrow \cos 2 \theta=\cos 2 \alpha \\
&\Rightarrow 2 \theta=2 n \pi \pm 2 \alpha \\
&\Rightarrow \theta=(n \pi \pm \alpha), n \in I.
\end{aligned}
$$
(ii) $\cos ^{2} \theta=\cos ^{2} \alpha$
$$
\begin{aligned}
&\Rightarrow \quad \frac{(1+\cos 2 \theta)}{2}=\frac{(1+\cos 2 \alpha)}{2} \\
&\Rightarrow \cos 2 \theta=\cos 2 \alpha \\
&\Rightarrow 2 \theta=2 n \pi \pm 2 \alpha \\
&\Rightarrow \theta=(n \pi \pm \alpha), \text{ where } n \in I.
\end{aligned}
$$
(iii) $\tan ^{2} \theta=\tan ^{2} \alpha$
$$
\begin{aligned}
&\Rightarrow \frac{1-\tan ^{2} \theta}{1+\tan ^{2} \theta}=\frac{1-\tan ^{2} \alpha}{1+\tan ^{2} \alpha} \\
&\Rightarrow \cos 2 \theta=\cos 2 \alpha \\
&\Rightarrow 2 \theta=2 n \pi \pm 2 \alpha, \text{ where } n \in I \\
&\Rightarrow \theta=(n \pi \pm \alpha), \text{ where } n \in I.
\end{aligned}
$$

---

### Theorem 6

**$a \cos \theta+b \sin \theta=c \Leftrightarrow \theta=2 n \pi+\alpha \pm \beta$,
where $\cos \alpha=\frac{a}{\sqrt{a^{2}+b^{2}}}$, $\cos \beta=\frac{c}{\sqrt{a^{2}+b^{2}}}$ and $\sin \alpha=\frac{b}{\sqrt{a^{2}+b^{2}}}$.**

#### Proof

The given equation is $a \cos \theta+b \sin \theta=c$.

Dividing (i) throughout by $\sqrt{a^{2}+b^{2}}$, we get
$$
\begin{aligned}
& \frac{a}{\sqrt{a^{2}+b^{2}}} \cdot \cos \theta+\frac{b}{\sqrt{a^{2}+b^{2}}} \cdot \sin \theta=\frac{c}{\sqrt{a^{2}+b^{2}}} \\
\Rightarrow & \cos \theta \cos \alpha+\sin \theta \sin \alpha=\cos \beta \\
& \text{ where } \cos \alpha=\frac{a}{\sqrt{a^{2}+b^{2}}}, \sin \alpha=\frac{b}{\sqrt{a^{2}+b^{2}}} \text{ and } \cos \beta=\frac{c}{\sqrt{a^{2}+b^{2}}} \\
\Rightarrow & \cos (\theta-\alpha)=\cos \beta \\
\Rightarrow & (\theta-\alpha)=2 n \pi \pm \beta \\
\Rightarrow & \theta=(2 n \pi+\alpha \pm \beta)
\end{aligned}
$$

---

## Summary

1.  For $n \in I$:
    - (i) $\sin \theta=0 \Rightarrow \theta=n \pi$
    - (ii) $\cos \theta=0 \Rightarrow \theta=(2 n+1) \frac{\pi}{2}$
    - (iii) $\tan \theta=0 \Rightarrow \theta=n \pi$
2.  For $n \in I$:
    - (i) $\sin \theta=\sin \alpha \Rightarrow \theta=n \pi+(-1)^{n} \alpha$
    - (ii) $\cos \theta=\cos \alpha \Rightarrow \theta=2 n \pi \pm \alpha$
    - (iii) $\tan \theta=\tan \alpha \Rightarrow \theta=n \pi+\alpha$
3.  For $n \in I$:
    - (i) $\sin ^{2} \theta=\sin ^{2} \alpha \Rightarrow \theta=n \pi \pm \alpha$
    - (ii) $\cos ^{2} \theta=\cos ^{2} \alpha \Rightarrow \theta=n \pi \pm \alpha$
    - (iii) $\tan ^{2} \theta=\tan ^{2} \alpha \Rightarrow \theta=n \pi \pm \alpha$

---

## Solved Examples

### Example 1:

Find the principal solutions of each of the following equations:
(i) $\sin x=\frac{1}{2}$
(ii) $\cos x=\frac{1}{\sqrt{2}}$
(iii) $\tan x=\frac{1}{\sqrt{3}}$

#### Solution:

(i) The given equation is $\sin x=\frac{1}{2}$.
We know that $\sin \frac{\pi}{6}=\frac{1}{2}$ and $\sin \left(\pi-\frac{\pi}{6}\right)=\frac{1}{2}$.
$\therefore \quad \sin \frac{\pi}{6}=\frac{1}{2}$ and $\sin \frac{5 \pi}{6}=\frac{1}{2}$.
Hence, the **principal solutions** are $x=\frac{\pi}{6}$ and $x=\frac{5 \pi}{6}$.

(ii) The given equation is $\cos x=\frac{1}{\sqrt{2}}$.
We know that $\cos \frac{\pi}{4}=\frac{1}{\sqrt{2}}$ and $\cos \left(2 \pi-\frac{\pi}{4}\right)=\frac{1}{\sqrt{2}}$.
$\therefore \quad \cos \frac{\pi}{4}=\frac{1}{\sqrt{2}}$ and $\cos \frac{7 \pi}{4}=\frac{1}{\sqrt{2}}$.
Hence, the **principal solutions** are $x=\frac{\pi}{4}$ and $x=\frac{7 \pi}{4}$.

(iii) The given equation is $\tan x=\frac{1}{\sqrt{3}}$.
We know that $\tan \frac{\pi}{6}=\frac{1}{\sqrt{3}}$ and $\tan \left(\pi+\frac{\pi}{6}\right)=\frac{1}{\sqrt{3}}$.
$\therefore \quad \tan \frac{\pi}{6}=\frac{1}{\sqrt{3}}$ and $\tan \frac{7 \pi}{6}=\frac{1}{\sqrt{3}}$.
Hence, the **principal solutions** are $x=\frac{\pi}{6}$ and $x=\frac{7 \pi}{6}$.

---

### Example 2:

Find the principal solutions of each of the following equations:
(i) $\sin x=\frac{-\sqrt{3}}{2}$
(ii) $\cos x=\frac{-1}{2}$
(iii) $\cot x=-\sqrt{3}$

#### Solution:

(i) The given equation is $\sin x=\frac{-\sqrt{3}}{2}$.
We know that $\sin \frac{\pi}{3}=\frac{\sqrt{3}}{2}$.
$\therefore \sin \left(\pi+\frac{\pi}{3}\right)=-\sin \frac{\pi}{3}=\frac{-\sqrt{3}}{2}$, and $\sin\left(2 \pi-\frac{\pi}{3}\right)=-\sin \frac{\pi}{3}=\frac{-\sqrt{3}}{2}$.
$\therefore \sin \frac{4 \pi}{3}=\frac{-\sqrt{3}}{2}$ and $\sin \frac{5 \pi}{3}=\frac{-\sqrt{3}}{2}$.
Hence, the **principal solutions** are $x=\frac{4 \pi}{3}$ and $x=\frac{5 \pi}{3}$.

(ii) The given equation is $\cos x=\frac{-1}{2}$.
We know that $\cos \frac{\pi}{3}=\frac{1}{2}$.
$\therefore \cos \left(\pi-\frac{\pi}{3}\right)=-\cos \frac{\pi}{3}=-\frac{1}{2}$, and $\cos \left(\pi+\frac{\pi}{3}\right)=-\cos \frac{\pi}{3}=-\frac{1}{2}$.
$\therefore \cos \frac{2 \pi}{3}=-\frac{1}{2}$ and $\cos \frac{4 \pi}{3}=-\frac{1}{2}$.
Hence, the **principal solutions** are $x=\frac{2 \pi}{3}$ and $x=\frac{4 \pi}{3}$.

(iii) The given equation is $\cot x=-\sqrt{3} \Leftrightarrow \tan x=-\frac{1}{\sqrt{3}}$.
We know that $\tan \frac{\pi}{6}=\frac{1}{\sqrt{3}}$.
$\therefore \tan \left(\pi-\frac{\pi}{6}\right)=-\tan \frac{\pi}{6}=\frac{-1}{\sqrt{3}}$, and $\tan \left(2 \pi-\frac{\pi}{6}\right)=-\tan \frac{\pi}{6}=\frac{-1}{\sqrt{3}}$.
$\therefore \tan \frac{5 \pi}{6}=\frac{-1}{\sqrt{3}}$ and $\tan \frac{11 \pi}{6}=\frac{-1}{\sqrt{3}}$.
Hence, the **principal solutions** are $x=\frac{5 \pi}{6}$ and $x=\frac{11 \pi}{6}$.

---

### Example 3:

In each of the following, find the general value of $x$ satisfying the equation:
(i) $\sin x=\frac{1}{\sqrt{2}}$
(ii) $\cos x=\frac{1}{2}$
(iii) $\tan x=\frac{1}{\sqrt{3}}$

#### Solution:

(i) Given: $\sin x=\frac{1}{\sqrt{2}}$.
The least value of $x$ in $[0,2 \pi[$ for which $\sin x=\frac{1}{\sqrt{2}}$ is $x=\frac{\pi}{4}$.
$\therefore \sin x=\sin \frac{\pi}{4} \Rightarrow x=n \pi+(-1)^{n} \cdot \frac{\pi}{4}$, where $n \in I$.
Hence, the **general solution** is $x=n \pi+(-1)^{n} \cdot \frac{\pi}{4}$, where $n \in I$.

(ii) Given: $\cos x=\frac{1}{2}$.
The least value of $x$ in $[0,2 \pi[$ for which $\cos x=\frac{1}{2}$ is $x=\frac{\pi}{3}$.
$\therefore \cos x=\cos \frac{\pi}{3} \Rightarrow x=\left(2 n \pi \pm \frac{\pi}{3}\right)$, where $n \in I$.
Hence, the **general solution** is $x=\left(2 n \pi \pm \frac{\pi}{3}\right)$, where $n \in I$.

(iii) Given: $\tan x=\frac{1}{\sqrt{3}}$.
The least value of $x$ in $[0,2 \pi[$ for which $\tan x=\frac{1}{\sqrt{3}}$ is $\frac{\pi}{6}$.
$\therefore \tan x=\tan \frac{\pi}{6} \Rightarrow x=\left(n \pi+\frac{\pi}{6}\right)$, where $n \in I$.
Hence, the **general solution** is $x=\left(n \pi+\frac{\pi}{6}\right)$, where $n \in I$.

---

### Example 4:

Find the general value of $x$ for which $\sqrt{3} \operatorname{cosec} x=2$.

#### Solution:

Given: $\sqrt{3} \operatorname{cosec} x=2 \Rightarrow \operatorname{cosec} x=\frac{2}{\sqrt{3}} \Rightarrow \sin x=\frac{\sqrt{3}}{2}$.
The least value of $x$ in $[0,2 \pi[$ for which $\sin x=\frac{\sqrt{3}}{2}$ is $\frac{\pi}{3}$.
$\therefore \quad \sin x=\sin \frac{\pi}{3} \Rightarrow x=\left\{n \pi+(-1)^{n} \cdot \frac{\pi}{3}\right\}$, where $n \in I$.
Hence, the **general solution** is $x=\left\{n \pi+(-1)^{n} \cdot \frac{\pi}{3}\right\}$, where $n \in I$.

---

### Example 5:

In each of the following, find the general value of $x$ satisfying the equation:
(i) $\sin x=\frac{-\sqrt{3}}{2}$
(ii) $\cos x=\frac{-1}{2}$
(iii) $\cot x=-\sqrt{3}$

#### Solution:

(i) $\sin x=\frac{-\sqrt{3}}{2}=-\sin \frac{\pi}{3}=\sin \left(\pi+\frac{\pi}{3}\right)=\sin \frac{4 \pi}{3}$.
$\therefore \sin x=\sin \frac{4 \pi}{3} \Rightarrow x=\left\{n \pi+(-1)^{n} \cdot \frac{4 \pi}{3}\right\}$, where $n \in I$.
Hence, the **general solution** is $x=\left\{n \pi+(-1)^{n} \cdot \frac{4 \pi}{3}\right\}$, where $n \in I$.

(ii) $\cos x=\frac{-1}{2}=-\cos \frac{\pi}{3}=\cos \left(\pi-\frac{\pi}{3}\right)=\cos \frac{2 \pi}{3}$.
$\therefore \cos x=\cos \frac{2 \pi}{3} \Rightarrow x=\left(2 n \pi \pm \frac{2 \pi}{3}\right)$, where $n \in I$.
Hence, the **general solution** is $x=\left(2 n \pi \pm \frac{2 \pi}{3}\right)$, where $n \in I$.

(iii) $\cot x=-\sqrt{3}$
$$
\begin{aligned}
& \Rightarrow \tan x=\frac{-1}{\sqrt{3}}=-\tan \frac{\pi}{6}=\tan \left(\pi-\frac{\pi}{6}\right)=\tan \frac{5 \pi}{6} \\
& \Rightarrow \tan x=\tan \frac{5 \pi}{6} \\
& \Rightarrow x=\left(n \pi+\frac{5 \pi}{6}\right), \text{ where } n \in I
\end{aligned}
$$
Hence, the **general solution** is $x=\left(n \pi+\frac{5 \pi}{6}\right)$, where $n \in I$.

---

### Example 6:

Find the general solution of each equation:
(i) $\sqrt{3} \cot x+1=0$
(ii) $\operatorname{cosec} x+\sqrt{2}=0$

#### Solution:

(i) $\sqrt{3} \cot x+1=0$
$$
\begin{aligned}
&\Rightarrow \cot x=\frac{-1}{\sqrt{3}} \\
&\Rightarrow \tan x=-\sqrt{3}=-\tan \frac{\pi}{3}=\tan \left(\pi-\frac{\pi}{3}\right)=\tan \frac{2 \pi}{3} \\
&\Rightarrow \tan x=\tan \frac{2 \pi}{3} \\
&\Rightarrow x=\left(n \pi+\frac{2 \pi}{3}\right), \text{ where } n \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\left(n \pi+\frac{2 \pi}{3}\right)$, where $n \in I$.

(ii) $\operatorname{cosec} x+\sqrt{2}=0$
$$
\begin{aligned}
&\Rightarrow \sin x=-\frac{1}{\sqrt{2}}=-\sin \frac{\pi}{4}=\sin \left(\pi+\frac{\pi}{4}\right)=\sin \frac{5 \pi}{4} \\
&\Rightarrow \sin x=\sin \frac{5 \pi}{4} \\
&\Rightarrow x=\left\{n \pi+(-1)^{n} \cdot \frac{5 \pi}{4}\right\}, \text{ where } n \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\left\{n \pi+(-1)^{n} \cdot \frac{5 \pi}{4}\right\}$, where $n \in I$.

---

### Example 7:

Find the general solution of each of the equations:
(i) $\sin 2 x=-\frac{1}{2}$
(ii) $\tan 3 x=-1$

#### Solution:

(i) $\sin 2 x=-\frac{1}{2}=-\sin \frac{\pi}{6}=\sin \left(\pi+\frac{\pi}{6}\right)=\sin \frac{7 \pi}{6}$
$$
\begin{aligned}
&\Rightarrow \sin 2 x=\sin \frac{7 \pi}{6} \\
&\Rightarrow 2 x=\left\{n \pi+(-1)^{n} \cdot \frac{7 \pi}{6}\right\}, \text{ where } n \in I \\
&\Rightarrow x=\left\{\frac{n \pi}{2}+(-1)^{n} \cdot \frac{7 \pi}{12}\right\}, \text{ where } n \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\left\{\frac{n \pi}{2}+(-1)^{n} \cdot \frac{7 \pi}{12}\right\}$, where $n \in I$.

(ii) $\tan 3 x=-1=-\tan \frac{\pi}{4}=\tan \left(\pi-\frac{\pi}{4}\right)=\tan \frac{3 \pi}{4}$
$$
\begin{aligned}
&\Rightarrow \tan 3 x=\tan \frac{3 \pi}{4} \\
&\Rightarrow 3 x=\left(n \pi+\frac{3 \pi}{4}\right), \text{ where } n \in I. \\
&\Rightarrow x=\left(\frac{n \pi}{3}+\frac{\pi}{4}\right), \text{ where } n \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\left(\frac{n \pi}{3}+\frac{\pi}{4}\right)$, where $n \in I$.

---

### Example 8:

Find the general solution of each of the equations:
(i) $4 \sin ^{2} x=1$
(ii) $2 \cos ^{2} x=1$
(iii) $\cot ^{2} x=3$

#### Solution:

(i) $4 \sin ^{2} x=1 \Rightarrow \sin ^{2} x=\frac{1}{4}=\left(\frac{1}{2}\right)^{2}=\sin ^{2} \frac{\pi}{6}$
$$
\begin{aligned}
&\Rightarrow \sin ^{2} x=\sin ^{2} \frac{\pi}{6} \\
&\Rightarrow x=\left\{n \pi \pm \frac{\pi}{6}\right\}, \text{ where } n \in I
\end{aligned}
$$
Hence, the **general solution** is $x=\left(n \pi \pm \frac{\pi}{6}\right), n \in I$.

(ii) $2 \cos ^{2} x=1 \Rightarrow \cos ^{2} x=\frac{1}{2}=\left(\frac{1}{\sqrt{2}}\right)^{2}=\cos ^{2} \frac{\pi}{4}$
$$
\begin{aligned}
&\Rightarrow \cos ^{2} x=\cos ^{2} \frac{\pi}{4} \\
&\Rightarrow x=\left(n \pi \pm \frac{\pi}{4}\right), \text{ where } n \in I
\end{aligned}
$$
Hence, the **general solution** is $x=\left(n \pi \pm \frac{\pi}{4}\right), n \in I$.

(iii) $\cot ^{2} x=3 \Rightarrow \tan ^{2} x=\frac{1}{3}=\left(\frac{1}{\sqrt{3}}\right)^{2}=\tan ^{2} \frac{\pi}{6}$
$$
\begin{aligned}
&\Rightarrow \tan ^{2} x=\tan ^{2} \frac{\pi}{6} \\
&\Rightarrow x=\left(n \pi \pm \frac{\pi}{6}\right), \text{ where } n \in I
\end{aligned}
$$
Hence, the **general solution** is $\left(n \pi \pm \frac{\pi}{6}\right)$, where $n \in I$.

---

### Example 9:

Find the general solution of the equation $\sin 2 x+\sin 4 x+\sin 6 x=0$.

#### Solution:

The given equation may be written as $(\sin 6 x+\sin 2 x)+\sin 4 x=0$.
$$
\begin{aligned}
&\Rightarrow \quad 2 \sin \frac{(6 x+2 x)}{2} \cos \frac{(6 x-2 x)}{2}+\sin 4 x =0 \quad \left[\because \sin C+\sin D=2 \sin \frac{(C+D)}{2} \cos \frac{(C-D)}{2}\right] \\
&\Rightarrow \quad 2 \sin 4 x \cos 2 x+\sin 4 x=0 \\
&\Rightarrow \sin 4 x(2 \cos 2 x+1)=0 \\
&\Rightarrow \quad \sin 4 x=0 \text{ or } 2 \cos 2 x+1=0 \\
&\Rightarrow \quad \sin 4 x=0 \text{ or } \cos 2 x=-\frac{1}{2}=-\cos \frac{\pi}{3}=\cos \left(\pi-\frac{\pi}{3}\right)=\cos \frac{2 \pi}{3} \\
&\Rightarrow \quad \sin 4 x=0 \text{ or } \cos 2 x=\cos \frac{2 \pi}{3} \\
&\Rightarrow \quad 4 x=n \pi \text{ or } 2 x=\left(2 m \pi \pm \frac{2 \pi}{3}\right), \text{ where } m, n \in I \\
&\Rightarrow \quad x=\frac{n \pi}{4} \text{ or } x=\left(m \pi \pm \frac{\pi}{3}\right), \text{ where } m, n \in I.
\end{aligned}
$$
Hence, the **general solution** is given by $x=\frac{n \pi}{4}$ or $x=\left(m \pi \pm \frac{\pi}{3}\right)$, where $m, n \in I$.

---

### Example 10:

Solve: $2 \cos ^{2} x+3 \sin x=0$.

#### Solution:

We have
$$
\begin{aligned}
& 2 \cos ^{2} x+3 \sin x=0 \\
\Rightarrow & 2\left(1-\sin ^{2} x\right)+3 \sin x=0 \\
\Rightarrow & 2 \sin ^{2} x-3 \sin x-2=0 \\
\Rightarrow & 2 \sin ^{2} x-4 \sin x+\sin x-2=0 \\
\Rightarrow & 2 \sin x(\sin x-2)+(\sin x-2)=0 \\
\Rightarrow & (\sin x-2)(2 \sin x+1)=0 \\
\Rightarrow & (\sin x-2)=0 \text{ or } (2 \sin x+1)=0 \\
\Rightarrow & 2 \sin x+1=0 \quad [\because \sin x=2 \text{ is not possible}] \\
\Rightarrow & \sin x=-\frac{1}{2}=-\sin \frac{\pi}{6}=\sin \left(\pi+\frac{\pi}{6}\right)=\sin \frac{7 \pi}{6} \\
\Rightarrow & \sin x=\sin \frac{7 \pi}{6} \\
\Rightarrow & x=\left\{n \pi+(-1)^{n} \cdot \frac{7 \pi}{6}\right\}, \text{ where } n \in I .
\end{aligned}
$$
Hence, the **general solution** is given by $x=\left\{n \pi+(-1)^{n} \cdot \frac{7 \pi}{6}\right\}$, where $n \in I$.

---

### Example 11:

Find the general solution for each of the following equations:
(i) $\cos 4 x=\cos 2 x$
(ii) $\cos 3 x=\sin 2 x$
(iii) $\sin 3 x+\cos 2 x=0$
(iv) $\sin m x+\sin n x=0$

#### Solution:

(i) $\cos 4 x=\cos 2 x$
$$
\begin{aligned}
&\Rightarrow \cos 4 x-\cos 2 x=0 \\
&\Rightarrow-2 \sin \frac{(4 x+2 x)}{2} \sin \frac{(4 x-2 x)}{2}=0 \quad \left[\because \cos C-\cos D=-2 \sin \frac{(C+D)}{2} \sin \frac{(C-D)}{2}\right] \\
&\Rightarrow-2 \sin 3 x \sin x=0 \\
&\Rightarrow \sin 3 x=0 \text{ or } \sin x=0 \\
&\Rightarrow 3 x=n \pi \text{ or } x=m \pi, \text{ where } m, n \in I \\
&\Rightarrow x=\frac{n \pi}{3} \text{ or } x=m \pi, \text{ where } m, n \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\frac{n \pi}{3}$ or $x=m \pi$, where $m, n \in I$.

(ii) $\cos 3 x=\sin 2 x$
$$
\begin{aligned}
&\Rightarrow \cos 3 x=\cos \left(\frac{\pi}{2}-2 x\right) \\
&\Rightarrow 3 x=2 n \pi \pm\left(\frac{\pi}{2}-2 x\right) \quad [\cos \theta=\cos \alpha \Rightarrow \theta=2 n \pi \pm \alpha] \\
&\Rightarrow 3 x=2 n \pi+\left(\frac{\pi}{2}-2 x\right) \text{ or } 3 x=2 n \pi-\left(\frac{\pi}{2}-2 x\right), \text{ where } n \in I \\
&\Rightarrow 5 x=2 n \pi+\frac{\pi}{2} \text{ or } x=\left(2 n \pi-\frac{\pi}{2}\right), \text{ where } n \in I \\
&\Rightarrow x=\left(\frac{2 n \pi}{5}+\frac{\pi}{10}\right) \text{ or } x=\left(2 n \pi-\frac{\pi}{2}\right), \text{ where } n \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\left(\frac{2 n \pi}{5}+\frac{\pi}{10}\right)$ or $x=\left(2 n \pi-\frac{\pi}{2}\right)$, where $n \in I$.

(iii) $\sin 3 x+\cos 2 x=0$
$$
\begin{aligned}
&\Rightarrow \cos 2 x=-\sin 3 x=\cos \left(\frac{\pi}{2}+3 x\right) \\
&\Rightarrow \cos 2 x=\cos \left(\frac{\pi}{2}+3 x\right) \\
&\Rightarrow 2 x=2 n \pi \pm\left(\frac{\pi}{2}+3 x\right), \text{ where } n \in I \\
&\Rightarrow 2 x=2 n \pi+\left(\frac{\pi}{2}+3 x\right) \text{ or } 2 x=2 n \pi-\left(\frac{\pi}{2}+3 x\right), \text{ where } n \in I \\
&\Rightarrow x=\left(-2 n \pi-\frac{\pi}{2}\right) \text{ or } x=\left(\frac{2 n \pi}{5}-\frac{\pi}{10}\right), \text{ where } n \in I \\
&\Rightarrow x=\left(2 n \pi-\frac{\pi}{2}\right) \text{ or } x=\left(\frac{2 n \pi}{5}-\frac{\pi}{10}\right), \text{ where } n \in I.
\end{aligned}
$$
*Note: $\left(-2 n \pi-\frac{\pi}{2}\right)$ and $\left(2 n \pi-\frac{\pi}{2}\right)$ give the same result as $n \in I$.*
Hence, the **general solution** is $x=\left(2 n \pi-\frac{\pi}{2}\right)$ or $x=\left(\frac{2 n \pi}{5}-\frac{\pi}{10}\right)$, where $n \in I$.

(iv) $\sin m x+\sin n x=0$
$$
\begin{aligned}
&\Rightarrow 2 \sin \frac{(m+n) x}{2} \cos \frac{(m-n) x}{2}=0 \\
&\text{or } \sin \frac{(m+n) x}{2}=0 \quad \text{ or } \quad \cos \frac{(m-n) x}{2}=0 \\
&\Rightarrow \quad \frac{(m+n) x}{2}=p \pi \text{ or } \frac{(m-n) x}{2}=(2 q+1) \frac{\pi}{2}, \text{ where } p, q \in I \\
&\Rightarrow \quad x=\frac{2 p \pi}{(m+n)} \text{ or } x=\frac{(2 q+1) \pi}{(m-n)}, \text{ where } p, q \in I.
\end{aligned}
$$
Hence, the **general solution** is $x=\frac{2 p \pi}{(m+n)}$ or $x=\frac{(2 q+1) \pi}{(m-n)}$, where $p, q \in I$.

---

### Example 12:

Solve: $\sqrt{3} \cos x-\sin x=1$.

#### Solution:

Given: $\sqrt{3} \cos x-\sin x=1$.
Dividing both sides by $\sqrt{(\sqrt{3})^{2}+(-1)^{2}}$, i.e., by 2, we get
$$
\begin{aligned}
& \frac{\sqrt{3}}{2} \cos x-\frac{1}{2} \sin x=\frac{1}{2} \\
\Rightarrow & \cos x \cos \frac{\pi}{6}-\sin x \sin \frac{\pi}{6}=\frac{1}{2} \\
\Rightarrow & \cos \left(x+\frac{\pi}{6}\right)=\cos \frac{\pi}{3}\left[\because \frac{1}{2}=\cos \frac{\pi}{3}\right] \\
\Rightarrow & \left(x+\frac{\pi}{6}\right)=2 n \pi \pm \frac{\pi}{3}, \text{ where } n \in I[\because \cos \theta=\cos \alpha \Rightarrow \theta=2 n \pi \pm \alpha] \\
\Rightarrow & \left(x+\frac{\pi}{6}\right)=\left(2 n \pi+\frac{\pi}{3}\right) \text{ or }\left(x+\frac{\pi}{6}\right)=\left(2 n \pi-\frac{\pi}{3}\right) \\
& x=\left(2 n \pi+\frac{\pi}{6}\right) \text{ or } x=\left(2 n \pi-\frac{\pi}{2}\right), \text{ where } n \in I
\end{aligned}
$$
Hence, the **general solution** is $x=\left(2 n \pi+\frac{\pi}{6}\right)$ or $x=\left(2 n \pi-\frac{\pi}{2}\right)$, where $n \in I$.

---

### Example 13:

Solve: $\sec x-\tan x=\sqrt{3}$.

#### Solution:

We have
$$
\begin{aligned}
\sec x-\tan x=\sqrt{3} & \Rightarrow \frac{1}{\cos x}-\frac{\sin x}{\cos x}=\sqrt{3} \Rightarrow (1-\sin x)=\sqrt{3} \cos x \\
& \Rightarrow \sqrt{3} \cos x+\sin x=1
\end{aligned}
$$
Thus, the given equation becomes $\sqrt{3} \cos x+\sin x=1$.
Dividing both sides by $\sqrt{(\sqrt{3})^{2}+1^{2}}$, i.e., by 2, we get
$$
\begin{aligned}
& \frac{\sqrt{3}}{2} \cos x+\frac{1}{2} \sin x=\frac{1}{2} \\
\Rightarrow \quad & \cos x \cos \frac{\pi}{6}+\sin x \sin \frac{\pi}{6}=\frac{1}{2} \\
\Rightarrow & \cos \left(x-\frac{\pi}{6}\right)=\cos \frac{\pi}{3} \\
\Rightarrow \quad & \left(x-\frac{\pi}{6}\right)=2 n \pi \pm \frac{\pi}{3}, \text{ where } n \in I[\because \cos \theta=\cos \alpha \Rightarrow \theta=2 n \pi \pm \alpha] \\
\Rightarrow & \left(x-\frac{\pi}{6}\right)=\left(2 n \pi+\frac{\pi}{3}\right) \text{ or } \left(x-\frac{\pi}{6}\right)=\left(2 n \pi-\frac{\pi}{3}\right) \\
\Rightarrow & x=2 n \pi+\left(+\frac{\pi}{3}+\frac{\pi}{6}\right) \text{ or } x=2 n \pi+\left(-\frac{\pi}{3}+\frac{\pi}{6}\right), \text{ where } n \in I \\
\Rightarrow \quad & x=\left(2 n \pi+\frac{\pi}{2}\right) \text{ or } x=\left(2 n \pi-\frac{\pi}{6}\right), \text{ where } n \in I \\
\Rightarrow \quad & x=\left(2 n \pi-\frac{\pi}{6}\right), \text{ where } n \in I
\end{aligned}
$$
($\because \sec x$ is not defined when $x=\left(2 n \pi+\frac{\pi}{2}\right)$).
Hence, the **general solution** is $x=\left(2 n \pi-\frac{\pi}{6}\right)$, where $n \in I$.

---

