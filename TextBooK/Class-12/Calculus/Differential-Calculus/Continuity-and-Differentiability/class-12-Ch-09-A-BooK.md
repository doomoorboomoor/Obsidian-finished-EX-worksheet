## 9. Continuity and Differentiability

## Functions

### Real Functions

Let $R$ be the set of all real numbers, and let $X$ and $Y$ be any two nonempty subsets of $R$. Then, a rule $f$ which associates to each $x \in X$, a unique real number $f(x) \in Y$ is called a **real function** from $X$ to $Y$ and we write, $f: X \rightarrow Y$.

$f(x)$ is called the **image** of $x$ or the **value of the function** at $x$. The sets $X$ and $Y$ are respectively known as the **domain** and the **codomain** of $f$.

Also, the set $\{f(x): x \in X\}$ is called the **range** of $f$.

Clearly, range $(f) \subseteq Y$.

However, if range $(f)=Y$, we say that $f$ is an **onto function**; otherwise $f$ is said to be an **into function**.

If two or more than two elements in $X$ have the same image in $Y$ then $f$ is said to be a **many-one function**.

On the other hand, if different elements in $X$ have different images in $Y$, we say that $f$ is **one-one**.

Clearly, $f$ is one-one $\Leftrightarrow\left[f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow x_{1}=x_{2}\right]$.

A one-one onto function is called a **one-to-one correspondence**.

**REMARK 1** Sometimes a function is described only by a formula and the domain of the function is not explicitly stated. In such cases, the domain of the function is the set of all those real numbers for which the formula is meaningful.

