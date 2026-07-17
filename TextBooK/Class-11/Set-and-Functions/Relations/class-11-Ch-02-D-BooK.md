## Binary Relation on a Set

Let $A$ be a nonempty set. Then, every subset of ($A \times A$) is called a **binary relation** or simply a **relation** on $A$.

**Remarks:**

1.  Since $\phi \subset A \times A$, so $\phi$ is a relation on $A$, called the **empty** or **void relation** on $A$.
2.  Since $A \times A \subseteq A \times A$, so ($A \times A$) is a relation on $A$, called the **universal relation** on $A$.
3.  Let $I_{A}=\{(a, a): a \in A\}$. Then, clearly, $I_{A} \subseteq(A \times A)$ and therefore, it is a relation on $A$, called the **identity relation** on $A$.

---

### Example: 1

Let $A=\{1,2,3\}$ and $R=\{(1,2),(2,2),(3,1),(3,2)\}$. Show that $R$ is a binary relation on $A$. Find its domain and range.

#### Solution:

Given $R=\{(1,2),(2,2),(3,1),(3,2)\}$.

Clearly, $R \subset A \times A$ and so $R$ is a relation on $A$.

**Dom(R)** = set of first coordinates of elements of $R=\{1,2,3\}$.

**Range(R)** = set of second coordinates of elements of $R=\{1,2\}$.

Hence, $\text{dom}(R)=\{1,2,3\}$ and $\text{range}(R)=\{1,2\}$.

---

### Example: 2

Let $N$ be the set of all natural numbers. Let $R=\{(a, b): a, b \in N \text{ and } 2a+b=10\}$. Show that $R$ is a binary relation on $N$. Find its domain, range and co-domain.

#### Solution:

Here $R=\{(a, b): a, b \in N \text{ and } 2a+b=10\}$.

Now, $2a+b=10 \Rightarrow b=(10-2a)$.

-   $a=1 \Rightarrow b=8$
-   $a=2 \Rightarrow b=6$
-   $a=3 \Rightarrow b=4$
-   $a=4 \Rightarrow b=2$

$\therefore R=\{(1,8),(2,6),(3,4),(4,2)\}$.

Since $R \subset N \times N$, so $R$ is a binary relation on $N$.

**Dom(R)** = set of 1st coordinates of elements of $R = \{1,2,3,4\}$.

**Range(R)** = set of 2nd coordinates of elements of $R = \{8,6,4,2\}$.

**Co-domain of R** = $N$.

---

## Inverse Relation

Let $R$ be a binary relation on a set $A$. Then, the **inverse** of $R$, denoted by $R^{-1}$, is a binary relation on $A$, defined by:
$$
R^{-1}=\{(b, a):(a, b) \in R\}
$$

Clearly, $(a, b) \in R \Leftrightarrow(b, a) \in R^{-1}$.
Also, $\text{dom}(R)=\text{range}(R^{-1})$ and $\text{range}(R)=\text{dom}(R^{-1})$.

---

### Example: 3

Let $A$ be the set of first ten natural numbers. Let $R$ be a binary relation on $A$, defined by
$$
R=\{(a, b): a, b \in A \text{ and } a+2b=10\}
$$
Express $R$ and $R^{-1}$ as sets of ordered pairs.
Show that (i) $\text{dom}(R) = \text{range}(R^{-1})$ and (ii) $\text{range}(R) = \text{dom}(R^{-1})$.

#### Solution:

Given $a+2b=10 \Rightarrow b=\frac{(10-a)}{2}$.

-   $a=2 \Rightarrow b=4$
-   $a=4 \Rightarrow b=3$
-   $a=6 \Rightarrow b=2$
-   $a=8 \Rightarrow b=1$

$\therefore R=\{(2,4),(4,3),(6,2),(8,1)\}$
$\Rightarrow R^{-1}=\{(4,2),(3,4),(2,6),(1,8)\}$.

Therefore:
1.  $\text{dom}(R)=\{2,4,6,8\}=\text{range}(R^{-1})$.
2.  $\text{range}(R)=\{4,3,2,1\}=\text{dom}(R^{-1})$.

---

## Various Types of Relations

Let $A$ be a nonempty set. Then, a relation $R$ on $A$ is said to be:

1.  **Reflexive**, if $(a, a) \in R$ for all $a \in A$, i.e., $a R a$ for all $a \in A$.
2.  **Symmetric**, if $(a, b) \in R \Rightarrow(b, a) \in R$ for all $a, b \in A$, i.e., $a R b \Rightarrow b R a$ for all $a, b \in A$.
3.  **Transitive**, if $(a, b) \in R$ and $(b, c) \in R \Rightarrow(a, c) \in R$ for all $a, b, c \in A$, i.e., $a R b, b R c \Rightarrow a R c$ for all $a, b, c \in A$.

---

