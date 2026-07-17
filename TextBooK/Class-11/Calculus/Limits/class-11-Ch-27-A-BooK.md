# Limits

## Concept of Limit

Consider the function $f(x)=\frac{\left(x^{2}-1\right)}{(x-1)}$.

Clearly, $f(1)=\frac{0}{0}$, which is meaningless. Thus, $f(x)$ is not defined at $x=1$.

Now, $f(x)=\frac{\left(x^{2}-1\right)}{(x-1)}=\frac{(x-1)(x+1)}{(x-1)}=(x+1)$, only when $x \neq 1$.

If we give to $x$, a value not exactly 1 but slightly more than 1 then clearly, the value of $f(x)$ is slightly more than 2. Now, if we go on decreasing this value and take it nearer to 1 then clearly the value of $f(x)$ will come nearer to 2, as shown below.

| If $x=1.1$ | then $f(x)=2.1$. |
| :--- | :--- |
| If $x=1.01$ | then $f(x)=2.01$. |
| If $x=1.001$ | then $f(x)=2.001$. |
| If $x=1.0000001$ | then $f(x)=2.0000001$. |

Thus, as the value of $x$ approaches 1, the value of $f(x)$ approaches 2, and we write: as $x \rightarrow 1, f(x) \rightarrow 2$. (The symbol '$\rightarrow$' stands for 'approaches to'.)

Similarly, if we give to $x$, a value slightly less than 1 then the value of $f(x)$ is slightly less than 2. Now, if we go on increasing this value and take it nearer to 1, the value of $f(x)$ will come nearer to 2, as shown below.

| If $x=0.9$ | then $f(x)=1.9$. |
| :--- | :--- |
| If $x=0.99$ | then $f(x)=1.99$. |
| If $x=0.999$ | then $f(x)=1.999$. |
| If $x=0.999999$ | then $f(x)=1.999999$. |

Thus, in this case also as $x \rightarrow 1, f(x) \rightarrow 2$.

We express this fact as:
$$
\lim_{x \rightarrow 1}\left(\frac{x^{2}-1}{x-1}\right)=2
$$

**LIMIT**: We say that $\lim_{x \rightarrow a} f(x)=l$ if whenever $x \rightarrow a, f(x) \rightarrow l$.

---

## Working Rules for Finding $\lim_{x \to a} f(x)$

**RULE I**: Put $x=a$ in the given function. If $f(a)$ is a definite value then:
$$
\lim_{x \rightarrow a} f(x)=f(a)
$$
**Examples**:
1. $\lim_{x \rightarrow 0} \sin x=\sin 0=0$.
2. $\lim_{x \rightarrow 1}\left(x^{2}+5 x-2\right)=\left(1^{2}+5 \times 1-2\right)=4$.

If $f(a)$ is indeterminate, we adopt the rules given below.

---

**RULE II**: If $f(x)$ is a rational function then factorize the numerator and the denominator. Cancel out the common factors and then put $x=a$.

### Example:
Evaluate:
(i) $\lim_{x \rightarrow 3}\left(\frac{x^{2}-9}{x-3}\right)$
(ii) $\lim_{x \rightarrow 1} \frac{\left(x^{2}-4 x+3\right)}{(x-1)}$

#### Solution:
(i) $\lim_{x \rightarrow 3}\left(\frac{x^{2}-9}{x-3}\right)=\lim_{x \rightarrow 3} \frac{(x+3)(x-3)}{(x-3)}=\lim_{x \rightarrow 3}(x+3)=6$.
(ii) $\lim_{x \rightarrow 1} \frac{\left(x^{2}-4 x+3\right)}{(x-1)}=\lim_{x \rightarrow 1} \frac{(x-1)(x-3)}{(x-1)}=\lim_{x \rightarrow 1}(x-3)=-2$.

---

**RULE III**: If the given function contains a surd then simplify it by using conjugate surds. After simplification, put $x=a$.

### Example:
Evaluate $\lim_{x \rightarrow 0}\left\{\frac{\sqrt{1+x}-\sqrt{1-x}}{x}\right\}$.

