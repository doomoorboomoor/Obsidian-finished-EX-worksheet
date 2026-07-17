
## Derivative of the Product of Functions

### Theorem: Product Rule

If $f(x)$ and $g(x)$ are two differentiable functions then $f(x) \cdot g(x)$ is also differentiable, and

$$
\frac{d}{d x}\{f(x) \cdot g(x)\}=f(x) \cdot \frac{d}{d x}\{g(x)\}+g(x) \cdot \frac{d}{d x}\{f(x)\}
$$

#### Proof:

Let $y=f(x) \cdot g(x)$ and $y+\delta y=f(x+\delta x) \cdot g(x+\delta x)$.

Then,

$$
\frac{\delta y}{\delta x}=\frac{f(x+\delta x) \cdot g(x+\delta x)-f(x) \cdot g(x)}{\delta x}
$$

$$
\therefore \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim _{\delta x \rightarrow 0} \frac{f(x+\delta x) \cdot g(x+\delta x)-f(x) \cdot g(x)}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} \frac{f(x+\delta x) \cdot g(x+\delta x)-f(x+\delta x) \cdot g(x)+f(x+\delta x) \cdot g(x)-f(x) \cdot g(x)}{\delta x}
$$

*[Adding and subtracting $f(x+\delta x) \cdot g(x)$ in the numerator]*

$$
=\lim _{\delta x \rightarrow 0} \frac{f(x+\delta x) \cdot\{g(x+\delta x)-g(x)\}+g(x) \cdot\{f(x+\delta x)-f(x)\}}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} f(x+\delta x) \cdot \frac{g(x+\delta x)-g(x)}{\delta x}+\lim _{\delta x \rightarrow 0} g(x) \cdot \frac{f(x+\delta x)-f(x)}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} f(x+\delta x) \cdot \lim _{\delta x \rightarrow 0} \frac{g(x+\delta x)-g(x)}{\delta x}+g(x) \cdot \lim _{\delta x \rightarrow 0} \frac{f(x+\delta x)-f(x)}{\delta x}
$$

$$
=f(x) \cdot \frac{d}{d x}\{g(x)\}+g(x) \cdot \frac{d}{d x}\{f(x)\}
$$

$$
\therefore \frac{d}{d x}\{f(x) \cdot g(x)\}=f(x) \cdot \frac{d}{d x}\{g(x)\}+g(x) \cdot \frac{d}{d x}\{f(x)\}
$$

Now, since $f(x)$ and $g(x)$ are differentiable, it follows that $\frac{d}{d x}\{f(x)\}$ as well as $\frac{d}{d x}\{g(x)\}$ exists. Consequently, $f(x) \cdot \frac{d}{d x}\{g(x)\}+g(x) \cdot \frac{d}{d x}\{f(x)\}$ exists. So, from the above result, we conclude that $\frac{d}{d x}\{f(x) \cdot g(x)\}$ exists and therefore, $f(x) \cdot g(x)$ is differentiable.

#### Remark:

The above result may be expressed as $\frac{d}{d x}[u v]=u \cdot \frac{d v}{d x}+v \cdot \frac{d u}{d x}$.

It may be remembered as:
> *Derivative of the product of two functions*
> $= [(1\text{st function}) \times (\text{derivative of } 2\text{nd})] + [(\text{2nd function}) \times (\text{derivative of } 1\text{st})]$

---

## Solved Examples

### Example 1

Differentiate:
(i) $x e^{x}$
(ii) $x^{2} e^{x} \sin x$

#### Solution:

(i)
$$
\frac{d}{d x}\left(x e^{x}\right)=x \cdot \frac{d}{d x}\left(e^{x}\right)+e^{x} \cdot \frac{d}{d x}(x)=\left(x e^{x}+e^{x} \cdot 1\right)=e^{x}(x+1)
$$

(ii)
$$
\begin{aligned}
\frac{d}{d x}\left(x^{2} e^{x} \sin x\right) & =\frac{d}{d x}\left[\left(x^{2} e^{x}\right) \sin x\right] \\
& =\left(x^{2} e^{x}\right) \cdot \frac{d}{d x}(\sin x)+\sin x \cdot \frac{d}{d x}\left(x^{2} e^{x}\right) \\
& =x^{2} e^{x} \cos x+\sin x \cdot\left\{x^{2} \cdot \frac{d}{d x}\left(e^{x}\right)+e^{x} \cdot \frac{d}{d x}\left(x^{2}\right)\right\} \\
& =x^{2} e^{x} \cos x+\sin x \cdot\left[x^{2} e^{x}+2 x e^{x}\right] \\
& =x^{2} e^{x} \cos x+x^{2} e^{x} \sin x+2 x e^{x} \sin x \\
& =x e^{x}[x \cos x+x \sin x+2 \sin x]
\end{aligned}
$$

