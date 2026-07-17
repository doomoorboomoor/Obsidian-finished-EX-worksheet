## Formation of a Differential Equation whose General Solution is Given

**METHOD** Suppose an equation of a family of curves contains $n$ arbitrary constants (called parameters).

Then, we obtain its differential equation as given below.
1.  Differentiate the equation of the given family of curves $n$ times to get $n$ more equations.
2.  Eliminate $n$ constants, using these ($n+1$) equations.

This gives us the required differential equation of order $n$.

---

## SOLVED EXAMPLES

---

### Example 1
Write the differential equation representing the family of curves $y=m x$, where $m$ is an arbitrary constant.
[CBSE 2013]

#### Solution

The equation of the given family of curves is

$$
y=m x \quad \ldots(\mathrm{i}), \text { where } m \text { is a constant. }
$$

Since the given equation contains one arbitrary constant, we differentiate it once only.
On differentiating (i) w.r.t. $x$, we get

$$
\begin{equation*}
\frac{d y}{d x}=m . \tag{ii}
\end{equation*}
$$

Putting this value of $m$ from (ii) in (i), we get

$$
y=\left(\frac{d y}{d x}\right) x \Rightarrow x\left(\frac{d y}{d x}\right)-y=0
$$

Hence, $x\left(\frac{d y}{d x}\right)-y=0$ is the required differential equation.

---

### Example 2
Find the differential equation of the family of curves $y=A e^{x}+B e^{-x}$, where $A$ and $B$ are arbitrary constants.

#### Solution

The equation of the given family of curves is

$$
\begin{equation*}
y=A e^{x}+B e^{-x} \tag{i}
\end{equation*}
$$

Since the given equation contains two arbitrary constants, we differentiate it two times w.r.t. $x$.
Now, $\frac{d y}{d x}=A e^{x}-B e^{-x}$
$\Rightarrow \frac{d^{2} y}{d x^{2}}=A e^{x}+B e^{-x}$
$\Rightarrow \frac{d^{2} y}{d x^{2}}=y \Rightarrow \frac{d^{2} y}{d x^{2}}-y=0$.
Hence, $\frac{d^{2} y}{d x^{2}}-y=0$ is the required differential equation.

---

### Example 3
Find the differential equation of the family of curves $y=e^{x}(A \cos x+B \sin x)$, where $A$ and $B$ are arbitrary constants.

#### Solution

The equation of the given family of curves is

$$
\begin{equation*}
y=e^{x}(A \cos x+B \sin x) \tag{i}
\end{equation*}
$$

Since the given equation contains two arbitrary constants, we differentiate it two times w.r.t. $x$.
Now, $\frac{d y}{d x}=e^{x}(-A \sin x+B \cos x)+e^{x}(A \cos x+B \sin x)$

$$
\begin{equation*}
\Rightarrow \frac{d y}{d x}-y=e^{x}(-A \sin x+B \cos x) \tag{ii}
\end{equation*}
$$

$\Rightarrow \frac{d^{2} y}{d x^{2}}-\frac{d y}{d x}=e^{x}(-A \cos x-B \sin x)+e^{x}(-A \sin x+B \cos x)$
$\Rightarrow \frac{d^{2} y}{d x^{2}}-\frac{d y}{d x}=-y+\left(\frac{d y}{d x}-y\right) \quad$ [using (i) and (ii)]
$\Rightarrow \frac{d^{2} y}{d x^{2}}-2 \frac{d y}{d x}+2 y=0$, which is the required differential equation of the given family of curves.

---

### Example 4
Find the differential equation of the family of all straight lines.

#### Solution

The general equation of the family of all straight lines is given by
$y=m x+c$, where $m$ and $c$ are parameters.

$$
\text { Now, } \begin{aligned}
y=m x+c & \Rightarrow \frac{d y}{d x}=m \\
& \Rightarrow \frac{d^{2} y}{d x^{2}}=0
\end{aligned}
$$

So, the required differential equation is

$$
\frac{d^{2} y}{d x^{2}}=0
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Equations/Differential-Equations-and-Their-Formation/class-12-Ch-18-C-BooK-001.jpg)

---

### Example 5
Form the differential equation of the family of all circles of radius $r$.
[CBSE 2010]

#### Solution

The equation of the family of all circles of radius $r$ is

