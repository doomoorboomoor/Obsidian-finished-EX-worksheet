## 10. Second-Order Derivatives

Let $y=f(x)$ be a differentiable function of $x$ whose second-order derivative exists. We denote the second-order derivative of $y$ w.r.t. $x$ by $\frac{d^{2} y}{d x^{2}}$ or $y_{2}$.

## SOLVED EXAMPLES

### Example 1:

Find the second-order derivative of:
(i) $x^{10}$
(ii) $\log x$
(iii) $\tan ^{-1} x$

#### Solution:

(i) Let $y=x^{10}$. Then,

$$
\begin{aligned}
& \quad \frac{d y}{d x}=10 x^{9} . \\
& \therefore \quad \frac{d^{2} y}{d x^{2}}=(10 \times 9) x^{8}=90 x^{8} . \\
& \text { Hence, } \frac{d^{2} y}{d x^{2}}\left(x^{10}\right)=90 x^{8} .
\end{aligned}
$$

(ii) Let $y=\log x$. Then,

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{1}{x}=x^{-1} . \\
\therefore \quad \frac{d^{2} y}{d x^{2}} & =\frac{d}{d x}\left(x^{-1}\right)=(-1) x^{(-1-1)}=-x^{-2}=\frac{-1}{x^{2}} .
\end{aligned}
$$

Hence, $\frac{d^{2}}{d x^{2}}(\log x)=\frac{-1}{x^{2}}$.

(iii) Let $y=\tan ^{-1} x$. Then,

$$
\begin{aligned}
& \qquad \frac{d y}{d x}=\frac{1}{\left(1+x^{2}\right)}=\left(1+x^{2}\right)^{-1} . \\
& \therefore \quad \frac{d^{2} y}{d x^{2}}=\frac{d}{d x}\left(1+x^{2}\right)^{-1}=(-1)\left(1+x^{2}\right)^{-2} \cdot(2 x)=\frac{-2 x}{\left(1+x^{2}\right)^{2}} . \\
& \text { Hence, } \frac{d^{2}}{d x^{2}}\left\{\tan ^{-1} x\right\}=\frac{-2 x}{\left(1+x^{2}\right)^{2}} .
\end{aligned}
$$

---

### Example 2:

If $y=(\tan x+\sec x)$, prove that $\frac{d^{2} y}{d x^{2}}=\frac{\cos x}{(1-\sin x)^{2}}$.

#### Solution:

Given that $y=(\tan x+\sec x)$.

$$
\begin{aligned}
& \begin{array}{l}
\therefore \quad \frac{d y}{d x}=\sec ^{2} x+\sec x \tan x=\left(\frac{1}{\cos ^{2} x}+\frac{1}{\cos x} \cdot \frac{\sin x}{\cos x}\right) \\
\quad=\left(\frac{1+\sin x}{\cos ^{2} x}\right)=\left(\frac{1+\sin x}{1-\sin ^{2} x}\right)=\frac{1}{(1-\sin x)} .
\end{array} \\
& \begin{aligned}
\therefore \quad \frac{d^{2} y}{d x^{2}} & =\frac{d}{d x}\left\{\frac{1}{(1-\sin x)}\right\}=\frac{d}{d x}(1-\sin x)^{-1} \\
& =(-1)(1-\sin x)^{-2}(-\cos x)=\frac{\cos x}{(1-\sin x)^{2}} .
\end{aligned} \\
& \text { Hence, } \frac{d^{2} y}{d x^{2}}=\frac{\cos x}{(1-\sin x)^{2}} .
\end{aligned}
$$

---

### Example 3:

If $y=e^{4 x} \sin 3 x$, find $\frac{d^{2} y}{d x^{2}}$.

#### Solution:

Let $y=e^{4 x} \sin 3 x$. Then,

