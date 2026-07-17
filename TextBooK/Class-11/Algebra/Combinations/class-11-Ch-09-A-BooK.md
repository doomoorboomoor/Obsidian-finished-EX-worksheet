## Combinations

A **combination** is each of the different groups or selections that can be made from a given number of things by taking some or all of them at a time, irrespective of their arrangements.

---

## Illustrative Examples

### Example 1:

All combinations of three persons $A, B, C$ taken two at a time are:

$$
AB, AC, BC.
$$

Clearly, $AB$ and $BA$ represent the same combination, but they represent different permutations.

---

### Example 2:

All combinations of four persons $A, B, C, D$ taken two at a time are:

$$
AB, AC, AD, BC, BD, CD.
$$

---

### Example 3:

All combinations of four persons $A, B, C, D$ taken three at a time are:

$$
ABC, ABD, ACD, BCD.
$$

---

## Difference Between a Permutation and a Combination

In a **combination**, only a group is made, and the order in which the objects are arranged is immaterial.

On the other hand, in a **permutation**, not only is the group formed, but an arrangement in a definite order is also considered.

**Remark:** In general, we use the word **arrangements** for permutations and the word **selections** for combinations.

---

### Example 4:

-   $AB$ and $BA$ are two different permutations, but each represents the same combination.
-   $ABC, ACB, BAC, BCA, CAB, CBA$ are six different permutations, but each one represents the same combination, namely $ABC$.

**Notation:** The number of all combinations of $n$ things, taken $r$ at a time, is denoted by ${}^{n}C_{r}$ or $C(n, r)$, where $n$ and $r$ are integers such that $n>0, r \geq 0$ and $n \geq r$.

---

## Combinations of $n$ Different Objects

### Theorem 1
The number of all combinations of $n$ distinct objects, taken $r$ at a time, is given by:

$$
{}^{n}C_{r} = \frac{n!}{r!(n-r)!}
$$

#### Proof:
Let the number of all combinations of $n$ objects, taken $r$ at a time, be $x$.
Then, ${}^{n}C_{r} = x$.

Now, each combination contains $r$ objects, which may be arranged among themselves in $r!$ ways.
Thus, each combination gives rise to $r!$ permutations.

Therefore, $x$ combinations will give rise to $x \times (r!)$ permutations.
So, the number of permutations of $n$ things, taken $r$ at a time, is $x \times (r!)$.

Consequently, ${}^{n}P_{r} = x \times (r!) = {}^{n}C_{r} \times (r!)$.

$$
\therefore {}^{n}C_{r} = \frac{{}^{n}P_{r}}{r!} = \frac{n!}{r!(n-r)!} \quad \left[\because {}^{n}P_{r} = \frac{n!}{(n-r)!}\right]
$$

---

### Corollary 1
Prove that ${}^{n}C_{r} = \frac{n(n-1)(n-2) \ldots \text{ to } r \text{ factors}}{r!}$.

#### Proof:
We have:

$$
\begin{aligned}
{}^{n}C_{r} &= \frac{n!}{r!(n-r)!} \\
&= \frac{n(n-1)(n-2) \ldots (n-r+1)(n-r)(n-r-1) \ldots 3 \cdot 2 \cdot 1}{r! \times [(n-r)(n-r-1) \ldots 3 \cdot 2 \cdot 1]} \\
&= \frac{n(n-1)(n-2) \ldots (n-r+1)}{r!} \\
&= \frac{n(n-1)(n-2) \ldots \text{ to } r \text{ factors}}{r!}
\end{aligned}
$$

Hence, ${}^{n}C_{r} = \frac{n(n-1)(n-2) \ldots \text{ to } r \text{ factors}}{r!}$.

---

### Example 1:
Evaluate ${}^{11}C_{4}$.

#### Solution:

$$
{}^{11}C_{4} = \frac{11 \times 10 \times 9 \times 8}{4!} = \frac{11 \times 10 \times 9 \times 8}{4 \times 3 \times 2 \times 1} = 330.
$$

---

### Corollary 2
Prove that ${}^{n}C_{n} = {}^{n}C_{0} = 1$.

