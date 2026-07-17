## Polynomials

An expression of the form $p(x)=a_{0}+a_{1} x+a_{2} x^{2}+\ldots+a_{n} x^{n}$, where $a_{n} \neq 0$, is called a **polynomial** in $x$ of **degree** $n$.

Here $a_{0}, a_{1}, a_{2}, \ldots, a_{n}$ are real numbers and each power of $x$ is a non-negative integer.

### Examples
1. $3x+5$ is a polynomial in $x$ of degree 1.
2. $8x^{2}-5x+3$ is a polynomial in $x$ of degree 2.
3. $2y^{3}+\frac{4}{9} y^{2}-5y+\sqrt{3}$ is a polynomial in $y$ of degree 3.
4. $3z^{4}-5z^{3}+2z^{2}-8z+1$ is a polynomial in $z$ of degree 4.

**REMARK:** Note that $(\sqrt{x}+3)$, $\frac{1}{(x+5)}$, $\frac{6}{\left(x^{2}-3x+1\right)}$, etc., are not polynomials.

#### Linear Polynomial
A polynomial of degree 1 is called a **linear polynomial**. A linear polynomial is of the form $p(x) = ax+b$, where $a \neq 0$.

Thus, $(3x-5)$, $(\sqrt{2}x+3)$, $\left(x-\frac{5}{8}\right)$, etc., are all linear polynomials.

#### Quadratic Polynomial
A polynomial of degree 2 is called a **quadratic polynomial**. A quadratic polynomial is of the form $p(x) = ax^{2}+bx+c$, where $a \neq 0$.

Thus, $\left(3x^{2}+5x-8\right)$, $\left(2x^{2}-2\sqrt{2}x+6\right)$, $\left(y^{2}-3y+\sqrt{3}\right)$, etc., are all quadratic polynomials.

#### Cubic Polynomial
A polynomial of degree 3 is called a **cubic polynomial**. A cubic polynomial is of the form $p(x) = ax^{3}+bx^{2}+cx+d$, where $a \neq 0$.

Thus, $\left(2x^{3}-3x^{2}+8x+1\right)$, $\left(\sqrt{2}y^{3}-2y^{2}+y-8\right)$, $\left(z^{3}+2z^{2}-\sqrt{3}z+3\right)$, etc., are all cubic polynomials.

#### Biquadratic Polynomial
A polynomial of degree 4 is called a **biquadratic polynomial**. A biquadratic polynomial is of the form $p(x) = ax^{4}+bx^{3}+cx^{2}+dx+e$, where $a \neq 0$.

Thus, $\left(2x^{4}+3x^{3}-5x^{2}+9x+1\right)$, $\left(4y^{4}-5y^{3}+6y^{2}-8y+3\right)$, etc., are all biquadratic polynomials.

---
## Value of a Polynomial at a Given Point

If $p(x)$ is a polynomial in $x$ and if $\alpha$ is any real number then the value obtained by putting $x=\alpha$ in $p(x)$ is called the **value of $p(x)$ at $x=\alpha$**.

The value of $p(x)$ at $x=\alpha$ is denoted by $p(\alpha)$.

### Example
Let $p(x) = 2x^{2}-3x+5$. Then,
$$
\begin{aligned}
& p(2)=\left\{2 \times 2^{2}-3 \times 2+5\right\}=(8-6+5)=7 \\
& p(-1)=\left\{2 \times(-1)^{2}-3 \times(-1)+5\right\}=(2+3+5)=10
\end{aligned}
$$
---
### Zeros of a Polynomial
A real number $\alpha$ is called a **zero of the polynomial** $p(x)$, if $p(\alpha)=0$.

### Example
Let $p(x)=x^{2}-2x-3$. Find (i) $p(3)$ and (ii) $p(-1)$. What do you conclude?

#### Solution

We have $p(x)=x^{2}-2x-3$.
$\therefore$ (i) $p(3)=\left(3^{2}-2 \times 3-3\right)=(9-6-3)=0$
and (ii) $p(-1)=\left\{(-1)^{2}-2 \times(-1)-3\right\}=(1+2-3)=0$.

This shows that 3 and -1 are the zeros of the polynomial $p(x)$.

