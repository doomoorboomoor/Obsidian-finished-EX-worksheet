## Integration Using Trigonometric Identities

When the integrand consists of trigonometric functions, we use known identities to convert it into a form which can easily be integrated. Some of the identities useful for this purpose are given below:

- $2 \sin ^{2}\left(\frac{x}{2}\right)=(1-\cos x)$
- $2 \cos ^{2}\left(\frac{x}{2}\right)=(1+\cos x)$
- $2 \sin a \cos b=\sin (a+b)+\sin (a-b)$
- $2 \cos a \sin b=\sin (a+b)-\sin (a-b)$
- $2 \cos a \cos b=\cos (a+b)+\cos (a-b)$
- $2 \sin a \sin b=\cos (a-b)-\cos (a+b)$

---

## Solved Examples

---

### Example 1: Evaluate:

1. $\int \sin ^{2} \frac{x}{2} d x$
2. $\int \tan ^{2} \frac{x}{2} d x$
3. $\int \cos ^{2} n x d x$
4. $\int \cos ^{5} x d x$
5. $\int \sin ^{7} x d x$
6. $\int \sin ^{3}(2 x+1) d x$

#### Solution:

$$
\begin{aligned}
& \text { (i) } \begin{aligned}
\int \sin ^{2} \frac{x}{2} d x & =\frac{1}{2} \int 2 \sin ^{2} \frac{x}{2} d x \\
& =\frac{1}{2} \int(1-\cos x) d x=\frac{1}{2} \int d x-\frac{1}{2} \int \cos x d x \\
& =\frac{1}{2} x-\frac{1}{2} \sin x+C
\end{aligned} \\
& \text { (ii) } \begin{aligned}
\int \tan ^{2} \frac{x}{2} d x & =\int\left(\sec ^{2} \frac{x}{2}-1\right) d x=\int \sec ^{2} \frac{x}{2} d x-\int d x \\
& =2 \int \sec ^{2} t d t-\int d x, \text { where } \frac{x}{2}=t \\
& =2 \tan t-x+C=2 \tan \frac{x}{2}-x+C \\
\text { (iii) } & \int \cos ^{2} n x d x \\
& =\frac{1}{2} \int 2 \cos ^{2} n x d x \\
& =\frac{1}{2} \int(1+\cos 2 n x) d x=\frac{1}{2} \int d x+\frac{1}{2} \int \cos 2 n x d x \\
& =\frac{x}{2}+\frac{1}{4 n} \sin 2 n x+C \\
\text { (iv) } & \int \cos ^{5} x d x \\
= & \int \cos ^{4} x \cdot \cos x d x \\
= & \int\left(1-\sin ^{2} x\right)^{2} \cdot \cos x d x=\int\left(1-t^{2}\right)^{2} d t, \text { where sin } x=t \\
= & \int\left(1+t^{4}-2 t^{2}\right) d t=\int d t+\int t^{4} d t-2 \int t^{2} d t \\
= & t+\frac{t^{5}}{5}-\frac{2 t^{3}}{3}+C=\sin x+\frac{1}{5} \sin ^{5} x-\frac{2}{3} \sin ^{3} x+C \\
\text { (v) } \int \sin ^{7} x d x & =\int \sin ^{6} x \cdot \sin x d x \\
& =\int\left(1-\cos ^{2} x\right)^{3} \sin x d x \\
& =-\int\left(1-t^{2}\right)^{3} d t, \text { where } \cos x=t \\
& =\int\left(t^{6}-3 t^{4}+3 t^{2}-1\right) d t=\frac{t^{7}}{7}-\frac{3 t^{5}}{5}+t^{3}-t+C \\
& =\frac{1}{7} \cos ^{7} x-\frac{3}{5} \cos ^{5} x+\cos ^{3} x-\cos x+C
\end{aligned}
\end{aligned}
$$

