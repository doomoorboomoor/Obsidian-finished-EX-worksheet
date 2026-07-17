## Real Functions

A function which has either $R$ or one of its subsets as its range is called a **real-valued function**.

A function $f: X \rightarrow Y$ is called a **real function**, if $x \subseteq R$ and $y \subseteq R$. In general, real functions are described as general expressions or formulae, without mentioning their domains and co-domains. Following are some examples of real functions.

---

## Solved Examples

### Example 1
If $f(x)=3 x^{3}-5 x^{2}+10$, find $f(x-1)$.

#### Solution
We have, $f(x)=3 x^{3}-5 x^{2}+10$.

Replacing $x$ by $(x-1)$, we get
$$
\begin{aligned}
f(x-1) & =3(x-1)^{3}-5(x-1)^{2}+10 \\
& =3\left\{x^{3}-1-3 x(x-1)\right\}-5\left(x^{2}-2 x+1\right)+10 \\
& =3\left(x^{3}-3 x^{2}+3 x-1\right)-5\left(x^{2}-2 x+1\right)+10 \\
& =3 x^{3}-14 x^{2}+19 x+2 .
\end{aligned}
$$
$\therefore \quad f(x-1) =3 x^{3}-14 x^{2}+19 x+2$.

---

### Example 2
If $f(x)=x+\frac{1}{x}$, show that $\{f(x)\}^{3}=f\left(x^{3}\right)+3 f\left(\frac{1}{x}\right)$.

#### Solution
We have, $f(x)=x+\frac{1}{x}$.

On cubing both sides, we get
$$
\begin{aligned}
\{f(x)\}^{3} & =x^{3}+\frac{1}{x^{3}}+3 \times x \times \frac{1}{x} \times\left(x+\frac{1}{x}\right) \\
& =\left(x^{3}+\frac{1}{x^{3}}\right)+3\left(\frac{1}{x}+x\right) \\
& =f\left(x^{3}\right)+3 f\left(\frac{1}{x}\right) \quad\left[\because f\left(\frac{1}{x}\right)=\left\{\frac{1}{x}+\frac{1}{\frac{1}{x}}\right\}=\left(\frac{1}{x}+x\right)\right] .
\end{aligned}
$$
Hence, $\{f(x)\}^{3}=f\left(x^{3}\right)+3 f\left(\frac{1}{x}\right)$.

---

### Example 3
If $f(x)=\frac{x-1}{x+1}$, $x \neq-1$ then show that $f\{f(x)\}=\frac{-1}{x}$, where $x \neq 0$.

#### Solution
We have, $f(x)=\frac{x-1}{x+1}$, where $x \neq-1$.

$$
\begin{aligned}
\therefore \quad f\{f(x)\} & =f\left(\frac{x-1}{x+1}\right)=\frac{\left\{\frac{x-1}{x+1}-1\right\}}{\left\{\frac{x-1}{x+1}+1\right\}} \\
& =\frac{\{(x-1)-(x+1)\}}{(x+1)} \times \frac{(x+1)}{\{(x-1)+(x+1)\}}=\frac{-2}{2 x}=\frac{-1}{x}
\end{aligned}
$$
Hence, $f\{f(x)\}=\frac{-1}{x}$, where $x \neq 0$.

---

### Example 4
If $y=f(x)=\frac{a x-b}{b x-a}$ and $a^{2} \neq b^{2}$ then prove that $x=f(y)$.

#### Solution
We have, $y=f(x)=\frac{a x-b}{b x-a}$.

$$
\begin{aligned}
\therefore \quad f(y) & =f\{f(x)\}=f\left(\frac{a x-b}{a x-a}\right)=\frac{\left\{a\left(\frac{a x-b}{b x-a}\right)-b\right\}}{\left\{b\left(\frac{a x-b}{b x-a}\right)-a\right\}} \\
& =\frac{\left\{\left(a^{2} x-a b\right)-\left(b^{2} x-a b\right)\right\}}{(b x-a)} \times \frac{(b x-a)}{\left\{\left(a b x-b^{2}\right)-\left(a b x-a^{2}\right)\right\}} \\
& =\frac{\left(a^{2} x-b^{2} x\right)}{\left(a^{2}-b^{2}\right)}=\frac{\left(a^{2}-b^{2}\right) x}{\left(a^{2}-b^{2}\right)}=x .
\end{aligned}
$$
Hence, $x=f(y)$.

