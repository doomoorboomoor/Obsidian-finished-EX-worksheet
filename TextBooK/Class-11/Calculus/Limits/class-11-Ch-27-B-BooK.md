## Trigonometric Limits

For finding the limits of trigonometric functions, we use trigonometric transformations and simplify.

The following theorems are quite important.

---

### Theorem 1
- (i) $\lim _{\theta \rightarrow 0} \sin \theta=0$
- (ii) $\lim _{\theta \rightarrow 0} \cos \theta=1$

#### Proof
Consider a triangle $ABC$ in which $\angle C$ is a right angle and $\angle ABC=\theta$ radians.
Then, $\sin \theta=\frac{C A}{B A}$ and $\cos \theta=\frac{B C}{B A}$.

If we keep $BC$ fixed and go on decreasing $\theta$, we find that $A$ keeps on coming nearer and nearer to $C$.
$\therefore$ when $\theta \rightarrow 0$ then $A \rightarrow C$.
$\therefore \theta \rightarrow 0 \Rightarrow CA \rightarrow 0$ and $BA \rightarrow BC$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Calculus/Limits/class-11-Ch-27-B-BooK-001.jpg)

$$
\begin{aligned}
& \Rightarrow \frac{C A}{B A} \rightarrow 0 \text { and } \frac{B C}{B A} \rightarrow 1 \\
& \Rightarrow \sin \theta \rightarrow 0 \text { and } \cos \theta \rightarrow 1 .
\end{aligned}
$$

Thus, we have:
- (i) $\lim _{\theta \rightarrow 0} \sin \theta=0$
- (ii) $\lim _{\theta \rightarrow 0} \cos \theta=1$

---

### Theorem 2
- (i) $\lim _{x \rightarrow 0} \frac{\sin x}{x}=1$
- (ii) $\lim _{x \rightarrow 0} \frac{\tan x}{x}=1$

#### Proof
(i)
$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{\sin x}{x} &= \lim _{x \rightarrow 0} \frac{\left(x-\frac{x^{3}}{3!}+\frac{x^{5}}{5!}-\ldots\right)}{x} \quad [\text{by sine series}] \\
&= \lim _{x \rightarrow 0} \frac{x\left(1-\frac{x^{2}}{3!}+\frac{x^{4}}{5!}-\ldots\right)}{x} \\
&= \lim _{x \rightarrow 0}\left(1-\frac{x^{2}}{3!}+\frac{x^{4}}{5!}-\ldots\right) = 1 . \\
\therefore \quad \lim _{x \rightarrow 0} \frac{\sin x}{x} &= 1 .
\end{aligned}
$$

(ii)
$$
\lim _{x \rightarrow 0} \frac{\tan x}{x}=\lim _{x \rightarrow 0}\left[\frac{\sin x}{x} \cdot \frac{1}{\cos x}\right]=\lim _{x \rightarrow 0} \frac{\sin x}{x} \cdot \frac{1}{\lim _{x \rightarrow 0} \cos x}=(1 \times 1)=1
$$

---

## Solved Examples

### Example 1

Evaluate:
- (i) $\lim _{x \rightarrow 0} \frac{\sin 2 x}{x}$
- (ii) $\lim _{x \rightarrow 0} \frac{\sin 3 x}{5 x}$
- (iii) $\lim _{x \rightarrow 0}\left(\frac{\sin a x}{\sin b x}\right)$

#### Solution

(i)
$$
\begin{array}{ll}
\lim _{x \rightarrow 0} \frac{\sin 2 x}{x} & =\lim _{x \rightarrow 0}\left(\frac{2 \times \sin 2 x}{2 x}\right) \\
& =2 \cdot \lim _{2 x \rightarrow 0} \frac{\sin 2 x}{2 x} \quad [\because \text { when } x \rightarrow 0 \text { then } 2 x \rightarrow 0] \\
& =(2 \times 1)=2 \quad \left[\because \lim _{\theta \rightarrow 0} \frac{\sin \theta}{\theta}=1\right] .
\end{array}
$$