$$
\begin{aligned}
\frac{d y}{d x} & =3 e^{4 x} \cos 3 x+4 e^{4 x} \sin 3 x=e^{4 x}(3 \cos 3 x+4 \sin 3 x) \\
\therefore \frac{d^{2} y}{d x^{2}} & =\frac{d}{d x}\left(\frac{d y}{d x}\right)=\frac{d}{d x}\left\{e^{4 x}(3 \cos 3 x+4 \sin 3 x)\right\} \\
& =e^{4 x}(-9 \sin 3 x+12 \cos 3 x)+4 e^{4 x}(3 \cos 3 x+4 \sin 3 x) \\
& =e^{4 x}(7 \sin 3 x+24 \cos 3 x)
\end{aligned}
$$

---

### Example 4:

If $y=\left(x^{4}+\cot x\right)$, find $\frac{d^{2} y}{d x^{2}}$.

#### Solution:

We have

$$
\begin{aligned}
y= & \left(x^{4}+\cot x\right) \\
\Rightarrow \frac{d y}{d x}= & 4 x^{3}-\operatorname{cosec}^{2} x \\
\Rightarrow \frac{d^{2} y}{d x^{2}} & =\frac{d}{d x}\left(4 x^{3}-\operatorname{cosec}^{2} x\right) \\
& =4 \cdot \frac{d}{d x}\left(x^{3}\right)-\frac{d}{d x}\left(\operatorname{cosec}^{2} x\right) \\
& =\left(4 \times 3 x^{2}\right)-2 \operatorname{cosec} x(-\operatorname{cosec} x \cot x) \\
& =\left(12 x^{2}+2 \operatorname{cosec}^{2} x \cot x\right)
\end{aligned}
$$

---

### Example 5:

Find the second derivative of $\log (\log x)$ w.r.t. $x$.

#### Solution:

Let $y=\log (\log x)$. Then,

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{1}{(\log x)} \cdot \frac{1}{x}=\frac{1}{(x \log x)}=(x \log x)^{-1} \\
\Rightarrow \frac{d^{2} y}{d x^{2}} & =\frac{d}{d x}(x \log x)^{-1} \\
& =(-1)(x \log x)^{-2} \cdot \frac{d}{d x}(x \log x) \\
& =\frac{-1}{(x \log x)^{2}} \cdot\left(x \cdot \frac{1}{x}+\log x \cdot 1\right)=\frac{-(1+\log x)}{(x \log x)^{2}}
\end{aligned}
$$

---

### Example 6:

If $y=\sin (\log x)$, find $\frac{d^{2} y}{d x^{2}}$.

#### Solution:

We have

$$
\begin{aligned}
y & =\sin (\log x) \\
\Rightarrow \frac{d y}{d x} & =\frac{d}{d x}\{\sin (\log x)\}=\cos (\log x) \cdot \frac{1}{x}=\frac{\cos (\log x)}{x}
\end{aligned}
$$

$$
\begin{aligned}
\Rightarrow \frac{d^{2} y}{d x^{2}} & =\frac{d}{d x}\left\{\frac{\cos (\log x)}{x}\right\} \\
& =\frac{x \cdot \frac{d}{d x}\{\cos (\log x)\}-\cos (\log x) \cdot \frac{d}{d x}(x)}{x^{2}} \\
& =\frac{x\left\{-\sin (\log x) \cdot \frac{1}{x}\right\}-\cos (\log x) \cdot 1}{x^{2}} \\
& =\frac{-\{\sin (\log x)+\cos (\log x)\}}{x^{2}}
\end{aligned}
$$

---

### Example 7:

If $e^{y}(x+1)=1$, prove that $\frac{d^{2} y}{d x^{2}}=\left(\frac{d y}{d x}\right)^{2}$.

#### Solution:

We have

