## Method of Cross Multiplication

### Theorem

The system of two linear equations
$$
a_{1} x+b_{1} y+c_{1}=0, a_{2} x+b_{2} y+c_{2}=0
$$
where $\frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}}$, has a unique solution, given by
$$
x=\frac{\left(b_{1} c_{2}-b_{2} c_{1}\right)}{\left(a_{1} b_{2}-a_{2} b_{1}\right)}, y=\frac{\left(c_{1} a_{2}-c_{2} a_{1}\right)}{\left(a_{1} b_{2}-a_{2} b_{1}\right)}.
$$

---

### Proof

The given equations are
$$
\begin{align*}
& a_{1} x+b_{1} y+c_{1}=0 \tag{i}\\
& a_{2} x+b_{2} y+c_{2}=0 \tag{ii}
\end{align*}
$$
Multiplying (i) by $b_{2}$, (ii) by $b_{1}$ and subtracting, we get
$$
\begin{aligned}
& \left(a_{1} b_{2}-a_{2} b_{1}\right) x=\left(b_{1} c_{2}-b_{2} c_{1}\right) \\
\Rightarrow \quad & x=\frac{\left(b_{1} c_{2}-b_{2} c_{1}\right)}{\left(a_{1} b_{2}-a_{2} b_{1}\right)} \quad\left[\because \frac{a_{1}}{a_{2}} \neq \frac{b_{1}}{b_{2}} \Rightarrow\left(a_{1} b_{2}-a_{2} b_{1}\right) \neq 0\right] .
\end{aligned}
$$
Multiplying (ii) by $a_{1}$, (i) by $a_{2}$ and subtracting, we get
$$
\begin{aligned}
& \left(a_{1} b_{2}-a_{2} b_{1}\right) y=\left(c_{1} a_{2}-c_{2} a_{1}\right) \\
\Rightarrow \quad & y=\frac{\left(c_{1} a_{2}-c_{2} a_{1}\right)}{\left(a_{1} b_{2}-a_{2} b_{1}\right)} \quad\left[\because \quad\left(a_{1} b_{2}-a_{2} b_{1}\right) \neq 0\right] .
\end{aligned}
$$
Hence, a unique solution exists, which is given by
$$
x=\frac{\left(b_{1} c_{2}-b_{2} c_{1}\right)}{\left(a_{1} b_{2}-a_{2} b_{1}\right)}, y=\frac{\left(c_{1} a_{2}-c_{2} a_{1}\right)}{\left(a_{1} b_{2}-a_{2} b_{1}\right)}.
$$
This is customarily written as
$$
\frac{x}{\left(b_{1} c_{2}-b_{2} c_{1}\right)}=\frac{y}{\left(c_{1} a_{2}-c_{2} a_{1}\right)}=\frac{1}{\left(a_{1} b_{2}-a_{2} b_{1}\right)}.
$$

---

### Remark

The following diagram helps in remembering the above solution.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Algebra/Linear-Equations-in-Two-Variables/class-10-Ch-03-C-BooK-001.jpg)

**Rule**: Numbers with **downward arrows** are multiplied first; and from this product, the product of numbers with **upward arrows** is subtracted.

---

## Solved Examples

### Example 1

Solve the system of equations $2x+3y=17, 3x-2y=6$ by the method of cross multiplication.

#### Solution:

The given equations may be written as
$$
\begin{align*}
& 2x+3y-17=0 \tag{i}\\
& 3x-2y-6=0 \tag{ii}
\end{align*}
$$
By cross multiplication, we have
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Algebra/Linear-Equations-in-Two-Variables/class-10-Ch-03-C-BooK-002.jpg)
$$
\begin{aligned}
& \therefore \quad \frac{x}{\{3 \times(-6)-(-2) \times(-17)\}}=\frac{y}{\{(-17) \times 3-(-6) \times 2\}} =\frac{1}{\{2 \times(-2)-3 \times 3\}} \\
& \Rightarrow \quad \frac{x}{(-18-34)}=\frac{y}{(-51+12)}=\frac{1}{(-4-9)} \\
& \Rightarrow \quad \frac{x}{-52}=\frac{y}{-39}=\frac{1}{-13} \\
& \Rightarrow \quad x=\frac{-52}{-13}=4, y=\frac{-39}{-13}=3
\end{aligned}
$$
Hence, $x=4$ and $y=3$ is the required solution.

