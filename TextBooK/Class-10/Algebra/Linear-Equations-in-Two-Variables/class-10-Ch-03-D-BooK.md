# Conditions for Solvability of Linear Equations

## Consistent and Inconsistent Systems of Linear Equations

A system of equations $a_{1} x+b_{1} y+c_{1}=0, a_{2} x+b_{2} y+c_{2}=0$ is said to be **consistent** if it has at least one solution. On the other hand, the above system is said to be **inconsistent** if it has no solution at all.

---

## Conditions for Solvability of Linear Equations

The system of a pair of linear equations:
$$
a_{1} x+b_{1} y+c_{1}=0, \quad a_{2} x+b_{2} y+c_{2}=0
$$
1.  has a **unique solution**, if
    $$
    \frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}}
    $$
    and the solution is
    $$
    x=\left(\frac{b_{1} c_{2}-b_{2} c_{1}}{a_{1} b_{2}-a_{2} b_{1}}\right), \quad y=\left(\frac{c_{1} a_{2}-c_{2} a_{1}}{a_{1} b_{2}-a_{2} b_{1}}\right)
    $$
2.  has an **infinite number of solutions**, if
    $$
    \frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}
    $$
3.  has **no solution** (i.e., is inconsistent), if
    $$
    \frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}
    $$

---

# Solved Examples

### Example 1:

Show that the system of equations
$$
2 x+5 y=17, \quad 5 x+3 y=14
$$
has a unique solution. Find the solution.

#### Solution:

The given system of equations is
$$
2 x+5 y-17=0, \quad 5 x+3 y-14=0
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0, \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=2, b_{1}=5, c_{1}=-17$ and $a_{2}=5, b_{2}=3, c_{2}=-14$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{2}{5}, \frac{b_{1}}{b_{2}}=\frac{5}{3}, \frac{c_{1}}{c_{2}}=\frac{-17}{-14}=\frac{17}{14}$.

Thus, $\frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}}$.

Hence, the given system of equations has a **unique solution**.

By cross multiplication, we have
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Algebra/Linear-Equations-in-Two-Variables/class-10-Ch-03-D-BooK-001.jpg)

$$
\frac{x}{(-70+51)}=\frac{y}{(-85+28)}=\frac{1}{(6-25)}
$$
$$
\Rightarrow \frac{x}{-19}=\frac{y}{-57}=\frac{1}{-19}
$$
$$
\Rightarrow x=\frac{-19}{-19}=1 \quad \text{and} \quad y=\frac{-57}{-19}=3
$$
Hence, **$x=1$** and **$y=3$** is the required solution.

---

### Example 2:

Find the values of $k$ for which the system of equations
$$
x-2 y=3, \quad 3 x+k y=1
$$
has a unique solution.

#### Solution:

The given system of equations is
$$
x-2 y-3=0, \quad 3 x+k y-1=0
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=1, b_{1}=-2, c_{1}=-3$ and $a_{2}=3, b_{2}=k, c_{2}=-1$.

For a **unique solution**, we must have $\frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}}$.
$$
\therefore \quad \frac{1}{3} \neq \frac{-2}{k} \Rightarrow k \neq-6
$$
Hence, the given system of equations will have a unique solution for all real values of $k$, other than **-6**.

---

### Example 3:

Show that the system of equations
$$
4 x+6 y=7, \quad 12 x+18 y=21
$$
has infinitely many solutions.

#### Solution:

The given system of equations is
$$
4 x+6 y-7=0, \quad 12 x+18 y-21=0
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=4, b_{1}=6, c_{1}=-7$ and $a_{2}=12, b_{2}=18, c_{2}=-21$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{4}{12}=\frac{1}{3}, \frac{b_{1}}{b_{2}}=\frac{6}{18}=\frac{1}{3}$ and $\frac{c_{1}}{c_{2}}=\left(\frac{-7}{-21}\right)=\frac{1}{3}$.

Thus, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.

Hence, the given system of equations has **infinitely many solutions**.

---

### Example 4:

Find the value of $k$ for which the following pair of linear equations has infinitely many solutions:
$$
2 x-3 y=7, \quad (k+1) x+(1-2 k) y=(5 k-4)
$$

#### Solution:

The given equations are
$$
\begin{aligned}
& 2 x-3 y-7=0 \\
& (k+1) x+(1-2 k) y+(4-5 k)=0
\end{aligned}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=2, b_{1}=-3, c_{1}=-7$ and $a_{2}=(k+1), b_{2}=(1-2 k), c_{2}=(4-5 k)$.

