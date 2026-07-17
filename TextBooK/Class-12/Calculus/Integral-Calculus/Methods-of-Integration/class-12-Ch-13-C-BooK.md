## Integration by Parts

**THEOREM** If $u$ and $v$ are two functions of $x$ then

$$
\int(u v) d x=\left[u \cdot \int v d x\right]-\int\left\{\frac{d u}{d x} \cdot \int v d x\right\} d x
$$

**PROOF** For any two functions $f_{1}(x)$ and $f_{2}(x)$, we have

$$
\begin{array}{ll}
& \frac{d}{d x}\left[f_{1}(x) \cdot f_{2}(x)\right]=f_{1}(x) \cdot f_{2}^{\prime}(x)+f_{2}(x) \cdot f_{1}^{\prime}(x) \\
\therefore & \int\left\{f_{1}(x) \cdot f_{2}^{\prime}(x)+f_{2}(x) \cdot f_{1}^{\prime}(x)\right\} d x=f_{1}(x) \cdot f_{2}(x)
\end{array}
$$

or $\quad \int f_{1}(x) \cdot f_{2}{ }^{\prime}(x) d x+\int f_{2}(x) \cdot f_{1}{ }^{\prime}(x) d x=f_{1}(x) \cdot f_{2}(x)$
or $\quad \int f_{1}(x) \cdot f_{2}{ }^{\prime}(x) d x=f_{1}(x) \cdot f_{2}(x)-\int f_{2}(x) \cdot f_{1}{ }^{\prime}(x) d x$.
Let $\quad f_{1}(x)=u$ and $f_{2}{ }^{\prime}(x)=v$ so that $f_{2}(x)=\int v d x$.
$\therefore \quad \int(u v) d x=u \cdot \int v d x-\int\left\{\frac{d u}{d x} \cdot \int v d x\right\} d x$.

We can express this result as given below:
**Integral of product of two functions**

$$
\begin{aligned}
= & (1 \text { st function }) \times(\text { integral of } 2 \text { nd }) \\
& -\int\{(\text { derivative } \text { of } 1 \text { st }) \times(\text { integral of } 2 \text { nd })\} d x .
\end{aligned}
$$

**REMARKS** (i) If the integrand is of the form $f(x) x^{n}$, we consider $x^{n}$ as the first function and $f(x)$ as the second function.
(ii) If the integrand contains a logarithmic or an inverse trigonometric function, we take it as the first function. In all such cases, if the second function is not given, we take it as $1$.

---

## SOLVED EXAMPLES

### Example: 1

Evaluate:
- (i) $\int x \sec ^{2} x d x$
- (ii) $\int x \sin 2 x d x$

#### Solution:

(i) Integrating by parts, taking $x$ as the first function, we get

$$
\begin{aligned}
\int x \sec ^{2} x d x & =x \cdot \int \sec ^{2} x d x-\int\left\{\frac{d}{d x}(x) \cdot \int \sec ^{2} x d x\right\} d x \\
& =x \tan x-\int 1 \cdot \tan x d x=x \tan x+\log |\cos x|+C
\end{aligned}
$$

(ii) Integrating by parts, taking $x$ as the first function, we get

$$
\begin{aligned}
\int x \sin 2 x d x & =x \cdot \int \sin 2 x d x-\int\left\{\frac{d}{d x}(x) \cdot \int \sin 2 x d x\right\} d x \\
& =x \cdot\left(\frac{-\cos 2 x}{2}\right)-\int 1 \cdot\left(\frac{-\cos 2 x}{2}\right) d x \\
& =\frac{-x \cos 2 x}{2}+\frac{1}{2} \int \cos 2 x d x \\
& =\frac{-x \cos 2 x}{2}+\frac{1}{2} \cdot \frac{\sin 2 x}{2}+C \\
& =\frac{-x \cos 2 x}{2}+\frac{1}{4} \sin 2 x+C
\end{aligned}
$$

---

### Example: 2

Evaluate $\int x^{n} \log x d x$.

#### Solution:

Integrating by parts, taking $\log x$ as the first function, we get

$$
\begin{aligned}
\int x^{n} \log x & =(\log x) \cdot \int x^{n} d x-\int\left\{\frac{d}{d x}(\log x) \cdot \int x^{n} d x\right\} d x \\
& =(\log x) \cdot \frac{x^{n+1}}{(n+1)}-\int \frac{1}{x} \cdot \frac{x^{n+1}}{(n+1)} d x \\
& =\frac{x^{n+1} \log x}{(n+1)}-\frac{1}{(n+1)} \int x^{n} d x \\
& =\frac{x^{n+1} \log x}{(n+1)}-\frac{x^{n+1}}{(n+1)^{2}}+C
\end{aligned}
$$

---

### Example: 3

Evaluate $\int x^{2} \sin x d x$.

#### Solution:

Integrating by parts, taking $x^{2}$ as the first function, we get

$$
\begin{aligned}
\int x^{2} \sin x d x & =x^{2} \int \sin x d x-\int\left[\frac{d}{d x}\left(x^{2}\right) \cdot \int \sin x d x\right] d x \\
& =x^{2}(-\cos x)-\int 2 x(-\cos x) d x \\
& =-x^{2} \cos x+2 \int x \cos x d x \\
& =-x^{2} \cos x+2\left[x(\sin x)-\int\left\{\frac{d}{d x}(x) \cdot \int \cos x d x\right\} d x\right]
\end{aligned}
$$

[integrating $x \cos x$ by parts]

$$
\begin{aligned}
& =-x^{2} \cos x+2\left[x \sin x-\int \sin x d x\right] \\
& =-x^{2} \cos x+2[x \sin x+\cos x]+C
\end{aligned}
$$

---

### Example: 4

Evaluate $\int x \cos ^{2} x d x$.

#### Solution:

$\int x \cos ^{2} x d x=\int x\left(\frac{1+\cos 2 x}{2}\right) d x=\frac{1}{2} \int x d x+\frac{1}{2} \int x \cos 2 x d x$

$$
\begin{aligned}
& =\frac{x^{2}}{4}+\frac{1}{2} \cdot\left[x \cdot \int \cos 2 x d x-\int\left\{\frac{d}{d x}(x) \cdot \int \cos 2 x d x\right\} d x\right] \\
& \quad \quad \text { [integrating } x \cos 2 x \text { by parts] } \\
& =\frac{x^{2}}{4}+\frac{1}{2}\left[\frac{x \sin 2 x}{2}-\int \frac{\sin 2 x}{2} d x\right] \\
& =\frac{x^{2}}{4}+\frac{x \sin 2 x}{4}-\frac{1}{4} \cdot \frac{(-\cos 2 x)}{2}+C \\
& =\frac{x^{2}}{4}+\frac{x \sin 2 x}{4}+\frac{\cos 2 x}{8}+C
\end{aligned}
$$

---

### Example: 5

Evaluate $\int \log x d x$.

#### Solution:

Integrating by parts, taking $\log x$ as the first function and $1$ as the second function, we get

