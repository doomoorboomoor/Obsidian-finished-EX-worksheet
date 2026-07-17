# 16. Definite Integrals

## Fundamental Theorem of Integral Calculus

Let $f(x)$ be a continuous function defined on an interval $[a, b]$ and let the antiderivative of $f(x)$ be $F(x)$. Then, the definite integral of $f(x)$ over $[a, b]$, denoted by $\int_{a}^{b} f(x) d x$, is given by

$$
\int_{a}^{b} f(x) d x=[F(x)]_{a}^{b}=F(b)-F(a) .
$$

**NOTE** Here, $a$ and $b$ are respectively known as the **lower limit** and the **upper limit** of the integral.
The value of a definite integral is unique, for, if $\int f(x) d x=F(x)+C$ then

$$
\int_{a}^{b} f(x) d x=[F(x)+C]_{a}^{b}=\{F(b)+C\}-\{F(a)+C\}=F(b)-F(a)
$$

---

## Solved Examples

*[Integrals based on formulae and integration by parts]*

### Example 1:

Evaluate:
(i) $\int_{2}^{4} \frac{d x}{x}$
(ii) $\int_{4}^{9} \sqrt{x} d x$
(iii) $\int_{0}^{2} \sqrt{6 x+4} d x$
(iv) $\int_{0}^{1} \frac{d x}{\sqrt{5 x+3}}$
(v) $\int_{1}^{\sqrt{2}} \frac{d x}{x\left(\sqrt{x^{2}-1}\right)}$
(vi) $\int_{0}^{\pi} \sin 5 x d x$
(vii) $\int_{0}^{\pi / 2} \cos ^{2} x d x$ *[CBSE 2002]*
(viii) $\int_{0}^{\pi / 4} \tan ^{2} x d x$
(ix) $\int_{0}^{\pi / 4} \sin 2 x \sin 3 x d x$ *[CBSE 2006]*

#### Solution:

(i) $\int_{2}^{4} \frac{d x}{x}=[\log x]_{2}^{4}=(\log 4-\log 2)=(2 \log 2-\log 2)=\log 2$.

(ii) $\int_{4}^{9} \sqrt{x} d x=\left[\frac{2}{3} x^{3 / 2}\right]_{4}^{9}=\frac{2}{3} \cdot\left[(9)^{3 / 2}-(4)^{3 / 2}\right]=\frac{38}{3}$.

(iii) $\int_{0}^{2} \sqrt{6 x+4} d x=\left[\frac{2}{3} \cdot \frac{(6 x+4)^{3 / 2}}{6}\right]_{0}^{2}=\frac{1}{9} \cdot\left[(16)^{3 / 2}-(4)^{3 / 2}\right]=\frac{56}{9}$.

(iv) $\int_{0}^{1} \frac{1}{\sqrt{5 x+3}} d x=\int_{0}^{1}(5 x+3)^{-1 / 2} d x=\left[2 \cdot \frac{(5 x+3)^{1 / 2}}{5}\right]_{0}^{1} =\frac{2}{5}(\sqrt{8}-\sqrt{3})$.

(v) $\int_{1}^{\sqrt{2}} \frac{d x}{x\left(\sqrt{x^{2}-1}\right)}=\left[\sec ^{-1} x\right]_{1}^{\sqrt{2}}=\left[\sec ^{-1}(\sqrt{2})-\sec ^{-1}(1)\right]=\left(\frac{\pi}{4}-0\right)=\frac{\pi}{4}$.

(vi) $\int_{0}^{\pi} \sin 5 x d x=\left[\frac{-\cos 5 x}{5}\right]_{0}^{\pi}=-\frac{1}{5}[\cos 5 \pi-\cos 0]=\frac{2}{5}$.

(vii) $\int_{0}^{\pi / 2} \cos ^{2} x d x=\frac{1}{2} \int_{0}^{\pi / 2}(1+\cos 2 x) d x=\frac{1}{2}\left[x+\frac{\sin 2 x}{2}\right]_{0}^{\pi / 2}=\frac{\pi}{4}$.

