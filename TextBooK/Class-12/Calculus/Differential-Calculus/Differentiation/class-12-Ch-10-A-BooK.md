## 10. Differentiation

## 1. Derivatives of Some Functions

In class 11, we have studied about the derivatives of algebraic and trigonometric functions. We derived the following results.

1.  $\frac{d}{d x}\left(x^{n}\right)=n x^{n-1}$
2.  $\frac{d}{d x}(\sin x)=\cos x$
3.  $\frac{d}{d x}(\cos x)=-\sin x$
4.  $\frac{d}{d x}(\tan x)=\sec ^{2} x$
5.  $\frac{d}{d x}(\cot x)=-\operatorname{cosec}^{2} x$
6.  $\frac{d}{d x}(\sec x)=\sec x \tan x$
7.  $\frac{d}{d x}(\operatorname{cosec} x)=-\operatorname{cosec} x \cot x$

In algebra of derivatives, we have established the following rules.

## Some Rules of Differentiation

1.  $\frac{d}{d x}(u+v)=\left(\frac{d u}{d x}+\frac{d v}{d x}\right)$
2.  $\frac{d}{d x}(u-v)=\left(\frac{d u}{d x}-\frac{d v}{d x}\right)$
3.  $\frac{d}{d x}(u v)=\left(u \cdot \frac{d v}{d x}+v \cdot \frac{d u}{d x}\right)$
4.  $\frac{d}{d x}\left(\frac{u}{v}\right)=\frac{\left(v \cdot \frac{d u}{d x}-u \cdot \frac{d v}{d x}\right)}{v^{2}}$

## Derivatives of Composite Functions (Chain Rule)

1.  Let $y=f(t)$ and $t=g(x)$. Then, $\frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)$.
2.  Let $y=f(t), t=g(u)$ and $u=h(x)$. Then, $\frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d u} \times \frac{d u}{d x}\right)$. This rule may be extended further on more variables.

---

## Solved Examples

### Example 1

Differentiate each of the following w.r.t. $x$ :
1.  $\sin x^{3}$
2.  $\cos ^{3} x$
3.  $\tan \sqrt{x}$

#### Solution:

(i) Let $y=\sin x^{3}$.

Putting $x^{3}=t$, we get

$$
\begin{aligned}
y & =\sin t \text { and } t=x^{3} \\
\Rightarrow \frac{d y}{d t} & =\cos t \text { and } \frac{d t}{d x}=3 x^{2} \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right) \\
& =\left(\cos t \cdot 3 x^{2}\right)=3 x^{2} \cos t=3 x^{2} \cos x^{3}
\end{aligned}
$$

Hence, **$\frac{d}{d x}\left(\sin x^{3}\right)=3 x^{2} \cos x^{3}$**.

(ii) Let $y=\cos ^{3} x=(\cos x)^{3}$.

Putting $\cos x=t$, we get

$$
\begin{aligned}
y & =t^{3} \text { and } t=\cos x \\
\Rightarrow \frac{d y}{d t} & =3 t^{2} \text { and } \frac{d t}{d x}=-\sin x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right) \\
& =\left(-3 t^{2} \sin x\right)=(-3 \sin x) t^{2}=\left(-3 \sin x \cos ^{2} x\right)
\end{aligned}
$$

Hence, **$\frac{d}{d x}\left(\cos ^{3} x\right)=-3 \sin x \cos ^{2} x$**.

(iii) Let $y=\tan \sqrt{x}$.

Putting $\sqrt{x}=t$, we get

$$
\begin{aligned}
y & =\tan t \text { and } t=\sqrt{x} \\
\Rightarrow \frac{d y}{d t} & =\sec ^{2} t \text { and } \frac{d t}{d x}=\frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x}} \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right) \\
& =\left(\sec ^{2} t \cdot \frac{1}{2 \sqrt{x}}\right)=\frac{\sec ^{2} \sqrt{x}}{2 \sqrt{x}} \quad[\because t=\sqrt{x}] .
\end{aligned}
$$