$$
\begin{aligned}
\int \log x d x & =\int(\log x \cdot 1) d x \\
& =(\log x) \cdot \int 1 d x-\int\left\{\frac{d}{d x}(\log x) \cdot \int 1 d x\right\} d x \\
& =(\log x) \cdot x-\int\left(\frac{1}{x} \cdot x\right) d x=x \log x-\int d x \\
& =x \log x-x+C=x(\log x-1)+C
\end{aligned}
$$

---

### Example: 6

Evaluate $\int \log \left(1+x^{2}\right) d x$.

#### Solution:

Integrating by parts, taking $\log \left(1+x^{2}\right)$ as the first function and $1$
as the second function, we get

$$
\begin{aligned}
\int \log \left(1+x^{2}\right) d x & =\int\left\{\log \left(1+x^{2}\right) \cdot 1\right\} d x \\
& =\log \left(1+x^{2}\right) \cdot \int 1 d x-\int\left[\frac{d}{d x}\left\{\log \left(1+x^{2}\right)\right\} \cdot \int 1 d x\right] d x \\
& =\log \left(1+x^{2}\right) \cdot x-\int \frac{2 x}{\left(1+x^{2}\right)} \cdot x d x \\
& =x \log \left(1+x^{2}\right)-2 \int \frac{x^{2}}{\left(1+x^{2}\right)} d x \\
& =x \log \left(1+x^{2}\right)-2 \int\left(1-\frac{1}{1+x^{2}}\right) d x \\
& =x \log \left(1+x^{2}\right)-2 \int d x+2 \int \frac{d x}{\left(1+x^{2}\right)} \\
& =x \log \left(1+x^{2}\right)-2 x+2 \tan ^{-1} x+C
\end{aligned}
$$

---

### Example: 7

Evaluate $\int(\log x)^{2} d x$.

#### Solution:

Integrating by parts, taking $(\log x)^{2}$ as the first function and $1$ as the second function, we get

$$
\begin{aligned}
\int(\log x)^{2} d x & =\int\left\{(\log x)^{2} \cdot 1\right\} d x \\
& =(\log x)^{2} \cdot \int 1 d x-\int\left\{\frac{d}{d x}(\log x)^{2} \cdot \int 1 d x\right\} d x \\
& =x(\log x)^{2}-\int\left(\frac{2 \log x}{x} \cdot x\right) d x \\
& =x(\log x)^{2}-2 \int(\log x \cdot 1) d x \\
& =x(\log x)^{2}-2\left[(\log x) \int d x-\int\left\{\frac{d}{d x}(\log x) \cdot \int d x\right\} d x\right] \\
& =x(\log x)^{2}-2\left[x \log x-\int \frac{1}{x} \cdot x d x\right] \\
& =x(\log x)^{2}-2 x \log x+2 x+C
\end{aligned}
$$

---

### Example: 8

Evaluate $\int \frac{\log x}{x^{2}} d x$.

#### Solution:

Integrating by parts, taking $\log x$ as the first function and $\frac{1}{x^{2}}$ as the second function, we get

$$
\begin{aligned}
\int \frac{\log x}{x^{2}} d x & =\int(\log x) \cdot \frac{1}{x^{2}} d x \\
& =(\log x) \cdot \int \frac{1}{x^{2}} d x-\int\left\{\frac{d}{d x}(\log x) \cdot \int \frac{1}{x^{2}} d x\right\} d x \\
& =(\log x)\left(-\frac{1}{x}\right)-\int \frac{1}{x} \cdot\left(-\frac{1}{x}\right) d x=-\frac{\log x}{x}+\int \frac{1}{x^{2}} d x \\
& =-\frac{\log x}{x}-\frac{1}{x}+C=\frac{-(\log x+1)}{x}+C
\end{aligned}
$$

---

### Example: 9

Evaluate $\int e^{2 x} \sin x d x$.

#### Solution:

Integrating by parts, we get

$$
\begin{aligned}
& \qquad \begin{aligned}
& \int e^{2 x} \sin x d x=\left(e^{2 x} \cdot \int \sin x d x\right)-\int\left\{\frac{d}{d x}\left(e^{2 x}\right) \cdot \int \sin x d x\right\} d x \\
&=e^{2 x} \cdot(-\cos x)-2 \int e^{2 x}(-\cos x) d x \\
&=-e^{2 x} \cos x+2 \int e^{2 x} \cos x d x \\
&=-e^{2 x} \cos x+2\left[\left(e^{2 x} \cdot \int \cos x d x\right)-\int\left\{\frac{d}{d x}\left(e^{2 x}\right) \cdot \int \cos x d x\right\} d x\right] \\
& \quad\left[\text { integrating } e^{2 x} \cos x \text { by parts }\right]
\end{aligned} \\
& \quad=-e^{2 x} \cos x+2 e^{2 x} \sin x-4 \int e^{2 x} \sin x d x+C \\
& \text { or } \quad 5 \int e^{2 x} \sin x d x=e^{2 x}(2 \sin x-\cos x)+C \\
& \therefore \quad \int e^{2 x} \sin x d x=\frac{1}{5} e^{2 x}(2 \sin x-\cos x)+C
\end{aligned}
$$

---

### Example: 10

Evaluate $\int\left(\frac{x-\sin x}{1-\cos x}\right) d x$.

#### Solution:

$\int\left(\frac{x-\sin x}{1-\cos x}\right) d x=\int \frac{x}{(1-\cos x)} d x-\int \frac{\sin x}{(1-\cos x)} d x$

$$
\begin{aligned}
= & \int \frac{x}{2 \sin ^{2}(x / 2)} d x-\int \frac{2 \sin (x / 2) \cos (x / 2)}{2 \sin ^{2}(x / 2)} d x \\
= & \frac{1}{2} \int x \operatorname{cosec}^{2}(x / 2) d x-\int \cot (x / 2) d x \\
= & \frac{1}{2}\left[x \cdot \int \operatorname{cosec}^{2}(x / 2) d x-\int\left\{\frac{d}{d x}(x) \cdot \int \operatorname{cosec}^{2}(x / 2) d x\right\} d x\right] \\
& \quad-\int \cot (x / 2) d x \quad[\text { integrating by parts }] \\
= & \frac{1}{2}\left[x \cdot\left(-2 \cot \frac{x}{2}\right)-\int\left[1 \cdot\left(-2 \cot \frac{x}{2}\right)\right] d x\right]-\int \cot (x / 2) d x+C \\
= & -x \cot \frac{x}{2}+\int \cot \frac{x}{2} d x-\int \cot \frac{x}{2} d x+C=-x \cot \frac{x}{2}+C
\end{aligned}
$$

---

### Example: 11

