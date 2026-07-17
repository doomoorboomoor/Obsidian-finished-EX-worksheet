## 3. Derivatives of Inverse Trigonometric Functions

In the table given below, we mention the domain and range of various inverse trigonometric functions.

| Function | Domain | Range |
| :--- | :--- | :--- |
| (i) $\sin ^{-1} x$ | [-1, 1] | $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ |
| (ii) $\cos ^{-1} x$ | [-1, 1] | $[0, \pi]$ |
| (iii) $\tan ^{-1} x$ | $R$ | $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ |
| (iv) $\cot ^{-1} x$ | $R$ | $]0, \pi[$ |
| (v) $\sec ^{-1} x$ | $R-]-1,1[$ | $[0, \pi]-\left\{\frac{\pi}{2}\right\}$ |
| (vi) $\operatorname{cosec}^{-1} x$ | $R-]-1, 1[$ | $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]-\{0\}$ |

---

## Derivatives of Inverse Trigonometric Functions

### Example 1:

Prove that $\frac{d}{d x}\left(\sin ^{-1} x\right)=\frac{1}{\sqrt{1-x^{2}}}$, where $x \in]-1,1[$.

#### Solution:

Let $y=\sin ^{-1} x$, where $x \in]-1,1[$ and $y \in]-\frac{\pi}{2}, \frac{\pi}{2}[$. Then,

$$
\begin{aligned}
y=\sin ^{-1} x & \Rightarrow x=\sin y \\
& \left.\Rightarrow \frac{d x}{d y}=\cos y \geq 0 \text { since } y \in\right]-\frac{\pi}{2}, \frac{\pi}{2}[ \\
& \Rightarrow \frac{d x}{d y}=\sqrt{1-\sin ^{2} y}=\sqrt{1-x^{2}} \\
& \Rightarrow \frac{d y}{d x}=\frac{1}{\sqrt{1-x^{2}}}
\end{aligned}
$$

Hence, $\frac{d}{d x}\left(\sin ^{-1} x\right)=\frac{1}{\sqrt{1-x^{2}}}$.

---

### Example 2:

Prove that $\frac{d}{d x}\left(\cos ^{-1} x\right)=\frac{-1}{\sqrt{1-x^{2}}}$, where $x \in]-1,1[$.

#### Solution:

Let $y=\cos ^{-1} x$, where $x \in]-1,1[$ and $y \in] 0, \frac{\pi}{2}[$. Then,

$$
\begin{aligned}
y=\cos ^{-1} x & \Rightarrow x=\cos y \\
& \left.\Rightarrow \frac{d x}{d y}=-\sin y, \text { where } \sin y>0, \text { since } y \in\right] 0, \frac{\pi}{2}[ \\
& \Rightarrow \frac{d x}{d y}=-\sqrt{1-\cos ^{2} y}=-\sqrt{1-x^{2}} \\
& \Rightarrow \frac{d y}{d x}=\frac{-1}{\sqrt{1-x^{2}}}
\end{aligned}
$$

Hence, $\frac{d}{d x}\left(\cos ^{-1} x\right)=\frac{-1}{\sqrt{1-x^{2}}}$.

---

### Example 3:

Prove that $\frac{d}{d x}\left(\tan ^{-1} x\right)=\frac{1}{\left(1+x^{2}\right)}$, where $x \in R$.

#### Solution:

Let $y=\tan ^{-1} x$, where $x \in R$ and $y \in]-\frac{\pi}{2}, \frac{\pi}{2}[$. Then,

$$
\begin{aligned}
& x=\tan y \\
& \Rightarrow \frac{d x}{d y}=\sec ^{2} y=\left(1+\tan ^{2} y\right)=\left(1+x^{2}\right) \\
& \Rightarrow \frac{d y}{d x}=\frac{1}{\left(1+x^{2}\right)} \\
& \text { Hence, } \frac{d}{d x}\left(\tan ^{-1} x\right)=\frac{1}{\left(1+x^{2}\right)}
\end{aligned}
$$

---

### Example 4:

Prove that $\frac{d}{d x}\left(\cot ^{-1} x\right)=\frac{-1}{\left(1+x^{2}\right)}$, where $x \in R$.

#### Solution:

Let $y=\cot ^{-1} x$, where $x \in R$ and $y \in] 0, \pi[$. Then,

$$
\begin{aligned}
& x=\cot y \\
\Rightarrow & \frac{d x}{d y}=-\operatorname{cosec}^{2} y=-\left(1+\cot ^{2} y\right)=-\left(1+x^{2}\right) \\
\Rightarrow & \frac{d y}{d x}=\frac{-1}{\left(1+x^{2}\right)}
\end{aligned}
$$

Hence, $\frac{d}{d x}\left(\cot ^{-1} x\right)=\frac{-1}{\left(1+x^{2}\right)}$.

---

### Example 5:

Prove that $\frac{d}{d x}\left(\sec ^{-1} x\right)=\frac{1}{|x| \sqrt{x^{2}-1}}$, where $x \in R-[-1,1]$.

#### Solution:

Let $y=\sec ^{-1} x$, where $x \in R-[-1,1]$ and $y \in] 0, \pi\left[-\left\{\frac{\pi}{2}\right\}\right.$. Then,

$$
\begin{aligned}
& x=\sec y \\
\Rightarrow & \frac{d x}{d y}=\sec y \tan y>0 \\
\Rightarrow & \frac{d y}{d x}=\frac{1}{\sec y \tan y}=\frac{1}{\sec y \cdot \sqrt{\sec ^{2} y-1}} \\
\Rightarrow & \frac{d y}{d x}=\frac{1}{|x| \sqrt{x^{2}-1}}
\end{aligned}
$$

Hence, $\frac{d}{d x}\left(\sec ^{-1} x\right)=\frac{1}{|x| \sqrt{x^{2}-1}}$.

---

### Example 6:

Prove that $\frac{d}{d x}\left(\operatorname{cosec}^{-1} x\right)=\frac{-1}{|x| \sqrt{x^{2}-1}}$, where $x \in R-[-1,1]$.

#### Solution:

Let $y=\operatorname{cosec}^{-1} x$, where $x \in R-[-1,1]$ and $y \in]-\frac{\pi}{2}, \frac{\pi}{2}[-\{0\}$. Then,

$$
\begin{aligned}
x & =\operatorname{cosec} y \\
\Rightarrow \frac{d x}{d y} & =-\operatorname{cosec} y \cot y, \text { where } \operatorname{cosec} y \cot y>0 \\
\Rightarrow \frac{d y}{d x} & =\frac{-1}{\operatorname{cosec} y \cot y}=\frac{-1}{(\operatorname{cosec} y) \sqrt{\operatorname{cosec}^{2} y-1}}=\frac{-1}{|x| \sqrt{x^{2}-1}} .
\end{aligned}
$$

Hence, $\frac{d}{d x}\left(\operatorname{cosec}^{-1} x\right)=\frac{-1}{|x| \sqrt{x^{2}-1}}$.

---

## Summary

1.  $\frac{d}{d x}\left(\sin ^{-1} x\right)=\frac{1}{\sqrt{1-x^{2}}}$
2.  $\frac{d}{d x}\left(\cos ^{-1} x\right)=\frac{-1}{\sqrt{1-x^{2}}}$
3.  $\frac{d}{d x}\left(\tan ^{-1} x\right)=\frac{1}{\left(1+x^{2}\right)}$
4.  $\frac{d}{d x}\left(\cot ^{-1} x\right)=\frac{-1}{\left(1+x^{2}\right)}$
5.  $\frac{d}{d x}\left(\sec ^{-1} x\right)=\frac{1}{|x| \sqrt{x^{2}-1}}$
6.  $\frac{d}{d x}\left(\operatorname{cosec}^{-1} x\right)=\frac{-1}{|x| \cdot \sqrt{x^{2}-1}}$

---

## Solved Examples

### Example 1:

Differentiate the following w.r.t. $x$:
(i) $\sin ^{-1} 2 x$
(ii) $\tan ^{-1} \sqrt{x}$
(iii) $\cos ^{-1}(\cot x)$

#### Solution:

(i) Let $y=\sin ^{-1} 2 x$.
Putting $2 x=t$, we get $y=\sin ^{-1} t$ and $t=2 x$.
Now, $y=\sin ^{-1} t \Rightarrow \frac{d y}{d t}=\frac{1}{\sqrt{1-t^{2}}}$.
And, $t=2 x \Rightarrow \frac{d t}{d x}=2$.
$\therefore \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{2}{\sqrt{1-t^{2}}}=\frac{2}{\sqrt{1-4 x^{2}}} \quad[\because \quad t=2 x]$.
Hence, $\frac{d}{d x}\left(\sin ^{-1} 2 x\right)=\frac{2}{\sqrt{1-4 x^{2}}}$.

(ii) Let $y=\tan ^{-1} \sqrt{x}$.
Putting $\sqrt{x}=t$, we get $y=\tan ^{-1} t$ and $t=\sqrt{x}$.
Now, $y=\tan ^{-1} t \Rightarrow \frac{d y}{d t}=\frac{1}{\left(1+t^{2}\right)}$.
And, $t=\sqrt{x} \Rightarrow \frac{d t}{d x}=\frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x}}$.
$\therefore \quad \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{1}{\left(1+t^{2}\right)} \cdot \frac{1}{2 \sqrt{x}}=\frac{1}{2 \sqrt{x}(1+x)} \quad[\because t=\sqrt{x}]$.
Hence, $\frac{d}{d x}\left(\tan ^{-1} \sqrt{x}\right)=\frac{1}{2 \sqrt{x}(1+x)}$.

