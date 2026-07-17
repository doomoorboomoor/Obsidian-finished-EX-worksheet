## Relation Between the Zeros and Coefficients of a Cubic Polynomial

Let $\alpha$, $\beta$ and $\gamma$ be the zeros of a cubic polynomial

$$
p(x) = ax^3 + bx^2 + cx + d, \text{ where } a \neq 0.
$$

Then, $(x-\alpha)$, $(x-\beta)$ and $(x-\gamma)$ are the factors of $p(x)$.

$$
\begin{aligned}
\therefore \quad (ax^3 + bx^2 + cx + d) & = k(x-\alpha)(x-\beta)(x-\gamma) \text{ for some constant } k \\
& = k\{x^3 - (\alpha+\beta+\gamma)x^2 + (\alpha\beta+\beta\gamma+\gamma\alpha)x - (\alpha\beta\gamma)\} \\
& = kx^3 - k(\alpha+\beta+\gamma)x^2 + k(\alpha\beta+\beta\gamma+\gamma\alpha)x - k(\alpha\beta\gamma).
\end{aligned}
$$

Comparing coefficients of like powers of $x$ on both sides, we get

$$
\begin{aligned}
& k = a, -k(\alpha+\beta+\gamma) = b, k(\alpha\beta+\beta\gamma+\gamma\alpha) = c, -k(\alpha\beta\gamma) = d \\
\Rightarrow \quad & -a(\alpha+\beta+\gamma) = b, a(\alpha\beta+\beta\gamma+\gamma\alpha) = c, -a(\alpha\beta\gamma) = d \quad [\because k=a] \\
\Rightarrow \quad & (\alpha+\beta+\gamma) = \frac{-b}{a}, (\alpha\beta+\beta\gamma+\gamma\alpha) = \frac{c}{a}, \alpha\beta\gamma = \frac{-d}{a}.
\end{aligned}
$$

---

## Summary

I. If $\alpha$, $\beta$ and $\gamma$ are the zeros of $p(x) = ax^3 + bx^2 + cx + d$ then
   - (i) $(\alpha+\beta+\gamma) = \frac{-b}{a}$
   - (ii) $(\alpha\beta+\beta\gamma+\gamma\alpha) = \frac{c}{a}$
   - (iii) $\alpha\beta\gamma = \frac{-d}{a}$.

II. A cubic polynomial whose zeros are $\alpha$, $\beta$ and $\gamma$ is given by
    $$
    p(x) = \{x^3 - (\alpha+\beta+\gamma)x^2 + (\alpha\beta+\beta\gamma+\gamma\alpha)x - \alpha\beta\gamma\}.
    $$

---

## Solved Examples

### Example 1:

Verify that $3, -1$ and $\frac{-1}{3}$ are the zeros of the cubic polynomial $p(x) = 3x^3 - 5x^2 - 11x - 3$ and verify the relation between its zeros and coefficients.

#### Solution:

The given polynomial is $p(x) = 3x^3 - 5x^2 - 11x - 3$.

$$
\begin{aligned}
\therefore \quad p(3) & = \{3 \times 3^3 - 5 \times 3^2 - 11 \times 3 - 3\} = (81 - 45 - 33 - 3) = 0; \\
p(-1) & = \{3 \times (-1)^3 - 5 \times (-1)^2 - 11 \times (-1) - 3\} \\
& = (-3 - 5 + 11 - 3) = 0;
\end{aligned}
$$

and
$$
\begin{aligned}
p\left(\frac{-1}{3}\right) & = \left\{3 \times \left(\frac{-1}{3}\right)^3 - 5 \times \left(\frac{-1}{3}\right)^2 - 11 \times \left(\frac{-1}{3}\right) - 3\right\} \\
& = \left\{3 \times \left(\frac{-1}{27}\right) - 5 \times \frac{1}{9} + \frac{11}{3} - 3\right\} = \left(\frac{-1}{9} - \frac{5}{9} + \frac{11}{3} - 3\right) \\
& = \frac{(-1 - 5 + 33 - 27)}{9} = 0.
\end{aligned}
$$

$\therefore 3, -1$ and $\frac{-1}{3}$ are the zeros of $p(x)$.

Let $\alpha = 3$, $\beta = -1$ and $\gamma = \frac{-1}{3}$. Then,

