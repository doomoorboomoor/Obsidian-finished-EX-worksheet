## Differentiability

Let $f(x)$ be a real function and $a$ be any real number. Then, we define:

1.  **Right-hand derivative:** $\lim _{h \rightarrow 0} \frac{f(a+h)-f(a)}{h}$, if it exists, is called the right-hand derivative of $f(x)$ at $x=a$, and it is denoted by $R f^{\prime}(a)$.
2.  **Left-hand derivative:** $\lim _{h \rightarrow 0} \frac{f(a-h)-f(a)}{-h}$, if it exists, is called the left-hand derivative of $f(x)$ at $x=a$, and it is denoted by $L f^{\prime}(a)$.

**Differentiability:** A function $f(x)$ is said to be **differentiable** at $x=a$, if $R f^{\prime}(a)=L f^{\prime}(a)$.

The common value of $R f^{\prime}(a)$ and $L f^{\prime}(a)$ is denoted by $f^{\prime}(a)$ and it is known as the **derivative** of $f(x)$ at $x=a$.

If, however, $R f^{\prime}(a) \neq L f^{\prime}(a)$, we say that $f(x)$ is **not differentiable** at $x=a$.

> **Remark:** In each case, $h$ is taken as positive and very small.

---

## Solved Examples

### Example 1
Show that $f(x)=x^{2}$ is differentiable at $x=1$ and find $f^{\prime}(1)$.

#### Solution:

$$
\begin{aligned}
R f^{\prime}(1) &= \lim _{h \rightarrow 0} \frac{f(1+h)-f(1)}{h} = \lim _{h \rightarrow 0} \frac{(1+h)^{2}-(1)^{2}}{h} \\
&= \lim _{h \rightarrow 0}\left(\frac{1+h^{2}+2 h-1}{h}\right) = \lim _{h \rightarrow 0}(h+2)=2 .
\end{aligned}
$$

And,
$$
\begin{aligned}
L f^{\prime}(1) &= \lim _{h \rightarrow 0} \frac{f(1-h)-f(1)}{-h} = \lim _{h \rightarrow 0} \frac{(1-h)^{2}-(1)^{2}}{-h} \\
&= \lim _{h \rightarrow 0}\left(\frac{1+h^{2}-2 h-1}{-h}\right) = \lim _{h \rightarrow 0}(-h+2)=2 .
\end{aligned}
$$

$\therefore R f^{\prime}(1)=L f^{\prime}(1)=2$.

This shows that $f(x)$ is differentiable at $x=1$ and $f^{\prime}(1)=2$.

---

### Example 2
Show that $f(x)=[x]$ is not differentiable at $x=1$.

#### Solution:

We have $R f^{\prime}(1)=\lim _{h \rightarrow 0} \frac{f(1+h)-f(1)}{h}=\lim _{h \rightarrow 0} \frac{[1+h]-[1]}{h}=0$
$$
\{\because [1+h]=1 \text{ and }[1]=1\},
$$
and $L f^{\prime}(1)=\lim _{h \rightarrow 0} \frac{f(1-h)-f(1)}{-h}=\lim _{h \rightarrow 0} \frac{[1-h]-[1]}{-h}=\infty$
$$
\{\because [1-h]=0 \text{ and }[1]=1\}.
$$
Thus, $R f^{\prime}(1) \neq L f^{\prime}(1)$.

Hence, $f(x)=[x]$ is not differentiable at $x=1$.

---

### Example 3
(i) Show that $f(x)=x^{4 / 3}$ is differentiable at $x=0$, and hence find $f^{\prime}(0)$.
(ii) Show that $g(x)=x^{3 / 2}$ is not differentiable at $x=0$.

#### Solution:

**(i)** We have
$$
\begin{aligned}
R f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h} = \lim _{h \rightarrow 0} \frac{f(h)-f(0)}{h} \\
&= \lim _{h \rightarrow 0} \frac{h^{4 / 3}-0}{h} = \lim _{h \rightarrow 0} \frac{h^{4 / 3}}{h} = \lim _{h \rightarrow 0} h^{1 / 3}=0 .
\end{aligned}
$$
And,
$$
\begin{aligned}
L f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0-h)-f(0)}{-h} = \lim _{h \rightarrow 0} \frac{f(-h)-0}{-h} \\
&= \lim _{h \rightarrow 0} \frac{(-h)^{4 / 3}-0}{(-h)} = \lim _{h \rightarrow 0} \frac{(-h)^{4 / 3}}{(-h)} = \lim _{h \rightarrow 0}(-h)^{1 / 3}=0 .
\end{aligned}
$$
Thus, $R f^{\prime}(0)=L f^{\prime}(0)=0$.

Hence, $f(x)=x^{4 / 3}$ is differentiable at $x=0$ and $f^{\prime}(0)=0$.

**(ii)** Consider $g(x)=x^{3 / 2}$.

Now,
$$
\begin{aligned}
R g^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{g(0+h)-g(0)}{h} = \lim _{h \rightarrow 0} \frac{g(h)-g(0)}{h} \\
&= \lim _{h \rightarrow 0} \frac{h^{3 / 2}-0}{h} = \lim _{h \rightarrow 0} \frac{h^{3 / 2}}{h} = \lim _{h \rightarrow 0} h^{1 / 2}=0 .
\end{aligned}
$$
And,
$$
\begin{aligned}
L g^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{g(0-h)-g(0)}{-h} = \lim _{h \rightarrow 0} \frac{g(-h)-g(0)}{-h} \\
&= \lim _{h \rightarrow 0} \frac{(-h)^{3 / 2}-0}{(-h)} = \lim _{h \rightarrow 0} \frac{(-h)^{3 / 2}}{(-h)} \\
&= \lim _{h \rightarrow 0}(-h)^{1 / 2}, \text{ which is imaginary.}
\end{aligned}
$$
Thus, $L g^{\prime}(0)$ does not exist.

Hence, $g(x)=x^{3 / 2}$ is not differentiable at $x=0$.

---

### Example 4
Show that the function $f(x)=\left\{\begin{array}{ll}1+x, & \text{if } x \leq 2 \\ 5-x, & \text{if } x>2\end{array}\right.$ is not differentiable at $x=2$.

#### Solution:

$$
\begin{aligned}
R f^{\prime}(2) &= \lim _{h \rightarrow 0} \frac{f(2+h)-f(2)}{h} = \lim _{h \rightarrow 0}\left[\frac{5-(2+h)-3}{h}\right] \\
&= \lim _{h \rightarrow 0} \frac{-h}{h} = \lim _{h \rightarrow 0}(-1)=-1 .
\end{aligned}
$$
And,
$$
\begin{aligned}
L f^{\prime}(2) &= \lim _{h \rightarrow 0} \frac{f(2-h)-f(2)}{-h} \\
&= \lim _{h \rightarrow 0}\left[\frac{1+(2-h)-3}{-h}\right] = \lim _{h \rightarrow 0} \frac{-h}{-h} = \lim _{h \rightarrow 0} 1=1 .
\end{aligned}
$$
Thus, $R f^{\prime}(2) \neq L f^{\prime}(2)$.

Hence, $f(x)$ is not differentiable at $x=2$.

---

### Example 5
Let $f(x)=\left\{\begin{array}{r}(1+\sin x), \text{ when } 0 \leq x<\frac{\pi}{2} \\ 1, \text{ when } x<0 .\end{array}\right.$
Show that $f^{\prime}(0)$ does not exist.

#### Solution:

We have
$$
\begin{aligned}
R f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h} = \lim _{h \rightarrow 0} \frac{f(h)-f(0)}{h} \\
&= \lim _{h \rightarrow 0} \frac{(1+\sin h)-1}{h} = \lim _{h \rightarrow 0} \frac{\sin h}{h}=1 .
\end{aligned}
$$
And,
$$
L f^{\prime}(0) = \lim _{h \rightarrow 0} \frac{f(0-h)-f(0)}{-h} = \lim _{h \rightarrow 0} \frac{f(-h)-f(0)}{-h} = \lim _{h \rightarrow 0} \frac{(1-1)}{-h}=0 .
$$
Thus, $R f^{\prime}(0) \neq L f^{\prime}(0)$. Hence, $f^{\prime}(0)$ does not exist.

---

### Example 6
Let $f(x)=m x+c$ and $f(0)=f^{\prime}(0)=1$. Find $f(2)$.

#### Solution:

Clearly, $f(0)=(m \times 0+c)=c=1$ (given).

Also,
$$
\begin{aligned}
f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h} = \lim _{h \rightarrow 0} \frac{f(h)-f(0)}{h} \\
&= \lim _{h \rightarrow 0} \frac{(m h+c)-1}{h} = \lim _{h \rightarrow 0} \frac{m h+1-1}{h} \quad [\because c=1] \\
&= \lim _{h \rightarrow 0} \frac{m h}{h} = \lim _{h \rightarrow 0} m=m
\end{aligned}
$$
Thus, $f^{\prime}(0)=1 \Rightarrow m=1$.

