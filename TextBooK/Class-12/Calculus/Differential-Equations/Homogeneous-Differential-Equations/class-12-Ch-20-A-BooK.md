## 20. HOMOGENEOUS DIFFERENTIAL EQUATIONS

**Homogeneous Function:** A function $f(x, y)$ in $x$ and $y$ is said to be a **homogeneous function of degree $n$**, if the degree of each term is $n$.

**Examples:**
- (i) $f(x, y)=\left(x^{2}+y^{2}-x y\right)$ is a homogeneous function of degree 2.
- (ii) $g(x, y)=\left(x^{3}-3 x y^{2}+3 x^{2} y+y^{3}\right)$ is a homogeneous function of degree 3.

In general, a homogeneous function $f(x, y)$ of degree $n$ is expressible as

$$
f(x, y)=x^{n} f\left(\frac{y}{x}\right)
$$

**HOMOGENEOUS DIFFERENTIAL EQUATION:** An equation of the form $\frac{d y}{d x}=\frac{f(x, y)}{g(x, y)}$, where both $f(x, y)$ and $g(x, y)$ are homogeneous functions of degree $n$, is called a **homogeneous differential equation** of order 1 and degree 1.

Such a differential equation may be expressed in the form $\frac{d y}{d x}=f\left(\frac{y}{x}\right)$.
For example, $\frac{d y}{d x}=\frac{x^{2}-y^{2}}{x y}=\frac{f(x, y)}{g(x, y)}$, where $f(x, y)$ and $g(x, y)$ are homogeneous functions of degree 2 each. So, it is a homogeneous differential equation of order 1 and degree 1.

We may write, $\frac{d y}{d x}=\frac{x^{2}-y^{2}}{x y}=\frac{\left\{1-\left(\frac{y}{x}\right)^{2}\right\}}{\left\{\frac{y}{x}\right\}}$ [on dividing Nr and Dr by $x^{2}$ ]
Thus, $\frac{d y}{d x}=f\left(\frac{y}{x}\right)$.

---

## Method of Solving a Homogeneous Differential Equation

Let $\frac{d y}{d x}=\frac{f(x, y)}{g(x, y)}$ be a homogeneous differential equation of order 1 and degree 1.
Putting $y=v x$ and $\frac{d y}{d x}=\left(v+x \frac{d v}{d x}\right)$ in the given equation, we get

$$
v+x \frac{d v}{d x}=F(v)
$$

$\Rightarrow \frac{d v}{[F(v)-v]}=\frac{d x}{x}$
$\Rightarrow \quad \int \frac{d v}{[F(v)-v)]}=\int \frac{d x}{x}$
$\Rightarrow \int \frac{d v}{[F(v)-v]}=\log |x|+C$.

Now, replace $v$ by ($y / x$) to obtain the required solution.

> **NOTE:** If the differential equation is of the form $\frac{d x}{d y}=f\left(\frac{x}{y}\right)$ then we put $x=v y$ and proceed in a manner similar to as above.

---

## SOLVED EXAMPLES

### Example 1: Show that the differential equation $2 x^{2} \frac{d y}{d x}-2 x y+y^{2}=0$ is homogeneous and solve it. [CBSE 2012]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{2 x y-y^{2}}{2 x^{2}} . \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $2 x^{2}$, we get

$$
\frac{d y}{d x}=\left\{\frac{y}{x}-\frac{1}{2}\left(\frac{y}{x}\right)^{2}\right\}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{align*}
& v+x \frac{d v}{d x}=\frac{2 v x^{2}-v^{2} x^{2}}{2 x^{2}} \\
\Rightarrow & v+x \frac{d v}{d x}=\left(v-\frac{1}{2} v^{2}\right) \\
\Rightarrow & x \frac{d v}{d x}=-\frac{1}{2} v^{2} \Rightarrow \frac{d v}{v^{2}}+\frac{1}{2} \frac{d x}{x}=0 . \tag{ii}
\end{align*}
$$

On integrating (ii), we get
$\int \frac{d v}{v^{2}}+\frac{1}{2} \int \frac{1}{x} d x=C$, where $C$ is an arbitrary constant
$\Rightarrow \frac{-1}{v}+\frac{1}{2} \log |x|=C$
$\Rightarrow \quad \frac{-x}{y}+\frac{1}{2} \log |x|=C$, which is the required solution.

---

### Example 2: Show that the differential equation $\frac{d y}{d x}=\frac{y-x}{y+x}$ is homogeneous and solve it. [CBSE 2004]

#### Solution:

The given differential equation is

$$
\begin{equation*}
\frac{d y}{d x}=\frac{y-x}{y+x} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x$, we get

$$
\frac{d y}{d x}=\left\{\frac{\frac{y}{x}-1}{\frac{y}{x}+1}\right\}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{v x-x}{v x+x} \\
\Rightarrow & v+x \frac{d v}{d x}=\frac{v-1}{v+1} \\
\Rightarrow & x \frac{d v}{d x}=\left(\frac{v-1}{v+1}-v\right) \\
\Rightarrow & x \frac{d v}{d x}=\frac{-\left(1+v^{2}\right)}{(1+v)} \\
\Rightarrow & \frac{(1+v)}{\left(1+v^{2}\right)} d v=\frac{-1}{x} d x \\
\Rightarrow & \int \frac{(1+v)}{\left(1+v^{2}\right)} d v=-\int \frac{d x}{x} \\
\Rightarrow & \int \frac{1}{\left(1+v^{2}\right)} d v+\frac{1}{2} \int \frac{2 v}{\left(1+v^{2}\right)} d v=-\int \frac{d x}{x} \\
\Rightarrow & \tan ^{-1} v+\frac{1}{2} \log \left|1+v^{2}\right|=-\log |x|+C \\
\Rightarrow & \tan ^{-1} v+\log \left|x \sqrt{1+v^{2}}\right|=C \\
\Rightarrow & \tan ^{-1} \frac{y}{x}+\log \left|\sqrt{x^{2}+y^{2}}\right|=C \quad\left[\text { putting } v=\frac{y}{x}\right] \\
\Rightarrow & \tan ^{-1} \frac{y}{x}+\frac{1}{2} \log \left(x^{2}+y^{2}\right)=C, \text { which is the required solution. }
\end{aligned}
$$