#### Solution:
We have:
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left\{\frac{\sqrt{1+x}-\sqrt{1-x}}{x}\right\} &= \lim_{x \rightarrow 0}\left\{\frac{(\sqrt{1+x}-\sqrt{1-x})}{x} \cdot \frac{(\sqrt{1+x}+\sqrt{1-x})}{(\sqrt{1+x}+\sqrt{1-x})}\right\} \\
&= \lim_{x \rightarrow 0} \frac{\{(1+x)-(1-x)\}}{x(\sqrt{1+x}+\sqrt{1-x})} \\
&= \lim_{x \rightarrow 0} \frac{2x}{x(\sqrt{1+x}+\sqrt{1-x})} \\
&= \lim_{x \rightarrow 0} \frac{2}{(\sqrt{1+x}+\sqrt{1-x})} = 1 \quad [\text{putting } x=0].
\end{aligned}
$$

---

**RULE IV**: If the given function contains a series which is capable of being expanded then after making proper expansion and simplifying, cancel the common factors in the numerator and denominator, if any. Then, put $x=a$.

Some important expansions are given below:

(i) For $|x|<1$, we have the binomial expansion:
$$
(1+x)^{n}=\left\{1+n x+\frac{n(n-1)}{2!} x^{2}+\frac{n(n-1)(n-2)}{3!} x^{3}+\ldots\right\}
$$
(ii)
$$
\left(\frac{x^{n}-a^{n}}{x-a}\right)=\left(x^{n-1}+a x^{n-2}+a^{2} x^{n-3}+\ldots+a^{n-1}\right)
$$
(iii)
$$
e^{x}=\left\{1+x+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\ldots+\frac{x^{n}}{n!}+\ldots\right\}
$$
(iv)
$$
a^{x}=\left\{1+x(\log a)+\frac{x^{2}}{2!}(\log a)^{2}+\ldots\right\}
$$
(v)
$$
\log (1+x)=\left\{x-\frac{x^{2}}{2}+\frac{x^{3}}{3}-\frac{x^{4}}{4}+\ldots\right\}
$$
(vi)
$$
\sin x=\left\{x-\frac{x^{3}}{3!}+\frac{x^{5}}{5!}-\frac{x^{7}}{7!}+\ldots\right\}
$$
(vii)
$$
\cos x=\left\{1-\frac{x^{2}}{2!}+\frac{x^{4}}{4!}-\frac{x^{6}}{6!}+\ldots\right\}
$$
(viii)
$$
\tan x=\left\{x+\frac{x^{3}}{3}+\frac{2}{15} x^{5}+\ldots\right\}
$$

---

## Fundamental Theorems on Limits (Without Proof)

We shall also make use of the following theorems on limits. The proof of these theorems is beyond the scope of this book.

(i) $\lim_{x \rightarrow a}\{f(x)+g(x)\}=\left\{\lim_{x \rightarrow a} f(x)\right\}+\left\{\lim_{x \rightarrow a} g(x)\right\}$
(ii) $\lim_{x \rightarrow a}\{f(x)-g(x)\}=\left\{\lim_{x \rightarrow a} f(x)\right\}-\left\{\lim_{x \rightarrow a} g(x)\right\}$
(iii) $\lim_{x \rightarrow a}\{c \cdot f(x)\}=c \cdot\left\{\lim_{x \rightarrow a} f(x)\right\}$, where $c$ is a constant
(iv) $\lim_{x \rightarrow a}\{f(x) \cdot g(x)\}=\left\{\lim_{x \rightarrow a} f(x)\right\} \cdot\left\{\lim_{x \rightarrow a} g(x)\right\}$
(v) $\lim_{x \rightarrow a}\left\{\frac{f(x)}{g(x)}\right\}=\frac{\left\{\lim_{x \rightarrow a} f(x)\right\}}{\left\{\lim_{x \rightarrow a} g(x)\right\}}$, provided $\lim_{x \rightarrow a} g(x) \neq 0$
(vi) If $f(x) \leq g(x)$ for all $x$ then $\lim_{x \rightarrow a} f(x) \leq \lim_{x \rightarrow a} g(x)$.

---

## Things to Remember

(i) $\sin C+\sin D=2 \sin \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right)$
(ii) $\sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$
(iii) $\cos C+\cos D=2 \cos \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right)$
(iv) $\cos C-\cos D=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$

---

## Some More Important Theorems on Limits

### Theorem 1: $\lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}$, where $a>0$.

#### Proof:
We know that $\left(\frac{x^{n}-a^{n}}{x-a}\right)=\left(x^{n-1}+a x^{n-2}+a^{2} x^{n-3}+\ldots+a^{n-1}\right)$.
$$
\begin{aligned}
\therefore \quad \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right) &= \lim_{x \rightarrow a}\left(x^{n-1}+a x^{n-2}+a^{2} x^{n-3}+\ldots+a^{n-1}\right) \\
&= n a^{n-1} \quad [\text{putting } x=a].
\end{aligned}
$$