---
## Relation Between the Zeros and Coefficients of a Quadratic Polynomial

Let $\alpha$ and $\beta$ be the zeros of a quadratic polynomial $p(x)=ax^{2}+bx+c$, where $a \neq 0$.

Then, $(x-\alpha)$ and $(x-\beta)$ are the factors of $p(x)$.

$$
\begin{aligned}
\therefore \quad (ax^{2}+bx+c) & =k(x-\alpha)(x-\beta), \text{ where } k \text{ is a constant} \\
& =k \cdot \left\{x^{2}-(\alpha+\beta)x+\alpha\beta\right\} \\
& =kx^{2}-k(\alpha+\beta)x+k(\alpha\beta).
\end{aligned}
$$

On comparing coefficients of like powers of $x$ on both sides, we get
$$
k=a, -k(\alpha+\beta)=b \text{ and } k(\alpha\beta)=c
$$
$$
\Rightarrow \quad -a(\alpha+\beta)=b \text{ and } a(\alpha\beta)=c \quad [\because k=a]
$$
$$
\Rightarrow \quad (\alpha+\beta)=\frac{-b}{a} \text{ and } \alpha\beta=\frac{c}{a}.
$$

$\therefore \quad \text{Sum of zeros} = \frac{-(\text{coefficient of } x)}{(\text{coefficient of } x^{2})}$

$\text{Product of zeros} = \frac{\text{constant term}}{\text{coefficient of } x^{2}}$

---
## Summary

1.  If $\alpha$ and $\beta$ are the zeros of $p(x)=ax^{2}+bx+c, a \neq 0$ then
    - (i) $\alpha+\beta=\frac{-b}{a}$
    - (ii) $\alpha\beta=\frac{c}{a}$

2.  A quadratic polynomial whose zeros are $\alpha$ and $\beta$ is given by $p(x)=\left\{x^{2}-(\alpha+\beta)x+\alpha\beta\right\}$.

---
## Solved Examples

### Example 1
Find the zeros of the polynomial $2x^{2}+5x-12$ and verify the relationship between its zeros and coefficients.

#### Solution
Let the given polynomial be denoted by $f(x)$. Then,
$$
\begin{aligned}
f(x) &= 2x^{2}+5x-12 \\
&= 2x^{2}+8x-3x-12 \\
&= 2x(x+4)-3(x+4) \\
&= (x+4)(2x-3)
\end{aligned}
$$
$$
\begin{aligned}
\therefore \quad f(x)=0 &\Rightarrow (x+4)(2x-3)=0 \\
&\Rightarrow x+4=0 \text{ or } 2x-3=0 \\
&\Rightarrow x=-4 \text{ or } x=\frac{3}{2}
\end{aligned}
$$
So, the zeros of $f(x)$ are -4 and $\frac{3}{2}$.

**Sum of the zeros** = $\left(-4+\frac{3}{2}\right) = \frac{-5}{2} = \frac{-(\text{coefficient of } x)}{(\text{coefficient of } x^{2})}$

**Product of the zeros** = $(-4) \times \frac{3}{2} = \frac{-12}{2} = \frac{\text{constant term}}{(\text{coefficient of } x^{2})}$

---
### Example 2
Find the zeros of the polynomial $6x^{2}-3-7x$ and verify the relationship between the zeros and the coefficients. [CBSE 2008]

#### Solution
Let the given polynomial be denoted by $f(x)$. Then,
$$
\begin{aligned}
f(x) &= 6x^{2}-3-7x \\
&= 6x^{2}-7x-3 \quad [\text{in standard form}] \\
&= 6x^{2}-9x+2x-3 \\
&= 3x(2x-3)+(2x-3) \\
&= (2x-3)(3x+1)
\end{aligned}
$$
$$
\begin{aligned}
\therefore \quad f(x)=0 &\Rightarrow (2x-3)(3x+1)=0 \\
&\Rightarrow 2x-3=0 \text{ or } 3x+1=0 \\
&\Rightarrow x=\frac{3}{2} \text{ or } x=\frac{-1}{3}.
\end{aligned}
$$
So, the zeros of $f(x)$ are $\frac{3}{2}$ and $\frac{-1}{3}$.

