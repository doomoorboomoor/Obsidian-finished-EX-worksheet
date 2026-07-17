## 1. Relations

In class 11 we discussed about the Cartesian product of sets. Now, we extend our ideas to relation in a set and then in next chapter we shall be taking up functions.

## Relation in a Set

A relation $R$ in a set $A$ is a subset of $A \times A$.
Thus, $R$ is a relation in a set $A \Leftrightarrow R \subseteq A \times A$.

If $(a, b) \in R$ then we say that $a$ is related to $b$ and write, $a R b$.
If $(a, b) \notin R$ then we say that $a$ is not related to $b$ and write, $a, R b$.

**Example:** Let $A=\{1,2,3,4,5,6\}$ and let $R$ be a relation in $A$, given by
$$
R=\{(a, b): a-b=2\} .
$$
Then, $R=\{(3,1),(4,2),(5,3),(6,4)\}$.
Clearly, $3 R 1,4 R 2,5 R 3$ and $6 R 4$.
But, $1 R^{\prime} 3,2 R^{\prime} 4,5 R^{\prime} 6$, etc.

## Domain and Range of a Relation

Let $R$ be a relation in a set $A$. Then, the set of all first coordinates of elements of $R$ is called the **domain of $R$**, written as $\operatorname{dom}(R)$ and the set of all second coordinates of $R$ is called the **range of $R$**, written as $\operatorname{range}(R)$.

$$
\therefore \operatorname{dom}(R)=\{a:(a, b) \in R\} \text { and range }(R)=\{b:(a, b) \in R\} .
$$

**Example:** Let $A=\{1,2,3,4, \ldots, 15,16\}$ and let $R$ be a relation in $A$, given by
$$
R=\left\{(a, b): b=a^{2}\right\} .
$$
Then, $R=\{(1,1),(2,4),(3,9),(4,16)\}$.

$$
\therefore \operatorname{dom}(R)=\{1,2,3,4\} \text { and range }(R)=\{1,4,9,16\} .
$$

## Some Particular Types of Relations

**EMPTY RELATION (Or VOID RELATION)**
A relation $R$ in a set $A$ is called an **empty relation**, if no element of $A$ is related to any element of $A$ and we denote such a relation by $\phi$.
Thus, $R=\phi \subseteq A \times A$.

**Example:** Let $A=\{1,2,3,4,5\}$ and let $R$ be a relation in $A$, given by $R=\{(a, b): a-b=6\}$.
Clearly, no element $(a, b) \in A \times A$ satisfies the property $a-b=6$.
$\therefore \quad R$ is an empty relation in $A$.

**UNIVERSAL RELATION**
A relation $R$ in a set $A$ is called a **universal relation**, if each element of $A$ is related to every element of $A$.
Thus, $R=(A \times A) \subseteq(A \times A)$ is the universal relation on $A$.

**Example:** Let $A=\{1,2,3\}$. Then,
$$
R=(A \times A)=\{(1,1),(1,2),(1,3),(2,1),(2,2),(2,3),(3,1),(3,2),(3,3)\}
$$
is the universal relation in $A$.

**IDENTITY RELATION**
The relation $I_{A}=\{(a, a): a \in A\}$ is called the **identity relation** on $A$.

**Example:** Let $A=\{1,2,3\}$. Then,
$$
I_{A}=\{(1,1),(2,2),(3,3)\} \text { is the identity relation on } A \text {. }
$$

## Various Types of Relations

Let $A$ be a nonempty set. Then, a relation $R$ on $A$ is said to be:

-   **(i) reflexive:** if $(a, a) \in R$ for each $a \in A$,
    i.e., if $a R a$ for each $a \in A$.
-   **(ii) symmetric:** if $(a, b) \in R \Rightarrow(b, a) \in R$ for all $a, b \in A$,
    i.e., if $a R b \Rightarrow b R a$ for all $a, b \in A$.
-   **(iii) transitive:** if $(a, b) \in R,(b, c) \in R \Rightarrow(a, c) \in R$ for all $a, b, c \in A$,
    i.e., if $a R b$ and $b R c \Rightarrow a R c$.

**EQUIVALENCE RELATION**
A relation $R$ in a set $A$ is said to be an **equivalence relation** if it is reflexive, symmetric and transitive.

---

## Solved Examples

### Example 1:

Let $A$ be the set of all triangles in a plane and let $R$ be a relation in $A$, defined by $R=\left\{\left(\triangle_{1}, \triangle_{2}\right): \triangle_{1} \cong \triangle_{2}\right\}$.
Show that $R$ is an equivalence relation in $A$.

#### Solution:

The given relation satisfies the following properties:

**(i) Reflexivity**

Let $\Delta$ be an arbitrary triangle in $A$. Then,
$$
\Delta \cong \Delta \Rightarrow(\Delta, \Delta) \in R \text { for all values of } \Delta \text { in } A \text {. }
$$
$\therefore \quad R$ is reflexive.

**(ii) Symmetry**

Let $\Delta_{1}, \Delta_{2} \in A$ such that $\left(\Delta_{1}, \Delta_{2}\right) \in R$. Then,
$$
\begin{aligned}
\left(\Delta_{1}, \Delta_{2}\right) \in R & \Rightarrow \Delta_{1} \cong \Delta_{2} \\
& \Rightarrow \Delta_{2} \cong \Delta_{1} \\
& \Rightarrow\left(\Delta_{2}, \Delta_{1}\right) \in R .
\end{aligned}
$$
$\therefore \quad R$ is symmetric.

**(iii) Transitivity**

Let $\triangle_{1}, \triangle_{2}, \triangle_{3} \in A$ such that $\left(\triangle_{1}, \triangle_{2}\right) \in R$ and $\left(\triangle_{2}, \triangle_{3}\right) \in R$.
Then, $\left(\triangle_{1}, \triangle_{2}\right) \in R$ and $\left(\triangle_{2}, \triangle_{3}\right) \in R$
$$
\begin{aligned}
& \Rightarrow \triangle_{1} \cong \triangle_{2} \text { and } \triangle_{2} \cong \triangle_{3} \\
& \Rightarrow \triangle_{1} \cong \triangle_{2} \\
& \Rightarrow\left(\triangle_{1}, \triangle_{3}\right) \in R .
\end{aligned}
$$
$\therefore \quad R$ is transitive.

Thus, $R$ is reflexive, symmetric and transitive.
Hence, $R$ is an equivalence relation.

---

### Example 2:

Let $A$ be the set of all lines in xy-plane and let $R$ be a relation in $A$, defined by
$$
R=\left\{\left(L_{1}, L_{2}\right): L_{1} \| L_{2}\right\} .
$$
Show that $R$ is an equivalence relation in $A$.
Find the set of all lines related to the line $y=3 x+5$.

#### Solution:

The given relation satisfies the following properties:

**(i) Reflexivity**

Let $L$ be an arbitrary line in $A$. Then,
$$
L \| L \Rightarrow(L, L) \in R \forall L \in A .
$$
Thus, $R$ is reflexive.

**(ii) Symmetry**

Let $L_{1}, L_{2} \in A$ such that $\left(L_{1}, L_{2}\right) \in R$. Then,
$$
\begin{aligned}
\left(L_{1}, L_{2}\right) \in R & \Rightarrow L_{1} \| L_{2} \\
& \Rightarrow L_{2} \| L_{1} \\
& \Rightarrow\left(L_{2}, L_{1}\right) \in R .
\end{aligned}
$$
$\therefore \quad R$ is symmetric.

**(iii) Transitivity**

Let $L_{1}, L_{2}, L_{3} \in A$ such that $\left(L_{1}, L_{2}\right) \in R$ and $\left(L_{2}, L_{3}\right) \in R$.
Then, $\left(L_{1}, L_{2}\right) \in R$ and $\left(L_{2}, L_{3}\right) \in R$
$$
\Rightarrow L_{1} \| L_{2} \text { and } L_{2} \| L_{3}
$$
$$
\begin{aligned}
& \Rightarrow L_{1} \| L_{3} \\
& \Rightarrow\left(L_{1}, L_{3}\right) \in R .
\end{aligned}
$$
$\therefore \quad R$ is transitive.

Thus $R$ is reflexive, symmetric and transitive.
Hence, $R$ is an equivalence relation.

The family of lines parallel to the line $y=3 x+5$ is given by $y=3 x+k$, where $k$ is real.

---

### Example 3:

Let $Z$ be the set of all integers and let $R$ be a relation in $Z$, defined by
$R=\{(a, b):(a-b)$ is even $\}$.
Show that $R$ is an equivalence relation in $Z$.

#### Solution:

Here, $R$ satisfies the following properties:

**(i) Reflexivity**

Let $a$ be an arbitrary element of $Z$.
Then, $(a-a)=0$, which is even.
$\therefore \quad(a, a) \in R \forall a \in Z$.
So, $R$ is reflexive.

**(ii) Symmetry**

Let $a, b \in Z$ such that $(a, b) \in R$. Then,
$$
\begin{aligned}
(a, b) \in R & \Rightarrow(a-b) \text { is even } \\
& \Rightarrow-(a-b) \text { is even } \\
& \Rightarrow(b-a) \text { is even } \\
& \Rightarrow(b, a) \in R
\end{aligned}
$$
$\therefore \quad R$ is symmetric.