### Theorem 2: $\lim_{x \rightarrow 0}\left(\frac{e^{x}-1}{x}\right)=1$.

#### Proof:
We have
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{e^{x}-1}{x}\right) &= \lim_{x \rightarrow 0}\left\{\frac{\left(1+x+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\ldots\right)-1}{x}\right\} \quad \left\{\because e^{x}=\left(1+x+\frac{x^{2}}{2!}+\ldots\right)\right\} \\
&= \lim_{x \rightarrow 0}\left\{\frac{\left(x+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\ldots\right)}{x}\right\}=\lim_{x \rightarrow 0}\left\{\frac{x\left(1+\frac{x}{2!}+\frac{x^{2}}{3!}+\ldots\right)}{x}\right\} \\
&= \lim_{x \rightarrow 0}\left(1+\frac{x}{2!}+\frac{x^{2}}{3!}+\ldots\right) \\
&= 1 \quad [\text{putting } x=0].
\end{aligned}
$$

### Theorem 3: $\lim_{x \rightarrow 0}\left(\frac{a^{x}-1}{x}\right)=\log a$.

#### Proof:
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{a^{x}-1}{x}\right) &= \lim_{x \rightarrow 0}\left\{\frac{\left\{1+x(\log a)+\frac{x^{2}}{2!}(\log a)^{2}+\ldots\right\}-1}{x}\right\} \quad [\text{on expanding } a^{x}] \\
&= \lim_{x \rightarrow 0} \frac{x\left\{(\log a)+\frac{x}{2!}(\log a)^{2}+\ldots\right\}}{x} \\
&= \lim_{x \rightarrow 0}\left\{(\log a)+\frac{x}{2!}(\log a)^{2}+\frac{x^{2}}{3!}(\log a)^{3}+\ldots\right\} \\
&= \log a \quad [\text{putting } x=0].
\end{aligned}
$$

### Theorem 4: $\lim_{x \rightarrow 0}(1+x)^{1 / x}=e$.

#### Proof:
$$
\begin{aligned}
\lim_{x \rightarrow 0}(1+x)^{1 / x} &= \lim_{x \rightarrow 0}\left\{1+\frac{1}{x} \cdot x+\frac{\frac{1}{x}\left(\frac{1}{x}-1\right)}{2!} \cdot x^{2}+\frac{\frac{1}{x}\left(\frac{1}{x}-1\right)\left(\frac{1}{x}-2\right)}{3!} \cdot x^{3}+\ldots \infty\right\} \quad [\text{using the binomial expansion of } (1+x)^{1/x}] \\
&= \lim_{x \rightarrow 0}\left\{1+1+\frac{(1-x)}{2!}+\frac{(1-x)(1-2 x)}{3!}+\ldots\right\} \\
&= \left(1+1+\frac{1}{2!}+\frac{1}{3!}+\ldots\right) \\
&= e
\end{aligned}
$$

### Theorem 5: $\lim_{x \rightarrow 0} \frac{\log (1+x)}{x}=1$.

#### Proof:
$$
\begin{aligned}
\lim_{x \rightarrow 0} \frac{\log (1+x)}{x} &= \lim_{x \rightarrow 0} \frac{\left(x-\frac{x^{2}}{2}+\frac{x^{3}}{3}-\ldots\right)}{x} \quad [\text{expanding } \log (1+x)] \\
&= \lim_{x \rightarrow 0}\left(1-\frac{x}{2}+\frac{x^{2}}{3}-\ldots\right) = 1 \quad [\text{putting } x=0].
\end{aligned}
$$

---

## Summary

1. $\lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}$, where $a>0$.
2. $\lim_{x \rightarrow 0}\left(\frac{e^{x}-1}{x}\right)=1$.
3. $\lim_{x \rightarrow 0}\left(\frac{a^{x}-1}{x}\right)=\log_{e} a$.
4. $\lim_{x \rightarrow 0}(1+x)^{1 / x}=e$.
5. $\lim_{x \rightarrow 0} \frac{\log (1+x)}{x}=1$.

---

## Solved Examples

### Example 1: Evaluate $\lim_{x \rightarrow a}\left\{\frac{x^{12}-a^{12}}{x-a}\right\}$.

