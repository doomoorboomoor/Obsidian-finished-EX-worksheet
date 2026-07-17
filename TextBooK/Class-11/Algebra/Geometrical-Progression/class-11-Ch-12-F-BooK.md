## Geometric Mean

Let $a$ and $b$ be two given numbers. We say that $G$ is the **geometric mean (GM)** between $a$ and $b$ if $a, G, b$ are in a Geometric Progression (GP).

$G$ is the GM between $a$ and $b \Leftrightarrow a, G, b$ are in GP.

$$
\begin{aligned}
& \Leftrightarrow \frac{G}{a}=\frac{b}{G} \\
& \Leftrightarrow G^{2}=a b \Leftrightarrow G=\sqrt{a b}
\end{aligned}
$$

So, the GM between $a$ and $b$ is $\sqrt{ab}$.

#### Remarks
1.  The GM between two positive numbers is positive.
2.  The GM between two negative numbers is negative.
3.  The GM between two numbers of opposite signs does not exist.

---
## Solved Examples

### Example 1
Find the geometric mean between:
1.  6 and 24
2.  -9 and -25
3.  -6 and 9

#### Solution
1.  The GM between 6 and 24 is $\sqrt{6 \times 24} = \sqrt{144} = 12$.
2.  The GM between -9 and -25 is $-\sqrt{(-9) \times(-25)} = -\sqrt{225} = -15$.
3.  Since the GM between two numbers of opposite signs does not exist, the GM between -6 and 9 does not exist.

---
### Example 2
Find two positive numbers $a$ and $b$ whose AM and GM are 34 and 16 respectively.

#### Solution
We have:
$$
\frac{a+b}{2}=34 \quad \text{and} \quad \sqrt{a b}=16
$$
$$
\Rightarrow a+b=68 \quad \text{and} \quad a b=256
$$
Now, we find $(a-b)$:
$$
\begin{aligned}
(a-b) &= \sqrt{(a+b)^{2}-4 a b} \\
&= \sqrt{(68)^{2}-4 \times 256} \\
&= \sqrt{4624 - 1024} \\
&= \sqrt{3600} = \pm 60
\end{aligned}
$$
So we have two systems of equations:
-   Case 1: $a+b=68$ and $a-b=60$. Solving this gives $2a=128 \Rightarrow a=64$, and $b=4$.
-   Case 2: $a+b=68$ and $a-b=-60$. Solving this gives $2a=8 \Rightarrow a=4$, and $b=64$.

Hence, the required numbers are **(a=64, b=4)** or **(a=4, b=64)**.

---
### Example 3
Find the value of $n$ so that $\frac{a^{(n+1)}+b^{(n+1)}}{a^{n}+b^{n}}$ may be the geometric mean between $a$ and $b$, where $a \neq b$.

#### Solution
Given that $\frac{a^{(n+1)}+b^{(n+1)}}{a^{n}+b^{n}}$ is the GM between $a$ and $b$:
$$
\begin{aligned}
\frac{a^{(n+1)}+b^{(n+1)}}{a^{n}+b^{n}} &= \sqrt{ab} = a^{\frac{1}{2}} b^{\frac{1}{2}} \\
\Rightarrow a^{(n+1)}+b^{(n+1)} &= \left(a^{n}+b^{n}\right) \left(a^{\frac{1}{2}} b^{\frac{1}{2}}\right) \\
\Rightarrow a^{(n+1)}+b^{(n+1)} &= a^{\left(n+\frac{1}{2}\right)} b^{\frac{1}{2}}+a^{\frac{1}{2}} b^{\left(n+\frac{1}{2}\right)} \\
\Rightarrow a^{(n+1)}-a^{\left(n+\frac{1}{2}\right)} b^{\frac{1}{2}} &= a^{\frac{1}{2}} b^{\left(n+\frac{1}{2}\right)}-b^{(n+1)} \\
\Rightarrow a^{\left(n+\frac{1}{2}\right)}\left(a^{\frac{1}{2}}-b^{\frac{1}{2}}\right) &= b^{\left(n+\frac{1}{2}\right)}\left(a^{\frac{1}{2}}-b^{\frac{1}{2}}\right)
\end{aligned}
$$
Since $a \neq b$, we have $\left(a^{\frac{1}{2}}-b^{\frac{1}{2}}\right) \neq 0$. We can divide both sides by this term:
$$
\begin{aligned}
a^{\left(n+\frac{1}{2}\right)} &= b^{\left(n+\frac{1}{2}\right)} \\
\Rightarrow \left(\frac{a}{b}\right)^{\left(n+\frac{1}{2}\right)} &= 1 = \left(\frac{a}{b}\right)^{0} \\
\Rightarrow n+\frac{1}{2} &= 0 \\
\Rightarrow n &= -\frac{1}{2}
\end{aligned}
$$
Hence, **$n = -\frac{1}{2}$**.

