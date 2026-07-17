## Solution of a Differential Equation

A function of the form $y=f(x)+C$ which satisfies a given differential equation is called its **solution**.

## General Solution of a Differential Equation

Suppose a differential equation of order $n$ is being given. If its solution contains $n$ arbitrary constants then it is called a **general solution**.

## Particular Solution of a Differential Equation

Giving particular values to arbitrary constants in the general solution of a differential equation, we get its **particular solutions**.

---

## Solved Examples

### Example 1

Verify that $y=A \cos x-B \sin x$ is a solution of the differential equation

$$
\frac{d^{2} y}{d x^{2}}+y=0
$$

[CBSE 2005C, '06]

#### Solution:

Given: $y=A \cos x-B \sin x$

$$
\begin{equation*}
\Rightarrow \frac{d y}{d x}=-A \sin x-B \cos x \tag{i}
\end{equation*}
$$

$\Rightarrow \frac{d^{2} y}{d x^{2}}=-A \cos x+B \sin x$
$ =-(A \cos x-B \sin x)=-y \quad[$ from (i) $] $
$\Rightarrow \frac{d^{2} y}{d x^{2}}+y=0$.

**Hence, $y=A \cos x-B \sin x$ is a solution of the differential equation $\frac{d^{2} y}{d x^{2}}+y=0$.**

---

### Example 2

Verify that $y=a e^{2 x}+b e^{-x}$ is a solution of the differential equation

$$
\frac{d^{2} y}{d x^{2}}-\frac{d y}{d x}-2 y=0
$$

[CBSE 2003C]

#### Solution:

Given: $y=a e^{2 x}+b e^{-x}$

$$
\begin{equation*}
\Rightarrow \frac{d y}{d x}=2 a e^{2 x}-b e^{-x} \tag{i}
\end{equation*}
$$

$$
\begin{equation*}
\Rightarrow \frac{d^{2} y}{d x^{2}}=4 a e^{2 x}+b e^{-x} \tag{ii}
\end{equation*}
$$

$$
\begin{equation*}
\therefore\left(\frac{d^{2} y}{d x^{2}}-\frac{d y}{d x}-2 y\right)=\left(4 a e^{2 x}+b e^{-x}\right)-\left(2 a e^{2 x}-b e^{-x}\right)-2\left(a e^{2 x}+b e^{-x}\right) \tag{iii}
\end{equation*}
$$

$ =0 $
[using (i), (ii) and (iii)].

**Hence, $y=a e^{2 x}+b e^{-x}$ is a solution of the differential equation**

$$
\frac{d^{2} y}{d x^{2}}-\frac{d y}{d x}-2 y=0
$$

---

### Example 3

Verify that $y=A x+\frac{B}{x}$ is a solution of the differential equation

$$
\begin{equation*}
x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}-y=0 \tag{i}
\end{equation*}
$$

#### Solution:

Given: $y=A x+\frac{B}{x}$

$$
\begin{equation*}
\Rightarrow \frac{d y}{d x}=A-\frac{B}{x^{2}} \tag{ii}
\end{equation*}
$$

$$
\begin{equation*}
\Rightarrow \frac{d^{2} y}{d x^{2}}=\frac{2 B}{x^{3}} \tag{iii}
\end{equation*}
$$

Substituting the values of $y$, $\frac{d y}{d x}$ and $\frac{d^{2} y}{d x^{2}}$ from (i), (ii) and (iii) respectively, we get

$$
\begin{aligned}
\left(x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}-y\right) & =x^{2} \cdot \frac{2 B}{x^{3}}+x\left(A-\frac{B}{x^{2}}\right)-\left(A x+\frac{B}{x}\right) \\
& =\left(\frac{2 B}{x}+A x-\frac{B}{x}-A x-\frac{B}{x}\right)=0 .
\end{aligned}
$$

Thus, $y=A x+\frac{B}{x}$ satisfies $x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}-y=0$.

**Hence, $y=A x+\frac{B}{x}$ is a solution of $x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}-y=0$.**

---

### Example 4

Verify that $y=a \cos (\log x)+b \sin (\log x)$ is a solution of the differential equation $x^{2}+\frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}+y=0$.
[CBSE 2007]

#### Solution:

Given: $y=a \cos (\log x)+b \sin (\log x)$
$\Rightarrow \frac{d y}{d x}=\frac{-a \sin (\log x)}{x}+\frac{b \cos (\log x)}{x}$ [on differentiating (i) w.r.t. $x$ ]

$$
\begin{equation*}
\Rightarrow \quad x \frac{d y}{d x}=-a \sin (\log x)+b \cos (\log x) \tag{ii}
\end{equation*}
$$