**Sum of zeros** = $\left\{\frac{3}{2}+\left(\frac{-1}{3}\right)\right\} = \left(\frac{3}{2}-\frac{1}{3}\right) = \frac{7}{6} = \frac{-(\text{coefficient of } x)}{(\text{coefficient of } x^{2})}$

**Product of zeros** = $\frac{3}{2} \times \left(\frac{-1}{3}\right) = \frac{-3}{6} = \frac{\text{constant term}}{\text{coefficient of } x^{2}}$

---
### Example 3
Find the zeros of the polynomial $f(x)=x^{2}-2$ and verify the relationship between its zeros and coefficients.

#### Solution
We have
$$
f(x) = (x^{2}-2) = \left\{x^{2}-(\sqrt{2})^{2}\right\} = (x+\sqrt{2})(x-\sqrt{2})
$$
$$
\begin{aligned}
\therefore \quad f(x)=0 &\Rightarrow (x+\sqrt{2})(x-\sqrt{2})=0 \\
&\Rightarrow x+\sqrt{2}=0 \text{ or } x-\sqrt{2}=0 \\
&\Rightarrow x=-\sqrt{2} \text{ or } x=\sqrt{2}
\end{aligned}
$$
So, the zeros of $f(x)$ are $-\sqrt{2}$ and $\sqrt{2}$.

**Sum of zeros** = $(-\sqrt{2}+\sqrt{2}) = 0 = \frac{0}{1} = \frac{-(\text{coefficient of } x)}{(\text{coefficient of } x^{2})}$

**Product of zeros** = $(-\sqrt{2}) \times (\sqrt{2}) = \frac{-2}{1} = \frac{\text{constant term}}{\text{coefficient of } x^{2}}$

---
### Example 4
Obtain the zeros of the quadratic polynomial $\sqrt{3}x^{2}-8x+4\sqrt{3}$ and verify the relation between its zeros and coefficients. [CBSE 2008C]

#### Solution
We have
$$
\begin{aligned}
f(x) &= \sqrt{3}x^{2}-8x+4\sqrt{3} = \sqrt{3}x^{2}-6x-2x+4\sqrt{3} \\
&= \sqrt{3}x(x-2\sqrt{3})-2(x-2\sqrt{3}) = (x-2\sqrt{3})(\sqrt{3}x-2)
\end{aligned}
$$
$$
\begin{aligned}
\therefore \quad f(x)=0 &\Rightarrow (x-2\sqrt{3})(\sqrt{3}x-2)=0 \\
&\Rightarrow (x-2\sqrt{3})=0 \text{ or } (\sqrt{3}x-2)=0 \\
&\Rightarrow x=2\sqrt{3} \text{ or } x=\frac{2}{\sqrt{3}}
\end{aligned}
$$
So, the zeros of $f(x)$ are $2\sqrt{3}$ and $\frac{2}{\sqrt{3}}$.

**Sum of zeros** = $\left(2\sqrt{3}+\frac{2}{\sqrt{3}}\right) = \frac{8}{\sqrt{3}} = \frac{-(\text{coefficient of } x)}{(\text{coefficient of } x^{2})}$

**Product of zeros** = $\left(2\sqrt{3} \times \frac{2}{\sqrt{3}}\right) = \frac{4\sqrt{3}}{\sqrt{3}} = \frac{\text{constant term}}{\text{coefficient of } x^{2}}$

---
### Example 5
Find a quadratic polynomial, the sum and product of whose zeros are -5 and 6 respectively.

#### Solution
Let $\alpha$ and $\beta$ be the zeros of the required polynomial $f(x)$.
Then, $(\alpha+\beta)=-5$ and $\alpha\beta=6$.
$$
\begin{aligned}
\therefore \quad f(x) &= x^{2}-(\alpha+\beta)x+\alpha\beta \\
&= x^{2}-(-5)x+6 \\
&= x^{2}+5x+6
\end{aligned}
$$
Hence, the required polynomial is $f(x)=x^{2}+5x+6$.

---
### Example 6
Find the quadratic polynomial, the sum of whose zeros is $\sqrt{2}$ and their product is -12. Hence, find the zeros of the polynomial.

