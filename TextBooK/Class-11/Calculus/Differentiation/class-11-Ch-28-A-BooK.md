# Differentiation

## Derivative of a Function

Let $y=f(x)$ be a given continuous function. Then, the value of $y$ depends upon the value of $x$ and it changes with a change in the value of $x$. We use the word **increment** to denote a small change, i.e., an increase or decrease, in the values of $x$ and $y$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$. Then,

$$
y=f(x) \text{ and } y+\delta y=f(x+\delta x)
$$

On subtraction, we get $\delta y=f(x+\delta x)-f(x)$.

$$
\therefore \frac{\delta y}{\delta x}=\frac{f(x+\delta x)-f(x)}{\delta x}
$$

So,

$$
\lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{f(x+\delta x)-f(x)}{\delta x}
$$

The above limit, if it exists finitely, is called the **derivative** or **differential coefficient** of $y=f(x)$ with respect to $x$, and it is denoted by

$$
\frac{d y}{d x} \text{ or } \frac{d}{d x}\{f(x)\} \text{ or } f^{\prime}(x)
$$

The process of finding the derivative is known as **differentiation**.

**REMARK**: $\frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim _{\delta x \rightarrow 0} \frac{f(x+\delta x)-f(x)}{\delta x}$.

**Derivative at a Point**: The value of $f^{\prime}(x)$, obtained by putting $x=a$, is called the derivative of $f(x)$ at $x=a$, and it is denoted by $f^{\prime}(a)$ or $\left\{\frac{d y}{d x}\right\}_{x=a}$.

If $f^{\prime}(a)$ exists, we say that $f(x)$ is **differentiable** at $x=a$.
If $f^{\prime}(x)$ exists for every value of $x$ in the domain of the function, we say that $f(x)$ is **differentiable**.

---

## Geometrical Significance of a Derivative

Let $y=f(x)$ be a continuous function. Then, we draw its graph. Suppose it is a curve. Let $a$ be a point in the domain of the given function. Let $P[a, f(a)]$ be a point on this curve, and let $Q[a+h, f(a+h)]$ be some neighbouring point on it.

$$
\text{Slope of chord } PQ=\frac{f(a+h)-f(a)}{(a+h-a)}
$$

$$
=\frac{f(a+h)-f(a)}{h}
$$

Let the point $Q$ move along the curve such that $Q \rightarrow P$. As $Q$ comes closer and closer to $P$ along the curve, the chord $QP$ approaches the tangent at $P$. This happens when $h \rightarrow 0$.

$$
\therefore \lim_{h \rightarrow 0} \frac{f(a+h)-f(a)}{h}=\lim_{Q \rightarrow P} (\text{slope of chord } PQ)
$$

or

$$
f^{\prime}(a)=\text{the slope of the tangent at } P
$$

Hence, **the derivative of $f(x)$ at $x=a$ is the slope of the tangent to the curve $y=f(x)$ at the point $[a, f(a)]$**.

---

## Physical Significance of a Derivative

Let $s=f(t)$ be a function representing the distance travelled by a particle moving in a straight line in time $t$.

Let $(s+\delta s)$ be the distance travelled by it in time $(t+\delta t)$.

$$
\therefore s+\delta s=f(t+\delta t)
$$

On subtraction, we get $\delta s=f(t+\delta t)-f(t)$.

$$
\therefore \text{average velocity} =\frac{\delta s}{\delta t}=\frac{f(t+\delta t)-f(t)}{\delta t}
$$

Now, when $\delta t \rightarrow 0$, the average velocity becomes the **instantaneous velocity**.

$$
\therefore \text{velocity at time } t=\lim_{\delta t \rightarrow 0} \frac{\delta s}{\delta t}=\lim_{\delta t \rightarrow 0} \frac{f(t+\delta t)-f(t)}{\delta t}=f^{\prime}(t)
$$

---

## Differentiation From the First Principle

Obtaining the derivative of a given function by using the definition is called differentiation from the **first principle** or **ab initio** or by **delta method**.

