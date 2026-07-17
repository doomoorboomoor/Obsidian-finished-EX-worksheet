## 7. ADJOINT AND INVERSE OF A MATRIX

adjoint of a matrix Let $A=\left[a_{i j}\right]$ be a square matrix of order $n$ and let $A_{i j}$ denote the cofactor of $a_{i j}$ in $|A|$. Then, the adjoint of $A$, denoted by adj $A$, is defined as

$$
\operatorname{adj} A=\left[A_{j i}\right]_{n \times n}
$$

Thus $\operatorname{adj} A$ is the transpose of the matrix of the corresponding cofactors of elements of $|A|$.

If $A=\left[\begin{array}{lll}a_{11} & a_{12} & a_{13} \\ a_{21} & a_{22} & a_{23} \\ a_{31} & a_{32} & a_{33}\end{array}\right]$, then
$\operatorname{adj} A=\left[\begin{array}{lll}A_{11} & A_{12} & A_{13} \\ A_{21} & A_{22} & A_{23} \\ A_{31} & A_{32} & A_{33}\end{array}\right]^{\prime}=\left[\begin{array}{lll}A_{11} & A_{21} & A_{31} \\ A_{12} & A_{22} & A_{32} \\ A_{13} & A_{23} & A_{33}\end{array}\right]$,
where $A_{i j}$ denotes the cofactor of $a_{i j}$ in $|A|$.
EXAMPLE 1 If $A=\left[\begin{array}{ll}2 & 5 \\ 1 & 3\end{array}\right]$, find $\operatorname{adj} A$.
SOLUTION Clearly, $|A|=\left|\begin{array}{ll}2 & 5 \\ 1 & 3\end{array}\right|$.
The cofactors of the elements of $|A|$ are given by

$$
\begin{gathered}
A_{11}=3, A_{12}=-1 ; \\
A_{21}=-5, A_{22}=2 \\
\therefore \quad \operatorname{adj} A=\left[\begin{array}{rr}
3 & -1 \\
-5 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
3 & -5 \\
-1 & 2
\end{array}\right] .
\end{gathered}
$$

EXAMPLE 2 If $A=\left[\begin{array}{rrr}1 & -2 & 4 \\ 0 & 2 & 1 \\ -4 & 5 & 3\end{array}\right]$, find $\operatorname{adj} A$.
SOLUTION We have, $|A|=\left|\begin{array}{rrr}1 & -2 & 4 \\ 0 & 2 & 1 \\ -4 & 5 & 3\end{array}\right|$.

The cofactors of the elements of $|A|$ are given by

$$
\begin{aligned}
& A_{11}=\left|\begin{array}{ll}
2 & 1 \\
5 & 3
\end{array}\right|=1 ; A_{12}=-\left|\begin{array}{rr}
0 & 1 \\
-4 & 3
\end{array}\right|=-4 ; A_{13}=\left|\begin{array}{rr}
0 & 2 \\
-4 & 5
\end{array}\right|=8 ; \\
& A_{21}=-\left|\begin{array}{rr}
-2 & 4 \\
5 & 3
\end{array}\right|=26 ; A_{22}=\left|\begin{array}{rr}
1 & 4 \\
-4 & 3
\end{array}\right|=19 ; A_{23}=-\left|\begin{array}{rr}
1 & -2 \\
-4 & 5
\end{array}\right|=3 ; \\
& A_{31}=\left|\begin{array}{rr}
-2 & 4 \\
2 & 1
\end{array}\right|=-10 ; A_{32}=-\left|\begin{array}{cc}
1 & 4 \\
0 & 1
\end{array}\right|=-1 ; A_{33}=\left|\begin{array}{rr}
1 & -2 \\
0 & 2
\end{array}\right|=2 . \\
& \therefore \operatorname{adj} A=\left[\begin{array}{rrr}
1 & -4 & 8 \\
26 & 19 & 3 \\
-10 & -1 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
1 & 26 & -10 \\
-4 & 19 & -1 \\
8 & 3 & 2
\end{array}\right] .
\end{aligned}
$$

THEOREM 1 If $A$ is a square matrix of order $n$ then prove that

$$
\begin{gathered}
A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I . \\
\text { PROOF Let } A=\left[\begin{array}{cccc}
a_{11} & a_{12} & \ldots & a_{1 n} \\
a_{21} & a_{22} & \ldots & a_{2 n} \\
\ldots & \ldots & \ldots & \ldots \\
\ldots & \ldots & \ldots & \ldots \\
a_{i 1} & a_{i 2} & \ldots & a_{i n} \\
\ldots & \ldots & \ldots & \ldots \\
\ldots & \ldots & \ldots & \ldots \\
a_{n 1} & a_{n 2} & \ldots & a_{n n}
\end{array}\right] . \text { Then, } \\
\operatorname{adj} A=\left[\begin{array}{cccc}
A_{11} & A_{12} & \ldots & A_{1 n} \\
A_{21} & A_{22} & \ldots & A_{2 n} \\
\ldots & \ldots & \ldots & \ldots \\
\ldots & \ldots & \ldots & \ldots \\
A_{k 1} & A_{k 2} & \ldots & A_{k n} \\
\ldots & \ldots & \ldots & \ldots \\
A_{n 1} & A_{n 2} & \ldots & A_{n n}
\end{array}\right]=\left[\begin{array}{cccccc}
A_{11} & A_{21} & \ldots & A_{k 1} & \ldots & A_{n 1} \\
A_{12} & A_{22} & \ldots & A_{k 2} & \ldots & A_{n 2} \\
\ldots & \ldots & \ldots & \ldots & \ldots & \ldots \\
A_{1 n} & A_{2 n} & \ldots & A_{k n} & \ldots & A_{n n}
\end{array}\right] .
\end{gathered}
$$

Now, the $(i, k)$ th element of $A \cdot(\operatorname{adj} A)=a_{i 1} A_{k 1}+a_{i 2} A_{k 2}+\ldots+a_{i n} A_{k n}$

$$
=\left\{\begin{array}{cl}
|A|, & \text { when } i=k \\
0, & \text { when } i \neq k .
\end{array}\right.
$$

This shows that each diagonal element of $A \cdot(\operatorname{adj} A)$ is $|A|$ and each one of its nondiagonal elements is 0 .

$$
\begin{aligned}
\therefore \quad A(\operatorname{adj} A) & =\left[\begin{array}{ccccc}
|A| & 0 & 0 & \ldots & 0 \\
0 & |A| & 0 & \ldots & 0 \\
\ldots & \ldots & \ldots & \ldots & \ldots \\
0 & 0 & 0 & \ldots & |A|
\end{array}\right] \\
& =|A|\left[\begin{array}{ccccc}
1 & 0 & 0 & \ldots & 0 \\
0 & 1 & 0 & \ldots & 0 \\
\ldots & \ldots & \ldots & \ldots & \ldots \\
0 & 0 & 0 & \ldots & 1
\end{array}\right]=|A| \cdot I .
\end{aligned}
$$

Thus, $A(\operatorname{adj} A)=|A| \cdot I$.
Similarly, $(\operatorname{adj} A) A=|A| \cdot I$.
Hence, $\quad A(\operatorname{adj} A)=(\operatorname{adj} A) A=|A| \cdot I$.

## SUMMARY

For every square matrix $A$, we have
$A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I$.
EXAMPLE 3 If $A=\left[\begin{array}{ll}3 & 1 \\ 7 & 5\end{array}\right]$, verify that

$$
A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I .
$$

SOLUTION We have

$$
A=\left[\begin{array}{ll}
3 & 1 \\
7 & 5
\end{array}\right]=(15-7)=8 \neq 0 .
$$

The cofactors of the elements of $|A|$ are given by

$$
\begin{aligned}
& A_{11}=5, A_{12}=-7 ; \\
& A_{21}=-1, A_{22}=3 . \\
\therefore & (\operatorname{adj} A)=\left[\begin{array}{rr}
5 & -7 \\
-1 & 3
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
5 & -1 \\
-7 & 3
\end{array}\right] . \\
\therefore \quad & A \cdot(\operatorname{adj} A)=\left[\begin{array}{ll}
3 & 1 \\
7 & 5
\end{array}\right]\left[\begin{array}{rr}
5 & -1 \\
-7 & 3
\end{array}\right] \\
& =\left[\begin{array}{ll}
15-7 & -3+3 \\
35-35 & -7+15
\end{array}\right]=\left[\begin{array}{ll}
8 & 0 \\
0 & 8
\end{array}\right] \\
& =8 \cdot\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right]=8 I=|A| \cdot I \quad[\because \quad|A|=8] .
\end{aligned}
$$