Hence, **$\frac{d}{d x}(\tan \sqrt{x})=\frac{\sec ^{2} \sqrt{x}}{2 \sqrt{x}}$**.

---

### Example 2

Differentiate each of the following w.r.t. $x$ :
1.  $(a x+b)^{m}$
2.  $(2 x+3)^{5}$
3.  $\sqrt{a x^{2}+2 b x+c}$

#### Solution:

(i) Let $y=(a x+b)^{m}$.
Putting $(a x+b)=t$, we get

$$
\begin{aligned}
& y=t^{m} \text { and } t=(a x+b) \\
\Rightarrow & \frac{d y}{d t}=m t^{m-1} \text { and } \frac{d t}{d x}=a \\
\Rightarrow & \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\left(m t^{m-1} \times a\right)=m a t^{m-1}=m a(a x+b)^{m-1} \\
\therefore & \frac{d}{d x}(a x+b)^{m}=m a(a x+b)^{m-1}
\end{aligned}
$$

(ii) Let $y=(2 x+3)^{5}$.

Putting $(2 x+3)=t$, we get

$$
\begin{aligned}
y & =t^{5} \text { and } t=2 x+3 \\
\Rightarrow \frac{d y}{d t} & =5 t^{4} \text { and } \frac{d t}{d x}=2 \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=10 t^{4}=10(2 x+3)^{4}
\end{aligned}
$$

(iii) Let $y=\sqrt{a x^{2}+2 b x+c}$.

Putting $\left(a x^{2}+2 b x+c\right)=t$, we get

$$
\begin{aligned}
y & =\sqrt{t} \text { and } t=\left(a x^{2}+2 b x+c\right) \\
\Rightarrow \frac{d y}{d t} & =\frac{1}{2} t^{-1 / 2}=\frac{1}{2 \sqrt{t}} \text { and } \frac{d t}{d x}=(2 a x+2 b)=2(a x+b) \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{1}{2 \sqrt{t}} \times 2(a x+b) \\
& =\frac{(a x+b)}{\sqrt{t}}=\frac{(a x+b)}{\sqrt{a x^{2}+2 b x+c}}
\end{aligned}
$$

---

### Example 3

Differentiate $\sin 3 x \cos 5 x$ w.r.t. $x$.

#### Solution:

Let $y=\sin 3 x \cos 5 x=\frac{1}{2}\{2 \cos 5 x \sin 3 x\}$

$$
\begin{aligned}
& =\frac{1}{2}\{\sin (5 x+3 x)-\sin (5 x-3 x)\} \\
& =\frac{1}{2} \cdot(\sin 8 x-\sin 2 x)=\frac{1}{2} \sin 8 x-\frac{1}{2} \sin 2 x \\
\therefore \quad \frac{d y}{d x} & =\frac{1}{2} \cdot \frac{d}{d x}(\sin 8 x)-\frac{1}{2} \cdot \frac{d}{d x}(\sin 2 x) \\
& =\left(\frac{1}{2} \cdot 8 \cos 8 x-\frac{1}{2} \times 2 \cos 2 x\right)=(4 \cos 8 x-\cos 2 x)
\end{aligned}
$$

---

### Example 4

Differentiate $\sin 2 x \sin 4 x$ w.r.t. $x$.

#### Solution:

Let $y=\sin 2 x \sin 4 x=\frac{1}{2}(2 \sin 4 x \sin 2 x)$

$$
\begin{aligned}
& =\frac{1}{2}\{\cos (4 x-2 x)-\cos (4 x+2 x)\} \\
& =\frac{1}{2}[\cos 2 x-\cos 6 x] . \\
\therefore \quad \frac{d y}{d x} & =\frac{1}{2} \cdot \frac{d}{d x}(\cos 2 x)-\frac{1}{2} \cdot \frac{d}{d x}(\cos 6 x) \\
& =\frac{1}{2} \cdot(-2 \sin 2 x)-\frac{1}{2} \cdot(-6 \sin 6 x) \\
& =(3 \sin 6 x-\sin 2 x) .
\end{aligned}
$$

---

### Example 5