---

### Example 2

Differentiate $x^{2} \tan x$.

#### Solution:

We have
$$
\frac{d}{d x}\left(x^{2} \tan x\right) = \left\{x^{2} \cdot \frac{d}{d x}(\tan x)+\tan x \cdot \frac{d}{d x}\left(x^{2}\right)\right\} = \left(x^{2} \sec ^{2} x+2 x \tan x\right)
$$

---

### Example 3

Differentiate $(e^{x} \sin x+x^{p} \cos x)$.

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{d x}\left(e^{x} \sin x+x^{p} \cos x\right) &= \frac{d}{d x}\left(e^{x} \sin x\right)+\frac{d}{d x}\left(x^{p} \cos x\right) \\
& =\left\{e^{x} \cdot \frac{d}{d x}(\sin x)+\sin x \cdot \frac{d}{d x}\left(e^{x}\right)\right\}+\left\{x^{p} \cdot \frac{d}{d x}(\cos x)+\cos x \cdot \frac{d}{d x}\left(x^{p}\right)\right\} \\
& =\left(e^{x} \cos x+e^{x} \sin x\right)+\left[x^{p}(-\sin x)+\cos x \cdot\left(p x^{p-1}\right)\right] \\
& =e^{x}(\cos x+\sin x)-x^{p} \sin x+p x^{p-1} \cos x \\
& =e^{x}(\cos x+\sin x)-x^{p-1}(x \sin x-p \cos x)
\end{aligned}
$$

---

### Example 4

Differentiate $e^{x}\left(x^{3}+\sqrt{x}\right)$.

#### Solution:

$$
\begin{aligned}
\frac{d}{d x}\left[e^{x}\left(x^{3}+\sqrt{x}\right)\right] &= e^{x} \cdot \frac{d}{d x}\left(x^{3}+\sqrt{x}\right)+\left(x^{3}+\sqrt{x}\right) \cdot \frac{d}{d x}\left(e^{x}\right) \\
&= e^{x}\left\{3 x^{2}+\frac{1}{2} x^{-1 / 2}\right\}+\left(x^{3}+\sqrt{x}\right) \cdot e^{x} \\
&= e^{x}\left\{x^{3}+3 x^{2}+\frac{1}{2 \sqrt{x}}+\sqrt{x}\right\}
\end{aligned}
$$

---

### Example 5

Differentiate $\left(\frac{e^{x} \cos x}{x^{3}}\right)$, using the product rule.

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{d x}\left\{\frac{e^{x} \cos x}{x^{3}}\right\} &= \frac{d}{d x}\left[\left(e^{x} \cos x\right) \cdot x^{-3}\right] \\
&= e^{x} \cos x \cdot \frac{d}{d x}\left(x^{-3}\right)+x^{-3} \cdot \frac{d}{d x}\left(e^{x} \cos x\right) \\
&= e^{x} \cos x \cdot\left(-3 x^{-4}\right)+x^{-3} \cdot\left\{e^{x} \cdot \frac{d}{d x}(\cos x)+\cos x \cdot \frac{d}{d x}\left(e^{x}\right)\right\} \\
&= \frac{-3 e^{x} \cos x}{x^{4}}+\frac{1}{x^{3}}\left[-e^{x} \sin x+e^{x} \cos x\right] \\
&= \frac{-3 e^{x} \cos x-x e^{x} \sin x+x e^{x} \cos x}{x^{4}}=\frac{e^{x}[(x-3) \cos x-x \sin x]}{x^{4}}
\end{aligned}
$$

---

### Example 6

If $u, v, w$ are differentiable functions of $x$, prove that

$$
\frac{d}{d x}(u v w)=(u v) \cdot \frac{d w}{d x}+(w u) \cdot \frac{d v}{d x}+(w v) \cdot \frac{d u}{d x}
$$

