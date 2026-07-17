## 19. Differential Equations with Variable Separable

## Method of Solving Differential Equations with Variables Separable

**General Solution:** Let the given differential equation be expressed in the form $g(y) d y=f(x) d x$.

Then, the general solution of the above differential equation is given by $\int g(y) d y=\int f(x) d x+C$, where $C$ is an arbitrary constant.

**Particular Solution:** Let $x=a$ be given and let the corresponding value of $y$ be given as $b$. Putting $x=a$ and $y=b$ in the general solution, we get the value of $C$. With this value of $C$, we get the particular solution of the given differential equation.

---

## Solved Examples

### Example 1:

Find the general solution of the differential equation

$$
(x+2) \frac{d y}{d x}=x^{2}+5 x-3(x \neq-2)
$$

#### Solution:

The given differential equation may be written as

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{x^{2}+5 x-3}{x+2} \\
\Rightarrow & d y=\left(\frac{x^{2}+5 x-3}{x+2}\right) d x \quad \text { [separating the variables] } \\
\Rightarrow & \int d y=\int\left(\frac{x^{2}+5 x-3}{x+2}\right) d x \\
\Rightarrow & y=\int\left\{x+3-\frac{9}{(x+2)}\right\} d x+C, \text { where } C \text { is an arbitrary constant } \\
\Rightarrow & y=\frac{x^{2}}{2}+3 x-9 \log |x+2|+C
\end{aligned}
$$

Hence, $y=\frac{x^{2}}{2}+3 x-9 \log |x+2|+C$ is the required general solution.

---

### Example 2:

Find the general solution of the differential equation

$$
\left(1+x^{2}\right) \frac{d y}{d x}-x=2 \tan ^{-1} x
$$

[CBSE 2007]

#### Solution:

The given differential equation may be written as

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{2 \tan ^{-1} x}{\left(1+x^{2}\right)}+\frac{x}{\left(1+x^{2}\right)} \\
\Rightarrow & d y=\left\{\frac{2 \tan ^{-1} x}{\left(1+x^{2}\right)}+\frac{x}{\left(1+x^{2}\right)}\right\} d x \quad \text { [separating the variables] } \\
\Rightarrow & \int d y=\int \frac{2 \tan ^{-1} x}{\left(1+x^{2}\right)} d x+\int \frac{x}{\left(1+x^{2}\right)} d x+C, \\
\Rightarrow & y=2 \int t d t+\frac{1}{2} \int \frac{2 x}{\left(1+x^{2}\right)} d x+C \\
& \quad\left[\text { putting } \tan ^{-1} x=t \text { and } \frac{1}{\left(1+x^{2}\right)} d x=d t \text { in } 1 \text { st integral }\right] \\
\Rightarrow & y=t^{2}+\frac{1}{2} \log \left|1+x^{2}\right|+C \\
\Rightarrow & y=\left(\tan ^{-1} x\right)^{2}+\frac{1}{2} \log \left|1+x^{2}\right|+C .
\end{aligned}
$$

Hence, $y=\left(\tan ^{-1} x\right)^{2}+\frac{1}{2} \log \left|1+x^{2}\right|+C$ is the required solution.

---

### Example 3:

Find the general solution of the differential equation $\frac{d y}{d x}=\log (x+1)$.
[CBSE 2006]

#### Solution:

We have

$$
\begin{aligned}
& \frac{d y}{d x}=\log (x+1) \\
\Rightarrow \quad & d y=\log (x+1) d x \\
\Rightarrow \quad & \int d y=\int \log (x+1) d x \quad \text { [integrating both sides] } \\
\Rightarrow \quad y & =\int\{\log (x+1) \cdot 1\} d x+C, \text { where } C \text { is an arbitrary constant } \\
= & \{\log (x+1) \cdot x\}-\int \frac{1}{(x+1)} \cdot x d x+C \quad \text { [integrating by parts] } \\
= & x \log (x+1)-\int \frac{(x+1)-1}{(x+1)} d x+C \\
= & x \log (x+1)-\int\left\{1-\frac{1}{(x+1)}\right\} d x+C \\
= & x \log (x+1)-x+\log (x+1)+C \\
= & (x+1) \log (x+1)-x+C
\end{aligned}
$$

Hence, $y=(x+1) \log (x+1)-x+C$ is the required solution.

---

### Example 4:

Find the general solution of the differential equation

$$
\frac{d y}{d x}=\sin ^{-1} x .
$$

#### Solution:

We have

$$
\begin{aligned}
\quad \frac{d y}{d x} & =\sin ^{-1} x \\
\Rightarrow \quad d y & =\sin ^{-1} x d x \quad \quad \text { [separating the variables] } \\
\Rightarrow \quad \int d y & =\int \sin ^{-1} x d x \quad \text { [integrating both sides] } \\
\Rightarrow \quad y & =\int\left\{\left(\sin ^{-1} x\right) \cdot 1\right\} d x+C, \text { where } C \text { is an arbitrary constant } \\
\quad & \quad \text { II } \\
& \quad\left(\sin ^{-1} x\right) \cdot x-\int \frac{1}{\sqrt{1-x^{2}}} \cdot x d x+C \quad \text { [integrating by parts] } \\
& \quad\left(\sin ^{-1} x\right) \cdot x+\frac{1}{2} \int \frac{-2 x}{\sqrt{1-x^{2}}} d x+C \\
& =\left(\sin ^{-1} x\right) \cdot x+\frac{1}{2} \int \frac{1}{\sqrt{t}} d t+C, \text { where }\left(1-x^{2}\right)=t \\
& =\left(\sin ^{-1} x\right) \cdot x+\frac{1}{2} \times 2 \sqrt{t}+C \\
& =\left(\sin ^{-1} x\right) x+\sqrt{1-x^{2}}+C
\end{aligned}
$$