#### Solution:
$$
\lim_{x \rightarrow a}\left\{\frac{x^{12}-a^{12}}{x-a}\right\}=12 a^{(12-1)}=12 a^{11} \quad \left[\because \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}\right].
$$

---

### Example 2: Evaluate $\lim_{x \rightarrow 2}\left(\frac{x^{5}-32}{x^{3}-8}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 2}\left(\frac{x^{5}-32}{x^{3}-8}\right) &= \lim_{x \rightarrow 2}\left(\frac{x^{5}-2^{5}}{x^{3}-2^{3}}\right) \\
&= \lim_{x \rightarrow 2}\left\{\left(\frac{x^{5}-2^{5}}{x-2}\right) \div \left(\frac{x^{3}-2^{3}}{x-2}\right)\right\} \\
&= \lim_{x \rightarrow 2}\left(\frac{x^{5}-2^{5}}{x-2}\right) \div \lim_{x \rightarrow 2}\left(\frac{x^{3}-2^{3}}{x-2}\right) \\
&= \left[\left(5 \times 2^{4}\right) \div \left(3 \times 2^{2}\right)\right] \quad \left[\because \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}\right] \\
&= \left(\frac{80}{12}\right)=\frac{20}{3}.
\end{aligned}
$$

---

### Example 3: Evaluate $\lim_{x \rightarrow 1} \frac{x^{15}-1}{x^{10}-1}$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 1} \frac{x^{15}-1}{x^{10}-1} &= \lim_{x \rightarrow 1}\left\{\left(\frac{x^{15}-1}{x-1}\right) \div \left(\frac{x^{10}-1}{x-1}\right)\right\} \\
&= \lim_{x \rightarrow 1}\left(\frac{x^{15}-1}{x-1}\right) \div \lim_{x \rightarrow 1}\left(\frac{x^{10}-1}{x-1}\right) \\
&= \left(15 \times 1^{14}\right) \div \left(10 \times 1^{9}\right)=\frac{15}{10}=\frac{3}{2}.
\end{aligned}
$$

---

### Example 4: Evaluate $\lim_{x \rightarrow a}\left(\frac{x^{m}-a^{m}}{x^{n}-a^{n}}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow a}\left(\frac{x^{m}-a^{m}}{x^{n}-a^{n}}\right) &= \lim_{x \rightarrow a}\left\{\left(\frac{x^{m}-a^{m}}{x-a}\right) \div \left(\frac{x^{n}-a^{n}}{x-a}\right)\right\} \\
&= \lim_{x \rightarrow a}\left(\frac{x^{m}-a^{m}}{x-a}\right) \div \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right) \\
&= \left(m a^{m-1}\right) \div \left(n a^{n-1}\right) \\
&= \frac{m a^{m-1}}{n a^{n-1}}=\frac{m}{n} a^{m-n}.
\end{aligned}
$$

---

### Example 5: Evaluate $\lim_{x \rightarrow a} \frac{(x+2)^{3 / 2}-(a+2)^{3 / 2}}{x-a}$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow a} \frac{(x+2)^{3 / 2}-(a+2)^{3 / 2}}{x-a} &= \lim_{(x+2) \rightarrow(a+2)} \frac{(x+2)^{3 / 2}-(a+2)^{3 / 2}}{(x+2)-(a+2)} \\
&= \frac{3}{2} \cdot(a+2)^{\left(\frac{3}{2}-1\right)}=\frac{3}{2}(a+2)^{1 / 2} \quad \left[\because \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}\right].
\end{aligned}
$$

---

### Example 6: Evaluate $\lim_{x \rightarrow 0} \frac{(1+x)^{n}-1}{x}$.

#### Solution:
Put $(1+x)=y$, so that when $x \rightarrow 0$ then $y \rightarrow 1$.
$$
\begin{aligned}
\therefore \quad \lim_{x \rightarrow 0} \frac{(1+x)^{n}-1}{x} &= \lim_{y \rightarrow 1}\left(\frac{y^{n}-1}{y-1}\right) \\
&= \lim_{y \rightarrow 1}\left(\frac{y^{n}-1^{n}}{y-1}\right)=n \times 1^{(n-1)}=(n \times 1)=n .
\end{aligned}
$$

---