$\Rightarrow x \frac{d^{2} y}{d x^{2}}+\frac{d y}{d x}=\frac{-a \cos (\log x)}{x}-\frac{b \sin (\log x)}{x}$
[on differentiating (ii) w.r.t. $x$ ]
$\Rightarrow \quad x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}=-a \cos (\log x)-b \sin (\log x)$
$\Rightarrow \quad x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}+y=0 \quad$ [using (i)].

**Hence, $y=a \cos (\log x)+b \sin (\log x)$ is a solution of**

$$
x^{2} \frac{d^{2} y}{d x^{2}}+x \frac{d y}{d x}+y=0
$$

---

### Example 5

Verify that $y=e^{m \sin ^{-1} x}$ is a solution of the differential equation

$$
\left(1-x^{2}\right) \frac{d^{2} y}{d x^{2}}-x \frac{d y}{d x}-m^{2} y=0
$$

#### Solution:

Given: $y=e^{m \sin ^{-1} x}$

$$
\begin{equation*}
\Rightarrow \quad \frac{d y}{d x}=\frac{e^{m \sin ^{-1} x}}{\sqrt{1-x^{2}}} \cdot m \tag{i}
\end{equation*}
$$

[on differentiating (i)]

$$
\begin{equation*}
\Rightarrow \quad \sqrt{1-x^{2}}\left(\frac{d y}{d x}\right)=m y \tag{ii}
\end{equation*}
$$

$$
\left[\because e^{m \sin ^{-1} x}=y\right]
$$

$\Rightarrow \quad\left(1-x^{2}\right)\left(\frac{d y}{d x}\right)^{2}=m^{2} y^{2}$
... (iii) [on squaring both sides of (ii)]
$\Rightarrow \quad\left(1-x^{2}\right) 2 \frac{d y}{d x} \cdot\left(\frac{d^{2} y}{d x^{2}}\right)-2 x\left(\frac{d y}{d x}\right)^{2}=2 m^{2} y \frac{d y}{d x}$
[on differentiating both sides of (iii)]
$\Rightarrow 2\left(\frac{d y}{d x}\right) \cdot\left\{\left(1-x^{2}\right) \frac{d^{2} y}{d x^{2}}-x \frac{d y}{d x}-m^{2} y\right\}=0$
$\Rightarrow \quad\left(1-x^{2}\right) \frac{d^{2} y}{d x^{2}}-x \frac{d y}{d x}-m^{2} y=0$.

**Hence, $y=e^{m \sin ^{-1} x}$ is a solution of the differential equation**

$$
\left(1-x^{2}\right) \frac{d^{2} y}{d x^{2}}-x \frac{d y}{d x}-m^{2} y=0
$$

---

### Example 6

Verify that $v=\frac{A}{r}+B$ is a solution of the differential equation

$$
\frac{d^{2} v}{d r^{2}}+\frac{2}{r} \cdot \frac{d v}{d r}=0
$$

#### Solution:

Since the given relation contains two arbitrary constants, we differentiate it two times w.r.t. $r$, and eliminate $A$ and $B$.

$$
\begin{align*}
v=\frac{A}{r}+B & \Rightarrow \frac{d v}{d r}=\frac{-A}{r^{2}} \tag{i}\\
& \Rightarrow \frac{d^{2} v}{d r^{2}}=\frac{2 A}{r^{3}} \tag{ii}
\end{align*}
$$

On dividing (ii) by (i), we get

$$
\begin{aligned}
& \frac{\left(d^{2} v / d r^{2}\right)}{(d v / d r)}=\left\{\frac{2 A}{r^{3}} \times \frac{r^{2}}{(-A)}\right\}=\frac{-2}{r} \\
\Rightarrow & \frac{d^{2} v}{d r^{2}}=\frac{-2}{r} \cdot \frac{d v}{d r} \\
\Rightarrow & \frac{d^{2} v}{d r^{2}}+\frac{2}{r} \cdot \frac{d v}{d r}=0
\end{aligned}
$$

**Hence, $v=\frac{A}{r}+B$ is a solution of the differential equation**

$$
\frac{d^{2} v}{d r^{2}}+\frac{2}{r} \cdot \frac{d v}{d r}=0
$$

---

### Example 7

Prove that $\left(x^{2}-y^{2}\right)=c\left(x^{2}+y^{2}\right)^{2}$ is the general solution of the differential equation $\left(x^{3}-3 x y^{2}\right) d x=\left(y^{3}-3 x^{2} y\right) d y$, where $c$ is a parameter.

#### Solution:

We have

$$
\begin{equation*}
\left(x^{2}-y^{2}\right)=c\left(x^{2}+y^{2}\right)^{2} . \tag{i}
\end{equation*}
$$

On differentiating (i) w.r.t. $x$, we get

