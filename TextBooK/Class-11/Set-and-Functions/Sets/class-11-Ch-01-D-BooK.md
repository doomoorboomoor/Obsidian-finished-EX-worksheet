## Operations on Sets

### Union of Sets

The **union** of two sets $A$ and $B$, denoted by $A \cup B$, is the set of all those elements which are either in $A$ or in $B$ or in both $A$ and $B$.

Thus, $A \cup B = \{x: x \in A \text{ or } x \in B\}$.
Therefore, $x \in A \cup B \Leftrightarrow x \in A \text{ or } x \in B$.

---

### Example: 1

If $A = \{3, 4, 5, 6\}$ and $B = \{4, 6, 8, 10\}$, find $A \cup B$.

#### Solution:

Clearly, $A \cup B = \{3, 4, 5, 6, 8, 10\}$.

---

### Example: 2

Let $A = \{x: x \text{ is a prime number less than 10}\}$ and $B = \{x: x \in N, x \text{ is a factor of 12}\}$. Find $A \cup B$.

#### Solution:

We have
$$
\begin{array}{ll}
& A = \{2, 3, 5, 7\} \text{ and } B = \{1, 2, 3, 4, 6, 12\}. \\
\therefore & A \cup B = \{2, 3, 5, 7\} \cup \{1, 2, 3, 4, 6, 12\} = \{1, 2, 3, 4, 5, 6, 7, 12\}.
\end{array}
$$

---

### Example: 3

Let $A = \{x: x \text{ is a positive integer}\}$ and let $B = \{x: x \text{ is a negative integer}\}$. Find $A \cup B$.

#### Solution:

Clearly, $A \cup B = \{x: x \text{ is an integer and } x \neq 0\}$.

---

### Example: 4

If $A = \{x: x = 2n+1, n \in Z\}$ and $B = \{x: x = 2n, n \in Z\}$ then find $A \cup B$.

#### Solution:

We have
$$
\begin{aligned}
A \cup B & = \{x: x \text{ is an odd integer}\} \cup \{x: x \text{ is an even integer}\} \\
& = \{x: x \text{ is an integer}\} = Z.
\end{aligned}
$$

---

**Remark:** The union of $n$ sets $A_1, A_2, A_3, \ldots, A_n$ is denoted by
$$
(A_1 \cup A_2 \cup A_3 \cup \ldots \cup A_n) = \bigcup_{i=1}^{n} A_i.
$$

### Intersection of Sets

The **intersection** of two sets $A$ and $B$, denoted by $A \cap B$, is the set of all elements which are common to both $A$ and $B$.

Thus, $A \cap B = \{x: x \in A \text{ and } x \in B\}$.
$$
\begin{array}{ll}
\therefore & x \in A \cap B \Leftrightarrow x \in A \text{ and } x \in B; \\
& x \notin A \cap B \Rightarrow x \notin A \text{ or } x \notin B.
\end{array}
$$

---

### Example: 5

Let $A = \{1, 3, 5, 7, 9\}$ and $B = \{2, 3, 5, 7, 11, 13\}$. Find $A \cap B$.

#### Solution:

We have
$$
A \cap B = \{1, 3, 5, 7, 9\} \cap \{2, 3, 5, 7, 11, 13\} = \{3, 5, 7\}.
$$

---

### Example: 6

If $A = \{x: x \in N, x \text{ is a factor of 12}\}$ and $B = \{x: x \in N, x \text{ is a factor of 18}\}$, find $A \cap B$.

#### Solution:

We have
$$
\begin{array}{ll}
& A = \{x: x \in N, x \text{ is a factor of 12}\} = \{1, 2, 3, 4, 6, 12\}, \\
& B = \{x: x \in N, x \text{ is a factor of 18}\} = \{1, 2, 3, 6, 9, 18\}. \\
\therefore & A \cap B = \{1, 2, 3, 4, 6, 12\} \cap \{1, 2, 3, 6, 9, 18\} = \{1, 2, 3, 6\}.
\end{array}
$$

---

### Example: 7

If $A = \{x: x=3n, n \in Z\}$ and $B = \{x: x=4n, n \in Z\}$ then find $A \cap B$.

#### Solution:

We have
$$
\begin{aligned}
& A = \{x: x \in Z \text{ and } x \text{ is a multiple of 3}\} \\
\text{and } & B = \{x: x \in Z \text{ and } x \text{ is a multiple of 4}\}. \\
\therefore \quad & A \cap B = \{x: x \in Z \text{ and } x \text{ is a multiple of both 3 and 4}\} \\
& = \{x: x \in Z \text{ and } x \text{ is a multiple of 12}\} \\
& = \{x: x = 12n, n \in Z\}.
\end{aligned}
$$
Hence, $A \cap B = \{x: x = 12n, n \in Z\}$.

---

### Example: 8

If $A = (2, 4)$ and $B = [3, 5)$, find $A \cap B$.

#### Solution:

We have
$$
\begin{aligned}
& A = (2, 4) = \{x: x \in R, 2 < x < 4\} \\
& B = [3, 5) = \{x: x \in R, 3 \leq x < 5\}
\end{aligned}
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-19.jpg?height=61&width=895&top_left_y=1520&top_left_x=300)

Clearly, $A \cap B = \{x: x \in R, 3 \leq x < 4\} = [3, 4)$.

---

**Remark:** The intersection of $n$ sets $A_1, A_2, A_3, \ldots, A_n$ is denoted by
$$
(A_1 \cap A_2 \cap A_3 \cap \ldots \cap A_n) = \bigcap_{i=1}^{n} A_i.
$$

### Disjoint Sets

Two sets $A$ and $B$ are said to be **disjoint** if $A \cap B = \phi$.

### Intersecting Sets

Two sets $A$ and $B$ are said to be **intersecting** if $A \cap B \neq \phi$.

---

### Example: 9

If $A = \{1, 3, 5, 7, 9\}$, $B = \{2, 4, 6, 8\}$ and $C = \{2, 3, 5, 7, 11\}$, find $(A \cap B)$ and $(A \cap C)$. What do you conclude?

#### Solution:

We have
$$
A \cap B = \{1, 3, 5, 7, 9\} \cap \{2, 4, 6, 8\} = \phi
$$
and $A \cap C = \{1, 3, 5, 7, 9\} \cap \{2, 3, 5, 7, 11\} = \{3, 5, 7\} \neq \phi$.

Thus, $A$ and $B$ are disjoint sets while $A$ and $C$ are intersecting sets.

---

### Example: 10

Give examples of three sets $A, B, C$ such that $(A \cap B) \neq \phi$, $(B \cap C) \neq \phi$, $(A \cap C) \neq \phi$ and $(A \cap B \cap C) = \phi$.

#### Solution:

Consider the sets $A = \{1, 2\}$, $B = \{2, 3, 4\}$ and $C = \{1, 3, 5\}$.

Then, $(A \cap B) = \{1, 2\} \cap \{2, 3, 4\} = \{2\} \neq \phi$;
$$
\begin{aligned}
& (B \cap C) = \{2, 3, 4\} \cap \{1, 3, 5\} = \{3\} \neq \phi; \\
& (A \cap C) = \{1, 2\} \cap \{1, 3, 5\} = \{1\} \neq \phi; \\
& (A \cap B \cap C) = \{1, 2\} \cap \{2, 3, 4\} \cap \{1, 3, 5\} = \phi.
\end{aligned}
$$
Thus, $A \cap B \neq \phi$, $B \cap C \neq \phi$; $A \cap C \neq \phi$ and $A \cap B \cap C = \phi$.

---

### Example: 11

Give an example of three sets $A, B, C$ such that $A \cap B = A \cap C$ but $B \neq C$.

#### Solution:

Consider the sets $A = \{1, 2, 3\}$, $B = \{3, 4\}$ and $C = \{3, 5, 7\}$.

Then, $A \cap B = \{1, 2, 3\} \cap \{3, 4\} = \{3\}$.
And, $A \cap C = \{1, 2, 3\} \cap \{3, 5, 7\} = \{3\}$.

Thus, $A \cap B = A \cap C$, and clearly, $B \neq C$.

---

### Difference of Sets

For any sets $A$ and $B$, their **difference** ($A-B$) is defined as
$$
(A-B) = \{x: x \in A \text{ and } x \notin B\}.
$$
Thus, $x \in (A-B) \Rightarrow x \in A \text{ and } x \notin B$.

---

### Example: 12

If $A = \{x: x \in N, x \text{ is a factor of 6}\}$ and $B = \{x \in N: x \text{ is a factor of 8}\}$ then find (i) $A \cup B$, (ii) $A \cap B$, (iii) $A-B$, (iv) $B-A$.