---

### Example 3: Show that the differential equation $x \frac{d y}{d x}-y=\sqrt{x^{2}+y^{2}}$ is homogeneous and solve it. [CBSE 2005, '07, '11]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{y+\sqrt{x^{2}+y^{2}}}{x} . \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x$, we get

$$
\frac{d y}{d x}=\left\{\frac{y}{x}+\sqrt{1+\left(\frac{y}{x}\right)^{2}}\right\}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{v x+\sqrt{x^{2}+v^{2} x^{2}}}{x}=v+\sqrt{1+v^{2}} \\
\Rightarrow & x \frac{d v}{d x}=\sqrt{1+v^{2}} \\
\Rightarrow & \frac{d v}{\sqrt{1+v^{2}}}=\frac{1}{x} d x \\
\Rightarrow & \int \frac{d v}{\left(1+v^{2}\right)}=\int \frac{d x}{x} \\
\Rightarrow & \log \left|v+\sqrt{1+v^{2}}\right|=\log |x|+\log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$\Rightarrow \quad \log \left|\frac{v+\sqrt{1+v^{2}}}{x}\right|=\log \left|C_{1}\right|$
$\Rightarrow \frac{v+\sqrt{1+v^{2}}}{x}= \pm C_{1}=C$ (say)
$\Rightarrow v+\sqrt{1+v^{2}}=C x$
$\Rightarrow y+\sqrt{x^{2}+y^{2}}=C x^{2}$, which is the required solution $\left[\because v=\frac{y}{x}\right]$.

---

### Example 4: Show that the differential equation $\left(x \sqrt{x^{2}+y^{2}}-y^{2}\right) d x+x y d y=0$ is homogeneous and solve it.

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{y^{2}-x \sqrt{x^{2}+y^{2}}}{x y} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\left\{\frac{\left(\frac{y}{x}\right)^{2}-\sqrt{1+\left(\frac{y}{x}\right)^{2}}}{\left(\frac{y}{x}\right)}\right\}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{v^{2} x^{2}-x \sqrt{x^{2}+v^{2} x^{2}}}{v x^{2}} \\
\Rightarrow & x \frac{d v}{d x}=\left(\frac{v^{2}-\sqrt{1+v^{2}}}{v}-v\right) \\
\Rightarrow & x \frac{d v}{d x}=\frac{-\sqrt{1+v^{2}}}{v} \\
\Rightarrow & \int \frac{v}{\sqrt{1+v^{2}}} d v=-\int \frac{d x}{x} \\
\Rightarrow & \sqrt{1+v^{2}}=-\log |x|+C \\
\Rightarrow & \sqrt{x^{2}+y^{2}}+x \log |x|=C x, \text { which is the required solution. }
\end{aligned}
$$

---

### Example 5: Show that the differential equation $\left(x^{2}+x y\right) d y=\left(x^{2}+y^{2}\right) d x$ is homogeneous and solve it. [CBSE 2005]

#### Solution:

The given differential equation is

$$
\begin{equation*}
\frac{d y}{d x}=\frac{x^{2}+y^{2}}{x^{2}+x y} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\frac{\left\{1+\left(\frac{y}{x}\right)^{2}\right\}}{\left\{1+\frac{y}{x}\right\}}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{x^{2}+v^{2} x^{2}}{x^{2}+v x^{2}}=\frac{1+v^{2}}{1+v} \\
\Rightarrow & x \frac{d v}{d x}=\frac{\left(1+v^{2}\right)}{(1+v)}-v=\frac{1+v^{2}-v-v^{2}}{(1+v)}=\frac{(1-v)}{(1+v)} \\
\Rightarrow & \frac{(1+v)}{(1-v)} d v=\frac{1}{x} d x \\
\Rightarrow & \int \frac{(1+v)}{(1-v)} d v=\int \frac{1}{x} d x \quad[\text { on integrating both sides }] \\
\Rightarrow & \int \frac{\{2-(1-v)\}}{(1-v)} d v=\int \frac{1}{x} d x
\end{aligned}
$$

$\Rightarrow \int\left\{\frac{2}{(1-v)}-1\right\} d v=\int \frac{1}{x} d x$
$\Rightarrow \quad-2 \log |1-v|-v=\log |x|+\log |C|$, where $C$ is an arbitrary constant
$\Rightarrow \log |x|+\log |C|+2 \log |1-v|=-v$
$\Rightarrow \quad \log \left|C x(1-v)^{2}\right|=-v$
$\Rightarrow\left|C x(1-v)^{2}\right|=e^{-v}$
$\Rightarrow\left|C x\left(1-\frac{y}{x}\right)^{2}\right|=e^{-y / x} \quad\left[\because v=\frac{y}{x}\right]$
$\Rightarrow|C|(x-y)^{2}=|x| e^{-y / x}$, which is the required solution.

---

### Example 6: Show that the differential equation $y^{2} d x+\left(x^{2}-x y+y^{2}\right) d y=0$ is homogeneous and solve it.

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{-y^{2}}{\left(x^{2}-x y+y^{2}\right)} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\frac{-\left(\frac{y}{x}\right)^{2}}{\left\{1-\frac{y}{x}+\left(\frac{y}{x}\right)^{2}\right\}}=f\left(\frac{y}{x}\right)
$$

Thus, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{-v^{2}}{\left(1-v+v^{2}\right)} \\
\Rightarrow & x \frac{d v}{d x}=-\left[\frac{v^{2}}{\left(1-v+v^{2}\right)}+v\right] \\
\Rightarrow & x \frac{d v}{d x}=\frac{-\left(v+v^{3}\right)}{\left(1-v+v^{2}\right)} \\
\Rightarrow & \frac{\left(1-v+v^{2}\right)}{v\left(1+v^{2}\right)} d v=-\frac{1}{x} d x \\
\Rightarrow & \int \frac{\left(1+v^{2}\right)-v}{v\left(1+v^{2}\right)} d v=-\int \frac{d x}{x} \\
\Rightarrow & \int \frac{d v}{v}-\int \frac{d v}{\left(1+v^{2}\right)}+\int \frac{d x}{x}=\log C \\
\Rightarrow & \log |v|-\tan ^{-1} v+\log |x|=\log C \\
\Rightarrow & \tan ^{-1} v=\log \frac{|v x|}{C}
\end{aligned}
$$

