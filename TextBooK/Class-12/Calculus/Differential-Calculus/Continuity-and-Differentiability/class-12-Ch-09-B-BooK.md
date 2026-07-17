## Continuous Functions

### Continuity in an Interval
A function $f(x)$ is said to be continuous in an open interval $] a, b[$ if it is continuous at each point of $] a, b[$.

If $f(x)$ is defined on a closed interval $[a, b]$, we say that:
1.  $f$ is continuous at $a$ if $\lim _{x \rightarrow a+} f(x)=f(a)$;
2.  $f$ is continuous at $b$ if $\lim _{x \rightarrow b-} f(x)=f(b)$;
3.  $f$ is continuous in $[a, b]$ if it is continuous at $a$, at $b$ and at each point of $] a, b[$.

### Continuous Functions
A function $f(x)$ is said to be **continuous** if it is continuous at each point of its domain.

---

## Algebra of Continuous Functions

**THEOREM 1** *Every constant function is continuous.*

**PROOF** Let $f(x)=c$, where $c$ is constant.
Clearly, the domain of a constant function is $R$.
Let $a$ be an arbitrary real number.
Then, $f(a)=c$ and $\lim _{x \rightarrow a} f(x)=\lim _{x \rightarrow a} c=c \quad[\because \quad f(x)=c]$.
$\therefore \quad \lim _{x \rightarrow a} f(x)=f(a)$.
Thus, $\quad f(x)$ is continuous at $x=a$ for all $a \in R$.
Hence, $f(x)$ is continuous.

---

**THEOREM 2** *Show that the identity function is continuous.*

**PROOF** Let $f(x)=x$ for all $x \in R$.
Let $a$ be an arbitrary real number. Then, $f(a)=a$.
And, $\lim _{x \rightarrow a} f(x)=\lim _{x \rightarrow a} x=a \quad[\because \quad f(x)=x]$.
$\therefore \quad \lim _{x \rightarrow a} f(x)=f(a)=a$.
This shows that $f(x)$ is continuous at $x=a$ for all $a \in R$.
Hence, the identity function is continuous.

---

**THEOREM 3** *If $f$ and $g$ be continuous functions then:*
1.  $f+g$ is continuous
2.  $f-g$ is continuous
3.  $cf$ is continuous
4.  $f g$ is continuous
5.  $\left(\frac{f}{g}\right)$ is continuous at those points where $g(x) \neq 0$

**PROOF** (i) Let $\operatorname{dom}(f)=D_{1}$ and $\operatorname{dom}(g)=D_{2}$. Then, $\operatorname{dom}(f+g)=D_{1} \cap D_{2}$.
Let $a \in D_{1} \cap D_{2}$. Then, $a \in D_{1}$ and $a \in D_{2}$.
By continuity of $f$ and $g$, we have

$$
\begin{aligned}
& \lim _{x \rightarrow a} f(x)=f(a) \text { and } \lim _{x \rightarrow a} g(x)=g(a) \\
\therefore \quad & \lim _{x \rightarrow a}(f+g)(x)= \\
& =\lim _{x \rightarrow a}[f(x)+g(x)]=\lim _{x \rightarrow a} f(x)+\lim _{x \rightarrow a} g(x) \\
& =f(a)+g(a)=(f+g)(a)
\end{aligned}
$$

This shows that $(f+g)$ is continuous at $a$ for all $a \in D_{1} \cap D_{2}$.
Hence, $(f+g)$ is continuous.
(ii) Similarly, (ii) may be proved.
(iii) Let $\operatorname{dom}(f)=D_{1}$. Then, $\operatorname{dom}(c f)=D_{1}$. Let $a \in D_{1}$.

Then, by the continuity of $f$, we have $\lim _{x \rightarrow a} f(x)=f(a)$.
$\therefore \quad \lim _{x \rightarrow a}(c f)(x)=\lim _{x \rightarrow a} c \cdot f(x)=c \cdot \lim _{x \rightarrow a} f(x)=c \cdot f(a)=(c f)(a)$.
This shows that (cf) is continuous at $a$ for all $a \in D_{1}$.
Hence, $c f$ is continuous.
(iv) Let $\operatorname{dom}(f)=D_{1}$ and $\operatorname{dom}(g)=D_{2}$. Then, $\operatorname{dom}(f g)=D_{1} \cap D_{2}$.

Let $a \in D_{1} \cap D_{2}$. Then, $a \in D_{1}$ and $a \in D_{2}$.
By continuity of $f$ and $g$, we have

$$
\begin{aligned}
& \lim _{x \rightarrow a} f(x)=f(a) \text { and } \lim _{x \rightarrow a} g(x)=g(a) . \\
\therefore \quad & \lim _{x \rightarrow a}(f g)(x)= \\
& =\lim _{x \rightarrow a}[f(x) \cdot g(x)] \\
& =\lim _{x \rightarrow a} f(x) \cdot \lim _{x \rightarrow a} g(x)=f(a) \cdot g(a)=(f g)(a) .
\end{aligned}
$$

This shows that $f g$ is continuous.
(v) Let $\operatorname{dom}(f)=D_{1}$ and $\operatorname{dom}(g)=D_{2}$.

Then, $\operatorname{dom}\left(\frac{f}{g}\right)=\left[\left(D_{1} \cap D_{2}\right)-\{x: g(x)=0\}\right]=D$ (say).
Let $a \in D$. Then $a \in D_{1}, a \in D_{2}$ and $g(a) \neq 0$.
By continuity of $f$ and $g$, we have
$\lim _{x \rightarrow a} f(x)=f(a)$ and $\lim _{x \rightarrow a} g(x)=g(a)$.
$\therefore \lim _{x \rightarrow a}\left(\frac{f}{g}\right)(x)=\lim _{x \rightarrow a} \frac{f(x)}{g(x)}=\frac{\lim _{x \rightarrow a} f(x)}{\lim _{x \rightarrow a} g(x)}=\frac{f(a)}{g(a)}=\left(\frac{f}{g}\right)(a)$, since $g(a) \neq 0$.
Thus, $\left(\frac{f}{g}\right)$ is continuous at $a$ for all $a \in D$. Hence, $\left(\frac{f}{g}\right)$ is continuous.

---

**THEOREM 4** *Every polynomial function is continuous.*

**PROOF** Let $f(x)=a_{0}+a_{1} x+a_{2} x^{2}+\ldots+a_{n} x^{n}$ be a polynomial. We shall prove the theorem by induction on $n$.
When $n=0$ then $f(x)=a_{0}$, which being a constant function is continuous.
When $n=1$ then $f(x)=a_{0}+a_{1} x$.
Clearly, $f(x)$ is the sum of a constant function and a multiple of the identity function. It, being the sum of two continuous functions, is continuous.
Let every polynomial of degree at most $n$ be continuous.
Consider a general polynomial of degree ($n+1$), namely,

$$
a_{0}+a_{1} x+a_{2} x^{2}+\ldots+a_{n} x^{n}+a_{n+1} x^{n+1} .
$$

This can be written as $a_{0}+x\left(a_{1}+a_{2} x+\ldots+a_{n} x^{n-1}+a_{n+1} x^{n}\right)$.
This is the sum of a constant function $a_{0}$ (which is continuous) and the product of the identity function $x$ (which is continuous) and the polynomial function $a_{1}+a_{2} x+\ldots+a_{n+1} x^{n}$ of degree at most $n$ (which we assumed to be continuous).
Therefore, it is continuous.
Thus, the continuity of a polynomial of degree $n$ implies the continuity of a polynomial of degree $(n+1)$.
Hence, by the principle of induction, every polynomial function is continuous.

---

**THEOREM 5** *Every rational function is continuous.*

**PROOF** Let $f(x)=\frac{p(x)}{q(x)}$, where $p(x)$ and $q(x)$ are polynomials.
Then, $\quad \operatorname{dom}[p(x)]=R$ and $\operatorname{dom}[q(x)]=R$.
$\therefore \operatorname{dom}[f(x)]=\operatorname{dom}\left\{\frac{p(x)}{q(x)}\right\}=R \cap R-\{x: q(x)=0\}=R-\{x: q(x)=0\}$.

Let $a$ be an arbitrary element of $\operatorname{dom} f(x)$.
Then, $a \in R$ and $q(a) \neq 0$.
But, every polynomial function being continuous, we have

$$
\begin{aligned}
& \lim _{x \rightarrow a} p(x)=p(a) \text { and } \lim _{x \rightarrow a} q(x)=q(a) . \\
\therefore \quad & \lim _{x \rightarrow a} f(x)=\lim _{x \rightarrow a}=\frac{\lim _{x \rightarrow a} p(x)}{\lim _{x \rightarrow a} q(x)}=\frac{p(a)}{q(a)}, \text { where } q(a) \neq 0 .
\end{aligned}
$$

This shows that $f(x)$ is continuous at $x=a$ for all $a \in \operatorname{dom} f(x)$.
Hence, every rational function is continuous.

---

**THEOREM 6** *Let $f$ and $g$ be real functions such that $f \mathrm{o} g$ is defined. If $g$ is continuous at $a$ and $f$ is continuous at $g(a)$, show that $f \circ g$ is continuous at $a$.*

**PROOF** Since $f og$ is defined, we have $\operatorname{range}(g) \subseteq \operatorname{dom}(f)$.
Since $g$ is continuous at $a$, we have $\quad \lim _{x \rightarrow a} g(x)=g(a)$.

Also, $f$ being continuous at $g(a)$, we have $\lim _{y \rightarrow g(a)} f(y)=f\{g(a)\}$.

$$
\begin{equation*}
\therefore \lim _{x \rightarrow a}(f \circ g)(x)=\lim _{x \rightarrow a} f\{g(x)\}=\lim _{g(x) \rightarrow g(a)} f\{g(x)\} \tag{ii}
\end{equation*}
$$

$$
\begin{aligned}
& \quad[\because \quad x \rightarrow a \Rightarrow g(x) \rightarrow g(a) \text { from (i) }] \\
& =\lim _{y \rightarrow g(a)} f(y)=f\{g(a)\} \quad[\text { using }(\text { ii })] \\
& =(f \circ g)(a) .
\end{aligned}
$$

Thus, $(f \circ g)$ is continuous at $a$.

---

**THEOREM 7** *The composite of two continuous functions is continuous.*

**PROOF** Let $f$ and $g$ be continuous functions such that $g$ of is defined.
Then, $\operatorname{range}(f) \subseteq \operatorname{dom}(g)$. Let $a \in \operatorname{dom}(f)$.
Then, $\quad a \in \operatorname{dom}(f) \Rightarrow f(a) \in \operatorname{range}(f)$

$$
\Rightarrow f(a) \in \operatorname{dom}(g) \quad[\because \quad \operatorname{range}(f) \subseteq \operatorname{dom}(g)]
$$

Thus, $f$ is continuous at $a$, and $g$ is continuous at $f(a)$.
Consequently, $\quad \lim _{x \rightarrow a} f(x)=f(a)$.

And, $\quad \lim _{y \rightarrow f(a)} g(y)=g[f(a)]$.

$$
\begin{equation*}
\therefore \quad \lim _{x \rightarrow a}(g \circ f)(x)=\lim _{x \rightarrow a} g[f(x)] \tag{ii}
\end{equation*}
$$

$=\lim _{f(x) \rightarrow f(a)} g[f(x)][\because x \rightarrow a \Rightarrow f(x) \rightarrow f(a)$ from (i) $]$
$=\lim _{y \rightarrow f(a)} g(y)=g[f(a)] \quad$ [using (ii)]
$=(g \circ f)(a)$.

This shows that $g$ o $f$ is continuous at $a$ for all $a \in \operatorname{dom}(f)$.
Hence $g$ o $f$ is continuous.

---

## An Important Result

For continuity of $f$ at $a$, it is sufficient to show that $\lim _{h \rightarrow 0} f(a+h)=f(a)$, since $f$ is continuous $\Leftrightarrow \lim _{x \rightarrow a} f(x)=f(a)$

$$
\begin{aligned}
& \Leftrightarrow \lim _{(a+h) \rightarrow a} f(a+h)=f(a) \quad[\text { putting } x=(a+h)] \\
& \Leftrightarrow \lim _{h \rightarrow 0} f(a+h)=f(a) .
\end{aligned}
$$

---

**THEOREM 8** *The exponential function is continuous.*

**PROOF** Let $f(x)=e^{x}$. Then, clearly, $\operatorname{dom}(f)=R$.
Let $a$ be an arbitrary real number. Then,

$\lim _{x \rightarrow a} e^{x}=\lim _{h \rightarrow 0} e^{a+h}=\lim _{h \rightarrow 0} e^{a} \cdot e^{h}=e^{a} \cdot \lim _{h \rightarrow 0} e^{h}=e^{a} \times 1=e^{a} .$

Thus, $f(x)=e^{x}$ is continuous at $x=a$ for all $a \in R$.
Hence, the exponential function is continuous.

---

**THEOREM 9**
1.  *The sine function is continuous.*
2.  *The cosine function is continuous.*
3.  *The tangent function is continuous.*

**PROOF** (i) Let $f(x)=\sin x$. Then, clearly $\operatorname{dom}(f)=R$.
Let $a$ be an arbitrary real number. Then,

$$
\begin{aligned}
\lim _{x \rightarrow a} f(x) & =\lim _{x \rightarrow a} \sin x=\lim _{h \rightarrow 0} \sin (a+h)=\lim _{h \rightarrow 0}[\sin a \cos h+\cos a \sin h] \\
& =\sin a \cdot \lim _{h \rightarrow 0} \cos h+\cos a \cdot \lim _{h \rightarrow 0} \sin h \\
& =(\sin a \times 1+\cos a \times 0)=\sin a=f(a) .
\end{aligned}
$$

Thus, $\quad \lim _{x \rightarrow a} f(x)=f(a)$ for all $a \in R$.
$\therefore \quad f(x)=\sin x$ is continuous at $a$ for all $a \in R$.
Hence, $\sin x$ is continuous.

(ii) Let $f(x)=\cos x$. Clearly, $\operatorname{dom}(f)=R$.

Let $a$ be an arbitrary real number. Then,

$$
\begin{aligned}
\lim _{x \rightarrow a} f(x) & =\lim _{x \rightarrow a} \cos x=\lim _{h \rightarrow 0} \cos (a+h)=\lim _{h \rightarrow 0}[\cos a \cos h-\sin a \sin h] \\
& =\cos a \cdot \lim _{h \rightarrow 0} \cos h-\sin a \cdot \lim _{h \rightarrow 0} \sin h=(\cos a \times 1-\sin a \times 0) \\
& =\cos a=f(a) .
\end{aligned}
$$

Thus, $\quad \lim _{x \rightarrow a} f(x)=f(a)$ for all $a \in R$.
$\therefore f(x)=\cos x$ is continuous at $a$ for all $a \in R$.
Hence, $\cos x$ is continuous.

(iii) We have $\tan x=\frac{\sin x}{\cos x}$ and $\operatorname{dom}(\tan x)=R-\left\{(2 n+1) \frac{\pi}{2}: n \in I\right\}$.

Let $a \in R-\left\{(2 n+1) \frac{\pi}{2}: n \in I\right\}$. Then,

$$
\begin{aligned}
\lim _{x \rightarrow a} \tan x & =\lim _{x \rightarrow a} \frac{\sin x}{\cos x}=\frac{\lim _{h \rightarrow 0} \sin (a+h)}{\lim _{h \rightarrow 0} \cos (a+h)} \\
& =\frac{\lim _{h \rightarrow 0}(\sin a \cos h+\cos a \sin h)}{\lim _{h \rightarrow 0}(\cos a \cos h-\sin a \sin h)} \\
& =\left(\frac{\sin a \times \cos 0+\cos a \times \sin 0}{\cos a \times \cos 0-\sin a \times \sin 0}\right)=\left(\frac{\sin a \times 1+\cos a \times 0}{\cos a \times 1-\sin a \times 0}\right) \\
& =\tan a
\end{aligned}
$$

Thus, $\tan x$ is continuous at $a$ for all $a \in R-\left\{(2 n+1) \frac{\pi}{2}: n \in I\right\}$.
Hence, $\tan x$ is continuous.

---

**THEOREM 10** *The logarithmic function is continuous.*

**PROOF** Let $f(x)=\log x$. Then, $\operatorname{dom}(f)=$ set of positive real numbers.
Let $a$ be any positive real number. Then,

$$
\begin{aligned}
\lim _{x \rightarrow a} f(x) & =\lim _{x \rightarrow a} \log x \\
& =\lim \left[\log \left(a \cdot \frac{x}{a}\right)\right]=\lim _{x \rightarrow a}\left[\log a+\log \frac{x}{a}\right] \\
& =\log a+\lim _{x \rightarrow a} \log \frac{x}{a}=\log a=f(a)\left[\because \lim _{x \rightarrow 0} \log \frac{x}{a}=\log 1=0\right] .
\end{aligned}
$$

Thus, $f(x)=\log x$ is continuous at $a \in R^{+}$.
Hence, $f(x)=\log x$ is continuous.

---

**THEOREM 11** *$\sin |x|$ is continuous.*

**PROOF** Let $f(x)=|x|$ and $g(x)=\sin x$. Then,

$(g \circ f)(x)=g\{f(x)\}=g(|x|)=\sin |x| .$

Now, $f$ and $g$ being continuous, it follows that their composite ( $g \circ f$ ) is continuous.
Hence, $\sin |x|$ is continuous.

---

## Solved Examples

### Example 1:

Let $f(x)=\left\{\begin{array}{ll}x & \text { if } x \geq 1 \\ x^{2} & \text { if } x<1 .\end{array}\right.$ Is $f$ a continuous function? Why?

#### Solution:

Let $a$ be any real number. Then, three possibilities arise.

**Case I: When $a>1$**
In this case, $f(a)=a$.
Also, $\quad \lim _{x \rightarrow a+} f(x)=\lim _{h \rightarrow 0} f(a+h)=\lim _{h \rightarrow 0}(a+h)=a$.

And, $\quad \lim _{x \rightarrow a-} f(x)=\lim _{h \rightarrow 0} f(a-h)=\lim _{h \rightarrow 0}(a-h)=a$
$[\because \quad a>1$ and $h$ is very small $\Rightarrow(a-h)>1]$.
$\therefore \lim _{x \rightarrow a+} f(x)=\lim _{a \rightarrow a-} f(x)=a=f(a)$.
So, $f(x)$ is continuous at each $a>1$.

**Case II: When $a<1$**
In this case, $f(a)=a^{2}$.

$$
\lim _{x \rightarrow a+} f(x)=\lim _{h \rightarrow 0} f(a+h)=\lim _{h \rightarrow 0}(a+h)^{2}=a^{2}
$$

$[\because \quad a<1$ and $h$ is very small $\Rightarrow(a+h)<1]$.
And, $\lim _{x \rightarrow a_{-}} f(x)=\lim _{h \rightarrow 0} f(a-h)=\lim _{h \rightarrow 0}(a-h)^{2}=a^{2}$
$[\because \quad a<1$ and $h$ is very small $\Rightarrow(a-h)<1]$.
$\therefore \lim _{x \rightarrow a+} f(x)=\lim _{x \rightarrow a-} f(x)=a^{2}=f(a)$.

**Case III: When $a=1$**
In this case, $f(1)=1$.

$$
\begin{aligned}
\lim _{x \rightarrow 1+} f(x) & =\lim _{h \rightarrow 0} f(1+h)=\lim _{h \rightarrow 0}(1+h)=1 \quad[\because(1+h)>1] . \\
\lim _{x \rightarrow 1-} f(x) & =\lim _{h \rightarrow 0} f(1-h)=\lim _{h \rightarrow 0}(1-h)^{2}=1[\because(1-h)<1] . \\
\therefore \quad \lim _{x \rightarrow 1+} f(x) & =\lim _{x \rightarrow 1-} f(x)=1 .
\end{aligned}
$$

So, $\lim _{x \rightarrow 1} f(x)=1=f(1)$.
So, $f$ is continuous at $a=1$.
Thus, from all the above three cases, it follows that $f(x)$ is continuous at $x=a$ for all $a \in R$.
Hence, $f(x)$ is continuous.

---

### Example 2:

Prove that $f(x)=|x|$ is a continuous function.

#### Solution:

Let $f(x)=|x|=\left\{\begin{array}{rll}x, & \text { if } & x \geq 0 \\ -x, & \text { if } & x<0 .\end{array}\right.$
Clearly, $\operatorname{dom}(f)=R$.
Let $a$ be any real number. Then, the following cases arise.

**Case I: When $a < 0$**
In this case, $f(a)=-a$.

$$
\lim _{x \rightarrow a+} f(x)=\lim _{h \rightarrow 0} f(a+h)=\lim _{h \rightarrow 0}\{-(a+h)\}=-a
$$

$[\because \quad a<0$ and $h$ is very small and positive $\Rightarrow a+h<0]$.
And, $\lim _{x \rightarrow a-} f(x)=\lim _{h \rightarrow 0} f(a-h)=\lim _{h \rightarrow 0}\{-(a-h)\}=-a$.
$[\because \quad a<0$ and $h$ is very small and positive $\Rightarrow a-h<0]$.
So, $\lim _{x \rightarrow a+} f(x)=\lim _{x \rightarrow a-} f(x)=-a=f(a)$.
Thus, $f(x)$ is continuous at each $a<0$.

**Case II: When $a>0$**
In this case, $f(a)=a$.

$$
\begin{aligned}
\lim _{x \rightarrow a+} f(x) & =\lim _{h \rightarrow 0} f(a+h)=\lim _{h \rightarrow 0}(a+h)=a \quad[\because(a+h)>0] . \\
\lim _{x \rightarrow a-} f(x) & =\lim _{h \rightarrow 0} f(a-h)=\lim _{h \rightarrow 0}(a-h)=a \quad[\because(a-h)>0] . \\
\therefore \lim _{x \rightarrow a+} f(x) & =\lim _{x \rightarrow a-} f(x)=f(a) .
\end{aligned}
$$

So, $f(x)$ is continuous at each $a>0$.

**Case III: When $a=0$**
Clearly, $f(0)=0$.

$$
\begin{aligned}
& \quad \lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0} h=0 . \\
& \lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)=\lim _{h \rightarrow 0}\{-(-h)\} \\
& \quad=\lim _{h \rightarrow 0} h=0 . \\
& \therefore \lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=0=f(0) .
\end{aligned}
$$

So, $f(x)$ is continuous at $x=0$.
Thus, from all the above cases, it follows that $f(x)=|x|$ is continuous at $a$ for all $a \in R$.
Hence, $f(x)=|x|$ is continuous.

---

### Example 3:

Discuss the continuity of the function $f(x)=\left\{\begin{array}{lll}2 x-1, & \text { if } & x<0 \\ 2 x+1, & \text { if } & x \geq 0 .\end{array}\right.$
[CBSE 2002]

#### Solution:

When $x<0$, we have $f(x)=2 x-1$, which being a polynomial function, is continuous at each point where $x<0$.
Also, when $x>0$, we have $f(x)=2 x+1$, which being a polynomial function, is continuous at each point where $x>0$.
Let us consider the point $x=0$.

$$
\begin{gathered}
f(0)=(2 \times 0+1)=1 \\
\lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0}(2 h+1)=1
\end{gathered}
$$

And, $\lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)=\lim _{h \rightarrow 0}[(2(-h)-1)]=-1$.
$\therefore \quad \lim _{x \rightarrow 0+} f(x) \neq \lim _{x \rightarrow 0-} f(x)$.
So, $\lim _{x \rightarrow 0} f(x)$ does not exist, and therefore $f(x)$ is not continuous at $x=0$.