$$
\text { (vi) } \begin{aligned}
\int \sin ^{3}(2 x+1) d x & =\int\left\{1-\cos ^{2}(2 x+1)\right\} \cdot \sin (2 x+1) d x \\
& =-\frac{1}{2} \int\left(1-t^{2}\right) d t, \text { where } \cos (2 x+1)=t \\
& =-\frac{1}{2} \int d t+\frac{1}{2} \int t^{2} d t=-\frac{1}{2} t+\frac{1}{6} t^{3}+C \\
& =-\frac{1}{2} \cos (2 x+1)+\frac{1}{6} \cos ^{3}(2 x+1)+C
\endt{aligned}
$$

---

### Example 2: Evaluate $\int \cos m x \cos n x d x$, when (i) $m \neq n$ (ii) $m=n$.

#### Solution:

(i) When $m \neq n$, we have

$$
\begin{aligned}
\int \cos m x \cos n x d x & =\frac{1}{2} \int[\cos (m+n) x+\cos (m-n) x] d x \\
& =\frac{1}{2} \int \cos (m+n) x d x+\frac{1}{2} \int \cos (m-n) x d x \\
& =\frac{\sin (m+n) x}{2(m+n)}+\frac{\sin (m-n) x}{2(m-n)}+C
\end{aligned}
$$

(ii) When $m=n$, we have

$$
\begin{aligned}
\int \cos m x \cos n x d x & =\int \cos ^{2} n x d x \\
& =\frac{1}{2} \int 2 \cos ^{2} n x d x=\frac{1}{2} \int(1+\cos 2 n x) d x \\
& =\frac{1}{2} \int d x+\frac{1}{2} \int \cos 2 n x d x=\frac{x}{2}+\frac{\sin 2 n x}{4 n}+C
\end{aligned}
$$

---

### Example 3: Evaluate:

1. $\int \sin 3 x \sin 2 x d x$
2. $\int \cos 3 x \sin 2 x d x$
3. $\int \cos 4 x \cos x d x$ [CBSE 2001]
4. $\int \sin ^{3} x \cos ^{3} x d x$

#### Solution:

(i) Using $2 \sin a \sin b=\cos (a-b)-\cos (a+b)$, we have

$$
\begin{aligned}
\int \sin 3 x \sin 2 x d x & =\frac{1}{2} \int 2 \sin 3 x \sin 2 x d x \\
& =\frac{1}{2} \int(\cos x-\cos 5 x) d x \\
& =\frac{1}{2} \int \cos x d x-\frac{1}{2} \int \cos 5 x d x \\
& =\frac{1}{2} \sin x-\frac{\sin 5 x}{10}+C
\end{aligned}
$$

(ii) Using $2 \cos a \sin b=\sin (a+b)-\sin (a-b)$, we get

$$
\begin{aligned}
\int \cos 3 x \sin 2 x d x & =\frac{1}{2} \int 2 \cos 3 x \sin 2 x d x \\
& =\frac{1}{2} \int(\sin 5 x-\sin x) d x
\end{aligned}
$$

$$
\begin{aligned}
& =\frac{1}{2} \int \sin 5 x d x-\frac{1}{2} \int \sin x d x \\
& =\frac{-\cos 5 x}{10}+\frac{\cos x}{2}+C
\end{aligned}
$$

(iii) Using $2 \cos a \cos b=\cos (a+b)+\cos (a-b)$, we get

$$
\begin{aligned}
\int \cos 4 x \cos x d x & =\frac{1}{2} \int 2 \cos 4 x \cos x d x \\
& =\frac{1}{2} \int(\cos 5 x+\cos 3 x) d x \\
& =\frac{1}{2} \int \cos 5 x d x+\frac{1}{2} \int \cos 3 x d x \\
& =\frac{\sin 5 x}{10}+\frac{\sin 3 x}{6}+C
\end{aligned}
$$

$$
\text { (iv) } \begin{aligned}
\int \sin ^{3} x \cos ^{3} x d x & =\int \sin ^{3} x \cos ^{2} x \cos x d x \\
& =\int \sin ^{3} x\left(1-\sin ^{2} x\right) \cos x d x \\
& =\int t^{3}\left(1-t^{2}\right) d t, \text { where } \sin x=t \\
& =\int t^{3} d t-\int t^{5} d t=\frac{t^{4}}{4}-\frac{t^{6}}{6}+C \\
& =\frac{1}{4} \sin ^{4} x-\frac{1}{6} \sin ^{6} x+C
\end{aligned}
$$

