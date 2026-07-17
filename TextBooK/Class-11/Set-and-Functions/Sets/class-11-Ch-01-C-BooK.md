## Subsets

**Subset**: A set $A$ is said to be a subset of set $B$ if every element of $A$ is also an element of $B$, and we write, $A \subseteq B$.

**Superset**: If $A \subseteq B$, then $B$ is called a superset of $A$, and we write, $B \supseteq A$.

**Proper Subset**: If $A \subseteq B$ and $A \neq B$ then $A$ is called a proper subset of $B$ and we write, $A \subset B$.

**Remark**: If there exists even a single element in $A$ which is *not* in $B$, then $A$ is not a subset of $B$, and we write, $A \not\subset B$.

---

### Example: 1

Let $A=\{2,3,5\}$ and $B=\{2,3,5,7,9\}$.
Then, every element of $A$ is an element of $B$.
Therefore, $A \subseteq B$ but $A \neq B$.
Hence, $A$ is a proper subset of set $B$, i.e., $A \subset B$.

---

### Example: 2

Let $A=\{1,2\}$ and $B=\{2,3,5\}$.
Then, $1 \in A$ but $1 \notin B$.
Therefore, $A \nsubseteq B$.
Again, $3 \in B$ but $3 \notin A$.
Therefore, $B \nsubseteq A$.
Thus, $A \nsubseteq B$ and $B \nsubseteq A$.

---

### Example: 3

Clearly, $N \subset W \subset Z \subset Q \subset R$.
But, $0 \in W$ and $0 \notin N$.
Therefore, $W \nsubseteq N$.

---

### Example: 4

Let $A=\{1,\{2,3\}, 4\}$.
Then, which of the following statements is true?
1. $\{2,3\} \in A$
2. $\{2,3\} \subset A$

Rectify the wrong statement.

#### Solution:

Clearly, $A$ is a set containing three elements, namely $1$, $\{2,3\}$ and $4$.
1. $\{2,3\} \in A$ is a **true** statement.
2. $\{2,3\} \subset A$ is **wrong**.

On rectifying this statement, we get $\{\{2,3\}\} \subset A$ as a true statement.

---

## Some Results on Subsets

### Theorem 1
**Every set is a subset of itself.**

#### Proof:
Let $A$ be any set.
Then, each element of $A$ is in $A$.
Therefore, $A \subseteq A$.
Hence, every set is a subset of itself.

### Theorem 2
**The empty set is a subset of every set.**

#### Proof:
Let $A$ be any set and $\phi$ be the empty set.
Since $\phi$ contains no element at all, so there is no element of $\phi$ which is not contained in $A$.
Hence, $\phi \subset A$.

### Theorem 3
**The total number of subsets of a set containing $n$ elements is $2^{n}$.**

#### Proof:
Let $A$ be a finite set containing $n$ elements. Then,

- number of subsets of $A$ each containing no element $=1={ }^{n} C_{0}$.
- number of subsets of $A$ each containing 1 element $={ }^{n} C_{1}$.
- number of subsets of $A$ each containing 2 elements $={ }^{n} C_{2}$.
...
- number of subsets of $A$ each containing $n$ elements $={ }^{n} C_{n}$.

Therefore, the total number of subsets of $A$ is:

$$
\begin{aligned}
& =\left({ }^{n} C_{0}+{ }^{n} C_{1}+{ }^{n} C_{2}+\ldots+{ }^{n} C_{n}\right) \\
& =(1+1)^{n}=2^{n}
\end{aligned}
$$

---

## Universal Set

If there are some sets under consideration then there happens to be a set which is a superset of each one of the given sets. Such a set is known as the **universal set** for those sets. We shall denote a universal set by $U$.

### Example: 1

Let $A=\{1,2,3\}$, $B=\{2,3,4,5\}$ and $C=\{6,7\}$.
If we consider the set $U=\{1,2,3,4,5,6,7\}$ then clearly, $U$ is a superset of each of the given sets.
Hence, $U$ is the universal set.

---

### Example: 2

When we discuss sets of lines, triangles or circles in two-dimensional geometry, the plane in which these lines, triangles or circles lie, is the universal set.

---

## Subsets of the Set $R$ of all Real Numbers