Hence, $y=\left(\sin ^{-1} x\right) x+\sqrt{1-x^{2}}+C$ is the required solution.
Hence, $y=x\left(\sin ^{-1} x\right)+\sqrt{1-x^{2}}+C$ is the required solution of the given differential equation.

---

### Example 5:

Find the general solution of the differential equation

$$
\frac{d y}{d x}=\sqrt{4-y^{2}}(-2<y<2) .
$$

[CBSE 2002C]

#### Solution:

We have $\frac{d y}{d x}=\sqrt{4-y^{2}}$

$$
\begin{aligned}
& \Rightarrow \frac{d y}{\sqrt{4-y^{2}}}=d x \quad \text { [on separating the variables] } \\
& \Rightarrow \int \frac{d y}{\sqrt{2^{2}-y^{2}}}=\int d x \quad \text { [integrating both sides] } \\
& \Rightarrow \sin ^{-1}\left(\frac{y}{2}\right)=x+C, \text { where } C \text { is an arbitrary constant. }
\end{aligned}
$$

Hence, $\sin ^{-1}\left(\frac{y}{2}\right)=x+C$ is the required solution.

---

### Example 6:

Find the general solution of the differential equation

$$
\left(x^{3}+x^{2}+x+1\right) \frac{d y}{d x}=2 x^{2}+x .
$$

[CBSE 2010]

#### Solution:

The given differential equation may be written as

$$
\frac{d y}{d x}=\frac{2 x^{2}+x}{\left(x^{3}+x^{2}+x+1\right)}=\frac{\left(2 x^{2}+x\right)}{x^{2}(x+1)+(x+1)}=\frac{\left(2 x^{2}+x\right)}{(x+1)\left(x^{2}+1\right)}
$$

$$
\begin{aligned}
\Rightarrow \quad & d y=\left\{\frac{\left(2 x^{2}+x\right)}{(x+1)\left(x^{2}+1\right)}\right\} d x \\
\Rightarrow \quad & \int d y=\int \frac{\left(2 x^{2}+x\right)}{(x+1)\left(x^{2}+1\right)} d x \\
\Rightarrow & y=\int \frac{\left(2 x^{2}+x\right)}{(x+1)\left(x^{2}+1\right)} d x+C, \text { where } C \text { is an arbitrary constant. }
\end{aligned}
$$

... (i) [integrating both sides]

Let $\frac{2 x^{2}+x}{(x+1)\left(x^{2}+1\right)}=\frac{A}{(x+1)}+\frac{B x+C}{\left(x^{2}+1\right)}$.
Then, $2 x^{2}+x \equiv A\left(x^{2}+1\right)+(B x+C)(x+1)$. ... (ii)

Putting $x=-1$ in (ii), we get $2 A=1 \Rightarrow A=\frac{1}{2}$.
Putting $x=0$ in (ii), we get $A+C=0 \Rightarrow C=-A=\frac{-1}{2}$.
Putting $x=1$ in (ii), we get $2 A+2 B+2 C=3$.
$\therefore \quad A+B+C=\frac{3}{2} \Rightarrow \frac{1}{2}+B-\frac{1}{2}=\frac{3}{2} \Rightarrow B=\frac{3}{2}$.
$\therefore \quad A=\frac{1}{2}, B=\frac{3}{2}$ and $C=\frac{-1}{2}$.

$$
\begin{aligned}
\therefore \quad y & =\frac{1}{2} \int \frac{d x}{(x+1)}+\int \frac{\left(\frac{3}{2} x-\frac{1}{2}\right)}{\left(x^{2}+1\right)} d x+C \\
\Rightarrow \quad y & =\frac{1}{2} \int \frac{d x}{(x+1)}+\frac{3}{2} \int \frac{x}{\left(x^{2}+1\right)} d x-\frac{1}{2} \int \frac{d x}{\left(x^{2}+1\right)}+C \\
\Rightarrow \quad y & =\frac{1}{2} \log |x+1|+\frac{3}{4} \int \frac{2 x}{\left(x^{2}+1\right)} d x-\frac{1}{2} \tan ^{-1} x+C \\
\Rightarrow \quad y & =\frac{1}{2} \log |x+1|+\frac{3}{4} \log \left|x^{2}+1\right|-\frac{1}{2} \tan ^{-1} x+C .
\end{aligned}
$$

Hence, $y=\frac{1}{2} \log |x+1|+\frac{3}{4} \log \left|x^{2}+1\right|-\frac{1}{2} \tan ^{-1} x+C$ is the required solution.

---

### Example 7:

Find the general solution of the differential equation

$$
\frac{d y}{d x}=\frac{1+y^{2}}{1+x^{2}}
$$

#### Solution:

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{1+y^{2}}{1+x^{2}} \\
\Rightarrow & \frac{1}{\left(1+y^{2}\right)} d y=\frac{1}{\left(1+x^{2}\right)} d x \quad \text { [separating the variables] } \\
\Rightarrow & \int \frac{1}{\left(1+y^{2}\right)} d y=\int \frac{1}{\left(1+x^{2}\right)} d x \\
\Rightarrow & \tan ^{-1} y=\tan ^{-1} x+C_{1}, \text { where } C_{1} \text { is an arbitrary constant } \\
\Rightarrow & \tan ^{-1} y-\tan ^{-1} x=C_{1} \\
\Rightarrow & \tan ^{-1}\left(\frac{y-x}{1+y x}\right)=C_{1} \\
\Rightarrow & \frac{y-x}{1+y x}=\tan C_{1}=C, \text { where } C=\tan C_{1} .
\end{aligned}
$$

Hence, $\frac{y-x}{1+y x}=C$ is the required solution.

---

### Example 8:

Find the general solution of the differential equation

$$
\log \left(\frac{d y}{d x}\right)=(a x+b y)
$$

#### Solution:

$$
\begin{aligned}
& \log \left(\frac{d y}{d x}\right)=a x+b y \\
\Rightarrow \quad & \frac{d y}{d x}=e^{a x+b y}=e^{a x} \cdot e^{b y} \\
\Rightarrow \quad & \frac{1}{e^{b y}} d y=e^{a x} d x \quad \text { [on separating the variables] } \\
\Rightarrow \quad & \int e^{-b y} d y=\int e^{a x} d x \quad \text { [integrating both sides] } \\
\Rightarrow \quad & \frac{e^{-b y}}{-b}=\frac{e^{a x}}{a}+C \\
\Rightarrow & a e^{-b y}+b e^{a x}=C^{\prime}, \text { where } C^{\prime}=-a b C .
\end{aligned}
$$

Thus, $a e^{-b y}+b e^{a x}=C^{\prime}$ is the required solution.

---

### Example 9:

Find the general solution of the differential equation

$$
\sqrt{1+x^{2}+y^{2}+x^{2} y^{2}}+x y \frac{d y}{d x}=0
$$

[CBSE 2010]

#### Solution:

The given differential equation may be written as

$$
\begin{aligned}
& \sqrt{\left(1+x^{2}\right)+y^{2}\left(1+x^{2}\right)}+x y \frac{d y}{d x}=0 \\
\Rightarrow & \sqrt{\left(1+x^{2}\right)\left(1+y^{2}\right)}+x y \frac{d y}{d x}=0 \\
\Rightarrow & \left(\sqrt{1+x^{2}}\right)\left(\sqrt{1+y^{2}}\right)+x y \frac{d y}{d x}=0 \\
\Rightarrow & x y \frac{d y}{d x}=-\left(\sqrt{1+x^{2}}\right)\left(\sqrt{1+y^{2}}\right) \\
\Rightarrow & \frac{y}{\sqrt{1+y^{2}}} d y=\frac{-\sqrt{1+x^{2}}}{x} d x
\end{aligned}
$$

$\Rightarrow \int \frac{y}{\sqrt{1+y^{2}}} d y=-\int \frac{\sqrt{1+x^{2}}}{x^{2}} \cdot x d x$. ... (i)

Putting $1+x^{2}=u^{2}$ and $1+y^{2}=v^{2}$, we get
$2 x d x=2 u d u$ and $2 y d y=2 v d v$
$\Rightarrow \quad x d x=u d u$ and $y d y=v d v$.
Substituting these values in (i), we get

$$
\begin{aligned}
& \int \frac{v d v}{v}=-\int \frac{u \times u d u}{\left(u^{2}-1\right)} \\
\Rightarrow & \int d v=-\int \frac{u^{2}}{\left(u^{2}-1\right)} d u=-\int \frac{\left(u^{2}-1\right)+1}{\left(u^{2}-1\right)} d u \\
\Rightarrow & v=-\int\left\{1+\frac{1}{\left(u^{2}-1\right)}\right\} d u+C, \text { where } C \text { is an arbitrary constant } \\
\Rightarrow & v=-u-\frac{1}{2} \log \left|\frac{u-1}{u+1}\right|+C \\
\Rightarrow & \sqrt{1+y^{2}}=-\sqrt{1+x^{2}}-\frac{1}{2} \log \left|\frac{\sqrt{1+x^{2}}-1}{\sqrt{1+x^{2}}+1}\right|+C
\end{aligned}
$$

which is the required solution.

---

### Example 10:

Find the general solution of the differential equation

$$
(x \cos y) d y=e^{x}(x \log x+1) d x
$$

[CBSE 2007]

#### Solution:

The given differential equation may be written as

$$
\begin{gathered}
\cos y d y=\left(e^{x} \log x+\frac{e^{x}}{x}\right) d x \\
\Rightarrow \quad \int \cos y d y=\int\left(\log _{\mathrm{I}} x\right) e_{\mathrm{II}}^{x} d x+\int \frac{e^{x}}{x} d x+C
\end{gathered}
$$

where $C$ is an arbitrary constant
$$
\begin{aligned}
\Rightarrow \quad \sin y & =(\log x) e^{x}-\int \frac{1}{x} \cdot e^{x} d x+\int \frac{e^{x}}{x} d x+C \text { [integrating by parts] } \\
\Rightarrow \quad \sin y & =(\log x) e^{x}+C, \text { which is the required solution. }
\end{aligned}
$$

---

### Example 11:

Find the general solution of the differential equation

$$
x \sqrt{1-y^{2}} d x+y \sqrt{1-x^{2}} d y=0
$$

#### Solution:

We have

$$
\begin{aligned}
& x \sqrt{1-y^{2}} d x+y \sqrt{1-x^{2}} d y=0 \\
\Rightarrow & \frac{x}{\sqrt{1-x^{2}}} d x+\frac{y}{\sqrt{1-y^{2}}} d y=0 \quad \text { [on separating the variables] }
\end{aligned}
$$

$$
\begin{aligned}
\Rightarrow & \int \frac{x}{\sqrt{1-x^{2}}} d x+\int \frac{y}{\sqrt{1-y^{2}}} d y=C \quad \text { [integrating both sides] } \\
\Rightarrow & -\frac{1}{2} \cdot \int \frac{(-2 x)}{\sqrt{1-x^{2}}} d x-\frac{1}{2} \cdot \int \frac{(-2 y)}{\sqrt{1-y^{2}}} d y=C \\
\Rightarrow & \quad-\frac{1}{2} \cdot \int \frac{1}{\sqrt{t}} d t-\frac{1}{2} \cdot \int \frac{1}{\sqrt{s}} d s=C, \text { where }\left(1-x^{2}\right)=t \text { and }\left(1-y^{2}\right)=s \\
\Rightarrow & -\frac{1}{2} \int t^{-1 / 2} d t-\frac{1}{2} \int s^{-1 / 2} d s=C \\
\Rightarrow & -\sqrt{t}-\sqrt{s}=C \\
\Rightarrow & \quad \sqrt{t}+\sqrt{s}=k \quad[\text { where } k=-C] \\
\Rightarrow & \sqrt{1-x^{2}}+\sqrt{1-y^{2}}=k .
\end{aligned}
$$

