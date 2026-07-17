## Polynomials

In our previous classes, we have learnt about expressions and various operations on them. Here, we shall review these concepts and extend them to particular types of expressions, known as polynomials.

We shall come across two types of symbols, namely, constants and variables, defined below.

**constants** A symbol having a fixed numerical value is called a constant.
*Examples* $\quad 9,-6, \frac{4}{7}, \sqrt{2}, \pi$ are all constants.

**variables** A symbol which may be assigned different numerical values is known as a variable.
*Example* We know that the circumference of a circle is given by the formula $C=2 \pi r$, where $r$ is the radius of the circle. Here, $2$ and $\pi$ are constants, while $C$ and $r$ are variables.

---

## Algebraic Expressions

A combination of constants and variables, connected by some or all of the operations $+, -, \times$ and $\div$, is known as an **algebraic expression**.

---

## Terms of an Algebraic Expression

The several parts of an algebraic expression separated by $+$ or $-$ operations are called the **terms** of the expression.

*Examples*
- $5x^{2}-9x+4$ is an algebraic expression containing three terms, namely $5x^{2}, -9x$ and $4$.
- $4x^{3}+\sqrt{2}x^{2}-\frac{5}{9}x-8$ is an algebraic expression containing four terms, namely $4x^{3}, \sqrt{2}x^{2}, \frac{-5}{9}x$ and $-8$.
- $y^{6}-64$ is an expression containing two terms, namely $y^{6}$ and $-64$.

---

## Polynomials in One Variable

An expression of the form

$$
a_{0}+a_{1}x+a_{2}x^{2}+\ldots+a_{n-1}x^{n-1}+a_{n}x^{n}
$$

where $a_{0}, a_{1}, a_{2}, \ldots, a_{n-1}, a_{n}$ are real numbers, $a_{n} \neq 0$ and $n$ is a non-negative integer, is called a **polynomial** in $x$ of degree $n$.

Here, $a_{0}$ is called the **constant term** of the given polynomial and $a_{1}, a_{2}, a_{3}, \ldots, a_{n-1}, a_{n}$ are called the **coefficients** of $x, x^{2}, x^{3}, \ldots, x^{n-1}$ and $x^{n}$ respectively.

*Examples*
- $f(x)=7x^{2}-4x+3$ is a polynomial in $x$ of degree 2.
- $g(x)=\sqrt{3}x^{3}+5x^{2}-\frac{3}{4}x-9$ is a polynomial in $x$ of degree 3.
- $h(x)=x^{4}-2x^{3}+5x+\sqrt{2}$ is a polynomial in $x$ of degree 4.
- $p(y)=2y^{5}-6y^{4}+8y^{2}-\frac{5}{7}$ is a polynomial in $y$ of degree 5.
- $q(z)=z^{9}-1$ is a polynomial in $z$ of degree 9.

### Standard Form of a Polynomial
A polynomial in $x$ expressed either in ascending powers of $x$ or in descending powers of $x$ is said to be in **standard form**.

---

### An Illustrative Example

Give reasons to show that none of the following expressions is a polynomial.

1.  $f(x)=x+\frac{1}{x}$
2.  $g(x)=\sqrt{x}-3$
3.  $h(y)=\sqrt[3]{y}-6$
4.  $p(x)=\frac{(x-1)(x-3)}{x}$
5.  $q(x)=\frac{1}{x+2}$
6.  $r(x)=\frac{x+3}{x+4}$

#### Solution:

1.  $f(x)=x+\frac{1}{x}$ may be written as $f(x)=x+x^{-1}$.
    Here, in one term, the exponent of $x$ is $-1$, which is a negative integer.
    $\therefore f(x)$ is not a polynomial.

2.  $g(x)=\sqrt{x}-3$ may be written as $g(x)=x^{1/2}-3$.
    Here, in one term, the exponent of $x$ is $\frac{1}{2}$, which is not a non-negative integer.
    $\therefore g(x)$ is not a polynomial.