---

## Some Important Derivatives Using the First Principle

### Theorem 1

**From the first principle, we have**

$$
\frac{d}{d x}\left(x^{n}\right)=n x^{n-1}, \text{ where } n \text{ is a fixed number, integer or rational.}
$$

#### Proof:

Let $y=x^{n}$. (i)

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.
Then, $y+\delta y=(x+\delta x)^{n}$. (ii)

On subtracting (i) from (ii), we get $\delta y=(x+\delta x)^{n}-x^{n}$.

$$
\text{or } \frac{\delta y}{\delta x}=\frac{(x+\delta x)^{n}-x^{n}}{\delta x}
$$

$$
\therefore \frac{d y}{d x}=\lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x} = \lim_{(x+\delta x) \rightarrow x} \frac{(x+\delta x)^{n}-x^{n}}{(x+\delta x)-x} \quad [\because \delta x \rightarrow 0 \text{ means } (x+\delta x) \rightarrow x]
$$

$$
= n x^{n-1} \quad \left[\because \lim_{z \rightarrow a} \frac{z^{n}-a^{n}}{z-a}=n a^{n-1}\right]
$$

Thus, $\frac{d y}{d x}=n x^{n-1}$, i.e., $\frac{d}{d x}\left(x^{n}\right)=n x^{n-1}$.

---

### Example

Find the derivatives of:
1.  $x^{9}$
2.  $x^{-3}$
3.  $\sqrt[3]{x}$
4.  $\frac{1}{\sqrt{x}}$

#### Solution:

We know that $\frac{d}{d x}\left(x^{n}\right)=n x^{n-1}$. So, we have:

1.  $\frac{d}{d x}\left(x^{9}\right)=9 \cdot x^{(9-1)}=9 x^{8}$.
2.  $\frac{d}{d x}\left(x^{-3}\right)=(-3) \cdot x^{(-3-1)}=-3 x^{-4}=\frac{-3}{x^{4}}$.
3.  $\frac{d}{d x}(\sqrt[3]{x})=\frac{d}{d x}\left(x^{1 / 3}\right)=\frac{1}{3} x^{\left(\frac{1}{3}-1\right)}=\frac{1}{3} x^{-2 / 3}$.
4.  $\frac{d}{d x}\left(\frac{1}{\sqrt{x}}\right)=\frac{d}{d x}\left(x^{-1 / 2}\right)=-\frac{1}{2} \cdot x^{\left(-\frac{1}{2}-1\right)}=-\frac{1}{2} x^{-3 / 2}$.

---

### Theorem 2

**From the first principle, we have $\frac{d}{d x}\left(e^{x}\right)=e^{x}$.**

#### Proof:

Let $y=e^{x}$ and $y+\delta y=e^{x+\delta x}$. Then, $\frac{\delta y}{\delta x}=\frac{e^{(x+\delta x)}-e^{x}}{\delta x}$.

$$
\therefore \frac{d y}{d x} = \lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{e^{(x+\delta x)}-e^{x}}{\delta x}=\lim_{\delta x \rightarrow 0} e^{x}\left(\frac{e^{\delta x}-1}{\delta x}\right)
$$

$$
= e^{x} \cdot \lim_{\delta x \rightarrow 0}\left(\frac{e^{\delta x}-1}{\delta x}\right)=e^{x} \quad \left[\because \lim_{\delta x \rightarrow 0} \frac{e^{\delta x}-1}{\delta x}=1\right]
$$

Thus, $\frac{d y}{d x}=e^{x}$, i.e., $\frac{d}{d x}\left(e^{x}\right)=e^{x}$.

---

### Theorem 3

**From the first principle, we have $\frac{d}{d x}(\sin x)=\cos x$.**

#### Proof:

Let $y=\sin x$ and $y+\delta y=\sin (x+\delta x)$. Then, $\frac{\delta y}{\delta x}=\frac{\sin (x+\delta x)-\sin x}{\delta x}$.

