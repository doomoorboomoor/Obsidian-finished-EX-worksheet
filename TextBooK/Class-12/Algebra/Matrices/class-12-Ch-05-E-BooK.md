## Elementary Operations on Matrices

Given below are three row operations and three column operations on a matrix, which are called elementary operations or transformations.

EQUIVALENT MATRICES Two matrices $A$ and $B$ are said to be equivalent if one is obtained from the other by one or more elementary operations and we write, $A \sim B$.

## THREE ELEMENTARY ROW OPERATIONS

(i) Interchange of any two rows The interchange of $i$ th and $j$ th rows is denoted by $R_{i} \leftrightarrow R_{j}$.

EXAMPLE Let $A=\left[\begin{array}{rrr}3 & 2 & -1 \\ \sqrt{2} & 4 & 6 \\ 5 & -3 & 7\end{array}\right]$.

$$
\text { Applying } R_{2} \leftrightarrow R_{3} \text {, we get } A \sim\left[\begin{array}{rrr}
3 & 2 & -1 \\
5 & -3 & 7 \\
\sqrt{2} & 4 & 6
\end{array}\right] \text {. }
$$

(ii) Multiplication of the elements of a row by a nonzero number Suppose each element of $i$ th row of a given matrix is multiplied by a nonzero number $k$.

Then, we denote it by $R_{i} \rightarrow k R_{i}$.
EXAMPLE Let $A=\left[\begin{array}{rrr}3 & 2 & -1 \\ \sqrt{3} & -5 & 6 \\ 1 & 8 & 4\end{array}\right]$.

$$
\text { Applying } R_{2} \rightarrow 4 R_{2} \text {, we get } A \sim\left[\begin{array}{rrr}
3 & 2 & -1 \\
4 \sqrt{3} & -20 & 24 \\
1 & 8 & 4
\end{array}\right] \text {. }
$$

(iii) Multiplying each element of a row by a nonzero number and then adding them to the corresponding elements of another row Suppose each element of $j$ th row of a matrix $A$ is multiplied by a nonzero number $k$ and then added to the corresponding elements of $i$ th row.

We denote it by $\boldsymbol{R}_{\boldsymbol{i}} \rightarrow \boldsymbol{R}_{\boldsymbol{i}}+\boldsymbol{k} \boldsymbol{R}_{\boldsymbol{j}}$.
EXAMPLE Let $A=\left[\begin{array}{rrr}2 & -1 & 5 \\ -3 & 4 & \sqrt{2} \\ 7 & 6 & 3\end{array}\right]$.
Applying $R_{1} \rightarrow R_{1}+2 R_{3}$, we get $A \sim\left[\begin{array}{rrr}16 & 11 & 11 \\ -3 & 4 & \sqrt{2} \\ 7 & 6 & 3\end{array}\right]$.

## THREE ELEMENTARY COLUMN OPERATIONS

(i) Interchange of any two columns The interchange of $i$ th and $j$ th columns is denoted by $C_{i} \leftrightarrow C_{j}$.

EXAMPLE Let $A=\left[\begin{array}{rrr}2 & 1 & -3 \\ -1 & 5 & 4 \\ 6 & 3 & \frac{1}{2}\end{array}\right]$.

$$
\text { Applying } C_{1} \leftrightarrow C_{2} \text {, we get } A \sim\left[\begin{array}{rrr}
1 & 2 & -3 \\
5 & -1 & 4 \\
3 & 6 & \frac{1}{2}
\end{array}\right] \text {. }
$$

(ii) Multiplying each element of a column by a nonzero number Suppose each element of $i$ th column of matrix $A$ is multiplied by a nonzero number $k$.

Then, we write, $C_{i} \rightarrow k C_{i}$.
EXAMPLE Let $A=\left[\begin{array}{rrr}3 & 1 & -5 \\ \sqrt{2} & -2 & 4 \\ 6 & 2 & 8\end{array}\right]$.

$$
\text { Applying } C_{3} \rightarrow 2 C_{3} \text {, we get } A \sim\left[\begin{array}{rrr}
3 & 1 & -10 \\
\sqrt{2} & -2 & 8 \\
6 & 2 & 16
\end{array}\right] \text {. }
$$