Evaluate $\int x \tan ^{-1} x d x$.
[CBSE 2000C, '04C]

#### Solution:

Integrating by parts, taking $\tan ^{-1} x$ as the first function, we get

$$
\begin{array}{rl}
\int x \tan ^{-1} x & d x=\left(\tan ^{-1} x\right) \cdot \int x d x-\int\left\{\frac{d}{d x}\left(\tan ^{-1} x\right) \cdot \int x d x\right\} d x \\
= & \left(\tan ^{-1} x\right) \cdot \frac{x^{2}}{2}-\int \frac{1}{\left(1+x^{2}\right)} \cdot \frac{x^{2}}{2} d x \\
= & \frac{x^{2} \tan ^{-1} x}{2}-\frac{1}{2} \int\left(1-\frac{1}{1+x^{2}}\right) d x \text { [on dividing } x^{2} \text { by } 1+x^{2} \text { ] }
\end{array}
$$

$$
\begin{aligned}
& =\frac{x^{2} \tan ^{-1} x}{2}-\frac{1}{2} \int d x+\frac{1}{2} \int \frac{1}{\left(1+x^{2}\right)} d x \\
& =\frac{x^{2} \tan ^{-1} x}{2}-\frac{x}{2}+\frac{1}{2} \tan ^{-1} x+C \\
& =\frac{1}{2}\left(1+x^{2}\right) \tan ^{-1} x-\frac{1}{2} x+C .
\end{aligned}
$$

---

### Example: 12

Evaluate $\int x^{2} \sin ^{-1} x d x$.

#### Solution:

Integrating by parts, taking $\sin ^{-1} x$ as the first function we get

$$
\begin{aligned}
\int x^{2} \sin ^{-1} x d x & =\left(\sin ^{-1} x\right) \cdot \frac{x^{3}}{3}-\int \frac{1}{\sqrt{1-x^{2}}} \cdot \frac{x^{3}}{3} d x \\
& =\frac{x^{3} \sin ^{-1} x}{3}-\frac{1}{3} \int \frac{x^{3}}{\sqrt{1-x^{2}}} d x \\
& =\frac{x^{3} \sin ^{-1} x}{3}-\frac{1}{3} \int \frac{x \cdot x^{2}}{\sqrt{1-x^{2}}} d x \\
& =\frac{x^{3} \sin ^{-1} x}{3}+\frac{1}{3} \int \frac{t\left(1-t^{2}\right)}{t} d t, \text { where }\left(1-x^{2}\right)=t^{2} \\
& =\frac{x^{3} \sin ^{-1} x}{3}+\frac{1}{3} \int d t-\frac{1}{3} \int t^{2} d t \\
& =\frac{x^{3} \sin ^{-1} x}{3}+\frac{1}{3} t-\frac{1}{9} t^{3}+C \\
& =\frac{x^{3} \sin ^{-1} x}{3}+\frac{1}{3} \sqrt{1-x^{2}}-\frac{1}{9}\left(1-x^{2}\right)^{3 / 2}+C
\end{aligned}
$$

---

### Example: 13

Evaluate:
- (i) $\int \cos ^{-1} x d x$
- (ii) $\int \tan ^{-1} x d x$
- (iii) $\int \sec ^{-1} x d x$

#### Solution:

(i) Put $\cos ^{-1} x=t$ so that $x=\cos t$ and $d x=-\sin t d t$.

$$
\begin{aligned}
\therefore \quad \int \cos ^{-1} x d x & =-\int t \sin t d t \\
& =-\left[t \cdot(-\cos t)-\int 1 \cdot(-\cos t) d t\right]
\end{aligned}
$$

[integrating by parts]

$$
\begin{aligned}
& =t \cos t-\int \cos t d t=t \cos t-\sin t+C \\
& =x \cos ^{-1} x-\sqrt{1-x^{2}}+C \\
& \quad\left[\because \quad \cos t=x \Rightarrow \sin t=\sqrt{1-x^{2}}\right]
\end{aligned}
$$

(ii) Put $\tan ^{-1} x=t$ so that $x=\tan t$ and $d x=\sec ^{2} t d t$.

$$
\begin{aligned}
\therefore \quad \int \tan ^{-1} x d x & =\int t \sec ^{2} t d t \\
& =t \cdot \tan t-\int 1 \cdot \tan t d t \quad \text { [integrating by parts] } \\
& =t \cdot \tan t+\log |\cos t|+C
\end{aligned}
$$

$$
\begin{aligned}
& =\left(\tan ^{-1} x\right) \cdot x+\log \left|\frac{1}{\sqrt{1+x^{2}}}\right|+C \\
& \quad\left[\because \tan t=x \Rightarrow \cos t=\frac{1}{\sqrt{1+x^{2}}}\right] \\
& =x\left(\tan ^{-1} x\right)-\frac{1}{2} \log \left|1+x^{2}\right|+C
\end{aligned}
$$

(iii) Put $\sec ^{-1} x=t$ so that $x=\sec t$ and $d x=\sec t \tan t d t$.

$$
\begin{aligned}
\therefore \quad \int \sec ^{-1} x d x & =\int t(\sec t \tan t) d t \\
& =t(\sec t)-\int 1 \cdot \sec t d t \quad \quad[\text { integrating by parts] } \\
& =t(\sec t)-\log |\sec t+\tan t|+C \\
& =t(\sec t)-\log \left|\sec t+\sqrt{\sec ^{2} t-1}\right|+C \\
& =x\left(\sec ^{-1} x\right)-\log \left|x+\sqrt{x^{2}-1}\right|+C
\end{aligned}
$$

---

### Example: 14

Evaluate $\int\left(\sin ^{-1} x\right)^{2} d x$.
[CBSE 2004]

#### Solution:

Putting $x=\sin t$ and $d x=\cos t d t$, we get

$$
\begin{aligned}
\int\left(\sin ^{-1} x\right)^{2} d x & =\int t^{2} \cos t d t \\
& =t^{2} \cdot(\sin t)-\int 2 t(\sin t) d t \quad[\text { integrating by parts }] \\
& =t^{2} \sin t-2\left[t(-\cos t)-\int 1 \cdot(-\cos t) d t\right] \\
& \quad[\text { integrating } t(\sin t) \text { by parts] } \\
& =t^{2} \sin t+2 t \cos t-2 \sin t+C \\
& =x\left(\sin ^{-1} x\right)^{2}+2\left(\sin ^{-1} x\right) \sqrt{1-x^{2}}-2 x+C
\end{aligned}
$$

---

### Example: 15

Evaluate $\int \frac{\sin ^{-1} x}{\left(1-x^{2}\right)^{3 / 2}} d x$.

#### Solution:

Put $x=\sin t$ so that $d x=\cos t d t$ and $t=\sin ^{-1} x$.

$$
\begin{aligned}
\therefore \quad \int \frac{\sin ^{-1} x}{\left(1-x^{2}\right)^{3 / 2}} d x= & \int \frac{t \cos t}{\left(1-\sin ^{2} t\right)^{3 / 2}} d t=\int \frac{t \cos t}{\cos ^{3} t} d t \\
= & \int t \sec ^{2} t d t \\
= & t \cdot(\tan t)-\int 1 \cdot \tan t d t \quad[\text { integrating by parts }] \\
= & t \cdot(\tan t)+\log |\cos t|+C \\
= & \left(\sin ^{-1} x\right) \cdot \frac{x}{\sqrt{1-x^{2}}}+\log \left|\sqrt{1-x^{2}}\right|+C . \\
& \quad\left[\because \cos t=\sqrt{1-x^{2}} \text { and } \tan t=\frac{x}{\sqrt{1-x^{2}}}\right] \\
= & \frac{x\left(\sin ^{-1} x\right)}{\sqrt{1-x^{2}}}+\frac{1}{2} \log \left|\left(1-x^{2}\right)\right|+C .
\end{aligned}
$$

---

### Example: 16

Evaluate $\int \frac{x \tan ^{-1} x}{\left(1+x^{2}\right)^{3 / 2}} d x$.

#### Solution:

Put $x=\tan t$ so that $d x=\sec ^{2} t d t$.

$$
\begin{aligned}
\therefore \int \frac{x \tan ^{-1} x}{\left(1+x^{2}\right)^{3 / 2}} d x= & \int \frac{(\tan t) t}{\left(1+\tan ^{2} t\right)^{3 / 2}} \cdot \sec ^{2} t d t \\
= & \int \frac{(\tan t) t}{\sec t} d t=\int t \sin t d t \\
= & t(-\cos t)-\int 1 \cdot(-\cos t) d t[\text { integrating by parts }] \\
= & -t \cos t+\sin t+C=\frac{-\tan ^{-1} x}{\sqrt{1+x^{2}}}+\frac{x}{\sqrt{1+x^{2}}}+C \\
& {\left[\because \sin t=\frac{x}{\sqrt{1+x^{2}}} \text { and } \cos t=\frac{1}{\sqrt{1+x^{2}}}\right] }
\end{aligned}
$$

---

### Example: 17

Evaluate:
- (i) $\int \sin ^{-1}\left(3 x-4 x^{3}\right) d x$
- (ii) $\int \sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right) d x$
- (iii) $\int \tan ^{-1} \sqrt{\frac{1-x}{1+x}} d x$
- (iv) $\int \sin ^{-1} \sqrt{\frac{x}{a+x}} d x$ [CBSE 2002]