$$
\therefore \frac{d y}{d x}=\lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\sin (x+\delta x)-\sin x}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{2 \cos \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\delta x} \quad \left[\because \sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\right]
$$

$$
= \lim_{\delta x \rightarrow 0} \cos \left(x+\frac{\delta x}{2}\right) \cdot \lim_{\left(\frac{\delta x}{2}\right) \rightarrow 0} \frac{\sin \left(\frac{\delta x}{2}\right)}{\left(\frac{\delta x}{2}\right)}=(\cos x \times 1)=\cos x
$$

$\therefore \frac{d y}{d x}=\cos x$, i.e., $\frac{d}{d x}(\sin x)=\cos x$.

---

### Theorem 4

**From the first principle, we have $\frac{d}{d x}(\cos x)=-\sin x$.**

#### Proof:

Let $y=\cos x$ and $y+\delta y=\cos (x+\delta x)$. Then, $\frac{\delta y}{\delta x}=\frac{\cos (x+\delta x)-\cos x}{\delta x}$.

$$
\therefore \frac{d y}{d x} = \lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\cos (x+\delta x)-\cos x}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{-2 \sin \left(x+\frac{\delta x}{2}\right) \cdot \sin \left(\frac{\delta x}{2}\right)}{\delta x} \quad \left[\because \cos C-\cos D=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\right]
$$

$$
= -\lim_{\delta x \rightarrow 0} \sin \left(x+\frac{\delta x}{2}\right) \cdot \lim_{\delta x \rightarrow 0} \frac{\sin (\delta x / 2)}{(\delta x / 2)}=(-\sin x) \times 1=-\sin x
$$

$\therefore \frac{d y}{d x} = -\sin x$, i.e., $\frac{d}{d x}(\cos x)=-\sin x$.

---

### Theorem 5

**From the first principle, we have $\frac{d}{d x}(\tan x)=\sec ^{2} x$.**

#### Proof:

Let $y=\tan x$ and $y+\delta y=\tan (x+\delta x)$. Then, $\frac{\delta y}{\delta x}=\frac{\tan (x+\delta x)-\tan x}{\delta x}$.

$$
\therefore \frac{d y}{d x}=\lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\tan (x+\delta x)-\tan x}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\left\{\frac{\sin (x+\delta x)}{\cos (x+\delta x)}-\frac{\sin x}{\cos x}\right\}}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{\sin (x+\delta x) \cos x-\cos (x+\delta x) \sin x}{\delta x \cdot \cos (x+\delta x) \cdot \cos x}
$$

$$
= \frac{1}{\cos x} \cdot \lim_{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x \cdot \cos (x+\delta x)}
$$

$$
= \frac{1}{\cos x} \cdot \lim_{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x} \cdot \lim_{\delta x \rightarrow 0} \frac{1}{\cos (x+\delta x)}
$$

$$
= \left(\frac{1}{\cos x} \times 1 \times \frac{1}{\cos x}\right)=\frac{1}{\cos ^{2} x}=\sec ^{2} x
$$

$\therefore \frac{d y}{d x}= \sec ^{2} x$, i.e., $\frac{d}{d x}(\tan x)=\sec ^{2} x$.

---

### Theorem 6

**From the first principle, we have $\frac{d}{d x}(\sec x)=\sec x \tan x$.**

#### Proof:

Let $y=\sec x$ and $y+\delta y=\sec (x+\delta x)$. Then, $\frac{\delta y}{\delta x}=\frac{\sec (x+\delta x)-\sec x}{\delta x}$.

$$
\therefore \frac{d y}{d x} = \lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\sec (x+\delta x)-\sec x}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{\left\{\frac{1}{\cos (x+\delta x)}-\frac{1}{\cos x}\right\}}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\cos x-\cos (x+\delta x)}{\delta x \cdot \cos (x+\delta x) \cdot \cos x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{2 \sin \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\cos (x+\delta x) \cdot \cos x \cdot \delta x} \quad \left[\because \cos C-\cos D=2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{D-C}{2}\right)\right]
$$