#### Solution
Let $\alpha$ and $\beta$ be the zeros of the required polynomial $f(x)$.
Then, $(\alpha+\beta)=\sqrt{2}$ and $\alpha\beta=-12$.
$$
\begin{aligned}
\therefore \quad f(x) &= x^{2}-(\alpha+\beta)x+\alpha\beta \\
&= x^{2}-\sqrt{2}x-12
\end{aligned}
$$
So, the required polynomial is $f(x)=x^{2}-\sqrt{2}x-12$.
Now,
$$
\begin{aligned}
f(x) &= x^{2}-\sqrt{2}x-12 \\
&= x^{2}-3\sqrt{2}x+2\sqrt{2}x-12 \quad [\text{note it}] \\
&= x(x-3\sqrt{2})+2\sqrt{2}(x-3\sqrt{2}) \\
&= (x-3\sqrt{2})(x+2\sqrt{2})
\end{aligned}
$$
$$
\begin{aligned}
\therefore \quad f(x)=0 &\Rightarrow (x-3\sqrt{2})(x+2\sqrt{2})=0 \\
&\Rightarrow x-3\sqrt{2}=0 \text{ or } x+2\sqrt{2}=0 \\
&\Rightarrow x=3\sqrt{2} \text{ or } x=-2\sqrt{2}.
\end{aligned}
$$
Hence, the required polynomial is $f(x)=x^{2}-\sqrt{2}x-12$ whose zeros are $3\sqrt{2}$ and $-2\sqrt{2}$.

---
### Example 7
If the product of the zeros of the polynomial $(ax^{2}-6x-6)$ is 4, find the value of $a$. [CBSE 2009]

#### Solution
Let $\alpha$ and $\beta$ be the zeros of the polynomial $(ax^{2}-6x-6)$.
Then, $\alpha\beta = \frac{\text{constant term}}{\text{coefficient of } x^{2}} = \frac{-6}{a}$.
But, $\alpha\beta=4$ (given).
$$
\therefore \quad \frac{-6}{a}=4 \Rightarrow 4a=-6 \Rightarrow a=\frac{-6}{4}=\frac{-3}{2}.
$$
Hence, $a=\frac{-3}{2}$.

---
### Example 8
If one zero of the polynomial $(a^{2}+9)x^{2}+13x+6a$ is reciprocal of the other, find the value of a. [CBSE 2008]

#### Solution
Let one zero of the given polynomial be $\alpha$. Then, the other zero is $\frac{1}{\alpha}$.
$\therefore$ product of zeros = $\left(\alpha \times \frac{1}{\alpha}\right)=1$.
But, product of zeros = $\frac{\text{constant term}}{\text{coefficient of } x^{2}} = \frac{6a}{(a^{2}+9)}$.
$$
\begin{aligned}
\therefore \quad \frac{6a}{(a^{2}+9)}=1 &\Rightarrow a^{2}+9=6a \\
&\Rightarrow a^{2}+9-6a=0 \\
&\Rightarrow (a-3)^{2}=0 \\
&\Rightarrow a-3=0 \Rightarrow a=3.
\end{aligned}
$$
Hence, $a=3$.

---
### Example 9
Find a quadratic polynomial whose zeros are 1 and -3. Verify the relation between the coefficients and zeros of the polynomial. [CBSE 2008C]

#### Solution
Let $\alpha=1$ and $\beta=-3$.
Sum of zeros = $(\alpha+\beta)=1+(-3)=-2$.
Product of zeros = $\alpha\beta=1 \times(-3)=-3$.

So, the required polynomial is
$$
\begin{aligned}
x^{2}-(\alpha+\beta)x+\alpha\beta &= x^{2}-(-2)x+(-3) \\
&= x^{2}+2x-3
\end{aligned}
$$
**Sum of zeros** = $-2 = \frac{-2}{1} = \frac{-(\text{coefficient of } x)}{(\text{coefficient of } x^{2})}$

**Product of zeros** = $-3 = \frac{-3}{1} = \frac{\text{constant term}}{\text{coefficient of } x^{2}}$

---
