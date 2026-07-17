## Transpose of Matrices

TRANSPOSE OF A MATRIX Let $A$ be an ( $m \times n$ ) matrix. Then, the matrix obtained by interchanging the rows and columns of $A$ is called the transpose of $A$, denoted by $A^{\prime}$ or $A^{T}$.

Thus, if $A=\left[a_{i j}\right]_{m \times n}$ then $A^{\prime}=\left[a_{j i}\right]_{n \times m}$.
REMARKS (i) If $A$ is an ( $m \times n$ ) matrix then $A^{\prime}$ is an ( $n \times m$ ) matrix.
(ii) $(i, j)$ th element of $A=(j, i)$ th element of $A^{\prime}$.

$$
\text { EXAMPLE If } A=\left[\begin{array}{ccc}
2 & \sqrt{2} & 0 \\
3 & -2 & \frac{2}{5}
\end{array}\right] \text {, then } A^{\prime}=\left[\begin{array}{cc}
2 & 3 \\
\sqrt{2} & -2 \\
0 & \frac{2}{5}
\end{array}\right] \text {. }
$$

Some Results on Transpose of Matrices
THEOREM 1 For any matrix $A$, prove that $\left(A^{\prime}\right)^{\prime}=A$.
PROOF Let $A=\left[a_{i j}\right]_{m \times n}$. Then,
$A$ is an $m \times n$ matrix $\Rightarrow A^{\prime}$ is an $n \times m$ matrix
$\Rightarrow\left(A^{\prime}\right)^{\prime}$ is an $m \times n$ matrix.
$\therefore \quad A$ and $\left(A^{\prime}\right)^{\prime}$ are matrices of the same order.
Also, $(i, j)$ th element of $A=(j, i)$ th element of $A^{\prime}$
$=(i, j)$ th element of $\left(A^{\prime}\right)^{\prime}$.
$\therefore \quad(i, j)$ th element of $A=(i, j)$ th element of $\left(A^{\prime}\right)^{\prime}$.
Thus, $A$ and $\left(A^{\prime}\right)^{\prime}$ are comparable matrices having their corresponding elements equal.
Hence, $\left(A^{\prime}\right)^{\prime}=A$.

THEOREM 2 If $A$ is any matrix and $k$ is a scalar, prove that $(k A)^{\prime}=k A^{\prime}$.
PROOF Let $A=\left[a_{i j}\right]_{m \times n}$ be an $m \times n$ matrix and $k$ be a scalar.
Then, $A$ is an $m \times n$ matrix $\Rightarrow k A$ is an $m \times n$ matrix

$$
\Rightarrow(k A)^{\prime} \text { is an } n \times m \text { matrix. }
$$

Again, $A$ is an $m \times n$ matrix $\Rightarrow A^{\prime}$ is an $n \times m$ matrix
$\Rightarrow k A^{\prime}$ is an $n \times m$ matrix.
Thus, $(k A)^{\prime}$ and $k A^{\prime}$ are matrices of the same order.
Now, $(j, i)$ th element of $(k A)^{\prime}=(i, j)$ th element of $k A$

$$
\begin{aligned}
& =k \text { times }(i, j) \text { th element of } A \\
& =k \text { times }(j, i) \text { th element of } A^{\prime} \\
& =(j, i) \text { th element of } k A^{\prime} .
\end{aligned}
$$

$\therefore \quad(j, i)$ th element of $(k A)^{\prime}=(j, i)$ th element of $k A^{\prime}$.
Thus, $(k A)^{\prime}$ and $k A^{\prime}$ are comparable matrices having their corresponding elements equal.
Hence, $(k A)^{\prime}=k A^{\prime}$.
THEOREM 3 If $A$ and $B$ are two matrices of the same order then prove that $(A+B)^{\prime}=A^{\prime}+B^{\prime}$.
PROOF Let $A=\left[a_{i j}\right]_{m \times n}$ and $B=\left[b_{i j}\right]_{m \times n}$. Then,
$A$ is an $m \times n$ matrix and $B$ is an $m \times n$ matrix
$\Rightarrow(A+B)$ is an $m \times n$ matrix
$\Rightarrow(A+B)^{\prime}$ is an $n \times m$ matrix.
Also, $A$ is an $m \times n$ matrix and $B$ is an $m \times n$ matrix
$\Rightarrow A^{\prime}$ is an $n \times m$ matrix and $B^{\prime}$ is an $n \times m$ matrix
$\Rightarrow$ ( $A^{\prime}+B^{\prime}$ ) is an $n \times m$ matrix.
$\therefore(A+B)^{\prime}$ and $\left(A^{\prime}+B^{\prime}\right)$ are comparable matrices.
Also, ( $j, i$ )th element of ( $A+B^{\prime}$ )