$$
= \frac{1}{\cos x} \cdot \lim_{\delta x \rightarrow 0} \sin \left(x+\frac{\delta x}{2}\right) \cdot \lim_{\delta x \rightarrow 0} \frac{1}{\cos (x+\delta x)} \cdot \lim_{\delta x \rightarrow 0} \frac{\sin (\delta x / 2)}{(\delta x / 2)}
$$

$$
= \left(\frac{1}{\cos x} \times \sin x \times \frac{1}{\cos x} \times 1\right)=\sec x \tan x
$$

$\therefore \frac{d y}{d x}= \sec x \tan x$, i.e., $\frac{d}{d x}(\sec x)=\sec x \tan x$.

---

### Theorem 7

**From the first principle, we have $\frac{d}{d x}(\operatorname{cosec} x)=-\operatorname{cosec} x \cot x$.**

#### Proof:

Let $y=\operatorname{cosec} x$ and $y+\delta y=\operatorname{cosec}(x+\delta x)$. Then, $\frac{\delta y}{\delta x}=\frac{\operatorname{cosec}(x+\delta x)-\operatorname{cosec} x}{\delta x}$.

$$
\therefore \frac{d y}{d x} = \lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\operatorname{cosec}(x+\delta x)-\operatorname{cosec} x}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{\left\{\frac{1}{\sin (x+\delta x)}-\frac{1}{\sin x}\right\}}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\sin x-\sin (x+\delta x)}{\sin (x+\delta x) \cdot \sin x \cdot \delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{-2 \cos \left\{x+\frac{\delta x}{2}\right\} \cdot \sin \frac{\delta x}{2}}{\sin (x+\delta x) \cdot \sin x \cdot \delta x} \quad \left[\because \sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\right]
$$

$$
= -\frac{1}{\sin x} \cdot \lim_{\delta x \rightarrow 0} \cos \left(x+\frac{\delta x}{2}\right) \cdot \lim_{\delta x \rightarrow 0} \frac{\sin (\delta x / 2)}{(\delta x / 2)} \cdot \lim_{\delta x \rightarrow 0} \frac{1}{\sin (x+\delta x)}
$$

$$
= \left(-\frac{1}{\sin x} \times \cos x \times 1 \times \frac{1}{\sin x}\right)=-\operatorname{cosec} x \cot x
$$

$\therefore \frac{d y}{d x} = -\operatorname{cosec} x \cot x$, i.e., $\frac{d}{d x}(\operatorname{cosec} x)=-\operatorname{cosec} x \cot x$.

---

### Theorem 8

**From the first principle, we have $\frac{d}{d x}(\cot x)=-\operatorname{cosec}^{2} x$.**

#### Proof:

Let $y=\cot x$ and $y+\delta y=\cot (x+\delta x)$. Then, $\frac{\delta y}{\delta x}=\frac{\cot (x+\delta x)-\cot x}{\delta x}$.

$$
\therefore \frac{d y}{d x} = \lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\cot (x+\delta x)-\cot x}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\left\{\frac{\cos (x+\delta x)}{\sin (x+\delta x)}-\frac{\cos x}{\sin x}\right\}}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0} \frac{\sin x \cos (x+\delta x)-\cos x \sin (x+\delta x)}{\sin (x+\delta x) \cdot \sin x \cdot \delta x}
$$

$$
= \frac{1}{\sin x} \cdot \lim_{\delta x \rightarrow 0} \frac{-\sin \delta x}{\sin (x+\delta x) \cdot \delta x} \quad [\because \sin A \cos B-\cos A \sin B=\sin (A-B)]
$$

$$
= \frac{-1}{\sin x} \cdot \lim_{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x} \cdot \frac{1}{\lim_{\delta x \rightarrow 0} \sin (x+\delta x)}
$$

$$
= \left\{-\frac{1}{\sin x} \cdot 1 \cdot \frac{1}{\sin x}\right\}=\frac{-1}{\sin ^{2} x}=-\operatorname{cosec}^{2} x
$$

