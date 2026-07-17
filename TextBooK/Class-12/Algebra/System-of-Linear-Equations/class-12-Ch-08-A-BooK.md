## 8. System of Linear Equations

### Solving a System of Linear Equations by Matrix Method

**Consistent System of Equations:** A given system of equations is said to be consistent if it has one or more solutions.

**Inconsistent System of Equations:** A given system of equations is said to be inconsistent if it has no solution.

Consider the system of equations

$$
\begin{aligned}
& a_{1} x+b_{1} y+c_{1} z=d_{1} \\
& a_{2} x+b_{2} y+c_{2} z=d_{2} \\
& a_{3} x+b_{3} y+c_{3} z=d_{3}
\end{aligned}
$$

Let $A=\left[\begin{array}{lll}a_{1} & b_{1} & c_{1} \\ a_{2} & b_{2} & c_{2} \\ a_{3} & b_{3} & c_{3}\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $B=\left[\begin{array}{l}d_{1} \\ d_{2} \\ d_{3}\end{array}\right]$.

Then, the given system can be written as

$$
\left[\begin{array}{lll}
a_{1} & b_{1} & c_{1} \\
a_{2} & b_{2} & c_{2} \\
a_{3} & b_{3} & c_{3}
\end{array}\right]\left[\begin{array}{l}
x \\
y \\
z
\end{array}\right]=\left[\begin{array}{l}
d_{1} \\
d_{2} \\
d_{3}
\end{array}\right]
$$

$\therefore AX=B$.

#### Case 1: When $|A| \neq 0$

In this case, $A^{-1}$ exists.

$$
\begin{array}{rlrl}
\therefore AX=B & \Rightarrow A^{-1}(A X)=A^{-1} B & \\
& \Rightarrow\left(A^{-1} A\right) X=A^{-1} B & & {[\text { by associative law }]} \\
& \Rightarrow I \cdot X=A^{-1} B & & {\left[\because A^{-1} A=I\right]} \\
& \Rightarrow X=A^{-1} B . & &
\end{array}
$$

Since $A^{-1}$ is unique, the given system has a **unique solution**.

Thus, when $|A| \neq 0$, then the given system is **consistent** and it has a unique solution.

#### Case 2: When $|A|=0$ and $(\operatorname{adj} A) B \neq O$

In this case, the given system has **no solution** and hence it is **inconsistent**.

#### Case 3: When $|A|=0$ and $(\operatorname{adj} A) B=O$

In this case, the given system has **infinitely many solutions**.

---

### Summary

Let $AX=B$ be the given system of equations.

- (i) If $|A| \neq 0$, the system has a **unique solution**.
- (ii) If $|A|=0$ and $(\operatorname{adj} A) B \neq O$ then the given system has **no solution** (inconsistent).
- (iii) If $|A|=0$ and $(\operatorname{adj} A) B=O$ then the system has **infinitely many solutions** (consistent).

---

## Solved Examples

### Example 1:

Use matrix method to show that the system of equations

$$
\begin{aligned}
2 x+5 y & =7 \\
6 x+15 y & =13
\end{aligned}
$$

is inconsistent.

#### Solution:

The given equations are

$$
\begin{align*}
2 x+5 y & =7  \tag{i}\\
6 x+15 y & =13 \tag{ii}
\end{align*}
$$

Let $A=\left[\begin{array}{rr}2 & 5 \\ 6 & 15\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y\end{array}\right]$ and $B=\left[\begin{array}{r}7 \\ 13\end{array}\right]$.

Then, the given system in matrix form is $AX=B$.

Now, $|A|=\left|\begin{array}{rr}2 & 5 \\ 6 & 15\end{array}\right|=0$.

The system will be inconsistent if $(\operatorname{adj} A) B \neq O$.

The minors of the elements of $|A|$ are

$$
\begin{array}{ll}
M_{11}=15, & M_{12}=6 ; \\
M_{21}=5, & M_{22}=2 .
\end{array}
$$

So, the cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=15, \quad A_{12}=-6 ; \\
& A_{21}=-5, \quad A_{22}=2 . \\
\therefore \quad & \operatorname{adj} A=\left[\begin{array}{rr}
15 & -6 \\
-5 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
15 & -5 \\
-6 & 2
\end{array}\right] \\
\Rightarrow \quad & (\operatorname{adj} A) B=\left[\begin{array}{rr}
15 & -5 \\
-6 & 2
\end{array}\right]\left[\begin{array}{r}
7 \\
13
\end{array}\right]=\left[\begin{array}{r}
105-65 \\
-42+26
\end{array}\right]=\left[\begin{array}{r}
40 \\
-16
\end{array}\right] \neq O .
\end{aligned}
$$

Thus, $|A|=0$ and $(\operatorname{adj} A) B \neq O$.

Hence, the given system of equations is **inconsistent**.

---

### Example 2:

Use matrix method to show that the following system of equations is inconsistent:

$$
\begin{array}{r}
3 x-y+2 z=3 \\
2 x+y+3 z=5 \\
x-2 y-z=1
\end{array}
$$

#### Solution:

Let us take

$$
A=\left[\begin{array}{rrr}
3 & -1 & 2 \\
2 & 1 & 3 \\
1 & -2 & -1
\end{array}\right], X=\left[\begin{array}{l}
x \\
y \\
z
\end{array}\right] \text { and } B=\left[\begin{array}{l}
3 \\
5 \\
1
\end{array}\right] .
$$

The given system in matrix form is $AX=B$.

Now, $|A|=\left|\begin{array}{rrr}3 & -1 & 2 \\ 2 & 1 & 3 \\ 1 & -2 & -1\end{array}\right|$

$$
\begin{aligned}
& =3(-1+6)+1 \cdot(-2-3)+2 \cdot(-4-1) \\
& =(15-5-10)=0
\end{aligned}
$$

So, the system will be inconsistent if $(\operatorname{adj} A) \cdot B \neq O$.

The minors of the elements of $|A|$ are

$$
\begin{array}{lll}
M_{11}=5, & M_{12}=-5, & M_{13}=-5 ; \\
M_{21}=5, & M_{22}=-5, & M_{23}=-5 ; \\
M_{31}=-5, & M_{32}=5, & M_{33}=5 .
\end{array}
$$

So, the cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=5, A_{12}=5, A_{13}=-5 ; \\
& A_{21}=-5, A_{22}=-5, A_{23}=5 ; \\
& A_{31}=-5, A_{32}=-5, A_{33}=5 . \\
\therefore & (\operatorname{adj} A)=\left[\begin{array}{rrr}
5 & 5 & -5 \\
-5 & -5 & 5 \\
-5 & -5 & 5
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
5 & -5 & -5 \\
5 & -5 & -5 \\
-5 & 5 & 5
\end{array}\right] \\
\Rightarrow & (\operatorname{adj} A) B=\left[\begin{array}{rrr}
5 & -5 & -5 \\
5 & -5 & -5 \\
-5 & 5 & 5
\end{array}\right]\left[\begin{array}{c}
3 \\
5 \\
1
\end{array}\right] \\
& =\left[\begin{array}{r}
5 \cdot 3+(-5) \cdot 5+(-5) \cdot 1 \\
5 \cdot 3+(-5) \cdot 5+(-5) \cdot 1 \\
(-5) \cdot 3+5 \cdot 5+5 \cdot 1
\end{array}\right]=\left[\begin{array}{r}
15-25-5 \\
15-25-5 \\
-15+25+5
\end{array}\right] \\
& =\left[\begin{array}{r}
-15 \\
-15 \\
15
\end{array}\right] \neq O .
\end{aligned}
$$

Thus, $|A|=0$ and $(\operatorname{adj} A) B \neq O$.

Hence, the given system of equations is **inconsistent**.

---

### Example 3:

Show that the following system of equations is consistent and solve it:

$$
\begin{aligned}
& 2 x+5 y=1 \\
& 3 x+2 y=7
\end{aligned}
$$

#### Solution:

The given system of equations is

$$
\begin{align*}
& 2 x+5 y=1  \tag{i}\\
& 3 x+2 y=7 \tag{ii}
\end{align*}
$$

Let $A=\left[\begin{array}{ll}2 & 5 \\ 3 & 2\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y\end{array}\right]$ and $B=\left[\begin{array}{l}1 \\ 7\end{array}\right]$.

Then, the given system is $AX=B$.

Now, $|A|=\left|\begin{array}{ll}2 & 5 \\ 3 & 2\end{array}\right|=(4-15)=-11 \neq 0$.

Hence, the given system has a **unique solution**.

The minors of the elements of $|A|$ are

$$
\begin{array}{ll}
M_{11}=2, & M_{12}=3 ; \\
M_{21}=5, & M_{22}=2 .
\end{array}
$$

So, the cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=2, A_{12}=-3 ; \\
& A_{21}=-5, A_{22}=2 .
\end{aligned}
$$

$$
\therefore (\operatorname{adj} A)=\left[\begin{array}{rr}
2 & -3 \\
-5 & 2
\end{array}\right]^{\prime}=\left[\begin{array}{rr}
2 & -5 \\
-3 & 2
\end{array}\right]
$$

$$
\Rightarrow A^{-1}=\frac{1}{|A|}(\operatorname{adj} A)=\frac{-1}{11} \cdot\left[\begin{array}{rr}
2 & -5 \\
-3 & 2
\end{array}\right]=\left[\begin{array}{cc}
\frac{-2}{11} & \frac{5}{11} \\
\frac{3}{11} & \frac{-2}{11}
\end{array}\right]
$$

$$
\Rightarrow X=A^{-1} B
$$

$$
\Rightarrow {\left[\begin{array}{l}
x \\
y
\end{array}\right]=\left[\begin{array}{cc}
\frac{-2}{11} & \frac{5}{11} \\
\frac{3}{11} & \frac{-2}{11}
\end{array}\right]\left[\begin{array}{l}
1 \\
7
\end{array}\right]=\left[\begin{array}{c}
\frac{-2}{11}+\frac{35}{11} \\
\frac{3}{11}-\frac{14}{11}
\end{array}\right]=\left[\begin{array}{r}
3 \\
-1
\end{array}\right] }
$$

$$
\Rightarrow x=3 \text { and } y=-1 .
$$

Hence, $x=3$ and $y=-1$.

---

### Example 4:

If $A=\left[\begin{array}{rrr}1 & 2 & -3 \\ 2 & 3 & 2 \\ 3 & -3 & -4\end{array}\right]$, find $A^{-1}$ and hence solve the system of linear equations:

$x+2 y-3 z=-4 ; 2 x+3 y+2 z=2 ; 3 x-3 y-4 z=11 .$

[CBSE 2012C]

#### Solution:

The given equations are $x+2 y-3 z=-4$.

$$
\begin{align*}
& 2 x+3 y+2 z=2  \tag{ii}\\
& 3 x-3 y-4 z=11
\end{align*}
$$

Let $A=\left[\begin{array}{rrr}1 & 2 & -3 \\ 2 & 3 & 2 \\ 3 & -3 & -4\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $B=\left[\begin{array}{r}-4 \\ 2 \\ 11\end{array}\right]$.

So, the given system in matrix form is $AX=B$.

Now, $|A|=\left|\begin{array}{rrr}1 & 2 & -3 \\ 2 & 3 & 2 \\ 3 & -3 & -4\end{array}\right|=\left|\begin{array}{rrr}1 & 2 & -3 \\ 0 & -1 & 8 \\ 0 & -9 & 5\end{array}\right|$

$$
\begin{aligned}
& \quad\left[R_{2} \rightarrow R_{2}-2 R_{1} \text { and } R_{3} \rightarrow R_{3}-3 R_{1}\right] \\
& =1 \cdot(-5+72)=67 \neq 0 .
\end{aligned}
$$

Thus, $A$ is invertible.

So, the system has a unique solution, $X=A^{-1} B$.

Now, the cofactors of the elements of $|A|$ are

$$
\begin{array}{ll} 
& A_{11}=-6, \quad A_{12}=14, \quad A_{13}=-15 ; \\
& A_{21}=17, \quad A_{22}=5, \quad A_{23}=9 ; \\
& A_{31}=13, \quad A_{32}=-8, \quad A_{33}=-1 .
\end{array}
$$

$$
\therefore \operatorname{adj} A=\left[\begin{array}{rrr}
-6 & 14 & -15 \\
17 & 5 & 9 \\
13 & -8 & -1
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
-6 & 17 & 13 \\
14 & 5 & -8 \\
-15 & 9 & -1
\end{array}\right] .
$$

So,
$$
A^{-1}=\frac{1}{|A|} \cdot \operatorname{adj} A=\frac{1}{67} \cdot\left[\begin{array}{rrr}
-6 & 17 & 13 \\
14 & 5 & -8 \\
-15 & 9 & -1
\end{array}\right] .
$$

$$
\therefore X=A^{-1} B
$$

or
$$
{\left[\begin{array}{l}
x \\
y \\
z
\end{array}\right]=\frac{1}{67} \cdot\left[\begin{array}{rrr}
-6 & 17 & 13 \\
14 & 5 & -8 \\
-15 & 9 & -1
\end{array}\right] \cdot\left[\begin{array}{r}
-4 \\
2 \\
11
\end{array}\right]}
$$

$$
=\frac{1}{67} \cdot\left[\begin{array}{r}
201 \\
-134 \\
67
\end{array}\right]=\left[\begin{array}{r}
3 \\
-2 \\
1
\end{array}\right] .
$$

$\therefore x=3, y=-2$ and $z=1$.

---

### Example 5:

Using matrices, solve the following system of linear equations:

$$
\begin{aligned}
3 x+4 y+2 z & =8 \\
2 y-3 z & =3 \\
x-2 y+6 z & =-2
\end{aligned}
$$

[CBSE 2006C]

#### Solution:

The given equations are

$$
\begin{array}{r}
3 x+4 y+2 z=8 \\
2 y-3 z=3 \\
x-2 y+6 z=-2 \tag{iii}
\end{array}
$$

Let $A=\left[\begin{array}{rrr}3 & 4 & 2 \\ 0 & 2 & -3 \\ 1 & -2 & 6\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $B=\left[\begin{array}{r}8 \\ 3 \\ -2\end{array}\right]$.

So, the given system in matrix form is $AX=B$.

Now, $\quad|A|=\left|\begin{array}{rrr}3 & 4 & 2 \\ 0 & 2 & -3 \\ 1 & -2 & 6\end{array}\right|=\left|\begin{array}{rrr}0 & 10 & -16 \\ 0 & 2 & -3 \\ 1 & -2 & 6\end{array}\right| \quad\left[R_{1} \rightarrow R_{1}-3 R_{3}\right]$

$$
=1 \cdot(-30+32)=2 \neq 0 .
$$

So, $A$ is invertible.

Therefore, the given system has a unique solution, $X=A^{-1} B$.

Now, the minors of the elements of $|A|$ are

$$
\begin{aligned}
& M_{11}=6, \quad M_{12}=3, \quad M_{13}=-2 ; \\
& M_{21}=28, \quad M_{22}=16, \quad M_{23}=-10 ; \\
& M_{31}=-16, \quad M_{32}=-9, \quad M_{33}=6 .
\end{aligned}
$$

---

The cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=6, \quad A_{12}=-3, \quad A_{13}=-2 ; \\
& A_{21}=-28, \quad A_{22}=16, \quad A_{23}=10 ; \\
& A_{31}=-16, \quad A_{32}=9, \quad A_{33}=6 . \\
\therefore & (\operatorname{adj} A)=\left[\begin{array}{rrr}
6 & -3 & -2 \\
-28 & 16 & 10 \\
-16 & 9 & 6
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
6 & -28 & -16 \\
-3 & 16 & 9 \\
-2 & 10 & 6
\end{array}\right] \\
\Rightarrow & A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A) \\
& =\frac{1}{2} \cdot\left[\begin{array}{rrr}
6 & -28 & -16 \\
-3 & 16 & 9 \\
-2 & 10 & 6
\end{array}\right]=\left[\begin{array}{rrr}
3 & -14 & -8 \\
\frac{-3}{2} & 8 & \frac{9}{2} \\
-1 & 5 & 3
\end{array}\right] . \\
\therefore & X=A^{-1} B \Rightarrow\left[\begin{array}{c}
x \\
y \\
z
\end{array}\right]=\left[\begin{array}{rrr}
3 & -14 & -8 \\
\frac{-3}{2} & 8 & \frac{9}{2} \\
-1 & 5 & 3
\end{array}\right]\left[\begin{array}{r}
8 \\
3 \\
-2
\end{array}\right] \\
& \Rightarrow\left[\begin{array}{c}
x \\
y \\
z
\end{array}\right]=\left[\begin{array}{c}
24-42+16 \\
-12+24-9 \\
-8+15-6
\end{array}\right]=\left[\begin{array}{r}
-2 \\
3 \\
1
\end{array}\right] \\
& \Rightarrow x=-2, y=3 \text { and } z=1 .
\end{aligned}
$$

Hence, $x=-2$, $y=3$ and $z=1$.

---

### Example:

6 Using matrices, solve the following system of equations:

$$
\begin{aligned}
& \frac{2}{x}+\frac{3}{y}+\frac{10}{z}=4 \\
& \frac{4}{x}-\frac{6}{y}+\frac{5}{z}=1 \\
& \frac{6}{x}+\frac{9}{y}-\frac{20}{z}=2 .(x, y, z \neq 0)
\end{aligned}
$$

_[CBSE 2011]_

#### Solution:

Putting $\frac{1}{x}=u$, $\frac{1}{y}=v$ and $\frac{1}{z}=w$, the given equations become:

$$
\begin{align*}
& 2 u+3 v+10 w=4 \tag{i}\\
& 4 u-6 v+5 w=1 \tag{ii}\\
& 6 u+9 v-20 w=2 \tag{iii}
\end{align*}
$$

Let $A=\left[\begin{array}{rrr}2 & 3 & 10 \\ 4 & -6 & 5 \\ 6 & 9 & -20\end{array}\right]$, $Y=\left[\begin{array}{c}u \\ v \\ w\end{array}\right]$ and $B=\left[\begin{array}{l}4 \\ 1 \\ 2\end{array}\right]$.
Then, the given system in matrix form is $AY=B$.

$$
\text { Now, } \begin{aligned}
|A| & =\left|\begin{array}{rrr}
2 & 3 & 10 \\
4 & -6 & 5 \\
6 & 9 & -20
\end{array}\right| \\
& =\left|\begin{array}{rrr}
2 & 3 & 10 \\
0 & -12 & -15 \\
0 & 0 & -50
\end{array}\right| \quad\left[R_{2} \rightarrow R_{2}-2 R_{1} ; R_{3} \rightarrow R_{3}-3 R_{1}\right] \\
& =(-50) \cdot(-24-0)=1200 \neq 0 .
\end{aligned}
$$

Thus, $A$ is invertible.
So, the given system has a unique solution, $Y=A^{-1} B$.
The minors of the elements of $|A|$ are

$$
\begin{aligned}
& M_{11}=75, M_{12}=-110, M_{13}=72 ; \\
& M_{21}=-150, M_{22}=-100, M_{23}=0 ; \\
& M_{31}=75, M_{32}=-30, M_{33}=-24 .
\end{aligned}
$$

So, the cofactors of the elements of $|A|$ are

$$
\begin{aligned}
& A_{11}=75, A_{12}=110, A_{13}=72 ; \\
& A_{21}=150, A_{22}=-100, A_{23}=0 ; \\
& A_{31}=75, A_{32}=30, A_{33}=-24 . \\
\therefore & (\operatorname{adj} A)=\left[\begin{array}{rrr}
75 & 110 & 72 \\
150 & -100 & 0 \\
75 & 30 & -24
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
75 & 150 & 75 \\
110 & -100 & 30 \\
72 & 0 & -24
\end{array}\right] .
\end{aligned}
$$

$$
\begin{aligned}
& \therefore \quad A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)=\frac{1}{1200} \cdot\left[\begin{array}{rrr}
75 & 150 & 75 \\
110 & -100 & 30 \\
72 & 0 & -24
\end{array}\right] . \\
& \begin{aligned}
& \therefore Y=A^{-1} B \\
& \Rightarrow \quad\left[\begin{array}{c}
u \\
v \\
w
\end{array}\right]=\frac{1}{1200} \cdot\left[\begin{array}{rrr}
75 & 150 & 75 \\
110 & -100 & 30 \\
72 & 0 & -24
\end{array}\right]\left[\begin{array}{l}
4 \\
1 \\
2
\end{array}\right] \\
&=\frac{1}{1200} \cdot\left[\begin{array}{c}
300+150+150 \\
440-100+60 \\
288+0-48
\end{array}\right]=\frac{1}{1200} \cdot\left[\begin{array}{l}
600 \\
400 \\
240
\end{array}\right] \\
&=\left[\begin{array}{c}
\frac{600}{1200} \\
\frac{400}{1200} \\
\frac{240}{1200}
\end{array}\right]=\left[\begin{array}{c}
\frac{1}{2} \\
\frac{1}{3} \\
\frac{1}{5}
\end{array}\right] \\
& \Rightarrow \quad u=\frac{1}{2}, v=\frac{1}{3}, w=\frac{1}{5} \\
& \Rightarrow \quad \frac{1}{x}=\frac{1}{2}, \frac{1}{y}=\frac{1}{3} \text { and } \frac{1}{z}=\frac{1}{5} \\
& \Rightarrow \quad x=2, y=3 \text { and } z=5
\end{aligned}
\end{aligned}
$$

Hence $x=2$, $y=3$ and $z=5$.

---

### Example:

7 Use the product $\left[\begin{array}{rrr}1 & -1 & 2 \\ 0 & 2 & -3 \\ 3 & -2 & 4\end{array}\right]\left[\begin{array}{rrr}-2 & 0 & 1 \\ 9 & 2 & -3 \\ 6 & 1 & -2\end{array}\right]$ to solve the following system of equations:

$$
\begin{array}{r}
x-y+2 z=1 \\
2 y-3 z=1 \\
3 x-2 y+4 z=2
\end{array}
$$

#### Solution:

The given equations are

$$
\begin{array}{r}
x-y+2 z=1 \\
2 y-3 z=1 \\
3 x-2 y+4 z=2 \tag{iii}
\end{array}
$$

Let $A=\left[\begin{array}{rrr}1 & -1 & 2 \\ 0 & 2 & -3 \\ 3 & -2 & 4\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $B=\left[\begin{array}{l}1 \\ 1 \\ 2\end{array}\right]$.
Then, the given system in matrix form is $A X=B$.

$$
\begin{aligned}
& \text { Now, }\left[\begin{array}{rrr}
1 & -1 & 2 \\
0 & 2 & -3 \\
3 & -2 & 4
\end{array}\right]\left[\begin{array}{rrr}
-2 & 0 & 1 \\
9 & 2 & -3 \\
6 & 1 & -2
\end{array}\right] \\
& \quad=\left[\begin{array}{rrr}
-2-9+12 & 0-2+2 & 1+3-4 \\
0+18-18 & 0+4-3 & 0-6+6 \\
-6-18+24 & 0-4+4 & 3+6-8
\end{array}\right]=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right] \\
& \Rightarrow A \cdot\left[\begin{array}{rrr}
-2 & 0 & 1 \\
9 & 2 & -3 \\
6 & 1 & -2
\end{array}\right]=I \\
& \Rightarrow A^{-1}=\left[\begin{array}{rrr}
-2 & 0 & 1 \\
9 & 2 & -3 \\
6 & 1 & -2
\end{array}\right]
\end{aligned}
$$

Now, $A X=B$
$\Rightarrow \quad X=A^{-1} B$

$$
\begin{aligned}
\Rightarrow\left[\begin{array}{l}
x \\
y \\
z
\end{array}\right] & =\left[\begin{array}{rrr}
-2 & 0 & 1 \\
9 & 2 & -3 \\
6 & 1 & -2
\end{array}\right]\left[\begin{array}{l}
1 \\
1 \\
2
\end{array}\right] \\
& =\left[\begin{array}{r}
-2+0+2 \\
9+2-6 \\
6+1-4
\end{array}\right]=\left[\begin{array}{l}
0 \\
5 \\
3
\end{array}\right]
\end{aligned}
$$

$\Rightarrow \quad x=0, y=5$ and $z=3$.

Hence, $x=0$, $y=5$ and $z=3$.

---

### Example:

8 Given $A=\left[\begin{array}{rrr}1 & -1 & 1 \\ 1 & -2 & -2 \\ 2 & 1 & 3\end{array}\right]$ and $B=\left[\begin{array}{rrr}-4 & 4 & 4 \\ -7 & 1 & 3 \\ 5 & -3 & -1\end{array}\right]$, find $AB$ and use this result in solving the following system of equations:

$$
\begin{gathered}
x-y+z=4 \\
x-2 y-2 z=9 \\
2 x+y+3 z=1
\end{gathered}
$$

_[CBSE 2006C, '10C, '12C]_

#### Solution:

The given equations are

$$
\begin{array}{r}
x-y+z=4 \\
x-2 y-2 z=9 \\
2 x+y+3 z=1 \tag{iii}
\end{array}
$$

Let $A=\left[\begin{array}{rrr}1 & -1 & 1 \\ 1 & -2 & -2 \\ 2 & 1 & 3\end{array}\right]$, $X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $C=\left[\begin{array}{l}4 \\ 9 \\ 1\end{array}\right]$.
Then, the given system of equations is $A X=C$.

$$
\begin{aligned}
\text { Now, } A B= & {\left[\begin{array}{rrr}
1 & -1 & 1 \\
1 & -2 & -2 \\
2 & 1 & 3
\end{array}\right]\left[\begin{array}{rrr}
-4 & 4 & 4 \\
-7 & 1 & 3 \\
5 & -3 & -1
\end{array}\right] } \\
& =\left[\begin{array}{lll}
-4+7+5 & 4-1-3 & 4-3-1 \\
-4+14-10 & 4-2+6 & 4-6+2 \\
-8-7+15 & 8+1-9 & 8+3-3
\end{array}\right]=\left[\begin{array}{lll}
8 & 0 & 0 \\
0 & 8 & 0 \\
0 & 0 & 8
\end{array}\right] \\
& =8 I \\
\Rightarrow A \cdot\left(\frac{1}{8} B\right)=I & \Rightarrow A^{-1}=\frac{1}{8} B=\frac{1}{8} \cdot\left[\begin{array}{rrr}
-4 & 4 & 4 \\
-7 & 1 & 3 \\
5 & -3 & -1
\end{array}\right]
\end{aligned}
$$

Now, $A X=C$
$\Rightarrow \quad X=A^{-1} C$

$$
\begin{aligned}
& \Rightarrow \quad\left[\begin{array}{l}
x \\
y \\
z
\end{array}\right]=\frac{1}{8} \cdot\left[\begin{array}{rrr}
-4 & 4 & 4 \\
-7 & 1 & 3 \\
5 & -3 & -1
\end{array}\right]\left[\begin{array}{l}
4 \\
9 \\
1
\end{array}\right] \\
& \quad=\frac{1}{8} \cdot\left[\begin{array}{r}
-16+36+4 \\
-28+9+3 \\
20-27-1
\end{array}\right]=\frac{1}{8} \cdot\left[\begin{array}{r}
24 \\
-16 \\
-8
\end{array}\right]=\left[\begin{array}{r}
3 \\
-2 \\
-1
\end{array}\right] \\
& \Rightarrow \quad x=3, y=-2 \text { and } z=-1 .
\end{aligned}
$$

Hence, $x=3$, $y=-2$ and $z=-1$.

---

### Example 9

The sum of three numbers is 6. Twice the third number when added to the first number gives 7. On adding the sum of the second and third numbers to thrice the first number, we get 12. Find the numbers, using method.

#### Solution:

Let the first, second and third numbers be $x, y, z$ respectively. Then,

$$
\begin{array}{r}
x+y+z=6 \\
x+2 z=7 \\
3 x+y+z=12 \tag{iii}
\end{array}
$$

Let $A=\left[\begin{array}{lll}1 & 1 & 1 \\ 1 & 0 & 2 \\ 3 & 1 & 1\end{array}\right], X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $B=\left[\begin{array}{c}6 \\ 7 \\ 12\end{array}\right]$.
Then, the given system in matrix form is $A X=B$.

Now, $|A|=\left|\begin{array}{rrr}1 & 1 & 1 \\ 1 & 0 & 2 \\ 3 & 1 & 1\end{array}\right|=\left|\begin{array}{rrr}1 & 1 & 1 \\ 0 & -1 & 1 \\ 0 & -2 & -2\end{array}\right| \quad\left[\begin{array}{l}R_{2} \rightarrow R_{2}-R_{1} ; \\ R_{3} \rightarrow R_{3}-3 R_{1}\end{array}\right]$

$$
=1 \cdot(2+2)=4 \neq 0 .
$$

$\therefore A$ is **invertible**.
So, the given system has a **unique solution**, $X=A^{-1} B$.

The **minors** of the elements of $|A|$ are
$$
\begin{aligned}
& M_{11}=-2, \quad M_{12}=-5, \quad M_{13}=1 \\
& M_{21}=0, \quad M_{22}=-2, \quad M_{23}=-2 \\
& M_{31}=2, \quad M_{32}=1, \quad M_{33}=-1
\end{aligned}
$$

The **cofactors** of the elements of $|A|$ are
$$
\begin{aligned}
& A_{11}=-2, A_{12}=5, A_{13}=1 ; \\
& A_{21}=0, A_{22}=-2, A_{23}=2 ; \\
& A_{31}=2, A_{32}=-1, A_{33}=-1 . \\
\end{aligned}
$$

$\therefore (\operatorname{adj} A)=\left[\begin{array}{rrr}
-2 & 5 & 1 \\
0 & -2 & 2 \\
2 & -1 & -1
\end{array}\right]^{\prime}=\left[\begin{array}{rrr}
-2 & 0 & 2 \\
5 & -2 & -1 \\
1 & 2 & -1
\end{array}\right]$

$$
\Rightarrow A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)=\frac{1}{4} \cdot\left[\begin{array}{rrr}
-2 & 0 & 2 \\
5 & -2 & -1 \\
1 & 2 & -1
\end{array}\right]
$$