Hence, $\sqrt{1-x^{2}}+\sqrt{1-y^{2}}=k$ is the required solution.

---

### Example 12:

Find the general solution of the differential equation

$$
y-x \frac{d y}{d x}=a\left(y^{2}+\frac{d y}{d x}\right) .
$$

[CBSE 2008]

#### Solution:

We have

$$
\begin{aligned}
& y-x \frac{d y}{d x}=a\left(y^{2}+\frac{d y}{d x}\right) \\
\Rightarrow & \left(y-a y^{2}\right)=(a+x) \frac{d y}{d x} \\
\Rightarrow & \frac{d y}{y(1-a y)}=\frac{d x}{(a+x)} \quad \text { [on separating the variables] } \\
\Rightarrow & \int \frac{d y}{y(1-a y)}=\int \frac{d x}{(a+x)} \quad \text { [integrating both sides] } \\
\Rightarrow & \int\left(\frac{1}{y}+\frac{a}{1-a y}\right) d y=\int \frac{d x}{(a+x)} \quad \text { [by partial fractions] } \\
\Rightarrow & \log |y|-\log |1-a y|=\log |a+x|+\log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$$
\begin{aligned}
\Rightarrow \quad \log \left|\frac{y}{(1-a y)(a+x)}\right| & =\log \left|C_{1}\right| \\
\Rightarrow \quad \frac{y}{(1-a y)(a+x)} & = \pm C_{1}=C \text { (say). }
\end{aligned}
$$

Hence, $y=C(1-a y)(a+x)$ is the required solution.

---

### Example 13:

Find the general solution of the differential equation

$$
(\sqrt{a+x}) \frac{d y}{d x}+x=0 .
$$

#### Solution:

We have

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{-x}{\sqrt{a+x}} \\
\Rightarrow \quad & d y=\frac{-x}{\sqrt{a+x}} d x \quad \text { [on separating the variables] } \\
\Rightarrow \quad & \int d y=\int \frac{-x}{\sqrt{a+x}} d x \quad \text { [integrating both sides] } \\
\Rightarrow \quad & y=-\int \frac{[(a+x)-a]}{\sqrt{a+x}} d x \\
\Rightarrow & y=-\int\left(\sqrt{a+x}-\frac{a}{\sqrt{a+x}}\right) d x \\
\Rightarrow \quad & y=-\int \sqrt{a+x} d x+a \int(a+x)^{-1 / 2} d x \\
\Rightarrow & y=-\frac{2}{3}(a+x)^{3 / 2}+2 a \sqrt{a+x}+C, \text { which is the required solution. }
\end{aligned}
$$

---

### Example 14:

Solve the differential equation

$$
x \cos y d y=\left(x e^{x} \log x+e^{x}\right) d x
$$

#### Solution:

We have

$$
\begin{aligned}
& x \cos y d y=\left(x e^{x} \log x+e^{x}\right) d x \\
\Rightarrow & \cos y d y=e^{x}\left(\log x+\frac{1}{x}\right) d x \quad[\text { on separating the variables }] \\
\Rightarrow & \int \cos y d y=\int e^{x}\left(\log x+\frac{1}{x}\right) d x \quad[\text { integrating both sides }] \\
\Rightarrow & \sin y=e^{x} \log x+C \quad\left[\because \quad \int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x=e^{x} f(x)\right]
\end{aligned}
$$

Hence, $\sin y=e^{x}(\log x)+C$ is the required solution.

---

### Example 15:

Solve the differential equation

$$
\frac{d y}{d x}=\frac{e^{x}\left(\sin ^{2} x+\sin 2 x\right)}{y(2 \log y+1)}
$$

#### Solution:

We have

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{e^{x}\left(\sin ^{2} x+\sin 2 x\right)}{y(2 \log y+1)} \\
\Rightarrow & y(2 \log y+1) d y=e^{x}\left(\sin ^{2} x+\sin 2 x\right) d x \\
\Rightarrow & 2 \int_{\text {II }} y \log y d y+\int y d y=\int e^{x}\left(\sin ^{2} x+\sin 2 x\right) d x \\
\Rightarrow & 2\left[(\log y) \cdot \frac{y^{2}}{2}-\int \frac{1}{y} \cdot \frac{y^{2}}{2} d y\right]+\frac{1}{2} y^{2}=\int e^{x}\left(\sin ^{2} x+\sin 2 x\right) d x
\end{aligned}
$$

[integrating by parts]
$$
\begin{aligned}
\Rightarrow & \quad y^{2}(\log y)-\int y d y+\frac{1}{2} y^{2}=\int e^{x}\left(\sin ^{2} x+\sin 2 x\right) d x \\
\Rightarrow & \quad y^{2}(\log y)=e^{x} \sin ^{2} x+C \quad\left[\because \int e^{x}\left\{f(x)+f^{\prime}(x)\right\} d x=e^{x} f(x)+C\right] .
\end{aligned}
$$

$\therefore \quad y^{2}(\log y)=e^{x} \sin ^{2} x+C$ is the required solution.

---

### Example 16:

Solve the differential equation

$$
(1+x)\left(1+y^{2}\right) d x+(1+y)\left(1+x^{2}\right) d y=0
$$

#### Solution:

$$
\begin{aligned}
& (1+x)\left(1+y^{2}\right) d x+(1+y)\left(1+x^{2}\right) d y=0 \\
\Rightarrow & \frac{(1+x)}{\left(1+x^{2}\right)} d x+\frac{(1+y)}{\left(1+y^{2}\right)} d y=0 \quad \text { [on separating the variables] } \\
\Rightarrow & \int \frac{(1+x)}{\left(1+x^{2}\right)} d x+\int \frac{(1+y)}{\left(1+y^{2}\right)} d y=C \quad \text { [integrating both sides] } \\
\Rightarrow & \int\left\{\frac{1}{\left(1+x^{2}\right)}+\frac{x}{\left(1+x^{2}\right)}\right\} d x+\int\left\{\frac{1}{\left(1+y^{2}\right)}+\frac{y}{\left(1+y^{2}\right)}\right\} d y=C \\
\Rightarrow & \int \frac{1}{\left(1+x^{2}\right)} d x+\frac{1}{2} \cdot \int \frac{2 x}{\left(1+x^{2}\right)} d x+\int \frac{1}{\left(1+y^{2}\right)} d y+\frac{1}{2} \cdot \int \frac{2 y}{\left(1+y^{2}\right)} d y=C \\
\Rightarrow & \tan ^{-1} x+\frac{1}{2} \log \left(1+x^{2}\right)+\tan ^{-1} y+\frac{1}{2} \log \left(1+y^{2}\right)=C \\
\Rightarrow & \tan ^{-1} x+\tan ^{-1} y+\frac{1}{2}\left\{\log \left(1+x^{2}\right)+\log \left(1+y^{2}\right)\right\}=C
\end{aligned}
$$

which is the required solution.

---

### Example 17:

Solve the differential equation

$$
\operatorname{cosec} x \log y \frac{d y}{d x}+x^{2} y^{2}=0 .
$$

[CBSE 2014]

#### Solution:

The given differential equation may be written as

$$
\begin{aligned}
& \operatorname{cosec} x \log y \frac{d y}{d x}=-x^{2} y^{2} \\
\Rightarrow & \frac{\log y}{y^{2}} d y=-x^{2} \sin x d x \quad \text { [separating the variables] } \\
\Rightarrow & \int\left(\log _{\mathrm{I}} y\right)\left(\frac{1}{y^{2}}\right) d y=-\int_{\mathrm{II}} x_{\mathrm{I}}^{2} \sin _{\mathrm{II}} x d x \quad \text { [integrating both sides]. }
\end{aligned}
$$

Integrating by parts on each side, we get:

$$
\begin{aligned}
& (\log y)\left(\frac{-1}{y}\right)-\int \frac{1}{y} \cdot\left(\frac{-1}{y}\right) d y=-\left[x^{2}(-\cos x)-\int 2 x(-\cos x) d x\right]+C_{1} \\
\Rightarrow & \frac{-\log y}{y}+\int \frac{1}{y^{2}} d y=x^{2} \cos x-2 \int_{\mathrm{I}} x \cos x d x+C_{1} \\
\Rightarrow & \frac{-\log y}{y}-\frac{1}{y}=x^{2} \cos x-2 x \sin x+2 \int \sin x d x+C_{1} \\
\Rightarrow & \frac{-\log y}{y}-\frac{1}{y}=x^{2} \cos x-2 x \sin x-2 \cos x+C_{1} \\
\Rightarrow & \frac{\log y}{y}+\frac{1}{y}=-x^{2} \cos x+2 x \sin x+2 \cos x+C, \text { where }-C_{1}=C .
\end{aligned}
$$

This is the required solution of the given differential equation.

---

### Example 18:

Show that the general solution of the differential equation $\frac{d y}{d x}+\frac{y^{2}+y+1}{x^{2}+x+1}=0$ is given by $(x+y+1)=C(1-x-y-2 x y)$, where $C$ is an arbitrary constant.

#### Solution:

We have

$$
\begin{aligned}
& \frac{d y}{d x}+\frac{y^{2}+y+1}{x^{2}+x+1}=0 \\
\Rightarrow & \frac{d y}{d x}=\frac{-\left(y^{2}+y+1\right)}{\left(x^{2}+x+1\right)} \\
\Rightarrow & \frac{d y}{\left(y^{2}+y+1\right)}=-\frac{d x}{\left(x^{2}+x+1\right)} \\
\Rightarrow & \int \frac{d y}{\left(y^{2}+y+1\right)}=-\int \frac{d x}{\left(x^{2}+x+1\right)} \quad \text { [on integrating both sides] } \\
\Rightarrow & \int \frac{d y}{\left\{\left(y+\frac{1}{2}\right)^{2} j+\left(\frac{\sqrt{3}}{2}\right)^{2}\right\}}=-\int \frac{d x}{\left\{\left(x+\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}\right\}} \\
\Rightarrow & \frac{1}{\left(\frac{\sqrt{3}}{2}\right) \tan ^{-1}\left(\frac{y+\frac{1}{2}}{\sqrt{3}}\right)}=\frac{-1}{\left(\frac{\sqrt{3}}{2}\right)} \tan ^{-1}\left(\frac{x+\frac{1}{2}}{\frac{\sqrt{3}}{2}}\right)+C_{1} \\
\Rightarrow & \left(\frac{2}{\sqrt{3}}\right) \tan ^{-1}\left(\frac{2 y+1}{\sqrt{3}}\right)+\left(\frac{2}{\sqrt{3}}\right) \tan ^{-1}\left(\frac{2 x+1}{\sqrt{3}}\right)=C_{1} \\
\Rightarrow & \tan ^{-1}\left(\frac{2 y+1}{\sqrt{3}}\right)+\tan ^{-1}\left(\frac{2 x+1}{\sqrt{3}}\right)=\frac{\sqrt{3}}{2} C_{1} \\
\Rightarrow & \tan ^{-1} a+\tan ^{-1} b=\frac{\sqrt{3}}{2} C_{1}, \text { where }\left(\frac{2 y+1}{\sqrt{3}}\right)=a \text { and }\left(\frac{2 x+1}{\sqrt{3}}\right)=b \\
\Rightarrow & \tan ^{-1}\left(\frac{a+b}{1-a b}\right)=\frac{\sqrt{3}}{2} C_{1}, \\
\Rightarrow & \left(\frac{a+b}{1-a b}\right)=\tan \left(\frac{\sqrt{3}}{2} C_{1}\right)
\end{aligned}
$$