Thus, $\frac{d y}{d x}=-\operatorname{cosec}^{2} x$, i.e., $\frac{d}{d x}(\cot x)=-\operatorname{cosec}^{2} x$.

---

## Summary

We may summarise the above results as given below:
1.  $\frac{d}{d x}\left(x^{n}\right)=n x^{n-1}$
2.  $\frac{d}{d x}\left(e^{x}\right)=e^{x}$
3.  $\frac{d}{d x}(\sin x)=\cos x$
4.  $\frac{d}{d x}(\cos x)=-\sin x$
5.  $\frac{d}{d x}(\tan x)=\sec ^{2} x$
6.  $\frac{d}{d x}(\sec x)=\sec x \tan x$
7.  $\frac{d}{d x}(\operatorname{cosec} x)=-\operatorname{cosec} x \cot x$
8.  $\frac{d}{d x}(\cot x)=-\operatorname{cosec}^{2} x$

---

## Some More Results on Differentiation

### Theorem 9

**The derivative of a constant function is zero, i.e., $\frac{d}{d x}(c)=0$.**

#### Proof:

Let $f(x)=c$ be a constant function. Then, for any change $\delta x$ in $x$, there is no change in the value of the function.
$\therefore f(x)=c$ and $f(x+\delta x)=c$.

So, from first principle, we have

$$
\frac{d}{d x}(c)=f^{\prime}(x)=\lim_{\delta x \rightarrow 0} \frac{f(x+\delta x)-f(x)}{\delta x}=\lim_{\delta x \rightarrow 0}\left(\frac{c-c}{\delta x}\right)=0
$$

Hence, $\frac{d}{d x}(c)=0$, where $c$ is a constant.

---

### Theorem 10

**Let $f(x)$ be a differentiable function and let $c$ be a fixed real number. Then, $c \cdot f(x)$ is also differentiable and $\frac{d}{d x}\{c \cdot f(x)\}=c \cdot \frac{d}{d x}\{f(x)\}$.**

#### Proof:

Let $y=c \cdot f(x)$ and $y+\delta y=c \cdot f(x+\delta x)$.
Then, $\delta y=c \cdot f(x+\delta x)-c \cdot f(x)$.
$\therefore \frac{\delta y}{\delta x}=\frac{c \cdot f(x+\delta x)-c \cdot f(x)}{\delta x}$.

So,

$$
\frac{d y}{d x}=\lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{c \cdot f(x+\delta x)-c \cdot f(x)}{\delta x}
$$

$$
= c \cdot \lim_{\delta x \rightarrow 0} \frac{f(x+\delta x)-f(x)}{\delta x}=c \cdot \frac{d}{d x}\{f(x)\}
$$

Thus, $\frac{d y}{d x}=c \cdot \frac{d}{d x}\{f(x)\}$, i.e., $\frac{d}{d x}\{c \cdot f(x)\}=c \cdot \frac{d}{d x}\{f(x)\}$.

Now, $f(x)$ being differentiable, it follows that $\frac{d}{d x}\{f(x)\}$ exists and therefore, $c \cdot \frac{d}{d x}\{f(x)\}$ exists. Consequently, $\frac{d}{d x}\{c \cdot f(x)\}$ exists. This shows that $c \cdot f(x)$ is differentiable.

---

### Example 1

Find the derivative of:
1.  $8 x^{3}$
2.  $6 \sqrt{x}$
3.  $5 e^{x}$
4.  $9 \times 2^{x}$

#### Solution:

1.  $\frac{d}{d x}\left(8 x^{3}\right)=8 \cdot \frac{d}{d x}\left(x^{3}\right)=8 \times 3 x^{2}=24 x^{2}$.
2.  $\frac{d}{d x}(6 \sqrt{x})=6 \cdot \frac{d}{d x}\left(x^{1 / 2}\right)=6 \cdot \frac{1}{2} x^{-1 / 2}=\frac{3}{\sqrt{x}}$.
3.  $\frac{d}{d x}\left(5 e^{x}\right)=5 \cdot \frac{d}{d x}\left(e^{x}\right)=5 e^{x}$.
4.  $\frac{d}{d x}\left(9 \cdot 2^{x}\right)=9 \cdot \frac{d}{d x}\left(2^{x}\right)=9 \times 2^{x}(\log 2)$.

