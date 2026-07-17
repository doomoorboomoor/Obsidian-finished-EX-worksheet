## Properties of GP

Let $a, a r, a r^{2}, a r^{3}, \ldots$ be a **GP**. Then,

1.  $\frac{1}{a}, \frac{1}{a r}, \frac{1}{a r^{2}}, \frac{1}{a r^{3}}, \ldots$ is a **GP**.
2.  $k a, k(a r), k\left(a r^{2}\right), k\left(a r^{3}\right), \ldots$ is a **GP**, where $k \neq 0$.
3.  $\frac{k}{a}, \frac{k}{a r}, \frac{k}{a r^{2}}, \frac{k}{a r^{3}}, \ldots$ is a **GP**, where $k \neq 0$.
4.  $a^{k},(a r)^{k},\left(a r^{2}\right)^{k},\left(a r^{3}\right)^{k}, \ldots$ is a **GP**, where $k \neq 0$.

---

## Solved Examples

### Example 1

If $a, b, c$ are in **GP**, prove that $\log a, \log b, \log c$ are in **AP**.

#### Solution:

Let $a, b, c$ be in **GP**. Then,

$$
\begin{aligned}
b^{2}=a c & \Rightarrow \log b^{2}=\log (a c) \\
& \Rightarrow 2 \log b=\log a+\log c
\end{aligned}
$$

This implies that **$\log a, \log b, \log c$ are in AP**.

---

### Example 2

If $a, b, c, d$ are in **GP** then prove that $a+b, b+c, c+d$ are also in **GP**.

#### Solution:

Let $a, b, c, d$ be in **GP** with common ratio $r$. Then, $b=a r$, $c=a r^{2}$ and $d=a r^{3}$.

Therefore:
- $(a+b)=(a+a r)=a(1+r)$
- $(b+c)=\left(a r+a r^{2}\right)=a r(1+r)$
- $(c+d)=\left(a r^{2}+a r^{3}\right)=a r^{2}(1+r)$

Now we check the condition for a **GP**:

- $(b+c)^{2} = [ar(1+r)]^2 = a^{2} r^{2}(1+r)^{2}$
- $(a+b)(c+d) = [a(1+r)][ar^2(1+r)] = a^{2} r^{2}(1+r)^{2}$

Consequently, $(b+c)^{2}=(a+b)(c+d)$.

Hence, **$(a+b),(b+c)$ and $(c+d)$ are in GP**.

---

### Example 3

If $a, b, c, d$ are in **GP** then prove that $a^{n}+b^{n}, b^{n}+c^{n}, c^{n}+d^{n}$ are also in **GP**.

#### Solution:

Let $a, b, c, d$ be in **GP** with common ratio $r$. Then, $b=a r, c=a r^{2}$ and $d=a r^{3}$.

Therefore:
- $\left(a^{n}+b^{n}\right)=\left(a^{n}+a^{n} r^{n}\right)=a^{n}\left(1+r^{n}\right)$
- $\left(b^{n}+c^{n}\right)=\left(a^{n} r^{n}+a^{n} r^{2 n}\right)=a^{n} r^{n}\left(1+r^{n}\right)$
- $\left(c^{n}+d^{n}\right)=\left(a^{n} r^{2 n}+a^{n} r^{3 n}\right)=a^{n} r^{2 n}\left(1+r^{n}\right)$

Now we check the condition for a **GP**:
- $\left(b^{n}+c^{n}\right)^{2} = [a^n r^n(1+r^n)]^2 = a^{2 n} r^{2 n}\left(1+r^{n}\right)^{2}$
- $\left(a^{n}+b^{n}\right)\left(c^{n}+d^{n}\right) = [a^n(1+r^n)][a^n r^{2n}(1+r^n)] = a^{2 n} r^{2 n}\left(1+r^{n}\right)^{2}$

Consequently, $\left(b^{n}+c^{n}\right)^{2}=\left(a^{n}+b^{n}\right)\left(c^{n}+d^{n}\right)$.

Hence, **$\left(a^{n}+b^{n}\right),\left(b^{n}+c^{n}\right)$ and $\left(c^{n}+d^{n}\right)$ are in GP**.

---

### Example 4

If $\left(a^{2}+b^{2}\right),(a b+b c),\left(b^{2}+c^{2}\right)$ are in **GP** then prove that $a, b, c$ are also in **GP**.

#### Solution:

Let $\left(a^{2}+b^{2}\right),(a b+b c)$ and $\left(b^{2}+c^{2}\right)$ be in **GP**. Then,

