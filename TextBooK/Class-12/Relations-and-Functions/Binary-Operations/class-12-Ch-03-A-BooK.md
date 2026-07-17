## 3. Binary Operations

**Closure Property:** An operation $*$ on a nonempty set $S$ is said to satisfy the **closure property**, if

$$
a \in S, b \in S \Rightarrow a * b \in S \text { for all } a, b \in S .
$$

Also, in this case, we say that $S$ is **closed for $*$**.
An operation $*$ on a nonempty set $S$, satisfying the closure property is known as a **binary operation**.

---

### Example 1:

(i) Addition on the set $N$ of all natural numbers is a binary operation, since

$$
a \in N, b \in N \Rightarrow a+b \in N \text { for all } a, b \in N .
$$

(ii) Multiplication on $N$ is a binary operation, since

$$
a \in N, b \in N \Rightarrow a \times b \in N \text { for all } a, b \in N .
$$

Similarly, addition as well as multiplication is a binary operation on each one of the sets $Z$, $Q$, $R$ and $C$ of integers, rationals, reals and complex numbers respectively.

---

### Example 2:

Let $S$ be a nonempty set and $P(S)$ be its power set. Then, the union operation on $P(S)$ is a binary operation, since

$$
A \in P(S), B \in P(S) \Rightarrow A \cup B \in P(S) \text { for all } A, B \in P(S) .
$$

Similarly, intersection on $P(S)$ is a binary operation, as

$$
A \in P(S), B \in P(S) \Rightarrow A \cup B \in P(S) \text { for all } A, B \in P(S) .
$$
*(Note: The original document has a typo, listing $A \cup B$ for intersection. The math content is preserved exactly as written.)*

---

### Example 3:

Subtraction on $N$ is not a binary operation, since

$$
3 \in N, 5 \in N \text { but }(3-5)=-2 \notin N .
$$

Subtraction on the set $Z$ of all integers is a binary operation, since

$$
a \in Z, b \in Z \Rightarrow a-b \in Z \text { for all } a, b \in Z .
$$

---

### Example 4:

Addition on the set $S$ of all irrationals is not a binary operation, since

$$
2+\sqrt{3} \in S, 2-\sqrt{3} \in S \text { but }(2+\sqrt{3})+(2-\sqrt{3})=4 \notin S .
$$

Multiplication on the set $S$ of all irrationals is not a binary operation, since

$$
\sqrt{2} \in S,-\sqrt{2} \in S \text { but }(\sqrt{2})(-\sqrt{2})=-2 \notin S .
$$

---

### Example 5:

Let $N$ be the set of all natural numbers. Then, the exponential operation $(a, b) \Rightarrow a^{b}$ is a binary operation on $N$, since

$$
a \in N, b \in N \Rightarrow a^{b} \in N \text { for all } a, b \in N .
$$

Let $Z$ be the set of all integers. The exponential operation $(a, b) \rightarrow a^{b}$ is not a binary operation on $Z$, since $2 \in Z, -3 \in Z$ but $2^{-3}=\frac{1}{2^{3}}=\frac{1}{8} \notin Z$.

---

## Properties of a Binary Operation

(i) **Associative Law:** A binary operation $*$ on a nonempty set $S$ is said to be **associative**, if

$$
(a * b) * c=a *(b * c) \text { for all } a, b, c \in S .
$$

(ii) **Commutative Law:** A binary operation $*$ on a nonempty set $S$ is said to be **commutative**, if

$$
a * b=b * a \text { for all } a, b \in S .
$$

(iii) **Distributive Law:** Let $*$ and $\circ$ be two binary operations on a nonempty set $S$. We say that $*$ is **distributive over $\circ$**, if

$$
a *(b \circ c)=(a * b) \circ(a * c) \text { for all } a, b, c \in S .
$$

---

### Example 1:

Let $R$ be the set of all real numbers. Then,
- (i) addition on $R$ satisfies the closure property, the associative law and the commutative law,
- (ii) multiplication on $R$ satisfies the closure property, the associative law and the commutative law,
- (iii) multiplication distributes addition on $R$, since

$$
a \cdot(b+c)=a \cdot b+a \cdot c \text { for all } a, b, c \in R
$$

---

### Example 2:

Let $Z$ be the set of all integers. Then, subtraction on $Z$ is clearly a binary operation. But, it is neither commutative nor associative, as

$$
(3-5) \neq(5-3) \text { and }(3-4)-5 \neq 3-(4-5) .
$$

---

**Identity Element:** Let $*$ be a binary operation on a nonempty set $S$. An element $e \in S$, if it exists such that

