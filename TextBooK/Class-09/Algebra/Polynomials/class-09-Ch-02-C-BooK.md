## Division Algorithm in Polynomials

Let $p(x)$ and $g(x)$ be two given polynomials such that degree $p(x) \geq$ degree $g(x)$. On dividing $p(x)$ by $g(x)$, let $q(x)$ be the quotient and $r(x)$ be the remainder. Then, in general, we have:

$$
\text{dividend} = (\text{divisor} \times \text{quotient}) + \text{remainder}
$$

i.e., $p(x) = g(x) \cdot q(x) + r(x)$, where $r(x) = 0$ or degree $r(x) <$ degree $g(x)$.

---

### Example 1:

Verify division algorithm for the polynomials $p(x) = 3x^{4} - 4x^{3} - 3x - 1$ and $g(x) = x-2$.
Find $p(2)$. What do you observe?

#### Solution:

By long division, we have:

$$
\begin{array}{c|l}
x-2 & 3x^4-4x^3+0x^2-3x-1 \\ \hline
   & 3x^3+2x^2+4x+5 \\[4pt]
   & \underline{3x^4-6x^3} \\[2pt]
   & 2x^3+0x^2 \\[2pt]
   & \underline{2x^3-4x^2} \\[2pt]
   & 4x^2-3x \\[2pt]
   & \underline{4x^2-8x} \\[2pt]
   & 5x-1 \\[2pt]
   & \underline{5x-10} \\[2pt]
   & 9
\end{array}
$$


$\therefore$ **quotient**, $q(x) = 3x^3 + 2x^2 + 4x + 5$ and **remainder**, $r(x) = 9$.

Now, $g(x) \times q(x) + r(x) = (x-2)(3x^3 + 2x^2 + 4x + 5) + 9$
$= 3x^4 - 4x^3 - 3x - 10 + 9$
$= 3x^4 - 4x^3 - 3x - 1 = p(x)$

$\therefore p(x) = g(x) \times q(x) + r(x)$, where degree $r(x) = 0 < 1 =$ degree $g(x)$.

Thus, the division algorithm is verified.

Now, $p(2) = 3 \times 2^4 - 4 \times 2^3 - 3 \times 2 - 1 = 48 - 32 - 6 - 1 = 9$.

**Observation:** When $p(x)$ is divided by $(x-2)$, the remainder is $p(2)$.

---

### Example 2:

Verify division algorithm for the polynomials $p(x) = x^3 + x^2 + 2x + 3$ and $g(x) = x+2$.
Find $p(-2)$. What do you observe?

#### Solution:

By long division, we have:

$$
\begin{aligned}
x^{3}+x^{2}+2x+3
    &= (x^{2}-x+4)(x+2)-5 \\[4pt]
\frac{x^{3}+x^{2}+2x+3}{x^{2}-x+4}
    &= x+2-\frac{5}{x^{2}-x+4}.
\end{aligned}
$$



$\therefore$ **quotient**, $q(x) = x^2 - x + 4$ and **remainder**, $r(x) = -5$.

Now, $g(x) \times q(x) + r(x) = (x+2)(x^2 - x + 4) - 5$
$= x^3 + x^2 + 2x + 8 - 5$
$= x^3 + x^2 + 2x + 3 = p(x)$

$\therefore p(x) = g(x) \times q(x) + r(x)$, where $r(x)=-5$ and degree $r(x)=0<1=$ degree $g(x)$.

Thus, the division algorithm is verified.

Now, $p(-2) = (-2)^3 + (-2)^2 + 2 \times (-2) + 3 = (-8 + 4 - 4 + 3) = -5$.

**Observation:** When $p(x)$ is divided by $(x+2)$, the remainder is $p(-2)$.

---

### Remainder Theorem

Let $p(x)$ be a polynomial of degree 1 or more and let $\alpha$ be any real number. If $p(x)$ is divided by $(x-\alpha)$ then the remainder is $p(\alpha)$.