$$
\begin{aligned}
& =(i, j) \text { th element of }(A+B) \\
& =(i, j) \text { th element of } A+(i, j) \text { th element of } B \\
& =(j, i) \text { th element of } A^{\prime}+(j, i) \text { th element of } B^{\prime} \\
& =(j, i) \text { th element of }\left(A^{\prime}+B^{\prime}\right)
\end{aligned}
$$

$\therefore(j, i)$ th element of $\left(A+B^{\prime}\right)=(j, i)$ th element of $\left(A^{\prime}+B^{\prime}\right)$.
Thus, $(A+B)^{\prime}$ and $\left(A^{\prime}+B^{\prime}\right)$ are comparable and their corresponding elements are equal.

Hence, $(A+B)^{\prime}=A^{\prime}+B^{\prime}$.
THEOREM 4 If $A$ and $B$ are square matrices of the same order then $(A B)^{\prime}=B^{\prime} A^{\prime}$.
REMARK The proof of this theorem is beyond the scope of this book.

## SUMMARY

(i) $\left(A^{\prime}\right)^{\prime}=A$
(ii) $(k A)^{\prime}=k A^{\prime}$
(iii) $(A+B)^{\prime}=A^{\prime}+B^{\prime}$
(iv) $(A B)^{\prime}=B^{\prime} A^{\prime}$

## SOLVED EXAMPLES

EXAMPLE 1 Let $A=\left[\begin{array}{rrr}2 & 3 & -1 \\ 0 & -5 & 7\end{array}\right] \cdot$ Verify that $\left(A^{\prime}\right)^{\prime}=A$.
SOLUTION We have

$$
\begin{aligned}
& A^{\prime}=\left[\begin{array}{rrr}
2 & 3 & -1 \\
0 & -5 & 7
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
2 & 0 \\
3 & -5 \\
-1 & 7
\end{array}\right] \\
\Rightarrow & \left(A^{\prime}\right)^{\prime}=\left[\begin{array}{rr}
2 & 0 \\
3 & -5 \\
-1 & 7
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
2 & 3 & -1 \\
0 & -5 & 7
\end{array}\right]=A
\end{aligned}
$$

Hence, $\left(A^{\prime}\right)^{\prime}=A$.
EXAMPLE 2 If $A=\left[\begin{array}{rrr}2 & 3 & -5 \\ 0 & -1 & 4\end{array}\right]$, verify that $(3 A)^{\prime}=3 A^{\prime}$.
SOLUTION We have

$$
\begin{aligned}
& 3 A=\left[\begin{array}{lll}
3 \times 2 & 3 \times 3 & 3 \times(-5) \\
3 \times 0 & 3 \times(-1) & 3 \times 4
\end{array}\right]=\left[\begin{array}{rrr}
6 & 9 & -15 \\
0 & -3 & 12
\end{array}\right] . \\
& \therefore \quad(3 A)^{\prime}=\left[\begin{array}{rrr}
6 & 9 & -15 \\
0 & -3 & 12
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
6 & 0 \\
9 & -3 \\
-15 & 12
\end{array}\right] . \\
& \text { Also, } A^{\prime}=\left[\begin{array}{rrr}
2 & 3 & -5 \\
0 & -1 & 4
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
2 & 0 \\
3 & -1 \\
-5 & 4
\end{array}\right] . \\
& \therefore \quad 3 A^{\prime}=3 \cdot\left[\begin{array}{rr}
2 & 0 \\
3 & -1 \\
-5 & 4
\end{array}\right]=\left[\begin{array}{rr}
6 & 0 \\
9 & -3 \\
-15 & 12
\end{array}\right] .
\end{aligned}
$$