$$
a * e=e * a=a \text { for all } a \in S
$$

is called an **identity element** of $S$, with respect to $*$.

### Example 1:

(i) For addition on $R$, zero is the identity element in $R$, since

$$
a+0=0+a=a \text { for all } a \in R .
$$

(ii) For multiplication on $R$, 1 is the identity element in $R$, since

$$
a \times 1=1 \times a=a \text { for all } a \in R .
$$

---

### Example 2:

Let $P(S)$ be the power set of a nonempty set $S$. Then, $\phi$ is the identity element for union on $P(S)$ as

$$
A \cup \phi=\phi \cup A=A \text { for all } A \in P(S) .
$$

Also, $S$ is the identity element for intersection on $P(S)$, since

$$
A \cap S=S \cap A=A \text { for all } A \in P(S) .
$$

---

**Inverse of an Element:** Let $*$ be a binary operation on a nonempty set $S$ and let $e$ be the identity element.
Let $a \in S$. We say that $a$ is **invertible** if there exists an element $b \in S$ such that

$$
a * b=b * a=e .
$$

Also, in this case, $b$ is called the **inverse** of $a$, and we write, $a^{-1}=b$.

### Example 1:

Consider addition on $Z$.
Clearly, the additive identity is 0, since

$$
a+0=0+a=a \text { for all } a \in Z .
$$

Also, corresponding to each $a \in Z$, there exists $-a \in Z$ such that

$$
a+(-a)=(-a)+a=0 .
$$

Thus, the additive inverse of $a$ is $-a$.

---

### Example 2:

Consider multiplication on $Z$.
Clearly, 1 is the multiplicative identity on $Z$, since

$$
a \times 1=1 \times a=a \text { for all } a \in Z .
$$

Since $1 \times 1=1$, so the multiplicative inverse of 1 is 1.
Since $(-1) \times(-1)=1$, so the multiplicative inverse of $(-1)$ is $(-1)$.
No integer other than 1 and -1 has its multiplicative inverse in $Z$.

---

## Solved Examples

### Example 1:

Let $Z$ be the set of all integers. Then, addition on $Z$ satisfies the following properties:

(i) **Closure Property**
We know that the sum of two integers is always an integer, i.e., $a \in Z, b \in Z \Rightarrow a+b \in Z$ for all $a, b \in Z$.

(ii) **Associative Law**
For all $a, b, c \in Z$, we have

$$
(a+b)+c=a+(b+c) .
$$

(iii) **Commutative Law**
For all $a, b \in Z$, we have

$$
a+b=b+a .
$$

(iv) **Existence of Additive Identity**
Clearly, $0 \in Z$ is the additive identity, since

$$
0+a=a+0=a \text { for all } a \in Z .
$$

(v) **Existence of Additive Inverse**
For each $a \in Z$, there exists $-a \in Z$ such that

$$
a+(-a)=(-a)+a=0 .
$$

So, $-a$ is the additive inverse of $a$.

---

### Example 2:

Let $R_{0}$ be the set of all nonzero real numbers. Then, multiplication on $R_{0}$ satisfies the following properties:

(i) **Closure Property**
We know that the product of two nonzero real numbers is a nonzero real number.
Thus, $a \in R_{0}, b \in R_{0} \Rightarrow a b \in R_{0}$ for all $a, b \in R_{0}$.

(ii) **Associative Law**
For all $a, b, c \in R_{0}$, we have $(a b) c=a(b c)$.

(iii) **Commutative Law**
For all $a, b \in R_{0}$, we have $a b=b a$.

(iv) **Existence of Multiplicative Identity**
Clearly, $1 \in R_{0}$ is the multiplicative identity, since

$$
1 \times a=a \times 1 \text { for all } a \in R_{0} .
$$

(v) **Existence of Multiplicative Inverse**
For each $a \in R_{0}$ there exists $\frac{1}{a} \in R_{0}$ such that

$$
a \times \frac{1}{a}=\frac{1}{a} \times a=1 .
$$

Thus, the multiplicative inverse of $a$ is $\frac{1}{a}$.

---

### Example 3:

Show that the operation $*$ on $Z$, defined by

$$
a * b=a+b+1 \text { for all } a, b \in Z
$$

satisfies (i) the closure property, (ii) the associative law and (iii) the commutative law.
(iv) Find the identity element in Z.
(v) What is the inverse of an element $a \in Z$?

#### Solution:

(i) **Closure Property**
Let $a \in Z, b \in Z$. Then,

$$
a * b=a+b+1 .
$$

Now, $a \in Z, b \in Z \Rightarrow a+b \in Z$