---
### Example 4
If $A$ and $G$ are respectively the arithmetic and geometric means between two distinct positive numbers $a$ and $b$, then prove that $A>G$.

#### Solution
We have the definitions for the Arithmetic Mean (AM) and Geometric Mean (GM):
$$
A = \frac{a+b}{2} \quad \text{and} \quad G = \sqrt{a b}
$$
Consider the difference $A-G$:
$$
\begin{aligned}
A-G &= \frac{a+b}{2}-\sqrt{a b} \\
&= \frac{a+b-2 \sqrt{a b}}{2} \\
&= \frac{1}{2}(\sqrt{a}-\sqrt{b})^{2}
\end{aligned}
$$
Since $a$ and $b$ are distinct positive numbers, $\sqrt{a} \neq \sqrt{b}$, which means $(\sqrt{a}-\sqrt{b}) \neq 0$. The square of any non-zero real number is positive, so $(\sqrt{a}-\sqrt{b})^{2} > 0$.
Therefore, $A-G > 0$, which implies **$A > G$**.

---
### Example 5
If $A$ and $G$ are respectively the arithmetic and geometric means between two positive numbers $a$ and $b$, then prove that the quadratic equation having $a, b$ as its roots is given by $x^{2}-2 A x+G^{2}=0$.

#### Solution
We have:
$$
A=\frac{a+b}{2} \quad \text{and} \quad G=\sqrt{a b}
$$
The quadratic equation with roots $a$ and $b$ is given by the formula $x^2 - (\text{sum of roots})x + (\text{product of roots}) = 0$.
$$
x^{2}-(a+b) x+a b=0
$$
From the definitions of A and G, we can write $a+b = 2A$ and $ab = G^2$. Substituting these into the equation:
$$
x^{2}-2 A x+G^{2}=0
$$
This is the required quadratic equation.

---
### Example 6
If $A$ and $G$ be the AM and GM between two positive numbers, then prove that the numbers are $A \pm \sqrt{A^{2}-G^{2}}$.

#### Solution
Let the numbers be $a$ and $b$. Then:
$$
A=\frac{a+b}{2} \quad \text{and} \quad G=\sqrt{a b}
$$
From the previous example, the quadratic equation with roots $a$ and $b$ is:
$$
x^{2}-2 A x+G^{2}=0
$$
Using the quadratic formula to solve for $x$ (which represents the roots $a$ and $b$):
$$
\begin{aligned}
x &= \frac{-(-2A) \pm \sqrt{(-2A)^{2}-4(1)(G^{2})}}{2(1)} \\
&= \frac{2 A \pm \sqrt{4 A^{2}-4 G^{2}}}{2} \\
&= \frac{2 A \pm 2\sqrt{A^{2}-G^{2}}}{2} \\
&= A \pm \sqrt{A^{2}-G^{2}}
\end{aligned}
$$
Hence, the required numbers are **$A \pm \sqrt{A^{2}-G^{2}}$**.

---
### Example 7
If $x, y, z$ are distinct positive numbers, then prove that $(x+y)(y+z)(z+x)>8 x y z$.

#### Solution
Using the AM-GM inequality ($AM > GM$ for distinct positive numbers), we can write three inequalities:
$$
\frac{x+y}{2}>\sqrt{x y} \Rightarrow x+y>2 \sqrt{x y}
$$
$$
\frac{y+z}{2}>\sqrt{y z} \Rightarrow y+z>2 \sqrt{y z}
$$
$$
\frac{z+x}{2}>\sqrt{z x} \Rightarrow z+x>2 \sqrt{z x}
$$
Multiplying these three inequalities together:
$$
\begin{aligned}
(x+y)(y+z)(z+x) &> (2 \sqrt{x y})(2 \sqrt{y z})(2 \sqrt{z x}) \\
&> 8 \sqrt{x^2 y^2 z^2} \\
&> 8xyz
\end{aligned}
$$
Hence, **$(x+y)(y+z)(z+x)>8 x y z$**.

---
### Example 8
If $a, b, c, d$ are four distinct positive numbers in GP, then prove that $a+d>b+c$.