#### Proof:
We have:

$$
{}^{n}C_{r} = \frac{n!}{r!(n-r)!} \tag{i}
$$

Putting $r=n$ in (i), we get:

$$
{}^{n}C_{n} = \frac{n!}{n!(n-n)!} = \frac{1}{0!} = 1 \quad [\because 0!=1].
$$

Putting $r=0$ in (i), we get:

$$
{}^{n}C_{0} = \frac{n!}{0!(n-0)!} = \frac{n!}{1 \times n!} = 1 \quad [\because 0!=1].
$$

Hence, ${}^{n}C_{n} = {}^{n}C_{0} = 1$.

---

### Corollary 3
Prove that ${}^{n}C_{r} = \frac{{}^{n}P_{r}}{r!}$.

#### Proof:
We have:

$$
{}^{n}C_{r} = \frac{n!}{r!(n-r)!} = \frac{1}{r!} \cdot \left\{\frac{n!}{(n-r)!}\right\} = \frac{{}^{n}P_{r}}{r!}.
$$

---

### Example 2:
If ${}^{n}P_{r} = 720$ and ${}^{n}C_{r} = 120$, find $r$.

#### Solution:
We have:

$$
{}^{n}C_{r} = \frac{{}^{n}P_{r}}{r!} \Rightarrow \frac{720}{r!} = 120 \Rightarrow r! = \frac{720}{120} = 6 = (3 \times 2 \times 1) = 3!
$$

$$
\Rightarrow r=3
$$

Hence, $r=3$.

---

## Summary of Results

-   ${}^{n}C_{r} = \frac{n!}{r!(n-r)!} = \frac{n(n-1)(n-2) \ldots (n-r+1)}{r!}$
-   ${}^{n}C_{r} = \frac{n(n-1)(n-2) \ldots \text{ to } r \text{ factors}}{r!}$
-   ${}^{n}C_{n} = {}^{n}C_{0} = 1$
-   ${}^{n}C_{r} = \frac{{}^{n}P_{r}}{r!}$

---

## Properties of ${}^{n}C_{r}$

### Theorem 1
For $0 \leq r \leq n$, prove that ${}^{n}C_{r} = {}^{n}C_{n-r}$.

#### Proof:
We have:

$$
{}^{n}C_{n-r} = \frac{n!}{(n-r)!\{n-(n-r)\}!} = \frac{n!}{(n-r)!r!} = {}^{n}C_{r}.
$$

Hence, ${}^{n}C_{r} = {}^{n}C_{n-r}$.

---

### Example 1:
Evaluate ${}^{100}C_{98}$.

#### Solution:
Using the result ${}^{n}C_{r} = {}^{n}C_{n-r}$, we get:

$$
{}^{100}C_{98} = {}^{100}C_{(100-98)} = {}^{100}C_{2} = \frac{100 \times 99}{2} = 4950.
$$

---

### Theorem 2
If ${}^{n}C_{x} = {}^{n}C_{y}$ and $x \neq y$ then prove that $x+y=n$.

#### Proof:
We have:

$$
\begin{aligned}
& {}^{n}C_{x} = {}^{n}C_{y} = {}^{n}C_{n-y} && [\because {}^{n}C_{r} = {}^{n}C_{n-r}] \\
\Rightarrow \quad & x=y \text{ or } x=n-y \\
\Rightarrow \quad & x=n-y && [\because x \neq y (\text{given})] \\
\Rightarrow \quad & x+y=n.
\end{aligned}
$$

Hence, if ${}^{n}C_{x} = {}^{n}C_{y}$ and $x \neq y$, then $x+y=n$.

---

### Example 2:

(i) If ${}^{n}C_{18} = {}^{n}C_{12}$ then find the value of ${}^{32}C_{n}$.
(ii) If ${}^{10}C_{r} = {}^{10}C_{r+4}$ then find the value of ${}^{5}C_{r}$.

#### Solution:
(i) ${}^{n}C_{18} = {}^{n}C_{12} \Rightarrow n=(18+12)=30$.

