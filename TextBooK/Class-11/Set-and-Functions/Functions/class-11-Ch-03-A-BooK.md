## Functions

Let $X$ and $Y$ be two nonempty sets. Then, a relation from $X$ to $Y$ is called a **function**, if every element in $X$ has a unique image in $Y$, and we write, $f: X \rightarrow Y$.

Thus, a relation $f$ from $X$ to $Y$ is a function, if $\operatorname{dom}(f)=X$ and no two distinct ordered pairs in $f$ have the same first coordinate.

If $(x, y) \in f$, we write, $f(x)=y$.
Here, $y$ is called the **image** of $x$ under $f$ and $x$ is called the **pre-image** of $y$.
If $f: X \rightarrow Y$ then $\operatorname{dom}(f)=X$ and $\operatorname{range}(f) \subseteq Y$.
Also, $Y$ is called the **co-domain** of $f$.

---

## Image of a Subset

Let $f: X \rightarrow Y$ and let $A \subset X$.
Then, the image of $A$ under $f$ is defined as

$$
f(A)=\{f(x): x \in A\}
$$

Clearly, $f(A) \subseteq Y$.

---

### Example: 1

Let $X=\{1,2,3,4\}$ and $Y=\{1,4,9,16,25\}$.
Let $f=\left\{(x, y): x \in X, y \in Y\right.$ and $\left.y=x^{2}\right\}$.

- **(i)** Show that $f$ is a function from $X$ to $Y$. Find its domain and range.
- **(ii)** Draw a pictorial representation of the above function.
- **(iii)** If $A=\{2,3,4\}$, find $f(A)$.

#### Solution:

**(i)** We have, $f=\left\{(x, y): x \in X, y \in Y\right.$ and $\left.y=x^{2}\right\}$.
Giving different values to $x$ from the set $X$ and getting the corresponding value of $y=x^{2}$, we get

$$
f=\{(1,1),(2,4),(3,9),(4,16)\}
$$

Clearly, every element in $X$ has a unique image in $Y$.
Hence, $f$ is a function from $X$ to $Y$.
$\operatorname{Dom}(f)=\{1,2,3,4\}=X$.
$\operatorname{Range}(f)=\{1,4,9,16\} \subset Y$.
Clearly, $25 \in Y$ does not have its pre-image in $X$.