(iii) Multiplying each element of a column of a given matrix $\boldsymbol{A}$ by a nonzero number and then adding to the corresponding elements of another column
Suppose each element of $j$ th column of a given matrix $A$ is multiplied by a nonzero number $k$ and then added to the corresponding elements of $i$ th column.

Then, we write, $C_{i} \rightarrow C_{i}+k C_{j}$.
EXAMPLE Let $A=\left[\begin{array}{rrr}2 & 0 & 4 \\ -1 & 3 & 1 \\ 5 & -2 & 6\end{array}\right]$.

$$
\text { Applying } C_{3} \rightarrow C_{3}+2 C_{1} \text {, we get } A \sim\left[\begin{array}{rrr}
2 & 0 & 8 \\
-1 & 3 & -1 \\
5 & -2 & 16
\end{array}\right] \text {. }
$$

INVERTIBLE MATRICES $A$ square matrix $A$ of order $n$ is said to be invertible if there exists a square matrix $B$ of order $n$ such that

$$
A B=B A=I
$$

Also, then $B$ is called the inverse of $A$ and we write, $A^{-\mathbf{1}}=B$.
EXAMPLE Let $A=\left[\begin{array}{ll}3 & 5 \\ 1 & 2\end{array}\right]$ and $B=\left[\begin{array}{rr}2 & -5 \\ -1 & 3\end{array}\right]$. Then,

$$
\begin{aligned}
& A B=\left[\begin{array}{ll}
3 & 5 \\
1 & 2
\end{array}\right]\left[\begin{array}{rr}
2 & -5 \\
-1 & 3
\end{array}\right]=\left[\begin{array}{rr}
6-5 & -15+15 \\
2-2 & -5+6
\end{array}\right]=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right]=I \\
& B A=\left[\begin{array}{rr}
2 & -5 \\
-1 & 3
\end{array}\right]\left[\begin{array}{ll}
3 & 5 \\
1 & 2
\end{array}\right]=\left[\begin{array}{rr}
6-5 & 10-10 \\
-3+3 & -5+6
\end{array}\right]=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right]=I
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \quad A B=B A=I . \\
& \text { Hence, } A^{-1}=B .
\end{aligned}
$$

THEOREM 1 (Uniqueness of Inverse) Every invertible square matrix has a unique inverse.
PROOF Let $A$ be an invertible square matrix of order $n$.
If possible, let $B$ as well as $C$ be the inverse of $A$.
Then, $A B=B A=I$ and $A C=C A=I$.
Now, $A C=I \Rightarrow B(A C)=B \cdot I=B$,

$$
B A=I \Rightarrow(B A) C=I \cdot C=C .
$$

But, $B(A C)=(B A) C$ [by associative law of multiplication]
$\therefore \quad B=C$.
Hence, an invertible matrix has a unique inverse.

## INVERSE OF A MATRIX BY ELEMENTARY ROW OPERATIONS

Let $A$ be a square matrix of order $n$.
We can write, $A=I \cdot A$.

Now, let a sequence of elementary row operations reduce $\boldsymbol{A}$ on LHS of (i) to $I$ and $I$ on RHS of (i) to a matrix $B$.

$$
\text { Then, } \begin{aligned}
I=B A & \Rightarrow I \cdot A^{-1}=(B A) A^{-1}=B\left(A A^{-1}\right)=B I \\
& \Rightarrow A^{-1}=B .
\end{aligned}
$$

We can summarise the above method as given below.
METHOD Step 1. Write $A=I \cdot A$.
Step 2. By using elementary row operations on $A$, transform it into a unit matrix.
Step 3. In the same order we apply elementary operations on $I$ to convert it into a matrix $B$.
Step 4. Then, $A^{-1}=B$.
REMARK If on applying one or more elementary row operations on $A$, we obtain all zeros in one or more rows, then we say that $A^{-1}$ does not exist.

## SOLVED EXAMPLES

EXAMPLE 1 By using elementary row operations, find the inverse of the matrix

$$
A=\left[\begin{array}{ll}
1 & -2 \\
2 & -6
\end{array}\right] .
$$

