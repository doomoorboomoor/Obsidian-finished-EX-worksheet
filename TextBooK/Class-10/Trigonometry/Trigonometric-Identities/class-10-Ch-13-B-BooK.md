## Elimination of Trigonometric Ratios

In order to eliminate the T-ratios from given relations, we make use of the fundamental trigonometrical identities, as shown in the examples given below.

---

## Solved Examples

### Example: 1

If $x=a \sin \theta+b \cos \theta$ and $y=a \cos \theta-b \sin \theta$, prove that $x^{2}+y^{2}=a^{2}+b^{2}$.

#### Solution:

We have

$$
\begin{aligned}
x^{2}+y^{2} & =(a \sin \theta+b \cos \theta)^{2}+(a \cos \theta-b \sin \theta)^{2} \\
& =a^{2}\left(\sin ^{2} \theta+\cos ^{2} \theta\right)+b^{2}\left(\cos ^{2} \theta+\sin ^{2} \theta\right) \\
& =a^{2}+b^{2} \quad\left[\because \sin ^{2} \theta+\cos ^{2} \theta=1\right]
\end{aligned}
$$

Hence, **$x^{2}+y^{2}=a^{2}+b^{2}$**.

---

### Example: 2

If $x=a \sin \theta$ and $y=b \tan \theta$, prove that $\left(\frac{a^{2}}{x^{2}}-\frac{b^{2}}{y^{2}}\right)=1$.

#### Solution:

We have

$$
x=a \sin \theta \Rightarrow \frac{a}{x}=\frac{1}{\sin \theta} \Rightarrow \frac{a}{x}=\operatorname{cosec} \theta \tag{i}
$$

and

$$
y=b \tan \theta \Rightarrow \frac{b}{y}=\frac{1}{\tan \theta} \Rightarrow \frac{b}{y}=\cot \theta \tag{ii}
$$

Squaring (i) and (ii) and subtracting, we get

$$
\left(\frac{a^{2}}{x^{2}}-\frac{b^{2}}{y^{2}}\right)=\left(\operatorname{cosec}^{2} \theta-\cot ^{2} \theta\right)=1
$$

Hence, **$\left(\frac{a^{2}}{x^{2}}-\frac{b^{2}}{y^{2}}\right)=1$**.

---

### Example: 3

If $\tan \theta+\sin \theta=m$ and $\tan \theta-\sin \theta=n$, prove that $\left(m^{2}-n^{2}\right)=4 \sqrt{m n}$. [CBSE 2010]

#### Solution:

We have

**LHS**:
$$
\begin{aligned}
\left(m^{2}-n^{2}\right) &= (\tan \theta+\sin \theta)^{2}-(\tan \theta-\sin \theta)^{2} \\
&= 4 \tan \theta \sin \theta \quad\left[\because(a+b)^{2}-(a-b)^{2}=4 a b\right]
\end{aligned}
$$

**RHS**:
$$
\begin{aligned}
4 \sqrt{m n} &= 4 \sqrt{(\tan \theta+\sin \theta)(\tan \theta-\sin \theta)} \\
&= 4 \sqrt{\left(\tan ^{2} \theta-\sin ^{2} \theta\right)} \\
&= 4 \cdot \sqrt{\left(\frac{\sin ^{2} \theta}{\cos ^{2} \theta}-\sin ^{2} \theta\right)} \\
&= 4 \cdot \frac{\sqrt{\sin ^{2} \theta-\sin ^{2} \theta \cos ^{2} \theta}}{\cos \theta} \\
&= 4 \cdot \frac{\sin \theta}{\cos \theta} \cdot \sqrt{1-\cos ^{2} \theta} \\
&= 4 \tan \theta \cdot \sqrt{\sin ^{2} \theta} \\
&= 4 \tan \theta \sin \theta
\end{aligned}
$$

Thus, **LHS = RHS**. Hence, **$\left(m^{2}-n^{2}\right)=4 \sqrt{m n}$**.

---

### Example: 4

If $\sec \theta+\tan \theta=m$, show that $\frac{\left(m^{2}-1\right)}{\left(m^{2}+1\right)}=\sin \theta$. [CBSE 2004]