---

### Example 4: Evaluate $\int \cos x \cos 2 x \cos 3 x d x$.

#### Solution:

$\int \cos x \cos 2 x \cos 3 x d x$

$$
\begin{aligned}
& =\frac{1}{2} \int(2 \cos x \cos 2 x) \cos 3 x d x \\
& =\frac{1}{2} \int(\cos 3 x+\cos x) \cos 3 x d x=\frac{1}{2} \int\left(\cos ^{2} 3 x+\cos x \cos 3 x\right) d x \\
& =\frac{1}{4} \int\left(2 \cos ^{2} 3 x\right) d x+\frac{1}{4} \int(2 \cos x \cos 3 x) d x \\
& =\frac{1}{4} \int(1+\cos 6 x) d x+\frac{1}{4} \int(\cos 4 x+\cos 2 x) d x \\
& =\frac{1}{4} \int d x+\frac{1}{4} \int \cos 6 x d x+\frac{1}{4} \int \cos 4 x d x+\frac{1}{4} \int \cos 2 x d x \\
& =\frac{1}{4} x+\frac{1}{4} \cdot \frac{\sin 6 x}{6}+\frac{1}{4} \cdot \frac{\sin 4 x}{4}+\frac{1}{4} \cdot \frac{\sin 2 x}{2}+C \\
& =\frac{x}{4}+\frac{\sin 6 x}{24}+\frac{\sin 4 x}{16}+\frac{\sin 2 x}{8}+C
\end{aligned}
$$

---

### Example 5: Evaluate $\int \sec ^{4} x \tan x d x$.

#### Solution:

$\int \sec ^{4} x \tan x d x=\int \sec ^{2} x \cdot \sec ^{2} x \tan x d x$

$$
\begin{aligned}
& =\int\left(1+\tan ^{2} x\right) \sec ^{2} x \tan x d x \\
& =\int\left(1+t^{2}\right) t d t, \text { where } \tan x=t \\
& =\int t d t+\int t^{3} d t=\frac{t^{2}}{2}+\frac{t^{4}}{4}+C \\
& =\frac{1}{2} \tan ^{2} x+\frac{1}{4} \tan ^{4} x+C
\end{aligned}
$$

---

### Example 6: Evaluate $\int \sin ^{4} x d x$. [CBSE 2004]

#### Solution:

$\int \sin ^{4} x d x=\frac{1}{4} \int\left(2 \sin ^{2} x\right)^{2} d x$

$$
\begin{aligned}
& =\frac{1}{4} \int(1-\cos 2 x)^{2} d x=\frac{1}{4} \int\left(1+\cos ^{2} 2 x-2 \cos 2 x\right) d x \\
& =\frac{1}{8} \int\left(2+2 \cos ^{2} 2 x-4 \cos 2 x\right) d x \\
& =\frac{1}{8} \int[2+(1+\cos 4 x)-4 \cos 2 x] d x \\
& =\frac{3}{8} \int d x+\frac{1}{8} \int \cos 4 x d x-\frac{1}{2} \int \cos 2 x d x \\
& =\frac{3}{8} x+\frac{\sin 4 x}{32}-\frac{\sin 2 x}{4}+C
\end{aligned}
$$

---

### Example 7: Evaluate $\int \frac{\sin x}{\sin (x-\alpha)} d x$. [CBSE 2003C, '04]

#### Solution:

Put $(x-\alpha)=t$ so that $x=(t+\alpha)$ and $d x=d t$.

$$
\begin{aligned}
\therefore \int \frac{\sin x}{\sin (x-\alpha)} d x & =\int \frac{\sin (t+\alpha)}{\sin t} d t \\
& =\int \frac{\sin t \cos \alpha+\cos t \sin \alpha}{\sin t} d t \\
& =\cos \alpha \cdot \int d t+\sin \alpha \cdot \int \cot t d t \\
& =\cos \alpha \cdot t+\sin \alpha \cdot \log |\sin t|+C \\
& =(\cos \alpha)(x-\alpha)+\sin \alpha \cdot \log |\sin (x-\alpha)|+C
\end{aligned}
$$

