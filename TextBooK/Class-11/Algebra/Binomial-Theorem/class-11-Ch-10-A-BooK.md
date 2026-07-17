# Binomial Theorem

The expression of the form $(a+b)^{n}$ is called a **binomial**. By direct multiplication it is easy to expand $(a+b)^{2}$, $(a+b)^{3}$, etc. The ancient mathematicians knew about the expansion of $(a+b)^{n}$ for $0 \leq n \leq 7$. Around 1660, **B. Pascal** introduced **Pascal's triangle** for the coefficients in the expansion of $(a+b)^{n}$ and in the same year he gave the present form of binomial theorem.

---

## Binomial Theorem (For Non-negative Integers)

$$
(a+b)^{n} = { }^{n} C_{0} a^{n} + { }^{n} C_{1} a^{n-1} b + { }^{n} C_{2} a^{n-2} b^{2} + \ldots + { }^{n} C_{n-1} a b^{n-1} + { }^{n} C_{n} b^{n}
$$

By direct multiplication, we have:

1.  $(a+b)^{0} = 1$. $[\because x^{0}=1 \text{ for every real } x]$
2.  $(a+b)^{1} = a+b = { }^{1} C_{0} a + { }^{1} C_{1} b$.
3.  $(a+b)^{2} = a^{2} + 2 a b + b^{2} = { }^{2} C_{0} a^{2} + { }^{2} C_{1} a b + { }^{2} C_{2} b^{2}$.
4.  $(a+b)^{3} = a^{3} + 3 a^{2} b + 3 a b^{2} + b^{3} = { }^{3} C_{0} a^{3} + { }^{3} C_{1} a^{2} b + { }^{3} C_{2} a b^{2} + { }^{3} C_{3} b^{3}$.
5.  $(a+b)^{4} = a^{4} + 4 a^{3} b + 6 a^{2} b^{2} + 4 a b^{3} + b^{4} = { }^{4} C_{0} a^{4} + { }^{4} C_{1} a^{3} b + { }^{4} C_{2} a^{2} b^{2} + { }^{4} C_{3} a b^{3} + { }^{4} C_{4} b^{4}$.

---

## Pascal's Triangle

Given below is the Pascal's Triangle showing the coefficients of various terms in a binomial expansion.

