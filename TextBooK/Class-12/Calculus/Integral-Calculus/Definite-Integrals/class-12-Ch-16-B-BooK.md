## To Evaluate a Definite Integral by Substitution

In $\int_{a}^{b} f(x) d x$, when the variable $x$ is converted into a new variable $t$ by some relation then we put $x=a$ and $x=b$ in that relation to obtain the corresponding values of $t$, giving the **lower limit** and the **upper limit** respectively of the new integrand in $t$.

---

## Solved Examples

### Example 1

Evaluate:

1.  $\int_{0}^{2} e^{x / 2} d x$
2.  $\int_{2}^{4} \frac{x}{\left(x^{2}+1\right)} d x$
3.  $\int_{0}^{1} \cos ^{-1} x d x$
4.  $\int_{0}^{1} \frac{(2 x+3)}{\left(5 x^{2}+1\right)} d x$

#### Solution

**(i)** Put $\frac{x}{2}=t$ so that $d x=2 d t$.
Also, $(x=0 \Rightarrow t=0)$ and $(x=2 \Rightarrow t=1)$.

$$
\therefore \quad \int_{0}^{2} e^{x / 2} d x=2 \int_{0}^{1} e^{t} d t=2\left[e^{t}\right]_{0}^{1}=2(e-1)
$$

**(ii)** Put $\left(x^{2}+1\right)=t$ so that $x d x=\frac{1}{2} d t$.
Also, $(x=2 \Rightarrow t=5)$ and $(x=4 \Rightarrow t=17)$.

$$
\therefore \int_{2}^{4} \frac{x}{\left(x^{2}+1\right)} d x=\frac{1}{2} \int_{5}^{17} \frac{d t}{t}=\frac{1}{2}[\log |t|]_{5}^{17}=\frac{1}{2}(\log 17-\log 5)
$$

**(iii)** Put $x=\cos t$ so that $d x=-\sin t d t$.
Also, $\left(x=0 \Rightarrow t=\frac{\pi}{2}\right)$ and $(x=1 \Rightarrow t=0)$.

$$
\begin{aligned}
\therefore \int_{0}^{1} \cos ^{-1} x d x & =-\int_{\pi / 2}^{0} \cos ^{-1}(\cos t) \sin t d t=\int_{0}^{\pi / 2} t \sin t d t \\
& =[t(-\cos t)]_{0}^{\pi / 2}-\int_{0}^{\pi / 2} 1 \cdot(-\cos t) d t \quad \text{[integrating by parts]} \\
& =[\sin t]_{0}^{\pi / 2}=1 .
\end{aligned}
$$

**(iv)** Let $(2 x+3) \equiv A \cdot \frac{d}{d x}\left(5 x^{2}+1\right)+B$.
Then, $(2 x+3) \equiv(10 x) A+B$.
Comparing the coefficients of like powers of $x$, we get

$$
\begin{aligned}
10 A & =2 \text { or } A=\frac{1}{5} \text { and } B=3 . \\
\therefore \quad(2 x+3) & =\frac{1}{5}(10 x)+3 .
\end{aligned}
$$

So, $\int_{0}^{1} \frac{(2 x+3)}{\left(5 x^{2}+1\right)} d x=\int_{0}^{1} \frac{\frac{1}{5}(10 x)+3}{\left(5 x^{2}+1\right)} d x$

$$
\begin{aligned}
& =\frac{1}{5} \int_{0}^{1} \frac{10 x}{\left(5 x^{2}+1\right)} d x+3 \int_{0}^{1} \frac{d x}{\left(5 x^{2}+1\right)} \\
& =\frac{1}{5}\left[\log \left|5 x^{2}+1\right|\right]_{0}^{1}+\frac{3}{5} \int_{0}^{1} \frac{d x}{x^{2}+\left(\frac{1}{\sqrt{5}}\right)^{2}} \\
& =\frac{1}{5} \log 6+\frac{3}{5} \cdot \sqrt{5}\left[\tan ^{-1} \frac{x}{(1 / \sqrt{5})}\right]_{0}^{1} \\
& =\frac{1}{5} \log 6+\frac{3}{\sqrt{5}}\left(\tan ^{-1} \sqrt{5}\right)
\end{aligned}
$$