---

### Example 8: Evaluate:

1. $\int \frac{\sin 4 x}{\cos 2 x} d x$
2. $\int \frac{\sin 4 x}{\sin x} d x$

#### Solution:

$$
\text { (i) } \begin{aligned}
\int \frac{\sin 4 x}{\cos 2 x} d x & =\int \frac{2 \sin 2 x \cos 2 x}{\cos 2 x} d x \\
& =2 \int \sin 2 x d x=-\cos 2 x+C
\end{aligned}
$$

$$
\text { (ii) } \begin{aligned}
\int \frac{\sin 4 x}{\sin x} d x & =\int \frac{2 \sin 2 x \cos 2 x}{\sin x} d x \\
& =\int \frac{4 \sin x \cos x \cos 2 x}{\sin x} d x=2 \int 2 \cos x \cos 2 x d x \\
& =2 \int(\cos 3 x+\cos x) d x=2 \int \cos 3 x d x+2 \int \cos x d x \\
& =\frac{2 \sin 3 x}{3}+2 \sin x+C
\end{aligned}
$$

---

### Example 9: Evaluate $\int \sqrt{1+\sin x} d x$.

#### Solution:

$\int \sqrt{1+\sin x} d x=\int \sqrt{\sin ^{2} \frac{x}{2}+\cos ^{2} \frac{x}{2}+2 \sin \frac{x}{2} \cos \frac{x}{2}} d x$

$$
\begin{aligned}
& =\int\left(\sin \frac{x}{2}+\cos \frac{x}{2}\right) d x=\int \sin \frac{x}{2} d x+\int \cos \frac{x}{2} d x \\
& =-2 \cos \frac{x}{2}+2 \sin \frac{x}{2}+C
\end{aligned}
$$

---

### Example 10: Evaluate $\int \frac{\sin ^{2} x}{(1+\cos x)^{2}} d x$.

#### Solution:

$\int \frac{\sin ^{2} x}{(1+\cos x)^{2}} d x=\int\left(\frac{\sin x}{1+\cos x}\right)^{2} d x=\int\left[\frac{2 \sin (x / 2) \cos (x / 2)}{2 \cos ^{2}(x / 2)}\right]^{2} d x$

$$
\begin{aligned}
& =\int \tan ^{2}(x / 2) d x=\int\left(\sec ^{2} \frac{x}{2}-1\right) d x \\
& =\int \sec ^{2}(x / 2) d x-\int d x=2 \tan (x / 2)-x+C
\end{aligned}
$$

---

### Example 11: Evaluate:

1. $\int \sin x \sqrt{1-\cos 2 x} d x$
2. $\int \frac{\cos 2 x}{\sqrt{1+\cos 4 x}} d x$

#### Solution:

(i) $\int \sin x \sqrt{1-\cos 2 x} d x$

$$
\begin{aligned}
& =\int \sin x \cdot \sqrt{2 \sin ^{2} x} d x=\sqrt{2} \int \sin ^{2} x d x=\frac{1}{\sqrt{2}} \int 2 \sin ^{2} x d x \\
& =\frac{1}{\sqrt{2}} \int(1-\cos 2 x) d x=\frac{1}{\sqrt{2}} \int d x-\frac{1}{\sqrt{2}} \int \cos 2 x d x \\
& =\frac{1}{\sqrt{2}} x-\frac{\sin 2 x}{2 \sqrt{2}}+C
\end{aligned}
$$

(ii) $\int \frac{\cos 2 x}{\sqrt{1+\cos 4 x}} d x=\int \frac{\cos 2 x}{\sqrt{2 \cos ^{2} 2 x}} d x=\frac{1}{\sqrt{2}} \int d x=\frac{x}{\sqrt{2}}+C$.

---

### Example 12: Evaluate:

1. $\int \frac{d x}{a \sin x+b \cos x}$
2. $\int \frac{d x}{\sin x+\cos x}$

#### Solution:

(i) Put $a=r \cos \theta$ and $b=r \sin \theta$ so that

$$
r^{2}=\left(a^{2}+b^{2}\right) \text { and } \theta=\tan ^{-1}(b / a) .
$$