---

### Theorem 11

**If $f(x)$ and $g(x)$ are differentiable functions then $f(x)+g(x)$ is also differentiable, and**

$$
\frac{d}{d x}\{f(x)+g(x)\}=\frac{d}{d x}\{f(x)\}+\frac{d}{d x}\{g(x)\}
$$

#### Proof:

Let $y=f(x)+g(x)$ and let $y+\delta y=f(x+\delta x)+g(x+\delta x)$.
Then, $\frac{\delta y}{\delta x}=\frac{\{f(x+\delta x)+g(x+\delta x)\}-\{f(x)+g(x)\}}{\delta x}$.

$$
\therefore \frac{d y}{d x} = \lim_{\delta x \rightarrow 0} \frac{\delta y}{\delta x}=\lim_{\delta x \rightarrow 0} \frac{\{f(x+\delta x)+g(x+\delta x)\}-\{f(x)+g(x)\}}{\delta x}
$$

$$
= \lim_{\delta x \rightarrow 0}\left\{\frac{f(x+\delta x)-f(x)}{\delta x}+\frac{g(x+\delta x)-g(x)}{\delta x}\right\}
$$

$$
= \lim_{\delta x \rightarrow 0}\left\{\frac{f(x+\delta x)-f(x)}{\delta x}\right\}+\lim_{\delta x \rightarrow 0}\left\{\frac{g(x+\delta x)-g(x)}{\delta x}\right\}
$$

$$
= \frac{d}{d x}\{f(x)\}+\frac{d}{d x}\{g(x)\}
$$

$$
\therefore \frac{d}{d x}\{f(x)+g(x)\}=\frac{d}{d x}\{f(x)\}+\frac{d}{d x}\{g(x)\}
$$

Since $f(x)$ and $g(x)$ are differentiable, it follows that $\frac{d}{d x}\{f(x)\}$ as well as $\frac{d}{d x}\{g(x)\}$ exists. Consequently, $\frac{d}{d x}\{f(x)\}+\frac{d}{d x}\{g(x)\}$ exists. So, by the above result, $\frac{d}{d x}\{f(x)+g(x)\}$ exists. Hence, $\{f(x)+g(x)\}$ is differentiable.

**REMARK**: We may extend the above result for a finite number of differentiable functions. Thus, we have

$$
\frac{d}{d x}\left[f_{1}(x)+f_{2}(x)+\ldots+f_{n}(x)\right]=\frac{d}{d x}\left\{f_{1}(x)\right\}+\frac{d}{d x}\left\{f_{2}(x)\right\}+\ldots+\frac{d}{d x}\left\{f_{n}(x)\right\}
$$

---

### Example 2

Find the derivative of $\left(x^{3}+e^{x}+3^{x}+\cot x\right)$ with respect to $x$.

#### Solution:

We have

$$
\frac{d}{d x}\left(x^{3}+e^{x}+3^{x}+\cot x\right) = \frac{d}{d x}\left(x^{3}\right)+\frac{d}{d x}\left(e^{x}\right)+\frac{d}{d x}\left(3^{x}\right)+\frac{d}{d x}(\cot x)
$$

$$
=3 x^{2}+e^{x}+3^{x}(\log 3)-\operatorname{cosec}^{2} x
$$

---

### Example 3

Find the derivative of $\left(9 x^{2}+\frac{3}{x}+5 \sin x\right)$ with respect to $x$.

#### Solution:

We have $\frac{d}{d x}\left(9 x^{2}+\frac{3}{x}+5 \sin x\right)$

$$
= 9 \cdot \frac{d}{d x}\left(x^{2}\right)+3 \cdot \frac{d}{d x}\left(x^{-1}\right)+5 \cdot \frac{d}{d x}(\sin x)
$$

