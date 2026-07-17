## Relations

Let $A$ and $B$ be two nonempty sets. Then, a **relation** $R$ from $A$ to $B$ is a subset of $(A \times B)$.

Thus, $R$ is a relation from $A$ to $B \Leftrightarrow R \subseteq(A \times B)$.

If $(a, b) \in R$ then we say that '$a$ is related to $b$' and we write, $a R b$.
If $(a, b) \notin R$ then '$a$ is not related to $b$' and we write, $a \mathbb{R} b$.

---

## Domain, Range, and Co-domain of a Relation

Let $R$ be a relation from $A$ to $B$. Then, $R \subseteq(A \times B)$.

- (i) The set of all first coordinates of elements of $R$ is called the **domain of R**, written as dom ($R$).
- (ii) The set of all second coordinates of elements of $R$ is called the **range of R**, denoted by range ($R$).
- (iii) The set $B$ is called the **co-domain of R**.

$$
\operatorname{Dom}(R)=\{a:(a, b) \in R\} \text{ and } \text{Range}(R)=\{b:(a, b) \in R\}
$$

---

## Total Number of Relations from A to B

Let $n(A)=p$ and $n(B)=q$. Then, $n(A \times B)=p q$.

We know that every subset of $A \times B$ is a relation from $A$ to $B$.
Total number of subsets of $A \times B$ is $2^{p q}$.

$\therefore$ total number of relations from $A$ to $B = 2^{p q}$.

---

## Representation of a Relation

Let $A$ and $B$ be two given sets. Then, a relation $R \subseteq A \times B$ can be represented in any of the forms, given below.

### (i) Roster Form

In this form, $R$ is given as a set of ordered pairs.

### Example 1:

Let $A=\{-2,-1,0,1,2\}$ and $B=\{0,1,4,9\}$.
Let $R=\{(-2,4),(-1,1),(0,0),(1,1),(2,4)\}$.

(i) Show that $R$ is a relation from $A$ to $B$.
(ii) Find dom ($R$), range ($R$) and co-domain of $R$.

#### Solution:

(i) Since $R \subset A \times B$, so $R$ is a relation from $A$ to $B$.
Note that $-2 R 4, -1 R 1, 0 R 0, 1 R 1$ and $2 R 4$.

(ii) $\operatorname{Dom}(R) =$ set of first coordinates of elements of $R$
$$
=\{-2,-1,0,1,2\}.
$$
Range $(R) =$ set of second coordinates of elements of $R$
$$
=\{0,1,4\}.
$$
Co-domain of $R=\{0,1,4,9\}=B$.

---

### (ii) Set-Builder Form

Under this method, for every $(a, b) \in R$, a general relation is being given between $a$ and $b$.
Using this relation, all the elements of $R$ can be obtained.

### Example 2:

Let $A=\{1,2,3,5\}$ and $B=\{4,6,9\}$.
Define a relation from $A$ to $B$, given by
$$
R=\{(a, b): a \in A, b \in B \text { and } (a-b) \text{ is odd} \}.
$$
(i) Write $R$ in roster form.
(ii) Find dom ($R$) and range ($R$).

#### Solution:

(i) Clearly, we have
$$
R=\{(1,4),(1,6),(2,9),(3,4),(3,6),(5,4),(5,6)\}
$$
(ii) $\operatorname{Dom}(R)=$ set of first coordinates of elements of $R$
$$
=\{1,2,3,5\}.
$$
Range $(R)=$ set of second coordinates of elements of $R$
$$
=\{4,6,9\}.
$$

---

### Example 3:

Let $R=\left\{\left(x, x^{3}\right)\right.$ : $x$ is a prime number less than 10$\}$.
(i) Write $R$ in roster form.
(ii) Find dom ($R$) and range ($R$).

#### Solution:

Prime numbers less than 10 are $2,3,5,7$.
(i) $R=\left\{\left(2,2^{3}\right),\left(3,3^{3}\right),\left(5,5^{3}\right),\left(7,7^{3}\right)\right\}$
$$
=\{(2,8),(3,27),(5,125),(7,343)\}.
$$
(ii) $\operatorname{Dom}(R)=\{2,3,5,7\}$.

Range $(R)=\{8,27,125,343\}$.

---

### Example 4:

Let $R=\{(x, y): x$ and $y$ are integers and $x y=4\}$.
(i) Write $R$ in roster form.
(ii) Find dom ($R$) and range ($R$).

#### Solution:

Clearly, we have
(i) $R=\{(-4,-1),(-2,-2),(-1,-4),(1,4),(2,2),(4,1)\}$.
(ii) $\operatorname{Dom}(R)=\{-4,-2,-1,1,2,4\}$.

Range $(R)=\{-4,-2,-1,1,2,4\}$.

---

### (iii) Arrow Diagram

Let $R$ be a relation from $A$ to $B$. First, we draw two bounded figures to represent $A$ and $B$ respectively. We mark the elements of $A$ and $B$ in these figures. For each $(a, b) \in R$, we draw an arrow from $a$ to $b$. This gives us the required arrow diagram.

### Example 5:

Let $A=\{1,2,3,4,5\}$. Define a relation $R$ from $A$ to $A$ by $R=\{(x, y): y=2 x-3\}$.
(i) Depict $R$ using an arrow diagram.
(ii) Find dom ($R$) and range ($R$).

#### Solution:

- $x=1 \Rightarrow y=(2-3)=-1 \notin A$
- $x=2 \Rightarrow y=(4-3)=1$
- $x=3 \Rightarrow y=(6-3)=3$
- $x=4 \Rightarrow y=(8-3)=5$
- $x=5 \Rightarrow y=(10-3)=7 \notin A$

$\therefore R=\{(2,1),(3,3),(4,5)\}$.

(i) We may depict it by arrow diagram, as shown below:
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Set-and-Functions/Relations/class-11-Ch-02-C-BooK-001.jpg)

(ii) We have, $\operatorname{dom}(R)=\{2,3,4\}$ and $\operatorname{range}(R)=\{1,3,5\}$.

---

### Example 6:

Let $A=\{1,2,3,4,5\}$ and $B=\{1,4,5\}$.
Let $R$ be a relation 'is less than' from $A$ to $B$.

(i) List the elements of $R$.
(ii) Find the domain, co-domain and range of $R$.
(iii) Depict the above relation by an arrow diagram.

#### Solution:

Here, $A=\{1,2,3,4,5\}$ and $B=\{1,4,5\}$.

(i) $R=\{(1,4),(1,5),(2,4),(2,5),(3,4),(3,5),(4,5)\}$.
(ii) $\operatorname{Dom}(R)=\{1,2,3,4\}$, $\operatorname{range}(R)=\{4,5\}$ and $\operatorname{co-domain}(R)=\{1,4,5\}$.
(iii) We may represent the above relation by an arrow diagram, shown below.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Set-and-Functions/Relations/class-11-Ch-02-C-BooK-002.jpg)

---

**Remark:** Let $A$ and $B$ be two nonempty sets. Then, every subset of $A \times B$ is a relation from $A$ to $B$. Since $\phi \subset A \times B$, so $\phi$ is also a relation from $A$ to $B$, called an **empty** or **void relation**.

---

### Example 7:

Let $A=\{x, y, z\}$ and $B=\{1,2\}$. Find the number of all possible relations that can be defined from $A$ to $B$.

#### Solution:

Here $n(A)=3$ and $n(B)=2$. So, $n(A \times B)=(3 \times 2)=6$.
Since a set containing $n$ elements has $2^{n}$ subsets.
$\therefore (A \times B)$ will have $2^{6}=64$ subsets.
But, every subset of $A \times B$ is a relation from $A$ to $B$.
Hence, there are in all 64 relations from $A$ to $B$.

---