Differentiate $\sqrt{\frac{1-\tan x}{1+\tan x}}$ w.r.t.x.

#### Solution:

Let $y=\sqrt{\frac{1-\tan x}{1+\tan x}}$.
Putting $\frac{(1-\tan x)}{(1+\tan x)}=t$, we get

$$
\begin{aligned}
& y=\sqrt{t} \text { and } t=\frac{(1-\tan x)}{(1+\tan x)} \\
\therefore \quad & \frac{d y}{d t}=\frac{1}{2} t^{-1 / 2}=\frac{1}{2 \sqrt{t}} . \\
\text { And, } & \frac{d t}{d x}=\frac{(1+\tan x) \cdot \frac{d}{d x}(1-\tan x)-(1-\tan x) \cdot \frac{d}{d x}(1+\tan x)}{(1+\tan x)^{2}} \\
& =\frac{(1+\tan x)\left(-\sec ^{2} x\right)-(1-\tan x)\left(\sec ^{2} x\right)}{(1+\tan x)^{2}}=\frac{-2 \sec ^{2} x}{(1+\tan x)^{2}} \\
\therefore \quad \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{1}{2 \sqrt{t}} \times \frac{-2 \sec ^{2} x}{(1+\tan x)^{2}} \\
& =\frac{-\sec ^{2} x}{(1+\tan x)^{2}} \times \frac{\sqrt{1+\tan x}}{\sqrt{1-\tan x}} \\
& =\frac{-\sec ^{2} x}{(1+\tan x)^{3 / 2}(1-\tan x)^{1 / 2}}
\end{aligned}
$$

---

### Example 6

If $y=\frac{1}{\sqrt{a^{2}-x^{2}}}$, find $\frac{d y}{d x}$.

#### Solution:

Putting $\left(a^{2}-x^{2}\right)=t$, we get

$$
\begin{aligned}
y & =\frac{1}{\sqrt{t}}=t^{-1 / 2} \text { and } t=\left(a^{2}-x^{2}\right) \\
\Rightarrow \frac{d y}{d t} & =-\frac{1}{2} t^{-3 / 2}=\frac{-1}{2 t^{3 / 2}} \text { and } \frac{d t}{d x}=-2 x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{-1}{2 t^{3 / 2}} \times(-2 x)=\frac{x}{t^{3 / 2}}=\frac{x}{\left(a^{2}-x^{2}\right)^{3 / 2}} .
\end{aligned}
$$

---

### Example 7

If $y=\cos ^{2} x^{2}$, find $\frac{d y}{d x}$.

#### Solution:

Given: $y=\left(\cos x^{2}\right)^{2}$.
Putting $x^{2}=t$ and $\cos t=u$, we get

$$
\begin{aligned}
y & =u^{2}, u=\cos t \text { and } t=x^{2} \\
\Rightarrow \frac{d y}{d u} & =2 u, \frac{d u}{d t}=-\sin t \text { and } \frac{d t}{d x}=2 x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) \\
& =(2 u) \times(-\sin t) \times 2 x \\
& =-4 x u \sin t=-4 x \cos t \sin t=-4 x \cos x^{2} \sin x^{2} . \\
\therefore \quad \frac{d y}{d x} & =-4 x \cos x^{2} \sin x^{2} .
\end{aligned}
$$

---

### Example 8

If $y=\sin \left(\cos x^{2}\right)$, find $\frac{d y}{d x}$.

#### Solution:

Putting $x^{2}=t$ and $\cos x^{2}=\cos t=u$, we get

$$
\begin{aligned}
y & =\sin u, u=\cos t \text { and } t=x^{2} \\
\Rightarrow \frac{d y}{d u} & =\cos u, \frac{d u}{d t}=-\sin t \text { and } \frac{d t}{d x}=2 x \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) \\
& =\{\cos u \times(-\sin t) \times 2 x\}=-2 x \sin t \cos u \\
& =-2 x \sin t \cos (\cos t)=-2 x \sin x^{2} \cos \left(\cos x^{2}\right) . \\
\therefore \quad \frac{d y}{d x} & =-2 x \sin x^{2} \cos \left(\cos x^{2}\right) .
\end{aligned}
$$

