## Multiplication of Matrices

For two given matrices $A$ and $B$, we say that the product $A B$ exists only when the number of rows in $A$ equals the number of columns in $B$.

When $A B$ exists, we say that $A$ is conformable to $B$ for multiplication.

## PRODUCT OF MATRICES

Let $A=\left[a_{i j}\right]_{m \times n}$ and $B=\left[b_{j k}\right]_{n \times p}$ be two matrices such that the number of columns in $A$ equals the number of rows in $B$.

Then, $A B$ exists and it is an ( $m \times p$ ) matrix, given by

$$
A B=\left[c_{i k}\right]_{m \times p}, \text { where } c_{i k}=\left(a_{i 1} b_{1 k}+a_{i 2} b_{2 k}+\ldots a_{i n} b_{n k}\right)=\sum_{j=1}^{n} a_{i j} b_{j k} .
$$

$\therefore \quad(i, k)$ th element of $A B$
$=$ sum of the products of corresponding elements of $i$ th row of $A$ and $k$ th column of $B$.

## SUMMARY

(i) If $A$ is an ( $m \times n$ ) matrix and $B$ is an ( $n \times p$ ) matrix then $A B$ exists and it is an ( $m \times p$ ) matrix.
(ii) $(i, k)$ th element of $A B$
$=$ sum of the products of corresponding elements of $i$ th row of $A$ and $k$ th column of $B$.
remarks For two given matrices $A$ and $B$ :
(i) $A B$ may exist and $B A$ may not exist;
(ii) $B A$ may exist and $A B$ may not exist;
(iii) $A B$ and $B A$ both may not exist;
(iv) $A B$ and $B A$ both may exist.

## SOLVED EXAMPLES

EXAMPLE 1 If $A=\left[\begin{array}{lll}a_{11} & a_{12} & a_{13} \\ a_{21} & a_{22} & a_{23}\end{array}\right]$ and $B=\left[\begin{array}{ll}b_{11} & b_{12} \\ b_{21} & b_{22} \\ b_{31} & b_{32}\end{array}\right]$ then show that $A B$ and $B A$ both exist. Find $A B$ and $B A$.
solution Here, $A$ is a $2 \times 3$ matrix and $B$ is a $3 \times 2$ matrix.
$\therefore A B$ exists and it is a $2 \times 2$ matrix.
Let $A B=\left[\begin{array}{ll}c_{11} & c_{12} \\ c_{21} & c_{22}\end{array}\right]$. Then,

$$
\begin{aligned}
c_{11} & =(1 \text { st row of } A) \times(1 \text { st column of } B) \\
& =a_{11} b_{11}+a_{12} b_{21}+a_{13} b_{31} ; \\
c_{12} & =(1 \text { st row of } A) \times(2 \text { nd column of } B) \\
& =a_{11} b_{12}+a_{12} b_{22}+a_{13} b_{32} ; \\
c_{21} & =(2 \text { nd row of } A) \times(1 \text { st column of } B) \\
& =a_{21} b_{11}+a_{22} b_{21}+a_{23} b_{31} ;
\end{aligned}
$$

$$
\text { and } \begin{aligned}
c_{22} & =(2 \text { nd row of } A) \times(2 \text { nd column of } B) \\
& =a_{21} b_{12}+a_{22} b_{22}+a_{23} b_{32} \\
\therefore \quad A B & =\left[\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23}
\end{array}\right]\left[\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22} \\
b_{31} & b_{32}
\end{array}\right] \\
& =\left[\begin{array}{ll}
a_{11} b_{11}+a_{12} b_{21}+a_{13} b_{31} & a_{11} b_{12}+a_{12} b_{22}+a_{13} b_{32} \\
a_{21} b_{11}+a_{22} b_{21}+a_{23} b_{31} & a_{21} b_{12}+a_{22} b_{22}+a_{23} b_{32}
\end{array}\right] .
\end{aligned}
$$

Again, $B$ is a $3 \times 2$ matrix and $A$ is a $2 \times 3$ matrix. So, $B A$ exists and it is a $3 \times 3$ matrix.

Proceeding as above, we get

$$
\begin{aligned}
B A & =\left[\begin{array}{ll}
b_{11} & b_{12} \\
b_{21} & b_{22} \\
b_{31} & b_{32}
\end{array}\right]\left[\begin{array}{lll}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23}
\end{array}\right] \\
& =\left[\begin{array}{lll}
b_{11} a_{11}+b_{12} a_{21} & b_{11} a_{12}+b_{12} a_{22} & b_{11} a_{13}+b_{12} a_{23} \\
b_{21} a_{11}+b_{22} a_{21} & b_{21} a_{12}+b_{22} a_{22} & b_{21} a_{13}+b_{22} a_{23} \\
b_{31} a_{11}+b_{32} a_{21} & b_{31} a_{12}+b_{32} a_{22} & b_{31} a_{13}+b_{32} a_{23}
\end{array}\right] .
\end{aligned}
$$

EXAMPLE 2 If $A=\left[\begin{array}{rr}2 & -1 \\ 3 & 4 \\ 1 & 5\end{array}\right]$ and $B=\left[\begin{array}{rr}-1 & 3 \\ 2 & 1\end{array}\right]$, find $A B$. Does $B A$ exist?
SOLUTION Here $A$ is a $3 \times 2$ matrix and $B$ is a $2 \times 2$ matrix.
Clearly, the number of columns in $A$ equals the number of rows in $B$.
$\therefore A B$ exists and it is a $3 \times 2$ matrix.
Now, $A B=\left[\begin{array}{rr}2 & -1 \\ 3 & 4 \\ 1 & 5\end{array}\right]\left[\begin{array}{rr}-1 & 3 \\ 2 & 1\end{array}\right]$

$$
\begin{aligned}
& =\left[\begin{array}{rr}
2 \cdot(-1)+(-1) \cdot 2 & 2 \cdot 3+(-1) \cdot 1 \\
3 \cdot(-1)+4 \cdot 2 & 3 \cdot 3+4 \cdot 1 \\
1 \cdot(-1)+5 \cdot 2 & 1 \cdot 3+5 \cdot 1
\end{array}\right] \\
& =\left[\begin{array}{rr}
-4 & 5 \\
5 & 13 \\
9 & 8
\end{array}\right] .
\end{aligned}
$$

Further, $B$ is a $2 \times 2$ matrix and $A$ is a $3 \times 2$ matrix. So, the number of columns in $B$ is not equal to the number of rows in $A$.
So, $B A$ does not exist.

EXAMPLE 3 Let $A=\left[\begin{array}{rrr}1 & -2 & 3 \\ -4 & 2 & 5\end{array}\right]$ and $B=\left[\begin{array}{rr}2 & 3 \\ 4 & 5 \\ -2 & 1\end{array}\right]$. Find $A B$ and $B A$, and show that $A B \neq B A$.

SOLUTION Here $A$ is a $2 \times 3$ matrix and $B$ is a $3 \times 2$ matrix.
So, $A B$ exists and it is a $2 \times 2$ matrix.
Now, $A B=\left[\begin{array}{rrr}1 & -2 & 3 \\ -4 & 2 & 5\end{array}\right]\left[\begin{array}{rr}2 & 3 \\ 4 & 5 \\ -2 & 1\end{array}\right]$