(ii)
$$
\begin{array}{ll}
\lim _{x \rightarrow 0} \frac{\sin 3 x}{5 x} & =\lim _{x \rightarrow 0}\left(\frac{3}{5} \cdot \frac{\sin 3 x}{3 x}\right) \\
& =\frac{3}{5} \cdot \lim _{3 x \rightarrow 0} \frac{\sin 3 x}{3 x} \quad [\because \text { when } x \rightarrow 0 \text { then } 3 x \rightarrow 0] \\
& =\left(\frac{3}{5} \times 1\right)=\frac{3}{5} \quad \left[\because \lim _{\theta \rightarrow 0} \frac{\sin \theta}{\theta}=1\right] .
\end{array}
$$

(iii)
$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{\sin a x}{\sin b x}\right) & =\lim _{x \rightarrow 0} \frac{a x \cdot\left(\frac{\sin a x}{a x}\right)}{b x \cdot\left(\frac{\sin b x}{b x}\right)} \\
& =\frac{a}{b} \cdot \lim _{x \rightarrow 0} \frac{\left(\frac{\sin a x}{a x}\right)}{\left(\frac{\sin b x}{b x}\right)} \\
& =\frac{a}{b} \cdot \frac{\lim _{a x \rightarrow 0} \frac{\sin a x}{a x}}{\lim _{b x \rightarrow 0} \frac{\sin b x}{b x}} \quad [\because x \rightarrow 0 \Rightarrow a x \rightarrow 0 \text { and } b x \rightarrow 0] \\
& =\left(\frac{a}{b} \times \frac{1}{1}\right)=\frac{a}{b} \quad \left[\because \lim _{\theta \rightarrow 0} \frac{\sin \theta}{\theta}=1\right] .
\end{aligned}
$$

---
### Example 2

Evaluate $\lim _{x \rightarrow 0} \frac{\sin 5 x}{\tan 3 x}$.

#### Solution

$$
\lim _{x \rightarrow 0} \frac{\sin 5 x}{\tan 3 x}=\lim _{x \rightarrow 0} \frac{5 x \cdot\left(\frac{\sin 5 x}{5 x}\right)}{3 x \cdot\left(\frac{\tan 3 x}{3 x}\right)} = \frac{5}{3} \cdot \frac{\lim _{5 x \rightarrow 0}\left(\frac{\sin 5 x}{5 x}\right)}{\lim _{3 x \rightarrow 0}\left(\frac{\tan 3 x}{3 x}\right)}=\left(\frac{5}{3} \times \frac{1}{1}\right)=\frac{5}{3}
$$

---
### Example 3

Evaluate $\lim _{x \rightarrow 0} \frac{(1-\cos x)}{x^{2}}$. [CBSE 2000]

#### Solution

$$
\lim _{x \rightarrow 0} \frac{(1-\cos x)}{x^{2}}=\lim _{x \rightarrow 0} \frac{2 \sin ^{2}(x / 2)}{\left(\frac{x}{2}\right)^{2} \times 4} = \frac{1}{2} \lim _{x \rightarrow 0}\left\{\frac{\sin (x / 2)}{(x / 2)}\right\}^{2}=\left(\frac{1}{2} \times 1^{2}\right)=\frac{1}{2}
$$

---
### Example 4

Evaluate:
- (i) $\lim _{x \rightarrow 0}\left(\frac{1-\cos 4 x}{1-\cos 5 x}\right)$ [CBSE 2002C]
- (ii) $\lim _{x \rightarrow 0}\left(\frac{1-\cos m x}{1-\cos n x}\right)$

#### Solution