#### Proof:

Let $p(x)$ be a polynomial of degree 1 or more.
Suppose that when $p(x)$ is divided by $(x-\alpha)$ then the quotient is $q(x)$ and the remainder is $r(x)$.

By division algorithm, we have
$p(x) = (x-\alpha) \cdot q(x) + r(x)$ (i)

where degree $r(x) < \text{degree}(x-\alpha) = 1$ $[\because \text{degree}(x-\alpha) = 1]$.
But, degree $r(x) < 1 \Rightarrow$ degree $r(x) = 0$.
$\Rightarrow r(x)$ is a constant, equal to $r$ (say).
$\therefore p(x) = (x-\alpha) \cdot q(x) + r$.

Putting $x=\alpha$ on both sides of (i), we get
$p(\alpha) = 0 \times q(\alpha) + r \Rightarrow r = p(\alpha)$.

Thus, when $p(x)$ is divided by $(x-\alpha)$, then the **remainder** is $p(\alpha)$.

---

## Solved Examples

### Example 1:

Find the remainder when the polynomial $p(x) = x^4 + 2x^3 - 3x^2 + x - 1$ is divided by $g(x) = x-2$.

#### Solution:

$g(x) = 0 \Rightarrow x-2=0 \Rightarrow x=2$.
By the remainder theorem, we know that when $p(x)$ is divided by $(x-2)$ then the remainder is $p(2)$.

Now, $p(2) = (2^4 + 2 \times 2^3 - 3 \times 2^2 + 2 - 1)$
$= (16 + 16 - 12 + 2 - 1) = 21$.

Hence, the required remainder is **21**.

---

### Example 2:

Find the remainder when the polynomial $p(x) = x^3 - 3x^2 + 4x + 50$ is divided by $g(x) = x+3$.

#### Solution:

$g(x) = 0 \Rightarrow x+3=0 \Rightarrow x=-3$.
By the remainder theorem, we know that when $p(x)$ is divided by $(x+3)$ then the remainder is $p(-3)$.

Now, $p(-3) = [(-3)^3 - 3 \times (-3)^2 + 4 \times (-3) + 50]$
$= (-27 - 27 - 12 + 50) = -16$.

Hence, the required remainder is **-16**.

---

### Example 3:

Find the remainder when the polynomial $p(x) = 4x^3 - 12x^2 + 14x - 3$ is divided by $g(x) = (2x-1)$.

#### Solution:

$g(x)=0 \Rightarrow 2x-1=0 \Rightarrow x = \frac{1}{2}$.
By the remainder theorem, we know that when $p(x)$ is divided by $(2x-1)$ then the remainder is $p(\frac{1}{2})$.

Now, $p(\frac{1}{2}) = [4 \times (\frac{1}{2})^3 - 12 \times (\frac{1}{2})^2 + 14 \times \frac{1}{2} - 3]$
$= (\frac{1}{2} - 3 + 7 - 3) = \frac{3}{2}$.

Hence, the required remainder is $\frac{3}{2}$.

---

### Example 4:

Find the remainder when the polynomial $p(x) = 12x^3 - 13x^2 - 5x + 7$ is divided by $g(x) = (2+3x)$.

#### Solution:

$g(x)=0 \Rightarrow 2+3x=0 \Rightarrow 3x=-2 \Rightarrow x = \frac{-2}{3}$.
By the remainder theorem, we know that when $p(x)$ is divided by $(2+3x)$ then the remainder is $p(\frac{-2}{3})$.

Now, $p(\frac{-2}{3}) = [12 \times (\frac{-2}{3})^3 - 13 \times (\frac{-2}{3})^2 - 5 \times (\frac{-2}{3}) + 7]$
$= \{12 \times \frac{(-8)}{27} - 13 \times \frac{4}{9} + \frac{10}{3} + 7\} = 1$.

