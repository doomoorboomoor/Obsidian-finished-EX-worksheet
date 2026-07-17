## Trigonometric Functions of Multiples of Angles

### Theorem 1

- (i) $\sin 2x = 2 \sin x \cos x$
- (ii) $\cos 2x = (\cos^{2} x - \sin^{2} x) = (2 \cos^{2} x - 1) = (1 - 2 \sin^{2} x)$
- (iii) $\tan 2x = \frac{2 \tan x}{1 - \tan^{2} x}$

#### Proof:

- **(i)** We know that $\sin(x+y) = \sin x \cos y + \cos x \sin y$.
$$
\begin{aligned}
\sin 2x &= \sin(x+x) \\
&= \sin x \cos x + \cos x \sin x \\
&= 2 \sin x \cos x
\end{aligned}
$$

- **(ii)** We know that $\cos(x+y) = \cos x \cos y - \sin x \sin y$.
$$
\begin{aligned}
\cos 2x &= \cos(x+x) \\
&= \cos x \cos x - \sin x \sin x \\
&= \cos^{2} x - \sin^{2} x
\end{aligned}
$$
Now,
$$
\begin{aligned}
\cos 2x &= \cos^{2} x - \sin^{2} x \\
&= (1 - \sin^{2} x) - \sin^{2} x \quad [\because \cos^{2} x = (1 - \sin^{2} x)] \\
&= (1 - 2 \sin^{2} x)
\end{aligned}
$$
Also,
$$
\begin{aligned}
\cos 2x &= \cos^{2} x - \sin^{2} x \\
&= \cos^{2} x - (1 - \cos^{2} x) \quad [\because \sin^{2} x = 1 - \cos^{2} x] \\
&= (2 \cos^{2} x - 1)
\end{aligned}
$$
$$
\therefore \cos 2x = (\cos^{2} x - \sin^{2} x) = (1 - 2 \sin^{2} x) = (2 \cos^{2} x - 1)
$$

- **(iii)** We know that $\tan(x+y) = \frac{\tan x + \tan y}{1 - \tan x \tan y}$.
$$
\begin{aligned}
\tan 2x &= \tan(x+x) \\
&= \frac{\tan x + \tan x}{1 - (\tan x \times \tan x)} \\
&= \frac{2 \tan x}{1 - \tan^{2} x}
\end{aligned}
$$
$$
\therefore \tan 2x = \frac{2 \tan x}{1 - \tan^{2} x}
$$

#### Remark:

The above results may be expressed as:
- (i) $(1 - \cos 2x) = 2 \sin^{2} x$
- (ii) $(1 + \cos 2x) = 2 \cos^{2} x$
- (iii) $\frac{(1 - \cos 2x)}{(1 + \cos 2x)} = \tan^{2} x$

---

### Theorem 2

If $x$ is not an odd multiple of $\frac{\pi}{2}$, then prove that:
- (i) $\sin 2x = \frac{2 \tan x}{1 + \tan^{2} x}$
- (ii) $\cos 2x = \frac{1 - \tan^{2} x}{1 + \tan^{2} x}$

#### Proof:

Since $x$ is not an odd multiple of $\frac{\pi}{2}$, we have $\cos x \neq 0$.

- **(i)**
$$
\begin{aligned}
\sin 2x &= 2 \sin x \cos x \\
&= \frac{2 \sin x \cos x}{\cos^{2} x + \sin^{2} x} \quad [\because 1 = \cos^{2} x + \sin^{2} x] \\
&= \frac{\frac{2 \sin x \cos x}{\cos^{2} x}}{\frac{\cos^{2} x + \sin^{2} x}{\cos^{2} x}} \quad [\text{dividing num. and denom. by } \cos^{2} x] \\
&= \frac{2 \frac{\sin x}{\cos x}}{1 + \frac{\sin^{2} x}{\cos^{2} x}} \\
&= \frac{2 \tan x}{1 + \tan^{2} x}
\end{aligned}
$$
$$
\therefore \sin 2x = \frac{2 \tan x}{1 + \tan^{2} x}
$$

- **(ii)**
$$
\begin{aligned}
\cos 2x &= \cos^{2} x - \sin^{2} x \\
&= \frac{\cos^{2} x - \sin^{2} x}{\cos^{2} x + \sin^{2} x} \quad [\because 1 = \cos^{2} x + \sin^{2} x] \\
&= \frac{\frac{\cos^{2} x - \sin^{2} x}{\cos^{2} x}}{\frac{\cos^{2} x + \sin^{2} x}{\cos^{2} x}} \quad [\text{dividing num. and denom. by } \cos^{2} x] \\
&= \frac{1 - \frac{\sin^{2} x}{\cos^{2} x}}{1 + \frac{\sin^{2} x}{\cos^{2} x}} \\
&= \frac{1 - \tan^{2} x}{1 + \tan^{2} x}
\end{aligned}
$$
$$
\therefore \cos 2x = \frac{1 - \tan^{2} x}{1 + \tan^{2} x}
$$

---

## Summary

- (i) $\sin 2x = 2 \sin x \cos x$
- (ii) $\cos 2x = \cos^{2} x - \sin^{2} x = 2 \cos^{2} x - 1 = 1 - 2 \sin^{2} x$
- (iii) $\tan 2x = \frac{2 \tan x}{1 - \tan^{2} x}$
- (iv) $\sin 2x = \frac{2 \tan x}{1 + \tan^{2} x}$
- (v) $\cos 2x = \frac{1 - \tan^{2} x}{1 + \tan^{2} x}$

---

### Theorem 3

- (i) $\sin 3x = 3 \sin x - 4 \sin^{3} x$
- (ii) $\cos 3x = 4 \cos^{3} x - 3 \cos x$
- (iii) $\tan 3x = \frac{3 \tan x - \tan^{3} x}{1 - 3 \tan^{2} x}$