$$
\begin{aligned}
& (\alpha+\beta+\gamma) = \left(3 - 1 - \frac{1}{3}\right) = \frac{5}{3} = \frac{-(\text{coefficient of } x^2)}{(\text{coefficient of } x^3)} \\
& (\alpha\beta+\beta\gamma+\gamma\alpha) = \left(-3 + \frac{1}{3} - 1\right) = \frac{-11}{3} = \frac{(\text{coefficient of } x)}{(\text{coefficient of } x^3)} \\
& \alpha\beta\gamma = \left\{3 \times (-1) \times \left(\frac{-1}{3}\right)\right\} = 1 = \frac{3}{3} = \frac{-(\text{constant term})}{(\text{coefficient of } x^3)}
\end{aligned}
$$

---

### Example 2:

Find a cubic polynomial with the sum of its zeros, sum of the products of its zeros taken two at a time and the product of its zeros as $2, -7$ and $-14$ respectively.

#### Solution:

Let $\alpha, \beta, \gamma$ be the zeros of the required polynomial. Then,

$$
\alpha+\beta+\gamma = 2, \quad \alpha\beta+\beta\gamma+\gamma\alpha = -7 \text{ and } \alpha\beta\gamma = -14.
$$

So, the required polynomial is

$$
\begin{aligned}
p(x) & = x^3 - (\alpha+\beta+\gamma)x^2 + (\alpha\beta+\beta\gamma+\gamma\alpha)x - \alpha\beta\gamma \\
& = x^3 - 2x^2 - 7x - (-14) = x^3 - 2x^2 - 7x + 14.
\end{aligned}
$$

---

### Example 3:

If the zeros of the polynomial $x^3 - 3x^2 + x + 1$ are $(a-b)$, $a$, $(a+b)$, find $a$ and $b$.

#### Solution:

Given polynomial is $f(x) = x^3 - 3x^2 + x + 1$.

Let $\alpha = (a-b)$, $\beta = a$ and $\gamma = (a+b)$. Then,

$$
\begin{aligned}
& \alpha+\beta+\gamma = 3 \Rightarrow (a-b)+a+(a+b) = 3 \Rightarrow 3a = 3 \Rightarrow a=1. \\
& \alpha\beta+\beta\gamma+\gamma\alpha = 1 \Rightarrow a(a-b)+a(a+b)+(a+b)(a-b) = 1 \\
& \quad \Rightarrow 3a^2 - b^2 = 1 \Rightarrow (3 \times 1^2) - b^2 = 1 \\
& \quad \Rightarrow b^2 = 2 \Rightarrow b = \pm \sqrt{2}.
\end{aligned}
$$

---

### Example 4:

Find a cubic polynomial whose zeros are $3, \frac{1}{2}$ and $-1$.

#### Solution:

Let $\alpha = 3$, $\beta = \frac{1}{2}$ and $\gamma = -1$. Then,

$$
\begin{aligned}
& (\alpha+\beta+\gamma) = \left(3 + \frac{1}{2} - 1\right) = \frac{5}{2} \\
& (\alpha\beta+\beta\gamma+\gamma\alpha) = \left(\frac{3}{2} - \frac{1}{2} - 3\right) = \frac{-4}{2} = -2 \\
& \alpha\beta\gamma = \left\{3 \times \frac{1}{2} \times (-1)\right\} = \frac{-3}{2}
\end{aligned}
$$

Hence, the required polynomial is

$$
x^3 - (\alpha+\beta+\gamma)x^2 + (\alpha\beta+\beta\gamma+\gamma\alpha)x - \alpha\beta\gamma = x^3 - \frac{5}{2}x^2 - 2x + \frac{3}{2}
$$

Thus, $2x^3 - 5x^2 - 4x + 3$ is the desired polynomial.

---

## Division Algorithm for Polynomials

If $f(x)$ and $g(x)$ are any two polynomials with $g(x) \neq 0$ then we can find polynomials $q(x)$ and $r(x)$ such that

$$
f(x) = q(x) \times g(x) + r(x)
$$

where $r(x)=0$ or $\{\text{degree of } r(x)\} < \{\text{degree of } g(x)\}$.

We may write it as

**Dividend** = (**Quotient** $\times$ **Divisor**) + **Remainder**.

---

## Some More Examples

### Example 5:

Divide $3 - x + 2x^2$ by $(2-x)$ and verify the division algorithm.

#### Solution:

First we write the terms of dividend and divisor in decreasing order of their degrees and then perform the division as shown below.