$$
\begin{equation*}
(x-a)^{2}+(y-b)^{2}=r^{2} \tag{i}
\end{equation*}
$$

where $a$ and $b$ are arbitrary constants.
Differentiating (i) w.r.t. $x$, we get

$$
\begin{align*}
& 2(x-a)+2(y-b) y_{1}=0 \\
\Rightarrow \quad & (x-a)+(y-b) y_{1}=0 \tag{ii}
\end{align*}
$$

On differentiating (ii) again w.r.t. $x$, we get

$$
\begin{align*}
& 1+(y-b) y_{2}+\left(y_{1}\right)^{2}=0 \\
\Rightarrow \quad & (y-b)=-\frac{\left\{1+\left(y_{1}\right)^{2}\right\}}{y_{2}} . \tag{iii}
\end{align*}
$$

Putting the value of $(y-b)$ from (iii) in (ii), we get

$$
\begin{equation*}
(x-a)-\frac{\left\{1+\left(y_{1}\right)^{2}\right\} y_{1}}{y_{2}}=0 \Rightarrow(x-a)=\frac{\left\{1+\left(y_{1}\right)^{2}\right\} y_{1}}{y_{2}} . \tag{iv}
\end{equation*}
$$

Putting the values of $(y-b)$ and $(x-a)$ from (iii) and (iv) in (i), we get

$$
\begin{aligned}
& \frac{\left\{1+\left(y_{1}\right)^{2}\right\}^{2} \times\left(y_{1}\right)^{2}}{\left(y_{2}\right)^{2}}+\frac{\left\{1+\left(y_{1}\right)^{2}\right\}^{2}}{\left(y_{2}\right)^{2}}=r^{2} \\
\Rightarrow & \frac{\left\{1+\left(y_{1}\right)^{2}\right\}^{2} \cdot\left\{\left(y_{1}\right)^{2}+1\right\}}{\left(y_{2}\right)^{2}}=r^{2} \\
\Rightarrow & \left\{1+\left(y_{1}\right)^{2}\right\}^{3}=r^{2}\left(y_{2}\right)^{2},
\end{aligned}
$$

which is the required differential equation.

---

### Example 6
Form the differential equation of the family of all circles in first quadrant and touching the coordinate axes.
[CBSE 2010]

#### Solution

The general equation of a circle in first quadrant and touching the coordinate axes is given by

$$
(x-a)^{2}+(y-a)^{2}=a^{2} \quad \ldots(\mathrm{i}), \text { where } a \text { is a parameter. }
$$

Since this equation contains one parameter, so we will differentiate it only once to get the differential equation. On differentiating (i) w.r.t, $x$, we get

$$
\begin{align*}
& 2(x-a)+2(y-a) \frac{d y}{d x}=0 \\
\Rightarrow & (x-a)+(y-a) \frac{d y}{d x}=0 \\
\Rightarrow & (x-a)+(y-a) p=0, \text { where } \frac{d y}{d x}=p \\
\Rightarrow & x+y p=a(1+p) \Rightarrow a=\frac{(x+y p)}{(1+p)} \tag{ii}
\end{align*}
$$

Putting the value of $a$ from (ii) in (i), we get

$$
\begin{aligned}
& \left(x-\frac{x+y p}{1+p}\right)^{2}+\left(y-\frac{x+y p}{1+p}\right)^{2}=\left(\frac{x+y p}{1+p}\right)^{2} \\
& \Rightarrow \quad(x p-y p)^{2}+(y-x)^{2}=(x+y p)^{2} \\
& \Rightarrow \quad(x-y)^{2} p^{2}+(x-y)^{2}=(x+y p)^{2} \\
& \Rightarrow \quad(x-y)^{2}\left(p^{2}+1\right)=(x+y p)^{2} \\
& \Rightarrow \quad(x-y)^{2}\left\{\left(\frac{d y}{d x}\right)^{2}+1\right\}=\left(x+y \frac{d y}{d x}\right)^{2}
\end{aligned}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Equations/Differential-Equations-and-Their-Formation/class-12-Ch-18-C-BooK-002.jpg)

which is the required differential equation.

---

### Example 7
Form the differential equation of the family of all circles touching the $x$-axis at the origin.
[CBSE 2005, '08, '10C]

#### Solution

The general equation of a circle touching the $x$-axis at the origin, is given by