$\Rightarrow \tan ^{-1} \frac{y}{x}=\log \left(\frac{|y|}{C}\right)\left[\because v=\frac{y}{x}\right]$
$\Rightarrow \quad \frac{|y|}{C}=e^{\tan ^{-1}(y / x)}$
$\Rightarrow \quad|y|=C e^{\tan ^{-1}(y / x)}$, which is the required solution.

---

### Example 7: Show that the differential equation $x^{2}\left(\frac{d y}{d x}\right)=\left(x^{2}-2 y^{2}+x y\right)$ is homogeneous and solve it.

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{\left(x^{2}-2 y^{2}+x y\right)}{x^{2}} . \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\left\{1-2\left(\frac{y}{x}\right)^{2}+\left(\frac{y}{x}\right)\right\}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{x^{2}-2 v^{2} x^{2}+v x^{2}}{x^{2}} \\
\Rightarrow & v+x \frac{d v}{d x}=1-2 v^{2}+v \\
\Rightarrow & x \frac{d v}{d x}=1-2 v^{2} \\
\Rightarrow & \frac{d v}{\left(1-2 v^{2}\right)}=\frac{d x}{x} \\
\Rightarrow & \int \frac{d v}{\left(1-2 v^{2}\right)}=\int \frac{d x}{x} \\
\Rightarrow & \frac{1}{2} \int \frac{d v}{\left(\frac{1}{2}-v^{2}\right)}=\int \frac{d x}{x} \\
\Rightarrow & \frac{1}{2} \int \frac{d v}{\left\{\left(\frac{1}{\sqrt{2}}\right)^{2}-v^{2}\right\}}=\int \frac{d x}{x} \\
\Rightarrow & \frac{1}{2} \cdot \frac{1}{\left(2 \times \frac{1}{\sqrt{2}}\right)} \log \left|\frac{\frac{1}{\sqrt{2}}+v}{\frac{1}{\sqrt{2}}-v}\right|=\log |x|+C \\
\Rightarrow & \frac{1}{2 \sqrt{2}} \log \left|\frac{x+\sqrt{2} y}{x-\sqrt{2} y}\right|-\log |x|=C \quad\left[\because v=\frac{y}{x}\right] .
\end{aligned}
$$

This is the required solution.

---

### Example 8: Show that the differential equation $\left(x^{3}+y^{3}\right) d y-x^{2} y d x=0$ is homogeneous and solve it. [CBSE 2008]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{x^{2} y}{\left(x^{3}+y^{3}\right)} . \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{3}$, we get

$$
\frac{d y}{d x}=\frac{\left(\frac{y}{x}\right)}{\left\{1+\left(\frac{y}{x}\right)^{3}\right\}}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{v x^{3}}{x^{3}+v^{3} x^{3}} \\
\Rightarrow & v+x \frac{d v}{d x}=\frac{v}{1+v^{3}} \\
\Rightarrow & x \frac{d v}{d x}=\left(\frac{v}{1+v^{3}}-v\right)=\frac{-v^{4}}{\left(1+v^{3}\right)} \\
\Rightarrow & \frac{\left(1+v^{3}\right)}{v^{4}} d v=\frac{-1}{x} d x \\
\Rightarrow & \int\left(\frac{1}{v^{4}}+\frac{1}{v}\right) d v=-\int \frac{1}{x} d x \\
\Rightarrow & \int\left(\frac{1}{v^{4}}+\frac{1}{v}\right) d v+\int \frac{1}{x} d x=C \\
\Rightarrow & \frac{-1}{3 v^{3}}+\log |v|+\log |x|=C \\
\Rightarrow & \frac{-1}{3 v^{3}}+\log |v x|=C \\
\Rightarrow & \frac{-x^{3}}{3 y^{3}}+\log |y|=C, \text { which is the required solution. }
\endaligned}
$$

---

### Example 9: Show that the differential equation $\left(y^{2}-x^{2}\right) d y=3 x y d x$ is homogeneous and solve it. [CBSE 2006,'08]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{3 x y}{\left(y^{2}-x^{2}\right)} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\frac{3\left(\frac{y}{x}\right)}{\left\{\left(\frac{y}{x}\right)^{2}-1\right\}}=f\left(\frac{y}{x}\right)
$$

Thus, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
v+x \frac{d v}{d x}=\frac{3 v}{\left(v^{2}-1\right)}
$$

$\Rightarrow x \frac{d v}{d x}=\left\{\frac{3 v}{\left(v^{2}-1\right)}-v\right\}=\frac{\left(4 v-v^{3}\right)}{\left(v^{2}-1\right)}$

$$
\begin{equation*}
\Rightarrow \frac{\left(v^{2}-1\right)}{\left(4 v-v^{3}\right)} d v=\frac{1}{x} d x \tag{ii}
\end{equation*}
$$

$\Rightarrow \int \frac{\left(v^{2}-1\right)}{v(2-v)(2+v)} d v=\int \frac{1}{x} d x$.

Let $\frac{\left(v^{2}-1\right)}{v(2-v)(2+v)}=\frac{A}{v}+\frac{B}{(2-v)}+\frac{C}{(2+v)}$.
Then, $\left(v^{2}-1\right) \equiv A(2-v)(2+v)+B v(2+v)+C v(2-v)$.

Putting $v=0$ on each side of (iii), we get $A=\frac{-1}{4}$.
Putting $v=2$ on each side of (iii), we get $B=\frac{3}{8}$.
Putting $v=-2$ on each side of (iii), we get $C=\frac{-3}{8}$.
$\therefore \frac{\left(v^{2}-1\right)}{v(2-v)(2+v)}=\frac{-1}{4 v}+\frac{3}{8(2-v)}-\frac{3}{8(2+v)}$.

Putting these values from (iv) in (ii), we get