$$
\begin{aligned}
& =\left[\begin{array}{rr}
1 \cdot 2+(-2) \cdot 4+3 \cdot(-2) & 1 \cdot 3+(-2) \cdot 5+3 \cdot 1 \\
(-4) \cdot 2+2 \cdot 4+5 \cdot(-2) & (-4) \cdot 3+2 \cdot 5+5 \cdot 1
\end{array}\right] \\
& =\left[\begin{array}{rr}
-12 & -4 \\
-10 & 3
\end{array}\right] .
\end{aligned}
$$

Again, $B$ is a $3 \times 2$ matrix and $A$ is a $2 \times 3$ matrix.
So, $B A$ exists and it is a $3 \times 3$ matrix.
Now, $B A=\left[\begin{array}{rr}2 & 3 \\ 4 & 5 \\ -2 & 1\end{array}\right]\left[\begin{array}{rrr}1 & -2 & 3 \\ -4 & 2 & 5\end{array}\right]$

$$
\begin{aligned}
& =\left[\begin{array}{rrr}
2 \cdot 1+3 \cdot(-4) & 2 \cdot(-2)+3 \cdot 2 & 2 \cdot 3+3 \cdot 5 \\
4 \cdot 1+5 \cdot(-4) & 4 \cdot(-2)+5 \cdot 2 & 4 \cdot 3+5 \cdot 5 \\
(-2) \cdot 1+1 \cdot(-4) & (-2) \cdot(-2)+1 \cdot 2 & (-2) \cdot 3+1 \cdot 5
\end{array}\right] \\
& =\left[\begin{array}{rrr}
-10 & 2 & 21 \\
-16 & 2 & 37 \\
-6 & 6 & -1
\end{array}\right] .
\end{aligned}
$$

Hence, $A B \neq B A$.
EXAMPLE 4 If $\left[\begin{array}{ll}2 x & 4\end{array}\right]\left[\begin{array}{c}x \\ -8\end{array}\right]=O$, find the positive value of $x$.
[CBSE 2014C]

SOLUTION The given matrix equation is $A B=O$, where $A$ is a ( $1 \times 2$ ) matrix and $B$ is a ( $2 \times 1$ ) matrix. So, $A B$ is a ( $1 \times 1$ ) matrix.
So, $O$ is a $(1 \times 1)$ matrix.
$\therefore \quad\left[\begin{array}{ll}2 x & 4\end{array}\right]\left[\begin{array}{c}x \\ -8\end{array}\right]=[0]$
$\Rightarrow 2 x^{2}-32=0 \Rightarrow 2 x^{2}=32$
$\Rightarrow \quad x^{2}=16 \Rightarrow x=\sqrt{16}=4$.
Hence, $x=4$.

## Properties of Matrix Multiplication

## 1. Commutativity

Matrix multiplication is not commutative in general.
PROOF Let $A$ and $B$ be two given matrices.
If $A B$ exists then it is quite possible that $B A$ may not exist.
For example, if $A$ is a $3 \times 2$ matrix and $B$ is a $2 \times 2$ matrix then clearly, $A B$ exists but $B A$ does not exist.

Similarly, if $B A$ exists then $A B$ may not exist.
For example, if $A$ is a $2 \times 3$ matrix and $B$ is a $2 \times 2$ matrix then clearly, $B A$ exists but $A B$ does not exist.

Further, if $A B$ and $B A$ both exist, they may not be comparable. For example, if $A$ is a $2 \times 3$ matrix and $B$ is a $3 \times 2$ matrix then clearly, $A B$ as well as $B A$ exists. But, $A B$ is a $2 \times 2$ matrix while $B A$ is a $3 \times 3$ matrix.

Again, if $A B$ and $B A$ both exist and they are comparable, even then they may not be equal.
For example, if $A=\left[\begin{array}{ll}1 & 1 \\ 1 & 2\end{array}\right]$ and $B=\left[\begin{array}{ll}1 & 2 \\ 0 & 3\end{array}\right]$ then $A B$ and $B A$ are both defined and each one is a $2 \times 2$ matrix.
But, $A B=\left[\begin{array}{ll}1 & 5 \\ 1 & 8\end{array}\right]$ and $B A=\left[\begin{array}{ll}3 & 5 \\ 3 & 6\end{array}\right]$.
This shows that $A B \neq B A$.
Hence, in general, $A B \neq B A$.
remarks (i) When $A B=B A$, we say that $A$ and $B$ commute.
(ii) When $A B=-B A$, we say that $A$ and $B$ anticommute.

## 2. Associative law

For any matrices $A, B, C$ for which $(A B) C$ and $A(B C)$ both exist, we have

$$
(A B) C=A(B C) .
$$

## 3. Distributive laws of multiplication over addition

We have:
(i) $A \cdot(B+C)=(A B+A C)$
(ii) $(A+B) \cdot C=(A C+B C)$
4. The product of two nonzero matrices can be a zero matrix.

Example Let $A=\left[\begin{array}{ll}0 & 1 \\ 0 & 2\end{array}\right]$ and $B=\left[\begin{array}{ll}1 & 2 \\ 0 & 0\end{array}\right]$.
Then, $A \neq O$ and $B \neq O$.
And, $A B=\left[\begin{array}{ll}0 & 1 \\ 0 & 2\end{array}\right] \cdot\left[\begin{array}{ll}1 & 2 \\ 0 & 0\end{array}\right]=\left[\begin{array}{ll}0 \cdot 1+1 \cdot 0 & 0 \cdot 2+1 \cdot 0 \\ 0 \cdot 1+2 \cdot 0 & 0 \cdot 2+2 \cdot 0\end{array}\right]$

$$
=\left[\begin{array}{ll}
0 & 0 \\
0 & 0
\end{array}\right] .
$$

Left zero divisor If $A B=O$ and $A \neq O$ then $A$ is called a left zero divisor of $A B$.
Right zero divisor If $A B=O$ and $B \neq O$ then $B$ is called a right zero divisor of $A B$.
5. If $A$ is a given square matrix and $I$ is an identity matrix of the same order as $A$ then we have $A \cdot I=I \cdot A=A$.
6. If $A$ is a given square matrix and $O$ is the null matrix of the same order as $A$ then $O \cdot A=A \cdot O=O$.

## Positive Integral Powers of a Square Matrix

Let $A$ be a square matrix of order $n$. Then, we define:

$$
\begin{aligned}
A^{2} & =A \cdot A ; \\
A^{3} & =A \cdot A \cdot A=A^{2} \cdot A ; \\
A^{4} & =A \cdot A \cdot A \cdot A=A^{3} \cdot A, \text { and so on. } \\
\therefore \quad A^{n} & =(A \cdot A \cdot A \cdot \ldots \cdot n \text { times }) .
\end{aligned}
$$

THEOREM 1 If $A$ and $B$ are square matrices of the same order then

$$
(A+B)^{2}=A^{2}+A B+B A+B^{2} .
$$

Also, when $A B=B A$ then $(A+B)^{2}=A^{2}+2 A B+B^{2}$.
PROOF Let $A$ and $B$ be $n$-rowed square matrices.
Then, clearly, $(A+B)$ is a square matrix of order $n$.
So, $(A+B)^{2}$ is defined.
Now, $(A+B)^{2}=(A+B) \cdot(A+B)$

