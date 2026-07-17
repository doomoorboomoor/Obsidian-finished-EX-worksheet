## Relations

**ORDERED PAIR** Two numbers $a$ and $b$ listed in a specific order and enclosed in parentheses form an ordered pair $(a, b)$.

In the ordered pair $(a, b)$, we call $a$ as **first member** (or first component) and $b$ as **second member** (or second component).

By interchanging the positions of the components, the ordered pair is changed. Thus, $(a, b) \neq (b, a)$.

### Example:

In coordinate geometry, the position of a point in a plane is determined by an ordered pair. In the given figure, the ordered pairs $(2,3)$ and $(3,2)$ represent two different points $A$ and $B$ respectively. Thus, $(2,3) \neq (3,2)$.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Set-and-Functions/Relations/class-11-Ch-02-A-BooK-001.jpg)

---

## Equality of Two Ordered Pairs

We have $(a, b) = (c, d) \Leftrightarrow a=c$ and $b=d$.

### Example 1:

Find $a$ and $b$, when $(a-1, b+5)=(2,3)$.

#### Solution:

Using the definition of equality of two ordered pairs, we have:

$$
(a-1, b+5)=(2,3) \Rightarrow a-1=2 \text{ and } b+5=3 \\
\Rightarrow a=3 \text{ and } b=-2.
$$

Hence, $a=3$ and $b=-2$.

---

### Example 2:

Find $a$ and $b$, when $(2a+b, 11)=(1, a-3b)$.

#### Solution:

Using the definition of equality of two ordered pairs, we have:

$$
\begin{align*}
(2a+b, 11)=(1, a-3b) \\
\Rightarrow \left\{\begin{array}{l}
2a+b=1 \quad \dots(\text{i}) \\
a-3b=11 \quad \dots(\text{ii})
\end{array}\right.
\end{align*}
$$

On solving (i) and (ii), we get $a=2$ and $b=-3$.

Hence, $a=2$ and $b=-3$.

---

### Example 3:

If $(\frac{x}{3}+1, y-\frac{2}{3})=(\frac{5}{3}, \frac{1}{3})$, find the values of $x$ and $y$.

#### Solution:

Since the given two ordered pairs are equal, we have:

$$
\frac{x}{3}+1=\frac{5}{3} \Rightarrow \frac{x}{3}=(\frac{5}{3}-1)=\frac{2}{3} \Rightarrow \frac{x}{3}=\frac{2}{3} \Rightarrow x=2
$$

and

$$
y-\frac{2}{3}=\frac{1}{3} \Rightarrow y=(\frac{1}{3}+\frac{2}{3})=\frac{3}{3}=1 \Rightarrow y=1.
$$

Hence, $x=2$ and $y=1$.

---

### Example 4:

Express $\{(x, y): x^{2}+y^{2}=25, \text{ where } x, y \in W\}$ as a set of ordered pairs.

#### Solution:

It is easy to verify that each of the following ordered pairs of whole numbers satisfies the given relation $x^{2}+y^{2}=25$: $(5,0), (0,5), (3,4)$ and $(4,3)$.

Hence, the set of required ordered pairs is:

$$
\{(5,0), (0,5), (3,4), (4,3)\}
$$

---

## Cartesian Product of Two Sets

Let $A$ and $B$ be two nonempty sets. Then, the **Cartesian product** of $A$ and $B$ is the set denoted by $(A \times B)$, consisting of all ordered pairs $(a, b)$ such that $a \in A$ and $b \in B$.

$$
\therefore A \times B = \{(a, b): a \in A \text{ and } b \in B\}
$$

If $A=\phi$ or $B=\phi$, we define $A \times B = \phi$.

**REMARKS**
- If $n(A)=p$ and $n(B)=q$ then $n(A \times B)=pq$ and $n(B \times A)=pq$.
- If at least one of $A$ and $B$ is infinite then $(A \times B)$ is infinite and $(B \times A)$ is infinite.

---

## Solved Examples

### Example 1:

If $A=\{1,3,5\}$ and $B=\{2,3\}$ then find:
(i) $A \times B$
(ii) $B \times A$
(iii) $(A \times B) \cap (B \times A)$

#### Solution:

We have:

(i) $A \times B = \{1,3,5\} \times \{2,3\}$
$$
= \{(1,2), (1,3), (3,2), (3,3), (5,2), (5,3)\}
$$

(ii) $B \times A = \{2,3\} \times \{1,3,5\}$
$$
= \{(2,1), (2,3), (2,5), (3,1), (3,3), (3,5)\}
$$

(iii) $(A \times B) \cap (B \times A) = \{(3,3)\}$.

---

### Example 2:

If $A=\{1,2,3\}, B=\{3,4\}$ and $C=\{4,5,6\}$ then find:
(i) $A \times (B \cap C)$
(ii) $(A \times B) \cap (A \times C)$
(iii) $A \times (B \cup C)$
(iv) $(A \times B) \cup (A \times C)$

#### Solution:

We have:

(i) $B \cap C = \{3,4\} \cap \{4,5,6\} = \{4\}$.
$$
\therefore A \times (B \cap C) = \{1,2,3\} \times \{4\} = \{(1,4), (2,4), (3,4)\}
$$

(ii)
$$
\begin{aligned}
(A \times B) &= \{1,2,3\} \times \{3,4\} \\
&= \{(1,3), (1,4), (2,3), (2,4), (3,3), (3,4)\}. \\
(A \times C) &= \{1,2,3\} \times \{4,5,6\} \\
&= \{(1,4), (1,5), (1,6), (2,4), (2,5), (2,6), (3,4), (3,5), (3,6)\}. \\
\therefore (A \times B) &\cap (A \times C) = \{(1,4), (2,4), (3,4)\}.
\end{aligned}
$$

(iii) $B \cup C = \{3,4\} \cup \{4,5,6\} = \{3,4,5,6\}$.
$$
\begin{aligned}
\therefore A \times (B \cup C) &= \{1,2,3\} \times \{3,4,5,6\} \\
&= \{(1,3), (1,4), (1,5), (1,6), (2,3), (2,4), (2,5), (2,6), (3,3), (3,4), (3,5), (3,6)\}.
\end{aligned}
$$

(iv) Also, from (ii), we get:
$$
\begin{aligned}
(A \times B) \cup (A \times C) = \{&(1,3), (1,4), (1,5), (1,6), (2,3), (2,4), (2,5), \\
&(2,6), (3,3), (3,4), (3,5), (3,6)\}.
\end{aligned}
$$

---

### Example 3:

Let $A = \{x \in N: x^{2}-5x+6=0\}$, $B = \{x \in W: 0 \leq x < 2\}$ and $C = \{x \in N: x<3\}$. Verify that:
(i) $A \times (B \cup C) = (A \times B) \cup (A \times C)$
(ii) $A \times (B \cap C) = (A \times B) \cap (A \times C)$

#### Solution:

We have:
$A = \{x \in N: x^{2}-5x+6=0\} = \{x \in N: (x-2)(x-3)=0\} = \{2,3\}$;
$B = \{x \in W: 0 \leq x < 2\} = \{0,1\}$ and $C = \{x \in N: x<3\} = \{1,2\}$.
$\therefore A=\{2,3\}, B=\{0,1\}$ and $C=\{1,2\}$.

(i) $(B \cup C) = \{0,1\} \cup \{1,2\} = \{0,1,2\}$.
$$
\begin{aligned}
\therefore A \times (B \cup C) &= \{2,3\} \times \{0,1,2\} \\
&= \{(2,0), (2,1), (2,2), (3,0), (3,1), (3,2)\}.
\end{aligned}
$$
Now, $(A \times B) = \{2,3\} \times \{0,1\} = \{(2,0), (2,1), (3,0), (3,1)\}$
and $(A \times C) = \{2,3\} \times \{1,2\} = \{(2,1), (2,2), (3,1), (3,2)\}$.
$$
\therefore (A \times B) \cup (A \times C) = \{(2,0), (2,1), (2,2), (3,0), (3,1), (3,2)\}.
$$
Hence, $A \times (B \cup C) = (A \times B) \cup (A \times C)$.

(ii) $(B \cap C) = \{0,1\} \cap \{1,2\} = \{1\}$.
$$
\therefore A \times (B \cap C) = \{2,3\} \times \{1\} = \{(2,1), (3,1)\}.
$$
And,
$$
\begin{aligned}
(A \times B) \cap (A \times C) &= \{(2,0), (2,1), (3,0), (3,1)\} \cap \{(2,1), (2,2), (3,1), (3,2)\} \\
&= \{(2,1), (3,1)\}.
\end{aligned}
$$
Hence, $A \times (B \cap C) = (A \times B) \cap (A \times C)$.

---

### Example 4:

If $(A \times B) = \{(3,2), (3,4), (5,2), (5,4)\}$, find $A$ and $B$.

#### Solution:

Clearly, we have:
$A$ = set of all first coordinates of the elements of $(A \times B) = \{3,5\}$.
$B$ = set of all second coordinates of the elements of $(A \times B) = \{2,4\}$.
Thus, $A = \{3,5\}$ and $B = \{2,4\}$.

---

### Example 5:

$A$ and $B$ are two sets given in such a way that $(A \times B)$ contains 6 elements. If three elements of $(A \times B)$ be $(1,3), (2,5)$ and $(3,3)$, find its remaining elements.

#### Solution:

Since $(1,3), (2,5)$ and $(3,3)$ are in $(A \times B)$, it follows that $1,2,3$ are elements of $A$ and $3,5$ are elements of $B$.

$$
\begin{aligned}
\therefore (A \times B) &= \{1,2,3\} \times \{3,5\} \\
&= \{(1,3), (1,5), (2,3), (2,5), (3,3), (3,5)\}.
\end{aligned}
$$

Hence, the remaining elements of $(A \times B)$ are $(1,5), (2,3)$ and $(3,5)$.

---

### Example 6:

If $A=\{a,b\}$, find $(A \times A)$.

#### Solution:

We have:
$$
\begin{aligned}
(A \times A) &= \{a,b\} \times \{a,b\} \\
&= \{(a,a), (a,b), (b,a), (b,b)\}.
\end{aligned}
$$

---

### Example 7:

Let $R$ be the set of all real numbers. What does $(R \times R)$ represent?

#### Solution:

We have $(R \times R) = \{(x,y): x,y \in R\}$.
Thus, $(R \times R)$ represents the set of all coordinates of points in two-dimensional space.

---

### Example 8:

If $(A \times A)$ has 9 elements two of which are $(-1,0)$ and $(0,1)$, find the set $A$ and the remaining elements of $(A \times A)$.

#### Solution:

Clearly, $-1,0$ and $1$ are elements of $A$.
$\therefore A = \{-1, 0, 1\}$.

$$
\begin{aligned}
A \times A &= \{-1,0,1\} \times \{-1,0,1\} \\
&= \{(-1,-1), (-1,0), (-1,1), (0,-1), (0,0), (0,1), (1,-1), (1,0), (1,1)\}.
\end{aligned}
$$

Hence, the remaining elements of $(A \times A)$ are:
$(-1,-1), (-1,1), (0,-1), (0,0), (1,-1), (1,0), (1,1)$.

---

## Graphical Representation of A × B and B × A

Let $X'OX$ and $YOY'$ be the $x$-axis and $y$-axis respectively, drawn on a graph paper.

Let $A = \{-1, 2, 4\}$ and $B = \{1, 3\}$. Then,
$$
A \times B = \{(-1,1), (-1,3), (2,1), (2,3), (4,1), (4,3)\}
$$
These points may be plotted on the graph paper, as shown below:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Set-and-Functions/Relations/class-11-Ch-02-A-BooK-002.jpg)