(iii) Let $y=\cos ^{-1}(\cot x)$.
Putting $\cot x=t$, we get $y=\cos ^{-1} t$ and $t=\cot x$.
Now, $y=\cos ^{-1} t \Rightarrow \frac{d y}{d t}=\frac{-1}{\sqrt{1-t^{2}}}$.
And, $t=\cot x \Rightarrow \frac{d t}{d x}=-\operatorname{cosec}^{2} x$.
$\therefore \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{\operatorname{cosec}^{2} x}{\sqrt{1-t^{2}}}=\frac{\operatorname{cosec}^{2} x}{\sqrt{1-\cot ^{2} x}} \quad[\because t=\cot x]$.
Hence, $\frac{d}{d x}\left\{\cos ^{-1}(\cot x)\right\}=\frac{\operatorname{cosec}^{2} x}{\sqrt{1-\cot ^{2} x}}$.

---

### Example 2:

Differentiate the following w.r.t. $x$:
(i) $\sec \left(\tan ^{-1} x\right)$
(ii) $\sin \left(\tan ^{-1} x\right)$
(iii) $\cot \left(\cos ^{-1} x\right)$

#### Solution:

(i) Let $y=\sec \left(\tan ^{-1} x\right)$.
Putting $\tan ^{-1} x=t$, we get $y=\sec t$ and $t=\tan ^{-1} x$.
Now, $y=\sec t \Rightarrow \frac{d y}{d t}=\sec t \tan t$.
And, $t=\tan ^{-1} x \Rightarrow \frac{d t}{d x}=\frac{1}{\left(1+x^{2}\right)}$.
$\therefore \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{\sec t \tan t}{\left(1+x^{2}\right)}=\frac{\left(\sqrt{1+\tan ^{2} t}\right)(\tan t)}{\left(1+x^{2}\right)}$
$=\frac{\left(\sqrt{1+x^{2}}\right) x}{\left(1+x^{2}\right)}=\frac{x}{\sqrt{1+x^{2}}} \quad\left[\because t=\tan ^{-1} x \Rightarrow \tan t=x\right]$
Hence, $\frac{d}{d x}\left\{\sec \left(\tan ^{-1} x\right)\right\}=\frac{x}{\sqrt{1+x^{2}}}$.