Now, $a+b=\left(\frac{2 y+1}{\sqrt{3}}\right)+\left(\frac{2 x+1}{\sqrt{3}}\right)=\frac{2(x+y+1)}{\sqrt{3}}$ and $a b=\frac{(4 x y+2 x+2 y+1)}{3}$.

$$
\begin{aligned}
\therefore \quad & \frac{\left\{\frac{2(x+y+1)}{\sqrt{3}}\right\}}{\left\{1-\frac{(4 x y+2 x+2 y+1)}{3}\right\}}=\tan \left(\frac{\sqrt{3}}{2} C_{1}\right) \\
\Rightarrow & \frac{2(x+y+1)}{\sqrt{3}} \times \frac{3}{(3-4 x y-2 x-2 y-1)}=\tan \left(\frac{\sqrt{3}}{2} C_{1}\right) \\
\Rightarrow & \frac{2(x+y+1)}{\sqrt{3}} \times \frac{3}{2(1-x-y-2 x y)}=\tan \left(\frac{\sqrt{3}}{2} C_{1}\right)
\end{aligned}
$$

$\Rightarrow \quad \frac{(x+y+1)}{(1-x-y-2 x y)}=\frac{1}{\sqrt{3}} \tan \left(\frac{\sqrt{3}}{2} C_{1}\right)=C$ (say)
$\Rightarrow \quad(x+y+1)=C(1-x-y-2 x y)$,
which is the solution of the given DE.

---

### Example 19:

Solve the differential equation

$$
x\left(1+y^{2}\right) d x-y\left(1+x^{2}\right) d y=0
$$

