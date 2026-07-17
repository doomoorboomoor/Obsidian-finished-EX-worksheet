## 6. Differentiation Using Logarithms

When the given function is a power of some expression or a product of expressions, then we take the **logarithm on both sides** and differentiate termwise, as shown below.

## SOLVED EXAMPLES

### Example 1:
If $y=\sqrt{\frac{(x-3)\left(x^{2}+4\right)}{\left(3 x^{2}+4 x+5\right)}}$, find $\frac{d y}{d x}$.
[CBSE 2006]

#### Solution:
Given: $y=\sqrt{\frac{(x-3)\left(x^{2}+4\right)}{\left(3 x^{2}+4 x+5\right)}}$.

Taking logarithm on both sides of (i), we get

$$
\log y=\frac{1}{2}\left\{\log (x-3)+\log \left(x^{2}+4\right)-\log \left(3 x^{2}+4 x+5\right)\right\} .
$$

Differentiating both sides w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x} & =\frac{1}{2} \cdot\left\{\frac{1}{(x-3)}+\frac{2 x}{\left(x^{2}+4\right)}-\frac{(6 x+4)}{\left(3 x^{2}+4 x+5\right)}\right\} \\
\Rightarrow \frac{d y}{d x} & =\left(\frac{1}{2} y\right) \cdot\left\{\frac{1}{(x-3)}+\frac{2 x}{\left(x^{2}+4\right)}-\frac{(6 x+4)}{\left(3 x^{2}+4 x+5\right)}\right\} \\
& =\frac{1}{2} \cdot \sqrt{\frac{(x-3)\left(x^{2}+4\right)}{\left(3 x^{2}+4 x+5\right)}} \cdot\left\{\frac{1}{(x-3)}+\frac{2 x}{\left(x^{2}+4\right)}-\frac{(6 x+4)}{\left(3 x^{2}+4 x+5\right)}\right\}
\end{aligned}
$$

---

### Example 2:
If $y=\frac{\sqrt{x}(x+4)^{3 / 2}}{(4 x-3)^{4 / 3}}$, find $\frac{d y}{d x}$.

#### Solution:
Given: $y=\frac{\sqrt{x}(x+4)^{3 / 2}}{(4 x-3)^{4 / 3}}$.

Taking logarithm on both sides of (i), we get

$$
\log y=\frac{1}{2} \log x+\frac{3}{2} \log (x+4)-\frac{4}{3} \log (4 x-3) .
$$

On differentiating both sides w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x} & =\frac{1}{2} \cdot \frac{1}{x}+\frac{3}{2} \cdot \frac{1}{(x+4)}-\frac{4}{3} \cdot \frac{4}{(4 x-3)} \\
\Rightarrow \quad \frac{d y}{d x} & =y\left[\frac{1}{2 x}+\frac{3}{2(x+4)}-\frac{16}{3(4 x-3)}\right] \\
& =\frac{\sqrt{x}(x+4)^{3 / 2}}{(4 x-3)^{4 / 3}} \cdot\left[\frac{1}{2 x}+\frac{3}{2(x+4)}-\frac{16}{3(4 x-3)}\right] .
\end{aligned}
$$

---

### Example 3:
Differentiate $(x+1)^{2}(x+2)^{3}(x+3)^{4}$ w.r.t. $x$.

#### Solution:
Let $y=(x+1)^{2}(x+2)^{3}(x+3)^{4}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=2 \log (x+1)+3 \log (x+2)+4 \log (x+3) \tag{ii}
\end{equation*}
$$

Differentiating both sides of (ii) w.r.t. $x$, we get

$$
\frac{1}{y} \cdot \frac{d y}{d x}=\frac{2}{(x+1)}+\frac{3}{(x+2)}+\frac{4}{(x+3)}
$$

$$
\begin{aligned}
\Rightarrow \frac{d y}{d x} & =y \cdot\left[\frac{2}{(x+1)}+\frac{3}{(x+2)}+\frac{4}{(x+3)}\right] \\
& =(x+1)^{2}(x+2)^{3}(x+3)^{4} \cdot\left[\frac{2}{(x+1)}+\frac{3}{(x+2)}+\frac{4}{(x+3)}\right]
\end{aligned}
$$

---

### Example 4:
Differentiate $\sqrt{(x-1)(x-2)(x-3)(x-4)}$ w.r.t. $x$.

#### Solution:
Let $y=\sqrt{(x-1)(x-2)(x-3)(x-4)}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=\frac{1}{2}\{\log (x-1)+\log (x-2)+\log (x-3)+\log (x-4)\} \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$ we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x}=\frac{1}{2} \cdot\left\{\frac{1}{(x-1)}+\frac{1}{(x-2)}+\frac{1}{(x-3)}+\frac{1}{(x-4)}\right\} \\
\Rightarrow \frac{d y}{d x}=\left(\frac{y}{2}\right) \cdot\left\{\frac{1}{(x-1)}+\frac{1}{(x-2)}+\frac{1}{(x-3)}+\frac{1}{(x-4)}\right\} \\
=\frac{1}{2} \cdot \sqrt{(x-1)(x-2)(x-3)(x-4)} \\
\cdot\left\{\frac{1}{(x-1)}+\frac{1}{(x-2)}+\frac{1}{(x-3)}+\frac{1}{(x-4)}\right\}
\end{aligned}
$$

---

### Example 5:
Differentiate $\left(e^{x} \cos ^{3} x \sin ^{2} x\right)$ w.r.t. $x$.