**(iii) Transitivity**

Let $a, b, c \in Z$ such that $(a, b) \in R$ and $(b, c) \in R$. Then,
$$
(a, b) \in R \text { and }(b, c) \in R
$$
$\Rightarrow(a-b)$ is even and $(b-c)$ is even
$\Rightarrow\{(a-b)+(b-c)\}$ is even
$\Rightarrow(a-c)$ is even
$\Rightarrow(a, c) \in R$.
$\therefore \quad R$ is transitive.

Thus, $R$ is reflexive, symmetric and transitive.
Hence, $R$ is an equivalence relation in $Z$.

---

### Example 4:

Let $A$ be the set of all lines in a plane and let $R$ be a relation in $A$ defined by
$$
R=\left\{\left(L_{1}, L_{2}\right): L_{1} \perp L_{2}\right\} .
$$
Show that $R$ is symmetric but neither reflexive nor transitive.

#### Solution:

Clearly, any line $L$ cannot be perpendicular to itself.
$\therefore \quad(L, L) \notin R$ for any $L \in A$.
So, $R$ is not reflexive.

Again, let $\left(L_{1}, L_{2}\right) \in R$. Then,
$$
\begin{aligned}
\left(L_{1}, L_{2}\right) \in R & \Rightarrow L_{1} \perp L_{2} \\
& \Rightarrow L_{2} \perp L_{1} \\
& \Rightarrow\left(L_{2}, L_{1}\right) \in R .
\end{aligned}
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Relations-and-Functions/Relations/class-12-Ch-01-A-BooK-001.jpg)

$\therefore \quad R$ is symmetric.

Now, let $L_{1}, L_{2}, L_{3} \in A$ such that $L_{1} \perp L_{2}$ and $L_{2} \perp L_{3}$.
Then, clearly $L_{1}$ is not perpendicular to $L_{3}$.
Thus, $\left(L_{1}, L_{2}\right) \in R$ and $\left(L_{2}, L_{3}\right) \in R$, but $\left(L_{1}, L_{3}\right) \notin R$.
$\therefore R$ is not transitive.

Hence, $R$ is symmetric but neither reflexive nor transitive.

---

### Example 5:

Let $S$ be the set of all real numbers and let $R$ be a relation in $S$ defined by
$$
R=\{(a, b):(1+a b)>0\} .
$$
Show that $R$ is reflexive and symmetric but not transitive.

#### Solution:

Let $a$ be any real number. Then,
$$
(1+a a)=\left(1+a^{2}\right)>0 \text { shows that }(a, a) \in R \forall a \in S \text {. }
$$
$\therefore \quad R$ is reflexive.

$$
\text { Also, } \begin{aligned}
(a, b) \in R & \Rightarrow(1+a b)>0 \\
& \Rightarrow(1+b a)>0[\because a b=b a] \\
& \Rightarrow(b, a) \in R .
\end{aligned}
$$
$\therefore \quad R$ is symmetric.

In order to show that $R$ is not transitive, consider $(-1,0)$ and $(0,2)$.
Clearly, $(-1,0) \in R$, since $[1+(-1) \times 0]>0$.
And, $(0,2) \in R$, since $[1+0 \times 2]>0$.
But, $(-1,2) \notin R$, since $[1+(-1) \times 2]$ is not greater than 0.

Hence, $R$ is reflexive and symmetric but not transitive.

---

### Example 6:

Let $S$ be the set of all real numbers and let $R$ be a relation in $S$, defined by
$$
R=\{(a, b): a \leq b\} .
$$
Show that $R$ is reflexive and transitive but not symmetric.

#### Solution:

Here, $R$ satisfies the following properties:

**(i) Reflexivity**

Let $a$ be an arbitrary real number.
Then, $a \leq a \Rightarrow(a, a) \in R$.
Thus, $(a, a) \in R \forall a \in S$.
$\therefore \quad R$ is reflexive.

**(ii) Transitivity**

Let $a, b, c$ be real numbers such that $(a, b) \in R$ and $(b, c) \in R$.
Then, $(a, b) \in R$ and $(b, c) \in R$
$$
\begin{aligned}
& \Rightarrow a \leq b \text { and } b \leq c \\
& \Rightarrow a \leq c \\
& \Rightarrow(a, c) \in R .
\end{aligned}
$$
$\therefore \quad R$ is transitive.

**(iii) Nonsymmetry**