$$
\begin{aligned}
& -\frac{1}{4} \int \frac{d v}{v}+\frac{3}{8} \int \frac{d v}{(2-v)}-\frac{3}{8} \int \frac{d v}{(2+v)}=\int \frac{1}{x} d x \\
\Rightarrow & \int \frac{1}{x} d x+\frac{1}{4} \int \frac{d v}{v}+\frac{3}{8} \int \frac{-d v}{(2-v)}+\frac{3}{8} \int \frac{d v}{(2+v)}=\log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$\Rightarrow \log |x|+\frac{1}{4} \log |v|+\frac{3}{8} \log |2-v|+\frac{3}{8} \log |2+v|=\log \left|C_{1}\right|$
$\Rightarrow 8 \log |x|+2 \log |v|+3 \log |2-v|+3 \log |2+v|=8 \log \left|C_{1}\right|$
$\Rightarrow \log \left|x^{8} v^{2}(2-v)^{3}(2+v)^{3}\right|=\log \left\{\left(C_{1}\right)^{8}\right\}$
$\Rightarrow\left|x^{8} v^{2}(2-v)^{3}(2+v)^{3}\right|=C_{1}^{8}=C$ (say)
$\Rightarrow \quad x^{8} \frac{y^{2}}{x^{2}}\left(2-\frac{y}{x}\right)^{3}\left(2+\frac{y}{x}\right)^{3}=C$
$\Rightarrow y^{2}(2 x-y)^{3}(2 x+y)^{3}=C$, where $C$ is an arbitrary constant.
$\Rightarrow y^{2}\left(4 x^{2}-y^{2}\right)^{3}=C$, which is the required solution.

---

### Example 10: Show that the differential equation $\left(x^{3}-3 x y^{2}\right) d x=\left(y^{3}-3 x^{2} y\right) d y$ is homogeneous and solve it.

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{x^{3}-3 x y^{2}}{y^{3}-3 x^{2} y} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{3}$, we get

$$
\frac{d y}{d x}=\frac{1-3\left(\frac{y}{x}\right)^{2}}{\left(\frac{y}{x}\right)^{3}-3\left(\frac{y}{x}\right)}=f\left(\frac{y}{x}\right)
$$

Thus, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{align*}
& v+x \frac{d v}{d x}=\frac{x^{3}-3 v^{2} x^{3}}{v^{3} x^{3}-3 v x^{3}} \\
\Rightarrow & v+x \frac{d v}{d x}=\frac{1-3 v^{2}}{v^{3}-3 v} \\
\Rightarrow & x \frac{d v}{d x}=\left(\frac{1-3 v^{2}}{v^{3}-3 v}-v\right) \\
\Rightarrow & x \frac{d v}{d x}=\frac{\left(1-v^{4}\right)}{\left(v^{3}-3 v\right)} \\
\Rightarrow & \frac{\left(3 v-v^{3}\right)}{\left(v^{4}-1\right)} d v=\frac{d x}{x} \\
\Rightarrow & \int \frac{\left(3 v-v^{3}\right)}{\left(v^{4}-1\right)} d v=\int \frac{d x}{x} \tag{ii}
\end{align*}
$$

Let $\frac{\left(3 v-v^{3}\right)}{\left(v^{4}-1\right)}=\frac{A}{(v-1)}+\frac{B}{(v+1)}+\frac{C v+D}{\left(v^{2}+1\right)}$. Then, $\left(3 v-v^{3}\right) \equiv A(v+1)\left(v^{2}+1\right)+B(v-1)\left(v^{2}+1\right)+(C v+D)(v-1)(v+1)$.

Putting $v=1$ on each side of (iii), we get $A=\frac{1}{2}$.
Putting $v=-1$ on each side of (iii), we get $B=\frac{1}{2}$.
Comparing coefficients of $v^{3}$ on both sides of (iii), we get

$$
A+B+C=-1 \Rightarrow \frac{1}{2}+\frac{1}{2}+C=-1 \Rightarrow C=-2 .
$$

Comparing the independent terms on both sides of (iii), we get

$$
\begin{aligned}
A-B-D & =0 \Rightarrow D=(A-B)=\left(\frac{1}{2}-\frac{1}{2}\right)=0 . \\
\therefore \quad & \frac{\left(3 v-v^{3}\right)}{\left(v^{4}-1\right)}=\frac{1}{2(v-1)}+\frac{1}{2(v+1)}-\frac{2 v}{\left(v^{2}+1\right)} .
\end{aligned}
$$

Putting this value in (ii), we get

$$
\begin{aligned}
& \frac{1}{2} \int \frac{d v}{(v-1)}+\frac{1}{2} \int \frac{d v}{(v+1)}-\int \frac{2 v}{\left(v^{2}+1\right)} d v=\int \frac{d x}{x} \\
\Rightarrow & \frac{1}{2} \log |v-1|+\frac{1}{2} \log |v+1|-\log \left|v^{2}+1\right|=\log |x|+\log |C|
\end{aligned}
$$

where $C$ is an arbitrary constant
$\Rightarrow \log |v-1|+\log |v+1|-2 \log \left|v^{2}+1\right|=2 \log |x|+2 \log |C|$
$\Rightarrow \log \left|\frac{(v-1)(v+1)}{\left(v^{2}+1\right)^{2}}\right|=\log \left|C^{2} x^{2}\right| \Rightarrow \log \left|\frac{\left(v^{2}-1\right)}{\left(v^{2}+1\right)^{2}}\right|=\log \left|C^{2} x^{2}\right|$
$\Rightarrow\left(y^{2}-x^{2}\right)=C^{2}\left(y^{2}+x^{2}\right)^{2} \quad\left[\because v=\frac{y}{x}\right]$.
Hence, $\left(y^{2}-x^{2}\right)=C^{2}\left(y^{2}+x^{2}\right)^{2}$ is the required solution.

---

### Example 11: Show that the differential equation $(x-y) \frac{d y}{d x}=(x+2 y)$ is homogeneous and solve it. [CBSE 2013C]

#### Solution:

The given differential equation can be expressed as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{x+2 y}{x-y} \tag{i}
\end{equation*}
$$

On dividing the $\operatorname{Nr}$ and $\operatorname{Dr}$ of (i) by $x$, we get

