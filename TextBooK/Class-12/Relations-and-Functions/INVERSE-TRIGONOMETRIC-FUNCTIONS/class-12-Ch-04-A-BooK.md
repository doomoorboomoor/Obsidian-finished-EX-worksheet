## INVERSE TRIGONOMETRIC FUNCTIONS

### Invertible Functions

A **one-one onto function** is called an **invertible function**.

### Inverse of a Function

Let $f: X \rightarrow Y$ be a **one-one onto function**. Then, for each $y \in Y$, there exists a unique element $x \in X$ such that $f(x)=y$.

So, we define a new function, denoted by $f^{-1}$, called the **inverse of $f$**, as

$$
f^{-1}: Y \rightarrow X: f^{-1}(y)=x \Leftrightarrow f(x)=y .
$$

Clearly,

$$
\text { domain }\left(f^{-1}\right)=\operatorname{range}(f) \text { and } \operatorname{range}\left(f^{-1}\right)=\operatorname{domain}(f) .
$$

Trigonometric functions are, in general, not one-one onto.
Therefore, their inverses do not exist.
However, if we restrict their **domains**, we can make them one-one onto, enabling us to have their inverses.

*Example:* The sine function restricted to any of the intervals $[-\pi / 2, \pi / 2]$, $[3 \pi / 2, 5 \pi / 2]$, etc., is one-one onto and in each case, the **range** is $[-1,1]$.

Therefore, we can define the inverse of the sine function, denoted by $\sin ^{-1} x$, in each of these intervals. Corresponding to each such interval, we get a branch of $\sin ^{-1} x$.

The branch $[-\pi / 2, \pi / 2]$ is called the **principal-value branch** and the value belonging to it is called the **principal value**.

We denote the inverse of the sine function as $\sin ^{-1} x$, called **sine inverse $x$**.

$\therefore \quad \sin ^{-1}:[-1,1] \rightarrow\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ and $\sin ^{-1} x=\theta \Leftrightarrow x=\sin \theta$.

Thus, $\sin ^{-1} x$ is a function whose **domain** is $[-1,1]$ and **range** is $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.

Note that $\sin ^{-1} x$ does not mean $(\sin x)^{-1}$.

Similarly, we can define the principal-value branches of the remaining five trigonometrical functions.

The following table shows the inverse trigonometric functions and their principal-value branches.

| Function | Domain | Range (Principal value) |
| :--- | :--- | :--- |
| 1. $y=\sin ^{-1} x$ | [-1,1] | $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]$ |
| 2. $y=\cos ^{-1} x$ | [-1, 1] | $[0, \pi]$ |
| 3. $y=\tan ^{-1} x$ | $R$ | $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right)$ |
| 4. $y=\operatorname{cosec}^{-1} x$ | $R-(-1,1)$ | $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\}$ |
| 5. $y=\sec ^{-1} x$ | $R-[-1,1]$ | $[0, \pi]-\left\{\frac{\pi}{2}\right\}$ |
| 6. $y=\cot ^{-1} x$ | $R$ | $(0, \pi)$ |

---

## SOLVED EXAMPLES

### Example 1:

Find the principal value of each of the following:
(i) $\sin ^{-1}\left(\frac{1}{\sqrt{2}}\right)$
(ii) $\cos ^{-1}\left(\frac{\sqrt{3}}{2}\right)$
(iii) $\tan ^{-1}(\sqrt{3})$
(iv) $\operatorname{cosec}^{-1}(2)$

#### Solution:

(i) We know that the range of the principal-value branch of

$$
\sin ^{-1} \text { is }\left[\frac{-\pi}{2}, \frac{\pi}{2}\right] .
$$

Let $\sin ^{-1}\left(\frac{1}{\sqrt{2}}\right)=\theta$. Then,

$$
\sin \theta=\frac{1}{\sqrt{2}}=\sin \frac{\pi}{4} \Rightarrow \theta=\frac{\pi}{4} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right] .
$$

Hence, the principal value of $\sin ^{-1}\left(\frac{1}{\sqrt{2}}\right)$ is $\frac{\pi}{4}$.

(ii) We know that the range of the principal-value branch of $\cos ^{-1}$ is $[0, \pi]$.

Let $\cos ^{-1}\left(\frac{\sqrt{3}}{2}\right)=\theta$. Then,

$$
\cos \theta=\frac{\sqrt{3}}{2}=\cos \frac{\pi}{6} \Rightarrow \theta=\frac{\pi}{6} \in[0, \pi] .
$$

Hence, the principal value of $\cos ^{-1}\left(\frac{\sqrt{3}}{2}\right)$ is $\frac{\pi}{6}$.

