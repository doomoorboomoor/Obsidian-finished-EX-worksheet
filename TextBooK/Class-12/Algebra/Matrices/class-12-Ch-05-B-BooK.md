## Various Types of Matrices

### Row Matrix

A matrix having only one row is known as a **row matrix** or a **row vector**.

*Examples:*
- (i) $A=\left[\begin{array}{ll}5 & 18\end{array}\right]$ is a row matrix of order $1 \times 2$.
- (ii) $B=\left[\begin{array}{lll}2 & \sqrt{5} & -9\end{array}\right]$ is a row matrix of order $1 \times 4$.

### Column Matrix

A matrix having only one column is known as a **column matrix** or a **column vector**.

*Examples:*
- (i) $A=\left[\begin{array}{r}2 \\ 7 \\ -3\end{array}\right]$ is a column matrix of order $3 \times 1$.
- (ii) $B=\left[\begin{array}{l}6 \\ 4\end{array}\right]$ is a column matrix of order $2 \times 1$.

### Zero or Null Matrix

A matrix each of whose elements is zero is called a **zero matrix** or a **null matrix**.

*Examples:* The matrices [0], [0 0], $\left[\begin{array}{ll}0 & 0 \\ 0 & 0\end{array}\right]$ and $\left[\begin{array}{lll}0 & 0 & 0 \\ 0 & 0 & 0\end{array}\right]$ are null matrices of order $(1 \times 1),(1 \times 2),(2 \times 2)$ and $(2 \times 3)$ respectively.

### Square Matrix

A matrix having the same number of rows and columns is called a **square matrix**.

A matrix of order ( $n \times n$ ) is called a square matrix of order $n$ or an $n$-rowed square matrix.

A matrix of order $m \times n$, where $m \neq n$, is called a **rectangular matrix**.

*Examples:*
- (i) The matrix $\left[\begin{array}{cc}3 & 2 \\ 6 & -5\end{array}\right]$ is a 2-rowed square matrix.
- (ii) The matrix $\left[\begin{array}{ccc}5 & 3 & 6 \\ 7 & \sqrt{2} & -4 \\ -9 & \frac{1}{3} & 0\end{array}\right]$ is a 3-rowed square matrix.

### Diagonal Elements of a Matrix

Let $A=\left[a_{i j}\right]_{m \times n}$ be an $m \times n$ matrix. Then, the elements $a_{i j}$ for which $i=j$, are called the **diagonal elements** of $A$.

Thus, the diagonal elements of $A=\left[a_{i j}\right]_{m \times n}$ are $a_{11}, a_{22}, a_{33}, a_{44}$, etc.
The line along which the diagonal elements lie is called the **diagonal of the matrix**.

*Example:* Let $A=\left[\begin{array}{ccc}3 & 2 & -1 \\ \sqrt{5} & \frac{5}{8} & 7 \\ 6 & -4 & \sqrt{2}\end{array}\right]$
Then, the diagonal elements of $A$ are:

$$
a_{11}=3, a_{22}=\frac{5}{8}, a_{33}=\sqrt{2} .
$$

### Diagonal Matrix

A square matrix in which every nondiagonal element is zero is called a **diagonal matrix**.

If $A=\left[a_{i j}\right]_{n \times n}$ be a diagonal matrix then $a_{i j}=0$ when $i \neq j$ and we write it as
$A=\operatorname{diag}\left[a_{11}, a_{22}, a_{33}, \ldots, a_{n n}\right]$.

*Example:* Let $A=\left[\begin{array}{rrr}6 & 0 & 0 \\ 0 & 4 & 0 \\ 0 & 0 & -2\end{array}\right]$. Then, $A$ is a diagonal matrix.
We may write it as, $A=\operatorname{diag}[6,4,-2]$.

### Scalar Matrix

A square matrix in which every nondiagonal element is zero and all diagonal elements are equal is known as a **scalar matrix**.

*Examples:*
- (i) $A=\left[\begin{array}{ll}5 & 0 \\ 0 & 5\end{array}\right]$ is a scalar matrix of order 2.
- (ii) $B=\left[\begin{array}{rrr}-3 & 0 & 0 \\ 0 & -3 & 0 \\ 0 & 0 & -3\end{array}\right]$ is a scalar matrix of order 3.

### Unit Matrix

A square matrix in which every nondiagonal element is 0 and every diagonal element is 1 is called a **unit matrix** or an **identity matrix**.

Thus, a square matrix $\left[a_{i j}\right]_{n \times n}$ is a unit matrix if