Hence, the required remainder is **1**.

---

### Example 5:

Find the remainder when $x^3 + 3x^2 + 3x + 1$ is divided by $(x+\pi)$.

#### Solution:

Let $p(x) = x^3 + 3x^2 + 3x + 1$ and $g(x) = x+\pi$.
Now, $g(x)=0 \Rightarrow x+\pi=0 \Rightarrow x=-\pi$.

By the remainder theorem, we know that when $p(x)$ is divided by $(x+\pi)$ then the remainder is $p(-\pi)$.

And, $p(-\pi) = (-\pi)^3 + 3 \times (-\pi)^2 + 3 \times (-\pi) + 1$
$= -\pi^3 + 3\pi^2 - 3\pi + 1$.

Hence, the required remainder is $(-\pi^3 + 3\pi^2 - 3\pi + 1)$.

---

### Example 6:

Let $p(x) = x^3 - x + 1$ and $g(x) = 2-3x$. Check whether $p(x)$ is a multiple of $g(x)$ or not.

#### Solution:

$g(x) = 0 \Rightarrow 2-3x = 0 \Rightarrow 3x=2 \Rightarrow x=\frac{2}{3}$.
By the remainder theorem, we know that when $p(x)$ is divided by $(2-3x)$ then the remainder is $p(\frac{2}{3})$.

And, $p(\frac{2}{3}) = \{(\frac{2}{3})^3 - (\frac{2}{3}) + 1\} = (\frac{8}{27} - \frac{2}{3} + 1)$
$= (\frac{8 - 18 + 27}{27}) = \frac{17}{27} \neq 0$.

Thus, when $p(x)$ is divided by $g(x)$, the remainder is nonzero. Hence, $p(x)$ is **not a multiple** of $g(x)$.

---

### Example 7:

Check whether $(7+3x)$ is a factor of $(3x^3 + 7x)$.

#### Solution:

Let $p(x) = 3x^3 + 7x$ and $g(x) = 7+3x$. Then,
$g(x) = 0 \Rightarrow 7+3x=0 \Rightarrow 3x=-7 \Rightarrow x = \frac{-7}{3}$.

By the remainder theorem, we know that when $p(x)$ is divided by $(7+3x)$ then the remainder is $p(\frac{-7}{3})$.

Now, $p(\frac{-7}{3}) = \{3 \times (\frac{-7}{3})^3 + 7 \times (\frac{-7}{3})\} = \{3 \times \frac{(-343)}{27} - \frac{49}{3}\}$
$= (\frac{-343}{9} - \frac{49}{3}) = (\frac{-343 - 147}{9}) = \frac{-490}{9} \neq 0$.

Thus, when $p(x)$ is divided by $g(x)$, the remainder is nonzero.
$\therefore (7+3x)$ is **not a factor** of $(3x^3 + 7x)$.

---

### Example 8:

If the polynomials $(2x^3 + ax^2 + 3x - 5)$ and $(x^3 + x^2 - 2x + a)$ leave the same remainder when divided by $(x-2)$, find the value of $a$. Also, find the remainder in each case.

#### Solution:

Let $f(x) = 2x^3 + ax^2 + 3x - 5$ and $g(x) = x^3 + x^2 - 2x + a$.

When $f(x)$ is divided by $(x-2)$, remainder $= f(2)$.
When $g(x)$ is divided by $(x-2)$, remainder $= g(2)$.

Now, $f(2) = (2 \times 2^3 + a \times 2^2 + 3 \times 2 - 5) = (17 + 4a)$.
And, $g(2) = (2^3 + 2^2 - 2 \times 2 + a) = (8 + a)$.

$\therefore 17 + 4a = 8 + a \Rightarrow 3a = -9 \Rightarrow a = -3$.

Hence, $\boldsymbol{a = -3}$.
Remainder in each case $= (8 + (-3)) = \boldsymbol{5}$.

---