Hence, $(3 A)^{\prime}=3 A^{\prime}$.
EXAMPLE 3 Let $A=\left[\begin{array}{rr}3 & 4 \\ -2 & 0 \\ 7 & -5\end{array}\right]$ and $B=\left[\begin{array}{rr}2 & -3 \\ 5 & 6 \\ -1 & 8\end{array}\right]$. Verify that $(A+B)^{\prime}=A^{\prime}+B^{\prime}$.

SOLUTION We have

$$
\begin{aligned}
& A+B=\left[\begin{array}{rr}
3 & 4 \\
-2 & 0 \\
7 & -5
\end{array}\right]^{+}\left[\begin{array}{rr}
2 & -3 \\
5 & 6 \\
-1 & 8
\end{array}\right] \\
& =\left[\begin{array}{rr}
3+2 & 4+(-3) \\
-2+5 & 0+6 \\
7+(-1) & -5+8
\end{array}\right]=\left[\begin{array}{ll}
5 & 1 \\
3 & 6 \\
6 & 3
\end{array}\right] . \\
& \therefore \quad(A+B)^{\prime}=\left[\begin{array}{ll}
5 & 1 \\
3 & 6 \\
6 & 3
\end{array}\right]^{\prime}=\left[\begin{array}{lll}
5 & 3 & 6 \\
1 & 6 & 3
\end{array}\right] . \\
& \text { Also, } A^{\prime}=\left[\begin{array}{rr}
3 & 4 \\
-2 & 0 \\
7 & -5
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
3 & -2 & 7 \\
4 & 0 & -5
\end{array}\right] . \\
& \text { And, } B^{\prime}=\left[\begin{array}{rr}
2 & -3 \\
5 & 6 \\
-1 & 8
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
2 & 5 & -1 \\
-3 & 6 & 8
\end{array}\right] . \\
& \therefore \quad\left(A^{\prime}+B^{\prime}\right)=\left[\begin{array}{rrr}
3 & -2 & 7 \\
4 & 0 & -5
\end{array}\right]+\left[\begin{array}{rrr}
2 & 5 & -1 \\
-3 & 6 & 8
\end{array}\right] \\
& \quad=\left[\begin{array}{rrr}
3+2 & -2+5 & 7+(-1) \\
4+(-3) & 0+6 & -5+8
\end{array}\right]=\left[\begin{array}{lll}
5 & 3 & 6 \\
1 & 6 & 3
\end{array}\right] .
\end{aligned}
$$

Hence, $(A+B)^{\prime}=A^{\prime}+B^{\prime}$.
EXAMPLE 4 If $A=\left[\begin{array}{r}-3 \\ 5 \\ 2\end{array}\right]$ and $B=\left[\begin{array}{lll}1 & 6 & -4\end{array}\right]$ then verify that $(A B)^{\prime}=B^{\prime} A^{\prime}$.
[CBSE 2002]
SOLUTION We have $A=\left[\begin{array}{r}-3 \\ 5 \\ 2\end{array}\right]$ and $B=\left[\begin{array}{lll}1 & 6 & -4\end{array}\right]$.

$$
\begin{aligned}
\therefore \quad A B & =\left[\begin{array}{r}
-3 \\
5 \\
2
\end{array}\right]\left[\begin{array}{lll}
1 & 6 & -4
\end{array}\right] \\
& =\left[\begin{array}{rrr}
-3 & -18 & 12 \\
5 & 30 & -20 \\
2 & 12 & -8
\end{array}\right] .
\end{aligned}
$$

So, $(A B)^{\prime}=\left[\begin{array}{rrr}-3 & 5 & 2 \\ -18 & 30 & 12 \\ 12 & -20 & -8\end{array}\right]$.
Also, $A^{\prime}=\left[\begin{array}{lll}-3 & 5 & 2\end{array}\right]$ and $B^{\prime}=\left[\begin{array}{r}1 \\ 6 \\ -4\end{array}\right]$.
$\therefore \quad B^{\prime} A^{\prime}=\left[\begin{array}{r}1 \\ 6 \\ -4\end{array}\right]\left[\begin{array}{lll}-3 & 5 & 2\end{array}\right]$