$$
a_{i j}=\left\{\begin{array}{l}
0 \text { when } i \neq j, \\
1 \text { when } i=j .
\end{array}\right.
$$

A unit matrix of order $n$ will be denoted by $I_{n}$ or simply by $I$.

*Examples:*
- (i) $I_{2}=\left[\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right]$ is a unit matrix of order 2.
- (ii) $I_{3}=\left[\begin{array}{lll}1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1\end{array}\right]$ is a unit matrix of order 3.

### Comparable Matrices

Two matrices $A$ and $B$ are said to be **comparable** if they are of the same order, i.e., they have the same number of rows and the same number of columns.

*Example:* $A=\left[\begin{array}{rrr}2 & -5 & 1 \\ 0 & 3 & 6\end{array}\right]$ and $B=\left[\begin{array}{rrr}3 & 7 & 0 \\ 1 & 4 & -9\end{array}\right]$ are comparable matrices, each being of order ( $2 \times 3$ ).

### Equal Matrices

Two matrices $A$ and $B$ are said to be **equal**, written as $A=B$, if they are of the same order and their corresponding elements are equal.

### Example: 1 Find $x, y, z$ when $\left[\begin{array}{cc}5 & 3 \\ x & 7\end{array}\right]=\left[\begin{array}{cc}y & z \\ 1 & 7\end{array}\right]$.

#### Solution:

Since the corresponding elements of equal matrices are equal, we have

$$
\left[\begin{array}{cc}
5 & 3 \\
x & 7
\end{array}\right]=\left[\begin{array}{cc}
y & z \\
1 & 7
\end{array}\right] \Leftrightarrow x=1, y=5 \text { and } z=3 .
$$

---

### Example: 2 Find $x, y, z, w$ when $\left[\begin{array}{ll}x-y & 2 x+z \\ 2 x-y & 3 z+w\end{array}\right]=\left[\begin{array}{rr}-1 & 5 \\ 0 & 13\end{array}\right]$.
[CBSE 2013]

#### Solution:

We know that in equal matrices, the corresponding elements are equal.
$\therefore\left[\begin{array}{rr}x-y & 2 x+z \\ 2 x-y & 3 z+w\end{array}\right]=\left[\begin{array}{rr}-1 & 5 \\ 0 & 13\end{array}\right]$
$\Leftrightarrow \quad x-y=-1,2 x-y=0,2 x+z=5$ and $3 z+w=13$.

Solving the first two equations, we get $x=1$ and $y=2$.
Putting $x=1$ in $2 x+z=5$, we get $z=3$.
Putting $z=3$ in $3 z+w=13$, we get $w=4$.
$\therefore \quad x=1, y=2, z=3$ and $w=4$.

---

### Example: 3 $\left[\begin{array}{lll}0 & 0 & 0 \\ 0 & 0 & 0\end{array}\right] \neq\left[\begin{array}{ll}0 & 0 \\ 0 & 0 \\ 0 & 0\end{array}\right]$. Why?

#### Solution:

Since the given null matrices are not comparable, they are not equal.

---

## Operations on Matrices

### Addition of Matrices

Let $A$ and $B$ be two comparable matrices, each of order $(m \times n)$. Then, their sum $(A+B)$ is a matrix of order $(m \times n)$, obtained by adding the corresponding elements of $A$ and $B$.

Thus, if $A=\left[a_{i j}\right]_{m \times n}$ and $B=\left[b_{i j}\right]_{m \times n}$ then

$$
A+B=\left[a_{i j}+b_{i j}\right]_{m \times n}
$$

**REMARK:** For two matrices $A$ and $B$, the sum ( $A+B$ ) exists only when $A$ and $B$ are comparable.

*Example 1:* If $A=\left[\begin{array}{ll}2 & 1 \\ 0 & 4\end{array}\right]$ and $B=\left[\begin{array}{lll}3 & 4 & 5 \\ 1 & 2 & 3\end{array}\right]$ then $A$ and $B$ are matrices of order $2 \times 2$ and $2 \times 3$ respectively. So, $A$ and $B$ are not comparable. Hence, $A+B$ is not defined.

*Example 2:* Let $A=\left[\begin{array}{rrr}5 & 0 & -2 \\ 3 & 2 & -7\end{array}\right]$ and $B=\left[\begin{array}{rrr}4 & -3 & -6 \\ -1 & 0 & 4\end{array}\right]$.
Clearly, each one of $A$ and $B$ is a $2 \times 3$ matrix.
So, $A$ and $B$ are comparable matrices.
$\therefore A+B$ is defined.
Now, $A+B=\left[\begin{array}{lll}5+4 & 0+(-3) & -2+(-6) \\ 3+(-1) & 2+0 & -7+4\end{array}\right] =\left[\begin{array}{rrr}9 & -3 & -8 \\ 2 & 2 & -3\end{array}\right]$.

---

## Some Results on Addition of Matrices

### Theorem 1

Matrix addition is **commutative**, i.e., $A+B=B+A$ for all comparable matrices $A$ and $B$.

**PROOF:** Let $A=\left[a_{i j}\right]_{m \times n}$ and $B=\left[b_{i j}\right]_{m \times n}$. Then,

$$
\begin{aligned}
A+B & =\left[a_{i j}\right]_{m \times n}+\left[b_{i j}\right]_{m \times n} \\
& =\left[a_{i j}+b_{i j}\right]_{m \times n} \quad[\text { by the definition of addition of matrices }] \\
& =\left[b_{i j}+a_{i j}\right]_{m \times n} \quad[\because \quad \text { addition of numbers is commutative }] \\
& =\left[b_{i j}\right]_{m \times n}+\left[a_{i j}\right]_{m \times n}=B+A .
\end{aligned}
$$

Hence, $A+B=B+A$.

### Theorem 2

Matrix addition is **commutative**,
i.e, $(A+B)+C=A+(B+C)$ for all comparable matrices $A, B, C$.

**PROOF:** Let $A=\left[a_{i j}\right]_{m \times n}, B=\left[b_{i j}\right]_{m \times n}$ and $C=\left[c_{i j}\right]_{m \times n}$. Then,

$$
\begin{aligned}
(A+B)+C & =\left(\left[a_{i j}\right]_{m \times n}+\left[b_{i j}\right]_{m \times n}\right)+\left[c_{i j}\right]_{m \times n} \\
& =\left[a_{i j}+b_{i j}\right]_{m \times n}+\left[c_{i j}\right]_{m \times n} \\
& =\left[\left(a_{i j}+b_{i j}\right)+c_{i j}\right]_{m \times n} \\
& =\left[a_{i j}+\left(b_{i j}+c_{i j}\right)\right]_{m \times n}
\end{aligned}
$$

[ $\because$ addition of numbers is associative]

$$
\begin{aligned}
& =\left[a_{i j}\right]_{m \times n}+\left[b_{i j}+c_{i j}\right]_{m \times n} \\
& =\left[a_{i j}\right]_{m \times n}+\left(\left[b_{i j}\right]+\left[c_{i j}\right]_{m \times n}\right)=A+(B+C) .
\end{aligned}
$$

Hence, $(A+B)+C=A+(B+C)$.

### Theorem 3

If $A$ is an $m \times n$ matrix and $O$ is an $m \times n$ null matrix then

$$
A+O=O+A=A .
$$

**PROOF:** Let $A=\left[a_{i j}\right]_{m \times n}$ and $O=\left[b_{i j}\right]_{m \times n}$,
where $b_{i j}=0$ for all suffixes $i$ and $j$.
Then, $\quad A+O=\left[a_{i j}\right]_{m \times n}+\left[b_{i j}\right]_{m \times n}=\left[a_{i j}+b_{i j}\right]_{m \times n}$

$$
\begin{aligned}
& =\left[a_{i j}+0\right]_{m \times n} \quad\left[\because \quad b_{i j}=0\right] \\
& =\left[a_{i j}\right]_{m \times n}=A
\end{aligned}
$$

$\therefore \quad A+O=A$.
Similarly, $O+A=A$.
Hence, $A+O=O+A=A$.

**REMARK:** The null matrix $O$ of order $m \times n$ is the **additive identity** in the set of all $m \times n$ matrices.

### Example: 3 Let $A=\left[\begin{array}{rrr}3 & 5 & 4 \\ 1 & 2 & -3\end{array}\right]$ and $O=\left[\begin{array}{lll}0 & 0 & 0 \\ 0 & 0 & 0\end{array}\right]$, then verify that $A+O=O+A=A$.

#### Solution:

Clearly, each one of $A$ and $O$ is a matrix of order ( $2 \times 3$ ).
So, $(A+O)$ and $(O+A)$ are both defined.
Now, $A+O=\left[\begin{array}{rrr}3 & 5 & 4 \\ 1 & 2 & -3\end{array}\right]+\left[\begin{array}{lll}0 & 0 & 0 \\ 0 & 0 & 0\end{array}\right]$

$$
=\left[\begin{array}{rrr}
3+0 & 5+0 & 4+0 \\
1+0 & 2+0 & -3+0
\end{array}\right]+\left[\begin{array}{rrr}
3 & 5 & 4 \\
1 & 2 & -3
\end{array}\right]=A .
$$

$$
\text { And, } \begin{aligned}
O+A & =\left[\begin{array}{lll}
0 & 0 & 0 \\
0 & 0 & 0
\end{array}\right]+\left[\begin{array}{rrr}
3 & 5 & 4 \\
1 & 2 & -3
\end{array}\right] \\
& =\left[\begin{array}{lll}
0+3 & 0+5 & 0+4 \\
0+1 & 0+2 & 0+(-3)
\end{array}\right]=\left[\begin{array}{rrr}
3 & 5 & 4 \\
1 & 2 & -3
\end{array}\right]=A .
\end{aligned}
$$

Hence, $A+O=O+A=A$.

---

### Negative of a Matrix

Let $A=\left[a_{i j}\right]_{m \times n}$. Then, the **negative of $A$** is the matrix $(-A)=\left[-a_{i j}\right]_{m \times n}$, obtained by replacing each element of $A$ with its corresponding additive inverse. ( $-A$ ) is called the **additive inverse** of $A$.

### Example: 4 If $A=\left[\begin{array}{rrc}3 & -2 & 0 \\ -5 & 7 & \sqrt{2}\end{array}\right]$, find ( $-A$ ) and verify that $A+(-A)=(-A)+A=0$

#### Solution:

Clearly, we have:

$$
(-A)= {\left[\begin{array}{rrr}
-3 & 2 & 0 \\
5 & -7 & -\sqrt{2}
\end{array}\right]}
$$

$$
\begin{aligned}
A+(-A) & =\left[\begin{array}{rrr}
3 & -2 & 0 \\
-5 & 7 & \sqrt{2}
\end{array}\right]+\left[\begin{array}{rrr}
-3 & 2 & 0 \\
5 & -7 & -\sqrt{2}
\end{array}\right] \\
& =\left[\begin{array}{ccc}
3+(-3) & -2+2 & 0+0 \\
-5+5 & 7+(-7) & \sqrt{2}+(-\sqrt{2})
\end{array}\right]=\left[\begin{array}{lll}
0 & 0 & 0 \\
0 & 0 & 0
\end{array}\right]=O .
\end{aligned}
$$

And, $(-A)+A=\left[\begin{array}{rrc}-3 & 2 & 0 \\ 5 & -7 & -\sqrt{2}\end{array}\right]+\left[\begin{array}{rrc}3 & -2 & 0 \\ -5 & 7 & \sqrt{2}\end{array}\right]$

$$
=\left[\begin{array}{ccc}
-3+3 & 2+(-2) & 0+0 \\
5+(-5) & -7+7 & -\sqrt{2}+\sqrt{2}
\end{array}\right]=\left[\begin{array}{ccc}
0 & 0 & 0 \\
0 & 0 & 0
\end{array}\right]
$$

Hence, $A+(-A)=(-A)+A=O$.

---

## Summary

### Laws of Addition on Matrices

- (i) $A+B=B+A$ [Commutative law]
- (ii) $(A+B)+C=A+(B+C)$ [Associative law]
- (iii) $A+O=O+A=A$
- (iv) $A+(-A)=(-A)+A=O$

---

## Solved Examples

### Example: 1 Let $A=\left[\begin{array}{rrr}2 & 3 & 5 \\ -1 & 0 & 4\end{array}\right]$ and $B=\left[\begin{array}{rrr}4 & -2 & 3 \\ 2 & 6 & -1\end{array}\right]$. Verify that $A+B=B+A$.

#### Solution:

Here, $A$ is a $2 \times 3$ matrix and $B$ is a $2 \times 3$ matrix. So, $A$ and $B$ are comparable.
Therefore, $(A+B)$ and $(B+A)$ both exist and each is a $2 \times 3$ matrix.
Now, $A+B=\left[\begin{array}{rrr}2 & 3 & 5 \\ -1 & 0 & 4\end{array}\right]+\left[\begin{array}{rrr}4 & -2 & 3 \\ 2 & 6 & -1\end{array}\right]$

$$
=\left[\begin{array}{ccc}
2+4 & 3+(-2) & 5+3 \\
-1+2 & 0+6 & 4+(-1)
\end{array}\right]=\left[\begin{array}{lll}
6 & 1 & 8 \\
1 & 6 & 3
\end{array}\right] .
$$

And, $B+A=\left[\begin{array}{rrr}4 & -2 & 3 \\ 2 & 6 & -1\end{array}\right]+\left[\begin{array}{rrr}2 & 3 & 5 \\ -1 & 0 & 4\end{array}\right]$

$$
=\left[\begin{array}{lrr}
4+2 & -2+3 & 3+5 \\
2+(-1) & 6+0 & (-1)+4
\end{array}\right]=\left[\begin{array}{lll}
6 & 1 & 8 \\
1 & 6 & 3
\end{array}\right] .
$$

Hence, $A+B=B+A$.

---

### Example: 2 Let $A=\left[\begin{array}{rr}1 & -2 \\ 5 & 4 \\ 3 & 0\end{array}\right], B=\left[\begin{array}{rr}3 & 1 \\ 0 & 2 \\ -3 & 5\end{array}\right]$ and $C=\left[\begin{
{rr}4 & 3 \\ -2 & 2 \\ 1 & 6\end{array}\right]$. Verify that $(A+B)+C=A+(B+C)$.