Thus, the given function is continuous at each point except at $x=0$, where it is discontinuous.

---

### Example 4:

Discuss the continuity of the function $f(x)= \begin{cases}\frac{\sin x}{x}, & \text { if } x<0 \\ (x+1), & \text { if } x \geq 0 .\end{cases}$

#### Solution:

We know that $\sin x$ as well as the identity function $x$ is continuous.

So, the quotient function, $\frac{\sin x}{x}$ is continuous at each $x<0$.
Also, when $x>0$, we have $f(x)=(x+1)$, which being a polynomial function, is continuous.
Let us consider the point $x=0$.
Clearly, $\quad f(0)=(0+1)=1$.
We have $\quad f(0)=(0+1)=1$;

$$
\lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0}(h+1)=1
$$

and, $\quad \lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)$

$$
=\lim _{h \rightarrow 0} \frac{\sin (-h)}{-h}=\lim _{h \rightarrow 0}\left(\frac{-\sin h}{-h}\right)=\lim _{h \rightarrow 0} \frac{\sin h}{h}=1 .
$$

$\therefore \quad \lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=1$.
So, $\quad \lim _{x \rightarrow 0} f(x)=1=f(0)$.
Thus, $\quad f(x)$ is continuous at $x=0$ also.
Hence, $f(x)$ is continuous at all points.