$$
\begin{align*}
& 2 x-2 y \frac{d y}{d x}=2 c\left(x^{2}+y^{2}\right)\left(2 x+2 y \frac{d y}{d x}\right) \\
\Rightarrow & \left(x-y \frac{d y}{d x}\right)=2 c\left(x^{2}+y^{2}\right)\left(x+y \frac{d y}{d x}\right) \tag{ii}\\
\Rightarrow & \left(x-y \frac{d y}{d x}\right)=\frac{2\left(x^{2}-y^{2}\right)}{\left(x^{2}+y^{2}\right)^{2}}\left(x^{2}+y^{2}\right)\left(x+y \frac{d y}{d x}\right)
\end{align*}
$$

[putting the value of $c$ from (i) in (ii)]
$\Rightarrow \quad\left(x^{2}+y^{2}\right)\left(x-y \frac{d y}{d x}\right)=2\left(x^{2}-y^{2}\right)\left(x+y \frac{d y}{d x}\right)$
$\Rightarrow\left\{x\left(x^{2}+y^{2}\right)-2 x\left(x^{2}-y^{2}\right)\right\}=\left\{2 y\left(x^{2}-y^{2}\right)+y\left(x^{2}+y^{2}\right)\right\} \frac{d y}{d x}$
$\Rightarrow \quad\left(3 x y^{2}-x^{3}\right)=\left(3 x^{2} y-y^{3}\right) \frac{d y}{d x}$
$\Rightarrow \quad\left(x^{3}-3 x y^{2}\right) d x=\left(y^{3}-3 x^{2} y\right) d y$,
which is the required differential equation.

---

### Example 8

Prove that $x y=a e^{x}+b e^{-x}+x^{2}$ is the general solution of the differential equation $x \frac{d^{2} y}{d x^{2}}+2 \frac{d y}{d x}-x y+x^{2}-2=0$.

#### Solution:

We have

$$
\begin{equation*}
x y=a e^{x}+b e^{-x}+x^{2} \tag{i}
\end{equation*}
$$

On differentiating (i) w.r.t. $x$, we get

$$
\begin{equation*}
x \frac{d y}{d x}+y=a e^{x}-b e^{-x}+2 x \tag{ii}
\end{equation*}
$$

On differentiating (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& x \frac{d^{2} y}{d x^{2}}+2 \frac{d y}{d x}=a e^{x}+b e^{-x}+2 \\
\Rightarrow & x \frac{d^{2} y}{d x^{2}}+2 \frac{d y}{d x}=x y-x^{2}+2 \quad\left[\because \text { from }(\mathrm{i}),\left(a e^{x}+b e^{-x}\right)=\left(x y-x^{2}\right)\right] \\
\Rightarrow & x \frac{d^{2} y}{d x^{2}}+2 \frac{d y}{d x}-x y+x^{2}-2=0,
\end{aligned}
$$

which is the required differential equation.

---

### Example 9

Verify that $y=A e^{a x} \cos b x+B e^{a x} \sin b x$, where $A$ and $B$ are arbitrary constants, is the general solution of the differential equation $\frac{d^{2} y}{d x^{2}}-2 a \frac{d y}{d x}+\left(a^{2}+b^{2}\right) y=0$.

#### Solution:

We have

$$
\begin{equation*}
y=A e^{a x} \cos b x+B e^{a x} \sin b x \tag{i}
\end{equation*}
$$

Differentiating (i) on both sides w.r.t. $x$, we get

$$
\begin{align*}
& \frac{d y}{d x}=A \cdot\left\{e^{a x}(-b \sin b x)+a e^{a x} \cos b x\right\}+B \cdot\left\{e^{a x}(b \cos b x)+a e^{a x} \sin b x\right\} \\
& \Rightarrow \frac{d y}{d x}=a\left\{A e^{a x} \cos b x+B e^{a x} \sin b x\right\}+b\left\{-A e^{a x} \sin b x+B e^{a x} \cos b x\right\} \\
& \Rightarrow \frac{d y}{d x}=a y+b e^{a x}\{B \cos b x-A \sin b x\} \quad \text { _ (ii) [using (i)] } \tag{ii}
\end{align*}
$$

Differentiating (ii) on both sides w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{d^{2} y}{d x^{2}}=a \frac{d y}{d x}+b\left[e^{a x}(-b B \sin b x-b A \cos b x)\right. \\
\Rightarrow & \frac{d^{2} y}{d x^{2}}=a \frac{d y}{d x}-b^{2}\left\{A e^{a x} \cos b x+B e^{a x} \sin b x\right\} \\
\Rightarrow & \frac{d^{2} y}{d x^{2}}=a \frac{d y}{d x}-b^{2} y+a\left(\frac{d y}{d x}-a y\right) \quad[\text { using (i) and (ii) }] \\
\Rightarrow & \frac{d^{2} y}{d x^{2}}-2 a \frac{d y}{d x}+\left(a^{2}+b^{2}\right) y=0,
\end{aligned}
$$

which is the required differential equation.

---