(i)
$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{1-\cos 4 x}{1-\cos 5 x}\right) &= \lim _{x \rightarrow 0} \frac{2 \sin ^{2} 2 x}{2 \sin ^{2}(5 x / 2)} \\
&= \lim _{x \rightarrow 0} \frac{\sin ^{2} 2 x}{\sin ^{2}(5 x / 2)} \\
&= \lim _{x \rightarrow 0}\left\{\frac{\left\{\frac{\sin 2 x}{2 x}\right\}^{2} \cdot 4 x^{2}}{\left\{\frac{\sin (5 x / 2)}{(5 x / 2)}\right\}^{2} \cdot \frac{25 x^{2}}{4}}\right\} \\
&= \frac{16}{25} \cdot \frac{\lim _{2 x \rightarrow 0}\left(\frac{\sin 2 x}{2 x}\right)^{2}}{\lim _{\frac{5 x}{2} \rightarrow 0}\left\{\frac{\sin (5 x / 2)}{(5 x / 2)}\right\}^{2}} = \left(\frac{16}{25} \times \frac{1^{2}}{1^{2}}\right)=\frac{16}{25}
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{1-\cos m x}{1-\cos n x}\right) &= \lim _{x \rightarrow 0}\left\{\frac{2 \sin ^{2}(m x / 2)}{2 \sin ^{2}(n x / 2)}\right\}=\lim _{x \rightarrow 0}\left\{\frac{\sin ^{2}(m x / 2)}{\sin ^{2}(n x / 2)}\right\} \\
&= \lim _{x \rightarrow 0}\left\{\frac{\frac{\sin ^{2}(m x / 2)}{(m x / 2)^{2}} \times \frac{m^{2} x^{2}}{4}}{\frac{\sin ^{2}(n x / 2)}{(n x / 2)^{2}} \times \frac{n^{2} x^{2}}{4}}\right\}=\frac{m^{2}}{n^{2}} \cdot \frac{\lim _{\frac{m x}{2} \rightarrow 0}\left\{\frac{\sin (m x / 2)}{(m x / 2)}\right\}^{2}}{\lim _{\frac{n x}{2} \rightarrow 0}\left\{\frac{\sin (n x / 2)}{(n x / 2)}\right\}^{2}} \\
&= \left(\frac{m^{2}}{n^{2}} \times \frac{1^{2}}{1^{2}}\right)=\frac{m^{2}}{n^{2}}
\end{aligned}
$$

---
### Example 5

Evaluate $\lim _{x \rightarrow 0}\left(\frac{\sin 2 x+\sin 6 x}{\sin 5 x-\sin 3 x}\right)$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{\sin 2 x+\sin 6 x}{\sin 5 x-\sin 3 x}\right) &= \lim _{x \rightarrow 0}\left(\frac{2 \sin 4 x \cos 2 x}{2 \cos 4 x \sin x}\right) \\
&= \lim _{x \rightarrow 0}\left(\frac{\sin 4 x \cos 2 x}{\cos 4 x \sin x}\right) \\
&= \lim _{x \rightarrow 0}\left\{\frac{\sin 4 x}{4 x} \times \frac{x}{\sin x} \times \cos 2 x \times \frac{1}{\cos 4 x} \times 4\right\} \\
&= 4 \times \lim _{4 x \rightarrow 0} \frac{\sin 4 x}{4 x} \times \lim _{x \rightarrow 0}\left(\frac{x}{\sin x}\right) \times \lim _{2 x \rightarrow 0} \cos 2 x \times \frac{1}{\lim _{4 x \rightarrow 0} \cos 4 x} \\
&= \left(4 \times 1 \times 1 \times 1 \times \frac{1}{1}\right)=4
\end{aligned}
$$

---
### Example 6

Evaluate $\lim _{x \rightarrow \pi}\left(\frac{1+\cos x}{\tan ^{2} x}\right)$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow \pi}\left(\frac{1+\cos x}{\tan ^{2} x}\right) &= \lim _{x \rightarrow \pi} \frac{\cos ^{2} x(1+\cos x)}{\sin ^{2} x} \\
&= \lim _{x \rightarrow \pi} \frac{\cos ^{2} x(1+\cos x)}{\left(1-\cos ^{2} x\right)} \\
&= \lim _{x \rightarrow \pi} \frac{\cos ^{2} x}{(1-\cos x)}=\frac{1}{2} \quad [\text{putting } x=\pi]
\end{aligned}
$$