(iii) We know that the range of the principal-value branch of $\tan ^{-1}$ is $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right)$.

Let $\tan ^{-1}(\sqrt{3})=\theta$. Then,

$$
\tan \theta=\sqrt{3}=\tan \frac{\pi}{3} \Rightarrow \theta=\frac{\pi}{3} \in\left(\frac{-\pi}{2}, \frac{\pi}{2}\right) .
$$

Hence, the principal value of $\tan ^{-1}(\sqrt{3})$ is $\frac{\pi}{3}$.

(iv) We know that the range of the principal-value branch of $\operatorname{cosec}^{-1}$ is $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\}$.

Let $\operatorname{cosec}^{-1}(2)=\theta$. Then,

$$
\operatorname{cosec} \theta=2=\operatorname{cosec} \frac{\pi}{6} \Rightarrow \theta=\frac{\pi}{6} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\} .
$$

Hence, the principal value of $\operatorname{cosec}^{-1}(2)$ is $\frac{\pi}{6}$.

---

### Example 2:

Find the principal value of each of the following:
(i) $\sin ^{-1}\left(\frac{-1}{2}\right)$
(ii) $\sin ^{-1}\left(\frac{-\sqrt{3}}{2}\right)$
(iii) $\tan ^{-1}\left(\frac{-1}{\sqrt{3}}\right)$
(iv) $\tan ^{-1}(-1)$
(v) $\operatorname{cosec}^{-1}(-2)$
(vi) $\tan ^{-1}(-\sqrt{3})$

#### Solution:

(i) We know that the principal-value branch of $\sin ^{-1}$ is $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]$.

Let $\sin ^{-1}\left(\frac{-1}{2}\right)=\theta$. Then,

$$
\sin \theta=-\frac{1}{2}=\sin \left(\frac{-\pi}{6}\right), \text { where } \frac{-\pi}{6} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right] .
$$

Hence, the principal value of $\sin ^{-1}\left(\frac{-1}{2}\right)$ is $\frac{-\pi}{6}$.

(ii) We know that the principal-value branch of $\sin ^{-1}$ is $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]$.
Let $\sin ^{-1}\left(\frac{-\sqrt{3}}{2}\right)=\theta$. Then,

$$
\sin \theta=\frac{-\sqrt{3}}{2}=\sin \left(\frac{-\pi}{3}\right), \text { where } \frac{-\pi}{3} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right] .
$$

Hence, the principal value of $\sin ^{-1}\left(\frac{-\sqrt{3}}{2}\right)$ is $\frac{-\pi}{3}$.

(iii) We know that the principal-value branch of $\tan ^{-1}$ is $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right)$.

Let $\tan ^{-1}\left(\frac{-1}{\sqrt{3}}\right)=\theta$. Then,

$$
\tan \theta=\frac{-1}{\sqrt{3}}=\tan \left(\frac{-\pi}{6}\right), \text { where } \frac{-\pi}{6} \in\left(\frac{-\pi}{2}, \frac{\pi}{2}\right) .
$$

Hence, the principal value of $\tan ^{-1}\left(\frac{-1}{\sqrt{3}}\right)$ is $\frac{-\pi}{6}$.

(iv) We know that the principal-value branch of $\tan ^{-1}$ is $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right)$.

Let $\tan ^{-1}(-1)=\theta$. Then,

$$
\tan \theta=-1=\tan \left(\frac{-\pi}{4}\right), \text { where } \frac{-\pi}{4} \in\left(\frac{-\pi}{2}, \frac{\pi}{2}\right) .
$$

Hence, the principal value of $\tan ^{-1}(-1)$ is $\frac{-\pi}{4}$.

(v) We know that the principal-value branch of $\operatorname{cosec}^{-1}$ is $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\}$.

Let $\operatorname{cosec}^{-1}(-2)=\theta$. Then,

$$
\operatorname{cosec} \theta=-2=\operatorname{cosec}\left(\frac{-\pi}{6}\right), \text { where } \frac{-\pi}{6} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\}
$$

Hence, the principal value of $\operatorname{cosec}^{-1}(-2)$ is $\frac{-\pi}{6}$.

(vi) We know that the principal-value branch of $\tan ^{-1}$ is $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right)$.

Let $\tan ^{-1}(-\sqrt{3})=\theta$. Then,

$$
\tan \theta=-\sqrt{3}=\tan \left(\frac{-\pi}{3}\right), \text { where } \frac{-\pi}{3} \in\left(\frac{-\pi}{2}, \frac{\pi}{2}\right) .
$$

Hence, the principal value of $\tan ^{-1}(-\sqrt{3})$ is $\frac{-\pi}{3}$.

---