And, $(\operatorname{adj} A) \cdot A=\left[\begin{array}{rr}5 & -1 \\ -7 & 3\end{array}\right]\left[\begin{array}{ll}3 & 1 \\ 7 & 5\end{array}\right]$

$$
=\left[\begin{array}{rr}
15-7 & 5-5 \\
-21+21 & -7+15
\end{array}\right]=\left[\begin{array}{ll}
8 & 0 \\
0 & 8
\end{array}\right]
$$

$$
=8 \cdot\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right]=8 I=|A| \cdot I \quad[\because \quad|A|=8] .
$$

Hence, $A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I$.
EXAMPLE 4 If $A=\left[\begin{array}{rrr}1 & 0 & -1 \\ 3 & 4 & 5 \\ 0 & -6 & -7\end{array}\right]$, verify that

$$
A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I .
$$

SOLUTION We have

$$
|A|=\left|\begin{array}{rrr}
1 & 0 & -1 \\
3 & 4 & 5 \\
0 & -6 & -7
\end{array}\right|=[1 \cdot(-28+30)-1 \cdot(-18-0)]=20 .
$$

Now, the cofactors of the elements of $|A|$ are given by

$$
\begin{aligned}
& A_{11}=\left|\begin{array}{rr}
4 & 5 \\
-6 & -7
\end{array}\right|=2, A_{12}=-\left|\begin{array}{rr}
3 & 5 \\
0 & -7
\end{array}\right|=21, A_{13}=\left|\begin{array}{rr}
3 & 4 \\
0 & -6
\end{array}\right|=-18 ; \\
& A_{21}=-\left|\begin{array}{rr}
0 & -1 \\
-6 & -7
\end{array}\right|=6, A_{22}=\left|\begin{array}{rr}
1 & -1 \\
0 & -7
\end{array}\right|=-7, A_{23}=-\left|\begin{array}{rr}
1 & 0 \\
0 & -6
\end{array}\right|=6 ; \\
& A_{31}=\left|\begin{array}{rr}
0 & -1 \\
4 & 5
\end{array}\right|=4, A_{32}=-\left|\begin{array}{rr}
1 & -1 \\
3 & 5
\end{array}\right|=-8, A_{33}=\left|\begin{array}{ll}
1 & 0 \\
3 & 4
\end{array}\right|=4 .
\end{aligned}
$$

$\therefore \quad \operatorname{adj} A=\left[\begin{array}{rrr}2 & 21 & -18 \\ 6 & -7 & 6 \\ 4 & -8 & 4\end{array}\right]^{\prime}=\left[\begin{array}{rrr}2 & 6 & 4 \\ 21 & -7 & -8 \\ -18 & 6 & 4\end{array}\right]$.
So, $A \cdot(\operatorname{adj} A)=\left[\begin{array}{rrr}1 & 0 & -1 \\ 3 & 4 & 5 \\ 0 & -6 & -7\end{array}\right]\left[\begin{array}{rrr}2 & 6 & 4 \\ 21 & -7 & -8 \\ -18 & 6 & 4\end{array}\right]$

$$
=\left[\begin{array}{rrr}
20 & 0 & 0 \\
0 & 20 & 0 \\
0 & 0 & 20
\end{array}\right]=20 \cdot\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}|=|A| \cdot I .\right.
$$

Thus, $A \cdot(\operatorname{adj} A)=|A| \cdot I$.
Further, $(\operatorname{adj} A) \cdot A=\left[\begin{array}{rrr}2 & 6 & 4 \\ 21 & -7 & -8 \\ -18 & 6 & 4\end{array}\right] \cdot\left[\begin{array}{rrr}1 & 0 & -1 \\ 3 & 4 & 5 \\ 0 & -6 & -7\end{array}\right]$

$$
=\left[\begin{array}{rrr}
20 & 0 & 0 \\
0 & 20 & 0 \\
0 & 0 & 20
\end{array}\right]=20 \cdot\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}|=|A| \cdot I .\right.
$$

Thus, $(\operatorname{adj} A) \cdot A=|A| \cdot I$.
Hence, $\quad A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I$.

SINGULAR AND NONSINGULAR MATRICES $A$ square matrix $A$ is said to be

$$
\text { (i) singular if }|A|=0 \text {, (ii) nonsingular if }|A| \neq 0 \text {. }
$$

Examples (i) Let $A=\left[\begin{array}{ll}1 & 2 \\ 4 & 8\end{array}\right]$. Then,

$$
|A|=\left|\begin{array}{ll}
1 & 2 \\
4 & 8
\end{array}\right|=(8-8)=0 \text { and therefore, } A \text { is singular. }
$$

(ii) Let $B=\left[\begin{array}{ll}1 & 2 \\ 3 & 4\end{array}\right]$. Then,

$$
|B|=\left|\begin{array}{ll}
1 & 2 \\
3 & 4
\end{array}\right|=(4-6)=-2 \neq 0, \text { and }
$$

therefore, $B$ is nonsingular.
INVERTIBLE MATRIX $A$ nonzero square matrix $A$ of order $n$ is said to be invertible if there exists a square matrix $B$ of order $n$ such that $A B=B A=I$.

We say that the inverse of $A$ is $B$ and we write, $A^{-1}=B$.

## RESULTS ON INVERTIBLE MATRICES

THEOREM 2 An invertible matrix possesses a unique inverse.
PROOF Let $A$ be an invertible square of order $n$.
If possible, let $B$ as well as $C$ be the inverse of $A$.
Then, $A B=B A=I$ and $A C=C A=I$.
Now, $A C=I \Rightarrow B(A C)=B \cdot I=B$.
And, $B A=I \Rightarrow(B A) C=I \cdot C=C$.
But $\quad B(A C)=(B A) C \quad$ [by associative law of multiplication].

$$
\therefore \quad B=C .
$$

Hence, an invertible has a unique inverse.
THEOREM 3 A square matrix $A$ is invertible if and only if $A$ is nonsingular, i.e., $A$ is invertible $\Leftrightarrow|A| \neq 0$.
PROOF Let $A$ be an invertible square matrix of order $n$.
Then, there exists a square matrix $B$ of order $n$ such that