So, $f(x)=1 \cdot x+1$, i.e., $f(x)=(x+1)$. Hence, $f(2)=(2+1)=3$.

---

## Relation between Continuity and Differentiability

### Theorem
Every differentiable function is continuous. But, every continuous function need not be differentiable.

#### Proof:
Let $f(x)$ be a differentiable function and let $a$ be any real number in its domain. Then,
$$
\lim _{h \rightarrow 0} \frac{f(a+h)-f(a)}{h}=f^{\prime}(a). \tag{i}
$$
Now,
$$
\begin{aligned}
\lim _{h \rightarrow 0}[f(a+h)-f(a)] &= \lim _{h \rightarrow 0}\left[\frac{f(a+h)-f(a)}{h} \times h\right] \\
&= \lim _{h \rightarrow 0} \frac{f(a+h)-f(a)}{h} \times \lim _{h \rightarrow 0} h \\
&= f^{\prime}(a) \times 0=0 \quad \text{[using (i)]}.
\end{aligned}
$$
Thus, $\lim _{h \rightarrow 0}[f(a+h)-f(a)]=0$ or $\lim _{h \rightarrow 0} f(a+h)=f(a)$.

This shows that $f(x)$ is continuous at $a$ for all $a$.
Hence, every differentiable function is continuous.

In order to show that a continuous function need not be differentiable, it is sufficient to give an example of a function which is continuous but not differentiable.

Consider $f(x)=|x|$ at $x=0$.
Clearly, $f(0)=0$.

$$
\lim _{x \rightarrow 0+} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0}|h|=\lim _{h \rightarrow 0} h=0 .
$$
And,
$$
\lim _{x \rightarrow 0-} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)=\lim _{h \rightarrow 0}|-h|=\lim _{h \rightarrow 0} h=0 .
$$
Thus, $\lim _{x \rightarrow 0+} f(x)=\lim _{x \rightarrow 0-} f(x)=f(0)$.
So, $f(x)=|x|$ is continuous at $x=0$.

But,
$$
\begin{aligned}
R f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h} = \lim _{h \rightarrow 0} \frac{f(h)-f(0)}{h} \\
&= \lim _{h \rightarrow 0} \frac{|h|-0}{h} = \lim _{h \rightarrow 0} \frac{h}{h}=1 .
\end{aligned}
$$
And,
$$
\begin{aligned}
L f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0-h)-f(0)}{-h} = \lim _{h \rightarrow 0} \frac{f(-h)-f(0)}{-h} \\
&= \lim _{h \rightarrow 0} \frac{|-h|-0}{-h} = \lim _{h \rightarrow 0} \frac{h}{-h}=-1 .
\end{aligned}
$$
Thus, $R f^{\prime}(0) \neq L f^{\prime}(0)$.

This shows that $f(x)=|x|$ is not differentiable at $x=0$.
Thus, $f(x)=|x|$ is continuous but not differentiable at $x=0$.
Hence, a continuous function need not be differentiable.

---

