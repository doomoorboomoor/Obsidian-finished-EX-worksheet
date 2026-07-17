## 15. Integration Using Partial Fractions

## Partial Fractions

### Rational Functions

If $f(x)$ and $g(x)$ are polynomial functions such that $g(x) \neq 0$ then $\frac{f(x)}{g(x)}$ is called a **rational function**.

If degree $f(x)<$ degree $g(x)$ then $\frac{f(x)}{g(x)}$ is called a **proper rational function**.

If degree $f(x) \geq$ degree $g(x)$ then $\frac{f(x)}{g(x)}$ is called an **improper rational function**.

If $\frac{f(x)}{g(x)}$ is an improper rational function then by dividing $f(x)$ by $g(x)$, we can express $\frac{f(x)}{g(x)}$ as the sum of a polynomial and a proper rational function.

---

### Partial Fractions

Any proper rational function $\frac{p(x)}{q(x)}$ can be expressed as the sum of rational functions, each having a simplest factor $q(x)$. Each such fraction is known as a **partial fraction** and the process of obtaining them is called the **decomposition** or **resolving** of the given function into partial fractions.

---

### Method

We first resolve the denominator of the given fraction into simplest factors. On the basis of these factors, we obtain the corresponding partial fraction as per rules given below:

| Factor in the denominator | Corresponding partial fraction |
| :--- | :--- |
| (i) $(x-a)$ | $\frac{A}{(x-a)}$ |
| (ii) $(x-b)^{2}$ | $\frac{A}{(x-b)}+\frac{B}{(x-b)^{2}}$ |
| (iii) $(x-c)^{3}$ | $\frac{A}{(x-c)}+\frac{B}{(x-c)^{2}}+\frac{C}{(x-c)^{3}}$ |
| (iv) $\left(a x^{2}+b x+c\right)$ | $\frac{A x+B}{\left(a x^{2}+b x+c\right)}$ |

The values of $A$, $B$, $C$, etc., can be obtained as shown below.

---

## Solved Examples on Partial Fractions

### Example 1:

Resolve $\frac{2 x+3}{(x-3)(x+1)}$ into partial fractions.

#### Solution:

Let $\frac{(2 x+3)}{(x-3)(x+1)}=\frac{A}{(x-3)}+\frac{B}{(x+1)}$. Then,

$$
\frac{2 x+3}{(x-3)(x+1)}=\frac{A(x+1)+B(x-3)}{(x-3)(x+1)}
$$

or $(2 x+3) \equiv A(x+1)+B(x-3)$.

Putting $(x-3)=0$ or $x=3$ in (i), we get

$$
\begin{equation*}
A=(9 / 4) . \tag{i}
\end{equation*}
$$

Putting $(x+1)=0$ or $x=-1$ in (i), we get

$$
B=(-1 / 4) .
$$

$\therefore \quad \frac{(2 x+3)}{(x-3)(x+1)}=\frac{9}{4(x-3)}-\frac{1}{4(x+1)}$.

---

### Example 2:

Resolve $\frac{x^{3}-2 x^{2}-13 x-12}{x^{2}-3 x-10}$ into partial fractions.

#### Solution:

On dividing, we get

$$
\begin{equation*}
\frac{x^{3}-2 x^{2}-13 x-12}{x^{2}-3 x-10}=(x+1)-\frac{2}{\left(x^{2}-3 x-10\right)} . \tag{i}
\end{equation*}
$$

Let

$$
\frac{2}{\left(x^{2}-3 x-10\right)}=\frac{2}{(x-5)(x+2)}=\frac{A}{x-5}+\frac{B}{x+2}
$$

Then,

$$
\frac{2}{(x-5)(x+2)}=\frac{A(x+2)+B(x-5)}{(x-5)(x+2)}
$$

or

$$
\begin{equation*}
2 \equiv A(x+2)+B(x-5) . \tag{ii}
\end{equation*}
$$

Putting $(x-5)=0$ or $x=5$ in (ii), we get

$$
A=(2 / 7) .
$$

Putting $(x+2)=0$ or $x=-2$ in (ii), we get

$$
B=(-2 / 7) .
$$

$\therefore \quad \frac{2}{\left(x^{2}-3 x-10\right)}=\frac{2}{7(x-5)}-\frac{2}{7(x+2)}$.

Hence, $\quad \frac{x^{3}-2 x^{2}-13 x-12}{x^{2}-3 x-10}=(x+1)-\frac{2}{7(x-5)}+\frac{2}{7(x+2)}$.

---

### Example 3:

Resolve $\frac{16}{(x-2)(x+2)^{2}}$ into partial fractions.

#### Solution:

Let $\frac{16}{(x-2)(x+2)^{2}}=\frac{A}{x-2}+\frac{B}{x+2}+\frac{C}{(x+2)^{2}}$

or $\frac{16}{(x-2)(x+2)^{2}}=\frac{A(x+2)^{2}+B(x-2)(x+2)+C(x-2)}{(x-2)(x+2)^{2}}$

$$
\begin{array}{ll}
\therefore & 16 \equiv A(x+2)^{2}+B(x-2)(x+2)+C(x-2) \tag{i} \\
\text { or } & 16 \equiv(A+B) x^{2}+(4 A+C) x+(4 A-4 B-2 C) . \tag{ii}
\end{array}
$$

Putting $(x-2)=0$ or $x=2$ in (i), we get $A=1$.

Putting $(x+2)=0$ or $x=-2$ in (i), we get $C=-4$.

Comparing the coefficients of $x^{2}$ on both sides of (ii), we get

$$
A+B=0 \text { or } B=-A=-1 \text {. }
$$

Thus $A=1, B=-1$ and $C=-4$.

$$
\therefore \quad \frac{16}{(x-2)(x+2)^{2}}=\left[\frac{1}{(x-2)}-\frac{1}{(x+2)}-\frac{4}{(x+2)^{2}}\right] .
$$

---

### Example 4:

Resolve $\frac{2 x+1}{(x-1)\left(x^{2}+1\right)}$ into partial fractions.

#### Solution:

Let $\frac{2 x+1}{(x-1)\left(x^{2}+1\right)}=\frac{A}{(x-1)}+\frac{B x+C}{\left(x^{2}+1\right)}$

or $\frac{(2 x+1)}{(x-1)\left(x^{2}+1\right)}=\frac{A\left(x^{2}+1\right)+(B x+C)(x-1)}{(x-1)\left(x^{2}+1\right)}$.

$\therefore \quad 2 x+1 \equiv A\left(x^{2}+1\right)+(B x+C)(x-1)$

or

$$
\begin{equation*}
2 x+1 \equiv(A+B) x^{2}+(C-B) x+(A-C) . \tag{i}
\end{equation*}
$$

Equating the like powers of $x$ on both sides of (i), we get

$$
A+B=0, C-B=2 \text { and } A-C=1 .
$$

On solving these equations, we get

$$
\begin{gathered}
A=\frac{3}{2}, B=\frac{-3}{2} \text { and } C=\frac{1}{2} . \\
\therefore \frac{2 x+1}{(x-1)\left(x^{2}+1\right)}=\frac{3}{2(x-1)}+\frac{\left(\frac{-3}{2} x+\frac{1}{2}\right)}{x^{2}+1}=\left[\frac{3}{2(x-1)}+\frac{(1-3 x)}{2\left(x^{2}+1\right)}\right] .
\end{gathered}
$$

---

## Integration Using Partial Fractions

## Solved Examples

### Example 1:

Evaluate $\int \frac{(x-1)}{(x+1)(x-2)} d x$.
[CBSE 2001]

#### Solution:

Let $\frac{(x-1)}{(x+1)(x-2)}=\frac{A}{(x+1)}+\frac{B}{(x-2)}$.

Then, $(x-1) \equiv A(x-2)+B(x+1)$. (i)

Putting $x=-1$ in (i), we get $A=\frac{2}{3}$.

Putting $x=2$ in (i), we get $B=\frac{1}{3}$.

$$
\begin{aligned}
& \therefore \frac{(x-1)}{(x+1)(x-2)}=\frac{2}{3(x+1)}+\frac{1}{3(x-2)} \\
& \begin{aligned}
\Rightarrow \int \frac{(x-1)}{(x+1)(x-2)} d x & =\frac{2}{3} \int \frac{d x}{(x+1)}+\frac{1}{3} \int \frac{d x}{(x-2)} \\
& =\frac{2}{3} \log |x+1|+\frac{1}{3} \log |x-2|+C
\end{aligned}
\end{aligned}
$$

---

### Example 2:

Evaluate $\int \frac{\left(x^{2}+1\right)}{\left(x^{2}-5 x+6\right)} d x$.

#### Solution:

Here the integrand is not a proper rational function; on dividing $\left(x^{2}+1\right)$ by $\left(x^{2}-5 x+6\right)$, we get

$$
\frac{\left(x^{2}+1\right)}{\left(x^{2}-5 x+6\right)}=1+\frac{(5 x-5)}{\left(x^{2}-5 x+6\right)}=1+\frac{(5 x-5)}{(x-2)(x-3)}
$$

Now, let $\frac{(5 x-5)}{(x-2)(x-3)}=\frac{A}{(x-2)}+\frac{B}{(x-3)}$

$$
\begin{equation*}
\Rightarrow \frac{(5 x-5)}{(x-2)(x-3)}=\frac{A(x-3)+B(x-2)}{(x-2)(x-3)} \tag{i}
\end{equation*}
$$

$\Rightarrow(5 x-5) \equiv A(x-3)+B(x-2)$.

Putting $x=2$ on both sides of (i), we get $A=-5$.

Putting $x=3$ on both sides of (i), we get $B=10$.

$\therefore \frac{\left(x^{2}+1\right)}{\left(x^{2}-5 x+6\right)}=1-\frac{5}{(x-2)}+\frac{10}{(x-3)}$

$\Rightarrow \int \frac{\left(x^{2}+1\right)}{\left(x^{2}-5 x+6\right)} d x=\int d x-5 \int \frac{d x}{(x-2)}+10 \int \frac{d x}{(x-3)}$

$=x-5 \log |x-2|+10 \log |x-3|+C$.

---

### Example 3:

Evaluate $\int \frac{(3 x-2)}{(x+1)^{2}(x+3)} d x$.
[CBSE 2006C]

#### Solution:

Let $\frac{(3 x-2)}{(x+1)^{2}(x+3)}=\frac{A}{(x+1)}+\frac{B}{(x+1)^{2}}+\frac{C}{(x+3)}$

$\Rightarrow(3 x-2) \equiv A(x+1)(x+3)+B(x+3)+C(x+1)^{2}$. (i)

Putting $x=-3$ on both sides of (i), we get $C=\frac{-11}{4}$.

Putting $x=-1$ on both sides of (i), we get $B=\frac{-5}{2}$.

Comparing the coefficients of $x^{2}$ on both sides of (i), we get

$$
\begin{aligned}
& A+C=0 \Rightarrow A=-C=\frac{11}{4} \\
\therefore & \frac{(3 x-2)}{(x+1)^{2}(x+3)}=\frac{11}{4(x+1)}-\frac{5}{2(x+1)^{2}}-\frac{11}{4(x+3)}
\end{aligned}
$$

$$
\begin{aligned}
\Rightarrow \int \frac{(3 x-2)}{(x+1)^{2}(x+3)} d x & =\frac{11}{4} \cdot \int \frac{d x}{(x+1)}-\frac{5}{2} \cdot \int \frac{1}{(x+1)^{2}} d x-\frac{11}{4} \cdot \int \frac{d x}{(x+3)} \\
& =\frac{11}{4} \cdot \log |x+1|+\frac{5}{2(x+1)}-\frac{11}{4} \cdot \log |x+3|+C \\
& =\frac{11}{4} \cdot \log \left|\frac{x+1}{x+3}\right|+\frac{5}{2(x+1)}+C
\end{aligned}
$$

---

### Example 4:

Evaluate $\int \frac{d x}{\left(x^{3}+x^{2}+x+1\right)}$.
[CBSE 2006]

#### Solution:

We have $\frac{1}{\left(x^{3}+x^{2}+x+1\right)}=\frac{1}{x^{2}(x+1)+(x+1)}=\frac{1}{(x+1)\left(x^{2}+1\right)}$.

Let $\frac{1}{(x+1)\left(x^{2}+1\right)}=\frac{A}{(x+1)}+\frac{B x+C}{\left(x^{2}+1\right)}$

$$
\begin{equation*}
\Rightarrow 1 \equiv A\left(x^{2}+1\right)+(B x+C)(x+1) . \tag{i}
\end{equation*}
$$

Putting $x=-1$ on both sides of (i), we get $A=\frac{1}{2}$.

Comparing the coefficients of $x^{2}$ on both sides of (i), we get

$$
A+B=0 \Rightarrow B=-A=\frac{-1}{2} .
$$

Comparing the coefficients of $x$ on both sides of (i), we get

$$
\begin{aligned}
B+C=0 \Rightarrow C & =-B=\frac{1}{2} \\
\therefore \frac{1}{(x+1)\left(x^{2}+1\right)}= & \frac{1}{2(x+1)}+\frac{\frac{-1}{2} x+\frac{1}{2}}{x^{2}+1} \\
\therefore \int \frac{d x}{\left(x^{3}+x^{2}+x+1\right)} & =\int \frac{d x}{(x+1)\left(x^{2}+1\right)} \\
& =\frac{1}{2} \cdot \int \frac{d x}{(x+1)}-\frac{1}{2} \int \frac{x}{\left(x^{2}+1\right)} d x+\frac{1}{2} \int \frac{d x}{\left(x^{2}+1\right)} \\
& =\frac{1}{2} \cdot \int \frac{d x}{(x+1)}-\frac{1}{4} \cdot \int \frac{2 x}{\left(x^{2}+1\right)} d x+\frac{1}{2} \int \frac{d x}{\left(x^{2}+1\right)} \\
& =\frac{1}{2} \log |x+1|-\frac{1}{4} \log \left|x^{2}+1\right|+\frac{1}{2} \tan ^{-1} x+C
\end{aligned}
$$

---

### Example 5:

Evaluate $\int \frac{x^{4}}{(x-1)\left(x^{2}+1\right)} d x$.

#### Solution:

$\frac{x^{4}}{(x-1)\left(x^{2}+1\right)}=\frac{x^{4}}{\left(x^{3}-x^{2}+x-1\right)}=(x+1)+\frac{1}{\left(x^{3}-x^{2}+x-1\right)}$

$\Rightarrow \frac{x^{4}}{(x-1)\left(x^{2}+1\right)}=(x+1)+\frac{1}{(x-1)\left(x^{2}+1\right)}$.

Let $\frac{1}{(x-1)\left(x^{2}+1\right)}=\frac{A}{(x-1)}+\frac{B x+C}{\left(x^{2}+1\right)}$. Then,

$$
\begin{equation*}
1 \equiv A\left(x^{2}+1\right)+(B x+C)(x-1) . \tag{ii}
\end{equation*}
$$

Putting $x=1$ in (ii), we get $A=\frac{1}{2}$.

Comparing the coefficients of $x^{2}$ on both sides of (ii), we get

$$
A+B=0 \Rightarrow B=-A=-\frac{1}{2} .
$$

Comparing the constant terms on both sides of (ii), we get

$$
\begin{aligned}
& \quad A-C=1 \Rightarrow C=(A-1)=\left(\frac{1}{2}-1\right)=\frac{-1}{2} \\
& \therefore \frac{1}{(x-1)\left(x^{2}+1\right)}=\frac{1}{2(x-1)}+\frac{-\frac{1}{2} x-\frac{1}{2}}{\left(x^{2}+1\right)} \\
& \therefore \frac{x^{4}}{(x-1)\left(x^{2}+1\right)}=(x+1)+\frac{1}{2(x-1)}-\frac{1}{2} \cdot \frac{(x+1)}{\left(x^{2}+1\right)} \\
& \Rightarrow \int \frac{x^{4}}{(x-1)\left(x^{2}+1\right)} d x=\int(x+1) d x+\frac{1}{2} \int \frac{d x}{(x-1)} \\
& \quad-\frac{1}{4} \cdot \int \frac{2 x}{\left(x^{2}+1\right)} d x-\frac{1}{2} \int \frac{d x}{\left(x^{2}+1\right)} \\
& \quad=\frac{x^{2}}{2}+x+\frac{1}{2} \log |x-1|-\frac{1}{4} \log \left(x^{2}+1\right)-\frac{1}{2} \tan ^{-1} x+C
\end{aligned}
$$

---

### Example 6:

Evaluate $\int \frac{(3 x+5)}{\left(x^{3}-x^{2}-x+1\right)} d x$.
[CBSE 2005C, '13C]

#### Solution:

$\quad\left(x^{3}-x^{2}-x+1\right)=x^{2}(x-1)-(x-1)=(x-1)\left(x^{2}-1\right)=(x-1)^{2}(x+1)$.

Let $\frac{3 x+5}{\left(x^{3}-x^{2}-x+1\right)}=\frac{3 x+5}{(x-1)^{2}(x+1)}=\frac{A}{(x-1)}+\frac{B}{(x-1)^{2}}+\frac{C}{(x+1)}$

$\Rightarrow(3 x+5) \equiv A(x-1)(x+1)+B(x+1)+C(x-1)^{2}$. (i)

Putting $x=1$ on both sides of (i), we get $B=4$.

Putting $x=-1$ on both sides of (i), we get $C=\frac{1}{2}$.

Comparing the coefficient of $x^{2}$ on both sides of (i), we get

$$
\begin{aligned}
& A+C=0 \Rightarrow A=-C=\frac{-1}{2} \\
\therefore & \frac{(3 x+5)}{\left(x^{3}-x^{2}-x+1\right)}=\frac{-1}{2(x-1)}+\frac{4}{(x-1)^{2}}+\frac{1}{2(x+1)}
\end{aligned}
$$

$$
\begin{aligned}
\Rightarrow \int \frac{(3 x+5)}{\left(x^{3}-x^{2}-x+1\right)} d x & =-\frac{1}{2} \int \frac{d x}{(x-1)}+4 \int \frac{d x}{(x-1)^{2}}+\frac{1}{2} \int \frac{d x}{(x+1)} \\
& =-\frac{1}{2} \log |x-1|-\frac{4}{(x-1)}+\frac{1}{2} \log |x+1|+C
\end{aligned}
$$

---

### Example 7:

Evaluate $\int \frac{\left(x^{3}-1\right)}{\left(x^{3}+x\right)} d x$.

#### Solution:

We have

$$
\begin{align*}
\frac{\left(x^{3}-1\right)}{\left(x^{3}+x\right)} & =1-\frac{(x+1)}{\left(x^{3}+x\right)} \quad[\text { on dividing }] \\
& =1-\frac{(x+1)}{x\left(x^{2}+1\right)} \tag{i}
\end{align*}
$$

Let $\frac{(x+1)}{x\left(x^{2}+1\right)}=\frac{A}{x}+\frac{B x+C}{\left(x^{2}+1\right)}$.

Then, $(x+1) \equiv A\left(x^{2}+1\right)+(B x+C) x$. (ii)

Putting $x=0$ in (ii), we get $A=1$.

Comparing the coefficients of $x$ in (ii), we get $C=1$.

Comparing the coefficients of $x^{2}$ in (ii), we get

$$
\begin{aligned}
& \qquad A+B=0 \Rightarrow B=-A=-1 \\
& \therefore \quad A=1, B=-1 \text { and } C=1 \\
& \text { Thus, } \frac{(x+1)}{x\left(x^{2}+1\right)}=\frac{1}{x}+\frac{(1-x)}{\left(x^{2}+1\right)} \\
& \Rightarrow \int \frac{\left(x^{3}-1\right)}{\left(x^{3}+x\right)} d x=\int d x-\int \frac{(x+1)}{x\left(x^{2}+1\right)} d x \\
& =x-\left\{\int \frac{d x}{x}+\int \frac{(1-x)}{\left(x^{2}+1\right)} d x\right\} \\
& =x-\int \frac{d x}{x}-\int \frac{d x}{\left(x^{2}+1\right)}+\frac{1}{2} \int \frac{2 x}{\left(x^{2}+1\right)} d x \\
& =x-\log |x|-\tan ^{-1} x+\frac{1}{2} \log \left(x^{2}+1\right)+C
\end{aligned}
$$

---

### Example 8:

Evaluate $\int \frac{\cos x}{(1-\sin x)(2-\sin x)} d x$.
[CBSE 2006C]

#### Solution:

Putting $\sin x=t$ and $\cos x d x=d t$, we get

$$
\begin{align*}
& \quad I=\frac{\cos x}{(1-\sin x)(2-\sin x)} d x=\int \frac{d t}{(1-t)(2-t)} \\
& \text { Let } \frac{1}{(1-t)(2-t)}=\frac{A}{(1-t)}+\frac{B}{(2-t)} \\
& \Rightarrow 1 \equiv A(2-t)+B(1-t) \tag{i}
\end{align*}
$$

Putting $t=1$ in (i), we get $A=1$.

Putting $t=2$ in (i), we get $B=-1$.

$$
\begin{aligned}
& \therefore \frac{1}{(1-t)(2-t)}=\frac{1}{(1-t)}-\frac{1}{(2-t)} \\
& \Rightarrow \int \frac{\cos x}{(1-\sin x)(2-\sin x)} d x \\
& =\int \frac{d t}{(1-t)(2-t)} \\
& =\int\left\{\frac{1}{(1-t)}-\frac{1}{(2-t)}\right\} d t \\
& =\int \frac{d t}{(1-t)}-\int \frac{d t}{(2-t)} \\
& =-\log |1-t|+\log |2-t|+C \\
& =\log \left|\frac{2-t}{1-t}\right|+C=\log \left|\frac{2-\sin x}{1-\sin x}\right|+C
\end{aligned}
$$

---

### Example 9:

Evaluate $\int \frac{d x}{x\left\{6(\log x)^{2}+7 \log x+2\right\}}$.

#### Solution:

Putting $\log x=t$ and $\frac{1}{x} d x=d t$, we get

$$
I=\int \frac{d x}{x\left\{6(\log x)^{2}+7 \log x+2\right\}}=\int \frac{d t}{\left(6 t^{2}+7 t+2\right)}=\int \frac{d t}{(2 t+1)(3 t+2)}
$$

Let $\frac{1}{(2 t+1)(3 t+2)}=\frac{A}{(2 t+1)}+\frac{B}{(3 t+2)}$.

Then, $1 \equiv A(3 t+2)+B(2 t+1)$. (i)

Putting $t=-\frac{1}{2}$ in (i), we get $A=2$.

Putting $t=\frac{-2}{3}$ in (i), we get $B=-3$.

$\therefore \frac{1}{(2 t+1)(3 t+2)}=\frac{2}{(2 t+1)}-\frac{3}{(3 t+2)}$

$\Rightarrow I=\int \frac{d t}{(2 t+1)(3 t+2)}$

$=\int \frac{2 d t}{(2 t+1)}-\int \frac{3 d t}{(3 t+2)}$

$=\log |2 t+1|-\log |3 t+2|+C$

$=\log \left|\frac{2 t+1}{3 t+2}\right|+C$

$=\log \left|\frac{2 \log x+1}{3 \log x+2}\right|+C$.

---

### Example 10:

Evaluate $\int \frac{x^{2}}{\left(1+x^{3}\right)\left(2+x^{3}\right)} d x$.
[CBSE 2003C]

#### Solution:

Putting $x^{3}=t$ and $x^{2} d x=\frac{1}{3} d t$, we get

$$
I=\int \frac{x^{2}}{\left(1+x^{3}\right)\left(2+x^{3}\right)} d x=\frac{1}{3} \cdot \int \frac{d t}{(1+t)(2+t)}
$$

Let $\frac{1}{(1+t)(2+t)}=\frac{A}{(1+t)}+\frac{B}{(2+t)}$. Then,

$$
\begin{equation*}
1 \equiv A(2+t)+B(1+t) \tag{i}
\end{equation*}
$$

Putting $t=-1$ in (i), we get $A=1$.

Putting $t=-2$ in (i), we get $B=-1$.

$$
\begin{aligned}
\therefore \quad & \frac{1}{(1+t)(2+t)}=\frac{1}{(1+t)}-\frac{1}{(2+t)} \\
\Rightarrow \quad I & =\int \frac{d t}{(1+t)(2+t)}=\int \frac{d t}{(1+t)}-\int \frac{d t}{(2+t)} \\
& \quad=\log |1+t|-\log |2+t|+C \\
& \quad=\log \left|\frac{1+t}{2+t}\right|+C \\
& \quad=\log \left|\frac{1+x^{3}}{2+x^{3}}\right|+C
\end{aligned}
$$

---

### Example 11:

Evaluate $\int \frac{d x}{\left(e^{x}-1\right)}$.
[CBSE 2003]

#### Solution:

Putting $e^{x}=t$ and $e^{x} d x=d t$, i.e., $d x=\frac{1}{t} d t$, we get

$$
I=\int \frac{d x}{\left(e^{x}-1\right)}=\int \frac{d t}{t(t-1)}
$$

Let $\frac{1}{t(t-1)}=\frac{A}{t}+\frac{B}{(t-1)}$.

Then, $1 \equiv A(t-1)+B t$. (i)

Putting $t=0$ in (i), we get $A=-1$.

Putting $t=1$ in (i), we get $B=1$.

$\therefore \frac{1}{t(t-1)}=\frac{-1}{t}+\frac{1}{(t-1)}$.

Hence, $I=\int \frac{d x}{\left(e^{x}-1\right)}$

$$
\begin{aligned}
& =\int \frac{d t}{t(t-1)}=\int \frac{-1}{t} d t+\int \frac{1}{(t-1)} d t \\
& =-\log |t|+\log |t-1|+C
\end{aligned}
$$

$$
\begin{aligned}
& =\log \left|\frac{t-1}{t}\right|+C \\
& =\log \left|\frac{e^{x}-1}{e^{x}}\right|+C
\end{aligned}
$$

---

### Example 12:

Evaluate $\int \frac{d x}{x\left(x^{n}+1\right)}$.

#### Solution:

Putting $x^{n}=t$, we get $n x^{n-1} d x=d t$.

$$
\begin{align*}
& \therefore \quad \frac{n x^{n}}{x} d x=d t \Rightarrow \frac{1}{x} d x=\frac{1}{n t} d t \quad \text { (note). } \\
& \therefore \int \frac{d x}{x\left(x^{n}+1\right)}=\int \frac{d t}{n t(t+1)}=\frac{1}{n} \cdot \int \frac{d t}{t(t+1)} \tag{i}
\end{align*}
$$

Let $\frac{1}{t(t+1)}=\frac{A}{t}+\frac{B}{(t+1)}$.

Then, $1 \equiv A(t+1)+B t$. (i)

Putting $t=0$ in (i), we get $A=1$.

Putting $t=-1$ in (i), we get $B=-1$.

$$
\begin{aligned}
& \therefore \frac{1}{t(t+1)}=\left\{\frac{1}{t}-\frac{1}{(t+1)}\right\} \\
& \begin{aligned}
\Rightarrow \int \frac{d x}{x\left(x^{n}+1\right)} & =\frac{1}{n} \int \frac{d t}{t(t+1)} \\
& =\frac{1}{n}\left[\int \frac{1}{t} d t-\int \frac{1}{(t+1)} d t\right] \\
& =\frac{1}{n} \cdot\{\log |t|-\log |t+1|\}+C \\
& =\frac{1}{n} \cdot \log \left|\frac{t}{t+1}\right|+C \\
& =\frac{1}{n} \log \left|\frac{x^{n}}{x^{n}+1}\right|+C
\end{aligned}
\end{aligned}
$$

---

### Example 13:

Evaluate $\int \frac{d x}{x\left(x^{5}+3\right)}$.
[CBSE 2013]

#### Solution:

Let $I=\int \frac{d x}{x\left(x^{5}+3\right)}=\int \frac{x^{4}}{x^{5}\left(x^{5}+3\right)} d x$. (i)

Putting $x^{5}=t$ and $5 x^{4} d x=d t$ in (i), we get

$$
\begin{equation*}
I=\frac{1}{5} \int \frac{d t}{t(t+3)} \tag{ii}
\end{equation*}
$$

Let $\frac{1}{t(t+3)}=\frac{A}{t}+\frac{B}{t+3}$. (iii)

Then, $1 \equiv A(t+3)+B t$.

Putting $t=0$ on both sides of (iii), we get $A=\frac{1}{3}$.

Putting $t=-3$ on both sides of (iii), we get $B=\frac{-1}{3}$.

$$
\begin{aligned}
\therefore \quad & \frac{1}{t(t+3)}=\frac{1}{3 t}-\frac{1}{3(t+3)} \\
\Rightarrow \quad I & =\frac{1}{5} \int\left\{\frac{1}{3 t}-\frac{1}{3(t+3)}\right\} d t \\
& =\frac{1}{15} \int \frac{1}{t} d t-\frac{1}{15} \int \frac{1}{(t+3)} d t \\
& =\frac{1}{15} \log |t|-\frac{1}{15} \log |t+3|+C \\
& =\frac{1}{15} \log \left|x^{5}\right|-\frac{1}{15} \log \left|x^{5}+3\right|+C
\end{aligned}
$$

---

### Example 14:

Evaluate $\int \frac{x^{2}}{\left(x^{2}+4\right)\left(x^{2}+9\right)} d x$.
[CBSE 2013]

#### Solution:

Let $\frac{x^{2}}{\left(x^{2}+4\right)\left(x^{2}+9\right)}=\frac{y}{(y+4)(y+9)}$, where $x^{2}=y$.

Let $\frac{y}{(y+4)(y+9)}=\frac{A}{(y+4)}+\frac{B}{(y+9)}$.

Then, $y \equiv A(y+9)+B(y+4)$. (i)

Putting $y=-4$ on both sides of (i), we get $A=\frac{-4}{5}$.

Putting $y=-9$ on both sides of (i), we get $B=\frac{9}{5}$.

$$
\begin{aligned}
& \therefore \quad \frac{y}{(y+4)(y+9)}=\frac{-4}{5(y+4)}+\frac{9}{5(y+9)} \\
& \begin{aligned}
\Rightarrow \quad \frac{x^{2}}{\left(x^{2}+4\right)\left(x^{2}+9\right)}= & \frac{-4}{5\left(x^{2}+4\right)}+\frac{9}{5\left(x^{2}+9\right)} \\
\Rightarrow \int \frac{x^{2}}{\left(x^{2}+4\right)\left(x^{2}+9\right)} d x & =\frac{-4}{5} \int \frac{d x}{\left(x^{2}+4\right)}+\frac{9}{5} \int \frac{d x}{\left(x^{2}+9\right)} \\
& =\left(\frac{-4}{5} \times \frac{1}{2}\right) \tan ^{-1} \frac{x}{2}+\left(\frac{9}{5} \times \frac{1}{3}\right) \tan ^{-1} \frac{x}{3}+C \\
& =\frac{-2}{5} \tan ^{-1} \frac{x}{2}+\frac{3}{5} \tan ^{-1} \frac{x}{3}+C .
\end{aligned}
\end{aligned}
$$

---

### Example 15:

Evaluate $\int \frac{(x-1)(x-2)(x-3)}{(x-4)(x-5)(x-6)} d x$.

#### Solution:

Let $\frac{(x-1)(x-2)(x-3)}{(x-4)(x-5)(x-6)}=1+\frac{A}{(x-4)}+\frac{B}{(x-5)}+\frac{C}{(x-6)}$.

Then, $(x-1)(x-2)(x-3)$

$$
\begin{align*}
\equiv(x-4)(x-5)(x-6)+A(x-5)(x-6) & +B(x-4)(x-6) \\
& +C(x-4)(x-5) \tag{i}
\end{align*}
$$

Putting $x=4$ on both sides of (i), we get $A=3$.

Putting $x=5$ on both sides of (i), we get $B=-24$.

Putting $x=6$ on both sides of (i), we get $C=30$.

$$
\begin{aligned}
\therefore \quad I & =\int \frac{(x-1)(x-2)(x-3)}{(x-4)(x-5)(x-6)} d x \\
& =\int\left\{1+\frac{3}{(x-4)}-\frac{24}{(x-5)}+\frac{30}{(x-6)}\right\} d x \\
& =\int d x+3 \int \frac{d x}{(x-4)}-24 \int \frac{d x}{(x-5)}+30 \int \frac{d x}{(x-6)} \\
& =x+3 \log |x-4|-24 \log |x-5|+30 \log |x-6|+C
\end{aligned}
$$

---

### Example 16:

Evaluate $\int \frac{\left(x^{2}+1\right)\left(x^{2}+2\right)}{\left(x^{2}+3\right)\left(x^{2}+4\right)} d x$.

#### Solution:

We have

$$
\begin{aligned}
\frac{\left(x^{2}+1\right)\left(x^{2}+2\right)}{\left(x^{2}+3\right)\left(x^{2}+4\right)} & =\frac{(t+1)(t+2)}{(t+3)(t+4)}, \text { where } x^{2}=t \\
& =\frac{\left(t^{2}+3 t+2\right)}{\left(t^{2}+7 t+12\right)}=1-\frac{(4 t+10)}{(t+3)(t+4)}
\end{aligned}
$$

Let $\frac{(4 t+10)}{(t+3)(t+4)}=\frac{A}{(t+3)}+\frac{B}{(t+4)}$

$\Rightarrow(4 t+10) \equiv A(t+4)+B(t+3)$. (i)

Putting $t=-3$ in (i), we get $A=-2$.

Putting $t=-4$ in (i), we get $B=6$.

$\therefore \frac{(4 t+10)}{(t+3)(t+4)}=\frac{-2}{(t+3)}+\frac{6}{(t+4)}$. (ii)

Thus, $\frac{\left(x^{2}+1\right)\left(x^{2}+2\right)}{\left(x^{2}+3\right)\left(x^{2}+4\right)}=\frac{(t+1)(t+2)}{(t+3)(t+4)}$, where $x^{2}=t$

$$
\begin{aligned}
& =\frac{\left(t^{2}+3 t+2\right)}{\left(t^{2}+7 t+12\right)}=1-\frac{(4 t+10)}{(t+3)(t+4)} \\
& =1-\left\{\frac{-2}{(t+3)}+\frac{6}{(t+4)}\right\} \quad \text { [from (ii)] } \\
& =\left\{1+\frac{2}{(t+3)}-\frac{6}{(t+4)}\right\} \\
& =\left\{1+\frac{2}{\left(x^{2}+3\right)}-\frac{6}{\left(x^{2}+4\right)}\right\} .
\end{aligned}
$$

$$
\begin{aligned}
\therefore \int \frac{\left(x^{2}+1\right)\left(x^{2}+2\right)}{\left(x^{2}+3\right)\left(x^{2}+4\right)} d x & =\int\left\{1+\frac{2}{\left(x^{2}+3\right)}-\frac{6}{\left(x^{2}+4\right)}\right\} d x \\
& =\int d x+2 \int \frac{d x}{\left(x^{2}+3\right)}-6 \int \frac{d x}{\left(x^{2}+4\right)} \\
& =x+\frac{2}{\sqrt{3}} \tan ^{-1}\left(\frac{x}{\sqrt{3}}\right)-\frac{6}{2} \tan ^{-1}\left(\frac{x}{2}\right)+C \\
& =x+\frac{2}{\sqrt{3}} \tan ^{-1}\left(\frac{x}{\sqrt{3}}\right)-3 \tan ^{-1}\left(\frac{x}{2}\right)+C
\end{aligned}
$$

---

### Example 17:

Evaluate $\int \frac{(3 \sin \theta-2) \cos \theta}{\left(5-\cos ^{2} \theta-4 \sin \theta\right)} d \theta$.

#### Solution:

We have

$$
\begin{aligned}
I & =\int \frac{(3 \sin \theta-2) \cos \theta}{\left\{5-\left(1-\sin ^{2} \theta\right)-4 \sin \theta\right\}} d \theta \\
& =\int \frac{(3 \sin \theta-2) \cos \theta}{\left(4+\sin ^{2} \theta-4 \sin \theta\right)} d \theta \\
& =\int \frac{(3 \sin \theta-2) \cos \theta}{(\sin \theta-2)^{2}} d \theta=\int \frac{(3 t-2)}{(t-2)^{2}} d t, \text { where } \sin \theta=t
\end{aligned}
$$

Let $\frac{(3 t-2)}{(t-2)^{2}}=\frac{A}{(t-2)}+\frac{B}{(t-2)^{2}}$. Then,

$$
\begin{equation*}
(3 t-2) \equiv A(t-2)+B \tag{i}
\end{equation*}
$$

Putting $t=2$ in (i), we get $B=4$.

Comparing the coefficients of $t$ on both sides of (i), we get $A=3$.

Thus, $A=3$ and $B=4$.

$$
\begin{aligned}
& \therefore \quad \frac{(3 t-2)}{(t-2)^{2}}=\frac{3}{(t-2)}+\frac{4}{(t-2)^{2}} \\
& \Rightarrow \quad I=\int \frac{(3 t-2)}{(t-2)^{2}} d t=\int \frac{3}{(t-2)} d t+\int \frac{4}{(t-2)^{2}} d t \\
& \quad=3 \log |t-2|-\frac{4}{(t-2)}+C \\
& \quad=3 \log |\sin \theta-2|-\frac{4}{(\sin \theta-2)}+C \\
& \quad=3 \log (2-\sin \theta)+\frac{4}{(2-\sin \theta)}+C \quad[\because(2-\sin \theta)>0]
\end{aligned}
$$

---

### Example 18:

Evaluate $\int \frac{\left(\tan \theta+\tan ^{3} \theta\right)}{\left(1+\tan ^{3} \theta\right)} d \theta$.
[CBSE 2009C]

#### Solution:

We have

$$
\frac{\left(\tan \theta+\tan ^{3} \theta\right)}{\left(1+\tan ^{3} \theta\right)}=\frac{\tan \theta\left(1+\tan ^{2} \theta\right)}{\left(1+\tan ^{3} \theta\right)}=\frac{\tan \theta \sec ^{2} \theta}{\left(1+\tan ^{3} \theta\right)}
$$

$$
\begin{aligned}
\therefore \quad I & =\int \frac{\left(\tan \theta+\tan ^{3} \theta\right)}{\left(1+\tan ^{3} \theta\right)} d \theta \\
& =\int \frac{\tan \theta \sec ^{2} \theta}{\left(1+\tan ^{3} \theta\right)} d \theta \\
& =\int \frac{t}{\left(1+t^{3}\right)} d t=\int \frac{t}{(1+t)\left(1-t+t^{2}\right)} d t, \text { where } \tan \theta=t
\end{aligned}
$$

Let $\frac{t}{(1+t)\left(1-t+t^{2}\right)}=\frac{A}{(1+t)}+\frac{(B t+C)}{\left(1-t+t^{2}\right)}$. Then,

$$
\begin{equation*}
t \equiv A\left(1-t+t^{2}\right)+(B t+C)(1+t) . \tag{i}
\end{equation*}
$$

Putting $t=-1$ on both sides of (i), we get $A=\frac{-1}{3}$.

Comparing the coefficients of $t^{2}$ on both sides of (i), we get

$$
A+B=0 \Rightarrow B=-A=\frac{1}{3} .
$$

Comparing the constant terms on both sides of (i), we get

$$
\begin{aligned}
& \begin{array}{l}
A+C=0 \Rightarrow C=-A=\frac{1}{3} \\
\therefore \quad \frac{t}{(1+t)\left(1-t+t^{2}\right)}=\frac{-1}{3(1+t)}+\frac{\left(\frac{1}{3} t+\frac{1}{3}\right)}{\left(1-t+t^{2}\right)} \cdot \\
\text { Now, } I=\int \frac{t}{(1+t)\left(1-t+t^{2}\right)} d t \\
\quad=-\frac{1}{3} \int \frac{d t}{(1+t)}+\frac{1}{6} \int \frac{2 t}{\left(t^{2}-t+1\right)} d t+\frac{1}{3} \int \frac{d t}{\left(t^{2}-t+1\right)} \\
\quad=-\frac{1}{3} \int \frac{d t}{(1+t)}+\frac{1}{6} \int \frac{(2 t-1)+1}{\left(t^{2}-t+1\right)} d t+\frac{1}{3} \int \frac{d t}{\left(t^{2}-t+1\right)} \\
\quad=-\frac{1}{3} \int \frac{d t}{(1+t)}+\frac{1}{6} \int \frac{(2 t-1)}{\left(t^{2}-t+1\right)} d t+\frac{1}{2} \int \frac{d t}{\left(t^{2}-t+1\right)} \\
\quad=-\frac{1}{3} \log |1+t|+\frac{1}{6} \log \left|t^{2}-t+1\right|+\frac{1}{2} \int \frac{d t}{\left(t^{2}-t+\frac{1}{4}\right)+\frac{3}{4}} \\
\quad=-\frac{1}{3} \log |1+t|+\frac{1}{6} \log \left|t^{2}-t+1\right|+\frac{1}{2} \int \frac{d t}{(t-1 / 2)^{2}+(\sqrt{3} / 2)^{2}} \\
\quad=-\frac{1}{3} \log |1+t|+\frac{1}{6} \log \left|t^{2}-t+1\right|+\frac{1}{2} \cdot \frac{2}{\sqrt{3}} \tan ^{-1} \frac{\left(t-\frac{1}{2}\right)}{(\sqrt{3} / 2)}+C
\end{array}
\end{aligned}
$$

$$
\begin{aligned}
=-\frac{1}{3} \log |1+t|+\frac{1}{6} \log \left|t^{2}-t+1\right| & +\frac{1}{\sqrt{3}} \tan ^{-1}\left(\frac{2 t-1}{\sqrt{3}}\right)+C \\
\left.=-\frac{1}{3} \log |1+\tan \theta|+\frac{1}{6} \log \right\rvert\, \tan ^{2} \theta & -\tan \theta+1 \mid \\
& +\frac{1}{\sqrt{3}} \tan ^{-1}\left(\frac{2 \tan \theta-1}{\sqrt{3}}\right)+C .
\end{aligned}
$$

---

### Example 19:

Evaluate $\int \frac{d x}{(\sin x-\sin 2 x)}$.
[CBSE 2010]

#### Solution:

$\int \frac{d x}{(\sin x-\sin 2 x)}=\int \frac{d x}{(\sin x-2 \sin x \cos x)}$

$$
\begin{align*}
& =\int \frac{d x}{\sin x(1-2 \cos x)}=\int \frac{\sin x}{\sin ^{2} x(1-2 \cos x)} d x \\
& =\int \frac{\sin x}{\left(1-\cos ^{2} x\right)(1-2 \cos x)} d x \\
& =-\int \frac{d t}{\left(1-t^{2}\right)(1-2 t)}, \text { where } \cos x=t \\
& =\int \frac{d t}{(t-1)(t+1)(1-2 t)} . \tag{i}
\end{align*}
$$

Let

$$
\begin{equation*}
\frac{1}{(t-1)(t+1)(1-2 t)}=\frac{A}{(t-1)}+\frac{B}{(t+1)}+\frac{C}{(1-2 t)} . \tag{ii}
\end{equation*}
$$

Then, $\quad 1 \equiv A(t+1)(1-2 t)+B(t-1)(1-2 t)+C(t-1)(t+1)$.

Putting $t=1$ in (ii), we get $A=\frac{-1}{2}$.

Putting $t=-1$ in (ii), we get $B=\frac{-1}{6}$.

Putting $t=\frac{1}{2}$ in (ii), we get $C=\frac{-4}{3}$.

$$
\begin{aligned}
\therefore \quad I & =-\frac{1}{2} \int \frac{d t}{(t-1)}-\frac{1}{6} \cdot \int \frac{d t}{(t+1)}-\frac{4}{3} \cdot \int \frac{d t}{(1-2 t)} \\
& =-\frac{1}{2} \log |t-1|-\frac{1}{6} \log |t+1|+\frac{2}{3} \cdot \int \frac{-2 d t}{(1-2 t)} \\
& =-\frac{1}{2} \log |t-1|-\frac{1}{6} \log |t+1|+\frac{2}{3} \log |1-2 t|+C \\
& =-\frac{1}{2} \log |\cos x-1|-\frac{1}{6} \log |\cos x+1|+\frac{2}{3} \log |1-2 \cos x|+C .
\end{aligned}
$$

---

### Example 20:

Evaluate $\int \frac{(1-\cos x)}{\cos x(1+\cos x)} d x$.

#### Solution:

Let $\frac{(1-\cos x)}{\cos x(1+\cos x)}=\frac{(1-t)}{t(1+t)}=\frac{A}{t}+\frac{B}{(1+t)}$, where $t=\cos x$.

Then, $\quad(1-t) \equiv A(1+t)+B t$.

Putting $t=0$ in this identity, we get $A=1$.

Putting $t=-1$ in the identity, we get $B=-2$.

$$
\begin{aligned}
& \therefore \\
& \text { or } \quad \begin{aligned}
\frac{(1-t)}{t(1+t)} & =\frac{1}{t}-\frac{2}{1+t} \\
\therefore \int \frac{(1-\cos x)}{\cos x(1+\cos x)} & =\frac{1}{\cos x}-\frac{2}{(1+\cos x)} \\
\therefore \int \frac{(1-\cos x)}{\cos x(1+\cos x)} d x & =\int \frac{d x}{\cos x}-2 \int \frac{d x}{(1+\cos x)} \\
& =\int \sec x d x-\int \sec ^{2} \frac{x}{2} d x \\
& =\log |\sec x+\tan x|-2 \tan \frac{x}{2}+C
\end{aligned}
\end{aligned}
$$

---

### Example 21:

Evaluate $\int \frac{\left(x^{2}+1\right)}{(x+1)^{2}} d x$.
[CBSE 2006]

#### Solution:

On dividing $\left(x^{2}+1\right)$ by $\left(x^{2}+2 x+1\right)$, we get

$$
\frac{\left(x^{2}+1\right)}{(x+1)^{2}}=\left\{1-\frac{2 x}{(x+1)^{2}}\right\} .
$$

Let $\frac{2 x}{(x+1)^{2}}=\frac{A}{(x+1)}+\frac{B}{(x+1)^{2}}$

$$
\begin{equation*}
\Rightarrow 2 x \equiv A(x+1)+B . \tag{i}
\end{equation*}
$$

On equating the coefficients of $x$, we get $A=2$.

On equating constant terms, we get $A+B=0 \Rightarrow B=-A=-2$.

$$
\begin{aligned}
& \therefore \quad \frac{2 x}{(x+1)^{2}}=\frac{2}{(x+1)}-\frac{2}{(x+1)^{2}} \\
& \therefore \quad I=\int\left\{1-\frac{2 x}{(x+1)^{2}}\right\} \\
& \quad=\int\left\{1-\frac{2}{(x+1)}+\frac{2}{(x+1)^{2}}\right\} d x \\
& \quad=x-2 \log |x+1|-\frac{2}{(x+1)}+C
\end{aligned}
$$