Clearly, $(4,5) \in R$ since $4 \leq 5$.
But, $(5,4) \notin R$ since $5 \leq 4$ is not true.
$\therefore \quad R$ is not symmetric.

---

### Example 7:

Let $S$ be the set of all real numbers and let $R$ be a relation in $S$, defined by
$R=\left\{(a, b): a \leq b^{2}\right\}$.
Show that $R$ satisfies none of reflexivity, symmetry and transitivity.

#### Solution:

**(i) Nonreflexivity**

Clearly, $\frac{1}{2}$ is a real number and $\frac{1}{2} \leq\left(\frac{1}{2}\right)^{2}$ is not true.
$\therefore\left(\frac{1}{2}, \frac{1}{2}\right) \notin R$.
Hence, $R$ is not reflexive.

**(ii) Nonsymmetry**

Consider the real numbers $\frac{1}{2}$ and 1.
Clearly, $\frac{1}{2} \leq 1^{2} \Rightarrow\left(\frac{1}{2}, 1\right) \in R$.
But, $1 \leq\left(\frac{1}{2}\right)^{2}$ is not true and so $\left(1, \frac{1}{2}\right) \notin R$.
Thus, $\left(\frac{1}{2}, 1\right) \in R$ but $\left(1, \frac{1}{2}\right) \notin R$.
Hence, $R$ is not symmetric.

**(iii) Nontransitivity**

Consider the real numbers $2,-2$ and 1.
Clearly, $2 \leq(-2)^{2}$ and $-2 \leq(1)^{2}$ but $2 \leq 1^{2}$ is not true.
Thus, $(2,-2) \in R$ and $(-2,1) \in R$, but $(2,1) \notin R$.
Hence, $R$ is not transitive.

---

### Example 8:

Let $S$ be the set of all real numbers and let $R$ be a relation in $S$, defined by $R=\left\{(a, b): a \leq b^{3}\right\}$.
Show that $R$ satisfies none of reflexivity, symmetry and transitivity.

#### Solution:

**(i) Nonreflexivity**

Clearly, $\frac{1}{2}$ is a real number and $\frac{1}{2} \leq\left(\frac{1}{2}\right)^{3}$ is not true.
$\therefore \quad\left(\frac{1}{2}, \frac{1}{2}\right) \notin R$.
Hence, $R$ is not reflexive.

**(ii) Nonsymmetry**

Take the real numbers $\frac{1}{2}$ and 1.
Clearly, $\frac{1}{2} \leq 1^{3}$ is true and therefore, $\left(\frac{1}{2}, 1\right) \in R$.
But, $1 \leq\left(\frac{1}{2}\right)^{3}$ is not true and so $\left(1, \frac{1}{2}\right) \notin R$.
Hence, $R$ is not symmetric.

**(iii) Nontransitivity**

Consider the real numbers $3, \frac{3}{2}$ and $\frac{4}{3}$.
Clearly, $3 \leq\left(\frac{3}{2}\right)^{3}$ and $\frac{3}{2} \leq\left(\frac{4}{3}\right)^{3}$ but $3 \leq\left(\frac{4}{3}\right)^{3}$ is not true.
Thus, $\left(3, \frac{3}{2}\right) \in R$ and $\left(\frac{3}{2}, \frac{4}{3}\right) \in R$, but $\left(3, \frac{4}{3}\right) \notin R$.
Hence, $R$ is not transitive.

Thus, $R$ satisfies none of reflexivity, symmetry and transitivity.

---

### Example 9:

Let $N$ be the set of all natural numbers and let $R$ be a relation in $N$, defined by
$$
R=\{(a, b)\}: a \text { is a factor of } b\} .
$$
Then, show that $R$ is reflexive and transitive but not symmetric.

#### Solution:

Here, $R$ satisfies the following properties:

**(i) Reflexivity**

Let $a$ be an arbitrary element of $N$.
Then, clearly, $a$ is a factor of $a$.
$\therefore \quad(a, a) \in R \forall a \in N$.
So, $R$ is reflexive.

**(ii) Transitivity**

Let $a, b, c \in N$ such that $(a, b) \in R$ and $(b, c) \in R$.
Now, $(a, b) \in R$ and $(b, c) \in R$
$\Rightarrow \quad(a$ is a factor of $b)$ and ( $b$ is a factor of $c$ )
$\Rightarrow \quad b=a d$ and $c=b e$ for some $d, e \in N$
$\Rightarrow c=(a d) e=a(d e) \quad$ [by associative law]
$\Rightarrow a$ is a factor of $c$
$\Rightarrow \quad(a, c) \in R$.
$\therefore \quad(a, b) \in R$ and $(b, c) \in R \Rightarrow(a, c) \in R$.
Hence, $R$ is transitive.