$$
A B=B A=I .
$$

Now, $A B=I \Rightarrow|A B|=|I|$

$$
\begin{array}{ll}
\Rightarrow|A| \cdot|B|=1 & {[\because|A B|=|A| \cdot|B| \text { and }|I|=1]} \\
\Rightarrow|A| \neq 0 & {[\because a b=1 \Rightarrow a \neq 0 \text { and } b \neq 0] .}
\end{array}
$$

This shows that $A$ is nonsingular.
Conversely, Let $A$ be nonsingular. Then, $|A| \neq 0$.

$$
\begin{array}{ll}
\therefore \quad & A \cdot(\operatorname{adj} A)=(\operatorname{adj} A) \cdot A=|A| \cdot I \text { and }|A| \neq 0 \\
& \Rightarrow A \cdot\left(\frac{1}{|A|} \cdot \operatorname{adj} A\right)=\left(\frac{1}{|A|} \cdot \operatorname{adj} A\right) \cdot A=I
\end{array}
$$

$$
\Rightarrow A^{-1}=\frac{1}{|A|} \cdot \operatorname{adj} A .
$$

This shows that $A$ is invertible.
Hence, $A$ is invertible $\Leftrightarrow A$ is nonsingular.

## FORMULA FOR FINDING $\boldsymbol{A}^{-\mathbf{1}}$

Let $A$ be a square matrix such that $|A| \neq 0$.
Then, $A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)$.

EXAMPLE 5 Find the inverse of the matrix, $A=\left[\begin{array}{rr}2 & -3 \\ -4 & 7\end{array}\right]$.

## SOLUTION We have

$$
|A|=\left|\begin{array}{rr}
2 & -3 \\
-4 & 7
\end{array}\right|=(14-12)=2 \neq 0 .
$$

So, $A^{-1}$ exists.
The cofactors of the elements of $|A|$ are given by

$$
\begin{aligned}
& \qquad A_{11}=7, A_{12}=-(-4)=4 ; \\
& A_{21}=-(-3)=3, A_{22}=2 . \\
& \therefore \quad(\operatorname{adj} A)=\left[\begin{array}{ll}
7 & 4 \\
3 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{ll}
7 & 3 \\
4 & 2
\end{array}\right] . \\
& \text { Hence, } A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A) \\
& \qquad=\frac{1}{2} \cdot\left[\begin{array}{ll}
7 & 3 \\
4 & 2
\end{array}\right]=\left[\begin{array}{cc}
\frac{7}{2} & \frac{3}{2} \\
2 & 1
\end{array}\right] .
\end{aligned}
$$

EXAMPLE 6 Find the inverse of the matrix $\left[\begin{array}{rrr}3 & -10 & -1 \\ -2 & 8 & 2 \\ 2 & -4 & -2\end{array}\right]$.
SOLUTION Let $\left[\begin{array}{rrr}3 & -10 & -1 \\ -2 & 8 & 2 \\ 2 & -4 & -2\end{array}\right]$. Then,

$$
\begin{aligned}
|A| & =\left|\begin{array}{rrr}
3 & -10 & -1 \\
-2 & 8 & 2 \\
2 & -4 & -2
\end{array}\right|=\left|\begin{array}{rrr}
0 & 0 & -1 \\
4 & -12 & 2 \\
-4 & 16 & -2
\end{array}\right| \\
& {\left[C_{1} \rightarrow C_{1}+3 C_{3} \text { and } C_{2} \rightarrow C_{2}-10 C_{3}\right] } \\
& =(-1) \cdot(64-48)=-16 \neq 0 .
\end{aligned}
$$

Thus, $|A| \neq 0$ and therefore, $A^{-1}$ exists.
Now, the cofactors of the elements of $|A|$ are given by
$A_{11}=\left|\begin{array}{rr}8 & 2 \\ -4 & -2\end{array}\right|=-8, A_{12}=-\left|\begin{array}{rr}-2 & 2 \\ 2 & -2\end{array}\right|=0, A_{13}=\left|\begin{array}{rr}-2 & 8 \\ 2 & -4\end{array}\right|=-8 ;$
$A_{21}=-\left|\begin{array}{rr}-10 & -1 \\ -4 & -2\end{array}\right|=-16, A_{22}=\left|\begin{array}{rr}3 & -1 \\ 2 & -2\end{array}\right|=-4, A_{23}=-\left|\begin{array}{rr}3 & -10 \\ 2 & -4\end{array}\right|=-8 ;$
$A_{31}=\left|\begin{array}{rr}-10 & -1 \\ 8 & 2\end{array}\right|=-12, A_{32}=-\left|\begin{array}{rr}3 & -1 \\ -2 & 2\end{array}\right|=-4, A_{33}=\left|\begin{array}{rr}3 & -10 \\ -2 & 8\end{array}\right|=4$.
$\therefore \quad(\operatorname{adj} A)=\left[\begin{array}{rrr}-8 & 0 & -8 \\ -16 & -4 & -8 \\ -12 & -4 & 4\end{array}\right]^{\prime}=\left[\begin{array}{rrr}-8 & -16 & -12 \\ 0 & -4 & -4 \\ -8 & -8 & 4\end{array}\right]$.
Hence, $\quad A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)$

$$
=\frac{1}{-16} \cdot\left[\begin{array}{rrr}
-8 & -16 & -12 \\
0 & -4 & -4 \\
-8 & -8 & 4
\end{array}\right]=\left[\begin{array}{ccc}
\frac{1}{2} & 1 & \frac{3}{4} \\
0 & \frac{1}{4} & \frac{1}{4} \\
\frac{1}{2} & \frac{1}{2} & -\frac{1}{4}
\end{array}\right] .
$$

## Some Results on Invertible Matrices

THEOREM 1 (Cancellation law) Let $A, B, C$ be three square matrices, each of order $n$ such that $A B=A C$. If $A$ is nonsingular then $B=C$.
proof Let $A, B, C$ be square matrices, each of order $n$ such that $A B=A C$ and $A$ is nonsingular.
Then, $|A| \neq 0$ and therefore, $A^{-1}$ exists.

$$
\begin{aligned}
\therefore \quad A B=A C & \Rightarrow A^{-1}(A B)=A^{-1}(A C) \\
& \Rightarrow\left(A^{-1} A\right) B=\left(A^{-1} A\right) C \\
& \Rightarrow I B=I C \\
& \Rightarrow B=C .
\end{aligned}
$$

Thus, $A B=A C$ and $A$ is nonsingular $\Rightarrow B=C$.
remark If $A B=A C$ and $|A|=0$ then $B$ and $C$ are not necessarily equal.
Example Let $A=\left[\begin{array}{ll}1 & 2 \\ 3 & 6\end{array}\right], B=\left[\begin{array}{ll}2 & 0 \\ 0 & 0\end{array}\right]$ and $C=\left[\begin{array}{ll}0 & 0 \\ 1 & 0\end{array}\right]$.
Then, $|A|=\left|\begin{array}{ll}1 & 2 \\ 3 & 6\end{array}\right|=(6-6)=0$.