#### Solution
Since $a, b, c, d$ are in GP:
1.  The terms $a, b, c$ are in GP. This means $b$ is the GM between $a$ and $c$. The AM between $a$ and $c$ is $\frac{a+c}{2}$. By the AM-GM inequality:
$$
\frac{a+c}{2}>b \Rightarrow a+c>2 b \quad \cdots (i)
$$
2.  The terms $b, c, d$ are in GP. This means $c$ is the GM between $b$ and $d$. The AM between $b$ and $d$ is $\frac{b+d}{2}$. By the AM-GM inequality:
$$
\frac{b+d}{2}>c \Rightarrow b+d>2 c \quad \cdots (ii)
$$
Adding inequalities (i) and (ii):
$$
(a+c) + (b+d) > 2b + 2c
$$
$$
a+b+c+d > 2b+2c
$$
Subtracting $b+c$ from both sides:
$$
a+d > b+c
$$

---
### Example 9
The sum of two numbers is 6 times their geometric mean. Show that the numbers are in the ratio $(3+2 \sqrt{2}):(3-2 \sqrt{2})$.

#### Solution
Let the numbers be $a$ and $b$. According to the problem statement:
$$
a+b=6 \sqrt{a b}
$$
$$
\Rightarrow \frac{a+b}{2 \sqrt{a b}}=\frac{3}{1}
$$
Applying componendo and dividendo:
$$
\begin{aligned}
\frac{(a+b)+2 \sqrt{a b}}{(a+b)-2 \sqrt{a b}} &= \frac{3+1}{3-1} = \frac{4}{2} = \frac{2}{1} \\
\Rightarrow \frac{(\sqrt{a}+\sqrt{b})^{2}}{(\sqrt{a}-\sqrt{b})^{2}} &= \frac{2}{1}
\end{aligned}
$$
Taking the square root of both sides:
$$
\frac{\sqrt{a}+\sqrt{b}}{\sqrt{a}-\sqrt{b}}=\frac{\sqrt{2}}{1}
$$
Applying componendo and dividendo again:
$$
\begin{aligned}
\frac{(\sqrt{a}+\sqrt{b})+(\sqrt{a}-\sqrt{b})}{(\sqrt{a}+\sqrt{b})-(\sqrt{a}-\sqrt{b})} &= \frac{\sqrt{2}+1}{\sqrt{2}-1} \\
\Rightarrow \frac{2\sqrt{a}}{2\sqrt{b}} &= \frac{\sqrt{2}+1}{\sqrt{2}-1} \\
\Rightarrow \frac{\sqrt{a}}{\sqrt{b}} &= \frac{\sqrt{2}+1}{\sqrt{2}-1}
\end{aligned}
$$
Squaring both sides to find the ratio $\frac{a}{b}$:
$$
\begin{aligned}
\frac{a}{b} &= \left(\frac{\sqrt{2}+1}{\sqrt{2}-1}\right)^{2} = \frac{(\sqrt{2}+1)^{2}}{(\sqrt{2}-1)^{2}} \\
&= \frac{2+1+2\sqrt{2}}{2+1-2\sqrt{2}} = \frac{3+2 \sqrt{2}}{3-2 \sqrt{2}}
\end{aligned}
$$
Hence, the ratio **$a: b=(3+2 \sqrt{2}):(3-2 \sqrt{2})$**.

---
### Example 10
If the AM and GM of the roots of a quadratic equation are 8 and 5 respectively, then obtain the equation.

#### Solution
Let the roots of the quadratic equation be $a$ and $b$.
Given:
-   AM = $\frac{a+b}{2} = 8 \Rightarrow a+b = 16$ (Sum of roots)
-   GM = $\sqrt{a b} = 5 \Rightarrow ab = 25$ (Product of roots)

The quadratic equation is given by $x^2 - (\text{sum of roots})x + (\text{product of roots}) = 0$.
Substituting the values:
$$
x^{2}-16 x+25=0
$$
This is the required equation.

---
### Example 11
If the AM and GM of two positive numbers $a$ and $b$ are in the ratio $m: n$, show that $a: b=\left(m+\sqrt{m^{2}-n^{2}}\right):\left(m-\sqrt{m^{2}-n^{2}}\right)$.

#### Solution
Let $A$ and $G$ be the AM and GM of $a$ and $b$.
$$
A=\frac{a+b}{2} \quad \text{and} \quad G=\sqrt{a b}
$$
We are given $\frac{A}{G} = \frac{m}{n}$. Let $A = km$ and $G=kn$ for some constant $k$.