**(iii) Nonsymmetry**

Clearly, 2 and 6 are natural numbers and 2 is a factor of 6 .
$\therefore(2,6) \in R$.
But, 6 is not a factor of 2 .
$\therefore(6,2) \notin R$.
Thus, $(2,6) \in R$ and $(6,2) \notin R$.
Hence, $R$ is not symmetric.

---

### Example 10:

Let $N$ be the set of all natural numbers and let $R$ be a relation in $N$, defined by
$R=\{(a, b): a$ is a multiple of $b\}$.
Show that $R$ is reflexive and transitive but not symmetric.

#### Solution:

Here $R$ satisfies the following properties:

**(i) Reflexivity**

Let $a$ be an arbitrary element of $N$.
Then, $a=(a \times 1)$ shows that $a$ is a multiple of $a$.
$\therefore \quad(a, a) \in R \forall a \in N$.
So, $R$ is reflexive.

**(ii) Transitivity**

Let $a, b, c \in N$ such that $(a, b) \in R$ and $(b, c) \in R$.
Now, $(a, b) \in R$ and $(b, c) \in R$
$\Rightarrow \quad(a$ is a multiple of $b)$ and ( $b$ is a multiple of $c$ )
$\Rightarrow \quad a=b d$ and $b=c e$ for some $d \in N$ and $e \in N$
$\Rightarrow a=(c e) d$
$\Rightarrow a=c(e d)$
$\Rightarrow a$ is a multiple of $c$
$\Rightarrow \quad(a, c) \in R$.
$\therefore \quad(a, b) \in R$ and $(b, c) \in R \Rightarrow(a, c) \in R$.
Hence, $R$ is transitive.

**(iii) Nonsymmetry**

Clearly, 6 and 2 are natural numbers and 6 is a multiple of 2 .
$\therefore(6,2) \in R$.
But, 2 is not a multiple of 6 .
$\therefore(2,6) \notin R$.
Thus, $(6,2) \in R$ and $(2,6) \notin R$.
Hence, $R$ is not symmetric.

---

### Example 11:

Let $X$ be a nonempty set and let $S$ be the collection of all subsets of $X$. Let $R$ be a relation in $S$, defined by
$$
R=\{(A, B): A \subset B\} .
$$
Show that $R$ is transitive but neither reflexive nor symmetric.

#### Solution:

Clearly, $R$ satisfies the following properties:

**(i) Transitivity**

Let $A, B, C \in S$ such that $(A, B) \in R$ and $(B, C) \in R$.
Now, $(A, B) \in R$ and $(B, C) \in R$
$\Rightarrow A \subset B$ and $B \subset C$
$\Rightarrow A \subset C$
$\Rightarrow(A, C) \in R$.
$\therefore \quad R$ is transitive.

**(ii) Nonreflexivity**

Let $A$ be any set in $S$.
Then, $A \not \subset A$ shows that $(A, A) \notin R$.
$\therefore \quad R$ is not reflexive.

**(iii) Nonsymmetry**
$$
\text { Now } \begin{aligned}
(A, B) \in R & \Rightarrow A \subset B \\
& \Rightarrow B \not \subset A \\
& \Rightarrow(B, A) \notin R .
\end{aligned}
$$
$\therefore \quad R$ is not symmetric.

Hence, $R$ is transitive but neither reflexive nor symmetric.

---

### Example 12:

Give an example of a relation which is
-   (i) reflexive and transitive but not symmetric;
-   (ii) symmetric and transitive but not reflexive;
-   (iii) reflexive and symmetric but not transitive;
-   (iv) symmetric but neither reflexive nor transitive;
-   (v) transitive but neither reflexive nor symmetric.

#### Solution:

Let $A=\{1,2,3\}$.
Then, it is easy to verify that the relation:

**(i)** $R_{1}=\{(1,1),(2,2),(3,3),(1,2)\}$
is reflexive and transitive.
$R_{1}$ is not symmetric, since
$$
(1,2) \in R \text { and }(2,1) \notin R .
$$

**(ii)** $R_{2}=\{(1,1),(2,2),(1,2),(2,1)\}$
is symmetric and transitive.
But, $R_{2}$ is not reflexive, since $(3,3) \notin R_{2}$.

**(iii)** $R_{3}=\{(1,1),(2,2),(3,3),(1,2),(2,1),(2,3),(3,2)\}$
is reflexive and symmetric.
But, $R_{3}$ is not transitive, since
$$
(1,2) \in R_{3},(2,3) \in R_{3} \text { but }(1,3) \notin R_{3} .
$$