---
### Example 7

Evaluate $\lim _{x \rightarrow 0} \frac{x \tan x}{(1-\cos x)}$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{x \tan x}{(1-\cos x)} &= \lim _{x \rightarrow 0} \frac{x \sin x}{\cos x(1-\cos x)} \\
&= \lim _{x \rightarrow 0} \frac{x\left(1-\cos ^{2} x\right)}{\sin x \cos x(1-\cos x)} \\
&= \lim _{x \rightarrow 0} \frac{x(1+\cos x)}{\sin x \cos x} \\
&= \lim _{x \rightarrow 0} \frac{x}{\sin x} \cdot \lim _{x \rightarrow 0} \frac{(1+\cos x)}{\cos x} = \left(1 \times \frac{2}{1}\right) = 2
\end{aligned}
$$

---
### Example 8

Evaluate:
- (i) $\lim _{x \rightarrow \frac{\pi}{2}}(\sec x-\tan x)$
- (ii) $\lim _{x \rightarrow 0} \frac{(\operatorname{cosec} x-\cot x)}{x}$

#### Solution

(i)
$$
\begin{aligned}
\lim _{x \rightarrow \frac{\pi}{2}}(\sec x-\tan x) &= \lim _{x \rightarrow \frac{\pi}{2}}\left(\frac{1}{\cos x}-\frac{\sin x}{\cos x}\right) \\
&= \lim _{x \rightarrow \frac{\pi}{2}} \frac{(1-\sin x)}{\cos x} \\
&= \lim _{x \rightarrow \frac{\pi}{2}} \frac{(1-\sin x) \cos x}{\cos ^{2} x} \\
&= \lim _{x \rightarrow \frac{\pi}{2}} \frac{(1-\sin x) \cos x}{\left(1-\sin ^{2} x\right)} \\
&= \lim _{x \rightarrow \frac{\pi}{2}} \frac{\cos x}{(1+\sin x)}=0 \quad \left[\text{putting } x=\frac{\pi}{2}\right]
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{(\operatorname{cosec} x-\cot x)}{x} &= \lim _{x \rightarrow 0} \frac{\left(\frac{1}{\sin x}-\frac{\cos x}{\sin x}\right)}{x} \\
&= \lim _{x \rightarrow 0} \frac{(1-\cos x)}{x \sin x} \\
&= \lim _{x \rightarrow 0} \frac{(1-\cos x) \sin x}{x\left(1-\cos ^{2} x\right)} \\
&= \lim _{x \rightarrow 0} \frac{\sin x}{x(1+\cos x)} \\
&= \lim _{x \rightarrow 0} \frac{\sin x}{x} \cdot \lim _{x \rightarrow 0} \frac{1}{(1+\cos x)} = \left(1 \times \frac{1}{2}\right) = \frac{1}{2}
\end{aligned}
$$

---
### Example 9

Evaluate:
- (i) $\lim _{x \rightarrow 0}\left(\frac{\tan x-\sin x}{\sin ^{3} x}\right)$
- (ii) $\lim _{x \rightarrow 0} \frac{(\tan x-\sin x)}{x^{3}}$

#### Solution

(i)
$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{(\tan x-\sin x)}{\sin ^{3} x} &= \lim _{x \rightarrow 0}\left(\frac{\sin x-\sin x \cos x}{\cos x \sin ^{3} x}\right) \\
&= \lim _{x \rightarrow 0} \frac{\sin x(1-\cos x)}{\cos x \sin ^{3} x} \\
&= \lim _{x \rightarrow 0} \frac{(1-\cos x)}{\cos x \sin ^{2} x} \\
&= \lim _{x \rightarrow 0} \frac{(1-\cos x)}{\cos x\left(1-\cos ^{2} x\right)} \\
&= \lim _{x \rightarrow 0} \frac{1}{\cos x(1+\cos x)} = \frac{1}{2} \quad [\text{putting } x=0]
\end{aligned}
$$