#### Proof:

- **(i)**
$$
\begin{aligned}
\sin 3x &= \sin(2x + x) \\
&= \sin 2x \cos x + \cos 2x \sin x \\
&= (2 \sin x \cos x) \cos x + (1 - 2 \sin^{2} x) \sin x \\
&= 2 \sin x \cos^{2} x + \sin x - 2 \sin^{3} x \\
&= 2 \sin x (1 - \sin^{2} x) + \sin x - 2 \sin^{3} x \\
&= 2 \sin x - 2 \sin^{3} x + \sin x - 2 \sin^{3} x \\
&= 3 \sin x - 4 \sin^{3} x
\end{aligned}
$$

- **(ii)**
$$
\begin{aligned}
\cos 3x &= \cos(2x + x) \\
&= \cos 2x \cos x - \sin 2x \sin x \\
&= (2 \cos^{2} x - 1) \cos x - (2 \sin x \cos x) \sin x \\
&= 2 \cos^{3} x - \cos x - 2 \sin^{2} x \cos x \\
&= 2 \cos^{3} x - \cos x - 2(1 - \cos^{2} x) \cos x \\
&= 2 \cos^{3} x - \cos x - 2 \cos x + 2 \cos^{3} x \\
&= 4 \cos^{3} x - 3 \cos x
\end{aligned}
$$

- **(iii)**
$$
\begin{aligned}
\tan 3x &= \tan(2x + x) \\
&= \frac{\tan 2x + \tan x}{1 - \tan 2x \tan x} \\
&= \frac{\frac{2 \tan x}{1 - \tan^{2} x} + \tan x}{1 - \left(\frac{2 \tan x}{1 - \tan^{2} x}\right) \tan x} \\
&= \frac{2 \tan x + \tan x(1 - \tan^{2} x)}{1 - \tan^{2} x - 2 \tan^{2} x} \\
&= \frac{2 \tan x + \tan x - \tan^{3} x}{1 - 3 \tan^{2} x} \\
&= \frac{3 \tan x - \tan^{3} x}{1 - 3 \tan^{2} x}
\end{aligned}
$$

---

## Summary

- (i) $\sin 3x = 3 \sin x - 4 \sin^{3} x$
- (ii) $\cos 3x = 4 \cos^{3} x - 3 \cos x$
- (iii) $\tan 3x = \frac{3 \tan x - \tan^{3} x}{1 - 3 \tan^{2} x}$

---

## Solved Examples

### Example 1:

If $\sin x = -\frac{1}{2}$ and $\pi < x < \frac{3\pi}{2}$, find the values of:
- (i) $\sin 2x$
- (ii) $\cos 2x$
- (iii) $\tan 2x$

#### Solution:

Since $x$ lies in **Quadrant III**, we have $\sin x < 0$, $\cos x < 0$, and $\tan x > 0$.
Given, $\sin x = -\frac{1}{2}$.

$$
\cos x = -\sqrt{1 - \sin^{2} x} = -\sqrt{1 - \left(-\frac{1}{2}\right)^2} = -\sqrt{1 - \frac{1}{4}} = -\sqrt{\frac{3}{4}} = -\frac{\sqrt{3}}{2}
$$

$$
\tan x = \frac{\sin x}{\cos x} = \frac{-1/2}{-\sqrt{3}/2} = \frac{1}{\sqrt{3}}
$$

- **(i)** $\sin 2x = 2 \sin x \cos x$
$$
= 2 \times \left(-\frac{1}{2}\right) \times \left(-\frac{\sqrt{3}}{2}\right) = \frac{\sqrt{3}}{2}
$$

- **(ii)** $\cos 2x = 2 \cos^{2} x - 1$
$$
= 2 \left(-\frac{\sqrt{3}}{2}\right)^2 - 1 = 2 \times \frac{3}{4} - 1 = \frac{3}{2} - 1 = \frac{1}{2}
$$

- **(iii)** $\tan 2x = \frac{\sin 2x}{\cos 2x}$
$$
= \frac{\sqrt{3}/2}{1/2} = \sqrt{3}
$$

---

### Example 2:

If $\sec x = -\frac{13}{12}$ and $\frac{\pi}{2} < x < \pi$, find the values of:
- (i) $\sin 2x$
- (ii) $\cos 2x$
- (iii) $\tan 2x$

#### Solution:

Since $x$ lies in **Quadrant II**, we have $\sin x > 0$, $\cos x < 0$, and $\tan x < 0$.
Given, $\sec x = -\frac{13}{12} \implies \cos x = -\frac{12}{13}$.

$$
\sin x = \sqrt{1 - \cos^{2} x} = \sqrt{1 - \left(-\frac{12}{13}\right)^2} = \sqrt{1 - \frac{144}{169}} = \sqrt{\frac{25}{169}} = \frac{5}{13}
$$

$$
\tan x = \frac{\sin x}{\cos x} = \frac{5/13}{-12/13} = -\frac{5}{12}
$$

- **(i)** $\sin 2x = 2 \sin x \cos x$
$$
= 2 \times \frac{5}{13} \times \left(-\frac{12}{13}\right) = -\frac{120}{169}
$$

- **(ii)** $\cos 2x = 2 \cos^{2} x - 1$
$$
= 2 \left(-\frac{12}{13}\right)^2 - 1 = 2 \times \frac{144}{169} - 1 = \frac{288 - 169}{169} = \frac{119}{169}
$$

- **(iii)** $\tan 2x = \frac{\sin 2x}{\cos 2x}$
$$
= \frac{-120/169}{119/169} = -\frac{120}{119}
$$

---

### Example 3:

If $\tan x = -\frac{3}{4}$ and $\frac{3\pi}{2} < x < 2\pi$, find the values of:
- (i) $\sin 2x$
- (ii) $\cos 2x$
- (iii) $\tan 2x$

#### Solution:

Since $x$ lies in **Quadrant IV**, we have $\cos x > 0$, $\sin x < 0$, and $\tan x < 0$.
Given, $\tan x = -\frac{3}{4}$.

$$
\sec x = \sqrt{1 + \tan^{2} x} = \sqrt{1 + \left(-\frac{3}{4}\right)^2} = \sqrt{1 + \frac{9}{16}} = \sqrt{\frac{25}{16}} = \frac{5}{4}
$$
$$
\cos x = \frac{1}{\sec x} = \frac{4}{5}
$$
$$
\sin x = -\sqrt{1 - \cos^{2} x} = -\sqrt{1 - \left(\frac{4}{5}\right)^2} = -\sqrt{1 - \frac{16}{25}} = -\sqrt{\frac{9}{25}} = -\frac{3}{5}
$$

- **(i)** $\sin 2x = 2 \sin x \cos x$
$$
= 2 \times \left(-\frac{3}{5}\right) \times \frac{4}{5} = -\frac{24}{25}
$$

- **(ii)** $\cos 2x = 2 \cos^{2} x - 1$
$$
= 2 \left(\frac{4}{5}\right)^2 - 1 = 2 \times \frac{16}{25} - 1 = \frac{32 - 25}{25} = \frac{7}{25}
$$

- **(iii)** $\tan 2x = \frac{\sin 2x}{\cos 2x}$
$$
= \frac{-24/25}{7/25} = -\frac{24}{7}
$$

---

### Example 4:

- (i) If $\sin x = \frac{1}{3}$, find the value of $\sin 3x$.
- (ii) If $\cos x = \frac{1}{2}$, find the value of $\cos 3x$.

#### Solution:

- **(i)**
$$
\begin{aligned}
\sin 3x &= 3 \sin x - 4 \sin^{3} x \\
&= 3 \left(\frac{1}{3}\right) - 4 \left(\frac{1}{3}\right)^3 \\
&= 1 - 4 \left(\frac{1}{27}\right) = 1 - \frac{4}{27} = \frac{23}{27}
\end{aligned}
$$

- **(ii)**
$$
\begin{aligned}
\cos 3x &= 4 \cos^{3} x - 3 \cos x \\
&= 4 \left(\frac{1}{2}\right)^3 - 3 \left(\frac{1}{2}\right) \\
&= 4 \left(\frac{1}{8}\right) - \frac{3}{2} = \frac{1}{2} - \frac{3}{2} = -1
\end{aligned}
$$

---

### Example 5:

If $\cos x = \frac{4}{5}$ and $x$ is acute, find the value of $\tan 2x$.

#### Solution:

Given $\cos x = \frac{4}{5}$. Since $x$ is acute, $\tan x > 0$.
$$
\sec x = \frac{1}{\cos x} = \frac{5}{4}
$$
$$
\tan x = \sqrt{\sec^{2} x - 1} = \sqrt{\left(\frac{5}{4}\right)^2 - 1} = \sqrt{\frac{25}{16} - 1} = \sqrt{\frac{9}{16}} = \frac{3}{4}
$$
Now,
$$
\tan 2x = \frac{2 \tan x}{1 - \tan^{2} x} = \frac{2 \times \frac{3}{4}}{1 - \left(\frac{3}{4}\right)^2} = \frac{\frac{3}{2}}{1 - \frac{9}{16}} = \frac{\frac{3}{2}}{\frac{7}{16}} = \frac{3}{2} \times \frac{16}{7} = \frac{24}{7}
$$

---

### Example 6:

If $\tan x = \frac{1}{7}$ and $\tan y = \frac{1}{3}$, show that $\cos 2x = \sin 4y$.

#### Solution:

We have
$$
\cos 2x = \frac{1 - \tan^{2} x}{1 + \tan^{2} x} = \frac{1 - (\frac{1}{7})^2}{1 + (\frac{1}{7})^2} = \frac{1 - \frac{1}{49}}{1 + \frac{1}{49}} = \frac{\frac{48}{49}}{\frac{50}{49}} = \frac{48}{50} = \frac{24}{25}
$$
And
$$
\begin{aligned}
\sin 4y &= 2 \sin 2y \cos 2y \\
&= 2 \left( \frac{2 \tan y}{1 + \tan^{2} y} \right) \left( \frac{1 - \tan^{2} y}{1 + \tan^{2} y} \right) \\
&= 2 \left( \frac{2 \times \frac{1}{3}}{1 + (\frac{1}{3})^2} \right) \left( \frac{1 - (\frac{1}{3})^2}{1 + (\frac{1}{3})^2} \right) \\
&= 2 \left( \frac{\frac{2}{3}}{1 + \frac{1}{9}} \right) \left( \frac{1 - \frac{1}{9}}{1 + \frac{1}{9}} \right) \\
&= 2 \left( \frac{\frac{2}{3}}{\frac{10}{9}} \right) \left( \frac{\frac{8}{9}}{\frac{10}{9}} \right) \\
&= 2 \left( \frac{2}{3} \times \frac{9}{10} \right) \left( \frac{8}{10} \right) \\
&= 2 \left( \frac{3}{5} \right) \left( \frac{4}{5} \right) = \frac{24}{25}
\end{aligned}
$$
$$
\therefore \cos 2x = \sin 4y
$$

---

### Example 7:

Prove that:
- (i) $\sin \frac{\pi}{6} \cos \frac{\pi}{6} = \frac{\sqrt{3}}{4}$
- (ii) $\cos^{2} \frac{\pi}{12} - \sin^{2} \frac{\pi}{12} = \frac{\sqrt{3}}{2}$

