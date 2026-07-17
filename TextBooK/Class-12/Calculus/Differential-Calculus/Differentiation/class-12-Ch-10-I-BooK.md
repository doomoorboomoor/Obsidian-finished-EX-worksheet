## 9. Derivatives of Parametric Functions

Sometimes $x$ and $y$ are given as functions of a variable $t$. Then, $t$ is called a **parameter**.

**Let $x=f(t)$ and $y=g(t)$**. Then,

$$
\begin{aligned}
\frac{d x}{d t} & =f^{\prime}(t) \text { and } \frac{d y}{d t}=g^{\prime}(t) \\
\therefore \quad \frac{d y}{d x} & =\frac{(d y / d t)}{(d x / d t)}=\frac{g^{\prime}(t)}{f^{\prime}(t)}, \text { where } f^{\prime}(t) \neq 0
\end{aligned}
$$

---

## Summary

Let $x=f(t)$ and $y=g(t)$. Then,

$$
\frac{d y}{d x}=\frac{(d y / d t)}{(d x / d t)}=\frac{g^{\prime}(t)}{f^{\prime}(t)}, \text { where } f^{\prime}(t) \neq 0
$$

---

## Solved Examples

### Example 1:

**Find $\frac{d y}{d x}$**, when $x=a(t+\sin t)$ and $y=a(1-\cos t)$.

#### Solution:

We have:

$$
\begin{aligned}
x=a(t+\sin t) & \Rightarrow \frac{d x}{d t}=a(1+\cos t) \\
y=a(1-\cos t) & \Rightarrow \frac{d y}{d t}=a \sin t \\
\therefore \quad & \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{a \sin t}{a(1+\cos t)}=\frac{2 a \sin (t / 2) \cos (t / 2)}{2 a \cos ^{2}(t / 2)}=\tan \frac{t}{2}
\end{aligned}
$$

---

### Example 2:

If $x=a[\cos \theta+\log \tan (\theta / 2)]$ and $y=a \sin \theta$, **find $\frac{d y}{d x}$ at $\theta=(\pi / 4)$**.
[CBSE 2008]

#### Solution:

We have

$$
\begin{aligned}
x & =a\{\cos \theta+\log \tan (\theta / 2)\} \\
\Rightarrow \frac{d x}{d \theta} & =a\left\{-\sin \theta+\frac{\sec ^{2}(\theta / 2)}{2 \tan (\theta / 2)}\right\}=a\left\{-\sin \theta+\frac{1}{2 \sin (\theta / 2) \cos (\theta / 2)}\right\} \\
& =a\left\{-\sin \theta+\frac{1}{\sin \theta}\right\}=\frac{a\left(1-\sin ^{2} \theta\right)}{\sin \theta}=\frac{a \cos ^{2} \theta}{\sin \theta}
\end{aligned}
$$

And, $y=a \sin \theta \Rightarrow \frac{d y}{d \theta}=a \cos \theta$.

$\therefore \quad \frac{d y}{d x}=\left(\frac{d y}{d \theta} \times \frac{d \theta}{d x}\right)=\left(a \cos \theta \cdot \frac{\sin \theta}{a \cos ^{2} \theta}\right)=\tan \theta$.

$\therefore\left[\frac{d y}{d x}\right]_{\theta=\pi / 4}=\tan \frac{\pi}{4}=1$.

---

### Example 3:

If $x=a \sin 2 t(1+\cos 2 t)$ and $y=b \cos 2 t(1-\cos 2 t)$, **show that**

$$
\left(\frac{d y}{d x}\right)_{a t t=\frac{\pi}{4}}=\frac{b}{a}
$$

[CBSE 2006]

#### Solution:

We have

$$
\begin{aligned}
x & =a \sin 2 t(1+\cos 2 t) \\
\Rightarrow \frac{d x}{d t} & =a \cdot[\sin 2 t(-2 \sin 2 t)+(1+\cos 2 t)(2 \cos 2 t)] \\
& =(2 a) \cdot\left[-\sin ^{2} 2 t+\cos 2 t+\cos ^{2} 2 t\right] \\
& =(2 a)[\cos 4 t+\cos 2 t] \quad\left\{\because \quad\left(\cos ^{2} 2 t-\sin ^{2} 2 t\right)=\cos 4 t\right\}
\end{aligned}
$$

