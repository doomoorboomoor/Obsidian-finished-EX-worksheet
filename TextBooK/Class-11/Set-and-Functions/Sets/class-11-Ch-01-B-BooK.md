## Some Terms Related to Sets

### Empty Set

A set containing no element at all is called the **empty set**, or the **null set**, or the **void set**, denoted by $\phi$, or $\{\}$.

A set which has at least one element is called a **nonempty set**.

---

#### Examples of empty sets

1.  $\{x: x \in N \text{ and } 2<x<3\}=\phi$, since there is no natural number lying between 2 and 3.
2.  $\{x: x \text{ is a number, } x \neq x\}=\phi$, since there is no number which is not equal to itself.
3.  $\{x: x \in N, x<5 \text{ and } x>7\}=\phi$, since there is no natural number which is less than 5 and greater than 7.
4.  $\{x: x \in R \text{ and } x^{2}=-1\}=\phi$, since there is no real number whose square is -1.
5.  $\{x: x \text{ is rational and } x^{2}-2=0\}=\phi$, since there is no rational number whose square is 2.
6.  $\{x: x \text{ is an even prime number greater than 2}\}=\phi$, since there is no prime number which is even and greater than 2.
7.  $\{x: x \text{ is a point common to two parallel lines}\}=\phi$, since there is no point common to two parallel lines.

---

### Singleton Set

A set containing exactly one element is called a **singleton set**.

---

#### Examples of singleton sets

1.  $\{0\}$ is a singleton set whose only element is 0.
2.  $\{15\}$ is a singleton set whose only element is 15.
3.  $\{-8\}$ is a singleton set whose only element is -8.
4.  $\{x: x \in N \text{ and } x^{2}=4\}=\{2\}$, since 2 is the only natural number whose square is 4.
    However, $\{x: x \in Z \text{ and } x^{2}=4\}=\{-2,2\}$, which is not a singleton set.
5.  Consider the set $\{x: x \in R \text{ and } x^{3}-1=0\}$.

    Now, $x^{3}-1=0 \Rightarrow(x-1)(x^{2}+x+1)=0$

    $$
    \Rightarrow x=1 \text{ or } x=\frac{-1 \pm \sqrt{1-4}}{2}=\frac{-1 \pm \sqrt{-3}}{2}
    $$

    Thus, the given equation has one real root, namely $x=1$.
    $\therefore \quad \{x: x \in R \text{ and } x^{3}-1=0\}=\{1\}$, which is a singleton set.

---

### Finite and Infinite Sets

An empty set or a nonempty set in which the process of counting of elements surely comes to an end is called a **finite set**. A set which is not finite is called an **infinite set**.

The number of distinct elements contained in a finite set $A$ is denoted by $n(A)$.

---

#### Examples of finite sets

1.  Let $A=\{2,4,6,8,10,12\}$. Then, $A$ is clearly a finite set and $n(A)=6$.
2.  Let $B=$ set of all letters in the English alphabet. Then, $n(B)=26$ and therefore, $B$ is finite.
3.  Let $C=\{x: x \in Z \text{ and } x^{2}-36=0\}$. Then, $C=\{-6,6\}$, which is clearly a finite set and $n(C)=2$.
4.  The set of all persons on earth is a finite set.
5.  The set of all animals on earth is a finite set.

---

#### Examples of infinite sets

1.  The set of all points on the arc of a circle is an infinite set.
2.  The set of all points on a line segment is an infinite set.
3.  The set of all circles passing through a given point is an infinite set.
4.  The set of all straight lines parallel to a given line, say the x-axis, is an infinite set.
5.  The set of all positive integral multiples of 5 is an infinite set. Let $Z^{+}$ be the set of all positive integers. Then, $\{5x: x \in Z^{+}\}=\{5,10,15,20,25, \ldots\}$ is an infinite set.
6.  Each of the sets $N$, $Z$, $Q$ and $R$ is an infinite set.

**Note:** All infinite sets cannot be described in roster form. For example, the set $R$ of all real numbers cannot be described in this form, since the elements of this set do not follow a particular pattern.

---

### Equal Sets

Two nonempty sets $A$ and $B$ are said to be **equal**, if they have exactly the same elements and we write, $A=B$.

Otherwise, the sets are unequal and we write, $A \neq B$.

#### Remarks

1.  The elements of a set may be listed in any order. Thus, $\{1,2,3\}=\{2,1,3\}=\{3,2,1\}$.
2.  The repetition of elements in a set has no meaning. Thus, $\{1,1,2,2,3\}=\{1,2,3\}$.

---

#### Some examples of equal sets

### Example 1:

Let $A=$ set of letters in the word 'follow', and $B=$ set of letters in the word 'wolf'. Show that $A=B$.

#### Solution:

Clearly, we have

$$
A=\{\mathrm{f}, \mathrm{o}, \mathrm{l}, \mathrm{w}\} \text{ and } B=\{\mathrm{w}, \mathrm{o}, \mathrm{l}, \mathrm{f}\}
$$

Clearly, $A$ and $B$ have exactly same elements. $\therefore \quad A=B$.

---

### Example 2:

Let $A=\{p, q, r, s\}$ and $B=\{q, r, p, s\}$. Are $A$ and $B$ equal?

#### Solution:

Since $A$ and $B$ have exactly the same elements, so $A=B$.

---

### Example 3:

Show that $\phi$, $\{0\}$ and $0$ are all different.

#### Solution:

We know that $\phi$ is a set containing no element at all. And, $\{0\}$ is a set containing one element, namely 0. Also, 0 is a number, not a set.

Hence, $\phi$, $\{0\}$ and $0$ are all different.

---

### Example 4:

Let $A=\{x: x \in N, x^{2}-9=0\}$ and $B=\{x: x \in Z, x^{2}-9=0\}$. Show that $A \neq B$.

#### Solution:

$x^{2}-9=0 \Rightarrow (x+3)(x-3)=0 \Rightarrow x=-3 \text{ or } x=3$.

$\therefore A=\{x: x \in N, x^{2}-9=0\}=\{3\} \quad [\because -3 \notin N]$

and $B=\{x: x \in Z, x^{2}-9=0\}=\{-3,3\}$.

Hence, $A \neq B$.

---

### Equivalent Sets

Two finite sets $A$ and $B$ are said to be **equivalent**, if $n(A)=n(B)$.

Equal sets are always equivalent. But, equivalent sets need not be equal.

---

### Example 1:

Let $A=\{1,3,5\}$ and $B=\{2,4,6\}$. Then, $n(A)=n(B)=3$. So, $A$ and $B$ are equivalent. Clearly, $A \neq B$.

Hence, $A$ and $B$ are equivalent sets but not equal.

---

### Example 2:

Show that $\{0\}$ and $\phi$ are not equivalent sets.

#### Solution:

Let $A=\{0\}$ and $B=\phi$. Then, clearly $n(A)=1$ and $n(B)=0$.

$\therefore \quad n(A) \neq n(B)$ and hence $A$ and $B$ are not equivalent sets.

---