(ii) Let $y=\sin \left(\tan ^{-1} x\right)$.
Putting $\tan ^{-1} x=t$, we get $y=\sin t$ and $t=\tan ^{-1} x$.
Now, $y=\sin t \Rightarrow \frac{d y}{d t}=\cos t$.
And, $t=\tan ^{-1} x \Rightarrow \frac{d t}{d x}=\frac{1}{\left(1+x^{2}\right)}$.
$\therefore \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\cos t \cdot \frac{1}{\left(1+x^{2}\right)}=\frac{1}{\left(1+x^{2}\right)^{3 / 2}}$
$\left[\because \tan t=x \Rightarrow \cos t=\frac{1}{\sqrt{1+x^{2}}}\right]$
Hence, $\frac{d}{d x}\left\{\sin \left(\tan ^{-1} x\right)\right\}=\frac{1}{\left(1+x^{2}\right)^{3 / 2}}$.

(iii) Let $y=\cot \left(\cos ^{-1} x\right)$.
Putting $\cos ^{-1} x=t$, we get $y=\cot t$ and $t=\cos ^{-1} x$.
Now, $y=\cot t \Rightarrow \frac{d y}{d t}=-\operatorname{cosec}^{2} t$.
And, $t=\cos ^{-1} x \Rightarrow \frac{d t}{d x}=\frac{-1}{\sqrt{1-x^{2}}}$.
$\therefore \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\frac{\operatorname{cosec}^{2} t}{\sqrt{1-x^{2}}}=\frac{1}{\left(1-x^{2}\right)^{3 / 2}}$
$\left[\because \cos t=x \Rightarrow \operatorname{cosec}^{2} t=\frac{1}{\left(1-x^{2}\right)}\right]$
Hence, $\frac{d}{d x}\left\{\cot \left(\cos ^{-1} x\right)\right\}=\frac{1}{\left(1-x^{2}\right)^{3 / 2}}$.

