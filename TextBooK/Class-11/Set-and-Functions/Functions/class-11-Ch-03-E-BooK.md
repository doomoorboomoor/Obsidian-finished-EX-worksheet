## Operations on Functions

### (i) Sum of Two Real Functions

Let $f: D_{1} \rightarrow R$ and $g: D_{2} \rightarrow R$, where $D_{1} \subseteq R$ and $D_{2} \subseteq R$. Then, the **sum** function $(f+g)$ is defined as:

$$
(f+g):\left(D_{1} \cap D_{2}\right) \rightarrow R:(f+g)(x)=f(x)+g(x) \text { for all } x \in\left(D_{1} \cap D_{2}\right) .
$$

### (ii) Difference of Two Real Functions

Let $f: D_{1} \rightarrow R$ and $g: D_{2} \rightarrow R$, where $D_{1} \subseteq R$ and $D_{2} \subseteq R$. Then, the **difference** function $(f-g)$ is defined as:

$$
(f-g):\left(D_{1} \cap D_{2}\right) \rightarrow R:(f-g)(x)=f(x)-g(x) \text { for all } x \in\left(D_{1} \cap D_{2}\right) .
$$

### (iii) Multiplication of Two Real Functions

Let $f: D_{1} \rightarrow R$ and $g: D_{2} \rightarrow R$, where $D_{1} \subseteq R$ and $D_{2} \subseteq R$. Then, the **product** function $(fg)$ is defined as:

$$
(f g):\left(D_{1} \cap D_{2}\right) \rightarrow R:(f g)(x)=f(x) \cdot g(x) \text { for all } x \in\left(D_{1} \cap D_{2}\right) .
$$

*This is known as pointwise multiplication of functions.*

### (iv) Quotient of Two Real Functions

Let $f: D_{1} \rightarrow R$ and $g: D_{2} \rightarrow R$, where $D_{1} \subseteq R$ and $D_{2} \subseteq R$.
Let $D=\left(D_{1} \cap D_{2}\right)-\{x: g(x)=0\}$. Then, the **quotient** function $\left(\frac{f}{g}\right)$ is defined as:

$$
\left(\frac{f}{g}\right): D \rightarrow R:\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)} \text { for all } x \in D .
$$

### (v) Reciprocal of a Function

Let $f: D_{1} \rightarrow R$ and let $D=D_{1}-\{x: f(x)=0\}$. Then, the **reciprocal** of $f$ is the function $\frac{1}{f}$, defined by:

$$
\frac{1}{f}: D \rightarrow R:\left(\frac{1}{f}\right)(x)=\frac{1}{f(x)} \text { for all } x \in D
$$

### (vi) Scalar Multiple of a Function

Let $f: D \rightarrow R$ and let $\alpha$ be a scalar (a real number). Then, the **scalar multiple** $(\alpha f)$ is defined as:

$$
(\alpha f): D \rightarrow R:(\alpha f)(x)=\alpha \cdot f(x) \text { for all } x \in D .
$$

---

## Solved Examples

### Example: 1

Let $f: R \rightarrow R: f(x)=x^{2}$ and $g: R \rightarrow R: g(x)=2 x+1$.
Find (i) $(f+g)(x)$ (ii) $(f-g)(x)$ (iii) $(f g)(x)$ (iv) $\left(\frac{f}{g}\right)(x)$

#### Solution:

Here, $\operatorname{dom}(f)=R$ and $\operatorname{dom}(g)=R$.

$$
\therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)=(R \cap R)=R .
$$

(i) $(f+g): R \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=x^{2}+(2 x+1)=(x+1)^{2} .
$$

(ii) $(f-g): R \rightarrow R$ is given by:
$$
(f-g)(x)=f(x)-g(x)=x^{2}-(2 x+1)=\left(x^{2}-2 x-1\right) .
$$

(iii) $(f g): R \rightarrow R$ is given by:
$$
(f g)(x)=f(x) \cdot g(x)=x^{2} \cdot(2 x+1)=\left(2 x^{3}+x^{2}\right).
$$

(iv) The set where $g(x)=0$ is $\{x: g(x)=0\}=\{x: 2 x+1=0\}=\left\{\frac{-1}{2}\right\}$.
$$
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right)=R \cap R-\left\{\frac{-1}{2}\right\}=R-\left\{\frac{-1}{2}\right\}.
$$
The function $\frac{f}{g}: R-\left\{\frac{-1}{2}\right\} \rightarrow R$ is given by:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{x^{2}}{2 x+1}, x \neq \frac{-1}{2} .
$$