#### Solution:
Let $y=e^{x} \cos ^{3} x \sin ^{2} x$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=x+3 \log \cos x+2 \log \sin x \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} & \cdot \frac{d y}{d x}=1+\frac{3}{\cos x} \cdot(-\sin x)+\frac{2}{\sin x} \cdot \cos x \\
\Rightarrow \frac{d y}{d x} & =y \cdot\{1-3 \tan x+2 \cot x\} \\
& =\left(e^{x} \cos ^{3} x \sin ^{2} x\right)(1-3 \tan x+2 \cot x)
\end{aligned}
$$

---

### Example 6:
Differentiate ( $\tan x \tan 2 x \tan 3 x \tan 4 x$ ) w.r.t. $x$.

#### Solution:
Let $y=\tan x \tan 2 x \tan 3 x \tan 4 x$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=\log \tan x+\log \tan 2 x+\log \tan 3 x+\log \tan 4 x \tag{ii}
\end{equation*}
$$

On diffferentiating both sides of (ii) w.r.t. $x$, we get

$$
\frac{1}{y} \cdot \frac{d y}{d x}=\left\{\frac{\sec ^{2} x}{\tan x}+\frac{2 \sec ^{2} 2 x}{\tan 2 x}+\frac{3 \sec ^{2} 3 x}{\tan 3 x}+\frac{4 \sec ^{2} 4 x}{\tan 4 x}\right\}
$$

$$
\begin{aligned}
\Rightarrow \frac{d y}{d x}= & y \cdot\left[\frac{1}{\sin x \cos x}+\frac{2}{\sin 2 x \cos 2 x}\right. \\
& \left.\quad+\frac{3}{\sin 3 x \cos 3 x}+\frac{4}{\sin 4 x \cos 4 x}\right] \\
= & y \cdot\left[\frac{2}{\sin 2 x}+\frac{4}{\sin 4 x}+\frac{6}{\sin 6 x}+\frac{8}{\sin 8 x}\right] \\
= & {[2 \tan x \tan 2 x \tan 3 x \tan 4 x] } \\
& \quad \times[\operatorname{cosec} 2 x+2 \operatorname{cosec} 4 x+3 \operatorname{cosec} 6 x+4 \operatorname{cosec} 8 x]
\end{aligned}
$$

---

### Example 7:
If $y=(2 x+3)^{(3 x-5)}$, find $\frac{d y}{d x}$.

#### Solution:
Given: $y=(2 x+3)^{(3 x-5)}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=(3 x-5) \log (2 x+3) \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{1}{y} \cdot \frac{d y}{d x}=(3 x-5) \cdot \frac{d}{d x}\{\log (2 x+3)\}+\log (2 x+3) \cdot \frac{d}{d x}(3 x-5) \\
&=(3 x-5) \cdot \frac{1}{(2 x+3)} \cdot 2+\log (2 x+3) \cdot 3 \\
& \Rightarrow \frac{d y}{d x}=y \cdot\left\{\frac{(6 x-10)}{(2 x+3)}+3 \log (2 x+3)\right\} \\
& \Rightarrow \frac{d y}{d x}=(2 x+3)^{(3 x-5)} \cdot\left\{\frac{(6 x-10)}{(2 x+3)}+3 \log (2 x+3)\right\} .
\end{aligned}
$$

---

### Example 8:
If $y=\frac{5^{x}}{x^{5}}$, find $\frac{d y}{d x}$.

#### Solution:
Given: $y=\frac{5^{x}}{x^{5}}$.

Taking logarithm on both sides of (i), we get

$$
\begin{aligned}
& \log y=\log \left(5^{x}\right)-\log \left(x^{5}\right) \\
\Rightarrow & \log y=x \log 5-5 \log x \\
\Rightarrow & \frac{1}{y} \cdot \frac{d y}{d x}=(\log 5) \cdot 1-\frac{5}{x} \quad \text { [differentiating both sides w.r.t. } x \text { ] } \\
\Rightarrow & \frac{d y}{d x}=y\left(\log 5-\frac{5}{x}\right) \\
\Rightarrow & \frac{d y}{d x}=\frac{5^{x}}{x^{5}}\left(\log 5-\frac{5}{x}\right)
\end{aligned}
$$

---

### Example 9:
Differentiate $x^{x}$ w.r.t. $x$.

#### Solution:
Let $y=x^{x}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=x \log x \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x} & =x \cdot \frac{d}{d x}(\log x)+\log x \cdot \frac{d}{d x}(x) \\
& =\left(x \cdot \frac{1}{x}+\log x \cdot 1\right)=(1+\log x) \\
\Rightarrow \frac{d y}{d x} & =y(1+\log x) \\
\Rightarrow \frac{d y}{d x} & =x^{x}(1+\log x) .
\end{aligned}
$$

---

### Example 10:
Differentiate $(\sin x)^{x}$ w.r.t. $x$.

#### Solution:
Let $y=(\sin x)^{x}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=x \log (\sin x) \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x} & =x \cdot \frac{d}{d x}\{\log (\sin x)\}+\log (\sin x) \cdot \frac{d}{d x}(x) \\
& =x \cdot \frac{1}{\sin x} \cdot \cos x+\log (\sin x) \cdot 1 \\
& =x \cot x+\log (\sin x) \\
\Rightarrow \frac{d y}{d x}=y \cdot & {[x \cot x+\log (\sin x)] } \\
\Rightarrow \frac{d y}{d x}= & (\sin x)^{x}[x \cot x+\log (\sin x)]
\end{aligned}
$$

---

### Example 11:
Differentiate $x^{\sin ^{-1} x}$ w.r.t. $x$.
[CBSE 2000]