---

### Example 3:

If $y=\sin \left(\tan ^{-1} 2 x\right)$, prove that $\frac{d y}{d x}=\frac{2}{\left(1+4 x^{2}\right)^{\frac{3}{2}}}$.

#### Solution:

Putting $\tan ^{-1} 2 x=t$, we get $y=\sin t$ and $t=\tan ^{-1} 2 x$.
Now, $y=\sin t \Rightarrow \frac{d y}{d t}=\cos t$.
And, $t=\tan ^{-1} 2 x \Rightarrow \frac{d t}{d x}=\left\{\frac{1}{\left(1+4 x^{2}\right)} \times 2\right\}=\frac{2}{\left(1+4 x^{2}\right)}$.
$\therefore \frac{d y}{d x}=\left(\frac{d y}{d t} \times \frac{d t}{d x}\right)=\left\{\cos t \times \frac{2}{\left(1+4 x^{2}\right)}\right\}$. (i)

Now, $t=\tan ^{-1} 2 x \Rightarrow \tan t=2 x$

$$
\begin{align*}
& \Rightarrow \sec t=\sqrt{1+\tan ^{2} t}=\sqrt{1+4 x^{2}} \\
& \Rightarrow \cos t=\frac{1}{\sec t}=\frac{1}{\sqrt{1+4 x^{2}}} \tag{ii}
\end{align*}
$$

Putting the value of $\cos t$ from (ii) in (i), we get
$$
\frac{d y}{d x}=\left\{\frac{1}{\sqrt{1+4 x^{2}}} \times \frac{2}{\left(1+4 x^{2}\right)}\right\}=\frac{2}{\left(1+4 x^{2}\right)^{3 / 2}}
$$

---

### Example 4:

Differentiate $\sqrt{\cot ^{-1} \sqrt{x}}$ w.r.t. $x$.

#### Solution:

Let $y=\sqrt{\cot ^{-1} \sqrt{x}}$.
Putting $\sqrt{x}=t$ and $\cot ^{-1} \sqrt{x}=\cot ^{-1} t=u$, we get
$y=\sqrt{u}$, where $u=\cot ^{-1} t$ and $t=\sqrt{x}$.