**(iv)** $R_{4}=\{(2,2),(3,3),(1,2),(2,1)\}$
is symmetric.
But, $R_{4}$ is not reflexive since $(1,1) \notin R_{4}$.
Also, $R_{4}$ is not transitive, as
$$
(1,2) \in R_{4} \text { and }(2,1) \in R_{4} \text { but }(1,1) \in R_{4} .
$$

**(v)** $R_{5}=\{(2,2),(3,3),(1,2)\}$
is transitive.
But, $R_{5}$ is not reflexive, since $(1,1) \notin R$.
And, $R_{5}$ is not symmetric as $(1,2) \in R_{5}$ but $(2,1) \notin R_{5}$.

---

### Example: 13

Let $N$ be the set of all natural numbers and let $R$ be a relation on $N \times N$, defined by
$(a, b) R(c, d) \Leftrightarrow a d=b c$.
Show that $R$ is an equivalence relation.

#### Solution:

Here $R$ satisfies the following properties:

**(i) Reflexivity**

Let $(a, b) \Rightarrow R$. Then,
$(a, b) R(a, b)$, since $a b=b a$
[by commutative law of multiplication on $N$ ].
Thus, $(a, b) R(a, b) \forall(a, b) \in R$.
$\therefore \quad R$ is **reflexive**.

**(ii) Symmetry**

Let $(a, b) R(c, d)$. Then,

$$
\begin{aligned}
(a, b) R(c, d) & \Rightarrow a d=b c \\
& \Rightarrow b c=a d \\
& \Rightarrow c b=d a
\end{aligned}
$$

[by commutativity of multiplication on $N$ ]

$$
\Rightarrow(c, d) R(a, b) .
$$

$\therefore \quad R$ is **symmetric**.

**(iii) Transitivity**

Let $(a, b)$
b) $R(c, d)$ and ( $c$,
d) $R(e, f)$. Then, $a d=b c$ and $c f=d e$
$\Rightarrow a d c f=b c d e$
$\Rightarrow(a f)(c d)=(b e)(c d)$
$\Rightarrow a f=b e$
[by cancellation law]
$\Rightarrow(a, b) R(e, f)$.
$\therefore(a, b) R(c, d)$ and $(c, d) R(e, f) \Rightarrow(a, b) R(e, f)$.
$\therefore \quad R$ is **transitive**.

Thus, $R$ is reflexive, symmetric and transitive.
Hence, $R$ is an **equivalence relation**.

---

### Example: 14

If $R_{1}$ and $R_{2}$ be two equivalence relations on a set $A$, prove that $R_{1} \cap R_{2}$ is also an equivalence relation on $A$.

#### Solution:

Let $R_{1}$ and $R_{2}$ be two equivalence relations on a set $A$.
Then, $R_{1} \subseteq A \times A, \quad R_{2} \subseteq A \times A \Rightarrow \quad\left(R_{1} \cap R_{2}\right) \subseteq A \times A$.
So, ( $R_{1} \cap R_{2}$ ) is a relation on $A$.
This relation on $A$ satisfies the following properties.

**(i) Reflexivity**

$R_{1}$ is reflexive and $R_{2}$ is reflexive
$\Rightarrow(a, a) \in R_{1}$ and $(a, a) \in R_{2}$ for all $a \in A$
$\Rightarrow(a, a) \in R_{1} \cap R_{2}$ for all $a \in A$
$\Rightarrow R_{1} \cap R_{2}$ is **reflexive**.

**(ii) Symmetry**

Let $(a, b)$ be an arbitrary element of $R_{1} \cap R_{2}$. Then,

$$
(a, b) \in R_{1} \cap R_{2}
$$

$\Rightarrow(a, b) \in R_{1}$ and $(a, b) \in R_{2}$
$\Rightarrow(b, a) \in R_{1}$ and $(b, a) \in R_{2}$
[ $\because \quad R_{1}$ is symmetric and $R_{2}$ is symmetric]
$\Rightarrow(b, a) \in R_{1} \cap R_{2}$.
This shows that $R_{1} \cap R_{2}$ is **symmetric**.

**(iii) Transitivity**

$$
\begin{aligned}
& (a, b) \in R_{1} \cap R_{2} \text { and }(b, c) \in R_{1} \cap R_{2} \\
\Rightarrow & (a, b) \in R_{1},(a, b) \in R_{2}, \text { and }(b, c) \in R_{1},(b, c) \in R_{2} \\
\Rightarrow & \left\{(a, b) \in R_{1},(b, c) \in R_{1}\right\}, \text { and }\left\{(a, b) \in R_{2},(b, c) \in R_{2}\right\} \\
\Rightarrow & (a, c) \in R_{1} \text { and }(a, c) \in R_{2}
\end{aligned}
$$