This is the graphical representation of $A \times B$.

For $B \times A$, we take $B = \{1, 3\}$ along the $x$-axis and $A = \{-1, 2, 4\}$ along the $y$-axis and plot the points $(1,-1), (1,2), (1,4), (3,-1), (3,2), (3,4)$ on the graph paper.

---

## Arrow Diagram of A × B

Let $A = \{-1, 2, 4\}$ and $B = \{1, 3\}$. Then,
$$
A \times B = \{(-1,1), (-1,3), (2,1), (2,3), (4,1), (4,3)\}
$$
Then, $A \times B$ may be represented by arrow diagram, as shown below:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Set-and-Functions/Relations/class-11-Ch-02-A-BooK-003.jpg)

---

## Arrow Diagram of B × A

Again, $B \times A = \{(1,-1), (1,2), (1,4), (3,-1), (3,2), (3,4)\}$.
We may exhibit $B \times A$ by arrow diagram, as shown below:

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Set-and-Functions/Relations/class-11-Ch-02-A-BooK-004.jpg)

---

## Ordered Triplet

**ORDERED TRIPLET** Three numbers $a, b$ and $c$ listed in a specific order and enclosed in parentheses form an ordered triplet $(a, b, c)$.

Thus, $(1,2,3) \neq (2,1,3) \neq (3,2,1)$, etc.

