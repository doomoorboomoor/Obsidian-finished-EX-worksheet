## 5. Differentiation of Implicit Function

Let $f(x, y)=a$ be a function of $x$ and $y$ defined in such a manner that $y$ is not expressible directly in terms of $x$. Then, $f(x, y)=a$ is called an **implicit function** of $x$ and $y$. In differentiating such a function, we differentiate both sides of the equation termwise, keeping in mind that

$$
\frac{d}{d x}\left(y^{2}\right)=2 y \cdot \frac{d y}{d x} ; \frac{d}{d x}\left(y^{3}\right)=3 y^{2} \cdot \frac{d y}{d x}, \text { and so on. }
$$

---

## Solved Examples

### Example 1:

If $x^{3}+y^{3}=3 a x y$, find $\frac{d y}{d x}$.

#### Solution:

Given: $x^{3}+y^{3}=3 a x y$.

Differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& 3 x^{2}+3 y^{2} \cdot \frac{d y}{d x}=3 a \cdot\left\{x \cdot \frac{d y}{d x}+y \cdot 1\right\} \\
\Rightarrow & 3\left(y^{2}-a x\right) \cdot \frac{d y}{d x}=3\left(a y-x^{2}\right) \\
\Rightarrow & \frac{d y}{d x}=\left(\frac{a y-x^{2}}{y^{2}-a x}\right)
\end{aligned}
$$

---

### Example 2:

If $a x^{2}+2 h x y+b y^{2}+2 g x+2 f y+c=0$, find $\frac{d y}{d x}$.

#### Solution:

Given: $a x^{2}+2 h x y+b y^{2}+2 g x+2 f y+c=0$. (i)

Differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& 2 a x+2 h\left(x \cdot \frac{d y}{d x}+y \cdot 1\right)+2 b y \cdot \frac{d y}{d x}+2 g+2 f \cdot \frac{d y}{d x}=0 \\
\Rightarrow & (2 a x+2 h y+2 g)+(2 h x+2 b y+2 f) \cdot \frac{d y}{d x}=0 \\
\Rightarrow & \frac{d y}{d x}=-\left(\frac{a x+h y+g}{h x+b y+f}\right)
\end{aligned}
$$

---

### Example 3:

If $\sqrt{1-x^{2}}+\sqrt{1-y^{2}}=a(x-y)$, prove that $\frac{d y}{d x}=\sqrt{\frac{1-y^{2}}{1-x^{2}}}$.

#### Solution:

Given: $\sqrt{1-x^{2}}+\sqrt{1-y^{2}}=a(x-y)$.

Putting $x=\sin \theta$ and $y=\sin \phi$, it becomes

$$
\cos \theta+\cos \phi = a(\sin \theta-\sin \phi)
$$
$$
\Rightarrow \frac{\cos \theta+\cos \phi}{\sin \theta-\sin \phi} = a
$$
$$
\Rightarrow \frac{2 \cos \left(\frac{\theta+\phi}{2}\right) \cos \left(\frac{\theta-\phi}{2}\right)}{2 \cos \left(\frac{\theta+\phi}{2}\right) \sin \left(\frac{\theta-\phi}{2}\right)}=a
$$
$$
\begin{equation*}
\Rightarrow \cot \left(\frac{\theta-\phi}{2}\right)=a \Rightarrow \theta-\phi=2 \cot ^{-1} a \tag{ii}
\end{equation*}
$$
$$
\Rightarrow \sin ^{-1} x-\sin ^{-1} y=2 \cot ^{-1} a.
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\frac{1}{\sqrt{1-x^{2}}}-\frac{1}{\sqrt{1-y^{2}}} \cdot \frac{d y}{d x}=0 .
$$

Hence, $\frac{d y}{d x}=\sqrt{\frac{1-y^{2}}{1-x^{2}}}$.

---

### Example 4:

If $x \sqrt{1-y^{2}}+y \sqrt{1-x^{2}}=1$, prove that $\frac{d y}{d x}=-\sqrt{\frac{1-y^{2}}{1-x^{2}}}$.

#### Solution:

We have $x \sqrt{1-y^{2}}+y \sqrt{1-x^{2}}=1$. (i)