**(ii)** A pictorial representation of the above mapping $f$ is given below.
![](https://cdn.mathpix.com/cropped/2025_09_25_d151f9018eef695a9ce3g-02.jpg?height=307&width=619&top_left_y=169&top_left_x=354)

**(iii)** Now, let $A=\{2,3,4\}$. Then,
$$
\begin{array}{ll}
& f(2)=2^{2}=4, f(3)=3^{2}=9 \text { and } f(4)=4^{2}=16 . \\
\therefore \quad & f(A)=\{f(x): x \in A\}=\{4,9,16\} .
\end{array}
$$

---

## Relation as a Particular Case of a Function

A relation $f$ from $X$ to $Y$ is a function if $\operatorname{dom}(f)=X$ and no two distinct ordered pairs in $f$ have the same first coordinate.

If $(x, y) \in f$, we write, $f(x)=y$.

---

### Example: 2

Let $X=\{2,3,4,5\}$ and $Y=\{7,9,11,13,15,17\}$.
Define a relation from $X$ to $Y$ by:

$$
f=\{(x, y): x \in X, y \in Y \text { and } y=2 x+3\} .
$$

- **(i)** Write $f$ in roster form.
- **(ii)** Find $\operatorname{dom}(f)$ and $\operatorname{range}(f)$.
- **(iii)** Show that $f$ is a function from $X$ to $Y$.

#### Solution:

Here $X=\{2,3,4,5\}$ and $Y=2 x+3$.
Now, $x=2 \Rightarrow y=(2 \times 2+3)=7$,
$$
\begin{aligned}
& x=3 \Rightarrow y=(2 \times 3+3)=9, \\
& x=4 \Rightarrow y=(2 \times 4+3)=11, \\
& x=5 \Rightarrow y=(2 \times 5+3)=13 .
\end{aligned}
$$

**(i)** $\therefore f=\{(2,7),(3,9),(4,11),(5,13)\}$.

**(ii)** Clearly, $\operatorname{dom}(f)=\{2,3,4,5\}$ and $\operatorname{range}(f)=\{7,9,11,13\} \subset Y$.

**(iii)** It is clear that no two distinct ordered pairs in $f$ have the same first coordinate.
$\therefore f$ is a function from $X$ to $Y$.

---

### Example: 3

Which of the following relations are functions? Give reasons. In case of a function, find its domain and range.
- **(i)** $f=\{(1,3),(1,5),(2,3),(2,5)\}$
- **(ii)** $g=\{(2,1),(5,1),(8,1),(11,1)\}$
- **(iii)** $h=\{(2,1),(4,2),(6,3),(8,4),(10,5),(12,6)\}$

#### Solution:

**(i)** $f=\{(1,3),(1,5),(2,3),(2,5)\}$.
Here, one element, namely 1 has two images 3 and 5 under $f$.
$\therefore f$ is **not a function**.

**(ii)** $g=\{(2,1),(5,1),(8,1),(11,1)\}$.
Clearly, no two distinct ordered pairs in $g$ have the same first coordinate. So, $g$ is a **function**.
$\therefore \operatorname{dom}(g)=\{2,5,8,11\}$ and $\operatorname{range}(g)=\{1\}$.

**(iii)** $h=\{(2,1),(4,2),(6,3),(8,4),(10,5),(12,6)\}$.
Clearly, no two distinct ordered pairs in $h$ have the same first coordinate. So, $h$ is a **function**.
$\therefore \operatorname{dom}(h)=\{2,4,6,8,10,12\}$ and $\operatorname{range}(h)=\{1,2,3,4,5,6\}$.

---

### Example: 4

Let $A=\{-2,-1,0,1,2\}$ and $f: A \rightarrow Z: f(x)=x^{2}-2 x-3$.
Find **(i)** $\operatorname{range}(f)$ **(ii)** pre-images of $6, -3$ and $5$.

#### Solution:

We have
$$
\begin{array}{ll}
& f(-2)=(-2)^{2}-2 \times(-2)-3=(4+4-3)=5 ; \\
& f(-1)=(-1)^{2}-2 \times(-1)-3=0 ; \\
& f(0)=-3 ; \\
& f(1)=(1-2-3)=-4 \text { and } f(2)=\left(2^{2}-2 \times 2-3\right)=-3 . \\
\therefore \quad & f=\{(-2,5),(-1,0),(0,-3),(1,-4),(2,-3)\} .
\end{array}
$$

**(i)** $\operatorname{Range}(f)=\{5,0,-3,-4\}$.

**(ii)** $f(x)=6 \Rightarrow x^{2}-2 x-3=6$
$$
\Rightarrow x^{2}-2 x-9=0 \Rightarrow x=\frac{2 \pm \sqrt{4+36}}{2}=(1 \pm \sqrt{10}) \notin A .
$$
$\therefore 6$ has **no pre-image** in $A$.

$f(x)=-3 \Rightarrow x^{2}-2 x-3=-3$
$$
\Rightarrow x^{2}-2 x=0 \Rightarrow x(x-2)=0 \Rightarrow x=0 \text { or } x=2 .
$$
Clearly, $0,2 \in A$.
So, the pre-images of -3 are **0 and 2**.

$f(x)=5 \Rightarrow x^{2}-2 x-3=5$
$$
\begin{aligned}
& \Rightarrow x^{2}-2 x-8=0 \Rightarrow x^{2}-4 x+2 x-8=0 \\
& \Rightarrow x(x-4)+2(x-4)=0 \Rightarrow(x-4)(x+2)=0 \\
& \Rightarrow x=-2 \text { or } x=4
\end{aligned}
$$
Now, $-2 \in A$ but $4 \notin A$.
So, the pre-image of 5 is **-2**.

---

## Equal Functions

Two functions $f$ and $g$ are said to be **equal** if
- **(i)** $\operatorname{dom}(f)=\operatorname{dom}(g)$
- **(ii)** co-domain of $f = \text{co-domain of } g$
- **(iii)** $f(x)=g(x)$ for every $x$ in their common domain.

---

### Example: 5

Let $A=\{1,2\}$ and $B=\{3,6\}$ and $f$ and $g$ be functions from $A$ to $B$, defined by $f(x)=3 x$ and $g(x)=x^{2}+2$. Show that $f=g$.

#### Solution:

Clearly, we have
$$
\operatorname{dom}(f)=\operatorname{dom}(g)=\{1,2\} .
$$
Co-domain of $f = \text{co-domain of } g=\{3,6\}$.
Also, $f(1)=(3 \times 1)=3$, $f(2)=(3 \times 2)=6$;
$g(1)=\left(1^{2}+2\right)=3$, $g(2)=\left(2^{2}+2\right)=6$.
$\therefore f(1)=g(1)$ and $f(2)=g(2)$.
Thus, $f(x)=g(x)$ for all $x \in A$.
Hence, $f=g$.

---

### Example: 6

Let $f: Z \rightarrow Z: f(x)=x^{2}$ and $g: Z \rightarrow Z: g(x)=|x|^{2}$ for all $x \in Z$. Show that $f=g$.

#### Solution:

We have
$$
\operatorname{dom}(f)=\operatorname{dom}(g)=Z
$$
and co-domain of $f = \text{co-domain of } g=Z$.
Also, for all $x \in Z$, we have
$$
\begin{aligned}
& f(x)=x^{2} \text { and } g(x)=|x|^{2}=x^{2} . \\
\therefore & f(x)=g(x) \text { for all } x \in Z .
\end{aligned}
$$
Hence, $f=g$.

---

### Example: 7

Let $f: R \rightarrow R: f(x)=x+2$ and $g: R-\{2\} \rightarrow R: g(x)=\frac{x^{2}-4}{x-2}$.
Show that $f \neq g$. Re-define $f$ and $g$ such that $f=g$.

#### Solution:

We have, $\operatorname{dom}(f)=R$ and $\operatorname{dom}(g)=R-\{2\}$.
Since $\operatorname{dom}(f) \neq \operatorname{dom}(g)$, so we have $f \neq g$.
For every real number $x \neq 2$, we have
$$
g(x)=\frac{x^{2}-4}{x-2}=\frac{(x-2)(x+2)}{(x-2)}=(x+2) \quad[\because(x-2) \neq 0]
$$
Thus, $f(x)=g(x)$ for all $x \in R-\{2\}$.
$\therefore f=g$ only when, they are re-defined as under:
$$
f: R-\{2\} \rightarrow R: f(x)=x+2 \text { and } g: R-\{2\} \rightarrow R: g(x)=\frac{x^{2}-4}{x-2}
$$

---

### Example: 8

Let $f=\{(-1,-3),(0,-1),(1,1),(2,3)\}$ be a function, described by the formula, $f(x)=\alpha x+\beta$. Then, find the values of $\alpha$ and $\beta$. Also, find the formula.

#### Solution:

Here $f(x)=\alpha x+\beta$.
Also, $f(-1)=-3, f(0)=-1, f(1)=1$ and $f(2)=3$.

Putting $x=-1$ and $f(-1)=-3$ in (i), we get
$$
-\alpha+\beta=-3 \Rightarrow \alpha-\beta=3 \tag{ii}
$$
Putting $x=0$ and $f(0)=-1$ in (i), we get
$$
\alpha \times 0+\beta=-1 \Rightarrow \beta=-1 . \tag{iii}
$$
Putting $\beta=-1$ from (iii) in (ii), we get $\alpha=2$.
$\therefore \alpha=2$ and $\beta=-1$.
Hence, $f(x)=2 x-1$ is the required formula.

---

### Example: 9

Let $f: R \rightarrow R: f(x)=x^{2}+3$.
Find the pre-images of each of the following under $f$:
- **(i)** 19
- **(ii)** 28
- **(iii)** 2

#### Solution:

Given: $f(x)=x^{2}+3$.

**(i)** Let $x$ be the pre-image of 19. Then,
$$
f(x)=19 \Rightarrow x^{2}+3=19 \Rightarrow x^{2}=16 \Rightarrow x= \pm 4
$$
$\therefore 4$ and -4 are the pre-images of 19.

**(ii)** Let $x$ be the pre-image of 28. Then,
$$
f(x)=28 \Rightarrow x^{2}+3=28 \Rightarrow x^{2}=25 \Rightarrow x= \pm 5 .
$$
$\therefore 5$ and -5 are the pre-images of 28.

**(iii)** Let $x$ be the pre-image of 2. Then,
$$
f(x)=2 \Rightarrow x^{2}+3=2 \Rightarrow x^{2}=-1
$$
But, no real value of $x$ satisfies the equation, $x^{2}=-1$.
$\therefore 2$ does not have any pre-image under $f$.

---

## Inverse of a Function

Let $f: X \rightarrow Y$ and let $y \in Y$.
Then, we define, $f^{-1}(y)=\{x \in X: f(x)=y\}= \text{set of pre-images of } y$.
$f^{-1}$ is called the **inverse** of $f$.

> **Remark**
> In above example 9, we have
> - **(i)** $f^{-1}\{19\}=\{-4,4\}$
> - **(ii)** $f^{-1}\{28\}=\{-5,5\}$
> - **(iii)** $f^{-1}\{2\}=\phi$.

---

### Example: 10

Let $f: R \rightarrow R: f(x)=x^{2}+1$.
Find **(i)** $f^{-1}\{-4\}$, **(ii)** $f^{-1}\{10\}$, **(iii)** $f^{-1}\{5,17\}$.

#### Solution:

It is given that $f(x)=x^{2}+1$.

**(i)** Let $f^{-1}(-4)=x$. Then,
$$
f(x)=-4 \Rightarrow x^{2}+1=-4 \Rightarrow x^{2}=-5
$$
But, there is no real value of $x$ whose square is -5.
$$
\therefore f^{-1}\{-4\}=\phi .
$$

**(ii)** Let $f^{-1}(10)=x$. Then,
$$
f(x)=10 \Rightarrow x^{2}+1=10 \Rightarrow x^{2}=9 \Rightarrow x= \pm 3 .
$$
$$
\therefore f^{-1}\{10\}=\{-3,3\} .
$$

**(iii)** Let $f^{-1}(5)=x$. Then,
$$
f(x)=5 \Rightarrow x^{2}+1=5 \Rightarrow x^{2}=4 \Rightarrow x= \pm 2 .
$$
$$
\therefore f^{-1}\{5\}=\{-2,2\} .
$$
Let $f^{-1}(17)=x$. Then,
$$
f(x)=17 \Rightarrow x^{2}+1=17 \Rightarrow x^{2}=16 \Rightarrow x= \pm 4 .
$$
$$
\therefore f^{-1}\{17\}=\{-4,4\} .
$$
Hence, $f^{-1}\{5,17\}=\{-2,2,-4,4\}$.

---

### Example: 11

Let $f: R \rightarrow R$, defined by
$$
f(x)=\left\{\begin{array}{l}
1, \text { if } x \in Q \\
-1, \text { if } x \notin Q .
\end{array}\right.
$$
Find **(i)** $f\left(\frac{1}{2}\right)$, **(ii)** $f(0.34)$, **(iii)** $f(\sqrt{2})$, **(iv)** $f(\pi)$, **(v)** $\operatorname{range}(f)$, **(vi)** $f^{-1}\{1\}$, **(vii)** $f^{-1}\{-1\}$

#### Solution:

Since each one of $\frac{1}{2}$ and 0.34 is rational, we have

**(i)** $f\left(\frac{1}{2}\right)=1$ and **(ii)** $f(0.34)=1$.

Since each one of $\sqrt{2}$ and $\pi$ is irrational, we have

**(iii)** $f(\sqrt{2})=-1$ and **(iv)** $f(\pi)=-1$.

**(v)** $\operatorname{range}(f)=\{f(x): x \in R\}$
$$
=\{f(x): x \in Q\} \cup\{f(x): x \in R-Q\}=\{1,-1\} .
$$
**(vi)** $f^{-1}\{1\}=\{x: f(x)=1\}=Q$.

**(vii)** $f^{-1}\{-1\}=\{x: f(x)=-1\}=(R-Q)$.

---

### Example: 12

Let $f: R \rightarrow R$, defined by
$$
f(x)= \begin{cases}3 x-2, & x<0 \\ 1, & x=0 \\ 4 x+1, & x>0\end{cases}
$$
Find **(i)** $f(2)$, **(ii)** $f(-2)$, **(iii)** $f(0)$, **(iv)** $f(3.5)$.

#### Solution:

Clearly, we have

**(i)** $f(2)=(4 \times 2+1)=9 \quad [\because 2>0]$.

**(ii)** $f(-2)=\{3 \times(-2)-2\}=-8 \quad [\because-2<0]$.

**(iii)** $f(0)=1$.

**(iv)** $f(3.5)=(4 \times 3.5+1)=15 \quad [\because 3.5>0]$.

---

### Example: 13

Consider the relation
$$
f(x)=\left\{\begin{array}{l}
x^{2}, 0 \leq x \leq 2 \\
3 x, 2 \leq x \leq 10
\end{array}\right.
$$
Show that $f$ is **not a function**.

#### Solution:

We have, $\operatorname{dom}(f)=[0,10] \subset R$.
Now, $f(2)=2^{2}=4$ and also, $f(2)=(3 \times 2)=6$.
As such, a single element, namely 2 has two distinct images, namely 4 and 6.
$\therefore f$ is not a function.

---

### Example: 14

Consider the relation
$$
g(x)=\left\{\begin{array}{l}
x^{2}, 0 \leq x \leq 3 \\
3 x, 3 \leq x \leq 10
\end{array}\right.
$$
Show that $g$ is a **function**.

#### Solution:

We have, $\operatorname{dom}(g)=[0,10] \subset R$.
It is easy to verify that every element in $[0,10]$ is associated with a unique real number under $g$.
In particular $g(3)=3^{2}=9$ and also $g(3)=3 \times 3=9$, i.e., 3 has a unique image, namely 9.
$\therefore g$ is a function from $[0,10]$ into $R$.

---