### Example 7
Show that the function $f(x)=\left\{\begin{array}{r}x \sin (1 / x), \text{ when } x \neq 0 \\ 0, \text{ when } x=0\end{array}\right.$
is continuous but not differentiable at $x=0$.

#### Solution:
We have already discussed the above function for continuity at $x=0$.

Now,
$$
\begin{aligned}
R f^{\prime}(0) &= \lim _{h \rightarrow 0} \frac{f(0+h)-f(0)}{h} = \lim _{h \rightarrow 0} \frac{h \sin (1 / h)-0}{h} \\
&= \lim _{h \rightarrow 0} \sin (1 / h), \text{ which does not exist.}
\end{aligned}
$$
Hence, $f(x)$ is not differentiable at $x=0$.

---

### Example 8
Show that $f(x)=|x-2|$ is continuous but not differentiable at $x=2$.

#### Solution:
We have $f(2)=|2-2|=0$.
$$
\lim _{x \rightarrow 2+} f(x) = \lim _{h \rightarrow 0} f(2+h) = \lim _{h \rightarrow 0}|2+h-2| = \lim _{h \rightarrow 0}|h| = \lim _{h \rightarrow 0} h=0 .
$$
$$
\lim _{x \rightarrow 2-} f(x) = \lim _{h \rightarrow 0} f(2-h) = \lim _{h \rightarrow 0}|2-h-2| = \lim _{h \rightarrow 0}|-h| = \lim _{h \rightarrow 0} h=0 .
$$
$\therefore \lim _{x \rightarrow 2+} f(x)=\lim _{x \rightarrow 2-} f(x)=f(2)=0$.

So, $f(x)$ is continuous at $x=2$.

But,
$$
\begin{aligned}
R f^{\prime}(2) &= \lim _{h \rightarrow 0} \frac{f(2+h)-f(2)}{h} = \lim _{h \rightarrow 0} \frac{|2+h-2|-0}{h} \\
&= \lim _{h \rightarrow 0} \frac{|h|}{h} = \lim _{h \rightarrow 0} \frac{h}{h}=1
\end{aligned}
$$
And,
$$
\begin{aligned}
L f^{\prime}(2) &= \lim _{h \rightarrow 0} \frac{f(2-h)-f(2)}{-h} = \lim _{h \rightarrow 0} \frac{|2-h-2|-0}{-h} \\
&= \lim _{h \rightarrow 0} \frac{|-h|}{-h} = \lim _{h \rightarrow 0} \frac{h}{-h}=-1 .
\end{aligned}
$$
Thus, $R f^{\prime}(2) \neq L f^{\prime}(2)$.

This shows that $f(x)$ is not differentiable at $x=2$.

---

## Exercise 9C

1.  Show that $f(x)=x^{3}$ is continuous as well as differentiable at $x=3$.
2.  Show that $f(x)=(x-1)^{1 / 3}$ is not differentiable at $x=1$.
3.  Show that a constant function is always differentiable.
4.  Show that $f(x)=|x-5|$ is continuous but not differentiable at $x=5$.
5.  Let $f(x)=\left\{\begin{array}{r}(2-x), \text{ when } x \geq 1 \\ x, \text{ when } 0 \leq x \leq 1 .\end{array}\right.$ Show that $f(x)$ is continuous but not differentiable at $x=1$.
6.  Show that $f(x)=[x]$ is neither continuous nor derivable at $x=2$.
7.  Show that the function $f(x)=\left\{\begin{array}{cl}(1-x), & \text{ when } x<1 \\ \left(x^{2}-1\right), & \text{ when } x \geq 1\end{array}\right.$ is continuous but not differentiable at $x=1$.
8.  Let $f(x)=\left\{\begin{array}{ll}(2+x), & \text{ if } x \geq 0 \\ (2-x), & \text{ if } x<0 .\end{array}\right.$ Show that $f(x)$ is not derivable at $x=0$.
9.  If $f(x)=|x|$, show that $f^{\prime}(2)=1$.
10. Find the values of $a$ and $b$ so that the function
    $$
    f(x)=\left\{\begin{array}{r}
    \left(x^{2}+3 x+a\right), \text{ when } x \leq 1 \\
    (b x+2), \text{ when } x>1
    \end{array}\right.
    $$
    is differentiable at each $x \in R$.

---

## Answers (Exercise 9C)

10. $a=3, b=5$

---

## Hints to Some Selected Questions (Exercise 9C)

9.  Show that $R f^{\prime}(2)=L f^{\prime}(2)=1$.
10. $R f^{\prime}(1)=L f^{\prime}(1)=5$.