### Example 3:

Find the principal value of each of the following:
(i) $\cos ^{-1}\left(\frac{-1}{\sqrt{2}}\right)$
(ii) $\cos ^{-1}\left(\frac{-1}{2}\right)$
(iii) $\cot ^{-1}\left(\frac{-1}{\sqrt{3}}\right)$

#### Solution:

(i) We know that the range of the principal value of $\cos ^{-1}$ is $[0, \pi]$.
Let $\cos ^{-1}\left(\frac{-1}{\sqrt{2}}\right)=\theta$. Then,

$$
\begin{aligned}
& \cos \theta=\frac{-1}{\sqrt{2}}=-\cos \frac{\pi}{4}=\cos \left(\pi-\frac{\pi}{4}\right)=\cos \frac{3 \pi}{4} . \\
\therefore & \theta=\frac{3 \pi}{4} \in[0, \pi] .
\end{aligned}
$$

Hence, the principal value of $\cos ^{-1}\left(\frac{-1}{\sqrt{2}}\right)$ is $\frac{3 \pi}{4}$.

(ii) We know that the range of the principal value of $\cos ^{-1}$ is $[0, \pi]$.
Let $\cos ^{-1}\left(\frac{-1}{2}\right)=\theta$. Then,

$$
\begin{array}{ll} 
& \cos \theta=\frac{-1}{2}=-\cos \frac{\pi}{3}=\cos \left(\pi-\frac{\pi}{3}\right)=\cos \frac{2 \pi}{3} . \\
\therefore & \quad \theta=\frac{2 \pi}{3} \in[0, \pi] .
\end{array}
$$

Hence, the principal value of $\cos ^{-1}\left(\frac{-1}{2}\right)$ is $\frac{2 \pi}{3}$.

(iii) We know that the range of the principal value of $\cot ^{-1}$ is $(0, \pi)$.
Let $\cot ^{-1}\left(\frac{-1}{\sqrt{3}}\right)=\theta$. Then,

$$
\begin{array}{ll} 
& \cot \theta=\frac{-1}{\sqrt{3}}=-\cot \frac{\pi}{3}=\cot \left(\pi-\frac{\pi}{3}\right)=\cot \frac{2 \pi}{3} . \\
\therefore & \theta=\frac{2 \pi}{3} \in(0, \pi) .
\end{array}
$$

Hence, the principal value of $\cot ^{-1}\left(\frac{-1}{\sqrt{3}}\right)$ is $\frac{2 \pi}{3}$.

---

### Example 4:

Find the principal value of each of the following:
(i) $\cot ^{-1}(-\sqrt{3})$
(ii) $\sec ^{-1}(-\sqrt{2})$
(iii) $\operatorname{cosec}^{-1}(-1)$

#### Solution:

(i) We know that the range of the principal value of $\cot ^{-1}$ is $(0, \pi)$.
Let $\cot ^{-1}(-\sqrt{3})=\theta$. Then,

$$
\begin{aligned}
& \quad \cot \theta=-\sqrt{3}=-\cot \frac{\pi}{6}=\cot \left(\pi-\frac{\pi}{6}\right)=\cot \frac{5 \pi}{6} . \\
& \therefore \quad \theta=\frac{5 \pi}{6} \in(0, \pi) .
\end{aligned}
$$

Hence, the principal value of $\cot ^{-1}(-\sqrt{3})$ is $\frac{5 \pi}{6}$.

(ii) We know that the range of principal value of $\mathrm{sec}^{-1}$ is $[0, \pi]-\left\{\frac{\pi}{2}\right\}$.

Let $\sec ^{-1}(-\sqrt{2})=\theta$. Then,

$$
\begin{array}{ll} 
& \sec \theta=-\sqrt{2}=-\sec \frac{\pi}{4}=\sec \left(\pi-\frac{\pi}{4}\right)=\sec \frac{3 \pi}{4} . \\
\therefore & \theta=\frac{3 \pi}{4} \in[0, \pi]-\left\{\frac{\pi}{2}\right\} .
\end{array}
$$

Hence, the principal value of $\sec ^{-1}(-\sqrt{2})$ is $\frac{3 \pi}{4}$.

(iii) We know that the range of principal value of $\operatorname{cosec}^{-1}$ is $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\}$.
Let $\operatorname{cosec}^{-1}(-1)=\theta$. Then, $\operatorname{cosec} \theta=-1$.

$$
\begin{aligned}
& \operatorname{cosec} \theta=-1=-\operatorname{cosec} \frac{\pi}{2}=\operatorname{cosec}\left(\frac{-\pi}{2}\right) . \\
\therefore & \theta=\frac{-\pi}{2} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]-\{0\} .
\end{aligned}
$$