---

### Example 9

If $y=\sin (\sqrt{\sin x+\cos x})$, find $\frac{d y}{d x}$.

#### Solution:

Putting $(\sin x+\cos x)=t$ and $\sqrt{t}=u$, we get

$$
\begin{aligned}
y & =\sin u, u=\sqrt{t} \text { and } t=(\sin x+\cos x) \\
\Rightarrow \frac{d y}{d u} & =\cos u, \frac{d u}{d t}=\frac{1}{2} t^{-1 / 2}=\frac{1}{2 \sqrt{t}} \text { and } \frac{d t}{d x}=(\cos x-\sin x) \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) \\
& =\left\{\cos u \times \frac{1}{2 \sqrt{t}} \times(\cos x-\sin x)\right\}=\frac{\cos \sqrt{t}}{2 \sqrt{t}} \cdot(\cos x-\sin x) \\
& =\frac{\cos (\sqrt{\sin x+\cos x})}{2 \sqrt{\sin x+\cos x}} \cdot(\cos x-\sin x)
\end{aligned}
$$

---

### Example 10

If $y=\sin [\sqrt{\sin \sqrt{x}}]$, find $\frac{d y}{d x}$.

#### Solution:

Putting $\sqrt{x}=t, \sin \sqrt{x}=\sin t=u$ and $\sqrt{\sin \sqrt{x}}=\sqrt{u}=v$, we get

$$
\begin{aligned}
& y=\sin v, v=\sqrt{u}, u=\sin t \text { and } t=\sqrt{x} . \\
\therefore \quad & \frac{d y}{d v}=\cos v ; \frac{d v}{d u}=\frac{1}{2} u^{-1 / 2}=\frac{1}{2 \sqrt{u}} ; \frac{d u}{d t}=\cos t \text { and } \frac{d t}{d x}=\frac{1}{2 \sqrt{x}} .
\end{aligned}
$$

So, $\frac{d y}{d x}=\left(\frac{d y}{d v} \times \frac{d v}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right)=\left[\cos v \cdot \frac{1}{2 \sqrt{u}} \cdot \cos t \cdot \frac{1}{2 \sqrt{x}}\right]$

$$
\begin{array}{ll}
=\left[\cos \sqrt{u} \cdot \frac{1}{2 \sqrt{u}} \cos t \cdot \frac{1}{2 \sqrt{x}}\right] & {[\because \quad v=\sqrt{u}]} \\
=\frac{1}{4} \cos (\sqrt{\sin t}) \cdot \frac{1}{\sqrt{\sin t}} \cdot \cos \sqrt{x} \cdot \frac{1}{\sqrt{x}} & {[\because \quad u=\sin t]} \\
=\frac{1}{4} \cos (\sqrt{\sin \sqrt{x}}) \cdot \frac{1}{\sqrt{\sin \sqrt{x}}} \cdot \cos \sqrt{x} \cdot \frac{1}{\sqrt{x}} & {[\because \quad t=\sqrt{x}]} \\
=\frac{\cos (\sqrt{\sin \sqrt{x}})}{4 \sqrt{x} \sqrt{\sin \sqrt{x}}} \cdot \cos \sqrt{x} . &
\end{array}
$$

---

### Example 11

If $y=\frac{5 x}{\sqrt[3]{1-x^{2}}}+\sin ^{2}(2 x+3)$, find $\frac{d y}{d x}$.
[CBSE 2000C]

#### Solution:

We have

