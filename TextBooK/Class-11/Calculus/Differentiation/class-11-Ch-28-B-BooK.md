## Some Derivatives from the First Principle

## Solved Examples

### Example: Differentiate $x^{6}$ from the first principle.

#### Solution:

Let $y=x^{6}$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=(x+\delta x)^{6}$.

$\Rightarrow \quad \delta y=(x+\delta x)^{6}-x^{6}$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{(x+\delta x)^{6}-x^{6}}{\delta x}$

$\Rightarrow \quad \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{(x+\delta x)^{6}-x^{6}}{\delta x}
$$

$$
=\lim _{(x+\delta x) \rightarrow x} \frac{(x+\delta x)^{6}-x^{6}}{(x+\delta x)-x} \quad[\because(\delta x \rightarrow 0) \Rightarrow(x+\delta x) \rightarrow x]
$$

$$
=6 x^{(6-1)}=6 x^{5} \quad\left[\because \lim _{x \rightarrow a} \frac{x^{n}-a^{n}}{x-a}=n a^{n-1}\right]
$$

**Hence, $\frac{d}{d x}\left(x^{6}\right)=6 x^{5}$.**

---

### Example: Differentiate $e^{3 x}$ from the first principle.

#### Solution:

Let $y=e^{3 x}$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=e^{3(x+\delta x)}$.

$\Rightarrow \quad \delta y=e^{3(x+\delta x)}-e^{3 x}$

$\Rightarrow \quad \frac{\delta y}{\delta x}=\frac{e^{3(x+\delta x)}-e^{3 x}}{\delta x}$

$\Rightarrow \quad \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{e^{3(x+\delta x)}-e^{3 x}}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} \frac{e^{3x} \cdot e^{3 \delta x}-e^{3 x}}{\delta x} = \lim _{\delta x \rightarrow 0} \frac{e^{3x}(e^{3 \delta x}-1)}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} 3 e^{3 x} \cdot\left(\frac{e^{3 \delta x}-1}{3 \delta x}\right)
$$

$$
\begin{align*}
&=3 e^{3 x} \cdot \lim _{z \rightarrow 0}\left(\frac{e^{z}-1}{z}\right), \text { where } z=3 \delta x \\
&=\left(3 e^{3 x} \times 1\right)=3 e^{3 x} \quad\left[\because \lim _{z \rightarrow 0}\left(\frac{e^{z}-1}{z}\right)=1\right]
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(e^{3 x}\right)=3 e^{3 x}$.**

---

### Example: Find the derivative of each of the following from the first principle.
1. $x^{2}+3 x+5$
2. $x^{3}+4 x^{2}+3 x+2$

#### Solution:

(i) Let $y=x^{2}+3 x+5$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=(x+\delta x)^{2}+3(x+\delta x)+5$.

$\Rightarrow \delta y=\left[(x+\delta x)^{2}+3(x+\delta x)+5\right]-\left(x^{2}+3 x+5\right)$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{\left[(x+\delta x)^{2}+3(x+\delta x)+5\right]-\left(x^{2}+3 x+5\right)}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{\left[(x+\delta x)^{2}+3(x+\delta x)+5\right]-\left(x^{2}+3 x+5\right)}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} \frac{(x^2 + 2x\delta x + (\delta x)^2 + 3x + 3\delta x + 5) - (x^2 + 3x + 5)}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} \frac{2x \cdot \delta x + (\delta x)^{2} + 3 \delta x}{\delta x}=\lim _{\delta x \rightarrow 0}[2x + \delta x+3]=(2 x+3)
$$

**$\therefore \frac{d}{d x}\left(x^{2}+3 x+5\right)=(2 x+3)$.**

(ii) Let $y=x^{3}+4 x^{2}+3 x+2$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=(x+\delta x)^{3}+4(x+\delta x)^{2}+3(x+\delta x)+2$.

$\Rightarrow \delta y=\left[(x+\delta x)^{3}+4(x+\delta x)^{2}+3(x+\delta x)+2\right]-\left(x^{3}+4 x^{2}+3 x+2\right)$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{\left[(x+\delta x)^{3}+4(x+\delta x)^{2}+3(x+\delta x)+2\right]-\left(x^{3}+4 x^{2}+3 x+2\right)}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{[(x+\delta x)^3 - x^3] + 4[(x+\delta x)^2 - x^2] + 3[(x+\delta x) - x]}{\delta x}
$$

$$
\begin{align*}
& =\lim _{\delta x \rightarrow 0} \frac{(3x^2\delta x + 3x(\delta x)^2 + (\delta x)^3) + 4(2x\delta x + (\delta x)^2) + 3\delta x}{\delta x} \\
& =\lim _{\delta x \rightarrow 0} \frac{3x^2\delta x + 8x\delta x + 3\delta x + 3x(\delta x)^2 + 4(\delta x)^2 + (\delta x)^3}{\delta x} \\
& =\lim _{\delta x \rightarrow 0}\left[3x^2 + 8x + 3 + 3x\delta x + 4\delta x + (\delta x)^2\right] = (3 x^{2}+8 x+3)
\end{align*}
$$

**$\therefore \frac{d}{d x}\left(x^{3}+4 x^{2}+3 x+2\right)=3 x^{2}+8 x+3$.**

---

### Example: Differentiate each of the following ab initio.
1. $(x+5)^{7}$
2. $(x-\frac{1}{x})$

#### Solution:

(i) Let $y=(x+5)^{7}$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=(x+\delta x+5)^{7}$.

$\Rightarrow \delta y=(x+\delta x+5)^{7}-(x+5)^{7}$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{(x+\delta x+5)^{7}-(x+5)^{7}}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{(x+\delta x+5)^{7}-(x+5)^{7}}{\delta x}
$$

$$
=\lim _{(x+\delta x+5) \rightarrow(x+5)} \frac{\left[(x+\delta x+5)^{7}-(x+5)^{7}\right]}{[(x+\delta x+5)-(x+5)]}
$$

Let $u = (x+\delta x+5)$ and $a = (x+5)$. As $\delta x \rightarrow 0$, $u \rightarrow a$.

