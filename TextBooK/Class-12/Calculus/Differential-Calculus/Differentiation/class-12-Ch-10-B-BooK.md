## 2. Derivatives of Exponential and Logarithmic Functions

## Exponential Function

Let $a$ be a real number such that $a>1$.
Then, $f(x)=a^{x}$ is called an **exponential function**.
Its domain $= R$ and range $= R^{+}$.

When $a=e$, we have the exponential function, $f(x)=e^{x}$.
This is called **natural exponential function**.

---

## Logarithmic Function

Let $a$ be a real number such that $a>1$.
If $a^{x}=b$, we define, $\log_{a} x = b$.
We say that $\log$ of $x$ to the base $a$ is equal to $b$.
$\log_{10} x$ is called **common logarithm** of $x$.
$\log_{e} x$ is called **natural logarithm** of $x$ and we denote it simply by $\log x$.

It is easy to verify the following results:
(i) $\log (x y) = (\log x) + (\log y)$
(ii) $\log \left(\frac{x}{y}\right) = (\log x) - (\log y)$
(iii) $\log(x^{n}) = n \log x$
(iv) $\log_{a} x = \frac{1}{\log_{x} a}$
(v) $\log_{x} x = 1$ and $\log 1 = 0$

---

## Derivatives of Exponential and Logarithmic Functions

We have
(i) $\frac{d}{d x}\left(e^{x}\right)=e^{x}$
(ii) $\frac{d}{d x}(\log x)=\frac{1}{x}$.

## Derivative of $\boldsymbol{a}^{\boldsymbol{x}}$

Let $y=a^{x}$. Then, $\log y=x \log a$.
(i)

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x}=\log a & \Rightarrow \frac{d y}{d x}=y(\log a) \\
& \Rightarrow \frac{d y}{d x}=a^{x}(\log a) .
\end{aligned}
$$

Hence, $\frac{d}{d x}\left(a^{x}\right)=a^{x}(\log a)$.

---

## Summary

(i) $\frac{d}{d x}\left(e^{x}\right)=e^{x}$
(ii) $\frac{d}{d x}\left(a^{x}\right)=a^{x}(\log a)$
(iii) $\frac{d}{d x}(\log x)=\frac{1}{x}$
(iv) $\frac{d}{d x}\left(\log _{a} x\right)=\frac{1}{x \log a}$

---

## Solved Examples

### Example 1

Differentiate each of the following w.r.t. $x$ :
(i) $e^{x^{2}}$
(ii) $e^{-3 x}$
(iii) $e^{\cos x}$

#### Solution

(i) Let $y=e^{x^{2}}$.

Putting $x^{2}=t$, we get
$y=e^{t}$ and $t=x^{2}$
$\Rightarrow \frac{d y}{d t}=e^{t}$ and $\frac{d t}{d x}=2 x$
$\Rightarrow \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\left(e^{t} \times 2 x\right)=\left(e^{x^{2}} \times 2 x\right)=2 x e^{x^{2}}$.
Hence, $\frac{d}{d x}\left(e^{x^{2}}\right)=2 x e^{x^{2}}$.

(ii) Let $y=e^{-3 x}$.

Putting $-3 x=t$, we get
$y=e^{t}$ and $t=-3 x$
$\Rightarrow \frac{d y}{d t}=e^{t}$ and $\frac{d t}{d x}=-3$
$\Rightarrow \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=-3 e^{t}=-3 e^{-3 x}$.
Hence, $\frac{d}{d x}\left(e^{-3 x}\right)=-3 e^{-3 x}$.

(iii) Let $y=e^{\cos x}$.

Putting $\cos x=t$, we get

$$
\begin{aligned}
& \qquad \begin{aligned}
y & =e^{t} \text { and } t=\cos x \\
\Rightarrow \frac{d y}{d t} & =e^{t} \text { and } \frac{d t}{d x}=-\sin x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\left(-e^{t} \sin x\right)=\left(-e^{\cos x} \sin x\right)
\end{aligned} \\
& \text { Hence, } \frac{d}{d x}\left(e^{\cos x}\right)=-e^{\cos x} \sin x
\end{aligned}
$$