$$
=\left[\begin{array}{rrr}
-3 & 5 & 2 \\
-18 & 30 & 12 \\
12 & -20 & -8
\end{array}\right] .
$$

Hence, $(A B)^{\prime}=B^{\prime} A^{\prime}$.

## SYMMETRIC AND SKEW-SYMMETRIC MATRICES

SYMMETRIC MATRIX $A$ square matrix $A$ is said to be symmetric if $A^{\prime}=A$.
$A$ is symmetric $\Leftrightarrow a_{j i}=a_{i j}$.
EXAMPLE 1 Consider the matrix $A=\left[\begin{array}{cc}4 & \sqrt{2} \\ \sqrt{2} & \frac{1}{3}\end{array}\right]$.
Then, $A^{\prime}=\left[\begin{array}{cc}4 & \sqrt{2} \\ \sqrt{2} & \frac{1}{3}\end{array}\right]^{\prime}=\left[\begin{array}{cc}4 & \sqrt{2} \\ \sqrt{2} & \frac{1}{3}\end{array}\right]=A$.
Hence, $A$ is symmetric.
EXAMPLE 2 Consider the matrix $B=\left[\begin{array}{rrr}6 & -7 & 4 \\ -7 & 3 & 0 \\ 4 & 0 & \sqrt{5}\end{array}\right]$.
Then, $B^{\prime}=\left[\begin{array}{rrr}6 & -7 & 4 \\ -7 & 3 & 0 \\ 4 & 0 & \sqrt{5}\end{array}\right]^{\prime}=\left[\begin{array}{rrr}6 & -7 & 4 \\ -7 & 3 & 0 \\ 4 & 0 & \sqrt{5}\end{array}\right]=B$.
Hence, $B$ is symmetric.
SKEW-SYMMETRIC MATRIX $A$ square matrix $A$ is said to be skew-symmetric if $A^{\prime}=-A$.

REMARK $\quad A$ is skew-symmetric $\Leftrightarrow A^{\prime}=-A \Leftrightarrow a_{j i}=-a_{i j}$

$$
\Leftrightarrow a_{i i}=-a_{i i} \Leftrightarrow 2 a_{i i}=0 \Leftrightarrow a_{i i}=0 .
$$

Thus, every diagonal element of a skew-symmetric matrix is zero.

EXAMPLE 1 Let $A=\left[\begin{array}{rr}0 & 5 \\ -5 & 0\end{array}\right]$. Then,

$$
A^{\prime}=\left[\begin{array}{rr}
0 & -5 \\
5 & 0
\end{array}\right]=-A .
$$

Hence, $A$ is skew-symmetric.
EXAMPLE 2 Let $A=\left[\begin{array}{rrr}0 & h & g \\ -h & 0 & f \\ -g & -f & 0\end{array}\right]$. Then,

$$
A^{\prime}=\left[\begin{array}{rrr}
0 & -h & -g \\
h & 0 & -f \\
g & f & 0
\end{array}\right]=-A
$$

Hence, $A$ is skew-symmetric.

## SOME RESULTS ON SYMMETRIC AND SKEW-SYMMETRIC MATRICES

THEOREM 1 Prove that the sum of two symmetric matrices is a symmetric matrix.
PROOF Let $A$ and $B$ be symmetric matrices of the same order.
Then, $A^{\prime}=A$ and $B^{\prime}=B$.
$\therefore \quad(A+B)^{\prime}=\left(A^{\prime}+B^{\prime}\right)=(A+B) \quad\left[\because \quad A^{\prime}=A\right.$ and $\left.B^{\prime}=B\right]$.
Hence, ( $A+B$ ) is symmetric.
THEOREM 2 If $A$ is a symmetric matrix then prove that $k A$ is symmetric.
PROOF Since $A$ is symmetric, we have $A^{\prime}=A$.
$\therefore(k A)^{\prime}=k \cdot A^{\prime}=k A \quad\left[\because \quad A^{\prime}=A\right]$.
This shows that $k A$ is symmetric.
THEOREM 3 Prove that the sum of two skew-symmetric matrices is a skew-symmetric matrix.
PROOF Let $A$ and $B$ be two skew-symmetric matrices.
Then, $A^{\prime}=-A$ and $B^{\prime}=-B$.
$\therefore(A+B)^{\prime}=\left(A^{\prime}+B^{\prime}\right)=(-A)+(-B)=-(A+B)$.
Hence, ( $A+B$ ) is skew-symmetric.
THEOREM 4 If $A$ is a skew-symmetric matrix then prove that $k A$ is skew-symmetric.
PROOF Since $A$ is skew-symmetric, we have $A^{\prime}=-A$.
$\therefore(k A)^{\prime}=k \cdot A^{\prime}=k \cdot(-A) \quad\left[\because \quad A^{\prime}=-A\right]$

