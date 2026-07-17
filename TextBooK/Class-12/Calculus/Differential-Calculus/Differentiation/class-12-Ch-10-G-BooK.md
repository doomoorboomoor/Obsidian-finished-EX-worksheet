## 7. Derivatives of an Infinite Series

If we take out a single term from an infinite series, it remains unaffected. We utilize this result in finding the derivative of an infinite series.

## SOLVED EXAMPLES

### Example:

If $y=x^{x^{x \ldots \infty}}$, prove that $\frac{d y}{d x}=\frac{y^{2}}{x(1-y \log x)}$.

#### Solution:

We know that an infinite series is not affected by the exclusion of a single term.

So, we may write the given function as $y=x^{y}$.
Now, $y=x^{y} \Rightarrow \log y=y \log x$.

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{1}{y} \cdot \frac{d y}{d x}=y \cdot \frac{1}{x}+\log x \cdot \frac{d y}{d x} \\
\Rightarrow & \left(\frac{1}{y}-\log x\right) \frac{d y}{d x}=\frac{y}{x} \\
\Rightarrow & \frac{(1-y \log x)}{y} \cdot \frac{d y}{d x}=\frac{y}{x} \\
& \frac{d y}{d x}=\left\{\frac{y}{x} \times \frac{y}{(1-y \log x)}\right\} \Rightarrow \frac{d y}{d x}=\frac{y^{2}}{x(1-y \log x)} .
\end{aligned}
$$

---

### Example:

If $y=\sqrt{\sin x+\sqrt{\sin x+\sqrt{\sin x+\ldots \text { to } \infty}}}$, prove that $\frac{d y}{d x}=\frac{\cos x}{(2 y-1)}$.

#### Solution:

We may write the given series as

$$
\begin{equation*}
y=\sqrt{\sin x+y} \Rightarrow y^{2}=(\sin x+y) . \tag{i}
\end{equation*}
$$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& 2 y \cdot \frac{d y}{d x}=\cos x+\frac{d y}{d x} \\
\Rightarrow & (2 y-1) \cdot \frac{d y}{d x}=\cos x \\
\Rightarrow & \frac{d y}{d x}=\frac{\cos x}{(2 y-1)}
\end{aligned}
$$

---

### Example:

If $y=e^{x+e^{x+e^{x+\ldots} \text { to } \infty}}$, prove that $\frac{d y}{d x}=\frac{y}{(1-y)}$.

#### Solution:

We may write the given series as

$$
\begin{equation*}
y=e^{x+y} \Rightarrow \log y=(x+y) . \tag{i}
\end{equation*}
$$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{1}{y} \cdot \frac{d y}{d x}=1+\frac{d y}{d x} \\
\Rightarrow & \left(\frac{1}{y}-1\right) \frac{d y}{d x}=1 \\
\Rightarrow & \frac{(1-y)}{y} \cdot \frac{d y}{d x}=1 \\
\Rightarrow & \frac{d y}{d x}=\frac{y}{(1-y)}
\end{aligned}
$$

---

### Example:

If $y=(\sqrt{x})^{(\sqrt{x})^{(\sqrt{x}) \ldots \infty}}$, prove that $x\left(\frac{d y}{d x}\right)=\frac{y^{2}}{(2-y \log x)}$.

#### Solution:

We may write the given series as

$$
y=(\sqrt{x})^{y} \Rightarrow y=x^{y / 2}
$$

$$
\begin{equation*}
\Rightarrow \log y=\frac{y}{2} \cdot \log x \tag{i}
\end{equation*}
$$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{1}{y} \cdot \frac{d y}{d x}=\frac{y}{2} \cdot \frac{1}{x}+\frac{1}{2} \log x \cdot \frac{d y}{d x} \\
\Rightarrow & \left(\frac{1}{y}-\frac{1}{2} \log x\right) \cdot \frac{d y}{d x}=\frac{y}{2 x} \\
\Rightarrow & \frac{(2-y \log x)}{2 y} \cdot \frac{d y}{d x}=\frac{y}{2 x} \\
\Rightarrow & x \cdot \frac{d y}{d x}=\frac{y^{2}}{(2-y \log x)}
\end{aligned}
$$

---

## EXERCISE 10G