From Example 6, the numbers $a$ and $b$ are given by $A \pm \sqrt{A^{2}-G^{2}}$.
So, we can set $a = A+\sqrt{A^{2}-G^{2}}$ and $b = A-\sqrt{A^{2}-G^{2}}$.
The ratio $\frac{a}{b}$ is:
$$
\begin{aligned}
\frac{a}{b} &= \frac{A+\sqrt{A^{2}-G^{2}}}{A-\sqrt{A^{2}-G^{2}}} \\
&= \frac{km+\sqrt{(km)^{2}-(kn)^{2}}}{km-\sqrt{(km)^{2}-(kn)^{2}}} \\
&= \frac{km+\sqrt{k^{2}m^{2}-k^{2}n^{2}}}{km-\sqrt{k^{2}m^{2}-k^{2}n^{2}}} \\
&= \frac{km+k\sqrt{m^{2}-n^{2}}}{km-k\sqrt{m^{2}-n^{2}}} \\
&= \frac{k(m+\sqrt{m^{2}-n^{2}})}{k(m-\sqrt{m^{2}-n^{2}})} \\
&= \frac{m+\sqrt{m^{2}-n^{2}}}{m-\sqrt{m^{2}-n^{2}}}
\end{aligned}
$$
Hence, **$a: b=\left(m+\sqrt{m^{2}-n^{2}}\right):\left(m-\sqrt{m^{2}-n^{2}}\right)$**.

---
### Example 12
Find two positive numbers whose difference is 12 and whose AM exceeds the GM by 2.

#### Solution
Let the positive numbers be $a$ and $b$, with $a>b$.
Given:
1.  $a-b=12 \quad \cdots (i)$
2.  $AM - GM = 2 \Rightarrow \frac{a+b}{2}-\sqrt{a b}=2$

From the second condition:
$$
a+b-2 \sqrt{a b}=4
$$
$$
(\sqrt{a}-\sqrt{b})^{2}=4
$$
Since $a>b$, $\sqrt{a}>\sqrt{b}$, so we take the positive root:
$$
\sqrt{a}-\sqrt{b}=2 \quad \cdots (ii)
$$
Now, consider the first condition $a-b=12$:
$$
(\sqrt{a}-\sqrt{b})(\sqrt{a}+\sqrt{b})=12
$$
Substitute the result from (ii):
$$
2(\sqrt{a}+\sqrt{b})=12
$$
$$
\sqrt{a}+\sqrt{b}=6 \quad \cdots (iii)
$$
Now we solve the system of linear equations for $\sqrt{a}$ and $\sqrt{b}$:
-   Add (ii) and (iii): $2\sqrt{a} = 8 \Rightarrow \sqrt{a}=4 \Rightarrow a=16$.
-   Substitute $\sqrt{a}=4$ into (iii): $4+\sqrt{b}=6 \Rightarrow \sqrt{b}=2 \Rightarrow b=4$.

The required numbers are **16 and 4**.

---
### Example 13
If $x \in R$, find the minimum value of $3^{x}+3^{(1-x)}$.

#### Solution
We know that for positive numbers, $AM \ge GM$. Let the two positive numbers be $3^x$ and $3^{(1-x)}$.
$$
\frac{3^{x}+3^{(1-x)}}{2} \ge \sqrt{3^{x} \times 3^{(1-x)}}
$$
$$
\frac{3^{x}+3^{(1-x)}}{2} \ge \sqrt{3^{x+1-x}}
$$
$$
\frac{3^{x}+3^{(1-x)}}{2} \ge \sqrt{3^{1}}
$$
$$
3^{x}+3^{(1-x)} \ge 2 \sqrt{3}
$$
The minimum value is achieved when the numbers are equal, i.e., $3^x = 3^{1-x} \Rightarrow x=1-x \Rightarrow 2x=1 \Rightarrow x=1/2$.
Hence, the minimum value of $3^{x}+3^{(1-x)}$ is **$2 \sqrt{3}$**.

---
## n Geometric Means Between Two Given Numbers

Let $a$ and $b$ be two given numbers. We say that $G_{1}, G_{2}, \ldots, G_{n}$ are **$n$ geometric means** between $a$ and $b$, if the sequence $a, G_{1}, G_{2}, \ldots, G_{n}, b$ is a Geometric Progression (GP).

---
### Example 14
Insert $n$ geometric means between $a$ and $b$.