Putting $x=\sin \theta$ and $y=\cos \phi$ in (i), we get
$$
\sin \theta \cos \phi+\cos \theta \sin \phi=1
$$
$$
\Rightarrow \sin (\theta+\phi)=1
$$
$$
\begin{equation*}
\Rightarrow(\theta+\phi)=\sin ^{-1}(1) \tag{ii}
\end{equation*}
$$
$$
\Rightarrow \sin ^{-1} x+\sin ^{-1} y=\frac{\pi}{2}.
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \quad \frac{1}{\sqrt{1-x^{2}}}+\frac{1}{\sqrt{1-y^{2}}} \cdot \frac{d y}{d x}=0 \\
& \therefore \quad \frac{d y}{d x}=-\sqrt{\frac{1-y^{2}}{1-x^{2}}} .
\end{aligned}
$$

---

### Example 5:

If $x \sqrt{1+y}+y \sqrt{1+x}=0$, prove that $\frac{d y}{d x}=\frac{-1}{(1+x)^{2}}$.

#### Solution:

$$
\begin{aligned}
& x \sqrt{1+y}+y \sqrt{1+x}=0 \\
& \Rightarrow x \sqrt{1+y}=-y \sqrt{1+x} \\
& \Rightarrow x^{2}(1+y)=y^{2}(1+x) \quad \text { [on squaring both sides] } \\
& \Rightarrow(x-y)(x+y+x y)=0 \\
& \Rightarrow x+y+x y=0 \quad[\because \quad x=y \text { does not satisfy the given equation] } \\
& \Rightarrow y=\frac{-x}{1+x}
\end{aligned}
$$

$$
\therefore \frac{d y}{d x}=-\left\{\frac{(1+x) \cdot 1-x \cdot 1}{(1+x)^{2}}\right\}=\frac{-1}{(1+x)^{2}} \quad \text [using the quotient rule].
$$

---

### Example 6:

If $\sin y=x \sin (a+y)$, prove that $\frac{d y}{d x}=\frac{\sin ^{2}(a+y)}{\sin a}$.
[CBSE 2012]

#### Solution:

$\sin y=x \sin (a+y)$

$$
\begin{equation*}
\Rightarrow x=\frac{\sin y}{\sin (a+y)} \tag{i}
\end{equation*}
$$

On differentiating both sides of (i) w.r.t. $y$, we get

$$
\begin{aligned}
\frac{d x}{d y} & =\frac{\sin (a+y) \cos y-\sin y \cos (a+y)}{\sin ^{2}(a+y)} \text { [using the quotient rule] } \\
& =\frac{\sin (a+y-y)}{\sin ^{2}(a+y)}=\frac{\sin a}{\sin ^{2}(a+y)}
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{\sin ^{2}(a+y)}{\sin a}$.

---

### Example 7:

If $y \cdot \sqrt{x^{2}+1}=\log \left\{\sqrt{x^{2}+1}-x\right\}$, show that

$$
\begin{equation*}
\left(x^{2}+1\right) \frac{d y}{d x}+x y+1=0 \tag{i}
\end{equation*}
$$
[CBSE 2006]

#### Solution:

Given: $y \cdot \sqrt{x^{2}+1}=\log \left\{\sqrt{x^{2}+1}-x\right\}$. (i)

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& y \cdot \frac{1}{2}\left(x^{2}+1\right)^{-1 / 2} \cdot 2 x+\left(\sqrt{x^{2}+1}\right) \cdot \frac{d y}{d x} \\
& =\frac{1}{\left\{\sqrt{x^{2}+1}-x\right\}} \cdot\left\{\frac{1}{2}\left(x^{2}+1\right)^{-1 / 2} \cdot 2 x-1\right\} \\
\Rightarrow & \frac{x y}{\sqrt{x^{2}+1}}+\left(\sqrt{x^{2}+1}\right) \frac{d y}{d x}=\frac{1}{\left\{\sqrt{x^{2}+1}-x\right\}} \cdot\left\{\frac{x}{\sqrt{x^{2}+1}}-1\right\} \\
\Rightarrow & \frac{x y}{\sqrt{x^{2}+1}}+\left(\sqrt{x^{2}+1}\right) \frac{d y}{d x}=\frac{1}{\left\{\sqrt{x^{2}+1}-x\right\}} \cdot \frac{\left\{x-\sqrt{x^{2}+1}\right\}}{\sqrt{x^{2}+1}} \\
\Rightarrow & x y+\left(x^{2}+1\right) \frac{d y}{d x}=-1 \\
\Rightarrow & \left(x^{2}+1\right) \frac{d y}{d x}+x y+1=0
\end{aligned}
$$

---

### Example 8:

If $y=\sqrt{x}+\frac{1}{\sqrt{x}}$, show that $2 x \frac{d y}{d x}+y=2 \sqrt{x}$.
[CBSE 2006]

#### Solution:

$y=\sqrt{x}+\frac{1}{\sqrt{x}} \Rightarrow \sqrt{x} y=x+1$ (i)

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& \sqrt{x} \cdot \frac{d y}{d x}+y \cdot \frac{1}{2} x^{-1 / 2}=1 \\
\Rightarrow & \sqrt{x} \frac{d y}{d x}+\frac{y}{2 \sqrt{x}}=1 \\
\Rightarrow & 2 x \frac{d y}{d x}+y=2 \sqrt{x} .
\end{aligned}
$$

---

### Example 9:

If $\cos (x+y)=y \sin x$, find $\frac{d y}{d x}$.

#### Solution:

Given: $\cos (x+y)=y \sin x$. (i)

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& -\sin (x+y) \cdot \frac{d}{d x}(x+y)=y \cos x+\sin x \cdot \frac{d y}{d x} \\
\Rightarrow & -\sin (x+y) \cdot\left(1+\frac{d y}{d x}\right)=y \cos x+\sin x \cdot \frac{d y}{d x} \\
\Rightarrow & \{\sin (x+y)+\sin x\} \cdot \frac{d y}{d x}=-\{\sin (x+y)+y \cos x\} \\
\Rightarrow & \frac{d y}{d x}=\frac{-\{\sin (x+y)+y \cos x\}}{\{\sin (x+y)+\sin x\}}
\end{aligned}
$$

---

### Example 10:

Find $\frac{d y}{d x}$ when $\sin (x y)+\frac{x}{y}=x^{2}-y$.

#### Solution:

Given: $\sin (x y)+\frac{x}{y}=x^{2}-y$.

Differentiating both sides w.r.t. $x$, we get

$$
\begin{aligned}
& \cos (x y) \cdot \frac{d}{d x}(x y)+x \cdot\left(-\frac{1}{y^{2}}\right) \frac{d y}{d x}+\frac{1}{y} \cdot 1=2 x-\frac{d y}{d x} \\
\Rightarrow & \cos (x y) \cdot\left[x \cdot \frac{d y}{d x}+y \cdot 1\right]-\frac{x}{y^{2}} \cdot \frac{d y}{d x}+\frac{1}{y}=2 x-\frac{d y}{d x} \\
\Rightarrow & {\left[x \cos (x y)-\frac{x}{y^{2}}+1\right] \cdot \frac{d y}{d x}=2 x-\frac{1}{y}-y \cos (x y) } \\
\Rightarrow & \left\{x y^{2} \cos (x y)-x+y^{2}\right\} \cdot \frac{d y}{d x}=2 x y^{2}-y-y^{3} \cos (x y)
\end{aligned}
$$

Hence,
$$
\frac{d y}{d x}=\left\{\frac{2 x y^{2}-y-y^{3} \cos (x y)}{x y^{2} \cos (x y)-x+y^{2}}\right\}
$$

---

### Example 11:

If $e^{x}+e^{y}=e^{x+y}$, prove that $\frac{d y}{d x}=-e^{y-x}$.

#### Solution:

Given: $e^{x}+e^{y}=e^{x+y}$. (i)

On dividing throughout by $e^{x+y}$, we get

$$
\begin{equation*}
e^{-y}+e^{-x}=1 \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& e^{-y} \cdot\left(\frac{-d y}{d x}\right)+e^{-x}(-1)=0 \\
\Rightarrow & \frac{d y}{d x}=\frac{-e^{-x}}{e^{-y}}=-e^{(y-x)}
\end{aligned}
$$

---

### Example 12:

If $\tan ^{-1}\left(\frac{x^{2}-y^{2}}{x^{2}+y^{2}}\right)=a$, show that $\frac{d y}{d x}=\frac{x(1-\tan a)}{y(1+\tan a)}$.

#### Solution:

$\tan ^{-1}\left(\frac{x^{2}-y^{2}}{x^{2}+y^{2}}\right)=a \Rightarrow \frac{\left(x^{2}-y^{2}\right)}{\left(x^{2}+y^{2}\right)}=\tan a$

$$
\begin{equation*}
\therefore\left(x^{2}-y^{2}\right)=\left(x^{2}+y^{2}\right) \tan a . \tag{i}
\end{equation*}
$$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& 2 x-2 y \cdot \frac{d y}{d x}=2 x \tan a+2 y \cdot \frac{d y}{d x} \cdot \tan a \\
\Rightarrow & y(1+\tan a) \frac{d y}{d x}=x(1-\tan a) \\
\Rightarrow & \frac{d y}{d x}=\frac{x(1-\tan a)}{y(1+\tan a)}
\end{aligned}
$$

---

## Exercise 10E

Find $\frac{d y}{d x}$, when:

1.  $x^{2}+y^{2}=4$
2.  $\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1$
3.  $\sqrt{x}+\sqrt{y}=\sqrt{a}$
4.  $x^{2 / 3}+y^{2 / 3}=a^{2 / 3}$
5.  $x y=c^{2}$
6.  $x^{2}+y^{2}-3 x y=1$
7.  $x y^{2}-x^{2} y-5=0$
8.  $\left(x^{2}+y^{2}\right)^{2}=x y$
9.  $x^{2}+y^{2}=\log (x y)$
10. $x^{n}+y^{n}=a^{n}$
11. $x \sin 2 y=y \cos 2 x$
12. $\sin ^{2} x+2 \cos y+x y=0$
13. $y \sec x+\tan x+x^{2} y=0$
14. $\cot (x y)+x y=y$
15. $y \tan x-y^{2} \cos x+2 x=0$
16. $e^{x} \log y=\sin ^{-1} x+\sin ^{-1} y$
17. $x y \log (x+y)=1$
18. $\tan (x+y)+\tan (x-y)=1$
19. $\log \sqrt{x^{2}+y^{2}}=\tan ^{-1} \frac{y}{x}$
20. If $y=x \sin y$, prove that $\left(x \cdot \frac{d y}{d x}\right)=\frac{y}{(1-x \cos y)}$.
21. If $x y=\tan (x y)$, show that $\frac{d y}{d x}=\frac{-y}{x}$.
22. If $y \log x=(x-y)$, prove that $\frac{d y}{d x}=\frac{\log x}{(1+\log x)^{2}}$.
23. If $\cos y=x \cos (y+a)$, prove that $\frac{d y}{d x}=\frac{\cos ^{2}(y+a)}{\sin a}$.
24. If $\cos ^{-1}\left(\frac{x^{2}-y^{2}}{x^{2}+y^{2}}\right)=\tan ^{-1} a$, prove that $\frac{d y}{d x}=\frac{y}{x}$.

---

## Answers (Exercise 10E)

1.  $\frac{-x}{y}$
2.  $\frac{-b^{2} x}{a^{2} y}$
3.  $-\sqrt{\frac{y}{x}}$
4.  $\frac{-y^{1 / 3}}{x^{1 / 3}}$
5.  $\frac{-c^{2}}{x^{2}}$
6.  $\frac{(2 x-3 y)}{(3 x-2 y)}$
7.  $\frac{\left(y^{2}-2 x y\right)}{\left(x^{2}-2 x y\right)}$
8.  $\frac{\left(y-4 x y^{2}-4 x^{3}\right)}{\left(4 y^{3}+4 x^{2} y-x\right)}$
9.  $\frac{y\left(1-2 x^{2}\right)}{x\left(2 y^{2}-1\right)}$
10. $\frac{-x^{n-1}}{y^{n-1}}$
11. $\frac{(2 y \sin 2 x+\sin 2 y)}{(\cos 2 x-2 x \cos 2 y)}$
12. $\frac{(y+\sin 2 x)}{(2 \sin y-x)}$
13. $\frac{-\left(y \sec x \tan x+\sec ^{2} x+2 x y\right)}{\left(x^{2}+\sec x\right)}$
14. $\frac{-y \cot ^{2}(x y)}{\left\{1+x \cot ^{2}(x y)\right\}}$
15. $\frac{\left(y \sec ^{2} x+y^{2} \sin x+2\right)}{(2 y \cos x-\tan x)}$
16. $y \cdot \sqrt{\frac{1-y^{2}}{1-x^{2}}} \cdot\left\{\frac{1-e^{x} \log y \cdot \sqrt{1-x^{2}}}{\left(e^{x} \sqrt{1-y^{2}}\right)-y}\right\}$
17. $\frac{-\left(x+y+x^{2} y\right)}{x^{2}\{y+(x+y) \log (x+y)\}}$
18. $\frac{\sec ^{2}(x+y)+\sec ^{2}(x-y)}{\sec ^{2}(x-y)-\sec ^{2}(x+y)}$
19. $\frac{x+y}{x-y}$

---

## Hints to Some Selected Questions (Exercise 10E)

8.  $x^{4}+y^{4}+2 x^{2} y^{2}=x y$
    $$
    \Rightarrow 4 x^{3}+4 y^{3} \cdot \frac{d y}{d x}+4 x^{2} y \cdot \frac{d y}{d x}+4 x y^{2}=x \frac{d y}{d x}+y
    $$
    $$
    \Rightarrow\left(4 y^{3}+4 x^{2} y-x\right) \frac{d y}{d x}=\left(y-4 x y^{2}-4 x^{3}\right)
    $$