#### Solution:

- **(i)**
$$
\begin{aligned}
\sin \frac{\pi}{6} \cos \frac{\pi}{6} &= \frac{1}{2} \left( 2 \sin \frac{\pi}{6} \cos \frac{\pi}{6} \right) \\
&= \frac{1}{2} \sin \left( 2 \times \frac{\pi}{6} \right) \quad [\because 2 \sin x \cos x = \sin 2x] \\
&= \frac{1}{2} \sin \frac{\pi}{3} = \frac{1}{2} \times \frac{\sqrt{3}}{2} = \frac{\sqrt{3}}{4}
\end{aligned}
$$

- **(ii)**
$$
\begin{aligned}
\cos^{2} \frac{\pi}{12} - \sin^{2} \frac{\pi}{12} &= \cos \left( 2 \times \frac{\pi}{12} \right) \quad [\because \cos^{2} x - \sin^{2} x = \cos 2x] \\
&= \cos \frac{\pi}{6} = \frac{\sqrt{3}}{2}
\end{aligned}
$$
*Note: There seems to be a typo in the original document where $\cos \frac{\pi}{6} = \frac{3}{2}$. The correct value is $\frac{\sqrt{3}}{2}$.*

---

### Example 8:

Prove that:
- (i) $\frac{\sin 2x}{1 - \cos 2x} = \cot x$
- (ii) $\frac{1 - \cos 2x}{1 + \cos 2x} = \tan^{2} x$

#### Solution:

- **(i)**
$$
\begin{aligned}
\textbf{LHS} &= \frac{\sin 2x}{1 - \cos 2x} \\
&= \frac{2 \sin x \cos x}{2 \sin^{2} x} \quad [\because \sin 2x = 2 \sin x \cos x, (1 - \cos 2x) = 2 \sin^{2} x] \\
&= \frac{\cos x}{\sin x} = \cot x = \textbf{RHS}
\end{aligned}
$$

- **(ii)**
$$
\begin{aligned}
\textbf{LHS} &= \frac{1 - \cos 2x}{1 + \cos 2x} \\
&= \frac{2 \sin^{2} x}{2 \cos^{2} x} \quad [\because (1 - \cos 2x) = 2 \sin^{2} x, (1 + \cos 2x) = 2 \cos^{2} x] \\
&= \tan^{2} x = \textbf{RHS}
\end{aligned}
$$

---

### Example 9:

Prove that $\cos 4x = 1 - 8 \sin^{2} x \cos^{2} x$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \cos 4x \\
&= \cos 2(2x) \\
&= 1 - 2 \sin^{2}(2x) \quad [\because \cos 2\theta = 1 - 2\sin^{2}\theta] \\
&= 1 - 2 (\sin 2x)^2 \\
&= 1 - 2 (2 \sin x \cos x)^2 \quad [\because \sin 2x = 2 \sin x \cos x] \\
&= 1 - 2 (4 \sin^{2} x \cos^{2} x) \\
&= 1 - 8 \sin^{2} x \cos^{2} x = \textbf{RHS}
\end{aligned}
$$

---

### Example 10:

Prove that $\frac{1 + \sin 2x - \cos 2x}{1 + \sin 2x + \cos 2x} = \tan x$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \frac{1 + \sin 2x - \cos 2x}{1 + \sin 2x + \cos 2x} \\
&= \frac{(1 - \cos 2x) + \sin 2x}{(1 + \cos 2x) + \sin 2x} \\
&= \frac{2 \sin^{2} x + 2 \sin x \cos x}{2 \cos^{2} x + 2 \sin x \cos x} \quad \left[\begin{aligned} \because (1 - \cos 2x) &= 2 \sin^{2} x \\ (1 + \cos 2x) &= 2 \cos^{2} x \\ \sin 2x &= 2 \sin x \cos x \end{aligned}\right] \\
&= \frac{2 \sin x (\sin x + \cos x)}{2 \cos x (\cos x + \sin x)} \\
&= \frac{\sin x}{\cos x} = \tan x = \textbf{RHS}
\end{aligned}
$$

---

### Example 11:

Prove that $\frac{1 - \sin 2x}{1 + \sin 2x} = \tan^{2}\left(\frac{\pi}{4} - x\right)$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \frac{1 - \sin 2x}{1 + \sin 2x} \\
&= \frac{1 - \cos\left(\frac{\pi}{2} - 2x\right)}{1 + \cos\left(\frac{\pi}{2} - 2x\right)} \quad \left[\because \sin \theta = \cos\left(\frac{\pi}{2} - \theta\right)\right] \\
&= \frac{2 \sin^{2}\left(\frac{\frac{\pi}{2} - 2x}{2}\right)}{2 \cos^{2}\left(\frac{\frac{\pi}{2} - 2x}{2}\right)} \quad \left[\begin{aligned} \because 1 - \cos 2\theta &= 2 \sin^{2}\theta \\ 1 + \cos 2\theta &= 2 \cos^{2}\theta \end{aligned}\right] \\
&= \frac{\sin^{2}\left(\frac{\pi}{4} - x\right)}{\cos^{2}\left(\frac{\pi}{4} - x\right)} \\
&= \tan^{2}\left(\frac{\pi}{4} - x\right) = \textbf{RHS}
\end{aligned}
$$

---

### Example 12:

Prove that $\frac{\cos x + \sin x}{\cos x - \sin x} - \frac{\cos x - \sin x}{\cos x + \sin x} = 2 \tan 2x$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \frac{\cos x + \sin x}{\cos x - \sin x} - \frac{\cos x - \sin x}{\cos x + \sin x} \\
&= \frac{(\cos x + \sin x)^2 - (\cos x - \sin x)^2}{(\cos x - \sin x)(\cos x + \sin x)} \\
&= \frac{(\cos^2 x + \sin^2 x + 2\sin x \cos x) - (\cos^2 x + \sin^2 x - 2\sin x \cos x)}{\cos^2 x - \sin^2 x} \\
&= \frac{(1 + \sin 2x) - (1 - \sin 2x)}{\cos 2x} \\
&= \frac{2 \sin 2x}{\cos 2x} \\
&= 2 \tan 2x = \textbf{RHS}
\end{aligned}
$$