$$
\Rightarrow X=A^{-1} B
$$

$$
\Rightarrow \left[\begin{array}{l}
x \\
y \\
z
\end{array}\right]=\frac{1}{4} \cdot\left[\begin{array}{rrr}
-2 & 0 & 2 \\
5 & -2 & -1 \\
1 & 2 & -1
\end{array}\right]\left[\begin{array}{r}
6 \\
7 \\
12
\end{array}\right]
$$

$$
=\frac{1}{4} \cdot\left[\begin{array}{r}
-12+0+24 \\
30-14-12 \\
6+14-12
\end{array}\right]=\frac{1}{4} \cdot\left[\begin{array}{r}
12 \\
4 \\
8
\end{array}\right]=\left[\begin{array}{l}
3 \\
1 \\
2
\end{array}\right]
$$

$$
\Rightarrow x=3, y=1, z=2 .
$$

Hence, the required numbers are **3, 1, 2**.

---

### Example 10

A school wants to award its students for the value of Honesty, Regularity and Hardwork with a total cash award of $₹ 6000$. Three times the award money for Hardwork added to that given for Honesty amounts to $₹ 11000$. The award money given for Honesty and Hardwork together is double the one given for Regularity. Represent the above situation algebraically and find the award money for each value, using matrix method. Apart from the given three values, suggest one more value which the school must include for awards.
[CBSE 2013]