Here, $A B=\left[\begin{array}{ll}1 & 2 \\ 3 & 6\end{array}\right]\left[\begin{array}{ll}2 & 0 \\ 0 & 0\end{array}\right]=\left[\begin{array}{ll}2 & 0 \\ 6 & 0\end{array}\right]$
and $A C=\left[\begin{array}{ll}1 & 2 \\ 3 & 6\end{array}\right]\left[\begin{array}{ll}0 & 0 \\ 1 & 0\end{array}\right]=\left[\begin{array}{ll}2 & 0 \\ 6 & 0\end{array}\right]$.
Thus, $A B=A C$ but $B \neq C$.
THEOREM 2 (Reversal law) If $A$ and $B$ are invertible square matrices of the same order then $A B$ is also invertible and $(A B)^{-1}=B^{-1} A^{-1}$.
proof Let $A$ and $B$ be two invertible square matrices, each of order $n$.
Then, $|A| \neq 0$ and $|B| \neq 0$.
$\therefore|A B|=|A| \cdot|B| \neq 0$.
Thus, $A B$ is invertible.
Now, $\quad(A B)\left(B^{-1} A^{-1}\right)=A\left(B B^{-1}\right) A^{-1} \quad$ [by associativity]

$$
\begin{array}{lll}
=(A I) A^{-1} & {[\because} & \left.B B^{-1}=I\right] \\
=A A^{-1}=I & {[\because} & A I=A] .
\end{array}
$$

And, $\left(B^{-1} A^{-1}\right)(A B)=B^{-1}\left(A^{-1} A\right) B$ [by associativity]

$$
\begin{array}{lll}
=B^{-1}(I B) & {[\because} & \left.A^{-1} A=I\right] \\
=B^{-1} B=I & {[\because} & I B=B] .
\end{array}
$$

$\therefore(A B)\left(B^{-1} A^{-1}\right)=\left(B^{-1} A^{-1}\right)(A B)=I$.
Hence, $(A B)^{-1}=B^{-1} A^{-1}$.
THEOREM 3 If $A$ is an invertible square matrix then prove that $A^{\prime}$ is also invertible and $\left(A^{\prime}\right)^{-1}=\left(A^{-1}\right)^{\prime}$.

PROOF Let $A$ be an invertible square matrix of order $n$.
Then, $|A| \neq 0$.
$\therefore\left|A^{\prime}\right|=|A| \neq 0$.
This shows that $A^{\prime}$ is invertible.
Now, $A A^{-1}=A^{-1} A=I$
$\Rightarrow\left(A A^{-1}\right)^{\prime}=\left(A^{-1} A\right)^{\prime}=I^{\prime}$
$\Rightarrow\left(A^{-1}\right)^{\prime} \cdot A^{\prime}=A^{\prime} \cdot\left(A^{-1}\right)^{\prime}=I \quad\left[\because \quad(A B)^{\prime}=B^{\prime} A^{\prime}\right.$ and $\left.I^{\prime}=I\right]$
$\Rightarrow\left(A^{\prime}\right)^{-1}=\left(A^{-1}\right)^{\prime} \quad\left[\because A B=B A=I \Rightarrow B^{-1}=A\right]$.
Hence, $\left(A^{\prime}\right)^{-1}=\left(A^{-1}\right)^{\prime}$.
THEOREM 4 If $A$ is an invertible symmetric then prove that $A^{-1}$ is also symmetric.
PROOF Let $A$ be an invertible symmetric matrix. Then, $A^{\prime}=A$.
We know that $\left(A^{-1}\right)^{\prime}=\left(A^{\prime}\right)^{-1}$.

$$
\therefore\left(A^{-1}\right)^{\prime}=A^{-1} \quad\left[\because \quad A^{\prime}=A\right] .
$$

Hence, $A^{-1}$ is symmetric.
THEOREM 5 If $A$ and $B$ are nonsingular matrices of the same order then prove that

$$
(\operatorname{adj} A B)=(\operatorname{adj} B) \cdot(\operatorname{adj} A) .
$$

PROOF We have

$$
\begin{array}{ll} 
& |A| \neq 0 \text { and }|B| \neq 0 . \\
\therefore \quad & |A B|=|A| \cdot|B| \neq 0 .
\end{array}
$$

So, $(A B)^{-1}$ exists.
Now, $A^{-1}=\frac{\operatorname{adj} A}{|A|} ; B^{-1}=\frac{\operatorname{adj} B}{|B|}$ and $(A B)^{-1}=\frac{\operatorname{adj}(A B)}{|A B|}$.

$$
\begin{aligned}
\therefore \quad \operatorname{adj}(A B)= & |A B| \cdot \frac{\operatorname{adj}(A B)}{|A B|}=|A| \cdot|B| \cdot(A B)^{-1} \\
& {\left[\because|A B|=|A| \cdot|B| \operatorname{and} \frac{\operatorname{adj}(A B)}{|A B|}=(A B)^{-1}\right] } \\
= & |A| \cdot|B| \cdot\left(B^{-1} A^{-1}\right) \quad\left[\because \quad(A B)^{-1}=B^{-1} A^{-1}\right] \\
= & |A| \cdot|B| \cdot \frac{\operatorname{adj} B}{|B|} \cdot \frac{\operatorname{adj} A}{|A|}=(\operatorname{adj} B)(\operatorname{adj} A) .
\end{aligned}
$$

Hence, $\operatorname{adj}(A B)=(\operatorname{adj} B)(\operatorname{adj} A)$.
THEOREM 6 For any square matrix $A$, prove that $(\operatorname{adj} A)^{\prime}=\operatorname{adj} A^{\prime}$.
PROOF Let $A$ be a square matrix of order $n$.
Then, each one of ( $\operatorname{adj} A$ )' and (adj $A^{\prime}$ ) is a square matrix of order $n$.
Also, $(i, j)$ th element of $(\operatorname{adj} A)^{\prime}$
$=(j, i)$ th element of $(\operatorname{adj} A)$
$=\operatorname{cofactor}$ of $(i, j)$ th element of $A$
$=$ cofactor of ( $j, i$ )th element of $A^{\prime}$
$=(i, j)$ th element of ( $\operatorname{adj} A^{\prime}$ ).
Hence, $(\operatorname{adj} A)^{\prime}=\left(\operatorname{adj} A^{\prime}\right)$.
THEOREM 7 If $A$ is a nonsingular square matrix of order $n$ then prove that $|\operatorname{adj} A|=|A|^{n-1}$.

PROOF We have