$$
\begin{aligned}
y & =5 x\left(1-x^{2}\right)^{-1 / 3}+\sin ^{2}(2 x+3) \\
\Rightarrow \frac{d y}{d x} & =\frac{d}{d x}\left\{5 x\left(1-x^{2}\right)^{-1 / 3}\right\}+\frac{d}{d x}\left\{\sin ^{2}(2 x+3)\right\} \\
& =\left\{5 x \cdot\left(\frac{-1}{3}\right)\left(1-x^{2}\right)^{-4 / 3} \cdot(-2 x)+\left(1-x^{2}\right)^{-1 / 3} \cdot 5\right\} \\
& \quad+\{2 \sin (2 x+3) \cos (2 x+3) \cdot 2\} \\
& =\frac{10 x^{2}}{3\left(1-x^{2}\right)^{\frac{4}{3}}}+\frac{5}{\left(1-x^{2}\right)^{\frac{1}{3}}}+2 \sin (4 x+6) \\
& =\frac{10 x^{2}+15\left(1-x^{2}\right)}{3\left(1-x^{2}\right)^{\frac{4}{3}}}+2 \sin (4 x+6) \\
& =\frac{\left(15-5 x^{2}\right)}{3\left(1-x^{2}\right)^{\frac{4}{3}}}+2 \sin (4 x+6)
\end{aligned}
$$

---

## Exercise 10A

Differentiate each of the following w.r.t. $x$ :

1.  $\sin 4 x$
2.  $\cos 5 x$
3.  $\tan 3 x$
4.  $\cos x^{3}$
5.  $\cot ^{2} x$
6.  $\tan ^{3} x$
7.  $\cot \sqrt{x}$
8.  $\sqrt{\tan x}$
9.  $(5+7 x)^{6}$
10. $(3-4 x)^{5}$
11. $\left(2 x^{2}-3 x+4\right)^{5}$
12. $\left(a x^{2}+b x+c\right)^{6}$
13. $\frac{1}{\left(x^{2}-3 x+5\right)^{3}}$
14. $\sqrt{\frac{a^{2}-x^{2}}{a^{2}+x^{2}}}$
15. $\sqrt{\frac{1+\sin x}{1-\sin x}}$
16. $\cos ^{2} x^{3}$
17. $\sec ^{3}\left(x^{2}+1\right)$
18. $\sqrt{\cos 3 x}$
19. $\sqrt[3]{\sin 2 x}$
20. $\sqrt{1+\cot x}$
21. $\operatorname{cosec}^{3} \frac{1}{x^{2}}$
22. $\sqrt{\sin x^{3}}$
23. $\sqrt{x \sin x}$
24. $\sqrt{\cot \sqrt{x}}$
25. $\cot ^{3} x^{2}$
26. $\cos (\sin \sqrt{a x+b})$
27. $\sqrt{\operatorname{cosec}\left(x^{3}+1\right)}$
28. $\sin 5 x \cos 3 x$
29. $\sin 2 x \sin x$
30. $\cos 4 x \cos 2 x$

**Find $\frac{d y}{d x}$, when:**
31. $y=\sin \left(\frac{1+x^{2}}{1-x^{2}}\right)$
32. $y=\frac{\left(\sin x+x^{2}\right)}{\cot 2 x}$
33. If $y=\frac{(\cos x-\sin x)}{(\cos x+\sin x)}$, prove that $\frac{d y}{d x}+y^{2}+1=0$.
34. If $y=\frac{(\cos x+\sin x)}{(\cos x-\sin x)}$, prove that $\frac{d y}{d x}=\sec ^{2}\left(x+\frac{\pi}{4}\right)$.

---

## Answers (Exercise 10A)