$$
=\lim _{u \rightarrow a}\left(\frac{u^{7}-a^{7}}{u-a}\right)
$$

$$
=7 a^{(7-1)}=7(x+5)^{6} \quad\left[\because \lim _{u \rightarrow a}\left(\frac{u^{n}-a^{n}}{u-a}\right)=n a^{n-1}\right]
$$

**Hence, $\frac{d}{d x}(x+5)^{7}=7(x+5)^{6}$.**

(ii) Let $y=\left(x-\frac{1}{x}\right)$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=\left[(x+\delta x)-\frac{1}{(x+\delta x)}\right]$.

$\Rightarrow \delta y=\left[(x+\delta x)-\frac{1}{(x+\delta x)}\right]-\left(x-\frac{1}{x}\right)$

$$
\Rightarrow \delta y = (x+\delta x - x) + \left(\frac{1}{x}-\frac{1}{x+\delta x}\right) = \delta x+\left\{\frac{(x+\delta x)-x}{x(x+\delta x)}\right\}
$$

$$
\Rightarrow \frac{\delta y}{\delta x} = \frac{\delta x+\frac{\delta x}{x(x+\delta x)}}{\delta x} = 1 + \frac{1}{x(x+\delta x)}
$$

$$
\begin{align*}
\Rightarrow \frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x} = \lim _{\delta x \rightarrow 0}\left[1+\frac{1}{x(x+\delta x)}\right] \\
&= \left(1+\frac{1}{x^{2}}\right)
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(x-\frac{1}{x}\right)=\left(1+\frac{1}{x^{2}}\right)$.**

---

### Example: Find the derivative of each of the following from the first principle.
1. $\sin 2x$
2. $\cos 3x$
3. $\tan 5x$

#### Solution:

(i) Let $y=\sin 2x$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=\sin 2(x+\delta x)$.

$\Rightarrow \delta y=\sin (2 x+2 \delta x)-\sin 2 x$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{\sin (2 x+2 \delta x)-\sin 2 x}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{\sin (2 x+2 \delta x)-\sin 2 x}{\delta x}
$$

Using the identity $(\sin C-\sin D)=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$,

$$
=\lim _{\delta x \rightarrow 0} \frac{2 \cos (2 x+\delta x) \sin \delta x}{\delta x}
$$

$$
=2 \cdot \lim _{\delta x \rightarrow 0} \cos (2 x+\delta x) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x}
$$

$$
=(2 \cos 2 x \times 1)=2 \cos 2 x
$$

**Hence, $\frac{d}{d x}(\sin 2 x)=2 \cos 2 x$.**

(ii) Let $y=\cos 3x$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=\cos 3(x+\delta x)$.

$\Rightarrow \delta y=\cos (3 x+3 \delta x)-\cos 3 x$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{\cos (3 x+3 \delta x)-\cos 3 x}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{\cos (3 x+3 \delta x)-\cos 3 x}{\delta x}
$$

Using the identity $(\cos C-\cos D)=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$,

$$
=\lim _{\delta x \rightarrow 0} \frac{-2 \sin \left(3 x+\frac{3}{2} \delta x\right) \sin \left(\frac{3}{2} \delta x\right)}{\delta x}
$$

$$
=-\lim _{\delta x \rightarrow 0} \sin \left(3 x+\frac{3}{2} \delta x\right) \cdot \lim _{\delta x \rightarrow 0} \frac{3 \sin \left(\frac{3}{2} \delta x\right)}{\left(\frac{3}{2} \delta x\right)}
$$

$$
=(-\sin 3 x \times 3 \times 1)=-3 \sin 3 x
$$

**Hence, $\frac{d}{d x}(\cos 3 x)=-3 \sin 3 x$.**

(iii) Let $y=\tan 5x$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=\tan 5(x+\delta x)$.

$\Rightarrow \delta y=\tan (5 x+5 \delta x)-\tan 5 x$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{\tan (5 x+5 \delta x)-\tan 5 x}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
=\lim _{\delta x \rightarrow 0} \frac{\tan (5 x+5 \delta x)-\tan 5 x}{\delta x}
$$

$$
=\lim _{\delta x \rightarrow 0} \frac{\frac{\sin (5 x+5 \delta x)}{\cos (5 x+5 \delta x)}-\frac{\sin 5 x}{\cos 5 x}}{\delta x}
$$

$$
\begin{align*}
& =\lim _{\delta x \rightarrow 0} \frac{\sin (5 x+5 \delta x) \cos 5 x-\cos (5 x+5 \delta x) \sin 5 x}{\delta x \cdot \cos (5 x+5 \delta x) \cdot \cos 5 x} \\
& =\lim _{\delta x \rightarrow 0} \frac{\sin (5 x+5 \delta x-5 x)}{\delta x \cdot \cos (5 x+5 \delta x) \cdot \cos 5 x} \quad [\because \sin A \cos B-\cos A \sin B=\sin (A-B)] \\
& =\lim _{\delta x \rightarrow 0} \frac{\sin (5 \delta x)}{\delta x \cdot \cos (5 x+5 \delta x) \cdot \cos 5 x} \\
& =\lim _{\delta x \rightarrow 0} \frac{\sin (5 \delta x)}{5\delta x} \cdot 5 \cdot \frac{1}{\cos (5 x+5 \delta x) \cdot \cos 5 x} \\
& = \left(1 \cdot 5 \cdot \frac{1}{\cos(5x) \cdot \cos(5x)}\right) = \frac{5}{\cos ^{2} 5 x}=5 \sec ^{2} 5 x
\end{align*}
$$

**Hence, $\frac{d}{d x}(\tan 5 x)=5 \sec ^{2} 5 x$.**

---

### Example: Differentiate $x \sin x$ from the first principle.

#### Solution:

Let $y=x \sin x$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=(x+\delta x) \sin (x+\delta x)$.