And, $y=b \cos 2 t(1-\cos 2 t)$

$$
\begin{aligned}
& \Rightarrow \frac{d y}{d t}=b[\cos 2 t(2 \sin 2 t)+(1-\cos 2 t)(-2 \sin 2 t)] \\
& \quad=(2 b)[\sin 2 t \cos 2 t-\sin 2 t+\sin 2 t \cos 2 t] \\
& \quad=(2 b)[2 \sin 2 t \cos 2 t-\sin 2 t]=(2 b)[\sin 4 t-\sin 2 t]
\end{aligned}
$$

$\therefore \frac{d y}{d x} =\frac{(d y / d t)}{(d x / d t)}=\frac{(2 b)(\sin 4 t-\sin 2 t)}{(2 a)(\cos 4 t+\cos 2 t)}$

$$
\begin{aligned}
\Rightarrow\left(\frac{d y}{d x}\right)_{\left(t=\frac{\pi}{4}\right)} & =\frac{b}{a} \cdot \frac{\left\{\sin \left(4 \times \frac{\pi}{4}\right)-\sin \left(2 \times \frac{\pi}{4}\right)\right\}}{\left\{\cos \left(4 \times \frac{\pi}{4}\right)+\cos \left(2 \times \frac{\pi}{4}\right)\right\}} \\
& \quad=\frac{b}{a} \cdot \frac{\left(\sin \pi-\sin \frac{\pi}{2}\right)}{\left(\cos \pi+\cos \frac{\pi}{2}\right)}=\frac{b}{a} \cdot \frac{(0-1)}{(-1+0)}=\frac{b}{a}
\end{aligned}
$$

---

### Example 4:

If $x=a\left(\frac{1+t^{2}}{1-t^{2}}\right)$ and $y=\frac{2 t}{\left(1-t^{2}\right)}$, **find $\frac{d y}{d x}$**.
[CBSE 2005]

#### Solution:

We have

$$
\begin{aligned}
x & =a\left[-1+\frac{2}{\left(1-t^{2}\right)}\right]=a\left[-1+2\left(1-t^{2}\right)^{-1}\right] \\
\Rightarrow \frac{d x}{d t} & =a\left[0+2(-1)\left(1-t^{2}\right)^{-2}(-2 t)\right]=a \times \frac{4 t}{\left(1-t^{2}\right)^{2}}=\frac{4 a t}{\left(1-t^{2}\right)^{2}}
\end{aligned}
$$

And, $y=\frac{2 t}{\left(1-t^{2}\right)}$

$$
\Rightarrow \frac{d y}{d t}=\frac{\left(1-t^{2}\right) \cdot 2-2 t(-2 t)}{\left(1-t^{2}\right)^{2}}=\frac{2\left(1+t^{2}\right)}{\left(1-t^{2}\right)^{2}}.
$$

$\therefore \quad \frac{d y}{d x}=\frac{(d y / d t)}{(d x / d t)}=\left\{\frac{2\left(1+t^{2}\right)}{\left(1-t^{2}\right)^{2}} \times \frac{\left(1-t^{2}\right)^{2}}{4 a t}\right\}=\frac{\left(1+t^{2}\right)}{2 a t}$.

---

### Example 5:

If $x=3 \sin t-\sin 3 t, y=3 \cos t-\cos 3 t$, **find $\frac{d^{2} y}{d x^{2}}$ at $t=\frac{\pi}{3}$**.
[CBSE 2005C]

#### Solution:

We have

$$
\begin{align*}
x & =3 \sin t-\sin 3 t \\
\Rightarrow \frac{d x}{d t} & =3 \cos t-3 \cos 3 t \tag{i}
\end{align*}
$$

And, $y=3 \cos t-\cos 3 t$
$\Rightarrow \frac{d y}{d t}=-3 \sin t+3 \sin 3 t$.

$$
\begin{equation*}
\therefore \frac{d y}{d x}=\frac{(d y / d t)}{(d x / d t)}=\frac{-3 \sin t+3 \sin 3 t}{3 \cos t-3 \cos 3 t}=\frac{\sin 3 t-\sin t}{\cos t-\cos 3 t} \tag{ii}
\end{equation*}
$$