(viii) $\int_{0}^{\pi / 4} \tan ^{2} x d x=\int_{0}^{\pi / 4}\left(\sec ^{2} x-1\right) d x=[\tan x-x]_{0}^{\pi / 4}=\left(1-\frac{\pi}{4}\right)$.

(ix) $\int_{0}^{\pi / 4} \sin 2 x \sin 3 x d x=\frac{1}{2} \int_{0}^{\pi / 4}(2 \sin 2 x \sin 3 x) d x$

$$
\begin{aligned}
& =\frac{1}{2} \int_{0}^{\pi / 4}(\cos x-\cos 5 x) d x \\
& =\frac{1}{2}\left[\sin x-\frac{\sin 5 x}{5}\right]_{0}^{\pi / 4} \\
& =\frac{1}{2}\left[\left(\sin \frac{\pi}{4}-\frac{\sin (5 \pi / 4)}{5}\right)\right]=\frac{3 \sqrt{2}}{10} .
\end{aligned}
$$

---

### Example 2:

Evaluate:
(i) $\int_{0}^{\pi / 4} \sqrt{1+\sin 2 x} d x$
(ii) $\int_{0}^{\pi / 2} \sqrt{1+\cos 2 x} d x$

#### Solution:

(i)
$$
\begin{aligned}
\int_{0}^{\pi / 4} \sqrt{1+\sin 2 x} d x & =\int_{0}^{\pi / 4} \sqrt{\cos ^{2} x+\sin ^{2} x+2 \sin x \cos x} d x \\
& =\int_{0}^{\pi / 4}(\cos x+\sin x) d x=[\sin x-\cos x]_{0}^{\pi / 4}=1
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\int_{0}^{\pi / 2} \sqrt{1+\cos 2 x} d x &=\int_{0}^{\pi / 2} \sqrt{2 \cos ^{2} x} d x \\
&=\sqrt{2} \int_{0}^{\pi / 2} \cos x d x=\sqrt{2}[\sin x]_{0}^{\pi / 2}=\sqrt{2}
\end{aligned}
$$

---

### Example 3:

Evaluate: (i) $\int_{0}^{\pi / 2} \cos ^{3} x d x \quad$ (ii) $\int_{0}^{\pi / 2} \sin ^{4} x d x$

#### Solution:

(i)
$$
\begin{aligned}
\int_{0}^{\pi / 2} \cos ^{3} x d x &=\int_{0}^{\pi / 2}\left(\frac{3 \cos x+\cos 3 x}{4}\right) d x \\
& \left.=\frac{3}{4} \cdot \int_{0}^{\pi / 2} \cos x d x+\frac{1}{4} \cdot \int_{0}^{\pi / 2} \cos 3 x=4 \cos ^{3} x-3 \cos x\right] \\
& =\frac{3}{4} \cdot[\sin x]_{0}^{\pi / 2}+\frac{1}{4} \cdot\left[\frac{\sin 3 x}{3}\right]_{0}^{\pi / 2} \\
& =\left(\frac{3}{4}-\frac{1}{12}\right)=\frac{8}{12}=\frac{2}{3}
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\int_{0}^{\pi / 2} \sin ^{4} x d x &=\frac{1}{4} \int_{0}^{\pi / 2}\left(2 \sin ^{2} x\right)^{2} d x \\
& =\frac{1}{4} \cdot \int_{0}^{\pi / 2}(1-\cos 2 x)^{2} d x \\
& =\frac{1}{4} \cdot \int_{0}^{\pi / 2}\left(1-2 \cos 2 x+\cos ^{2} 2 x\right) d x \\
& =\frac{1}{4} \cdot \int_{0}^{\pi / 2}\left[1-2 \cos 2 x+\frac{(1+\cos 4 x)}{2}\right] d x \\
& =\frac{1}{4} \cdot \int_{0}^{\pi / 2}\left(\frac{3}{2}-2 \cos 2 x+\frac{1}{2} \cos 4 x\right) d x \\
& =\frac{3}{8} \cdot \int_{0}^{\pi / 2} d x-\frac{1}{2} \int_{0}^{\pi / 2} \cos 2 x d x+\frac{1}{8} \int_{0}^{\pi / 2} \cos 4 x d x \\
& =\frac{3}{8} \cdot[x]_{0}^{\pi / 2}-\frac{1}{2} \cdot\left[\frac{\sin 2 x}{2}\right]_{0}^{\pi / 2}+\frac{1}{8} \cdot\left[\frac{\sin 4 x}{4}\right]_{0}^{\pi / 2} \\
& =\left(\frac{3 \pi}{16}-0+0\right)=\frac{3 \pi}{16} \cdot
\end{aligned}
$$