$$
\begin{aligned}
\therefore \int \frac{d x}{a \sin x+b \cos x} & =\int \frac{d x}{r \cos \theta \sin x+r \sin \theta \cos x} \\
& =\frac{1}{r} \int \frac{d x}{\sin (x+\theta)}=\frac{1}{r} \cdot \int \operatorname{cosec}(x+\theta) d x \\
& =\frac{1}{r} \log \left\{\tan \left(\frac{\theta+x}{2}\right)\right\}+C \\
& =\frac{1}{\sqrt{a^{2}+b^{2}}} \log \left[\tan \left\{\frac{1}{2} \tan ^{-1}\left(\frac{b}{a}\right)+\frac{x}{2}\right\}\right]+C
\end{aligned}
$$

(ii) We can write,

$$
\begin{aligned}
\int \frac{d x}{\sin x+\cos x} & =\frac{1}{\sqrt{2}} \int \frac{d x}{\frac{1}{\sqrt{2}} \sin x+\frac{1}{\sqrt{2}} \cos x} \\
& =\frac{1}{\sqrt{2}} \int \frac{d x}{\left(\cos \frac{\pi}{4} \sin x+\sin \frac{\pi}{4} \cos x\right)} \\
& =\frac{1}{\sqrt{2}} \int \frac{d x}{\sin \left(\frac{\pi}{4}+x\right)}=\frac{1}{\sqrt{2}} \int \operatorname{cosec}\left(\frac{\pi}{4}+x\right) d x \\
& =\frac{1}{\sqrt{2}} \log \tan \left(\frac{\pi}{8}+\frac{x}{2}\right)+C
\end{aligned}
$$

---

### Example 13: Evaluate:

1. $\int \frac{d x}{4 \cos x+3 \sin x}$
2. $\int \frac{d x}{(2 \sin x+3 \cos x)^{2}}$

#### Solution:

(i) Put $4=r \sin \theta$ and $3=r \cos \theta$ so that

$$
r^{2} =25 \text { and } \theta=\tan ^{-1}\left(\frac{4}{3}\right)
$$

$$
\begin{aligned}
\therefore \int \frac{d x}{4 \cos x+3 \sin x} & =\int \frac{d x}{r \sin \theta \cos x+r \cos \theta \sin x} \\
& =\frac{1}{r} \int \frac{d x}{\sin (\theta+x)}=\frac{1}{r} \int \operatorname{cosec}(\theta+x) d x \\
& =\frac{1}{r} \log \left\{\tan \left(\frac{\theta+x}{2}\right)\right\}+C \\
& =\frac{1}{5} \log \left[\tan \left\{\frac{1}{2} \tan ^{-1}\left(\frac{4}{3}\right)+\frac{x}{2}\right\}\right]+C
\end{aligned}
$$

(ii) Put $2=r \cos \theta$ and $3=r \sin \theta$ so that $r^{2}=13$ and $\theta=\tan ^{-1}\left(\frac{3}{2}\right)$.

$\because \int \frac{d x}{(2 \sin x+3 \cos x)^{2}}=\int \frac{d x}{(r \cos \theta \sin x+r \sin \theta \cos x)^{2}}$

$$
\begin{aligned}
& =\frac{1}{r^{2}} \int \frac{d x}{\sin ^{2}(\theta+x)}=\frac{1}{13} \cdot \int \operatorname{cosec}^{2}(\theta+x) d x \\
& =-\frac{1}{13} \cot (\theta+x)+C \\
& =-\frac{1}{13} \cot \left\{\tan ^{-1}\left(\frac{3}{2}\right)+x\right\}+C
\end{aligned}
$$

---

### Example 14: Evaluate $\int \frac{\cos x}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{3}} d x$.

#### Solution:

$\int \frac{\cos x}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{3}} d x=\int \frac{\cos ^{2}(x / 2)-\sin ^{2}(x / 2)}{\{\cos (x / 2)+\sin (x / 2)\}^{3}} d x$