#### Solution:
Let $y=x^{\sin ^{-1} x}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=\left(\sin ^{-1} x\right)(\log x) \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x} & =\left(\sin ^{-1} x\right) \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}\left(\sin ^{-1} x\right) \\
& =\left(\sin ^{-1} x\right) \frac{1}{x}+(\log x) \cdot \frac{1}{\sqrt{1-x^{2}}} \\
\Rightarrow \frac{d y}{d x} & =y \cdot\left[\frac{\sin ^{-1} x}{x}+\frac{\log x}{\sqrt{1-x^{2}}}\right] \\
\Rightarrow \frac{d y}{d x} & =x^{\sin ^{-1} x} \cdot\left\{\frac{\sin ^{-1} x}{x}+\frac{\log x}{\sqrt{1-x^{2}}}\right\}
\end{aligned}
$$

---

### Example 12:
Differentiate $(\sin x)^{\log x}$ w.r.t. $x$.

#### Solution:
Let $y=(\sin x)^{\log x}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=(\log x)(\log \sin x) . \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{1}{y} \cdot \frac{d y}{d x}=(\log x) \cdot \frac{d}{d x}(\log \sin x)+(\log \sin x) \cdot \frac{d}{d x}(\log x) \\
&=(\log x) \cdot \frac{1}{\sin x} \cdot \cos x+(\log \sin x) \cdot \frac{1}{x} \\
&=(\log x) \cot x+\frac{(\log \sin x)}{x} \\
& \Rightarrow \frac{d y}{d x}=y \cdot\left[(\log x) \cot x+\frac{(\log \sin x)}{x}\right] \\
& \Rightarrow \frac{d y}{d x}=(\sin x)^{\log x} \cdot\left[(\log x) \cot x+\frac{(\log \sin x)}{x}\right]
\end{aligned}
$$

---

### Example 13:
Differentiate $x^{x} \sin ^{-1} \sqrt{x}$ w.r.t. $x$.
[CBSE 2005C]

#### Solution:
Let $y=x^{x} \sin ^{-1} \sqrt{x}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=x \log x+\log \left(\sin ^{-1} \sqrt{x}\right) \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{1}{y} \cdot \frac{d y}{d x}=\frac{d}{d x}(x \log x)+\frac{d}{d x}\left\{\log \left(\sin ^{-1} \sqrt{x}\right)\right\} \\
&=\left(x \cdot \frac{1}{x}+\log x \cdot 1\right)+\frac{1}{\sin ^{-1} \sqrt{x}} \cdot \frac{1}{\sqrt{1-x}} \cdot \frac{1}{2} x^{-1 / 2} \\
&=\left\{(1+\log x)+\frac{1}{2\left(\sqrt{x-x^{2}}\right) \sin ^{-1} \sqrt{x}}\right\} \\
& \Rightarrow \frac{d y}{d x}=y \cdot\left\{(1+\log x)+\frac{1}{2\left(\sqrt{x-x^{2}}\right) \sin ^{-1} \sqrt{x}}\right\} \\
&=\left(x^{x} \sin ^{-1} \sqrt{x}\right)\left\{(1+\log x)+\frac{1}{2\left(\sqrt{x-x^{2}}\right) \sin ^{-1} \sqrt{x}}\right\} \\
&=\left\{\left(x^{x} \sin ^{-1} \sqrt{x}\right)(1+\log x)+\frac{x^{x}}{2\left(\sqrt{x-x^{2}}\right)}\right\}
\end{aligned}
$$

---

### Example 14:
Differentiate $\frac{e^{x^{2}} \tan ^{-1} x}{\sqrt{1+x^{2}}}$ w.r.t. $x$.

#### Solution:
Let $y=\frac{e^{x^{2}} \tan ^{-1} x}{\sqrt{1+x^{2}}}$.

Taking logarithm on both sides of (i), we get

$$
\begin{equation*}
\log y=x^{2}+\log \left(\tan ^{-1} x\right)-\frac{1}{2} \log \left(1+x^{2}\right) \tag{ii}
\end{equation*}
$$

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{1}{y} \cdot \frac{d y}{d x} & =2 x+\frac{1}{\tan ^{-1} x} \cdot \frac{1}{\left(1+x^{2}\right)}-\frac{1}{2} \cdot \frac{2 x}{\left(1+x^{2}\right)} \\
\Rightarrow \quad \frac{d y}{d x} & =y\left[2 x+\frac{1}{\left(1+x^{2}\right) \tan ^{-1} x}-\frac{x}{\left(1+x^{2}\right)}\right] \\
& =\frac{e^{x^{2}} \tan ^{-1} x}{\sqrt{1+x^{2}}} \cdot\left[2 x+\frac{1}{\left(1+x^{2}\right) \tan ^{-1} x}-\frac{x}{\left(1+x^{2}\right)}\right] .
\end{aligned}
$$

---

### Example 15:
Differentiate $\left\{x^{\tan x}+\sqrt{\frac{x^{2}+1}{x}}\right\}$ w.r.t. $x$.
[CBSE 2006C]

#### Solution:
Let $y=u+v$, where $u=x^{\tan x}$ and $v=\sqrt{\frac{x^{2}+1}{x}}$.

Now, $u=x^{\tan x}$
$\Rightarrow \log u=(\tan x)(\log x)$
$\Rightarrow \frac{1}{u} \cdot \frac{d u}{d x}=(\tan x) \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}(\tan x)$
[differentiating w.r.t. $x$ ]

$$
=(\tan x) \cdot \frac{1}{x}+(\log x) \sec ^{2} x
$$

$$
\begin{equation*}
\Rightarrow \frac{d u}{d x}=u \cdot\left[\frac{\tan x}{x}+(\log x) \sec ^{2} x\right] \tag{i}
\end{equation*}
$$