3.  $h(y)=\sqrt[3]{y}-6$ may be written as $h(y)=y^{1/3}-6$.
    Here, in one term, the exponent of $y$ is $\frac{1}{3}$, which is not a non-negative integer.
    $\therefore h(y)$ is not a polynomial.

4.  $p(x)=\frac{(x-1)(x-3)}{x}$
    $\Rightarrow p(x)=\frac{x^{2}-4x+3}{x}=\left(x-4+\frac{3}{x}\right)=\left(x-4+3x^{-1}\right)$.
    Here, in one term, the exponent of $x$ is $-1$, which is a negative integer.
    $\therefore p(x)$ is not a polynomial.

5.  $q(x)=\frac{1}{(x+2)}=(x+2)^{-1}$, which is not a polynomial in $(x+2)$ and therefore, it is not a polynomial in $x$.

6.  On dividing $(x+3)$ by $(x+4)$, we get $1$ as quotient and $-1$ as remainder.
    $\therefore$ we may write,
    $$
    \begin{array}{r} 1 \\ x+4 \overline{)x+3} \\ x+4 \\ \hline -1 \end{array}
    $$
    $$
    \frac{x+3}{x+4}=1-\frac{1}{(x+4)}=1-(x+4)^{-1}
    $$
    which is not a polynomial.
    Hence, $r(x)=\frac{x+3}{x+4}$ is not a polynomial.

---

## Polynomials of Various Degrees

### Linear Polynomial
A polynomial of degree 1 is called a **linear polynomial**.
A linear polynomial in $x$ is of the form, $f(x)=ax+b$, where $a$ and $b$ are real numbers and $a \neq 0$.

*Examples*
- $5x+7$ is a linear polynomial in $x$.
- $\sqrt{2}y-6$ is a linear polynomial in $y$.
- $-8z$ is a linear polynomial in $z$.

### Quadratic Polynomial
A polynomial of degree 2 is called a **quadratic polynomial**.
A quadratic polynomial in $x$ is of the form $f(x)=ax^{2}+bx+c$, where $a, b, c$ are real numbers and $a \neq 0$.

*Examples*
- $3x^{2}-8x+9$ is a quadratic polynomial in $x$.
- $4y^{2}-9y+5$ is a quadratic polynomial in $y$.
- $z^{2}-11z+18$ is a quadratic polynomial in $z$.

### Cubic Polynomial
A polynomial of degree 3 is called a **cubic polynomial**. A cubic polynomial in $x$ is of the form $ax^{3}+bx^{2}+cx+d$, where $a, b, c, d$ are real numbers and $a \neq 0$.

*Examples*
- $4x^{3}-x^{2}+6x+3$ is a cubic polynomial in $x$.
- $7y^{3}+5y^{2}-8y+9$ is a cubic polynomial in $y$.
- $8-z^{3}$ is a cubic polynomial in $z$.

### Biquadratic Polynomial
A polynomial of degree 4 is called a **biquadratic** or **quartic polynomial**.
A biquadratic polynomial is of the form $ax^{4}+bx^{3}+cx^{2}+dx+e$, where $a, b, c, d, e$ are real numbers and $a \neq 0$.

*Examples*
- $x^{4}-2x^{3}+3x^{2}-4x+5$ is a biquadratic polynomial in $x$.
- $3y^{4}+8y^{3}-5y^{2}+7$ is a biquadratic polynomial in $y$.
- $6z^{4}-9z^{2}+1$ is a biquadratic polynomial in $z$.

---

## Number of Terms in a Polynomial

### Monomial
A polynomial containing one term is called a **monomial**. ('Mono' means 'one'.)
*Examples* $9, -14, 6x, -8x^{2}, 5x^{3}, 2x^{4}$, etc., are all monomials.