$$
\frac{d y}{d x}=\frac{\left\{1+2 \cdot \frac{y}{x}\right\}}{\left\{1-\frac{y}{x}\right\}}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{align*}
& v+x \frac{d v}{d x}=\frac{1+2 v}{1-v} \\
\Rightarrow & x \frac{d v}{d x}=\left\{\frac{1+2 v}{1-v}-v\right\}=\frac{(1+2 v)-v+v^{2}}{(1-v)}=\frac{v^{2}+v+1}{(1-v)} \\
\Rightarrow & \frac{(v-1)}{\left(v^{2}+v+1\right)} d v=-\frac{1}{x} d x \Rightarrow \int \frac{(v-1)}{\left(v^{2}+v+1\right)} d v=-\int \frac{1}{x} d x \tag{ii}
\end{align*}
$$

Let $(v-1)=A \cdot \frac{d}{d v}\left(v^{2}+v+1\right)+B$.

Then, $(v-1)=A(2 v+1)+B$.

Comparing coefficients of like powers of $v$, we get

$$
(2 A=1 \text { and } A+B=-1) \Rightarrow\left(A=\frac{1}{2} \text { and } B=\frac{-3}{2}\right) .
$$

Putting $(v-1)=\frac{1}{2}(2 v+1)-\frac{3}{2}$ in (ii), we get

$$
\begin{aligned}
& \int \frac{\frac{1}{2}(2 v+1)-\frac{3}{2}}{\left(v^{2}+v+1\right)} d v=-\log |x|+C \\
\Rightarrow & \frac{1}{2} \int \frac{(2 v+1)}{\left(v^{2}+v+1\right)} d v-\frac{3}{2} \int \frac{d v}{\left(v^{2}+v+1\right)}=-\log |x|+C \\
\Rightarrow & \frac{1}{2} \log \left|v^{2}+v+1\right|-\frac{3}{2} \int \frac{1}{\left(v+\frac{1}{2}\right)^{2}+\left(\frac{\sqrt{3}}{2}\right)^{2}} d v=-\log |x|+C \\
\Rightarrow & \frac{1}{2} \log \left|v^{2}+v+1\right|-\frac{3}{2} \cdot \frac{2}{\sqrt{3}} \tan ^{-1}\left(\frac{2 v+1}{\sqrt{3}}\right)=-\log |x|+C \\
\Rightarrow & \frac{1}{2} \log \left|v^{2}+v+1\right|+\frac{1}{2} \log x^{2}=\sqrt{3} \tan ^{-1}\left(\frac{2 v+1}{\sqrt{3}}\right)+C \\
\Rightarrow & \frac{1}{2} \log \left|\frac{y^{2}}{x^{2}}+\frac{y}{x}+1\right|+\frac{1}{2} \log x^{2}=\sqrt{3} \tan ^{-1}\left(\frac{2 y+x}{\sqrt{3} x}\right)+C \\
\Rightarrow & \frac{1}{2} \log \left\{\frac{\left|\left(y^{2}+x y+x^{2}\right)\right|}{x^{2}} \cdot x^{2}\right\}=\sqrt{3} \tan ^{-1}\left(\frac{2 y+x}{\sqrt{3} x}\right)+C \\
\Rightarrow & \log \left|x^{2}+x y+y^{2}\right|=2 \sqrt{3} \tan ^{-1}\left(\frac{x+2 y}{\sqrt{3} x}\right)+C,
\end{aligned}
$$

which is the required solution.

---

### Example 12: Show that the differential equation $x \frac{d y}{d x}=y-x \tan \frac{y}{x}$ is homogeneous and solve it. [CBSE 2006C,'09]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{y}{x}-\tan \frac{y}{x} . \tag{i}
\end{equation*}
$$

This is of the form, $\frac{d y}{d x}=f\left(\frac{y}{x}\right)$.
So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
v+x \frac{d v}{d x}=v-\tan v
$$

$\Rightarrow x \frac{d v}{d x}=-\tan v$
$\Rightarrow \frac{d v}{\tan v}=-\frac{d x}{x}$
$\Rightarrow \quad \int \cot v d v=-\int \frac{d x}{x}$
$\Rightarrow \quad \int \frac{\cos v}{\sin v} d v+\int \frac{1}{x} d x=\log \left|C_{1}\right|$, where $C_{1}$ is an arbitrary constant
$\Rightarrow \log |\sin v|+\log |x|=\log \left|C_{1}\right|$
$\Rightarrow \log |x \sin v|=\log \left|C_{1}\right|$
$\Rightarrow x \sin v= \pm C_{1}=C$ (say)
$\Rightarrow x \sin \frac{y}{x}=C$, which is the required solution.

---