$\Rightarrow \frac{d u}{d x}=x^{\tan x} \cdot\left\{\frac{\tan x}{x}+(\log x) \sec ^{2} x\right\}$.

And, $v=\sqrt{\frac{x^{2}+1}{x}}$
$\Rightarrow \log v=\frac{1}{2} \cdot\left\{\log \left(x^{2}+1\right)-\log x\right\}$
$\Rightarrow \frac{1}{v} \cdot \frac{d v}{d x}=\frac{1}{2} \cdot\left\{\frac{2 x}{\left(x^{2}+1\right)}-\frac{1}{x}\right\}$
[differentiating w.r.t. $x$ ]

$$
\begin{equation*}
\Rightarrow \frac{d v}{d x}=\frac{v}{2} \cdot\left\{\frac{2 x^{2}-\left(x^{2}+1\right)}{x\left(x^{2}+1\right)}\right\} \tag{ii}
\end{equation*}
$$

$\Rightarrow \frac{d v}{d x}=\frac{1}{2} \sqrt{\frac{x^{2}+1}{x}} \cdot\left\{\frac{\left(x^{2}-1\right)}{x\left(x^{2}+1\right)}\right\}$.
$\therefore \quad y=u+v$
$\Rightarrow \frac{d y}{d x}=\frac{d u}{d x}+\frac{d v}{d x}$

$$
\Rightarrow \frac{d y}{d x}=x^{\tan x} \cdot\left\{\frac{\tan x}{x}+(\log x) \sec ^{2} x\right\}+\frac{1}{2} \cdot \sqrt{\frac{x^{2}+1}{x}} \cdot\left\{\frac{\left(x^{2}-1\right)}{x\left(x^{2}+1\right)}\right\} .
$$

### Example 16:
If $y=(x)^{\cos x}+(\cos x)^{\sin x}$, find $\frac{d y}{d x}$.
[CBSE 2005C, '06, '09]

#### Solution:
Let $y=u+v$, where $u=(x)^{\cos x}$ and $v=(\cos x)^{\sin x}$.

Now, $u=(x)^{\cos x}$
$\Rightarrow \log u=(\cos x)(\log x)$
$\Rightarrow \frac{1}{u} \cdot \frac{d u}{d x}=(\cos x) \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}(\cos x)$
[on differentiating w.r.t. $x$ ]

$$
=(\cos x) \cdot \frac{1}{x}+(\log x)(-\sin x)
$$

$\Rightarrow \frac{d u}{d x}=u \cdot\left\{\frac{\cos x}{x}-(\log x)(\sin x)\right\}$

$$
\begin{equation*}
\Rightarrow \frac{d u}{d x}=(x)^{\cos x}\left\{\frac{\cos x}{x}-(\log x)(\sin x)\right\} . \tag{i}
\end{equation*}
$$

And, $v=(\cos x)^{\sin x}$
$\Rightarrow \log v=(\sin x) \log (\cos x)$
$\Rightarrow \frac{1}{v} \cdot \frac{d v}{d x}=(\sin x) \cdot \frac{d}{d x}\{\log (\cos x)\}+\log (\cos x) \cdot \frac{d}{d x}(\sin x)$
[on differentiating w.r.t. $x$ ]
$\Rightarrow \frac{d v}{d x}=v \cdot\left\{(\sin x) \cdot \frac{(-\sin x)}{\cos x}+\log (\cos x) \cdot \cos x\right\}$

$$
\begin{equation*}
\Rightarrow \frac{d v}{d x}=(\cos x)^{\sin x} \cdot\{-\sin x \tan x+\cos x \cdot \log (\cos x)\} . \tag{ii}
\end{equation*}
$$

$\therefore \quad y=(u+v)$
$\Rightarrow \frac{d y}{d x}=\frac{d u}{d x}+\frac{d v}{d x}$
$\Rightarrow \frac{d y}{d x}=(x)^{\cos x} \cdot\left\{\frac{\cos x}{x}-(\log x) \sin x\right\}$

$$
+(\cos x)^{\sin x} \cdot\{-\sin x \tan x+\cos x \cdot \log (\cos x)\} .
$$

---

### Example 17:
If $y=(\sin x)^{\tan x}+(\cos x)^{\sec x}$, find $\frac{d y}{d x}$.

#### Solution:
Let $y=u+v$, where $u=(\sin x)^{\tan x}$ and $v=(\cos x)^{\sec x}$.

Now, $u=(\sin x)^{\tan x}$
$\Rightarrow \log u=(\tan x)(\log \sin x)$

$$
\begin{align*}
& \begin{aligned}
\Rightarrow \frac{1}{u} \cdot \frac{d u}{d x} & =(\tan x) \cdot \frac{d}{d x}(\log \sin x)+(\log \sin x) \cdot \frac{d}{d x}(\tan x) \\
& \quad[\text { on differentiating w.r.t. } x]
\end{aligned} \\
& \quad=(\tan x) \cdot \frac{1}{\sin x} \cdot \cos x+(\log \sin x) \cdot \sec ^{2} x \\
& \Rightarrow \frac{d u}{d x}=u\left[1+(\log \sin x) \sec ^{2} x\right] \\
& \Rightarrow \frac{d u}{d x}=(\sin x)^{\tan x} \cdot\left\{1+(\log \sin x) \sec ^{2} x\right\} . \\
& \begin{aligned}
\text { And, } v= & (\cos x)^{\sec x} \\
\Rightarrow & \log v= \\
\Rightarrow & \frac{1}{v} \cdot \frac{d v}{d x}=(\sec x) \cdot \log (\cos x) \cdot \frac{d}{d x}\{\log (\cos x)\}+\log (\cos x) \cdot \frac{d}{d x}(\sec x)
\end{aligned}  \tag{i}\\
& \quad[\operatorname{on} \operatorname{differentiating} \text { w.r.t. } x] \\
& \quad=(\sec x) \cdot \frac{1}{\cos x} \cdot(-\sin x)+\log (\cos x) \cdot \sec x \tan x \\
& \quad=(\sec x \tan x)[\log (\cos x)-1] \\
& \Rightarrow \frac{d v}{d x}=v \cdot(\sec x \tan x)[\log (\cos x)-1] \\
& \Rightarrow \frac{d v}{d x}=(\cos x)^{\sec x} \cdot(\sec x \tan x)[\log (\cos x)-1] . \\
& \begin{aligned}
\therefore \frac{d y}{d x}= & \frac{d u}{d x}+\frac{d v}{d x} \\
\Rightarrow \frac{d y}{d x}= & (\sin x)^{\tan x} \cdot\left\{1+(\log \sin x) \sec ^{2} x\right\} \\
& +(\cos x)^{\sec x} \cdot(\sec x \tan x)[\log (\cos x)-1][\text { from (i) and (ii)]. }
\end{aligned}
\end{align*}
$$

