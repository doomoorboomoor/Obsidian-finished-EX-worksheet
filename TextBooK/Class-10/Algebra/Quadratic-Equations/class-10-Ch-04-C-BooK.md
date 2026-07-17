## Quadratic Formula [Shridharacharya's Rule]

Consider the quadratic equation $a x^{2}+b x+c=0$, where $a, b, c$ are real numbers and $a \neq 0$.

Then,
$$
\begin{aligned}
& a x^{2}+b x+c=0 \\
\Rightarrow & a x^{2}+b x=-c \\
\Rightarrow & x^{2}+\frac{b}{a} \cdot x=\frac{-c}{a} \\
\Rightarrow & x^{2}+\frac{b}{a} \cdot x+\left(\frac{b}{2 a}\right)^{2}=\frac{-c}{a}+\left(\frac{b}{2 a}\right)^{2} \quad\left[\text { adding }\left(\frac{b}{2 a}\right)^{2}\right. \text { on both sides] } \\
\Rightarrow & \left(x+\frac{b}{2 a}\right)^{2}=\left(\frac{-c}{a}+\frac{b^{2}}{4 a^{2}}\right) \\
\Rightarrow & \left(x+\frac{b}{2 a}\right)^{2}=\frac{\left(b^{2}-4 a c\right)}{4 a^{2}} \\
\Rightarrow & \left(x+\frac{b}{2 a}\right)=\frac{ \pm \sqrt{b^{2}-4 a c}}{2 a}, \text { when }\left(b^{2}-4 a c\right) \geq 0 \\
\Rightarrow & x=\frac{-b}{2 a} \pm \frac{\sqrt{b^{2}-4 a c}}{2 a} \\
\Rightarrow & x=\frac{-b \pm \sqrt{b^{2}-4 a c}}{2 a}
\end{aligned}
$$

This is called the **quadratic formula** or **Shridharacharya's rule**.

Thus, $a x^{2}+b x+c=0$ has two roots $\alpha$ and $\beta$, given by
$$
\alpha=\frac{-b+\sqrt{b^{2}-4 a c}}{2 a} \text { and } \beta=\frac{-b-\sqrt{b^{2}-4 a c}}{2 a}
$$

For the equation $a x^{2}+b x+c=0$, the expression $D=\left(b^{2}-4 a c\right)$ is called the **discriminant**.

An important note: The roots of $a x^{2}+b x+c=0$ are **real** only when $\left(b^{2}-4 a c\right) \geq 0$.

Taking $\left(b^{2}-4 a c\right)=D$, the roots of $a x^{2}+b x+c=0$ are given by
$$
\alpha=\frac{-b+\sqrt{D}}{2 a} \text { and } \beta=\frac{-b-\sqrt{D}}{2 a}
$$

---
## Solved Examples

### Example 1: Show that the equation $9 x^{2}+7 x-2=0$ has real roots and solve it.

#### Solution:

The given equation is $9 x^{2}+7 x-2=0$.
Comparing it with $a x^{2}+b x+c=0$, we get $a=9, b=7$ and $c=-2$.
$$
\therefore \quad D=\left(b^{2}-4 a c\right)=\left(7^{2}-4 \times 9 \times(-2)\right]=121>0 .
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\sqrt{121}=11$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-b+\sqrt{D}}{2 a}=\frac{(-7+11)}{2 \times 9}=\frac{4}{18}=\frac{2}{9} \\
& \beta=\frac{-b-\sqrt{D}}{2 a}=\frac{(-7-11)}{2 \times 9}=\frac{-18}{18}=-1 .
\end{aligned}
$$
Hence, the required roots are $\frac{2}{9}$ and $-1$.

---
### Example 2: Show that the equation $x^{2}+6 x+6=0$ has real roots and solve it.

#### Solution:

The given equation is $x^{2}+6 x+6=0$.
Comparing it with $a x^{2}+b x+c=0$, we get $a=1, b=6$ and $c=6$.
$$
\therefore \quad D=\left(b^{2}-4 a c\right)=(36-4 \times 1 \times 6)=12>0 .
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\sqrt{12}=2 \sqrt{3}$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-b+\sqrt{D}}{2 a}=\frac{(-6+2 \sqrt{3})}{2 \times 1}=\frac{(-6+2 \sqrt{3})}{2}=(-3+\sqrt{3}), \\
& \beta=\frac{-b-\sqrt{D}}{2 a}=\frac{(-6-2 \sqrt{3})}{2 \times 1}=\frac{(-6-2 \sqrt{3})}{2}=(-3-\sqrt{3}) .
\end{aligned}
$$
Hence, $(-3+\sqrt{3})$ and $(-3-\sqrt{3})$ are the roots of the given equation.