#### Solution:

(i) Put $x=\sin t$ so that $d x=\cos t d t$.

$$
\begin{aligned}
\therefore \int \sin ^{-1}\left(3 x-4 x^{3}\right) d x & =\int \sin ^{-1}\left(3 \sin t-4 \sin ^{3} t\right) \cos t d t \\
& =\int \sin ^{-1}(\sin 3 t) \cos t d t \\
& =3 \int t \cos t d t \\
& =3\left[t(\sin t)-\int 1 \cdot \sin t d t\right]
\end{aligned}
$$

[integrating by parts]

$$
\begin{aligned}
& =3 t \sin t+3 \cos t+C \\
& =3 x\left(\sin ^{-1} x\right)+3 \sqrt{1-x^{2}}+C
\end{aligned}
$$

(ii) Put $x=\tan t$ so that $d x=\sec ^{2} t d t$.

$$
\begin{aligned}
\therefore \quad \int \sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right) d x & =\int \sin ^{-1}\left(\frac{2 \tan t}{1+\tan ^{2} t}\right) \sec ^{2} t d t \\
& =\int \sin ^{-1}(\sin 2 t) \sec ^{2} t d t=2 \int t \cdot \sec ^{2} t d t \\
& =2\left[t \cdot \tan t-\int 1 \cdot \tan t d t\right] \\
& =2 t \cdot \tan t+2 \log |\cos t|+C \\
& =2 x\left(\tan ^{-1} x\right)+2 \log \left|\frac{1}{\sqrt{1+x^{2}}}\right|+C \\
& =2 x\left(\tan ^{-1} x\right)+2 \cdot\left(-\frac{1}{2}\right) \log \left|1+x^{2}\right|+C \\
& =2 x\left(\tan ^{-1} x\right)-\log \left|1+x^{2}\right|+C
\end{aligned}
$$

(iii) Put $x=\cos t$ so that $d x=-\sin t d t$.

$$
\begin{aligned}
& \therefore \int \tan ^{-1} \sqrt{\frac{1-x}{1+x}} d x=\int \tan ^{-1} \sqrt{\frac{1-\cos t}{1+\cos t}}(-\sin t) d t \\
& \quad=\int \tan ^{-1} \sqrt{\frac{2 \sin ^{2}(t / 2)}{2 \cos ^{2}(t / 2)}}(-\sin t) d t \\
& \quad=\int\left[\tan ^{-1}\left(\tan \frac{t}{2}\right)\right](-\sin t) d t=-\frac{1}{2} \int t(\sin t) d t \\
& \quad=-\frac{1}{2}\left[t(-\cos t)-\int 1 \cdot(-\cos t) d t\right] \quad \text { [integrating by parts] } \\
& \quad=\frac{1}{2} t \cdot \cos t-\frac{1}{2} \sin t+C=\frac{1}{2} x\left(\cos ^{-1} x\right)-\frac{1}{2} \sqrt{1-x^{2}}+C
\end{aligned}
$$

(iv) Put $x=a \tan ^{2} t$ so that $d x=\left(2 a \sec ^{2} t \tan t\right) d t$.

$$
\begin{aligned}
\therefore \quad & \int \sin ^{-1} \sqrt{\frac{x}{a+x}} d x=\int \sin ^{-1}\left\{\sqrt{\frac{a \tan ^{2} t}{a\left(1+\tan ^{2} t\right)}}\right\} 2 a \sec ^{2} t \tan t d t \\
= & 2 a \int t\left(\sec ^{2} t \cdot \tan t\right) d t \\
= & 2 a\left[t \cdot \frac{1}{2} \tan ^{2} t-\int 1 \cdot \frac{1}{2} \tan ^{2} t d t\right] \\
& \quad\left[\text { integrating by parts and using } \int \sec ^{2} t \tan t d t=\frac{1}{2} \tan ^{2} t\right] \\
= & a t\left(\tan ^{2} t\right)-a \int\left(\sec ^{2} t-1\right) d t \\
= & a t\left(\tan ^{2} t\right)-a \int \sec ^{2} t d t+a \int d t \\
= & a t\left(\tan ^{2} t\right)-a \tan t+a t+C \\
= & a\left(\tan ^{-1} \sqrt{\frac{x}{a}}\right) \cdot\left(\frac{x}{a}\right)-a \cdot \sqrt{\frac{x}{a}}+a \tan ^{-1} \sqrt{\frac{x}{a}}+C \\
= & x \tan ^{-1} \sqrt{\frac{x}{a}}-\sqrt{a x}+a \tan ^{-1} \sqrt{\frac{x}{a}}+C .
\end{aligned}
$$

---

### Example: 18

Evaluate $\int x \cos ^{3} x \sin x d x$.

#### Solution:

Take $x$ as the first function and $\left(\cos ^{3} x \sin x\right)$ as the second.
Putting $\cos x=t$, we can evaluate $\int \cos ^{3} x \sin x d x$ as $-\frac{1}{4} \cos ^{4} x$.
So, integrating by parts, we get

