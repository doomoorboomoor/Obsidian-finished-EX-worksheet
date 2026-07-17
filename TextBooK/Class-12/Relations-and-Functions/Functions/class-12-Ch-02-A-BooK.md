## 2. Functions

**FUNCTION** Let $A$ and $B$ be two nonempty sets. Then, a rule $f$ which associates to each element $x \in A$, a unique element, denoted by $f(x)$ of $B$, is called a function from $A$ to $B$ and we write,

$$
f: A \in B
$$

$f(x)$ is called the **image** of $x$, while $x$ is called the **pre-image** of $f(x)$.

---

## Domain, Codomain, and Range of a Function

Let $f: A \rightarrow B$. Then, $A$ is called the **domain** of $f$ and $B$ is called the **codomain** of $f$. And, $f(A)=\{f(x): x \in A\}$ is called the **range** of $f$.

**Example 1** Let $A=\{1,2,3,4\}$ and $B=\{1,4,9,16,25\}$.

![](https://cdn.mathpix.com/cropped/2025_09_25_c2030f1a984df749fceag-025.jpg?height=294&width=443&top_left_y=907&top_left_x=440)

Consider the rule $f: A \rightarrow B: f(x)=x^{2} \forall x \in A$.
Then, each element in $A$ has its unique image in $B$.
So, $f$ is a function from $A$ to $B$.

$$
f(1)=1^{2}=1, f(2)=2^{2}=4, f(3)=3^{2}=9, f(4)=4^{2}=16 .
$$

$\operatorname{Dom}(f)=\{1,2,3,4\}=A$, **codomain**$(f)=\{1,4,9,16,25\}=B$
and **range**$(f)=\{1,4,9,16\}$.
Clearly, $25 \in B$ does not have its pre-image in $A$.

**Example 2** Let $N$ be the set of all natural numbers.
Let $f: N \rightarrow N: f(x)=2 x \quad \forall x \in N$.
Then, every element in $N$ has its unique image in $N$.
So, $f$ is a function from $N$ to $N$.
Clearly, $f(1)=2, f(2)=4, f(3)=6 \ldots$, and so on.
$\operatorname{Dom}(f)=N$, **codomain**$(f)=N$,
**range**$(f)=\{2,4,6,8,10, \ldots\}$.

---

## Various Types of Functions

### Many-One Function
A function $f: A \rightarrow B$ is said to be **many-one** if two or more than two elements in $A$ have the same image in $B$.

**Example** Let $A=\{-1,1,2,3\}$ and $B=\{1,4,9\}$.
Let $f: A \rightarrow B: f(x)=x^{2} \forall x \in A$.
Then, each element in $A$ has a unique image under $f$ in $B$.
$\therefore f$ is a function from $A$ to $B$ such that

$$
\begin{aligned}
& f(-1)=(-1)^{2}=1 ; f(1)=1^{2}=1 \\
& f(2)=2^{2}=4 \text { and } f(3)=3^{2}=9
\end{aligned}
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_c2030f1a984df749fceag-026.jpg?height=288&width=441&top_left_y=320&top_left_x=772)

Clearly, two different elements, namely -1 and 1, have the same image $1 \in B$.
Hence, $f$ is many-one.

---

### One-One (or Injective) Function

A function $f: A \rightarrow B$ is said to be **one-one** if distinct elements in $A$ have distinct images in $B$.

> $f$ is one-one when $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow x_{1}=x_{2}$.

**Example** Let $N$ be the set of all natural numbers.
Let $f: N \rightarrow N: f(x)=2 x \quad \forall x \in N$.
Then, $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow 2 x_{1}=2 x_{2}$

$$
\Rightarrow x_{1}=x_{2} .
$$

$\therefore f$ is one-one.

---

### Onto (or Surjective) Function

A function $f: A \rightarrow B$ is said to be **onto** if every element in $B$ has at least one pre-image in $A$.

Thus, if $f$ is onto then for each $y \in B \exists$ at least one element $x \in A$ such that $y=f(x)$.

$$
\text { Also, } f \text { is onto } \Leftrightarrow \text { range }(f)=B .
$$

**Example** Let $N$ be the set of all natural numbers and let $E$ be the set of all even natural numbers.
Let $f: N \rightarrow E: f(x)=2 x \quad \forall x \in N$.
Then, $y=2 x \Rightarrow x=\frac{1}{2} y$.