Now, $y=\sqrt{u} \Rightarrow \frac{d y}{d u}=\frac{1}{2} u^{-1 / 2}=\frac{1}{2 \sqrt{u}}$;
$u=\cot ^{-1} t \Rightarrow \frac{d u}{d t}=\frac{-1}{\left(1+t^{2}\right)}$
And, $t=\sqrt{x} \Rightarrow \frac{d t}{d x}=\frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x}}$.

$$
\begin{aligned}
\therefore \frac{d y}{d x}=\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right) & =\frac{-1}{4 \sqrt{u}\left(1+t^{2}\right) \sqrt{x}} \\
& =\frac{-1}{4\left(\sqrt{\cot ^{-1} t}\right)\left(1+t^{2}\right) \sqrt{x}} \quad\left[\because \quad u=\cot ^{-1} t\right] \\
& =\frac{-1}{4\left(\sqrt{\cot ^{-1} \sqrt{x}}\right)(1+x) \sqrt{x}} \quad[\because \quad t=\sqrt{x}]
\end{aligned}
$$

---

### Example 5:

Differentiate $e^{\tan ^{-1} \sqrt{x}}$ w.r.t. $x$.

#### Solution:

Let $y=e^{\tan ^{-1} \sqrt{x}}$.
Putting $\sqrt{x}=t$ and $\tan ^{-1} \sqrt{x}=\tan ^{-1} t=u$, we get
$y=e^{u}$, where $u=\tan ^{-1} t$ and $t=\sqrt{x}$.

Now, $y=e^{u} \Rightarrow \frac{d y}{d u}=e^{u}$;
$u=\tan ^{-1} t \Rightarrow \frac{d u}{d t}=\frac{1}{\left(1+t^{2}\right)}$
And, $t=\sqrt{x} \Rightarrow \frac{d t}{d x}=\frac{1}{2} x^{-1 / 2}=\frac{1}{2 \sqrt{x}}$.

$$
\begin{aligned}
\therefore \quad \frac{d y}{d x} & =\left(\frac{d y}{d u} \times \frac{d u}{d t} \times \frac{d t}{d x}\right)=e^{u} \cdot \frac{1}{\left(1+t^{2}\right)} \cdot \frac{1}{2 \sqrt{x}} \\
& =e^{\tan ^{-1} t} \cdot \frac{1}{\left(1+t^{2}\right)} \cdot \frac{1}{2 \sqrt{x}} \quad\left[\because \quad u=\tan ^{-1} t\right] \\
& =\frac{e^{\tan ^{-1} \sqrt{x}}}{2 \sqrt{x}(1+x)} \quad[\because \quad t=\sqrt{x}] .
\end{aligned}
$$

Hence, $\frac{d y}{d x}=\frac{e^{\tan ^{-1} \sqrt{x}}}{2 \sqrt{x}(1+x)}$.

---

### Example 6:

If $y=\frac{x \sin ^{-1} x}{\sqrt{1-x^{2}}}$, find $\frac{d y}{d x}$.

#### Solution:

$y=\frac{x \sin ^{-1} x}{\sqrt{1-x^{2}}}$ (i)
$\Rightarrow y \sqrt{1-x^{2}}=x \sin ^{-1} x$. (ii)