$$
\begin{aligned}
& A \cdot(\operatorname{adj} A)=|A| \cdot I & & \\
\Rightarrow & |A \cdot(\operatorname{adj} A)|=||A| \cdot I| & & {[\because} \\
\Rightarrow & |A||\operatorname{adj} A|=|A|^{n}|I| & & {\left[\because \quad|k I|=k^{n}|I|\right] } \\
\Rightarrow & |A| \cdot|\operatorname{adj} A|=|A|^{n} & & {[\because \quad|I|=1] } \\
\Rightarrow & |\operatorname{adj} A|=|A|^{n-1} & &
\end{aligned}
$$

Hence, $|\operatorname{adj} A|=|A|^{n-1}$.

THEOREM 8 If $A$ is a nonsingular square matrix of order $n$ then prove that $\operatorname{adj}(\operatorname{adj} A)=|A|^{n-2} A$.

PROOF For any nonsingular $B$ of order $n$, we have

$$
B(\operatorname{adj} B)=|B| \cdot I .
$$

Taking $B=\operatorname{adj} A$, we get

$$
\begin{array}{lll} 
& (\operatorname{adj} A)[\operatorname{adj}(\operatorname{adj} A)]=|\operatorname{adj} A| I \\
\Rightarrow & (\operatorname{adj} A)[\operatorname{adj}(\operatorname{adj} A)]=|A|^{n-1} I & {\left[\because \quad|\operatorname{adj} A|=|A|^{n-1}\right]} \\
\Rightarrow & A(\operatorname{adj} A)[\operatorname{adj}(\operatorname{adj} A)]=|A|^{n-1} A & {\left[\because \quad A I_{n}=A\right]} \\
\Rightarrow & |A| I_{n}[\operatorname{adj}(\operatorname{adj} A)]=|A|^{n-1} A & {[\because \quad A(\operatorname{adj} A)=|A| I]} \\
\Rightarrow & {[\operatorname{adj}(\operatorname{adj} A)]=|A|^{n-2} A .} &
\end{array}
$$

## SOLVED EXAMPLES

EXAMPLE 1 If $A=\left[\begin{array}{ll}3 & 2 \\ 7 & 5\end{array}\right]$ and $B=\left[\begin{array}{ll}6 & 7 \\ 8 & 9\end{array}\right]$, verify that $(A B)^{-1}=B^{-1} A^{-1}$. SOLUTION We have $|A|=\left|\begin{array}{ll}3 & 2 \\ 7 & 5\end{array}\right|=(15-14)=1 \neq 0$.

Cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=5, A_{12}=-7 ; \\
& A_{21}=-2, A_{22}=3 . \\
& \therefore \quad \operatorname{adj} A=\left[\begin{array}{rr}
5 & -7 \\
-2 & 3
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
5 & -2 \\
-7 & 3
\end{array}\right] . \\
& \text { Hence, } A^{-1}=\frac{1}{|A|} \cdot \operatorname{adj} A=\left[\begin{array}{rr}
5 & -2 \\
-7 & 3
\end{array}\right] \quad[\because \quad|A|=1] . \\
& \text { Further, }|B|=\left|\begin{array}{ll}
6 & 7 \\
8 & 9
\end{array}\right|=(54-56)=-2 \neq 0 .
\end{aligned}
$$

Cofactors of the elements of $|B|$ are

$$
\begin{aligned}
& B_{11}=9, B_{12}=-8 ; \\
& B_{21}=-7, B_{22}=6 . \\
\therefore & \operatorname{adj} B=\left[\begin{array}{rr}
9 & -8 \\
-7 & 6
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
9 & -7 \\
-8 & 6
\end{array}\right] . \\
\text { Hence, } & B^{-1}=\frac{1}{|B|} \cdot \operatorname{adj} B=-\frac{1}{2}\left[\begin{array}{rr}
9 & -7 \\
-8 & 6
\end{array}\right] .
\end{aligned}
$$

Now, $\quad|A B|=|A| \cdot|B|=1 \times(-2)=-2 \neq 0$, and $\quad \operatorname{adj} A B=(\operatorname{adj} B) \cdot(\operatorname{adj} A)$

$$
\begin{aligned}
& =\left[\begin{array}{rr}
9 & -7 \\
-8 & 6
\end{array}\right] \cdot\left[\begin{array}{rr}
5 & -2 \\
-7 & 3
\end{array}\right]=\left[\begin{array}{rr}
94 & -39 \\
-82 & 34
\end{array}\right] . \\
\therefore \quad(A B)^{-1} & =\frac{1}{|A B|} \cdot(\operatorname{adj} A B)=\frac{1}{-2} \cdot\left[\begin{array}{rr}
94 & -39 \\
-82 & 34
\end{array}\right] .
\end{aligned}
$$

Also, $B^{-1} A^{-1}=-\frac{1}{2} \cdot\left[\begin{array}{rr}9 & -7 \\ -8 & 6\end{array}\right] \cdot\left[\begin{array}{rr}5 & -2 \\ -7 & 3\end{array}\right]=-\frac{1}{2} \cdot\left[\begin{array}{rr}94 & -39 \\ -82 & 34\end{array}\right]$.
Hence, $(A B)^{-1}=B^{-1} A^{-1}$.
EXAMPLE 2 Show that the matrix $A=\left[\begin{array}{lll}1 & 2 & 2 \\ 2 & 1 & 2 \\ 2 & 2 & 1\end{array}\right]$ satisfies the equation

$$
A^{2}-4 A-5 I=O, \text { and hence find } A^{-1} .
$$

[CBSE 2008]
SOLUTION We leave it to the reader to show that $A^{2}-4 A-5 I=O$.
Now, $A^{2}-4 A-5 I=O$
$\Rightarrow A A-4 A=5 I$
$\Rightarrow \quad(A A) \cdot A^{-1}-4 A \cdot A^{-1}=5 I \cdot A^{-1}$
$\Rightarrow A\left(A A^{-1}\right)-4 I=5 A^{-1}$
$\Rightarrow A I-4 I=5 A^{-1}$
$\Rightarrow A-4 I=5 A^{-1}$
$\Rightarrow \quad A^{-1}=\frac{1}{5}(A-4 I)$.
$\therefore \quad A^{-1}=\frac{1}{5} \cdot\left\{\left[\begin{array}{lll}1 & 2 & 2 \\ 2 & 1 & 2 \\ 2 & 2 & 1\end{array}\right]-4 \cdot\left[\begin{array}{lll}1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1\end{array}\right]\right\}$
$=\frac{1}{5} \cdot\left\{\left[\begin{array}{lll}1 & 2 & 2 \\ 2 & 1 & 2 \\ 2 & 2 & 1\end{array}\right]-\left[\begin{array}{lll}4 & 0 & 0 \\ 0 & 4 & 0 \\ 0 & 0 & 4\end{array}\right]\right\}$
$=\frac{1}{5} \cdot\left[\begin{array}{rrr}-3 & 2 & 2 \\ 2 & -3 & 2 \\ 2 & 2 & -3\end{array}\right]$.
EXAMPLE 3 Find a matrix $X$ such that $X \cdot\left[\begin{array}{rr}3 & 2 \\ 1 & -1\end{array}\right]=\left[\begin{array}{ll}4 & 1 \\ 2 & 3\end{array}\right]$.
SOLUTION Let $A=\left[\begin{array}{rr}3 & 2 \\ 1 & -1\end{array}\right]$ and $B=\left[\begin{array}{ll}4 & 1 \\ 2 & 3\end{array}\right]$.

Here, $\quad|A|=\left|\begin{array}{rr}3 & 2 \\ 1 & -1\end{array}\right|=(-3-2)=-5 \neq 0$.
So, $A$ is nonsingular and therefore, invertible.
The given equation is $X A=B$.
Now,

$$
\begin{aligned}
X A=B & \Rightarrow(X A) \cdot A^{-1}=B A^{-1} \\
& \Rightarrow X\left(A A^{-1}\right)=B A^{-1} \\
& \Rightarrow X I=B A^{-1} \\
& \Rightarrow X=B A^{-1} .
\end{aligned}
$$

Now, cofactors of elements of $|A|$ are

$$
\begin{gathered}
A_{11}=-1, A_{12}=-1 ; \\
A_{21}=-2, A_{22}=3 . \\
\therefore \quad \operatorname{adj} A=\left[\begin{array}{rr}
-1 & -1 \\
-2 & 3
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
-1 & -2 \\
-1 & 3
\end{array}\right] . \\
\therefore \quad A^{-1}=\frac{1}{|A|} \cdot \operatorname{adj} A=-\frac{1}{5} \cdot\left[\begin{array}{rr}
-1 & -2 \\
-1 & 3
\end{array}\right] . \\
\text { Hence, } X=B A^{-1} \\
=\left[\begin{array}{rr}
4 & 1 \\
2 & 3
\end{array}\right] \cdot\left(-\frac{1}{5}\right) \cdot\left[\begin{array}{rr}
-1 & -2 \\
-1 & 3
\end{array}\right] \\
=\left(-\frac{1}{5}\right) \cdot\left[\begin{array}{rr}
4 & 1 \\
2 & 3
\end{array}\right]\left[\begin{array}{rr}
-1 & -2 \\
-1 & 3
\end{array}\right] \\
=\left(-\frac{1}{5}\right) \cdot\left[\begin{array}{rr}
-5 & -5 \\
-5 & 5
\end{array}\right]=\left[\begin{array}{rr}
1 & 1 \\
1 & -1
\end{array}\right]
\end{gathered}
$$

EXAMPLE 4 Find the matrix $A$ satisfying the equation

$$
\left[\begin{array}{ll}
2 & 1 \\
3 & 2
\end{array}\right] \cdot A \cdot\left[\begin{array}{rr}
-3 & 2 \\
5 & -3
\end{array}\right]=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right] .
$$