Let the given system of equations have **infinitely many solutions**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{2}{(k+1)}=\frac{-3}{(1-2 k)}=\frac{-7}{(4-5 k)}
$$
$$
\Rightarrow \frac{2}{(k+1)}=\frac{3}{(2 k-1)}=\frac{7}{(5 k-4)}
$$
$$
\Rightarrow \frac{2}{(k+1)}=\frac{3}{(2 k-1)} \quad \text{and} \quad \frac{3}{(2 k-1)}=\frac{7}{(5 k-4)}
$$
$$
\Rightarrow 4 k-2=3 k+3 \quad \text{and} \quad 15 k-12=14 k-7
$$
$$
\Rightarrow k=5 \quad \text{and} \quad k=5
$$
Hence, **$k=5$**.

---

### Example 5:

Find the value of $k$ for which the given system of equations has infinitely many solutions:
$$
k x+3 y=k-3, \quad 12 x+k y=k
$$

#### Solution:

The given system of equations is
$$
\begin{aligned}
& k x+3 y+(3-k)=0 \\
& 12 x+k y-k=0
\end{aligned}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=k, b_{1}=3, c_{1}=(3-k)$ and $a_{2}=12, b_{2}=k, c_{2}=-k$.

Let the given system of equations have **infinitely many solutions**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{k}{12}=\frac{3}{k}=\frac{(3-k)}{-k}
$$
$$
\Rightarrow \frac{k}{12}=\frac{3}{k}=\frac{k-3}{k}
$$
$$
\Rightarrow \frac{k}{12}=\frac{3}{k} \quad \text{and} \quad \frac{3}{k}=\frac{k-3}{k}
$$
$$
\Rightarrow k^{2}=36 \quad \text{and} \quad k^{2}-6 k=0
$$
$$
\Rightarrow (k=6 \text{ or } k=-6) \quad \text{and} \quad k(k-6)=0
$$
$$
\Rightarrow (k=6 \text{ or } k=-6) \quad \text{and} \quad (k=0 \text{ or } k=6)
$$
$$
\Rightarrow k=6
$$
Hence, the given system of equations has infinitely many solutions when **$k=6$**.

---

### Example 6:

Find the value of $k$ for which the given system of equations has infinitely many solutions:
$$
\begin{aligned}
& x+(k+1) y=5 \\
& (k+1) x+9 y+(1-8 k)=0
\end{aligned}
$$

#### Solution:

The given system of equations is
$$
\begin{align*}
& x+(k+1) y-5=0 \tag{i} \\
& (k+1) x+9 y+(1-8 k)=0 \tag{ii}
\end{align*}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=1, b_{1}=(k+1), c_{1}=-5$ and $a_{2}=(k+1), b_{2}=9, c_{2}=(1-8 k)$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{1}{(k+1)}, \frac{b_{1}}{b_{2}}=\frac{(k+1)}{9}$ and $\frac{c_{1}}{c_{2}}=\frac{-5}{(1-8 k)}=\frac{5}{(8 k-1)}$.

Let the given system of equations have **infinitely many solutions**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{1}{(k+1)}=\frac{(k+1)}{9}=\frac{5}{(8 k-1)}
$$
$$
\Rightarrow \frac{1}{(k+1)}=\frac{(k+1)}{9} \quad \text{and} \quad \frac{(k+1)}{9}=\frac{5}{(8 k-1)}
$$
$$
\Rightarrow (k+1)^{2}=9 \quad \text{and} \quad (k+1)(8 k-1)=45
$$
$$
\Rightarrow (k+1=3 \text{ or } k+1=-3) \quad \text{and} \quad 8 k^{2}+7 k-46=0
$$
$$
\Rightarrow (k=2 \text{ or } k=-4) \quad \text{and} \quad (k-2)(8 k+23)=0
$$
$$
\Rightarrow (k=2 \text{ or } k=-4) \quad \text{and} \quad \left(k=2 \text{ or } k=\frac{-23}{8}\right)
$$
$$
\Rightarrow k=2
$$
Hence, the given system of equations will have infinitely many solutions when **$k=2$**.

---

### Example 7:

Find the values of $a$ and $b$ for which the following pair of linear equations have an infinite number of solutions:
$$
2 x+3 y=7, \quad (a-b) x+(a+b) y=3 a+b-2
$$

#### Solution:

The given equations are
$$
\begin{align*}
& 2 x+3 y-7=0 \tag{i} \\
& (a-b) x+(a+b) y+(2-3 a-b)=0 \tag{ii}
\end{align*}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=2, b_{1}=3, c_{1}=-7$ and $a_{2}=(a-b), b_{2}=(a+b), c_{2}=(2-3 a-b)$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{2}{(a-b)}, \frac{b_{1}}{b_{2}}=\frac{3}{(a+b)}$ and $\frac{c_{1}}{c_{2}}=\frac{-7}{(2-3 a-b)}=\frac{7}{(3 a+b-2)}$.

Let the given system of equations have **infinitely many solutions**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{2}{(a-b)}=\frac{3}{(a+b)}=\frac{7}{(3 a+b-2)}
$$
$$
\Rightarrow \frac{2}{(a-b)}=\frac{3}{(a+b)} \quad \text{and} \quad \frac{3}{(a+b)}=\frac{7}{(3 a+b-2)}
$$
$$
\Rightarrow 2 a+2 b=3 a-3 b \quad \text{and} \quad 9 a+3 b-6=7 a+7 b
$$
$$
\Rightarrow a-5 b=0 \quad \text{and} \quad 2 a-4 b=6
$$
$$
\Rightarrow a-5 b=0 \quad \text{and} \quad a-2 b=3
$$
On solving $a-5 b=0$ and $a-2 b=3$, we get $a=5$ and $b=1$.
Hence, the required values are **$a=5$** and **$b=1$**.

---

### Example 8:

Find the values of $m$ and $n$ for which the following system of linear equations has infinitely many solutions:
$$
\begin{aligned}
& 3 x+4 y=12 \\
& (m+n) x+2(m-n) y=(5 m-1)
\end{aligned}
$$

#### Solution:

The given system of equations is
$$
\begin{aligned}
& 3 x+4 y-12=0 \\
& (m+n) x+2(m-n) y+(1-5 m)=0
\end{aligned}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=3, b_{1}=4, c_{1}=-12$ and $a_{2}=(m+n), b_{2}=2(m-n), c_{2}=(1-5 m)$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{3}{(m+n)}, \frac{b_{1}}{b_{2}}=\frac{4}{2(m-n)}=\frac{2}{(m-n)}$ and $\frac{c_{1}}{c_{2}}=\frac{-12}{(1-5m)}=\frac{12}{(5 m-1)}$.

Let the given system of equations have **infinitely many solutions**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{3}{(m+n)}=\frac{2}{(m-n)}=\frac{12}{(5 m-1)}
$$
$$
\Rightarrow \frac{3}{(m+n)}=\frac{2}{(m-n)} \quad \text{and} \quad \frac{2}{(m-n)}=\frac{12}{(5 m-1)}
$$
$$
\Rightarrow 3 m-3 n=2 m+2 n \quad \text{and} \quad 10 m-2=12 m-12 n
$$
$$
\Rightarrow m-5 n=0 \quad \text{(i) and} \quad -2m+12n-2 = 0 \Rightarrow m-6n+1=0 \quad \text{(ii)}
$$
On solving (i) and (ii), we get $m=5$ and $n=1$.
Hence, the required values are **$m=5$** and **$n=1$**.

---

### Example 9:

Show that the system of equations
$$
3 x-5 y=7, \quad 6 x-10 y=3
$$
has no solution.

#### Solution:

The given system of equations is
$$
3 x-5 y-7=0 \quad \text{and} \quad 6 x-10 y-3=0
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=3, b_{1}=-5, c_{1}=-7$ and $a_{2}=6, b_{2}=-10, c_{2}=-3$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{3}{6}=\frac{1}{2}, \frac{b_{1}}{b_{2}}=\frac{-5}{-10}=\frac{1}{2}$ and $\frac{c_{1}}{c_{2}}=\frac{-7}{-3}=\frac{7}{3}$.

Clearly, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}$.

Hence, the given system of equations has **no solution**.

---

### Example 10:

Find the value of $k$ for which the system of equations
$$
x+2 y=5, \quad 3 x+k y-15=0
$$
has no solution.

#### Solution:

The given system of equations is
$$
\begin{align*}
& x+2 y-5=0 \tag{i} \\
& 3 x+k y-15=0 \tag{ii}
\end{align*}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=1, b_{1}=2, c_{1}=-5$ and $a_{2}=3, b_{2}=k, c_{2}=-15$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{1}{3}, \frac{b_{1}}{b_{2}}=\frac{2}{k}$ and $\frac{c_{1}}{c_{2}}=\frac{-5}{-15}=\frac{1}{3}$.