$\Rightarrow \delta y=(x+\delta x) \sin (x+\delta x)-x \sin x$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{(x+\delta x) \sin (x+\delta x)-x \sin x}{\delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
\begin{align*}
& =\lim _{\delta x \rightarrow 0} \frac{x \sin (x+\delta x)+\delta x \sin (x+\delta x)-x \sin x}{\delta x} \\
& =\lim _{\delta x \rightarrow 0}\left[\frac{x\{\sin (x+\delta x)-\sin x\}}{\delta x}+\frac{\delta x \sin (x+\delta x)}{\delta x}\right] \\
& =\lim _{\delta x \rightarrow 0} \frac{x\{\sin (x+\delta x)-\sin x\}}{\delta x}+\lim _{\delta x \rightarrow 0} \sin (x+\delta x) \\
& =\lim _{\delta x \rightarrow 0}\left\{\frac{x \cdot 2 \cos \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\delta x}\right\}+\sin x \\
& =\lim _{\delta x \rightarrow 0}\left\{x \cos \left(x+\frac{\delta x}{2}\right) \frac{\sin (\delta x / 2)}{(\delta x / 2)}\right\}+\sin x \\
& =(x \cdot \cos x \cdot 1)+\sin x=(x \cos x+\sin x)
\end{align*}
$$

**Hence, $\frac{d}{d x}(x \sin x)=(x \cos x+\sin x)$.**

---

### Example: Differentiate $\frac{\sin x}{x}$ from the first principle.

#### Solution:

Let $y=\frac{\sin x}{x}$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=\frac{\sin (x+\delta x)}{(x+\delta x)}$.

$\Rightarrow \quad \delta y=\frac{\sin (x+\delta x)}{(x+\delta x)}-\frac{\sin x}{x}=\frac{x \sin (x+\delta x)-(x+\delta x) \sin x}{x(x+\delta x)}$

$\Rightarrow \frac{\delta y}{\delta x}=\frac{x \sin (x+\delta x)-(x+\delta x) \sin x}{x(x+\delta x) \cdot \delta x}$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\delta y}{\delta x}$

$$
\begin{align*}
& =\lim _{\delta x \rightarrow 0} \frac{x \sin (x+\delta x) - x \sin x - \delta x \sin x}{x(x+\delta x) \cdot \delta x} \\
& =\lim _{\delta x \rightarrow 0} \left( \frac{x[\sin (x+\delta x)-\sin x]}{x(x+\delta x) \cdot \delta x} - \frac{\delta x \sin x}{x(x+\delta x) \cdot \delta x} \right) \\
& =\lim _{\delta x \rightarrow 0} \frac{2 \cos \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{(x+\delta x) \cdot \delta x} - \lim_{\delta x \to 0} \frac{\sin x}{x(x+\delta x)} \\
& = \lim _{\delta x \rightarrow 0} \frac{\cos \left(x+\frac{\delta x}{2}\right)}{(x+\delta x)} \cdot \frac{\sin (\delta x / 2)}{(\delta x / 2)} - \frac{\sin x}{x^2} \\
& = \left( \frac{\cos x}{x} \cdot 1 \right) - \frac{\sin x}{x^{2}}=\frac{x \cos x-\sin x}{x^{2}}
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\frac{\sin x}{x}\right)=\frac{x \cos x-\sin x}{x^{2}}$.**

---

### Example: Differentiate $\cot (2 x+1)$ from the first principle.

#### Solution:

Let $y=\cot (2 x+1)$.

Let $\delta y$ be an increment in $y$, corresponding to an increment $\delta x$ in $x$.

Then, $y+\delta y=\cot [2(x+\delta x)+1]$.

$\Rightarrow \delta y=\cot [2(x+\delta x)+1]-\cot (2 x+1)$

$\Rightarrow \frac{d y}{d x}=\lim _{\delta x \rightarrow 0} \frac{\cot (2 x+2 \delta x+1)-\cot (2 x+1)}{\delta x}$

$$
\begin{align*}
& =\lim _{\delta x \rightarrow 0} \frac{\frac{\cos (2 x+2 \delta x+1)}{\sin (2 x+2 \delta x+1)}-\frac{\cos (2 x+1)}{\sin (2 x+1)}}{\delta x} \\
& =\lim _{\delta x \rightarrow 0} \frac{\sin (2 x+1) \cos (2 x+2 \delta x+1)-\cos (2 x+1) \sin (2 x+2 \delta x+1)}{\delta x \cdot \sin (2 x+2 \delta x+1) \cdot \sin (2 x+1)} \\
& =\lim _{\delta x \rightarrow 0} \frac{\sin [(2 x+1)-(2 x+2 \delta x+1)]}{\delta x \cdot \sin (2 x+2 \delta x+1) \cdot \sin (2 x+1)} \\
& =\lim _{\delta x \rightarrow 0} \frac{\sin (-2 \delta x)}{\delta x \cdot \sin (2 x+2 \delta x+1) \cdot \sin (2 x+1)} \\
& =\lim _{\delta x \rightarrow 0} \frac{-\sin (2 \delta x)}{2\delta x} \cdot \frac{2}{\sin (2 x+2 \delta x+1) \cdot \sin (2 x+1)} \\
& = (-1) \cdot \frac{2}{\sin(2x+1) \cdot \sin(2x+1)} = \frac{-2}{\sin ^{2}(2 x+1)} = -2 \operatorname{cosec}^{2}(2 x+1)
\end{align*}
$$

**Hence, $\frac{d}{d x}[\cot (2 x+1)]=-2 \operatorname{cosec}^{2}(2 x+1)$.**

---

### Example: Find the derivative of each of the following from the first principle.
1. $\sqrt{2 x+3}$
2. $\sqrt{4-x}$
3. $\frac{1}{\sqrt{x}}$

#### Solution:

(i) Let $y=\sqrt{2 x+3}$.