$$
\begin{aligned}
& =\int \frac{\cos (x / 2)-\sin (x / 2)}{\left(\cos \frac{x}{2}+\sin \frac{x}{2}\right)^{2}} d x=2 \int \frac{1}{t^{2}} d t, \text { where } t=\cos \frac{x}{2}+\sin \frac{x}{2} \\
& =\frac{-2}{t}+C=\frac{-2}{\cos (x / 2)+\sin (x / 2)}+C
\end{aligned}
$$

---

### Example 15: Evaluate $\int \frac{d x}{\sqrt{1-\sin x}}$.

#### Solution:

$\int \frac{d x}{\sqrt{1-\sin x}}=\int \frac{d x}{\left[\sin ^{2}(x / 2)+\cos ^{2}(x / 2)-2 \sin \frac{x}{2} \cos \frac{x}{2}\right]^{1 / 2}}$

$$
\begin{aligned}
& =\int \frac{d x}{\left(\sin \frac{x}{2}-\cos \frac{x}{2}\right)}=\frac{1}{\sqrt{2}} \int \frac{d x}{\left(\frac{1}{\sqrt{2}} \cdot \sin \frac{x}{2}-\cos \frac{x}{2} \cdot \frac{1}{\sqrt{2}}\right)} \\
& =\frac{1}{\sqrt{2}} \cdot \int \frac{d x}{\left(\sin \frac{x}{2} \cos \frac{\pi}{4}-\cos \frac{x}{2} \sin \frac{\pi}{4}\right)} \\
& =\frac{1}{\sqrt{2}} \int \operatorname{cosec}\left(\frac{x}{2}-\frac{\pi}{4}\right) d x=\frac{1}{\sqrt{2}} 2 \cdot \log \left[\tan \left(\frac{x}{4}-\frac{\pi}{8}\right)\right]+C \\
& =\sqrt{2} \log \tan \left(\frac{x}{4}-\frac{\pi}{8}\right)+C
\end{aligned}
$$

---

### Example 16: Evaluate $\int \frac{\sin x}{\sqrt{1+\sin x}} d x$.

#### Solution:

$\int \frac{\sin x}{\sqrt{1+\sin x}} d x=\int \frac{(1+\sin x)-1}{\sqrt{1+\sin x}} d x$

$$
\begin{aligned}
= & \int \sqrt{1+\sin x} d x-\int \frac{d x}{\sqrt{1+\sin x}} \\
= & \int \sqrt{\cos ^{2} \frac{x}{2}+\sin ^{2} \frac{x}{2}+2 \sin \frac{x}{2} \cos \frac{x}{2}} d x \\
& \quad-\int \frac{d x}{\sqrt{\cos ^{2}(x / 2)+\sin ^{2}(x / 2)+2 \sin (x / 2) \cos (x / 2)}} \\
= & \int[\cos (x / 2)+\sin (x / 2)] d x-\int \frac{d x}{[\cos (x / 2)+\sin (x / 2)]} \\
= & \left(2 \sin \frac{x}{2}-2 \cos \frac{x}{2}\right)-\frac{1}{\sqrt{2}} \cdot \int \frac{d x}{\frac{1}{\sqrt{2}} \cos \frac{x}{2}+\frac{1}{\sqrt{2}} \sin \frac{x}{2}} \\
= & \left(2 \sin \frac{x}{2}-2 \cos \frac{x}{2}\right)-\frac{1}{\sqrt{2}} \cdot \int \frac{d x}{\sin \left(\frac{x}{2}+\frac{\pi}{4}\right)} \\
= & \left(2 \sin \frac{x}{2}-2 \cos \frac{x}{2}\right)-\frac{1}{\sqrt{2}} \int \operatorname{cosec}\left(\frac{x}{2}+\frac{\pi}{4}\right) d x \\
= & 2\left(\sin \frac{x}{2}-\cos \frac{x}{2}\right)-\frac{1}{\sqrt{2}} \times 2 \log \left|\tan \left(\frac{x}{4}+\frac{\pi}{8}\right)\right|+C \\
= & 2\left(\sin \frac{x}{2}-\cos \frac{x}{2}\right)-\sqrt{2} \log \left|\tan \left(\frac{x}{4}+\frac{\pi}{8}\right)\right|+C
\end{aligned}
$$

---