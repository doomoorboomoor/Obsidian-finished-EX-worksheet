## 4. Differentiation by Trigonometrical Transformations

### Some Useful Results

- (i) $(1-\cos x)=2 \sin ^{2}\left(\frac{x}{2}\right)$
- (ii) $(1+\cos x)=2 \cos ^{2}\left(\frac{x}{2}\right)$
- (iii) $\sin 3 x=\left(3 \sin x-4 \sin ^{3} x\right)$
- (iv) $\cos 3 x=\left(4 \cos ^{3} x-3 \cos x\right)$
- (v) $\sin x=\frac{2 \tan (x / 2)}{1+\tan ^{2}(x / 2)}$
- (vi) $\cos x=\frac{1-\tan ^{2}(x / 2)}{1+\tan ^{2}(x / 2)}$
- (vii) $\boldsymbol{\operatorname { t a n }}^{-1} x-\boldsymbol{\operatorname { t a n }}^{-1} y=\boldsymbol{\operatorname { t a n }}^{-1}\left\{\frac{x-y}{1+x y}\right\}$
- (viii) $\boldsymbol{\operatorname { t a n }}^{-1} x+\boldsymbol{\operatorname { t an }}^{-1} y=\boldsymbol{\operatorname { t an }}^{-1}\left\{\frac{x+y}{1-x y}\right\}$

---

### Some Useful Substitutions

Suppose we are given $\sin ^{-1} f(x)$, $\cos ^{-1} f(x)$, $\tan ^{-1} f(x)$, etc.

- **Rule 1.** If $f(x)=\sqrt{a^{2}-x^{2}}$, put $x=a \sin \theta$ or $x=a \cos \theta$.
- **Rule 2.** If $f(x)=\sqrt{a^{2}+x^{2}}$, put $x=a \tan \theta$ or $x=a \cot \theta$.
- **Rule 3.** If $f(x)=\sqrt{x^{2}-a^{2}}$, put $x=a \sec \theta$ or $x=a \operatorname{cosec} \theta$.
- **Rule 4.** If $f(x)=\sqrt{a-x}$, put $x=a \cos 2 \theta$.

---

## Solved Examples

### Example 1:

Differentiate each of the following w.r.t. $x$:
1.  $\tan ^{-1}\left(\frac{1-\cos x}{\sin x}\right)$
2.  $\tan ^{-1}\left(\frac{\cos x-\sin x}{\cos x+\sin x}\right)$

#### Solution:

- (i)
$$
\text { Let } \begin{aligned}
y & =\tan ^{-1}\left(\frac{1-\cos x}{\sin x}\right)=\tan ^{-1}\left\{\frac{2 \sin ^{2}(x / 2)}{2 \sin (x / 2) \cos (x / 2)}\right\} \\
& =\tan ^{-1}\left\{\tan \frac{x}{2}\right\}=\frac{x}{2}
\end{aligned}
$$

$\therefore \quad y=\frac{x}{2}$.

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{x}{2}\right)=\frac{1}{2}$.

- (ii) Let $y=\tan ^{-1}\left(\frac{\cos x-\sin x}{\cos x+\sin x}\right)=\tan ^{-1}\left(\frac{1-\tan x}{1+\tan x}\right)$
[on dividing num. and denom. by $\cos x$]

$$
\begin{aligned}
& =\tan ^{-1}\left\{\tan \left(\frac{\pi}{4}-x\right)\right\}=\left(\frac{\pi}{4}-x\right) . \\
\therefore \quad y & =\left(\frac{\pi}{4}-x\right) .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{4}-x\right)=\frac{d}{d x}\left(\frac{\pi}{4}\right)-\frac{d}{d x}(x)=(0-1)=-1$.

---

### Example 2:

Differentiate w.r.t. $x$:
1.  $\tan ^{-1}\left(\frac{\cos x}{1+\sin x}\right)$
2.  $\tan ^{-1}(\sec x+\tan x)$

#### Solution:

- (i) Let $y=\tan ^{-1}\left(\frac{\cos x}{1+\sin x}\right)=\tan ^{-1}\left\{\frac{\sin \left(\frac{\pi}{2}-x\right)}{1+\cos \left(\frac{\pi}{2}-x\right)}\right\}$

$$
\begin{aligned}
& =\tan ^{-1}\left\{\frac{2 \sin \left(\frac{\pi}{4}-\frac{x}{2}\right) \cos \left(\frac{\pi}{4}-\frac{x}{2}\right)}{2 \cos ^{2}\left(\frac{\pi}{4}-\frac{x}{2}\right)}\right\} \\
& =\tan ^{-1}\left\{\tan \left(\frac{\pi}{4}-\frac{x}{2}\right)\right\}=\left(\frac{\pi}{4}-\frac{x}{2}\right) \\
& =\left(\frac{\pi}{4}-\frac{x}{2}\right)
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{4}-\frac{x}{2}\right)=\frac{d}{d x}\left(\frac{\pi}{4}\right)-\frac{d}{d x}\left(\frac{x}{2}\right)=\left(0-\frac{1}{2}\right)=\frac{-1}{2}$.

- (ii) Let $y=\tan ^{-1}(\sec x+\tan x)$

$$
\begin{aligned}
& =\tan ^{-1}\left(\frac{1}{\cos x}+\frac{\sin x}{\cos x}\right)=\tan ^{-1}\left(\frac{1+\sin x}{\cos x}\right) \\
& =\tan ^{-1}\left\{\frac{1-\cos \left(\frac{\pi}{2}+x\right)}{\sin \left(\frac{\pi}{2}+x\right)}\right\} \\
& \quad\left\{\because \cos \left(\frac{\pi}{2}+x\right)=-\sin x ; \sin \left(\frac{\pi}{2}+x\right)=\cos x\right\}
\end{aligned}
$$

$$
\begin{aligned}
& \quad=\tan ^{-1}\left\{\frac{2 \sin ^{2}\left(\frac{\pi}{4}+\frac{x}{2}\right)}{2 \sin \left(\frac{\pi}{4}+\frac{x}{2}\right) \cos \left(\frac{\pi}{4}+\frac{x}{2}\right)}\right\} \\
& \quad=\tan ^{-1}\left\{\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right\}=\left(\frac{\pi}{4}+\frac{x}{2}\right) . \\
& \therefore y=\left(\frac{\pi}{4}+\frac{x}{2}\right) . \\
& \text { Hence, } \frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{4}+\frac{x}{2}\right)=\frac{d}{d x}\left(\frac{\pi}{4}\right)+\frac{d}{d x}\left(\frac{x}{2}\right)=\left(0+\frac{1}{2}\right)=\frac{1}{2} .
\end{aligned}
$$

---

### Example 3:

Differentiate w.r.t. $x$:
(i) $\tan ^{-1}\left\{\sqrt{\frac{1+\cos x}{1-\cos x}}\right\}$ (ii) $\tan ^{-1}\left\{\sqrt{\frac{1+\sin x}{1-\sin x}}\right\}$
[CBSE 2003C, '04C]

#### Solution:

- (i) Let $y=\tan ^{-1}\left\{\sqrt{\frac{1+\cos x}{1-\cos x}}\right\}=\tan ^{-1}\left\{\sqrt{\frac{2 \cos ^{2}(x / 2)}{2 \sin ^{2}(x / 2)}}\right\}$

$$
=\tan ^{-1}\left(\cot \frac{x}{2}\right)=\tan ^{-1}\left\{\tan \left(\frac{\pi}{2}-\frac{x}{2}\right)\right\}=\left(\frac{\pi}{2}-\frac{x}{2}\right)
$$

$\therefore \quad y=\left(\frac{\pi}{2}-\frac{x}{2}\right)$.

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{2}-\frac{x}{2}\right)=\frac{d}{d x}\left(\frac{\pi}{2}\right)-\frac{d}{d x}\left(\frac{x}{2}\right)=\left(0-\frac{1}{2}\right)=\frac{-1}{2}$.

- (ii) Let $y=\tan ^{-1}\left\{\sqrt{\frac{1+\sin x}{1-\sin x}}\right\}=\tan ^{-1}\left\{\frac{1-\cos \left(\frac{\pi}{2}+x\right)}{1+\cos \left(\frac{\pi}{2}+x\right)}\right\}^{\frac{1}{2}}$

$$
\begin{aligned}
& =\tan ^{-1}\left\{\frac{2 \sin ^{2}\left(\frac{\pi}{4}+\frac{x}{2}\right)}{2 \cos ^{2}\left(\frac{\pi}{4}+\frac{x}{2}\right)}\right\}^{\frac{1}{2}}=\tan ^{-1}\left\{\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right\}=\left(\frac{\pi}{4}+\frac{x}{2}\right) \\
\therefore & y=\left(\frac{\pi}{4}+\frac{x}{2}\right)
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{4}+\frac{x}{2}\right)=\frac{d}{d x}\left(\frac{\pi}{4}\right)+\frac{d}{d x}\left(\frac{x}{2}\right)=\left(0+\frac{1}{2}\right)=\frac{1}{2}$.

---

### Example 4:

Differentiate $\cos ^{-1}\left\{\sqrt{\frac{1+\cos x}{2}}\right\}$ w.r.t. $x$.

#### Solution:

Let $y=\cos ^{-1}\left\{\sqrt{\frac{1+\cos x}{2}}\right\}=\cos ^{-1}\left\{\sqrt{\frac{2 \cos ^{2}(x / 2)}{2}}\right\}$

$$
\begin{aligned}
& =\cos ^{-1}\{\cos (x / 2)\}=\frac{x}{2} . \\
\therefore \quad y & =\frac{x}{2} .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{x}{2}\right)=\frac{1}{2}$.

---

### Example 5:

If $y=\cot ^{-1} \sqrt{\frac{1-\sin x}{1+\sin x}}$, find $\frac{d y}{d x}$.
[CBSE 2004C]

#### Solution:

We have

$$
\begin{aligned}
y & =\cot ^{-1} \sqrt{\frac{1-\sin x}{1+\sin x}}=\cot ^{-1} \sqrt{\frac{1+\cos \left(\frac{\pi}{2}+x\right)}{1-\cos \left(\frac{\pi}{2}+x\right)}} \\
& =\cot ^{-1} \sqrt{\frac{2 \cos ^{2}\left(\frac{\pi}{4}+\frac{x}{2}\right)}{2 \sin ^{2}\left(\frac{\pi}{4}+\frac{x}{2}\right)}}=\cot ^{-1}\left\{\cot \left(\frac{\pi}{4}+\frac{x}{2}\right)\right\}=\left(\frac{\pi}{4}+\frac{x}{2}\right) . \\
\therefore \quad \frac{d y}{d x} & =\frac{d}{d x}\left(\frac{\pi}{4}+\frac{x}{2}\right)=\frac{d}{d x}\left(\frac{\pi}{4}\right)+\frac{d}{d x}\left(\frac{x}{2}\right)=\left(0+\frac{1}{2}\right)=\frac{1}{2} .
\end{aligned}
$$

---

### Example 6:

If $y=\cot ^{-1} \frac{\sqrt{1+\sin x}+\sqrt{1-\sin x}}{\sqrt{1+\sin x}-\sqrt{1-\sin x}}$ and $0<x<\frac{\pi}{2}$, find $\frac{d y}{d x}$.
[CBSE 2008]

#### Solution:

We have

$$
\begin{aligned}
& (1+\sin x)=\left\{\cos ^{2}(x / 2)+\sin ^{2}(x / 2)+2 \sin (x / 2) \cos (x / 2)\right\} \\
& =\{\cos (x / 2)+\sin (x / 2)\}^{2} .
\end{aligned}
$$

$$
\begin{aligned}
& (1-\sin x)=\left\{\cos ^{2}(x / 2)+\sin ^{2}(x / 2)-2 \sin (x / 2) \cos (x / 2)\right\} \\
& =\{\cos (x / 2)-\sin (x / 2)\}^{2} .
\end{aligned}
$$

$\therefore \quad \sqrt{1+\sin x}=\sqrt{\{\cos (x / 2)+\sin (x / 2)\}^{2}}=\cos \left(\frac{x}{2}\right)+\sin \left(\frac{x}{2}\right)$
and $\sqrt{1-\sin x}=\sqrt{\{\cos (x / 2)-\sin (x / 2)\}^{2}}=\cos \left(\frac{x}{2}\right)-\sin \left(\frac{x}{2}\right)$.

$$
\begin{aligned}
\therefore \quad y & =\cot ^{-1}\left\{\frac{[\cos (x / 2)+\sin (x / 2)]+[\cos (x / 2)-\sin (x / 2)]}{[\cos (x / 2)+\sin (x / 2)]-[\cos (x / 2)-\sin (x / 2)]}\right\} \\
& =\cot ^{-1}\left\{\frac{2 \cos (x / 2)}{2 \sin (x / 2)}\right\}=\cot ^{-1}\{\cot (x / 2)\}=\frac{x}{2}
\end{aligned}
$$

$$
\Rightarrow \quad \frac{d y}{d x}=\frac{d}{d x}\left(\frac{x}{2}\right)=\frac{1}{2}
$$

---

### Example 7:

If $y=\tan ^{-1} \frac{(\sqrt{1+\sin x}+\sqrt{1-\sin x})}{(\sqrt{1+\sin x}-\sqrt{1-\sin x})}$, find $\frac{d y}{d x}$.
[CBSE 2004]

#### Solution:

We have