---

### Example 2

Differentiate each of the following w.r.t. $x$ :
(i) $\sin (\log x), x>0$
(ii) $\log (\log x), x>1$

#### Solution

(i) Let $y=\sin (\log x)$.

Putting $\log x=t$, we get

$$
\begin{aligned}
y & =\sin t \text { and } t=\log x \\
\Rightarrow \frac{d y}{d t} & =\cos t \text { and } \frac{d t}{d x}=\frac{1}{x}
\end{aligned}
$$

$$
\Rightarrow \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\left(\cos t \times \frac{1}{x}\right)=\cos (\log x) \times \frac{1}{x}=\frac{\cos (\log x)}{x} .
$$

Hence, $\frac{d}{d x}\{\sin (\log x)\}=\frac{\cos (\log x)}{x}$.

(ii) Let $y=\log (\log x)$.

Putting $\log x=t$, we get

$$
\begin{aligned}
& y=\log t \text { and } t=\log x \\
\Rightarrow & \frac{d y}{d t}=\frac{1}{t} \text { and } \frac{d t}{d x}=\frac{1}{x} \\
\Rightarrow & \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\left(\frac{1}{t} \times \frac{1}{x}\right)=\left(\frac{1}{\log x} \times \frac{1}{x}\right)=\frac{1}{(x \log x)} \\
\therefore & \frac{d}{d x}\{\log (\log x)\}=\frac{1}{(x \log x)}
\end{aligned}
$$

---

### Example 3

If $y=e^{\sqrt{\cot x}}$, find $\frac{d y}{d x}$.

#### Solution

Given: $y=e^{\sqrt{\cot x}}$.
Putting $\cot x=t$ and $\sqrt{\cot x}=\sqrt{t}=u$, we get

$$
\begin{aligned}
y & =e^{u}, u=\sqrt{t} \text { and } t=\cot x \\
\Rightarrow \frac{d y}{d u} & =e^{u}, \frac{d u}{d t}=\frac{1}{2} t^{-1 / 2}=\frac{1}{2 \sqrt{t}} \text { and } \frac{d t}{d x}=-\operatorname{cosec}^{2} x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) \\
& =\left\{e^{u} \cdot \frac{1}{2 \sqrt{t}} \cdot\left(-\operatorname{cosec}^{2} x\right)\right\}=e^{\sqrt{\cot x}} \cdot \frac{1}{2 \sqrt{\cot x}} \cdot\left(-\operatorname{cosec}^{2} x\right) \\
& =\frac{\left(-\operatorname{cosec}^{2} x\right) e^{\sqrt{\cot x}}}{2 \sqrt{\cot x}}
\end{aligned}
$$

---

### Example 4

If $y=\log \tan \frac{x}{2}$, find $\frac{d y}{d x}$.

#### Solution

Given: $y=\log \tan \frac{x}{2}$.
Putting $\frac{x}{2}=t$ and $\tan \frac{x}{2}=\tan t=u$, we get

$$
\begin{aligned}
y & =\log u, u=\tan t \text { and } t=\frac{x}{2} \\
\Rightarrow \frac{d y}{d u} & =\frac{1}{u}, \frac{d u}{d t}=\sec ^{2} t \text { and } \frac{d t}{d x}=\frac{1}{2} \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right)
\end{aligned}
$$

$$
=\left(\frac{1}{u} \times \sec ^{2} t \times \frac{1}{2}\right)=\left(\frac{1}{2 \tan t} \times \sec ^{2} t\right)=\frac{1}{\sin 2 t}=\frac{1}{\sin x}=\operatorname{cosec} x .
$$

Hence, $\frac{d y}{d x}=\operatorname{cosec} x$.

---

### Example 5

If $y=\frac{1}{\log \cos x}$, find $\frac{d y}{d x}$.

#### Solution

Given: $y=(\log \cos x)^{-1}$.
Putting $\cos x=t$ and $\log \cos x=\log t=u$, we get