SOLUTION We have

$$
\left[\begin{array}{ll}
1 & -2 \\
2 & -6
\end{array}\right]=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right] \cdot A
$$

$\Rightarrow\left[\begin{array}{ll}1 & -2 \\ 0 & -2\end{array}\right]=\left[\begin{array}{rr}1 & 0 \\ -2 & 1\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow R_{2}-2 R_{1}\right]$
$\Rightarrow\left[\begin{array}{rr}1 & -2 \\ 0 & 1\end{array}\right]=\left[\begin{array}{cc}1 & 0 \\ 1 & \frac{-1}{2}\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow\left(\frac{-1}{2}\right) R_{2}\right]$
$\Rightarrow\left[\begin{array}{ll}1 & 0 \\ 0 & 1\end{array}\right]=\left[\begin{array}{rr}3 & -1 \\ 1 & -\frac{1}{2}\end{array}\right] \cdot A \quad\left[R_{1} \rightarrow R_{1}+2 R_{2}\right]$.
Hence, $A^{-1}=\left[\begin{array}{rr}3 & -1 \\ 1 & -\frac{1}{2}\end{array}\right]$.

EXAMPLE 2 By using elementary row operations, find the inverse of the matrix

$$
A=\left[\begin{array}{rr}
3 & -1 \\
-4 & 2
\end{array}\right]
$$

SOLUTION We have

$$
\begin{aligned}
& A=\left[\begin{array}{rr}
3 & -1 \\
-4 & 2
\end{array}\right]=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right] \cdot A \\
& \Rightarrow\left[\begin{array}{rr}
-1 & 1 \\
-4 & 2
\end{array}\right]=\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right] \cdot A \quad\left[R_{1} \rightarrow R_{1}+R_{2}\right] \\
& \Rightarrow\left[\begin{array}{rr}
1 & -1 \\
-4 & 2
\end{array}\right]=\left[\begin{array}{rr}
-1 & -1 \\
0 & 1
\end{array}\right] \cdot A \quad\left[R_{1} \rightarrow(-1) \cdot R_{1}\right] \\
& \Rightarrow\left[\begin{array}{rr}
1 & -1 \\
0 & -2
\end{array}\right]=\left[\begin{array}{rr}
-1 & -1 \\
-4 & -3
\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow R_{2}+4 R_{1}\right] \\
& \Rightarrow\left[\begin{array}{rr}
1 & -1 \\
0 & 1
\end{array}\right]=\left[\begin{array}{rr}
-1 & -1 \\
2 & \frac{3}{2}
\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow\left(\frac{-1}{2}\right) R_{2}\right] \\
& \Rightarrow\left[\begin{array}{rr}
1 & 0 \\
0 & 1
\end{array}\right]=\left[\begin{array}{rr}
1 & \frac{1}{2} \\
2 & \frac{3}{2}
\end{array}\right] \cdot A \quad\left[R_{1} \rightarrow R_{1}+R_{2}\right] \\
& \text { Hence, } A^{-1}=\left[\begin{array}{ll}
1 & \frac{1}{2} \\
2 & \frac{3}{2}
\end{array}\right]
\end{aligned}
$$

EXAMPLE 3 If $A=\left[\begin{array}{rr}6 & -3 \\ -2 & 1\end{array}\right]$, show that $A^{-1}$ does not exist.
SOLUTION We have

$$
\begin{aligned}
& {\left[\begin{array}{rr}
6 & -3 \\
-2 & 1
\end{array}\right]=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right] \cdot A } \\
\Rightarrow & {\left[\begin{array}{cc}
1 & -\frac{1}{2} \\
-2 & 1
\end{array}\right]=\left[\begin{array}{ll}
\frac{1}{6} & 0 \\
0 & 1
\end{array}\right] \cdot A \quad\left[R_{1} \rightarrow \frac{1}{6} R_{1}\right] } \\
\Rightarrow & {\left[\begin{array}{cc}
1 & -\frac{1}{2} \\
0 & 0
\end{array}\right]=\left[\begin{array}{ll}
\frac{1}{6} & 0 \\
\frac{1}{3} & 1
\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow R_{2}+2 R_{1}\right] . }
\end{aligned}
$$