SOLUTION Let $B=\left[\begin{array}{ll}2 & 1 \\ 3 & 2\end{array}\right]$ and $C=\left[\begin{array}{rr}-3 & 2 \\ 5 & -3\end{array}\right]$.
Clearly, $|B|=\left|\begin{array}{ll}2 & 1 \\ 3 & 2\end{array}\right|=(4-3)=1 \neq 0$.
And, $|C|=\left|\begin{array}{rr}-3 & 2 \\ 5 & -3\end{array}\right|=(9-10)=-1 \neq 0$.
This shows that $B$ as well as $C$ is invertible.
The given matrix equation is $B A C=I$.
Now, $B A C=I \Rightarrow B^{-1} B A C C^{-1}=B^{-1} I C^{-1}$

$$
\begin{aligned}
& \Rightarrow I A I=B^{-1} C^{-1} \\
& \Rightarrow A=B^{-1} C^{-1} .
\end{aligned}
$$

Now, the cofactors of the elements of $|B|$ are

$$
B_{11}=2, \quad B_{12}=-3 ; \quad B_{21}=-1, \quad B_{22}=2 .
$$

$\therefore \quad \operatorname{adj} B=\left[\begin{array}{rr}2 & -3 \\ -1 & 2\end{array}\right]^{\prime}=\left[\begin{array}{rr}2 & -1 \\ -3 & 2\end{array}\right]$.
So, $\quad B^{-1}=\frac{1}{|B|} \cdot \operatorname{adj} B=\left[\begin{array}{rr}2 & -1 \\ -3 & 2\end{array}\right] \quad[\because \quad|B|=1]$.
Again, the cofactors of the elements of $|C|$ are

$$
C_{11}=-3, C_{12}=-5 ; C_{21}=-2, C_{22}=-3 .
$$

$\therefore \quad \operatorname{adj} C=\left[\begin{array}{ll}-3 & -5 \\ -2 & -3\end{array}\right]^{\prime}=\left[\begin{array}{ll}-3 & -2 \\ -5 & -3\end{array}\right]$
$\Rightarrow \quad C^{-1}=\frac{1}{|C|} \cdot(\operatorname{adj} C)=\frac{1}{(-1)} \cdot\left[\begin{array}{cc}-3 & -2 \\ -5 & -3\end{array}\right]=\left[\begin{array}{ll}3 & 2 \\ 5 & 3\end{array}\right]$
$\Rightarrow A=\left(B^{-1} C^{-1}\right)=\left[\begin{array}{rr}2 & -1 \\ -3 & 2\end{array}\right]\left[\begin{array}{ll}3 & 2 \\ 5 & 3\end{array}\right]=\left[\begin{array}{ll}1 & 1 \\ 1 & 0\end{array}\right]$.
EXAMPLE 5 If $A=\left[\begin{array}{rr}2 & -3 \\ 4 & 6\end{array}\right]$, verify that $(\operatorname{adj} A)^{-1}=\left(\operatorname{adj} A^{-1}\right)$.
SOLUTION We have, $|A|=\left|\begin{array}{rr}2 & -3 \\ 4 & 6\end{array}\right|=(12+12)=24 \neq 0$.
Cofactors of the elements of $|A|$ are

$$
A_{11}=6, A_{12}=-4 ; A_{21}=3, A_{22}=2 .
$$

$\therefore \quad \operatorname{adj} A=\left[\begin{array}{rr}6 & -4 \\ 3 & 2\end{array}\right]^{\prime}=\left[\begin{array}{rr}6 & 3 \\ -4 & 2\end{array}\right]$.
So, $A^{-1}=\frac{1}{|A|} \cdot \operatorname{adj} A=\frac{1}{24} \cdot\left[\begin{array}{rr}6 & 3 \\ -4 & 2\end{array}\right]=\left[\begin{array}{rr}\frac{1}{4} & \frac{1}{8} \\ -\frac{1}{6} & \frac{1}{12}\end{array}\right]$.
Now, $\left|A^{-1}\right|=\left|\begin{array}{cc}\frac{1}{4} & \frac{1}{8} \\ -\frac{1}{6} & \frac{1}{12}\end{array}\right|=\left(\frac{1}{48}+\frac{1}{48}\right)=\frac{1}{24}$.
Cofactors of the elements of $\left|A^{-1}\right|$ are

$$
C_{11}=\frac{1}{12}, C_{12}=\frac{1}{6} ; C_{21}=-\frac{1}{8}, C_{22}=\frac{1}{4} .
$$

$\therefore \quad \operatorname{adj} A^{-1}=\left[\begin{array}{cc}\frac{1}{12} & \frac{1}{6} \\ -\frac{1}{8} & \frac{1}{4}\end{array}\right]^{\prime}=\left[\begin{array}{cc}\frac{1}{12} & \frac{-1}{8} \\ \frac{1}{6} & \frac{1}{4}\end{array}\right]$.
$\therefore \quad(\operatorname{adj} A)\left(\operatorname{adj} A^{-1}\right)=\left[\begin{array}{rr}6 & 3 \\ -4 & 2\end{array}\right]\left[\begin{array}{cc}\frac{1}{12} & \frac{-1}{8} \\ \frac{1}{6} & \frac{1}{4}\end{array}\right]=\left[\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right]=I$.
And, $\left(\operatorname{adj} A^{-1}\right)(\operatorname{adj} A)=\left[\begin{array}{cc}\frac{1}{12} & \frac{-1}{8} \\ \frac{1}{6} & \frac{1}{4}\end{array}\right]\left[\begin{array}{rr}6 & 3 \\ -4 & 2\end{array}\right]=\left[\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right]=I$.
Thus, $(\operatorname{adj} A)\left(\operatorname{adj} A^{-1}\right)=\left(\operatorname{adj} A^{-1}\right)(\operatorname{adj} A)=I$.
Hence, $(\operatorname{adj} A)^{-1}=\left(\operatorname{adj} A^{-1}\right)$.
EXAMPLE 6 If $A=\left[\begin{array}{rrr}1 & -2 & 1 \\ -2 & 3 & 1 \\ 1 & 1 & 5\end{array}\right]$, verify that $(\operatorname{adj} A)^{-1}=\left(\operatorname{adj} A^{-1}\right)$.
SOLUTION We have