1.  $N=\{1,2,3,4,5, \ldots\}$ is the set of all **natural numbers**.
2.  $W=\{0,1,2,3,4,5, \ldots\}$ is the set of all **whole numbers**.
3.  $Z=\{\ldots,-4,-3,-2,-1,0,1,2,3,4, \ldots\}$ is the set of all **integers**.
    - $Z^{+}=\{1,2,3,4,5, \ldots\}$ is the set of all positive integers.
    - $Z^{-}=\{-1,-2,-3,-4, \ldots\}$ is the set of all negative integers.
    - Sometimes, we denote the set of all integers by $I$.
4.  $Q=\left\{x: x=\frac{p}{q}\right.$, where, $p, q \in Z$ and $\left.q \neq 0\right\}$ is the set of all **rational numbers**.
    - The set of all positive rational numbers is denoted by $Q^{+}$.
5.  $T=\{x: x \in R$ and $x \notin Q\}$ is the set of all **irrational numbers**.

---

## Intervals as Subsets of $R$

Let $a, b \in R$ and $a<b$. Then, we define:

1.  **Closed Interval**: $[a, b]=\{x \in R: a \leq x \leq b\}$.
2.  **Open Interval**: $(a, b)$ or $] a, b[=\{x \in R: a<x<b\}$.
3.  **Right Half Open Interval**: $[a, b)$ or $[a, b[=\{x \in R: a \leq x<b\}$.
4.  **Left Half Open Interval**: $(a, b]$ or $] a, b]=\{x \in R: a<x \leq b\}$.

On the real line, we represent these intervals as shown below:
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-13.jpg?height=186&width=613&top_left_y=1053&top_left_x=344)

**Length of an Interval**: The length of each of the intervals $[a, b]$, $(a, b)$, $[a, b)$ and $(a, b]$ is $(b-a)$.

---

## Examples on Intervals

1.  $[-2,3]=\{x \in R:-2 \leq x \leq 3\}$
2.  $(-2,3)=\{x \in R:-2<x<3\}$
3.  $[-2,3)=\{x \in R:-2 \leq x<3\}$
4.  $(-2,3]=\{x \in R:-2<x \leq 3\}$

---

## Power Set

The set of all subsets of a given set $A$ is called the **power set** of $A$, denoted by $P(A)$.

If $n(A)=m$ then $n[P(A)]=2^{m}$.

---

## Solved Examples on Subsets, Power Set and Intervals

### Example: 1

Write down all possible subsets of $A=\{4\}$.

#### Solution:

All possible subsets of $A$ are $\phi, \{4\}$.

$$
\therefore \quad P(A)=\{\phi,\{4\}\}.
$$

Here, $n(A)=1$ and $n[P(A)]=2=2^{1}$.

---

### Example: 2

Write down all possible subsets of $A=\{2,3\}$.

#### Solution:

All possible subsets of $A$ are $\phi,\{2\},\{3\},\{2,3\}$.

$$
\therefore \quad P(A)=\{\phi,\{2\},\{3\},\{2,3\}\}
$$

Thus, $n(A)=2$ and $n\{P(A)\}=4=2^{2}$.

---

### Example: 3

Write down all possible subsets of $A=\{-1,0,1\}$.

#### Solution:

All possible subsets of $A$ are $\phi,\{-1\},\{0\},\{1\},\{-1,0\},\{0,1\},\{-1,1\}, \text{ and } \{-1,0,1\}$.

$$
\therefore \quad P(A)=\{\phi,\{-1\},\{0\},\{1\},\{-1,0\},\{0,1\},\{-1,1\},\{-1,0,1\}\}.
$$

Thus, $n(A)=3$ and $n\{P(A)\}=8=2^{3}$.

---

### Example: 4

Write down all possible subsets of $A=\{1,\{2,3\}\}$.

#### Solution:

Here, $A$ contains two elements, namely $1$ and $\{2,3\}$.
Let $\{2,3\}=B$, then $A=\{1, B\}$.

$$
\begin{array}{ll}
\therefore & P(A)=\{\phi,\{1\},\{B\},\{1, B\}\} \\
\Rightarrow & P(A)=\{\phi,\{1\},\{\{2,3\}\},\{1,\{2,3\}\}\} .
\end{array}
$$

---

### Example: 5

Write down all possible subsets of $\phi$.

#### Solution:

$\phi$ has only one subset, namely $\phi$.

$$
\therefore \quad P(\phi)=\{\phi\}.
$$

---

### Example: 6

Write each of the following subsets of $R$ as an interval:
1.  $A=\{x: x \in R,-3<x \leq 5\}$
2.  $B=\{x: x \in R,-5<x<-1\}$
3.  $C=\{x: x \in R,-2 \leq x<0\}$
4.  $D=\{x: x \in R,-1 \leq x \leq 4\}$