**REMARK 2** Usually the domain of a real function is an interval. For any two real numbers $a$ and $b$, where $a<b$, we define
- **(i) closed interval** $[a, b]=\{x \in R: a \leq x \leq b\}$
- **(ii) onj h\npen interval** $] a, b[=\{x \in R: a<x<b\}$
- **(iii) right-half open interval** $[a, b[=\{x \in R: a \leq x<b\}$
- **(iv) left-half open interval** $] a, b]=\{x \in R: a<x \leq b\}$
- **(v)** $] a, \infty[=\{x \in R: x>a\}$
- **(vi)** $[a, \infty[=\{x \in R: x \geq a\}$
- **(vii)** $]-\infty, a[=\{x \in R: x<a\}$
- **(viii)** $]-\infty, a]=\{x \in R: x \leq a\}$

Sometimes, we write, $R=]-\infty, \infty[$.

---

### Some Important Functions

**1. Constant Function**
Let $c$ be a fixed real number. Then, the function defined by $f(x)=c$ for all $x \in R$ is called a **constant function** $c$.

Clearly, $\operatorname{dom}(f)=R$ and range $(f)=\{c\}$.

**2. Identity Function**
The function defined by $f(x)=x$ for all $x \in R$ is called the **identity function**.

Clearly, its domain is $R$ and its range is $R$.

**3. Modulus Function**
The function defined by

$$
f(x)=|x|=\left\{\begin{array}{r}
x, \text { when } x \geq 0 \\
-x,
\end{array} \text { when } x<0\right.
$$

is called the **modulus function**.
Since the modulus of every real number is a unique non-negative real number, so dom $f(x)=R$.
Since $|x|$ is either 0 or a positive real number, we have

$$
\operatorname{range}(f)=\{|x|: x \in R\}=\text { set of non-negative real numbers. }
$$

**4. Reciprocal Function**
The function defined by $f(x)=\frac{1}{x}$ is called the **reciprocal function**.

Clearly, $\frac{1}{x}$ is not defined when $x=0$.
$\therefore \quad \operatorname{dom}(f)=R-\{0\}$.
Also, $y=\frac{1}{x} \Leftrightarrow x=\frac{1}{y}$.
Clearly, $x$ is defined for all real numbers $y$ except when $y=0$.
$\therefore$ range $(f)=R-\{0\}$.

**5. Signum Function**
This function is defined by

$$
f(x)=\left\{\begin{array}{c}\frac{|x|}{x}, \text { when } x \neq 0 \\ 0, \text { when } x=0 .\end{array}\right.
$$

Thus, we have $f(x)=\left\{\begin{array}{r}1, \text { when } x>0 \\ 0, \text { when } x=0 \\ -1, \text { when } x<0 .\end{array}\right.$
Clearly, its domain is $R$ and $\text{range} = \{-1,0,1\}$.

**6. Square-Root Function**
Let $f(x)=+\sqrt{x}$.

We know that the negative real numbers do not have real square roots. So, $f(x)$ is not defined when $x$ is a negative real number.
$\therefore \quad \operatorname{dom}(f)=$ set of all non-negative real numbers $=[0, \infty[$.
Clearly, range $(f)=\{+\sqrt{x}: x \in[0, \infty[ \}=[0, \infty[$.

**7. Step Function or The Greatest Integer Function**

If $x \in R$ then $[x]$ is defined as the **greatest integer not exceeding $x$**.
For example, we have

$[2.01]=2 ;[2.9]=2 ;[-1.3]=-2 ;[3]=3 \text { and } [-1]=-1, \text { etc.}$

Now, if we consider $f(x)=[x]$ then clearly for each $x \in R,[x]$ is defined.
So $\operatorname{dom}(f)=R$.
By definition, $[x]$ is an integer.
So, range $(f)=\{[x]: x \in R\}=$ set of all integers.

---

### Example:

Find a set of all real numbers $x$ such that $[x]=2$.

#### Solution:

Clearly, for all $x$ such that $2 \leq x<3$, we have $f(x)=[x]=2$.
$\therefore$ required set $=\{x \in R: 2 \leq x<3\}=[2,3[$.

---

**8. Smallest Integer Function (or Ceiling Function)**
For any real number $x$, we define $\lceil x\rceil$ as the **smallest integer greater than or equal to $x$**.

For example,

$\lceil 6.3\rceil=7,\lceil 7.01\rceil=8,\lceil-6.1\rceil=-6,\lceil-2.9\rceil=-2,\lceil-3\rceil=-3,\lceil 5\rceil=5 .$

The function $f: R \in R: f(x)=\lceil x\rceil, x \in R$ is called the **smallest integer function** or **ceiling function**.
Clearly, domain $(f)=R$ and range $(f)=I$.

**9. Polynomial Function**
A function of the form

$$
p(x)=a_{0} x^{n}+a_{1} x^{n-1}+a_{2} x^{n-2}+\ldots+a_{n-1} x+a_{n},
$$

where $a_{0}, a_{1}, a_{2}, \ldots, a_{n-1}, a_{n}$ are real numbers, $a_{0} \neq 0$ and $n$ is a non-negative integer, is called a **polynomial function of degree $n$**.
Polynomials of degree $1, 2, 3$ and $4$ are respectively called **linear**, **quadratic**, **cubic** and **biquadratic** polynomials.
Thus,
- **(i)** $f(x)=a x+b, a \neq 0$, is a **linear polynomial**.
- **(ii)** $f(x)=a x^{2}+b x+c, a \neq 0$, is a **quadratic polynomial**.
- **(iii)** $f(x)=a x^{3}+b x^{2}+c x+d, a \neq 0$, is a **cubic polynomial**.

**10. Rational Function**
A function of the form $f(x)=\frac{p(x)}{q(x)}$, where $p(x)$ and $q(x)$ are polynomials and $q(x) \neq 0$, is called a **rational function**.

Thus, $f(x)=\left(\frac{x^{2}+1}{x^{3}-2 x+5}\right)$ is a rational function, where $x^{3}-2 x+5 \neq 0$.

---

## Graphs

### Graph of a Function

For a given function $f(x)$, the aggregate of the points $\{x, f(x)\}$ is called the **graph** or the **curve** representing the function.

In practice, we plot some of the points and join them freehand to obtain the graph.

---

### Example 1:

Draw the graphs of the constant functions
(i) $f(x)=2$
(ii) $f(x)=0$
(iii) $f(x)=-2$

#### Solution:

- **(i)** When $f(x)=2$ for all $x \in R$, some of the points on the graph may be taken as $(0,2),(-1,2),(1,2),(-2,2)$, $(2,2)$, etc. Joining these points, we obtain a line $y=2$, drawn parallel to the $x$-axis at a distance of 2 units from it, as the required graph.

![Graph of f(x)=2](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-004.jpg?height=298&width=347&top_left_y=188&top_left_x=860)

- **(ii)** The graph of the function $f(x)=0$ is the line $y=0$, i.e., the $x$-axis.

- **(iii)** The graph of the function $f(x)=-2$ is the line $y=-2$, drawn parallel to the $x$-axis at a distance of 2 units below the $x$-axis.

![Graph of f(x)=-2](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-004.jpg?height=307&width=347&top_left_y=554&top_left_x=860)

---

### Example 2:

Draw the graphs of the linear functions
(i) $f(x)=1-x$
(ii) $f(x)=2 x+1$

#### Solution:

- **(i)** When $f(x)=1-x$, some of the points on the graph are $(0,1)$, $(1,0),(2,-1),(-1,2)$, etc.
Joining these points, we get a line as the graph of the function.

![Graph of f(x)=1-x](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-004.jpg?height=313&width=347&top_left_y=933&top_left_x=860)

- **(ii)** Let $f(x)=2 x+1$.
Some of the points on the graph are $(0,1),(1,3),(-1,-1),(2,5)$, etc.
Joining these points, we obtain a line as the graph.

![Graph of f(x)=2x+1](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-004.jpg?height=311&width=345&top_left_y=1259&top_left_x=864)

**REMARK** The graph of a linear function is a straight line.

---

### Example 3:

Draw the graph of the identity function $f(x)=x$.

#### Solution:

$f(x)=x$ is clearly a linear function whose graph must be a line. Plotting the points $(0,0),(1,1),(-1,-1)$, etc., and joining them, we get the required graph.

![Graph of f(x)=x](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-004.jpg?height=308&width=353&top_left_y=1620&top_left_x=857)

---

### Example 4:

Draw the graphs of the polynomial functions
(i) $f(x)=x^{2}$
(ii) $f(x)=1-x^{2}$
(iii) $f(x)=x^{3}-x$

#### Solution:

- **(i)** The function $f(x)=x^{2}$ is a quadratic function. Some of the points on the graph are $(0,0)$, $(1,1),(-1,1),(-2,4),(2,4),(-3,9)$, $(3,9)$, etc. Joining these points, we get a parabola as the graph.

![Graph of f(x)=x^2](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-005.jpg?height=317&width=355&top_left_y=206&top_left_x=852)

- **(ii)** $f(x)=1-x^{2}$ is also a quadratic function. Some of the points on the graph are
$(0,1), \quad(1,0), \quad(-1,0), \quad(2,-3)$, $(-2,-3),(-3,-8),(3,-8)$, etc.
Joining these points, we obtain a parabola as its graph.

![Graph of f(x)=1-x^2](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-005.jpg?height=302&width=353&top_left_y=573&top_left_x=854)

- **(iii)** Let $f(x)=x^{3}-x$.
This is a cubic function.
Some of the points on the graph are $(0,0),(-1,0),(1,0)$, $(-0.5,0.375),(0.5,-0.375),(2,6)$, ( $-2,-6$ ), etc.
Joining these points, we obtain the required graph.

![Graph of f(x)=x^3-x](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-005.jpg?height=302&width=359&top_left_y=907&top_left_x=854)

**REMARK** It may be observed here that whenever $(x, y)$ is a point on the graph then
( $-x,-y$ ) is also a point on the graph. So, the graph is symmetrical about the origin.
This is an important property possessed by the graph of an **odd function**.

---

### Example 5:

Draw the graph of the modulus function $f(x)=|x|$.

#### Solution:

$f(x)=|x|=\left\{\begin{aligned} x & \text { when } x \geq 0 \\ -x & \text { when } x<0\end{aligned}\right.$
Some of the points on the graph are $(0,0),(-1,1),(-2,2),(1,1),(2,2)$, etc.

Joining these points, we get the required graph.

![Graph of f(x)=|x|](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-005.jpg?height=323&width=376&top_left_y=1581&top_left_x=833)

**REMARK** It may be observed here that whenever ( $x, y$ ) is a point on the graph, then ( $-x, y$ ) is also a point of it. Thus, the graph is symmetrical about the $y$-axis. This is an important property possessed by the graphs of **even functions**.

---

### Example 6:

Draw the graph of the reciprocal function $f(x)=\frac{1}{x}$.

#### Solution:

Clearly, $f(x)=\frac{1}{x}$ is not defined at $x=0$. Some points on the graph are $(1,1),(-1,-1),(1 / 2,2),(2,1 / 2)$, $(-1 / 2,-2), \quad(-2,-1 / 2), \quad(1 / 3,3)$, $(-1 / 3,-3),(3,1 / 3)$, etc.
Joining these points, we get the required graph. Since $f(x)=\frac{1}{x}$ is an **odd function**, it is symmetrical about the origin.

![Graph of f(x)=1/x](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-006.jpg?height=318&width=378&top_left_y=459&top_left_x=835)

---

### Example 7:

Draw the graph of the square-root function $f(x)=\sqrt{x}$.

#### Solution:

Let $f$ be a real-valued function which associates to each non-negative real number $x$, its non-negative square root.
Then, $f: R_{0}^{+} \rightarrow R_{0}^{+}: f(x)=\sqrt{x}$, is called the **square-root function**.
$\text{Domain } f(x) = R_{0}^{+}$, and $\text{range}(f) = R_{0}^{+}$.
Some of the points on the graph are $(0,0),(1,1),(2,1.4),(3,1.7)$, $(4,2),(5,2.2)$, etc. Joining these points, we get the required graph.

![Graph of f(x)=sqrt(x)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-006.jpg?height=389&width=451&top_left_y=950&top_left_x=758)

---

### Example 8:

Draw the graph of the rational function $f(x)=\frac{x^{2}-1}{x-1}$.

#### Solution:

Let $f(x)=\frac{x^{2}-1}{x-1}$.
Now, $f(1)=\frac{0}{0}$, which is meaningless.
So, the function is not defined at $x=1$. Also, when $x \neq 1$, we have

$f(x)=\left(\frac{x^{2}-1}{x-1}\right)=(x+1)$

![Graph of f(x)=(x^2-1)/(x-1)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-006.jpg?height=318&width=369&top_left_y=1455&top_left_x=840)

This being a linear function, its graph is a straight line.
Some of the points on the graph are $(0,1),(-1,0),(2,3),(3,4)$, $(-2,-1),(-3,-2)$, etc.

Joining these points, we obtain the required graph. Clearly, the point $(1,2)$ does not lie on the graph. So, it is a broken graph, and we shall say that the given function is **discontinuous at $x=1$**.

---

### Example 9:

Draw the graph of the step function $f(x)=[x]$.

#### Solution:

As the definition of the function indicates,
for all $x$ such that $-2 \leq x<-1$, we have $f(x)=-2$;
for all $x$ such that $-1 \leq x<0$, we have $f(x)=-1$;
for all $x$ such that $0 \leq x<1$, we have $f(x)=0$;

![Graph of f(x)=[x] (step function)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-007.jpg?height=325&width=431&top_left_y=290&top_left_x=776)

for all $x$ such that $1 \leq x<2$, we have $f(x)=1$, and so on,
i.e., $f(x)=\left[\begin{array}{l}-2 \text { when } x \in[-2,-1[ \\ -1 \text { when } x \in[-1,0[ \\ 0 \text { when } x \in[0,1[ \\ 1 \text { when } x \in[1,2[ \\ \text { and so on. }\end{array}\right.$
Clearly, the function jumps at the points $(-1,-2),(0,-1),(1,0)$, ( 2,1 ), etc.
In other words, the given function is **discontinuous at each integral value of $x$**.

---

### Example 10:

Draw the graph of the smallest integer function $f(x)=\lceil x\rceil$.

#### Solution:

As the definition of the function suggests,
for all $x$ such that $-3<x \leq-2$, we have $f(x)=-2$;
for all $x$ such that $-2<x \leq-1$, we have $f(x)=-1$;
for all $x$ such that $-1<x \leq 0$, we have $f(x)=0$;
for all $x$ such that $0<x \leq 1$, we have $f(x)=1$;
and so on.
i.e., $f(x)=\left[\begin{array}{llll}-2 \text { when } x \in]-3,-2] & & \\ -1 \text { when } x \in]-2, & -1] \\ 0 \text { when } x \in]-1, & 0\end{array}\right]$ jumps at the points $(-2,-1),(-1,0),(0,1),(1,2)$, etc., or is **discontinuous at each integral value of $x$**.

---

### Example 11:

Draw the graph of the signum function $f(x)=\left\{\begin{array}{c}\frac{|x|}{x} \text { when } x \neq 0 \\ 0 \text { when } x=0 .\end{array}\right.$

#### Solution:

Clearly, $(0,0)$ is a point on the graph. Now, when $x>0$, we have $|x|=x$, and so in this case, we have, $f(x)=1$, i.e., $f(x)=1$ for all values of $x>0$.
And, when $x<0$, we have $|x|=-x$ and therefore,

$f(x)=-1 \text { for all values of } x<0$

Hence the graph may be drawn, as shown in the adjoining figure.
Clearly, the function is broken (i.e., it is discontinuous) at each of the points $x=-1, 0$ and $1$.

![Graph of signum function](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-008.jpg?height=309&width=370&top_left_y=379&top_left_x=837)

---

### Example 12:

Draw the graph of the function

$$
f(x)=\left\{\begin{array}{l}x^{2}, \text { when } x<0 \\ x, \text { when } 0 \leq x \leq 1 \\ 1 / x, \text { when } 1 \leq x<\infty .\end{array}\right.
$$

#### Solution:

Here, the graph consists of three parts. Some of the points of the graph are $(-3,9),(-2,4),(-1,1)$, $(0,0),\left(\frac{1}{2}, \frac{1}{2}\right),\left(\frac{3}{4}, \frac{3}{4}\right),(1,1),\left(2, \frac{1}{2}\right)$, $\left(3, \frac{1}{3}\right)$, etc.

![Graph of piecewise function](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-008.jpg?height=301&width=414&top_left_y=892&top_left_x=799)

And, the graph may now be drawn, as shown in the adjoining figure.

---

### Example 13:

Draw the graph of the function $f(x)=|x|+|x-1|$.

#### Solution:

Let us consider the following cases.

**Case I: When $x<0$**
In this case, $(x-1)<0$.
$\therefore|x|=-x$ and $|x-1|=-(x-1)=1-x$.
Consequently, $|x|+|x-1|=-x+1-x=1-2 x$.

**Case II: When $0 \leq x \leq 1$**
In this case, $|x|=x$ and $|x-1|=-(x-1)=1-x$.
$\therefore \quad|x|+|x-1|=x+1-x=1$.

**Case III: When $x>1$**
In this case, $|x|=x$ and $|x-1|=x-1$.
$\therefore \quad|x|+|x-1|=x+(x-1)=(2 x-1)$.

Thus, we may define the above function as

$$
f(x)=\left\{\begin{array}{cl}
1-2 x, & \text { when } x<0 \\
1, & \text { when } 0 \leq x \leq 1 \\
2 x-1, & \text { when } x>1 .
\end{array}\right.
$$

So, we have
- **(i)** a linear function $1-2 x$ when $x<0$;
- **(ii)** a constant function $1$ when $0 \leq x \leq 1$;
- **(iii)** a linear function $2 x-1$ when $x>1$.

![Graph of f(x)=|x|+|x-1|](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-009.jpg?height=311&width=422&top_left_y=143&top_left_x=791)

The corresponding points on these parts of the graph are $(-1,3),(-2,5),(0,1),(1,1),(2,3),(3,5)$, etc.
Joining these points, we obtain the graph as shown.

---

### Example 14:

Draw the graph of the exponential function:
(i) $f(x)=2^{x}$
(ii) $f(x)=\left(\frac{1}{3}\right)^{x}$

#### Solution:

- **(i)** Let $f(x)=2^{x}$.
Some of the points on the graph are
$(0,1),(1,2),(2,4),(3,8),\left(-1, \frac{1}{2}\right),\left(-2, \frac{1}{4}\right),\left(-3, \frac{1}{8}\right), \text { etc. }$

![Graph of f(x)=2^x](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-009.jpg?height=319&width=449&top_left_y=949&top_left_x=115)

And so the graph takes the form, shown in the adjoining figure.
It may be observed here that the given function is strictly increasing. Also, as the value of $x$ decreases, the corresponding value of the function decreases, and therefore, on the left-hand side of the $y$-axis, the curve comes closer and closer to the $x$-axis.

- **(ii)** Let $f(x)=\left(\frac{1}{3}\right)^{x}=\frac{1}{3^{x}} .$
Some of the points on the graph are $(-2,9)$,
$(-1,3),(0,1),\left(1, \frac{1}{3}\right),\left(2, \frac{1}{9}\right), \text { etc. }$
Joining these points, we obtain the graph as
shown. It follows from the graph that the given
function is strictly decreasing.
On the RHS of the $y$-axis, the curve comes
closer and closer to the $x$-axis.

**REMARK** This is the case of the exponential function $a^{x}$, where $0<a<1$.

---

### Example 15:

Draw the graphs of the logarithmic functions

(i) $\log _{a} x$, when $a>1$
(ii) $\log _{a} x$, when $0<a<1$.

#### Solution:

- **(i)** We know that when $a>1$, the function $a^{x}$ is strictly increasing, i.e., different values of $x$ give different values of $a^{x}$. Also, the range of this function is $R$. So, the function $f(x)=a^{x}$ is one-one onto and therefore invertible. Its graph is of the form shown in the adjoining figure. The graph of the function $g(x)=\log _{a} x$ is the reflection of the graph of $f(x)=a^{x}$ in the line $y=x$.
It may be noted that the graph passes through $(1,0)$.

![Graph of log_a(x) when a > 1](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-010.jpg?height=317&width=437&top_left_y=271&top_left_x=766)

- **(ii)** We know that when $0<a<1$, the function $a^{x}$ is strictly decreasing, i.e., different values of $x$ give different values of $a^{x}$. So, the function is one-one. Also, its range is $R$. So, it is onto.
Thus, the function $a^{x}$ is invertible.
Its inverse is the log function reflected by the line $y=x$, as shown. The graph clearly passes through $(1,0)$.

![Graph of log_a(x) when 0 < a < 1](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-010.jpg?height=307&width=425&top_left_y=837&top_left_x=758)

---

### Example 16:

On the same scale draw the graphs of $e^{x}$ and $\log _{e} x$.

#### Solution:

Since $e$ lies between 2 and 3, it follows that $e>1$. So, it is a particular case of $a^{x}$, where $a>1$. The function $e^{x}$ is strictly increasing. Also, its range is $R$. So, the function is one-one onto and therefore invertible.

The graph passes through the point $(0,1)$ and comes closer and closer to the $x$-axis as the values of $x$ decrease. Thus, the graph of $e^{x}$ may be drawn as shown in the figure. Its reflection in the line $y=x$ gives the graph of $\log _{e} x$.

![Graph of e^x and log_e(x)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-010.jpg?height=335&width=376&top_left_y=1558&top_left_x=833)

---

## Graphs of Trigonometric Functions

**1. Graph of a Sine Function**
We know that a **sine function** is periodic with period $2 \pi$. So, we have to sketch the graph in the interval $[0,2 \pi]$ and then we may complete the graph by repeating it over intervals, each of length $2 \pi$. We first draw it in the interval $[0, \pi / 2]$. We know that it is strictly increasing in this interval. Also, we may use the table, given below.

| $x$ | $0^{\circ}$ | $30^{\circ}$ | $45^{\circ}$ | $60^{\circ}$ | $90^{\circ}$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\sin x$ | 0 | $\frac{1}{2}$ | $\frac{1}{\sqrt{2}}=0.707$ | $\frac{\sqrt{3}}{2}=0.87$ | 1 |

Thus, we may draw the graph in the interval $\left[0, \frac{\pi}{2}\right]$.

![Graph of sin(x)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-011.jpg?height=308&width=538&top_left_y=740&top_left_x=392)

Now, we know that $\sin (\pi-x)=\sin x$. So, we may get some other values of the function in the interval $[\pi / 2, \pi]$. Moreover, the function is strictly decreasing in this interval. Thus, we may draw it in the interval $[\pi / 2, \pi]$. Finally, we draw it in $(\pi, 2 \pi)$, using the fact that $\sin (\pi+x)=-\sin x$.

The graph may be completed now by making repetitions over each interval of length $2 \pi$.

**2. Graph of a Cosine Function**
We know that a **cosine function** is periodic with period $2 \pi$. By making use of the table given below, we may first draw it in the interval $[0, \pi / 2]$, keeping in view that it is strictly decreasing in this interval.

| $x$ | $0^{\circ}$ | $\frac{\pi}{6}$ | $\frac{\pi}{4}$ | $\frac{\pi}{3}$ | $\frac{\pi}{2}$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\cos x$ | 1 | $\frac{\sqrt{3}}{2}=0.87$ | $\frac{1}{\sqrt{2}}=0.707$ | $\frac{1}{2}$ | 0 |

Now, $\cos (\pi-x)=-\cos x$, so, we may draw the graph in the interval $[\pi / 2, \pi]$. It is strictly decreasing in this interval also. Further, making use of $\cos (\pi+x)=\cos x$, we may draw the graph from $\pi$ to $2 \pi$, as shown in the figure.

The graph may now be completed by making repetitions over each interval of length $2 \pi$.

![Graph of cos(x)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-012.jpg?height=307&width=569&top_left_y=263&top_left_x=379)

**3. Graph of a Tangent Function**
We know that a **tangent function** is a periodic function with period $\pi$. Therefore, it is enough to draw the graph over an interval of length $\pi$. The complete graph then consists of infinitely many repetitions of the same to the left as well as to the right.

Since $\tan (-x)=-\tan x$, therefore, if ( $x, \tan x$ ) is any point on the graph then $(-x,-\tan x)$ is also a point on the graph. Thus, we can say that the graph of $y=\tan x$ is symmetrical in opposite quadrants.

Some of the values of the function are given below:

| $x$ | $0^{\circ}$ | $\frac{\pi}{6}$ | $\frac{\pi}{4}$ | $\frac{\pi}{3}$ | $\frac{\pi}{2}$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| $\tan x$ | 0 | $\frac{\sqrt{3}}{3}=0.58$ | 1 | $\sqrt{3}=1.73$ | undefined |

| $x$ | $\frac{2 \pi}{3}$ | $\frac{3 \pi}{4}$ | $\frac{5 \pi}{6}$ | $\pi$ |
| :---: | :---: | :---: | :---: | :---: |
| $\tan x$ | $-\sqrt{3}=-1.73$ | -1 | $-\frac{\sqrt{3}}{3}=-0.58$ | 0 |

The graph may thus be drawn as shown below.

![Graph of tan(x)](https://cdn.mathpix.com/cropped/2025_09_25_4c9510ea0d4c9f57f674g-012.jpg?height=323&width=430&top_left_y=1481&top_left_x=447)

Similarly, the graphs of $\operatorname{cosec} x, \sec x$ and $\cot x$ may be drawn.

---

## Continuity

### Continuity at a Point

A real function $f(x)$ is said to be **continuous** at a point $a$ of its domain if $\lim _{x \rightarrow a} f(x)$ exists and equals $f(a)$.

Thus, $f(x)$ is continuous at $x=a$ if

$$
\lim _{x \rightarrow a+} f(x)=\lim _{x \rightarrow a-} f(x)=f(a) .
$$

If $f(x)$ is not continuous at a point, it is said to be **discontinuous** at that point.

**REMARK** $f(x)$ is discontinuous at $x=a$ in each of the following cases:
- (i) $f(a)$ is not defined
- (ii) $\lim _{x \rightarrow a} f(x)$ does not exist
- (iii) $\lim _{x \rightarrow a} f(x) \neq f(a) \quad$ {removable discontinuity}

---

## Solved Examples

### Example 1:

Show that $f(x)=x^{3}$ is continuous at $x=2$.

#### Solution:

We have $f(2)=2^{3}=8$;

$$
\begin{aligned}
\lim _{x \rightarrow 2^{+}} f(x) & =\lim _{h \rightarrow 0}(2+h)^{3}=\lim _{h \rightarrow 0}\left(8+h^{3}+12 h+6 h^{2}\right)=8 ; \\
\lim _{x \rightarrow 2^{-}} f(x) & =\lim _{h \rightarrow 0}(2-h)^{3}=\lim _{h \rightarrow 0}\left(8-h^{3}-12 h+6 h^{2}\right)=8 . \\
\therefore \quad \lim _{x \rightarrow 2+} f(x) & =\lim _{x \rightarrow 2-} f(x)=f(2) .
\end{aligned}
$$

Hence, $f(x)$ is continuous at $x=2$.

---

### Example 2:

Show that $f(x)=[x]$ is not continuous at $x=n$, where $n$ is an integer.

#### Solution:

We have $f(n)=[n]=n$;

$$
\begin{aligned}
\lim _{x \rightarrow n+} f(x) & =\lim _{h \rightarrow 0} f(n+h)=\lim _{h \rightarrow 0}[n+h]=n \quad\{\because \quad[n+h]=n\} ; \\
\lim _{x \rightarrow n^{-}} f(x) & =\lim _{h \rightarrow 0} f(n-h)=\lim _{h \rightarrow 0}[n-h]=(n-1)\{\because \quad[n-h]=(n-1)\} .
\end{aligned}
$$

Thus, $\lim _{x \rightarrow n_{+}} f(x) \neq \lim _{x \rightarrow n_{-}} f(x)$ and therefore, $\lim _{x \rightarrow n} f(x)$ does not exist.
Hence, $f(x)$ is discontinuous at $x=n$.

---

### Example 3:

Show that the function $f(x)= \begin{cases}x, & \text { if } x \text { is an integer; } \\ 0, & \text { if } x \text { is not an integer }\end{cases}$
is discontinuous at each integral value of $x$.

#### Solution:

Let $x=n$, where $n$ is an integer. Then, $f(n)=n$;

$$
\begin{array}{rl}
\lim _{x \rightarrow n+} f(x)=\lim _{h \rightarrow 0} & f(n+h)=0 \\
& {[\because(n+h) \text { is not an integer } \Rightarrow f(n+h)=0] ;}
\end{array}
$$

and $\quad \lim _{x \rightarrow n^{-}} f(x)=\lim _{h \rightarrow 0} f(n-h)=0$
$[\because \quad(n-h)$ is not an integer $\Rightarrow f(n-h)=0]$.
$\therefore \quad \lim _{x \rightarrow n+} f(x)=\lim _{x \rightarrow n_{-}} f(x)=0$.
So, $\quad \lim _{x \rightarrow n} f(x)=0 \neq f(n)$.
Hence, $f(x)$ is discontinuous at $x=n$.

---

### Example 4:

Discuss the continuity of the function $f(x)$ at $x=0$, if
[CBSE 2002]

$$
f(x)= \begin{cases}2 x-1, & x<0 \\ 2 x+1, & x \geq 0\end{cases}
$$

#### Solution:

Clearly, $f(0)=(2 \times 0+1)=1$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0}[2(0+h)+1]=\lim _{h \rightarrow 0}(2 h+1)=1 . \\
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h) \\
& \left.=\lim _{h \rightarrow 0}[2(0-h)-1)\right]=\lim _{h \rightarrow 0}(-2 h-1)=-1 .
\end{aligned}
$$

Thus, $\lim _{x \rightarrow 0+} f(x) \neq \lim _{x \rightarrow 0-} f(x)$ and therefore, $\lim _{x \rightarrow 0} f(x)$ does not exist.
Hence, $f(x)$ is discontinuous at $x=0$.

---

### Example 5:

Show that the function $f(x)=\left\{\begin{array}{rr}3 x-2, & \text { when } x \leq 0 \\ x+1, & \text { when } x>0\end{array}\right.$
is discontinuous at $x=0$.

#### Solution:

We have, $f(0)=(3 \times 0-2)=-2$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0}(h+1)=1 . \\
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h) \\
& =\lim _{h \rightarrow 0}[3(-h)-2]=\lim _{h \rightarrow 0}(-3 h-2)=-2 .
\end{aligned}
$$

$\therefore \lim _{x \rightarrow 0+} f(x) \neq \lim _{x \rightarrow 0-} f(x)$ and therefore, $\lim _{x \rightarrow 0} f(x)$ does not exist.
Hence, $f(x)$ is discontinuous at $x=0$.

---

### Example 6:

Show that the function $f(x)=\left\{\begin{array}{cc}\frac{x}{|x|}, & \text { when } x \neq 0 \\ 1, & \text { when } x=0\end{array}\right.$ is discontinuous at $x=0$.

#### Solution:

It is being given that $f(0)=1$.

$$
\begin{aligned}
& \lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} \frac{h}{|h|}=\lim _{h \rightarrow 0} \frac{h}{h}=1 . \\
& \lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} \frac{-h}{|h|}=\lim _{h \rightarrow 0} \frac{-h}{h}=-1 . \\
\therefore \quad & \lim _{x \rightarrow 0+} f(x) \neq \lim _{x \rightarrow 0-} f(x) .
\end{aligned}
$$

So, $\lim _{x \rightarrow 0} f(x)$ does not exist.
Hence, $f(x)$ is discontinuous at $x=0$.

---

### Example 7:

Examine the continuity of the function

$$
f(x)=\left\{\begin{array}{cl}
\frac{|\sin x|}{x}, & x \neq 0 \\
1, & x=0 \text { at } x=0
\end{array}\right.
\tag{CBSE 2004}
$$

#### Solution:

We have $f(0)=1$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0} \frac{|\sin (0+h)|}{(0+h)}=\lim _{h \rightarrow 0} \frac{|\sin h|}{h}=\lim _{h \rightarrow 0} \frac{\sin h}{h}=1 . \\
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h) \\
& =\lim _{h \rightarrow 0} \frac{|\sin (-h)|}{-h}=\lim _{h \rightarrow 0} \frac{|-\sin h|}{-h}=\lim _{h \rightarrow 0} \frac{\sin h}{-h}=-1 . \\
\therefore \quad \lim _{x \rightarrow 0+} f(x) & \neq \lim _{x \rightarrow 0-} f(x) . \text { So, } \lim _{x \rightarrow 0} f(x) \text { does not exist. }
\end{aligned}
$$

Hence, $f(x)$ is discontinuous at $x=0$.

---

### Example 8:

Show that the function $f(x)=2 x-|x|$ is continuous at $x=0$.
[CBSE 2002]

#### Solution:

We have, $f(0)=(2 \times 0)-|0|=0$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0}(2 h-|h|)=\lim _{h \rightarrow 0}(2 h-h)=\lim _{h \rightarrow 0} h=0 \\
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h)
\end{aligned}
$$

$$
=\lim _{h \rightarrow 0}\{2(-h)-|-h|\}=\lim _{h \rightarrow 0}(-2 h-h)=\lim _{h \rightarrow 0}(-3 h)=0 .
$$

Thus, $\lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=0$ and therefore, $\lim _{x \rightarrow 0} f(x)=0$.
$\therefore \lim _{x \rightarrow 0} f(x)=f(0)=0$.
Hence, $f(x)$ is continuous at $x=0$.

---

### Example 9:

Let $f(x)=\left\{\begin{aligned}|x|+3, & \text { if } x \leq-3 \\ -2 x, & \text { if }-3<x<3 \\ 6 x+2, & \text { if } x \geq 3 .\end{aligned}\right.$
Show that $f(x)$ is continuous at $x=-3$ but discontinuous at $x=3$.

#### Solution:

We have $f(-3)=|-3|+3=(3+3)=6$.

$$
\begin{aligned}
\lim _{x \rightarrow(-3)+} f(x) & =\lim _{h \rightarrow 0} f(-3+h) \\
& =\lim _{h \rightarrow 0}\{-2(-3+h)\}=\lim _{h \rightarrow 0}(6-2 h)=6 . \\
\lim _{x \rightarrow(-3)-} f(x) & =\lim _{h \rightarrow 0} f(-3-h) \\
& =\lim _{h \rightarrow 0}(|-3-h|+3)=\lim _{h \rightarrow 0}\{|-(3+h)|+3\} \\
& =\lim _{h \rightarrow 0}\{(3+h)+3\}=6 . \\
\therefore \quad \lim _{x \rightarrow(-3)+} f(x) & =\lim _{x \rightarrow(-3)_{-}} f(x)=6 . \quad \text { So, } \lim _{x \rightarrow(-3)} f(x)=6 .
\endExample>

Thus, $\lim _{x \rightarrow(-3)} f(x)=f(-3)=6$.
Hence, $f(x)$ is continuous at $x=-3$.

Now, $f(3)=(6 \times 3+2)=20$.

$$
\begin{aligned}
\lim _{x \rightarrow 3-} f(x) & =\lim _{h \rightarrow 0} f(3-h) \\
& =\lim _{h \rightarrow 0}\{-2(3-h)\}=\lim _{h \rightarrow 0}(-6+2 h)=-6 .
\end{aligned}
$$

Thus, $f(3) \neq \lim _{x \rightarrow 3-} f(x)$.
Hence, $f(x)$ is discontinuous at $x=3$.

---

### Example 10:

Find the value of $k$ for which

$$
f(x)=\left\{\begin{array}{r}
k x+5, \text { when } x \leq 2 \\
x-1, \text { when } x>2
\end{array}\right.
$$

is continuous at $x=2$.
[CBSE 2002]

#### Solution:

We have, $f(2)=(k \times 2+5)=(2 k+5)$.

$$
\begin{aligned}
\lim _{x \rightarrow 2+} f(x) & =\lim _{h \rightarrow 0} f(2+h) \\
& =\lim _{h \rightarrow 0}\{(2+h)-1\}=\lim _{h \rightarrow 0}(1+h)=1 . \\
\lim _{x \rightarrow 2-} f(x) & =\lim _{h \rightarrow 0} f(2-h) \\
& =\lim _{h \rightarrow 0}\{k(2-h)+5\}=\lim _{h \rightarrow 0}\{(2 k+5)-k h\}=(2 k+5) .
\end{aligned}
$$

Now, $\lim _{x \rightarrow 2} f(x)$ exists only when $2 k+5=1$, i.e., when $k=-2$.
When $k=-2$, we have $\lim _{x \rightarrow 2} f(x)=f(2)=1$.
Hence, $f(x)$ is continuous at $x=2$ when $k=-2$.

---

### Example 11:

If the following function $f(x)$ is continuous at $x=0$, find the value of $k$:
[CBSE 2008]

$$
f(x)=\left\{\begin{array}{rr}
\frac{1-\cos 2 x}{2 x^{2}}, & x \neq 0 \\
k, & x=0 .
\end{array}\right.
$$

#### Solution:

We have, $f(0)=k$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0} \frac{(1-\cos 2 h)}{2 h^{2}}=\lim _{h \rightarrow 0} \frac{2 \sin ^{2} h}{2 h^{2}}=\lim _{h \rightarrow 0}\left(\frac{\sin h}{h}\right)^{2} \\
& =\left\{\lim _{h \rightarrow 0}\left(\frac{\sin h}{h}\right)\right\}^{2}=(1)^{2}=1 . \\
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h) \\
& =\lim _{h \rightarrow 0}\left\{\frac{1-\cos 2(-h)}{2(-h)^{2}}\right\}=\lim _{h \rightarrow 0} \frac{\{1-\cos (-2 h)\}}{2 h^{2}} \\
& =\lim _{h \rightarrow 0} \frac{(1-\cos 2 h)}{2 h^{2}}=\lim _{h \rightarrow 0} \frac{2 \sin ^{2} h}{2 h^{2}}=\lim _{h \rightarrow 0}\left(\frac{\sin h}{h}\right)^{2} \\
& =\left\{\lim _{h \rightarrow 0} \frac{\sin h}{h}\right\}^{2}=1^{2}=1 .
\end{aligned}
$$

Since $f(x)$ is continuous at $x=0$, we must have

$$
f(0)=\lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x) \Rightarrow k=1 .
$$

---

### Example 12:

For what value of $k$ is the following function continuous at $x=0$?
[CBSE 2014C]

$$
f(x)=\left\{\begin{array}{rr}
\frac{1-\cos 4 x}{8 x^{2}}, & x \neq 0 \\
k, & x=0
\end{array}\right.
$$

#### Solution:

$$
\begin{aligned}
& \lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h) \\
&=\lim _{h \rightarrow 0} \frac{(1-\cos 4 h)}{8 h^{2}}=\lim _{h \rightarrow 0} \frac{2 \sin ^{2} 2 h}{8 h^{2}}=\lim _{h \rightarrow 0}\left(\frac{\sin 2 h}{2 h}\right)^{2} \\
&=1^{2}=1 . \\
& \lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h) \\
&=\lim _{h \rightarrow 0} \frac{\{1-\cos 4(-h)\}}{8(-h)^{2}}=\lim _{h \rightarrow 0} \frac{\{1-\cos (-4 h)\}}{8 h^{2}}=\lim _{h \rightarrow 0} \frac{(1-\cos 4 h)}{8 h^{2}} \\
& \quad[\because \cos (-\theta)=\cos \theta] \\
&= \lim _{h \rightarrow 0} \frac{2 \sin ^{2} 2 h}{8 h^{2}}=\lim _{h \rightarrow 0}\left(\frac{\sin 2 h}{2 h}\right)^{2} \\
&=1^{2}=1 . \\
& \therefore \quad \lim _{x \rightarrow 0} f(x)=1 .
\end{aligned}
$$

For continuity at $x=0$, we must have

$$
f(0)=\lim _{x \rightarrow 0} f(x) \Rightarrow k=1 \quad\left[\because f(0)=k \text { and } \lim _{x \rightarrow 0} f(x)=1\right] .
$$

---

### Example 13:

Given that
[CBSE 2006C, '12C,'13C]

$$
f(x)=\left\{\begin{aligned}
\frac{(1-\cos 4 x)}{x^{2}}, & \text { if } x<0 \\
a, & \text { if } x=0 \\
\frac{\sqrt{x}}{\sqrt{16+\sqrt{x}}-4}, & \text { if } x>0 .
\end{aligned}\right.
$$

If $f(x)$ is continuous at $x=0$, find the value of $a$.

#### Solution:

We have, $f(0)=a$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0}\left\{\frac{\sqrt{h}}{\sqrt{16+\sqrt{h}}-4}\right\} \\
& =\lim _{h \rightarrow 0}\left\{\frac{\sqrt{h}}{\sqrt{16+\sqrt{h}-4}} \times \frac{\sqrt{16+\sqrt{h}}+4}{\sqrt{16+\sqrt{h}}+4}\right\} \\
& =\lim _{h \rightarrow 0} \frac{\sqrt{h} \cdot\{\sqrt{16+\sqrt{h}}+4\}}{\{(16+\sqrt{h})-16\}}=\lim _{h \rightarrow 0} \frac{\sqrt{h} \cdot\{\sqrt{16+\sqrt{h}}+4\}}{\sqrt{h}} \\
& =\lim _{h \rightarrow 0}\{\sqrt{16+\sqrt{h}}+4\}=(4+4)=8 .
\end{aligned}
$$

$$
\begin{aligned}
& \lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h) \\
&=\lim _{h \rightarrow 0} \frac{\{1-\cos 4(-h)\}}{(-h)^{2}}=\lim _{h \rightarrow 0} \frac{\{1-\cos (-4 h)\}}{h^{2}} \\
&=\lim _{h \rightarrow 0} \frac{(1-\cos 4 h)}{h^{2}}=\lim _{h \rightarrow 0} \frac{2 \sin ^{2} 2 h}{h^{2}} \\
&=(2 \times 4) \cdot \lim _{h \rightarrow 0} \frac{\left(\sin ^{2} 2 h\right)}{(2 h)^{2}}=8 \cdot \lim _{h \rightarrow 0}\left(\frac{\sin 2 h}{2 h}\right)^{2} \\
&=\left(8 \times 1^{2}\right)=8 . \\
& \therefore \quad \lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=8 \Rightarrow \lim _{x \rightarrow 0} f(x)=8 .
\end{aligned}
$$

But, by continuity of $f$ at $x=0$, we have

$$
\lim _{x \rightarrow 0} f(x)=f(0) \Rightarrow a=8 \quad\left[\because f(0)=a \text { and } \lim _{x \rightarrow 0} f(x)=8\right] .
$$

Hence, $a=8$.

---

### Example 14:

If the following function $f(x)$ is continuous at $x=0$, find the values of $a, b$ and $c$.
[CBSE 2008]

$$
f(x)=\left\{\begin{array}{r}
\frac{\sin (a+1) x+\sin x}{x}, \text { if } x<0 \\
c, \text { if } x=0 \\
\frac{\sqrt{x+b x^{2}}-\sqrt{x}}{b x^{3 / 2}}, \text { if } x>0 .
\end{array}\right.
$$

#### Solution:

We have, $f(0)=c$.

$$
\begin{aligned}
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h) \\
& =\lim _{h \rightarrow 0} \frac{\sin (a+1)(-h)+\sin (-h)}{(-h)}=\lim _{h \rightarrow 0} \frac{-\{\sin (a+1) h+\sin h\}}{-h} \\
& =\lim _{h \rightarrow 0} \frac{\sin (a+1) h+\sin h}{h}=\lim _{h \rightarrow 0} \frac{2 \sin \left(\frac{a}{2}+1\right) h \cdot \cos \frac{a h}{2}}{h} \\
& =2 \cdot \lim _{h \rightarrow 0}\left\{\frac{\sin \left(\frac{a}{2}+1\right) h}{\left(\frac{a}{2}+1\right) h} \cdot\left(\frac{a}{2}+1\right) \cdot \cos \frac{a h}{2}\right\}
\end{aligned}
$$

$$
\begin{aligned}
=2 & \left(\frac{a}{2}+1\right) \cdot \lim _{h \rightarrow 0} \frac{\sin \left(\frac{a}{2}+1\right) h}{\left(\frac{a}{2}+1\right) h} \cdot \lim _{h \rightarrow 0} \cos \frac{a h}{2} \\
= & (a+2) \times 1 \times 1=(a+2) . \\
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
= & \lim _{h \rightarrow 0}\left\{\frac{\left[\sqrt{h+b h^{2}}-\sqrt{h}\right]}{b h^{3 / 2}} \times \frac{\left[\sqrt{h+b h^{2}}+\sqrt{h}\right]}{\left[\sqrt{h+b h^{2}}+\sqrt{h}\right]}\right\} \\
= & \lim _{h \rightarrow 0} \frac{\left(h+b h^{2}-h\right)}{b h^{3 / 2}\left(\sqrt{h+b h^{2}}+\sqrt{h}\right)}=\lim _{h \rightarrow 0} \frac{b h^{2}}{b h^{2}(\sqrt{1+b h}+1)} \\
= & \lim _{h \rightarrow 0} \frac{1}{(\sqrt{1+b h}+1)}=\frac{1}{2} .
\end{aligned}
$$

Since $f(x)$ is continuous at $x=0$, we have

$$
f(0)=\lim _{x \rightarrow 0-} f(x)=\lim _{x \rightarrow 0+} f(x) \Rightarrow c=\frac{1}{2} \text { and } a+2=\frac{1}{2} .
$$

$\therefore \quad c=\frac{1}{2}$ and $a=\frac{-3}{2}$.

---

### Example 15:

If the function $f(x)=\left\{\begin{aligned} 3 a x+b, & \text { for } x>1 \\ 11, & \text { for } x=1 \\ 5 a x-2 b, & \text { for } x<1\end{aligned}\right.$
is continuous at $x=1$, find the values of $a$ and $b$.
[CBSE 2012C]

#### Solution:

We have, $f(1)=11$.

$$
\begin{aligned}
\lim _{x \rightarrow 1+} f(x) & =\lim _{h \rightarrow 0} f(1+h) \\
& =\lim _{h \rightarrow 0}\{3 a(1+h)+b\}=\lim _{h \rightarrow 0}\{(3 a+b)+3 a h\} \\
& =(3 a+b) \\
\lim _{x \rightarrow 1-} f(x) & =\lim _{h \rightarrow 0} f(1-h) \\
& =\lim _{h \rightarrow 0}\{5 a(1-h)-2 b\}=\lim _{h \rightarrow 0}\{(5 a-2 b)-5 a h\} \\
& =(5 a-2 b)
\end{aligned}
$$

Since $f(x)$ is continuous at $x=1$, we have

$$
\lim _{x \rightarrow 1+} f(x)=\lim _{x \rightarrow 1-} f(x)=f(1) .
$$

$\therefore \quad 3 a+b=5 a-2 b=11 .$

On solving ($3 a+b=11$) and ($5 a-2 b=11$), we get $a=3, b=2$.
Hence, $a=3, b=2$.

---

### Example 16:

For what value of $k$ is the function

$$
f(x)=\left\{\begin{aligned}
k\left(x^{2}-2 x\right), & \text { if } x \leq 0 \\
4 x+1, & \text { if } x>0
\end{aligned}\right.
$$

(i) continuous at $x=0$?
(ii) continuous at $x=1$?
(iii) continuous at $x=-1$?

#### Solution:

**(i)** We have $f(0)=k(0-2 \times 0)=0$.

$$
\begin{aligned}
\lim _{x \rightarrow 0+} f(x) & =\lim _{h \rightarrow 0} f(0+h) \\
& =\lim _{h \rightarrow 0}\{4(0+h)+1\}=\lim _{h \rightarrow 0}(4 h+1)=1 . \\
\lim _{x \rightarrow 0-} f(x) & =\lim _{h \rightarrow 0} f(0-h) \\
& =\lim _{h \rightarrow 0} k\left\{(-h)^{2}-2(-h)\right\}=\lim _{h \rightarrow 0} k\left(h^{2}+2 h\right)=0 .
\end{aligned}
$$

Thus, $\lim _{x \rightarrow 0+} f(x) \neq \lim _{x \rightarrow 0-} f(x)$, and thus $\lim _{x \rightarrow 0} f(x)$ does not exist.
So, $f(x)$ is not continuous at $x=0$ for any value of $k$.

**(ii)** $f(1)=(4 \times 1+1)=5$.

$$
\begin{aligned}
\lim _{x \rightarrow 1+} f(x) & =\lim _{h \rightarrow 0} f(1+h) \\
& =\lim _{h \rightarrow 0}\{4(1+h)+1\}=\lim _{h \rightarrow 0}(5+4 h)=5 \\
\lim _{x \rightarrow 1-} f(x) & =\lim _{h \rightarrow 0} f(1-h) \\
& =\lim _{h \rightarrow 0}\{4(1-h)+1\}=\lim _{h \rightarrow 0}(5-4 h)=5
\end{aligned}
$$

Thus, $\lim _{x \rightarrow 1+} f(x)=\lim _{x \rightarrow 1-} f(x)=\lim _{x \rightarrow 1} f(x)=5$.
Hence, $f(x)$ is continuous at $x=1$ for every real value of $k$.

**(iii)** $f(-1)=k\left\{(-1)^{2}-2 \times(-1)\right\}=3 k$.

$$
\begin{aligned}
\lim _{x \rightarrow(-1)+} f(x) & =\lim _{h \rightarrow 0} f(-1+h) \\
& =\lim _{h \rightarrow 0} k\left\{(-1+h)^{2}-2(-1+h)\right\} \\
& =\lim _{h \rightarrow 0} k\left\{1+h^{2}-2 h+2-2 h\right\} \\
& =\lim _{h \rightarrow 0} k\left(3+h^{2}-4 h\right)=3 k
\end{aligned}
$$

$$
\begin{aligned}
\lim _{x \rightarrow(-1)-} f(x) & =\lim _{h \rightarrow 0} f(-1-h) \\
= & \lim _{h \rightarrow 0} k\left\{(-1-h)^{2}-2(-1-h)\right\}=\lim _{h \rightarrow 0} k\left\{1+h^{2}+2 h+2+2 h\right\} \\
= & \lim _{h \rightarrow 0} k\left(3+4 h+h^{2}\right)=3 k
\end{aligned}
$$

Thus, $\quad \lim _{x \rightarrow(-1)+} f(x)=\lim _{x \rightarrow(-1)-} f(x)=f(-1)=3 k$.
Hence, $f(x)$ is continuous at $x=-1$ for each real value of $k$.

---

### Example 17:

Show that the function $f(x)=\left\{\begin{array}{r}\frac{\sin ^{2} a x}{x^{2}}, \text { when } x \neq 0 \\ 1, \text { when } x=0\end{array}\right.$
is discontinuous at $x=0$.
Redefine the function in such a way that it becomes continuous at $x=a$.

#### Solution:

Clearly, $f(0)=1$.
Also, $\lim _{x \rightarrow 0} f(x)=\lim _{x \rightarrow 0} \frac{\sin ^{2} a x}{x^{2}}=a^{2} \cdot \lim _{a x \rightarrow 0}\left(\frac{\sin a x}{a x}\right)^{2}=a^{2}$.
Since $\quad \lim _{x \rightarrow 0} f(x) \neq f(0), f(x)$ is discontinuous at $x=0$.
However, it becomes continuous if $f(0)=a^{2}$.
So, the desired function is

$$
f(x)=\left\{\begin{array}{r}
\frac{\sin ^{2} a x}{x^{2}}, \text { when } x \neq 0 \\
a^{2}, \text { when } x=0 .
\end{array}\right.
$$

---

### Example 18:

Is the function $f(x)=\frac{(3 x+4 \tan x)}{x}$ continuous at $x=0$? If not, how may the function be defined to make it continuous at this point?

#### Solution:

Since $f(x)$ is not defined at $x=0$, it cannot be continuous at $x=0$.
However, $\lim _{x \rightarrow 0} f(x)=\lim _{x \rightarrow 0}\left(\frac{3 x+4 \tan x}{x}\right)=\lim _{x \rightarrow 0}\left[3+4 \cdot \frac{\sin x}{x} \cdot \frac{1}{\cos x}\right]$

$$
=3+4 \cdot \lim _{x \rightarrow 0}\left\{\frac{\sin x}{x}\right\} \cdot\left\{\lim _{x \rightarrow 0} \frac{1}{\cos x}\right\}=7 .
$$

So, in order to make $f(x)$ continuous at $x=0$, we define it as

$$
f(x)=\left\{\begin{aligned}
\frac{(3 x+4 \tan x)}{x}, & \text { when } x \neq 0 \\
7, & \text { when } x=0 .
\end{aligned}\right.
$$

---

### Example 19:

Show that the function $f(x)=\left\{\begin{array}{r}\left(\frac{e^{1 / x}-1}{e^{1 / x}+1}\right), \text { when } x \neq 0 \\ 0, \text { when } x=0\end{array}\right.$ is discontinuous at $x=0$.

#### Solution:

Clearly, $f(0)=0$.

Now, $\lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0}\left(\frac{e^{1 / h}-1}{e^{1 / h}+1}\right)$

$$
=\lim _{h \rightarrow 0} \frac{e^{1 / h}\left(1-\frac{1}{e^{1 / h}}\right)}{e^{1 / h}\left(1+\frac{1}{e^{1 / h}}\right)}=\lim _{h \rightarrow 0} \frac{\left(1-\frac{1}{e^{1 / h}}\right)}{\left(1+\frac{1}{e^{1 / h}}\right)}=1 .
$$

And, $\quad \lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)=\lim _{h \rightarrow 0}\left(\frac{e^{-1 / h}-1}{e^{-1 / h}+1}\right)$

$$
=\lim _{h \rightarrow 0} \frac{\left(\frac{1}{e^{1 / h}}-1\right)}{\left(\frac{1}{e^{1 / h}}+1\right)}=-1
$$

Thus, $\lim _{x \rightarrow 0+} f(x) \neq \lim _{x \rightarrow 0-} f(x)$, and therefore, $\lim _{x \rightarrow 0} f(x)$ does not exist.
Hence, $f(x)$ is discontinuous at $x=0$.

---