given that $y=0$ when $x=1$.
[CBSE 2006C, '14]

#### Solution:

The given differential equation is

$$
\begin{aligned}
& x\left(1+y^{2}\right) d x-y\left(1+x^{2}\right) d y=0 \\
\Rightarrow & x\left(1+y^{2}\right) d x=y\left(1+x^{2}\right) d y \\
\Rightarrow & \frac{y}{\left(1+y^{2}\right)} d y=\frac{x}{\left(1+x^{2}\right)} d x \\
\Rightarrow & \int \frac{y}{\left(1+y^{2}\right)} d y=\int \frac{x}{\left(1+x^{2}\right)} d x \\
\Rightarrow & \frac{1}{2} \int \frac{2 y}{\left(1+y^{2}\right)} d y=\frac{1}{2} \int \frac{2 x}{\left(1+x^{2}\right)} d x \\
\Rightarrow & \frac{1}{2} \log \left(1+y^{2}\right)=\frac{1}{2} \log \left(1+x^{2}\right)+\frac{1}{2} \log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$$
\begin{aligned}
\Rightarrow & \log \left(1+y^{2}\right)=\log \left(1+x^{2}\right)+\log \left|C_{1}\right| \\
\Rightarrow & \frac{\left(1+y^{2}\right)}{\left(1+x^{2}\right)}= \pm C_{1}=C \text { (say) }
\end{aligned}
$$

$$
\begin{equation*}
\Rightarrow \quad\left(1+y^{2}\right)=C\left(1+x^{2}\right). \tag{i}
\end{equation*}
$$

Putting $x=1$ and $y=0$ in (i), we get $C=\frac{1}{2}$.
$\therefore \quad\left(1+y^{2}\right)=\frac{1}{2}\left(1+x^{2}\right) \Rightarrow\left(x^{2}-2 y^{2}\right)=1$.
Hence, $\left(x^{2}-2 y^{2}\right)=1$ is the required solution.

---

### Example 20:

Find the particular solution of the differential equation $x y \frac{d y}{d x}=(x+2)(y+2)$, it being given that $y=-1$ when $x=1$.
[CBSE 2012]

#### Solution:

The given differential equation is

$$
\begin{aligned}
& x y \frac{d y}{d x}=(x+2)(y+2) \\
\Rightarrow & \frac{y}{(y+2)} d y=\frac{(x+2)}{x} d x
\end{aligned}
$$

$\Rightarrow \quad \int \frac{y}{(y+2)} d y=\int \frac{(x+2)}{x} d x+C$, where $C$ is an arbitrary constant

$$
\begin{equation*}
\Rightarrow \int\left\{1-\frac{2}{(y+2)}\right\} d y=\int\left(1+\frac{2}{x}\right) d x+C \tag{i}
\end{equation*}
$$

$\Rightarrow \quad y-2 \log |y+2|=x+2 \log |x|+C$.

Putting $x=1$ and $y=-1$ in (i), we get $C=-2$.
Hence, the required solution is

$$
y-2 \log |y+2|=x+2 \log |x|-2
$$

---

### Example 21:

Find the particular solution of the differential equation $x\left(x^{2}-1\right) \frac{d y}{d x}=1$, it being given that $y=0$ when $x=2$.
[CBSE 2012]

#### Solution:

We have

$$
\begin{align*}
& x\left(x^{2}-1\right) \frac{d y}{d x}=1 \\
\Rightarrow & d y=\frac{1}{x\left(x^{2}-1\right)} d x \\
\Rightarrow & \int d y=\int \frac{d x}{x(x-1)(x+1)} \tag{i}
\end{align*}
$$

Let $\frac{1}{x(x-1)(x+1)}=\frac{A}{x}+\frac{B}{(x-1)}+\frac{C}{(x+1)}$.
Then, $A(x-1)(x+1)+B x(x+1)+C x(x-1) \equiv 1$. ... (ii)

Putting $x=0$ in (ii), we get $A=-1$.
Putting $x=1$ in (ii), we get $B=\frac{1}{2}$.
Putting $x=-1$ in (ii), we get $C=\frac{1}{2}$.
$\therefore \quad \frac{1}{x(x-1)(x+1)}=\frac{-1}{x}+\frac{1}{2(x-1)}+\frac{1}{2(x+1)}$.
Putting this value in (i), we get

$$
\begin{align*}
& \int d y=\int \frac{-d x}{x}+\frac{1}{2} \int \frac{d x}{(x-1)}+\frac{1}{2} \int \frac{d x}{(x+1)}+C_{1} \\
& \quad \text { where } C_{1} \text { is an arbitrary constant } \\
\Rightarrow \quad & y=-\log |x|+\frac{1}{2} \log |x-1|+\frac{1}{2} \log |x+1|+C_{1} \tag{iii}
\end{align*}
$$

We are given that $y=0$ when $x=2$.
Putting $x=2$ and $y=0$ in (iii), we get

$$
\begin{aligned}
& -\log 2+\frac{1}{2} \log 3+C_{1}=0 \\
\Rightarrow & C_{1}=\log 2-\frac{1}{2} \log 3=\frac{1}{2} \log 4-\frac{1}{2} \log 3=\frac{1}{2} \log \left(\frac{4}{3}\right) .
\end{aligned}
$$

Putting $C_{1}=\frac{1}{2} \log \left(\frac{4}{3}\right)$ in (iii) we get

$$
\begin{aligned}
& y=-\log |x|+\frac{1}{2} \log |x-1|+\frac{1}{2} \log |x+1|+\frac{1}{2} \log \frac{4}{3} \\
\Rightarrow & y=-\frac{1}{2} \log x^{2}+\frac{1}{2} \log |(x-1)(x+1)|+\frac{1}{2} \log \frac{4}{3} \\
\Rightarrow & y=\frac{1}{2} \log \left|\frac{4\left(x^{2}-1\right)}{3 x^{2}}\right|, \text { which is the required solution. }
\end{aligned}
$$

---

### Example 22:

Find the particular solution of the differential equation $(x+1) \frac{d y}{d x}=2 e^{-y}-1$, it being given that $y=0$ when $x=0$.
[CBSE 2012]

#### Solution:

We have

$$
\begin{aligned}
& (x+1) \frac{d y}{d x}=2 e^{-y}-1 \\
\Rightarrow & \frac{1}{\left(2 e^{-y}-1\right)} d y=\frac{1}{(x+1)} d x \\
\Rightarrow & \frac{e^{y}}{\left(2-e^{y}\right)} d y=\frac{1}{(x+1)} d x \\
\Rightarrow & \int \frac{e^{y}}{\left(e^{y}-2\right)} d y=\int \frac{-1}{(x+1)} d x \\
\Rightarrow & \log \left|e^{y}-2\right|=-\log |x+1|+\log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$$
\begin{equation*}
\Rightarrow \log \left|e^{y}-2\right|+\log |x+1|=\log \left|C_{1}\right| \\
\Rightarrow \log \left|(x+1)\left(e^{y}-2\right)\right|=\log \left|C_{1}\right| \tag{i}
\end{equation*}
$$

$\Rightarrow \quad(x+1)\left(e^{y}-2\right)= \pm C_{1}=C$.

It is given that when $x=0$, then $y=0$.
Putting $x=0$ and $y=0$ in (i), we get $C=-1$.
Putting $C=-1$ in (i), we get

$$
\begin{aligned}
& \quad(x+1)\left(e^{y}-2\right)=-1 \Rightarrow\left(e^{y}-2\right)=\frac{-1}{(x+1)} \\
& \Rightarrow e^{y}=\left\{2-\frac{1}{(x+1)}\right\}=\frac{(2 x+1)}{(x+1)} . \\
& \therefore \quad y=\log \left|\frac{2 x+1}{x+1}\right|, x \neq-1 \text { is the required solution. }
\end{aligned}
$$

---

### Example 23:

Solve the differential equation
$\left(1+y^{2}\right)(1+\log x) d x+x d y=0$, it being given that $y=1$ when $x=1$.
[CBSE 2000, '03, '11]

#### Solution:

We have

$$
\begin{aligned}
& \left(1+y^{2}\right)(1+\log x) d x+x d y=0 \\
\Rightarrow \quad & \frac{(1+\log x)}{x} d x+\frac{1}{\left(1+y^{2}\right)} d y=0 \quad \text { [on separating the variables] } \\
\Rightarrow \quad & \int \frac{(1+\log x)}{x} d x+\int \frac{1}{\left(1+y^{2}\right)} d y=C \quad \text { [integrating both sides] } \\
\Rightarrow & \int t d t+\tan ^{-1} y=C, \text { where }(1+\log x)=t \\
\Rightarrow & \frac{1}{2} t^{2}+\tan ^{-1} y=C, \text { where } C \text { is an arbitrary constant } \\
\Rightarrow & \quad \frac{1}{2}(1+\log x)^{2}+\tan ^{-1} y=C . \quad \ldots \text{(i)}
\end{aligned}
$$

Putting $x=1$ and $y=1$ in (i), we get

$$
\begin{align*}
& C=\frac{1}{2}+\tan ^{-1} 1 \Rightarrow C=\left(\frac{1}{2}+\frac{\pi}{4}\right)  \tag{ii}\\
\therefore & \frac{1}{2}(1+\log x)^{2}+\tan ^{-1} y=\left(\frac{1}{2}+\frac{\pi}{4}\right) \quad \text { [using (ii) in (i)] } \\
\Rightarrow & \frac{1}{2}(\log x)^{2}+\log x+\tan ^{-1} y=\frac{\pi}{4}, \text { which is the required solution. }
\end{align*}
$$

---

### Example 24:

Solve the differential equation

$$
\begin{array}{r}
\left(1+e^{2 x}\right) d y+e^{x}\left(1+y^{2}\right) d x=0 \\
\text { it being given that } y=1 \text { when } x=0
\end{array}
$$

[CBSE 2004, '08C, '11]

#### Solution:

We have

$$
\begin{aligned}
& \left(1+e^{2 x}\right) d y+e^{x}\left(1+y^{2}\right) d x=0 \\
\Rightarrow & \frac{1}{\left(1+y^{2}\right)} d y+\frac{e^{x}}{\left(1+e^{2 x}\right)} d x=0 \quad \text { [separating the variables] } \\
\Rightarrow & \int \frac{1}{\left(1+y^{2}\right)} d y+\int \frac{e^{x}}{\left(1+e^{2 x}\right)} d x=C \quad \text { [integrating both sides] } \\
\Rightarrow & \tan ^{-1} y+\int \frac{d t}{\left(1+t^{2}\right)}=C, \text { where } e^{x}=t \\
\Rightarrow & \tan ^{-1} y+\tan ^{-1} t=C \\
\Rightarrow & \tan ^{-1} y+\tan ^{-1} e^{x}=C \quad \ldots \text { (i) }\left[\because t=e^{x}\right]
\end{aligned}
$$

Putting $x=0$ and $y=1$ in (i), we get

$$
C=\tan ^{-1} 1+\tan ^{-1} e^{0}=\left(\tan ^{-1} 1+\tan ^{-1} 1\right)=\left(\frac{\pi}{4}+\frac{\pi}{4}\right)=\frac{\pi}{2}
$$

$\therefore \quad \tan ^{-1} y+\tan ^{-1} e^{x}=\frac{\pi}{2}$ is the required solution.

---

### Example 25:

Find the equation of the curve that passes through the point $(1,2)$ and satisfies the differential equation $\frac{d y}{d x}=\frac{-2 x y}{\left(x^{2}+1\right)}$.

#### Solution:

We have

$$
\begin{aligned}
& \frac{d y}{d x}=\frac{-2 x y}{\left(x^{2}+1\right)} \\
\Rightarrow \quad & \frac{d y}{y}=\frac{-2 x}{\left(x^{2}+1\right)} d x \quad \text { [on separating the variables] } \\
\Rightarrow \quad & \int \frac{d y}{y}=\int \frac{-2 x}{\left(x^{2}+1\right)} d x \quad \text { [integrating both sides] } \\
\Rightarrow \quad & \log y=-\log \left(x^{2}+1\right)+\log C,
\end{aligned}
$$

where $\log C$ is an arbitrary constant
$$
\begin{equation*}
\Rightarrow \log y+\log \left(x^{2}+1\right)=\log C \\
\Rightarrow \log \left\{y\left(x^{2}+1\right)\right\}=\log C \\
\Rightarrow y\left(x^{2}+1\right)=C \tag{i}
\end{equation*}
$$

Now, it is given that the curve passes through $(1,2)$.
So, putting $x=1$ and $y=2$ in (i), we get $C=4$.
$\therefore y\left(x^{2}+1\right)=4$ is the required equation of the curve.

---

### Example 26:

Find the equation of a curve which passes through the point $(-2,3)$ and the slope of whose tangent at any point $(x, y)$ is $\frac{2 x}{y^{2}}$.

#### Solution:

We know that the slope of a curve at a point $(x, y)$ is $\frac{d y}{d x}$.

$$
\begin{equation*}
\therefore \quad \frac{d y}{d x}=\frac{2 x}{y^{2}} \tag{i}
\end{equation*}
$$

$\Rightarrow y^{2} d y=2 x d x \quad$ [separating the variables]
$\Rightarrow \quad \int y^{2} d y=\int 2 x d x$

$$
\begin{equation*}
\Rightarrow \quad \frac{1}{3} y^{3}=x^{2}+C \tag{ii}
\end{equation*}
$$

where $C$ is a constant.
Thus, (ii) is the equation of the curve whose differential equation is given by (i).
Since the given curve passes through the point ( $-2,3$ ), we have

$$
C=\left(\frac{1}{3} \times 27\right)-(-2)^{2}=(9-4)=5 .
$$

Hence, the required equation of the curve is

$$
\frac{1}{3} y^{3}=x^{2}+5 \Rightarrow y^{3}=3 x^{2}+15 .
$$

---

### Example 27:

In a bank principal increases at the rate of $5 \%$ per annum. In how many years will $₹ 1000$ double itself?

#### Solution:

Let $P$ be the principal at any time $t$. Then,

$$
\begin{aligned}
& \frac{d P}{d t}=\left(\frac{5}{100}\right) P \\
\Rightarrow & \frac{d P}{d t}=\frac{P}{20} \\
\Rightarrow & \frac{d P}{P}=\frac{1}{20} d t
\end{aligned}
$$

$\Rightarrow \quad \int \frac{d P}{P}=\int \frac{1}{20} d t \quad$ [on integrating both sides]
$\Rightarrow \quad \log P=\frac{1}{20} t+\log C$, where $C$ is an arbitrary constant

$$
\begin{equation*}
\Rightarrow \quad \log \left(\frac{P}{C}\right)=\frac{t}{20} \tag{i}
\end{equation*}
$$

$\Rightarrow \frac{P}{C}=e^{t / 20}$.

When $t=0$, we have $P=1000$ (given).
Putting $P=1000$ and $t=0$ in (i), we get $C=1000$.
$$
\begin{equation*}
\therefore \quad P=(1000) e^{t / 20}. \tag{ii}
\end{equation*}
$$

Let $₹ 1000$ double itself in $n$ years.
Thus, when $t=n$, then $P=2000$.
Putting these values in (ii), we get

$$
\begin{aligned}
(1000) \times e^{n / 20}=2000 & \Rightarrow e^{n / 20}=2 \\
& \Rightarrow \frac{n}{20}=\log _{e} 2 \Rightarrow n=20\left(\log _{e} 2\right)
\end{aligned}
$$

Hence, the required time is $\left\{20\left(\log _{e} 2\right)\right\}$ years.

---