**Index & Coefficients**
![](https://cdn.mathpix.com/cropped/2025_09_25_52cc27209592d3a5b33eg-01.jpg?height=492&width=692&top_left_y=1367&top_left_x=406)

Look at the pattern given below:
- For $n=4$, the various coefficients are ${ }^{4} C_{0}, { }^{4} C_{1}, { }^{4} C_{2}, { }^{4} C_{3}, { }^{4} C_{4}$.
- For $n=5$, the various coefficients are ${ }^{5} C_{0}, { }^{5} C_{1}, { }^{5} C_{2}, { }^{5} C_{3}, { }^{5} C_{4}, { }^{5} C_{5}$.
- For $n=6$, the various coefficients are ${ }^{6} C_{0}, { }^{6} C_{1}, { }^{6} C_{2}, { }^{6} C_{3}, { }^{6} C_{4}, { }^{6} C_{5}, { }^{6} C_{6}$.
- For $n=7$, the various coefficients are ${ }^{7} C_{0}, { }^{7} C_{1}, { }^{7} C_{2}, { }^{7} C_{3}, { }^{7} C_{4}, { }^{7} C_{5}, { }^{7} C_{6}, { }^{7} C_{7}$.

---

## Binomial Theorem for Positive Integral Index

**THEOREM** If $a$ and $b$ are real numbers then for all $n \in N$
$$
(a+b)^{n} = { }^{n} C_{0} a^{n} + { }^{n} C_{1} a^{n-1} b + { }^{n} C_{2} a^{n-2} b^{2} + \ldots + { }^{n} C_{n-1} a b^{n-1} + { }^{n} C_{n} b^{n}
$$

**PROOF** We shall prove the theorem by using the principle of mathematical induction.
Let $P(n)$ be the statement:
$$
(a+b)^{n} = { }^{n} C_{0} a^{n} + { }^{n} C_{1} a^{n-1} b + { }^{n} C_{2} a^{n-2} b^{2} + \ldots + { }^{n} C_{n-1} a b^{n-1} + { }^{n} C_{n} b^{n}
$$
Then, the statement $P(1)$ is
$$
(a+b)^{1} = { }^{1} C_{0} a^{1} + { }^{1} C_{1} a^{0} b = (a+b) \text {, which is true. }
$$
Thus, $P(1)$ is true.
Let $P(m)$ be true. Then,
$$
(a+b)^{m} = { }^{m} C_{0} a^{m} + { }^{m} C_{1} a^{m-1} b + { }^{m} C_{2} a^{m-2} b^{2} + \ldots + { }^{m} C_{m-1} a b^{m-1} + { }^{m} C_{m} b^{m} \quad \text{(i)}
$$
Multiplying both sides of (i) by $(a+b)$, we get
$$
\begin{aligned}
(a+b)^{m+1} &= { }^{m} C_{0} a^{m+1} + { }^{m} C_{0} a^{m} b + { }^{m} C_{1} a^{m} b + { }^{m} C_{1} a^{m-1} b^{2} + { }^{m} C_{2} a^{m-1} b^{2} \\
& \quad + { }^{m} C_{2} a^{m-2} b^{3} + \ldots + { }^{m} C_{m-1} a^{2} b^{m-1} + { }^{m} C_{m-1} a b^{m} + { }^{m} C_{m} a b^{m} + { }^{m} C_{m} b^{m+1} \\
&= { }^{m} C_{0} a^{m+1} + ({ }^{m} C_{0} + { }^{m} C_{1}) a^{m} b + ({ }^{m} C_{1} + { }^{m} C_{2}) a^{m-1} b^{2} + \ldots \\
& \quad + ({ }^{m} C_{m-1} + { }^{m} C_{m}) a b^{m} + { }^{m} C_{m} b^{m+1} \\
&= { }^{m+1} C_{0} a^{m+1} + { }^{m+1} C_{1} a^{m} b + { }^{m+1} C_{2} a^{m-1} b^{2} + \ldots + { }^{m+1} C_{m} a b^{m} + { }^{m+1} C_{m+1} b^{m+1}
\end{aligned}
$$
$[\because { }^{m} C_{0} = 1 = { }^{m+1} C_{0}, { }^{m} C_{m} = 1 = { }^{m+1} C_{m+1} \text{ and } { }^{m} C_{r-1} + { }^{m} C_{r} = { }^{m+1} C_{r}]$.

This shows that $P(m+1)$ is true, whenever $P(m)$ is true.
Hence, by the principle of mathematical induction the theorem is true for all $n \in N$.

**REMARK** ${ }^{n} C_{0}, { }^{n} C_{1}, { }^{n} C_{2}, \ldots, { }^{n} C_{n}$ are known as **binomial coefficients**. We may write the above result as:
$$
(a+b)^{n} = \sum_{r=0}^{n} {}^{n} C_{r} a^{n-r} b^{r}
$$

---

## Some Observations in a Binomial Expansion

1.  The expansion of $(a+b)^{n}$ has $(n+1)$ terms.
2.  Since ${ }^{n} C_{r} = { }^{n} C_{n-r}$, we have ${ }^{n} C_{0} = { }^{n} C_{n}, { }^{n} C_{1} = { }^{n} C_{n-1}$, and so on. Thus, the coefficients of the terms equidistant from the beginning and the end in a binomial expansion are equal.
3.  **General term** in the expansion of $(a+b)^{n}$ is the $(r+1)$-th term given by $T_{r+1} = { }^{n} C_{r} a^{n-r} b^{r}$.
4.  In the expansion of $(a+b)^{n}$, there are $(n+1)$ terms.
    -   When $n$ is even, the **middle term** = $(\frac{n}{2}+1)$-th term.
    -   When $n$ is odd, two **middle terms** are $\frac{1}{2}(n+1)$-th term and $\{\frac{1}{2}(n+1)+1\}$-th term.
5.  The $p$-th term from the end in $(a+b)^{n}$
    -   = $(n+1-p+1)$-th term from the beginning
    -   = $(n-p+2)$-th term from the beginning.
6.  **Results on binomial coefficients**
    We have the binomial expansion:
    $$
    (a+b)^{n} = { }^{n} C_{0} a^{n} + { }^{n} C_{1} a^{n-1} b + { }^{n} C_{2} a^{n-2} b^{2} + \ldots + { }^{n} C_{n-1} a b^{n-1} + { }^{n} C_{n} b^{n} \quad \text{(A)}
    $$
    Putting $a=b=1$ in (A), we get
    $$
    { }^{n} C_{0} + { }^{n} C_{1} + { }^{n} C_{2} + { }^{n} C_{3} + \ldots + { }^{n} C_{n} = 2^{n} \quad \text{(B)}
    $$
    Putting $a=1$ and $b=-1$ in (A) and using (B), we get
    $$
    { }^{n} C_{0} + { }^{n} C_{2} + { }^{n} C_{4} + \ldots = { }^{n} C_{1} + { }^{n} C_{3} + { }^{n} C_{5} + \ldots = \frac{2^{n}}{2} = 2^{n-1}
    $$
    Hence, ${ }^{n} C_{0} + { }^{n} C_{2} + { }^{n} C_{4} + \ldots = { }^{n} C_{1} + { }^{n} C_{3} + { }^{n} C_{5} + \ldots = 2^{n-1}$

---

## Deductions

1.  Putting $a=1$ and $b=x$ in the binomial expansion of $(a+b)^{n}$, we get
    $$
    (1+x)^{n} = { }^{n} C_{0} + { }^{n} C_{1} x + { }^{n} C_{2} x^{2} + \ldots + { }^{n} C_{n} x^{n}
    $$
    Thus, $(1+x)^{n} = \sum_{r=0}^{n} {}^{n} C_{r} x^{r}$. And, $T_{r+1} = { }^{n} C_{r} x^{r}$.
2.  Replacing $b$ by $-b$ in the binomial expansion of $(a+b)^{n}$, we get
    $$
    (a-b)^{n} = { }^{n} C_{0} a^{n} - { }^{n} C_{1} a^{n-1} b + { }^{n} C_{2} a^{n-2} b^{2} - { }^{n} C_{3} a^{n-3} b^{3} + \ldots
    $$
    $$
    \Rightarrow (a-b)^{n} = \sum_{r=0}^{n}(-1)^{r} \cdot { }^{n} C_{r} a^{n-r} b^{r}
    $$
    $\therefore T_{r+1}$ in the expansion of $(a-b)^{n}$ is given by
    $$
    T_{r+1} = (-1)^{r} \cdot { }^{n} C_{r} a^{n-r} b^{r}
    $$
3.  Putting $a=1$ and $b=x$ in the above expansion, we get
    $$
    (1-x)^{n} = { }^{n} C_{0} - { }^{n} C_{1} x + { }^{n} C_{2} x^{2} - { }^{n} C_{3} x^{3} + \ldots + (-1)^{n} \cdot { }^{n} C_{n} x^{n}
    $$
    $$
    \Rightarrow (1-x)^{n} = \sum_{r=0}^{n}(-1)^{r} \cdot { }^{n} C_{r} x^{r} .
    $$
    $\therefore T_{r+1}$ in the expansion of $(1-x)^{n}$ is given by
    $$
    T_{r+1} = (-1)^{r} \cdot { }^{n} C_{r} x^{r}
    $$

---

## Summary

1.  We have
    -   (i) $(a+b)^{n} = \sum_{r=0}^{n} { }^{n} C_{r} a^{n-r} b^{r}$ and $T_{r+1} = { }^{n} C_{r} a^{n-r} b^{r}$.
    -   (ii) $(a-b)^{n} = \sum_{r=0}^{n}(-1)^{r} \cdot { }^{n} C_{r} a^{n-r} b^{r}$ and $T_{r+1} = (-1)^{r} \cdot { }^{n} C_{r} a^{n-r} b^{r}$.
    -   (iii) When $n$ is even, then the middle term = $(\frac{n}{2}+1)$-th term.
    -   (iv) When $n$ is odd, then the middle terms are $\frac{1}{2}(n+1)$-th and $\{\frac{1}{2}(n+1)+1\}$-th.
    -   (v) $p$-th term from the end = $(n-p+2)$-th term from the beginning.
2.  -   (i) $(1+x)^{n} = \sum_{r=0}^{n} { }^{n} C_{r} x^{r}$ and $T_{r+1} = { }^{n} C_{r} x^{r}$.
    -   (ii) $(1-x)^{n} = \sum_{r=0}^{n}(-1)^{r} \cdot { }^{n} C_{r} x^{r}$ and $T_{r+1} = (-1)^{r} \cdot { }^{n} C_{r} x^{r}$.
3.  -   (i) ${ }^{n} C_{0} + { }^{n} C_{1} + { }^{n} C_{2} + \ldots + { }^{n} C_{n} = 2^{n}$.
    -   (ii) ${ }^{n} C_{0} + { }^{n} C_{2} + { }^{n} C_{4} + \ldots = { }^{n} C_{1} + { }^{n} C_{3} + { }^{n} C_{5} + \ldots = 2^{n-1}$.

---

## Solved Examples

### Example 1

Expand $\left(x^{2}+2 y\right)^{5}$ using binomial expansion.

#### Solution:

Using the binomial expansion, we have
$$
\begin{aligned}
\left(x^{2}+2 y\right)^{5} &= { }^{5} C_{0}\left(x^{2}\right)^{5} + { }^{5} C_{1}\left(x^{2}\right)^{4}(2 y) + { }^{5} C_{2}\left(x^{2}\right)^{3}(2 y)^{2} \\
& \quad + { }^{5} C_{3}\left(x^{2}\right)^{2}(2 y)^{3} + { }^{5} C_{4} x^{2}(2 y)^{4} + { }^{5} C_{5}(2 y)^{5} \\
&= x^{10} + 10 x^{8} y + 40 x^{6} y^{2} + 80 x^{4} y^{3} + 80 x^{2} y^{4} + 32 y^{5}
\end{aligned}
$$

---

### Example 2

Expand $\left(x^{3}-\frac{2}{x^{2}}\right)^{6}$ using binomial expansion.

#### Solution:

Using the binomial expansion, we get
$$
\begin{aligned}
\left(x^{3}-\frac{2}{x^{2}}\right)^{6} &= { }^{6} C_{0}\left(x^{3}\right)^{6} - { }^{6} C_{1}\left(x^{3}\right)^{5}\left(\frac{2}{x^{2}}\right) + { }^{6} C_{2}\left(x^{3}\right)^{4}\left(\frac{2}{x^{2}}\right)^{2} - { }^{6} C_{3}\left(x^{3}\right)^{3}\left(\frac{2}{x^{2}}\right)^{3} \\
& \quad + { }^{6} C_{4}\left(x^{3}\right)^{2}\left(\frac{2}{x^{2}}\right)^{4} - { }^{6} C_{5} x^{3}\left(\frac{2}{x^{2}}\right)^{5} + { }^{6} C_{6}\left(\frac{2}{x^{2}}\right)^{6} \\
&= x^{18} - 12 x^{13} + 60 x^{8} - 160 x^{3} + \frac{240}{x^{2}} - \frac{192}{x^{7}} + \frac{64}{x^{12}}
\end{aligned}
$$

---

### Example 3

Expand $\left(1+x+x^{2}\right)^{3}$ using binomial expansion.

#### Solution:

Put $1+x=y$. Then,
$\left(1+x+x^{2}\right)^{3} = \left(y+x^{2}\right)^{3}$
$$
\begin{aligned}
&= { }^{3} C_{0} y^{3} + { }^{3} C_{1} y^{2} x^{2} + { }^{3} C_{2} y\left(x^{2}\right)^{2} + { }^{3} C_{3}\left(x^{2}\right)^{3} \\
&= y^{3} + 3 y^{2} x^{2} + 3 y x^{4} + x^{6} \\
&= (1+x)^{3} + 3 x^{2}(1+x)^{2} + 3 x^{4}(1+x) + x^{6} \quad [\because y=(1+x)] \\
&= \left(1+{ }^{3} C_{1} x+{ }^{3} C_{2} x^{2}+{ }^{3} C_{3} x^{3}\right) + 3 x^{2}\left(1+2 x+x^{2}\right) + 3 x^{4}(1+x) + x^{6} \\
&= \left(1+3 x+3 x^{2}+x^{3}\right) + \left(3 x^{2}+6 x^{3}+3 x^{4}\right) + \left(3 x^{4}+3 x^{5}\right) + x^{6} \\
&= x^{6} + 3 x^{5} + 6 x^{4} + 7 x^{3} + 6 x^{2} + 3 x + 1 .
\end{aligned}
$$
Hence, $\left(1+x+x^{2}\right)^{3} = x^{6} + 3 x^{5} + 6 x^{4} + 7 x^{3} + 6 x^{2} + 3 x + 1$.

---

### Example 4

Expand $\left(1-x+x^{2}\right)^{4}$ using binomial expansion.

#### Solution:

Put $1-x=y$. Then,
$$
\begin{aligned}
\left(1-x+x^{2}\right)^{4} &= \left(y+x^{2}\right)^{4} \\
&= { }^{4} C_{0} y^{4} + { }^{4} C_{1} y^{3} x^{2} + { }^{4} C_{2} y^{2}\left(x^{2}\right)^{2} + { }^{4} C_{3} y\left(x^{2}\right)^{3} + { }^{4} C_{4}\left(x^{2}\right)^{4} \\
&= y^{4} + 4 y^{3} x^{2} + 6 y^{2} x^{4} + 4 y x^{6} + x^{8} \\
&= (1-x)^{4} + 4(1-x)^{3} x^{2} + 6(1-x)^{2} x^{4} + 4(1-x) x^{6} + x^{8} \quad [\because y=1-x] \\
&= \left(1-{ }^{4} C_{1} x+{ }^{4} C_{2} x^{2}-{ }^{4} C_{3} x^{3}+{ }^{4} C_{4} x^{4}\right) \\
& \quad + 4 x^{2}\left(1-{ }^{3} C_{1} x+{ }^{3} C_{2} x^{2}-{ }^{3} C_{3} x^{3}\right) \\
& \quad + 6 x^{4}\left(1-2 x+x^{2}\right) + 4 x^{6}(1-x) + x^{8} \\
&= \left(1-4 x+6 x^{2}-4 x^{3}+x^{4}\right) + 4 x^{2}\left(1-3 x+3 x^{2}-x^{3}\right) \\
& \quad + 6 x^{4}\left(1-2 x+x^{2}\right) + 4 x^{6}(1-x) + x^{8} \\
&= \left(1-4 x+6 x^{2}-4 x^{3}+x^{4}\right) + \left(4 x^{2}-12 x^{3}+12 x^{4}-4 x^{5}\right) \\
& \quad + \left(6 x^{4}-12 x^{5}+6 x^{6}\right) + \left(4 x^{6}-4 x^{7}\right) + x^{8} \\
&= x^{8} - 4 x^{7} + 10 x^{6} - 16 x^{5} + 19 x^{4} - 16 x^{3} + 10 x^{2} - 4 x + 1
\end{aligned}
$$
Hence, $\left(1-x+x^{2}\right)^{4} = x^{8}-4 x^{7}+10 x^{6}-16 x^{5}+19 x^{4}-16 x^{3}+10 x^{2}-4 x+1$.

---

### Example 5

Expand $\left\{(a+b)^{4}+(a-b)^{4}\right\}$ and use it to evaluate $\left(x^{2}+\sqrt{1-x^{2}}\right)^{4}+\left(x^{2}-\sqrt{1-x^{2}}\right)^{4}$.

#### Solution:

We have
$$
\begin{align*}
(a+b)^{4}+(a-b)^{4} &= \left[{ }^{4} C_{0} a^{4}+{ }^{4} C_{1} a^{3} b+{ }^{4} C_{2} a^{2} b^{2}+{ }^{4} C_{3} a b^{3}+{ }^{4} C_{4} b^{4}\right] \\
& \quad +\left[{ }^{4} C_{0} a^{4}-{ }^{4} C_{1} a^{3} b+{ }^{4} C_{2} a^{2} b^{2}-{ }^{4} C_{3} a b^{3}+{ }^{4} C_{4} b^{4}\right] \\
&= 2\left[{ }^{4} C_{0} a^{4}+{ }^{4} C_{2} a^{2} b^{2}+{ }^{4} C_{4} b^{4}\right] \quad \text{(i)}
\end{align*}
$$
Putting $\sqrt{1-x^{2}}=y$, we get
$$
\begin{aligned}
\left(x^{2}+\sqrt{1-x^{2}}\right)^{4} + \left(x^{2}-\sqrt{1-x^{2}}\right)^{4} &= \left(x^{2}+y\right)^{4}+\left(x^{2}-y\right)^{4} \\
&= 2\left[{ }^{4} C_{0}\left(x^{2}\right)^{4} + { }^{4} C_{2}\left(x^{2}\right)^{2} y^{2} + { }^{4} C_{4} y^{4}\right] \quad [\text{taking } a=x^{2} \text{ and } b=y \text{ in (i)}] \\
&= 2\left[x^{8} + 6 x^{4} y^{2} + y^{4}\right] \\
&= 2\left[x^{8} + 6 x^{4}\left(1-x^{2}\right) + \left(1-x^{2}\right)^{2}\right] \quad \left[\because y^{2}=\left(1-x^{2}\right)\right] \\
&= 2\left[x^{8} + \left(6 x^{4}-6 x^{6}\right) + \left(1-2 x^{2}+x^{4}\right)\right] \\
&= 2\left[x^{8} - 6 x^{6} + 7 x^{4} - 2 x^{2} + 1\right] \\
&= 2 x^{8} - 12 x^{6} + 14 x^{4} - 4 x^{2} + 2 .
\end{aligned}
$$

---

### Example 6

Find the 10th term in the expansion of $\left(2 x^{2}+\frac{1}{x}\right)^{12}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1} = { }^{12} C_{r} \times\left(2 x^{2}\right)^{(12-r)} \times\left(\frac{1}{x}\right)^{r} \quad \text{(i)}
$$
$$
\begin{align*}
\therefore \quad T_{10} &= T_{(9+1)} \\
&= { }^{12} C_{9} \times\left(2 x^{2}\right)^{(12-9)} \times\left(\frac{1}{x}\right)^{9} \\
&= { }^{12} C_{3} \times\left(2 x^{2}\right)^{3} \times\left(\frac{1}{x^{9}}\right) \quad\left[\because{ }^{12} C_{9}={ }^{12} C_{(12-9)}={ }^{12} C_{3}\right] \\
&= \left(\frac{12 \times 11 \times 10}{3 \times 2 \times 1} \times 8 x^{6} \times \frac{1}{x^{9}}\right) = \frac{1760}{x^{3}} .
\end{align*}
$$
Hence, the 10th term in the given expansion is $\frac{1760}{x^{3}}$.