---

### Example: 2

Let $f(x)=\sqrt{x}$ and $g(x)=x$ be two functions defined over the set of non-negative real numbers. Find:
(i) $(f+g)(x)$ (ii) $(f-g)(x)$ (iii) $(f g)(x)$ (iv) $\frac{f}{g}(x)$

#### Solution:

Here $f:[0, \infty) \rightarrow R: f(x)=\sqrt{x}$ and $g:[0, \infty) \rightarrow R: g(x)=x$.
$\therefore \quad \operatorname{dom}(f)=[0, \infty)$ and $\operatorname{dom}(g)=[0, \infty)$.
So, $\operatorname{dom}(f) \cap \operatorname{dom}(g)=[0, \infty) \cap[0, \infty)=[0, \infty)$.

(i) $(f+g):[0, \infty) \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=(\sqrt{x}+x).
$$

(ii) $(f-g):[0, \infty) \rightarrow R$ is given by:
$$
(f-g)(x)=f(x)-g(x)=(\sqrt{x}-x).
$$

(iii) $(f g):[0, \infty) \rightarrow R$ is given by:
$$
(f g)(x)=f(x) \cdot g(x)=(\sqrt{x} \times x)=x^{3 / 2}.
$$

(iv) The set where $g(x)=0$ is $\{x: g(x)=0\}=\{0\}$.
$$
\begin{aligned}
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right) & =\operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\} \\
& =[0, \infty) \cap[0, \infty)-\{0\}=(0, \infty) .
\end{aligned}
$$
So, $\frac{f}{g}:(0, \infty) \rightarrow R$ is given by:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{\sqrt{x}}{x}=\frac{1}{\sqrt{x}}, x \neq 0 .
$$

---

### Example: 3

Let $f$ and $g$ be real functions, defined by $f(x)=\frac{1}{(x+4)}$ and $g(x)=(x+4)^{3}$.
Find (i) $(f+g)(x)$ (ii) $(f-g)(x)$ (iii) $(f g)(x)$ (iv) $\left(\frac{f}{g}\right)(x)$ (v) $\left(\frac{1}{f}\right)(x)$

#### Solution:

Clearly, $f(x)=\frac{1}{(x+4)}$ is defined for all real values of $x$ except that at which $x+4=0$, i.e., $x=-4$.
$\therefore \quad \operatorname{dom}(f)=R-\{-4\}$.

And, $g(x)=(x+4)^{3}$ is defined for all $x \in R$. So, $\operatorname{dom}(g)=R$.
$\therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)=R-\{-4\} \cap R=R-\{-4\}$.

(i) $(f+g): R-\{-4\} \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=\frac{1}{(x+4)}+(x+4)^{3}=\frac{1+(x+4)^{4}}{(x+4)}
$$

(ii) $(f-g): R-\{-4\} \rightarrow R$ is given by:
$$
(f-g)(x)=f(x)-g(x)=\frac{1}{(x+4)}-(x+4)^{3}=\frac{1-(x+4)^{4}}{(x+4)}
$$

(iii) $(f g): R-\{-4\} \rightarrow R$ is given by:
$$
(f g)(x)=f(x) \cdot g(x)=\frac{1}{(x+4)} \times(x+4)^{3}=(x+4)^{2}
$$

(iv) The set where $g(x)=0$ is $\{x: g(x)=0\}=\left\{x:(x+4)^{3}=0\right\}=\{x: x+4=0\}=\{-4\}$.
$$
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right)=\operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\}=R-\{-4\} .
$$
$\left(\frac{f}{g}\right): R-\{-4\} \rightarrow R$ is given by:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{\frac{1}{(x+4)}}{(x+4)^{3}}=\frac{1}{(x+4)^{4}}, x \neq-4
$$

(v) Clearly, $f(x) \neq 0$ for any $x \in R-\{-4\}$.
$\therefore \quad \frac{1}{f}: R-\{-4\} \rightarrow R$ is given by:
$$
\left(\frac{1}{f}\right)(x)=\frac{1}{f(x)}=\frac{1}{\frac{1}{(x+4)}}=(x+4)
$$

---

### Example: 4