#### Solution
Let $G_{1}, G_{2}, \ldots, G_{n}$ be the $n$ geometric means between $a$ and $b$.
Then, the sequence $a, G_{1}, G_{2}, \ldots, G_{n}, b$ is a GP.
This GP contains $(n+2)$ terms, with the first term being $a$ and the $(n+2)$-th term being $b$.
Let the common ratio of this GP be $r$. Then:
$$
T_{n+2} = a r^{(n+2-1)} = b
$$
$$
a r^{(n+1)} = b \Rightarrow r = \left(\frac{b}{a}\right)^{\frac{1}{n+1}}
$$
Now we can find the geometric means:
$$
\begin{aligned}
G_{1} &= ar = a \cdot\left(\frac{b}{a}\right)^{\frac{1}{n+1}} \\
G_{2} &= ar^{2} = a \cdot\left(\frac{b}{a}\right)^{\frac{2}{n+1}} \\
G_{3} &= ar^{3} = a \cdot\left(\frac{b}{a}\right)^{\frac{3}{n+1}} \\
& \vdots \\
G_{n} &= ar^{n} = a \cdot\left(\frac{b}{a}\right)^{\frac{n}{n+1}}
\end{aligned}
$$

---
### Example 15
Insert two numbers between 3 and 81 so that the resulting sequence is a GP.

#### Solution
Let the required numbers be $G_1$ and $G_2$. The sequence is $3, G_1, G_2, 81$.
This is a GP with first term $a=3$ and fourth term $T_4 = 81$.
Let the common ratio be $r$.
$$
\begin{aligned}
T_4 = ar^{4-1} &= 81 \\
3 \cdot r^3 &= 81 \\
r^3 &= 27 \\
r &= 3
\end{aligned}
$$
The numbers are:
-   $G_1 = ar = 3 \times 3 = 9$
-   $G_2 = ar^2 = 3 \times 3^2 = 27$

The required numbers are **9 and 27**.

---
### Example 16
Insert three numbers between 1 and 256 so that the resulting sequence is a GP.

#### Solution
Let the numbers be $G_1, G_2, G_3$. The sequence is $1, G_1, G_2, G_3, 256$.
This is a GP with first term $a=1$ and fifth term $T_5 = 256$.
Let the common ratio be $r$.
$$
\begin{aligned}
T_5 = ar^{5-1} &= 256 \\
1 \cdot r^4 &= 256 \\
r^4 &= 4^4 \\
r &= 4
\end{aligned}
$$
The numbers are:
-   $G_1 = ar = 1 \times 4 = 4$
-   $G_2 = ar^2 = 1 \times 4^2 = 16$
-   $G_3 = ar^3 = 1 \times 4^3 = 64$

The required numbers are **4, 16, and 64**.

---
### Example 17
If $G$ is the GM between two given numbers and $A_1, A_2$ are the two AMs between them, prove that $G^{2}=\left(2 A_{1}-A_{2}\right)\left(2 A_{2}-A_{1}\right)$.

#### Solution
Let the two numbers be $a$ and $b$.
Then, $G^2 = ab \quad \cdots (i)$.
Also, the sequence $a, A_1, A_2, b$ is in AP.
The property of an AP states that any term is the average of its neighbors.
$$
A_1 = \frac{a+A_2}{2} \Rightarrow 2A_1 = a+A_2 \Rightarrow a = 2A_1 - A_2
$$
$$
A_2 = \frac{A_1+b}{2} \Rightarrow 2A_2 = A_1+b \Rightarrow b = 2A_2 - A_1
$$
Now, multiply the expressions for $a$ and $b$:
$$
ab = (2A_1 - A_2)(2A_2 - A_1)
$$
Using equation (i), we get:
$$
G^2 = (2A_1 - A_2)(2A_2 - A_1)
$$

---
### Example 18
If $A$ is the arithmetic mean and $G_1, G_2$ are the two geometric means between any two numbers, then prove that $2 A=\frac{G_{1}^{2}}{G_{2}}+\frac{G_{2}^{2}}{G_{1}}$.

#### Solution
Let the two numbers be $a$ and $b$.
The arithmetic mean is $A = \frac{a+b}{2}$, which means $a+b=2A \quad \cdots (i)$.
The sequence $a, G_1, G_2, b$ is in GP. This implies a common ratio between consecutive terms:
$$
\frac{G_1}{a} = \frac{G_2}{G_1} = \frac{b}{G_2}
$$
From these equalities, we can express $a$ and $b$:
-   From $\frac{G_1}{a} = \frac{G_2}{G_1}$, we get $G_1^2 = aG_2 \Rightarrow a = \frac{G_1^2}{G_2}$.
-   From $\frac{G_2}{G_1} = \frac{b}{G_2}$, we get $G_2^2 = bG_1 \Rightarrow b = \frac{G_2^2}{G_1}$.

Now, find the sum $a+b$:
$$
a+b = \frac{G_1^2}{G_2} + \frac{G_2^2}{G_1}
$$
Using equation (i), we substitute $2A$ for $a+b$:
$$
2A = \frac{G_1^2}{G_2} + \frac{G_2^2}{G_1}
$$

---