(ii)
$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{(\tan x-\sin x)}{x^{3}} &= \lim _{x \rightarrow 0}\left(\frac{\sin x-\sin x \cos x}{x^{3} \cos x}\right) \\
&= \lim _{x \rightarrow 0} \frac{\sin x(1-\cos x)}{x^{3} \cos x} \\
&= \lim _{x \rightarrow 0}\left\{\frac{\sin x}{x} \cdot \frac{2 \sin ^{2}(x / 2)}{x^{2}} \cdot \frac{1}{\cos x}\right\} \\
&= \lim _{x \rightarrow 0}\left\{\frac{\sin x}{x} \cdot \frac{2 \sin ^{2}(x / 2)}{(x / 2)^{2}} \cdot \frac{1}{4} \cdot \frac{1}{\cos x}\right\} \\
&= \frac{1}{2} \cdot \lim _{x \rightarrow 0} \frac{\sin x}{x} \cdot \lim _{x \rightarrow 0}\left\{\frac{\sin (x / 2)}{(x / 2)}\right\}^{2} \cdot \lim _{x \rightarrow 0} \frac{1}{\cos x} \\
&= \left(\frac{1}{2} \times 1 \times 1^{2} \times 1\right) = \frac{1}{2}
\end{aligned}
$$

---
### Example 10

Evaluate $\lim _{x \rightarrow 0}\left(\frac{x^{3} \cot x}{1-\cos x}\right)$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{x^{3} \cot x}{1-\cos x}\right) &= \lim _{x \rightarrow 0}\left\{\frac{x^{3} \cot x}{(1-\cos x)} \times \frac{(1+\cos x)}{(1+\cos x)}\right\} \\
&= \lim _{x \rightarrow 0} \frac{x^{3} \cos x(1+\cos x)}{\sin x\left(1-\cos ^{2} x\right)} \\
&= \lim _{x \rightarrow 0} \frac{x^{3} \cos x(1+\cos x)}{\sin ^{3} x} \\
&= \lim _{x \rightarrow 0}\left(\frac{x}{\sin x}\right)^{3} \times \lim _{x \rightarrow 0} \cos x \times \lim _{x \rightarrow 0}(1+\cos x) \\
&= \left(1^{3} \times 1 \times 2\right)=2
\end{aligned}
$$

---
### Example 11

Evaluate $\lim _{x \rightarrow 0}\left(\frac{\sin 3 x+7 x}{4 x+\sin 2 x}\right)$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{\sin 3 x+7 x}{4 x+\sin 2 x}\right) &= \lim _{x \rightarrow 0}\left(\frac{\frac{\sin 3 x}{x}+7}{4+\frac{\sin 2 x}{x}}\right) \quad [\text{dividing num. and denom. by } x] \\
&= \lim _{x \rightarrow 0}\left[\frac{\left(\frac{\sin 3 x}{3 x}\right) \cdot 3+7}{4+\left(\frac{\sin 2 x}{2 x}\right) \cdot 2}\right] \\
&= \frac{\left[3 \times \lim _{3 x \rightarrow 0} \frac{\sin 3 x}{3 x}\right]+7}{4+\left[2 \times \lim _{2 x \rightarrow 0}\left(\frac{\sin 2 x}{2 x}\right)\right]} \\
&= \frac{(3 \times 1)+7}{4+(2 \times 1)}=\frac{10}{6}=\frac{5}{3}
\end{aligned}
$$

---
### Example 12