---

### Example 5
If $f(x)=\frac{x-1}{x+1}$ then prove that $f(2 x)=\frac{3 f(x)+1}{f(x)+3}$.

#### Solution
We have, $f(x)=\frac{x-1}{x+1}$.

$$
\begin{aligned}
\therefore \quad \frac{3 f(x)+1}{f(x)+3} & =\frac{3\left(\frac{x-1}{x+1}\right)+1}{\frac{(x-1)}{(x+1)}+3} \\
& =\frac{(3 x-3)+(x+1)}{(x+1)} \times \frac{(x+1)}{(x-1)+(3 x+3)}=\frac{2 x-1}{2 x+1}=f(2 x) .
\end{aligned}
$$
Hence, $f(2 x)=\frac{3 f(x)+1}{f(x)+3}$.

---

### Example 6
Let the functions $f$ and $g$ be defined by $f(x)=(x-3)$ and
$$
g(x)= \begin{cases}\frac{x^{2}-9}{x+3}, & \text { when } x \neq-3 \\ k, & \text { when } x=-3\end{cases}
$$
Find the value of $k$ such that $f(x)=g(x)$ for all $x \in R$.

#### Solution
We have, $f(x)=g(x)$ for all $x \in R$.
$$
\begin{array}{ll}
\therefore & f(-3)=g(-3) \\
\Rightarrow & (-3-3)=k \quad[\because f(-3)=(-3-3) \text { and } g(-3)=k] \\
\Rightarrow & k=-6 .
\end{array}
$$
Hence, $k=-6$.

---

### Example 7
If $a f(x)+b f\left(\frac{1}{x}\right)=\frac{1}{x}$, where $a \neq b$ and $x \neq 0$, find $f(x)$.

#### Solution
We have, $a f(x)+b f\left(\frac{1}{x}\right)=\frac{1}{x}$. (i)

Replacing $x$ by $\frac{1}{x}$ in (i), we get
$$
a f\left(\frac{1}{x}\right)+b f(x)=x \tag{ii}
$$
Adding (i) and (ii), we get
$$
\begin{array}{ll} 
& a\left\{f(x)+f\left(\frac{1}{x}\right)\right\}+b\left\{f(x)+f\left(\frac{1}{x}\right)\right\}=\left(x+\frac{1}{x}\right) \\
\Rightarrow & (a+b)\left\{f(x)+f\left(\frac{1}{x}\right)\right\}=\left(x+\frac{1}{x}\right) \\
\Rightarrow & f(x)+f\left(\frac{1}{x}\right)=\frac{1}{(a+b)}\left(x+\frac{1}{x}\right) \tag{iii}
\end{array}
$$
On subtracting (ii) from (i), we get
$$
\begin{array}{ll} 
& a\left\{f(x)-f\left(\frac{1}{x}\right)\right\}-b\left\{f(x)-f\left(\frac{1}{x}\right)\right\}=\left(\frac{1}{x}-x\right) \\
\Rightarrow & (a-b)\left\{f(x)-f\left(\frac{1}{x}\right)\right\}=\left(\frac{1}{x}-x\right) \\
\Rightarrow & \left\{f(x)-f\left(\frac{1}{x}\right)\right\}=\frac{1}{(a-b)}\left(\frac{1}{x}-x\right) \tag{iv}
\end{array}
$$
On adding (iii) and (iv), we get
$$
\begin{aligned}
2 f(x) & =\left\{\frac{x}{(a+b)}-\frac{x}{(a-b)}\right\}+\left\{\frac{1}{(a+b) x}+\frac{1}{(a-b) x}\right\} \\
& =\frac{(a-b) x-(a+b) x}{\left(a^{2}-b^{2}\right)}+\frac{(a-b)+(a+b)}{\left(a^{2}-b^{2}\right) x} \\
& =\frac{-2 b x^{2}+2 d}{\left(a^{2}-b^{2}\right) x}=\frac{2}{\left(a^{2}-b^{2}\right)}\left(\frac{a}{x}-b x\right)
\end{aligned}
$$
Hence, $f(x)=\frac{1}{\left(a^{2}-b^{2}\right)}\left(\frac{a}{x}-b x\right)$.

---

