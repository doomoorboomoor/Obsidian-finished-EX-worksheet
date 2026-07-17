## Left-Hand Limit

Let $f(x)$ be a given function and let $x$ approach to **a** from the left. Then, the limit of $f(x)$, as $x$ approaches to **a** from the left, is denoted by $\lim _{x \rightarrow a^{-}} f(x)$.

### Method for Finding $\lim _{x \rightarrow a^{-}} f(x)$

Replace $x$ by $(a-h)$ and take the limit as $h \rightarrow 0$.

---

## Right-Hand Limit

Let $f(x)$ be a given function and let $x$ approach to **a** from the right. Then, the limit of $f(x)$, as $x$ approaches to **a** from the right, is denoted by $\lim _{x \rightarrow a^{+}} f(x)$.

### Method for Finding $\lim _{x \rightarrow a^{+}} f(x)$

Replace $x$ by $(a+h)$ and take the limit as $h \rightarrow 0$.

---

## Limit of a Function

We say that $\lim _{x \rightarrow a} f(x)$ exists only when $\lim _{x \rightarrow a^{-}} f(x)=\lim _{x \rightarrow a^{+}} f(x)$ and this common value is known as $\lim _{x \rightarrow a} f(x)$.

---

## Solved Examples

### Example 1:

Let $f(x)=\begin{cases} 2x+3, & x \leq 0 \\ 3(x+1), & x>0 \end{cases}$. Find (i) $\lim _{x \rightarrow 0} f(x)$ and (ii) $\lim _{x \rightarrow 1} f(x)$.

#### Solution:

(i) We have
$$
\lim _{x \rightarrow 0^{+}} f(x)=\lim _{h \rightarrow 0} 3(0+h+1)=\lim _{h \rightarrow 0} 3(h+1)=3 .
$$
$$
\lim _{x \rightarrow 0^{-}} f(x)=\lim _{h \rightarrow 0} 2(0-h)+3=\lim _{h \rightarrow 0} (-2h+3)=3 .
$$
$$
\therefore \lim _{x \rightarrow 0^{+}} f(x)=\lim _{x \rightarrow 0^{-}} f(x)=3 .
$$
Hence, $\lim _{x \rightarrow 0} f(x)=3$.

(ii) We have
$$
\lim _{x \rightarrow 1^{+}} f(x)=\lim _{h \rightarrow 0} f(1+h)=\lim _{h \rightarrow 0} 3(1+h+1)=\lim _{h \rightarrow 0} 3(2+h)=6 .
$$
$$
\lim _{x \rightarrow 1^{-}} f(x)=\lim _{h \rightarrow 0} f(1-h)=\lim _{h \rightarrow 0} 3(1-h+1)=\lim _{h \rightarrow 0} 3(2-h)=6 .
$$
$$
\therefore \lim _{x \rightarrow 1^{+}} f(x)=\lim _{x \rightarrow 1^{-}} f(x)=6 .
$$
Hence, $\lim _{x \rightarrow 1} f(x)=6$.

---

### Example 2:

Let $f(x)=\begin{cases} x^{2}-1, & x \leq 1 \\ -x^{2}-1, & x>1 \end{cases}$. Find $\lim _{x \rightarrow 1} f(x)$.

#### Solution:

We have
$$
\lim _{x \rightarrow 1^{+}} f(x)=\lim _{h \rightarrow 0} f(1+h)=\lim _{h \rightarrow 0}\left\{-(1+h)^{2}-1\right\}=\lim _{h \rightarrow 0}\left(-2-h^{2}-2 h\right)=-2 .
$$
$$
\lim _{x \rightarrow 1^{-}} f(x)=\lim _{h \rightarrow 0} f(1-h)=\lim _{h \rightarrow 0}\left\{(1-h)^{2}-1\right\} = \lim _{h \rightarrow 0}\left(1+h^{2}-2 h-1\right) = \lim _{h \rightarrow 0}\left(h^{2}-2 h\right)=0 .
$$
$$
\therefore \lim _{x \rightarrow 1^{+}} f(x) \neq \lim _{x \rightarrow 1^{-}} f(x) .
$$
Hence, $\lim _{x \rightarrow 1} f(x)$ does not exist.

---

### Example 3:

Let $f(x)=\begin{cases} \frac{|x|}{x}, & x \neq 0 \\ 0, & x=0 \end{cases}$. Find $\lim _{x \rightarrow 0} f(x)$.

#### Solution:

We have
$$
\lim _{x \rightarrow 0^{+}} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0} \frac{|h|}{h}=\lim _{h \rightarrow 0} \frac{h}{h}=1 .
$$
$$
\lim _{x \rightarrow 0^{-}} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)=\lim _{h \rightarrow 0} \frac{|-h|}{-h}=\lim _{h \rightarrow 0} \frac{h}{-h}=-1 .
$$
Thus, $\lim _{x \rightarrow 0^{+}} f(x) \neq \lim _{x \rightarrow 0^{-}} f(x)$.
Hence, $\lim _{x \rightarrow 0} f(x)$ does not exist.

> **Caution**: Here note that $\frac{h}{h}=1$, since $h \neq 0$.

---

### Example 4:

Let $f(x)= \begin{cases}a+b x, & x<1 \\ 4, & x=1 \\ b-a x, & x>1 \end{cases}$. If $\lim _{x \rightarrow 1} f(x)=f(1)$, find the values of $a$ and $b$.

#### Solution:

Clearly, $f(1)=4$.
$$
\lim _{x \rightarrow 1^{+}} f(x)=\lim _{h \rightarrow 0} f(1+h)=\lim _{h \rightarrow 0}\{b-a(1+h)\}=(b-a) .
$$
$$
\lim _{x \rightarrow 1^{-}} f(x)=\lim _{h \rightarrow 0} f(1-h)=\lim _{h \rightarrow 0}\{a+b(1-h)\}=(a+b) .
$$
Now, $\lim _{x \rightarrow 1} f(x)=f(1)=4$
$$
\Rightarrow \lim _{x \rightarrow 1^{+}} f(x)=\lim _{x \rightarrow 1^{-}} f(x)=f(1)=4
$$
$$
\Rightarrow (b-a)=(a+b)=4
$$
$$
\Rightarrow b-a=4 \text{ and } b+a=4 \Rightarrow a=0, b=4 .
$$
Hence, $a=0$ and $b=4$.

---

### Example 5:

Let $f(x)= \begin{cases}|x|+1, & x<0 \\ 0, & x=0 \\ |x|-1, & x>0\end{cases}$. For what value(s) of $a$ does $\lim _{x \rightarrow a} f(x)$ exists?

#### Solution:

**Case 1: When $a<0$.**
In this case, we have
$$
\lim _{x \rightarrow a^{+}} f(x) =\lim _{h \rightarrow 0} f(a+h)=\lim _{h \rightarrow 0}\{|a+h|+1\}=|a|+1 .
$$
$$
\lim _{x \rightarrow a^{-}} f(x) = \lim _{h \rightarrow 0} f(a-h)=\lim _{h \rightarrow 0}\{|a-h|+1\}=|a|+1 .
$$
$$
\therefore \lim _{x \rightarrow a^{+}} f(x) = \lim _{x \rightarrow a^{-}} f(x)=|a|+1 .
$$
So, in this case, $\lim _{x \rightarrow a} f(x)$ exists.

**Case 2: When $a>0$.**
In this case, we have
$$
\lim _{x \rightarrow a^{+}} f(x) = \lim _{h \rightarrow 0} f(a+h)=\lim _{h \rightarrow 0}\{|a+h|-1\}=|a|-1 .
$$
$$
\lim _{x \rightarrow a^{-}} f(x) = \lim _{h \rightarrow 0} f(a-h)=\lim _{h \rightarrow 0}\{|a-h|-1\}=|a|-1 .
$$
$$
\therefore \lim _{x \rightarrow a^{+}} f(x) = \lim _{x \rightarrow a^{-}} f(x)=|a|-1 .
$$
So, in this case, $\lim _{x \rightarrow a} f(x)$ exists.

**Case 3: When $a=0$.**
In this case, we have
$$
\lim _{x \rightarrow 0^{+}} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0}\{|h|-1\}=-1 .
$$
$$
\lim _{x \rightarrow 0^{-}} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0}\{|-h|+1\}=1 .
$$
Thus, $\lim _{x \rightarrow 0^{+}} f(x) \neq \lim _{x \rightarrow 0^{-}} f(x)$.
Hence, $\lim _{x \rightarrow 0} f(x)$ does not exist.
Thus, $\lim _{x \rightarrow a} f(x)$ exists only when $a \neq 0$.

---

### Example 6:

Let $f(x)=\begin{cases} m x^{2}+n, & x<0 \\ n x+m, & 0 \leq x \leq 1 \\ n x^{3}+m, & x>1 \end{cases}$. For what values of integers $m$ and $n$, $\lim _{x \rightarrow 0} f(x)$ and $\lim _{x \rightarrow 1} f(x)$ both exist?

#### Solution:

We have
$$
\lim _{x \rightarrow 0^{+}} f(x)= \lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0}(n h+m)=m
$$
$$
\lim _{x \rightarrow 0^{-}} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h) = \lim _{h \rightarrow 0}\left\{m(-h)^{2}+n\right\} = \lim _{h \rightarrow 0}\left(m h^{2}+n\right)=n
$$
$\therefore \lim _{x \rightarrow 0} f(x)$ exists only when $m=n$.

Now,
$$
\lim _{x \rightarrow 1^{+}} f(x)=\lim _{h \rightarrow 0} f(1+h)=\lim _{h \rightarrow 0}\left\{n(1+h)^{3}+m\right\} = \lim _{h \rightarrow 0}\left\{n\left(1+h^{3}+3 h+3 h^{2}\right)+m\right\}=(n+m) .
$$
And,
$$
\lim _{x \rightarrow 1^{-}} f(x)=\lim _{h \rightarrow 0} f(1-h)=\lim _{h \rightarrow 0}\{n(1-h)+m\}=(n+m) .
$$
$\therefore \lim _{x \rightarrow 1} f(x)=(n+m)$.
Hence, $\lim _{x \rightarrow 0} f(x)$ and $\lim _{x \rightarrow 1} f(x)$ both exist only when $m=n$.

---

### Example 7:

Let $a_{1}, a_{2}, \ldots, a_{n}$ be fixed real numbers and let $f(x)=\left(x-a_{1}\right)\left(x-a_{2}\right)\left(x-a_{3}\right) \ldots\left(x-a_{n}\right)$. Find $\lim _{x \rightarrow a_{1}} f(x)$. If $a \neq a_{1}, a_{2}, \ldots, a_{n}$, compute $\lim _{x \rightarrow a} f(x)$.

#### Solution:

We have
$$
\begin{aligned}
\lim _{x \rightarrow a_{1}^{+}} f(x) &= \lim _{h \rightarrow 0} f\left(a_{1}+h\right) \\
&= \lim _{h \rightarrow 0}\left\{\left(a_{1}+h-a_{1}\right)\left(a_{1}+h-a_{2}\right) \ldots \left(a_{1}+h-a_{n}\right)\right\} \\
&= \lim _{h \rightarrow 0}\left\{h\left(a_{1}+h-a_{2}\right)\left(a_{1}+h-a_{3}\right) \ldots \left(a_{1}+h-a_{n}\right)\right\} \\
&= \left\{0 \times\left(a_{1}-a_{2}\right) \times\left(a_{1}-a_{3}\right) \times \ldots \times\left(a_{1}-a_{n}\right)\right\} = 0.
\end{aligned}
$$
$$
\begin{aligned}
\lim _{x \rightarrow a_{1}^{-}} f(x) &= \lim _{h \rightarrow 0} f\left(a_{1}-h\right) \\
&= \lim _{h \rightarrow 0}\left\{\left(a_{1}-h-a_{1}\right)\left(a_{1}-h-a_{2}\right) \ldots \left(a_{1}-h-a_{n}\right)\right\} \\
&= \lim _{h \rightarrow 0}\left\{(-h)\left(a_{1}-h-a_{2}\right)\left(a_{1}-h-a_{3}\right) \ldots \left(a_{1}-h-a_{n}\right)\right\} \\
&= \left\{0 \times\left(a_{1}-a_{2}\right) \times\left(a_{1}-a_{3}\right) \times \ldots \times\left(a_{1}-a_{n}\right)\right\}=0.
\end{aligned}
$$
$$
\therefore \lim _{x \rightarrow a_{1}^{+}} f(x) = \lim _{x \rightarrow a_{1}^{-}} f(x)=0 .
$$
Hence, $\lim _{x \rightarrow a_{1}} f(x)=0$.

For any $a \neq a_{1}, a_{2}, \ldots, a_{n}$, we have
$$
\lim _{x \rightarrow a} f(x) = \lim _{x \rightarrow a}\left\{\left(x-a_{1}\right)\left(x-a_{2}\right)\left(x-a_{3}\right) \ldots\left(x-a_{n}\right)\right\} = \left(a-a_{1}\right)\left(a-a_{2}\right)\left(a-a_{3}\right) \ldots\left(a-a_{n}\right).
$$

---

### Example 8:

Let $f(x)=[x]$ = greatest integer less than or equal to $x$. For any integer $k$, show that $\lim _{x \rightarrow k} f(x)$ does not exist.

#### Solution:

We have
$$
\lim _{x \rightarrow k^{+}} f(x)=\lim _{h \rightarrow 0} f(k+h)=\lim _{h \rightarrow 0}[k+h]=\lim _{h \rightarrow 0} k=k \quad (\because[k+h]=k)
$$
and
$$
\lim _{x \rightarrow k^{-}} f(x)=\lim _{h \rightarrow 0} f(k-h)=\lim _{h \rightarrow 0}[k-h]=\lim _{h \rightarrow 0}(k-1)=(k-1) \quad (\because[k-h]=k-1)
$$
Thus, $\lim _{x \rightarrow k^{+}} f(x) \neq \lim _{x \rightarrow k^{-}} f(x)$.
Hence, $\lim _{x \rightarrow k} f(x)$ does not exist.

---

### Example 9:

If $f$ is an odd function and $\lim _{x \rightarrow 0} f(x)$ exists then prove that this limit must be 0.

#### Solution:

Let $f$ be an odd function and let $\lim _{x \rightarrow 0} f(x)$ exist. Then
$$
\lim _{x \rightarrow 0^{+}} f(x)=\lim _{x \rightarrow 0^{-}} f(x)
$$
$$
\Rightarrow \lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(0-h)
$$
$$
\Rightarrow \lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0} f(-h)=-\lim _{h \rightarrow 0} f(h) \quad (\because f \text{ being odd, } f(-h)=-f(h))
$$
$$
\Rightarrow 2 \lim _{h \rightarrow 0} f(h)=0 \Rightarrow \lim _{h \rightarrow 0} f(h)=0
$$
Hence, $\lim _{x \rightarrow 0} f(x)=0$.

---

### Example 10:

If $f$ is an even function, prove that $\lim _{x \rightarrow 0^{-}} f(x)=\lim _{x \rightarrow 0^{+}} f(x)$.

#### Solution:

Let $f$ be an even function. Then,
$$
\lim _{x \rightarrow 0^{-}} f(x) = \lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)
$$
$$
= \lim _{h \rightarrow 0} f(h) \quad (\because f \text{ being even, } f(-h)=f(h))
$$
$$
= \lim _{h \rightarrow 0} f(0+h)=\lim _{x \rightarrow 0^{+}} f(x) .
$$
Hence, $\lim _{x \rightarrow 0^{-}} f(x)=\lim _{x \rightarrow 0^{+}} f(x)$.

---

### Example 11:

Show that $\lim _{x \rightarrow 0}\left(\frac{e^{1 / x}-1}{e^{1 / x}+1}\right)$ does not exist.

#### Solution:

Let $f(x)=\left(\frac{e^{1 / x}-1}{e^{1 / x}+1}\right)$. Then,
$$
\lim _{x \rightarrow 0^{+}} f(x) = \lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h) = \lim _{h \rightarrow 0}\left(\frac{e^{1 / h}-1}{e^{1 / h}+1}\right)=\lim _{h \rightarrow 0}\left(\frac{1-\frac{1}{e^{1 / h}}}{1+\frac{1}{e^{1 / h}}}\right)=\left(\frac{1-0}{1+0}\right)=1 .
$$
$$
\lim _{x \rightarrow 0^{-}} f(x) = \lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h) = \lim _{h \rightarrow 0}\left(\frac{e^{-1 / h}-1}{e^{-1 / h}+1}\right)=\lim _{h \rightarrow 0}\left(\frac{\frac{1}{e^{1 / h}}-1}{\frac{1}{e^{1 / h}}+1}\right)=\left(\frac{0-1}{0+1}\right)=-1 .
$$
Thus, $\lim _{x \rightarrow 0^{+}} f(x) \neq \lim _{x \rightarrow 0^{-}} f(x)$.
Hence, $\lim _{x \rightarrow 0} f(x)$ does not exist.

---

### Example 12:

Show that $\lim _{x \rightarrow 0} \frac{x}{|x|}$ does not exist.

#### Solution:

Let $f(x)=\frac{x}{|x|}$. Then,
$$
\lim _{x \rightarrow 0^{+}} f(x)=\lim _{h \rightarrow 0} f(0+h)=\lim _{h \rightarrow 0} f(h)=\lim _{h \rightarrow 0} \frac{h}{|h|}=\lim _{h \rightarrow 0} \frac{h}{h}=1 .
$$
$$
\lim _{x \rightarrow 0^{-}} f(x)=\lim _{h \rightarrow 0} f(0-h)=\lim _{h \rightarrow 0} f(-h)=\lim _{h \rightarrow 0} \frac{-h}{|-h|}=\lim _{h \rightarrow 0} \frac{-h}{h}=-1 .
$$
$$
\therefore \lim _{x \rightarrow 0^{+}} f(x) \neq \lim _{x \rightarrow 0^{-}} f(x) .
$$
Hence, $\lim _{x \rightarrow 0} f(x)$ does not exist.

---