$$
\begin{aligned}
y & =u^{-1}=\frac{1}{u}, u=\log t \text { and } t=\cos x \\
\Rightarrow \frac{d y}{d u} & =\frac{-1}{u^{2}}, \frac{d u}{d t}=\frac{1}{t} \text { and } \frac{d t}{d x}=-\sin x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) \\
& =\left\{\frac{-1}{u^{2}} \times \frac{1}{t} \times(-\sin x)\right\}=\left\{\frac{1}{(\log \cos x)^{2}} \cdot \frac{1}{\cos x} \cdot \sin x\right\} \\
& =\frac{\tan x}{(\log \cos x)^{2}}
\end{aligned}
$$

---

### Example 6

If $y=\sqrt{e^{\sqrt{x}}}$, find $\frac{d y}{d x}$.

#### Solution

Putting $\sqrt{x}=t, e^{\sqrt{x}}=e^{t}=u$, we get

$$
\begin{aligned}
y & =\sqrt{u}, u=e^{t} \text { and } t=\sqrt{x} \\
\Rightarrow \frac{d y}{d u} & =\frac{1}{2} u^{-1 / 2}=\frac{1}{2 \sqrt{u}}, \frac{d u}{d t}=e^{t} \text { and } \frac{d t}{d x}=\frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x}} \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) \\
& =\left(\frac{1}{2 \sqrt{u}} \times e^{t} \times \frac{1}{2 \sqrt{x}}\right)=\left\{\frac{1}{2 \sqrt{u}} \times u \times \frac{1}{2 \sqrt{x}}\right\}=\frac{\sqrt{u}}{4 \sqrt{x}}=\frac{e^{\frac{1}{2} t}}{4 \sqrt{x}} \\
& =\frac{e^{\frac{1}{2} \sqrt{x}}}{4 \sqrt{x}}
\end{aligned}
$$

---

### Example 7

If $y=\log \log \log x^{3}$, find $\frac{d y}{d x}$.

#### Solution

Let $x^{3}=t, \log x^{3}=\log t=u$ and $\log \log x^{3}=\log u=v$.
Then, $y=\log v, v=\log u, u=\log t$ and $t=x^{3}$
$\Rightarrow \frac{d y}{d x}=\left(\frac{d y}{d v} \times \frac{d v}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right)$

$$
\begin{aligned}
& =\left(\frac{1}{v} \times \frac{1}{u} \times \frac{1}{t} \times 3 x^{2}\right)=\frac{3 x^{2}}{t u v} \\
& =\frac{3 x^{2}}{x^{3}(\log t)(\log u)}=\frac{3}{x(\log t)(\log \log t)} \\
& =\frac{3}{x\left(\log x^{3}\right)\left(\log \log x^{3}\right)}=\frac{1}{x(\log x)\left(\log \log x^{3}\right)}
\end{aligned}
$$

---

### Example 8

If $y=\sqrt{\log \left\{\sin \left(\frac{x^{2}}{3}-1\right)\right\}}$, find $\frac{d y}{d x}$.

#### Solution

Put $\left(\frac{x^{2}}{3}-1\right)=t, \sin \left(\frac{x^{2}}{3}-1\right)=\sin t=u$
and $\log \left\{\sin \left(\frac{x^{2}}{3}-1\right)\right\}=\log u=v$.
Then, $y=\sqrt{v}$, where $v=\log u, u=\sin t$ and $t=\left(\frac{x^{2}}{3}-1\right)$.
$\therefore \quad \frac{d y}{d v}=\frac{1}{2} v^{-1 / 2}=\frac{1}{2 \sqrt{v}} ; \frac{d v}{d u}=\frac{1}{u} ; \frac{d u}{d t}=\cos t$ and $\frac{d t}{d x}=\frac{2 x}{3}$.
So, $\frac{d y}{d x}=\left(\frac{d y}{d v} \times \frac{d v}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right)$

$$
\begin{aligned}
& =\left(\frac{1}{2 \sqrt{v}} \cdot \frac{1}{u} \cdot \cos t \cdot \frac{2 x}{3}\right) \\
& =\frac{x}{3} \cdot \frac{\cos t}{u \cdot \sqrt{\log u}}=\frac{x}{3} \cdot \frac{\cos t}{\sin t \sqrt{\log \sin t}} \\
& =\frac{x \cot t}{3 \sqrt{\log \sin t}}=\frac{x \cot \left(\frac{x^{2}}{3}-1\right)}{3 \cdot \sqrt{\log \sin \left(\frac{x^{2}}{3}-1\right)}} \quad\left[\because t=\left(\frac{x^{2}}{3}-1\right)\right] .
\end{aligned}
$$