Thus, we have all zeros in second row of the left-hand side matrix.
Hence, $A^{-1}$ does not exist.

EXAMPLE 4 By using elementary row operations, find the inverse of the matrix

$$
A=\left[\begin{array}{rrr}
1 & 3 & -2 \\
-3 & 0 & -5 \\
2 & 5 & 0
\end{array}\right] .
$$

SOLUTION We have

$$
\begin{aligned}
& {\left[\begin{array}{rrr}
1 & 3 & -2 \\
-3 & 0 & -5 \\
2 & 5 & 0
\end{array}\right]=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A } \\
\Rightarrow\left[\begin{array}{rrr}
1 & 3 & -2 \\
0 & 9 & -11 \\
0 & -1 & 4
\end{array}\right] & =\left[\begin{array}{rrr}
1 & 0 & 0 \\
3 & 1 & 0 \\
-2 & 0 & 1
\end{array}\right] \cdot A\left[\begin{array}{ll}
R_{2} \rightarrow R_{2}+3 R_{1} \\
R_{3} \rightarrow R_{3}-2 R_{1}
\end{array}\right] \\
\Rightarrow\left[\begin{array}{rrr}
1 & 3 & -2 \\
0 & -1 & 4 \\
0 & 9 & -11
\end{array}\right] & =\left[\begin{array}{rrr}
1 & 0 & 0 \\
-2 & 0 & 1 \\
3 & 1 & 0
\end{array}\right] \cdot A l l \\
\Rightarrow\left[\begin{array}{rrr}
1 & 0 & 10 \\
0 & -1 & 4 \\
0 & 0 & 25
\end{array}\right] & {\left[\begin{array}{rrr}
-5 & 0 & 3 \\
-2 & 0 & 1 \\
-15 & 1 & 9
\end{array}\right] \cdot A\left[\begin{array}{ll}
R_{1} \rightarrow R_{3}+3 R_{2} & \\
R_{3} \rightarrow R_{3}+9 R_{2}
\end{array}\right] } \\
\Rightarrow & {\left[\begin{array}{rrr}
1 & 0 & 10 \\
0 & 1 & -4 \\
0 & 0 & 25
\end{array}\right]=\left[\begin{array}{rrr}
-5 & 0 & 3 \\
2 & 0 & -1 \\
-15 & 1 & 9
\end{array}\right] \cdot A l }
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow\left[\begin{array}{rrr}
1 & 0 & 10 \\
0 & 1 & -4 \\
0 & 0 & 1
\end{array}\right]=\left[\begin{array}{ccc}
-5 & 0 & 3 \\
2 & 0 & -1 \\
\frac{-3}{5} & \frac{1}{25} & \frac{9}{25}
\end{array}\right] \cdot A\left[R_{3} \rightarrow \frac{1}{25} R_{3}\right] \\
& \Rightarrow\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]=\left[\begin{array}{ccc}
1 & \frac{-2}{5} & \frac{-3}{5} \\
\frac{-2}{5} & \frac{4}{25} & \frac{11}{25} \\
\frac{-3}{5} & \frac{1}{25} & \frac{9}{25}
\end{array}\right] \cdot A \quad\left[\begin{array}{l}
R_{1} \rightarrow R_{1}-10 R_{3} \\
R_{2} \rightarrow R_{2}+4 R_{3}
\end{array}\right] . \\
& \text { Hence, } A^{-1}=\left[\begin{array}{ccc}
1 & \frac{-2}{5} & \frac{-3}{5} \\
\frac{-2}{5} & \frac{4}{25} & \frac{11}{25} \\
\frac{-3}{5} & \frac{1}{25} & \frac{9}{25}
\end{array}\right] .
\end{aligned}
$$

EXAMPLE 5 By using elementary row operations, find the inverse of the matrix

$$
A=\left[\begin{array}{rrr}
3 & -1 & -2 \\
2 & 0 & -1 \\
3 & -5 & 0
\end{array}\right] .
$$

SOLUTION We have