#### Solution:

We have

$$
\begin{align*}
\left(m^{2}-1\right) & =(\sec \theta+\tan \theta)^{2}-1 \\
& =\sec ^{2} \theta+\tan ^{2} \theta+2 \sec \theta \tan \theta-1 \\
& =\left(\sec ^{2} \theta-1\right)+\tan ^{2} \theta+2 \sec \theta \tan \theta \\
& =2 \tan ^{2} \theta+2 \sec \theta \tan \theta \quad\left[\because \sec ^{2} \theta-1=\tan ^{2} \theta\right] \\
& =2 \tan \theta(\tan \theta+\sec \theta) \tag{i}
\end{align*}
$$

$$
\begin{align*}
\left(m^{2}+1\right) & =(\sec \theta+\tan \theta)^{2}+1 \\
& =\sec ^{2} \theta+\tan ^{2} \theta+2 \sec \theta \tan \theta+1 \\
& =\left(1+\tan ^{2} \theta\right)+\sec ^{2} \theta+2 \sec \theta \tan \theta \\
& =2 \sec ^{2} \theta+2 \sec \theta \tan \theta \quad\left[\because 1+\tan ^{2} \theta=\sec ^{2} \theta\right] \\
& =2 \sec \theta(\sec \theta+\tan \theta) \tag{ii}
\end{align*}
$$

From (i) and (ii), we get

$$
\frac{\left(m^{2}-1\right)}{\left(m^{2}+1\right)}=\frac{2 \tan \theta(\tan \theta+\sec \theta)}{2 \sec \theta(\sec \theta+\tan \theta)} = \frac{\tan \theta}{\sec \theta}=\left(\frac{\sin \theta}{\cos \theta} \times \cos \theta\right)=\sin \theta
$$

Hence, **$\frac{\left(m^{2}-1\right)}{\left(m^{2}+1\right)}=\sin \theta$**.

---

### Example: 5

If $\sin \theta+\cos \theta=m$ and $\sec \theta+\operatorname{cosec} \theta=n$, prove that $n\left(m^{2}-1\right)=2 m$.

#### Solution:

We have

$$
\begin{aligned}
n\left(m^{2}-1\right) & =(\sec \theta+\operatorname{cosec} \theta)\left[(\sin \theta+\cos \theta)^{2}-1\right] \\
& =\left(\frac{1}{\cos \theta}+\frac{1}{\sin \theta}\right)\left[\left(\sin ^{2} \theta+\cos ^{2} \theta\right)+2 \sin \theta \cos \theta-1\right] \\
& =\frac{(\sin \theta+\cos \theta)}{\sin \theta \cos \theta} \cdot (1 + 2 \sin \theta \cos \theta - 1) \\
& =\frac{(\sin \theta+\cos \theta)}{\sin \theta \cos \theta} \cdot 2 \sin \theta \cos \theta \\
& =2(\sin \theta+\cos \theta) \\
& =2 m
\end{aligned}
$$

Hence, **$n\left(m^{2}-1\right)=2 m$**.

---

### Example: 6

If $\cos \theta+\sin \theta=\sqrt{2} \cos \theta$, show that $(\cos \theta-\sin \theta)=\sqrt{2} \sin \theta$.

#### Solution:

We have

$$
\cos \theta+\sin \theta=\sqrt{2} \cos \theta
$$

Squaring both sides,

$$
\begin{aligned}
(\cos \theta+\sin \theta)^{2} &= 2 \cos ^{2} \theta \\
\cos ^{2} \theta+\sin ^{2} \theta+2 \cos \theta \sin \theta &= 2 \cos ^{2} \theta \\
\sin ^{2} \theta &= 2 \cos ^{2} \theta - \cos ^{2} \theta - 2 \cos \theta \sin \theta \\
\sin ^{2} \theta &= \cos ^{2} \theta-2 \cos \theta \sin \theta
\end{aligned}
$$

Adding $\sin^{2} \theta$ on both sides,