---

### Example 2

Solve $4x-7y+28=0, 5y-7x+9=0$.

#### Solution:

The given equations are
$$
\begin{align*}
& 4x-7y+28=0 \tag{i}\\
& -7x+5y+9=0 \tag{ii}
\end{align*}
$$
By cross multiplication, we have
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Algebra/Linear-Equations-in-Two-Variables/class-10-Ch-03-C-BooK-003.jpg)
$$
\begin{aligned}
& \therefore \frac{x}{\{(-7) \times 9-5 \times 28\}}=\frac{y}{\{28 \times(-7)-9 \times 4\}}=\frac{1}{\{4 \times 5-(-7) \times(-7)\}} \\
& \Rightarrow \quad \frac{x}{(-63-140)}=\frac{y}{(-196-36)}=\frac{1}{(20-49)} \\
& \Rightarrow \frac{x}{-203}=\frac{y}{-232}=\frac{1}{-29} \\
& \Rightarrow x=\left(\frac{-203}{-29}\right)=7 \text{ and } y=\left(\frac{-232}{-29}\right)=8.
\end{aligned}
$$
Hence, $x=7$ and $y=8$ is the required solution.

---

### Example 3

Solve $\frac{2}{x}+\frac{3}{y}=13, \frac{5}{x}-\frac{4}{y}=-2$, where $x \neq 0$ and $y \neq 0$.

#### Solution:

Taking $\frac{1}{x}=u$ and $\frac{1}{y}=v$, the given equations become
$$
\begin{align*}
& 2u+3v-13=0 \tag{i}\\
& 5u-4v+2=0 . \tag{ii}
\end{align*}
$$
By cross multiplication, we have
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Algebra/Linear-Equations-in-Two-Variables/class-10-Ch-03-C-BooK-004.jpg)
$$
\begin{aligned}
& \therefore \frac{u}{[3 \times 2-(-4) \times(-13)]}=\frac{v}{[(-13) \times 5-2 \times 2]}=\frac{1}{[2 \times(-4)-5 \times 3]} \\
& \Rightarrow \frac{u}{-46}=\frac{v}{-69}=\frac{1}{-23} \\
& \Rightarrow \quad u=\left(\frac{-46}{-23}\right)=2, v=\left(\frac{-69}{-23}\right)=3 \\
& \Rightarrow \frac{1}{x}=2, \frac{1}{y}=3 \\
& \Rightarrow \quad x=\frac{1}{2}, y=\frac{1}{3}.
\end{aligned}
$$
Hence, $x=\frac{1}{2}$ and $y=\frac{1}{3}$ is the required solution.

---

### Example 4

Solve $ax+by=c, bx+ay=1+c$.

#### Solution:

The given equations may be written as
$$
\begin{align*}
& ax+by-c=0 \tag{i}\\
& bx+ay-(1+c)=0 \tag{ii}
\end{align*}
$$
By cross multiplication, we have
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-10/Algebra/Linear-Equations-in-Two-Variables/class-10-Ch-03-C-BooK-005.jpg)
$$
\begin{aligned}
& \therefore \quad \frac{x}{-b(1+c)+ac}=\frac{y}{-cb+a(1+c)}=\frac{1}{\left(a^{2}-b^{2}\right)} \\
& \Rightarrow \quad x=\frac{c(a-b)-b}{\left(a^{2}-b^{2}\right)} \text{ and } y=\frac{c(a-b)+a}{\left(a^{2}-b^{2}\right)}.
\end{aligned}
$$
Hence, $x=\frac{c(a-b)-b}{\left(a^{2}-b^{2}\right)}$ and $y=\frac{c(a-b)+a}{\left(a^{2}-b^{2}\right)}$.

---