Thus, for each $y \in E$ there exists $\frac{1}{2} y \in N$ such that

$$
f\left(\frac{1}{2} y\right)=\left(2 \times \frac{1}{2} y\right)=y .
$$

$\therefore f$ is onto.

---

### Into Function
A function $f: A \rightarrow B$ is said to be **into** if there exists even a single element in $B$ having no pre-image in $A$.

> Clearly, $f$ is into $\Leftrightarrow \text{range}(f) \subset B$.

**Example** Let $A=\{2,3,5,7\}$ and $B=\{0,1,3,5,7\}$.
Let $f: A \rightarrow B: f(x)=(x-2)$. Then,

$$
\begin{aligned}
& f(2)=(2-2)=0, f(3)=(3-2)=1, f(5)=(5-2)=3 \text { and } \\
& f(7)=(7-2)=5 .
\end{aligned}
$$

Thus, every element in $A$ has a unique image in $B$.
Now, $\exists 7 \in B$ having no pre-image in $A$.
$\therefore f$ is into.
Note that $\text{range}(f)=\{0,1,3,5\} \subset B$.

---

### Bijective Function

A one-one onto function is said to be **bijective** or a one-to-one correspondence.

---

### Constant Function
A function $f: A \rightarrow B$ is called a **constant function** if every element of $A$ has the same image in $B$.

**Example** Let $A=\{1,2,3\}$ and $B=\{5,7,9\}$.
Let $f: A \rightarrow B: f(x)=5$ for all $x \in A$.
Clearly, every element in $A$ has the same image.
So, $f$ is a constant function.

**Remark:** The range of a constant function is a singleton set.

---

### Identity Function
The function $I_{A}: A \rightarrow A: I_{A}(x)=x \forall x \in A$ is called an **identity function** on $A$.

**Domain**$(I_{A})=A$ and **Range**$(I_{A})=A$.

---

### Equal Functions
Two functions $f$ and $g$ having the same domain $D$ are said to be **equal** if $f(x)=g(x) \forall x \in D$.

---

## Solved Examples

### Example 1:

Let $f: N \rightarrow N: f(x)=2 x$ for all $x \in N$.
Show that $f$ is one-one and into.

#### Solution:

We have

$$
f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow 2 x_{1}=2 x_{2} \Rightarrow x_{1}=x_{2} .
$$

$\therefore f$ is one-one.

Let $y=2 x$. Then, $x=\frac{y}{2}$.
If we put $y=3$ then $x=\frac{3}{2} \notin N$.
Thus, $3 \in N$ has no pre-image in $N$.
$\therefore f$ is into.

Hence, $f$ is one-one and into.

---

### Example 2:

Show that the function $f: R \rightarrow R: f(x)=x^{2}$ is neither one-one nor onto.

#### Solution:

We have $f(-1)=(-1)^{2}=1$ and $f(1)=1^{2}=1$.
Thus, two different elements in $R$ have the same image.
$\therefore f$ is not one-one.

If we consider -1 in the codomain $R$, then it is clear that there is no element in $R$ whose image is -1 .
$\therefore f$ is not onto.

Hence, $f$ is neither one-one nor onto.

---

### Example 3:

Show that the function $f: R \rightarrow R: f(x)=|x|$ is neither one-one nor onto.

#### Solution:

We have $f(-1)=|-1|=1$ and $f(1)=|1|=1$.
Thus, two different elements in $R$ have the same image.
$\therefore f$ is not one-one.

If we consider -1 in the codomain $R$, then it is clear that there is no real number $x$ whose modulus is -1 .
Thus, $-1 \in R$ has no pre-image in $R$.
$\therefore f$ is not onto.

Hence, $f$ is neither one-one nor onto.

---

### Example 4:

For any real number $x$, we define
$[x]=$ **greatest integer less than or equal to $x$**.

Prove that the **greatest integer function** $f: R \rightarrow R: f(x)=[x]$ is neither one-one nor onto.

#### Solution:

Clearly, $[1.2]=1$ and $[1.3]=1$.
$\therefore f(1.2)=1$ and $f(1.3)=1$.
Thus, two different real numbers have the same image.
$\therefore f$ is not one-one.

Clearly, there is no real number $x$ such that

$$
f(x)=[x]=1.1 .
$$