$$
=\frac{2 \cos 2 t \sin t}{2 \sin 2 t \sin t}=\cot 2 t .
$$

$\therefore \frac{d^{2} y}{d x^{2}}=-2 \operatorname{cosec}^{2} 2 t \cdot \frac{d t}{d x}=\frac{-2 \operatorname{cosec}^{2} 2 t}{(d x / d t)}=\frac{-2 \operatorname{cosec}^{2} 2 t}{3(\cos t-\cos 3 t)}$.

$\therefore\left(\frac{d^{2} y}{d x^{2}}\right)_{\left(t=\frac{\pi}{3}\right)}=\frac{-2 \operatorname{cosec}^{2}(2 \pi / 3)}{3 \cos \frac{\pi}{3}-\cos \pi}=-2 \times\left(\frac{2}{\sqrt{3}}\right)^{2} \cdot \frac{1}{3\left(\frac{1}{2}+1\right)}$

$$
=\left(-2 \times \frac{4}{3} \times \frac{2}{9}\right)=\frac{-16}{27} .
$$

---

### Example 6:

If $x=\sqrt{a^{\sin ^{-1} t}}$ and $y=\sqrt{a^{\cos ^{-1} t}}$, **show that $\frac{d y}{d x}=\frac{-y}{x}$**.

#### Solution:

We have

$$
\begin{aligned}
& x^{2}=a^{\sin ^{-1} t} \text { and } y^{2}=a^{\cos ^{-1} t} \\
\Rightarrow & 2 x \frac{d x}{d t}=a^{\sin ^{-1} t} \cdot \frac{1}{\sqrt{1-t^{2}}} \text { and } 2 y \frac{d y}{d t}=a^{\cos ^{-1} t} \cdot \frac{(-1)}{\sqrt{1-t^{2}}} \\
\Rightarrow & \frac{2 y}{2 x} \cdot \frac{(d y / d t)}{(d x / d t)}=\frac{-a^{\cos ^{-1} t}}{\sqrt{1-t^{2}}} \times \frac{\sqrt{1-t^{2}}}{a^{\sin ^{-1} t}} \\
\Rightarrow & \frac{y}{x} \cdot \frac{d y}{d x}=-\frac{a^{\cos ^{-1} t}}{a^{\sin ^{-1} t}}=-\frac{y^{2}}{x^{2}} \\
\Rightarrow & \frac{d y}{d x}=\frac{-y}{x} \quad \text { [on dividing both sides by } \frac{y}{x} \text { ]. }
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{-y}{x}$.

---

### Example 7:

If $a>0, x=\left(t+\frac{1}{t}\right)^{a}$ and $y=a^{\left(t+\frac{1}{t}\right)}$, **find $\frac{d y}{d x}$**.

#### Solution:

We have

$x=\left(t+\frac{1}{t}\right)^{a} \Rightarrow \frac{d x}{d t}=a\left(t+\frac{1}{t}\right)^{(a-1)} \cdot \frac{d}{d t}\left(t+\frac{1}{t}\right)=a\left(t+\frac{1}{t}\right)^{(a-1)} \cdot\left(1-\frac{1}{t^{2}}\right).$

$$
\begin{aligned}
& \text { And, } y=a^{\left(t+\frac{1}{t}\right)} \Rightarrow \frac{d y}{d t}=a^{\left(t+\frac{1}{t}\right)} \log a \cdot \frac{d}{d t}\left(t+\frac{1}{t}\right) \\
& =a^{\left(t+\frac{1}{t}\right)} \log a \cdot\left(1-\frac{1}{t^{2}}\right) .
\end{aligned}
$$

$\therefore \quad \frac{d y}{d x}=\frac{(d y / d t)}{(d x / d t)}=\frac{a^{\left(t+\frac{1}{t}\right)} \log a \cdot\left(1-\frac{1}{t^{2}}\right)}{a\left(t+\frac{1}{t}\right)^{(a-1)}\left(1-\frac{1}{t^{2}}\right)}=\frac{a^{\left(t+\frac{1}{t}-1\right)} \cdot \log a}{\left(t+\frac{1}{t}\right)^{(a-1)}} .$

---