$$
\begin{aligned}
\sin ^{2} \theta + \sin ^{2} \theta &= \cos ^{2} \theta-2 \cos \theta \sin \theta+\sin ^{2} \theta \\
2 \sin ^{2} \theta &= (\cos \theta-\sin \theta)^{2}
\end{aligned}
$$

Taking the square root on both sides,

$$
\sqrt{2} \sin \theta = (\cos \theta-\sin \theta)
$$

Hence, **$(\cos \theta-\sin \theta)=\sqrt{2} \sin \theta$**.

---

### Example: 7

If $\sin \theta+\sin ^{2} \theta=1$, prove that $\cos ^{2} \theta+\cos ^{4} \theta=1$.

#### Solution:

Given, $\sin \theta+\sin ^{2} \theta=1$.

$$
\begin{aligned}
\sin \theta &= 1-\sin ^{2} \theta \\
\sin \theta &= \cos ^{2} \theta \quad\left[\because 1-\sin ^{2} \theta=\cos ^{2} \theta\right]
\end{aligned}
$$

Squaring both sides,

$$
\begin{aligned}
\sin ^{2} \theta &= \cos ^{4} \theta \\
1-\cos ^{2} \theta &= \cos ^{4} \theta \quad\left[\because \sin ^{2} \theta=1-\cos ^{2} \theta\right] \\
1 &= \cos ^{4} \theta + \cos ^{2} \theta
\end{aligned}
$$

Hence, **$\cos ^{2} \theta+\cos ^{4} \theta=1$**.

---

### Example: 8

If $\cos \theta+\sin \theta=1$, prove that $\cos \theta-\sin \theta= \pm 1$.

#### Solution:

We know the identity:

$$
(\cos \theta+\sin \theta)^{2}+(\cos \theta-\sin \theta)^{2}=2\left(\cos ^{2} \theta+\sin ^{2} \theta\right)
$$

Substituting the known values,

$$
\begin{aligned}
(\cos \theta+\sin \theta)^{2}+(\cos \theta-\sin \theta)^{2} &= 2(1) \\
1^{2}+(\cos \theta-\sin \theta)^{2} &= 2 \quad [\because \cos \theta+\sin \theta=1 \text{ (given)}] \\
(\cos \theta-\sin \theta)^{2} &= 2 - 1 \\
(\cos \theta-\sin \theta)^{2} &= 1
\end{aligned}
$$

Taking the square root on both sides,

$$
(\cos \theta-\sin \theta)= \pm 1
$$

Hence, **$(\cos \theta-\sin \theta)= \pm 1$**.

---

### Example: 9

If $x \sin ^{3} \theta+y \cos ^{3} \theta=\sin \theta \cos \theta$ and $x \sin \theta=y \cos \theta$, prove that $x^{2}+y^{2}=1$.

#### Solution:

Given,

$$
x \sin ^{3} \theta+y \cos ^{3} \theta=\sin \theta \cos \theta
$$

Rewriting the expression:

$$
\begin{aligned}
(x \sin \theta) \sin ^{2} \theta+(y \cos \theta) \cos ^{2} \theta &= \sin \theta \cos \theta \\
(x \sin \theta) \sin ^{2} \theta+(x \sin \theta) \cos ^{2} \theta &= \sin \theta \cos \theta \quad [\because y \cos \theta=x \sin \theta] \\
(x \sin \theta)\left(\sin ^{2} \theta+\cos ^{2} \theta\right) &= \sin \theta \cos \theta \\
x \sin \theta &= \sin \theta \cos \theta \quad \left[\because \sin ^{2} \theta+\cos ^{2} \theta=1\right] \\
x &= \cos \theta \tag{i}
\end{aligned}
$$

Now, using $x \sin \theta=y \cos \theta$:

$$
\begin{aligned}
\cos \theta \sin \theta &= y \cos \theta \quad [\because x=\cos \theta] \\
y &= \sin \theta \tag{ii}
\end{aligned}
$$

Squaring and adding (i) and (ii), we get:

$$
x^2 + y^2 = \cos^2 \theta + \sin^2 \theta = 1
$$

Hence, **$x^{2}+y^{2}=1$**.