---

### Example 4:

Evaluate: (i) $\int_{0}^{4} \frac{d x}{\sqrt{x^{2}+2 x+3}} \quad$ (ii) $\int_{0}^{1} \frac{d x}{\left(1+x+x^{2}\right)}$

#### Solution:

(i)
$$
\begin{aligned}
\int_{0}^{4} \frac{d x}{\sqrt{x^{2}+2 x+3}} &=\int_{0}^{4} \frac{d x}{\sqrt{(x+1)^{2}+(\sqrt{2})^{2}}} \\
& =\left[\log \left|(x+1)+\sqrt{x^{2}+2 x+3}\right|\right]_{0}^{4} \\
& =\{\log |5+\sqrt{27}|-\log |1+\sqrt{3}|\} .
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\int_{0}^{1} \frac{d x}{\left(1+x+x^{2}\right)} &=\int_{0}^{1} \frac{d x}{\left[\left(x^{2}+x+\frac{1}{4}\right)+\frac{3}{4}\right]}=\int_{0}^{1} \frac{d x}{\left[\left(x+\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}\right]} \\
& =\left[\frac{2}{\sqrt{3}} \tan ^{-1} \frac{\left(x+\frac{1}{2}\right)}{(\sqrt{3} / 2)}\right]_{0}^{1}=\frac{2}{\sqrt{3}}\left[\tan ^{-1}\left(\frac{2 x+1}{\sqrt{3}}\right)\right]_{0}^{1} \\
& =\frac{2}{\sqrt{3}}\left[\tan ^{-1}(\sqrt{3})-\tan ^{-1}\left(\frac{1}{\sqrt{3}}\right)\right] \\
& =\frac{2}{\sqrt{3}} \cdot\left[\frac{\pi}{3}-\frac{\pi}{6}\right]=\frac{\pi}{3 \sqrt{3}}
\end{aligned}
$$

---

### Example 5:

Evaluate:
(i) $\int_{0}^{a} \frac{d x}{\sqrt{a x-x^{2}}}$
(ii) $\int_{0}^{\sqrt{2}} \sqrt{2-x^{2}} d x$

#### Solution:

(i)
$$
\begin{aligned}
\int_{0}^{a} \frac{d x}{\sqrt{a x-x^{2}}} & =\int_{0}^{a} \frac{d x}{\sqrt{-\left(x^{2}-a x+\frac{a^{2}}{4}\right)+\frac{a^{2}}{4}}} \\
& =\int_{0}^{a} \frac{d x}{\sqrt{\left(\frac{a}{2}\right)^{2}-\left(x-\frac{a}{2}\right)^{2}}} \\
& =\left[\sin ^{-1} \frac{\left(x-\frac{a}{2}\right)}{\left(\frac{a}{2}\right)}\right]_{0}^{a}=\left[\sin ^{-1}\left(\frac{2 x-a}{a}\right)\right]_{0}^{a} \\
& =\left[\sin ^{-1}(1)-\sin ^{-1}(-1)\right] \\
& =2 \sin ^{-1}(1)=\left(2 \times \frac{\pi}{2}\right)=\pi
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\int_{0}^{\sqrt{2}} \sqrt{2-x^{2}} d x &=\int_{0}^{\sqrt{2}} \sqrt{(\sqrt{2})^{2}-x^{2}} d x \\
& =\left[\frac{x}{2} \sqrt{2-x^{2}}+\frac{(\sqrt{2})^{2}}{2} \cdot \sin ^{-1} \frac{x}{\sqrt{2}}\right]_{0}^{\sqrt{2}} \\
& =\left[0+\sin ^{-1}(1)\right]-\left[0+\sin ^{-1} 0\right]=\frac{\pi}{2}
\end{aligned}
$$