Let $f$ and $g$ be real functions defined by $f(x)=\sqrt{x-1}$ and $g(x)=\sqrt{x+1}$.
Find (i) $(f+g)(x)$ (ii) $(f-g)(x)$ (iii) $(f g)(x)$ (iv) $\left(\frac{f}{g}\right)(x)$.

#### Solution:

Clearly, $f(x)=\sqrt{x-1}$ is defined for all real values of $x$ for which $x-1 \geq 0$, i.e., $x \geq 1$. So, $\operatorname{dom}(f)=[1, \infty)$.
Also, $g(x)=\sqrt{x+1}$ is defined for all real values of $x$ for which $x+1 \geq 0$, i.e., $x \geq-1$. So, $\operatorname{dom}(g)=[-1, \infty)$.

$$
\therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)=[1, \infty) \cap[-1, \infty)=[1, \infty) .
$$

(i) $(f+g):[1, \infty) \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=(\sqrt{x-1}+\sqrt{x+1})
$$

(ii) $(f-g):[1, \infty) \rightarrow R$ is given by:
$$
(f-g)(x)=f(x)-g(x)=(\sqrt{x-1}-\sqrt{x+1}) .
$$

(iii) $(f g):[1, \infty) \rightarrow R$ is given by:
$$
(f g)(x)=f(x) \cdot g(x)=\sqrt{x-1} \times \sqrt{x+1}=\sqrt{x^{2}-1}
$$

(iv) The set where $g(x)=0$ is $\{x: g(x)=0\}=\{x: \sqrt{x+1}=0\}=\{x: x+1=0\}=\{-1\}$.
$$
\begin{aligned}
& \therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\} \\
& \quad=[1, \infty) \cap[-1, \infty)-\{-1\}=[1, \infty) .
\end{aligned}
$$
$\therefore \quad \frac{f}{g}:[1, \infty) \rightarrow R$ is given by:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{\sqrt{x-1}}{\sqrt{x+1}} .
$$

---

### Example: 5

Let $f$ and $g$ be real functions, defined by $f(x)=\sqrt{x+2}$ and $g(x)=\sqrt{4-x^{2}}$.
Find (i) $(f+g)(x)$ (ii) $(f-g)(x)$ (iii) $(f g)(x)$ (iv) $(f f)(x)$ (v) $(g g)(x)$ (vi) $\left(\frac{f}{g}\right)(x)$.

#### Solution:

Clearly, $f(x)=\sqrt{x+2}$ is defined for all $x \in R$ such that $x+2 \geq 0$, i.e., $x \geq-2$.
$\therefore \quad \operatorname{dom}(f)=[-2, \infty)$.

Again, $g(x)=\sqrt{4-x^{2}}$ is defined for all $x \in R$ such that $4-x^{2} \geq 0$.
But, $4-x^{2} \geq 0 \Rightarrow x^{2}-4 \leq 0 \Rightarrow (x+2)(x-2) \leq 0 \Rightarrow x \in[-2,2]$.
$\therefore \quad \operatorname{dom}(g)=[-2,2]$.
$\therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)=[-2, \infty) \cap[-2,2]=[-2,2]$.

(i) $(f+g):[-2,2] \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=\sqrt{x+2}+\sqrt{4-x^{2}}
$$

(ii) $(f-g):[-2,2] \rightarrow R$ is given by:
$$
(f-g)(x)=f(x)-g(x)=\sqrt{x+2}-\sqrt{4-x^{2}}
$$

(iii) $(f g):[-2,2] \rightarrow R$ is given by:
$$
(f g)(x)=f(x) \cdot g(x)=(\sqrt{x+2})\left(\sqrt{4-x^{2}}\right)=\sqrt{(x+2)^{2}(2-x)}=(x+2) \sqrt{(2-x)}
$$

(iv) $(f f):[-2,2] \rightarrow R$ is given by:
$$
(f f)(x)=f(x) \cdot f(x)=(\sqrt{x+2})(\sqrt{x+2})=(x+2) .
$$

(v) $(g g):[-2,2] \rightarrow R$ is given by:
$$
(g g)(x)=g(x) \cdot g(x)=\left(\sqrt{4-x^{2}}\right)\left(\sqrt{4-x^{2}}\right)=\left(4-x^{2}\right) .
$$