---

### Example: 10

If $x=a \sec \theta \cos \phi, y=b \sec \theta \sin \phi$ and $z=c \tan \theta$ then prove that $\left(\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}\right)=\left(1+\frac{z^{2}}{c^{2}}\right)$.

#### Solution:

We have

$$
\frac{x}{a}=\sec \theta \cos \phi \quad \ldots \text { (i)}
$$

$$
\frac{y}{b}=\sec \theta \sin \phi \quad \ldots \text { (ii)}
$$

Squaring and adding (i) and (ii), we get

$$
\begin{aligned}
\left(\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}\right) & =\sec ^{2} \theta \cos ^{2} \phi + \sec^{2} \theta \sin^{2} \phi \\
& = \sec ^{2} \theta\left(\cos ^{2} \phi+\sin ^{2} \phi\right) \\
& =\sec ^{2} \theta & {\left[\because \cos ^{2} \phi+\sin ^{2} \phi=1\right]} \\
& =\left(1+\tan ^{2} \theta\right) & {\left[\because \sec^2 \theta = 1 + \tan^2 \theta \right]} \\
& =\left(1+\frac{z^{2}}{c^{2}}\right) & {\left[\because \tan \theta=\frac{z}{c}\right]}
\end{aligned}
$$

Hence, **$\left(\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}\right)=\left(1+\frac{z^{2}}{c^{2}}\right)$**.

---

### Example: 11

If $x=r \sin \alpha \cos \beta, y=r \sin \alpha \sin \beta$ and $z=r \cos \alpha$, prove that $x^{2}+y^{2}+z^{2}=r^{2}$.

#### Solution:

We have

$$
\begin{aligned}
x^{2}+y^{2}+z^{2} & = (r \sin \alpha \cos \beta)^2 + (r \sin \alpha \sin \beta)^2 + (r \cos \alpha)^2 \\
& = r^{2} \sin ^{2} \alpha \cos ^{2} \beta+r^{2} \sin ^{2} \alpha \sin ^{2} \beta+r^{2} \cos ^{2} \alpha \\
& = r^{2} \sin ^{2} \alpha\left(\cos ^{2} \beta+\sin ^{2} \beta\right)+r^{2} \cos ^{2} \alpha \\
& = r^{2} \sin ^{2} \alpha(1)+r^{2} \cos ^{2} \alpha \quad\left[\because \cos ^{2} \beta+\sin ^{2} \beta=1\right] \\
& = r^{2}\left(\sin ^{2} \alpha+\cos ^{2} \alpha\right) \\
& = r^{2}(1) \quad\left[\because \sin ^{2} \alpha+\cos ^{2} \alpha=1\right]
\end{aligned}
$$

Hence, **$x^{2}+y^{2}+z^{2}=r^{2}$**.

---

### Example: 12

If $\operatorname{cosec} \theta-\sin \theta=m$ and $\sec \theta-\cos \theta=n$, prove that $\left(m^{2} n\right)^{2 / 3}+\left(m n^{2}\right)^{2 / 3}=1$.

#### Solution:

First, let's find $m^2 n$:
$$
\begin{align*}
m^{2} n &= (\operatorname{cosec} \theta-\sin \theta)^{2} \cdot(\sec \theta-\cos \theta) \\
&= \left(\frac{1}{\sin \theta}-\sin \theta\right)^{2} \cdot\left(\frac{1}{\cos \theta}-\cos \theta\right) \\
&= \frac{\left(1-\sin ^{2} \theta\right)^{2}}{\sin ^{2} \theta} \cdot \frac{\left(1-\cos ^{2} \theta\right)}{\cos \theta} \\
&= \frac{(\cos^2 \theta)^2}{\sin ^{2} \theta} \cdot \frac{\sin^2 \theta}{\cos \theta} \\
&= \frac{\cos ^{4} \theta}{\sin ^{2} \theta} \times \frac{\sin ^{2} \theta}{\cos \theta} = \cos ^{3} \theta \\
\end{align*}
$$
Therefore,
$$
\left(m^{2} n\right)^{1 / 3}=\cos \theta \tag{i}
$$