#### Solution:

We have
$$
\begin{aligned}
\frac{d}{d x}(u v w) &= \frac{d}{d x}\{(u v) w\}=(u v) \cdot \frac{d w}{d x}+w \cdot \frac{d}{d x}(u v) \\
&= (u v) \cdot \frac{d w}{d x}+w \cdot\left\{u \cdot \frac{d v}{d x}+v \cdot \frac{d u}{d x}\right\} \\
&= (u v) \cdot \frac{d w}{d x}+(w u) \cdot \frac{d v}{d x}+(w v) \cdot \frac{d u}{d x}
\end{aligned}
$$

---

## Exercise 28C

**Differentiate:**

1.  $x^{2} \sin x$
2.  $e^{x} \cos x$
3.  $e^{x} \cot x$
4.  $x^{n} \cot x$
5.  $x^{3} \sec x$
6.  $\left(x^{2}+3 x+1\right) \sin x$
7.  $x^{4} \tan x$
8.  $(3 x-5)\left(4 x^{2}-3+e^{x}\right)$
9.  $\left(x^{2}-4 x+5\right)\left(x^{3}-2\right)$
10. $\left(x^{2}+2 x-3\right)\left(x^{2}+7 x+5\right)$
11. $(\tan x+\sec x)(\cot x+\operatorname{cosec} x)$
12. $\left(x^{3} \cos x-2^{x} \tan x\right)$

---

## Answers (Exercise 28C)

1.  $\left(x^{2} \cos x+2 x \sin x\right)$
2.  $e^{x}(\cos x-\sin x)$
3.  $e^{x}\left(\cot x-\operatorname{cosec}^{2} x\right)$
4.  $x^{n-1}\left(n \cot x-x \operatorname{cosec}^{2} x\right)$
5.  $x^{3} \sec x \tan x+3 x^{2} \sec x$
6.  $\left(x^{2}+3 x+1\right) \cos x+(2 x+3) \sin x$
7.  $x^{4} \sec ^{2} x+4 x^{3} \tan x$
8.  $\left(36 x^{2}-40 x+3 x e^{x}-2 e^{x}-9\right)$
9.  $5 x^{4}-16 x^{3}+15 x^{2}-4 x+8$
10. $4 x^{3}+27 x^{2}+32 x-11$
11. $(\sec x-\operatorname{cosec} x)(\sec x+\tan x)(\operatorname{cosec} x+\cot x)$
12. $x^{2}(3 \cos x-x \sin x)-2^{x}\left[(\log 2) \tan x+\sec ^{2} x\right]$

---

## Derivative of the Quotient of Two Functions

### Theorem: Quotient Rule

If $f(x)$ and $g(x)$ are two differentiable functions and $g(x) \neq 0$ then $\frac{f(x)}{g(x)}$ is also differentiable, and

$$
\frac{d}{d x}\left\{\frac{f(x)}{g(x)}\right\}=\frac{g(x) \cdot \frac{d}{d x}\{f(x)\}-f(x) \cdot \frac{d}{d x}\{g(x)\}}{[g(x)]^{2}}
$$

#### Proof:

Let $y=\frac{f(x)}{g(x)}$ and $y+\delta y=\frac{f(x+\delta x)}{g(x+\delta x)}$.
Then,
$$
\frac{\delta y}{\delta x}=\frac{1}{\delta x} \cdot\left\{\frac{f(x+\delta x)}{g(x+\delta x)}-\frac{f(x)}{g(x)}\right\}
$$