Let $\delta y = \sqrt{2(x+\delta x)+3}-\sqrt{2 x+3}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{2 x+2 \delta x+3}-\sqrt{2 x+3}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{2 x+2 \delta x+3}-\sqrt{2 x+3}}{\delta x} \times \frac{\sqrt{2 x+2 \delta x+3}+\sqrt{2 x+3}}{\sqrt{2 x+2 \delta x+3}+\sqrt{2 x+3}} \\
& =\lim _{\delta x \rightarrow 0} \frac{(2 x+2 \delta x+3)-(2 x+3)}{\delta x \cdot(\sqrt{2 x+2 \delta x+3}+\sqrt{2 x+3})} \\
& =\lim _{\delta x \rightarrow 0} \frac{2 \delta x}{\delta x \cdot(\sqrt{2 x+2 \delta x+3}+\sqrt{2 x+3})} \\
& =\lim _{\delta x \rightarrow 0} \frac{2}{\sqrt{2 x+2 \delta x+3}+\sqrt{2 x+3}} \\
& =\frac{2}{2 \sqrt{2 x+3}}=\frac{1}{\sqrt{2 x+3}}
\end{align*}
$$

**$\therefore \frac{d}{d x}(\sqrt{2 x+3})=\frac{1}{\sqrt{2 x+3}}$.**

(ii) Let $y=\sqrt{4-x}$.