---

### Example 18:
If $x^{y}=y^{x}$, find $\frac{d y}{d x}$.

#### Solution:
Given: $x^{y}=y^{x}$
$\Rightarrow y \log x=x \log y$.
... (i)

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& y \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}(y)=x \cdot \frac{d}{d x}(\log y)+(\log y) \cdot \frac{d}{d x}(x) \\
\Rightarrow & y \cdot \frac{1}{x}+(\log x) \cdot \frac{d y}{d x}=x \cdot \frac{1}{y} \cdot \frac{d y}{d x}+(\log y) \cdot 1 \\
\Rightarrow & \left(\log x-\frac{x}{y}\right) \frac{d y}{d x}=\left(\log y-\frac{y}{x}\right) \\
\Rightarrow & \frac{(y \log x-x)}{y} \cdot \frac{d y}{d x}=\frac{(x \log y-y)}{x}
\end{aligned}
$$

$\Rightarrow \frac{d y}{d x}=\frac{y(x \log y-y)}{x(y \log x-x)}$.

---

### Example 19:
If $x^{y} \cdot y^{x}=1$, find $\frac{d y}{d x}$.

#### Solution:
Given: $x^{y} \cdot y^{x}=1$
$\Rightarrow(y \log x)+(x \log y)=0$.
... (i) $\quad[\because \log 1=0]$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& y \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}(y)+x \cdot \frac{d}{d x}(\log y)+(\log y) \cdot \frac{d}{d x}(x)=0 \\
\Rightarrow & y \cdot \frac{1}{x}+(\log x) \cdot \frac{d y}{d x}+x \cdot \frac{1}{y} \cdot \frac{d y}{d x}+(\log y) \cdot 1=0 \\
\Rightarrow & \left(\log x+\frac{x}{y}\right) \cdot \frac{d y}{d x}=-\left(\log y+\frac{y}{x}\right) \\
\Rightarrow & \frac{(y \log x+x)}{y} \cdot \frac{d y}{d x}=\frac{-(x \log y+y)}{x} \\
\Rightarrow & \frac{d y}{d x}=\frac{-y(x \log y+y)}{x(y \log x+x)}
\end{aligned}
$$

---

### Example 20:
If $x^{y}=e^{x-y}$, prove that $\frac{d y}{d x}=\frac{\log x}{(1+\log x)^{2}}$.
[CBSE 2010C]

#### Solution:
We have

$$
\begin{align*}
& x^{y}=e^{x-y} \Rightarrow y \log x=(x-y) \\
\Rightarrow & (1+\log x) y=x \\
\Rightarrow & y=\frac{x}{(1+\log x)} \tag{i}
\end{align*}
$$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
\frac{d y}{d x} & =\frac{(1+\log x) \cdot \frac{d}{d x}(x)-x \cdot \frac{d}{d x}(1+\log x)}{(1+\log x)^{2}} \\
& =\frac{(1+\log x) \cdot 1-x \cdot \frac{1}{x}}{(1+\log x)^{2}}=\frac{(1+\log x-1)}{(1+\log x)^{2}}=\frac{\log x}{(1+\log x)^{2}}
\end{aligned}
$$

---

### Example 21:
If $x^{y}+y^{x}=a^{b}$, find $\frac{d y}{d x}$.

#### Solution:
Let $u=x^{y}$ and $v=y^{x}$.

$$
\text { Then, } \begin{aligned}
u+v=a^{b} & \Rightarrow \frac{d u}{d x}+\frac{d v}{d x}=0 . \quad \ldots \text { (i) } \quad\left[\because \quad a^{b}=\text { constant] } \right. \\
\text { Now, } u=x^{y} & \Rightarrow \log u=y \log x \quad \text { [taking log on both sides] } \\
& \Rightarrow \frac{1}{u} \cdot \frac{d u}{d x}=y \cdot \frac{1}{x}+\log x \cdot \frac{d y}{d x} \quad \text { [on differentiation] }
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow \frac{d u}{d x}=u\left[\frac{y}{x}+\log x \cdot \frac{d y}{d x}\right] \\
& \Rightarrow \frac{d u}{d x}=x^{y}\left[\frac{y+x \log x \cdot \frac{d y}{d x}}{x}\right] \\
& \Rightarrow \frac{d u}{d x}=x^{y-1}\left[y+x \log x \cdot \frac{d y}{d x}\right] .
\end{aligned}
$$

And, $v=y^{x} \Rightarrow \log v=x \log y \quad$ [taking log on both sides]