$$
\begin{array}{ll}
=A \cdot(A+B)+B \cdot(A+B) & {[\text { by distributive law }]} \\
=A A+A B+B A+B B & {[\text { by distributive law }]} \\
=A^{2}+A B+B A+B^{2} . &
\end{array}
$$

Hence, $(A+B)^{2}=\left(A^{2}+A B+B A+B^{2}\right)$.
Particular case When $A B=B A$
In this case, we have

$$
(A+B)^{2}=\left(A^{2}+A B+A B+B^{2}\right)=\left(A^{2}+2 A B+B^{2}\right)[\because \quad B A=A B] .
$$

THEOREM 2 If $A$ and $B$ are square matrices of the same order then

$$
(A+B)(A-B)=A^{2}-A B+B A-B^{2} .
$$

Also, when $A B=B A$ then $(A+B)(A-B)=A^{2}-B^{2}$.
PROOF We have:

$$
\begin{aligned}
(A+B) \cdot(A-B) & =A(A-B)+B(A-B) \quad[\text { by distributive law }] \\
& =A A-A B+B A-B B \quad[\because \quad A(B-C)=A B-A C] \\
& =A^{2}-A B+B A-B^{2} .
\end{aligned}
$$

Hence, $\quad(A+B)(A-B)=A^{2}-A B+B A-B^{2}$.

Particular case When $A B=B A$
In this case, $(A+B)(A-B)=\left(A^{2}-B^{2}\right) \quad[\because \quad B A=A B]$.
MATRIX POLYNOMIAL Let $f(x)=a_{0} x^{m}+a_{1} x^{m-1}+a_{2} x^{m-2}+\ldots+a_{m-1} x+a_{m}$ be a polynomial of degree $m$ and let $A$ be a square matrix of order $n$. Then, we define

$$
f(A)=a_{0} A^{m}+a_{1} A^{m-1}+a_{2} A^{m-2}+\ldots+a_{m-1} A+a_{m} I,
$$

where $I$ is a unit matrix of order $n$.

## SOLVED EXAMPLES

EXAMPLE 1 If $A=\left[\begin{array}{ll}5 & 4 \\ 2 & 3\end{array}\right]$ and $B=\left[\begin{array}{lll}3 & 5 & 1 \\ 6 & 8 & 4\end{array}\right]$, find $A B$ and $B A$ whichever exists.
solution Here, $A$ is a $2 \times 2$ matrix and $B$ is a $2 \times 3$ matrix.
Clearly, the number of columns in $A=$ number of rows in $B$.
$\therefore A B$ exists and it is a $2 \times 3$ matrix.

$$
\begin{aligned}
A B & =\left[\begin{array}{ll}
5 & 4 \\
2 & 3
\end{array}\right]\left[\begin{array}{lll}
3 & 5 & 1 \\
6 & 8 & 4
\end{array}\right] \\
& =\left[\begin{array}{lll}
5 \cdot 3+4 \cdot 6 & 5 \cdot 5+4 \cdot 8 & 5 \cdot 1+4 \cdot 4 \\
2 \cdot 3+3 \cdot 6 & 2 \cdot 5+3 \cdot 8 & 2 \cdot 1+3 \cdot 4
\end{array}\right] \\
& =\left[\begin{array}{ccc}
15+24 & 25+32 & 5+16 \\
6+18 & 10+24 & 2+12
\end{array}\right]=\left[\begin{array}{lll}
39 & 57 & 21 \\
24 & 34 & 14
\end{array}\right] .
\end{aligned}
$$

Again, $B$ is a $2 \times 3$ matrix and $A$ is a $2 \times 2$ matrix.
$\therefore$ number of columns in $B \neq$ number of rows in $A$.
So, $B A$ does not exist.
EXAMPLE 2 If $A=\left[\begin{array}{rrr}2 & -1 & 3 \\ -4 & 5 & 1\end{array}\right]$ and $B=\left[\begin{array}{rr}2 & 3 \\ 4 & -2 \\ 1 & 5\end{array}\right]$ then find $A B$ and $B A$.
Show that $A B \neq B A$.
SOLUTION Here, $A$ is a $2 \times 3$ matrix and $B$ is a $3 \times 2$ matrix
So, number of columns in $A=$ number of rows in $B$.
$\therefore A B$ exists and it is a $2 \times 2$ matrix.

$$
\begin{aligned}
A B & =\left[\begin{array}{rrr}
2 & -1 & 3 \\
-4 & 5 & 1
\end{array}\right]\left[\begin{array}{rr}
2 & 3 \\
4 & -2 \\
1 & 5
\end{array}\right] \\
& =\left[\begin{array}{rl}
2 \cdot 2+(-1) \cdot 4+3 \cdot 1 & 2 \cdot 3+(-1) \cdot(-2)+3 \cdot 5 \\
-4 \cdot 2+5 \cdot 4+1 \cdot 1 & -4 \cdot 3+5 \cdot(-2)+1 \cdot 5
\end{array}\right]
\end{aligned}
$$

$$
=\left[\begin{array}{rr}
4-4+3 & 6+2+15 \\
-8+20+1 & -12-10+5
\end{array}\right]=\left[\begin{array}{rr}
3 & 23 \\
13 & -17
\end{array}\right] .
$$

Again, $B$ is a $3 \times 2$ matrix and $A$ is a $2 \times 3$ matrix.
So, number of columns in $B=$ number of rows in $A$.
$\therefore B A$ exists and it is a $3 \times 3$ matrix.

$$
\begin{aligned}
B A & =\left[\begin{array}{cc}
2 & 3 \\
4 & -2 \\
1 & 5
\end{array}\right]\left[\begin{array}{rrr}
2 & -1 & 3 \\
-4 & 5 & 1
\end{array}\right] \\
& =\left[\begin{array}{lll}
2 \cdot 2+3 \cdot(-4) & 2 \cdot(-1)+3 \cdot 5 & 2 \cdot 3+3 \cdot 1 \\
4 \cdot 2+(-2) \cdot(-4) & 4 \cdot(-1)+(-2) \cdot 5 & 4 \cdot 3+(-2) \cdot 1 \\
1 \cdot 2+5 \cdot(-4) & 1 \cdot(-1)+5 \cdot 5 & 1 \cdot 3+5 \cdot 1
\end{array}\right] \\
& =\left[\begin{array}{ccc}
4-12 & -2+15 & 6+3 \\
8+8 & -4-10 & 12-2 \\
2-20 & -1+25 & 3+5
\end{array}\right]=\left[\begin{array}{rrr}
-8 & 13 & 9 \\
16 & -14 & 10 \\
-18 & 24 & 8
\end{array}\right] .
\end{aligned}
$$

Clearly, $A B \neq B A$.
EXAMPLE 3 If $A=\left[\begin{array}{rrr}1 & -1 & 2 \\ 3 & 2 & 0 \\ -2 & 0 & 1\end{array}\right], B=\left[\begin{array}{rr}3 & 1 \\ 0 & 2 \\ -2 & 5\end{array}\right]$ and $C=\left[\begin{array}{rrr}2 & 1 & -3 \\ 3 & 0 & -1\end{array}\right]$ then verify that $(A B) C=A(B C)$.