---

### Example 2

Evaluate:

1.  $\int_{1}^{3} \frac{\cos (\log x)}{x} d x$
2.  $\int_{0}^{\pi / 2} \sqrt{\cos \theta} \sin ^{3} \theta d \theta$
3.  $\int_{0}^{\pi / 2} \frac{\cos x}{(1+\sin x)(2+\sin x)} d x$ \[CBSE 2004]
4.  $\int_{0}^{\pi / 2} \frac{d x}{(1-2 \sin x)}$
5.  $\int_{0}^{\pi / 2} \frac{d x}{(3+2 \cos x)}$
6.  $\int_{0}^{\pi / 2} \frac{d x}{\left(4 \sin ^{2} x+5 \cos ^{2} x\right)}$

#### Solution

**(i)** Put $\log x=t$ so that $\frac{1}{x} d x=d t$.
Also, $(x=1 \Rightarrow t=\log 1=0)$ and $(x=3 \Rightarrow t=\log 3)$.

$$
\therefore \quad \int_{1}^{3} \frac{\cos (\log x)}{x} d x=\int_{0}^{\log 3} \cos t d t=[\sin t]_{0}^{\log 3}=\sin (\log 3)
$$

**(ii)** Put $\cos \theta=t$ so that $\sin \theta d \theta=-d t$.
Also, $(\theta=0 \Rightarrow t=1)$ and $\left(\theta=\frac{\pi}{2} \Rightarrow t=0\right)$.

$$
\begin{aligned}
\therefore \quad \int_{0}^{\pi / 2} \sqrt{\cos \theta} \sin ^{3} \theta d \theta & =\int_{0}^{\pi / 2} \sqrt{\cos \theta} \cdot\left(1-\cos ^{2} \theta\right) \sin \theta d \theta \\
& =-\int_{1}^{0} \sqrt{t}\left(1-t^{2}\right) d t=\int_{0}^{1}\left(t^{1 / 2}-t^{5 / 2}\right) d t \\
& =\left[\frac{2}{3} t^{3 / 2}-\frac{2}{7} t^{7 / 2}\right]_{0}^{1}=\left(\frac{2}{3}-\frac{2}{7}\right)=\frac{8}{21}
\end{aligned}
$$

**(iii)** Put $\sin x=t$ so that $\cos x d x=d t$.
Also, $(x=0 \Rightarrow t=0)$ and $\left(x=\frac{\pi}{2} \Rightarrow t=1\right)$.

$$
\begin{aligned}
\therefore \quad \int_{0}^{\pi / 2} & \frac{\cos x}{(1+\sin x)(2+\sin x)} d x \\
& =\int_{0}^{1} \frac{d t}{(1+t)(2+t)} \\
& =\int_{0}^{1}\left[\frac{1}{(1+t)}-\frac{1}{(2+t)}\right] d t \quad \text{[by partial fractions]} \\
& =\int_{0}^{1} \frac{d t}{(1+t)}-\int_{0}^{1} \frac{d t}{(2+t)} \\
& =[\log |1+t|]_{0}^{1}-[\log |2+t|]_{0}^{1} \\
& =[(\log 2-\log 1)-(\log 3-\log 2)]=(2 \log 2)-(\log 3)
\end{aligned}
$$

**(iv)** $\int_{0}^{\pi / 2} \frac{d x}{(1-2 \sin x)}=\int_{0}^{\pi / 2} \frac{d x}{1-2\left\{\frac{2 \tan (x / 2)}{1+\tan ^{2}(x / 2)}\right\}}$