On differentiating both sides of (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& y \cdot \frac{d}{d x}\left(\sqrt{1-x^{2}}\right)+\left(\sqrt{1-x^{2}}\right) \frac{d y}{d x}=x \cdot \frac{d}{d x}\left(\sin ^{-1} x\right)+\sin ^{-1} x \cdot \frac{d}{d x}(x) \\
\Rightarrow & y \cdot \frac{1}{2}\left(1-x^{2}\right)^{-\frac{1}{2}} \cdot(-2 x)+\left(\sqrt{1-x^{2}}\right) \frac{d y}{d x}=x \cdot \frac{1}{\sqrt{1-x^{2}}}+\sin ^{-1} x \cdot 1 \\
\Rightarrow & \frac{-x y}{\sqrt{1-x^{2}}}+\left(\sqrt{1-x^{2}}\right) \frac{d y}{d x}=\frac{x}{\sqrt{1-x^{2}}}+\sin ^{-1} x \\
\Rightarrow & \frac{-x^{2} \sin ^{-1} x}{\left(1-x^{2}\right)}+\left(\sqrt{1-x^{2}}\right) \frac{d y}{d x}=\frac{x}{\sqrt{1-x^{2}}}+\sin ^{-1} x \quad \text { [using (i)] } \\
\Rightarrow & -x^{2} \sin ^{-1} x+\left(1-x^{2}\right)^{3 / 2} \frac{d y}{d x}=x\left(\sqrt{1-x^{2}}\right)+\left(1-x^{2}\right) \sin ^{-1} x \\
\Rightarrow & \left(1-x^{2}\right)^{3 / 2} \frac{d y}{d x}=x\left(\sqrt{1-x^{2}}\right)+\sin ^{-1} x \\
\Rightarrow & \frac{d y}{d x}=\frac{x\left(\sqrt{1-x^{2}}\right)+\sin ^{-1} x}{\left(1-x^{2}\right)^{3 / 2}}
\end{aligned}
$$

---

### Example 7:

Find $\frac{d}{d x}\left[\sqrt{1-x^{2}} \sin ^{-1} x-x\right]$.

#### Solution:

We have

$$
\begin{aligned}
& \frac{d}{d x}\left[\left(\sqrt{1-x^{2}}\right) \sin ^{-1} x-x\right] \\
= & \frac{d}{d x}\left[\left(\sqrt{1-x^{2}} \sin ^{-1} x\right]-\frac{d}{d x}(x)\right. \\
= & \left(\sqrt{1-x^{2}}\right) \cdot \frac{d}{d x}\left(\sin ^{-1} x\right)+\left(\sin ^{-1} x\right) \cdot \frac{d}{d x}\left(\sqrt{1-x^{2}}\right)-1 \\
= & \left(\sqrt{1-x^{2}}\right) \cdot \frac{1}{\left(\sqrt{1-x^{2}}\right)}+\left(\sin ^{-1} x\right) \cdot \frac{1}{2}\left(1-x^{2}\right)^{-1 / 2} \cdot(-2 x)-1 \\
= & \left\{1-\frac{x \sin ^{-1} x}{\sqrt{1-x^{2}}}-1\right\}=\frac{-x \sin ^{-1} x}{\sqrt{1-x^{2}}} .
\end{aligned}
$$

---

### Example 8:

Show that $\frac{d}{d x}\left[\frac{x}{2} \sqrt{a^{2}-x^{2}}+\frac{a^{2}}{2} \sin ^{-1} \frac{x}{a}\right]=\sqrt{a^{2}-x^{2}}$. [CBSE 2004C]

#### Solution:

We have

$$
\begin{aligned}
& \frac{d}{d x}\left[\frac{x}{2} \cdot \sqrt{a^{2}-x^{2}}+\frac{a^{2}}{2} \cdot \sin ^{-1} \frac{x}{a}\right] \\
& \quad=\frac{d}{d x}\left[\frac{x}{2} \cdot \sqrt{a^{2}-x^{2}}\right]+\frac{a^{2}}{2} \cdot \frac{d}{d x}\left[\sin ^{-1} \frac{x}{a}\right] \\
& \quad=\frac{x}{2} \cdot \frac{d}{d x}\left(\sqrt{a^{2}-x^{2}}\right)+\left(\sqrt{a^{2}-x^{2}}\right) \cdot \frac{d}{d x}\left(\frac{x}{2}\right)+\frac{a^{2}}{2} \cdot \frac{1}{\sqrt{1-\frac{x^{2}}{a^{2}}}} \cdot \frac{1}{a} \\
& \quad=\frac{x}{2} \cdot \frac{1}{2}\left(a^{2}-x^{2}\right)^{-1 / 2} \cdot(-2 x)+\left(\sqrt{a^{2}-x^{2}}\right) \cdot \frac{1}{2}+\frac{a^{2}}{2 \sqrt{a^{2}-x^{2}}} \\
& \quad=\frac{-x^{2}}{2 \sqrt{a^{2}-x^{2}}}+\frac{\sqrt{a^{2}-x^{2}}}{2}+\frac{a^{2}}{2 \sqrt{a^{2}-x^{2}}} \\
& \quad=\frac{-x^{2}+\left(a^{2}-x^{2}\right)+a^{2}}{2 \sqrt{a^{2}-x^{2}}}=\frac{\left(a^{2}-x^{2}\right)}{\sqrt{\left(a^{2}-x^{2}\right)}}=\sqrt{\left(a^{2}-x^{2}\right)}
\end{aligned}
$$

Hence, $\quad \frac{d}{d x}\left[\frac{x}{2} \cdot \sqrt{a^{2}-x^{2}}+\frac{a^{2}}{2} \cdot \sin ^{-1} \frac{x}{a}\right]=\sqrt{a^{2}-x^{2}}$.

---

## Exercise 10C

Differentiate each of the following w.r.t. $x$:

1.  $\cos ^{-1} 2 x$
2.  $\tan ^{-1} x^{2}$
3.  $\sec ^{-1} \sqrt{x}$
4.  $\sin ^{-1} \frac{x}{a}$
5.  $\tan ^{-1}(\log x)$
6.  $\cot ^{-1}\left(e^{x}\right)$
7.  $\log \left(\tan ^{-1} x\right)$
8.  $\cot ^{-1} x^{3}$
9.  $\sin ^{-1}(\cos x)$
10. $\left(1+x^{2}\right) \tan ^{-1} x$
11. $\tan ^{-1}(\cot x)$
12. $\log \left(\sin ^{-1} x^{4}\right)$
13. $\left(\cot ^{-1} x^{2}\right)^{3}$
14. $\tan ^{-1}(\cos \sqrt{x})$
15. $\tan \left(\sin ^{-1} x\right)$
16. $e^{\tan ^{-1} \sqrt{x}}$
17. $\sqrt{\sin ^{-1} x^{2}}$
18. If $y=\sin ^{-1}(\cos x)+\cos ^{-1}(\sin x)$, prove that $\frac{d y}{d x}=-2$.
19. Prove that $\frac{d}{d x}\left\{2 x \tan ^{-1} x-\log \left(1+x^{2}\right)\right\}=2 \tan ^{-1} x$.

---

## Answers (Exercise 10C)

1.  $\frac{-2}{\sqrt{1-4 x^{2}}}$
2.  $\frac{2 x}{\left(1+x^{4}\right)}$
3.  $\frac{1}{2 x \sqrt{x-1}}$
4.  $\frac{1}{\sqrt{a^{2}-x^{2}}}$
5.  $\frac{1}{x\left\{1+(\log x)^{2}\right\}}$
6.  $\frac{-e^{x}}{\left(1+e^{2 x}\right)}$
7.  $\frac{1}{\left(1+x^{2}\right) \tan ^{-1} x}$
8.  $\frac{-3 x^{2}}{\left(1+x^{6}\right)}$
9.  -1
10. $\left(1+2 x \tan ^{-1} x\right)$
11. -1
12. $\frac{4 x^{3}}{\left(\sin ^{-1} x^{4}\right) \sqrt{1-x^{8}}}$
13. $\frac{-6 x\left(\cot ^{-1} x^{2}\right)^{2}}{\left(1+x^{4}\right)}$
14. $\frac{-\sin \sqrt{x}}{(2 \sqrt{x})\left(1+\cos ^{2} \sqrt{x}\right)}$
15. $\frac{1}{\left(1-x^{2}\right)^{3 / 2}}$
16. $\frac{e^{\tan ^{-1} \sqrt{x}}}{2 \sqrt{x}(1+x)}$
17. $\frac{x}{\left(\sqrt{1-x^{4}}\right) \sqrt{\sin ^{-1} x^{2}}}$