#### Solution:

Clearly, each one of the matrices $A, B, C$ is a ( $3 \times 2$ ) matrix. So, $(A+B)+C$ and $A+(B+C)$ are both defined and each one is a $3 \times 2$ matrix.

$$
\begin{aligned}
& \text { Now, }(A+B)= {\left[\begin{array}{rr}
1 & -2 \\
5 & 4 \\
3 & 0
\end{array}\right]+\left[\begin{
{rr}
3 & 1 \\
0 & 2 \\
-3 & 5
\end{array}\right] } \\
&= {\left[\begin{
{ll}
1+3 & -2+1 \\
5+0 & 4+2 \\
3+(-3) & 0+5
\end{array}\right]+\left[\begin{
{rr}
4 & -1 \\
5 & 6 \\
0 & 5
\end{array}\right] . } \\
\end{aligned}
$$

$$
\begin{aligned}
\therefore \quad(A+B)+C & =\left[\begin{
{rr}
4 & -1 \\
5 & 6 \\
0 & 5
\end{array}\right]+\left[\begin{
{rr}
4 & 3 \\
-2 & 2 \\
1 & 6
\end{array}\right] \\
& =\left[\begin{
{lr}
4+4 & -1+3 \\
5+(-2) & 6+2 \\
0+1 & 5+6
\end{array}\right]=\left[\begin{
{rr}
8 & 2 \\
3 & 8 \\
1 & 11
\end{array}\right] .
\end{aligned}
$$

$$
\begin{aligned}
& \text { Also, }(B+C)= {\left[\begin{
{rr}
3 & 1 \\
0 & 2 \\
-3 & 5
\end{array}\right]+\left[\begin{
{rr}
4 & 3 \\
-2 & 2 \\
1 & 6
\end{array}\right] }
\end{aligned}
$$

$$
\begin{aligned}
& =\left[\begin{
{cc}
3+4 & 1+3 \\
0+(-2) & 2+2 \\
-3+1 & 5+6
\end{array}\right]=\left[\begin{
{rr}
7 & 4 \\
-2 & 4 \\
-2 & 11
\end{array}\right] \\
\therefore \quad A+(B+C) & =\left[\begin{
{ll}
1 & -2 \\
5 & 4 \\
3 & 0
\end{array}\right]+\left[\begin{
{rr}
7 & 4 \\
-2 & 4 \\
-2 & 11
\end{array}\right] \\
& =\left[\begin{
{cc}
1+7 & -2+4 \\
5+(-2) & 4+4 \\
3+(-2) & 0+11
\end{array}\right]=\left[\begin{
{rr}
8 & 2 \\
3 & 8 \\
1 & 11
\end{array}\right] .
\end{aligned}
$$

Hence, $(A+B)+C=A+(B+C)$.

---

### Example: 3 Find the additive inverse of the matrix $A=\left[\begin{
{rrr}2 & -5 & 0 \\ 4 & 3 & -1\end{array}\right]$.

#### Solution:

Clearly, the additive inverse of the given matrix $A$ is the matrix $-A$, given by

$$
-A=\left[\begin{
{ccc}
-2 & -(-5) & 0 \\
-4 & -3 & -(-1)
\end{array}\right]=\left[\begin
{rrr}
-2 & 5 & 0 \\
-4 & -3 & 1
\end{array}\right]
$$

---

### Subtraction of Matrices

If $A$ and $B$ are two comparable matrices then we define

$$
(A-B)=A+(-B)
$$

### Example: 4

If $A=\left[\begin{array}{rrr}2 & -3 & 1 \\ 0 & 7 & -9\end{array}\right]$ and $B=\left[\begin{array}{rrr}1 & 2 & -3 \\ 4 & 8 & -4\end{array}\right]$, find $(A-B)$.

#### Solution:

We have, $(-B)=\left[\begin{array}{ccc}-1 & -2 & 3 \\ -4 & -8 & 4\end{array}\right]$.

$$
\begin{aligned}
\therefore(A-B) & =A+(-B) \\
& =\left[\begin{array}{rrr}
2 & -3 & 1 \\
0 & 7 & -9
\end{array}\right]+\left[\begin{array}{lll}
-1 & -2 & 3 \\
-4 & -8 & 4
\end{array}\right] \\
& =\left[\begin{array}{rrr}
2+(-1) & -3+(-2) & 1+3 \\
0+(-4) & 7+(-8) & -9+4
\end{array}\right]=\left[\begin{array}{rrr}
1 & -5 & 4 \\
-4 & -1 & -5
\end{array}\right] .
\end{aligned}
$$

Hence, $(A-B)=\left[\begin{array}{rrr}1 & -5 & 4 \\ -4 & -1 & -5\end{array}\right]$.

---

### Example: 5

If $\left[\begin{array}{cc}a+4 & 3 b \\ 8 & -6\end{array}\right]=\left[\begin{array}{cc}2 a+2 & b+2 \\ 8 & a-8 b\end{array}\right]$, then find the value of $(a-2 b)$.
[CBSE 2014]

#### Solution:

Comparing the corresponding elements of given equal matrices, we have $a+4=2 a+2$, $3 b=b+2$ and $a-8 b=-6$.
From these equations, we get $a=2$ and $b=1$.
$\therefore (a-2 b)=(2-2 \times 1)=(2-2)=0$.

---

### Example: 6

If $\left[\begin{array}{rrr}9 & -1 & 4 \\ -2 & 1 & 3\end{array}\right]=A+\left[\begin{array}{rrr}1 & 2 & -1 \\ 0 & 4 & 9\end{array}\right]$, then find the matrix $A$.
[CBSE 2013]

#### Solution:

Clearly, we have

$$
\begin{aligned}
A & =\left[\begin{array}{rrr}
9 & -1 & 4 \\
-2 & 1 & 3
\end{array}\right]-\left[\begin{array}{rrr}
1 & 2 & -1 \\
0 & 4 & 9
\end{array}\right] \\
& =\left[\begin{array}{rrr}
9-1 & -1-2 & 4+1 \\
-2-0 & 1-4 & 3-9
\end{array}\right]=\left[\begin{array}{rrr}
8 & -3 & 5 \\
-2 & -3 & -6
\end{array}\right] .
\end{aligned}
$$

---

## Scalar Multiplication

Let $A$ be a given matrix and $k$ be a number. Then, the matrix obtained by multiplying each element of $A$ by $k$ is called the **scalar multiple** of $A$ by $k$, to be denoted by $kA$.

If $A$ is an ($m \times n$) matrix then $kA$ is also an ($m \times n$) matrix.
If $A=\left[a_{i j}\right]_{m \times n}$ then $kA=\left[k \cdot a_{i j}\right]_{m \times n}$.

### Example: 7

If $A=\left[\begin{array}{rrr}5 & 4 & -2 \\ 6 & -1 & 7\end{array}\right]$, find (i) $3 A$ (ii) $\frac{1}{2} A$ (iii) $-2 A$.

#### Solution:

We have:

$$
\text { (i) } 3 A=\left[\begin{array}{lll}
3 \cdot 5 & 3 \cdot 4 & 3 \cdot(-2) \\
3 \cdot 6 & 3 \cdot(-1) & 3 \cdot 7
\end{array}\right]=\left[\begin{array}{ccc}
15 & 12 & -6 \\
18 & -3 & 21
\end{array}\right] .
$$

$$
\text { (ii) } \begin{aligned}
& \frac{1}{2} A=\left[\begin{array}{lll}
\frac{1}{2} \cdot 5 & \frac{1}{2} \cdot 4 & \frac{1}{2} \cdot(-2) \\
\frac{1}{2} \cdot 6 & \frac{1}{2} \cdot(-1) & \frac{1}{2} \cdot 7
\end{array}\right]=\left[\begin{array}{rrr}
\frac{5}{2} & 2 & -1 \\
3 & -\frac{1}{2} & \frac{7}{2}
\end{array}\right] . \\
& \text { (iii) }-2 A=(-2) \cdot A=\left[\begin{array}{lll}
(-2) \cdot 5 & (-2) \cdot 4 & (-2) \cdot(-2) \\
(-2) \cdot 6 & (-2) \cdot(-1) & (-2) \cdot 7
\end{array}\right] \\
&=\left[\begin{array}{rrr}
-10 & -8 & 4 \\
-12 & 2 & -14
\end{array}\right] .
\end{aligned}
$$

---

## Some Properties of Scalar Multiplication

### Theorem 1

If $A$ and $B$ are two matrices of the same order and $k$ is a scalar then prove that $k(A+B)=k A+k B$.

**PROOF:** Let $A=\left[a_{i j}\right]_{m \times n}$ and $B=\left[b_{i j}\right]_{m \times n}$. Then,

$$
\begin{aligned}
k(A+B) & =k \cdot\left(\left[a_{i j}\right]_{m \times n}+\left[b_{i j}\right]_{m \times n}\right) \\
& =k \cdot\left[a_{i j}+b_{i j}\right]_{m \times n} \quad[\text { by definition of addition of matrices }] \\
& =\left[k\left(a_{i j}+b_{i j}\right)\right]_{m \times n} \quad[\text { by definition of scalar multiplication }] \\
& =\left[k \cdot a_{i j}+k \cdot b_{i j}\right]_{m \times n} \quad[\text { by distributive law }] \\
& =\left[k \cdot a_{i j}\right]_{m \times n}+\left[k \cdot b_{i j}\right]_{m \times n} \\
& =k A+k B .
\end{aligned}
$$

Hence, $k(A+B)=k A+k B$.

---

### Theorem 2

If $A$ is any matrix and $k_{1}, k_{2}$ are any scalars then prove that
- (i) $\left(k_{1}+k_{2}\right) A=k_{1} A+k_{2} A$
- (ii) $k_{1}\left(k_{2} A\right)=\left(k_{1} k_{2}\right) A$.

**PROOF:** Let $A=\left[a_{i j}\right]_{m \times n}$. Then,

(i)

$$
\begin{aligned}
\left(k_{1}+k_{2}\right) A & =\left(k_{1}+k_{2}\right) \cdot\left[a_{i j}\right]_{m \times n} \\
& =\left[\left(k_{1}+k_{2}\right) \cdot a_{i j}\right]_{m \times n} \text { [by definition of scalar multiplication] } \\
& =\left[k_{1} \cdot a_{i j}+k_{2} \cdot a_{i j}\right]_{m \times n} \quad[\text { by distributive law }] \\
& =\left[k_{1} \cdot a_{i j}\right]_{m \times n}+\left[k_{2} \cdot a_{i j}\right]_{m \times n}
\end{aligned}
$$

[by definition of addition of matrices]

$$
=k_{1} A+k_{2} A .
$$

Hence, $\left(k_{1}+k_{2}\right) A=k_{1} A+k_{2} A$.

(ii)

$$
\begin{aligned}
k_{1}\left(k_{2} A\right) & =k_{1}\left[k_{2} \cdot a_{i j}\right]_{m \times n}=\left[k_{1}\left(k_{2} \cdot a_{i j}\right)\right]_{m \times n} \\
& =\left[\left(k_{1} k_{2}\right) \cdot a_{i j}\right]_{m \times n}
\end{aligned}
$$

[by associativity of multiplication in numbers]

$$
=\left(k_{1} k_{2}\right) \cdot\left[a_{i j}\right]_{m \times n}=\left(k_{1} k_{2}\right) A .
$$

Hence, $k_{1}\left(k_{2} A\right)=\left(k_{1} k_{2}\right) A$.

---

## Summary

1.  If $A$ and $B$ are comparable matrices and $k$ is a scalar then

$$
k(A+B)=(k A+k B) .
$$

2.  If $k_{1}, k_{2}$ are scalars and $A$ is any matrix then
    - (i) $\left(k_{1}+k_{2}\right) A=\left(k_{1} A+k_{2} A\right)$
    - (ii) $k_{1}\left(k_{2} A\right)=\left(k_{1} k_{2}\right) A$

---

## Solved Examples

### Example: 1

If $A=\left[\begin{array}{cc}3 & 5 \\ 7 & -9\end{array}\right]$ and $B=\left[\begin{array}{cc}6 & -4 \\ 2 & 3\end{array}\right]$, find $(4 A-3 B)$.

#### Solution:

$(4 A-3 B)=4 A+(-3 B)$.

Now, $4 A=\left[\begin{array}{ll}4 \cdot 3 & 4 \cdot 5 \\ 4 \cdot 7 & 4 \cdot(-9)\end{array}\right]=\left[\begin{array}{rr}12 & 20 \\ 28 & -36\end{array}\right]$.

And, $-3 B=(-3) \cdot B=\left[\begin{array}{ll}(-3) \cdot 6 & (-3) \cdot(-4) \\ (-3) \cdot 2 & (-3) \cdot 3\end{array}\right]=\left[\begin{array}{ll}-18 & 12 \\ -6 & -9\end{array}\right]$.

$$
\begin{aligned}
\therefore \quad 4 A-3 B & =4 A+(-3 B) \\
& =\left[\begin{array}{rr}
12 & 20 \\
28 & -36
\end{array}\right]+\left[\begin{array}{rr}
-18 & 12 \\
-6 & -9
\end{array}\right] \\
& =\left[\begin{array}{cc}
12+(-18) & 20+12 \\
28+(-6) & -36+(-9)
\end{array}\right]=\left[\begin{array}{rr}
-6 & 32 \\
22 & -45
\end{array}\right] .
\end{aligned}
$$

Hence, $(4 A-3 B)=\left[\begin{array}{rr}-6 & 32 \\ 22 & -45\end{array}\right]$.

---

### Example: 2

Let $A=\operatorname{diag}[3,-5,7]$ and $B=\operatorname{diag}[-1,2,4]$.
Find (i) $(A+B)$ (ii) $(A-B)$ (iii) $-5 A$ (iv) $(2 A+3 B)$.

#### Solution:

We have

$$
A=\left[\begin{array}{rrr}
3 & 0 & 0 \\
0 & -5 & 0 \\
0 & 0 & 7
\end{array}\right] \text { and } B=\left[\begin{array}{rrr}
-1 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 4
\end{array}\right]
$$

$\therefore$ (i) $A+B=\left[\begin{array}{rrr}3 & 0 & 0 \\ 0 & -5 & 0 \\ 0 & 0 & 7\end{array}\right]+\left[\begin{array}{rrr}-1 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 4\end{array}\right]=\left[\begin{array}{rrr}2 & 0 & 0 \\ 0 & -3 & 0 \\ 0 & 0 & 11\end{array}\right]$.

(ii) $(A-B)=A+(-B)$

$$
=\left[\begin{array}{rrr}
3 & 0 & 0 \\
0 & -5 & 0 \\
0 & 0 & 7
\end{array}\right]+\left[\begin{array}{rrr}
1 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & -4
\end{array}\right]=\left[\begin{
{rrr}
4 & 0 & 0 \\
0 & -7 & 0 \\
0 & 0 & 3
\end{array}\right] .
$$

(iii) $-5 A=(-5) \cdot A=(-5) \cdot\left[\begin{array}{rrr}3 & 0 & 0 \\ 0 & -5 & 0 \\ 0 & 0 & 7\end{array}\right]=\left[\begin{array}{rrr}-15 & 0 & 0 \\ 0 & 25 & 0 \\ 0 & 0 & -35\end{array}\right]$.

(iv) $2 A+3 B=\left[\begin{array}{rrr}6 & 0 & 0 \\ 0 & -10 & 0 \\ 0 & 0 & 14\end{array}\right]+\left[\begin{array}{rrr}-3 & 0 & 0 \\ 0 & 6 & 0 \\ 0 & 0 & 12\end{array}\right]=\left[\begin{array}{rrr}3 & 0 & 0 \\ 0 & -4 & 0 \\ 0 & 0 & 26\end{array}\right]$.

---

### Example: 3

Simplify $\cos \theta \cdot\left[\begin{array}{rr}\cos \theta & \sin \theta \\ -\sin \theta & \cos \theta\end{array}\right]+\sin \theta \cdot\left[\begin{array}{rr}\sin \theta & -\cos \theta \\ \cos \theta & \sin \theta\end{array}\right]$.
[CBSE 2012]

#### Solution:

We have

$$
\begin{aligned}
\cos \theta & \cdot\left[\begin{array}{cc}
\cos \theta & \sin \theta \\
-\sin \theta & \cos \theta
\end{array}\right]+\sin \theta \cdot\left[\begin{array}{rr}
\sin \theta & -\cos \theta \\
-\cos \theta & \sin \theta
\end{array}\right] \\
& =\left[\begin{array}{ccc}
\cos ^{2} \theta & \sin \theta & \cos \theta \\
-\sin \theta & \cos \theta & \cos 2 \theta
\end{array}\right]+\left[\begin{array}{ccc}
\sin ^{2} \theta & -\sin \theta & \cos \theta \\
\sin \theta & \cos \theta & \sin ^{2} \theta
\end{array}\right] \\
& =\left[\begin{array}{ccc}
\cos ^{2} \theta+\sin ^{2} \theta & \sin \theta & \cos \theta+(-\sin \theta \\
-\sin \theta & \cos \theta+\sin \theta & \cos \theta
\end{array}\right] \\
& =\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right] .
\end{aligned}
$$

---

### Example: 4

If $2\left[\begin{array}{cc}3 & 4 \\ 5 & x\end{array}\right]+\left[\begin{array}{cc}1 & y \\ 0 & 1\end{array}\right]=\left[\begin{array}{cc}7 & 0 \\ 10 & 5\end{array}\right]$, find $(x-y)$.
[CBSE 2014]

#### Solution:

We have

$$
\begin{aligned}
& 2\left[\begin{array}{cc}
3 & 4 \\
5 & x
\end{array}\right]+\left[\begin{array}{ll}
1 & y \\
0 & 1
\end{array}\right]=\left[\begin{array}{cc}
7 & 0 \\
10 & 5
\end{array}\right] \\
\Rightarrow & {\left[\begin{array}{cc}
6 & 8 \\
10 & 2 x
\end{array}\right]+\left[\begin{array}{ll}
1 & y \\
0 & 1
\end{array}\right]=\left[\begin{array}{cc}
7 & 0 \\
10 & 5
\end{array}\right] } \\
\Rightarrow & {\left[\begin{array}{cc}
6+1 & 8+y \\
10+0 & 2 x+1
\end{array}\right]=\left[\begin{array}{cc}
7 & 0 \\
10 & 5
\end{array}\right] } \\
\Rightarrow & 2 x+1=5 \text { and } 8+y=0
\end{aligned}
$$

[comparing the corresponding elements]
$\Rightarrow \quad x=2$ and $y=-8$.
$\Rightarrow \quad(x-y)=2-(-8)=10$.

---

### Example: 5

Find a matrix $X$, if $X+\left[\begin{array}{rr}4 & 6 \\ -3 & 7\end{array}\right]=\left[\begin{array}{rr}3 & -6 \\ 5 & -8\end{array}\right]$.

#### Solution:

Let $A=\left[\begin{array}{rr}4 & 6 \\ -3 & 7\end{array}\right]$ and $B=\left[\begin{array}{rr}3 & -6 \\ 5 & -8\end{array}\right]$.
Then, the given matrix equation is $X+A=B$.

$$
\begin{aligned}
\therefore \quad X+A=B \Rightarrow X & =B+(-A) \\
& =\left[\begin{array}{ll}
3 & -6 \\
5 & -8
\end{array}\right]+\left[\begin{array}{rr}
-4 & -6 \\
3 & -7
\end{array}\right] \\
& =\left[\begin{array}{cc}
3+(-4) & -6+(-6) \\
5+3 & -8+(-7)
\end{array}\right]=\left[\begin{
{rr}
-1 & -12 \\
8 & -15
\end{array}\right] .
\end{aligned}
$$

Hence, $X=\left[\begin{array}{rr}-1 & -12 \\ 8 & -15\end{array}\right]$.

---

### Example: 6

Find a matrix $X$ such that $2 A+B+X=O$, where $A=\left[\begin{array}{rr}-1 & 2 \\ 3 & 4\end{array}\right]$ and

$$
B=\left[\begin{array}{rr}
3 & -2 \\
1 & 5
\end{array}\right] .
$$
[CBSE 2002C]

#### Solution:

We have

$$
\begin{aligned}
2 A+B+X & =O \Rightarrow X=-(2 A+B) \\
\text { Now, }(2 A+B) & =2 \cdot\left[\begin{array}{rr}
-1 & 2 \\
3 & 4
\end{array}\right]+\left[\begin{array}{rr}
3 & -2 \\
1 & 5
\end{array}\right] \\
& =\left[\begin{array}{rr}
-2 & 4 \\
6 & 8
\end{array}\right]+\left[\begin{array}{rr}
3 & -2 \\
1 & 5
\end{array}\right]
\end{aligned}
$$

$$
\begin{aligned}
& =\left[\begin{array}{rr}
-2+3 & 4+(-2) \\
6+1 & 8+5
\end{array}\right]=\left[\begin{
{rr}
1 & 2 \\
7 & 13
\end{array}\right] . \\
\therefore \quad X=-(2 A+B) & =\left[\begin{array}{rr}
-1 & -2 \\
-7 & -13
\ends_vector
\end{array}\right] .
\end{aligned}
$$

---

### Example: 7

Find matrices $X$ and $Y$, if $X+Y=\left[\begin{array}{ll}5 & 2 \\ 0 & 9\end{array}\right]$ and $X-Y=\left[\begin{array}{rr}3 & 6 \\ 0 & -1\end{array}\right]$.

#### Solution:

Adding the given matrices, we get

$$
\begin{aligned}
& (X+Y)+(X-Y)=\left[\begin{array}{ll}
5 & 2 \\
0 & 9
\end{array}\right]+\left[\begin{array}{rr}
3 & 6 \\
0 & -1
\end{array}\right] \\
\Rightarrow & 2 X=\left[\begin{array}{ll}
5+3 & 2+6 \\
0+0 & 9+(-1)
\end{array}\right] \\
\Rightarrow & 2 X=\left[\begin{array}{ll}
8 & 8 \\
0 & 8
\end{array}\right] \Rightarrow X=\frac{1}{2} \cdot\left[\begin{array}{ll}
8 & 8 \\
0 & 8
\end{array}\right]=\left[\begin{
{ll}
4 & 4 \\
0 & 4
\end{array}\right] .
\end{aligned}
$$

On subtracting the given matrices, we get

$$
\begin{array}{ll} 
& (X+Y)-(X-Y)=\left[\begin{array}{ll}
5 & 2 \\
0 & 9
\end{array}\right]-\left[\begin{
{rr}
3 & 6 \\
0 & -1
\end{array}\right] \\
\Rightarrow & 2 Y=\left[\begin{array}{ll}
5-3 & 2-6 \\
0-0 & 9-(-1)
\end{array}\right]=\left[\begin{
{ll}
2 & -4 \\
0 & 10
\end{array}\right] \\
\Rightarrow & Y=\frac{1}{2}\left[\begin{array}{ll}
2 & -4 \\
0 & 10
\end{array}\right]=\left[\begin{
{rr}
1 & -2 \\
0 & 5
\end{array}\right] .
\end{array}
$$

Hence, $X=\left[\begin{array}{ll}4 & 4 \\ 0 & 4\end{array}\right]$ and $Y=\left[\begin{array}{rr}1 & -2 \\ 0 & 5\end{array}\right]$.