---

### Example 9

If $y=e^{x} \log (\sin 2 x)$, find $\frac{d y}{d x}$.

#### Solution

We have

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{d}{d x}\left\{e^{x} \log (\sin 2 x)\right\} \\
& =e^{x} \cdot \frac{d}{d x}\{\log (\sin 2 x)\}+\log (\sin 2 x) \cdot \frac{d}{d x}\left(e^{x}\right) \\
& =e^{x} \cdot\left\{\frac{1}{\sin 2 x} \cdot \cos 2 x \cdot 2\right\}+\log (\sin 2 x) \cdot e^{x} \\
& =2 e^{x} \cot 2 x+e^{x} \log (\sin 2 x) \\
& =e^{x}\{2 \cot 2 x+\log (\sin 2 x)\} .
\end{aligned}
$$

---

### Example 10

If $y=e^{a x} \cos (b x+c)$, find $\frac{d y}{d x}$.

#### Solution

We have

$$
\begin{aligned}
\frac{d y}{d x} & =e^{a x} \cdot \frac{d}{d x}\{\cos (b x+c)\}+\cos (b x+c) \cdot \frac{d}{d x}\left(e^{a x}\right) \\
& =e^{a x} \cdot\{-b \sin (b x+c)\}+\cos (b x+c) \cdot a e^{a x} \\
& =e^{a x} \cdot\{a \cos (b x+c)-b \sin (b x+c)\} .
\end{aligned}
$$

---

### Example 11

Differentiate $\log \sqrt{\frac{1+\cos ^{2} x}{\left(1-e^{2 x}\right)}}$ w.r.t. $x$.
[CBSE 2003C]

#### Solution

Let $y=\log \sqrt{\frac{1+\cos ^{2} x}{\left(1-e^{2 x}\right)}}=\log \left(\frac{1+\cos ^{2} x}{1-e^{2 x}}\right)^{1 / 2}=\frac{1}{2} \log \left(\frac{1+\cos ^{2} x}{1-e^{2 x}}\right)$.
$\therefore \quad y=\frac{1}{2} \log \left(1+\cos ^{2} x\right)-\frac{1}{2} \log \left(1-e^{2 x}\right)$
$\Rightarrow \frac{d y}{d x}=\frac{1}{2} \cdot \frac{1}{\left(1+\cos ^{2} x\right)}(2 \cos x)(-\sin x)-\frac{1}{2} \cdot \frac{1}{\left(1-e^{2 x}\right)} \cdot\left(-2 e^{2 x}\right)$

$$
=\left\{\frac{-\sin x \cos x}{\left(1+\cos ^{2} x\right)}+\frac{e^{2 x}}{\left(1-e^{2 x}\right)}\right\} .
$$

Hence, $\frac{d}{d x}\left\{\log \sqrt{\frac{1+\cos ^{2} x}{\left(1-e^{2 x}\right)}}\right\}=\left\{\frac{-\sin x \cos x}{\left(1+\cos ^{2} x\right)}+\frac{e^{2 x}}{\left(1-e^{2 x}\right)}\right\}$.

---

### Example 12

If $y=\log \sqrt{\frac{1+\sin ^{2} x}{1-\sin x}}$, find $\frac{d y}{d x}$.
[CBSE 2003C]

#### Solution

We have

$$
\begin{equation*}
y=\frac{1}{2}\left\{\log \left(1+\sin ^{2} x\right)-\log (1-\sin x)\right\} \tag{i}
\end{equation*}
$$