---

### Example 13:

Prove that $\tan 4\theta = \frac{4 \tan \theta (1 - \tan^{2} \theta)}{1 - 6 \tan^{2} \theta + \tan^{4} \theta}$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \tan 4\theta = \tan 2(2\theta) \\
&= \frac{2 \tan 2\theta}{1 - \tan^{2} 2\theta} \\
&= \frac{2 \left(\frac{2 \tan \theta}{1 - \tan^{2} \theta}\right)}{1 - \left(\frac{2 \tan \theta}{1 - \tan^{2} \theta}\right)^2} \\
&= \frac{\frac{4 \tan \theta}{1 - \tan^{2} \theta}}{1 - \frac{4 \tan^{2} \theta}{(1 - \tan^{2} \theta)^2}} \\
&= \frac{\frac{4 \tan \theta}{1 - \tan^{2} \theta}}{\frac{(1 - \tan^{2} \theta)^2 - 4 \tan^{2} \theta}{(1 - \tan^{2} \theta)^2}} \\
&= \frac{4 \tan \theta}{1 - \tan^{2} \theta} \times \frac{(1 - \tan^{2} \theta)^2}{(1 - 2\tan^2 \theta + \tan^4 \theta) - 4 \tan^{2} \theta} \\
&= \frac{4 \tan \theta (1 - \tan^{2} \theta)}{1 - 6 \tan^{2} \theta + \tan^{4} \theta} = \textbf{RHS}
\end{aligned}
$$

---

### Example 14:

Prove that $\frac{\tan 5\theta + \tan 3\theta}{\tan 5\theta - \tan 3\theta} = 4 \cos 2\theta \cos 4\theta$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \frac{\tan 5\theta + \tan 3\theta}{\tan 5\theta - \tan 3\theta} \\
&= \frac{\frac{\sin 5\theta}{\cos 5\theta} + \frac{\sin 3\theta}{\cos 3\theta}}{\frac{\sin 5\theta}{\cos 5\theta} - \frac{\sin 3\theta}{\cos 3\theta}} \\
&= \frac{\frac{\sin 5\theta \cos 3\theta + \cos 5\theta \sin 3\theta}{\cos 5\theta \cos 3\theta}}{\frac{\sin 5\theta \cos 3\theta - \cos 5\theta \sin 3\theta}{\cos 5\theta \cos 3\theta}} \\
&= \frac{\sin(5\theta + 3\theta)}{\sin(5\theta - 3\theta)} = \frac{\sin 8\theta}{\sin 2\theta} \\
&= \frac{2 \sin 4\theta \cos 4\theta}{\sin 2\theta} \\
&= \frac{2 (2 \sin 2\theta \cos 2\theta) \cos 4\theta}{\sin 2\theta} \\
&= 4 \cos 2\theta \cos 4\theta = \textbf{RHS}
\end{aligned}
$$

---

### Example 15:

Prove that $\frac{\sec 8\theta - 1}{\sec 4\theta - 1} = \frac{\tan 8\theta}{\tan 2\theta}$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \frac{\sec 8\theta - 1}{\sec 4\theta - 1} \\
&= \frac{\frac{1}{\cos 8\theta} - 1}{\frac{1}{\cos 4\theta} - 1} = \frac{\frac{1 - \cos 8\theta}{\cos 8\theta}}{\frac{1 - \cos 4\theta}{\cos 4\theta}} \\
&= \frac{1 - \cos 8\theta}{1 - \cos 4\theta} \cdot \frac{\cos 4\theta}{\cos 8\theta} \\
&= \frac{2 \sin^{2} 4\theta}{2 \sin^{2} 2\theta} \cdot \frac{\cos 4\theta}{\cos 8\theta} \\
&= \frac{\sin 4\theta (\sin 4\theta \cos 4\theta)}{\sin^{2} 2\theta \cos 8\theta} \\
&= \frac{\sin 4\theta (\frac{1}{2} \sin 8\theta)}{\sin^{2} 2\theta \cos 8\theta} \\
&= \frac{(2 \sin 2\theta \cos 2\theta) (\frac{1}{2} \sin 8\theta)}{\sin^{2} 2\theta \cos 8\theta} \\
&= \frac{\sin 2\theta \cos 2\theta \sin 8\theta}{\sin^{2} 2\theta \cos 8\theta} \\
&= \frac{\cos 2\theta \sin 8\theta}{\sin 2\theta \cos 8\theta} = \frac{\sin 8\theta}{\cos 8\theta} \cdot \frac{\cos 2\theta}{\sin 2\theta} \\
&= \tan 8\theta \cot 2\theta = \frac{\tan 8\theta}{\tan 2\theta} = \textbf{RHS}
\end{aligned}
$$

---

### Example 16:

Show that $\sqrt{2 + \sqrt{2 + 2 \cos 4\theta}} = 2 \cos \theta$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \sqrt{2 + \sqrt{2 + 2 \cos 4\theta}} \\
&= \sqrt{2 + \sqrt{2(1 + \cos 4\theta)}} \\
&= \sqrt{2 + \sqrt{2(2 \cos^{2} 2\theta)}} \quad [\because 1 + \cos 2A = 2 \cos^2 A] \\
&= \sqrt{2 + \sqrt{4 \cos^{2} 2\theta}} \\
&= \sqrt{2 + 2 \cos 2\theta} \\
&= \sqrt{2(1 + \cos 2\theta)} \\
&= \sqrt{2(2 \cos^{2} \theta)} \\
&= \sqrt{4 \cos^{2} \theta} = 2 \cos \theta = \textbf{RHS}
\end{aligned}
$$