Evaluate $\lim _{x \rightarrow 0}\left(\frac{\tan 3 x-2 x}{3 x-\sin ^{2} x}\right)$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0}\left(\frac{\tan 3 x-2 x}{3 x-\sin ^{2} x}\right) &= \lim _{x \rightarrow 0} \frac{\left(\frac{\tan 3 x}{3 x}-\frac{2}{3}\right)}{\left(1-\frac{1}{3} \cdot \frac{\sin x}{x} \cdot \sin x\right)} \quad [\text{dividing num. and denom. by } 3x] \\
&= \frac{\left(\lim _{3 x \rightarrow 0} \frac{\tan 3 x}{3 x}-\frac{2}{3}\right)}{\left\{1-\frac{1}{3} \lim _{x \rightarrow 0} \frac{\sin x}{x} \cdot \lim _{x \rightarrow 0} \sin x\right\}} \\
&= \frac{\left(1-\frac{2}{3}\right)}{1-\left(\frac{1}{3} \times 1 \times 0\right)}=\frac{\left(\frac{1}{3}\right)}{1}=\frac{1}{3}
\end{aligned}
$$

---
### Example 13

Evaluate $\lim _{x \rightarrow 0} \frac{x \tan 4 x}{1-\cos 4 x}$. [CBSE 2004]

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{x \tan 4 x}{1-\cos 4 x} &= \lim _{x \rightarrow 0} \frac{x \sin 4 x}{\cos 4 x\left(2 \sin ^{2} 2 x\right)} \\
&= \lim _{x \rightarrow 0} \frac{2 x \sin 2 x \cos 2 x}{\cos 4 x\left(2 \sin ^{2} 2 x\right)} \\
&= \lim _{x \rightarrow 0}\left(\frac{\cos 2 x}{\cos 4 x} \cdot \frac{2 x}{\sin 2 x} \times \frac{1}{2}\right) \\
&= \frac{1}{2} \times \frac{\lim _{2 x \rightarrow 0} \cos 2 x}{\lim _{4 x \rightarrow 0} \cos 4 x} \times \lim _{2 x \rightarrow 0}\left(\frac{2 x}{\sin 2 x}\right) = \left(\frac{1}{2} \times \frac{1}{1} \times 1\right)=\frac{1}{2}
\end{aligned}
$$

---
### Example 14

Evaluate $\lim _{x \rightarrow 0} \frac{(1-\cos x \sqrt{\cos 2 x})}{x^{2}}$. [CBSE 2004C, '05]

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow 0} \frac{(1-\cos x \sqrt{\cos 2 x})}{x^{2}} &= \lim _{x \rightarrow 0}\left\{\frac{(1-\cos x \sqrt{\cos 2 x})}{x^{2}} \times \frac{(1+\cos x \sqrt{\cos 2 x})}{(1+\cos x \sqrt{\cos 2 x})}\right\} \\
&= \lim _{x \rightarrow 0}\left\{\frac{\left(1-\cos ^{2} x \cos 2 x\right)}{x^{2}} \times \frac{1}{(1+\cos x \sqrt{\cos 2 x})}\right\} \\
&= \lim _{x \rightarrow 0} \frac{\left(1-\cos ^{2} x \cos 2 x\right)}{x^{2}} \times \lim _{x \rightarrow 0} \frac{1}{(1+\cos x \sqrt{\cos 2 x})} \\
&= \lim _{x \rightarrow 0}\left\{\frac{1-\cos ^{2} x\left(1-2 \sin ^{2} x\right)}{x^{2}}\right\} \times \frac{1}{(1+1 \sqrt{1})} \\
&= \lim _{x \rightarrow 0} \frac{\left(1-\cos ^{2} x+2 \sin ^{2} x \cos ^{2} x\right)}{x^{2}} \times \frac{1}{2} \\
&= \frac{1}{2} \times \lim _{x \rightarrow 0} \frac{\left(\sin ^{2} x+2 \sin ^{2} x \cos ^{2} x\right)}{x^{2}} \\
&= \frac{1}{2} \times \lim _{x \rightarrow 0} \frac{\sin ^{2} x\left(1+2 \cos ^{2} x\right)}{x^{2}} \\
&= \frac{1}{2} \times \lim _{x \rightarrow 0}\left(\frac{\sin x}{x}\right)^{2} \times \lim _{x \rightarrow 0}\left(1+2 \cos ^{2} x\right) \\
&= \frac{1}{2} \times 1^{2} \times\left(1+2 \times 1^{2}\right)=\frac{3}{2}
\end{aligned}
$$