$$
\begin{aligned}
y & =\tan ^{-1}\left\{\frac{(\sqrt{1+\sin x}+\sqrt{1-\sin x}}{\sqrt{1+\sin x}-\sqrt{1-\sin x}} \times \frac{(\sqrt{1+\sin x}+\sqrt{1-\sin x}}{(\sqrt{1+\sin x}+\sqrt{1-\sin x}}\right\} \\
& =\tan ^{-1}\left\{\frac{(1+\sin x)+(1-\sin x)+2 \sqrt{1-\sin ^{2} x}}{(1+\sin x)-(1-\sin x)}\right\}=\tan ^{-1}\left(\frac{1+\cos x}{\sin x}\right) \\
& =\tan ^{-1}\left\{\frac{2 \cos ^{2}(x / 2)}{2 \sin (x / 2) \cos (x / 2)}\right\}=\tan ^{-1}\left\{\cot \frac{x}{2}\right\}=\tan ^{-1}\left\{\tan \left(\frac{\pi}{2}-\frac{x}{2}\right)\right\} \\
& =\left(\frac{\pi}{2}-\frac{x}{2}\right) \\
\therefore & \frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{2}-\frac{x}{2}\right)=\frac{d}{d x}\left(\frac{\pi}{2}\right)-\frac{d}{d x}\left(\frac{x}{2}\right)=\left(0-\frac{1}{2}\right)=-\frac{1}{2}
\end{aligned}
$$

---

### Example 8:

Differentiate w.r.t. $x$:
(i) $\cot ^{-1}\left(\frac{1}{x}\right)$
(ii) $\tan ^{-1}\left(\frac{2 x}{1-x^{2}}\right)$
(iii) $\cot ^{-1}\left(\frac{1-x}{1+x}\right)$

#### Solution:

- (i) Let $y=\cot ^{-1}\left(\frac{1}{x}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
y & =\cot ^{-1}\left(\frac{1}{\tan \theta}\right)=\cot ^{-1}(\cot \theta)=\theta=\tan ^{-1} x \\
\therefore \quad \frac{d y}{d x} & =\frac{1}{\left(1+x^{2}\right)}
\end{aligned}
$$

Hence, $\frac{d}{d x}\left\{\cot ^{-1}\left(\frac{1}{x}\right)\right\}=\frac{1}{\left(1+x^{2}\right)}$.

- (ii) Let $y=\tan ^{-1}\left(\frac{2 x}{1-x^{2}}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
& \qquad y=\tan ^{-1}\left(\frac{2 \tan \theta}{1-\tan ^{2} \theta}\right)=\tan ^{-1}(\tan 2 \theta)=2 \theta=2 \tan ^{-1} x \\
& \therefore \quad \frac{d y}{d x}=\frac{2}{\left(1+x^{2}\right)} \\
& \text { Hence, } \frac{d}{d x}\left\{\tan ^{-1}\left(\frac{2 x}{1-x^{2}}\right)\right\}=\frac{2}{\left(1+x^{2}\right)}
\end{aligned}
$$

- (iii) Let $y=\cot ^{-1}\left(\frac{1-x}{1+x}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
y & =\cot ^{-1}\left(\frac{1-\tan \theta}{1+\tan \theta}\right)=\cot ^{-1}\left\{\tan \left(\frac{\pi}{4}-\theta\right)\right\} \\
& =\cot ^{-1}\left[\cot \left\{\frac{\pi}{2}-\left(\frac{\pi}{4}-\theta\right)\right\}\right]=\left(\frac{\pi}{4}+\theta\right)=\frac{\pi}{4}+\tan ^{-1} x \\
\therefore \quad & \frac{d y}{d x}=\frac{1}{\left(1+x^{2}\right)} .
\end{aligned}
$$

Hence, $\frac{d}{d x}\left\{\cot ^{-1}\left(\frac{1-x}{1+x}\right)\right\}=\frac{1}{\left(1+x^{2}\right)}$.

---

### Example 9:

Differentiate w.r.t. $x$:
(i) $\cos ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)$
(ii) $\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)$
(iii) $\sec ^{-1}\left(\frac{1}{2 x^{2}-1}\right)$

#### Solution:

- (i) Let $y=\cos ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
& \quad y=\cos ^{-1}\left(\frac{1-\tan ^{2} \theta}{1+\tan ^{2} \theta}\right)=\cos ^{-1}(\cos 2 \theta)=2 \theta=2 \tan ^{-1} x . \\
& \therefore \quad \frac{d y}{d x}=\frac{2}{\left(1+x^{2}\right)} . \\
& \text { Hence, } \frac{d}{d x}\left\{\cos ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)\right\}=\frac{2}{\left(1+x^{2}\right)} .
\end{aligned}
$$

- (ii) Let $y=\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
& \qquad y=\sin ^{-1}\left(\frac{2 \tan \theta}{1+\tan ^{2} \theta}\right)=\sin ^{-1}(\sin 2 \theta)=2 \theta=2 \tan ^{-1} x . \\
& \therefore \quad \frac{d y}{d x}=\frac{2}{\left(1+x^{2}\right)} . \\
& \text { Hence, } \frac{d}{d x}\left\{\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)\right\}=\frac{2}{\left(1+x^{2}\right)} .
\end{aligned}
$$

- (iii) Let $y=\sec ^{-1}\left(\frac{1}{2 x^{2}-1}\right)$.
Putting $x=\cos \theta$, we get

$$
\begin{aligned}
y & =\sec ^{-1}\left(\frac{1}{2 \cos ^{2} \theta-1}\right)=\sec ^{-1}\left(\frac{1}{\cos 2 \theta}\right) \\
& =\sec ^{-1}(\sec 2 \theta)=2 \theta=2 \cos ^{-1} x
\end{aligned}
$$

$$
\therefore \quad y=2 \cos ^{-1} x .
$$

Hence, $\frac{d y}{d x}=2 \frac{d}{d x}\left(\cos ^{-1} x\right)=\frac{-2}{\sqrt{1-x^{2}}}$.

---

### Example 10:

Differentiate w.r.t. $x$:
(i) $\cos ^{-1}\left(4 x^{3}-3 x\right)$
(ii) $\sin ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)$
(iii) $\sec ^{-1}\left(\frac{x^{2}+1}{x^{2}-1}\right)$

#### Solution:

- (i) Let $y=\cos ^{-1}\left(4 x^{3}-3 x\right)$.
Putting $x=\cos \theta$, we get

$$
\begin{aligned}
y=\cos ^{-1}( & \left.4 \cos ^{3} \theta-3 \cos \theta\right)=\cos ^{-1}(\cos 3 \theta)=3 \theta \\
\therefore \quad y=3 \theta & \Rightarrow y=3 \cos ^{-1} x \\
& \Rightarrow \frac{d y}{d x}=\frac{-3}{\sqrt{1-x^{2}}}
\end{aligned}
$$