### Binomial
A polynomial containing two nonzero terms is called a **binomial**. ('Bi' means 'two'.)
*Examples* $(9+4x), (x-3x^{2}), (8+x^{3}), (-x^{4}+7)$ are all binomials.

### Trinomial
A polynomial containing three nonzero terms is called a **trinomial**. ('Tri' means 'three'.)
*Examples* $(x^{2}+2x-3), (2x^{3}+5x^{2}-4), (-7x^{4}+5x^{2}+6), (5x^{6}-3x^{4}+x)$ are all trinomials.

### Constant Polynomial
A polynomial containing one term, consisting of a nonzero constant, is called a **constant polynomial**.
In general, every nonzero real number is a constant polynomial. The degree of a nonzero constant polynomial is zero.
*Examples* $\quad 6, -8, \frac{9}{14}, \frac{-7}{12}, \pi$, etc., are all constant polynomials.

### Zero Polynomial
A polynomial consisting of one term, namely zero, is called a **zero polynomial**.
The degree of a zero polynomial is not defined.

---

## Solved Examples

### Example 1

Which of the following expressions are polynomials? In case of a polynomial write its degree.

1.  $x^{3}-5x+2$
2.  $y^{2}+\sqrt{2}y-\sqrt{5}$
3.  $2\sqrt{x}+7$
4.  $-6$
5.  $4t^{2}+\frac{1}{6}t+2\sqrt{3}$
6.  $z^{2}+\frac{5}{z^{2}}+1$
7.  $\frac{1}{3x}$
8.  $1-\sqrt{5x}$
9.  $\frac{1}{4x^{-2}}+3x+5$
10. $\frac{6\sqrt{x}+x^{3/2}}{\sqrt{x}}$

#### Solution:

1.  $x^{3}-5x+2$ is an expression having only non-negative integral powers of $x$. So, it is a polynomial. The highest power of $x$ is 3. So, it is a polynomial of degree 3.

2.  $y^{2}+\sqrt{2}y-\sqrt{5}$ is an expression having only non-negative integral powers of $y$. So, it is a polynomial. The highest power of $y$ is 2. So, it is a polynomial of degree 2.

3.  $2\sqrt{x}+7$ is an expression in which one term, namely $2\sqrt{x}$ (written as $2x^{1/2}$), has rational power of $x$. So, it is not a polynomial.

4.  $-6$ is clearly a constant polynomial of degree 0.

5.  $4t^{2}+\frac{1}{6}t+2\sqrt{3}$ is an expression having only non-negative integral powers of $t$. So, it is a polynomial in $t$. The highest power of $t$ is 2. So, it is a polynomial of degree 2.

6.  $z^{2}+\frac{5}{z^{2}}+1$ may be written as $z^{2}+5z^{-2}+1$. Here, in one term, the exponent of $z$ is $-2$, which is a negative integer. So, the given expression is not a polynomial.

7.  $\frac{1}{3x}$ may be written as $\frac{1}{3}x^{-1}$, which is not a polynomial.

8.  $1-\sqrt{5x}$ may be written as $1-\sqrt{5}x^{1/2}$. Thus, in one term, the exponent of $x$ is $\frac{1}{2}$, which is rational. So, the given expression is not a polynomial.

9.  $\frac{1}{4x^{-2}}+3x+5$ may be written as $\frac{1}{4}x^{2}+3x+5$. Thus, it is an expression having only non-negative integral powers of $x$. So, the given expression is a polynomial of degree 2.

10. $\frac{6\sqrt{x}+x^{3/2}}{\sqrt{x}}$ may be written as $\frac{6\sqrt{x}}{\sqrt{x}}+\frac{x^{3/2}}{x^{1/2}}=6+x^{\left(\frac{3}{2}-\frac{1}{2}\right)}=6+x$, which is clearly a polynomial of degree 1.

---

### Example 2

Classify the following as constant, linear, quadratic, cubic and quartic polynomials.