### Example 13: Show that the differential equation
$$
\left(x \cos \frac{y}{x}\right)(y d x+x d y)=\left(y \sin \frac{y}{x}\right)(x d y-y d x)
$$
is homogeneous and solve it. [CBSE 2010, '13C]

#### Solution:

The given differential equation may be written as

$$
\begin{align*}
& \left(x y \cos \frac{y}{x}+y^{2} \sin \frac{y}{x}\right) d x=\left(x y \sin \frac{y}{x}-x^{2} \cos \frac{y}{x}\right) d y \\
\Rightarrow & \frac{d y}{d x}=\frac{\left\{x y \cos \frac{y}{x}+y^{2} \sin \frac{y}{x}\right\}}{\left\{x y \sin \frac{y}{x}-x^{2} \cos \frac{y}{x}\right\}} \\
\Rightarrow & \frac{d y}{d x}=\frac{(y / x) \cos (y / x)+(y / x)^{2} \sin (y / x)}{(y / x) \sin (y / x)-\cos (y / x)}=f\left(\frac{y}{x}\right) \tag{i}
\end{align*}
$$

[dividing Nr and $\operatorname{Dr}$ by $x^{2}$ ]
So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{\left(v \cos v+v^{2} \sin v\right)}{(v \sin v-\cos v)} \\
\Rightarrow & x \frac{d v}{d x}=\left\{\frac{\left(v \cos v+v^{2} \sin v\right)}{(v \sin v-\cos v)}-v\right\} \\
\Rightarrow & x \frac{d v}{d x}=\frac{2 v \cos v}{(v \sin v-\cos v)} \\
\Rightarrow & \int \frac{(v \sin v-\cos v)}{v \cos v} d v=\int \frac{2}{x} d x
\end{aligned}
$$

$\Rightarrow \quad \int \tan v d v-\int \frac{d v}{v}=\int \frac{2}{x} d x$
$\Rightarrow-\log |\cos v|-\log |v|-2 \log |x|=$ constant
$\Rightarrow \log |\cos v|+\log |v|+2 \log |x|=\log \left|C_{1}\right|$, where $C_{1}$ is an arbitrary constant
$\Rightarrow \quad \log \left|x^{2} v \cos v\right|=\log \left|C_{1}\right|$
$\Rightarrow \quad x^{2} v \cos v= \pm C_{1}=C$ (say)
$\Rightarrow \quad x y \cos \frac{y}{x}=C$, which is the required solution $\quad\left[\because v=\frac{y}{x}\right]$.

---

### Example 14: Show that the differential equation
$x y \log \left(\frac{y}{x}\right) d x+\left\{y^{2}-x^{2} \log \left(\frac{y}{x}\right)\right\} d y=0$ is homogeneous and solve it. [CBSE 2010C]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{x y \log \left(\frac{y}{x}\right)}{\left\{x^{2} \log \left(\frac{y}{x}\right)-y^{2}\right\}} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\frac{\left(\frac{y}{x}\right) \log \left(\frac{y}{x}\right)}{\left\{\log \left(\frac{y}{x}\right)-\left(\frac{y}{x}\right)^{2}\right\}}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{v x^{2} \log v}{x^{2}\left(\log v-v^{2}\right)}=\frac{v \log v}{\left(\log v-v^{2}\right)} \\
\Rightarrow & x \frac{d v}{d x}=\left\{\frac{v \log v}{\left(\log v-v^{2}\right)}-v\right\}=\frac{v^{3}}{\left(\log v-v^{2}\right)} \\
\Rightarrow & \frac{\left(\log v-v^{2}\right)}{v^{3}} d v=\frac{1}{x} d x \\
\Rightarrow & \int\left\{\frac{\log v}{v^{3}}-\frac{1}{v}\right\} d v=\int \frac{1}{x} d x \quad \text { [integrating both sides] } \\
\Rightarrow & \int(\log v) v_{\mathrm{II}}^{-3} d v-\int \frac{1}{v} d v=\int \frac{1}{x} d x+C_{1}
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$\Rightarrow \quad(\log v) \cdot\left(\frac{v^{-2}}{-2}\right)-\int \frac{1}{v} \cdot\left(\frac{v^{-2}}{-2}\right) d v-\log |v|=\log |x|+C_{1}$
[integrating by parts]
$\Rightarrow \frac{-\log v}{2 v^{2}}+\frac{1}{2} \int v^{-3} d v-\log |v|=\log |x|+C_{1}$
$\Rightarrow \frac{-\log v}{2 v^{2}}-\frac{1}{4 v^{2}}-\log |v|=\log |x|+C_{1}$
$\Rightarrow \frac{\log v}{2 v^{2}}+\frac{1}{4 v^{2}}+\log |v|+\log |x|=-C_{1}=C$ (say)
$\Rightarrow \frac{\log \left|\frac{y}{x}\right|}{2\left(\frac{y^{2}}{x^{2}}\right)}+\frac{x^{2}}{4 y^{2}}+\log |y|=C \quad\left[\because \quad v=\frac{y}{x}\right]$
$\Rightarrow \quad 2 x^{2} \log \left|\frac{y}{x}\right|+x^{2}+4 y^{2} \log |y|=4 C y^{2}$
$\Rightarrow \quad x^{2}\left(2 \log \left|\frac{y}{x}\right|+1\right)+4 y^{2} \log |y|=4 C y^{2}$,
which is the required solution.

---

### Example 15: Show that the differential equation $x \frac{d y}{d x} \sin \left(\frac{y}{x}\right)+x-y \sin \left(\frac{y}{x}\right)=0$ is homogeneous. Find the particular solution of this differential equation, given that $x=1$ when $y=\frac{\pi}{2}$. [CBSE 2013]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{(y / x) \sin (y / x)-1}{\sin (y / x)}=f\left(\frac{y}{x}\right) . \tag{i}
\end{equation*}
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
v+x \frac{d v}{d x}=\frac{v \sin v-1}{\sin v}
$$

$\Rightarrow \quad x \frac{d v}{d x}=\left\{\frac{v \sin v-1}{\sin v}-v\right\}=\frac{-1}{\sin v}$
$\Rightarrow \quad \sin v d v=\frac{-1}{x} d x$
$\Rightarrow \quad \int \sin v d v=-\int \frac{1}{x} d x \quad$ [on integrating both sides]
$\Rightarrow \quad-\cos v=-\log |x|+C$, where $C$ is an arbitrary constant
$\Rightarrow \log |x|-\cos \left(\frac{y}{x}\right)=C$
... (ii) $\left[\because v=\frac{y}{x}\right]$.
Putting $x=1$ and $y=\frac{\pi}{2}$ in (ii), we get $C=0$.

Hence, $\log |x|=\cos \left(\frac{y}{x}\right)$ is the required solution.

---

### Example 16: Find the particular solution of the differential equation $\left(3 x y+y^{2}\right) d x+\left(x^{2}+x y\right) d y=0$ for $x=1$ and $y=1$. [CBSE 2004C, '07, '13C]

#### Solution:

We may write the given differential equation as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{-\left(3 x y+y^{2}\right)}{\left(x^{2}+x y\right)} . \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\frac{-\left\{3\left(\frac{y}{x}\right)+\left(\frac{y}{x}\right)^{2}\right\}}{\left\{1+\frac{y}{x}\right\}}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{-\left(3 v x^{2}+v^{2} x^{2}\right)}{\left(x^{2}+v x^{2}\right)}=\frac{-\left(3 v+v^{2}\right)}{(v+1)} \\
\Rightarrow & x \frac{d v}{d x}=\left\{\frac{-\left(3 v+v^{2}\right)}{(v+1)}-v\right\}=\frac{-2\left(v^{2}+2 v\right)}{(v+1)} \\
\Rightarrow & \frac{(v+1)}{\left(v^{2}+2 v\right)} d v=\frac{-2}{x} d x \\
\Rightarrow & \frac{1}{2} \int \frac{2(v+1)}{\left(v^{2}+2 v\right)} d v+\int \frac{2}{x} d x=\log \left|C_{1}\right| \\
\Rightarrow & \frac{1}{2} \log \left|v^{2}+2 v\right|+2 \log |x|=\log \left|C_{1}\right| \\
\Rightarrow & \log \left|x^{2} \sqrt{v^{2}+2 v}\right|=\log \left|C_{1}\right| \\
\Rightarrow & \log \left|x \sqrt{y^{2}+2 x y}\right|=\log \left|C_{1}\right| \quad\left[\because v=\frac{y}{x}\right] . \\
\Rightarrow & x \sqrt{y^{2}+2 x y}= \pm C_{1} \\
\Rightarrow & x^{2}\left(y^{2}+2 x y\right)=C, \text { where } C=C_{1}^{2} . \tag{ii}
\end{aligned}
$$

Putting $x=1$ and $y=1$ in (ii), we get $C=3$.
$\therefore \quad x^{2}\left(y^{2}+2 x y\right)=3$ is the required solution.

---

### Example 17: Find the particular solution of the differential equation $x \frac{d y}{d x}-y+x \operatorname{cosec} \frac{y}{x}=0$, given that $y=0$ when $x=1$. [CBSE 2009, '14C]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{y}{x}-\operatorname{cosec} \frac{y}{x} . \tag{i}
\end{equation*}
$$

This is of the form $\frac{d y}{d x}=f\left(\frac{y}{x}\right) \cdot$ So, it is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=v-\operatorname{cosec} v \\
\Rightarrow & x \frac{d v}{d x}=-\operatorname{cosec} v \\
\Rightarrow & -\sin v d v=\frac{1}{x} d x \\
\Rightarrow & \int(-\sin v) d v=\int \frac{1}{x} d x \quad[\text { on integrating both sides }] \\
\Rightarrow & \cos v=\log |x|+C, \text { where } C \text { is an arbitrary constant } \\
\Rightarrow & \cos \frac{y}{x}=\log |x|+C \quad \ldots \text { (ii) }\left[\because v=\frac{y}{x}\right] .
\end{aligned}
$$

Putting $x=1$ and $y=0$ in (ii), we get $C=1$.
Hence, $\cos \frac{y}{x}=1+\log |x|$ is the required solution.

---

### Example 18: Find the particular solution of the differential equation
$$
\left[x \sin ^{2}\left(\frac{y}{x}\right)-y\right] d x+x d y=0, \text { given that } y=\frac{\pi}{4} \text { when } x=1
$$

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d y}{d x}=\frac{y}{x}-\sin ^{2}\left(\frac{y}{x}\right) \tag{i}
\end{equation*}
$$

