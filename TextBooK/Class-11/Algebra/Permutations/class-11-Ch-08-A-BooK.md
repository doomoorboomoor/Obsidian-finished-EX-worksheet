## Permutations

## The Factorial

**Factorial Notation:** Let $n$ be a positive integer. Then, the continued product of first $n$ natural numbers is called **factorial n**, to be denoted by $n!$, or $\underline{n}$. Also, we define $0! = 1$.

When $n$ is negative or a fraction, $n!$ is not defined.

Thus, $n! = n(n-1)(n-2) \ldots 3 \cdot 2 \cdot 1$.

**EXAMPLE:** $6! = (6 \times 5 \times 4 \times 3 \times 2 \times 1) = 720$, $3! = 3 \times 2 \times 1 = 6$ and $1! = 1$.

**DEDUCTION:** $n! = n(n-1)(n-2)(n-3) \ldots 3 \cdot 2 \cdot 1$

$$
\begin{aligned}
& = n[(n-1)(n-2)(n-3) \ldots 3 \cdot 2 \cdot 1] \\
& = n[(n-1)!]
\end{aligned}
$$

Thus, $9! = 9 \times (8!)$, $6! = 6 \times (5!)$, $3! = 3 \times (2!)$.

Also, $1! = 1 \times (0!) \Rightarrow 0! = 1$.

Thus, we have:
- (i) $n! = n(n-1)(n-2) \ldots 3 \times 2 \times 1$.
- (ii) $n! = n \times (n-1)!$.
- (iii) $0! = 1$.

---

## Solved Examples

### Example 1:

Compute:
(i) $\frac{10!}{(7!) \times (3!)}$
(ii) $\frac{30!}{28!}$
(iii) $\frac{11!-10!}{9!}$

#### Solution:

We have:

(i)
$$
\frac{10!}{(7!) \times (3!)} = \frac{10 \times 9 \times 8 \times (7!)}{(7!) \times (3 \times 2 \times 1)} = \frac{10 \times 9 \times 8}{3 \times 2 \times 1} = 120
$$

(ii)
$$
\frac{30!}{28!} = \frac{30 \times 29 \times (28!)}{(28!)} = 30 \times 29 = 870
$$

(iii)
$$
\frac{11!-10!}{9!} = \frac{11 \times 10 \times (9!) - 10 \times (9!)}{9!} = \frac{(110-10)(9!)}{(9!)} = 100
$$

---

### Example 2:

If $\frac{x}{10!} = \frac{1}{8!} + \frac{1}{9!}$, find the value of $x$.

#### Solution:

On multiplying both sides by $10!$, we get:

$$
\begin{aligned}
x &= \frac{10!}{8!} + \frac{10!}{9!} \\
\Rightarrow x &= \frac{10 \times 9 \times (8!)}{(8!)} + \frac{10 \times (9!)}{(9!)} \\
\Rightarrow x &= (10 \times 9) + 10 = (90+10) = 100
\end{aligned}
$$

Hence, $x=100$.

---

### Example 3:

Express each of the following products in factorials:
(i) $5 \times 6 \times 7 \times 8 \times 9$
(ii) $2 \times 4 \times 6 \times 8 \times 10$

#### Solution:

We have:

(i) $5 \times 6 \times 7 \times 8 \times 9 = \frac{(1 \times 2 \times 3 \times 4) \times (5 \times 6 \times 7 \times 8 \times 9)}{(1 \times 2 \times 3 \times 4)}$
[Multiplying and dividing the given product by $(1 \times 2 \times 3 \times 4)$]

$$
= \frac{1 \times 2 \times 3 \times 4 \times 5 \times 6 \times 7 \times 8 \times 9}{1 \times 2 \times 3 \times 4} = \frac{9!}{4!}
$$

(ii) $2 \times 4 \times 6 \times 8 \times 10 = (2 \times 1) \times (2 \times 2) \times (2 \times 3) \times (2 \times 4) \times (2 \times 5)$

$$
= 2^{5} \times (1 \times 2 \times 3 \times 4 \times 5) = 2^{5} \times (5!)
$$

---

### Example 4:

Find the LCM of $(5!, 6!, 7!)$.

#### Solution:

We have:

$$
\begin{aligned}
\operatorname{LCM}(5!, 6!, 7!) &= \operatorname{LCM}(5!, 6 \times 5!, 7 \times 6 \times 5!) \\
&= (5!) \times \operatorname{LCM}(1, 6, 42) = (5!) \times 42 \\
&= 7 \times 6 \times 5! = 7!
\end{aligned}
$$

---

### Example 5:

If $(n+1)! = 90 \times (n-1)!$, find $n$.

#### Solution:

We have:

$$
\begin{aligned}
& (n+1)! = 90 \times (n-1)! \\
\Rightarrow & (n+1) \times n \times (n-1)! = 90 \times (n-1)! \\
\Rightarrow & (n+1)n = 90 \\
\Rightarrow & (n+1)n = 10 \times 9 \quad \text{[writing 90 as product of two consecutive integers]} \\
\Rightarrow & n=9
\end{aligned}
$$

Hence, $n=9$.

---

### Example 6:

If $(n+2)! = 60 \times (n-1)!$, find $n$.

#### Solution:

We have:

$$
\begin{aligned}
& (n+2)! = 60 \times (n-1)! \\
\Rightarrow & (n+2) \times (n+1) \times n \times (n-1)! = 60 \times (n-1)! \\
\Rightarrow & (n+2)(n+1)n = 60 \\
\Rightarrow & (n+2)(n+1)n = 5 \times 4 \times 3 \quad \text{[writing 60 as product of 3 consecutive integers]} \\
\Rightarrow & n=3
\end{aligned}
$$

Hence, $n=3$.

---

### Example 7:

Prove that $(n!+1)$ is not divisible by any natural number between 2 and $n$.

#### Solution:

Since $n! = n(n-1)(n-2) \ldots 3 \cdot 2 \cdot 1$, it follows that $n!$ is divisible by every natural number between $2$ and $n$. So, $(n!+1)$, when divided by any natural number between $2$ and $n$, leaves $1$ as remainder.

Hence, $(n!+1)$ is not divisible by any natural number between $2$ and $n$.

---

### Example 8:

Prove that $n(n-1)(n-2) \ldots (n-r+1) = \frac{n!}{(n-r)!}$.

#### Solution:

We have:

$$
\begin{aligned}
n(n-1)(n-2) \ldots (n-r+1) &= \frac{n(n-1)(n-2) \ldots (n-r+1) \cdot (n-r)!}{(n-r)!} \\
&= \frac{n!}{(n-r)!}
\end{aligned}
$$

Hence, $n(n-1)(n-2) \ldots (n-r+1) = \frac{n!}{(n-r)!}$.

---

### Example 9:

Prove that $\frac{(2n)!}{n!} = 2^{n} \times \{1 \times 3 \times 5 \times \ldots \times (2n-1)\}$.

#### Solution:

We have:

$$
\begin{aligned}
\frac{(2n)!}{n!} &= \frac{\{1 \times 2 \times 3 \times 4 \times 5 \times \ldots \times (2n-2) \times (2n-1) \times 2n\}}{n!} \\
&= \frac{\{1 \times 3 \times 5 \times \ldots \times (2n-1)\} \times \{2 \times 4 \times 6 \times \ldots \times (2n-2) \times 2n\}}{n!} \\
&= \frac{\{1 \times 3 \times 5 \times \ldots \times (2n-1)\} \times 2^{n} \times \{1 \times 2 \times 3 \times \ldots \times n\}}{n!} \\
&= \frac{\{1 \times 3 \times 5 \times \ldots \times (2n-1)\} \times 2^{n} \times (n!)}{n!} \\
&= 2^{n} \times \{1 \times 3 \times 5 \times \ldots \times (2n-1)\}
\end{aligned}
$$

Hence, $\frac{(2n)!}{n!} = 2^{n} \times \{1 \times 3 \times 5 \times \ldots \times (2n-1)\}$.

---

### Example 10:

Prove that $(n!)^{2} \leq (n!) \times n^{n} < (2n)!$ for all $n \in N$.

#### Solution:

We have:

$$
(n!)^{2} = (n!) \times (n!) = (n!) \times (1 \times 2 \times 3 \times \ldots \times n)
$$

$$
\leq (n!) \times n^{n} \quad [\because r \leq n \text{ for each } r=1, 2, 3, \ldots, n]
$$

$$
\therefore (n!)^{2} \leq (n!) \times n^{n} \quad \text{(i)}
$$

Again, we have:

$$
\begin{align*}
(2n)! &= (1 \times 2 \times 3 \times \ldots \times n) \times (n+1) \times (n+2) \times \ldots \times 2n \\
& >(n!) \times n^{n} \quad [\because (n+r)>n \text{ for each } r=1, 2, \ldots, n] \quad \text{(ii)}
\end{align*}
$$

Thus, $(n!) \times n^{n} < (2n)!$.

Hence, from (i) and (ii), we have:

$$
(n!)^{2} \leq (n!) \times n^{n} < (2n)!
$$

---