#### Solution:

Let the amount of award for Honesty, Regularity and Hardwork be $₹ x$, $₹ y$ and $₹ z$ respectively. Then,

$$
\begin{gather*}
x+y+z=6000 \tag{i}\\
x+0 y+3 z=11000 \tag{ii}
\end{gather*}
$$

and

$$
\begin{equation*}
x+z=2 y \Rightarrow x-2 y+z=0 . \tag{iii}
\end{equation*}
$$

Let $A=\left[\begin{array}{rrr}1 & 1 & 1 \\ 1 & 0 & 3 \\ 1 & -2 & 1\end{array}\right], X=\left[\begin{array}{l}x \\ y \\ z\end{array}\right]$ and $B=\left[\begin{array}{c}6000 \\ 11000 \\ 0\end{array}\right]$.

Then, the matrix equation is $A X=B$.
$\therefore \quad X=A^{-1} B$.

Now, $|A|=\left|\begin{array}{rrr}1 & 1 & 1 \\ 1 & 0 & 3 \\ 1 & -2 & 1\end{array}\right|=\left|\begin{array}{rrr}1 & 0 & 0 \\ 1 & -1 & 2 \\ 1 & -3 & 0\end{array}\right| \quad \left\{C_{2} \rightarrow\left(C_{2}-C_{1}\right) \text { and } C_{3} \rightarrow\left(C_{3}-C_{1}\right)\right\}$