$$
\begin{aligned}
\int x \cos ^{3} x \sin x d x & =x \cdot\left(\frac{-1}{4} \cos ^{4} x\right)-\int 1 \cdot\left(-\frac{1}{4}\right) \cos ^{4} x d x \\
& =-\frac{x}{4} \cos ^{4} x+\frac{1}{4} \int\left(\frac{1+\cos 2 x}{2}\right)^{2} d x
\end{aligned}
$$

$$
\begin{aligned}
& =-\frac{x \cos ^{4} x}{4}+\frac{1}{4} \int\left(\frac{1}{4}+\frac{\cos ^{2} 2 x}{4}+\cos 2 x\right) d x \\
& =-\frac{x \cos ^{4} x}{4}+\frac{1}{16} \int d x+\frac{1}{4} \int \cos 2 x d x+\frac{1}{32} \int 2 \cos ^{2} 2 x d x \\
& =-\frac{x \cos ^{4} x}{4}+\frac{x}{16}+\frac{\sin 2 x}{8}+\frac{1}{32} \int(1+\cos 4 x) d x+C \\
& =-\frac{x \cos ^{4} x}{4}+\frac{x}{16}+\frac{\sin 2 x}{8}+\frac{1}{32} \int d x+\frac{1}{32} \int \cos 4 x d x \\
& =-\frac{x \cos ^{4} x}{4}+\frac{3 x}{32}+\frac{\sin 2 x}{8}+\frac{\sin 4 x}{128}+C
\end{aligned}
$$

---

### Example: 19

Evaluate $\int \sin (\log x) d x$.

#### Solution:

Put $\log x=t$ so that $x=e^{t}$ and $\frac{1}{x} d x=d t$ or $d x=e^{t} d t$.

$$
\begin{equation*}
\therefore \quad \int \sin (\log x) d x=\int e^{t} \sin t d t \tag{i}
\end{equation*}
$$

Now, $\int e^{t} \sin t d t=e^{t}(-\cos t)-\int e^{t} \cdot(-\cos t) d t$ [integrating by parts]

$$
\begin{aligned}
& =-e^{t} \cos t+\int e^{t} \cos t d t \\
& =-e^{t} \cos t+\left[e^{t} \sin t-\int e^{t} \sin t d t\right]
\end{aligned}
$$

[integrating $e^{t} \cos t$ by parts]

$$
\begin{aligned}
& =-e^{t} \cos t+e^{t} \sin t-\int e^{t} \sin t d t \\
\therefore \quad 2 \int e^{t} \sin t d t & =-e^{t} \cos t+e^{t} \sin t \\
\text { or } \quad \int e^{t} \sin t d t & =\frac{1}{2}\left(-e^{t} \cos t+e^{t} \sin t\right)+C
\end{aligned}
$$

Putting this value in (i), we get

$$
\begin{aligned}
\int \sin (\log x) d x & =\int e^{t} \sin t d t \\
& =\frac{1}{2}\left(-e^{t} \cos t+e^{t} \sin t\right)+C \\
& =\frac{1}{2}[-x \cos (\log x)+x \sin (\log x)]+C \\
& =-\frac{1}{2} x \cos (\log x)+\frac{1}{2} x \sin (\log x)+C
\end{aligned}
$$

---

### Example: 20

Evaluate $\int \sin \sqrt{x} d x$.

#### Solution:

Put $\sqrt{x}=t$ so that $\frac{1}{2 \sqrt{x}} d x=d t$ or $d x=2 t d t$.

$\therefore \quad \int \sin \sqrt{x} d x=2 \int t \sin t d t=2\left[t(-\cos t)-\int 1 \cdot(-\cos t) d t\right]$

[integrating $t \sin t$ by parts]

$$
\begin{aligned}
& =-2 t \cos t+2 \sin t+C \\
& =-2 \sqrt{x} \cos \sqrt{x}+2 \sin \sqrt{x}+C .
\end{aligned}
$$

---

### Example: 21

Evaluate $\int \sec ^{3} x d x$.
[CBSE 2003]

#### Solution:

$\int \sec ^{3} x d x=\int \sec x \cdot \sec ^{2} x d x$

$$
\begin{gathered}
=\sec x \cdot(\tan x)-\int \sec x \tan x(\tan x) d x \\
=\sec x \tan x-\int \sec x\left(\sec ^{2} x-1\right) d x \\
=\sec x \tan x-\int \sec ^{3} x d x+\int \sec x d x \\
\therefore 2 \int \sec ^{3} x d x=\sec x \tan x+\log \left|\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right|+C \\
\text { or } \int \sec ^{3} x d x=\frac{1}{2} \sec x \tan x+\frac{1}{2} \log \left|\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right|+C^{\prime}
\end{gathered}
$$

[integrating by parts]

---

### Example: 22

Evaluate $\int \tan ^{-1} \sqrt{x} d x$.

#### Solution:

Put $\sqrt{x}=t$ so that $\frac{1}{2 \sqrt{x}} d x=d t$ or $d x=2 t d t$.

$$
\begin{aligned}
\therefore \int \tan ^{-1} \sqrt{x} d x & =2 \int t\left(\tan ^{-1} t\right) d t \\
& =2\left[\left(\tan ^{-1} t\right) \cdot \frac{t^{2}}{2}-\int\left\{\frac{1}{\left(1+t^{2}\right)} \cdot \frac{t^{2}}{2}\right\} d t\right]+C \\
& =t^{2}\left(\tan ^{-1} t\right)-\int \frac{t^{2}}{\left(1+t^{2}\right)} d t+C \\
& =t^{2}\left(\tan ^{-1} t\right)-\int \frac{\left[\left(1+t^{2}\right)-1\right]}{\left(1+t^{2}\right)} d t+C \\
& =t^{2}\left(\tan ^{-1} t\right)-\int d t+\int \frac{1}{\left(1+t^{2}\right)} d t+C \\
& =t^{2}\left(\tan ^{-1} t\right)-t+\tan ^{-1} t+C=\left(t^{2}+1\right) \tan ^{-1} t-t+C \\
& =(x+1) \tan ^{-1} \sqrt{x}-\sqrt{x}+C
\end{aligned}
$$

---

### Example: 23

Evaluate $\int \frac{\tan ^{-1} x}{(1+x)^{2}} d x$.
[CBSE 2003]

#### Solution:

Integrating by parts, taking $\tan ^{-1} x$ as the first function and $\frac{1}{(1+x)^{2}}$ as the second function, we get

$$
\begin{aligned}
I & =\tan ^{-1} x \cdot \frac{(-1)}{(1+x)}-\int \frac{1}{\left(1+x^{2}\right)} \cdot \frac{(-1)}{(1+x)} d x \\
& =\frac{-\tan ^{-1} x}{(1+x)}+\int \frac{d x}{(1+x)\left(1+x^{2}\right)}=\frac{-\tan ^{-1} x}{(1+x)}+\frac{1}{2} \cdot \int\left\{\frac{1}{(1+x)}+\frac{(1-x)}{\left(1+x^{2}\right)}\right\}
\end{aligned}
$$