---

### Example 17:

Prove that $\cos 5x = 16 \cos^{5} x - 20 \cos^{3} x + 5 \cos x$.

#### Solution:

$$
\begin{aligned}
\cos 5x &= \cos(3x + 2x) \\
&= \cos 3x \cos 2x - \sin 3x \sin 2x \\
&= (4 \cos^3 x - 3 \cos x)(2 \cos^2 x - 1) - (3 \sin x - 4 \sin^3 x)(2 \sin x \cos x) \\
&= (8 \cos^5 x - 4 \cos^3 x - 6 \cos^3 x + 3 \cos x) - (6 \sin^2 x \cos x - 8 \sin^4 x \cos x) \\
&= (8 \cos^5 x - 10 \cos^3 x + 3 \cos x) - 6(1 - \cos^2 x)\cos x + 8(1 - \cos^2 x)^2 \cos x \\
&= 8 \cos^5 x - 10 \cos^3 x + 3 \cos x - 6\cos x + 6\cos^3 x + 8(1 - 2\cos^2 x + \cos^4 x)\cos x \\
&= 8 \cos^5 x - 4 \cos^3 x - 3 \cos x + 8\cos x - 16\cos^3 x + 8\cos^5 x \\
&= 16 \cos^5 x - 20 \cos^3 x + 5 \cos x = \textbf{RHS}
\end{aligned}
$$

---

### Example 18:

Prove that $\cos 6x = 32 \cos^{6} x - 48 \cos^{4} x + 18 \cos^{2} x - 1$.

#### Solution:

$$
\begin{aligned}
\cos 6x &= \cos 2(3x) \\
&= 2 \cos^{2}(3x) - 1 \quad [\because \cos 2\theta = 2\cos^2\theta - 1] \\
&= 2(\cos 3x)^2 - 1 \\
&= 2(4 \cos^{3} x - 3 \cos x)^2 - 1 \\
&= 2(16 \cos^{6} x - 24 \cos^{4} x + 9 \cos^{2} x) - 1 \\
&= 32 \cos^{6} x - 48 \cos^{4} x + 18 \cos^{2} x - 1 = \textbf{RHS}
\end{aligned}
$$

---

### Example 19:

Prove that $\cot 2x \cot x - \cot 3x \cot 2x - \cot 3x \cot x = 1$.

#### Solution:

We start with the identity for $\cot(A+B)$:
$$
\begin{aligned}
\cot 3x &= \cot(2x + x) \\
\cot 3x &= \frac{\cot 2x \cot x - 1}{\cot 2x + \cot x} \\
\cot 3x (\cot 2x + \cot x) &= \cot 2x \cot x - 1 \\
\cot 3x \cot 2x + \cot 3x \cot x &= \cot 2x \cot x - 1 \\
1 &= \cot 2x \cot x - \cot 3x \cot 2x - \cot 3x \cot x
\end{aligned}
$$
Hence, $\cot 2x \cot x - \cot 3x \cot 2x - \cot 3x \cot x = 1$.

---

### Example 20:

Find the value of:
- (i) $\sin 18^{\circ}$
- (ii) $\cos 18^{\circ}$
- (iii) $\cos 36^{\circ}$
- (iv) $\sin 36^{\circ}$
- (v) $\sin 72^{\circ}$
- (vi) $\cos 72^{\circ}$
- (vii) $\sin 54^{\circ}$
- (viii) $\cos 54^{\circ}$

#### Solution:

- **(i)** Let $\theta = 18^{\circ}$.
$$
\begin{aligned}
5\theta &= 90^{\circ} \\
2\theta &= 90^{\circ} - 3\theta \\
\sin(2\theta) &= \sin(90^{\circ} - 3\theta) = \cos(3\theta) \\
2 \sin\theta \cos\theta &= 4 \cos^{3}\theta - 3 \cos\theta \\
\end{aligned}
$$
Since $\cos 18^{\circ} \neq 0$, we can divide by $\cos\theta$:
$$
\begin{aligned}
2 \sin\theta &= 4 \cos^{2}\theta - 3 \\
2 \sin\theta &= 4(1 - \sin^{2}\theta) - 3 \\
2 \sin\theta &= 4 - 4 \sin^{2}\theta - 3 \\
4 \sin^{2}\theta + 2 \sin\theta - 1 &= 0
\end{aligned}
$$
Using the quadratic formula, $\sin\theta = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$:
$$
\sin\theta = \frac{-2 \pm \sqrt{4 - 4(4)(-1)}}{8} = \frac{-2 \pm \sqrt{20}}{8} = \frac{-2 \pm 2\sqrt{5}}{8} = \frac{-1 \pm \sqrt{5}}{4}
$$
Since $18^{\circ}$ is in Quadrant I, $\sin 18^{\circ}$ must be positive.
$$
\sin 18^{\circ} = \frac{\sqrt{5} - 1}{4}
$$

- **(ii)** $\cos 18^{\circ}$
$$
\cos^{2} 18^{\circ} = 1 - \sin^{2} 18^{\circ} = 1 - \left(\frac{\sqrt{5} - 1}{4}\right)^2 = 1 - \frac{5 - 2\sqrt{5} + 1}{16} = 1 - \frac{6 - 2\sqrt{5}}{16} = \frac{16 - 6 + 2\sqrt{5}}{16} = \frac{10 + 2\sqrt{5}}{16}
$$
$$
\cos 18^{\circ} = \sqrt{\frac{10 + 2\sqrt{5}}{16}} = \frac{\sqrt{10 + 2\sqrt{5}}}{4}
$$