[ $\because \quad R_{1}$ is transitive and $R_{2}$ is transitive]
$\Rightarrow(a, c) \in R_{1} \cap R_{2}$.
This shows that ( $R_{1} \cap R_{2}$ ) is **transitive**.

Thus, $R_{1} \cap R_{2}$ is reflexive, symmetric and transitive.
Hence, $R_{1} \cap R_{2}$ is an **equivalence relation**.

---

### Example: 15

Give an example to show that the union of two equivalence relations on a set $A$ need not be an equivalence relation on $A$.

#### Solution:

Let $R_{1}$ and $R_{2}$ be two relations on a set $A=\{1,2,3\}$, given by

$$
R_{1}=\{(1,1),(2,2),(3,3),(1,2),(2,1)\}
$$

and $R_{2}=\{(1,1),(2,2),(3,3),(1,3),(3,1)\}$.
Then, it is easy to verify that each one of $R_{1}$ and $R_{2}$ is an equivalence relation.

But, $R_{1} \cup R_{2}=\{(1,1),(2,2),(3,3),(1,2),(2,1),(1,3),(3,1)\}$ is not transitive, as
$(3,1) \in R_{1} \cup R_{2}$ and $(1,2) \in R_{1} \cup R_{2}$ but $(3,2) \notin R_{1} \cup R_{2}$.
Hence, ( $R_{1} \cup R_{2}$ ) is not an **equivalence relation**.

---

## Equivalence Classes

Let $R$ be an equivalence relation in a set $A$ and let $a \in A$. Then, the set of all those elements of $A$ which are related to $a$, is called the **equivalence class** determined by $a$ and it is denoted by [ $a$ ].
Thus, $[a]=\{b \in A:(a, b) \in R\}$.

Two equivalence classes are either disjoint or identical.

**An Important Result**
An equivalence relation $R$ on a set $A$ partitions the set into mutually disjoint equivalence classes.

---

### Example: 16

On the set $Z$ of all integers, consider the relation
$R=\{(a, b):(a-b)$ is divisible by 3$\}$.
Show that $R$ is an equivalence relation on $Z$.
Also find the partitioning of $Z$ into mutually disjoint equivalence classes.

#### Solution:

The relation $R$ on $Z$ satisfies the following properties:

**(i) Reflexivity**

Let $a \in Z$.
Then, $(a-a)=0$, which is divisible by 3 .
$\therefore \quad a R a \forall a \in Z$.
So, $R$ is **reflexive**.

**(ii) Symmetry**

Let $a, b \in Z$ such that $a R b$. Then,
$a R b \Rightarrow(a-b)$ is divisible by 3
$\Rightarrow-(a-b)$ is divisible by 3
$\Rightarrow(b-a)$ is divisible by 3
$\Rightarrow b R a$.
$\therefore \quad a R b \Rightarrow b R a \forall a, b \in Z$.
So, $R$ is **symmetric**.

**(iii) Transitivity**

Let $a, b, c \in Z$ such that $a R b$ and $b R c$. Then,
$a R b, b R c \Rightarrow(a-b)$ is divisible by 3
and $(b-c)$ is divisible by 3
$\Rightarrow[(a-b)+(b-c)]$ is divisible by 3
$\Rightarrow(a-c)$ is divisible by 3 .
Thus, $a R b, b R c \Rightarrow a R c \forall a, b, c \in Z$.
$\therefore \quad R$ is an **equivalence relation** on $Z$.

Now, let us consider [0], [1] and [2].
We have:

$$
\begin{aligned}
& \qquad[0]=\{x \in Z: x R 0\} \\
& =\{x \in Z:(x-0) \text { is divisible by } 3\} \\
& =\{\ldots,-6,-3,0,3,6,9, \ldots\} .
\end{aligned}
$$

$\therefore \quad[0]=\{\ldots,-6,-3,0,3,6,9, \ldots\}$.

Similarly,

$$
\begin{aligned}
[1] & =\{x \in Z: x R 1\} \\
\quad & =\{x \in Z:(x-1) \text { is divisible by } 3\} \\
\quad & =\{\ldots,-5,-2,1,4,7,10, \ldots\} .
\end{aligned}
$$

$\therefore \quad[1]=\{\ldots,-5,-2,1,4,7,10, \ldots\}$.

And,

$$
\begin{aligned}
[2] & =\{x \in Z: x R 2\} \\
\quad & =\{x \in Z:(x-2) \text { is divisible by } 3\} \\
\quad & =\{\ldots,-4,-1,2,5,8,11, \ldots\} .
\end{aligned}
$$