$$
\begin{aligned}
& \Rightarrow \frac{1}{v} \cdot \frac{d v}{d x}=x \cdot \frac{1}{y} \cdot \frac{d y}{d x}+\log y \quad \text { [on differentiation] } \\
& \Rightarrow \frac{d v}{d x}=v \cdot\left[\frac{x}{y} \cdot \frac{d y}{d x}+\log y\right] \Rightarrow \frac{d v}{d x}=y^{x}\left\{\frac{x \cdot \frac{d y}{d x}+y \log y}{y}\right\} \\
& \Rightarrow \frac{d v}{d x}=y^{(x-1)} \cdot\left\{x \cdot \frac{d y}{d x}+y \log y\right\} .
\end{aligned}
$$

Using (i), we get $\frac{d u}{d x}+\frac{d v}{d x}=0$

$$
\begin{aligned}
& \Rightarrow x^{(y-1)}\left\{y+x \log x \cdot \frac{d y}{d x}\right\}+y^{(x-1)} \cdot\left\{x \frac{d y}{d x}+y \log y\right\}=0 \\
& \Rightarrow\left\{x^{y}(\log x)+x \cdot y^{(x-1)}\right\} \cdot \frac{d y}{d x}=-\left\{y \cdot x^{(y-1)}+y^{x}(\log y)\right\} \\
\therefore & \frac{d y}{d x}=\frac{-\left\{y \cdot x^{(y-1)}+y^{x}(\log y)\right\}}{\left\{x^{y}(\log x)+x y^{(x-1)}\right\}}
\end{aligned}
$$

---

### Example 22:
If $x^{x}+x^{y}+y^{x}=a^{b}$, find $\frac{d y}{d x}$.

#### Solution:
Let $u=x^{x}, v=x^{y}$ and $w=y^{x}$. Then,

$$
\begin{aligned}
& u+v+w=a^{b} \\
\Rightarrow & \frac{d u}{d x}+\frac{d v}{d x}+\frac{d w}{d x}=0 . \quad \ldots \text { (i) }\left[\because \quad a^{b}=\text { constant }\right]
\end{aligned}
$$

Now, $u=x^{x}$
$\Rightarrow \log u=x \log x$
[on differentiating both sides w.r.t. $x$ ]

$$
\begin{equation*}
\Rightarrow \frac{d u}{d x}=u \cdot\left\{x \cdot \frac{1}{x}+(\log x) \cdot 1\right\} \tag{ii}
\end{equation*}
$$

$\Rightarrow \frac{d u}{d x}=x^{x}(1+\log x)$.

And, $v=x^{y}$
$\Rightarrow \log v=y \log x$
$\Rightarrow \frac{1}{v} \cdot \frac{d v}{d x}=y \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}(y)$
[on differentiating both sides w.r.t. $x$ ]

$$
\begin{equation*}
\Rightarrow \frac{d v}{d x}=v \cdot\left[y \cdot \frac{1}{x}+(\log x) \cdot \frac{d y}{d x}\right] \tag{iii}
\end{equation*}
$$

$\Rightarrow \frac{d v}{d x}=x^{y}\left\{\frac{y}{x}+(\log x) \frac{d y}{d x}\right\}$.

And, $w=y^{x}$
$\Rightarrow \log w=x \log y$
$\Rightarrow \frac{1}{w} \cdot \frac{d w}{d x}=x \cdot \frac{d}{d x}(\log y)+(\log y) \cdot \frac{d}{d x}(x)$
[on differentiating both sides w.r.t. $x$ ]

$$
\begin{equation*}
\Rightarrow \frac{d w}{d x}=w \cdot\left\{x \cdot \frac{1}{y} \cdot \frac{d y}{d x}+(\log y) \cdot 1\right\} \tag{iv}
\end{equation*}
$$

$\Rightarrow \frac{d w}{d x}=y^{x} \cdot\left\{\frac{x}{y} \cdot \frac{d y}{d x}+(\log y)\right\}$.

Using (ii), (iii) and (iv) in (i), we get

$$
\begin{aligned}
& x^{x}(1+\log x)+x^{y}\left\{\frac{y}{x}+(\log x) \frac{d y}{d x}\right\}+y^{x} \cdot\left\{\frac{x}{y} \cdot \frac{d y}{d x}+(\log y)\right\}=0 \\
\Rightarrow & \left\{x^{x}(1+\log x)+y \cdot x^{(y-1)}+y^{x}(\log y)\right\}+\left\{x^{y}(\log x)+x y^{(x-1)}\right\} \frac{d y}{d x}=0 \\
\Rightarrow & \frac{d y}{d x}=\frac{-\left\{x^{x}(1+\log x)+y \cdot x^{(y-1)}+y^{x}(\log y)\right\}}{\left\{x^{y}(\log x)+x y^{(x-1)}\right\}} .
\end{aligned}
$$

---

### Example 23:
If $y=x^{\left(x^{x}\right)}$, find $\frac{d y}{d x}$.

#### Solution:
Let $x^{x}=u$. Then, $y=x^{u}$.
$\therefore \quad x \log x=\log u$ and $\log y=u \log x$.

Now, $\log u=x \log x$
$\Rightarrow \frac{1}{u} \cdot \frac{d u}{d x}=x \cdot \frac{d}{d x}(\log x)+\log x \cdot \frac{d}{d x}(x)$ [on differentiating w.r.t. $x$ ]

$$
\begin{equation*}
\Rightarrow \frac{d u}{d x}=u \cdot\left[x \cdot \frac{1}{x}+\log x \cdot 1\right] \tag{i}
\end{equation*}
$$

$\Rightarrow \frac{d u}{d x}=x^{x}(1+\log x)$.