$$
\therefore {}^{32}C_{n} = {}^{32}C_{30} = {}^{32}C_{32-30} = {}^{32}C_{2} = \frac{32 \times 31}{2!} = 496.
$$

(ii) ${}^{10}C_{r} = {}^{10}C_{r+4} \Rightarrow r+(r+4)=10 \Rightarrow r=3$.

$$
\therefore {}^{5}C_{r} = {}^{5}C_{3} = {}^{5}C_{5-3} = {}^{5}C_{2} = \frac{5 \times 4}{2!} = 10.
$$

---

### Theorem 3 (Pascal's Rule)
Let $1 \leq r \leq n$. Then, prove that:

$$
{}^{n}C_{r} + {}^{n}C_{r-1} = {}^{n+1}C_{r}
$$

#### Proof:
We have:

$$
\begin{aligned}
{}^{n}C_{r} + {}^{n}C_{r-1} &= \frac{n!}{r!(n-r)!} + \frac{n!}{(r-1)!\{n-(r-1)\}!} \\
&= \frac{n!}{r!(n-r)!} + \frac{n!}{(r-1)!(n-r+1)!} \\
&= \frac{n!(n-r+1)}{r!(n-r+1)!} + \frac{n! \cdot r}{r!(n-r+1)!} \\
&= \left\{\frac{n!}{r!(n-r+1)!}\right\} \cdot \{n-r+1+r\} \\
&= \frac{(n+1) \cdot n!}{r!(n-r+1)!} \\
&= \frac{(n+1)!}{r!(n+1-r)!} \\
&= {}^{n+1}C_{r}.
\end{aligned}
$$

Hence, ${}^{n}C_{r} + {}^{n}C_{r-1} = {}^{n+1}C_{r}$.

---

### Theorem 4
If $1 \leq r \leq n$, prove that $n \times {}^{n-1}C_{r-1} = (n-r+1) \times {}^{n}C_{r-1}$.

#### Proof:
We have:

$$
\begin{aligned}
n \times {}^{n-1}C_{r-1} &= n \times \frac{(n-1)!}{(r-1)![(n-1)-(r-1)]!} \\
&= \frac{n \times (n-1)!}{(r-1)!(n-r)!} \\
&= \frac{n! \times (n-r+1)}{(r-1)!(n-r)! \times (n-r+1)} \quad [\text{multiplying num. and denom. by } (n-r+1)] \\
&= (n-r+1) \times \frac{n!}{(r-1)!(n-r+1)!} \\
&= (n-r+1) \times {}^{n}C_{r-1}.
\end{aligned}
$$

Hence, $n \times {}^{n-1}C_{r-1} = (n-r+1) \times {}^{n}C_{r-1}$.

**Remark:** The above result may be written as:

$$
\frac{{}^{n}C_{r-1}}{{}^{n-1}C_{r-1}} = \frac{n}{n-r+1}.
$$

---

### Theorem 5
If $n$ and $r$ are positive integers such that $1 \leq r \leq n$ then prove that:
(i) $\frac{{}^{n}C_{r}}{{}^{n}C_{r-1}} = \frac{n-r+1}{r}$
(ii) $\frac{{}^{n}C_{r}}{{}^{n-1}C_{r-1}} = \frac{n}{r}$

#### Proof:
(i) We know that:

$$
{}^{n}C_{r} = \frac{n!}{r!(n-r)!} \quad \text{and} \quad {}^{n}C_{r-1} = \frac{n!}{(r-1)!(n-r+1)!}.
$$

$$
\begin{aligned}
\therefore \frac{{}^{n}C_{r}}{{}^{n}C_{r-1}} &= \frac{n!}{r!(n-r)!} \times \frac{(r-1)!(n-r+1)!}{n!} \\
&= \frac{(r-1)!(n-r+1)(n-r)!}{r(r-1)!(n-r)!} \\
&= \frac{n-r+1}{r}.
\end{aligned}
$$

Hence, $\frac{{}^{n}C_{r}}{{}^{n}C_{r-1}} = \frac{n-r+1}{r}$.

(ii) We have:

$$
{}^{n}C_{r} = \frac{n!}{r!(n-r)!}
$$

and

$$
{}^{n-1}C_{r-1} = \frac{(n-1)!}{(r-1)!\{(n-1)-(r-1)\}!} = \frac{(n-1)!}{(r-1)!(n-r)!}.
$$

$$
\therefore \frac{{}^{n}C_{r}}{{}^{n-1}C_{r-1}} = \frac{n!}{r!(n-r)!} \times \frac{(r-1)!(n-r)!}{(n-1)!} = \frac{n}{r}.
$$

Hence, $\frac{{}^{n}C_{r}}{{}^{n-1}C_{r-1}} = \frac{n}{r}$.

---

## Summary of Properties

-   (i) ${}^{n}C_{r} = {}^{n}C_{n-r}$
-   (ii) ${}^{n}C_{x} = {}^{n}C_{y}$ and $x \neq y \Rightarrow x+y=n$
-   (iii) ${}^{n}C_{r} + {}^{n}C_{r-1} = {}^{n+1}C_{r}$ [Pascal's rule]
-   (iv) $\frac{{}^{n}C_{r-1}}{{}^{n-1}C_{r-1}} = \frac{n}{n-r+1}$
-   (v) $\frac{{}^{n}C_{r}}{{}^{n-1}C_{r-1}} = \frac{n}{r}$
-   (vi) $\frac{{}^{n}C_{r}}{{}^{n}C_{r+1}} = \frac{r+1}{n-r}$

---

## Solved Examples

### Example 1:
Evaluate:
(i) ${}^{10}C_{3}$
(ii) ${}^{11}C_{8}$
(iii) ${}^{50}C_{48}$
(iv) ${}^{63}C_{63}$

#### Solution:
We have:
(i) ${}^{10}C_{3} = \frac{10 \times 9 \times 8}{3!} = \frac{10 \times 9 \times 8}{3 \times 2 \times 1} = 120$.
(ii) ${}^{11}C_{8} = {}^{11}C_{(11-8)} = {}^{11}C_{3} = \frac{11 \times 10 \times 9}{3!} = \frac{11 \times 10 \times 9}{3 \times 2 \times 1} = 165 \quad [\because {}^{n}C_{r} = {}^{n}C_{n-r}]$.
(iii) ${}^{50}C_{48} = {}^{50}C_{(50-48)} = {}^{50}C_{2} = \frac{50 \times 49}{2} = 1225$.
(iv) ${}^{63}C_{63} = 1 \quad [\because {}^{n}C_{n} = 1]$.

---

### Example 2:
If ${}^{n}C_{8} = {}^{n}C_{6}$, find ${}^{n}C_{3}$.

#### Solution:
We know that if ${}^{n}C_{p} = {}^{n}C_{q}$ and $p \neq q \Rightarrow n = p+q$.
$\therefore {}^{n}C_{8} = {}^{n}C_{6} \Rightarrow n = (8+6) = 14$.
$\therefore {}^{n}C_{3} = {}^{14}C_{3} = \frac{14 \times 13 \times 12}{3!} = \frac{14 \times 13 \times 12}{3 \times 2 \times 1} = 364$.

---

### Example 3:
If ${}^{n}C_{r-1} : {}^{n}C_{r} : {}^{n}C_{r+1} = 3:4:5$, find the values of $n$ and $r$.

#### Solution:
We have, $\frac{{}^{n}C_{r}}{{}^{n}C_{r+1}} = \frac{r+1}{n-r}$. (i)

Putting $\frac{{}^{n}C_{r}}{{}^{n}C_{r+1}} = \frac{4}{5}$ in (i), we get:

$$
\frac{r+1}{n-r} = \frac{4}{5} \Rightarrow 5r+5 = 4n-4r \Rightarrow 4n-9r=5. \tag{ii}
$$

From property $\frac{{}^{n}C_{r-1}}{{}^{n}C_{r}} = \frac{r}{n-r+1}$, we get:

$$
\frac{r}{n-r+1} = \frac{3}{4} \Rightarrow 3n-3r+3 = 4r \Rightarrow 3n-7r=-3. \tag{iii}
$$

On solving (ii) and (iii), we get $n=62$ and $r=27$.

---

### Example 4:
If ${}^{2n}C_{3} : {}^{n}C_{3} = 11:1$, find $n$.

#### Solution:
We have:

$$
{}^{2n}C_{3} = \frac{2n(2n-1)(2n-2)}{3!} = \frac{2n(2n-1)2(n-1)}{6} = \frac{2n(n-1)(2n-1)}{3}
$$

and

$$
{}^{n}C_{3} = \frac{n(n-1)(n-2)}{3!} = \frac{n(n-1)(n-2)}{6}.
$$

$$
\therefore \frac{{}^{2n}C_{3}}{{}^{n}C_{3}} = \frac{2n(n-1)(2n-1)}{3} \times \frac{6}{n(n-1)(n-2)} = \frac{4(2n-1)}{(n-2)}.
$$

Now,

$$
\frac{{}^{2n}C_{3}}{{}^{n}C_{3}} = \frac{11}{1} \Rightarrow \frac{4(2n-1)}{(n-2)} = \frac{11}{1}
$$

$$
\Rightarrow 8n-4 = 11n-22 \Rightarrow 3n=18 \Rightarrow n=6.
$$

Hence, $n=6$.

---

### Example 5:
Prove that the product of $r$ consecutive positive integers is divisible by $r!$.

#### Solution:
Let the $r$ consecutive positive integers be $(n+1), (n+2), \ldots, (n+r)$.

Then, their product is $(n+1)(n+2)(n+3) \ldots (n+r)$.

$$
\begin{aligned}
&= \frac{n!(n+1)(n+2)(n+3) \ldots (n+r)}{n!} \\
&= \frac{(n+r)!}{n!} = r! \cdot \frac{(n+r)!}{r![(n+r)-r]!} \\
&= r! \times {}^{n+r}C_{r},
\end{aligned}
$$

which is divisible by $r!$, since ${}^{n+r}C_{r}$ is a positive integer.

---

### Example 6:
If ${}^{n}P_{r} = {}^{n}P_{r+1}$ and ${}^{n}C_{r} = {}^{n}C_{r-1}$, find $n$ and $r$.

#### Solution:
${}^{n}P_{r} = {}^{n}P_{r+1} \Rightarrow \frac{n!}{(n-r)!} = \frac{n!}{(n-r-1)!}$

$$
\begin{aligned}
&\Rightarrow (n-r)! = (n-r-1)! \\
&\Rightarrow (n-r) \times (n-r-1)! = (n-r-1)! \\
&\Rightarrow n-r=1. \tag{i}
\end{aligned}
$$

${}^{n}C_{r} = {}^{n}C_{r-1} \Rightarrow \frac{{}^{n}C_{r}}{{}^{n}C_{r-1}} = 1$

$$
\begin{aligned}
&\Rightarrow \frac{n-r+1}{r} = 1 \quad \left[\because \frac{{}^{n}C_{r}}{{}^{n}C_{r-1}} = \frac{n-r+1}{r}\right] \\
&\Rightarrow n-2r = -1. \tag{ii}
\end{aligned}
$$

Solving (i) and (ii), we get $n=3$ and $r=2$.

---

### Example 7:
Prove that ${}^{2n}C_{n} = \frac{2^{n} \times [1 \cdot 3 \cdot 5 \ldots (2n-1)]}{n!}$.

#### Solution:

$$
\begin{aligned}
{}^{2n}C_{n} &= \frac{(2n)!}{n!(2n-n)!} = \frac{(2n)!}{(n!)^{2}} \\
&= \frac{(2n)(2n-1)(2n-2) \ldots 4 \cdot 3 \cdot 2 \cdot 1}{(n!)^{2}} \\
&= \frac{[(2n)(2n-2)(2n-4) \ldots 4 \cdot 2] \times [(2n-1)(2n-3) \ldots 5 \cdot 3 \cdot 1]}{(n!)^{2}} \\
&= \frac{2^{n}[n(n-1)(n-2) \ldots 2 \cdot 1] \times [(2n-1)(2n-3) \ldots 5 \cdot 3 \cdot 1]}{(n!)^{2}} \\
&= \frac{2^{n} \times n! \times [1 \cdot 3 \cdot 5 \ldots (2n-3)(2n-1)]}{(n!)^{2}} \\
&= \frac{2^{n} \times [1 \cdot 3 \cdot 5 \ldots (2n-3)(2n-1)]}{n!}.
\end{aligned}
$$

Hence, ${}^{2n}C_{n} = \frac{2^{n} \times \{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2n-1)\}}{n!}$.