#### Solution:

We have
$$
A = \{x: x \in N, x \text{ is a factor of 6}\} = \{1, 2, 3, 6\}
$$
and $B = \{x: x \in N, x \text{ is a factor of 8}\} = \{1, 2, 4, 8\}$.

- (i) $A \cup B = \{1, 2, 3, 6\} \cup \{1, 2, 4, 8\} = \{1, 2, 3, 4, 6, 8\}$.
- (ii) $A \cap B = \{1, 2, 3, 6\} \cap \{1, 2, 4, 8\} = \{1, 2\}$.
- (iii) $A - B = \{1, 2, 3, 6\} - \{1, 2, 4, 8\} = \{3, 6\}$.
- (iv) $B - A = \{1, 2, 4, 8\} - \{1, 2, 3, 6\} = \{4, 8\}$.

---
## Symmetric Difference of Two Sets

The **symmetric difference** of two sets $A$ and $B$, denoted by $A \Delta B$, is defined as
$$
A \Delta B = (A-B) \cup (B-A)
$$

---

### Example: 13

Let $A = \{a, b, c, d\}$ and $B = \{b, d, f, g\}$. Find $A \Delta B$.

#### Solution:

We have
$$
(A-B) = \{a, b, c, d\} - \{b, d, f, g\} = \{a, c\}
$$
$$
\begin{array}{ll}
& (B-A) = \{b, d, f, g\} - \{a, b, c, d\} = \{f, g\} \\
\therefore & A \Delta B = (A-B) \cup (B-A) = \{a, c\} \cup \{f, g\} = \{a, c, f, g\}.
\end{array}
$$

---
## Complement of a Set

Let $U$ be the universal set and let $A \subset U$. Then, the **complement** of $A$, denoted by $A'$ or $(U-A)$, is defined as
$$
A' = \{x \in U: x \notin A\}.
$$
Clearly, $x \in A' \Leftrightarrow x \notin A$.

---

### Example: 14

If $U = \{1, 2, 3, 4, 5, 6, 7, 8\}$ and $A = \{2, 4, 6, 8\}$, find (i) $A'$ (ii) $(A')'$.

#### Solution:

We have
- (i) $A' = U - A = \{1, 2, 3, 4, 5, 6, 7, 8\} - \{2, 4, 6, 8\} = \{1, 3, 5, 7\}$.
- (ii) $(A')' = U - A' = \{1, 2, 3, 4, 5, 6, 7, 8\} - \{1, 3, 5, 7\} = \{2, 4, 6, 8\} = A$.

---

### Example: 15

Let $N$ be the universal set.
- (i) If $A = \{x: x \in N \text{ and } x \text{ is odd}\}$, find $A'$.
- (ii) If $B = \{x: x \in N, x \text{ is divisible by 3 and 5}\}$, find $B'$.

#### Solution:

We have
- (i) $A' = \{x: x \in N \text{ and } x \text{ is not odd}\} = \{x: x \in N \text{ and } x \text{ is even}\}$.
- (ii) $B' = \{x: x \in N, x \text{ is not divisible by 3 or } x \text{ is not divisible by 5}\}$.

---
## Some Results on Complementation

### Example: 16

If $A \subset U$, prove that:
- (i) $U' = \phi$
- (ii) $\phi' = U$
- (iii) $(A')' = A$
- (iv) $A \cup A' = U$
- (v) $A \cap A' = \phi$

#### Solution:

We have
- (i) $U' = \{x \in U: x \notin U\} = \phi$.
- (ii) $\phi' = \{x \in U: x \notin \phi\} = U$.
- (iii) $(A')' = \{x \in U: x \notin A'\} = \{x \in U: x \in A\} = A$.
- (iv)
$$
\begin{aligned}
A \cup A' & = \{x \in U: x \in A \cup A'\} \\
& = \{x \in U: x \in A \text{ or } x \in A'\} \\
& = \{x \in U: x \in A \text{ or } x \notin A\} = U.
\end{aligned}
$$
- (v)
$$
\begin{aligned}
A \cap A' & = \{x \in U: x \in A \cap A'\} \\
& = \{x \in U: x \in A \text{ and } x \in A'\} \\
& = \{x \in U: x \in A \text{ and } x \notin A\} = \phi.
\end{aligned}
$$

---
#	- (iv) $\phi$