This is of the form $\frac{d y}{d x}=f\left(\frac{y}{x}\right) \cdot$ So, it is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=v-\sin ^{2} v \\
\Rightarrow & x \frac{d v}{d x}=-\sin ^{2} v \\
\Rightarrow & -\operatorname{cosec}^{2} v d v=\frac{1}{x} d x \\
\Rightarrow & \int\left(-\operatorname{cosec}^{2} v\right) d v=\int \frac{1}{x} d x \quad[\text { on integrating both sides }] \\
\Rightarrow & \cot v=\log |x|+C, \text { where } C \text { is an arbitrary constant } \\
\Rightarrow & \cot \frac{y}{x}=\log |x|+C \quad \ldots \text { (ii) }\left[\because v=\frac{y}{x}\right]
\end{aligned}
$$

Putting $x=1$ and $y=\frac{\pi}{4}$ in (ii), we get $C=1$.
$\therefore \quad \cot \frac{y}{x}=\log |x|+1$ is the desired solution.

---

### Example 19: Find the equation of the family of curves for which the slope of tangent at any point ( $x, y$ ) on it, is $\frac{x^{2}+y^{2}}{2 x y}$.

#### Solution:

We know that the slope of the tangent at any point $(x, y)$ of the curve is $\frac{d y}{d x}$.

$$
\begin{equation*}
\therefore \quad \frac{d y}{d x}=\frac{x^{2}+y^{2}}{2 x y} . \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $x^{2}$, we get

$$
\frac{d y}{d x}=\frac{\left\{1+\left(\frac{y}{x}\right)^{2}\right\}}{2\left(\frac{y}{x}\right)}=f\left(\frac{y}{x}\right)
$$

So, the given differential equation is homogeneous.
Putting $y=v x$ and $\frac{d y}{d x}=v+x \frac{d v}{d x}$ in (i), we get

$$
\begin{aligned}
& v+x \frac{d v}{d x}=\frac{1+v^{2}}{2 v} \\
\Rightarrow & x \frac{d v}{d x}=\left\{\frac{\left(1+v^{2}\right)}{2 v}-v\right\}=\frac{\left(1-v^{2}\right)}{2 v} \\
\Rightarrow & \frac{2 v}{\left(1-v^{2}\right)} d v=\frac{1}{x} d x \\
\Rightarrow & \int \frac{2 v}{\left(v^{2}-1\right)} d v=-\int \frac{1}{x} d x \quad[\text { on integrating both sides }] \\
\Rightarrow & \log \left|v^{2}-1\right|=-\log |x|+\log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$\Rightarrow \log \left|v^{2}-1\right|+\log |x|=\log \left|C_{1}\right|$
$\Rightarrow \quad \log \left|\left(v^{2}-1\right) x\right|=\log \left|C_{1}\right|$
$\Rightarrow \quad\left(v^{2}-1\right) x= \pm C_{1}$
$\Rightarrow\left(\frac{y^{2}}{x^{2}}-1\right) x= \pm C_{1}$
$\Rightarrow \quad\left(y^{2}-x^{2}\right)= \pm C_{1} x$
$\Rightarrow \quad\left(x^{2}-y^{2}\right)=C x$, where $\pm C_{1}=C$.
Hence, $\left(x^{2}-y^{2}\right)=C x$ is the equation of the required family of curves.