---

### Example 8:
Prove that ${}^{4n}C_{2n} : {}^{2n}C_{n} = \{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (4n-1)\} : \{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2n-1)\}^{2}$.

#### Solution:
We have:

$$
\begin{aligned}
\frac{{}^{4n}C_{2n}}{{}^{2n}C_{n}} &= \frac{(4n)!}{(2n)!(2n)!} \times \frac{n!n!}{(2n)!} \\
&= \frac{(4n)!(n!)^{2}}{(2n)![(2n)!]^{2}} \\
&= \frac{[1 \cdot 2 \cdot 3 \ldots (4n-1)(4n)](n!)^{2}}{(2n)![1 \cdot 2 \cdot 3 \ldots (2n-1)(2n)]^{2}} \\
&= \frac{[1 \cdot 3 \cdot 5 \ldots (4n-1)] \times [2 \cdot 4 \cdot 6 \ldots (4n)] \times (n!)^{2}}{(2n)![1 \cdot 3 \cdot 5 \ldots (2n-1)]^{2} \times [2 \cdot 4 \cdot 6 \ldots (2n)]^{2}} \\
&= \frac{[1 \cdot 3 \cdot 5 \ldots (4n-1)] \times 2^{2n} \times [1 \cdot 2 \cdot 3 \ldots (2n)] \times (n!)^{2}}{(2n)![1 \cdot 3 \cdot 5 \ldots (2n-1)]^{2} \times 2^{2n} \times (n!)^{2}} \\
&= \frac{[1 \cdot 3 \cdot 5 \ldots (4n-1)]}{[1 \cdot 3 \cdot 5 \ldots (2n-1)]^{2}}.
\end{aligned}
$$