Let $\delta y=\sqrt{4-(x+\delta x)}-\sqrt{4-x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{4-x-\delta x}-\sqrt{4-x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{4-x-\delta x}-\sqrt{4-x}}{\delta x} \times \frac{\sqrt{4-x-\delta x}+\sqrt{4-x}}{\sqrt{4-x-\delta x}+\sqrt{4-x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{(4-x-\delta x)-(4-x)}{\delta x(\sqrt{4-x-\delta x}+\sqrt{4-x})} \\
&= \lim _{\delta x \rightarrow 0} \frac{-\delta x}{\delta x(\sqrt{4-x-\delta x}+\sqrt{4-x})} \\
&= \lim _{\delta x \rightarrow 0} \frac{-1}{\sqrt{4-x-\delta x}+\sqrt{4-x}} = \frac{-1}{2 \sqrt{4-x}}
\end{align*}
$$

**$\therefore \frac{d}{d x}(\sqrt{4-x})=\frac{-1}{2 \sqrt{4-x}}$.**

(iii) Let $y=\frac{1}{\sqrt{x}}$.

Let $\delta y=\frac{1}{\sqrt{x+\delta x}}-\frac{1}{\sqrt{x}}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{1}{\delta x} \cdot \left[\frac{1}{\sqrt{x+\delta x}}-\frac{1}{\sqrt{x}}\right] \\
&= \lim _{\delta x \rightarrow 0} \frac{1}{\delta x} \cdot \frac{\sqrt{x}-\sqrt{x+\delta x}}{\sqrt{x+\delta x} \cdot \sqrt{x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{x}-\sqrt{x+\delta x}}{\delta x \cdot \sqrt{x(x+\delta x)}} \times \frac{\sqrt{x}+\sqrt{x+\delta x}}{\sqrt{x}+\sqrt{x+\delta x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{x-(x+\delta x)}{\delta x \cdot \sqrt{x(x+\delta x)} \cdot (\sqrt{x}+\sqrt{x+\delta x})} \\
&= \lim _{\delta x \rightarrow 0} \frac{-\delta x}{\delta x \cdot \sqrt{x(x+\delta x)} \cdot (\sqrt{x}+\sqrt{x+\delta x})} \\
&= \lim _{\delta x \rightarrow 0} \frac{-1}{\sqrt{x(x+\delta x)} \cdot (\sqrt{x}+\sqrt{x+\delta x})} \\
&= \frac{-1}{\sqrt{x^2} \cdot (\sqrt{x}+\sqrt{x})} = \frac{-1}{x \cdot (2\sqrt{x})} = \frac{-1}{2 x^{3 / 2}}
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\frac{1}{\sqrt{x}}\right)=\frac{-1}{2 x^{3 / 2}}$.**

---

### Example: Find the derivative of $x^{-3 / 2}$ from the first principle.

#### Solution:

Let $y=x^{-3 / 2}$. Let $u = x + \delta x$. As $\delta x \to 0$, $u \to x$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{(x+\delta x)^{-3 / 2}-x^{-3 / 2}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{(x+\delta x)^{-3 / 2}-x^{-3 / 2}}{(x+\delta x)-x} \\
&= \lim_{u \to x} \frac{u^{-3/2} - x^{-3/2}}{u-x} \\
&= -\frac{3}{2} x^{\left(-\frac{3}{2}-1\right)} \\
&= -\frac{3}{2} x^{-5 / 2}
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(x^{-3 / 2}\right)=-\frac{3}{2} x^{-5 / 2}$.**

---

### Example: Find the derivative of $\frac{1}{x^{2}}$ from the first principle.

#### Solution:

Let $y=\frac{1}{x^{2}} = x^{-2}$. Let $u=x+\delta x$. As $\delta x \to 0$, $u \to x$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{(x+\delta x)^{-2}-x^{-2}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{(x+\delta x)^{-2}-x^{-2}}{(x+\delta x)-x} \\
&= \lim _{u \rightarrow x} \frac{u^{-2}-x^{-2}}{u-x} \\
&= -2 x^{(-2-1)}=-2 x^{-3}=\frac{-2}{x^{3}} \quad\left[\because \lim _{u \rightarrow a} \frac{u^{n}-a^{n}}{u-a}=n a^{n-1}\right]
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\frac{1}{x^{2}}\right)=\frac{-2}{x^{3}}$.**

---

### Example: Differentiate $\sqrt{\sin 3 x}$ from the first principle.

#### Solution:

Let $y=\sqrt{\sin 3 x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\sin (3 x+3 \delta x)}-\sqrt{\sin 3 x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\sin (3 x+3 \delta x)}-\sqrt{\sin 3 x}}{\delta x} \times \frac{\sqrt{\sin (3 x+3 \delta x)}+\sqrt{\sin 3 x}}{\sqrt{\sin (3 x+3 \delta x)}+\sqrt{\sin 3 x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin (3 x+3 \delta x)-\sin 3 x}{\delta x \cdot\{\sqrt{\sin (3 x+3 \delta x)}+\sqrt{\sin 3 x}\}} \\
&= \lim _{\delta x \rightarrow 0} \frac{2 \cos \left(3 x+\frac{3}{2} \delta x\right) \sin \left(\frac{3}{2} \delta x\right)}{\delta x \cdot\{\sqrt{\sin (3 x+3 \delta x)}+\sqrt{\sin 3 x}\}} \\
&= \lim _{\delta x \rightarrow 0} \left[ \cos \left(3 x+\frac{3}{2} \delta x\right) \cdot \frac{\sin \left(\frac{3}{2} \delta x\right)}{\frac{3}{2}\delta x} \cdot 3 \cdot \frac{1}{\{\sqrt{\sin (3 x+3 \delta x)}+\sqrt{\sin 3 x}\}} \right] \\
&= \cos(3x) \cdot 1 \cdot 3 \cdot \frac{1}{\sqrt{\sin 3x} + \sqrt{\sin 3x}} \\
&= 3 \cos 3 x \cdot \frac{1}{2 \sqrt{\sin 3 x}}=\frac{3 \cos 3 x}{2 \sqrt{\sin 3 x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\sqrt{\sin 3 x})=\frac{3 \cos 3 x}{2 \sqrt{\sin 3 x}}$.**

---

### Example: Find the derivative of $e^{\sqrt{x}}$ from the first principle.

#### Solution:

Let $y=e^{\sqrt{x}}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{e^{\sqrt{x+\delta x}}-e^{\sqrt{x}}}{\delta x} = \lim _{\delta x \rightarrow 0} \frac{e^{\sqrt{x}}\left[e^{\sqrt{x+\delta x}-\sqrt{x}}-1\right]}{x+\delta x-x} \\
&= \lim _{\delta x \rightarrow 0} \frac{e^{\sqrt{x}}\left[e^{\sqrt{x+\delta x}-\sqrt{x}}-1\right]}{(\sqrt{x+\delta x}-\sqrt{x})(\sqrt{x+\delta x}+\sqrt{x})} \\
&= e^{\sqrt{x}} \cdot \lim_{\delta x \to 0} \frac{e^{\sqrt{x+\delta x}-\sqrt{x}}-1}{\sqrt{x+\delta x}-\sqrt{x}} \cdot \lim_{\delta x \to 0} \frac{1}{\sqrt{x+\delta x}+\sqrt{x}}
\end{align*}
$$

Let $\theta = \sqrt{x+\delta x}-\sqrt{x}$. As $\delta x \rightarrow 0$, $\theta \rightarrow 0$.

$$
\begin{align*}
&=e^{\sqrt{x}} \cdot \lim _{\theta \rightarrow 0} \frac{e^{\theta}-1}{\theta} \cdot \lim _{\delta x \rightarrow 0} \frac{1}{\sqrt{x+\delta x}+\sqrt{x}} \\
&= e^{\sqrt{x}} \times 1 \times \frac{1}{2 \sqrt{x}} = \frac{e^{\sqrt{x}}}{2 \sqrt{x}} \quad\left[\because \lim _{\theta \rightarrow 0} \frac{e^{\theta}-1}{\theta}=1\right]
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(e^{\sqrt{x}}\right)=\frac{e^{\sqrt{x}}}{2 \sqrt{x}}$.**

---

### Example: Find the derivative of $e^{x^{2}}$ from the first principle.

#### Solution:

Let $y=e^{x^{2}}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{e^{(x+\delta x)^{2}}-e^{x^{2}}}{\delta x} = \lim _{\delta x \rightarrow 0} \frac{e^{x^{2}+2 x \delta x+\delta x^{2}}-e^{x^{2}}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{e^{x^{2}}\left[e^{2 x \delta x+\delta x^{2}}-1\right]}{\delta x} \\
&= e^{x^{2}} \cdot \lim _{\delta x \rightarrow 0} \frac{e^{2 x \delta x+\delta x^{2}}-1}{2 x \delta x+\delta x^{2}} \times \frac{2 x \delta x+\delta x^{2}}{\delta x} \\
&= e^{x^{2}} \cdot \lim _{\delta x \rightarrow 0} \frac{e^{2 x \delta x+\delta x^{2}}-1}{2 x \delta x+\delta x^{2}} \cdot \lim_{\delta x \to 0} (2x+\delta x)
\end{align*}
$$

Let $\theta = 2 x \delta x+\delta x^{2}$. As $\delta x \to 0$, $\theta \to 0$.

$$
\begin{align*}
&=e^{x^{2}} \cdot \lim _{\theta \rightarrow 0}\left(\frac{e^{\theta}-1}{\theta}\right) \cdot \lim _{\delta x \rightarrow 0}(2 x+\delta x) \\
&= e^{x^{2}} \times 1 \times 2 x=2 x e^{x^{2}} \quad\left[\because \lim _{\theta \rightarrow 0}\left(\frac{e^{\theta}-1}{\theta}\right)=1\right]
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(e^{x^{2}}\right)=2 x e^{x^{2}}$.**

---

### Example: Find the derivative of $e^{\sin x}$ from the first principle.

#### Solution:

Let $y=e^{\sin x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{e^{\sin (x+\delta x)}-e^{\sin x}}{\delta x} = \lim _{\delta x \rightarrow 0} \frac{e^{\sin x} \cdot\left[e^{\sin (x+\delta x)-\sin x}-1\right]}{\delta x} \\
&= e^{\sin x} \cdot \lim _{\delta x \rightarrow 0} \frac{e^{\sin (x+\delta x)-\sin x}-1}{\sin (x+\delta x)-\sin x} \cdot \frac{\sin (x+\delta x)-\sin x}{\delta x}
\end{align*}
$$

Let $\theta=\sin (x+\delta x)-\sin x$. As $\delta x \rightarrow 0$, $\theta \rightarrow 0$.

$$
\begin{align*}
&= e^{\sin x} \cdot \lim _{\theta \rightarrow 0}\left(\frac{e^{\theta}-1}{\theta}\right) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin (x+\delta x)-\sin x}{\delta x} \\
&= e^{\sin x} \cdot 1 \cdot \lim _{\delta x \rightarrow 0} \frac{2 \cos \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\delta x} \\
&= e^{\sin x} \cdot \lim _{\delta x \rightarrow 0} \cos \left(x+\frac{\delta x}{2}\right) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin \left(\frac{\delta x}{2}\right)}{\left(\frac{\delta x}{2}\right)} \\
&= e^{\sin x} \cdot \cos x \cdot 1=e^{\sin x} \cos x
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(e^{\sin x}\right)=e^{\sin x} \cos x$.**

---

### Example: Differentiate each of the following from the first principle.
1. $\sqrt{\sin x}$
2. $\sqrt{\cos x}$
3. $\sqrt{\tan x}$
4. $\sqrt{\operatorname{cosec} x}$

#### Solution:

(i) Let $y=\sqrt{\sin x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\sin (x+\delta x)}-\sqrt{\sin x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\sin (x+\delta x)}-\sqrt{\sin x}}{\delta x} \times \frac{\sqrt{\sin (x+\delta x)}+\sqrt{\sin x}}{\sqrt{\sin (x+\delta x)}+\sqrt{\sin x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin (x+\delta x)-\sin x}{\delta x \cdot\{\sqrt{\sin (x+\delta x)}+\sqrt{\sin x}\}} \\
&= \lim _{\delta x \rightarrow 0} \frac{2 \cos \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\delta x \cdot\{\sqrt{\sin (x+\delta x)}+\sqrt{\sin x}\}} \\
&= \lim _{\delta x \rightarrow 0} \cos \left(x+\frac{\delta x}{2}\right) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin \left(\frac{\delta x}{2}\right)}{\left(\frac{\delta x}{2}\right)} \cdot \lim _{\delta x \rightarrow 0} \frac{1}{\sqrt{\sin (x+\delta x)}+\sqrt{\sin x}} \\
&= \cos x \cdot 1 \cdot \frac{1}{2\sqrt{\sin x}} = \frac{\cos x}{2\sqrt{\sin x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\sqrt{\sin x})=\frac{\cos x}{2\sqrt{\sin x}}$.**

(ii) Let $y=\sqrt{\cos x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\cos (x+\delta x)}-\sqrt{\cos x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\cos (x+\delta x)}-\sqrt{\cos x}}{\delta x} \times \frac{\sqrt{\cos (x+\delta x)}+\sqrt{\cos x}}{\sqrt{\cos (x+\delta x)}+\sqrt{\cos x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{\cos (x+\delta x)-\cos x}{\delta x \cdot\{\sqrt{\cos (x+\delta x)}+\sqrt{\cos x}\}} \\
&= \lim _{\delta x \rightarrow 0} \frac{-2 \sin \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\delta x \cdot\{\sqrt{\cos (x+\delta x)}+\sqrt{\cos x}\}} \\
&= -\lim _{\delta x \rightarrow 0} \sin \left(x+\frac{\delta x}{2}\right) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin (\delta x / 2)}{(\delta x / 2)} \cdot \lim _{\delta x \rightarrow 0} \frac{1}{\sqrt{\cos (x+\delta x)}+\sqrt{\cos x}} \\
&= (-\sin x) \times 1 \times \frac{1}{2 \sqrt{\cos x}}=\frac{-\sin x}{2 \sqrt{\cos x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\sqrt{\cos x})=\frac{-\sin x}{2 \sqrt{\cos x}}$.**

(iii) Let $y=\sqrt{\tan x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\tan (x+\delta x)}-\sqrt{\tan x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\tan (x+\delta x)-\tan x}{\delta x[\sqrt{\tan (x+\delta x)}+\sqrt{\tan x}]} \\
&= \lim _{\delta x \rightarrow 0} \frac{\frac{\sin (x+\delta x)}{\cos (x+\delta x)}-\frac{\sin x}{\cos x}}{\delta x[\sqrt{\tan (x+\delta x)}+\sqrt{\tan x}]} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin (x+\delta x-x)}{\cos (x+\delta x) \cos x \cdot \delta x \cdot[\sqrt{\tan (x+\delta x)}+\sqrt{\tan x}]} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x} \cdot \frac{1}{\cos (x+\delta x) \cos x \cdot[\sqrt{\tan (x+\delta x)}+\sqrt{\tan x}]} \\
&= 1 \cdot \frac{1}{\cos x \cdot \cos x \cdot [\sqrt{\tan x}+\sqrt{\tan x}]} = \frac{1}{\cos^2 x \cdot 2\sqrt{\tan x}} = \frac{\sec ^{2} x}{2 \sqrt{\tan x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\sqrt{\tan x})=\frac{\sec ^{2} x}{2 \sqrt{\tan x}}$.**

(iv) Let $y=\sqrt{\operatorname{cosec} x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\operatorname{cosec}(x+\delta x)}-\sqrt{\operatorname{cosec} x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\frac{1}{\sqrt{\sin (x+\delta x)}}-\frac{1}{\sqrt{\sin x}}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sqrt{\sin x}-\sqrt{\sin (x+\delta x)}}{\delta x \cdot \sqrt{\sin (x+\delta x)} \cdot \sqrt{\sin x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin x-\sin (x+\delta x)}{\delta x \cdot \sqrt{\sin(x+\delta x)\sin x} \cdot [\sqrt{\sin x}+\sqrt{\sin (x+\delta x)}]} \\
&= \lim _{\delta x \rightarrow 0} \frac{-2 \cos \left(x+\frac{\delta x}{2}\right) \sin \left(\frac{\delta x}{2}\right)}{\delta x \cdot \sqrt{\sin(x+\delta x)\sin x} \cdot [\sqrt{\sin x}+\sqrt{\sin (x+\delta x)}]} \\
&= -\lim_{\delta x \to 0} \cos\left(x+\frac{\delta x}{2}\right) \cdot \lim_{\delta x \to 0}\frac{\sin(\delta x/2)}{(\delta x/2)} \cdot \frac{1}{\sqrt{\sin(x+\delta x)\sin x}[\sqrt{\sin x}+\sqrt{\sin(x+\delta x)}]} \\
&= -\cos x \cdot 1 \cdot \frac{1}{\sqrt{\sin x \cdot \sin x}[\sqrt{\sin x}+\sqrt{\sin x}]} \\
&= \frac{-\cos x}{\sin x \cdot 2\sqrt{\sin x}} = -\cot x \cdot \frac{1}{2\sqrt{\sin x}} = -\frac{1}{2} \cot x \sqrt{\operatorname{cosec} x}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\sqrt{\operatorname{cosec} x})=-\frac{1}{2} \cot x \sqrt{\operatorname{cosec} x}$.**

---

### Example: Differentiate each of the following from the first principle.
1. $\sin \sqrt{x}$
2. $\cos \sqrt{x}$
3. $\tan \sqrt{x}$

#### Solution:

(i) Let $y=\sin \sqrt{x}$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{\sin \sqrt{x+\delta x}-\sin \sqrt{x}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{2 \cos \left(\frac{\sqrt{x+\delta x}+\sqrt{x}}{2}\right) \sin \left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)}{x+\delta x-x} \\
&= \lim _{\delta x \rightarrow 0} \frac{2 \cos \left(\frac{\sqrt{x+\delta x}+\sqrt{x}}{2}\right) \sin \left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)}{(\sqrt{x+\delta x}-\sqrt{x})(\sqrt{x+\delta x}+\sqrt{x})} \\
&= \lim _{\delta x \rightarrow 0} \cos \left(\frac{\sqrt{x+\delta x}+\sqrt{x}}{2}\right) \cdot \frac{\sin \left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)}{\left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)} \cdot \frac{1}{(\sqrt{x+\delta x}+\sqrt{x})} \\
&= \cos\left(\frac{2\sqrt{x}}{2}\right) \cdot 1 \cdot \frac{1}{2\sqrt{x}} = \frac{\cos \sqrt{x}}{2 \sqrt{x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\sin \sqrt{x})=\frac{\cos \sqrt{x}}{2 \sqrt{x}}$.**

(ii) Let $y=\cos \sqrt{x}$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\cos \sqrt{x+\delta x}-\cos \sqrt{x}}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{-2 \sin \left(\frac{\sqrt{x+\delta x}+\sqrt{x}}{2}\right) \sin \left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)}{(\sqrt{x+\delta x}-\sqrt{x})(\sqrt{x+\delta x}+\sqrt{x})} \\
&=-\lim _{\delta x \rightarrow 0} \sin \left(\frac{\sqrt{x+\delta x}+\sqrt{x}}{2}\right) \cdot \frac{\sin \left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)}{\left(\frac{\sqrt{x+\delta x}-\sqrt{x}}{2}\right)} \cdot \frac{1}{(\sqrt{x+\delta x}+\sqrt{x})} \\
&=-\sin \left(\frac{2 \sqrt{x}}{2}\right) \times 1 \times \frac{1}{2 \sqrt{x}}=\frac{-\sin \sqrt{x}}{2 \sqrt{x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\cos \sqrt{x})=\frac{-\sin \sqrt{x}}{2 \sqrt{x}}$.**

(iii) Let $y=\tan \sqrt{x}$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\tan \sqrt{x+\delta x}-\tan \sqrt{x}}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{\sin \sqrt{x+\delta x} \cos \sqrt{x}-\cos \sqrt{x+\delta x} \sin \sqrt{x}}{\delta x \cdot \cos \sqrt{x+\delta x} \cdot \cos \sqrt{x}} \\
&=\lim _{\delta x \rightarrow 0} \frac{\sin (\sqrt{x+\delta x}-\sqrt{x})}{(x+\delta x)-x} \cdot \frac{1}{\cos \sqrt{x+\delta x} \cdot \cos \sqrt{x}} \\
&=\lim _{\delta x \rightarrow 0} \frac{\sin (\sqrt{x+\delta x}-\sqrt{x})}{(\sqrt{x+\delta x}-\sqrt{x})(\sqrt{x+\delta x}+\sqrt{x})} \cdot \frac{1}{\cos \sqrt{x+\delta x} \cdot \cos \sqrt{x}} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin (\sqrt{x+\delta x}-\sqrt{x})}{(\sqrt{x+\delta x}-\sqrt{x})} \cdot \frac{1}{(\sqrt{x+\delta x}+\sqrt{x})} \cdot \frac{1}{\cos \sqrt{x+\delta x} \cos \sqrt{x}} \\
&= 1 \cdot \frac{1}{2\sqrt{x}} \cdot \frac{1}{\cos^2\sqrt{x}} = \frac{\sec ^{2} \sqrt{x}}{2 \sqrt{x}}
\end{align*}
$$

**Hence, $\frac{d}{d x}(\tan \sqrt{x})=\frac{\sec ^{2} \sqrt{x}}{2 \sqrt{x}}$.**

---

### Example: Find the derivative of the following from the first principle.
1. $\sin ^{2} x$
2. $\cos ^{2} x$

#### Solution:

(i) Let $y=\sin ^{2} x$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\sin ^{2}(x+\delta x)-\sin ^{2} x}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{\sin (x+\delta x+x) \sin (x+\delta x-x)}{\delta x} \quad\left[\because \sin ^{2} A-\sin ^{2} B=\sin (A+B) \cdot \sin (A-B)\right] \\
&=\lim _{\delta x \rightarrow 0} \frac{\sin (2 x+\delta x) \sin \delta x}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \sin (2 x+\delta x) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x} \\
&=(\sin 2 x \times 1)=\sin 2 x
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\sin ^{2} x\right)=\sin 2 x$.**