- **(iii)** $\cos 36^{\circ}$
$$
\cos 36^{\circ} = 1 - 2 \sin^{2} 18^{\circ} = 1 - 2 \left(\frac{\sqrt{5} - 1}{4}\right)^2 = 1 - 2\left(\frac{6 - 2\sqrt{5}}{16}\right) = 1 - \frac{6 - 2\sqrt{5}}{8} = \frac{8 - 6 + 2\sqrt{5}}{8} = \frac{2 + 2\sqrt{5}}{8} = \frac{\sqrt{5} + 1}{4}
$$

- **(iv)** $\sin 36^{\circ}$
$$
\sin^{2} 36^{\circ} = 1 - \cos^{2} 36^{\circ} = 1 - \left(\frac{\sqrt{5} + 1}{4}\right)^2 = 1 - \frac{6 + 2\sqrt{5}}{16} = \frac{16 - 6 - 2\sqrt{5}}{16} = \frac{10 - 2\sqrt{5}}{16}
$$
$$
\sin 36^{\circ} = \frac{\sqrt{10 - 2\sqrt{5}}}{4}
$$

- **(v)** $\sin 72^{\circ} = \sin(90^{\circ} - 18^{\circ}) = \cos 18^{\circ} = \frac{\sqrt{10 + 2\sqrt{5}}}{4}$

- **(vi)** $\cos 72^{\circ} = \cos(90^{\circ} - 18^{\circ}) = \sin 18^{\circ} = \frac{\sqrt{5} - 1}{4}$

- **(vii)** $\sin 54^{\circ} = \sin(90^{\circ} - 36^{\circ}) = \cos 36^{\circ} = \frac{\sqrt{5} + 1}{4}$

- **(viii)** $\cos 54^{\circ} = \cos(90^{\circ} - 36^{\circ}) = \sin 36^{\circ} = \frac{\sqrt{10 - 2\sqrt{5}}}{4}$

---

## Summary of Special Angles

- (i) $\sin 18^{\circ} = \frac{\sqrt{5} - 1}{4} = \cos 72^{\circ}$
- (ii) $\cos 18^{\circ} = \frac{\sqrt{10 + 2\sqrt{5}}}{4} = \sin 72^{\circ}$
- (iii) $\cos 36^{\circ} = \frac{\sqrt{5} + 1}{4} = \sin 54^{\circ}$
- (iv) $\sin 36^{\circ} = \frac{\sqrt{10 - 2\sqrt{5}}}{4} = \cos 54^{\circ}$

---

### Example 21:

Prove that $\sin \frac{\pi}{10} + \sin \frac{13\pi}{10} = -\frac{1}{2}$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \sin \frac{\pi}{10} + \sin \frac{13\pi}{10} \\
&= \sin 18^{\circ} + \sin(13 \times 18^{\circ}) = \sin 18^{\circ} + \sin 234^{\circ} \\
&= \sin 18^{\circ} + \sin(180^{\circ} + 54^{\circ}) \\
&= \sin 18^{\circ} - \sin 54^{\circ} \quad [\because \sin(180^{\circ} + \theta) = -\sin\theta] \\
&= \sin 18^{\circ} - \cos 36^{\circ} \quad [\because \sin 54^{\circ} = \sin(90^{\circ} - 36^{\circ}) = \cos 36^{\circ}] \\
&= \frac{\sqrt{5} - 1}{4} - \frac{\sqrt{5} + 1}{4} \\
&= \frac{\sqrt{5} - 1 - \sqrt{5} - 1}{4} = \frac{-2}{4} = -\frac{1}{2} = \textbf{RHS}
\end{aligned}
$$

---

### Example 22:

Prove that $\cos^{2} 48^{\circ} - \sin^{2} 12^{\circ} = \frac{\sqrt{5} + 1}{8}$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \cos^{2} 48^{\circ} - \sin^{2} 12^{\circ} \\
&= \frac{1 + \cos(2 \times 48^{\circ})}{2} - \frac{1 - \cos(2 \times 12^{\circ})}{2} \quad [\because \cos^2 A = \frac{1+\cos 2A}{2}, \sin^2 A = \frac{1-\cos 2A}{2}] \\
&= \frac{1}{2} (1 + \cos 96^{\circ} - 1 + \cos 24^{\circ}) \\
&= \frac{1}{2} (\cos 96^{\circ} + \cos 24^{\circ}) \\
&= \frac{1}{2} \left[ 2 \cos\left(\frac{96^{\circ} + 24^{\circ}}{2}\right) \cos\left(\frac{96^{\circ} - 24^{\circ}}{2}\right) \right] \\
&= \cos 60^{\circ} \cos 36^{\circ} \\
&= \frac{1}{2} \times \frac{\sqrt{5} + 1}{4} = \frac{\sqrt{5} + 1}{8} = \textbf{RHS}
\end{aligned}
$$

---

### Example 23:

Prove that $\sin^{2} 72^{\circ} - \sin^{2} 60^{\circ} = \frac{\sqrt{5} - 1}{8}$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \sin^{2} 72^{\circ} - \sin^{2} 60^{\circ} \\
&= \frac{1 - \cos(144^{\circ})}{2} - \frac{1 - \cos(120^{\circ})}{2} \\
&= \frac{1}{2} (\cos 120^{\circ} - \cos 144^{\circ}) \\
&= \frac{1}{2} \left( -\frac{1}{2} - \cos(180^{\circ} - 36^{\circ}) \right) \\
&= \frac{1}{2} \left( -\frac{1}{2} - (-\cos 36^{\circ}) \right) = \frac{1}{2} \left( -\frac{1}{2} + \cos 36^{\circ} \right) \\
&= \frac{1}{2} \left( -\frac{1}{2} + \frac{\sqrt{5} + 1}{4} \right) \\
&= \frac{1}{2} \left( \frac{-2 + \sqrt{5} + 1}{4} \right) = \frac{\sqrt{5} - 1}{8} = \textbf{RHS}
\end{aligned}
$$