So, $f$ is not onto.
Hence, $f$ is neither one-one nor onto.

---

### Example 5:

Let $R_{0}$ be the set of all nonzero real numbers.
Show that $f: R_{0} \rightarrow R_{0}: f(x)=\frac{1}{x}$ is a one-one onto function.

#### Solution:

We have

$$
f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow \frac{1}{x_{1}}=\frac{1}{x_{2}} \Rightarrow x_{1}=x_{2}
$$

$\therefore f$ is one-one.

Again, $y=\frac{1}{x} \Rightarrow x=\frac{1}{y}$.
Now, if $y$ is a nonzero real number, then $x=\left(\frac{1}{y}\right)$ is a nonzero real number such that $f\left(\frac{1}{y}\right)=y$.
Thus, each $y$ in $R_{0}$ has its pre-image in $R_{0}$.
So, $f$ is onto.

Hence, $f$ is one-one onto.

---

### Example 6:

Show that the function $f: R \rightarrow R: f(x)=x^{3}$ is one-one and onto.

#### Solution:

We have

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow x_{1}^{3}=x_{2}^{3} \\
& \Rightarrow\left(x_{1}^{3}-x_{2}^{3}\right)=0 \\
& \Rightarrow\left(x_{1}-x_{2}\right)\left(x_{1}^{2}+x_{1} x_{2}+x_{2}^{2}\right)=0 \\
& \Rightarrow\left(x_{1}-x_{2}\right)\left[\left(x_{1}+\frac{x_{2}}{2}\right)^{2}+\frac{3}{4} x_{2}^{2}\right]=0 \\
& \Rightarrow\left(x_{1}-x_{2}\right)=0 \quad\left[\because\left(x_{1}+\frac{x_{2}}{2}\right)^{2}+\frac{3}{4} x_{2}^{2} \neq 0\right] \\
& \Rightarrow x_{1}=x_{2}
\end{aligned}
$$

$\therefore f$ is one-one.

Let $y \in R$ and let $y=x^{3}$. Then, $x=y^{1 / 3} \in R$.
Thus, for each $y$ in the codomain $R$ there exists $y^{1 / 3}$ in $R$ such that $f\left(y^{1 / 3}\right)=\left(y^{1 / 3}\right)^{3}=y$.
$\therefore f$ is onto.

Hence, $f$ is one-one onto.

---

### Example 7:

Show that the function $f: R \rightarrow R: f(x)=3-4 x$ is one-one onto and hence bijective.

#### Solution:

We have $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow 3-4 x_{1}=3-4 x_{2}$

$$
\Rightarrow-4 x_{1}=-4 x_{2} \Rightarrow x_{1}=x_{2} .
$$

$\therefore f$ is one-one.

Now, let $y=3-4 x$. Then, $x=\frac{(3-y)}{4}$.
Thus, for each $y \in R$ (codomain of $f$), there exists $x=\frac{(3-y)}{4} \in R$ such that $f(x)=f\left(\frac{3-y}{4}\right)=\left\{3-4 \cdot \frac{(3-y)}{4}\right\}=3-(3-y)=y$.

This shows that every element in codomain of $f$ has its pre-image in $\operatorname{dom}(f)$.
$\therefore f$ is onto.

Hence, the given function is bijective.

---

### Example 8:

Show that the function $f: N \rightarrow N$, defined by

$$
f(x)= \begin{cases}x+1, & \text { if } x \text { is odd } \\ x-1, & \text { if } x \text { is even }\end{cases}
$$

is one-one and onto.
[CBSE 2012]

#### Solution:

Suppose $f\left(x_{1}\right)=f\left(x_{2}\right)$.

**Case 1** When $x_{1}$ is odd and $x_{2}$ is even
In this case, $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow x_{1}+1=x_{2}-1$

$$
\Rightarrow x_{2}-x_{1}=2 .
$$

This is a contradiction, since the difference between an odd integer and an even integer can never be 2.
Thus, in this case, $f\left(x_{1}\right) \neq f\left(x_{2}\right)$.
Similarly, when $x_{1}$ is even and $x_{2}$ is odd, then $f\left(x_{1}\right) \neq f\left(x_{2}\right)$.

**Case 2** When $x_{1}$ and $x_{2}$ are both odd
In this case, $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow x_{1}+1=x_{2}+1$