$$
\begin{aligned}
|A| & =\left[\begin{array}{rrr}
1 & -2 & 1 \\
-2 & 3 & 1 \\
1 & 1 & 5
\end{array}\right]=\left[\begin{array}{rrr}
1 & -2 & 1 \\
0 & -1 & 3 \\
0 & 3 & 4
\end{array}\right]\left[\begin{array}{l}
R_{2} \rightarrow R_{2}+2 R_{1} \\
R_{3} \rightarrow R_{3}-R_{1}
\end{array}\right] \\
& =1 \cdot(-4-9)=-13 \neq 0 .
\end{aligned}
$$

So, $A^{-1}$ exists.
The cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=\left|\begin{array}{ll}
3 & 1 \\
1 & 5
\end{array}\right|=14, A_{12}=-\left|\begin{array}{rr}
-2 & 1 \\
1 & 5
\end{array}\right|=11, A_{13}=\left|\begin{array}{rr}
-2 & 3 \\
1 & 1
\end{array}\right|=-5 ; \\
& A_{21}=-\left|\begin{array}{rr}
-2 & 1 \\
1 & 5
\end{array}\right|=11, A_{22}=\left|\begin{array}{rr}
1 & 1 \\
1 & 5
\end{array}\right|=4, A_{23}=-\left|\begin{array}{rr}
1 & -2 \\
1 & 1
\end{array}\right|=-3 ; \\
& A_{31}=\left|\begin{array}{rr}
-2 & 1 \\
3 & 1
\end{array}\right|=-5, A_{32}=-\left|\begin{array}{rr}
1 & 1 \\
-2 & 1
\end{array}\right|=-3, A_{33}=\left|\begin{array}{rr}
1 & -2 \\
-2 & 3
\end{array}\right|=-1 . \\
\therefore & (\operatorname{adj} A)=\left[\begin{array}{rrr}
14 & 11 & -5 \\
11 & 4 & -3 \\
-5 & -3 & -1
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
14 & 11 & -5 \\
11 & 4 & -3 \\
-5 & -3 & -1
\end{array}\right]
\end{aligned}
$$

$$
\Rightarrow A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)=\frac{1}{-13} \cdot\left[\begin{array}{ccc}
14 & 11 & -5 \\
11 & 4 & -3 \\
-5 & -3 & -1
\end{array}\right]=\left[\begin{array}{ccc}
\frac{-14}{13} & \frac{-11}{13} & \frac{5}{13} \\
\frac{-11}{13} & \frac{-4}{13} & \frac{3}{13} \\
\frac{5}{13} & \frac{3}{13} & \frac{1}{13}
\end{array}\right] .
$$

The cofactors of the elements of $\left|A^{-1}\right|$ are

$$
\begin{aligned}
& C_{11}=\left|\begin{array}{cc}
\frac{-4}{13} & \frac{3}{13} \\
\frac{3}{13} & \frac{1}{13}
\end{array}\right|=\frac{-1}{13}, C_{12}=-\left|\begin{array}{cc}
\frac{-11}{13} & \frac{3}{13} \\
\frac{5}{13} & \frac{1}{13}
\end{array}\right|=\frac{2}{13}, \\
& C_{13}=\left|\begin{array}{cc}
\frac{-11}{13} & \frac{-4}{13} \\
\frac{5}{13} & \frac{3}{13}
\end{array}\right|=\frac{-1}{13} ; \\
& C_{21}=-\left|\begin{array}{cc}
\frac{-11}{13} & \frac{5}{13} \\
\frac{3}{13} & \frac{1}{13}
\end{array}\right|=\frac{2}{13}, C_{22}=\left|\begin{array}{cc}
\frac{-14}{13} & \frac{5}{13} \\
\frac{5}{13} & \frac{1}{13}
\end{array}\right|=\frac{-3}{13}, \\
& C_{23}=-\left|\begin{array}{cc}
\frac{-14}{13} & \frac{-11}{13} \\
\frac{5}{13} & \frac{3}{13}
\end{array}\right|=\frac{-1}{13} ; \\
& C_{31}=\left|\begin{array}{cc}
\frac{-11}{13} & \frac{5}{13} \\
\frac{-4}{13} & \frac{3}{13}
\end{array}\right|=\frac{-1}{13}, C_{32}=-\left|\begin{array}{cc}
\frac{-14}{13} & \frac{5}{13} \\
\frac{-11}{13} & \frac{3}{13}
\end{array}\right|=\frac{-1}{13}, \\
& C_{33}=\left|\begin{array}{cc}
\frac{-14}{13} & \frac{-11}{13} \\
\frac{-11}{13} & \frac{-4}{13}
\end{array}\right|=\frac{-5}{13} . \\
& \therefore \quad\left(\operatorname{adj} A^{-1}\right)=\left[\left.\begin{array}{ccc}
\frac{-1}{13} & \frac{2}{13} & \frac{-1}{13} \\
\frac{2}{13} & \frac{-3}{13} & \frac{-1}{13} \\
\frac{-1}{13} & \frac{-1}{13} & \frac{-5}{13}
\end{array}\right|^{\prime}=\left[\begin{array}{ccc}
\frac{-1}{13} & \frac{2}{13} & \frac{-1}{13} \\
\frac{2}{13} & \frac{-3}{13} & \frac{-1}{13} \\
\frac{-1}{13} & \frac{-1}{13} & \frac{-5}{13}
\end{array}\right] .\right.
\end{aligned}
$$

$\therefore \quad(\operatorname{adj} A)\left(\operatorname{adj} A^{-1}\right)=\left[\begin{array}{ccc}14 & 11 & -5 \\ 11 & 4 & -3 \\ -5 & -3 & -1\end{array}\right]\left[\begin{array}{ccc}\frac{-1}{13} & \frac{2}{13} & \frac{-1}{13} \\ \frac{2}{13} & \frac{-3}{13} & \frac{-1}{13} \\ \frac{-1}{13} & \frac{-1}{13} & \frac{-5}{13}\end{array}\right]$

$$
=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] .
$$

Thus, $(\operatorname{adj} A)\left(\operatorname{adj} A^{-1}\right)=I$. Similarly, $\left(\operatorname{adj} A^{-1}\right)(\operatorname{adj} A)=I$.
Hence, $(\operatorname{adj} A)^{-1}=\left(\operatorname{adj} A^{-1}\right)$.
EXAMPLE 7 If $A=\left[\begin{array}{ll}2 & 3 \\ 1 & 5\end{array}\right]$, verify that $\left(A^{\prime}\right)^{-1}=\left(A^{-1}\right)^{\prime}$.
solution Given: $A=\left[\begin{array}{ll}2 & 3 \\ 1 & 5\end{array}\right]$, and therefore $A^{\prime}=\left[\begin{array}{ll}2 & 1 \\ 3 & 5\end{array}\right]$.
$\therefore \quad|A|=\left|\begin{array}{ll}2 & 3 \\ 1 & 5\end{array}\right|=(10-3)=7 \neq 0$.
So, $A^{-1}$ exists.
The cofactors of the elements of $|A|$ are