$$
\begin{align*}
& (x-0)^{2}+(y-a)^{2}=a^{2}, \text { where } a \text { is a parameter } \\
\Rightarrow \quad & x^{2}+y^{2}-2 a y=0 . \tag{i}
\end{align*}
$$

Since this equation contains one parameter, so we shall differentiate it only once to get the differential equation.
On differentiating (i) w.r.t. $x$, we get

$$
\begin{aligned}
& 2 x+2 y \frac{d y}{d x}-2 a \frac{d y}{d x}=0 \\
\Rightarrow & x+y \frac{d y}{d x}=a \frac{d y}{d x} \\
\Rightarrow & x+y p=a p \Rightarrow a=\frac{x+y p}{p} \quad \ldots \text { (ii), where } \frac{d y}{d x}=p
\end{aligned}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Equations/Differential-Equations-and-Their-Formation/class-12-Ch-18-C-BooK-003.jpg)

Putting the value of $a$ from (ii) in (i), we get

$$
\begin{aligned}
& x^{2}+y^{2}=\frac{2(x+y p) \cdot y}{p} \\
\Rightarrow & x^{2}+y^{2}=\frac{2 x y}{p}+2 y^{2} \\
\Rightarrow & x^{2}-y^{2}=\frac{2 x y}{p} \\
\Rightarrow & \left(x^{2}-y^{2}\right) p=2 x y .
\end{aligned}
$$

Hence, $\left(x^{2}-y^{2}\right) \frac{d y}{d x}=2 x y$ is the required differential equation.

---

### Example 8
Form the differential equation of the family of all parabolas having vertex at the origin and axis along the positive direction of the $x$-axis.

#### Solution

The general equation of a parabola having vertex at the origin and axis along the positive direction of the $x$-axis is given by $y^{2}=4 a x \quad \ldots$ (i), where $a$ is the parameter.
Since this equation contains one parameter, so we shall differentiate it only once to get the requisite differential equation.
Differentiating (i) w.r.t. $x$, we get

$$
\begin{align*}
2 y \frac{d y}{d x}=4 a & \Rightarrow y \frac{d y}{d x}=2 a \\
& \Rightarrow a=\frac{1}{2} y \frac{d y}{d x} \tag{ii}
\end{align*}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Equations/Differential-Equations-and-Their-Formation/class-12-Ch-18-C-BooK-004.jpg)

Putting the value of $a$ from (ii) in (i), we get

$$
y^{2}=4 \times \frac{1}{2} y \frac{d y}{d x} \times x \Rightarrow y^{2}-2 x y \frac{d y}{d x}=0 .
$$

Hence, $y^{2}-2 x y \frac{d y}{d x}=0$ is the required differential equation.

---

### Example 9
Form the differential equation of the family of all ellipses having foci on the $x$-axis and centre at the origin.
[CBSE 2009C]

#### Solution

The general equation of an ellipse having foci on the $x$-axis and centre at the origin, is given by
$\frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 \quad \ldots$ (i), where $a$ and $b$ are the parameters.
Since this equation contains two parameters, so we shall differentiate it twice to get the required differential equation.
Differentiating (i) w.r.t. $x$, we get:

$$
\frac{2 x}{a^{2}}+\frac{2 y}{b^{2}} \cdot \frac{d y}{d x}=0 \Rightarrow \frac{y}{b^{2}} \cdot \frac{d y}{d x}+\frac{x}{a^{2}}=0
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Equations/Differential-Equations-and-Their-Formation/class-12-Ch-18-C-BooK-005.jpg)

$$
\begin{align*}
& \Rightarrow \frac{y y_{1}}{b^{2}}=\frac{-x}{a^{2}}, \text { where } \frac{d y}{d x}=y_{1} \\
& \Rightarrow \frac{y y_{1}}{x}=\frac{-b^{2}}{a^{2}} . \tag{ii}
\end{align*}
$$