On differentiating (i) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{1}{2} \cdot\left[\frac{d}{d x}\left\{\log \left(1+\sin ^{2} x\right)\right\}-\frac{d}{d x}\{\log (1-\sin x)\}\right] \\
& =\frac{1}{2} \cdot\left\{\frac{2 \sin x \cos x}{\left(1+\sin ^{2} x\right)}-\frac{(-\cos x)}{(1-\sin x)}\right\} \\
& =\frac{1}{2} \cdot\left\{\frac{\sin 2 x}{\left(1+\sin ^{2} x\right)}+\frac{\cos x}{(1-\sin x)}\right\}
\end{aligned}
$$

---

### Example 13

If $y=\log \sin \left(e^{x}+5 x+8\right)$, find $\frac{d y}{d x}$.

#### Solution

Given: $y=\log \sin \left(e^{x}+5 x+8\right)$.

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{1}{\sin \left(e^{x}+5 x+8\right)} \cdot \cos \left(e^{x}+5 x+8\right) \cdot \frac{d}{d x}\left(e^{x}+5 x+8\right) \\
& =\left\{\cot \left(e^{x}+5 x+8\right)\right\}\left(e^{x}+5\right)=\left(e^{x}+5\right) \cdot \cot \left(e^{x}+5 x+8\right)
\end{aligned}
$$

---

### Example 14

If $y=\sqrt{x^{2}+1}-\log \left\{\frac{1}{x}+\sqrt{1+\frac{1}{x^{2}}}\right\}$, find $\frac{d y}{d x}$.
[CBSE 2008]

#### Solution

We have

$$
\begin{aligned}
y= & \sqrt{x^{2}+1}-\log \left\{\frac{1+\sqrt{x^{2}+1}}{x}\right\} \\
\Rightarrow \quad y= & \sqrt{x^{2}+1}-\log \left\{1+\sqrt{x^{2}+1}\right\}+\log x \\
\Rightarrow \quad \frac{d y}{d x} & =\frac{1}{2}\left(x^{2}+1\right)^{-1 / 2} \cdot 2 x-\frac{1}{\left\{1+\sqrt{x^{2}+1}\right\}} \cdot\left\{\frac{1}{2}\left(x^{2}+1\right)^{-1 / 2} \cdot 2 x\right\}+\frac{1}{x} \\
& =\frac{x}{\sqrt{x^{2}+1}}-\frac{1}{\left\{1+\sqrt{x^{2}+1}\right\}} \cdot \frac{x}{\sqrt{x^{2}+1}}+\frac{1}{x} \\
& =\frac{x\left\{1+\sqrt{x^{2}+1}\right\}-x}{\left(\sqrt{x^{2}+1}\right)\left\{1+\sqrt{x^{2}+1}\right\}}+\frac{1}{x}=\frac{x \sqrt{x^{2}+1}}{\left(\sqrt{x^{2}+1}\right)\left\{1+\sqrt{x^{2}+1}\right\}}+\frac{1}{x} \\
& =\frac{x}{\left\{1+\sqrt{x^{2}+1}\right\}}+\frac{1}{x}=\frac{\left(x^{2}+1\right)+\sqrt{x^{2}+1}}{x\left\{1+\sqrt{x^{2}+1}\right\}} \\
& =\frac{\left(\sqrt{x^{2}+1}\right)\left\{\left(\sqrt{x^{2}+1}\right)+1\right\}}{x\left\{1+\sqrt{x^{2}+1}\right\}}=\frac{\sqrt{x^{2}+1}}{x}
\end{aligned}
$$

---

## Exercise 10B

Differentiate each of the following w.r.t. $x$ :

1.  (i) $e^{4 x}$
    (ii) $e^{-5 x}$
    (iii) $e^{x^{3}}$
2.  (i) $e^{2 / x}$
    (ii) $e^{\sqrt{x}}$
    (iii) $e^{-2 \sqrt{x}}$
3.  (i) $e^{\cot x}$
    (ii) $e^{-\sin 2 x}$
    (iii) $e^{\sqrt{\sin x}}$
4.  (i) $\tan (\log x)$
    (ii) $\log \sec x$ (iii) $\log \sin \frac{x}{2}$
5.  (i) $\log _{3} x$
    (ii) $2^{-x}$
    (iii) $3^{x+2}$