## Equivalence Relation

A relation which is **reflexive**, **symmetric** and **transitive** is called an **equivalence relation**.

---

### Example: 4

Let $R$ be a relation on the set $Q$ of all rationals defined by $R=\{(a, b): a, b \in Q \text{ and } a-b \in Z\}$. Show that $R$ is an equivalence relation.

#### Solution:

Given: $R=\{(a, b): a, b \in Q \text{ and } a-b \in Z\}$.

1.  **Reflexivity:** Let $a \in Q$. Then, $a-a=0 \in Z$.
    $\therefore (a, a) \in R$ for all $a \in Q$.
    So, $R$ is **reflexive**.

2.  **Symmetry:** Let $(a, b) \in R$. Then $(a-b) \in Z$, i.e., $(a-b)$ is an integer.
    $\Rightarrow -(a-b)$ is an integer.
    $\Rightarrow (b-a)$ is an integer.
    $\Rightarrow (b, a) \in R$.
    Thus, $(a, b) \in R \Rightarrow (b, a) \in R$.
    $\therefore R$ is **symmetric**.

3.  **Transitivity:** Let $(a, b) \in R$ and $(b, c) \in R$.
    $\Rightarrow (a-b)$ is an integer and $(b-c)$ is an integer.
    $\Rightarrow \{(a-b)+(b-c)\}$ is an integer.
    $\Rightarrow (a-c)$ is an integer.
    $\Rightarrow (a, c) \in R$.
    Thus, $(a, b) \in R$ and $(b, c) \in R \Rightarrow (a, c) \in R$.
    $\therefore R$ is **transitive**.

Thus, $R$ is reflexive, symmetric and transitive. So, $R$ is an **equivalence relation**.

---

### Example: 5

Let $m$ be a given fixed positive integer. Let $R=\{(a, b): a, b \in Z \text{ and } (a-b) \text{ is divisible by } m\}$. Show that $R$ is an equivalence relation on $Z$.

#### Solution:

Given: $R=\{(a, b): a, b \in Z \text{ and } (a-b) \text{ is divisible by } m\}$.

1.  **Reflexivity:** Let $a \in Z$. Then, $a-a=0$, which is divisible by $m$.
    $\therefore (a, a) \in R$ for all $a \in Z$.
    So, $R$ is **reflexive**.

2.  **Symmetry:** Let $(a, b) \in R$. Then, $(a-b)$ is divisible by $m$.
    $\Rightarrow -(a-b)$ is divisible by $m$.
    $\Rightarrow (b-a)$ is divisible by $m$.
    $\Rightarrow (b, a) \in R$.
    Thus, $(a, b) \in R \Rightarrow (b, a) \in R$.
    So, $R$ is **symmetric**.

3.  **Transitivity:** Let $(a, b) \in R$ and $(b, c) \in R$.
    $\Rightarrow (a-b)$ is divisible by $m$ and $(b-c)$ is divisible by $m$.
    $\Rightarrow \{(a-b)+(b-c)\}$ is divisible by $m$.
    $\Rightarrow (a-c)$ is divisible by $m$.
    $\Rightarrow (a, c) \in R$.
    $\therefore (a, b) \in R$ and $(b, c) \in R \Rightarrow (a, c) \in R$.
    So, $R$ is **transitive**.

Thus, $R$ is reflexive, symmetric and transitive. Hence, $R$ is an **equivalence relation** on $Z$.

---

### Example: 6

Show that the relation 'is parallel to' on the set $S$ of all straight lines in a plane is an equivalence relation.

#### Solution:

Let $S$ be the set of all straight lines in a plane. Then, the relation, 'is parallel to' on $S$ is:

1.  **Reflexive**, since every line is parallel to itself, i.e., $L \| L$ for all $L$ in $S$.
2.  **Symmetric**, since $L\|M \Rightarrow M\| L$ for all $L, M \in S$.
3.  **Transitive**, since for all $L, M, N$ in $S$, we have $L \| M$ and $M\|N \Rightarrow L\| N$.

Thus, the given relation is reflexive, symmetric and transitive. Hence, it is an **equivalence relation** on $S$.

---

### Example: 7

Show that the relation 'is congruent to' on the set of all triangles in a plane is an equivalence relation.

#### Solution:

Let $S$ be the set of all triangles in a plane. Then, the congruence relation on $S$ is:

1.  **Reflexive**, since $\triangle \cong \triangle$ for every $\triangle \in S$.
2.  **Symmetric**, since $\Delta_{1} \cong \Delta_{2} \Rightarrow \Delta_{2} \cong \Delta_{1}$ for all $\Delta_{1}, \Delta_{2} \in S$.
3.  **Transitive**, since $\Delta_{1} \cong \Delta_{2}$ and $\Delta_{2} \cong \Delta_{3} \Rightarrow \Delta_{1} \cong \Delta_{3}$ for all $\triangle_{1}, \triangle_{2}, \triangle_{3} \in S$.

