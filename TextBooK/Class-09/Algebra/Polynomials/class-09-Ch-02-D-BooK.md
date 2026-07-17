## Factor Theorem

Let $p(x)$ be a polynomial of degree 1 or more and let $\alpha$ be any real number.

1.  If $p(\alpha)=0$ then $(x-\alpha)$ is a factor of $p(x)$.
2.  If $(x-\alpha)$ is a factor of $p(x)$ then $p(\alpha)=0$.

#### Proof:

When $p(x)$ is divided by $(x-\alpha)$, let $q(x)$ be the quotient. By the **Remainder Theorem**, the remainder is $p(\alpha)$.
Therefore, by the division algorithm:
$$
p(x)=(x-\alpha) \cdot q(x)+p(\alpha)
$$

1.  If $p(\alpha)=0$, then $p(x)=(x-\alpha) \cdot q(x)$.
    This shows that **$(x-\alpha)$ is a factor of $p(x)$**.

2.  If $(x-\alpha)$ is a factor of $p(x)$, then we have $p(x)=(x-\alpha) \cdot q(x)$ for some polynomial $q(x)$.
    Putting $x=\alpha$ on both sides, we get $p(\alpha)=0$.
    Thus, when $(x-\alpha)$ is a factor of $p(x)$, then $p(\alpha)=0$.

---
## Solved Examples

### Example 1

If $p(x)=8 x^{3}-6 x^{2}-4 x+3$ and $g(x)=\frac{x}{3}-\frac{1}{4}$, then check whether $g(x)$ is a factor of $p(x)$ or not.

#### Solution:

Given $g(x)=0 \Rightarrow \frac{x}{3}-\frac{1}{4}=0 \Rightarrow \frac{x}{3}=\frac{1}{4} \Rightarrow x=\frac{3}{4}$.

By the **Factor Theorem**, $g(x)$ will be a factor of $p(x)$ if $p\left(\frac{3}{4}\right)=0$.

Now,
$$
p\left(\frac{3}{4}\right) = \left\{8 \times\left(\frac{3}{4}\right)^{3}-6 \times\left(\frac{3}{4}\right)^{2}-4 \times \frac{3}{4}+3\right\}
$$
$$
= \left\{\left(8 \times \frac{27}{64}\right)-\left(6 \times \frac{9}{16}\right)-3+3\right\} = \left(\frac{27}{8}-\frac{27}{8}\right)=0.
$$
Since $p\left(\frac{3}{4}\right)=0$, it follows that **$g(x)$ is a factor of $p(x)$**.

---
### Example 2

Show that $(2 x-3)$ is a factor of $(x+2 x^{3}-9 x^{2}+12)$.

#### Solution:

Let $p(x)=2 x^{3}-9 x^{2}+x+12$ and $g(x)=2 x-3$.

Now, $g(x)=0 \Rightarrow 2 x-3=0 \Rightarrow 2 x=3 \Rightarrow x=\frac{3}{2}$.

By the **Factor Theorem**, $g(x)$ will be a factor of $p(x)$ if $p\left(\frac{3}{2}\right)=0$.

Now,
$$
p\left(\frac{3}{2}\right) = \left\{2 \times\left(\frac{3}{2}\right)^{3}-9 \times\left(\frac{3}{2}\right)^{2}+\frac{3}{2}+12\right\}
$$
$$
= \left\{\left(2 \times \frac{27}{8}\right)-\left(9 \times \frac{9}{4}\right)+\frac{3}{2}+12\right\}
$$
$$
= \left(\frac{27}{4}-\frac{81}{4}+\frac{3}{2}+12\right)=\left(\frac{27-81+6+48}{4}\right)=\frac{0}{4}=0.
$$
Since $p\left(\frac{3}{2}\right)=0$, so **$g(x)$ is a factor of $p(x)$**.

---
### Example 3

Use the Factor Theorem to show that $x^{4}+2 x^{3}-2 x^{2}+2 x-3$ is exactly divisible by $(x+3)$.

#### Solution:

Let $p(x)=x^{4}+2 x^{3}-2 x^{2}+2 x-3$ and $g(x)=x+3$.

Then, $g(x)=0 \Rightarrow x+3=0 \Rightarrow x=-3$.

By the **Factor Theorem**, $p(x)$ will be exactly divisible by $(x+3)$ if $p(-3)=0$.

Now,
$$
p(-3) = \left\{(-3)^{4}+2 \times(-3)^{3}-2 \times(-3)^{2}+2 \times(-3)-3\right\}
$$
$$
= (81-54-18-6-3) = 0.
$$
Since $p(-3)=0$, it follows that **$p(x)$ is exactly divisible by $(x+3)$**.

---
### Example 4