$$
\begin{aligned}
\therefore \frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim _{\delta x \rightarrow 0} \frac{1}{\delta x}\left\{\frac{f(x+\delta x)}{g(x+\delta x)}-\frac{f(x)}{g(x)}\right\} \\
&= \lim _{\delta x \rightarrow 0} \frac{g(x) \cdot f(x+\delta x)-g(x+\delta x) \cdot f(x)}{\delta x \cdot g(x+\delta x) \cdot g(x)} \\
&= \lim _{\delta x \rightarrow 0} \frac{g(x) \cdot f(x+\delta x)-g(x) \cdot f(x)+g(x) \cdot f(x)-g(x+\delta x) \cdot f(x)}{\delta x \cdot g(x+\delta x) \cdot g(x)} \\
&= \frac{\lim _{\delta x \rightarrow 0} g(x) \cdot\left\{\frac{f(x+\delta x)-f(x)}{\delta x}\right\}-\lim _{\delta x \rightarrow 0} f(x) \cdot\left\{\frac{g(x+\delta x)-g(x)}{\delta x}\right\}}{\lim _{\delta x \rightarrow 0} g(x+\delta x) \cdot g(x)} \\
&= \left[g(x) \cdot \frac{d}{d x}\{f(x)\}-f(x) \cdot \frac{d}{d x}\{g(x)\}\right] \times \frac{1}{[g(x)]^{2}} \\
&= \frac{g(x) \cdot \frac{d}{d x}\{f(x)\}-f(x) \cdot \frac{d}{d x}\{g(x)\}}{[g(x)]^{2}} \\
\therefore \frac{d}{d x}\left\{\frac{f(x)}{g(x)}\right\} &= \frac{g(x) \cdot \frac{d}{d x}\{f(x)\}-f(x) \cdot \frac{d}{d x}\{g(x)\}}{[g(x)]^{2}}
\end{aligned}
$$

Now, each of $f(x)$ and $g(x)$ being differentiable, it follows that $\frac{d}{d x}\{f(x)\}$ and $\frac{d}{d x}\{g(x)\}$ both exist. So, by the above result, it follows that $\frac{d}{d x}\left\{\frac{f(x)}{g(x)}\right\}$ exists, and hence $\frac{f(x)}{g(x)}$ is differentiable.

#### Remark:

The above result may be expressed as $\frac{d}{d x}\left(\frac{u}{v}\right)=\frac{v \cdot \frac{d u}{d x}-u \cdot \frac{d v}{d x}}{v^{2}}$.

> *Derivative of the quotient of two functions*
> $=\frac{(\text{denom} . \times \text{derivative of num} .)-(\text{num} . \times \text{derivative of denom} .)}{(\text{denominator})^{2}}$

---

## Solved Examples

### Example 1

Differentiate:
(i) $\frac{e^{x}}{x}$
(ii) $\left(\frac{2 x+3}{x^{2}-5}\right)$
(iii) $\frac{e^{x}}{(1+\sin x)}$

#### Solution:

(i)
$$
\frac{d}{d x}\left(\frac{e^{x}}{x}\right)=\frac{x \cdot \frac{d}{d x}\left(e^{x}\right)-e^{x} \cdot \frac{d}{d x}(x)}{x^{2}}=\frac{x e^{x}-e^{x} \cdot 1}{x^{2}}=\frac{e^{x}(x-1)}{x^{2}}
$$

(ii)
$$
\frac{d}{d x}\left(\frac{2 x+3}{x^{2}-5}\right)=\frac{\left(x^{2}-5\right) \cdot \frac{d}{d x}(2 x+3)-(2 x+3) \cdot \frac{d}{d x}\left(x^{2}-5\right)}{\left(x^{2}-5\right)^{2}} = \frac{\left(x^{2}-5\right) \cdot 2-(2 x+3) \cdot 2 x}{\left(x^{2}-5\right)^{2}}=\frac{-2\left(x^{2}+3 x+5\right)}{\left(x^{2}-5\right)^{2}}
$$

(iii)
$$
\frac{d}{d x}\left(\frac{e^{x}}{1+\sin x}\right)=\frac{(1+\sin x) \cdot \frac{d}{d x}\left(e^{x}\right)-e^{x} \cdot \frac{d}{d x}(1+\sin x)}{(1+\sin x)^{2}} = \frac{(1+\sin x) \cdot e^{x}-e^{x}(\cos x)}{(1+\sin x)^{2}}=\frac{(1+\sin x-\cos x) e^{x}}{(1+\sin x)^{2}}
$$

---

### Example 2

Differentiate $\left(\frac{x^{2}+5 x-6}{4 x^{2}-x+3}\right)$.

#### Solution:

Using the quotient rule, we have

$$
\begin{aligned}
\frac{d}{d x}\left(\frac{x^{2}+5 x-6}{4 x^{2}-x+3}\right) &= \frac{\left(4 x^{2}-x+3\right) \cdot \frac{d}{d x}\left(x^{2}+5 x-6\right)-\left(x^{2}+5 x-6\right) \cdot \frac{d}{d x}\left(4 x^{2}-x+3\right)}{\left(4 x^{2}-x+3\right)^{2}} \\
&= \frac{\left(4 x^{2}-x+3\right)(2 x+5)-\left(x^{2}+5 x-6\right)(8 x-1)}{\left(4 x^{2}-x+3\right)^{2}}=\frac{\left(9+54 x-21 x^{2}\right)}{\left(4 x^{2}-x+3\right)^{2}}
\end{aligned}
$$