Hence, the given relation is an **equivalence relation**.

---

### Example: 8

Let $R=\{(a, b): a, b \in N \text{ and } a=b^{2}\}$. Show that $R$ satisfies none of reflexivity, symmetry and transitivity.

#### Solution:

1.  **Not Reflexive:** $R$ is not reflexive, since $2 \neq 2^{2}$ and therefore $(2,2) \notin R$.
2.  **Not Symmetric:** Since $4=2^{2}$, so $(4,2) \in R$. But, $2 \neq 4^{2}$. So, $(2,4) \notin R$. Thus, $(4,2) \in R$ but $(2,4) \notin R$.
3.  **Not Transitive:** Since $16=4^{2}$, so $(16,4) \in R$. Also, $4=2^{2}$, so $(4,2) \in R$. But, $16 \neq 2^{2} \Rightarrow(16,2) \notin R$. Thus, $(16,4) \in R$ and $(4,2) \in R$, but $(16,2) \notin R$.

Hence, $R$ satisfies none of reflexivity, symmetry and transitivity.

---

### Example: 9

Let $S$ be the set of all real numbers and let $R$ be a binary relation on $S$ defined by $(a, b) \in R \Leftrightarrow 1+ab>0$ for all $a, b \in S$. Show that $R$ is reflexive as well as symmetric. Give an example to show that $R$ is not transitive.

#### Solution:

1.  **Reflexivity:** Let $a$ be an arbitrary real number. Then, $(1+a^{2})>0 \Rightarrow(a, a) \in R$ for every $a \in S$.
    $\therefore R$ is **reflexive**.

2.  **Symmetry:** Let $(a, b) \in R$. Then,
    $(a, b) \in R \Rightarrow 1+ab>0$
    $\Rightarrow 1+ba>0$
    $\Rightarrow (b, a) \in R$.
    $\therefore (a, b) \in R \Rightarrow (b, a) \in R$.
    So, $R$ is **symmetric**.

3.  **Transitivity:** In order to show that $R$ is not transitive, consider the real numbers $(-\frac{2}{3}), 1$ and $2$.
    Now, $(-\frac{2}{3}, 1) \in R$, since $\{1+(-\frac{2}{3}) \times 1\} = (1-\frac{2}{3})=\frac{1}{3}>0$.
    And, $(1,2) \in R$, since $\{1+(1 \times 2)\}=3>0$.
    But, $(-\frac{2}{3}, 2) \notin R$, since $\{1+(-\frac{2}{3}) \times 2\}=(1-\frac{4}{3})=-\frac{1}{3}<0$.
    Thus, $(-\frac{2}{3}, 1) \in R$, $(1,2) \in R$ but $(-\frac{2}{3}, 2) \notin R$.
    This shows that $R$ is **not transitive**.

---

### Example: 10

Let $R$ be a relation on $N \times N$, defined by
$$
(a, b) R (c, d) \Leftrightarrow a+d=b+c \text{ for all } (a, b), (c, d) \in N \times N.
$$
Show that $R$ is an equivalence relation.

#### Solution:

Here $R$ is a relation on $N \times N$, defined by $(a, b) R (c, d) \Leftrightarrow a+d=b+c$ for all $(a, b), (c, d) \in N \times N$. We shall show that $R$ satisfies the following properties.

-   **Reflexivity:**
    We know that $a+b=b+a$ for all $a, b \in N$.
    $\therefore (a, b) R (a, b)$ for all $(a, b) \in (N \times N)$.
    So, $R$ is **reflexive**.

-   **Symmetry:**
    Let $(a, b) R (c, d)$. Then,
    $(a, b) R (c, d) \Rightarrow a+d=b+c$
    $\Rightarrow c+b=d+a$
    $\Rightarrow (c, d) R (a, b)$.
    $\therefore (a, b) R (c, d) \Rightarrow (c, d) R (a, b)$ for all $(a, b),(c, d) \in N \times N$.
    This shows that $R$ is **symmetric**.

-   **Transitivity:**
    Let $(a, b) R (c, d)$ and $(c, d) R (e, f)$. Then,
    $(a, b) R (c, d) \text{ and } (c, d) R (e, f)$
    $\Rightarrow a+d=b+c \text{ and } c+f=d+e$
    $\Rightarrow a+d+c+f=b+c+d+e$
    $\Rightarrow a+f=b+e$
    $\Rightarrow (a, b) R (e, f)$.
    Thus, $(a, b) R (c, d)$ and $(c, d) R (e, f) \Rightarrow (a, b) R (e, f)$.
    This shows that $R$ is **transitive**.

$\therefore R$ is reflexive, symmetric and transitive. Hence, $R$ is an **equivalence relation** on $N \times N$.

---