---

### Example 20: Show that the differential equation $2 y e^{x / y} d x+\left(y-2 x e^{x / y}\right) d y=0$ is homogeneous. Find the particular solution of this differential equation, given that $x=0$ when $y=1$. [CBSE 2013]

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d x}{d y}=\frac{\left(2 x e^{x / y}-y\right)}{2 y e^{x / y}} \tag{i}
\end{equation*}
$$

On dividing the Nr and Dr of RHS of (i) by $y$, we get

$$
\begin{equation*}
\frac{d x}{d y}=\frac{\left\{2 \frac{x}{y} \cdot e^{x / y}-1\right\}}{2 e^{x / y}}=f\left(\frac{x}{y}\right) \tag{ii}
\end{equation*}
$$

So, the given differential equation is homogeneous.
Putting $x=v y$ and $\frac{d x}{d y}=v+y \frac{d v}{d y}$ in (ii), we get

$$
\begin{aligned}
& v+y \frac{d v}{d y}=\frac{\left(2 v e^{v}-1\right)}{2 e^{v}} \\
\Rightarrow & y \frac{d v}{d y}=\left\{\frac{\left(2 v e^{v}-1\right)}{2 e^{v}}-v\right\}=\frac{-1}{2 e^{v}} \\
\Rightarrow & 2 e^{v} d v=\frac{-1}{y} d y \\
\Rightarrow & 2 \int e^{v} d v=-\int \frac{1}{y} d y \quad \text { [on integrating both sides] } \\
\Rightarrow & 2 e^{v}=-\log |y|+C \quad \ldots \text { (iii) } \\
\Rightarrow & 2 e^{x / y}+\log |y|=C \quad\left[\because v=\frac{x}{y}\right]
\end{aligned}
$$

Putting $y=1$ and $x=0$ in (iii), we get $C=2$.
$\therefore \quad 2 e^{x / y}+\log |y|=2$ is the required solution.

---

### Example 21: Show that the differential equation $\left(1+e^{x / y}\right) d x+e^{x / y}\left(1-\frac{x}{y}\right) d y=0$ is homogeneous and solve it.

#### Solution:

The given differential equation may be written as

$$
\begin{equation*}
\frac{d x}{d y}=\frac{e^{x / y}\left(\frac{x}{y}-1\right)}{\left(1+e^{x / y}\right)} \tag{i}
\end{equation*}
$$

This is of the form $\frac{d x}{d y}=f\left(\frac{x}{y}\right) \cdot$ So, it is homogeneous.
Putting $x=v y$ and $\frac{d x}{d y}=v+y \frac{d v}{d y}$ in (i), we get

$$
\begin{aligned}
& v+y \frac{d v}{d y}=\frac{e^{v}(v-1)}{\left(1+e^{v}\right)} \\
\Rightarrow & y \frac{d v}{d y}=\left\{\frac{e^{v}(v-1)}{\left(1+e^{v}\right)}-v\right\}=\frac{-\left(v+e^{v}\right)}{\left(1+e^{v}\right)} \\
\Rightarrow & \frac{\left(1+e^{v}\right)}{\left(v+e^{v}\right)} d v=-\frac{1}{y} d y \\
\Rightarrow & \int \frac{\left(1+e^{v}\right)}{\left(v+e^{v}\right)} d v=-\int \frac{1}{y} d y \quad \text { [on integrating both sides] } \\
\Rightarrow & \log \left|v+e^{v}\right|=-\log |y|+\log \left|C_{1}\right|
\end{aligned}
$$

where $C_{1}$ is an arbitrary constant
$\Rightarrow \log \left|v+e^{v}\right|+\log |y|=\log \left|C_{1}\right|$
$\Rightarrow \log \left|\left(v+e^{v}\right) y\right|=\log \left|C_{1}\right|$
$\Rightarrow \quad\left(v+e^{v}\right) y= \pm C_{1}=C$ (say)
$\Rightarrow\left(\frac{x}{y}+e^{x / y}\right) y=C$
$\Rightarrow x+y e^{x / y}=C$, which is the required solution.

---

### Example 22: Show that the differential equation $y d x+x \log \left(\frac{y}{x}\right) d y-2 x d y=0$ is homogeneous and solve it.

#### Solution:

The given differential equation may be written as

$$
\begin{align*}
y \frac{d x}{d y} & =2 x-x \log \left(\frac{y}{x}\right) \\
& =2 x-x \cdot \log \left\{\frac{1}{(x / y)}\right\} \\
& =2 x-x \cdot\left[\log 1-\log \frac{x}{y}\right] \\
& =2 x+x \log \frac{x}{y} \\
\therefore \quad \frac{d x}{d y}= & 2\left(\frac{x}{y}\right)+\left(\frac{x}{y}\right) \log \frac{x}{y}=f\left(\frac{x}{y}\right) . \tag{i}
\end{align*}
$$

So, the given differential equation is homogeneous.
Putting $x=v y$ and $\frac{d x}{d y}=v+y \frac{d v}{d y}$ in (i), we get

$$
\begin{aligned}
& v+y \frac{d v}{d y}=2 v+v(\log v) \\
\Rightarrow & y \frac{d v}{d y}=v(1+\log v)
\endaligned}
$$

$\Rightarrow \int \frac{1}{v(1+\log v)} d v=\int \frac{1}{y} d y \Rightarrow \int \frac{1}{t} d t=\int \frac{1}{y} d y$, where $(1+\log v)=t$
$\Rightarrow \log |t|=\log |y|+\log \left|C_{1}\right| \Rightarrow \log |1+\log v|-\log |y|=\log \left|C_{1}\right|$
$\Rightarrow \quad \log \left|\frac{1+\log v}{y}\right|=\log \left|C_{1}\right| \Rightarrow \frac{1+\log v}{y}= \pm C_{1}=C$
$\therefore \quad 1+\log \frac{x}{y}=C y$ is the required solution.

---