(ii) Let $y=\cos ^{2} x$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\cos ^{2}(x+\delta x)-\cos ^{2} x}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{(1-\sin^2(x+\delta x)) - (1-\sin^2 x)}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{\sin^2 x - \sin^2(x+\delta x)}{\delta x} \\
&= -\lim _{\delta x \rightarrow 0} \frac{\sin(x+x+\delta x)\sin(x+\delta x-x)}{\delta x} \\
&= -\lim _{\delta x \rightarrow 0} \frac{\sin(2x+\delta x)\sin(\delta x)}{\delta x} \\
&= -\lim _{\delta x \rightarrow 0} \sin(2x+\delta x) \cdot \lim _{\delta x \rightarrow 0} \frac{\sin \delta x}{\delta x} \\
&= -(\sin 2x \times 1) = -\sin 2x
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\cos ^{2} x\right)=-\sin 2 x$.**

---

### Example: Find the derivative of the following from the first principle:
1. $\sin x^{2}$
2. $\cos \left(x^{2}+1\right)$
3. $\tan x^{2}$

#### Solution:

(i) Let $y=\sin x^{2}$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\sin (x+\delta x)^{2}-\sin x^{2}}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{2 \cos \left(\frac{(x+\delta x)^{2}+x^{2}}{2}\right) \sin \left(\frac{(x+\delta x)^{2}-x^{2}}{2}\right)}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{2 \cos \left(\frac{x^2+2x\delta x+\delta x^2+x^2}{2}\right) \sin \left(\frac{2x\delta x+\delta x^2}{2}\right)}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} 2 \cos \left(x^2+x\delta x+\frac{\delta x^2}{2}\right) \frac{\sin \left(x\delta x + \frac{\delta x^2}{2}\right)}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} 2 \cos \left(x^2+x\delta x+\frac{\delta x^2}{2}\right) \frac{\sin \left(\delta x(x+\frac{\delta x}{2})\right)}{\delta x(x+\frac{\delta x}{2})} \cdot \left(x+\frac{\delta x}{2}\right) \\
&= 2 \cos(x^2) \cdot 1 \cdot x = 2x \cos x^2
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\sin x^{2}\right)=2 x \cos x^{2}$.**