### Example 7: Evaluate $\lim_{x \rightarrow 1}\left(\frac{1-x^{-1 / 3}}{1-x^{-2 / 3}}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 1}\left(\frac{1-x^{-1 / 3}}{1-x^{-2 / 3}}\right) &= \lim_{x \rightarrow 1}\left[\frac{\left(1-x^{-1 / 3}\right)}{(1)^{2}-\left(x^{-1 / 3}\right)^{2}}\right] \\
&= \lim_{x \rightarrow 1} \frac{\left(1-x^{-1 / 3}\right)}{\left(1-x^{-1 / 3}\right)\left(1+x^{-1 / 3}\right)} \\
&= \lim_{x \rightarrow 1} \frac{1}{\left(1+x^{-1 / 3}\right)}=\frac{1}{\left\{1+(1)^{-1 / 3}\right\}}=\frac{1}{2}.
\end{aligned}
$$

---

### Example 8: Evaluate $\lim_{x \rightarrow 0} \frac{(\sqrt{1+3 x}-\sqrt{1-3 x})}{x}$. [CBSE 2000C]

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 0} \frac{(\sqrt{1+3 x}-\sqrt{1-3 x})}{x} &= \lim_{x \rightarrow 0}\left\{\frac{(\sqrt{1+3 x}-\sqrt{1-3 x})}{x} \times \frac{(\sqrt{1+3 x}+\sqrt{1-3 x})}{(\sqrt{1+3 x}+\sqrt{1-3 x})}\right\} \\
&= \lim_{x \rightarrow 0} \frac{\{(1+3 x)-(1-3 x)\}}{x(\sqrt{1+3 x}+\sqrt{1-3 x})}=\lim_{x \rightarrow 0} \frac{6 x}{x(\sqrt{1+3 x}+\sqrt{1-3 x})} \\
&= \lim_{x \rightarrow 0} \frac{6}{(\sqrt{1+3 x}+\sqrt{1-3 x})}=\frac{6}{(\sqrt{1}+\sqrt{1})}=\frac{6}{2}=3.
\end{aligned}
$$

---

### Example 9: Evaluate $\lim_{x \rightarrow 2}\left\{\frac{\left(x^{2}-4\right)}{\sqrt{3 x-2}-\sqrt{x+2}}\right\}$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 2}\left\{\frac{\left(x^{2}-4\right)}{\sqrt{3 x-2}-\sqrt{x+2}}\right\} &= \lim_{x \rightarrow 2}\left\{\frac{\left(x^{2}-4\right)}{(\sqrt{3 x-2}-\sqrt{x+2})} \times \frac{(\sqrt{3 x-2}+\sqrt{x+2})}{(\sqrt{3 x-2}+\sqrt{x+2})}\right\} \\
&= \lim_{x \rightarrow 2}\left\{\frac{\left(x^{2}-4\right)(\sqrt{3 x-2}+\sqrt{x+2})}{(3 x-2)-(x+2)}\right\} \\
&= \lim_{x \rightarrow 2}\left\{\frac{\left(x^{2}-4\right)(\sqrt{3 x-2}+\sqrt{x+2})}{2(x-2)}\right\} \\
&= \lim_{x \rightarrow 2} \frac{(x-2)(x+2)(\sqrt{3 x-2}+\sqrt{x+2})}{2(x-2)} \\
&= \lim_{x \rightarrow 2} \frac{(x+2)(\sqrt{3 x-2}+\sqrt{x+2})}{2} \quad [\text{cancelling }(x-2)] \\
&= \frac{(2+2)(\sqrt{3(2)-2}+\sqrt{2+2})}{2} = \frac{4(\sqrt{4}+\sqrt{4})}{2} = \frac{4(2+2)}{2} = 8 \quad [\text{putting } x=2].
\end{aligned}
$$

---

### Example 10: Evaluate $\lim_{x \rightarrow 0}\left(\frac{e^{3 x}-1}{x}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{e^{3 x}-1}{x}\right) &= \lim_{3 x \rightarrow 0}\left\{\left(\frac{e^{3 x}-1}{3 x}\right) \times 3\right\} \quad [\because(x \rightarrow 0) \Rightarrow(3 x \rightarrow 0)] \\
&= 3 \times \lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{y}\right), \quad \text{where } y=3 x \\
&= (3 \times 1)=3 \quad \left[\because \lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{y}\right)=1\right].
\end{aligned}
$$

---

### Example 11: Evaluate $\lim_{x \rightarrow 2}\left(\frac{e^{x}-e^{2}}{x-2}\right)$. [CBSE 2003]