---

### Example 6:

Evaluate:
(i) $\int_{0}^{\pi / 2} x \cos x d x$
(ii) $\int_{0}^{\pi} \cos 2 x \log \sin x d x$
(iii) $\int_{1}^{2} \frac{\log x}{x^{2}} d x$
(iv) $\int_{0}^{\pi / 6}\left(2+3 x^{2}\right) \cos 3 x d x$

#### Solution:

(i) Integrating by parts, we get
$$
\begin{aligned}
\int_{0}^{\pi / 2} x \cos x d x & =[x \sin x]_{0}^{\pi / 2}-\int_{0}^{\pi / 2} 1 \cdot \sin x d x \\
& =\frac{\pi}{2}+[\cos x]_{0}^{\pi / 2}=\left(\frac{\pi}{2}-1\right)
\end{aligned}
$$

(ii) Integrating by parts, taking $\log (\sin x)$ as the first function, we get

$$
\int_{0}^{\pi} \cos 2 x \log \sin x d x
$$
$$
\begin{aligned}
& =\left[(\log \sin x) \cdot \frac{\sin 2 x}{2}\right]_{0}^{\pi}-\int_{0}^{\pi}\left(\cot x \cdot \frac{\sin 2 x}{2}\right) d x \\
& =0-\int_{0}^{\pi} \frac{\cos x}{\sin x} \cdot \frac{2 \sin x \cos x}{2} d x=-\int_{0}^{\pi} \cos ^{2} x d x \\
& =-\frac{1}{2} \int_{0}^{\pi} 2 \cos ^{2} x d x=-\frac{1}{2} \int_{0}^{\pi}(1+\cos 2 x) d x \\
& =-\frac{1}{2} \cdot\left[x+\frac{\sin 2 x}{2}\right]_{0}^{\pi}=-\frac{\pi}{2}
\end{aligned}
$$

(iii) Integrating by parts, taking ($\log x$) as the first function, we get
$$
\begin{aligned}
\int_{1}^{2} \frac{\log x}{x^{2}} d x & =\int_{1}^{2}(\log x) \cdot x^{-2} d x \\
& =\left[(\log x)\left(-\frac{1}{x}\right)\right]_{1}^{2}-\int_{1}^{2} \frac{1}{x} \cdot\left(-\frac{1}{x}\right) d x \\
& =\left[-\frac{\log 2}{2}+\frac{\log 1}{1}\right]+\int_{1}^{2} \frac{d x}{x^{2}} \\
& =\frac{-\log 2}{2}-\left[\frac{1}{x}\right]_{1}^{2}=\frac{-\log 2}{2}-\left\{\frac{1}{2}-1\right\}=\left(\frac{1-\log 2}{2}\right)
\end{aligned}
$$

(iv)
$$
\int_{0}^{\pi / 6}\left(2+3 x^{2}\right) \cos 3 x d x
$$
$$
\begin{aligned}
& \quad=2 \int_{0}^{\pi / 6} \cos 3 x d x+3 \int_{0}^{\pi / 6} x^{2} \cos 3 x d x \\
& \quad=2\left[\frac{\sin 3 x}{3}\right]_{0}^{\pi / 6}+3\left\{\left[x^{2}\left(\frac{\sin 3 x}{3}\right)\right]_{0}^{\pi / 6}-\int_{0}^{\pi / 6} 2 x\left(\frac{\sin 3 x}{3}\right) d x\right\} \\
& \quad \text { [integrating by parts] } \\
& \quad=\frac{2}{3}+\frac{\pi^{2}}{36}-2 \int_{0}^{\pi / 6} x \sin 3 x d x \\
& \quad=\frac{2}{3}+\frac{\pi^{2}}{36}-2\left\{\left[x\left(\frac{-\cos 3 x}{3}\right)\right]_{0}^{\pi / 6}-\int_{0}^{\pi / 6} 1 \cdot\left(\frac{-\cos 3 x}{3}\right) d x\right\}
\end{aligned}
$$