---

### Example 3

Differentiate $\left(\frac{x^{2} \sin x}{1-x}\right)$.

#### Solution:

By the quotient rule, we have

$$
\begin{aligned}
\frac{d}{d x}\left(\frac{x^{2} \sin x}{1-x}\right) & =\frac{(1-x) \cdot \frac{d}{d x}\left(x^{2} \sin x\right)-x^{2} \sin x \cdot \frac{d}{d x}(1-x)}{(1-x)^{2}} \\
& =\frac{(1-x)\left\{x^{2} \cdot \frac{d}{d x}(\sin x)+\sin x \cdot \frac{d}{d x}\left(x^{2}\right)\right\}-\left(x^{2} \sin x\right)(-1)}{(1-x)^{2}} \\
& =\frac{(1-x)\left[x^{2} \cos x+2 x \sin x\right]+x^{2} \sin x}{(1-x)^{2}} \\
& =\frac{x^{2}(1-x) \cos x+(x \sin x)(2-x)}{(1-x)^{2}}
\end{aligned}
$$

---

### Example 4

If $y=\left\{\frac{1-\tan x}{1+\tan x}\right\}$, show that $\frac{d y}{d x}=\frac{-2}{(1+\sin 2 x)}$.

#### Solution:

By the quotient rule, we have

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{(1+\tan x) \cdot \frac{d}{d x}(1-\tan x)-(1-\tan x) \cdot \frac{d}{d x}(1+\tan x)}{(1+\tan x)^{2}} \\
& =\frac{(1+\tan x)\left(-\sec ^{2} x\right)-(1-\tan x)\left(\sec ^{2} x\right)}{(1+\tan x)^{2}} \\
& =\frac{-2 \sec ^{2} x}{(1+\tan x)^{2}}=\frac{-2}{\left(\cos ^{2} x\right)\left(1+\tan ^{2} x+2 \tan x\right)} \\
& =\frac{-2}{\left(\cos ^{2} x\right)\left\{1+\frac{\sin ^{2} x}{\cos ^{2} x}+\frac{2 \sin x}{\cos x}\right\}}=\frac{-2}{(1+\sin 2 x)}
\end{aligned}
$$

---

### Example 5

Differentiate:
(i) $\left(\frac{\sin x+\cos x}{\sin x-\cos x}\right)$
(ii) $\left(\frac{\sec x-1}{\sec x+1}\right)$

#### Solution:

(i)
$$
\begin{aligned}
\frac{d}{d x}\left(\frac{\sin x+\cos x}{\sin x-\cos x}\right) &= \frac{(\sin x-\cos x) \cdot \frac{d}{d x}(\sin x+\cos x)-(\sin x+\cos x) \cdot \frac{d}{d x}(\sin x-\cos x)}{(\sin x-\cos x)^{2}} \\
&= \frac{(\sin x-\cos x)(\cos x-\sin x)-(\sin x+\cos x)(\cos x+\sin x)}{(\sin x-\cos x)^{2}} \\
&= \frac{-\left[(\sin x-\cos x)^{2}+(\sin x+\cos x)^{2}\right]}{(\sin x-\cos x)^{2}} \\
&= \frac{-2\left(\sin ^{2} x+\cos ^{2} x\right)}{\left(\sin ^{2} x+\cos ^{2} x-2 \sin x \cos x\right)}=\frac{-2}{(1-\sin 2 x)}
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\frac{d}{d x}\left(\frac{\sec x-1}{\sec x+1}\right) &= \frac{(\sec x+1) \cdot \frac{d}{d x}(\sec x-1)-(\sec x-1) \cdot \frac{d}{d x}(\sec x+1)}{(\sec x+1)^{2}} \\
&= \frac{(\sec x+1) \sec x \tan x-(\sec x-1) \sec x \tan x}{(\sec x+1)^{2}}=\frac{2 \sec x \tan x}{(\sec x+1)^{2}}
\end{aligned}
$$

---

.