If $(x-a)$ is a factor of $(x^{3}-a x^{2}+2 x+a-1)$, find the value of $a$.

#### Solution:

Let $p(x)=x^{3}-a x^{2}+2 x+a-1$ and $g(x)=x-a$.

Then, $g(x)=0 \Rightarrow x-a=0 \Rightarrow x=a$.

By the **Factor Theorem**, $(x-a)$ will be a factor of $p(x)$ if $p(a)=0$.

Now, $p(a)=0 \Rightarrow a^{3}-a \times a^{2}+2 a+a-1=0$.
$$
\Rightarrow a^{3}-a^{3}+3 a-1=0
$$
$$
\Rightarrow 3 a-1=0 \Rightarrow 3 a=1 \Rightarrow a=\frac{1}{3}.
$$
Hence, the required value of $a$ is $\frac{1}{3}$.

---
### Example 5

For what value of $m$ is $(x^{3}-2 m x^{2}+16)$ divisible by $(x+2)$?

#### Solution:

Let $p(x)=x^{3}-2 m x^{2}+16$ and $g(x)=x+2$.

Then, $g(x)=0 \Rightarrow x+2=0 \Rightarrow x=-2$.

By the **Factor Theorem**, $(x+2)$ will be a factor of $p(x)$ if $p(-2)=0$.

Now,
$$
p(-2)=0 \Rightarrow (-2)^{3}-2 m \times(-2)^{2}+16=0
$$
$$
\Rightarrow -8-8 m+16=0 \Rightarrow 8 m=8 \Rightarrow m=1.
$$
Hence, the required value of $m$ is **1**.

---
### Example 6

Without actual division, prove that $(2 x^{4}+3 x^{3}-12 x^{2}-7 x+6)$ is exactly divisible by $(x^{2}+x-6)$.

#### Solution:

Let $p(x)=2 x^{4}+3 x^{3}-12 x^{2}-7 x+6$ and $g(x)=x^{2}+x-6$.

First, factorize $g(x)$:
$$
g(x) = x^{2}+x-6 = x^{2}+3 x-2 x-6 = x(x+3)-2(x+3) = (x+3)(x-2).
$$
Clearly, $p(x)$ will be exactly divisible by $g(x)$ only when it is exactly divisible by both $(x+3)$ and $(x-2)$.

We check the conditions using the Factor Theorem:
- $x+3=0 \Rightarrow x=-3$
- $x-2=0 \Rightarrow x=2$

$g(x)$ will be a factor of $p(x)$ if $p(-3)=0$ and $p(2)=0$.

Now,
$$
p(-3) = \left\{2 \times(-3)^{4}+3 \times(-3)^{3}-12 \times(-3)^{2}-7 \times(-3)+6\right\}
$$
$$
= \{(2 \times 81)+3 \times(-27)-(12 \times 9)+21+6\}
$$
$$
= (162-81-108+21+6) = 0.
$$
And,
$$
p(2) = \left\{\left(2 \times 2^{4}\right)+\left(3 \times 2^{3}\right)-\left(12 \times 2^{2}\right)-(7 \times 2)+6\right\}
$$
$$
= (32+24-48-14+6) = 0.
$$
Thus, $p(x)$ is exactly divisible by both $(x+3)$ and $(x-2)$.
Hence, **$p(x)$ is exactly divisible by $(x+3)(x-2)$, i.e., by $(x^{2}+x-6)$**.

---
### Example 7

Find the values of $a$ and $b$ so that $(2 x^{3}+a x^{2}+x+b)$ has $(x+2)$ and $(2 x-1)$ as factors.

#### Solution:

Let $p(x)=2 x^{3}+a x^{2}+x+b$.
The roots of the factors are:
- $x+2=0 \Rightarrow x=-2$
- $2 x-1=0 \Rightarrow 2 x=1 \Rightarrow x=\frac{1}{2}$

For $(x+2)$ and $(2x-1)$ to be factors of $p(x)$, we must have $p(-2)=0$ and $p\left(\frac{1}{2}\right)=0$.

For $p(-2)=0$:
$$
2 \times(-2)^{3}+a \times(-2)^{2}+(-2)+b=0
$$
$$
\Rightarrow -16+4 a-2+b=0 \Rightarrow 4 a+b=18 \quad \cdots (i)
$$
For $p\left(\frac{1}{2}\right)=0$:
$$
2 \times\left(\frac{1}{2}\right)^{3}+a \times\left(\frac{1}{2}\right)^{2}+\frac{1}{2}+b=0
$$
$$
\Rightarrow \left(2 \times \frac{1}{8}\right)+\left(a \times \frac{1}{4}\right)+\frac{1}{2}+b=0
$$
$$
\Rightarrow \frac{1}{4}+\frac{a}{4}+\frac{1}{2}+b=0 \Rightarrow a+4 b=-3 \quad \cdots (ii)
$$
On solving equations (i) and (ii), we get $a=5$ and $b=-2$.
Hence, **$a=5$** and **$b=-2$**.