$$
=1 \cdot\left|\begin{array}{ll}
-1 & 2 \\
-3 & 0
\end{array}\right|=(0+6)=6 \neq 0 .
$$

$\therefore A^{-1}$ **exists**.
Now, the **cofactors** of the elements of $|A|$ are given by

$$
\begin{aligned}
& C_{11}=\left|\begin{array}{rr}
0 & 3 \\
-2 & 1
\end{array}\right|=6, C_{12}=-\left|\begin{array}{ll}
1 & 3 \\
1 & 1
\end{array}\right|=2, C_{13}=\left|\begin{array}{rr}
1 & 0 \\
1 & -2
\end{array}\right|=-2 ; \\
& C_{21}=-\left|\begin{array}{rr}
1 & 1 \\
-2 & 1
\end{array}\right|=-3, C_{22}=\left|\begin{array}{ll}
1 & 1 \\
1 & 1
\end{array}\right|=0, C_{23}=-\left|\begin{array}{rr}
1 & 1 \\
1 & -2
\end{array}\right|=3 ; \\
& C_{31}=\left|\begin{array}{ll}
1 & 1 \\
0 & 3
\end{array}\right|=3, C_{32}=-\left|\begin{array}{ll}
1 & 1 \\
1 & 3
\end{array}\right|=-2, C_{33}=\left|\begin{array}{ll}
1 & 1 \\
1 & 0
\end{array}\right|=-1 . \\
\end{aligned}
$$