*[integrating by parts]*

$$
\begin{aligned}
& =\frac{2}{3}+\frac{\pi^{2}}{36}+\frac{2}{3}[x \cos 3 x]_{0}^{\pi / 6}-\frac{2}{3} \cdot\left[\frac{\sin 3 x}{3}\right]_{0}^{\pi / 6} \\
& =\frac{2}{3}+\frac{\pi^{2}}{36}-\frac{2}{9}=\left(\frac{\pi^{2}}{36}+\frac{4}{9}\right)=\frac{1}{36}\left(\pi^{2}+16\right)
\endend{aligned}
$$

---

### Example 7:

Evaluate $\int_{1}^{2} \frac{d x}{x\left(1+x^{2}\right)}$.

#### Solution:

Let $\frac{1}{x\left(1+x^{2}\right)}=\frac{A}{x}+\frac{B x+C}{\left(1+x^{2}\right)}$.
Then, $1 \equiv A\left(1+x^{2}\right)+(B x+C) x$. Putting $x=0$, we get $A=1$.
Comparing the coefficients of $x^{2}$, we get $A+B=0$ or $B=-1$.
Comparing coefficients of $x$, we get $C=0$.

$$
\therefore \quad \frac{1}{x\left(1+x^{2}\right)}=\left[\frac{1}{x}-\frac{x}{1+x^{2}}\right]
$$

So,
$$
\begin{aligned}
\int_{1}^{2} \frac{d x}{x\left(1+x^{2}\right)} & =\int_{1}^{2} \frac{d x}{x}-\frac{1}{2} \int_{1}^{2} \frac{2 x}{1+x^{2}} d x \\
& =[\log x]_{1}^{2}-\frac{1}{2}\left[\log \left(1+x^{2}\right)\right]_{1}^{2} \\
& =\left[\frac{3}{2}(\log 2)-\frac{1}{2}(\log 5)\right]
\end{aligned}
$$

---

### Example 8:

Evaluate $\int_{2}^{4} \frac{\left(x^{2}+x\right)}{\sqrt{2 x+1}} d x$.

#### Solution:

Integrating by parts, taking ($x^{2}+x$) as the first function and $\frac{1}{\sqrt{2 x+1}}$ as the second function, we get
$$
\begin{aligned}
\int_{2}^{4} \frac{\left(x^{2}+x\right)}{\sqrt{2 x+1}} d x & =\left[\left(x^{2}+x\right) \cdot \sqrt{2 x+1}\right]_{2}^{4}-\int_{2}^{4}(2 x+1) \cdot \sqrt{2 x+1} d x \\
& =(60-6 \sqrt{5})-\int_{2}^{4}(2 x+1)^{3 / 2} d x \\
& =(60-6 \sqrt{5})-\frac{1}{5} \cdot\left[(2 x+1)^{5 / 2}\right]_{2}^{4} \\
& =(60-6 \sqrt{5})-\left(\frac{243}{5}-5 \sqrt{5}\right) \\
& =\left(\frac{57}{5}-\sqrt{5}\right)=\sqrt{\frac{57-5 \sqrt{5}}{5}}
\end{aligned}
$$

---

### Example 9:

Evaluate:
(i) $\int_{0}^{1 / 2} \frac{d x}{\sqrt{1-x}}$
(ii) $\int_{0}^{1}\left(\frac{1-x}{1+x}\right) d x$

#### Solution:

(i) $\int_{0}^{1 / 2} \frac{d x}{\sqrt{1-x}}=\int_{0}^{1 / 2}(1-x)^{-1 / 2} d x=\left[\frac{2 \sqrt{1-x}}{-1}\right]_{0}^{1 / 2}=(2-\sqrt{2})$.

(ii) $\int_{0}^{1}\left(\frac{1-x}{1+x}\right) d x=\int_{0}^{1}\left(-1+\frac{2}{x+1}\right) d x$ *[on dividing $(-x+1)$ by $(x+1)$]* $=[-x+2 \log |x+1|]_{0}^{1}=[(2 \log 2)-1]$.

---