#### Solution:
Put $(x-2)=y$, so that when $x \rightarrow 2$ then $y \rightarrow 0$.
$$
\begin{aligned}
\therefore \lim_{x \rightarrow 2}\left(\frac{e^{x}-e^{2}}{x-2}\right) &= \lim_{y \rightarrow 0}\left(\frac{e^{y+2}-e^{2}}{y}\right) \\
&= \lim_{y \rightarrow 0}\left\{e^{2} \cdot\left(\frac{e^{y}-1}{y}\right)\right\} \\
&= e^{2} \cdot \lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{y}\right)=\left(e^{2} \times 1\right)=e^{2} \quad \left[\because \lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{y}\right)=1\right].
\end{aligned}
$$

---

### Example 12: Evaluate:
(i) $\lim_{x \rightarrow 0}\left(\frac{e^{-x}-1}{x}\right)$
(ii) $\lim_{x \rightarrow 0}\left(\frac{e^{x}-e^{-x}}{x}\right)$
(iii) $\lim_{x \rightarrow 0}\left(\frac{e^{x}+e^{-x}-2}{x^{2}}\right)$ [CBSE 2004]

#### Solution:
(i)
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{e^{-x}-1}{x}\right) &= \lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{-y}\right), \text{ where } -x=y \\
&= -\lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{y}\right)=-1 \quad \left[\because \lim_{y \rightarrow 0}\left(\frac{e^{y}-1}{y}\right)=1\right].
\end{aligned}
$$
(ii)
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{e^{x}-e^{-x}}{x}\right) &= \lim_{x \rightarrow 0}\left\{\frac{\left(e^{x}-1\right)-\left(e^{-x}-1\right)}{x}\right\} \\
&= \lim_{x \rightarrow 0}\left\{\left(\frac{e^{x}-1}{x}\right)-\left(\frac{e^{-x}-1}{x}\right)\right\} \\
&= \lim_{x \rightarrow 0}\left(\frac{e^{x}-1}{x}\right)-\lim_{x \rightarrow 0}\left(\frac{e^{-x}-1}{x}\right) \\
&= 1 - (-1) = 2.
\end{aligned}
$$
(iii)
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{e^{x}+e^{-x}-2}{x^{2}}\right) &= \lim_{x \rightarrow 0}\left(\frac{e^{2 x}+1-2 e^{x}}{x^{2} e^{x}}\right) \\
&= \lim_{x \rightarrow 0}\left\{\left(\frac{e^{x}-1}{x}\right)^{2} \cdot \frac{1}{e^{x}}\right\} \\
&= \left(\lim_{x \rightarrow 0}\frac{e^{x}-1}{x}\right)^{2} \cdot \lim_{x \rightarrow 0} \frac{1}{e^{x}} \\
&= \left(1^{2} \times \frac{1}{e^{0}}\right)=(1 \times 1)=1 \quad \left[\because \lim_{x \rightarrow 0}\left(\frac{e^{x}-1}{x}\right)=1\right].
\end{aligned}
$$

---

### Example 13: Evaluate $\lim_{x \rightarrow 0}\left(\frac{3^{x}-2^{x}}{x}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{3^{x}-2^{x}}{x}\right) &= \lim_{x \rightarrow 0}\left\{\frac{\left(3^{x}-1\right)-\left(2^{x}-1\right)}{x}\right\} \\
&= \lim_{x \rightarrow 0}\left(\frac{3^{x}-1}{x}\right)-\lim_{x \rightarrow 0}\left(\frac{2^{x}-1}{x}\right) \\
&= (\log 3-\log 2)=\log \frac{3}{2} \quad \left[\because \lim_{x \rightarrow 0}\left(\frac{a^{x}-1}{x}\right)=\log a\right].
\end{aligned}
$$

---