- (ii) Let $y=\sin ^{-1}\left(\frac{1-x^{2}}{1+x^{2}}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
y & =\sin ^{-1}\left(\frac{1-\tan ^{2} \theta}{1+\tan ^{2} \theta}\right)=\sin ^{-1}(\cos 2 \theta)=\sin ^{-1}\left[\sin \left(\frac{\pi}{2}-2 \theta\right)\right] \\
& =\left(\frac{\pi}{2}-2 \theta\right)=\left(\frac{\pi}{2}-2 \tan ^{-1} x\right) . \\
\therefore y & =\left(\frac{\pi}{2}-2 \tan ^{-1} x\right) .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left(\frac{\pi}{2}-2 \tan ^{-1} x\right)=\frac{d}{d x}\left(\frac{\pi}{2}\right)-2 \cdot \frac{d}{d x}\left(\tan ^{-1} x\right)$

$$
=\left\{0-\frac{2}{\left(1+x^{2}\right)}\right\}=\frac{-2}{\left(1+x^{2}\right)}
$$

- (iii) Let $y=\sec ^{-1}\left(\frac{x^{2}+1}{x^{2}-1}\right)$.
Putting $x=\cot \theta$, we get

$$
\begin{aligned}
y & =\sec ^{-1}\left(\frac{\cot ^{2} \theta+1}{\cot ^{2} \theta-1}\right)=\sec ^{-1}\left(\frac{1+\tan ^{2} \theta}{1-\tan ^{2} \theta}\right) \\
& =\sec ^{-1}(\sec 2 \theta)=2 \theta=2 \cot ^{-1} x . \\
\therefore \quad \frac{d y}{d x} & =\frac{-2}{\left(1+x^{2}\right)} .
\end{aligned}
$$

Hence, $\frac{d}{d x}\left\{\sec ^{-1}\left(\frac{x^{2}+1}{x^{2}-1}\right)\right\}=\frac{-2}{\left(1+x^{2}\right)}$.

---

### Example 11:

Differentiate $\cot ^{-1}\left(\frac{1-x}{1+x}\right)$ w.r.t. $x$.
[CBSE 2004]

#### Solution:

Let $y=\cot ^{-1}\left(\frac{1-x}{1+x}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
y & =\cot ^{-1}\left(\frac{1-\tan \theta}{1+\tan \theta}\right)=\cot ^{-1}\left\{\tan \left(\frac{\pi}{4}-\theta\right)\right\} \\
& =\cot ^{-1}\left[\cot \left\{\frac{\pi}{2}-\left(\frac{\pi}{4}-\theta\right)\right\}\right]=\cot ^{-1}\left[\cot \left(\frac{\pi}{4}+\theta\right)\right] \\
& =\left(\frac{\pi}{4}+\theta\right) \\
& =\frac{\pi}{4}+\tan ^{-1} x \quad\left[\because \quad x=\tan \theta \Rightarrow \theta=\tan ^{-1} x\right] . \\
\therefore \quad y & =\frac{\pi}{4}+\tan ^{-1} x \\
\Rightarrow \quad \frac{d y}{d x} & =\frac{d}{d x}\left\{\frac{\pi}{4}+\tan ^{-1} x\right\}=\frac{d}{d x}\left(\frac{\pi}{4}\right)+\frac{d}{d x}\left(\tan ^{-1} x\right) \\
& =\left\{0+\frac{1}{\left(1+x^{2}\right)}\right\}=\frac{1}{\left(1+x^{2}\right)} .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{1}{\left(1+x^{2}\right)}$.

---

### Example 12:

Differentiate $\tan ^{-1}\left\{\frac{\sqrt{1+x^{2}}-1}{x}\right\}$ w.r.t. $x$.
[CBSE 2004]

#### Solution:

Let $y=\tan ^{-1}\left\{\frac{\sqrt{1+x^{2}}-1}{x}\right\}$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
y & =\tan ^{-1}\left\{\frac{\sqrt{1+\tan ^{2} \theta}-1}{\tan \theta}\right\}=\tan ^{-1}\left\{\frac{\sec \theta-1}{\tan \theta}\right\} \\
& =\tan ^{-1}\left\{\frac{\left(\frac{1}{\cos \theta}-1\right)}{\sin \theta} \cdot \cos \theta\right\}=\tan ^{-1}\left(\frac{1-\cos \theta}{\sin \theta}\right) \\
& =\tan ^{-1}\left\{\frac{2 \sin ^{2}(\theta / 2)}{2 \sin (\theta / 2) \cos (\theta / 2)}\right\}=\tan ^{-1}\left\{\tan \frac{\theta}{2}\right\} \\
& =\frac{\theta}{2}=\frac{1}{2} \tan ^{-1} x
\end{aligned}
$$

$$
\begin{aligned}
& \therefore y=\frac{1}{2} \tan ^{-1} x \\
& \Rightarrow \frac{d y}{d x}=\frac{1}{2} \cdot \frac{d}{d x}\left(\tan ^{-1} x\right)=\frac{1}{2\left(1+x^{2}\right)}
\end{aligned}
$$

---

### Example 13:

If $y=\tan ^{-1}\left\{\frac{\sqrt{1+x^{2}}-\sqrt{1-x^{2}}}{\sqrt{1+x^{2}}-\sqrt{1-x^{2}}}\right\}$, find $\frac{d y}{d x}$.
[CBSE 2006]

#### Solution:

Putting $x^{2}=\cos \theta$, we get

$$
\begin{aligned}
y & =\tan ^{-1}\left\{\frac{\sqrt{1+\cos \theta}-\sqrt{1-\cos \theta}}{\sqrt{1+\cos \theta}-\sqrt{1-\cos \theta}}\right\} \\
& =\tan ^{-1}\left\{\frac{\sqrt{2 \cos ^{2}(\theta / 2)}-\sqrt{2 \sin ^{2}(\theta / 2)}}{\sqrt{2 \cos ^{2}(\theta / 2)}+\sqrt{2} \sin ^{2}(\theta / 2)}\right\} \\
& =\tan ^{-1}\left\{\frac{\sqrt{2} \cos (\theta / 2)-\sqrt{2} \sin (\theta / 2)}{\sqrt{2} \cos (\theta / 2)+\sqrt{2} \sin (\theta / 2)}\right\}=\tan ^{-1}\left\{\frac{\cos (\theta / 2)-\sin (\theta / 2)}{\cos (\theta / 2)+\sin (\theta / 2)}\right\} \\
& =\tan ^{-1}\left\{\frac{1-\tan (\theta / 2)}{1+\tan (\theta / 2)}\right\}=\tan ^{-1}\left\{\tan \left(\frac{\pi}{4}-\frac{\theta}{2}\right)\right\} \\
& =\left(\frac{\pi}{4}-\frac{\theta}{2}\right)=\frac{\pi}{4}-\frac{1}{2} \cos ^{-1} x^{2} . \\
\therefore & \frac{d y}{d x}=\frac{d}{d x}\left\{\frac{\pi}{4}-\frac{1}{2} \cos ^{-1} x^{2}\right\}=\frac{d}{d x}\left(\frac{\pi}{4}\right)-\frac{1}{2} \cdot \frac{d}{d x}\left(\cos ^{-1} x^{2}\right) \\
& \quad=\left\{0-\frac{1}{2} \cdot \frac{-1}{\sqrt{1-x^{4}}} \cdot 2 x\right\}=\frac{x}{\sqrt{1-x^{4}}} \cdot
\end{aligned}
$$

---

### Example 14:

If $y=\sin ^{-1}\left[x \sqrt{1-x}-\sqrt{x} \sqrt{1-x^{2}}\right]$, find $\frac{d y}{d x}$.
[CBSE 2010]

#### Solution:

Putting $x=\sin \theta$ and $\sqrt{x}=\sin \phi$, we get

$$
\begin{aligned}
y= & \sin ^{-1}[\sin \theta \cos \phi-\sin \phi \cos \theta]=\sin ^{-1}[\sin (\theta-\phi)] \\
= & (\theta-\phi)=\sin ^{-1} x-\sin ^{-1} \sqrt{x} \\
\therefore \quad y= & \sin ^{-1} x-\sin ^{-1} \sqrt{x} \\
\Rightarrow \quad \frac{d y}{d x} & =\frac{d}{d x}\left\{\sin ^{-1} x-\sin ^{-1} \sqrt{x}\right\} \\
& =\frac{d}{d x}\left(\sin ^{-1} x\right)-\frac{d}{d x}\left\{\sin ^{-1} \sqrt{x}\right\} \\
& =\left[\frac{1}{\sqrt{1-x^{2}}}-\frac{1}{2 \sqrt{x} \cdot \sqrt{1-x}}\right]
\end{aligned}
$$

---

### Example 15:

Differentiate $\tan ^{-1}\left(\frac{x^{1 / 3}+a^{1 / 3}}{1-x^{1 / 3} a^{1 / 3}}\right)$ w.r.t. $x$.

#### Solution:

Let $y=\tan ^{-1}\left(\frac{x^{1 / 3}+a^{1 / 3}}{1-x^{1 / 3} a^{1 / 3}}\right)$.
Putting $x^{1 / 3}=\tan \theta$ and $a^{1 / 3}=\tan \phi$, we get

$$
\begin{aligned}
y & =\tan ^{-1}\left(\frac{\tan \theta+\tan \phi}{1-\tan \theta \tan \phi}\right)=\tan ^{-1}[\tan (\theta+\phi)] \\
& =(\theta+\phi)=\tan ^{-1}\left(x^{1 / 3}\right)+\tan ^{-1}\left(a^{1 / 3}\right) . \\
\therefore \quad \frac{d y}{d x} & =\frac{d}{d x}\left\{\tan ^{-1}\left(x^{1 / 3}\right)+\tan ^{-1}\left(a^{1 / 3}\right)\right\} \\
& =\frac{d}{d x}\left\{\tan ^{-1}\left(x^{1 / 3}\right)\right\}+\frac{d}{d x}\left\{\tan ^{-1}\left(a^{1 / 3}\right)\right\}=\frac{1}{\left(1+x^{2 / 3}\right)} \cdot \frac{1}{3} x^{-2 / 3} \\
& =\frac{1}{3 x^{2 / 3}\left(1+x^{2 / 3}\right)} \quad\left[\because \tan ^{-1}\left(a^{1 / 3}\right)=\text { constant }\right] .
\end{aligned}
$$

---

### Example 16:

Differentiate $\tan ^{-1}\left(\frac{a \cos x-b \sin x}{b \cos x+a \sin x}\right)$ w.r.t. $x$.

#### Solution:

Let $y=\tan ^{-1}\left(\frac{a \cos x-b \sin x}{b \cos x+a \sin x}\right)$.
Putting $a=r \sin \theta$ and $b=r \cos \theta$, we get

$$
\begin{aligned}
y & =\tan ^{-1}\left\{\frac{r(\sin \theta \cos x-\cos \theta \sin x)}{r(\cos \theta \cos x+\sin \theta \sin x)}\right\} \\
& =\tan ^{-1}\left\{\frac{\sin (\theta-x)}{\cos (\theta-x)}\right\}=\tan ^{-1}\{\tan (\theta-x)\} \\
& =\theta-x=\left(\tan ^{-1} \frac{a}{b}-x\right) \quad\left[\because \frac{a}{b}=\tan \theta \Rightarrow \theta=\tan ^{-1} \frac{a}{b}\right] . \\
\therefore \quad \frac{d y}{d x} & =\frac{d}{d x}\left(\tan ^{-1} \frac{a}{b}-x\right) \\
& =\frac{d}{d x}\left(\tan ^{-1} \frac{a}{b}\right)-\frac{d}{d x}(x)=-1 \quad\left[\because \tan ^{-1} \frac{a}{b}=\text { constant }\right] .
\end{aligned}
$$

---

### Example 17:

If $y=\sin ^{-1}\left\{\frac{\sqrt{1+x}-\sqrt{1-x}}{2}\right\}$, find $\frac{d y}{d x}$.

#### Solution:

Putting $x=\cos 2 \theta$, we get

$$
\begin{aligned}
y & =\sin ^{-1}\left\{\frac{\sqrt{1+\cos 2 \theta}-\sqrt{1-\cos 2 \theta}}{2}\right\} \\
& =\sin ^{-1}\left\{\frac{\sqrt{2 \cos ^{2} \theta}-\sqrt{2 \sin ^{2} \theta}}{2}\right\}=\sin ^{-1}\left\{\frac{\sqrt{2} \cos \theta-\sqrt{2} \sin \theta}{2}\right\}
\end{aligned}
$$

$$
\begin{aligned}
& =\sin ^{-1}\left\{\frac{1}{\sqrt{2}} \cos \theta-\frac{1}{\sqrt{2}} \sin \theta\right\}=\sin ^{-1}\left\{\sin \frac{\pi}{4} \cos \theta-\cos \frac{\pi}{4} \sin \theta\right\} \\
& =\sin ^{-1}\left\{\sin \left(\frac{\pi}{4}-\theta\right)\right\} \\
& =\left(\frac{\pi}{4}-\theta\right)=\left(\frac{\pi}{4}-\frac{1}{2} \cos ^{-1} x\right) \\
& \quad\left[\because x=\cos 2 \theta \Rightarrow 2 \theta=\cos ^{-1} x \Rightarrow \theta=\frac{1}{2} \cos ^{-1} x\right] \\
\therefore y & =\frac{\pi}{4}-\frac{1}{2} \cos ^{-1} x .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{d}{d x}\left\{\frac{\pi}{4}-\frac{1}{2} \cos ^{-1} x\right\}=\frac{d}{d x}\left(\frac{\pi}{4}\right)-\frac{1}{2} \frac{d}{d x}\left(\cos ^{-1} x\right)$

$$
=\left\{0-\frac{1}{2} \cdot \frac{(-1)}{\sqrt{1-x^{2}}}\right\}=\frac{1}{2 \sqrt{1-x^{2}}} .
$$

---

### Example 18:

Differentiate each of the following w.r.t. $x$:
(i) $\tan ^{-1}\left(\sqrt{1+x^{2}}+x\right)$
(ii) $\tan ^{-1}\left(\sqrt{1+x^{2}}-x\right)$

- (i) Let $y=\tan ^{-1}\left(\sqrt{1+x^{2}}+x\right)$.
Putting $x=\cot \theta$, we get

$$
\begin{aligned}
& \begin{aligned}
y & =\tan ^{-1}(\operatorname{cosec} \theta+\cot \theta)=\tan ^{-1}\left(\frac{1}{\sin \theta}+\frac{\cos \theta}{\sin \theta}\right) \\
& =\tan ^{-1}\left(\frac{1+\cos \theta}{\sin \theta}\right)=\tan ^{-1}\left(\frac{2 \cos ^{2}(\theta / 2)}{2 \sin (\theta / 2) \cos (\theta / 2)}\right) \\
& =\tan ^{-1}\left(\cot \frac{\theta}{2}\right)=\tan ^{-1}\left\{\tan \left(\frac{\pi}{2}-\frac{\theta}{2}\right)\right\} \\
& =\frac{\pi}{2}-\frac{1}{2} \theta=\frac{\pi}{2}-\frac{1}{2} \cot ^{-1} x .
\end{aligned} \\
& \therefore \quad \frac{d y}{d x}=-\frac{1}{2} \cdot \frac{-1}{\left(1+x^{2}\right)}=\frac{1}{2\left(1+x^{2}\right)} . \\
& \text { Hence, } \quad \frac{d}{d x}\left\{\tan ^{-1}\left(\sqrt{1+x^{2}}+x\right)\right\}=\frac{1}{2\left(1+x^{2}\right)} .
\end{aligned}
$$

- (ii) Let $y=\tan ^{-1}\left(\sqrt{1+x^{2}}-x\right)$.
Putting $x=\cot \theta$, we get

$$
\begin{aligned}
y & =\tan ^{-1}(\operatorname{cosec} \theta-\cot \theta)=\tan ^{-1}\left(\frac{1}{\sin \theta}-\frac{\cos \theta}{\sin \theta}\right) \\
& =\tan ^{-1}\left(\frac{1-\cos \theta}{\sin \theta}\right)=\tan ^{-1}\left\{\frac{2 \sin ^{2}(\theta / 2)}{2 \sin (\theta / 2) \cos (\theta / 2)}\right\} \\
& =\tan ^{-1}\left(\tan \frac{\theta}{2}\right)=\frac{1}{2} \theta=\frac{1}{2} \cot ^{-1} x
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \quad \frac{d y}{d x}=\frac{-1}{2\left(1+x^{2}\right)} . \\
& \text { Hence, } \frac{d}{d x}\left\{\tan ^{-1}\left(\sqrt{1+x^{2}}-x\right)\right\}=\frac{-1}{2\left(1+x^{2}\right)} .
\end{aligned}
$$

---

### Example 19:

Differentiate $\tan ^{-1}\left(\frac{\sqrt{1+x^{2}}+1}{x}\right)$ w.r.t. $x$.

#### Solution:

Let $y=\tan ^{-1}\left(\frac{\sqrt{1+x^{2}}+1}{x}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
& \begin{aligned}
y & =\tan ^{-1}\left(\frac{\sec \theta+1}{\tan \theta}\right)=\tan ^{-1}\left(\frac{1+\cos \theta}{\sin \theta}\right) \\
& =\tan ^{-1}\left\{\frac{2 \cos ^{2}(\theta / 2)}{2 \sin (\theta / 2) \cos (\theta / 2)}\right\}=\tan ^{-1}\left\{\cot \frac{\theta}{2}\right\} \\
& =\tan ^{-1}\left\{\tan \left(\frac{\pi}{2}-\frac{\theta}{2}\right)\right\}=\left(\frac{\pi}{2}-\frac{\theta}{2}\right)=\frac{\pi}{2}-\frac{1}{2} \tan ^{-1} x
\end{aligned} \\
& \therefore \frac{d y}{d x}=-\frac{1}{2\left(1+x^{2}\right)} \cdot \\
& \text { Hence, } \frac{d}{d x}\left\{\tan ^{-1}\left(\frac{\sqrt{1+x^{2}}+1}{x}\right)\right\}=\frac{-1}{2\left(1+x^{2}\right)} .
\end{aligned}
$$

---

### Example 20:

Differentiate $\cot ^{-1}\left(\sqrt{1+x^{2}}+x\right)$ w.r.t.x.

#### Solution:

Let $y=\cot ^{-1}\left(\sqrt{1+x^{2}}+x\right)$.
Putting $x=\cot \theta$, we get

$$
\begin{aligned}
y & =\cot ^{-1}(\operatorname{cosec} \theta+\cot \theta)=\cot ^{-1}\left(\frac{1}{\sin \theta}+\frac{\cos \theta}{\sin \theta}\right) \\
& =\cot ^{-1}\left(\frac{1+\cos \theta}{\sin \theta}\right)=\cot ^{-1}\left\{\frac{2 \cos ^{2}(\theta / 2)}{2 \sin (\theta / 2) \cos (\theta / 2)}\right\} \\
& =\cot ^{-1}\left(\cot \frac{\theta}{2}\right)=\frac{\theta}{2}=\frac{1}{2} \cot ^{-1} x . \\
\therefore \quad \frac{d y}{d x} & =\frac{-1}{2\left(1+x^{2}\right)} .
\end{aligned}
$$

Hence, $\frac{d}{d x}\left\{\cot ^{-1}\left(\sqrt{1+x^{2}}+x\right)\right\}=\frac{-1}{2\left(1+x^{2}\right)}$.

---

### Example 21:

Differentiate $\cos ^{-1}\left(\frac{x-x^{-1}}{x+x^{-1}}\right)$ w.r.t. $x$.

#### Solution:

Let $y=\cos ^{-1}\left(\frac{x-x^{-1}}{x+x^{-1}}\right)=\cos ^{-1}\left\{\frac{\left(x-\frac{1}{x}\right)}{\left(x+\frac{1}{x}\right)}\right\}=\cos ^{-1}\left(\frac{x^{2}-1}{x^{2}+1}\right)$.
Putting $x=\tan \theta$, we get

$$
\begin{aligned}
y & =\cos ^{-1}\left(\frac{\tan ^{2} \theta-1}{\tan ^{2} \theta+1}\right)=\cos ^{-1}(-\cos 2 \theta) \\
& =\cos ^{-1}\{\cos (\pi-2 \theta)\}=(\pi-2 \theta)=\pi-2 \tan ^{-1} x \\
\therefore \quad \frac{d y}{d x} & =\frac{d}{d x}\left(\pi-2 \tan ^{-1} x\right)=\frac{d}{d x}(\pi)-2 \cdot \frac{d}{d x}\left(\tan ^{-1} x\right) \\
& =\left(0-\frac{2}{1+x^{2}}\right)=\frac{-2}{\left(1+x^{2}\right)}
\end{aligned}
$$

---

### Example 22:

If $y=\tan ^{-1}\left(\frac{\sqrt{a}-\sqrt{x}}{1+\sqrt{a x}}\right)$, find $\frac{d y}{d x}$.

#### Solution:

Putting $\sqrt{a}=\tan \alpha$ and $\sqrt{x}=\tan \theta$, we get

$$
\begin{gathered}
y=\tan ^{-1}\left(\frac{\tan \alpha-\tan \theta}{1+\tan \alpha \tan \theta}\right)=\tan ^{-1}\{\tan (\alpha-\theta)\}=(\alpha-\theta) \\
\therefore y=(\alpha-\theta) \Rightarrow y=\tan ^{-1} \sqrt{a}-\tan ^{-1} \sqrt{x} \\
\Rightarrow \frac{d y}{d x}=\frac{d}{d x}\left(\tan ^{-1} \sqrt{a}\right)-\frac{d}{d x}\left(\tan ^{-1} \sqrt{x}\right) \\
=\left\{0-\frac{1}{(1+x)} \cdot \frac{1}{2} x^{-1 / 2}\right\}=\frac{-1}{2 \sqrt{x}(1+x)}
\end{gathered}
$$

Hence, $\frac{d y}{d x}=\frac{-1}{2 \sqrt{x}(1+x)}$.

---

### Example 23:

If $y=\sin ^{-1}\left\{\frac{5 x+12 \sqrt{1-x^{2}}}{13}\right\}$, find $\frac{d y}{d x}$.
[CBSE 2004C, '05C, '08]

#### Solution:

We have

$$
y=\sin ^{-1}\left\{\frac{5}{13} \cdot x+\frac{12}{13} \cdot \sqrt{1-x^{2}}\right\}
$$

Let $\frac{5}{13}=\sin \alpha$ and $x=\cos \theta$. Then,

$$
\cos \alpha=\sqrt{1-\frac{25}{169}}=\sqrt{\frac{144}{169}}=\frac{12}{13}
$$

and $\sqrt{1-x^{2}}=\sqrt{1-\cos ^{2} \theta}=\sqrt{\sin ^{2} \theta}=\sin \theta$.

$$
\begin{aligned}
\therefore \quad y & =\sin ^{-1}\{\sin \alpha \cos \theta+\cos \alpha \sin \theta\} \\
& =\sin ^{-1}\{\sin (\alpha+\theta)\} \\
& =\alpha+\theta=\sin ^{-1} \frac{5}{13}+\cos ^{-1} x .
\end{aligned}
$$

$$
\begin{aligned}
\therefore \frac{d y}{d x} & =\frac{d}{d x}\left\{\sin ^{-1} \frac{5}{13}+\cos ^{-1} x\right\}=\frac{d}{d x}\left\{\sin ^{-1} \frac{5}{13}\right\}+\frac{d}{d x}\left(\cos ^{-1} x\right) \\
& =\left\{0-\frac{1}{\sqrt{1-x^{2}}}\right\}=\frac{-1}{\sqrt{1-x^{2}}} .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{-1}{\sqrt{1-x^{2}}}$.

---

## Exercise 10D

### Differentiate each of the following w.r.t. $x$:

1.  $\sin ^{-1}\left\{\sqrt{\frac{1-\cos x}{2}}\right\}$
2.  $\tan ^{-1}\left(\frac{\sin x}{1+\cos x}\right)$
3.  $\cot ^{-1}\left(\frac{1+\cos x}{\sin x}\right)$
4.  $\cot ^{-1}\left(\sqrt{\frac{1+\cos x}{1-\cos x}}\right)$
5.  $\tan ^{-1}\left(\frac{\cos x+\sin x}{\cos x-\sin x}\right)$
6.  $\cot ^{-1}\left(\frac{\cos x-\sin x}{\cos x+\sin x}\right)$
7.  $\cot ^{-1}\left(\sqrt{\frac{1+\cos 3 x}{1-\cos 3 x}}\right)$
8.  $\sec ^{-1}\left(\frac{1+\tan ^{2} x}{1-\tan ^{2} x}\right)$
9.  $\sin ^{-1}\left(\frac{1-\tan ^{2} x}{1+\tan ^{2} x}\right)$
10. $\operatorname{cosec}^{-1}\left(\frac{1+\tan ^{2} x}{2 \tan x}\right)$
11. $\cot ^{-1}(\operatorname{cosec} x+\cot x)$
12. $\tan ^{-1}(\cot x)+\cot ^{-1}(\tan x)$
13. $\sin ^{-1}\left\{\sqrt{1-x^{2}}\right\}$
14. $\sin ^{-1}\left(\sqrt{\frac{1-x}{2}}\right)$
15. $\cos ^{-1}\left\{\sqrt{\frac{1+x}{2}}\right\}$
16. $\cos ^{-1}\left\{\sqrt{1-x^{2}}\right\}$
17. $\sin ^{-1}\left\{2 x \sqrt{1-x^{2}}\right\}$
18. $\sin ^{-1}\left(3 x-4 x^{3}\right)$
19. $\sin ^{-1}\left(1-2 x^{2}\right)$
20. $\sec ^{-1}\left(\frac{1}{\sqrt{1-x^{2}}}\right)$
21. $\tan ^{-1}\left(\frac{x}{\sqrt{1-x^{2}}}\right)$
22. $\tan ^{-1}\left(\frac{x}{1+\sqrt{1-x^{2}}}\right)$
23. $\cot ^{-1}\left(\frac{\sqrt{1-x^{2}}}{x}\right)$
24. $\sec ^{-1}\left(\frac{1}{1-2 x^{2}}\right)$
25. $\sin ^{-1}\left\{\frac{1}{\sqrt{1+x^{2}}}\right\}$
26. $\tan ^{-1}\left(\frac{1+x}{1-x}\right)$
27. $\cot ^{-1}\left(\frac{1+x}{1-x}\right)$
28. $\tan ^{-1}\left(\frac{3 x-x^{3}}{1-3 x^{2}}\right)$
29. $\operatorname{cosec}^{-1}\left(\frac{1+x^{2}}{2 x}\right)$
30. $\sec ^{-1}\left(\frac{1+x^{2}}{1-x^{2}}\right)$
31. $\sin ^{-1}\left(\frac{1}{\sqrt{1+x^{2}}}\right)$
32. $\sec ^{-1}\left(\frac{x^{2}+1}{x^{2}-1}\right)$
33. $\cos ^{-1}\left(\frac{1-x^{2 n}}{1+x^{2 n}}\right)$
34. $\tan ^{-1}\left\{\frac{x}{\sqrt{a^{2}-x^{2}}}\right\}$
35. $\sin ^{-1}\left\{2 a x \sqrt{1-a^{2} x^{2}}\right\}$
36. $\tan ^{-1}\left\{\frac{\sqrt{1+a^{2} x^{2}}-1}{a x}\right\}$
37. $\sin ^{-1}\left\{\frac{x^{2}}{\sqrt{x^{4}+a^{4}}}\right\}$
38. $\tan ^{-1}\left(\frac{e^{2 x}+1}{e^{2 x}-1}\right)$
39. $\cos ^{-1}(2 x)+2 \cos ^{-1} \sqrt{1-4 x^{2}}$
40. $\tan ^{-1}\left(\frac{a-x}{1+a x}\right)$
41. $\tan ^{-1}\left\{\frac{\sqrt{x}-x}{1+x^{3 / 2}}\right\}$
42. $\tan ^{-1}\left(\frac{\sqrt{a}+\sqrt{x}}{1-\sqrt{a x}}\right)$
43. $\tan ^{-1}\left(\frac{3-2 x}{1+6 x}\right)$
44. $\tan ^{-1}\left(\frac{5 x}{1-6 x^{2}}\right)$
45. $\tan ^{-1}\left(\frac{2 x}{1+15 x^{2}}\right)$
46. If $y=\tan ^{-1}\left(\frac{a x-b}{b x+a}\right)$, prove that $\frac{d y}{d x}=\frac{1}{\left(1+x^{2}\right)}$.
47. If $y=\sin ^{-1}\left(\frac{2 x}{1+x^{2}}\right)+\sec ^{-1}\left(\frac{1+x^{2}}{1-x^{2}}\right)$, show that $\frac{d y}{d x}=\frac{4}{\left(1+x^{2}\right)}$.
48. If $y=\sec ^{-1}\left(\frac{x+1}{x-1}\right)+\sin ^{-1}\left(\frac{x-1}{x+1}\right)$, show that $\frac{d y}{d x}=0$.
49. If $y=\sin \left\{2 \tan ^{-1}\left(\sqrt{\frac{1-x}{1+x}}\right)\right\}$, show that $\frac{d y}{d x}=\frac{-x}{\sqrt{1-x^{2}}}$.
50. If $y=\tan ^{-1}\left\{\frac{\sqrt{1+x}-\sqrt{1-x}}{\sqrt{1+x}+\sqrt{1-x}}\right\}$, prove that $\frac{d y}{d x}=\frac{1}{2 \sqrt{1-x^{2}}}$.
[CBSE 2003]
51. Differentiate $\sin ^{-1}\left(\frac{2^{x+1}}{1+4^{x}}\right)$ w.r.t. $x$.

---

## Answers (Exercise 10D)

1.  $\frac{1}{2}$
2.  $\frac{1}{2}$
3.  $\frac{1}{2}$
4.  $\frac{1}{2}$
5.  $1$
6.  $1$
7.  $\frac{3}{2}$
8.  $2$
9.  $-2$
10. $2$
11. $\frac{1}{2}$
12. $-2$
13. $\frac{-1}{\sqrt{1-x^{2}}}$
14. $\frac{-1}{2 \sqrt{1-x^{2}}}$
15. $\frac{-1}{2 \sqrt{1-x^{2}}}$
16. $\frac{1}{\sqrt{1-x^{2}}}$
17. $\frac{2}{\sqrt{1-x^{2}}}$
18. $\frac{3}{\sqrt{1-x^{2}}}$
19. $\frac{-2}{\sqrt{1-x^{2}}}$
20. $\frac{1}{\sqrt{1-x^{2}}}$
21. $\frac{1}{\sqrt{1-x^{2}}}$
22. $\frac{1}{2 \sqrt{1-x^{2}}}$
23. $\frac{1}{\sqrt{1-x^{2}}}$
24. $\frac{2}{\sqrt{1-x^{2}}}$
25. $\frac{1}{\left(1+x^{2}\right)}$
26. $\frac{1}{\left(1+x^{2}\right)}$
27. $\frac{-1}{\left(1+x^{2}\right)}$
28. $\frac{3}{\left(1+x^{2}\right)}$
29. $\frac{2}{\left(1+x^{2}\right)}$
30. $\frac{2}{\left(1+x^{2}\right)}$
31. $\frac{-1}{\left(1+x^{2}\right)}$
32. $\frac{-2}{\left(1+x^{2}\right)}$
33. $\frac{2 n x^{n-1}}{\left(1+x^{2 n}\right)}$
34. $\frac{1}{\sqrt{a^{2}-x^{2}}}$
35. $\frac{2 a}{\sqrt{1-a^{2} x^{2}}}$
36. $\frac{a}{2\left(1+a^{2} x^{2}\right)}$
37. $\frac{2 a^{2} x}{\left(a^{4}+x^{4}\right)}$
38. $\frac{-2 e^{2 x}}{\left(1+e^{4 x}\right)}$
39. $\frac{2}{\sqrt{1-4 x^{2}}}$
40. $\frac{-1}{\left(1+x^{2}\right)}$
41. $\frac{1}{2 \sqrt{x}(1+x)}-\frac{1}{\left(1+x^{2}\right)}$
42. $\frac{1}{2 \sqrt{x}(1+x)}$
43. $\frac{-2}{\left(1+4 x^{2}\right)}$
44. $\left(\frac{3}{1+9 x^{2}}+\frac{2}{1+4 x^{2}}\right)$
45. $\frac{5}{\left(1+25 x^{2}\right)}-\frac{3}{\left(1+9 x^{2}\right)}$
46. $\frac{2^{x+1}(\log 2)}{\left(1+4^{x}\right)}$

---

## Hints to Some Selected Questions (Exercise 10D)

- (i) Put $x=\cos \theta$ in Q. 13, 14, 15.
- (ii) Put $x=\sin \theta$ in Q. 16, 17, 18, 19, 20, 21, 22, 23, 24 .
- (iii) Put $x=\tan \theta$ in Q. 25, 26, 27, 28, 29, 30.
- (iv) Put $x=\cot \theta$ in Q. 31, 32.
- 33. Put $x^{n}=\tan \theta$.
- 34. Put $x=a \sin \theta$.
- 35. Put $a x=\sin \theta$.
- 36. Put $a x=\tan \theta$.
- 37. Put $x^{2}=a^{2} \tan \theta$.
- 38. Put $e^{2 x}=\cot \theta$.
- 39. Put $2 x=\cos \theta$.
- 40. $y=\tan ^{-1} a-\tan ^{-1} x$.
- 41. $y=\tan ^{-1} \sqrt{x}-\tan ^{-1} x$.
- 42. $y=\tan ^{-1} \sqrt{a}+\tan ^{-1} \sqrt{x}$.
- 43. $y=\tan ^{-1} 3-\tan ^{-1} 2 x$.
- 44. $y=\tan ^{-1} 3 x+\tan ^{-1} 2 x$.
- 45. $y=\tan ^{-1} 5 x-\tan ^{-1} 3 x$.
- 46. $y=\tan ^{-1}\left[\frac{x-(b / a)}{(b / a) x+1}\right]=\left[\tan ^{-1} x-\tan ^{-1} \frac{b}{a}\right]$.
- 48. $\sec ^{-1} \theta=\cos ^{-1} \frac{1}{\theta}$ and $\cos ^{-1} \theta+\sin ^{-1} \theta=\frac{\pi}{2}$.
- 51. Let $y=\sin ^{-1}\left\{\frac{2^{x} \cdot 2}{1+\left(2^{x}\right)^{2}}\right\}$. Puttting $2^{x}=\tan \theta$, we get

$$
\begin{aligned}
& y=\sin ^{-1}\left\{\frac{2 \tan \theta}{1+\tan ^{2} \theta}\right\}=\sin ^{-1}(\sin 2 \theta)=2 \theta=2 \tan ^{-1} 2^{x} . \\
\therefore & \frac{d y}{d x}=2 \cdot \frac{d}{d x}\left(\tan ^{-1} 2^{x}\right)=2 \cdot \frac{1}{\left\{1+\left(2^{x}\right)^{2}\right\}} \cdot \frac{d}{d x}\left(2^{x}\right)=\frac{2}{\left(1+4^{x}\right)} \cdot 2^{x}(\log 2)=\frac{2^{x+1}(\log 2)}{\left(1+4^{x}\right)} .
\end{aligned}
$$