$$
=-(k \cdot A) .
$$

Thus, $(k A)^{\prime}=-(k A)$.
Hence, ( $k A$ ) is skew-symmetric.
THEOREM 5 For any square matrix $A$ with real number entries, prove that
(i) ( $A+A^{\prime}$ ) is symmetric and (ii) ( $A-A^{\prime}$ ) is skew-symmetric.

PROOF Let $A$ be a square matrix with real number entries. Then, we have:

$$
\text { (i) } \begin{aligned}
\left(A+A^{\prime}\right)^{\prime} & =A^{\prime}+\left(A^{\prime}\right)^{\prime} & & {\left[\because(A+B)^{\prime}=A^{\prime}+B^{\prime}\right] } \\
& =A^{\prime}+A & & {\left[\because\left(A^{\prime}\right)^{\prime}=A\right] } \\
& =\left(A+A^{\prime}\right) & & {[\because(A+B)=(B+A)] . }
\end{aligned}
$$

Thus, $\left(A+A^{\prime}\right)^{\prime}=\left(A+A^{\prime}\right)$.
Hence, ( $A+A^{\prime}$ ) is symmetric.

$$
\text { (ii) } \begin{aligned}
\left(A-A^{\prime}\right)^{\prime} & =A^{\prime}-\left(A^{\prime}\right)^{\prime} & {[\because} & \left.(A-B)^{\prime}=A^{\prime}-B^{\prime}\right] \\
& =A^{\prime}-A & {[\because} & \left.\left(A^{\prime}\right)^{\prime}=A\right] \\
& =-\left(A-A^{\prime}\right) . & &
\end{aligned}
$$

Thus, $\left(A-A^{\prime}\right)^{\prime}=-\left(A-A^{\prime}\right)$
Hence, ( $A-A^{\prime}$ ) is skew-symmetric.
THEOREM 6 Prove that every square matrix is expressible as the sum of a symmetric and a skew-symmetric matrix.
PROOF Let $A$ be any square matrix. Then, we can write

$$
\begin{aligned}
& A=\frac{1}{2}\left(A+A^{\prime}\right)+\frac{1}{2}\left(A-A^{\prime}\right)=P+Q(\text { say }), \\
& \text { where } P=\frac{1}{2}\left(A+A^{\prime}\right) \text { and } Q=\frac{1}{2}\left(A-A^{\prime}\right) .
\end{aligned}
$$