1.  If $y=(\sin x)^{(\sin x)^{(\sin x) \ldots \infty}}$, prove that $\frac{d y}{d x}=\frac{y^{2} \cot x}{(1-y \log \sin x)}$.
2.  If $y=(\cos x)^{(\cos x)^{(\cos x) \ldots \infty}}$, prove that $\frac{d y}{d x}=\frac{-y^{2} \tan x}{(1-y \log \cos x)}$.
3.  If $y=\sqrt{x+\sqrt{x+\sqrt{x+\ldots \infty}}}$, prove that $\frac{d y}{d x}=\frac{1}{(2 y-1)}$.
4.  If $y=\sqrt{\cos x+\sqrt{\cos x+\sqrt{\cos x+\ldots \infty}}}$, prove that $\frac{d y}{d x}=\frac{\sin x}{(1-2 y)}$.
5.  If $y=\sqrt{\tan x+\sqrt{\tan x+\sqrt{\tan x+\ldots \infty}}}$, prove that $\frac{d y}{d x}=\frac{\sec ^{2} x}{(2 y-1)}$.
6.  If $y=\sqrt{\log x+\sqrt{\log x+\sqrt{\log x+\ldots \infty}}}$, show that $(2 y-1) \cdot \frac{d y}{d x}=\frac{1}{x}$.
7.  If $y=a^{x^{a^{x \ldots \infty}}}$, prove that $\frac{d y}{d x}=\frac{y^{2}(\log y)}{x[1-y(\log x)(\log y)]}$.
8.  If $y=x+\frac{1}{x}+\frac{1}{x}+\frac{1}{x}+\ldots \infty$, prove that $\frac{d y}{d x}=\frac{y}{(2 y-x)}$.

---

## HINTS TO SOME SELECTED QUESTIONS (EXERCISE 10G)

1.  $y=(\sin x)^{y}$.
2.  $y=\sqrt{x+y} \Rightarrow y^{2}=x+y$.
3.  $y=a^{\left(x^{y}\right)} \Rightarrow \log y=x^{y}(\log a) \Rightarrow \log (\log y)=(y \log x)+\log (\log a)$.
4.  $y=x+\frac{1}{y}$.

---

## 8. Derivative of One Function With Respect To Another Function

Let $f(x)$ and $g(x)$ be two functions of $x$. In order to find the derivative of $f(x)$ with respect to $g(x)$, we put $u=f(x)$ and $v=g(x)$. Now, find $\frac{d u}{d v}=\frac{(d u / d x)}{(d v / d x)}$, which is the required derivative.

## SOLVED EXAMPLES

### Example:

Differentiate $e^{x}$ w.r.t. $\sqrt{x}$.

#### Solution:

Let $u=e^{x}$ and $v=\sqrt{x}$.
Then, $\frac{d u}{d x}=e^{x}$ and $\frac{d v}{d x}=\frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x}}$.
$\therefore \quad \frac{d u}{d v}=\frac{(d u / d x)}{(d v / d x)}=\frac{e^{x}}{(1 / 2 \sqrt{x})}=2 e^{x} \sqrt{x}$.

---

### Example:

Differentiate $\sin ^{2} x$ w.r.t. $e^{\cos x}$.

#### Solution:

Let $u=\sin ^{2} x$ and $v=e^{\cos x}$. Then,

$$
\frac{d u}{d x}=2 \sin x \cos x
$$

and $\frac{d v}{d x}=e^{\cos x} \cdot(-\sin x)=(-\sin x) \cdot e^{\cos x}$.
$\therefore \quad \frac{d u}{d v}=\frac{(d u / d x)}{(d v / d x)}=\frac{2 \sin x \cos x}{(-\sin x) e^{\cos x}}=\frac{-2 \cos x}{e^{\cos x}}$.

---

### Example:

Differentiate $\sin ^{-1} x$ w.r.t. $\tan ^{-1} x$.

#### Solution:

Let $u=\sin ^{-1} x$ and $v=\tan ^{-1} x$.
Then, $\frac{d u}{d x}=\frac{1}{\sqrt{1-x^{2}}}$ and $\frac{d v}{d x}=\frac{1}{\left(1+x^{2}\right)}$.
$\therefore \quad \frac{d u}{d v}=\frac{(d u / d x)}{(d v / d x)}=\frac{1}{\sqrt{1-x^{2}}} \times\left(1+x^{2}\right)=\frac{\left(1+x^{2}\right)}{\sqrt{1-x^{2}}}$.

---

### Example:

Differentiate $\tan ^{-1}\left(\frac{\sqrt{1+x^{2}}-1}{x}\right)$ w.r.t. $\tan ^{-1} x$.

#### Solution:

Let $u=\tan ^{-1}\left(\frac{\sqrt{1+x^{2}}-1}{x}\right)$ and $v=\tan ^{-1} x$
Now, $v=\tan ^{-1} x \Rightarrow x=\tan v$.
Putting $x=\tan v$, we get

$$
\begin{aligned}
u & =\tan ^{-1}\left\{\frac{\sqrt{1+\tan ^{2} v}-1}{\tan v}\right\}=\tan ^{-1}\left(\frac{\sec v-1}{\tan v}\right) \\
& =\tan ^{-1}\left(\frac{1-\cos v}{\sin v}\right)=\tan ^{-1}\left\{\frac{2 \sin ^{2}(v / 2)}{2 \sin (v / 2) \cos (v / 2)}\right\}
\end{aligned}
$$

$$
\begin{aligned}
& =\tan ^{-1}\left\{\tan \frac{v}{2}\right\}=\frac{v}{2} . \\
\therefore \quad u=\frac{v}{2} & \Rightarrow \frac{d u}{d v}=\frac{1}{2} .
\end{aligned}
$$

---

### Example:

Differentiate $\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)$ w.r.t. $\cos ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)$.

#### Solution:

Let $u=\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)$ and $v=\cos ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
u & =\sin ^{-1}\left(\frac{2 \tan \theta}{1+\tan ^{2} \theta}\right)=\sin ^{-1}(\sin 2 \theta)=2 \theta \\
v & =\cos ^{-1}\left(\frac{1-\tan ^{2} \theta}{1+\tan ^{2} \theta}\right)=\cos ^{-1}(\cos 2 \theta)=2 \theta \\
\therefore \quad u & =v \Rightarrow \frac{d u}{d v}=1
\end{aligned}
$$

---

### Example:

Differentiate $\tan ^{-1}\left(\frac{2 x}{1-x^{2}}\right)$ w.r.t. $\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)$. [CBSE 2004C]

#### Solution:

Let $u=\tan ^{-1}\left(\frac{2 x}{1-x^{2}}\right)$ and $v=\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
u & =\tan ^{-1}\left(\frac{2 \tan \theta}{1-\tan ^{2} \theta}\right)=\tan ^{-1}(\tan 2 \theta)=2 \theta \\
v & =\sin ^{-1}\left(\frac{2 \tan \theta}{1+\tan ^{2} \theta}\right)=\sin ^{-1}(\sin 2 \theta)=2 \theta \\
\therefore \quad u & =v \Rightarrow \frac{d u}{d v}=1
\end{aligned}
$$

---

### Example:

Differentiate $\tan ^{-1}\left\{\frac{\sqrt{1+x^{2}}-\sqrt{1-x^{2}}}{\sqrt{1+x^{2}}+\sqrt{1-x^{2}}}\right\}$ w.r.t. $\cos ^{-1} x^{2}$.

#### Solution:

Let $u=\tan ^{-1}\left\{\frac{\sqrt{1+x^{2}}-\sqrt{1-x^{2}}}{\sqrt{1+x^{2}}+\sqrt{1-x^{2}}}\right\}$ and $v=\cos ^{-1} x^{2}$.
Then, $\cos ^{-1} x^{2}=v \Rightarrow x^{2}=\cos v$.
Putting $x^{2}=\cos v$, we get

$$
\begin{aligned}
u & =\tan ^{-1}\left\{\frac{\sqrt{1+\cos v}-\sqrt{1-\cos v}}{\sqrt{1+\cos v}+\sqrt{1-\cos v}}\right\} \\
& =\tan ^{-1}\left\{\frac{\sqrt{2 \cos ^{2}(v / 2)}-\sqrt{2 \sin ^{2}(v / 2)}}{\sqrt{2 \cos ^{2}(v / 2)}+\sqrt{2 \sin ^{2}(v / 2)}}\right\}
\end{aligned}
$$

$$
=\tan ^{-1}\left\{\frac{\cos (v / 2)-\sin (v / 2)}{\cos (v / 2)+\sin (v / 2)}\right\}=\tan ^{-1}\left\{\frac{1-\tan (v / 2)}{1+\tan (v / 2)}\right\}
$$

[dividing num. and denom. by $\cos (v / 2)$ ]
$=\tan ^{-1}\left\{\tan \left(\frac{\pi}{4}-\frac{v}{2}\right)\right\}=\left(\frac{\pi}{4}-\frac{v}{2}\right)$.
$\therefore \quad u=\left(\frac{\pi}{4}-\frac{v}{2}\right) \Rightarrow \frac{d u}{d v}=\frac{-1}{2}$.

---