$$
\begin{aligned}
& {\left[\begin{array}{rrr}
3 & -1 & -2 \\
2 & 0 & -1 \\
3 & -5 & 0
\end{array}\right]=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A } \\
\Rightarrow & {\left[\begin{array}{rrr}
1 & -1 & -1 \\
2 & 0 & -1 \\
3 & -5 & 0
\end{array}\right]=\left[\begin{array}{rrr}
1 & -1 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A \quad\left[R_{1} \rightarrow R_{1}-R_{2}\right] } \\
\Rightarrow & {\left[\begin{array}{rrr}
1 & -1 & -1 \\
0 & 2 & 1 \\
0 & -2 & 3
\end{array}\right]=\left[\begin{array}{rrr}
1 & -1 & 0 \\
-2 & 3 & 0 \\
-3 & 3 & 1
\end{array}\right] \cdot A \quad\left[\begin{array}{ll}
R_{2} \rightarrow R_{2}-2 R_{1} & \\
R_{3} \rightarrow R_{3}-3 R_{1}
\end{array}\right] } \\
\Rightarrow & {\left[\begin{array}{rrr}
1 & -1 & -1 \\
0 & 1 & \frac{1}{2} \\
0 & -2 & 3
\end{array}\right]=\left[\begin{array}{lll}
1 & -1 & 0 \\
-1 & \frac{3}{2} & 0 \\
-3 & 3 & 1
\end{array}\right] \cdot A \quad\left\{R_{2} \rightarrow \frac{1}{2} R_{2}\right\} }
\end{aligned}
$$

$$
\begin{aligned}
& \Rightarrow\left[\begin{array}{ccc}
1 & 0 & \frac{-1}{2} \\
0 & 1 & \frac{1}{2} \\
0 & 0 & 4
\end{array}\right]=\left[\begin{array}{ccc}
0 & \frac{1}{2} & 0 \\
-1 & \frac{3}{2} & 0 \\
-5 & 6 & 1
\end{array}\right] \cdot A\left\{\begin{array}{l}
R_{1} \rightarrow R_{1}+R_{2} \\
R_{3} \rightarrow R_{3}+2 R_{2}
\end{array}\right\} \\
& \Rightarrow\left[\begin{array}{ccc}
1 & 0 & \frac{-1}{2} \\
0 & 1 & \frac{1}{2} \\
0 & 0 & 1
\end{array}\right]=\left[\begin{array}{ccc}
0 & \frac{1}{2} & 0 \\
-1 & \frac{3}{2} & 0 \\
\frac{-5}{4} & \frac{3}{2} & \frac{1}{4}
\end{array}\right] \cdot A\left\{R_{3} \rightarrow \frac{1}{4} R_{3}\right\} \\
& \Rightarrow\left[\begin{array}{ccc}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]=\left[\begin{array}{ccc}
\frac{-5}{8} & \frac{5}{4} & \frac{1}{8} \\
\frac{-3}{8} & \frac{3}{4} & \frac{-1}{8} \\
\frac{-5}{4} & \frac{3}{2} & \frac{1}{4}
\end{array}\right] \cdot A .\left\{\begin{array}{l}
R_{1} \rightarrow R_{1}+\frac{1}{2} R_{3} \\
R_{2} \rightarrow R_{2}-\frac{1}{2} R_{3}
\end{array}\right\} \\
& \text { Hence, } A^{-1}=\left[\begin{array}{ccc}
\frac{-5}{8} & \frac{5}{4} & \frac{1}{8} \\
\frac{-3}{8} & \frac{3}{4} & \frac{-1}{8} \\
\frac{-5}{4} & \frac{3}{2} & \frac{1}{4}
\end{array}\right] .
\end{aligned}
$$

EXAMPLE 6 By using elementary row transformations, find the inverse of the matrix

$$
A=\left[\begin{array}{rrr}
2 & 0 & -1 \\
5 & 1 & 0 \\
0 & 1 & 3
\end{array}\right]
$$

SOLUTION We have

$$
\begin{aligned}
{\left[\begin{array}{rrr}
2 & 0 & -1 \\
5 & 1 & 0 \\
0 & 1 & 3
\end{array}\right] } & =\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A \\
\Rightarrow\left[\begin{array}{rrr}
2 & 0 & -1 \\
1 & 1 & 2 \\
0 & 1 & 3
\end{array}\right] & =\left[\begin{array}{rrr}
1 & 0 & 0 \\
-2 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow R_{2}-2 R_{1}\right] \\
\Rightarrow\left[\begin{array}{rrr}
1 & 1 & 2 \\
2 & 0 & -1 \\
0 & 1 & 3
\end{array}\right] & =\left[\begin{array}{rrr}
-2 & 1 & 0 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A \quad\left[R_{1} \leftrightarrow R_{2}\right]
\end{aligned}
$$

$\Rightarrow\left[\begin{array}{rrr}1 & 1 & 2 \\ 0 & -2 & -5 \\ 0 & 1 & 3\end{array}\right]=\left[\begin{array}{rrr}-2 & 1 & 0 \\ 5 & -2 & 0 \\ 0 & 0 & 1\end{array}\right] \cdot A \quad\left[R_{2} \rightarrow R_{2}-2 R_{1}\right]$
$\Rightarrow\left[\begin{array}{rrr}1 & 1 & 2 \\ 0 & 1 & 3 \\ 0 & -2 & -5\end{array}\right]=\left[\begin{array}{rrr}-2 & 1 & 0 \\ 0 & 0 & 1 \\ 5 & -2 & 0\end{array}\right] \cdot A \quad\left[R_{2} \leftrightarrow R_{3}\right]$
$\Rightarrow\left[\begin{array}{rrr}1 & 0 & -1 \\ 0 & 1 & 3 \\ 0 & 0 & 1\end{array}\right]=\left[\begin{array}{rrr}-2 & 1 & -1 \\ 0 & 0 & 1 \\ 5 & -2 & 2\end{array}\right] \cdot A\left[\begin{array}{l}R_{1} \rightarrow R_{1}-R_{2} \\ R_{3} \rightarrow R_{3}+2 R_{2}\end{array}\right]$
$\Rightarrow\left[\begin{array}{lll}1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1\end{array}\right]=\left[\begin{array}{rrr}3 & -1 & 1 \\ -15 & 6 & -5 \\ 5 & -2 & 2\end{array}\right] \cdot A\left[\begin{array}{l}R_{1} \rightarrow R_{1}+R_{3} \\ R_{2} \rightarrow R_{2}-3 R_{3}\end{array}\right]$.
Hence, $A^{-1}=\left[\begin{array}{rrr}3 & -1 & 1 \\ -15 & 6 & -5 \\ 5 & -2 & 2\end{array}\right]$.
EXAMPLE 7 If $A=\left[\begin{array}{rrr}1 & -1 & 1 \\ 2 & 1 & -1 \\ -1 & -2 & 2\end{array}\right]$, show that $A^{-1}$ does not exist.
SOLUTION We have

$$
\begin{aligned}
& {\left[\begin{array}{rrr}
1 & -1 & 1 \\
2 & 1 & -1 \\
-1 & -2 & 2
\end{array}\right]=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \cdot A } \\
\Rightarrow & {\left[\begin{array}{rrr}
1 & -1 & 1 \\
0 & 3 & -3 \\
0 & -3 & 3
\end{array}\right]=\left[\begin{array}{rrr}
1 & 0 & 0 \\
-2 & 1 & 0 \\
1 & 0 & 1
\end{array}\right] \cdot A\left[\begin{array}{l}
R_{2} \rightarrow R_{2}-2 R_{1} \\
R_{3} \rightarrow R_{3}+R_{1}
\end{array}\right] } \\
\Rightarrow & {\left[\begin{array}{rrr}
1 & -1 & 1 \\
0 & 3 & -3 \\
0 & 0 & 0
\end{array}\right]=\left[\begin{array}{rrr}
1 & 0 & 0 \\
-2 & 1 & 0 \\
-1 & 1 & 1
\end{array}\right] \cdot A\left[\begin{array}{ll}
R_{3} \rightarrow R_{3}+R_{2} &
\end{array}\right] }
\end{aligned}
$$

Thus, we have all zeros in 3rd row of the left-hand side matrix.
Hence, $A^{-1}$ does not exist.