### Example 14: Evaluate $\lim_{x \rightarrow 0}\left(\frac{3^{2 x}-2^{3 x}}{x}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{3^{2 x}-2^{3 x}}{x}\right) &= \lim_{x \rightarrow 0}\left\{\frac{\left(3^{2 x}-1\right)-\left(2^{3 x}-1\right)}{x}\right\} \\
&= \lim_{x \rightarrow 0}\left(\frac{3^{2 x}-1}{x}\right)-\lim_{x \rightarrow 0}\left(\frac{2^{3 x}-1}{x}\right) \\
&= \lim_{x \rightarrow 0}\left\{\left(\frac{3^{2 x}-1}{2 x}\right) \cdot 2\right\}-\lim_{x \rightarrow 0}\left\{\left(\frac{2^{3 x}-1}{3 x}\right) \cdot 3\right\} \\
&= 2 \cdot \lim_{2 x \rightarrow 0}\left(\frac{3^{2 x}-1}{2 x}\right)-3 \cdot \lim_{3 x \rightarrow 0}\left(\frac{2^{3 x}-1}{3 x}\right) \\
&= (2 \log 3-3 \log 2) \quad \left[\because \lim_{y \rightarrow 0}\left(\frac{a^{y}-1}{y}\right)=\log a\right] \\
&= \left[\log (3)^{2}-\log (2)^{3}\right]=(\log 9-\log 8)=\log \left(\frac{9}{8}\right).
\end{aligned}
$$

---

### Example 15: Evaluate $\lim_{x \rightarrow 0}\left(\frac{3^{2 x}-1}{2^{3 x}-1}\right)$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 0}\left(\frac{3^{2 x}-1}{2^{3 x}-1}\right) &= \lim_{x \rightarrow 0} \frac{\left\{\left(\frac{3^{2 x}-1}{2 x}\right) \cdot 2 x\right\}}{\left\{\left(\frac{2^{3 x}-1}{3 x}\right) \cdot 3 x\right\}} \\
&= \frac{2}{3} \cdot \frac{\lim_{2 x \rightarrow 0}\left(\frac{3^{2 x}-1}{2 x}\right)}{\lim_{3 x \rightarrow 0}\left(\frac{2^{3 x}-1}{3 x}\right)} \\
&= \frac{2}{3} \cdot \frac{\log 3}{\log 2} \\
&= \frac{2 \log 3}{3 \log 2}=\frac{\log \left(3^{2}\right)}{\log \left(2^{3}\right)}=\frac{\log 9}{\log 8}.
\end{aligned}
$$

---

### Example 16: Evaluate $\lim_{x \rightarrow 1} \frac{x^{2}-\sqrt{x}}{\sqrt{x}-1}$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 1} \frac{\left(x^{2}-\sqrt{x}\right)}{(\sqrt{x}-1)} &= \lim_{x \rightarrow 1} \frac{\sqrt{x}(x^{3/2}-1)}{(\sqrt{x}-1)} = \lim_{x \rightarrow 1} \frac{\sqrt{x}((\sqrt{x})^3-1)}{(\sqrt{x}-1)} \\
&= \lim_{x \rightarrow 1} \frac{\sqrt{x}(\sqrt{x}-1)(x+\sqrt{x}+1)}{(\sqrt{x}-1)} \\
&= \lim_{x \rightarrow 1} \sqrt{x}(x+\sqrt{x}+1) \\
&= \sqrt{1}(1+\sqrt{1}+1) = 1(1+1+1) = 3.
\end{aligned}
$$
*Alternative Solution:*
$$
\begin{aligned}
\lim_{x \rightarrow 1} \frac{x\left(x^{3}-1\right)(\sqrt{x}+1)}{(x-1)\left(x^{2}+\sqrt{x}\right)} &= \lim_{x \rightarrow 1} \frac{x(x-1)\left(x^{2}+x+1\right)(\sqrt{x}+1)}{(x-1)\left(x^{2}+\sqrt{x}\right)} \\
&= \lim_{x \rightarrow 1} \frac{x\left(x^{2}+x+1\right)(\sqrt{x}+1)}{\left(x^{2}+\sqrt{x}\right)} \\
&= \frac{1 \times\left(1^{2}+1+1\right)(\sqrt{1}+1)}{\left(1^{2}+\sqrt{1}\right)}=\left(\frac{1 \times 3 \times 2}{2}\right)=3 \quad [\text{putting } x=1].
\end{aligned}
$$

---