SOLUTION We have

$$
\begin{aligned}
A B & =\left[\begin{array}{rrr}
1 & -1 & 2 \\
3 & 2 & 0 \\
-2 & 0 & 1
\end{array}\right]\left[\begin{array}{rr}
3 & 1 \\
0 & 2 \\
-2 & 5
\end{array}\right] \\
& =\left[\begin{array}{rr}
3-0-4 & 1-2+10 \\
9+0-0 & 3+4+0 \\
-6+0-2 & -2+0+5
\end{array}\right]=\left[\begin{array}{rr}
-1 & 9 \\
9 & 7 \\
-8 & 3
\end{array}\right] \\
\Rightarrow \quad(A B) C & =\left[\begin{array}{rr}
-1 & 9 \\
9 & 7 \\
-8 & 3
\end{array}\right]\left[\begin{array}{rrr}
2 & 1 & -3 \\
3 & 0 & -1
\end{array}\right] \\
& =\left[\begin{array}{rrr}
-2+27 & -1+0 & 3-9 \\
18+21 & 9+0 & -27-7 \\
-16+9 & -8+0 & 24-3
\end{array}\right]=\left[\begin{array}{rrr}
25 & -1 & -6 \\
39 & 9 & -34 \\
-7 & -8 & 21
\end{array}\right] . \\
\text { Also, } B C & =\left[\begin{array}{rr}
3 & 1 \\
0 & 2 \\
-2 & 5
\end{array}\right]\left[\begin{array}{lll}
2 & 1 & -3 \\
3 & 0 & -1
\end{array}\right]
\end{aligned}
$$

$$
\begin{aligned}
& =\left[\begin{array}{rrr}
6+3 & 3+0 & -9-1 \\
0+6 & 0+0 & 0-2 \\
-4+15 & -2+0 & 6-5
\end{array}\right]=\left[\begin{array}{rrr}
9 & 3 & -10 \\
6 & 0 & -2 \\
11 & -2 & 1
\end{array}\right] \\
\Rightarrow A(B C) & =\left[\begin{array}{rrr}
1 & -1 & 2 \\
3 & 2 & 0 \\
-2 & 0 & 1
\end{array}\right]\left[\begin{array}{rrr}
9 & 3 & -10 \\
6 & 0 & -2 \\
11 & -2 & 1
\end{array}\right] \\
& =\left[\begin{array}{rrr}
9-6+22 & 3-0-4 & -10+2+2 \\
27+12+0 & 9+0-0 & -30-4+0 \\
-18+0+11 & -6+0-2 & 20-0+1
\end{array}\right] \\
& =\left[\begin{array}{rrr}
25 & -1 & -6 \\
39 & 9 & -34 \\
-7 & -8 & 21
\end{array}\right] .
\end{aligned}
$$

Hence, $(A B) C=A(B C)$.
EXAMPLE 4 If $A=\left[\begin{array}{ll}3 & 2 \\ 1 & 0\end{array}\right], B=\left[\begin{array}{rrr}1 & -2 & 5 \\ 0 & 7 & 3\end{array}\right]$ and $C=\left[\begin{array}{rrr}8 & 1 & -6 \\ 2 & -5 & 0\end{array}\right]$, verify that $A(B+C)=(A B+A C)$.

SOLUTION We have

$$
\begin{aligned}
A(B+C) & =\left[\begin{array}{ll}
3 & 2 \\
1 & 0
\end{array}\right] \cdot\left\{\left[\begin{array}{rrr}
1 & -2 & 5 \\
0 & 7 & 3
\end{array}\right]+\left[\begin{array}{rrr}
8 & 1 & -6 \\
2 & -5 & 0
\end{array}\right]\right\} \\
& =\left[\begin{array}{ll}
3 & 2 \\
1 & 0
\end{array}\right]\left[\begin{array}{rrr}
9 & -1 & -1 \\
2 & 2 & 3
\end{array}\right] \\
& =\left[\begin{array}{rrr}
3 \cdot 9+2 \cdot 2 & 3 \cdot(-1)+2 \cdot 2 & 3 \cdot(-1)+2 \cdot 3 \\
1 \cdot 9+0 \cdot 2 & 1 \cdot(-1)+0 \cdot 2 & 1 \cdot(-1)+0 \cdot 3
\end{array}\right] \\
& =\left[\begin{array}{rrr}
31 & 1 & 3 \\
9 & -1 & -1
\end{array}\right]
\end{aligned}
$$

Now, $A B=\left[\begin{array}{ll}3 & 2 \\ 1 & 0\end{array}\right]\left[\begin{array}{rrr}1 & -2 & 5 \\ 0 & 7 & 3\end{array}\right]$

$$
\begin{aligned}
& =\left[\begin{array}{rrr}
3 \cdot 1+2 \cdot 0 & 3 \cdot(-2)+2 \cdot 7 & 3 \cdot 5+2 \cdot 3 \\
1 \cdot 1+0 \cdot 0 & 1 \cdot(-2)+0 \cdot 7 & 1 \cdot 5+0 \cdot 3
\end{array}\right] \\
& =\left[\begin{array}{rrr}
3 & 8 & 21 \\
1 & -2 & 5
\end{array}\right] .
\end{aligned}
$$

And, $A C=\left[\begin{array}{ll}3 & 2 \\ 1 & 0\end{array}\right]\left[\begin{array}{rrr}8 & 1 & -6 \\ 2 & -5 & 0\end{array}\right]$

$$
\begin{gathered}
=\left[\begin{array}{lll}
3 \cdot 8+2 \cdot 2 & 3 \cdot 1+2 \cdot(-5) & 3 \cdot(-6)+2 \cdot 0 \\
1 \cdot 8+0 \cdot 2 & 1 \cdot 1+0 \cdot(-5) & 1 \cdot(-6)+0 \cdot 0
\end{array}\right] \\
=\left[\begin{array}{rrr}
28 & -7 & -18 \\
8 & 1 & -6
\end{array}\right] . \\
\therefore(A B+A C)=\left[\begin{array}{rrr}
3 & 8 & 21 \\
1 & -2 & 5
\end{array}\right]+\left[\begin{array}{rrr}
28 & -7 & -18 \\
8 & 1 & -6
\end{array}\right] \\
=\left[\begin{array}{rrr}
31 & 1 & 3 \\
9 & -1 & -1
\end{array}\right] .
\end{gathered}
$$

Hence, $\quad A(B+C)=A B+A C$.
EXAMPLE 5 Give an example of two matrices $A$ and $B$ such that $A \neq O, B \neq O$ and $A B=B A=O$.

SOLUTION Let $A=\left[\begin{array}{ll}1 & 1 \\ 1 & 1\end{array}\right]$ and $B=\left[\begin{array}{rr}1 & -1 \\ -1 & 1\end{array}\right]$. Then,