$$
= 9 \times 2 x+3 \cdot(-1) x^{-2}+5 \cos x=18 x-\frac{3}{x^{2}}+5 \cos x
$$

---

### Theorem 12

**If $f(x)$ and $g(x)$ be differentiable functions then $\{f(x)-g(x)\}$ is also differentiable, and**

$$
\frac{d}{d x}\{f(x)-g(x)\}=\frac{d}{d x}\{f(x)\}-\frac{d}{d x}\{g(x)\}
$$

#### Proof:

We have $\frac{d}{d x}\{f(x)-g(x)\}=\frac{d}{d x}\{f(x)+(-1) \cdot g(x)\}$.

$$
= \frac{d}{d x}\{f(x)\}+\frac{d}{d x}\{(-1) \cdot g(x)\}
$$

$$
= \frac{d}{d x}\{f(x)\}+(-1) \cdot \frac{d}{d x}\{g(x)\}=\frac{d}{d x}\{f(x)\}-\frac{d}{d x}\{g(x)\}
$$

$$
\therefore \frac{d}{d x}\{f(x)-g(x)\} = \frac{d}{d x}\{f(x)\}-\frac{d}{d x}\{g(x)\}
$$

Now, $f(x)$ and $g(x)$ being differentiable, it follows that $\frac{d}{d x}\{f(x)\}$ and $\frac{d}{d x}\{g(x)\}$ both exist. Consequently, $\frac{d}{d x}\{f(x)\}-\frac{d}{d x}\{g(x)\}$ exists. So, by the above result, $\frac{d}{d x}\{f(x)-g(x)\}$ exists. Hence, $\{f(x)-g(x)\}$ is differentiable.

---

## Solved Examples

### Example 1

Differentiate the following functions with respect to $x$: $\left(x^{2}+\frac{4}{x^{2}}-\frac{2}{3} \tan x+6 e\right)$

#### Solution:

$\frac{d}{d x}\left(x^{2}+\frac{4}{x^{2}}-\frac{2}{3} \tan x+6 e\right)$

$$
= \frac{d}{d x}\left(x^{2}\right)+4 \cdot \frac{d}{d x}\left(x^{-2}\right)-\frac{2}{3} \cdot \frac{d}{d x}(\tan x)+6 \cdot \frac{d}{d x}(e)
$$

$$
= 2 x+4 \cdot(-2) x^{-3}-\frac{2}{3} \sec ^{2} x+6 \times 0 \quad \left[\because \frac{d}{d x}(e)=0\right]
$$

$$
= 2 x-\frac{8}{x^{3}}-\frac{2}{3} \sec ^{2} x
$$

---

### Example 2

Find the derivative of $\left\{\frac{3}{\sqrt[3]{x}}-\frac{5}{\cos x}+\frac{6}{\sin x}-\frac{2 \tan x}{\sec x}+7\right\}$.

#### Solution:

We have $\frac{d}{d x}\left\{\frac{3}{\sqrt[3]{x}}-\frac{5}{\cos x}+\frac{6}{\sin x}-\frac{2 \tan x}{\sec x}+7\right\}$

$$
= \frac{d}{d x}\left\{3 x^{-1 / 3}-5 \sec x+6 \operatorname{cosec} x-2 \sin x+7\right\}
$$

$$
= 3 \cdot \frac{d}{d x}\left(x^{-1 / 3}\right)-5 \cdot \frac{d}{d x}(\sec x)+6 \cdot \frac{d}{d x}(\operatorname{cosec} x) -2 \cdot \frac{d}{d x}(\sin x)+\frac{d}{d x}(7)
$$

$$
= 3 \cdot\left(-\frac{1}{3}\right) x^{-4 / 3}-5 \sec x \tan x-6 \operatorname{cosec} x \cot x-2 \cos x
$$

$$
= \left\{\frac{-1}{x^{4 / 3}}-5 \sec x \tan x-6 \operatorname{cosec} x \cot x-2 \cos x\right\}
$$

---

### Example 3

