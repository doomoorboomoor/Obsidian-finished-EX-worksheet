## Invertible Function

Let $f: A \rightarrow B$. If there exists a function $g: B \rightarrow A$ such that $g \circ f=I_{A}$ and $f \circ g=I_{B}$ then $f$ is called an **invertible function** and $g$ is called the **inverse** of $f$. We write, $f^{-1}=g$.

**REMARK** Clearly, $f^{-1}$ o $f=I_{A}$ and $f$ o $f^{-1}=I_{B}$.

**Example** Let $f: R \rightarrow R: f(x)=2 x+3$.
Let $y=f(x)$. Then,

$$
\begin{aligned}
y=f(x) & \Rightarrow y=2 x+3 \\
& \Rightarrow x=\frac{1}{2}(y-3) \\
& \Rightarrow f^{-1}(y)=\frac{1}{2}(y-3)\left[\because y=f(x) \Rightarrow x=f^{-1}(y)\right] .
\end{aligned}
$$

Thus, we define:

$$
f^{-1}: R \rightarrow R: f^{-1}(y)=\frac{1}{2}(y-3) .
$$

---

**THEOREM 1** If $f: A \rightarrow B$ is one-one onto then prove that $f$ is an invertible function.

**PROOF** Let $y \in B$. Then, $f$ being one-one onto, there exists a unique $x \in A$ such that $f(x)=y$.
We define $g: B \rightarrow A: g(y)=x$. Then,

$$
\begin{aligned}
(g \circ f)(x) & =g[f(x)] & & \\
& =g(y) & {[\because} & f(x)=y] \\
& =x & {[\because} & g(y)=x] \\
& =I_{A}(x) . & &
\end{aligned}
$$

$$
\left.\therefore \quad \begin{array}{rll}
(g \circ f)= & I_{A} . \\
& (f \circ g)(y) & =f[g(y)] \\
& =f(x) & {[\because} & g(y)=x] \\
& =y & {[\because} & f(x)=y] \\
& =I_{B}(y) . & &
\end{array}\right]
$$

$\therefore \quad(f \circ g)=I_{B}$.
Hence, $f$ is invertible and $f^{-1}=g$.

---

**THEOREM 2** If $f: A \rightarrow B$ is an invertible function, then prove that $f$ is one-one onto.

**PROOF** Let $f: A \rightarrow B$ be an invertible function. Then, there exists a function $g: B \rightarrow A$ such that
$g \circ f=I_{A} \quad$ and $\quad f \circ g=I_{B}$.

Now, $f\left(x_{1}\right)=f\left(x_{2}\right)$
$\Rightarrow g\left\{f\left(x_{1}\right)\right\}=g\left\{f\left(x_{2}\right)\right\}$
$\Rightarrow(g \circ f)\left(x_{1}\right)=(g \circ f)\left(x_{2}\right)$
$\Rightarrow I_{A}\left(x_{1}\right)=I_{A}\left(x_{2}\right) \quad\left[\because \quad g \circ f=I_{A}\right]$
$\Rightarrow x_{1}=x_{2}$.
$\therefore f$ is one-one.

Let $y \in B$. Then, $g(y) \in A$. Let $g(y)=x$. Then,
$g(y)=x$
$\Rightarrow f\{g(y)\}=f(x)$
$\Rightarrow(f \circ g)(y)=f(x)$
$\Rightarrow I_{B}(y)=f(x) \quad\left[\because \quad f \circ g=I_{B}\right]$
$\Rightarrow y=f(x)$.

Thus, for each $y \in B$ there exists $x \in A$ such that $y=f(x)$.
$\therefore f$ is onto.
Hence, $f$ is one-one onto.

**REMARK** $f$ is invertible $\Leftrightarrow f$ is one-one onto.

---

## SOLVED EXAMPLES

### Example 1:

Let $f: R \rightarrow R: f(x)=4 x+3$ for all $x \in R$. Show that $f$ is invertible and find $f^{-1}$.

#### Solution:

We have

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow 4 x_{1}+3=4 x_{2}+3 \\
& \Rightarrow 4 x_{1}=4 x_{2} \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

$\therefore \quad f$ is one-one.
Again, $y=4 x+3 \Rightarrow x=\frac{(y-3)}{4}$.
Now, if $y \in R$ (codomain of $f$) then there exists $x=\frac{(y-3)}{4} \in R$ such that $f(x)=f\left(\frac{y-3}{4}\right)=\left\{4 \cdot \frac{(y-3)}{4}+3\right\}=y$.
$\therefore \quad f$ is onto.
Thus, $f$ is one-one onto and therefore invertible.

Now, $y=f(x) \Rightarrow y=4 x+3$

$$
\Rightarrow x=\frac{(y-3)}{4}
$$

$$
\Rightarrow \quad f^{-1}(y)=\frac{(y-3)}{4} \quad\left[\because \quad f(x)=y \Rightarrow x=f^{-1}(y)\right]
$$

Thus, we define:

$$
f^{-1}: R \rightarrow R: f^{-1}(y)=\frac{(y-3)}{4} \text { for all } y \in R .
$$

---

### Example 2:

Let $R_{+}$be the set of all positive real numbers. Let $f: R_{+} \rightarrow\left[4, \infty\left[: f(x)=x^{2}+4\right.\right.$. Show that $f$ is invertible and find $f^{-1}$.

#### Solution:

We have

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow x_{1}^{2}+4=x_{2}^{2}+4 \\
& \Rightarrow x_{1}^{2}=x_{2}^{2} \\
& \Rightarrow x_{1}^{2}-x_{2}^{2}=0 \\
& \Rightarrow\left(x_{1}-x_{2}\right)\left(x_{1}+x_{2}\right)=0 \\
& \Rightarrow x_{1}-x_{2}=0 \quad\left[\because \quad\left(x_{1}+x_{2}\right) \neq 0\right] \\
& \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

$\therefore f$ is one-one.
Now, $y=x^{2}+4 \Rightarrow x=\sqrt{y-4}$.
For each $y \in\left[4, \infty\left[\right.\right.$ there exists $x=\sqrt{y-4}$ in $R_{+}$such that $f(x)=f(\sqrt{y-4})=(\sqrt{y-4})^{2}+4=(y-4)+4=y$.
$\therefore \quad f$ is onto.
Thus, $f$ is one-one onto and therefore invertible.

$$
\begin{aligned}
\text { Now, } y=f(x) & \Rightarrow y=x^{2}+4 \\
& \Rightarrow x=\sqrt{y-4} \\
& \Rightarrow f^{-1}(y)=\sqrt{y-4} . \\
\therefore \quad f^{-1}:[4, \infty[ & \rightarrow R_{+}: f^{-1}(y)=\sqrt{y-4} .
\end{aligned}
$$

---

### Example 3:

Let $R^{+}$be the set of all positive real numbers. Let $f: R^{+} \rightarrow R^{+}: f(x)=e^{x}$ for all $x \in R^{+}$. Show that $f$ is invertible and hence find $f^{-1}$.

#### Solution:

$f$ is one-one, since

$$
f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow e^{x_{1}}=e^{x_{2}} \Rightarrow x_{1}=x_{2}
$$

Now, for each $y \in R^{+}$, there exists a positive real number, namely $\log y$ such that

$$
f(\log y)=e^{\log y}=y
$$

$\therefore f$ is onto.
Thus, $f$ is one-one onto and hence invertible.

We define:

$$
f^{-1}: R^{+} \rightarrow R^{+}: f^{-1}(y)=\log y \text { for all } y \in R^{+} .
$$

---

### Example 4:

Let $A=\left\{x: x \in R, \frac{-\pi}{2} \leq x \leq \frac{\pi}{2}\right\}$ and $B=\{y: y \in R,-1 \leq y \leq 1\}$. Show that the function $f: A \rightarrow B: f(x)=\sin x$ is invertible and hence find $f^{-1}$.

#### Solution:

Here, $A=\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]$ and $B=[-1,1]$.
Also, $f: A \rightarrow B: f(x)=\sin x$.
$f$ is one-one, since

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow \sin x_{1}=\sin x_{2} \\
& \Rightarrow x_{1}=x_{2} \quad\left\{\because \quad x_{1}, x_{2} \in\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]\right\} .
\end{aligned}
$$

$\therefore \quad f$ is one-one.
Also, range $(f)=[-1,1]=B$. So, $f$ is onto.
Thus, $f$ is one-one onto and hence invertible.

Now, $y=f(x) \Rightarrow y=\sin x$

$$
\begin{aligned}
& \Rightarrow x=\sin ^{-1} y \\
& \Rightarrow f^{-1}(y)=\sin ^{-1} y .
\end{aligned}
$$

Thus, we define:

$$
f^{-1}:[-1,1] \rightarrow\left[\frac{-\pi}{2}, \frac{\pi}{2}\right]: f^{-1}(y)=\sin ^{-1} y .
$$

---

### Example 5:

Let $f: N \rightarrow Y: f(x)=x^{2}$, where $Y=$ range $(f)$. Show that $f$ is invertible and find $f^{-1}$.

#### Solution:

We have

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow x_{1}^{2}=x_{2}^{2} \\
& \Rightarrow x_{1}^{2}-x_{2}^{2}=0 \\
& \Rightarrow\left(x_{1}-x_{2}\right)\left(x_{1}+x_{2}\right)=0 \\
& \Rightarrow x_{1}-x_{2}=0 \quad\left[\because \quad x_{1}+x_{2} \neq 0\right] \\
& \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

$\therefore \quad f$ is one-one.
Since range $(f)=Y$, so $f$ is onto.
Thus, $f$ is one-one onto and therefore invertible.
Let $y \in Y$. Then, there exists $x \in N$ such that $f(x)=y$.

$$
\text { Now, } \begin{aligned}
y=f(x) & \Rightarrow y=x^{2} \\
& \Rightarrow x=\sqrt{y} \\
& \Rightarrow f^{-1}(y)=\sqrt{y} \quad\left[\because \quad f(x)=y \Rightarrow x=f^{-1}(y)\right] .
\end{aligned}
$$

Thus, we define

$$
f^{-1}: Y \rightarrow N: f^{-1}(y)=\sqrt{y} .
$$

---

### Example 6:

Let $f:[-1,1] \rightarrow Y: f(x)=\frac{x}{(x+2)}, x \neq-2$ and $Y=\operatorname{range}(f)$. Show that $f$ is invertible and find $f^{-1}$.

#### Solution:

We have

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow \frac{x_{1}}{x_{1}+2}=\frac{x_{2}}{x_{2}+2} \\
& \Rightarrow x_{1} x_{2}+2 x_{1}=x_{1} x_{2}+2 x_{2} \\
& \Rightarrow 2\left(x_{1}-x_{2}\right)=0 \\
& \Rightarrow x_{1}-x_{2}=0 \\
& \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

$\therefore \quad f$ is one-one.
Since range $(f)=Y$, so $f$ is onto.
Thus, $f$ is one-one onto and therefore invertible.
Let $y \in Y$. Then, there exists $x \in[-1,1]$ such that $f(x)=y$.

Now, $y=f(x) \Rightarrow y=\frac{x}{(x+2)}$

$$
\begin{aligned}
& \Rightarrow x=\frac{2 y}{(1-y)} \\
& \Rightarrow f^{-1}(y)=\frac{2 y}{(1-y)} .
\end{aligned}
$$

Thus, we define:

$$
f^{-1}:[-1,1] \rightarrow Y: f^{-1}(y)=\frac{2 y}{(1-y)}, \quad y \neq 1
$$

---

### Example 7:

Let $f: N \rightarrow Y: f(x)=4 x^{2}+12 x+15$ and $Y=\operatorname{range}(f)$. Show that $f$ is invertible and find $f^{-1}$.
[CBSE 2013C]

#### Solution:

$f$ is one-one, since

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow 4 x_{1}^{2}+12 x_{1}+15=4 x_{2}^{2}+12 x_{2}+15 \\
& \Rightarrow 4\left(x_{1}^{2}-x_{2}^{2}\right)+12\left(x_{1}-x_{2}\right)=0 \\
& \Rightarrow\left(x_{1}^{2}-x_{2}^{2}\right)+3\left(x_{1}-x_{2}\right)=0 \\
& \Rightarrow\left(x_{1}-x_{2}\right)\left(x_{1}+x_{2}+3\right)=0 \\
& \Rightarrow x_{1}-x_{2}=0 \quad\left[\because x_{1}+x_{2}+3 \neq 0\right] \\
& \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

Also, range $(f)=Y$. So, $f$ is onto.
Thus, $f$ is one-one onto and therefore invertible.
Let $y \in Y$. Then, $f$ being onto, there exists $x$ such that $y=f(x)$.

$$
\text { Now, } \begin{aligned}
y=f(x) & \Rightarrow y=4 x^{2}+12 x+15 \\
& \Rightarrow y=(2 x+3)^{2}+6 \\
& \Rightarrow(2 x+3)=\sqrt{y-6} \\
& \Rightarrow x=\frac{1}{2}(\sqrt{y-6}-3) \\
& \Rightarrow f^{-1}(y)=\frac{1}{2}(\sqrt{y-6}-3)
\end{aligned}
$$

Thus, we define:

$$
f^{-1}: Y \rightarrow N: f^{-1}(y)=\frac{1}{2}(\sqrt{y-6}-3) .
$$

---

### Example 8:

Let $f: R \rightarrow R: f(x)=10 x+7$. Find the function $g: R \rightarrow R$ such that $g \circ f=f \circ g=I_{R}$.
[CBSE 2011]

#### Solution:

Clearly, $g=f^{-1}$

Now, $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow 10 x_{1}+7=10 x_{2}+7$

$$
\begin{aligned}
& \Rightarrow 10 x_{1}=10 x_{2} \\
& \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

$\therefore \quad f$ is one-one.
Now, $y=f(x) \Rightarrow y=10 x+7$

$$
\Rightarrow x=\frac{(y-7)}{10}
$$

Clearly, for each $y \in R$ (codomain of $f$) there exists $x \in R$ such that

$$
f(x)=f\left(\frac{y-7}{10}\right)=\left\{10 \cdot\left(\frac{y-7}{10}\right)+7\right\}=y .
$$

$\therefore \quad f$ is onto.
Thus, $f$ is one-one onto and therefore, $f^{-1}$ exists.
We define: $\quad f^{-1}: R \rightarrow R: f^{-1}(y)=\frac{y-7}{10}$.
Hence, $g: R \rightarrow R: g(y)=\frac{y-7}{10} \quad[$ using $(\mathrm{i})]$.

---

### Example 9:

Let $f: W \rightarrow W: f(n)=$
$$
\begin{cases}(n-1), & \text { when } n \text { is odd } \\ (n+1), & \text { when } n \text { is even. }\end{cases}
$$
Show that $f$ is invertible. Find $f^{-1}$.
[CBSE 2012]

#### Solution:

**Case 1** When $n_{1}$ is odd and $n_{2}$ is even

In this case, $f\left(n_{1}\right)=f\left(n_{2}\right) \Rightarrow n_{1}-1=n_{2}+1$

$$
\Rightarrow n_{1}-n_{2}=2 .
$$

If $n_{1}$ is odd and $n_{2}$ is even, then $\left(n_{1}-n_{2}\right) \neq 2$.
Thus, we arrive at a contradiction.
So, in this case, $f\left(n_{1}\right) \neq f\left(n_{2}\right)$.

Similarly, when $n_{1}$ is even and $n_{2}$ is odd, then $f\left(n_{1}\right) \neq f\left(n_{2}\right)$.

**Case 2** When $n_{1}$ and $n_{2}$ are both odd

$$
\text { In this case, } \begin{aligned}
f\left(n_{1}\right)=f\left(n_{2}\right) & \Rightarrow n_{1}-1=n_{2}-1 \\
& \Rightarrow n_{1}=n_{2} .
\end{aligned}
$$

**Case 3** When $n_{1}$ and $n_{2}$ are both even

In this case, $f\left(n_{1}\right)=f\left(n_{2}\right) \Rightarrow n_{1}+1=n_{2}+1$

$$
\Rightarrow n_{1}=n_{2} .
$$

Thus, from all the cases, we get $f\left(n_{1}\right)=f\left(n_{2}\right) \Rightarrow n_{1}=n_{2}$.
$\therefore f$ is one-one.

Now, we show that $f$ is onto.
Let $n \in W$.

**Case 1** When $n$ is odd

In this case, ( $n-1$ ) is even

$$
\begin{equation*}
\text { and } f(n-1)=(n-1)+1=n \text {. } \tag{i}
\end{equation*}
$$

**Case 2** When $n$ is even

In this case, ( $n+1$ ) is odd

$$
\begin{equation*}
\text { and } f(n+1)=(n+1)-1=n \text {. } \tag{ii}
\end{equation*}
$$

Thus, each $n \in W$ has its pre-image in $W$.
$\therefore f$ is onto.
Thus, $f$ is one-one onto and hence invertible.
Clearly, we have

$$
f^{-1}(n)=\left\{\begin{array}{ll}
(n-1), & \text { when } n \text { is odd } \\
(n+1), & \text { when } n \text { is even }
\end{array} \quad[\text { using (i) and (ii) }]\right.
$$

---

### Example 10:

Let $A=\{1,2,3\}$ and let $f: A \rightarrow A$, defined by

$$
f=\{(1,2),(2,3),(3,1)\} .
$$

Find $f^{-1}$, if it exists.

#### Solution:

We have $f(1)=2, f(2)=3$ and $f(3)=1$.
$\operatorname{Dom}(f)=\{1,2,3\}=A$ and range $(f)=\{1,2,3\}=A$.
Clearly, different elements in $A$ have different images.
$\therefore f$ is one-one.
Range $(f)=A \Rightarrow f$ is onto.
Thus, $f$ is one-one onto and therefore invertible.

Now, $f(1)=2, f(2)=3$ and $f(3)=1$
$\Rightarrow f^{-1}(2)=1, f^{-1}(3)=2$ and $f^{-1}(1)=3$.
Hence, $f^{-1}=\{(2,1),(3,2),(1,3)\}$.

---

## Some Results on Invertible Functions

**THEOREM 1** Prove that an invertible function has a unique inverse.

**PROOF** Let $f: A \rightarrow B$, which is one-one onto and therefore, invertible.
If possible, let it have two inverses, say $g$ and $h$.
Then, $(f \circ g)=I_{B}$ and $(f \circ h)=I_{B}$
$\Rightarrow(f \circ g)(y)=(f \circ h)(y) \quad\left[\right.$ each $\left.=I_{B}(y)\right]$
$\Rightarrow f\{g(y)\}=f\{h(y)\}$ for all $y \in B$
$\Rightarrow g(y)=h(y)$ for all $y \in B \quad[\because \quad f$ is one-one $]$.
$\therefore g=h$.
Hence, $f$ has a unique inverse.

---

**THEOREM 2** Let $f$ be an invertible function. Then, prove that

$$
\left(f^{-1}\right)^{-1}=f .
$$

**PROOF** Let $f: A \rightarrow B$, which is invertible.
In order to prove that $\left(f^{-1}\right)^{-1}=f$, it is sufficient to show that

$$
f^{-1} \circ f=I_{A} \text { and } f \circ f^{-1}=I_{B} .
$$

Clearly $f: A \rightarrow B$ is one-one onto.
$\therefore \quad f^{-1}: B \rightarrow A$ is one-one onto.
Let $x \in A$ and let $f(x)=y$. Then, $f^{-1}(y)=x$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Relations-and-Functions/Functions/class-12-Ch-02-C-BooK-001.jpg)

$$
\begin{aligned}
\therefore\left(f^{-1} \circ f\right)(x) & =f^{-1}\{f(x)\} \\
& =f^{-1}(y)[\because f(x)=y] \\
& =x \\
& =I_{A}(x) .
\end{aligned}
$$

$\therefore \quad f^{-1}$ o $f=I_{A}$.
Again, let $y \in B$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Relations-and-Functions/Functions/class-12-Ch-02-C-BooK-002.jpg)

Then, $f$ being onto, there exists $x \in A$ such that $f(x)=y$ and therefore, $f^{-1}(y)=x$.

$$
\begin{aligned}
\therefore \quad\left(f \circ f^{-1}\right)(y) & =f\left\{f^{-1}(y)\right\} \\
& =f(x) \quad\left[\because f^{-1}(y)=x\right] \\
& =y \\
& =I_{B}(y)
\end{aligned}
$$

$\therefore f \circ f^{-1}=I_{B}$.
Thus, $f^{-1}$ o $f=I_{A}$ and $f \circ f^{-1}=I_{B}$.
Hence, $\left(f^{-1}\right)^{-1}=f$.

---

**THEOREM 3** Let $f: A \rightarrow B$ and $g: B \rightarrow C$ be one-one onto functions. Prove that $(g \circ f): A \rightarrow C$ which is one-one onto and $(g \circ f)^{-1}=f^{-1} \circ g^{-1}$.

**PROOF** Let $f: A \rightarrow B$ be one-one onto and $g: B \rightarrow C$ be one-one onto.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Relations-and-Functions/Functions/class-12-Ch-02-C-BooK-003.jpg)

We first show that $g$ o $f$ is one-one onto.
( $g \circ f$ ) is one-one, since

$$
\begin{aligned}
& (g \circ f)\left(x_{1}\right)=(g \circ f)\left(x_{2}\right) \\
\Rightarrow & g\left\{f\left(x_{1}\right)\right\}=g\left\{f\left(x_{2}\right)\right\} \\
\Rightarrow & f\left(x_{1}\right)=f\left(x_{2}\right) \quad[\because \quad g \text { is one-one }] \\
\Rightarrow & x_{1}=x_{2} \quad[\because \quad f \text { is one-one }] .
\end{aligned}
$$

Let $z \in C$. Then, $g$ being onto, there exists $y \in B$ such that $g(y)=z$.
Now, $f$ being onto, there exists $x \in A$ such that $f(x)=y$.

$$
\begin{aligned}
\therefore \quad z & =g(y) \\
& =g\{f(x)\} \quad[\because \quad y=f(x)] \\
& =(g \circ f)(x) .
\end{aligned}
$$

Thus, for each $z \in C$, there exists $x \in A$ such that $(g \circ f)(x)=z$.
$\therefore \quad(g \circ f)$ is onto.
Thus, $(g \circ f)$ is one-one onto.

Now, $f(x)=y \Rightarrow f^{-1}(y)=x$.
And, $g(y)=z \Rightarrow g^{-1}(z)=y$.
Also, $(g \circ f)(x)=z \Rightarrow(g \circ f)^{-1}(z)=x$.

$$
\begin{aligned}
\therefore\left(f^{-1} \circ g^{-1}\right)(z) & =f^{-1}\left\{g^{-1}(z)\right\} \\
& =f^{-1}(y) \quad\left[\because \quad g^{-1}(z)=y\right] \\
& =x \quad\left[\because \quad f^{-1}(y)=x\right] \\
& =(g \circ f)^{-1}(z) . \\
\text { Hence, }(g \circ f)^{-1} & =\left(f^{-1} \circ g^{-1}\right) .
\end{aligned}
$$

---