(ii) Let $y=\cos \left(x^{2}+1\right)$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\cos \left[(x+\delta x)^{2}+1\right]-\cos \left(x^{2}+1\right)}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{-2 \sin \left(\frac{(x+\delta x)^2+1+x^2+1}{2}\right) \sin \left(\frac{(x+\delta x)^2+1-(x^2+1)}{2}\right)}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{-2 \sin \left(x^2+x\delta x+\frac{\delta x^2}{2}+1\right) \sin \left(x\delta x+\frac{\delta x^2}{2}\right)}{\delta x} \\
&= -2 \lim_{\delta x \to 0} \sin \left(x^2+x\delta x+\frac{\delta x^2}{2}+1\right) \cdot \lim_{\delta x \to 0} \frac{\sin \left(\delta x(x+\frac{\delta x}{2})\right)}{\delta x(x+\frac{\delta x}{2})} \cdot \left(x+\frac{\delta x}{2}\right) \\
&= -2 \sin(x^2+1) \cdot 1 \cdot x = -2x \sin(x^2+1)
\end{align*}
$$

**Hence, $\frac{d}{d x}\left[\cos \left(x^{2}+1\right)\right]=-2 x \sin \left(x^{2}+1\right)$.**

(iii) Let $y=\tan x^{2}$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{\tan (x+\delta x)^{2}-\tan x^{2}}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin \left((x+\delta x)^2 - x^2\right)}{\delta x \cdot \cos(x+\delta x)^2 \cdot \cos x^2} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin (2x\delta x + \delta x^2)}{\delta x \cdot \cos(x+\delta x)^2 \cdot \cos x^2} \\
&= \lim _{\delta x \rightarrow 0} \frac{\sin (\delta x(2x+\delta x))}{\delta x(2x+\delta x)} \cdot \frac{(2x+\delta x)}{\cos(x+\delta x)^2 \cdot \cos x^2} \\
&= 1 \cdot \frac{2x}{\cos(x^2) \cdot \cos(x^2)} = \frac{2x}{\cos^2 x^2} = 2x \sec^2 x^2
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(\tan x^{2}\right)=2 x \sec ^{2} x^{2}$.**