Differentiate the following functions:
1.  $\left(x^{2}-5 x+6\right)(x-3)$
2.  $\left(\sqrt{x}+\frac{1}{\sqrt{x}}\right)^{2}$
3.  $\frac{3 x^{2}+2 x+5}{\sqrt{x}}$

#### Solution:

1.  $\frac{d}{d x}\left\{\left(x^{2}-5 x+6\right)(x-3)\right\}$
    $$
    = \frac{d}{d x}\left(x^{3}-8 x^{2}+21 x-18\right)
    $$
    $$
    = \frac{d}{d x}\left(x^{3}\right)-8 \cdot \frac{d}{d x}\left(x^{2}\right)+21 \cdot \frac{d}{d x}(x)-\frac{d}{d x}(18)
    $$
    $$
    = 3 x^{2}-8 \times 2 x+21 \times 1-0=\left(3 x^{2}-16 x+21\right)
    $$

2.  $\frac{d}{d x}\left\{\left(\sqrt{x}+\frac{1}{\sqrt{x}}\right)^{2}\right\} = \frac{d}{d x}\left\{x+\frac{1}{x}+2\right\}$
    $$
    = \frac{d}{d x}(x)+\frac{d}{d x}\left(x^{-1}\right)+\frac{d}{d x}(2)
    $$
    $$
    = 1+(-1) x^{-2}+0=\left(1-\frac{1}{x^{2}}\right)
    $$

3.  $\frac{d}{d x}\left\{\frac{3 x^{2}+2 x+5}{\sqrt{x}}\right\} = \frac{d}{d x}\left\{3 x^{3 / 2}+2 x^{1 / 2}+5 x^{-1 / 2}\right\}$
    $$
    = 3 \cdot \frac{d}{d x}\left(x^{3 / 2}\right)+2 \cdot \frac{d}{d x}\left(x^{1 / 2}\right)+5 \cdot \frac{d}{d x}\left(x^{-1 / 2}\right)
    $$
    $$
    = \frac{9}{2} \sqrt{x}+\frac{1}{\sqrt{x}}-\frac{5}{2} x^{-3 / 2}
    $$

---

### Example 4

If $y=\sqrt{\frac{1-\cos 2 x}{1+\cos 2 x}}$, find $\frac{d y}{d x}$.

#### Solution:

$y=\sqrt{\frac{1-\cos 2 x}{1+\cos 2 x}}=\sqrt{\frac{2 \sin ^{2} x}{2 \cos ^{2} x}}=\tan x$.

$$
\therefore \frac{d y}{d x}=\frac{d}{d x}(\tan x)=\sec ^{2} x
$$

---

### Example 5

If $y=\left(1+x+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\ldots \infty\right)$, show that $\frac{d y}{d x}=y$.

#### Solution:

We have, $y=e^{x}$.

$$
\therefore \frac{d y}{d x}=\frac{d}{d x}\left(e^{x}\right)=e^{x}=y
$$

---

### Example 6

If $u=3 t^{4}-5 t^{3}+2 t^{2}-18 t+4$, find $\frac{d u}{d t}$ at $t=1$.

#### Solution:

$\frac{d u}{d t}=\frac{d}{d t}\left(3 t^{4}-5 t^{3}+2 t^{2}-18 t+4\right)$

$$
= 3 \cdot \frac{d}{d t}\left(t^{4}\right)-5 \cdot \frac{d}{d t}\left(t^{3}\right)+2 \cdot \frac{d}{d t}\left(t^{2}\right)-18 \cdot \frac{d}{d t}(t)+\frac{d}{d t}(4)
$$

$$
= 3 \times 4 t^{3}-5 \times 3 t^{2}+2 \times 2 t-18 \times 1+0
$$

$$
= 12 t^{3}-15 t^{2}+4 t-18
$$

$$
\therefore \left(\frac{d u}{d t}\right)_{t=1}=\left(12 \times 1^{3}-15 \times 1^{2}+4 \times 1-18\right)
$$

$$
= (12-15+4-18)=-17
$$

---