[by partial fractions]

$$
=\frac{-\tan ^{-1} x}{(1+x)}+\frac{1}{2} \log |1+x|+\frac{1}{2} \tan ^{-1} x-\frac{1}{4} \log \left(1+x^{2}\right)+C .
$$

---

### Example: 24

Evaluate $\int\left\{\frac{\sin ^{-1} \sqrt{x}-\cos ^{-1} \sqrt{x}}{\sin ^{-1} \sqrt{x}+\cos ^{-1} \sqrt{x}}\right\} d x$.
[CBSE 2014C]

#### Solution:

We have

$$
\begin{align*}
I & =\int \frac{\left\{\sin ^{-1} \sqrt{x}-\left(\frac{\pi}{2}-\sin ^{-1} \sqrt{x}\right)\right\}}{\left(\frac{\pi}{2}\right)} d x \quad\left[\because \sin ^{-1} \sqrt{x}+\cos ^{-1} \sqrt{x}=\frac{\pi}{2}\right] \\
& =\frac{2}{\pi} \int\left(2 \sin ^{-1} \sqrt{x}-\frac{\pi}{2}\right) d x \\
& =\frac{4}{\pi} \int \sin ^{-1} \sqrt{x} d x-\int d x=\frac{4}{\pi} \int \sin ^{-1} \sqrt{x} d x-x+C \tag{i}
\end{align*}
$$

Putting $x=\sin ^{2} \theta$ and $d x=2 \sin \theta \cos \theta d \theta=\sin 2 \theta d \theta$, we get

$$
\begin{align*}
\int \sin ^{-1} \sqrt{x} d x & =\int_{\mathrm{I}} \theta \sin 2 \theta d \theta \\
& =\theta\left(\frac{-\cos 2 \theta}{2}\right)-\int 1 \cdot \frac{(-\cos 2 \theta)}{2} d \theta \\
& =-\frac{\theta}{2} \cos 2 \theta+\int \frac{1}{2} \cos 2 \theta d \theta \\
& =-\frac{1}{2} \theta \cos 2 \theta+\frac{1}{4} \sin 2 \theta \\
& =-\frac{1}{2} \theta\left(1-2 \sin ^{2} \theta\right)+\frac{1}{2} \sin \theta \sqrt{1-\sin ^{2} \theta} \\
& =-\frac{1}{2} \sin ^{-1} \sqrt{x}(1-2 x)+\frac{1}{2} \sqrt{x} \cdot \sqrt{1-x} \tag{ii}
\end{align*}
$$

[integrating by parts]

From (i) and (ii), we get

$$
\begin{array}{ll}
& I=\frac{4}{\pi} \cdot\left\{-\frac{1}{2} \sin ^{-1} \sqrt{x}(1-2 x)+\frac{1}{2} \sqrt{x} \sqrt{1-x}\right\}-x+C \\
\therefore & I=\frac{-2}{\pi} \sin ^{-1} \sqrt{x}(1-2 x)+\frac{2}{\pi} \sqrt{x} \sqrt{1-x}-x+C .
\end{array}
$$

---

### Example: 25