For any nonempty set $A$, we define:
$$
(A \times A \times A) = \{(a, b, c): a, b, c \in A\}
$$

### Example 9:

If $A=\{1,2\}$, find $(A \times A \times A)$.

#### Solution:

$A \times A = \{1,2\} \times \{1,2\} = \{(1,1), (1,2), (2,1), (2,2)\}$.
$$
\begin{aligned}
\therefore A \times A \times A &= (A \times A) \times A \\
&= \{(1,1), (1,2), (2,1), (2,2)\} \times \{1,2\} \\
&= \{(1,1,1), (1,1,2), (1,2,1), (1,2,2), (2,1,1), (2,1,2), (2,2,1), (2,2,2)\}.
\end{aligned}
$$

---

### Example 10:

Let $R$ be the set of all real numbers. What does $(R \times R \times R)$ represent?

#### Solution:

$(R \times R \times R) = \{(a, b, c): a, b, c \in R\}$.
Thus, $(R \times R \times R)$ represents the set of all points in three-dimensional space.

**REMARK**
For any nonempty sets $A, B$ and $C$, we always have
$$
(A \times B) \times C = A \times (B \times C) = A \times B \times C
$$

---

### Example 11:

Let $A=\{1,2\}, B=\{3,4\}$ and $C=\{4,5\}$. Verify that $(A \times B) \times C = A \times (B \times C)$ and hence find $A \times B \times C$.

#### Solution:

We have:
$$
\begin{aligned}
A \times B = \{1,2\} \times \{3,4\} = \{(1,3), (1,4), (2,3), (2,4)\} \\
\Rightarrow (A \times B) \times C = \{(1,3), (1,4), (2,3), (2,4)\} \times \{4,5\} \\
= \{(1,3,4), (1,3,5), (1,4,4), (1,4,5), (2,3,4), (2,3,5), (2,4,4), (2,4,5)\}.
\end{aligned}
$$
Again,
$$
\begin{aligned}
B \times C = \{3,4\} \times \{4,5\} = \{(3,4), (3,5), (4,4), (4,5)\} \\
\Rightarrow A \times (B \times C) = \{1,2\} \times \{(3,4), (3,5), (4,4), (4,5)\} \\
= \{(1,3,4), (1,3,5), (1,4,4), (1,4,5), (2,3,4), (2,3,5), (2,4,4), (2,4,5)\}.
\end{aligned}
$$
$\therefore (A \times B) \times C = A \times (B \times C) = A \times B \times C$.

Hence, $A \times B \times C = \{(1,3,4), (1,3,5), (1,4,4), (1,4,5), (2,3,4), (2,3,5), (2,4,4), (2,4,5)\}$.

---