---
### Example 15

Evaluate $\lim _{x \rightarrow \frac{\pi}{4}} \frac{(\sin x-\cos x)}{\left(x-\frac{\pi}{4}\right)}$. [CBSE 2000, '03]

#### Solution

Put $\left(x-\frac{\pi}{4}\right)=y$ so that when $x \rightarrow \frac{\pi}{4}$ then $y \rightarrow 0$.

$$
\begin{aligned}
\lim _{x \rightarrow \frac{\pi}{4}} \frac{(\sin x-\cos x)}{\left(x-\frac{\pi}{4}\right)} &= \lim _{y \rightarrow 0} \frac{\left\{\sin \left(\frac{\pi}{4}+y\right)-\cos \left(\frac{\pi}{4}+y\right)\right\}}{y} \quad \left[\text{putting }\left(x-\frac{\pi}{4}\right)=y\right] \\
&= \lim _{y \rightarrow 0} \frac{\left\{\left(\sin \frac{\pi}{4} \cos y+\cos \frac{\pi}{4} \sin y\right)-\left(\cos \frac{\pi}{4} \cos y-\sin \frac{\pi}{4} \sin y\right)\right\}}{y} \\
&= \lim _{y \rightarrow 0} \frac{2 \sin \frac{\pi}{4} \sin y}{y} \\
&= \frac{2}{\sqrt{2}} \times \lim _{y \rightarrow 0}\left(\frac{\sin y}{y}\right) = (\sqrt{2} \times 1) = \sqrt{2}
\end{aligned}
$$

---
### Example 16

Evaluate $\lim _{x \rightarrow \frac{\pi}{2}} \frac{\cos x}{\left(\frac{\pi}{2}-x\right)}$.

#### Solution

Put $\left(x-\frac{\pi}{2}\right)=y$, so that when $x \rightarrow \frac{\pi}{2}$ then $y \rightarrow 0$.

$$
\lim _{x \rightarrow \frac{\pi}{2}} \frac{\cos x}{\left(\frac{\pi}{2}-x\right)}=\lim _{y \rightarrow 0} \frac{\cos \left(\frac{\pi}{2}+y\right)}{-y}=\lim _{y \rightarrow 0}\left(\frac{-\sin y}{-y}\right)=\lim _{y \rightarrow 0} \frac{\sin y}{y}=1
$$

---
### Example 17

Evaluate $\lim _{x \rightarrow \frac{\pi}{6}} \frac{(\sqrt{3} \sin x-\cos x)}{\left(x-\frac{\pi}{6}\right)}$.

#### Solution

$$
\begin{aligned}
\lim _{x \rightarrow \frac{\pi}{6}} \frac{(\sqrt{3} \sin x-\cos x)}{\left(x-\frac{\pi}{6}\right)} &= \lim _{x \rightarrow \frac{\pi}{6}} \frac{2\left(\frac{\sqrt{3}}{2} \sin x-\frac{1}{2} \cos x\right)}{\left(x-\frac{\pi}{6}\right)} \\
&= \lim _{x \rightarrow \frac{\pi}{6}} \frac{2\left(\sin x \cos \frac{\pi}{6}-\cos x \sin \frac{\pi}{6}\right)}{\left(x-\frac{\pi}{6}\right)} \\
&= 2 \lim _{x \rightarrow \frac{\pi}{6}} \frac{\sin \left(x-\frac{\pi}{6}\right)}{\left(x-\frac{\pi}{6}\right)} \\
&= 2 \lim _{y \rightarrow 0} \frac{\sin y}{y}=2 \quad \left[\text{putting }\left(x-\frac{\pi}{6}\right)=y\right]
\end{aligned}
$$

---