9.  $x^{2}+y^{2}=\log x+\log y$
    $$
    \Rightarrow 2 x+2 y \frac{d y}{d x}=\frac{1}{x}+\frac{1}{y} \cdot \frac{d y}{d x}
    $$

10. $x^{n}+y^{n}=a^{n} \Rightarrow n x^{n-1}+n y^{n-1} \frac{d y}{d x}=0$.

11. $\cot (x y)+x y=y$
    $$
    \Rightarrow-\operatorname{cosec}^{2}(x y) \cdot\left\{x \frac{d y}{d x}+y\right\}+\left(x \frac{d y}{d x}+y\right)=\frac{d y}{d x}
    $$
    $$
    \Rightarrow\left\{\operatorname{cosec}^{2}(x y)-1\right\} \cdot x \frac{d y}{d x}+\frac{d y}{d x}=\left\{1-\operatorname{cosec}^{2}(x y)\right\} y
    $$
    $$
    \Rightarrow\left\{x \cot ^{2}(x y)+1\right\} \cdot \frac{d y}{d x}=-y \cot ^{2}(x y)
    $$

12. $y \log (x+y)=\frac{1}{x}$
    $$
    \Rightarrow y \cdot \frac{1}{(x+y)} \cdot\left(1+\frac{d y}{d x}\right)+\log (x+y) \cdot \frac{d y}{d x}=\frac{-1}{x^{2}}
    $$
    $$
    \Rightarrow\left\{\frac{y}{(x+y)}+\log (x+y)\right\} \cdot \frac{d y}{d x}=-\left(\frac{1}{x^{2}}+\frac{y}{x+y}\right)
    $$

13. $\log \sqrt{x^{2}+y^{2}}=\tan ^{-1} \frac{y}{x}$
    $$
    \Rightarrow \frac{1}{2} \log \left(x^{2}+y^{2}\right)=\tan ^{-1}\left(\frac{y}{x}\right)
    $$
    $$
    \Rightarrow \log \left(x^{2}+y^{2}\right)=2 \tan ^{-1} \frac{y}{x} \Rightarrow\left(x^{2}+y^{2}\right)=e^{2 \tan ^{-1} y / x}
    $$

    On differentiating (i) w.r.t. $x$, we get
    $$
    \begin{aligned}
    & 2 x+2 y \cdot \frac{d y}{d x}=e^{2 \tan ^{-1} y / x} \cdot \frac{2}{\left(1+\frac{y^{2}}{x^{2}}\right)} \cdot \frac{\left(x \frac{d y}{d x}-y\right)}{x^{2}} \\
    \Rightarrow & x+y \frac{d y}{d x}=\left(x^{2}+y^{2}\right) \cdot \frac{x^{2}}{\left(x^{2}+y^{2}\right)} \cdot \frac{\left(x \frac{d y}{d x}-y\right)}{x^{2}} \quad \text { [using (i)] } \\
    \Rightarrow & x+y \frac{d y}{d x}=x \frac{d y}{d x}-y \\
    \Rightarrow & (x-y) \frac{d y}{d x}=(x+y) \Rightarrow \frac{d y}{d x}=\frac{(x+y)}{(x-y)}
    \end{aligned}
    $$

14. $\frac{x^{2}-y^{2}}{x^{2}+y^{2}}=\cos \left\{\tan ^{-1} a\right\}=$ constant
    $$
    \Rightarrow \frac{d}{d x}\left(\frac{x^{2}-y^{2}}{x^{2}+y^{2}}\right)=0
    $$
    $$
    \Rightarrow \frac{\left(x^{2}+y^{2}\right) \cdot \frac{d}{d x}\left(x^{2}-y^{2}\right)-\left(x^{2}-y^{2}\right) \cdot \frac{d}{d x}\left(x^{2}+y^{2}\right)}{\left(x^{2}+y^{2}\right)^{2}}=0
    $$
    $$
    \Rightarrow\left(x^{2}+y^{2}\right)\left[2 x-2 y \frac{d y}{d x}\right]-\left(x^{2}-y^{2}\right)\left(2 x+2 y \frac{d y}{d x}\right)=0
    $$
    $$
    \Rightarrow x\left\{\left(x^{2}+y^{2}\right)-\left(x^{2}-y^{2}\right)\right\}=y\left\{\left(x^{2}-y^{2}\right)+\left(x^{2}+y^{2}\right)\right\} \frac{d y}{d x}
    $$
    Hence, $\frac{d y}{d x}=\frac{y}{x}$.