$$
\begin{aligned}
A B & =\left[\begin{array}{ll}
1 & 1 \\
1 & 1
\end{array}\right]\left[\begin{array}{rr}
1 & -1 \\
-1 & 1
\end{array}\right] \\
& =\left[\begin{array}{ll}
1-1 & -1+1 \\
1-1 & -1+1
\end{array}\right]=\left[\begin{array}{ll}
0 & 0 \\
0 & 0
\end{array}\right] \\
\text { and } B A & =\left[\begin{array}{rr}
1 & -1 \\
-1 & 1
\end{array}\right]\left[\begin{array}{ll}
1 & 1 \\
1 & 1
\end{array}\right] \\
& =\left[\begin{array}{rr}
1-1 & 1-1 \\
-1+1 & -1+1
\end{array}\right]=\left[\begin{array}{ll}
0 & 0 \\
0 & 0
\end{array}\right] .
\end{aligned}
$$

Thus, $A \neq O, B \neq O$.
But, $A B=B A=O$.
EXAMPLE 6 If $A=\left[\begin{array}{cc}\cos ^{2} \theta & \cos \theta \sin \theta \\ \cos \theta \sin \theta & \sin ^{2} \theta\end{array}\right]$ and $B=\left[\begin{array}{cc}\cos ^{2} \phi & \cos \phi \sin \phi \\ \cos \phi \sin \phi & \sin ^{2} \phi\end{array}\right]$, show that $A B$ is a zero matrix if $\theta$ and $\phi$ differ by an odd multiple of $\frac{\pi}{2}$.

SOLUTION We have

$$
\left.\begin{array}{rl}
A B & =\left[\begin{array}{cc}
\cos ^{2} \theta & \cos \theta \sin \theta \\
\cos \theta \sin \theta & \sin ^{2} \theta
\end{array}\right]\left[\begin{array}{cc}
\cos ^{2} \phi & \cos \phi \sin \phi \\
\cos \phi \sin \phi & \sin ^{2} \phi
\end{array}\right] \\
& =\left[\begin{array}{cc}
\cos ^{2} \theta \cos ^{2} \phi+\cos \theta \sin \theta \cos \phi \sin \phi \\
\cos \theta \sin \theta \cos ^{2} \phi+\sin ^{2} \theta \cos \phi \sin \phi
\end{array}\right. \\
& \cos ^{2} \theta \cos \phi \sin \phi+\cos \theta \sin \theta \sin ^{2} \phi \\
& \cos \theta \sin \theta \cos \phi \sin \phi+\sin ^{2} \theta \sin ^{2} \phi
\end{array}\right]
$$

$$
\begin{aligned}
& =\left[\begin{array}{llll}
\cos \theta & \cos \phi \cdot \cos (\theta-\phi) & \cos \theta & \sin \phi \cdot \cos (\theta-\phi) \\
\sin \theta & \cos \phi \cdot \cos (\theta-\phi) & \sin \theta & \sin \phi \cdot \cos (\theta-\phi)
\end{array}\right] \\
& =\left[\begin{array}{ll}
0 & 0 \\
0 & 0
\end{array}\right]\left[\begin{array}{l}
\because(\theta-\phi) \text { being an odd multiple of }(\pi / 2), \\
\\
\text { we have } \cos (\theta-\phi)=0
\end{array}\right] .
\end{aligned}
$$

EXAMPLE 7 If $A=\left[\begin{array}{rr}3 & -5 \\ -4 & 2\end{array}\right]$, show that $A^{2}-5 A-14 I=O$.
[CBSE 2004]

SOLUTION We have

$$
\begin{aligned}
A^{2} & =\left[\begin{array}{rr}
3 & -5 \\
-4 & 2
\end{array}\right]\left[\begin{array}{rr}
3 & -5 \\
-4 & 2
\end{array}\right] \\
& =\left[\begin{array}{rr}
3 \cdot 3+(-5)(-4) & 3 \cdot(-5)+(-5) \cdot 2 \\
-4 \cdot 3+2 \cdot(-4) & -4 \cdot(-5)+2 \cdot 2
\end{array}\right]=\left[\begin{array}{rr}
29 & -25 \\
-20 & 24
\end{array}\right] \\
-5 A & =(-5)\left[\begin{array}{rr}
3 & -5 \\
-4 & 2
\end{array}\right]=\left[\begin{array}{rr}
-15 & 25 \\
20 & -10
\end{array}\right] \\
-14 I & =(-14)\left[\begin{array}{rr}
1 & 0 \\
0 & 1
\end{array}\right]=\left[\begin{array}{rr}
-14 & 0 \\
0 & -14
\end{array}\right] . \\
\therefore \quad A^{2}-5 A-14 I & =A^{2}+(-5) A+(-14 I) \\
& =\left[\begin{array}{rr}
29 & -25 \\
-20 & 24
\end{array}\right]+\left[\begin{array}{rr}
-15 & 25 \\
20 & -10
\end{array}\right]+\left[\begin{array}{rr}
-14 & 0 \\
0 & -14
\end{array}\right] \\
& =\left[\begin{array}{rr}
29+(-15)+(-14) & -25+25+0 \\
-20+20+0 & 24+(-10)+(-14)
\end{array}\right] \\
& =\left[\begin{array}{ll}
0 & 0 \\
0 & 0
\end{array}\right] .
\end{aligned}
$$

Hence, $A^{2}-5 A-14 I=O$.
$\underline{\text { EXAMPLE } 8}$ If $A=\left[\begin{array}{rr}1 & 0 \\ -1 & 7\end{array}\right]$, find $k$ so that $A^{2}=8 A+k I$.
[CBSE 2005C]

SOLUTION We have

$$
\begin{gathered}
A^{2}=\left[\begin{array}{rr}
1 & 0 \\
-1 & 7
\end{array}\right]\left[\begin{array}{rr}
1 & 0 \\
-1 & 7
\end{array}\right]=\left[\begin{array}{rr}
1-0 & 0+0 \\
-1-7 & 0+49
\end{array}\right]=\left[\begin{array}{rr}
1 & 0 \\
-8 & 49
\end{array}\right] ; \\
(8 A+k I)=8 \cdot\left[\begin{array}{rr}
1 & 0 \\
-1 & 7
\end{array}\right]+k \cdot\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right] \\
=\left[\begin{array}{rr}
8 & 0 \\
-8 & 56
\end{array}\right]+\left[\begin{array}{ll}
k & 0 \\
0 & k
\end{array}\right]=\left[\begin{array}{cc}
8+k & 0 \\
-8 & 56+k
\end{array}\right] \\
\therefore \quad A^{2}=8 A+k I \Rightarrow\left[\begin{array}{rr}
1 & 0 \\
-8 & 49
\end{array}\right]=\left[\begin{array}{cc}
8+k & 0 \\
-8 & 56+k
\end{array}\right] \\
\Rightarrow 8+k=1 \text { and } 56+k=49 \Rightarrow k=-7 .
\end{gathered}
$$

Hence, $k=-7$.