$$
\begin{aligned}
& =\int_{0}^{\pi / 2} \frac{\sec ^{2}(x / 2)}{\left[1+\tan ^{2}(x / 2)-4 \tan (x / 2)\right]} d x \\
& =2 \int_{0}^{1} \frac{d t}{\left(1+t^{2}-4 t\right)}, \text { where } \tan \frac{x}{2}=t \\
& \quad\left[\begin{array}{l}
x=0 \Rightarrow t=0 \\
x=\frac{\pi}{2} \Rightarrow t=1
\end{array}\right] \\
& =2 \int_{0}^{1} \frac{d t}{(t-2)^{2}-(\sqrt{3})^{2}}=2 \cdot \frac{1}{2 \sqrt{3}}\left[\log \left|\frac{t-2-\sqrt{3}}{t-2+\sqrt{3}}\right|\right]_{0}^{1}
\end{aligned}
$$

$$
=\frac{1}{\sqrt{3}}\left[\log \left(\frac{\sqrt{3}+1}{\sqrt{3}-1}\right)-\log \frac{\sqrt{3}+2}{\sqrt{3}-2}\right]
$$

**(v)** $\int_{0}^{\pi / 2} \frac{d x}{(3+2 \cos x)}=\int_{0}^{\pi / 2} \frac{d x}{3+2 \cdot\left[\frac{1-\tan ^{2}(x / 2)}{1+\tan ^{2}(x / 2)}\right]}$

$$
\begin{aligned}
& =\int_{0}^{\pi / 2} \frac{\sec ^{2}(x / 2)}{\tan ^{2}(x / 2)+5} d x \\
& =2 \int_{0}^{1} \frac{d t}{t^{2}+(\sqrt{5})^{2}}, \text { where } \tan \frac{x}{2}=t \\
& \qquad\left[\begin{array}{l}
x=0 \Rightarrow t=0 \\
x=\frac{\pi}{2} \Rightarrow t=1
\end{array}\right] \\
& =2 \cdot \frac{1}{\sqrt{5}}\left[\tan ^{-1} \frac{t}{\sqrt{5}}\right]_{0}^{1}=\frac{2}{\sqrt{5}} \tan ^{-1} \frac{1}{\sqrt{5}}
\end{aligned}
$$

**(vi)** $\int_{0}^{\pi / 2} \frac{d x}{\left(4 \sin ^{2} x+5 \cos ^{2} x\right)}=\int_{0}^{\pi / 2} \frac{\sec ^{2} x}{\left(4 \tan ^{2} x+5\right)} d x$
[dividing num. and denom. by $\cos ^{2} x$]

Put $\tan x=t$. Then $\int_{0}^{\infty} \frac{d t}{\left(4 t^{2}+5\right)}$

$$
\begin{aligned}
& =\frac{1}{4} \int_{0}^{\infty} \frac{d t}{t^{2}+\left(\frac{\sqrt{5}}{2}\right)^{2}}=\frac{1}{4} \cdot \frac{2}{\sqrt{5}}\left[\tan ^{-1} \frac{2 t}{\sqrt{5}}\right]_{0}^{\infty} \\
& =\frac{1}{2 \sqrt{5}}\left[\tan ^{-1}(\infty)-\tan ^{-1}(0)\right] \\
& =\frac{1}{2 \sqrt{5}}\left(\frac{\pi}{2}-0\right)=\frac{\pi}{4 \sqrt{5}}
\end{aligned}
$$

---

### Example 3

Evaluate:

1.  $\int_{0}^{1} \frac{x \tan ^{-1} x}{\left(1+x^{2}\right)^{3 / 2}} d x$
2.  $\int_{0}^{1 / \sqrt{2}} \frac{\sin ^{-1} x}{\left(1-x^{2}\right)^{3 / 2}} d x$ \[CBSE 1996, '97]

#### Solution

**(i)** Put $x=\tan \theta$ so that $d x=\sec ^{2} \theta d \theta$.
Clearly, $x=0 \Rightarrow \theta=0$ and $x=1 \Rightarrow \theta=(\pi / 4)$.

$$
\begin{aligned}
\therefore \int_{0}^{1} \frac{x \tan ^{-1} x}{\left(1+x^{2}\right)^{3 / 2}} d x &=\int_{0}^{\pi / 4} \frac{\theta \tan \theta}{\sec ^{3} \theta} \cdot \sec ^{2} \theta d \theta=\int_{0}^{\pi / 4} \theta \sin \theta d \theta \\
& =[-\theta \cos \theta]_{0}^{\pi / 4}-\int_{0}^{\pi / 4}(-\cos \theta) d \theta \quad \text{[integrating by parts]} \\
& =[-\theta \cos \theta]_{0}^{\pi / 4}+[\sin \theta]_{0}^{\pi / 4}=-\frac{\pi}{4} \cos \frac{\pi}{4}+\sin \frac{\pi}{4} \\
& =\left(\frac{-\pi}{4 \sqrt{2}}+\frac{1}{\sqrt{2}}\right)=\frac{(4-\pi)}{4 \sqrt{2}}=\frac{\sqrt{2}(4-\pi)}{8}
\end{aligned}
$$

**(ii)** Put $x=\sin \theta$ so that $d x=\cos \theta d \theta$.
Clearly, $(x=0 \Rightarrow \theta=0)$ and $\left(x=\frac{1}{\sqrt{2}} \Rightarrow \theta=\frac{\pi}{4}\right)$.

$$
\begin{aligned}
\therefore \int_{0}^{1 / \sqrt{2}} \frac{\sin ^{-1} x}{\left(1-x^{2}\right)^{3 / 2}} d x &=\int_{0}^{\pi / 4} \frac{\theta}{\cos ^{3} \theta} \cdot \cos \theta d \theta=\int_{0}^{\pi / 4} \theta \sec ^{2} \theta d \theta \\
&=[\theta \tan \theta]_{0}^{\pi / 4}-\int_{0}^{\pi / 4} 1 \cdot \tan \theta d \theta \quad \text{[integrating by parts]} \\
&=\frac{\pi}{4}+[\log (\cos \theta)]_{0}^{\pi / 4}=\frac{\pi}{4}+\log \left(\cos \frac{\pi}{4}\right) \\
&=\frac{\pi}{4}+\log \left(\frac{1}{\sqrt{2}}\right)=\left(\frac{\pi}{4}-\frac{1}{2} \log 2\right)
\end{aligned}
$$

---

### Example 4

Evaluate:
1.  $\int_{0}^{\pi / 2} \frac{\cos x}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{3}} d x$
2.  $\int_{0}^{\pi / 2} \frac{\cos x}{(1+\cos x+\sin x)} d x$

#### Solution

**(i)** $\int_{0}^{\pi / 2} \frac{\cos x}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{3}} d x=\int_{0}^{\pi / 2} \frac{\left(\cos ^{2} \frac{x}{2}-\sin ^{2} \frac{x}{2}\right)}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{3}} d x$
$=\int_{0}^{\pi / 2} \frac{2\left(\cos \frac{x}{2}-\sin \frac{x}{2}\right)}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{2}} d x=2 \cdot \int_{1}^{\sqrt{2}} \frac{d t}{t^{2}}=\left[\frac{-2}{t}\right]_{1}^{\sqrt{2}}=\sqrt{2}(\sqrt{2}-1)$.

[putting $\cos \frac{x}{2}+\sin \frac{x}{2}=t$ and $\frac{1}{2}\left(\cos \frac{x}{2}-\sin \frac{x}{2}\right) d x=d t$;
also, $x=0 \Rightarrow t=1$ and $x=(\pi / 2) \Rightarrow t=\sqrt{2}$]

**(ii)** $\int_{0}^{\pi / 2} \frac{\cos x}{(1+\cos x+\sin x)} d x=\int_{0}^{\pi / 2} \frac{\cos x}{(1+\cos x)+\sin x} d x$