$\therefore {}^{4n}C_{2n} : {}^{2n}C_{n} = [1 \cdot 3 \cdot 5 \ldots (4n-1)] : \{1 \cdot 3 \cdot 5 \ldots (2n-1)\}^{2}$.

---

### Example 9:
If ${}^{n+2}C_{8} : {}^{n-2}P_{4} = 57:16$, find $n$.

#### Solution:
We have:

$$
{}^{n+2}C_{8} = \frac{(n+2)!}{8!(n+2-8)!} = \frac{(n+2)!}{8!(n-6)!} \quad \left[\because {}^{n}C_{r} = \frac{n!}{r!(n-r)!}\right]
$$

and

$$
{}^{n-2}P_{4} = \frac{(n-2)!}{(n-2-4)!} = \frac{(n-2)!}{(n-6)!} \quad \left[\because {}^{n}P_{r} = \frac{n!}{(n-r)!}\right]
$$

Now, $\frac{{}^{n+2}C_{8}}{{}^{n-2}P_{4}} = \frac{57}{16}$

$$
\Rightarrow \frac{(n+2)!}{8!(n-6)!} \times \frac{(n-6)!}{(n-2)!} = \frac{57}{16}
$$

$$
\Rightarrow \frac{(n+2)(n+1)n(n-1)(n-2)!}{(n-2)!} = \frac{57}{16} \times 8!
$$

$$
\Rightarrow (n+2)(n+1)n(n-1) = \frac{57}{16} \times (8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1)
$$

$$
\Rightarrow (n+2)(n+1)n(n-1) = 57 \times 7 \times 6 \times 5 \times 3 = 21 \times 20 \times 19 \times 18
$$

$$
\Rightarrow n-1 = 18 \Rightarrow n=19.
$$

---

#