$$
\begin{align*}
& e^{y}(x+1)=1 \Rightarrow e^{y}=\frac{1}{(x+1)}  \tag{i}\\
\Rightarrow & y=\log \left\{\frac{1}{(x+1)}\right\}=\log 1-\log (x+1) \\
\Rightarrow & y=-\log (x+1)  \tag{ii}\\
\therefore & \frac{d y}{d x}=\frac{-1}{(x+1)} \\
\Rightarrow & \frac{d^{2} y}{d x^{2}}=\frac{1}{(x+1)^{2}}=\left(\frac{d y}{d x}\right)^{2}
\end{align*}
$$

Hence, $\frac{d^{2} y}{d x^{2}}=\left(\frac{d y}{d x}\right)^{2}$.

---

### Example 8:

If $y=A \cos n x+B \sin n x$, prove that $\frac{d^{2} y}{d x^{2}}+n^{2} y=0$.

#### Solution:

We have

$$
\begin{aligned}
y & =A \cos n x+B \sin n x \\
\Rightarrow \frac{d y}{d x} & =\frac{d}{d x}(A \cos n x)+\frac{d}{d x}(B \sin n x) \\
& =-A n \sin n x+B n \cos n x \\
& =n(B \cos n x-A \sin n x) \\
\Rightarrow \frac{d^{2} y}{d x^{2}} & =n \cdot \frac{d}{d x}(B \cos n x-A \sin n x) \\
& =n \cdot\left\{B \cdot \frac{d}{d x}(\cos n x)-A \cdot \frac{d}{d x}(\sin n x)\right\} \\
& =n \cdot\{-B n \sin n x-A n \cos n x\} \\
& =-n^{2}(A \cos n x+B \sin n x)=-n^{2} y \\
\Rightarrow \frac{d^{2} y}{d x^{2}} & +n^{2} y=0
\end{aligned}
$$

---

### Example 9:

If $y=e^{x}(\sin x+\cos x)$, prove that $\frac{d^{2} y}{d x^{2}}-2 \frac{d y}{d x}+2 y=0$. [CBSE 2002, '09]

#### Solution:

We have

$$
\begin{aligned}
& \Rightarrow \frac{d y}{d x}=e^{x}(\sin x+\cos x) \\
& \quad=e^{x}(\cos x-\sin x)+(\sin x+\cos x) \cdot e^{x}=2 e^{x} \cos x \\
& \Rightarrow \frac{d^{2} y}{d x^{2}}=2 \cdot \frac{d}{d x}\left(e^{x} \cos x\right) \\
& \quad=2 \cdot\left\{e^{x} \cdot \frac{d}{d x}(\cos x)+\cos x \cdot \frac{d}{d x}\left(e^{x}\right)\right\} \\
& \quad=2 \cdot\left\{e^{x}(-\sin x)+(\cos x) e^{x}\right\}=2 e^{x}(\cos x-\sin x) \\
& \therefore \quad\left(\frac{d^{2} y}{d x^{2}}-2 \frac{d y}{d x}+2 y\right) \\
& \quad=2 e^{x}(\cos x-\sin x)-4 e^{x} \cos x+2 e^{x}(\sin x+\cos x)=0
\end{aligned}
$$

Hence, $\frac{d^{2} y}{d x^{2}}-2 \frac{d y}{d x}+2 y=0$.

---

### Example 10:

If $y=3 e^{2 x}+2 e^{3 x}$, prove that $\frac{d^{2} y}{d x^{2}}-5 \frac{d y}{d x}+6 y=0$.

#### Solution:

We have

$$
\begin{align*}
y & =3 e^{2 x}+2 e^{3 x}  \tag{i}\\
\Rightarrow \frac{d y}{d x} & \left.=3 \cdot \frac{d}{d x}\left(e^{2 x}\right)+2 \cdot \frac{d}{d x}\left(e^{3 x}\right) \text { [on differentiating (i) w.r.t. } x\right] \\
& =\left(3 \times 2 e^{2 x}\right)+\left(2 \times 3 e^{3 x}\right)=\left(6 e^{2 x}+6 e^{3 x}\right) \\
\Rightarrow \frac{d y}{d x} & =6\left(e^{2 x}+e^{3 x}\right) \tag{ii}
\end{align*}
$$

On differentiating (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{d^{2} y}{d x^{2}}=6 \cdot\left\{\frac{d}{d x}\left(e^{2 x}\right)+\frac{d}{d x}\left(e^{3 x}\right)\right\} \\
&=6 \cdot\left(2 e^{2 x}+3 e^{3 x}\right) \\
& \therefore\left(\frac{d^{2} y}{d x^{2}}-5 \frac{d y}{d x}+6 y\right) \\
&=6\left(2 e^{2 x}+3 e^{3 x}\right)-30\left(e^{2 x}+e^{3 x}\right)+\left(18 e^{2 x}+12 e^{3 x}\right) \\
&=(12-30+18) e^{2 x}+(18-30+12) e^{3 x}=0
\end{aligned}
$$

Hence, $\left(\frac{d^{2} y}{d x^{2}}-5 \frac{d y}{d x}+6 y\right)=0$.

---

### Example 11:

If $y=\sin ^{-1} x$, prove that $\left(1-x^{2}\right) \frac{d^{2} y}{d x^{2}}-x \frac{d y}{d x}=0$. [CBSE 2012]

#### Solution:

Given: $y=\sin ^{-1} x$.

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{align*}
& y_{1}=\frac{1}{\sqrt{1-x^{2}}} \\
\Rightarrow & y_{1}^{2}=\frac{1}{\left(1-x^{2}\right)} \\
\Rightarrow & \left(1-x^{2}\right) y_{1}^{2}=1 \tag{ii}
\end{align*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \left(1-x^{2}\right) \cdot 2 y_{1} y_{2}+y_{1}^{2}(-2 x)=0 \\
\Rightarrow & \left(1-x^{2}\right) y_{2}-x y_{1}=0
\end{aligned}
$$

Hence, $\left(1-x^{2}\right) \frac{d^{2} y}{d x^{2}}-x \frac{d y}{d x}=0$.

---

### Example 12:

If $y=\left(\tan ^{-1} x\right)^{2}$, prove that $\left(1+x^{2}\right)^{2} y_{2}+2 x\left(1+x^{2}\right) y_{1}=2$. [CBSE 2012]

#### Solution:

Given: $y=\left(\tan ^{-1} x\right)^{2}$.

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{align*}
& y_{1}=2 \tan ^{-1} x \cdot \frac{1}{\left(1+x^{2}\right)} \\
\Rightarrow & \left(1+x^{2}\right) y_{1}=2 \tan ^{-1} x \\
\Rightarrow & \left(1+x^{2}\right)^{2} y_{1}^{2}=4\left(\tan ^{-1} x\right)^{2} \quad \text { [on squaring both sides] } \\
\Rightarrow & \left(1+x^{2}\right)^{2} y_{1}^{2}-4 y=0 \tag{ii}
\end{align*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \quad\left(1+x^{2}\right)^{2} \cdot 2 y_{1} y_{2}+y_{1}^{2} \cdot 2\left(1+x^{2}\right) \cdot 2 x-4 y_{1}=0 \\
& \Rightarrow\left(1+x^{2}\right)^{2} y_{2}+2 x\left(1+x^{2}\right) y_{1}-2=0 \\
& \text { Hence, }\left(1+x^{2}\right)^{2} y_{2}+2 x\left(1+x^{2}\right) y_{1}=2
\end{aligned}
$$

---

### Example 13:

If $x=a(\theta+\sin \theta)$ and $y=a(1-\cos \theta)$, find $\frac{d^{2} y}{d x^{2}}$ at $\theta=\frac{\pi}{2}$. [CBSE 2005, '09]

#### Solution:

We have

$$
\begin{aligned}
x & =a(\theta+\sin \theta) \text { and } y=a(1-\cos \theta) \\
\Rightarrow \frac{d x}{d \theta} & =a(1+\cos \theta) \text { and } \frac{d y}{d \theta}=a \sin \theta \\
\Rightarrow \frac{d y}{d x} & =\frac{(d y / d \theta)}{(d x / d \theta)} \\
& =\frac{a \sin \theta}{a(1+\cos \theta)}=\frac{\sin \theta}{(1+\cos \theta)}=\frac{2 \sin (\theta / 2) \cos (\theta / 2)}{2 \cos ^{2}(\theta / 2)}=\tan \frac{\theta}{2}
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow \frac{d^{2} y}{d x^{2}}=\frac{d}{d x}\left(\tan \frac{\theta}{2}\right)=\frac{1}{2} \sec ^{2} \frac{\theta}{2} \cdot \frac{d \theta}{d x}=\left(\frac{1}{2} \sec ^{2} \frac{\theta}{2}\right) \times \frac{1}{a(1+\cos \theta)} \\
& \Rightarrow\left(\frac{d^{2} y}{d x^{2}}\right)_{\theta=\frac{\pi}{2}}=\frac{1}{2} \sec ^{2} \frac{\pi}{4} \cdot \frac{1}{a\left(1+\cos \frac{\pi}{2}\right)}=\frac{1}{a}
\end{aligned}
$$

---

### Example 14:

If $x=(2 \cos \theta-\cos 2 \theta)$ and $y=(2 \sin \theta-\sin 2 \theta)$, find $\frac{d^{2} y}{d x^{2}}$ at $\theta=\frac{\pi}{2}$. [CBSE 2005C]

#### Solution:

We have

$$
\begin{gathered}
\quad x=(2 \cos \theta-\cos 2 \theta) \text { and } y=(2 \sin \theta-\sin 2 \theta) \\
\Rightarrow \frac{d x}{d \theta}=(-2 \sin \theta+2 \sin 2 \theta) \text { and } \frac{d y}{d \theta}=(2 \cos \theta-2 \cos 2 \theta) \\
\Rightarrow \frac{d y}{d x}=\frac{(d y / d \theta)}{(d x / d \theta)}=\frac{(2 \cos \theta-2 \cos 2 \theta)}{(-2 \sin \theta+2 \sin 2 \theta)}=\frac{(\cos \theta-\cos 2 \theta)}{(\sin 2 \theta-\sin \theta)} \\
\quad=\frac{2 \sin \left(\frac{3 \theta}{2}\right) \sin \frac{\theta}{2}}{2 \cos \left(\frac{3 \theta}{2}\right) \sin \frac{\theta}{2}}=\tan \frac{3 \theta}{2} \\
\Rightarrow \frac{d^{2} y}{d x^{2}}=\frac{d}{d x}\left(\tan \frac{3 \theta}{2}\right)=\frac{3}{2} \sec ^{2} \frac{3 \theta}{2} \cdot \frac{d \theta}{d x}=\frac{3}{2} \sec ^{2} \frac{3 \theta}{2} \cdot \frac{1}{2(\sin 2 \theta-\sin \theta)} \\
\Rightarrow\left(\frac{d^{2} y}{d x^{2}}\right)_{\theta=\frac{\pi}{2}}=\frac{3}{2} \cdot \sec ^{2}\left(\frac{3 \pi}{4}\right) \cdot \frac{1}{\left(2 \sin \pi-\sin \frac{\pi}{2}\right)} \\
\quad=\frac{-3}{4} \sec ^{2} \frac{\pi}{4}=\frac{-3}{4} \times(\sqrt{2})^{2}=\frac{-3}{2} \\
{\left[\because \sec \frac{3 \pi}{4}=\sec \left(\pi-\frac{\pi}{4}\right)=-\sec \frac{\pi}{4}\right]}
\end{gathered}
$$

---