(vi) The set where $g(x)=0$ is $\{x: g(x)=0\}=\left\{x: 4-x^{2}=0\right]=\{x:(2-x)(2+x)=0\}=\{-2,2\}$.
$$
\begin{aligned}
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right) & =\operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\} \\
& =[-2,2]-\{-2,2\}=(-2,2) .
\end{aligned}
$$
$\therefore \quad \frac{f}{g}:(-2,2) \rightarrow R$ is given by:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{\sqrt{x+2}}{\sqrt{4-x^{2}}}=\frac{\sqrt{2+x}}{(\sqrt{2+x})(\sqrt{2-x})}=\frac{1}{(\sqrt{2-x})} .
$$

---

### Example: 6

Let $f$ be the exponential function and $g$ be the logarithmic function. Then, find:
(i) $(f+g)(1)$ (ii) $(f g)(1)$ (iii) $(4 f)(1)$ (iv) $(3 g)(1)$

#### Solution:

Let $f: R \rightarrow R: f(x)=e^{x}$ and $g: R^{+} \rightarrow R: g(x)=\log _{e} x$.
Then, $\operatorname{dom}(f) \cap \operatorname{dom}(g)=R \cap R^{+}=R^{+}$.

(i) $(f+g): R^{+} \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=\left(e^{x}+\log _{e} x\right) .
$$
$$
\therefore \quad (f+g)(1)=\left(e^{1}+\log _{e} 1\right)=(e+0)=e .
$$

(ii) $(f g): R^{+} \rightarrow R$ is given by:
$$
(f g)(x) =f(x) \cdot g(x)=e^{x}\left(\log _{e} x\right)
$$
$$
\therefore \quad (f g)(1)=e^{1}\left(\log _{e} 1\right)=(e \times 0)=0
$$

(iii) $(4 f): R^{+} \rightarrow R$ is given by:
$$
(4 f)(x) =4 \times f(x)=4 e^{x}
$$
$$
\therefore \quad(4 f)(1) =\left(4 \times e^{1}\right)=4 e
$$

(iv) $(3 g): R^{+} \rightarrow R$ is given by:
$$
(3 g)(x)=3 \times g(x)=3 \times\left(\log _{e} x\right)
$$
$$
\therefore \quad (3 g)(1)=3 \times g(1)=3 \times\left(\log _{e} 1\right)=(3 \times 0)=0 .
$$

---

### Example: 7

If $f(x)=\log _{e}(1-x)$ and $g(x)=[x]$ then find:
(i) $(f+g)(x)$ (ii) $(f g)(x)$ (iii) $\left(\frac{f}{g}\right)(x)$ (iv) $\left(\frac{g}{f}\right)(x)$.
Also find $(f+g)(-1)$, $(f g)(0)$, $\left(\frac{f}{g}\right)(-1)$, $\left(\frac{g}{f}\right)\left(\frac{1}{2}\right)$.

#### Solution:

Clearly, $\log _{e}(1-x)$ is defined only when $1-x>0$, i.e., $x<1$.
$\therefore \quad \operatorname{dom}(f)=(-\infty, 1)$.
Also, $\operatorname{dom}(g)=R$.
$\therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)=(-\infty, 1) \cap R=(-\infty, 1)$.

(i) $(f+g):(-\infty, 1) \rightarrow R$ is given by:
$$
(f+g)(x)=f(x)+g(x)=\log _{e}(1-x)+[x]
$$

(ii) $(f g):(-\infty, 1) \rightarrow R$ is given by:
$$
(f g)(x)=f(x) \times g(x)=\left\{\log _{e}(1-x)\right\} \times[x] .
$$

(iii) The set where $g(x)=0$ is $\{x: g(x)=0\}=\{x:[x]=0\}=[0,1)$.
$$
\begin{aligned}
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right) & =\operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\} \\
& =(-\infty, 1) \cap R-[0,1)=(-\infty, 0) .
\end{aligned}
$$
$\therefore \quad \frac{f}{g}:(-\infty, 0) \rightarrow R$ is given by:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{\log _{e}(1-x)}{[x]} .
$$

(iv) The set where $f(x)=0$ is $\{x: f(x)=0\}=\left\{x: \log _{e}(1-x)=0\right\}=\{0\}$.
$$
\begin{aligned}
\therefore \quad \operatorname{dom}\left(\frac{g}{f}\right) & =\operatorname{dom}(g) \cap \operatorname{dom}(f)-\{x: f(x)=0\} \\
& =R \cap(-\infty, 1)-\{0\}=(-\infty, 0) \cup(0,1) .
\end{aligned}
$$
$\therefore \quad \frac{g}{f}:(-\infty, 0) \cup(0,1) \rightarrow R$ is given by:
$$
\left(\frac{g}{f}\right)(x)=\frac{g(x)}{f(x)}=\frac{[x]}{\log _{e}(1-x)} .
$$