1.  $x-x^{3}$
2.  $y^{4}-y$
3.  $y+y^{2}+4$
4.  $\sqrt{2}x-1$
5.  $5x^{3}$
6.  $3$
7.  $t^{2}$
8.  $2+x$
9.  $5t-\sqrt{7}$

#### Solution:

1.  $x-x^{3}$ is a polynomial of degree 3. So, it is a cubic polynomial.
2.  $y^{4}-y$ is a polynomial of degree 4. So, it is a quartic polynomial.
3.  $y+y^{2}+4$ is a polynomial of degree 2. So, it is a quadratic polynomial.
4.  $\sqrt{2}x-1$ is a polynomial of degree 1. So, it is a linear polynomial.
5.  $5x^{3}$ is a polynomial of degree 3. So, it is a cubic polynomial.
6.  Clearly, $3$ is a constant polynomial and its degree is 0.
7.  $t^{2}$ is a polynomial of degree 2. So, it is a quadratic polynomial.
8.  $2+x$ is a polynomial of degree 1. So, it is a linear polynomial.
9.  $5t-\sqrt{7}$ is a polynomial of degree 1. So, it is a linear polynomial.

---

### Example 3

Write the coefficient of $x^{2}$ in each of the following.

1.  $(x-1)(3x-4)$
2.  $(2x-5)(2x^{2}-3x+1)$
3.  $5x-3$
4.  $\frac{\pi}{2}x^{2}+x$

#### Solution:
We have:

1.  $(x-1)(3x-4)=3x^{2}-7x+4$.
    $\therefore$ coefficient of $x^{2}$ in $(x-1)(3x-4)$ is $3$.
2.  $(2x-5)(2x^{2}-3x+1)=4x^{3}-16x^{2}+17x-5$.
    $\therefore$ coefficient of $x^{2}$ in $(2x-5)(2x^{2}-3x+1)$ is $-16$.
3.  Coefficient of $x^{2}$ in $5x-3$ is $0$.
4.  Coefficient of $x^{2}$ in $\frac{\pi}{2}x^{2}+x$ is $\frac{\pi}{2}$.

---

### Example 4

Give an example of a polynomial, which is

1.  a monomial of degree 1
2.  a monomial of degree 5
3.  a binomial of degree 20
4.  a trinomial of degree 3

#### Solution:

1.  $x$ is a monomial of degree 1.
2.  $x^{5}$ is a monomial of degree 5.
3.  $(5+x^{20})$ is a binomial of degree 20.
4.  $(2+3x+5x^{3})$ is a trinomial of degree 3.

---

### Example 5

For the polynomial $\frac{x^{3}+2x+3}{5}-\frac{7}{2}x^{2}-x^{6}$, write

1.  the degree of the polynomial,
2.  the coefficient of $x^{3}$,
3.  the coefficient of $x^{6}$,
4.  the constant term.

#### Solution:

The given polynomial may be written as
$$
-x^{6}+\frac{1}{5}x^{3}-\frac{7}{2}x^{2}+\frac{2}{5}x+\frac{3}{5}
$$
1.  The degree of the given polynomial is 6.
2.  The coefficient of $x^{3}$ is $\frac{1}{5}$.
3.  The coefficient of $x^{6}$ is $-1$.
4.  The constant term is $\frac{3}{5}$.

---

### Example 6

Determine the degree of each of the following polynomials.

1.  $x^{3}-9x+3x^{5}$
2.  $y^{3}(1-y^{4})$
3.  $-2x+1$
4.  $-10$

#### Solution:

1.  The given polynomial is $3x^{5}+x^{3}-9x$.
    Clearly, it is a polynomial of degree 5.
2.  $y^{3}(1-y^{4})=y^{3}-y^{7}=-y^{7}+y^{3}$, which is a polynomial of degree 7.
3.  $-2x+1$ is a polynomial of degree 1.
4.  $-10$ is a constant polynomial. So, its degree is 0.

---