$$
\begin{aligned}
(a b+b c)^{2} &= \left(a^{2}+b^{2}\right)\left(b^{2}+c^{2}\right) \\
\Rightarrow \quad a^{2} b^{2}+b^{2} c^{2}+2 a b^{2} c &= a^{2} b^{2}+a^{2} c^{2}+b^{4}+b^{2} c^{2} \\
\Rightarrow \quad 2 a b^{2} c &= a^{2} c^{2}+b^{4} \\
\Rightarrow \quad b^{4}+a^{2} c^{2}-2 a b^{2} c &= 0 \\
\Rightarrow \quad \left(b^{2}-a c\right)^{2} &= 0 \\
\Rightarrow \quad b^{2}-a c &= 0 \\
\Rightarrow \quad b^{2} &= ac
\end{aligned}
$$

Hence, **$a, b, c$ are in GP**.

---

### Example 5

If the $m$-th, $n$-th and $p$-th terms of a **GP** form three consecutive terms of a **GP** then prove that $m, n, p$ are three consecutive terms of an **AP**.

#### Solution:

Let $a$ be the first term and $r$ be the common ratio of the given **GP**. Then,
- $T_{m}=a r^{(m-1)}$
- $T_{n}=a r^{(n-1)}$
- $T_{p}=a r^{(p-1)}$

Since $T_{m}, T_{n}, T_{p}$ are in **GP**, we have $T_{n}^{2}=T_{m} \times T_{p}$.

$$
\begin{aligned}
{\left[a r^{(n-1)}\right]^{2}} &= \left[a r^{(m-1)} \times a r^{(p-1)}\right] \\
\Rightarrow \quad a^{2} r^{(2 n-2)} &= a^{2} r^{(m+p-2)} \\
\Rightarrow \quad r^{(2 n-2)} &= r^{(m+p-2)} \\
\Rightarrow \quad 2 n-2 &= m+p-2 \\
\Rightarrow \quad 2 n &= m+p
\end{aligned}
$$

This is the condition for an **AP**.

Hence, **$m, n, p$ are three consecutive terms of an AP**.

---

### Example 6

If the 4th, 10th and 16th terms of a **GP** are $x, y, z$ respectively, prove that $x, y, z$ are in **GP**.

#### Solution:

Let $a$ be the first term and $r$ be the common ratio of the given **GP**. Then, $T_{4}=x, T_{10}=y$ and $T_{16}=z$.
This implies $a r^{3}=x, a r^{9}=y$ and $a r^{15}=z$.

Now we check the condition for a **GP** for $x, y, z$:
- $y^{2}=\left(a r^{9}\right)^{2}=a^{2} r^{18}$
- $x z=\left(a r^{3}\right)\left(a r^{15}\right)=a^{2} r^{18}$

Consequently, we have $y^{2}=x z$.

Hence, **$x, y, z$ are in GP**.

---

### Example 7

Three numbers are in **AP** and their sum is 15. If $1, 3, 9$ be added to them respectively, they form a **GP**. Find the numbers.

#### Solution:

Let the required numbers be $(a-d), a$ and $(a+d)$.

Their sum is $(a-d)+a+(a+d)=15 \Rightarrow 3 a=15 \Rightarrow a=5$.
So, the numbers are $(5-d), 5$ and $(5+d)$.

Adding 1, 3, 9 respectively to these numbers, we get the new numbers $(6-d), 8$ and $(14+d)$. These numbers are in **GP**.

Therefore, the square of the middle term equals the product of the other two:
$$
\begin{aligned}
8^{2} &= (6-d)(14+d) \\
\Rightarrow 64 &= 84 + 6d - 14d - d^2 \\
\Rightarrow 64 &= 84 - 8d - d^2 \\
\Rightarrow d^{2}+8 d-20 &= 0 \\
\Rightarrow d^{2}+10 d-2 d-20 &= 0 \\
\Rightarrow d(d+10)-2(d+10) &= 0 \\
\Rightarrow (d+10)(d-2) &= 0 \\
\Rightarrow d=-10 \text{ or } d=2
\end{aligned}
$$
If $d=2$, the numbers are $(5-2), 5, (5+2)$, which are $3, 5, 7$.
If $d=-10$, the numbers are $(5-(-10)), 5, (5-10)$, which are $15, 5, -5$.

So, the required numbers are **$(3,5,7)$ or $(15,5,-5)$**.

---