1.  $4 \cos 4 x$
2.  $-5 \sin 5 x$
3.  $3 \sec ^{2} 3 x$
4.  $-3 x^{2} \sin x^{3}$
5.  $-2 \cot x \operatorname{cosec}^{2} x$
6.  $3 \tan ^{2} x \sec ^{2} x$
7.  $\frac{-1}{2 \sqrt{x}} \operatorname{cosec}^{2} \sqrt{x}$
8.  $\frac{\sec ^{2} x}{2 \sqrt{\tan x}}$
9.  $42(5+7 x)^{5}$
10. $-20(3-4 x)^{4}$
11. $5\left(2 x^{2}-3 x+4\right)^{4}(4 x-3)$
12. $6\left(a x^{2}+b x+c\right)^{5}(2 a x+b)$
13. $\frac{-3(2 x-3)}{\left(x^{2}-3 x+5\right)^{4}}$
14. $\frac{-2 a^{2} x}{\left(a^{2}+x^{2}\right)^{3 / 2}\left(a^{2}-x^{2}\right)^{1 / 2}}$
15. $\sec x(\sec x+\tan x)$
16. $-3 x^{2} \sin \left(2 x^{3}\right)$
17. $6 x \sec ^{3}\left(x^{2}+1\right) \tan \left(x^{2}+1\right)$
18. $\frac{-3}{2} \cdot \frac{\sin 3 x}{\sqrt{\cos 3 x}}$
19. $\frac{2}{3} \cdot \frac{\cos 2 x}{(\sin 2 x)^{2 / 3}}$
20. $-\frac{1}{2} \cdot \frac{\operatorname{cosec}^{2} x}{\sqrt{1+\cot x}}$
21. $\frac{6}{x^{3}} \operatorname{cosec}^{3} \frac{1}{x^{2}} \cot \frac{1}{x^{2}}$
22. $\frac{3}{2} x^{2} \cdot \frac{\cos x^{3}}{\sqrt{\sin x^{3}}}$
23. $\frac{(x \cos x+\sin x)}{2 \sqrt{x \sin x}}$
24. $\frac{-\operatorname{cosec}^{2} \sqrt{x}}{4 \sqrt{x} \sqrt{\cot \sqrt{x}}}$
25. $-6 x \cot ^{2} x^{2} \operatorname{cosec}^{2} x^{2}$
26. $\frac{-a \cos \sqrt{a x+b}}{2 \sqrt{a x+b}} \cdot \sin \{\sin \sqrt{a x+b}\}$
27. $-\frac{3}{2} x^{2} \sqrt{\operatorname{cosec}\left(x^{3}+1\right)} \cdot \cot \left(x^{3}+1\right)$
28. $(4 \cos 8 x+\cos 2 x)$
29. $\left(\frac{3}{2} \sin 3 x-\frac{1}{2} \sin x\right)$
30. $-(3 \sin 6 x+\sin 2 x)$
31. $\frac{4 x}{\left(1-x^{2}\right)^{2}} \cdot \cos \left(\frac{1+x^{2}}{1-x^{2}}\right)$
32. $2\left(\sin x+x^{2}\right) \sec ^{2} 2 x+(\cos x+2 x) \tan 2 x$

---

## Hints to Some Selected Questions (Exercise 10A)

15. $y=\frac{\sqrt{1+\sin x}}{\sqrt{1-\sin x}} \times \frac{\sqrt{1+\sin x}}{\sqrt{1+\sin x}}=\frac{(1+\sin x)}{\cos x}=(\sec x+\tan x)$
    $\Rightarrow \frac{d y}{d x}=\left(\sec x \tan x+\sec ^{2} x\right)=\sec x(\sec x+\tan x)$.
16. $y=\left(\sin x+x^{2}\right) \tan 2 x$
    $\Rightarrow \frac{d y}{d x}=\left(\sin x+x^{2}\right) \cdot \frac{d}{d x}(\tan 2 x)+\tan 2 x \cdot \frac{d}{d x}\left(\sin x+x^{2}\right)$.
17. $y=\left(\frac{1-\tan x}{1+\tan x}\right)$ [on dividing num. and denom. by $\cos x$ ]
    $\Rightarrow y=\tan \left(\frac{\pi}{4}-x\right)$
    $\Rightarrow \frac{d y}{d x}=-\sec ^{2}\left(\frac{\pi}{4}-x\right)$
    $\Rightarrow \frac{d y}{d x}+y^{2}+1=-\sec ^{2}\left(\frac{\pi}{4}-x\right)+\tan ^{2}\left(\frac{\pi}{4}-x\right)+1=0$.
18. $y=\left(\frac{1+\tan x}{1-\tan x}\right)$
    $\Rightarrow y=\tan \left(\frac{\pi}{4}+x\right)$
    $\Rightarrow \frac{d y}{d x}=\sec ^{2}\left(\frac{\pi}{4}+x\right)$.