Hence, the principal value of $\operatorname{cosec}^{-1}(-1)$ is $\frac{-\pi}{2}$.

---

### Example 5:

Find the value of $\cos ^{-1}\left(\frac{1}{2}\right)+2 \sin ^{-1}\left(\frac{1}{2}\right)$.
[CBSE 2012C]

#### Solution:

We know that the ranges of principal values of $\cos ^{-1}$ and $\sin ^{-1}$ are $[0, \pi]$ and $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]$ respectively.
Let $\cos ^{-1}\left(\frac{1}{2}\right)=\theta_{1}$. Then,

$$
\cos \theta_{1}=\frac{1}{2}=\cos \frac{\pi}{3} \Rightarrow \theta_{1}=\frac{\pi}{3} \in[0, \pi] .
$$

Let $\sin ^{-1}\left(\frac{1}{2}\right)=\theta_{2}$. Then,

$$
\sin \theta_{2}=\frac{1}{2}=\sin \frac{\pi}{6} \Rightarrow \theta_{2}=\frac{\pi}{6} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right] .
$$

$\therefore \cos ^{-1}\left(\frac{1}{2}\right)+2 \sin ^{-1}\left(\frac{1}{2}\right)=\frac{\pi}{3}+\left(2 \times \frac{\pi}{6}\right)=\left(\frac{\pi}{3}+\frac{\pi}{3}\right)=\frac{2 \pi}{3}$.

---

### Example 6:

Find the value of $\tan ^{-1}(1)+\cos ^{-1}\left(\frac{-1}{2}\right)+\sin ^{-1}\left(\frac{-1}{2}\right)$.

#### Solution:

We know that the ranges of principal values of $\tan ^{-1}, \cos ^{-1}$ and $\sin ^{-1}$ are $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right),[0, \pi]$ and $\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]$ respectively.

Let $\tan ^{-1}(1)=\theta_{1}$. Then,

$$
\tan \theta_{1}=1=\tan \frac{\pi}{4} \Rightarrow \theta_{1}=\frac{\pi}{4} \in[0, \pi] .
$$

Let $\cos ^{-1}\left(\frac{-1}{2}\right)=\theta_{2}$. Then,

$$
\cos \theta_{2}=\frac{-1}{2}=-\cos \frac{\pi}{3}=\cos \left(\pi-\frac{\pi}{3}\right)=\cos \frac{2 \pi}{3} .
$$

$\therefore \quad \theta_{2}=\frac{2 \pi}{3} \in[0, \pi]$.
Let $\sin ^{-1}\left(\frac{-1}{2}\right)=\theta_{3}$. Then,

$$
\begin{aligned}
& \sin \theta_{3}=\frac{-1}{2}=-\sin \frac{\pi}{6}=\sin \left(\frac{-\pi}{6}\right) \Rightarrow \theta_{3}=\frac{-\pi}{6} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right] . \\
\therefore & \tan ^{-1}(1)+\cos ^{-1}\left(\frac{-1}{2}\right)+\sin ^{-1}\left(\frac{-1}{2}\right)=\left(\frac{\pi}{4}+\frac{2 \pi}{3}-\frac{\pi}{6}\right)=\frac{3 \pi}{4} .
\end{aligned}
$$

---

### Example 7:

Find the value of $\tan ^{-1} \sqrt{3}-\sec ^{-1}(-2)$.

#### Solution:

We know that the ranges of principal values of $\tan ^{-1}$ and $\sec ^{-1}$ are $\left(\frac{-\pi}{2}, \frac{\pi}{2}\right)$ and $[0, \pi]-\left\{\frac{\pi}{2}\right\}$ respectively.

Let $\tan ^{-1} \sqrt{3}=\theta_{1}$. Then,

$$
\tan \theta_{1}=\sqrt{3}=\tan \frac{\pi}{3} \Rightarrow \theta_{1}=\frac{\pi}{3} \in\left(\frac{-\pi}{2}, \frac{\pi}{2}\right) .
$$

Let $\sec ^{-1}(-2)=\theta_{2}$. Then,

$$
\sec \theta_{2}=-2=-\sec \frac{\pi}{3}=\sec \left(\pi-\frac{\pi}{3}\right)=\sec \frac{2 \pi}{3} .
$$

$\therefore \quad \theta_{2}=\frac{2 \pi}{3} \in[0, \pi]-\left\{\frac{\pi}{2}\right\}$.
Hence, $\tan ^{-1} \sqrt{3}-\sec ^{-1}(-2)=\left(\frac{\pi}{3}-\frac{2 \pi}{3}\right)=\frac{-\pi}{3}$.

---