EXAMPLE 9 If $f(x)=x^{2}-5 x+7$ and $A=\left[\begin{array}{rr}3 & 1 \\ -1 & 2\end{array}\right]$, find $f(A)$. [CBSE 2004C,'07C] SOLUTION We have $f(A)=A^{2}-5 A+7 I$.

$$
\text { Now, } \begin{aligned}
A^{2} & =\left[\begin{array}{rr}
3 & 1 \\
-1 & 2
\end{array}\right]\left[\begin{array}{rr}
3 & 1 \\
-1 & 2
\end{array}\right] \\
& =\left[\begin{array}{rr}
9-1 & 3+2 \\
-3-2 & -1+4
\end{array}\right]=\left[\begin{array}{rr}
8 & 5 \\
-5 & 3
\end{array}\right] ; \\
-5 A & =\left[\begin{array}{ll}
(-5) \cdot 3 & (-5) \cdot 1 \\
(-5) \cdot(-1) & (-5) \cdot 2
\end{array}\right]=\left[\begin{array}{rr}
-15 & -5 \\
5 & -10
\end{array}\right] ; \\
7 I & =7 \cdot\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right]=\left[\begin{array}{ll}
7 & 0 \\
0 & 7
\end{array}\right] . \\
\therefore \quad f(A) & =A^{2}-5 A+7 I \\
& =\left[\begin{array}{rr}
8 & 5 \\
-5 & 3
\end{array}\right]+\left[\begin{array}{rr}
-15 & -5 \\
5 & -10
\end{array}\right]+\left[\begin{array}{ll}
7 & 0 \\
0 & 7
\end{array}\right] \\
& =\left[\begin{array}{rr}
8+(-15)+7 & 5+(-5)+0 \\
-5+5+0 & 3+(-10)+7
\end{array}\right]=\left[\begin{array}{ll}
0 & 0 \\
0 & 0
\end{array}\right] .
\end{aligned}
$$

Hence, $f(A)=\left[\begin{array}{ll}0 & 0 \\ 0 & 0\end{array}\right]$.
EXAMPLE 10 Find the matrix $A$ such that $\left[\begin{array}{rr}2 & -1 \\ 1 & 0 \\ -3 & 4\end{array}\right] \cdot A=\left[\begin{array}{rrr}-1 & -8 & -10 \\ 1 & -2 & -5 \\ 9 & 22 & 15\end{array}\right]$.
SOLUTION Clearly, the product is a $3 \times 3$ matrix and the prefactor is a $3 \times 2$ matrix. So, $A$ must be a $2 \times 3$ matrix.
Let $A=\left[\begin{array}{ccc}x & y & z \\ u & v & w\end{array}\right]$.
Then, the given equation becomes

$$
\begin{aligned}
& {\left[\begin{array}{rr}
2 & -1 \\
1 & 0 \\
-3 & 4
\end{array}\right]\left[\begin{array}{ccc}
x & y & z \\
u & v & w
\end{array}\right]=\left[\begin{array}{rrr}
-1 & -8 & -10 \\
1 & -2 & -5 \\
9 & 22 & 15
\end{array}\right]} \\
& \text { or }\left[\begin{array}{ccc}
2 x-u & 2 y-v & 2 z-w \\
x & y & z \\
-3 x+4 u & -3 y+4 v & -3 z+4 w
\end{array}\right]=\left[\begin{array}{rrr}
-1 & -8 & -10 \\
1 & -2 & -5 \\
9 & 22 & 15
\end{array}\right] .
\end{aligned}
$$

So, by the definition of equal matrices, we have

$$
\begin{aligned}
& 2 x-u=-1 ; 2 y-v=-8 ; 2 z-w=-10 ; x=1 ; y=-2 ; z=-5 . \\
\therefore \quad & x=1 ; y=-2 ; z=-5 ; u=3 ; v=4 \text { and } w=0 .
\end{aligned}
$$

Hence, $A=\left[\begin{array}{rrr}1 & -2 & -5 \\ 3 & 4 & 0\end{array}\right]$.
EXAMPLE 11 Find the value of $x$, if

$$
\left[\begin{array}{lll}
1 & x & 1
\end{array}\right]\left[\begin{array}{rrr}
1 & 3 & 2 \\
2 & 5 & 1 \\
15 & 3 & 2
\end{array}\right]\left[\begin{array}{l}
1 \\
2 \\
x
\end{array}\right]=O .
$$

[CBSE 2006C]

SOLUTION We have

$$
\begin{aligned}
& {\left[\begin{array}{lll}
1 & x & 1
\end{array}\right]_{1 \times 3}\left[\begin{array}{rrr}
1 & 3 & 2 \\
2 & 5 & 1 \\
15 & 3 & 2
\end{array}\right]_{3 \times 3}\left[\begin{array}{l}
1 \\
2 \\
x
\end{array}\right]_{3 \times 1}=O } \\
& \Rightarrow {[1+2 x+15 \quad 3+5 x+3 \quad 2+x+2]\left[\begin{array}{l}
1 \\
2 \\
x
\end{array}\right]=O } \\
& \Rightarrow {[16+2 x \quad 6+5 x \quad 4+x]\left[\begin{array}{c}
1 \\
2 \\
x
\end{array}\right]=O } \\
& \Rightarrow {[(16+2 x) \cdot 1+(6+5 x) \cdot 2+(4+x) \cdot x]=O } \\
& \Rightarrow(16+2 x)+(12+10 x)+\left(4 x+x^{2}\right)=0 \\
& \Rightarrow x^{2}+16 x+28=0 \\
& \Rightarrow(x+14)(x+2)=0 \\
& \Rightarrow x+14=0 \text { or } x+2=0 \\
& \Rightarrow x=-14 \text { or } x=-2 \\
& \text { Hence, } x=-14 \text { or } x=-2
\end{aligned}
$$

EXAMPLE 12 Solve for $x$ and $y$, given that $\left[\begin{array}{cc}x & y \\ 3 y & x\end{array}\right]\left[\begin{array}{l}1 \\ 2\end{array}\right]=\left[\begin{array}{l}3 \\ 5\end{array}\right]$.
[CBSE 2003C]

SOLUTION We have