$\therefore (\operatorname{adj} A)=\left[\begin{array}{rrr}
6 & 2 & -2 \\
-3 & 0 & 3 \\
3 & -2 & -1
\end{array}\right]^{t}=\left[\begin{array}{rrr}
6 & -3 & 3 \\
2 & 0 & -2 \\
-2 & 3 & -1
\end{array}\right]$

$$
\Rightarrow A^{-1}=\frac{1}{|A|} \cdot(\operatorname{adj} A)=\frac{1}{6} \cdot\left[\begin{array}{rrr}
6 & -3 & 3 \\
2 & 0 & -2 \\
-2 & 3 & -1
\end{array}\right]
$$

$$
\Rightarrow X=A^{-1} B=\frac{1}{6} \cdot\left[\begin{array}{rrr}
6 & -3 & 3 \\
2 & 0 & -2 \\
-2 & 3 & -1
\end{array}\right]\left[\begin{array}{c}
6000 \\
11000 \\
0
\end{array}\right]
$$

$$
\begin{aligned}
& \Rightarrow X=\frac{1}{6} \cdot\left[\begin{array}{c}
36000-33000+0 \\
12000+0 \\
-12000+33000-0
\end{array}\right]=\frac{1}{6}\left[\begin{array}{c}
3000 \\
12000 \\
21000
\end{array}\right] \\
& \Rightarrow\left[\begin{array}{l}
x \\
y \\
z
\end{array}\right]=\left[\begin{array}{c}
500 \\
2000 \\
3500
\end{array}\right] \\
& \Rightarrow x=500, y=2000 \text { and } z=3500 .
\end{aligned}
$$

Hence, the award money for **Honesty**, **Regularity** and **Hardwork** is **$₹ 500$**, **$₹ 2000$** and **$₹ 3500$** respectively.

Apart from honesty, regularity and hardwork, the school must include an award for a student to be well-behaved.

---