---
### Example 8

If $(a x^{3}+b x^{2}-5 x+2)$ has $(x+2)$ as a factor and leaves a remainder of 12 when divided by $(x-2)$, find the values of $a$ and $b$.

#### Solution:

Let $p(x)=a x^{3}+b x^{2}-5 x+2$.

From the given conditions:
1.  $(x+2)$ is a factor of $p(x)$. By the Factor Theorem, $p(-2)=0$.
    $$
    p(-2) = a(-2)^{3}+b(-2)^{2}-5(-2)+2 = 0
    $$
    $$
    \Rightarrow -8 a+4 b+10+2=0
    $$
    $$
    \Rightarrow -8 a+4 b+12=0 \Rightarrow 8 a-4 b=12 \Rightarrow 2 a-b=3 \quad \cdots (i)
    $$
2.  When $p(x)$ is divided by $(x-2)$, the remainder is 12. By the Remainder Theorem, $p(2)=12$.
    $$
    p(2) = a(2)^{3}+b(2)^{2}-5(2)+2 = 12
    $$
    $$
    \Rightarrow 8 a+4 b-10+2=12
    $$
    $$
    \Rightarrow 8 a+4 b=20 \Rightarrow 2 a+b=5 \quad \cdots (ii)
    $$
On solving equations (i) and (ii), we get $a=2$ and $b=1$.
Hence, **$a=2$** and **$b=1$**.

---
### Example 9

What must be added to $(x^{3}-3 x^{2}+4 x-15)$ to obtain a polynomial which is exactly divisible by $(x-3)$?

#### Solution:

When the given polynomial is divided by a linear polynomial, the remainder is a constant. Let the required number to be added be $k$.

Let the new polynomial be $p(x)=x^{3}-3 x^{2}+4 x-15+k$.
Let the divisor be $g(x)=x-3$. Then $g(x)=0 \Rightarrow x=3$.

By the **Factor Theorem**, $p(x)$ will be divisible by $(x-3)$ if $p(3)=0$.

Now,
$$
p(3)=0 \Rightarrow \left\{3^{3}-3 \times 3^{2}+4 \times 3-15+k\right\}=0
$$
$$
\Rightarrow (27-27+12-15+k)=0 \Rightarrow k=3.
$$
Hence, the required number to be added is **3**.

---
### Example 10

What must be subtracted from $(4 x^{4}-2 x^{3}-6 x^{2}+2 x+6)$ so that the result is exactly divisible by $(2 x^{2}+x-1)$?

#### Solution:

When the given polynomial is divided by a quadratic polynomial, the remainder is a linear expression, say $(ax+b)$.

Let $p_{orig}(x) = 4 x^{4}-2 x^{3}-6 x^{2}+2 x+6$.
Let the expression to be subtracted be $(ax+b)$.
Let the new polynomial be $p(x) = p_{orig}(x) - (ax+b) = 4 x^{4}-2 x^{3}-6 x^{2}+(2-a) x+(6-b)$.
Let the divisor be $g(x)=2 x^{2}+x-1$.

First, factorize $g(x)$:
$$
g(x) = 2 x^{2}+x-1 = (x+1)(2 x-1)
$$
For $p(x)$ to be divisible by $g(x)$, it must be divisible by both $(x+1)$ and $(2x-1)$.
This means $p(-1)=0$ and $p\left(\frac{1}{2}\right)=0$.

For $p(-1)=0$:
$$
4(-1)^{4}-2(-1)^{3}-6(-1)^{2}+(2-a)(-1)+(6-b)=0
$$
$$
\Rightarrow 4+2-6-2+a+6-b=0 \Rightarrow a-b=-4 \quad \cdots (i)
$$
For $p\left(\frac{1}{2}\right)=0$:
$$
4\left(\frac{1}{2}\right)^{4}-2\left(\frac{1}{2}\right)^{3}-6\left(\frac{1}{2}\right)^{2}+(2-a)\frac{1}{2}+(6-b)=0
$$
$$
\Rightarrow \frac{4}{16}-\frac{2}{8}-\frac{6}{4}+1-\frac{a}{2}+6-b=0
$$
$$
\Rightarrow \frac{1}{4}-\frac{1}{4}-\frac{3}{2}+1-\frac{a}{2}+6-b=0 \Rightarrow \frac{a}{2}+b=\frac{11}{2} \Rightarrow a+2 b=11 \quad \cdots (ii)
$$
On solving (i) and (ii), we get $a=1$ and $b=5$.
Hence, the required expression to be subtracted is **$(x+5)$**.

---