---

### Example 5:

Discuss the continuity of the function $f(x)=\left\{\begin{array}{cl}\frac{x}{|x|}, & \text { if } x \neq 0 \\ 0, & \text { if } x=0 .\end{array}\right.$

#### Solution:

We know that the identity function $x$ is continuous and the modulus function $|x|$ is continuous.
So, the quotient function $\frac{x}{|x|}$ is continuous at each $x \neq 0$.
It has already been proved that $f(x)$ is discontinuous at $x=0$.
Hence, the given function is continuous at each point, except at $x=0$.

---

### Example 6:

Locate the point of discontinuity of the function $f(x)=\left\{\begin{aligned} \frac{x^{4}-16}{x-2}, & \text { if } x \neq 2 \\ 16, & \text { if } x=2 .\end{aligned}\right.$

#### Solution:

The function $f(x)=\frac{x^{4}-16}{x-2}$ being a rational function, is continuous at all points of its domain, i.e., for all real numbers except 2 .
Now, consider the given function at $x=2$.
We have $f(2)=16$.

$$
\begin{aligned}
\lim _{x \rightarrow 2} f(x) & =\lim _{h \rightarrow 0} f(2+h)=\lim _{h \rightarrow 0}\left\{\frac{(2+h)^{4}-16}{2+h-2}\right\}=\lim _{2+h \rightarrow 2}\left\{\frac{(2+h)^{4}-2^{4}}{(2+h)-2}\right\} \\
& =4 \times 2^{4-1}=32 \quad\left[\because \lim _{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}\right] .
\end{aligned}
$$

Thus, $\lim _{x \rightarrow 2+} f(x) \neq f(2)$, and therefore $\lim _{x \rightarrow 2} f(x) \neq f(2)$.
Hence, $\quad f(x)$ is discontinuous at $x=2$.

---

### Example 7:

Determine the value of $k$ so that the function

$$
f(x)=\left\{\begin{aligned}
k x^{2}, & \text { if } x \leq 2 ; \\
3, & \text { if } x>2
\end{aligned}\right. \text { is continuous. }
$$

[CBSE 1990C, '91]

#### Solution:

Since a polynomial function is continuous and a constant function is continuous, the given function is continuous for all $x<2$ and for all $x>2$.
So, consider the point $x=2$. We have $f(2)=4 k$.

$$
\lim _{x \rightarrow 2+} f(x)=\lim _{h \rightarrow 0} f(2+h)=\lim _{h \rightarrow 0} 3=3
$$

And, $\lim _{x \rightarrow 2-} f(x)=\lim _{h \rightarrow 0} f(2-h)=\lim _{h \rightarrow 0} k(2-h)^{2}=4 k$.
$\therefore \quad$ for continuity, we must have $4 k=3$ or $k=\frac{3}{4}$.

---

### Example 8:

Let $f(x)=\left\{\begin{aligned} 1, & \text { if } x \leq 3 \\ a x+b, & \text { if } 3<x<5 \\ 7, & \text { if } 5 \leq x .\end{aligned}\right.$
Find the values of $a$ and $b$ so that $f(x)$ is continuous.

#### Solution:

We know that a constant function is continuous, and a polynomial function is continuous.

So, the given function is continuous for all $x<3$; for all $x>5$ and for all $x$ lying in $] 3,5[$.
Now, consider the point $x=3$. We have $f(3)=1$.

$$
\lim _{x \rightarrow 3+} f(x)=\lim _{h \rightarrow 0} f(3+h)=\lim _{h \rightarrow 0}[a(3+h)+b]=(3 a+b) .
$$

And, $\lim _{x \rightarrow 3-} f(x)=\lim _{h \rightarrow 0}(3-h)=\lim _{h \rightarrow 0} 1=1$.
Since $f(x)$ is given to be continuous, it must be continuous at $x=3$ also.
So, we must have $f(3)=\lim _{x \rightarrow 3-} f(x)=\lim _{x \rightarrow 3+} f(x)$, i.e., $3 a+b=1 \ldots$ (i)

Again, consider the point $x=5$. We have $f(5)=7$.

$$
\lim _{x \rightarrow 5+} f(x)=\lim _{h \rightarrow 0} f(5+h)=\lim _{h \rightarrow 0} 7=7
$$

And, $\lim _{x \rightarrow 5-} f(x)=\lim _{h \rightarrow 0} f(5-h)=\lim _{h \rightarrow 0}[a(5-h)+b]=(5 a+b)$.
Now, by continuity of $f(x)$ at $x=5$, we have

$$
\begin{equation*}
f(5)=\lim _{x \rightarrow 5+} f(x)=\lim _{x \rightarrow 5-} f(x) \quad \text { or } \quad 5 a+b=7 \tag{ii}
\end{equation*}
$$

Solving (i) and (ii), we get $a=3$ and $b=-8$.

---

### Example 9:

Show that the function $f(x)=\sqrt{x^{4}+3}$ is continuous at each point.

#### Solution:

Let $g(x)=x^{4}+3$ and $h(y)=\sqrt{y}$.

Since every polynomial function is continuous at each point where $x=a$, it follows that $g(x)$ is continuous at $x=a$.
Clearly, $g(a)$ is positive. Moreover, $h[g(a)]=\sqrt{g(a)}=\lim _{y \rightarrow g(a)} \sqrt{y}$.
$\therefore \quad h(y)$ is continuous at $g(a)$.
Since the composite of continuous functions is continuous, it follows that $(h \circ g)(x)$ is continuous.
But, $\quad(h \circ g)(x)=h[g(x)]=h\left(x^{4}+3\right)=\sqrt{x^{4}+3}=f(x)$.
Hence, $f(x)$ is continuous.

---

### Example 10:

Show that the function $f(x)=|\sin x+\cos x|$ is continuous at $x=\pi$.

#### Solution:

Let $g(x)=\sin x+\cos x$ and $k(y)=|y|$.
We shall first show that $g$ is continuous at $x=\pi$ and $k$ is continuous at $y=g(\pi)$.
Now, $\quad \lim _{x \rightarrow \pi} g(x)=\lim _{x \rightarrow \pi}(\sin x+\cos x)=\sin \pi+\cos \pi=-1$.
Also, $\quad g(\pi)=(\sin \pi+\cos \pi)=-1 . \quad \therefore \quad \lim _{x \rightarrow \pi} g(x)=g(\pi)$.
So, $g$ is continuous at $x=\pi$. Now, $g(\pi)=-1$.
$\therefore \quad k[g(\pi)]=k(-1)=|-1|=1$.
Now, $\lim _{y \rightarrow(-1)+} k(y)=\lim _{y \rightarrow(-1)+}|y|=\lim _{h \rightarrow 0}|-1+h|=1$.
And, $\lim _{y \rightarrow(-1)_{-}} k(y)=\lim _{y \rightarrow(-1)_{-}}|y|=\lim _{h \rightarrow 0}|-1-h|=1$.
$\therefore \quad k[g(\pi)]=\lim _{y \rightarrow g(\pi)} k(y)$. This shows that $k$ is continuous at $g(\pi)$.
Consequently, ( $k \circ g$ ) is continuous at $x=\pi$.
But, $(k \circ g)(x)=k[g(x)]=k(\sin x+\cos x)=|\sin x+\cos x|=f(x)$.
Hence, $\quad f(x)$ is continuous at $x=\pi$.

---

## Exercise 9B

1.  Show that the function $f(x)=\left\{\begin{array}{ll}(7 x+5), & \text { when } x \geq 0 ; \\ (5-3 x), & \text { when } x<0\end{array}\right.$ is a continuous function.
2.  Show that the function $f(x)=\left\{\begin{array}{r}\sin x, \text { if } x<0 ; \\ x, \text { if } x \geq 0\end{array}\right.$ is continuous.
3.  Show that the function $f(x)=\left\{\begin{array}{r}\frac{x^{n}-1}{x-1}, \text { when } x \neq 1 ; \\ n, \text { when } x=1\end{array}\right.$ is continuous.
4.  Show that $\sec x$ is a continuous function.
5.  Show that $\cos |x|$ is a continuous function.
6.  Show that the function $f(x)=\left\{\begin{array}{r}\frac{\sin x}{x}, \text { when } x \neq 0 ; \\ 2, \text { when } x=0\end{array}\right.$ is continuous at each point except 0 .
7.  Discuss the continuity of $f(x)=[x]$.
8.  Show that $f(x)=\left\{\begin{array}{c}(2 x-1), \text { if } x<2 ; \\ \frac{3 x}{2}, \text { if } x \geq 2\end{array}\right.$ is continuous.
9.  Show that $f(x)=\left\{\begin{array}{ll}x, & \text { if } x \neq 0 ; \\ 1, & \text { if } x=0\end{array}\right.$ is continuous at each point except 0 .
10. Locate the point of discontinuity of the function

    $$
    f(x)=\left\{\begin{aligned}
    \left(x^{3}-x^{2}+2 x-2\right), & \text { if } x \neq 1 \\
    4, & \text { if } x=1
    \end{aligned}\right.
    $$

11. Discuss the continuity of the function $f(x)=|x|+|x-1|$ in the interval $[-1,2]$.

---

## Answers (Exercise 9B)

7.  discontinuous at $x=n$, where $n$ is an integer
10. discontinuous at $x=1$
11. continuous

---

## Hints to Some Selected Questions (Exercise 9B)

1.  Since a polynomial function is continuous, the given function is continuous at each $x>0$ as well as at each $x<0$. Test its continuity at $x=0$.
2.  Let $a \in R$.
    **Case I: When $a>0$**
    then, $\lim _{x \rightarrow a+} f(x)=\lim _{x \rightarrow a-} f(x)=f(a)=a$.
    **Case II: When $a<0$**
    then, $\lim _{x \rightarrow a+} f(x)=\lim _{x \rightarrow a-} f(x)=f(a)=\sin a$.
    **Case III: When $a=0$**
    then, $\lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=f(0)=0$.
7.  $f(x)$ is discontinuous at each integral value of $x$.
8.  Take three cases: (i) $a>2$ (ii) $a<2$ (iii) $a=2$.
10. Test at $x=1$.
11. The given function may be expressed as

    $$
    f(x)=\left\{\begin{array}{r}
    (1-2 x), \text { when }-1 \leq x<0 \\
    1, \text { when } \quad 0 \leq x \leq 1 \\
    (2 x-1), \text { when } \quad 1<x \leq 2
    \end{array}\right.
    $$

    Since a polynomial function as well as a constant function is continuous, it follows that $f(x)$ is continuous when $-1<x<0 ; 0<x<1$ and $1<x<2$.
    So, test the continuity at $-1,0,1$ and 2 .
    At $x=-1, \quad \lim _{x \rightarrow(-1)+} f(x)=f(-1)$, so it is continuous at $x=-1$.

    At $x=0, \quad \lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=f(0)=1$, so it is continuous at $x=0$.
    At $x=1, \quad \lim _{x \rightarrow 1+} f(x)=\lim _{x \rightarrow 1-} f(x)=f(1)=1$.
    At $\quad x=2, \quad \lim _{x \rightarrow 2-} f(x)=f(2)=3$, so it is continuous at $x=2$.

---