$$
\begin{align*}
& {\left[\begin{array}{cc}
x & y \\
3 y & x
\end{array}\right]\left[\begin{array}{l}
1 \\
2
\end{array}\right]=\left[\begin{array}{l}
3 \\
5
\end{array}\right] } \\
\Rightarrow & {\left[\begin{array}{c}
x+2 y \\
3 y+2 x
\end{array}\right]=\left[\begin{array}{l}
3 \\
5
\end{array}\right] } \\
\Rightarrow & \left\{\begin{array}{c}
x+2 y=3 \\
2 x+3 y=5
\end{array}\right. \tag{i}
\end{align*}
$$

Multiplying (i) by 2 and subtracting (ii) from it, we get $y=1$.
Putting $y=1$ in (i), we get $x=1$.
Hence, $x=1$ and $y=1$.

EXAMPLE 13 Let $A=\left[\begin{array}{cc}0 & -\tan \frac{\alpha}{2} \\ \tan \frac{\alpha}{2} & 0\end{array}\right]$ and $I$ is the identity matrix of order 2 .
Show that $\quad(I+A)=(I-A) \cdot\left[\begin{array}{rr}\cos \alpha & -\sin \alpha \\ \sin \alpha & \cos \alpha\end{array}\right]$.
SOLUTION Let $\tan \frac{\alpha}{2}=t$.
Then, $\cos \alpha=\frac{1-\tan ^{2}(\alpha / 2)}{1+\tan ^{2}(\alpha / 2)}=\frac{1-t^{2}}{1+t^{2}}$
and $\quad \sin \alpha=\frac{2 \tan (\alpha / 2)}{1+\tan ^{2}(\alpha / 2)}=\frac{2 t}{1+t^{2}}$.
$\therefore \quad(I+A)=\left[\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right]+\left[\begin{array}{rr}0 & -t \\ t & 0\end{array}\right]=\left[\begin{array}{rr}1 & -t \\ t & 1\end{array}\right]$.
And, $(I-A)=\left[\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right]-\left[\begin{array}{rr}0 & -t \\ t & 0\end{array}\right]=\left[\begin{array}{rr}1 & t \\ -t & 1\end{array}\right]$.
$\therefore(I-A) \cdot\left[\begin{array}{rr}\cos \alpha & -\sin \alpha \\ \sin \alpha & \cos \alpha\end{array}\right]$

$$
=\left[\begin{array}{rr}
1 & t \\
-t & 1
\end{array}\right]\left[\begin{array}{ll}
\frac{1-t^{2}}{1+t^{2}} & \frac{-2 t}{1+t^{2}} \\
\frac{2 t}{1+t^{2}} & \frac{1-t^{2}}{1+t^{2}}
\end{array}\right]
$$

$=\left[\begin{array}{cc}\frac{1-t^{2}}{1+t^{2}}+\frac{2 t^{2}}{1+t^{2}} & \frac{-2 t}{1+t^{2}}+\frac{t\left(1-t^{2}\right)}{1+t^{2}} \\ \frac{-t\left(1-t^{2}\right)}{1+t^{2}}+\frac{2 t}{1+t^{2}} & \frac{2 t^{2}}{1+t^{2}}+\frac{1-t^{2}}{1+t^{2}}\end{array}\right]$
$=\left[\begin{array}{rr}1 & -t \\ t & 1\end{array}\right]=(I+A)$.
Hence, $(I+A)=(I-A)\left[\begin{array}{rr}\cos \alpha & -\sin \alpha \\ \sin \alpha & \cos \alpha\end{array}\right]$.
EXAMPLE 14 If $A=\left[\begin{array}{rr}\cos \theta & \sin \theta \\ -\sin \theta & \cos \theta\end{array}\right]$ then prove that

$$
A^{n}=\left[\begin{array}{rr}
\cos n \theta & \sin n \theta \\
-\sin n \theta & \cos n \theta
\end{array}\right], n \in N .
$$

[CBSE 2004, '05, '06]

SOLUTION We shall prove the result by using the principle of mathematical induction.

When $n=1$, we have

$$
A^{1}=\left[\begin{array}{rr}
\cos 1 \cdot \theta & \sin 1 \cdot \theta \\
-\sin 1 \cdot \theta & \cos 1 \cdot \theta
\end{array}\right]=\left[\begin{array}{rr}
\cos \theta & \sin \theta \\
-\sin \theta & \cos \theta
\end{array}\right] .
$$

Thus, the result is true for $n=1$.
Let the result be true for $n=k$.
Then, $A^{k}=\left[\begin{array}{rr}\cos k \theta & \sin k \theta \\ -\sin k \theta & \cos k \theta\end{array}\right]$.

$$
\begin{aligned}
& \therefore \quad A^{k+1} \\
& =A \cdot A^{k}=\left[\begin{array}{rr}
\cos \theta & \sin \theta \\
-\sin \theta & \cos \theta
\end{array}\right]\left[\begin{array}{rrr}
\cos k \theta & \sin k \theta \\
-\sin k \theta & \cos k \theta
\end{array}\right] \\
& =\left[\begin{array}{rrr}
\cos \theta & \cos k \theta-\sin \theta & \sin k \theta \\
-\sin \theta & \cos k \theta-\cos \theta & \sin k \theta
\end{array}-\sin \theta \sin k \theta+\sin \theta \cos k \theta\right. \\
& =\left[\begin{array}{rr}
\cos (\theta+k \theta) & \sin (\theta+k \theta) \\
-\sin (\theta+k \theta) & \cos (\theta+k \theta)
\end{array}\right] \\
& =\left[\begin{array}{rr}
\cos (k+1) \theta & \sin (k+1) \theta \\
-\sin (k+1) \theta & \cos (k+1) \theta
\end{array}\right]
\end{aligned}
$$

Thus, the result is true for $n=(k+1)$, whenever it is true for $n=k$.
Hence, $A^{n}=\left[\begin{array}{rr}\cos n \theta & \sin n \theta \\ -\sin n \theta & \cos n \theta\end{array}\right]$ for all values of $n \in N$.
EXAMPLE 15 If $A=\left[\begin{array}{ll}3 & -4 \\ 1 & -1\end{array}\right]$ then prove that $A^{n}=\left[\begin{array}{cc}1+2 n & -4 n \\ n & 1-2 n\end{array}\right]$ for all values of $n \in N$.

SOLUTION We shall prove the result by using the principle of mathematical induction.
When $n=1$, we have

$$
A^{1}=\left[\begin{array}{cc}
1+2 \cdot 1 & -4 \cdot 1 \\
1 & 1-2 \cdot 1
\end{array}\right]=\left[\begin{array}{cc}
1+2 & -4 \\
1 & 1-2
\end{array}\right]=\left[\begin{array}{cc}
3 & -4 \\
1 & -1
\end{array}\right] .
$$

Thus, the result is true for $n=1$.
Let the result be true for $n=k$. Then, $A^{k}=\left[\begin{array}{cc}1+2 k & -4 k \\ k & 1-2 k\end{array}\right]$.

$$
\therefore \quad \begin{aligned}
A^{k+1} & =A \cdot A^{k} \\
& =\left[\begin{array}{cc}
3 & -4 \\
1 & -1
\end{array}\right]\left[\begin{array}{cc}
1+2 k & -4 k \\
k & 1-2 k
\end{array}\right] \\
& =\left[\begin{array}{cc}
3+6 k-4 k & -12 k-4+8 k \\
1+2 k-k & -4 k-1+2 k
\end{array}\right]=\left[\begin{array}{cc}
3+2 k & -4 k-4 \\
k+1 & 1-2 k
\end{array}\right]
\end{aligned}
$$

$$
=\left[\begin{array}{cc}
1+2(k+1) & -4(k+1) \\
k+1 & 1-2(k+1)
\end{array}\right] .
$$

Thus, the result is true for $n=(k+1)$, whenever it is true for $n=k$.
So, the result is true for all $n \in N$.
Hence, $A^{n}=\left[\begin{array}{cc}1+2 n & -4 n \\ n & 1-2 n\end{array}\right]$ for all values of $n \in N$.
EXAMPLE 16 If $A=\left[\begin{array}{lll}1 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1\end{array}\right]$, prove that $A^{n}=\left[\begin{array}{lll}3^{n-1} & 3^{n-1} & 3^{n-1} \\ 3^{n-1} & 3^{n-1} & 3^{n-1} \\ 3^{n-1} & 3^{n-1} & 3^{n-1}\end{array}\right]$ for all values of $n \in N$.
SOLUTION We shall prove the result by using the principle of mathematical induction.
When $n=1$, we have

$$
A^{1}=\left[\begin{array}{lll}
3^{1-1} & 3^{1-1} & 3^{1-1} \\
3^{1-1} & 3^{1-1} & 3^{1-1} \\
3^{1-1} & 3^{1-1} & 3^{1-1}
\end{array}\right]=\left[\begin{array}{lll}
3^{0} & 3^{0} & 3^{0} \\
3^{0} & 3^{0} & 3^{0} \\
3^{0} & 3^{0} & 3^{0}
\end{array}\right]=\left[\begin{array}{lll}
1 & 1 & 1 \\
1 & 1 & 1 \\
1 & 1 & 1
\end{array}\right] .
$$

Thus, the result is true for $n=1$.
Let it be true for $n=k$. Then, $A^{k}=\left[\begin{array}{lll}3^{k-1} & 3^{k-1} & 3^{k-1} \\ 3^{k-1} & 3^{k-1} & 3^{k-1} \\ 3^{k-1} & 3^{k-1} & 3^{k-1}\end{array}\right]$.
$\therefore \quad A^{k+1}=A \cdot A^{k}$

$$
\begin{aligned}
= & {\left[\begin{array}{lll}
1 & 1 & 1 \\
1 & 1 & 1 \\
1 & 1 & 1
\end{array}\right]\left[\begin{array}{lll}
3^{k-1} & 3^{k-1} & 3^{k-1} \\
3^{k-1} & 3^{k-1} & 3^{k-1} \\
3^{k-1} & 3^{k-1} & 3^{k-1}
\end{array}\right] } \\
= & {\left[\begin{array}{lll}
3\left(3^{k-1}\right) & 3\left(3^{k-1}\right) & 3\left(3^{k-1}\right) \\
3\left(3^{k-1}\right) & 3\left(3^{k-1}\right) & 3\left(3^{k-1}\right) \\
3\left(3^{k-1}\right) & 3\left(3^{k-1}\right) & 3\left(3^{k-1}\right)
\end{array}\right]=\left[\begin{array}{lll}
3^{k} & 3^{k} & 3^{k} \\
3^{k} & 3^{k} & 3^{k} \\
3^{k} & 3^{k} & 3^{k}
\end{array}\right] . }
\end{aligned}
$$

Thus, the result is true for $n=(k+1)$, whenever it is true for $n=k$.
So, the result is true for all $n \in N$.
Hence, $A^{n}=\left[\begin{array}{lll}3^{n-1} & 3^{n-1} & 3^{n-1} \\ 3^{n-1} & 3^{n-1} & 3^{n-1} \\ 3^{n-1} & 3^{n-1} & 3^{n-1}\end{array}\right]$ for all values of $n \in N$.

EXAMPLE 17 If $A=\left[\begin{array}{ll}0 & 1 \\ 0 & 0\end{array}\right]$, prove that for all $n \in N$,

$$
(a I+b A)^{n}=a^{n} I+n a^{n-1} b A,
$$

where $I$ is the identity matrix of order 2 .
SOLUTION We shall prove the result by mathematical induction.
When $n=1$, we have:

$$
\text { LHS }=(a I+b A)^{1}=(a I+b A)=\left(a^{1} I+1 a^{0} b A\right)=\text { RHS } .
$$

So, the result is true for $n=1$.
Let it be true for $n=m$, so that

$$
\begin{align*}
\quad(a I+b A)^{m}= & a^{m} I+m a^{m-1} b A  \tag{i}\\
\therefore \quad(a I+b A)^{m+1} & =(a I+b A) \cdot(a I+b A)^{m} \\
& =(a I+b A) \cdot\left(a^{m} I+m a^{m-1} b A\right) \\
& =a I\left(a^{m} I+m a^{m-1} b A\right)+b A\left(a^{m} I+m a^{m-1} b A\right) \\
& =a^{m+1} I+m a^{m} b A+a^{m} b A+m a^{m-1} b^{2} A^{2} \\
& =a^{m+1}+(m+1) a^{m} b A \quad[\because \quad I I=I, \quad I A=A=A I]
\end{align*}
$$

This shows that the result is true for $n=(m+1)$, whenever it is true for $n=m$.
Hence, by the principle of mathematical induction, the result is true for all $n \in N$.

EXAMPLE 18 If $A=\operatorname{diag}[a, b, c]$, show that $A^{n}=\operatorname{diag}\left[a^{n}, b^{n}, c^{n}\right]$ for all $n \in N$.
SOLUTION We shall prove the result by mathematical induction.
When $n=1$, we have

$$
A^{1}=\operatorname{diag}\left[a^{1}, b^{1}, c^{1}\right]=\operatorname{diag}[a, b, c]=A .
$$

So, the result is true for $n=1$.
Let it be true for $n=m$, so that

$$
\begin{align*}
A^{m}= & \operatorname{diag}\left[a^{m}, b^{m}, c^{m}\right]  \tag{i}\\
\therefore \quad A^{m+1} & =A \cdot A^{m} \\
& =\operatorname{diag}[a, b, c] \cdot \operatorname{diag}\left[a^{m}, b^{m}, c^{m}\right][\operatorname{using}(\mathrm{i})] \\
& =\left[\begin{array}{lll}
a & 0 & 0 \\
0 & b & 0 \\
0 & 0 & c
\end{array}\right] \cdot\left[\begin{array}{lll}
a^{m} & 0 & 0 \\
0 & b^{m} & 0 \\
0 & 0 & c^{m}
\end{array}\right] \\
& =\left[\begin{array}{lll}
a^{m+1} & 0 & 0 \\
0 & b^{m+1} & 0 \\
0 & 0 & c^{m+1}
\end{array}\right]=\operatorname{diag}\left[a^{m+1}, b^{m+1}, c^{m+1}\right] .
\end{align*}
$$

This shows that the result is true for $n=(m+1)$, whenever it is true for $n=m$.
Hence, by the principle of mathematical induction, the result is true for all $n \in N$.

EXAMPLE 19 If $A$ is an $m \times n$ matrix and $B$ is a matrix given in such a way that $A B$ and $B A$ are both defined, show that $B$ is an $n \times m$ matrix.
solution Since $A B$ is defined, we have
number of rows in $B=$ number of columns in $A=n$.
Again, since $B A$ is defined, we have
number of columns in $B=$ number of rows in $A=m$.
Hence, the order of $B$ is $n \times m$.
EXAMPLE 20 If $A$ and $B$ are two matrices given in such a way that $A B$ and $A+B$ are both defined, show that $A$ and $B$ are square matrices of the same order.
solution Since $(A+B)$ is defined, it follows that both $A$ and $B$ are of the same order, say ( $m \times n$ ).
Thus, order of $A$ is $m \times n$ and order of $B$ is $m \times n$.
But, $A B$ is defined.
So, number of columns in $A=$ number of rows in $B$.
Consequently, $n=m$.
$\therefore A$ and $B$ are square matrices of the same order.

## VALUE BASED QUESTION

EXAMPLE 21 The cooperative store of a particular school has 10 dozen physics books, 8 dozen chemistry books and 5 dozen mathematics books. Their selling prices are ₹ 65.70 , ₹ 43.20 and ₹ 76.50 respectively. Find by matrix method the total amount received by the store from selling all these items.
SOLUTION We have

$$
=\left[\begin{array}{ccc}
\text { physics } & \text { chemistry } & \text { mathematics } \\
120 & 96 & 60
\end{array}\right]\left[\begin{array}{c}
₹ 65.70 \\
₹ 43.20 \\
₹ 76.50
\end{array}\right]
$$

$\therefore$ the total amount realised $=₹ 16621.20$.