Let the given system of equations have **no solution**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{1}{3}=\frac{2}{k} \neq \frac{1}{3}
$$
This requires $\frac{1}{3}=\frac{2}{k}$ and $\frac{2}{k} \neq \frac{1}{3}$.
The first condition gives $k=6$. The second condition gives $k \neq 6$.
These two conditions, $k=6$ and $k \neq 6$, are contradictory.
Hence, there is **no value of $k$** for which the given system of equations has no solution.

---

### Example 11:

Find the values of $k$ for which the pair of linear equations
$$
k x+3 y=k-2 \quad \text{and} \quad 12 x+k y=k
$$
has no solution.

#### Solution:

The given equations are
$$
k x+3 y+(2-k)=0 \quad \text{and} \quad 12 x+k y-k=0
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=k, b_{1}=3, c_{1}=(2-k)$ and $a_{2}=12, b_{2}=k, c_{2}=-k$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{k}{12} ; \frac{b_{1}}{b_{2}}=\frac{3}{k}$ and $\frac{c_{1}}{c_{2}}=\frac{(2-k)}{-k}=\frac{(k-2)}{k}$.

Let the given system of equations have **no solution**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{k}{12}=\frac{3}{k} \neq \frac{(k-2)}{k}
$$
This requires:
$$
\frac{k}{12}=\frac{3}{k} \quad \text{and} \quad \frac{3}{k} \neq \frac{(k-2)}{k}
$$
From the first part: $k^{2}=36 \Rightarrow k=6$ or $k=-6$.
From the second part: $3 \neq k-2 \Rightarrow k \neq 5$. This simplifies to $k^{2}-2k \neq 3k \Rightarrow k^{2}-5k \neq 0 \Rightarrow k(k-5) \neq 0$.

-   **Case 1:** When $k=6$.
    In this case, $k(k-5)=6(6-5)=6 \times 1=6 \neq 0$. The condition is satisfied.
-   **Case 2:** When $k=-6$.
    In this case, $k(k-5)=(-6)(-6-5)=(-6) \times(-11)=66 \neq 0$. The condition is satisfied.

Thus, in each case, the given system has no solution.
Hence, **$k=6$** or **$k=-6$**.

---

### Example 12:

Find the value of $k$ for which the pair of linear equations
$$
(3 k+1) x+3 y-2=0, \quad \left(k^{2}+1\right) x+(k-2) y-5=0
$$
has no solution.

#### Solution:

The given linear equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=(3 k+1), b_{1}=3, c_{1}=-2$ and $a_{2}=\left(k^{2}+1\right), b_{2}=(k-2), c_{2}=-5$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{(3 k+1)}{\left(k^{2}+1\right)}, \frac{b_{1}}{b_{2}}=\frac{3}{(k-2)}$ and $\frac{c_{1}}{c_{2}}=\frac{-2}{-5}=\frac{2}{5}$.

Let the given system of equations have **no solution**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{(3 k+1)}{\left(k^{2}+1\right)}=\frac{3}{(k-2)} \neq \frac{2}{5}
$$
We need to solve:
$$
\frac{(3 k+1)}{\left(k^{2}+1\right)}=\frac{3}{(k-2)} \quad \text{(i) and} \quad \frac{3}{(k-2)} \neq \frac{2}{5} \quad \text{(ii)}
$$
From (i):
$$
(3 k+1)(k-2)=3\left(k^{2}+1\right)
$$
$$
\Rightarrow 3 k^{2}-6 k+k-2=3 k^{2}+3
$$
$$
\Rightarrow -5k - 2 = 3
$$
$$
\Rightarrow 5 k=-5 \Rightarrow k=-1
$$
When $k=-1$, we check condition (ii):
$$
\frac{3}{(-1-2)} = \frac{3}{-3} = -1 \neq \frac{2}{5}
$$
The condition is satisfied.
Hence, the given system of equations has no solution when **$k=-1$**.

---

### Example 13:

Find the value of $k$ for which the following pair of linear equations has no solution:
$$
3 x+y=1, \quad (2 k-1) x+(k-1) y=2 k+1
$$

#### Solution:

The given linear equations are
$$
\begin{align*}
& 3 x+y-1=0 \tag{i} \\
& (2 k-1) x+(k-1) y-(2 k+1)=0 \tag{ii}
\end{align*}
$$
These equations are of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=3, b_{1}=1, c_{1}=-1$ and $a_{2}=(2 k-1), b_{2}=(k-1), c_{2}=-(2 k+1)$.