### Example 17: Evaluate $\lim_{x \rightarrow a} \frac{\sqrt{a+2 x}-\sqrt{3 x}}{\sqrt{3 a+x}-2 \sqrt{x}}$.

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow a} \frac{(\sqrt{a+2 x}-\sqrt{3 x})}{(\sqrt{3 a+x}-2 \sqrt{x})} &= \lim_{x \rightarrow a} \frac{(\sqrt{a+2 x}-\sqrt{3 x})}{(\sqrt{3 a+x}-2 \sqrt{x})} \times \frac{(\sqrt{3 a+x}+2 \sqrt{x})}{(\sqrt{3 a+x}+2 \sqrt{x})} \times \frac{(\sqrt{a+2 x}+\sqrt{3 x})}{(\sqrt{a+2 x}+\sqrt{3 x})} \\
&= \lim_{x \rightarrow a} \frac{[(a+2 x)-3 x] \times(\sqrt{3 a+x}+2 \sqrt{x})}{[(3 a+x)-4 x] \times(\sqrt{a+2 x}+\sqrt{3 x})} \\
&= \lim_{x \rightarrow a} \frac{(a-x) \times(\sqrt{3 a+x}+2 \sqrt{x})}{3(a-x) \times(\sqrt{a+2 x}+\sqrt{3 x})} = \lim_{x \rightarrow a} \frac{(\sqrt{3 a+x}+2 \sqrt{x})}{3(\sqrt{a+2 x}+\sqrt{3 x})} \\
&= \frac{(\sqrt{4 a}+2 \sqrt{a})}{3(\sqrt{3 a}+\sqrt{3 a})} = \frac{4 \sqrt{a}}{3(2\sqrt{3a})} = \frac{4 \sqrt{a}}{6 \sqrt{3} \sqrt{a}} = \frac{2}{3 \sqrt{3}}.
\end{aligned}
$$

---

### Example 18: Evaluate $\lim_{x \rightarrow 1} \frac{(2 x-3)(\sqrt{x}-1)}{\left(2 x^{2}+x-3\right)}$. [CBSE 2005C]

#### Solution:
$$
\begin{aligned}
\lim_{x \rightarrow 1} \frac{(2 x-3)(\sqrt{x}-1)}{\left(2 x^{2}+x-3\right)} &= \lim_{x \rightarrow 1} \frac{(2 x-3)(\sqrt{x}-1)}{(2 x+3)(x-1)} \\
&= \lim_{x \rightarrow 1} \frac{(2 x-3)(\sqrt{x}-1)}{(2 x+3)(\sqrt{x}-1)(\sqrt{x}+1)} \\
&= \lim_{x \rightarrow 1} \frac{(2 x-3)}{(2 x+3)(\sqrt{x}+1)} = \frac{(2 \times 1-3)}{(2 \times 1+3)(\sqrt{1}+1)} = \frac{-1}{5 \times 2} = \frac{-1}{10}.
\end{aligned}
$$

---

### Example 19: Evaluate $\lim_{x \rightarrow 0} \frac{(1+x)^{4}-1}{x}$.

#### Solution:
Put $(1+x)=y$, so that when $x \rightarrow 0$ then $y \rightarrow 1$.
$$
\begin{aligned}
\therefore \quad \lim_{x \rightarrow 0} \frac{(1+x)^{4}-1}{x} &= \lim_{y \rightarrow 1}\left(\frac{y^{4}-1}{y-1}\right)=\lim_{y \rightarrow 1}\left(\frac{y^{4}-1^{4}}{y-1}\right) \\
&= 4 \times 1^{(4-1)} \quad \left[\because \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}\right] \\
&= \left(4 \times 1^{3}\right)=4.
\end{aligned}
$$

---

### Example 20: Evaluate $\lim_{x \rightarrow 0} \frac{(1+x)^{6}-1}{(1+x)^{5}-1}$.

#### Solution:
Put $(1+x)=y$, so that when $x \rightarrow 0$ then $y \rightarrow 1$.
$$
\begin{aligned}
\therefore \quad \lim_{x \rightarrow 0} \frac{(1+x)^{6}-1}{(1+x)^{5}-1} &= \lim_{y \rightarrow 1}\left(\frac{y^{6}-1}{y^{5}-1}\right) = \frac{\lim_{y \rightarrow 1}\left(\frac{y^{6}-1}{y-1}\right)}{\lim_{y \rightarrow 1}\left(\frac{y^{5}-1}{y-1}\right)} \\
&= \frac{\lim_{y \rightarrow 1}\left(\frac{y^{6}-1^{6}}{y-1}\right)}{\lim_{y \rightarrow 1}\left(\frac{y^{5}-1^{5}}{y-1}\right)} = \frac{6 \times 1^{(6-1)}}{5 \times 1^{(5-1)}} \\
&= \frac{6 \times 1^{5}}{5 \times 1^{4}}=\frac{6}{5} \quad \left[\because \lim_{x \rightarrow a}\left(\frac{x^{n}-a^{n}}{x-a}\right)=n a^{n-1}\right].
\end{aligned}
$$

---