$$
\Rightarrow a+b+1 \in Z .
$$

$\therefore \quad *$ on $Z$ satisfies the closure property.

(ii) **Associative Law**
For all $a, b, c \in Z$, we have:

$$
\begin{aligned}
(a * b) * c & =(a+b+1) * c \\
& =(a+b+1)+c+1 \\
& =a+b+c+2 . \\
a *(b * c) & =a *(b+c+1) \\
& =a+(b+c+1)+1 \\
& =a+b+c+2 . \\
\therefore \quad(a * b) * c= & a *(b * c) .
\end{aligned}
$$

(iii) **Commutative Law**
For all $a, b \in Z$, we have

$$
\begin{aligned}
a * b & =a+b+1 \\
& =b+a+1 \quad[\because a+b=b+a] \\
& =b * a
\end{aligned}
$$

(iv) **Existence of Identity Element**
Let $e$ be the identity element in $Z$.

$$
\text { Then, } \begin{aligned}
a * e=a & \Rightarrow a+e+1=a \\
& \Rightarrow e=-1 .
\end{aligned}
$$

Thus, $-1 \in Z$ is the identity element for $*$.

(v) **Existence of Inverse**
Let $a \in Z$ and let its inverse be $b$. Then,

$$
\begin{aligned}
a * b=-1 & \Rightarrow a+b+1=-1 \\
& \Rightarrow b=-(2+a)
\end{aligned}
$$

Clearly, $2 \in Z, a \in Z \Rightarrow -(2+a) \in Z$.
Thus, each $a \in Z$ has $-(2+a) \in Z$ as its inverse.

---

### Example 4:

Show that the operation $*$ on $Q-\{1\}$, defined by

$$
a * b=a+b-a b \text { for all } a, b \in Q-\{1\}
$$

satisfies (i) the closure property, (ii) the associative law,
(iii) the commutative law.
(iv) What is the identity element?
(v) For each $a \in Q-\{1\}$, find the inverse of $a$.

#### Solution:

(i) **Closure Property**
Let $a \in Q-\{1\}$ and $b \in Q-\{1\}$.
We know that $Q$ is closed for addition, subtraction and multiplication.

$$
\therefore a+b-a b \in Q
$$

But, $a * b=1 \Rightarrow a+b-a b=1$
$\quad \Rightarrow a(1-b)=(1-b) \Rightarrow a=1$,
which is a contradiction since $1 \notin Q-\{1\}$.

$$
\therefore \quad a * b \neq 1 .
$$

Thus, $a \in Q-\{1\}, b \in Q-\{1\} \Rightarrow a * b \in Q-\{1\}$.
$\therefore \quad *$ is a binary operation on $Q-\{1\}$.

(ii) **Associative Law**
Let $a, b, c \in Q-\{1\}$. Then,

$$
\begin{aligned}
(a * b) * c & =(a+b-a b) * c \\
& =(a+b-a b)+c-(a+b-a b) c \\
& =(a+b+c)-(a b+b c+a c)+a b c
\end{aligned}
$$

And, $a *(b * c)=a *(b+c-b c)$

$$
\begin{aligned}
& =a+(b+c-b c)-a(b+c-b c) \\
& =(a+b+c)-(a b+b c+a c)+a b c
\end{aligned}
$$

$\therefore(a * b) * c=a *(b * c)$.
Hence, $*$ is associative.

(iii) **Commutative Law**
Let $a, b \in Q-\{1\}$. Then,

$$
\begin{aligned}
a * b & =a+b-a b \\
& =b+a-b a \quad[\because+\text { and } \cdot \text { are commutative on } Q-\{1\}] \\
& =b * a .
\end{aligned}
$$

Hence, $*$ is commutative.

(iv) **Existence of Identity Element**
Let $e$ be the identity element.
Then, for all $a \in Q-\{1\}$, we have

$$
\begin{aligned}
a * e=a & \Rightarrow a+e-a e=a \\
& \Rightarrow e(1-a)=0 \Rightarrow e=0 \in Q-\{1\} .
\end{aligned}
$$

Now, $a * 0=a+0-a \times 0=a$.
And, $0 * a=0+a-0 \times a=a$.
Thus, 0 is the identity element in $Q-\{1\}$.

(v) **Existence of Inverse**
Let $a \in Q-\{1\}$ and let $a^{-1}=b$. Then,

$$
\begin{aligned}
& a * b=0 \Rightarrow a+b-a b=0 \\
& \Rightarrow a=a b-b=(a-1) b \\
& \Rightarrow b=\frac{a}{(a-1)} \in Q-\{1\} . \\
& \therefore \quad a^{-1}=\frac{a}{(a-1)} \in Q-\{1\} .
\end{aligned}
$$