---

### Example: Differentiate $x e^{x}$ from the first principle.

#### Solution:

Let $y=x e^{x}$.

$$
\begin{align*}
\frac{d y}{d x} &=\lim _{\delta x \rightarrow 0} \frac{(x+\delta x) e^{x+\delta x}-x e^{x}}{\delta x} \\
&=\lim _{\delta x \rightarrow 0} \frac{x e^{x+\delta x}+\delta x e^{x+\delta x}-x e^{x}}{\delta x} \\
&=\lim _{\delta x \rightarrow 0}\left[\frac{x e^{x}(e^{\delta x}-1)}{\delta x}+\frac{\delta x e^{x+\delta x}}{\delta x}\right] \\
&=x e^{x} \cdot \lim _{\delta x \rightarrow 0}\left(\frac{e^{\delta x}-1}{\delta x}\right)+\lim _{\delta x \rightarrow 0} e^{x+\delta x} \\
&= (x e^{x} \times 1)+e^{x} \quad\left[\because \lim _{\delta x \rightarrow 0}\left(\frac{e^{\delta x}-1}{\delta x}\right)=1\right] \\
&= (x+1) e^{x}
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(x e^{x}\right)=(x+1) e^{x}$.**

---

### Example: Differentiate $x^{2} \cos x$ from the first principle.

#### Solution:

Let $y=x^{2} \cos x$.

$$
\begin{align*}
\frac{d y}{d x} &= \lim _{\delta x \rightarrow 0} \frac{(x+\delta x)^{2} \cos (x+\delta x)-x^{2} \cos x}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{(x^{2}+2x\delta x+\delta x^2) \cos (x+\delta x)-x^{2} \cos x}{\delta x} \\
&= \lim _{\delta x \rightarrow 0} \frac{x^2(\cos(x+\delta x)-\cos x) + (2x\delta x+\delta x^2)\cos(x+\delta x)}{\delta x} \\
&= \lim_{\delta x \to 0} \frac{x^2(-2\sin(x+\frac{\delta x}{2})\sin(\frac{\delta x}{2}))}{\delta x} + \lim_{\delta x \to 0} (2x+\delta x)\cos(x+\delta x) \\
&= \lim_{\delta x \to 0} -x^2 \sin(x+\frac{\delta x}{2}) \frac{\sin(\delta x/2)}{(\delta x/2)} + \lim_{\delta x \to 0} (2x+\delta x)\cos(x+\delta x) \\
&= -x^2 \sin(x) \cdot 1 + (2x)\cos(x) \\
&= -x^2 \sin x + 2x \cos x
\end{align*}
$$

**Hence, $\frac{d}{d x}\left(x^{2} \cos x\right)=\left(2x \cos x-x^{2} \sin x\right)$.**

---