---

### Example 7

Find the 6th term in the expansion of $\left(\frac{4 x}{5}-\frac{5}{2 x}\right)^{9}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1} = (-1)^{r} \times{ }^{9} C_{r} \times\left(\frac{4 x}{5}\right)^{(9-r)} \times\left(\frac{5}{2 x}\right)^{r} \quad \text{(i)}
$$
$$
\begin{align*}
\therefore \quad T_{6} &= T_{(5+1)} \\
&= (-1)^{5} \times{ }^{9} C_{5} \times\left(\frac{4 x}{5}\right)^{(9-5)} \times\left(\frac{5}{2 x}\right)^{5} \\
&= -{ }^{9} C_{4} \times\left(\frac{4 x}{5}\right)^{4} \times\left(\frac{5}{2 x}\right)^{5} \\
&= -\left[\frac{9 \times 8 \times 7 \times 6}{4 \times 3 \times 2 \times 1} \times \frac{2^{8} x^{4}}{5^{4}} \times \frac{5^{5}}{2^{5} x^{5}}\right] = \frac{-5040}{x} .
\end{align*}
$$
Hence, the 6th term in the given expansion is $\frac{-5040}{x}$.

---

### Example 8

Find the 4th term from the end in the expansion of $\left(\frac{x^{3}}{2}-\frac{2}{x^{2}}\right)^{9}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1}=(-1)^{r} \times { }^{9} C_{r} \times \left(\frac{x^{3}}{2}\right)^{(9-r)} \times \left(\frac{2}{x^{2}}\right)^{r} \quad \text{(i)}
$$
Now, $p$-th term from the end = $(n-p+2)$-th term from the beginning.
$\therefore \quad$ 4th term from the end
= $(9-4+2)$-th term from the beginning $[\because n=9, p=4]$
= 7th term from the beginning
$$
\begin{aligned}
&= T_{7} = T_{(6+1)} \\
&= (-1)^{6} \times { }^{9} C_{6} \times \left(\frac{x^{3}}{2}\right)^{(9-6)} \times \left(\frac{2}{x^{2}}\right)^{6} \quad [\text{putting } r=6 \text{ in (i)}] \\
&= { }^{9} C_{3} \times \left(\frac{x^{3}}{2}\right)^{3} \times \left(\frac{2}{x^{2}}\right)^{6} \quad \left[\because{ }^{9} C_{6}={ }^{9} C_{(9-6)}={ }^{9} C_{3}\right] \\
&= \left(\frac{9 \times 8 \times 7}{3 \times 2 \times 1} \times \frac{x^{9}}{8} \times \frac{64}{x^{12}}\right) = \frac{672}{x^{3}} .
\end{aligned}
$$
Hence, the 4th term from the end is $\frac{672}{x^{3}}$.

---

### Example 9

If the ratio of the 5th term from the beginning to the 5th term from the end in the expansion of $\left(\sqrt[4]{2}+\frac{1}{\sqrt[4]{3}}\right)^{n}$ is $\sqrt{6} : 1$ then find the value of $n$.

#### Solution:

The given expression may be written as $\left(2^{\frac{1}{4}}+3^{-\frac{1}{4}}\right)^{n}$. The general term in this expansion is given by
$$
T_{r+1} = { }^{n} C_{r} \times \left(2^{\frac{1}{4}}\right)^{(n-r)} \times \left(3^{-\frac{1}{4}}\right)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = { }^{n} C_{r} \times 2^{\frac{(n-r)}{4}} \times 3^{\left(\frac{-r}{4}\right)} \quad \text{(i)}
$$
Now, $p$-th term from the end = $(n-p+2)$-th term from the beginning.
$\therefore \quad$ 5th term from the end = $(n-5+2)$-th term from the beginning = $(n-3)$-th term from the beginning.
Now, $T_{5} = T_{(4+1)}$
$$
= { }^{n} C_{4} \times 2^{\frac{(n-4)}{4}} \times 3^{\left(\frac{-4}{4}\right)} = { }^{n} C_{4} \times 2^{\frac{(n-4)}{4}} \times 3^{-1} \quad \text{(ii)}
$$
And, $T_{n-3} = T_{(n-4)+1}$
$$
= { }^{n} C_{n-4} \times 2^{1} \times 3^{\frac{-(n-4)}{4}} \quad [\text{putting } r=(n-4) \text{ in (i)}]
$$
$$
= { }^{n} C_{4} \times 2 \times 3^{\frac{-(n-4)}{4}} \quad \text{(iii)}
$$
$$
\begin{align*}
\therefore \quad \frac{T_{5}}{T_{n-3}} &= \frac{\sqrt{6}}{1} \\
\Rightarrow \quad \frac{{ }^{n} C_{4} \times 2^{\frac{(n-4)}{4}} \times 3^{-1}}{{ }^{n} C_{4} \times 2 \times 3^{\frac{-(n-4)}{4}}} &= \frac{\sqrt{6}}{1} \\
\Rightarrow \quad 2^{\left\{\frac{(n-4)}{4}-1\right\}} \times 3^{\left\{-1 - \frac{-(n-4)}{4}\right\}} &= \sqrt{6} \\
\Rightarrow \quad 2^{\frac{(n-8)}{4}} \times 3^{\frac{(n-8)}{4}} &= 6^{1 / 2} \\
\Rightarrow \quad (2 \times 3)^{\frac{(n-8)}{4}} &= 6^{1 / 2} \\
\Rightarrow \quad \frac{n-8}{4} = \frac{1}{2} \Rightarrow n-8=2 \Rightarrow n=10.
\end{align*}
$$
Hence, $n=10$.

---

### Example 10

Find the term independent of $x$ in the expansion of $\left(\frac{3 x^{2}}{2}-\frac{1}{3 x}\right)^{15}$.

#### Solution:

Let $T_{r+1}$ be independent of $x$.
Here, $T_{r+1} = (-1)^{r} \times { }^{15} C_{r} \times \left(\frac{3 x^{2}}{2}\right)^{(15-r)} \times \left(\frac{1}{3 x}\right)^{r}$
$$
\Rightarrow \quad T_{r+1} = (-1)^{r} \times { }^{15} C_{r} \times 3^{(15-2 r)} \times 2^{(r-15)} \times x^{(30-3 r)} \quad \text{(i)}
$$
Now, $T_{r+1}$ will be independent of $x$ only when the power of $x$ in it is 0.
$$
\therefore \quad 30-3 r=0 \Rightarrow 3 r=30 \Rightarrow r=10 \Rightarrow r+1=11.
$$
Thus, $T_{11}$ is independent of $x$.
Now, $T_{11} = T_{(10+1)}$
$$
\begin{aligned}
&= (-1)^{10} \times { }^{15} C_{10} \times 3^{(15-20)} \times 2^{(10-15)} \times x^{0} \quad [\text{putting } r=10 \text{ in (i)}] \\
&= { }^{15} C_{5} \times 3^{-5} \times 2^{-5} = \frac{{ }^{15} C_{5}}{6^{5}} \quad \left[\because{ }^{15} C_{10}={ }^{15} C_{(15-10)}={ }^{15} C_{5}\right] \\
&= \left(\frac{15 \times 14 \times 13 \times 12 \times 11}{5 \times 4 \times 3 \times 2 \times 1} \times \frac{1}{7776}\right) = \frac{3003}{7776} = \frac{1001}{2592}
\end{aligned}
$$
Hence, the term independent of $x$ in the given expansion is $\frac{1001}{2592}$.

---

### Example 11

Find the term independent of $x$ in the expansion of $\left(\frac{\sqrt{x}}{\sqrt{3}}+\frac{\sqrt{3}}{2 x^{2}}\right)^{10}$.

#### Solution:

Let $T_{r+1}$ be independent of $x$.
Here, $T_{r+1} = { }^{10} C_{r} \times \left(\sqrt{\frac{x}{3}}\right)^{(10-r)} \times \left(\frac{\sqrt{3}}{2 x^{2}}\right)^{r}$
$$
\begin{align*}
\Rightarrow \quad T_{r+1} &= { }^{10} C_{r} \times \left(\frac{x}{3}\right)^{\frac{(10-r)}{2}} \times 3^{\frac{r}{2}} \times \frac{1}{2^{r} x^{2r}} \\
&= { }^{10} C_{r} \times x^{\left(5-\frac{r}{2}-2 r\right)} \times \frac{1}{3^{\left(5-\frac{r}{2}\right)}} \times 3^{\frac{r}{2}} \times 2^{-r} \\
&= { }^{10} C_{r} \times x^{\left(5-\frac{5 r}{2}\right)} \times 3^{(r-5)} \times 2^{-r} \quad \text{(i)}
\end{align*}
$$
Now, $T_{r+1}$ will be independent of $x$ only when the power of $x$ in it is 0.
$$
\therefore \quad 5-\frac{5 r}{2}=0 \Rightarrow \frac{5 r}{2}=5 \Rightarrow r=2 \Rightarrow r+1=3.
$$
Thus, $T_{3}$ is independent of $x$.
Putting $r=2$ in (i), we get
$$
\begin{aligned}
T_{3} &= T_{(2+1)} \\
&= { }^{10} C_{2} \times 3^{(2-5)} \times 2^{-2} \times x^{0} = \left(\frac{10 \times 9}{2 \times 1} \times 3^{-3} \times 2^{-2}\right) \\
&= \left(\frac{45}{3^{3} \times 2^{2}}\right) = \left(\frac{45}{27 \times 4}\right) = \frac{5}{12}
\end{aligned}
$$
Hence, the term independent of $x$ in the given expansion is $\frac{5}{12}$.

---

### Example 12

If the term free from $x$ in the expansion of $\left(\sqrt{x}-\frac{m}{x^{2}}\right)^{10}$ is 405, find the value of $m$.

#### Solution:

The general term in the given expansion is given by
$$
\begin{align*}
T_{r+1} &= (-1)^{r} \times { }^{10} C_{r} \times (\sqrt{x})^{(10-r)} \times \left(\frac{m}{x^{2}}\right)^{r} \\
&= (-1)^{r} \times { }^{10} C_{r} \times x^{\left(5-\frac{r}{2}\right)} \times \frac{m^{r}}{x^{2r}} \\
&= (-1)^{r} \times { }^{10} C_{r} \times x^{\left(5-\frac{r}{2}-2 r\right)} \times m^{r} \\
&= (-1)^{r} \times { }^{10} C_{r} \times x^{\left(5-\frac{5 r}{2}\right)} \times m^{r} \quad \text{(i)}
\end{align*}
$$
Let $T_{r+1}$ be free from $x$. Then, the power of $x$ in $T_{r+1}$ must be 0.
$$
\therefore \quad 5-\frac{5 r}{2}=0 \Rightarrow \frac{5 r}{2}=5 \Rightarrow r=2 \Rightarrow r+1=3.
$$
So, $T_{3}$ will be free from $x$.
Now, $T_{3} = T_{(2+1)}$
$$
\begin{align*}
&= (-1)^{2} \times { }^{10} C_{2} \times x^{0} \times m^{2} \quad \text{[putting } r=2 \text{ in (i)]} \\
&= \left(\frac{10 \times 9}{2} \times m^{2}\right) = 45 m^{2}
\end{align*}
$$
But, it is given that the term free from $x$ is 405.
$$
\therefore \quad 45 m^{2}=405 \Rightarrow m^{2}=9 \Rightarrow m= \pm 3
$$
Hence, $m= \pm 3$.

---

### Example 13

Find the coefficients of $x^{32}$ and $\frac{1}{x^{17}}$ in the expansion of $\left(x^{4}-\frac{1}{x^{3}}\right)^{15}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1} = (-1)^{r} \times { }^{15} C_{r} \times \left(x^{4}\right)^{(15-r)} \times \left(\frac{1}{x^{3}}\right)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = (-1)^{r} \times { }^{15} C_{r} \times x^{(60-7 r)} \quad \text{(i)}
$$
Putting $60-7 r=32$, we get $7 r=28 \Rightarrow r=4 \Rightarrow r+1=5$.
Now, $T_{5} = T_{(4+1)} = (-1)^{4} \times { }^{15} C_{4} \times x^{(60-28)} = { }^{15} C_{4} \times x^{32}$.
$\therefore \quad$ coefficient of $x^{32} = { }^{15} C_{4} = \left(\frac{15 \times 14 \times 13 \times 12}{4 \times 3 \times 2 \times 1}\right) = 1365$.

Let $T_{s+1}$ be the term containing $x^{-17} \left[\because \frac{1}{x^{17}}=x^{-17}\right]$.
Then, $T_{s+1} = (-1)^{s} \times { }^{15} C_{s} \times x^{(60-7 s)}$. ... (ii) [putting $r=s$ in (i)]
Putting $60-7 s=-17$, we get $s=11$ and therefore, $s+1=12$.
Thus, the 12th term contains $x^{-17}$.
Now, $T_{12} = T_{(11+1)}$
$$
\begin{aligned}
&= (-1)^{11} \times { }^{15} C_{11} \times x^{(60-77)} \quad [\text{putting } s=11 \text{ in (ii)}] \\
&= -{ }^{15} C_{4} \times x^{-17}
\end{aligned}
$$
$\therefore \quad$ coefficient of $x^{-17} = -{ }^{15} C_{4} = -\left(\frac{15 \times 14 \times 13 \times 12}{4 \times 3 \times 2 \times 1}\right) = -1365$.
Hence, the coefficient of $x^{32}$ is 1365 and that of $x^{-17}$ is -1365.

---

### Example 14

Prove that there is no term containing $x^{10}$ in the expansion of $\left(x^{2}-\frac{2}{x}\right)^{18}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1} = (-1)^{r} \times { }^{18} C_{r} \times \left(x^{2}\right)^{(18-r)} \times \left(\frac{2}{x}\right)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = (-1)^{r} \times { }^{18} C_{r} \times 2^{r} \times x^{(36-3 r)}
$$
Let $T_{r+1}$ contain $x^{10}$. Then,
$$
36-3 r=10 \Rightarrow 3 r=26 \Rightarrow r=\frac{26}{3}
$$
Since the value of $r$ cannot be a fraction, so there is no term containing $x^{10}$.

---

### Example 15

Find the middle term in the expansion of $\left(a x-\frac{b}{x^{2}}\right)^{12}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1} = (-1)^{r} \times { }^{12} C_{r} \times (a x)^{(12-r)} \times \left(\frac{b}{x^{2}}\right)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = (-1)^{r} \times { }^{12} C_{r} \times a^{(12-r)} \times b^{r} \times x^{(12-3 r)} \quad \text{(i)}
$$
Since the given binomial contains an even power, so it has only one middle term.
Middle term = $\left(\frac{12}{2}+1\right)$-th term = 7th term.
Now, $T_{7}=T_{(6+1)}$
$$
\begin{aligned}
&= (-1)^{6} \times { }^{12} C_{6} \times a^{(12-6)} \times b^{6} \times x^{(12-3 \times 6)} \quad [\text{putting } r=6 \text{ in (i)}] \\
&= { }^{12} C_{6} \times a^{6} b^{6} \times x^{-6} \\
&= \left(\frac{12 \times 11 \times 10 \times 9 \times 8 \times 7}{6 \times 5 \times 4 \times 3 \times 2 \times 1} \times \frac{a^{6} b^{6}}{x^{6}}\right) = \frac{924 a^{6} b^{6}}{x^{6}} .
\end{aligned}
$$
Hence, the middle term in the given expansion is $\frac{924 a^{6} b^{6}}{x^{6}}$.

---

### Example 16

Find the middle terms in the expansion of $\left(3 x-\frac{x^{3}}{6}\right)^{7}$.

#### Solution:

The general term in the given expansion is given by
$$
T_{r+1} = (-1)^{r} \times { }^{7} C_{r} \times (3 x)^{7-r} \times \left(\frac{x^{3}}{6}\right)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = (-1)^{r} \times { }^{7} C_{r} \times 3^{(7-2 r)} \times 2^{-r} \times x^{(7+2 r)} \quad \text{(i)}
$$
Clearly, the given expansion has 8 terms. So, it has two middle terms, namely $(\frac{8}{2})$-th, i.e., 4th and 5th.
Now, $T_{4}=T_{(3+1)}$
$$
\begin{aligned}
&= (-1)^{3} \times { }^{7} C_{3} \times 3^{(7-6)} \times 2^{-3} \times x^{13} \quad [\text{putting } r=3 \text{ in (i)}] \\
&= -\left(\frac{7 \times 6 \times 5}{3 \times 2 \times 1} \times 3^{1} \times \frac{1}{2^{3}} \times x^{13}\right) \\
&= -\left(\frac{35 \times 3 \times x^{13}}{8}\right) = \frac{-105 x^{13}}{8} .
\end{aligned}
$$
And, $T_{5}=T_{(4+1)}$
$$
\begin{aligned}
&= (-1)^{4} \times { }^{7} C_{4} \times 3^{(7-8)} \times 2^{-4} \times x^{15} \quad [\text{putting } r=4 \text{ in (i)}] \\
&= { }^{7} C_{3} \times 3^{-1} \times 2^{-4} \times x^{15} \quad \left[\because{ }^{7} C_{4}={ }^{7} C_{(7-4)}={ }^{7} C_{3}\right] \\
&= \left(\frac{7 \times 6 \times 5}{3 \times 2 \times 1} \times \frac{1}{3} \times \frac{1}{2^{4}} \times x^{15}\right) = \frac{35 x^{15}}{48} .
\end{aligned}
$$
Hence, the required middle terms are $\frac{-105 x^{13}}{8}$ and $\frac{35 x^{15}}{48}$.

---

### Example 17

Show that the middle term in the expansion of $(1+x)^{2 n}$ is $\frac{1 \cdot 3 \cdot 5 \ldots(2 n-1)}{n!} \cdot 2^{n} \cdot x^{n}$, where $n \in N$.

#### Solution:

Clearly, the number of terms in the expansion of $(1+x)^{2 n}$ is $(2 n+1)$.
$\therefore \quad$ middle term = $\left(\frac{2 n}{2}+1\right)$-th term = $(n+1)$-th term = $T_{n+1}$.
Now, $T_{n+1} = { }^{2 n} C_{n} \cdot x^{n} = \frac{(2 n)!}{(n!) \times (n!)} \cdot x^{n}$
$$
\begin{aligned}
&= \frac{1 \cdot 2 \cdot 3 \cdot 4 \ldots(2 n-2)(2 n-1)(2 n)}{(n!) \times (n!)} \cdot x^{n} \\
&= \frac{[1 \cdot 3 \cdot 5 \ldots(2 n-3)(2 n-1)] \times [2 \cdot 4 \cdot 6 \ldots(2 n-2)(2 n)]}{(n!)(n!)} \cdot x^{n} \\
&= \frac{[1 \cdot 3 \cdot 5 \ldots(2 n-1)] \times 2^{n} \times [1 \cdot 2 \cdot 3 \ldots(n-1) \cdot n]}{(n!) \times (n!)} \cdot x^{n} \\
&= \frac{[1 \cdot 3 \cdot 5 \ldots(2 n-1)] \times 2^{n} \times x^{n}}{(n!)}
\end{aligned}
$$
Hence, the middle term in the given expansion is $\frac{1 \cdot 3 \cdot 5 \ldots(2 n-1) \times 2^{n} \times x^{n}}{(n!)}$.

---

### Example 18

If $x^{p}$ occurs in the expansion of $\left(x^{2}+\frac{1}{x}\right)^{2 n}$, prove that its coefficient is $\frac{(2 n)!}{\left\{\left(\frac{4 n-p}{3}\right)!\right\} \times \left\{\left(\frac{2 n+p}{3}\right)!\right\}}$.

#### Solution:

The general term in the expansion of $\left(x^{2}+\frac{1}{x}\right)^{2 n}$ is given by
$$
T_{r+1} = { }^{2 n} C_{r} \times \left(x^{2}\right)^{(2 n-r)} \times \left(\frac{1}{x}\right)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = { }^{2 n} C_{r} \times x^{(4 n-3 r)} \quad \text{(i)}
$$
This term contains $x^{p}$ only when $4 n-3 r=p$.
And, $4 n-3 r=p \Rightarrow r=\frac{(4 n-p)}{3}$.
Putting $4 n-3 r=p$ in (i), we get
coefficient of $x^{p} = { }^{2 n} C_{r}$, where $r=\frac{(4 n-p)}{3}$
$$
\begin{aligned}
&= \frac{(2 n)!}{(r!) \times (2 n-r)!} = \frac{(2 n)!}{\left\{\left(\frac{4 n-p}{3}\right)!\right\} \times \left\{\left[2 n-\frac{(4 n-p)}{3}\right]!\right\}} \\
&= \frac{(2 n)!}{\left\{\left(\frac{4 n-p}{3}\right)!\right\} \times \left\{\left(\frac{2 n+p}{3}\right)!\right\}}
\end{aligned}
$$
Hence, the coefficient of $x^{p}$ in the expansion of $\left(x^{2}+\frac{1}{x}\right)^{2 n}$ is $\frac{(2 n)!}{\left\{\left(\frac{4 n-p}{3}\right)!\right\} \times \left\{\left(\frac{2 n+p}{3}\right)!\right\}}$.

---

### Example 19

Show that the coefficient of the middle term in the expansion of $(1+x)^{2 n}$ is the sum of the coefficients of two middle terms in the expansion of $(1+x)^{2 n-1}$.

#### Solution:

The expansion of $(1+x)^{2 n}$ contains $(2 n+1)$ terms and therefore, the $(n+1)$-th term is the middle term.
$\therefore \quad$ the middle term in the expansion of $(1+x)^{2 n}$ is given by
$$
t_{n+1} = { }^{2 n} C_{n} x^{n} = \frac{(2 n)!}{(n!) \cdot (n!)} x^{n} = \frac{(2 n)!}{(n!)^{2}} x^{n}
$$
Thus, the coefficient of the middle term of $(1+x)^{2 n}$ is $\frac{(2 n)!}{(n!)^{2}}$.
Again, the expansion of $(1+x)^{2 n-1}$ contains $2 n$ terms.
So, the middle terms are the $n$-th and the ($n+1$)-th terms.
Now, $t_{n}=t_{(n-1)+1} = { }^{2 n-1} C_{n-1} x^{n-1}$ and $t_{n+1} = { }^{2 n-1} C_{n} x^{n}$.
$\therefore \quad$ the sum of the coefficients of the middle terms of $(1+x)^{2 n-1}$
$$
\begin{aligned}
&= { }^{2 n-1} C_{n-1} + { }^{2 n-1} C_{n} \\
&= { }^{2n} C_n \quad [\text{Using Pascal's Identity: } { }^{n} C_{r} + { }^{n} C_{r-1} = { }^{n+1} C_{r}] \\
&= \frac{(2 n)!}{(n!) \cdot (n!)} = \frac{(2 n)!}{(n!)^{2}} \\
&= \text{the coefficient of the middle term of } (1+x)^{2 n}.
\end{aligned}
$$

---

### Example 20

If $a_{1}, a_{2}, a_{3}, a_{4}$ be the coefficients of four consecutive terms in the expansion of $(1+x)^{n}$ then prove that $\frac{a_{1}}{\left(a_{1}+a_{2}\right)}+\frac{a_{3}}{\left(a_{3}+a_{4}\right)}=\frac{2 a_{2}}{\left(a_{2}+a_{3}\right)}$.

#### Solution:

Let $a_{1}, a_{2}, a_{3}$ and $a_{4}$ be the coefficients of the $r$-th, ($r+1$)-th, ($r+2$)-th and ($r+3$)-th terms in the expansion of $(1+x)^{n}$. Then,
$$
a_{1} = { }^{n} C_{r-1} ; a_{2} = { }^{n} C_{r}, a_{3} = { }^{n} C_{r+1} \text{ and } a_{4} = { }^{n} C_{r+2} .
$$
Now, $a_{1}+a_{2} = \left({ }^{n} C_{r-1}+{ }^{n} C_{r}\right) = { }^{n+1} C_{r}$;
$$
a_{3}+a_{4} = \left({ }^{n} C_{r+1}+{ }^{n} C_{r+2}\right) = { }^{n+1} C_{r+2} ;
$$
and $a_{2}+a_{3} = \left({ }^{n} C_{r}+{ }^{n} C_{r+1}\right) = { }^{n+1} C_{r+1}$.
$$
\begin{aligned}
\therefore \quad \frac{a_{1}}{\left(a_{1}+a_{2}\right)} + \frac{a_{3}}{\left(a_{3}+a_{4}\right)} &= \frac{{ }^{n} C_{r-1}}{{ }^{n+1} C_{r}} + \frac{{ }^{n} C_{r+1}}{{ }^{n+1} C_{r+2}} \\
&= \frac{{ }^{n} C_{r-1}}{\left(\frac{n+1}{r}\right) \cdot { }^{n} C_{r-1}} + \frac{{ }^{n} C_{r+1}}{\left(\frac{n+1}{r+2}\right) \cdot { }^{n} C_{r+1}} \quad \left[\because { }^{n} C_{r} = \left(\frac{n}{r}\right) \cdot { }^{n-1} C_{r-1}\right] \\
&= \frac{r}{(n+1)} + \frac{(r+2)}{(n+1)} = \frac{2(r+1)}{(n+1)} .
\end{aligned}
$$
And, $\frac{2 a_{2}}{\left(a_{2}+a_{3}\right)} = \frac{2 \times { }^{n} C_{r}}{{ }^{n+1} C_{r+1}} = \frac{2 \times { }^{n} C_{r}}{\left(\frac{n+1}{r+1}\right) \cdot { }^{n} C_{r}} = \frac{2(r+1)}{(n+1)}$.
Hence, $\frac{a_{1}}{\left(a_{1}+a_{2}\right)}+\frac{a_{3}}{\left(a_{3}+a_{4}\right)}=\frac{2 a_{2}}{\left(a_{2}+a_{3}\right)}$.

---

### Example 21

In the binomial expansion of $(1+x)^{m+n}$, prove that the coefficients of $x^{m}$ and $x^{n}$ are equal.

#### Solution:

In the binomial expansion of $(1+x)^{m+n}$, the general term is given by
$$
T_{r+1} = { }^{m+n} C_{r} \times x^{r} \quad \text{(i)}
$$
$\therefore \quad$ coefficient of $x^{m}$ in the expansion of $(1+x)^{m+n}$
$$
= { }^{m+n} C_{m} = \frac{(m+n)!}{\{(m+n-m)!\} \times (m!)} = \frac{(m+n)!}{(n!) \times (m!)}.
$$
coefficient of $x^{n}$ in the expansion of $(1+x)^{m+n}$
$$
= { }^{m+n} C_{n} = \frac{(m+n)!}{\{(m+n-n)!\} \times (n!)} = \frac{(m+n)!}{(m!) \times (n!)}.
$$
Hence, the coefficients of $x^{m}$ and $x^{n}$ are equal.

---

### Example 22

Find the value of $r$ when it is being given that the coefficients of $(2 r+4)$-th and $(r-2)$-th terms in the expansion of $(1+x)^{18}$ are equal.

#### Solution:

In the expansion of $(1+x)^{18}$, we have $T_{p+1}={ }^{18} C_{p} x^{p}$.
$$
\begin{align*}
\therefore \quad & T_{(2 r+4)} = T_{(2 r+3)+1} = { }^{18} C_{2 r+3} \cdot x^{2 r+3} \quad \text{(i)} \\
\text{ and } & T_{(r-2)} = T_{(r-3)+1} = { }^{18} C_{(r-3)} \cdot x^{r-3} \quad \text{(ii)}
\end{align*}
$$
It is being given that the coefficients of $T_{(2 r+4)}$ and $T_{(r-2)}$ are equal.
So, from (i) and (ii), we get
$$
{ }^{18} C_{2 r+3} = { }^{18} C_{r-3} \Rightarrow (2 r+3) = (r-3) \text{ or } (2 r+3) + (r-3) = 18
$$
$[\because { }^{n} C_{p} = { }^{n} C_{q} \Rightarrow p=q \text{ or } p+q=n]$.
Now, $(2 r+3)=(r-3)$ or $(2 r+3)+(r-3)=18$
$\Rightarrow \quad r=-6$ or $r=6$
$\Rightarrow \quad r=6 \quad [\because \text{ the negative value of } r \text{ is not permissible}]$.
Hence, $r=6$.

---

### Example 23

Find the coefficient of $x^{6} y^{3}$ in the expansion of $(x+2 y)^{9}$.

#### Solution:

The general term in the expansion of $(x+2 y)^{9}$ is given by
$$
T_{r+1} = { }^{9} C_{r} \times x^{(9-r)} \times (2 y)^{r}
$$
$$
\Rightarrow \quad T_{r+1} = { }^{9} C_{r} \times 2^{r} \times x^{(9-r)} \times y^{r} \quad \text{(i)}
$$
We have to find the coefficient of $x^{6} y^{3}$.
Putting $r=3$ in (i), we get
$$
T_{(3+1)} = { }^{9} C_{3} \times 2^{3} \times \left(x^{6} y^{3}\right)
$$
$\therefore \quad$ coefficient of $x^{6} y^{3}$ in the given expansion
$$
= \left({ }^{9} C_{3} \times 2^{3}\right) = \left(\frac{9 \times 8 \times 7}{3 \times 2 \times 1} \times 8\right) = 672 .
$$
Hence, the coefficient of $x^{6} y^{3}$ in the given expansion is 672.

---

### Example 24

Write down the binomial expansion of $(1+x)^{n+1}$ when $x=8$. Deduce that $(9^{n+1}-8 n-9)$ is divisible by 64, where $n$ is a positive integer.

#### Solution:

Using the binomial expansion, we get
$$
(1+x)^{n+1} = { }^{n+1} C_{0} + { }^{n+1} C_{1} x + { }^{n+1} C_{2} x^{2} + { }^{n+1} C_{3} x^{3} + \ldots + { }^{n+1} C_{n+1} x^{n+1}
$$
Putting $x=8$ in the above expansion, we get
$$
\begin{aligned}
9^{n+1} &= 1+(n+1) \times 8 + { }^{n+1} C_{2} \times (8)^{2} + { }^{n+1} C_{3} \times (8)^{3} + \ldots + { }^{n+1} C_{n+1} \times (8)^{n+1} \\
\Rightarrow \quad (9^{n+1}-8 n-9) &= (8)^{2} \times \left\{{ }^{n+1} C_{2} + { }^{n+1} C_{3} \times 8 + \ldots + (8)^{n-1}\right\} \\
\Rightarrow \quad (9^{n+1}-8 n-9) &= 64 \times (\text{an integer}) .
\end{aligned}
$$
Hence, $(9^{n+1}-8 n-9)$ is exactly divisible by 64.

---

### Example 25

Using the binomial theorem, prove that $(6^{n}-5 n)$ always leaves the remainder 1 when divided by 25.

#### Solution:

Using binomial expansion, we get
$$
\begin{aligned}
(6^{n}-5 n) &= (1+5)^{n}-5 n \\
&= \left\{{ }^{n} C_{0} + { }^{n} C_{1} \times 5 + { }^{n} C_{2} \times (5)^{2} + { }^{n} C_{3} \times (5)^{3} + \ldots + { }^{n} C_{n} \times 5^{n}\right\} - 5 n \\
&= \left\{1+5 n + { }^{n} C_{2} \times (5)^{2} + { }^{n} C_{3} \times (5)^{3} + \ldots + { }^{n} C_{n} \times 5^{n}\right\} - 5 n \\
&= 1 + (5)^{2} \times \left\{{ }^{n} C_{2} + { }^{n} C_{3} \times 5 + \ldots + { }^{n} C_{n} \times 5^{(n-2)}\right\} \\
&= 1 + 25 \times (\text{an integer})
\end{aligned}
$$
Hence, $(6^{n}-5 n)$ when divided by 25 leaves the remainder 1.

---

### Example 26

Show that $2^{4 n+4}-15 n-16$, where $n \in N$ is divisible by 225.

#### Solution:

We have
$$
2^{4 n+4}-15 n-16 = 2^{4(n+1)}-15 n-16 = 16^{(n+1)}-15 n-16
$$
Now, $16^{(n+1)}-15 n-16 = (1+15)^{n+1}-15 n-16$
$$
\begin{aligned}
&= { }^{n+1} C_{0} + { }^{n+1} C_{1} \times 15 + { }^{n+1} C_{2} \times (15)^{2} + { }^{n+1} C_{3} \times (15)^{3} + \ldots + { }^{n+1} C_{n+1} \times (15)^{n+1} - 15 n-16 \\
&= 1+(n+1) \times 15 + { }^{n+1} C_{2} \times (15)^{2} + { }^{n+1} C_{3} \times (15)^{3} + \ldots + (15)^{n+1} - 15 n - 16 \\
&= (15n + 15 - 15n - 15) + { }^{n+1} C_{2} \times (15)^{2} + { }^{n+1} C_{3} \times (15)^{3} + \ldots + (15)^{n+1} \\
&= (15)^{2} \times \left[{ }^{n+1} C_{2} + { }^{n+1} C_{3} \times 15 + \ldots + (15)^{n-1}\right] \\
&= 225 \times (\text{an integer})
\end{aligned}
$$
Hence, $(2^{4 n+4}-15 n-16)$ is divisible by 225.

---

### Example 27

If $a$ and $b$ are distinct integers then prove that $(a-b)$ is a factor of $(a^{n}-b^{n})$, whenever $n$ is a positive integer.

#### Solution:

We may write
$$
\begin{aligned}
a^{n} &= (a-b+b)^{n} = \{(a-b)+b\}^{n} \\
&= { }^{n} C_{0} \times (a-b)^{n} + { }^{n} C_{1} \times (a-b)^{(n-1)} \times b + \ldots + { }^{n} C_{n-1} \times (a-b) \times b^{n-1} + { }^{n} C_{n} \times b^{n} \\
&= (a-b)^{n} + n b(a-b)^{n-1} + \ldots + n b^{n-1}(a-b) + b^{n} \\
\Rightarrow \quad (a^{n}-b^{n}) &= (a-b)^{n} + n b(a-b)^{n-1} + \ldots + n b^{n-1}(a-b) \\
&= (a-b) \times \left[(a-b)^{n-1} + n b(a-b)^{n-2} + \ldots + n b^{n-1}\right] \quad [\text{taking }(a-b) \text{ common throughout}]
\end{aligned}
$$
Hence, $(a-b)$ is a factor of $(a^{n}-b^{n})$.

---

### Example 28

The second, third and fourth terms in the binomial expansion of $(x+a)^{n}$ are 240, 720 and 1080 respectively. Find $x, a$ and $n$.

#### Solution:

By the binomial expansion, we have
$$
(x+a)^{n} = { }^{n} C_{0} x^{n} + { }^{n} C_{1} x^{n-1} a + { }^{n} C_{2} x^{n-2} a^{2} + { }^{n} C_{3} x^{n-3} a^{3} + \ldots
$$
$$
\Rightarrow \quad (x+a)^{n} = x^{n} + n x^{n-1} a + \frac{n(n-1)}{2} x^{n-2} a^{2} + \frac{n(n-1)(n-2)}{6} x^{n-3} a^{3} + \ldots
$$
$\therefore \quad T_{2}=240 \Rightarrow n x^{n-1} a=240$ ... (i)
$T_{3}=720 \Rightarrow \frac{n(n-1)}{2} x^{n-2} a^{2} = 720 \Rightarrow n(n-1) x^{n-2} a^{2}=1440$ ... (ii)
$T_{4}=1080 \Rightarrow \frac{n(n-1)(n-2)}{6} x^{n-3} a^{3} = 1080 \Rightarrow n(n-1)(n-2) x^{n-3} a^{3}=6480$ ... (iii)

On dividing (ii) by (i), we get
$$
\frac{n(n-1) x^{n-2} a^{2}}{n x^{n-1} a} = \frac{1440}{240} \Rightarrow \frac{(n-1) a}{x} = 6 \Rightarrow \frac{a}{x} = \frac{6}{(n-1)} \quad \text{(iv)}
$$
On dividing (iii) by (ii), we get
$$
\frac{n(n-1)(n-2) x^{n-3} a^{3}}{n(n-1) x^{n-2} a^{2}} = \frac{6480}{1440} \Rightarrow \frac{(n-2) a}{x} = \frac{9}{2} \Rightarrow \frac{a}{x} = \frac{9}{2(n-2)} \quad \text{(v)}
$$
Equating the values of $\frac{a}{x}$ from (iv) and (v), we get
$$
\frac{6}{(n-1)} = \frac{9}{2(n-2)} \Rightarrow 12(n-2) = 9(n-1) \Rightarrow 12n-24 = 9n-9 \Rightarrow 3n=15 \Rightarrow n=5
$$
Putting $n=5$ in (i), we get $5x^{4}a = 240 \Rightarrow x^{4} a = 48$ ... (vi)
Putting $n=5$ in (iv), we get $\frac{a}{x} = \frac{6}{4} \Rightarrow \frac{a}{x} = \frac{3}{2} \Rightarrow a = \frac{3}{2} x$.
Putting $a = \frac{3}{2} x$ in (vi), we get
$$
x^{4} \times \frac{3}{2} x = 48 \Rightarrow x^{5} = 48 \times \frac{2}{3} = 32 = 2^{5} \Rightarrow x=2 .
$$
$\therefore \quad a = \frac{3}{2} \times 2=3$.
Hence, $x=2, a=3$, and $n=5$.

---

### Example 29

If the coefficients of ($r-1$)-th, $r$-th and ($r+1$)-th terms in the expansion of $(x+1)^{n}$ are in the ratio $1: 3: 5$, find the values of $n$ and $r$.

#### Solution:

We have $(x+1)^{n}=(1+x)^{n}$
$$
= { }^{n} C_{0} + { }^{n} C_{1} x + { }^{n} C_{2} x^{2} + \ldots + { }^{n} C_{r-2} x^{r-2} + { }^{n} C_{r-1} x^{r-1} + { }^{n} C_{r} x^{r} + \ldots
$$
$\therefore \quad T_{(r-1)} = T_{(r-2)+1} = { }^{n} C_{r-2} x^{r-2}$, ... (i)
$T_{r} = T_{(r-1)+1} = { }^{n} C_{r-1} x^{r-1}$, ... (ii)
$T_{r+1} = { }^{n} C_{r} x^{r}$. ... (iii)
It is given that coeff. of $T_{(r-1)}$ : coeff. of $T_{r}$ : coeff. of $T_{(r+1)}=1: 3: 5$
$\Rightarrow \quad { }^{n} C_{(r-2)} : { }^{n} C_{(r-1)} : { }^{n} C_{r} = 1: 3: 5$
$\Rightarrow \quad \frac{{ }^{n} C_{r-2}}{{ }^{n} C_{r-1}} = \frac{1}{3}$ and $\frac{{ }^{n} C_{r-1}}{{ }^{n} C_{r}} = \frac{3}{5}$.
But, $\frac{{ }^{n} C_{r-2}}{{ }^{n} C_{r-1}} = \frac{1}{3} \Rightarrow \frac{n!}{(r-2)!(n-r+2)!} \times \frac{(r-1)!(n-r+1)!}{n!} = \frac{1}{3}$
$$
\Rightarrow \frac{(r-1)}{(n-r+2)} = \frac{1}{3} \Rightarrow 3r-3 = n-r+2 \Rightarrow n-4r=-5 \quad \text{(i)}
$$
And, $\frac{{ }^{n} C_{r-1}}{{ }^{n} C_{r}} = \frac{3}{5} \Rightarrow \frac{r}{(n-r+1)} = \frac{3}{5} \Rightarrow 5r = 3n-3r+3$
$$
\Rightarrow 3 n-8 r=-3 \quad \text{(ii)}
$$
Solving (i) and (ii), we get $n=7$ and $r=3$.
Hence, $n=7$ and $r=3$.

---

### Example 30

If the coefficients of $x^{r-1}, x^{r}$ and $x^{r+1}$ in the binomial expansion of $(1+x)^{n}$ are in AP, prove that $n^{2}-n(4 r+1)+4 r^{2}-2=0$.

#### Solution:

We know that
$$
(1+x)^{n} = { }^{n} C_{0} + { }^{n} C_{1} x + \ldots + { }^{n} C_{r-1} x^{r-1} + { }^{n} C_{r} x^{r} + { }^{n} C_{r+1} x^{r+1} + \ldots .
$$
So, the coefficients of $x^{r-1}, x^{r}$ and $x^{r+1}$ in the given expansion are ${ }^{n} C_{r-1},{ }^{n} C_{r}$, and ${ }^{n} C_{r+1}$ respectively. It is given that ${ }^{n} C_{r-1},{ }^{n} C_{r}$, and ${ }^{n} C_{r+1}$ are in AP.
$$
\begin{aligned}
\therefore \quad 2 \times { }^{n} C_{r} &= { }^{n} C_{r-1} + { }^{n} C_{r+1} \\
\Rightarrow \quad 2 &= \frac{{ }^{n} C_{r-1}}{{ }^{n} C_{r}} + \frac{{ }^{n} C_{r+1}}{{ }^{n} C_{r}} \\
\Rightarrow \quad 2 &= \frac{r}{(n-r+1)} + \frac{(n-r)}{r+1} \\
\Rightarrow \quad 2(r+1)(n-r+1) &= r(r+1) + (n-r)(n-r+1) \\
\Rightarrow \quad 2(nr - r^2 + r + n - r + 1) &= r^2 + r + n^2 - nr + n - nr + r^2 - r \\
\Rightarrow \quad 2(nr - r^2 + n + 1) &= 2r^2 - 2nr + n^2 + n \\
\Rightarrow \quad 2nr - 2r^2 + 2n + 2 &= 2r^2 - 2nr + n^2 + n \\
\Rightarrow \quad n^{2} - 4nr - n + 4r^2 - 2 &= 0 \\
\Rightarrow \quad n^{2} - n(4r+1) + 4r^{2} - 2 &= 0
\end{aligned}
$$
Hence, $n^{2}-n(4 r+1)+4 r^{2}-2=0$.

---

### Example 31

Simplify the expression $(1+x)^{1000}+x(1+x)^{999}+x^{2}(1+x)^{998}+\ldots+x^{1000}$ and find the coefficient of $x^{50}$.

#### Solution:

Clearly, the given series is a geometric series in which
$a = (1+x)^{1000}, r = \frac{x(1+x)^{999}}{(1+x)^{1000}} = \frac{x}{(1+x)}$ and the number of terms is $n=1001$.
$$
\begin{aligned}
\therefore \quad \text{given sum} &= \frac{a(1-r^{n})}{1-r} \\
&= \frac{(1+x)^{1000} \times \left\{1-\left(\frac{x}{1+x}\right)^{1001}\right\}}{\left(1-\frac{x}{1+x}\right)} \\
&= \frac{(1+x)^{1000} \times \frac{(1+x)^{1001} - x^{1001}}{(1+x)^{1001}}}{\frac{1}{1+x}} \\
&= \frac{(1+x)^{1001} - x^{1001}}{(1+x)} \times (1+x) = (1+x)^{1001}-x^{1001} \\
&= \left(1 + { }^{1001} C_{1} x + { }^{1001} C_{2} x^{2} + \ldots + { }^{1001} C_{1001} x^{1001} \right) - x^{1001} \\
&= 1 + { }^{1001} C_{1} x + { }^{1001} C_{2} x^{2} + \ldots + { }^{1001} C_{1000} x^{1000}
\end{aligned}
$$
$\therefore \quad$ coefficient of $x^{50}$ in the above expansion = ${ }^{1001} C_{50} = \frac{(1001)!}{(50)!(951)!}$.

---

### Example 32

If $n$ is a positive integer, find the coefficient of $x^{-1}$ in the expansion of $(1+x)^{n}\left(1+\frac{1}{x}\right)^{n}$.

#### Solution:

We have
$$
(1+x)^{n}\left(1+\frac{1}{x}\right)^{n} = (1+x)^{n} \times \frac{(1+x)^{n}}{x^{n}} = \frac{(1+x)^{2 n}}{x^{n}}
$$
Coefficient of $x^{-1}$ in the expansion of $(1+x)^{n}\left(1+\frac{1}{x}\right)^{n}$
= coefficient of $x^{-1}$ in the expansion of $\frac{(1+x)^{2 n}}{x^{n}}$
= coefficient of $x^{n-1}$ in the expansion of $(1+x)^{2 n}$
= ${ }^{2 n} C_{n-1} \quad [\because (1+x)^{2n} = \sum_{r=0}^{2 n}{ }^{2 n} C_{r} x^{r}]$.

---

### Example 33

Find the coefficient of $x^{4}$ in the expansion of $\left(1+x+x^{2}+x^{3}\right)^{11}$.

#### Solution:

We have
$$
\begin{aligned}
\left(1+x+x^{2}+x^{3}\right)^{11} &= \left\{(1+x)+x^{2}(1+x)\right\}^{11} = \left\{(1+x)\left(1+x^{2}\right)\right\}^{11} \\
&= (1+x)^{11} \times \left(1+x^{2}\right)^{11} \\
&= \left({ }^{11} C_{0} x^{0} + { }^{11} C_{1} x + { }^{11} C_{2} x^{2} + { }^{11} C_{3} x^{3} + { }^{11} C_{4} x^{4} + \ldots\right) \\
& \quad \times \left({ }^{11} C_{0}\left(x^{2}\right)^{0} + { }^{11} C_{1}\left(x^{2}\right) + { }^{11} C_{2}\left(x^{2}\right)^{2} + \ldots\right) \\
&= \left(1+11 x+55 x^{2}+165 x^{3}+330 x^{4}+\ldots\right) \times \left(1+11 x^{2}+55 x^{4}+\ldots\right)
\end{aligned}
$$
$\therefore \quad$ coefficient of $x^{4}$ in the given expansion
$$
\begin{aligned}
&= ({ }^{11} C_{0} \times { }^{11} C_{2}) + ({ }^{11} C_{2} \times { }^{11} C_{1}) + ({ }^{11} C_{4} \times { }^{11} C_{0}) \\
&= (1 \times 55) + (55 \times 11) + (330 \times 1) \\
&= (55+605+330) = 990
\end{aligned}
$$
Hence, the coefficient of $x^{4}$ in the given expansion is 990.

---

### Example 34

Find the coefficient of $x^{4}$ in the product $(1+2 x)^{4} \times(2-x)^{5}$.

#### Solution:

Using the binomial expansion, we get
$$
\begin{aligned}
(1+2 x)^{4} &= { }^{4} C_{0} + { }^{4} C_{1}(2 x) + { }^{4} C_{2}(2 x)^{2} + { }^{4} C_{3}(2 x)^{3} + { }^{4} C_{4}(2 x)^{4} \\
&= 1+8 x+24 x^{2}+32 x^{3}+16 x^{4}
\end{aligned}
$$
and
$$
\begin{aligned}
(2-x)^{5} &= 2^{5} - { }^{5} C_{1}\left(2^{4}\right) x + { }^{5} C_{2}\left(2^{3}\right) x^{2} - { }^{5} C_{3}\left(2^{2}\right) x^{3} + { }^{5} C_{4}(2) x^4 - { }^{5} C_5 x^5 \\
&= 32 - 80x + 80x^2 - 40x^3 + 10x^4 - x^5
\end{aligned}
$$
$\therefore \quad (1+2 x)^{4} \times (2-x)^{5} = \left(1+8 x+24 x^{2}+32 x^{3}+16 x^{4}\right) \times \left(32-80 x+80 x^{2}-40 x^{3}+10 x^{4}-x^{5}\right)$
Sum of the terms containing $x^{4}$ in the given product
$$
\begin{aligned}
&= (1 \times 10 x^{4}) + (8x \times -40 x^{3}) + (24 x^{2} \times 80 x^{2}) + (32 x^{3} \times -80 x) + (16 x^{4} \times 32) \\
&= 10 x^{4} - 320 x^{4} + 1920 x^{4} - 2560 x^{4} + 512 x^{4} \\
&= (10 - 320 + 1920 - 2560 + 512) x^{4} = -438 x^{4}
\end{aligned}
$$
Hence, the coefficient of $x^{4}$ in the given product is -438.

---

### Example 35

If $P$ be the sum of all odd terms and $Q$ that of all even terms in the expansion of $(x+a)^{n}$, prove that
(i) $(P^{2}-Q^{2}) = (x^{2}-a^{2})^{n}$,
(ii) $4 P Q = \left\{(x+a)^{2 n}-(x-a)^{2 n}\right\}$,
(iii) $2\left(P^{2}+Q^{2}\right) = \left[(x+a)^{2 n}+(x-a)^{2 n}\right]$.

#### Solution:

By the binomial expansion, we have
$$
\begin{aligned}
(x+a)^{n} &= { }^{n} C_{0} x^{n} + { }^{n} C_{1} x^{n-1} a + { }^{n} C_{2} x^{n-2} a^{2} + { }^{n} C_{3} x^{n-3} a^{3} + \ldots \\
&= (T_{1} + T_{3} + T_{5} + \ldots) + (T_{2} + T_{4} + T_{6} + \ldots) \\
&= P+Q \quad \text{(I)}
\end{aligned}
$$
And, $(x-a)^{n} = { }^{n} C_{0} x^{n} - { }^{n} C_{1} x^{n-1} a + { }^{n} C_{2} x^{n-2} a^{2} - { }^{n} C_{3} x^{n-3} a^{3} + \ldots$
$$
\begin{aligned}
&= (T_{1} - T_{2} + T_{3} - T_{4} + \ldots) \\
&= (T_{1} + T_{3} + T_{5} + \ldots) - (T_{2} + T_{4} + T_{6} + \ldots) \\
&= P-Q \quad \text{(II)}
\end{aligned}
$$
(i) On multiplying (I) and (II), we get $(x+a)^n(x-a)^n = (P+Q)(P-Q)$
$$
\left(x^{2}-a^{2}\right)^{n} = \left(P^{2}-Q^{2}\right)
$$
(ii) On squaring (I) and (II) and subtracting, we get
$$
\left\{(x+a)^{2 n}-(x-a)^{2 n}\right\} = \left\{(P+Q)^{2}-(P-Q)^{2}\right\} = 4 P Q .
$$
(iii) On squaring (I) and (II) and adding, we get
$$
\left\{(x+a)^{2 n}+(x-a)^{2 n}\right\} = \left\{(P+Q)^{2}+(P-Q)^{2}\right\} = 2\left(P^{2}+Q^{2}\right)
$$

---

### Example 36

Using binomial theorem, find the value of $(103)^{4}$.

#### Solution:

By the binomial expansion, we have
$$
\begin{aligned}
(103)^{4} &= (100+3)^{4} \\
&= { }^{4} C_{0} \cdot (100)^{4} + { }^{4} C_{1} \times (100)^{3} \times 3 + { }^{4} C_{2} \times (100)^{2} \times 3^{2} + { }^{4} C_{3} \times 100 \times 3^{3} + { }^{4} C_{4} \times 3^{4} \\
&= (100)^{4} + 4 \times (100)^{3} \times 3 + 6 \times (100)^{2} \times 9 + 4 \times 100 \times 27 + 1 \times 81 \\
&= 100000000 + 12000000 + 540000 + 10800 + 81 \\
&= 112550881 .
\end{aligned}
$$
Hence, $(103)^{4}=112550881$.

---

### Example 37

Using binomial theorem, find the value of $(99)^{4}$.

#### Solution:

By the binomial expansion, we have
$$
\begin{aligned}
(99)^{4} &= (100-1)^{4} \\
&= { }^{4} C_{0} \times (100)^{4} - { }^{4} C_{1} \times (100)^{3} \times 1 + { }^{4} C_{2} \times (100)^{2} \times 1^{2} - { }^{4} C_{3} \times 100 \times 1^{3} + { }^{4} C_{4} \times 1^{4} \\
&= (100)^{4} - 4 \times (100)^{3} + 6 \times (100)^{2} - 4 \times 100 + 1 \\
&= 100000000 - 4000000 + 60000 - 400 + 1 \\
&= 96059601 .
\end{aligned}
$$
Hence, $(99)^{4}=96059601$.

---

### Example 38

Using binomial theorem, find the value of $(0.99)^{15}$ up to four places of decimal.

#### Solution:

We have
$$
\begin{aligned}
(0.99)^{15} &= (1-0.01)^{15} \\
&= 1 - { }^{15} C_{1} \times (0.01) + { }^{15} C_{2} \times (0.01)^{2} - { }^{15} C_{3} \times (0.01)^{3} + \ldots \\
&\approx 1 - 15 \times (0.01) + 105 \times (0.0001) - 455 \times (0.000001) \\
&= 1 - 0.15 + 0.0105 - 0.000455 \\
&= 0.860045
\end{aligned}
$$
Hence, $(0.99)^{15} \approx 0.8600$.

---

### Example 39

Using binomial theorem, prove that $(101)^{50} > (100^{50}+99^{50})$.

#### Solution:

We need to prove $(101)^{50} - (99)^{50} > 100^{50}$.
$$
\begin{aligned}
(101)^{50} - (99)^{50} &= (100+1)^{50} - (100-1)^{50} \\
&= 2 \times \left[{ }^{50} C_{1} \times 100^{49} + { }^{50} C_{3} \times 100^{47} + \ldots + { }^{50} C_{49} \times 100\right] \\
&= 2 \times [50 \times 100^{49} + { }^{50} C_{3} \times 100^{47} + \ldots] \\
&= 100 \times 100^{49} + 2 \times [{ }^{50} C_{3} \times 100^{47} + \ldots] \\
&= 100^{50} + (\text{a positive integer})
\end{aligned}
$$
Thus, $(101)^{50} - (99)^{50} > 100^{50}$.
$\Rightarrow (101)^{50} > (100^{50}+99^{50})$.

---

### Example 40

Which is larger, $(1.01)^{1000000}$ or 10000?

#### Solution:

We have
$$
\begin{aligned}
(1.01)^{1000000} &= (1+0.01)^{1000000} \\
&= { }^{1000000} C_{0} + { }^{1000000} C_{1} \times (0.01) + \text{other positive terms} \\
&= 1 + 1000000 \times 0.01 + \text{other positive terms} \\
&= 1 + 10000 + \text{other positive terms}
\end{aligned}
$$
Since $(1.01)^{1000000} = 10001 + (\text{a positive real number})$, it is clearly greater than 10000.
Hence, $(1.01)^{1000000} > 10000$.

---