Find the length of each of the above intervals.

#### Solution:

We have
1.  $A=\{x: x \in R,-3<x \leq 5\}=(-3,5]$. Length $(A)=5-(-3)=8$.
2.  $B=\{x: x \in R,-5<x<-1\}=(-5,-1)$. Length $(B)=-1-(-5)=4$.
3.  $C=\{x: x \in R,-2 \leq x<0\}=[-2,0)$. Length $(C)=0-(-2)=2$.
4.  $D=\{x: x \in R,-1 \leq x \leq 4\}=[-1,4]$. Length $(D)=4-(-1)=5$.

---

### Example: 7

Write each of the following intervals in the set-builder form:
1.  $A=(2,5)$
2.  $B=[-4,7]$
3.  $C=[-8,0)$
4.  $D=(5,9]$

#### Solution:

We have
1.  $A=(2,5)=\{x: x \in R, 2<x<5\}$.
2.  $B=[-4,7]=\{x: x \in R,-4 \leq x \leq 7\}$.
3.  $C=[-8,0)=\{x: x \in R,-8 \leq x<0\}$.
4.  $D=(5,9]=\{x: x \in R, 5<x \leq 9\}$.

---

## Equal Sets

Two sets $A$ and $B$ are said to be **equal**, if every element of $A$ is in $B$ and every element of $B$ is in $A$, and we write, $A=B$.

**Remarks**:
- The elements of a set may be listed in any order. Thus, $\{1,2,3\}=\{3,1,2\}=\{2,3,1\}$, etc.
- The repetition of elements in a set is meaningless. Thus, $\{2,4,6\}=\{2,2,4,6,6\}$.

### Theorem 4
Let $A$ and $B$ be two sets. Then, prove that $A=B \Leftrightarrow A \subseteq B$ and $B \subseteq A$.

#### Proof:
Let $A=B$.
Then, by definition of equal sets, every element of $A$ is in $B$ and every element of $B$ is in $A$.
Therefore, $A \subseteq B$ and $B \subseteq A$.
Thus, $(A=B) \Rightarrow (A \subseteq B$ and $B \subseteq A)$.

Again, let $A \subseteq B$ and $B \subseteq A$.
Then, by the definition of a subset, it follows that every element of $A$ is in $B$ and every element of $B$ is in $A$.
Consequently, $A=B$.
Thus, $(A \subseteq B$ and $B \subseteq A) \Rightarrow A=B$.
Hence, $A=B \Leftrightarrow (A \subseteq B$ and $B \subseteq A)$.

---

### Example: 8

Let $A=\{1,\{2\},\{3,4\}, 5\}$. Which of the following are incorrect statements? Rectify each:
1. $2 \in A$
2. $\{2\} \subset A$
3. $\{1,2\} \subset A$
4. $\{3,4\} \subset A$
5. $\{1,5\} \subset A$
6. $\{\phi\} \subset A$
7. $1 \subset A$
8. $\{1,2,3,4\} \subset A$

#### Solution:

Clearly, $A$ contains four elements, namely $1, \{2\}, \{3,4\}$ and $5$.

1.  $2 \in A$ is **incorrect**. The correct statement would be $\{2\} \in A$.
2.  $\{2\} \subset A$ is **incorrect**. The correct statement is $\{\{2\}\} \subset A$.
3.  Clearly, $2 \notin A$ and therefore, $\{1,2\} \subset A$ is **incorrect**. The correct statement would be $\{1,\{2\}\} \subset A$.
4.  Clearly, $\{3,4\}$ is an element of $A$. So, $\{3,4\} \subset A$ is **incorrect** and $\{\{3,4\}\} \subset A$ is **correct**.
5.  Since $1$ and $5$ are both elements of $A$, so $\{1,5\} \subset A$ is **correct**.
6.  Since $\phi \notin A$, so $\{\phi\} \subset A$ is **incorrect** while $\phi \subset A$ is **correct**.
7.  Since $1 \in A$, so $1 \subset A$ is **incorrect** and therefore, $\{1\} \subset A$ is **correct**.
8.  Since $2 \notin A$ and $3 \notin A$, so $\{1,2,3,4\} \subset A$ is **incorrect**. The correct statement would be $\{1,\{2\},\{3,4\}\} \subset A$.

---