Evaluate $\int \frac{\sqrt{x^{2}+1}\left\{\log \left(x^{2}+1\right)-2 \log x\right\}}{x^{4}} d x$.
[CBSE 2012, '14C]

#### Solution:

We have

$$
\begin{align*}
I & =\int \frac{\sqrt{x^{2}+1}}{x^{4}} \cdot \log \left(\frac{x^{2}+1}{x^{2}}\right) d x \\
& =\int \sqrt{1+\frac{1}{x^{2}}} \cdot \frac{1}{x^{3}} \log \left(1+\frac{1}{x^{2}}\right) d x \tag{i}
\end{align*}
$$

Putting $\left(1+\frac{1}{x^{2}}\right)=t$ and $\frac{-2}{x^{3}} d x=d t$, i.e., $\frac{1}{x^{3}} d x=-\frac{1}{2} d t$ in (i), we get

$$
\begin{aligned}
I & =-\frac{1}{2} \int(\log t) \sqrt{t} d t \\
& =-\frac{1}{2}\left\{\frac{2}{3}(\log t) t^{3 / 2}-\frac{2}{3} \int\left(\frac{1}{t} \times t^{3 / 2}\right) d t\right\} \\
& =-\frac{1}{3} t^{3 / 2}(\log t)+\frac{1}{3} \int t^{1 / 2} d t \\
& =-\frac{1}{3} t^{3 / 2}(\log t)+\frac{2}{9} t^{3 / 2}+C \\
& =-\frac{1}{3} t^{3 / 2}\left\{\log t-\frac{2}{3}\right\}+C \\
& =-\frac{1}{3}\left(1+\frac{1}{x^{2}}\right)^{3 / 2}\left\{\log \left(1+\frac{1}{x^{2}}\right)-\frac{2}{3}\right\}+C
\end{aligned}
$$

---

### Example: 26

Evaluate $\int \frac{\sqrt{1-\sin x}}{(1+\cos x)} e^{-x / 2} d x$.
[CBSE 2013C]

#### Solution:

Putting $\frac{-x}{2}=t$, we get $x=-2 t$ and $d x=-2 d t$.

$$
\begin{aligned}
\therefore \quad I & =\int \frac{\sqrt{1-\sin x}}{(1+\cos x)} e^{-x / 2} d x \\
& =\int \frac{\sqrt{1-\sin (-2 t)}}{\{1+\cos (-2 t)\}} e^{t}(-2 d t)=-2 \int \frac{\sqrt{1+\sin 2 t}}{(1+\cos 2 t)} e^{t} d t \\
& =-2 \int \frac{\sqrt{\cos ^{2} t+\sin ^{2} t+2 \sin t \cos t}}{2 \cos ^{2} t} e^{t} d t \\
& =-2 \int \frac{(\cos t+\sin t)}{2 \cos ^{2} t} e^{t} d t=-\int(\sec t+\sec t \tan t) e^{t} d t \\
& =-\int e^{t}\left\{f(t)+f^{\prime}(t)\right\} d t, \text { where } f(t)=\sec t \\
& =-e^{t} f(t)+C=-e^{-x / 2} \sec \left(\frac{-x}{2}\right)+C=-e^{-x / 2} \sec \frac{x}{2}+C
\end{aligned}
$$

---

## Integrals of the form $\int e^{x}\left[f(x)+f^{\prime}(x)\right] d x$

**THEOREM 1** $\int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x=e^{x} \cdot f(x)+C$.

**PROOF** $\int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x=\int e^{x} \cdot f(x) d x+\int e^{x} \cdot f^{\prime}(x) d x$

$$
=f(x) \cdot \int e^{x} d x-\int\left\{f^{\prime}(x) \cdot \int e^{x} d x\right\} d x+\int e^{x} f^{\prime}(x) d x+C
$$

[evaluating the first integral by parts]

$$
\begin{aligned}
& =e^{x} f(x)-\int e^{x} f^{\prime}(x) d x+\int e^{x} f^{\prime}(x) d x+C \\
& =e^{x} f(x)+C \\
\therefore \quad \int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x & =e^{x} f(x)+C
\end{aligned}
$$

---

### Example: 1

Evaluate:
- (i) $\int e^{x}\left(\frac{1}{x}-\frac{1}{x^{2}}\right) d x$
- (ii) $\int e^{x}\left(\frac{1}{x^{2}}-\frac{2}{x^{3}}\right) d x$
- (iii) $\int e^{x}\left\{\sin ^{-1} x+\frac{1}{\sqrt{1-x^{2}}}\right\} d x$
- (iv) $\int e^{x}(\tan x+\log \sec x) d x$

#### Solution:

We have

$$
\begin{aligned}
\text { (i) } I & =\int e^{x}\left\{\frac{1}{x}+\left(-\frac{1}{x^{2}}\right)\right\} d x \\
& =\int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x, \text { where } f(x)=\frac{1}{x} \text { and } f^{\prime}(x)=\frac{-1}{x^{2}} \\
& =e^{x} \cdot f(x)+C=e^{x} \cdot \frac{1}{x}+C=\frac{e^{x}}{x}+C \\
\text { (ii) } I & =\int e^{x}\left\{\frac{1}{x^{2}}+\left(\frac{-2}{x^{3}}\right)\right\} d x \\
& =\int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x, \text { where } f(x)=\frac{1}{x^{2}} \text { and } f^{\prime}(x)=\frac{-2}{x^{3}} \\
& =e^{x} \cdot f(x)+C=e^{x} \cdot \frac{1}{x^{2}}+C=\frac{e^{x}}{x^{2}}+C \\
\text { (iii) } I & =\int e^{x}\left\{\sin ^{-1} x+\frac{1}{\sqrt{1-x^{2}}}\right\} d x \\
& =\int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x, \text { where } f(x)=\sin ^{-1} x \text { and } f^{\prime}(x)=\frac{1}{\sqrt{1-x^{2}}} \\
& =e^{x} \cdot f(x)+C=e^{x} \cdot \sin { }^{-1} x+C=e^{x} \sin ^{-1} x+C \\
\text { (iv) } I & =\int e^{x}(\tan x+\log \sec x) d x \\
& =\int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x, \text { where } f(x)=\log (\sec x) \\
& =e^{x} f(x)+C=e^{x} \log (\sec x)+C
\end{aligned}
$$

---

### Example: 2

Evaluate $\int \frac{x e^{x}}{(1+x)^{2}} d x$.

#### Solution:

We have

$I=\int e^{x} \cdot\left\{\frac{x}{(1+x)^{2}}\right\} d x=\int e^{x} \cdot\left\{\frac{(1+x)-1}{(1+x)^{2}}\right\} d x$

$$
\begin{aligned}
& =\int e^{x} \cdot\left\{\frac{(1+x)}{(1+x)^{2}}-\frac{1}{(1+x)^{2}}\right\} d x=\int e^{x} \cdot\left\{\frac{1}{(1+x)}-\frac{1}{(1+x)^{2}}\right\} d x \\
& =\int e^{x} \cdot\left\{f(x)+f^{\prime}(x)\right\} d x, \text { where } f(x)=\frac{1}{1+x} \text { and } f^{\prime}(x)=\frac{-1}{(1+x)^{2}} \\
& =e^{x} \cdot f(x)+C=e^{x} \cdot \frac{1}{(1+x)}+C=\frac{e^{x}}{(1+x)}+C
\end{aligned}
$$

---

### Example: 3

Evaluate $\int e^{x}\left(\frac{1-\sin x}{1-\cos x}\right) d x$.

#### Solution:

We have $I=\int e^{x} \cdot\left(\frac{1-\sin x}{1-\cos x}\right) d x=\int e^{x} \cdot\left\{\frac{1}{(1-\cos x)}-\frac{\sin x}{(1-\cos x)}\right\} d x$

$$
\begin{aligned}
& =\int e^{x} \cdot\left\{\frac{1}{2 \sin ^{2}(x / 2)}-\frac{2 \sin (x / 2) \cos (x / 2)}{2 \sin ^{2}(x / 2)}\right\} d x \\
& =\int e^{x} \cdot\left\{\frac{1}{2} \operatorname{cosec}^{2} \frac{x}{2}-\cot \frac{x}{2}\right\} d x \\
& =\int e^{x} \cdot\left\{-\cot \frac{x}{2}+\frac{1}{2} \operatorname{cosec}^{2} \frac{x}{2}\right\} d x \\
& =\int e^{x} \cdot\left\{f(x)+f^{\prime}(x)\right\} d x \\
& \quad \text { where } f(x)=-\cot \frac{x}{2} \text { and } f^{\prime}(x)=\frac{1}{2} \operatorname{cosec}^{2} \frac{x}{2} \\
& =e^{x} \cdot f(x)+C=e^{x}\left(-\cot \frac{x}{2}\right)+C=-e^{x} \cot \frac{x}{2}+C
\end{aligned}
$$

---

### Example: 4

Evaluate $\int e^{x} \cdot\left\{\frac{2+\sin 2 x}{1+\cos 2 x}\right\} d x$.

#### Solution:

We have

$$
\begin{aligned}
I & =\int e^{x} \cdot\left\{\frac{2+\sin 2 x}{1+\cos 2 x}\right\} d x \\
& =\int e^{x} \cdot\left\{\frac{2}{(1+\cos 2 x)}+\frac{\sin 2 x}{(1+\cos 2 x)}\right\} d x \\
& =\int e^{x} \cdot\left\{\frac{2}{2 \cos ^{2} x}+\frac{2 \sin x \cos x}{2 \cos ^{2} x}\right\} d x=\int e^{x} \cdot\left\{\sec ^{2} x+\tan x\right\} d x \\
& =\int e^{x} \cdot\left\{\tan x+\sec ^{2} x\right\} d x \\
& =\int e^{x} \cdot\left\{f(x)+f^{\prime}(x)\right\} d x, \text { where } f(x)=\tan x \text { and } f^{\prime}(x)=\sec ^{2} x \\
& =e^{x} \cdot f(x)+C=e^{x} \tan x+C
\end{aligned}
$$

---

### Example: 5

Evaluate $\int \frac{\left(x^{2}+1\right) e^{x}}{(x+1)^{2}} d x$.
[CBSE 2005C, '06]

#### Solution:

We have

$$
\begin{aligned}
I & =\int e^{x} \cdot \frac{\left(x^{2}+1\right)}{(x+1)^{2}} d x=\int e^{x} \cdot\left\{\frac{(x+1)^{2}-2 x}{(x+1)^{2}}\right\} d x \\
& =\int e^{x} \cdot\left\{1-\frac{2 x}{(x+1)^{2}}\right\} d x=\int e^{x} d x-2 \int e^{x} \cdot \frac{x}{(x+1)^{2}} d x \\
& =e^{x}-2 \cdot \int e^{x} \cdot \frac{\{(x+1)-1\}}{(x+1)^{2}} d x=e^{x}-2 \cdot \int e^{x} \cdot\left\{\frac{1}{(x+1)}-\frac{1}{(x+1)^{2}}\right\} d x \\
& =e^{x}-2 \cdot \int e^{x} \cdot\left\{f(x)+f^{\prime}(x)\right\} d x \\
& \quad \text { where } f(x)=\frac{1}{(x+1)} \text { and } f^{\prime}(x)=\frac{-1}{(x+1)^{2}} \\
& =e^{x}-2 e^{x} \cdot f(x)+C=e^{x}-2 e^{x} \cdot \frac{1}{(x+1)}+C \\
& =e^{x} \cdot\left\{1-\frac{2}{(x+1)}\right\}+C=e^{x}\left(\frac{x-1}{x+1}\right)+C
\end{aligned}
$$

---

### Example: 6

Evaluate $\int e^{2 x}\left(\frac{\sin 4 x-2}{1-\cos 4 x}\right) d x$.
[CBSE 2007]

#### Solution:

Putting $2 x=t$ and $d x=\frac{1}{2} d t$, we get

$$
\begin{aligned}
I & =\frac{1}{2} \int e^{t}\left(\frac{\sin 2 t-2}{1-\cos 2 t}\right) d t=\frac{1}{2} \int e^{t}\left(\frac{2 \sin t \cos t-2}{2 \sin ^{2} t}\right) d t \\
& =\frac{1}{2} \int e^{t}\left\{\frac{\sin t \cos t-1}{\sin ^{2} t}\right\} d t=\frac{1}{2} \int e^{t}\left(\cot t-\operatorname{cosec}^{2} t\right) d t \\
& =\frac{1}{2} \int e^{t}\left\{f(t)+f^{\prime}(t)\right\} d t, \text { where } f(t)=\cot t \\
& =\frac{1}{2} e^{t} \cdot f(t)+C=\frac{1}{2} e^{t} \cot t+C=\frac{1}{2} e^{2 x} \cot 2 x+C
\end{aligned}
$$

---

## Integrals of the form $\int e^{k x} \cdot\left\{k \cdot f(x)+f^{\prime}(x)\right\} d x$

**THEOREM 2** $\int e^{k x}\left\{k \cdot f(x)+f^{\prime}(x)\right\} d x=e^{k x} \cdot f(x)+C$.

**PROOF** $\int e^{k x} \cdot\left\{k \cdot f(x)+f^{\prime}(x)\right\} d x$

$$
\begin{aligned}
& =k \cdot \int e^{k x} f(x) d x+\int e^{k x} f^{\prime}(x) d x \\
& =k \cdot\left[f(x) \cdot \frac{e^{k x}}{k}-\int f^{\prime}(x) \cdot \frac{e^{k x}}{k} d x\right]+\int e^{k x} f^{\prime}(x) d x+C
\end{aligned}
$$

[evaluating the first integral by parts]

$$
=e^{k x} \cdot f(x)-\int e^{k x} \cdot f^{\prime}(x) d x+\int e^{k x} f^{\prime}(x) d x+C=e^{k x} \cdot f(x)+C
$$

$$
\therefore \quad \int e^{k x} \cdot\left\{k \cdot f(x)+f^{\prime}(x)\right\} d x=e^{k x} \cdot f(x)+C .
$$

---

### Example: 7

Evaluate $\int e^{2 x} \cdot(-\sin x+2 \cos x) d x$.

#### Solution:

We have

$$
\begin{aligned}
I=\int e^{2 x} & \cdot\{2 \cos x-\sin x\} d x=2 \int e^{2 x} \cos x d x-\int e^{2 x} \sin x d x \\
& =2 \cdot\left[\cos x \cdot \frac{e^{2 x}}{2}-\int(-\sin x) \cdot \frac{e^{2 x}}{2} d x\right]-\int e^{2 x} \sin x d x \\
& \quad\left[\text { integrating } e^{2 x} \cos x \text { by parts }\right] \\
& =e^{2 x} \cos x+\int e^{2 x} \sin x d x-\int e^{2 x} \sin x d x+C \\
& =e^{2 x} \cos x+C
\end{aligned}
$$

---

## Integrals of the form $e^{a x} \cos (b x+c) \text { and } e^{a x} \sin (b x+c)$

### Example: 8

Evaluate $\int e^{a x} \cos (b x+c) d x$.
[CBSE 2002]

#### Solution:

Integrating by parts, taking $e^{a x}$ as the second function, we get

$$
\begin{aligned}
& \int e^{a x} \cos (b x+c) d x=\cos (b x+c) \cdot \frac{e^{a x}}{a}-\int\left\{-b \sin (b x+c) \cdot \frac{e^{a x}}{a}\right\} d x \\
& =\frac{e^{a x}}{a} \cos (b x+c)+\frac{b}{a} \int e^{a x} \sin (b x+c) d x \\
& =\frac{e^{a x}}{a} \cdot \cos (b x+c)+\frac{b}{a}\left[\sin (b x+c) \cdot \frac{e^{a x}}{a}-\int\left\{b \cos (b x+c) \cdot \frac{e^{a x}}{a}\right\}\right] d x+C \\
& \text { [integrating } e^{a x} \sin (b x+c) \text { by parts] } \\
& =\frac{e^{a x}}{a} \cdot \cos (b x+c)+\frac{b}{a^{2}} e^{a x} \sin (b x+c)-\frac{b^{2}}{a^{2}} \int e^{a x} \cos (b x+c) d x+C \\
& \therefore\left(1+\frac{b^{2}}{a^{2}}\right) \int e^{a x} \cos (b x+c) d x=\frac{e^{a x}}{a} \cos (b x+c)+\frac{b}{a^{2}} e^{a x} \sin (b x+c)+C \\
& \text { or } \int e^{a x} \cos (b x+c) d x=e^{a x}\left[\frac{a \cos (b x+c)+b \sin (b x+c)}{\left(a^{2}+b^{2}\right)}\right]+C^{\prime} \text {. }
\endAll$$

**REMARK** Put $a=r \cos \theta$ and $b=r \sin \theta$ so that

$$
\begin{aligned}
& r=\sqrt{a^{2}+b^{2}} \text { and } \theta=\tan ^{-1}\left(\frac{b}{a}\right) \\
\therefore \quad \begin{aligned}
\int e^{a x} \cos (b x+c) d x & =\frac{r e^{a x} \cos (b x+c-\theta)}{\left(a^{2}+b^{2}\right)} \\
& =e^{a x} \cdot \frac{\cos \left[b x+c-\tan ^{-1}(b / a)\right]}{\sqrt{a^{2}+b^{2}}}
\end{aligned} \\
& \text { Similarly, } \int e^{a x} \sin (b x+c) d x=e^{a x} \cdot \frac{\sin \left[b x+c-\tan ^{-1}(b / a)\right]}{\sqrt{a^{2}+b^{2}}}
\end{aligned}
$$

---