And, $\log y=u \log x$
$\Rightarrow \frac{1}{y} \cdot \frac{d y}{d x}=u \cdot \frac{d}{d x}(\log x)+(\log x) \cdot \frac{d}{d x}(u)$

$$
=u \cdot \frac{1}{x}+(\log x) \cdot \frac{d u}{d x}
$$

$$
\begin{aligned}
\Rightarrow \frac{d y}{d x} & =y \cdot\left[\frac{u}{x}+(\log x) \cdot \frac{d u}{d x}\right] \\
& =x^{\left(x^{x}\right)} \cdot\left[\frac{x^{x}}{x}+(\log x)\left\{x^{x}(1+\log x)\right\}\right] \\
& =x^{\left(x^{x}\right)} \cdot\left[x^{(x-1)}+x^{x}(\log x)+x^{x}(\log x)^{2}\right] .
\end{aligned}
$$

---

### Example 24:
If $y=(\log x)^{\cos x}+\frac{x^{2}+1}{x^{2}-1}$, find $\frac{d y}{d x}$.
[CBSE 2008C]

#### Solution:
Let $(\log x)^{\cos x}=u$ and $\frac{x^{2}+1}{x^{2}-1}=v$. Then,

$$
\begin{equation*}
u=(\log x)^{\cos x} \Rightarrow \log u=\cos x \cdot \log (\log x) . \tag{i}
\end{equation*}
$$

On differentiating both sides of (i) w.r.t. $x$, we get

$$
\begin{aligned}
& \quad \frac{1}{u} \cdot \frac{d u}{d x}=\cos x \cdot \frac{d}{d x}\{\log (\log x)\}+\log (\log x) \cdot \frac{d}{d x}(\cos x) \\
& \quad=\cos x \frac{1}{\log x} \cdot \frac{1}{x}-(\sin x) \cdot \log (\log x) \cdot \\
\end{aligned}
$$

$\therefore \quad \frac{d u}{d x}=u \cdot\left\{\frac{\cos x}{x \log x}-(\sin x) \cdot \log (\log x)\right\}$
$\Rightarrow \quad \frac{d u}{d x}=(\log x)^{\cos x} \cdot\left\{\frac{\cos x}{x \log x}-(\sin x) \cdot \log (\log x)\right\} \cdot$

And, $v=\frac{\left(x^{2}+1\right)}{\left(x^{2}-1\right)} \Rightarrow \frac{d v}{d x}=\frac{\left(x^{2}-1\right) \cdot \frac{d}{d x}\left(x^{2}+1\right)-\left(x^{2}+1\right) \cdot \frac{d}{d x}\left(x^{2}-1\right)}{\left(x^{2}-1\right)^{2}}$
$\Rightarrow \quad \frac{d v}{d x}=\frac{\left(x^{2}-1\right) \cdot 2 x-\left(x^{2}+1\right) \cdot 2 x}{\left(x^{2}-1\right)^{2}}=\frac{-4 x}{\left(x^{2}-1\right)^{2}} \cdot$

$\therefore \quad \frac{y=u+v}{d x}=\frac{d u}{d x}+\frac{d v}{d x}$

$$
\quad=(\log x)^{\cos x} \cdot\left\{\frac{\cos x}{x \log x}-(\sin x) \cdot \log (\log x)\right\}-\frac{4 x}{\left(x^{2}-1\right)^{2}} .
$$

---

### Example 25:
Differentiate $(\log x)^{x}+x^{\log x}$ w.r.t. $x$.
[CBSE 2013]

#### Solution:
Let $y=(\log x)^{x}+x^{\log x}$.
Let $(\log x)^{x}=u$ and $x^{\log x}=v$. Then,

$$
\begin{align*}
& y=u+v \Rightarrow \frac{d y}{d x}=\frac{d u}{d x}+\frac{d v}{d x}  \tag{i}\\
& \text { Now, } u=(\log x)^{x} \Rightarrow \log u=x \log (\log x) \\
& \Rightarrow \frac{1}{u} \frac{d u}{d x}=x \cdot \frac{1}{\log x} \cdot \frac{1}{x}+\log (\log x) \cdot 1
\end{align*}
$$

$$
\begin{align*}
\Rightarrow & \frac{d u}{d x}=u \cdot\left\{\frac{1}{\log x}+\log (\log x)\right\} \\
\Rightarrow & \frac{d u}{d x}=(\log x)^{x} \cdot\left\{\frac{1}{\log x}+\log (\log x)\right\}  \tag{ii}\\
v=x^{\log x} \Rightarrow & \log v=(\log x)(\log x)=(\log x)^{2} \\
\Rightarrow & \frac{1}{v} \cdot \frac{d v}{d x}=2 \log x \cdot \frac{1}{x} \\
\Rightarrow & \frac{d v}{d x}=v\left(\frac{2 \log x}{x}\right) \\
\Rightarrow & \frac{d v}{d x}=x^{\log x} \cdot \frac{2 \log x}{x}=x^{\log x-1} \cdot 2 \log x \tag{iii}
\end{align*}
$$

Putting the values of $\frac{d u}{d x}$ and $\frac{d v}{d x}$ from (ii) and (iii) in (i), we get

$$
\frac{d y}{d x}=(\log x)^{x-1}+(\log x)^{x} \times \log (\log x)+x^{\log x-1} \cdot 2 \log x .
$$

---

### Example 26:
If $y=(\sin x)^{x}+\sin ^{-1} \sqrt{x}$, find $\frac{d y}{d x}$.
[CBSE 2013C]

#### Solution:
Let $(\sin x)^{x}=u$ and $\sin ^{-1} \sqrt{x}=v$. Then,