---
### Example 3: Show that the equation $2 x^{2}+5 \sqrt{3} x+6=0$ has real roots and solve it.

#### Solution:

The given equation is $2 x^{2}+5 \sqrt{3} x+6=0$.
Comparing it with $a x^{2}+b x+c=0$, we get $a=2, b=5 \sqrt{3}$ and $c=6$.
$$
\therefore \quad D=\left(b^{2}-4 a c\right)=\left[(5 \sqrt{3})^{2}-4 \times 2 \times 6\right]=(75-48)=27>0 .
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\sqrt{27}=3 \sqrt{3}$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-b+\sqrt{D}}{2 a}=\frac{(-5 \sqrt{3}+3 \sqrt{3})}{2 \times 2}=\frac{-2 \sqrt{3}}{4}=\frac{-\sqrt{3}}{2}, \\
& \beta=\frac{-b-\sqrt{D}}{2 a}=\frac{(-5 \sqrt{3}-3 \sqrt{3})}{2 \times 2}=\frac{-8 \sqrt{3}}{4}=-2 \sqrt{3} .
\end{aligned}
$$
Hence, $\frac{-\sqrt{3}}{2}$ and $-2 \sqrt{3}$ are the roots of the given equation.

---
### Example 4: Using quadratic formula, solve for $x$: $p^{2} x^{2}+\left(p^{2}-q^{2}\right) x-q^{2}=0$.

#### Solution:

The given equation is $p^{2} x^{2}+\left(p^{2}-q^{2}\right) x-q^{2}=0$.
Comparing it with $a x^{2}+b x+c=0$, we get $a=p^{2}, b=\left(p^{2}-q^{2}\right)$ and $c=-q^{2}$.
$$
\begin{aligned}
\therefore \quad D=\left(b^{2}-4 a c\right) &=\left(p^{2}-q^{2}\right)^{2}-4 \times p^{2} \times\left(-q^{2}\right) \\
&=\left(p^{2}-q^{2}\right)^{2}+4 p^{2} q^{2}=\left(p^{2}+q^{2}\right)^{2}>0 .
\end{aligned}
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\left(p^{2}+q^{2}\right)$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-b+\sqrt{D}}{2 a}=\frac{-\left(p^{2}-q^{2}\right)+\left(p^{2}+q^{2}\right)}{2 p^{2}}=\frac{2 q^{2}}{2 p^{2}}=\frac{q^{2}}{p^{2}} \\
& \beta=\frac{-b-\sqrt{D}}{2 a}=\frac{-\left(p^{2}-q^{2}\right)-\left(p^{2}+q^{2}\right)}{2 p^{2}}=\frac{-2 p^{2}}{2 p^{2}}=-1 .
\end{aligned}
$$
Hence, $\frac{q^{2}}{p^{2}}$ and $-1$ are the roots of the given equation.

---
### Example 5: Using quadratic formula, solve for $x$: $9 x^{2}-9(a+b) x+\left(2 a^{2}+5 a b+2 b^{2}\right)=0$.

#### Solution:

The given equation is $9 x^{2}-9(a+b) x+\left(2 a^{2}+5 a b+2 b^{2}\right)=0$.
This is of the form $A x^{2}+B x+C=0$, where $A=9, B=-9(a+b)$ and $C=\left(2 a^{2}+5 a b+2 b^{2}\right)$.
$$
\begin{aligned}
\therefore \quad D=\left(B^{2}-4 A C\right) & =81(a+b)^{2}-36\left(2 a^{2}+5 a b+2 b^{2}\right) \\
& =81\left(a^{2}+b^{2}+2 a b\right)-36\left(2 a^{2}+5 a b+2 b^{2}\right) \\
& =9 a^{2}+9 b^{2}-18 a b=9\left(a^{2}+b^{2}-2 a b\right) \\
& =9(a-b)^{2} \geq 0 .
\end{aligned}
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\sqrt{9(a-b)^{2}}=3(a-b)$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-B+\sqrt{D}}{2 A}=\frac{9(a+b)+3(a-b)}{2 \times 9}=\frac{6(2 a+b)}{18}=\frac{(2 a+b)}{3}, \\
& \beta=\frac{-B-\sqrt{D}}{2 A}=\frac{9(a+b)-3(a-b)}{2 \times 9}=\frac{6(a+2 b)}{18}=\frac{(a+2 b)}{3} .
\end{aligned}
$$
Hence, $\frac{(2 a+b)}{3}$ and $\frac{(a+2 b)}{3}$ are the roots of the given equation.

---
### Example 6: Using quadratic formula, solve for $x$: $a b x^{2}+\left(b^{2}-a c\right) x-b c=0$.

#### Solution:

The given equation is $a b x^{2}+\left(b^{2}-a c\right) x-b c=0$.
This is of the form $A x^{2}+B x+C=0$, where $A=a b, B=\left(b^{2}-a c\right)$ and $C=-b c$.
$$
\begin{aligned}
\therefore \quad D=\left(B^{2}-4 A C\right) &=\left(b^{2}-a c\right)^{2}+4 a b^{2} c \\
&=b^{4}+a^{2} c^{2}-2 a b^{2} c+4 a b^{2} c \\
&=b^{4}+a^{2} c^{2}+2 a b^{2} c=\left(b^{2}+a c\right)^{2}>0 .
\end{aligned}
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\left(b^{2}+a c\right)$.
$$
\begin{aligned}
\therefore \quad \alpha & =\frac{-B+\sqrt{D}}{2 A}=\frac{-\left(b^{2}-a c\right)+\left(b^{2}+a c\right)}{2 a b}=\frac{2 a c}{2 a b}=\frac{c}{b}, \\
\beta & =\frac{-B-\sqrt{D}}{2 A}=\frac{-\left(b^{2}-a c\right)+\left(b^{2}+a c\right)}{2 a b}=\frac{-2 b^{2}}{2 a b}=\frac{-b}{a} .
\end{aligned}
$$
Hence, $\frac{c}{b}$ and $\frac{-b}{a}$ are the roots of the given equation.

---
### Example 7: Solve for $x: \frac{1}{x}-\frac{1}{(x-2)}=3, x \neq 0,2$.

#### Solution:

The given equation may be written as
$$
\begin{align*}
\frac{(x-2)-x}{x(x-2)}=3 & \Rightarrow 3 x(x-2)=-2 \\
& \Rightarrow 3 x^{2}-6 x+2=0 \tag{i}
\end{align*}
$$
This equation is of the form $a x^{2}+b x+c=0$, where $a=3$, $b=-6$ and $c=2$.
$$
\therefore \quad D=\left(b^{2}-4 a c\right)=(-6)^{2}-4 \times 3 \times 2=36-24=12>0 .
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\sqrt{12}=2 \sqrt{3}$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-b+\sqrt{D}}{2 a}=\frac{6+2 \sqrt{3}}{2 \times 3}=\frac{6+2 \sqrt{3}}{6}=\frac{3+\sqrt{3}}{3} \\
& \beta=\frac{-b-\sqrt{D}}{2 a}=\frac{6-2 \sqrt{3}}{2 \times 3}=\frac{6-2 \sqrt{3}}{6}=\frac{3-\sqrt{3}}{3}
\end{aligned}
$$
Hence, the required values of $x$ are $\frac{(3+\sqrt{3})}{3}$ and $\frac{(3-\sqrt{3})}{3}$.

---
### Example 8: Solve for $x: \frac{x-1}{x-2}+\frac{x-3}{x-4}=3 \frac{1}{3}, x \neq 2,4$.

#### Solution:

The given equation is
$$
\begin{align*}
& \frac{x-1}{x-2}+\frac{x-3}{x-4}=\frac{10}{3} \\
\Rightarrow & \frac{(x-1)(x-4)+(x-3)(x-2)}{(x-2)(x-4)}=\frac{10}{3} \\
\Rightarrow & \frac{\left(x^{2}-5 x+4\right)+\left(x^{2}-5 x+6\right)}{\left(x^{2}-6 x+8\right)}=\frac{10}{3} \Rightarrow \frac{2 x^{2}-10 x+10}{x^{2}-6 x+8}=\frac{10}{3} \\
\Rightarrow & 3\left(2 x^{2}-10 x+10\right)=10\left(x^{2}-6 x+8\right) \\
\Rightarrow & 6 x^{2}-30 x+30=10 x^{2}-60 x+80 \\
\Rightarrow & 4 x^{2}-30 x+50=0 \Rightarrow 2 x^{2}-15 x+25=0 \tag{i}
\end{align*}
$$
This equation is of the form $a x^{2}+b x+c=0$, where $a=2$, $b=-15$ and $c=25$.
$$
\therefore \quad D=\left(b^{2}-4 a c\right)=\left\{(-15)^{2}-4 \times 2 \times 25\right\}=(225-200)=25>0
$$
So, the given equation has real roots.
Now, $\sqrt{D}=\sqrt{25}=5$.
$$
\begin{aligned}
\therefore \quad & \alpha=\frac{-b+\sqrt{D}}{2 a}=\frac{(15+5)}{2 \times 2}=\frac{20}{4}=5, \\
& \beta=\frac{-b-\sqrt{D}}{2 a}=\frac{(15-5)}{2 \times 2}=\frac{10}{4}=\frac{5}{2} .
\end{aligned}
$$
Hence, the required values of $x$ are $5$ and $\frac{5}{2}$.

---