$$
\begin{align*}
& A_{11}=5, A_{12}=-1 ; A_{21}=-3, A_{22}=2 . \\
\therefore & (\operatorname{adj} A)=\left[\begin{array}{rr}
5 & -1 \\
-3 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
5 & -3 \\
-1 & 2
\end{array}\right] \\
\Rightarrow & A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)=\frac{1}{7} \cdot\left[\begin{array}{rr}
5 & -3 \\
-1 & 2
\end{array}\right]=\left[\begin{array}{cc}
\frac{5}{7} & \frac{-3}{7} \\
\frac{-1}{7} & \frac{2}{7}
\end{array}\right] \\
\Rightarrow & \left(A^{-1}\right)^{\prime}=\left[\begin{array}{cc}
\frac{5}{7} & \frac{-1}{7} \\
\frac{-3}{7} & \frac{2}{7}
\end{array}\right] . \tag{i}
\end{align*}
$$

Also, $\left|A^{\prime}\right|=|A|=7 \neq 0$.
So, $\left(A^{\prime}\right)^{-1}$ exists.
The cofactors of elements of $\left|A^{\prime}\right|$ are

$$
\begin{aligned}
& C_{11}=5, C_{12}=-3 ; C_{21}=-1, C_{22}=2 . \\
\therefore & \left(\operatorname{adj} A^{\prime}\right)=\left[\begin{array}{rr}
5 & -3 \\
-1 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
5 & -1 \\
-3 & 2
\end{array}\right]
\end{aligned}
$$

$$
\begin{align*}
& \Rightarrow \quad\left(A^{\prime}\right)^{-1}=\frac{1}{\left|A^{\prime}\right|} \cdot\left(\operatorname{adj} A^{\prime}\right)=\frac{1}{7} \cdot\left[\begin{array}{rr}
5 & -1 \\
-3 & 2
\end{array}\right] \\
& \Rightarrow \quad\left(A^{\prime}\right)^{-1}=\left[\begin{array}{rr}
\frac{5}{7} & \frac{-1}{7} \\
\frac{-3}{7} & \frac{2}{7}
\end{array}\right] . \tag{ii}
\end{align*}
$$

Hence, from (i) and (ii), we get $\left(A^{\prime}\right)^{-1}=\left(A^{-1}\right)^{\prime}$.
EXAMPLE 8 If $A=\left[\begin{array}{cc}1 & \tan x \\ -\tan x & 1\end{array}\right]$, show that $A^{\prime} A^{-1}=\left[\begin{array}{rr}\cos 2 x & -\sin 2 x \\ \sin 2 x & \cos 2 x\end{array}\right]$.
SOLUTION We have

$$
|A|=\left[\begin{array}{cc}
1 & \tan x \\
-\tan x & 1
\end{array}\right]=\left(1+\tan ^{2} x\right)=\sec ^{2} x \neq 0 .
$$

So, $A$ is invertible.
The cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=1, A_{12}=\tan x ; A_{21}=-\tan x, A_{22}=1 . \\
& \therefore \quad(\operatorname{adj} A)=\left[\begin{array}{cc}
1 & \tan x \\
-\tan x & 1
\end{array}\right]^{\prime}=\left[\begin{array}{cc}
1 & -\tan x \\
\tan x & 1
\end{array}\right] \\
& \Rightarrow \quad A^{-1}=\frac{1}{|A|}(\operatorname{adj} A)=\frac{1}{\sec ^{2} x} \cdot\left[\begin{array}{cc}
1 & -\tan x \\
\tan x & 1
\end{array}\right] \\
&=\cos ^{2} x \cdot\left[\begin{array}{cc}
1 & -\tan x \\
\tan x & 1
\end{array}\right]=\left[\begin{array}{cc}
\cos ^{2} x & -\tan x \cos ^{2} x \\
\tan x \cos ^{2} x & \cos ^{2} x
\end{array}\right] \\
&=\left[\begin{array}{cc}
\cos ^{2} x & -\sin x \cos x \\
\sin x \cos x & \cos ^{2} x
\end{array}\right] \\
& \Rightarrow \quad A^{\prime} A^{-1}=\left[\begin{array}{cc}
1 & -\tan x \\
\tan x & 1
\end{array}\right]\left[\begin{array}{cc}
\cos ^{2} x & -\sin x \cos x \\
\sin x \cos x & \cos ^{2} x
\end{array}\right] \\
&=\left[\begin{array}{cc}
\cos ^{2} x-\sin x^{2} x & -2 \sin x \cos x \\
2 \sin x \cos x & -\sin x^{2} x+\cos x^{2} x
\end{array}\right] \\
&=\left[\begin{array}{cc}
\cos 2 x & -\sin 2 x \\
\sin 2 x & \cos 2 x
\end{array}\right] . \\
& \text { Hence, } A^{\prime} A^{-1}=\left[\begin{array}{cc}
\cos 2 x & -\sin 2 x \\
\sin 2 x & \cos 2 x
\end{array}\right] .
\end{aligned}
$$

EXAMPLE 9 Let $F(\alpha)=\left[\begin{array}{ccc}\cos \alpha & -\sin \alpha & 0 \\ \sin \alpha & \cos \alpha & 0 \\ 0 & 0 & 1\end{array}\right]$ and $G(\beta)=\left[\begin{array}{ccc}\cos \beta & 0 & \sin \beta \\ 0 & 1 & 0 \\ -\sin \beta & 0 & \cos \beta\end{array}\right]$.
Show that $[F(\alpha) \cdot G(\beta)]^{-1}=G(-\beta) \cdot F(-\alpha)$.
SOLUTION We have

$$
\begin{aligned}
F(\alpha) \cdot F(-\alpha) & =\left[\begin{array}{ccc}
\cos \alpha & -\sin \alpha & 0 \\
\sin \alpha & \cos \alpha & 0 \\
0 & 0 & 1
\end{array}\right]\left[\begin{array}{ccc}
\cos (-\alpha) & -\sin (-\alpha) & 0 \\
\sin (-\alpha) & \cos (-\alpha) & 0 \\
0 & 0 & 1
\end{array}\right] \\
& =\left[\begin{array}{ccc}
\cos \alpha & -\sin \alpha & 0 \\
\sin \alpha & \cos \alpha & 0 \\
0 & 0 & 1
\end{array}\right]\left[\begin{array}{ccc}
\cos \alpha & \sin \alpha & 0 \\
-\sin \alpha & \cos \alpha & 0 \\
0 & 0 & 1
\end{array}\right] \\
& =\left[\begin{array}{ccc}
\cos ^{2} \alpha+\sin ^{2} \alpha & 0 & 0 \\
0 & \sin ^{2} \alpha+\cos ^{2} \alpha & 0 \\
0 & 0 & 1
\end{array}\right]=\left[\begin{array}{ccc}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]=I .
\end{aligned}
$$

Thus, $F(\alpha) \cdot F(-\alpha)=I \Rightarrow\{F(\alpha)\}^{-1}=F(-\alpha)$.
Similarly, $G(\beta) \cdot G(-\beta)=I \Rightarrow\{G(\beta)\}^{-1}=G(-\beta)$.

$$
\begin{aligned}
& \begin{aligned}
\therefore \quad\{F(\alpha) \cdot G(\beta)\}^{-1} & =\{G(\beta)\}^{-1} \cdot\{F(\alpha)\}^{-1} \quad[\text { by reversal law }] \\
& =G(-\beta) \cdot F(-\alpha)
\end{aligned} \\
& \text { Hence, }\{F(\alpha) \cdot G(\beta)\}^{-1}=G(-\beta) \cdot F(-\alpha)
\end{aligned}
$$