$$
\begin{align*}
& \begin{aligned}
y=u+v \Rightarrow & \frac{d y}{d x}=\frac{d u}{d x}+\frac{d v}{d x}
\end{aligned}  \tag{i}\\
& \text { Now, } u=(\sin x)^{x} \\
& \Rightarrow \log u=x \log (\sin x) \\
& \Rightarrow \frac{1}{u} \cdot \frac{d u}{d x}=x \cdot \frac{1}{\sin x} \cdot \cos x+\log (\sin x) \cdot 1 \\
& \Rightarrow \frac{d u}{d x}=u\{x \cot x+\log (\sin x)\}  \tag{ii}\\
& \Rightarrow \frac{d u}{d x}=(\sin x)^{x} \cdot\{x \cot x+\log (\sin x)\}  \tag{iii}\\
& v=\sin ^{-1} \sqrt{x} \Rightarrow \frac{d v}{d x}=\frac{1}{\sqrt{(1-x)}} \cdot \frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x} \sqrt{(1-x)}}=\frac{1}{2 \sqrt{x-x^{2}}}
\end{align*}
$$

Using (ii) and (iii) in (i), we get

$$
\frac{d y}{d x}=(\sin x)^{x}\{x \cot x+\log (\sin x)\}+\frac{1}{2 \sqrt{x-x^{2}}}
$$

---

### Example 27:
If $\left(\tan ^{-1} x\right)^{y}+y^{\cot x}=1$, then find $\frac{d y}{d x}$.
[CBSE 2014C]

#### Solution:
Let $\left(\tan ^{-1} x\right)^{y}=u$ and $y^{\cot x}=v$. Then,

$$
\begin{equation*}
u+v=1 \Rightarrow \frac{d u}{d x}+\frac{d v}{d x}=0 \tag{i}
\end{equation*}
$$

Now, $u=\left(\tan ^{-1} x\right)^{y}$
$\Rightarrow \log u=y \log \left(\tan ^{-1} x\right)$
$\Rightarrow \frac{1}{u} \cdot \frac{d u}{d x}=y \cdot \frac{1}{\tan ^{-1} x} \cdot \frac{1}{\left(1+x^{2}\right)}+\log \left(\tan ^{-1} x\right) \frac{d y}{d x}$
$\Rightarrow \frac{d u}{d x}=u \cdot\left\{\frac{y}{\left(1+x^{2}\right) \tan ^{-1} x}+\log \left(\tan ^{-1} x\right) \cdot \frac{d y}{d x}\right\}$

$$
\begin{equation*}
\Rightarrow \frac{d u}{d x}=\left(\tan ^{-1} x\right)^{y} \cdot\left\{\frac{y}{\left(1+x^{2}\right) \tan ^{-1} x}+\log \left(\tan ^{-1} x\right) \cdot \frac{d y}{d x}\right\} \tag{ii}
\end{equation*}
$$

$\Rightarrow \frac{d u}{d x}=\frac{y\left(\tan ^{-1} x\right)^{y-1}}{\left(1+x^{2}\right)}+\left(\tan ^{-1} x\right)^{y} \log \left(\tan ^{-1} x\right) \cdot \frac{d y}{d x}$.

Again, $v=y^{\cot x}$
$\Rightarrow \log v=(\cot x) \log y$
$\Rightarrow \frac{1}{v} \cdot \frac{d v}{d x}=(\cot x) \cdot \frac{1}{y} \cdot \frac{d y}{d x}+(\log y)\left(-\operatorname{cosec}^{2} x\right)$
$\Rightarrow \frac{d v}{d x}=v\left\{\frac{\cot x}{y} \cdot \frac{d y}{d x}-\left(\operatorname{cosec}^{2} x\right)(\log y)\right\}$

$$
\begin{equation*}
\Rightarrow \frac{d v}{d x}=y^{\cot x}\left\{\frac{\cot x}{y} \cdot \frac{d y}{d x}-\left(\operatorname{cosec}^{2} x\right)(\log y)\right\} \tag{iii}
\end{equation*}
$$

$\Rightarrow \frac{d v}{d x}=(\cot x) y^{(\cot x)-1} \cdot \frac{d y}{d x}-y^{\cot x}\left(\operatorname{cosec}^{2} x\right)(\log y)$.

Using (ii) and (iii) in (i), we get

$$
\begin{aligned}
& \frac{y\left(\tan ^{-1} x\right)^{y-1}}{\left(1+x^{2}\right)}+\left(\tan ^{-1} x\right)^{y} \log \left(\tan ^{-1} x\right) \frac{d y}{d x} \\
& +(\cot x) y^{(\cot x)-1} \cdot \frac{d y}{d x}-y^{\cot x}\left(\operatorname{cosec}^{2} x\right)(\log y)=0 \\
\Rightarrow & \left\{\left(\tan ^{-1} x\right)^{y} \log \left(\tan ^{-1} x\right)+(\cot x) y^{(\cot x)-1}\right\} \frac{d y}{d x} \\
& =\left\{y^{\cot x}\left(\operatorname{cosec}^{2} x\right)(\log y)-\frac{y\left(\tan ^{-1} x\right)^{y-1}}{\left(1+x^{2}\right)}\right\} \\
\Rightarrow & \frac{d y}{d x}=\frac{y^{\cot x}\left(\operatorname{cosec}^{2} x\right)(\log y)-\frac{y\left(\tan ^{-1} x\right)^{y-1}}{\left(1+x^{2}\right)}}{\left(\tan ^{-1} x\right)^{y} \log \left(\tan ^{-1} x\right)+(\cot x) y^{(\cot x)-1}}
\end{aligned}
$$

---