---

### Example 24:

Prove that $\cos 6^{\circ} \cos 42^{\circ} \cos 66^{\circ} \cos 78^{\circ} = \frac{1}{16}$.

#### Solution:

$$
\begin{aligned}
\textbf{LHS} &= \cos 6^{\circ} \cos 42^{\circ} \cos 66^{\circ} \cos 78^{\circ} \\
&= (\cos 6^{\circ} \cos 66^{\circ})(\cos 42^{\circ} \cos 78^{\circ}) \\
&= \frac{1}{2}(\cos 72^{\circ} + \cos 60^{\circ}) \cdot \frac{1}{2}(\cos 120^{\circ} + \cos 36^{\circ}) \\
&= \frac{1}{4}(\sin 18^{\circ} + \frac{1}{2})(-\frac{1}{2} + \cos 36^{\circ}) \\
&= \frac{1}{4} \left( \frac{\sqrt{5} - 1}{4} + \frac{2}{4} \right) \left( -\frac{2}{4} + \frac{\sqrt{5} + 1}{4} \right) \\
&= \frac{1}{4} \left( \frac{\sqrt{5} + 1}{4} \right) \left( \frac{\sqrt{5} - 1}{4} \right) \\
&= \frac{1}{4} \left( \frac{5 - 1}{16} \right) = \frac{1}{4} \cdot \frac{4}{16} = \frac{1}{16} = \textbf{RHS}
\end{aligned}
$$

---

### Example 25:

Prove that $\sin \frac{\pi}{5} \sin \frac{2\pi}{5} \sin \frac{3\pi}{5} \sin \frac{4\pi}{5} = \frac{5}{16}$.

#### Solution:

The angles are $36^{\circ}, 72^{\circ}, 108^{\circ}, 144^{\circ}$.
$$
\begin{aligned}
\textbf{LHS} &= \sin 36^{\circ} \sin 72^{\circ} \sin 108^{\circ} \sin 144^{\circ} \\
&= \sin 36^{\circ} \sin(90^{\circ}-18^{\circ}) \sin(180^{\circ}-72^{\circ}) \sin(180^{\circ}-36^{\circ}) \\
&= \sin 36^{\circ} \cos 18^{\circ} \sin 72^{\circ} \sin 36^{\circ} \\
&= (\sin 36^{\circ} \sin 72^{\circ})^2 \\
&= (\sin 36^{\circ} \cos 18^{\circ})^2 \\
&= \left( \frac{\sqrt{10 - 2\sqrt{5}}}{4} \cdot \frac{\sqrt{10 + 2\sqrt{5}}}{4} \right)^2 \\
&= \left( \frac{\sqrt{(10 - 2\sqrt{5})(10 + 2\sqrt{5})}}{16} \right)^2 \\
&= \left( \frac{\sqrt{100 - 20}}{16} \right)^2 = \left( \frac{\sqrt{80}}{16} \right)^2 \\
&= \frac{80}{256} = \frac{16 \times 5}{16 \times 16} = \frac{5}{16} = \textbf{RHS}
\end{aligned}
$$

---

### Example 26:

Find the value of:
- (i) $\sin 22.5^{\circ}$
- (ii) $\cos 22.5^{\circ}$
- (iii) $\tan 22.5^{\circ}$

#### Solution:

- **(i)** $\sin 22.5^{\circ}$
We use the identity $1 - \cos 2\theta = 2 \sin^2 \theta$.
Let $\theta = 22.5^{\circ}$, so $2\theta = 45^{\circ}$.
$$
\sin^{2}(22.5^{\circ}) = \frac{1 - \cos 45^{\circ}}{2} = \frac{1 - \frac{1}{\sqrt{2}}}{2} = \frac{\frac{\sqrt{2}-1}{\sqrt{2}}}{2} = \frac{\sqrt{2}-1}{2\sqrt{2}}
$$
$$
\sin(22.5^{\circ}) = \sqrt{\frac{\sqrt{2}-1}{2\sqrt{2}}}
$$

- **(ii)** $\cos 22.5^{\circ}$
We use the identity $1 + \cos 2\theta = 2 \cos^2 \theta$.
$$
\cos^{2}(22.5^{\circ}) = \frac{1 + \cos 45^{\circ}}{2} = \frac{1 + \frac{1}{\sqrt{2}}}{2} = \frac{\frac{\sqrt{2}+1}{\sqrt{2}}}{2} = \frac{\sqrt{2}+1}{2\sqrt{2}}
$$
$$
\cos(22.5^{\circ}) = \sqrt{\frac{\sqrt{2}+1}{2\sqrt{2}}}
$$

- **(iii)** $\tan 22.5^{\circ}$
$$
\tan^{2}(22.5^{\circ}) = \frac{\sin^{2}(22.5^{\circ})}{\cos^{2}(22.5^{\circ})} = \frac{\frac{\sqrt{2}-1}{2\sqrt{2}}}{\frac{\sqrt{2}+1}{2\sqrt{2}}} = \frac{\sqrt{2}-1}{\sqrt{2}+1}
$$
Rationalizing the denominator:
$$
\tan^{2}(22.5^{\circ}) = \frac{\sqrt{2}-1}{\sqrt{2}+1} \times \frac{\sqrt{2}-1}{\sqrt{2}-1} = \frac{(\sqrt{2}-1)^2}{2-1} = (\sqrt{2}-1)^2
$$
$$
\tan(22.5^{\circ}) = \sqrt{2} - 1
$$

---