Next, let's find $mn^2$:
$$
\begin{align*}
m n^{2} &= (\operatorname{cosec} \theta-\sin \theta) \cdot(\sec \theta-\cos \theta)^{2} \\
& =\left(\frac{1}{\sin \theta}-\sin \theta\right) \cdot\left(\frac{1}{\cos \theta}-\cos \theta\right)^{2} \\
& =\frac{\left(1-\sin ^{2} \theta\right)}{\sin \theta} \cdot \frac{\left(1-\cos ^{2} \theta\right)^{2}}{\cos ^{2} \theta} \\
& =\left(\frac{\cos ^{2} \theta}{\sin \theta} \times \frac{(\sin^2 \theta)^2}{\cos ^{2} \theta}\right) \\
& =\left(\frac{\cos ^{2} \theta}{\sin \theta} \times \frac{\sin ^{4} \theta}{\cos ^{2} \theta}\right) = \sin ^{3} \theta
\end{align*}
$$
Therefore,
$$
\left(m n^{2}\right)^{1 / 3}=\sin \theta \tag{ii}
$$

Squaring (i) and (ii) and adding the results, we get

$$
\left(m^{2} n\right)^{2 / 3}+\left(m n^{2}\right)^{2 / 3} = \cos^2 \theta + \sin^2 \theta = 1
$$

Hence, **$\left(m^{2} n\right)^{2 / 3}+\left(m n^{2}\right)^{2 / 3}=1$**.

---

### Example: 13

If $a \cos \theta-b \sin \theta=c$, prove that $(a \sin \theta+b \cos \theta)= \pm \sqrt{a^{2}+b^{2}-c^{2}}$. [CBSE 2006C]

#### Solution:

Given, $a \cos \theta-b \sin \theta=c$.

We know the identity:
$$
(a \cos \theta-b \sin \theta)^{2}+(a \sin \theta+b \cos \theta)^{2} = a^{2}\left(\cos ^{2} \theta+\sin ^{2} \theta\right)+b^{2}\left(\sin ^{2} \theta+\cos ^{2} \theta\right) = \left(a^{2}+b^{2}\right)
$$
Substituting the given value,
$$
\begin{aligned}
c^{2}+(a \sin \theta+b \cos \theta)^{2} &= \left(a^{2}+b^{2}\right) \\
(a \sin \theta+b \cos \theta)^{2} &= a^{2}+b^{2}-c^{2}
\end{aligned}
$$
Taking the square root of both sides,
$$
(a \sin \theta+b \cos \theta)= \pm \sqrt{a^{2}+b^{2}-c^{2}}
$$
Hence, **$(a \sin \theta+b \cos \theta)= \pm \sqrt{a^{2}+b^{2}-c^{2}}$**.

---

### Example: 14

If $(3 \sin \theta+5 \cos \theta)=5$, prove that $(5 \sin \theta-3 \cos \theta)= \pm 3$.

#### Solution:

We have the identity:

$$
\begin{aligned}
(3 \sin \theta+5 \cos \theta)^{2}+(5 \sin \theta-3 \cos \theta)^{2} &= (9 \sin^2\theta + 30\sin\theta\cos\theta+25\cos^2\theta) + (25\sin^2\theta - 30\sin\theta\cos\theta+9\cos^2\theta) \\
&= 9(\sin^2\theta+\cos^2\theta) + 25(\sin^2\theta+\cos^2\theta) \\
&= (9+25) = 34
\end{aligned}
$$
Substituting the given value $(3 \sin \theta+5 \cos \theta)=5$:
$$
\begin{aligned}
5^{2}+(5 \sin \theta-3 \cos \theta)^{2} &= 34 \\
25+(5 \sin \theta-3 \cos \theta)^{2} &= 34 \\
(5 \sin \theta-3 \cos \theta)^{2} &= 9
\end{aligned}
$$
Taking the square root on each side,
$$
(5 \sin \theta-3 \cos \theta)= \pm 3
$$
Hence, **$(5 \sin \theta-3 \cos \theta)= \pm 3$**.

---