$\therefore \quad \frac{a_{1}}{a_{2}}=\frac{3}{(2 k-1)}, \frac{b_{1}}{b_{2}}=\frac{1}{(k-1)}, \frac{c_{1}}{c_{2}}=\frac{-1}{-(2 k+1)}=\frac{1}{(2 k+1)}$.

Let the given system of equations have **no solution**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}$
$$
\Rightarrow \frac{3}{(2 k-1)}=\frac{1}{(k-1)} \neq \frac{1}{(2 k+1)}
$$
This requires:
$$
\frac{3}{(2 k-1)}=\frac{1}{(k-1)} \quad \text{and} \quad \frac{1}{(k-1)} \neq \frac{1}{(2 k+1)}
$$
From the first part: $3(k-1) = 1(2k-1) \Rightarrow 3k-3=2k-1 \Rightarrow k=2$.

We check this value in the second part: When $k=2$,
$$
\frac{1}{(2-1)} = 1 \quad \text{and} \quad \frac{1}{(2(2)+1)} = \frac{1}{5}
$$
Since $1 \neq \frac{1}{5}$, the condition is satisfied.
Hence, the given system of equations will have no solution when **$k=2$**.

---

### Example 14:

Find the values of $k$ for which the system of equations
$$
k x-y=2, \quad 6 x-2 y=3
$$
has (i) a unique solution, (ii) no solution.
(iii) Is there a value of $k$ for which the given system has infinitely many solutions?

#### Solution:

The given system of equations is
$$
k x-y-2=0, \quad 6 x-2 y-3=0
$$
This is of the form
$$
a_{1} x+b_{1} y+c_{1}=0 \quad \text{and} \quad a_{2} x+b_{2} y+c_{2}=0
$$
where $a_{1}=k, b_{1}=-1, c_{1}=-2$ and $a_{2}=6, b_{2}=-2, c_{2}=-3$.

1.  **For a unique solution**, we must have $\frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}}$.
    $$
    \therefore \quad \frac{k}{6} \neq \frac{-1}{-2} \Rightarrow \frac{k}{6} \neq \frac{1}{2} \Rightarrow k \neq 3
    $$
    Hence, the given system of equations will have a unique solution when **$k \neq 3$**.

2.  **For no solution**, we must have $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}} \neq \frac{c_{1}}{c_{2}}$.
    $$
    \therefore \quad \frac{k}{6}=\frac{-1}{-2} \neq \frac{-2}{-3}
    $$
    $$
    \Rightarrow \frac{k}{6}=\frac{1}{2} \neq \frac{2}{3}
    $$
    This requires $\frac{k}{6}=\frac{1}{2}$ and $\frac{1}{2} \neq \frac{2}{3}$.
    The second part is always true. From the first part, we get $k=3$.
    Hence, the given system of equations will have no solution when **$k=3$**.

3.  **For infinitely many solutions**, we must have $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}=\frac{c_{1}}{c_{2}}$.
    $$
    \text{i.e.,} \quad \frac{k}{6}=\frac{-1}{-2}=\frac{-2}{-3} \quad \Rightarrow \quad \frac{k}{6}=\frac{1}{2}=\frac{2}{3}
    $$
    This is never possible, as $\frac{1}{2} \neq \frac{2}{3}$.
    Hence, there is **no real value of $k$** for which the given system of equations has infinitely many solutions.

---

## Homogeneous System of Equations

The system of equations $a_{1} x+b_{1} y=0$ and $a_{2} x+b_{2} y=0$ has:
1.  the **zero solution**, $x=0$ and $y=0$, when $\frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}}$.
2.  an **infinite number of nonzero solutions** when $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}$.

*Note: The homogeneous system of equations is always consistent.*

---

### Example 15:

Find the value of $k$ for which the system of equations
$$
3 x+5 y=0, \quad k x+10 y=0
$$
has a nonzero solution.

#### Solution:

The given equations are of the form
$$
a_{1} x+b_{1} y=0 \quad \text{and} \quad a_{2} x+b_{2} y=0
$$
where $a_{1}=3, b_{1}=5$ and $a_{2}=k, b_{2}=10$.

Then, $\frac{a_{1}}{a_{2}}=\frac{3}{k}$ and $\frac{b_{1}}{b_{2}}=\frac{5}{10}=\frac{1}{2}$.

Let the given system of equations have a **nonzero solution**.
Then, $\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}$
$$
\Rightarrow \frac{3}{k}=\frac{1}{2} \Rightarrow k=6
$$
Hence, the required value of $k$ is **6**.

---