$\therefore \quad[2]=\{\ldots,-4,-1,2,5,8,11, \ldots\}$.

Clearly, [0], [1] and [2] are mutually disjoint and $Z=[0] \cup[1] \cup[2]$.

---

### Example: 17

Let $A=\{x \in Z: 0 \leq x \leq 12\}$.
Show that $R=\{(a, b):|a-b|$ is a multiple of 4$\}$ is
(i) reflexive, (ii) symmetric and (iii) transitive.

Find the set of elements related to 1 .
[CBSE 2010]

#### Solution:

Clearly, $A=\{0,1,2,3,4, \ldots, 10,11,12\}$.
Here, $R$ satisfies the following properties.

**(i) reflexive**

Let $a$ be an arbitrary element of $A$. Then, $a-a=0$, which is a multiple of 4 .
$\therefore \quad a R a$ for all $a \in A$.
So, $R$ is **reflexive**.

**(ii) symmetry**

Let $a R b$. Then,

$$
\begin{aligned}
a R b & \Rightarrow|a-b| \text { is a multiple of } 4 \\
& \Rightarrow|-(a-b)| \text { is a multiple of } 4 \\
& \Rightarrow|b-a| \text { is a multiple of } 4 \\
& \Rightarrow b R a .
\end{aligned}
$$

$\therefore \quad R$ is **symmetric**.

**(iii) transitivity**

Let $a R b$ and $b R c$. Then,

$$
a R b, b R c
$$

$\Rightarrow|a-b|$ is a multiple of 4 and $|b-c|$ is a multiple of 4 .
Let $|a-b|=4 k_{1}$ and $|b-c|=4 k_{2}$. Then,

$$
\begin{aligned}
|a-c| & =|(a-b)-(b-c)|=\left|4 k_{1}-4 k_{2}\right| \\
& =\left|4\left(k_{1}-k_{2}\right)\right|=4\left|k_{1}-k_{2}\right|, \text { which is a multiple of } 4 .
\end{aligned}
$$

$\therefore \quad a R b, b R c \Rightarrow a R c$. So, $R$ is **transitive**.

Thus, $R$ is reflexive, symmetric and transitive.
Hence, $R$ is an **equivalence relation**.

$$
\text { Now, } \begin{aligned}
{[1] } & =\{x \in A: x R 1\} \\
& =\{x \in A:|x-1| \text { is a multiple of } 4\} \\
& =\{1,5,9\} .
\end{aligned}
$$

Hence, the required set is $\{1,5,9\}$.

---

### Example: 18

Let $A=\{1,2,3,4,5,6,7,8,9\}$ and $R$ be a relation in $A \times A$, defined by $(a, b) R(c, d) \Leftrightarrow a+d=b+c$ for all $(a, b)$ and $(c, d) \in A \times A$. Prove that $R$ is an equivalence relation. Also obtain the equivalence class determined by $(2,5)$.
[CBSE 2014]

#### Solution:

**(i) Reflexivity**

Let $(a, b) \in A \times A$. Then,

$$
\begin{aligned}
(a, b) \in A \times A & \Rightarrow a, b \in A \\
& \Rightarrow a+b=b+a \\
& \Rightarrow(a, b) R(a, b)
\end{aligned}
$$

$\therefore \quad R$ is **reflexive**.

**(ii) Symmetry**

Let $(a, b) R(c, d)$. Then,

$$
\begin{aligned}
(a, b) R(c, d) & \Rightarrow a+d=b+c \\
& \Rightarrow c+b=d+a \\
& \Rightarrow(c, d) R(a, b)
\end{aligned}
$$

$\therefore \quad R$ is **symmetric**.

**(iii) Transitivity**

Let $(a, b) R(c, d)$ and $(c, d) R(e, f)$. Then,
$(a, b) R(c, d)$ and $(c, d) R(e, f)$
$\Rightarrow \quad a+d=b+c$ and $c+f=d+e$
$\Rightarrow a+d+c+f=b+c+d+e$
$\Rightarrow a+f=b+e$
$\Rightarrow \quad(a, b) R(e, f)$.
$\therefore \quad R$ is **transitive**.

Thus, $R$ is reflexive, symmetric and transitive. Hence, $R$ is an **equivalence relation**.

$$
\begin{aligned}
{[(2,5)] } & =\{(a, b):(2,5) R(a, b)\} \\
& =\{(a, b): 2+b=5+a\}=\{(a, b): b-a=3\} \\
& =\{(1,4),(2,5),(3,6),(4,7),(5,8),(6,9)\} .
\end{aligned}
$$

---