6.  (i) $\log \left(x+\frac{1}{x}\right)$
    (ii) $\log \sin 3 x$
    (iii) $\log \left(x+\sqrt{1+x^{2}}\right)$
7.  $e^{\sqrt{x}} \log x$
8.  $\log \sin \sqrt{x^{2}+1}$
9.  $e^{2 x} \sin 3 x$
10. $e^{3 x} \cos 2 x$
11. $e^{-5 x} \cot 4 x$
12. $e^{x} \log (\sin 2 x)$
13. $\log (\operatorname{cosec} x-\cot x)$
14. $\log \left(\sec \frac{x}{2}+\tan \frac{x}{2}\right)$
    [CBSE 2003]
    [CBSE 2003]
15. $\sqrt{\frac{1+e^{x}}{1-e^{x}}}$
16. $\frac{e^{x}+e^{-x}}{e^{x}-e^{-x}}$
17. $x e^{\sqrt{\sin x}}$
18. $e^{\sin x} \sin \left(e^{x}\right)$
19. $e^{\sqrt{1-x^{2}}} \tan x$
20. $\frac{e^{x}}{(1+\cos x)}$
21. $x^{3} e^{x} \cos x$
22. $e^{x \cos x}$

---

## Answers (Exercise 10B)

1.  (i) $4 e^{4 x}$
    (ii) $-5 e^{-5 x}$
    (iii) $\left(3 x^{2}\right) e^{x^{3}}$
2.  (i) $-\frac{2}{x^{2}} \cdot e^{2 / x}$
    (ii) $\frac{1}{2 \sqrt{x}} e^{\sqrt{x}}$
    (iii) $\frac{-1}{\sqrt{x}} e^{-2 \sqrt{x}}$
3.  (i) $-e^{\cot x}\left(\operatorname{cosec}^{2} x\right)$
    (ii) $(-2 \cos 2 x) e^{-\sin 2 x}$
    (iii) $\frac{\cos x}{2 \sqrt{\sin x}} \cdot e^{\sqrt{\sin x}}$
4.  (i) $\frac{\sec ^{2}(\log x)}{x}$
    (ii) $\tan x$
    (iii) $\frac{1}{2} \cot \frac{x}{2}$
5.  (i) $\frac{1}{x(\log 3)}$
    (ii) $-2^{-x} \log 2$
    (iii) $\left(9 \times 3^{x} \log 3\right)$
6.  (i) $\frac{\left(x^{2}-1\right)}{x\left(x^{2}+1\right)}$
    (ii) $3 \cot 3 x$
    (iii) $\frac{1}{\sqrt{1+x^{2}}}$
7.  $\frac{e^{\sqrt{x}}(2+\sqrt{x} \log x)}{2 x}$
8.  $\frac{x}{\sqrt{x^{2}+1}} \cot \sqrt{x^{2}+1}$
9.  $e^{2 x}(3 \cos 3 x+2 \sin 3 x)$
10. $e^{3 x}(3 \cos 2 x-2 \sin 2 x)$
11. $-e^{-5 x}\left(5 \cot 4 x+4 \operatorname{cosec}^{2} 4 x\right)$
12. $e^{x}\{2 \cot 2 x+\log \sin 2 x\}$
13. $\operatorname{cosec} x$
14. $\frac{1}{2} \sec \frac{x}{2}$
15. $\frac{e^{x}}{\left(1-e^{x}\right) \sqrt{1-e^{2 x}}}$
16. $\frac{-4}{\left(e^{x}-e^{-x}\right)^{2}}$
17. $e^{\sqrt{\sin x}} \cdot\left(\frac{x \cos x}{2 \sqrt{\sin x}}+1\right)$
18. $e^{\sin x}\left(e^{x} \cos e^{x}+\cos x \sin e^{x}\right)$
19. $e^{\sqrt{1-x^{2}}}\left\{\sec ^{2} x-\frac{x \tan x}{\sqrt{1-x^{2}}}\right\}$
20. $\frac{e^{x}(1+\cos x+\sin x)}{(1+\cos x)^{2}}$
21. $e^{x} x^{2}(x \cos x-x \sin x+3 \cos x)$
22. $e^{x \cos x}(\cos x-x \sin x)$