Thus, each $a \in Q-\{1\}$ has its inverse in $Q-\{1\}$.

---

### Example 5:

On the set $N$ of all natural numbers, define the operation $*$ on $N$ by
$m * n=\operatorname{gcd}(m, n)$ for all $m, n \in N$.
Show that $*$ is commutative as well as associative.

#### Solution:

(i) **Commutativity**
For all $m, n \in N$, we have $\operatorname{gcd}(m, n)=\operatorname{gcd}(n, m)$.
$\therefore m * n=n * m \forall m, n \in N$.
Hence, $*$ is commutative on $N$.

(ii) **Associativity**
Let $m, n, p \in N$. Then,

$$
\begin{aligned}
(m * n) * p & =[\operatorname{gcd}(m, n)] * p \\
& =\operatorname{gcd}[\operatorname{gcd}\{(m, n), p\}] \\
& =\operatorname{gcd}[\{m, \operatorname{gcd}(n, p)\}]
\end{aligned}
$$

$[\because \operatorname{gcd}$ of three numbers $=\operatorname{gcd}\{(\operatorname{gcd}$ of any two, third $)\}]$

$$
=\operatorname{gcd}(m, n * p)=m *(n * p) .
$$

Hence, $*$ is associative on $N$.

---

### Example 6:

Consider the set $A=\{-1,1\}$ with multiplication operation. We may prepare its composition table as shown below.

| $\times$ | 1 | -1 |
| ---: | :-: | ---: |
| 1 | 1 | -1 |
| -1 | -1 | 1 |

Multiplication on $A$ satisfies the following properties:

(i) **Closure Property**
Since all the entries of the composition table are in $A$, so $A$ is closed for multiplication.

(ii) **Associative Law**
Since multiplication of integers is associative, in particular, multiplication on $A$ is associative.

(iii) **Commutative Law**
Since every row of the table coincides with the corresponding column,
i.e., 1st row coincides with 1st column, 2nd row coincides with 2nd column.
So, multiplication is commutative on $A$.

(iv) **Existence of Identity**
Clearly, 1 is the identity element in $A$, since

$$
1 \times 1=1 \text { and }(-1) \times 1=1 \times(-1)=-1 .
$$

(v) **Existence of Inverse**
It is clear from the table that $1 \times 1=1 \Rightarrow$ inverse of 1 is 1 , $(-1) \times(-1)=1 \Rightarrow$ inverse of ( -1 ) is ( -1 ).

---

## New Operations

### Example 7:

Let $A=\{1,2,3,4,5\}$. Define an operation $\wedge$ by

$$
a \wedge b=\min \{a, b\} .
$$

Then, we may prepare its composition table as given below.

| $\vee$ | 1 | 2 | 3 | 4 | 5 |
| :--: | :-: | :-: | :-: | :-: | :-: |
| 1 | 1 | 1 | 1 | 1 | 1 |
| 2 | 1 | 2 | 2 | 2 | 2 |
| 3 | 1 | 2 | 3 | 3 | 3 |
| 4 | 1 | 2 | 3 | 4 | 4 |
| 5 | 1 | 2 | 3 | 4 | 5 |

#### Closure Property

Since all the entries of the composition table are from given set $A$, so $A$ is closed for the operation $\wedge$.

#### Commutative Law

In the given table every row coincides with the corresponding column,
i.e., 1st row coincides with 1st column, 2nd row coincides with 2nd column, and so on.
$\therefore \quad \wedge$ on $A$ is commutative.

---

### Example 8:

Let $A=\{1,2,3,4,5\}$. Define an operation $\vee$ by $a \vee b=\max \{a, b\}$.
Prepare its composition table.
Show that $A$ is closed for the given operation and that the given operation is commutative.

#### Solution:

We prepare the table as given below.

| $\vee$ | 1 | 2 | 3 | 4 | 5 |
| :--: | :-: | :-: | :-: | :-: | :-: |
| 1 | 1 | 2 | 3 | 4 | 5 |
| 2 | 2 | 2 | 3 | 4 | 5 |
| 3 | 3 | 3 | 3 | 4 | 5 |
| 4 | 4 | 4 | 4 | 4 | 5 |
| 5 | 5 | 5 | 5 | 5 | 5 |

**Closure Property**
Since all the entries of the composition table are from the given set, so closure property is satisfied.

**Commutative Law**
Clearly, every row coincides with the corresponding column. So, commutative law is satisfied.

---