$$
\text { Now, } \begin{aligned}
P^{\prime} & =\left\{\frac{1}{2}\left(A+A^{\prime}\right)\right\}^{\prime} \\
& =\frac{1}{2}\left(A+A^{\prime}\right)^{\prime} \\
& =\frac{1}{2}\left\{\begin{array} { l l } 
{ } & { } \\
{ } & { } \\
{ } & { ( k A ) ^ { \prime } + ( A ^ { \prime } ) ^ { \prime } \} }
\end{array} \quad \left[\because \quad\left(A+B A^{\prime}\right]\right.\right. \\
& =\frac{1}{2}\left(A^{\prime}+A\right) \\
& =\frac{1}{2}\left(A+A^{\prime}\right) \\
& =P
\end{aligned}
$$

Thus, $P^{\prime}=P$ and therefore, $P$ is symmetric.

$$
\text { And, } \begin{aligned}
Q^{\prime} & =\left\{\frac{1}{2}\left(A-A^{\prime}\right)\right\}^{\prime} \\
& =\frac{1}{2}\left(A-A^{\prime}\right) \quad\left[\because \quad(k A)^{\prime}=k A^{\prime}\right] \\
& =\frac{1}{2}\left\{A^{\prime}-\left(A^{\prime}\right)^{\prime}\right\} \quad\left[\because \quad(A-B)^{\prime}=A^{\prime}-B^{\prime}\right] \\
& =\frac{1}{2}\left(A^{\prime}-A\right) \quad\left[\because \quad\left(A^{\prime}\right)^{\prime}=A\right] \\
& =-\frac{1}{2}\left(A-A^{\prime}\right)=-Q .
\end{aligned}
$$

Thus, $Q^{\prime}=-Q$ and therefore, $Q$ is skew-symmetric.
$\therefore A=P+Q$, where $P$ is symmetric and $Q$ is skew-symmetric.

## SOLVED EXAMPLES

EXAMPLE 1 Express the matrix $A=\left[\begin{array}{ll}3 & -4 \\ 1 & -1\end{array}\right]$ as the sum of a symmetric matrix and a skew-symmetric matrix.
SOLUTION We know that $A=\frac{1}{2}\left(A+A^{\prime}\right)+\frac{1}{2}\left(A-A^{\prime}\right)$, where $\frac{1}{2}\left(A+A^{\prime}\right)$ is symmetric and $\frac{1}{2}\left(A-A^{\prime}\right)$ is skew-symmetric.
Here, $A=\left[\begin{array}{ll}3 & -4 \\ 1 & -1\end{array}\right] \Rightarrow A^{\prime}=\left[\begin{array}{rr}3 & 1 \\ -4 & -1\end{array}\right]$.

$$
\begin{aligned}
\therefore \quad\left(A+A^{\prime}\right) & =\left[\begin{array}{ll}
3 & -4 \\
1 & -1
\end{array}\right]=\left[\begin{array}{rr}
3 & 1 \\
-4 & -1
\end{array}\right] \\
& =\left[\begin{array}{cc}
3+3 & -4+1 \\
1+(-4) & -1+(-1)
\end{array}\right]=\left[\begin{array}{rr}
6 & -3 \\
-3 & -2
\end{array}\right] .
\end{aligned}
$$

Let $P=\frac{1}{2}\left(A+A^{\prime}\right)=\frac{1}{2} \cdot\left[\begin{array}{cc}6 & -3 \\ -3 & -2\end{array}\right]=\left[\begin{array}{cc}3 & \frac{-3}{2} \\ \frac{-3}{2} & -1\end{array}\right]$.
And, $\left(A-A^{\prime}\right)=\left[\begin{array}{rr}3 & -4 \\ 1 & -1\end{array}\right]-\left[\begin{array}{rr}3 & 1 \\ -4 & -1\end{array}\right]$

$$
=\left[\begin{array}{cc}
3-3 & -4-1 \\
1-(-4) & -1-(-1)
\end{array}\right]=\left[\begin{array}{cc}
0 & -5 \\
1+4 & -1+1
\end{array}\right]=\left[\begin{array}{cr}
0 & -5 \\
5 & 0
\end{array}\right] .
$$

Let $Q=\frac{1}{2}\left(A-A^{\prime}\right)=\frac{1}{2} \cdot\left[\begin{array}{rr}0 & -5 \\ 5 & 0\end{array}\right]=\left[\begin{array}{cc}0 & \frac{-5}{2} \\ \frac{5}{2} & 0\end{array}\right]$.
Then, $P^{\prime}=\left[\begin{array}{cc}3 & \frac{-3}{2} \\ \frac{-3}{2} & -1\end{array}\right]^{\prime}=\left[\begin{array}{cc}3 & \frac{-3}{2} \\ \frac{-3}{2} & -1\end{array}\right]=P$.
$\therefore \quad P$ is symmetric.
And, $Q^{\prime}=\left[\begin{array}{cc}0 & \frac{-5}{2} \\ \frac{5}{2} & 0\end{array}\right]^{\prime}=\left[\begin{array}{cc}0 & \frac{5}{2} \\ \frac{-5}{2} & 0\end{array}\right]=-Q$.
$\therefore \quad Q$ is skew-symmetric.

Now, $P+Q=\left[\begin{array}{cc}3 & \frac{-3}{2} \\ \frac{-3}{2} & -1\end{array}\right]+\left[\begin{array}{cc}0 & \frac{-5}{2} \\ \frac{5}{2} & 0\end{array}\right]=\left[\begin{array}{cc}3 & -4 \\ 1 & -1\end{array}\right]=A$.
Hence, $A=P+Q$, where $P$ is symmetric and $Q$ is skew-symmetric.
EXAMPLE 2 Express the matrix $A=\left[\begin{array}{rrr}1 & 3 & 5 \\ -6 & 8 & 3 \\ -4 & 6 & 5\end{array}\right]$ as the sum of a symmetric and a skew-symmetric matrix.
[CBSE 2006]
SOLUTION We have

$$
\begin{gathered}
\begin{array}{c}
A=\left[\begin{array}{rrr}
1 & 3 & 5 \\
-6 & 8 & 3 \\
-4 & 6 & 5
\end{array}\right] \Rightarrow A^{\prime}=\left[\begin{array}{rrr}
1 & -6 & -4 \\
3 & 8 & 6 \\
5 & 3 & 5
\end{array}\right] . \\
\therefore \quad\left(A+A^{\prime}\right)=\left[\begin{array}{rrr}
1 & 3 & 5 \\
-6 & 8 & 3 \\
-4 & 6 & 5
\end{array}\right]+\left[\begin{array}{rrr}
1 & -6 & -4 \\
3 & 8 & 6 \\
5 & 3 & 5
\end{array}\right] \\
=\left[\begin{array}{rrr}
1+1 & 3+(-6) & 5+(-4) \\
-6+3 & 8+8 & 3+6 \\
-4+5 & 6+3 & 5+5
\end{array}\right]=\left[\begin{array}{rrr}
2 & -3 & 1 \\
-3 & 16 & 9 \\
1 & 9 & 10
\end{array}\right] . \\
\text { Let } P=\frac{1}{2}\left(A+A^{\prime}\right)=\frac{1}{2} \cdot\left[\begin{array}{rrr}
-3 & 16 & 9 \\
1 & 9 & 10
\end{array}\right]=\left[\begin{array}{rrr}
1 & \frac{-3}{2} & \frac{1}{2} \\
\frac{-3}{2} & 8 & \frac{9}{2} \\
\frac{1}{2} & \frac{9}{2} & 5
\end{array}\right] . \\
\text { And, }\left(A-A^{\prime}\right)=\left[\begin{array}{rrr}
1 & 3 & 5 \\
-6 & 8 & 3 \\
-4 & 6 & 5
\end{array}\right]-\left[\begin{array}{rrr}
1 & -6 & -4 \\
3 & 8 & 6 \\
5 & 3 & 5
\end{array}\right] \\
=\left[\begin{array}{rrr}
1-1 & 3-(-6) & 5-(-4) \\
-6-3 & 8-8 & 3-6 \\
-4-5 & 6-3 & 5-5
\end{array}\right]=\left[\begin{array}{rrc}
0 & 3+6 & 5+4 \\
-9 & 0 & -3 \\
-9 & 3 & 0
\end{array}\right] \\
=\left[\begin{array}{rrr}
0 & 9 & 9 \\
-9 & 0 & -3 \\
-9 & 3 & 0
\end{array}\right] .
\end{array}
\end{gathered}
$$

Let $Q=\frac{1}{2}\left(A-A^{\prime}\right)=\frac{1}{2} \cdot\left[\begin{array}{ccc}0 & 9 & 9 \\ -9 & 0 & -3 \\ -9 & 3 & 0\end{array}\right]=\left[\begin{array}{ccc}0 & \frac{9}{2} & \frac{9}{2} \\ \frac{-9}{2} & 0 & \frac{-3}{2} \\ \frac{-9}{2} & \frac{3}{2} & 0\end{array}\right]$.

$$
P^{\prime}=\left[\begin{array}{ccc}
1 & \frac{-3}{2} & \frac{1}{2} \\
\frac{-3}{2} & 8 & \frac{9}{2} \\
\frac{1}{2} & \frac{9}{2} & 5
\end{array}\right]^{\prime}=\left[\begin{array}{ccc}
1 & \frac{-3}{2} & \frac{1}{2} \\
\frac{-3}{2} & 8 & \frac{9}{2} \\
\frac{1}{2} & \frac{9}{2} & 5
\end{array}\right]=P .
$$

$\therefore \quad P$ is symmetric.
And, $Q^{\prime}=\left[\begin{array}{ccc}0 & \frac{9}{2} & \frac{9}{2} \\ \frac{-9}{2} & 0 & \frac{-3}{2} \\ \frac{-9}{2} & \frac{3}{2} & 0\end{array}\right]^{\prime}=\left[\begin{array}{ccc}0 & \frac{-9}{2} & \frac{-9}{2} \\ \frac{9}{2} & 0 & \frac{3}{2} \\ \frac{9}{2} & \frac{-3}{2} & 0\end{array}\right]=-Q$.
$\therefore \quad Q$ is skew-symmetric.
Now, $(P+Q)=\left[\begin{array}{ccc}1 & \frac{-3}{2} & \frac{1}{2} \\ \frac{-3}{2} & 8 & \frac{9}{2} \\ \frac{1}{2} & \frac{9}{2} & 5\end{array}\right]+\left[\begin{array}{ccc}0 & \frac{9}{2} & \frac{9}{2} \\ \frac{-9}{2} & 0 & \frac{-3}{2} \\ \frac{-9}{2} & \frac{3}{2} & 0\end{array}\right]$

$$
=\left[\begin{array}{rrr}
1 & 3 & 5 \\
-6 & 8 & 3 \\
-4 & 6 & 5
\end{array}\right]=A .
$$

Hence, $A=P+Q$,
where $P$ is symmetric and $Q$ is skew-symmetric.
EXAMPLE 3 If $A$ and $B$ are symmetric matrices of the same order then show that $A B$ is symmetric if and only if $A B=B A$.

SOLUTION Let $A$ and $B$ be symmetric matrices.
Then, $A^{\prime}=A$ and $B^{\prime}=B$.
Let $A B$ be symmetric. Then,

$$
\begin{aligned}
A B & =(A B)^{\prime} \quad[\text { by definition }] \\
& =B^{\prime} A^{\prime}=B A \quad\left[\because \quad B^{\prime}=B \text { and } A^{\prime}=A\right] . \\
\therefore \quad A B & =B A .
\end{aligned}
$$

Conversely, let $A B=B A$. Then,

$$
\begin{aligned}
(A B)^{\prime} & =B^{\prime} A^{\prime} \\
& =B A \quad\left[\because \quad B^{\prime}=B \text { and } A^{\prime}=A\right] \\
& =A B \quad[\text { given }] .
\end{aligned}
$$

Thus, $(A B)^{\prime}=A B$ and hence, $A B$ is symmetric.
EXAMPLE 4 If $A$ and $B$ are symmetric matrices, prove that ( $A B-B A$ ) is skew-symmetric.

SOLUTION Let $A$ and $B$ be symmetric matrices.
Then, $A^{\prime}=A$ and $B^{\prime}=B$.
Now, $(A B-B A)^{\prime}=(A B)^{\prime}-(B A)^{\prime}$

$$
\begin{aligned}
& =\left(B^{\prime} A^{\prime}\right)-\left(A^{\prime} B^{\prime}\right) \\
& =(B A-A B) \quad\left[\because \quad A^{\prime}=A \text { and } B^{\prime}=B\right] \\
& =-(A B-B A)
\end{aligned}
$$

Thus, $(A B-B A)^{\prime}=-(A B-B A)$.
Hence, ( $A B-B A$ ) is skew-symmetric.
EXAMPLE 5 If $A$ is symmetric, show that $B^{\prime} A B$ is symmetric.
solution Let $A$ be symmetric. Then, $A^{\prime}=A$.

$$
\begin{aligned}
\therefore\left(B^{\prime} A B\right)^{\prime} & =B^{\prime} A^{\prime}\left(B^{\prime}\right)^{\prime} \\
& =B^{\prime} A^{\prime} B \quad\left[\because \quad\left(B^{\prime}\right)^{\prime}=B\right] \\
& =B^{\prime} A B \quad\left[\because \quad A^{\prime}=A\right] .
\end{aligned}
$$

Thus, $\left(B^{\prime} A B\right)^{\prime}=B^{\prime} A B$.
Hence, ( $B^{\prime} A B$ ) is symmetric.