$$
\begin{aligned}
& =\int_{0}^{\pi / 2} \frac{\cos ^{2}(x / 2)-\sin ^{2}(x / 2)}{\left[2 \cos ^{2}(x / 2)+2 \sin (x / 2) \cos (x / 2)\right]} d x \\
& =\frac{1}{2} \int_{0}^{\pi / 2} \frac{1-\tan ^{2}(x / 2)}{1+\tan (x / 2)} d x \quad \text{[dividing num. and denom. by $\cos ^{2}(x / 2)$]}
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{2} \int_{0}^{\pi / 2}[1-\tan (x / 2)] d x=\frac{1}{2} \int_{0}^{\pi / 2} d x-\frac{1}{2} \int_{0}^{\pi / 2} \frac{\sin (x / 2)}{\cos (x / 2)} d x \\
& =\frac{1}{2} \cdot[x]_{0}^{\pi / 2}+[\log \cos (x / 2)]_{0}^{\pi / 2} \\
& =\frac{\pi}{4}+\log \cos \frac{\pi}{4}=\frac{\pi}{4}+\log \left(\frac{1}{\sqrt{2}}\right)=\left(\frac{\pi}{4}-\frac{1}{2} \log 2\right)
\end{aligned}
$$

---

### Example 5

Evaluate $\int_{-a}^{a} \sqrt{\frac{a-x}{a+x}} d x$. \[CBSE 2008, '11C]

#### Solution

Put $x=a \cos \theta$ so that $d x=-a \sin \theta d \theta$.
Also, $(x=-a \Rightarrow \theta=\pi)$ and $(x=a \Rightarrow \theta=0)$.

$$
\begin{aligned}
\therefore \quad \int_{-a}^{a} \sqrt{\frac{a-x}{a+x}} d x & =\int_{\pi}^{0} \sqrt{\frac{1-\cos \theta}{1+\cos \theta}} \cdot(-a \sin \theta) d \theta \\
& =a \int_{0}^{\pi} \sqrt{\frac{2 \sin ^{2}(\theta / 2)}{2 \cos ^{2}(\theta / 2)}} \cdot 2 \sin (\theta / 2) \cos (\theta / 2) d \theta \\
& =a \int_{0}^{\pi} 2 \sin ^{2}(\theta / 2) d \theta=a \int_{0}^{\pi}(1-\cos \theta) d \theta \\
& =a \int_{0}^{\pi} d \theta-a \int_{0}^{\pi} \cos \theta d \theta \\
& =a \cdot[\theta]_{0}^{\pi}-a[\sin \theta]_{0}^{\pi}=a \pi
\end{aligned}
$$

---

### Example 6

Evaluate $\int_{0}^{1} x \cdot \sqrt{\frac{1-x^{2}}{1+x^{2}}} d x$. \[CBSE 2007]

#### Solution

Put $x^{2}=t$ and $x d x=\frac{1}{2} d t$. Then,
$[x=0 \Rightarrow t=0]$ and $[x=1 \Rightarrow t=1]$.

$$
\begin{aligned}
\therefore \quad I & =\frac{1}{2} \cdot \int_{0}^{1} \sqrt{\frac{1-t}{1+t}} d t \\
& =\frac{1}{2} \cdot \int_{0}^{1}\left\{\frac{\sqrt{1-t}}{\sqrt{1+t}} \times \frac{\sqrt{1-t}}{\sqrt{1-t}}\right\} d t=\frac{1}{2} \cdot \int_{0}^{1} \frac{(1-t)}{\sqrt{1-t^{2}}} d t \\
& =\frac{1}{2} \cdot \int_{0}^{1} \frac{d t}{\sqrt{1-t^{2}}}-\frac{1}{2} \cdot \int_{0}^{1} \frac{t}{\sqrt{1-t^{2}}} d t \\
& =\frac{1}{2} \cdot\left[\sin ^{-1} t\right]_{0}^{1}+\frac{1}{4} \cdot \int_{0}^{1} \frac{(-2 t)}{\sqrt{1-t^{2}}} d t \\
& =\frac{1}{2} \cdot\left[\sin ^{-1} 1-\sin ^{-1} 0\right]+\frac{1}{4} \cdot \int_{1}^{0} \frac{1}{\sqrt{u}} d u, \text { where }\left(1-t^{2}\right)=u \\
& =\frac{1}{2}\left(\frac{\pi}{2}-0\right)-\frac{1}{4} \cdot \int_{0}^{1} \frac{d u}{\sqrt{u}}=\frac{\pi}{4}-\frac{1}{4}[2 \sqrt{u}]_{0}^{1} \\
& =\frac{\pi}{4}-\frac{1}{2}[\sqrt{1}-\sqrt{0}]=\left(\frac{\pi}{4}-\frac{1}{2}\right)
\end{aligned}
$$

---

### Example 7

Evaluate $\int_{0}^{\pi / 2} \frac{\cos x}{(3 \cos x+\sin x)} d x$.

#### Solution

Let $\cos x=A(3 \cos x+\sin x)+B \cdot \frac{d}{d x}(3 \cos x+\sin x)$
Then, $\cos x=A(3 \cos x+\sin x)+B \cdot(-3 \sin x+\cos x)$
Comparing the coefficients of $\cos x$, we get $3 A+B=1$.
Comparing the coefficients of $\sin x$, we get $A-3 B=0$.
Solving $3 A+B=1$ and $A-3 B=0$, we get $A=\frac{3}{10}$ and $B=\frac{1}{10}$.
$\therefore \quad \cos x=\frac{3}{10}(3 \cos x+\sin x)+\frac{1}{10}(-3 \sin x+\cos x)$.

So, $\int_{0}^{\pi / 2} \frac{\cos x}{(3 \cos x+\sin x)} d x$

$$
\begin{aligned}
& =\frac{3}{10} \int_{0}^{\pi / 2} \frac{(3 \cos x+\sin x)}{(3 \cos x+\sin x)} d x+\frac{1}{10} \int_{0}^{\pi / 2} \frac{(-3 \sin x+\cos x)}{(3 \cos x+\sin x)} d x \\
& =\frac{3}{10} \int_{0}^{\pi / 2} d x+\frac{1}{10} \int_{0}^{\pi / 2} \frac{(-3 \sin x+\cos x)}{(3 \cos x+\sin x)} d x \\
& =\frac{3}{10} \cdot[x]_{0}^{\pi / 2}+\frac{1}{10} \cdot[\log |3 \cos x+\sin x|]_{0}^{\pi / 2}=\left(\frac{3 \pi}{20}-\frac{\log 3}{10}\right)
\end{aligned}
$$

---

### Example 8

Evaluate $\int_{0}^{\pi / 2}\{\sqrt{\tan x}+\sqrt{\cot x}\} d x$. \[CBSE 2003, '12]

#### Solution

We have

$$
\begin{aligned}
I & =\int_{0}^{\pi / 2}\left\{\frac{\sqrt{\sin x}}{\sqrt{\cos x}}+\frac{\sqrt{\cos x}}{\sqrt{\sin x}}\right\} d x=\int_{0}^{\pi / 2} \frac{(\sin x+\cos x)}{\sqrt{\sin x \cos x}} d x \\
& =\sqrt{2} \cdot \int_{0}^{\pi / 2} \frac{(\sin x+\cos x)}{\sqrt{2 \sin x \cos x}} d x=\sqrt{2} \cdot \int_{0}^{\pi / 2} \frac{(\sin x+\cos x)}{\sqrt{1-(\sin x-\cos x)^{2}}} d x
\end{aligned}
$$

Put $(\sin x-\cos x)=t$ and $(\cos x+\sin x) d x=d t$.
Also, $[x=0 \Rightarrow t=-1]$ and $\left[x=\frac{\pi}{2} \Rightarrow t=1\right]$.

$$
\begin{aligned}
\therefore \quad I & =\sqrt{2} \cdot \int_{-1}^{1} \frac{d t}{\sqrt{1-t^{2}}}=\sqrt{2}\left[\sin ^{-1} t\right]_{-1}^{1} \\
& =\sqrt{2}\left\{\sin ^{-1}(1)-\sin ^{-1}(-1)\right\}=\sqrt{2}\left\{2 \sin ^{-1}(1)\right\} \\
& =\left(\sqrt{2} \times 2 \times \frac{\pi}{2}\right)=\sqrt{2} \pi
\end{aligned}
$$

---