Differentiating (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& \frac{x \cdot \frac{d}{d x}\left(y y_{1}\right)-y y_{1} \cdot \frac{d}{d x}(x)}{x^{2}}=0 \\
\Rightarrow & x\left[y y_{2}+\left(y_{1}\right)^{2}\right]-y y_{1}=0 \\
\Rightarrow & (x y) y_{2}+x\left(y_{1}\right)^{2}-y y_{1}=0 .
\end{aligned}
$$

Hence, $(x y) \frac{d^{2} y}{d x^{2}}+x\left(\frac{d y}{d x}\right)^{2}-y\left(\frac{d y}{d x}\right)=0$ is the required differential equation.

---

### Example 10
Form the differential equation for the family of the curves $(y-b)^{2}=4(x-a)$, where $a$ and $b$ are parameters.

#### Solution

The general equation of the given family of curves is

$$
(y-b)^{2}=4(x-a) \quad \ldots(\mathrm{i}), \text { where } a \text { and } b \text { are parameters. }
$$

Since the given equation contains two parameters $a$ and $b$, so we shall differentiate it twice to get the required differential equation. Differentiating (i) w.r.t. $x$, we get

$$
2(y-b) \frac{d y}{d x}=4 \Rightarrow(y-b) y_{1}=2 \quad \ldots(\mathrm{ii}), \text { where } \frac{d y}{d x}=y_{1}
$$

Differentiating (ii) w.r.t. $x$, we get

$$
(y-b) y_{2}+\left(y_{1}\right)^{2}=0 \quad \ldots \text { (iii), where } \frac{d^{2} y}{d x^{2}}=y_{2} \text {. }
$$

Putting $(y-b)=\frac{2}{y_{1}}$ from (ii) in (iii), we get

$$
\frac{2 y_{2}}{y_{1}}+\left(y_{1}\right)^{2}=0 \Rightarrow 2 y_{2}+\left(y_{1}\right)^{3}=0
$$

Hence, $2 \frac{d^{2} y}{d x^{2}}+\left(\frac{d y}{d x}\right)^{3}=0$ is the required differential equation.

---

### Example 11
Form the differential equation for the family of the curves $a y^{2}=(x-c)^{3}$, where $c$ is a parameter.

#### Solution

The general equation of the given family of curves is

$$
\begin{equation*}
a y^{2}=(x-c)^{3}, \quad \text { where } c \text { is a parameter. } \tag{i}
\end{equation*}
$$

Since the given equation has only one parameter, so we shall differentiate it only once to get the required differential equation.
Differentiating (i) w.r.t. $x$, we get

$$
\begin{equation*}
2 a y y_{1}=3(x-c)^{2} . \tag{ii}
\end{equation*}
$$

On dividing (i) and (ii) on each side, we get

$$
\begin{equation*}
\frac{a y^{2}}{2 a y y_{1}}=\frac{(x-c)^{3}}{3(x-c)^{2}} \Rightarrow \frac{y}{2 y_{1}}=\frac{(x-c)}{3} \Rightarrow(x-c)=\frac{3 y}{2 y_{1}} . \tag{iii}
\end{equation*}
$$

Putting the value of $(x-c)$ from (iii) in (i), we get

$$
a y^{2}=\left(\frac{3 y}{2 y_{1}}\right)^{3} \Rightarrow 8 a y_{1}^{3}=27 y .
$$

Hence, $8 a\left(\frac{d y}{d x}\right)^{3}-27 y=0$ is the required differential equation.

---

### Example 12
Form the differential equation for the family of the curves $y^{2}=a\left(b^{2}-x^{2}\right)$, where $a$ and $b$ are arbitrary constants.

#### Solution

The general equation of the given family of curves is

$$
y^{2}=a\left(b^{2}-x^{2}\right) \quad \ldots(\mathrm{i}), \text { where } a \text { and } b \text { are the parameters. }
$$

Since the given equation has two parameters, so we shall have to differentiate it two times to get the required differential equations.
Differentiating (i) w.r.t. $x$ we get

$$
\begin{equation*}
2 y y_{1}=-2 a x \Rightarrow y y_{1}=-a x . \tag{ii}
\end{equation*}
$$

On differentiating (ii) w.r.t. $x$, we get

$$
\begin{aligned}
& y y_{2}-\left(y_{1}\right)^{2}=-a \\
\Rightarrow \quad & y y_{2}-\left(y_{1}\right)^{2}=\frac{y y_{1}}{x} \quad \text { [using (ii)] } \\
\Rightarrow \quad & (x y) y_{2}-x\left(y_{1}\right)^{2}-y y_{1}=0
\end{aligned}
$$

Hence, $(x y) \frac{d^{2} y}{d x^{2}}-x\left(\frac{d y}{d x}\right)^{2}-y\left(\frac{d y}{d x}\right)=0$ is the required differential equation.

---