Now, we have:
$$
\begin{aligned}
& (f+g)(-1)=f(-1)+g(-1)=[-1]+\log _{e}(1+1)=\left(\log _{e} 2\right)-1 . \\
& (f g)(0)=f(0) \times g(0)=\log _{e}(1-0) \times[0]=\left(\log _{e} 1 \times 0\right)=(0 \times 0)=0 . \\
& \left(\frac{f}{g}\right)(-1)=\frac{f(-1)}{g(-1)}=\frac{\log _{e}(1+1)}{[-1]}=\frac{\log _{e} 2}{-1} = -\log_e 2. \\
& \left(\frac{g}{f}\right)\left(\frac{1}{2}\right)=\frac{g\left(\frac{1}{2}\right)}{f\left(\frac{1}{2}\right)}=\frac{\left[\frac{1}{2}\right]}{\log _{e}\left(1-\frac{1}{2}\right)}=\frac{0}{\log _{e}\left(\frac{1}{2}\right)}=0 .
\end{aligned}
$$

---

### Example: 8

Find the sum and the difference of the **identity function** and the **modulus function**.

#### Solution:

Let $f: R \rightarrow R: f(x)=x$ be the **identity function**.
And, let $g: R \rightarrow R: g(x)=|x|$ be the **modulus function**.
Then, $\operatorname{dom}(f)=R$ and $\operatorname{dom}(g)=R$.
$\therefore \quad \operatorname{dom}(f) \cap \operatorname{dom}(g)=R \cap R=R$.