$$
\Rightarrow x_{1}=x_{2} .
$$

$\therefore f$ is one-one.

**Case 3** When $x_{1}$ and $x_{2}$ are both even
In this case, $f\left(x_{1}\right)=f\left(x_{2}\right) \Rightarrow x_{1}-1=x_{2}-1$

$$
\Rightarrow x_{1}=x_{2} .
$$

$\therefore f$ is one-one.

In order to show that $f$ is onto, let $y \in N$ (the codomain).

**Case 1** When $y$ is odd
In this case, $(y+1)$ is even.
$\therefore f(y+1)=(y+1)-1=y$.

**Case 2** When $y$ is even
In this case, $(y-1)$ is odd.
$\therefore f(y-1)=y-1+1=y$.

Thus, each $y \in N$ (codomain of $f$) has its pre-image in $\operatorname{dom}(f)$.
$\therefore f$ is onto.

Hence, $f$ is one-one onto.

---

### Example 9:

Show that $f: N \rightarrow N$, defined by

$$
f(n)=\left\{\begin{array}{l}
\frac{n+1}{2}, \text { if } n \text { is odd } \\
\frac{n}{2}, \text { if } n \text { is even }
\end{array}\right.
$$

is a many-one onto function.
[CBSE 2012C]

#### Solution:

We have

$$
f(1)=\frac{(1+1)}{2}=\frac{2}{2}=1 \quad \text { and } \quad f(2)=\frac{2}{2}=1 .
$$

Thus, $f(1)=f(2)$ while $1 \neq 2$.
$\therefore f$ is many-one.

In order to show that $f$ is onto, consider an arbitrary element $n \in N$.

If $n$ is odd then $(2 n-1)$ is odd, and

$$
f(2 n-1)=\frac{(2 n-1+1)}{2}=\frac{2 n}{2}=n .
$$

If $n$ is even then $2 n$ is even and

$$
f(2 n)=\frac{2 n}{2}=n .
$$

Thus, for each $n \in N$ (whether even or odd) there exists its pre-image in $N$.
$\therefore f$ is onto.

Hence, $f$ is many-one onto.

---

### Example 10:

Show that the signum function $f: R \rightarrow R$, defined by

$$
f(x)=\left\{\begin{rll}
1, & \text { if } & x>0 \\
0, & \text { if } & x=0 \\
-1, & \text { if } & x<0
\end{array}\right.
$$

is neither one-one nor onto.

Clearly, $f(2)=1$ and $f(3)=1$.
Thus, $f(2)=f(3)$ while $2 \neq 3$.
$\therefore f$ is not one-one.

$\operatorname{Range}(f)=\{1,0,-1\} \subset R$.
So, $f$ is into.

Hence, $f$ is neither one-one nor onto.

---

### Example 11:

Let $A=R-\{3\}$ and $B=R-\{1\}$.
Let $f: A \rightarrow B: f(x)=\frac{x-2}{x-3}$ for all values of $x \in A$.
Show that $f$ is one-one and onto.
[CBSE 2012]

#### Solution:

$f$ is one-one, since

$$
\begin{aligned}
f\left(x_{1}\right)=f\left(x_{2}\right) & \Rightarrow \frac{x_{1}-2}{x_{1}-3}=\frac{x_{2}-2}{x_{2}-3} \\
& \Rightarrow\left(x_{1}-2\right)\left(x_{2}-3\right)=\left(x_{1}-3\right)\left(x_{2}-2\right) \\
& \Rightarrow x_{1} x_{2}-3 x_{1}-2 x_{2}+6=x_{1} x_{2}-2 x_{1}-3 x_{2}+6 \\
& \Rightarrow x_{1}=x_{2}
\ends_of_pymatgen_code
Let $y \in B$ such that $y=\frac{x-2}{x-3}$.
Then, $(x-3) y=(x-2) \Rightarrow x=\frac{(3 y-2)}{(y-1)}$.
Clearly, $x$ is defined when $y \neq 1$.
Also, $x=3$ will give us $1=0$, which is false.
$\therefore x \neq 3$.

And, $f(x)=\frac{\left(\frac{3 y-2}{y-1}-2\right)}{\left(\frac{3 y-2}{y-1}-3\right)}=y$.
Thus, for each $y \in B$, there exists $x \in A$ such that $f(x)=y$.
$\therefore f$ is onto.

Hence, $f$ is one-one onto.

---

### Example 12:

Let $A$ and $B$ be two nonempty sets. Show that the function $f:(A \times B) \rightarrow(B \times A): f(a, b)=(b, a)$ is a bijective function.

#### Solution:

$f$ is one-one, since

$$
\begin{aligned}
f\left(a_{1}, b_{1}\right)=f\left(a_{2}, b_{2}\right) & \Rightarrow\left(b_{1}, a_{1}\right)=\left(b_{2}, a_{2}\right) \\
& \Rightarrow a_{1}=a_{2} \textand $b_{1}=b_{2} \\
& \Rightarrow\left(a_{1}, b_{1}\right)=\left(a_{2}, b_{2}\right)
\end{aligned}
$$

In order to show that $f$ is onto, let $(b, a)$ be an arbitrary element of $(B \times A)$.
Then, $(b, a) \in(B \times A) \Rightarrow b \in B$ and $a \in A$

$$
\Rightarrow(a, b) \in(A \times B) .
$$

Thus, for each $(b, a) \in(B \times A)$, there exists $(a, b) \in A \times B$ such that $f(a, b)=(b, a)$.
$\therefore f$ is onto.

Thus, $f$ is one-one onto and hence bijective.

---

### Example 13:

Find the domain and range of the real function

$$
f(x)=\sqrt{9-x^{2}}
$$

#### Solution:

It is clear that $f(x)=\sqrt{9-x^{2}}$ is not defined when $\left(9-x^{2}\right)<0$, i.e., when $x^{2}>9$, i.e., when $x>3$ or $x<-3$.
$\therefore \operatorname{dom}(f)=\{x \in R:-3 \leq x \leq 3\}$.

Also, $y=\sqrt{9-x^{2}} \Rightarrow y^{2}=\left(9-x^{2}\right)$

$$
\Rightarrow x=\sqrt{9-y^{2}} .
$$

Clearly, $x$ is not defined when $\left(9-y^{2}\right)<0$.
But, $\left(9-y^{2}\right)<0 \Rightarrow y^{2}>9$

$$
\Rightarrow y>3 \text { or } y<-3
$$

$\therefore \operatorname{range}(f)=\{y \in R:-3 \leq y \leq 3\}$.

---

### Example 14:

Find the domain and range of the real function, defined by

$$
f(x)=\frac{1}{\left(1-x^{2}\right)}
$$

#### Solution:

Clearly, $\frac{1}{\left(1-x^{2}\right)}$ is not defined when $1-x^{2}=0$,
i.e., when $x= \pm 1$.
$\therefore \operatorname{dom}(f)=R-\{-1,1\}$.

Also, $y=\frac{1}{\left(1-x^{2}\right)} \Rightarrow\left(1-x^{2}\right)=\frac{1}{y} \Rightarrow x=\sqrt{1-\frac{1}{y}}$.
Clearly, $x$ is not defined when $\left(1-\frac{1}{y}\right)<0$ or $1<\frac{1}{y}$ or $y<1$.
$\therefore \operatorname{range}(f)=R-\{y \in R: y<1\}=\{y \in R: y \geq 1\}$.

---

### Example 15:

Consider a function $f: X \rightarrow Y$ and define a relation $R$ in $X$ by $R=\{(a, b): f(a)=f(b)\}$. Show that $R$ is an equivalence relation.

#### Solution:

Here, $R$ satisfies the following properties:

**(i) Reflexivity**

Let $a \in X$. Then,

$$
f(a)=f(a) \Rightarrow(a, a) \in R .
$$

$\therefore R$ is reflexive.

**(ii) Symmetry**

Let $(a, b) \in R$. Then,

$$
(a, b) \in R \Rightarrow f(a)=f(b) \Rightarrow f(b)=f(a) \Rightarrow(b, a) \in R .
$$

$\therefore R$ is symmetric.

**(iii) Transitivity**

Let $(a, b) \in R$ and $(b, c) \in R$. Then,

$$
\begin{aligned}
& (a, b) \in R, \quad(b, c) \in R \\
\Rightarrow & f(a)=f(b) \text { and } f(b)=f(c) \\
\Rightarrow & f(a)=f(c) \\
\Rightarrow & (a, c) \in R .
\end{aligned}
$$

$\therefore R$ is transitive.

Hence, $R$ is an equivalence relation.

---