(i) **Sum**: $\operatorname{dom}(f+g)=\operatorname{dom}(f) \cap \operatorname{dom}(g)=R$.
Now, $(f+g): R \rightarrow R$ is given by:
$$
\begin{aligned}
(f+g)(x) & =f(x)+g(x) \\
& =x+|x|=x+\left\{\begin{array}{l}
x, \text { when } x \geq 0 \\
-x, \text { when } x<0
\end{array}\right. \\
& =\left\{\begin{array}{l}
x+x, \text { when } x \geq 0 \\
x-x, \text { when } x<0
\end{array}=\left\{\begin{array}{l}
2 x, \text { when } x \geq 0 \\
0, \text { when } x<0
\end{array}\right.\right.
\end{aligned}
$$
Hence, $(f+g)(x)=\left\{\begin{array}{l}2 x, \text { when } x \geq 0 \\ 0, \text { when } x<0 .\end{array}\right.$

(ii) **Difference**: $\operatorname{dom}(f-g)=\operatorname{dom}(f) \cap \operatorname{dom}(g)=R$.
$$
\begin{aligned}
\therefore \quad(f-g)(x) & =f(x)-g(x) \\
& =x-|x|=x-\left\{\begin{array}{l}
x, \text { when } x \geq 0 \\
-x, \text { when } x<0
\end{array}\right.
\end{aligned}
$$
$$
\begin{aligned}
& =\left\{\begin{array}{l}
x-x, \text { when } x \geq 0 \\
x+x, \text { when } x<0
\end{array}=\left\{\begin{array}{l}
0, \text { when } x \geq 0 \\
2 x, \text { when } x<0
\end{array}\right.\right. \\
\therefore \quad(f-g)(x) & =\left\{\begin{array}{l}
0, \text { when } x \geq 0 \\
2 x, \text { when } x<0
\end{array}\right.
\end{aligned}
$$

---

### Example: 9

Find the sum and the difference of the **identity function** and the **reciprocal function**.

#### Solution:

Let $f: R \rightarrow R: f(x)=x$ and $g: R-\{0\} \rightarrow R: g(x)=\frac{1}{x}$ be the identity function and the reciprocal function respectively.
Then, $\operatorname{dom}(f) \cap \operatorname{dom}(g)=R \cap (R-\{0\})=R-\{0\}$.

**Sum**:
$$
(f+g): R-\{0\} \rightarrow R:(f+g)(x)=f(x)+g(x)=\left(x+\frac{1}{x}\right) .
$$
Hence, $(f+g)(x)=\left(x+\frac{1}{x}\right)$ for all $x \in R-\{0\}$.

**Difference**:
$$
(f-g): R-\{0\} \rightarrow R:(f-g)(x)=f(x)-g(x)=\left(x-\frac{1}{x}\right) .
$$
Hence, $(f-g)(x)=\left(x-\frac{1}{x}\right)$ for all $x \in R-\{0\}$.

---

### Example: 10

Find the product of the **identity function** by the **modulus function**.

#### Solution:

Let $f: R \rightarrow R: f(x)=x$ and $g: R \rightarrow R: g(x)=|x|$ be the identity function and the modulus function respectively.
Then, $\operatorname{dom}(f g)=\operatorname{dom}(f) \cap \operatorname{dom}(g)=R \cap R=R$.
$\therefore \quad(f g): R \rightarrow R:(f g)(x)=f(x) \cdot g(x)$.
Now,
$$
(f g)(x)=f(x) \cdot g(x)=x \cdot|x|
$$
$$
=x \cdot\left\{\begin{array}{l}
x, \text { when } x \geq 0 \\
-x, \text { when } x<0
\end{array}=\left\{\begin{array}{l}
x^{2}, \text { when } x \geq 0 \\
-x^{2}, \text { when } x<0
\end{array}\right.\right.
$$
Hence, $(f g)(x)=\left\{\begin{array}{l}x^{2}, \text { when } x \geq 0 \\ -x^{2}, \text { when } x<0 .\end{array}\right.$

---

### Example: 11

Find the product of the **identity function** by the **reciprocal function**.

#### Solution:

Let $f: R \rightarrow R: f(x)=x$ and $g: R-\{0\} \rightarrow R: g(x)=\frac{1}{x}$ be the identity function and the reciprocal function respectively.
Then, $\operatorname{dom}(f g)=\operatorname{dom}(f) \cap \operatorname{dom}(g)=R \cap (R-\{0\})=R-\{0\}$.
$$
\therefore \quad(f g): R-\{0\} \rightarrow R:(f g)(x)=f(x) \cdot g(x)=\left(x \times \frac{1}{x}\right)=1 .
$$
Hence, $(f g)(x)=1$ for all $x \in R-\{0\}$.

---

### Example: 12

Find the quotient of the **identity function** by the **modulus function**.

#### Solution:

Let $f: R \rightarrow R: f(x)=x$ and $g: R \rightarrow R: g(x)=|x|$ be the identity function and the modulus function respectively.
Now, $\operatorname{dom}\left(\frac{f}{g}\right)=\operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\}$.
The set where $g(x)=0$ is $\{x: g(x)=0\}=\{x:|x|=0\}=\{0\}$.
$$
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right)=(R \cap R)-\{0\}=R-\{0\}.
$$
So, $\frac{f}{g}: R-\{0\} \rightarrow R$ is defined as:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{x}{|x|}=\left\{\begin{array}{l}1, \text { when } x>0 \\ -1, \text { when } x<0 .\end{array}\right.
$$
Hence, $\left(\frac{f}{g}\right)(x)=\left\{\begin{array}{l}1, \text { when } x>0 \\ -1, \text { when } x<0 .\end{array}\right.$

---

### Example: 13

Find the quotient of the **identity function** by the **reciprocal function**.

#### Solution:

Let $f: R \rightarrow R: f(x)=x$ and $g: R-\{0\} \rightarrow R: g(x)=\frac{1}{x}$ be the identity function and the reciprocal function respectively.
Now, $\operatorname{dom}\left(\frac{f}{g}\right)=\operatorname{dom}(f) \cap \operatorname{dom}(g)-\{x: g(x)=0\}$.
The set where $g(x)=0$ is $\{x: g(x)=0\}=\left\{x: \frac{1}{x}=0\right\}=\phi$.
$$
\therefore \quad \operatorname{dom}\left(\frac{f}{g}\right)=[R \cap (R-\{0\})]-\phi=R-\{0\}.
$$
So, $\frac{f}{g}: R-\{0\} \rightarrow R$ is defined as:
$$
\left(\frac{f}{g}\right)(x)=\frac{f(x)}{g(x)}=\frac{x}{\frac{1}{x}}=x^{2}.
$$
Hence, $\left(\frac{f}{g}\right)(x)=x^{2}$ for all $x \in R-\{0\}$.

---

