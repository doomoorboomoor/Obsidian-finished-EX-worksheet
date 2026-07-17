## Problems Based on Domains and Ranges of Real Functions

---

## Solved Examples

### Example 1:

Find the domain and the range of the real function, $f(x)=\frac{1}{x+3}$.

#### Solution:

We have, $f(x)=\frac{1}{(x+3)}$.

Clearly, $f(x)$ is defined for all real values of $x$ except that at which $x+3=0$, i.e., $x=-3$.
$\therefore$ **dom($f$) = $R-\{-3\}$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{1}{x+3} & \Rightarrow x+3=\frac{1}{y} \\
& \Rightarrow x=\left(\frac{1}{y}-3\right) \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ assumes real values for all real values of $y$ except $y=0$.
$\therefore$ **range($f$) = $R-\{0\}$**.

Hence, **dom($f$) = $R-\{-3\}$** and **range($f$) = $R-\{0\}$**.

---

### Example 2:

Find the domain and the range of the real function, $f(x)=\frac{x-3}{x-5}$.

#### Solution:

We have, $f(x)=\frac{x-3}{x-5}$.

Clearly, $f(x)$ is defined for all real values of $x$ except that at which $x-5=0$, i.e., $x=5$.
$\therefore$ **dom($f$) = $R-\{5\}$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{x-3}{x-5} & \Rightarrow xy-5y=x-3 \\
& \Rightarrow x(y-1)=5y-3 \Rightarrow x=\frac{5y-3}{y-1} \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ is not defined when $y-1=0$, i.e., when $y=1$.
$\therefore$ **range($f$) = $R-\{1\}$**.

Hence, **dom($f$) = $R-\{5\}$** and **range($f$) = $R-\{1\}$**.

---

### Example 3:

Find the domain and the range of the real function, $f(x)=\frac{x^{2}+1}{x^{2}-1}$.

#### Solution:

We have, $f(x)=\frac{x^{2}+1}{x^{2}-1}$.

Clearly, $f(x)$ is defined for all real values of $x$ except those for which $x^{2}-1=0$, i.e., $x= \pm 1$.
$\therefore$ **dom($f$) = $R-\{-1,1\}$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{x^{2}+1}{x^{2}-1} & \Rightarrow x^{2}y-y=x^{2}+1 \Rightarrow x^{2}(y-1)=(y+1) \\
& \Rightarrow x^{2}=\frac{y+1}{y-1} \Rightarrow x= \pm \sqrt{\frac{y+1}{y-1}} \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ is not defined when $y-1=0$ or when $\frac{y+1}{y-1}<0$.

Now, $y-1=0 \Rightarrow y=1$.

And $\frac{y+1}{y-1}<0 \Rightarrow (y+1>0$ and $y-1<0)$ or $(y+1<0$ and $y-1>0)$

$$
\begin{align*}
& \Rightarrow(y>-1 \text{ and } y<1) \text{ or } (y<-1 \text{ and } y>1) \\
& \Rightarrow -1<y<1 \tag{iii}
\end{align*}
$$

[$\because y<-1$ and $y>1$ is not possible]

Thus, $x$ is not defined when $-1<y \leq 1$. [using (ii) and (iii)]
$\therefore$ **range($f$) = $R-(-1,1]$**.

Hence, **dom($f$) = $R-\{-1,1\}$** and **range($f$) = $R-(-1,1]$**.

---

### Example 4:

Find the domain of the real-valued function: $f(x)=\frac{x^{2}-x+1}{x^{2}-5 x+4}$.

#### Solution:

We have, $f(x)=\frac{x^{2}-x+1}{x^{2}-5 x+4}$.

Clearly, $f(x)$ is defined for all real values of $x$ except those at which $x^{2}-5 x+4=0$.

But, $x^{2}-5 x+4=0 \Rightarrow (x-1)(x-4)=0 \Rightarrow x=1$ or $x=4$.
$\therefore$ **dom($f$) = $R-\{1,4\}$**.

---

### Example 5:

Find the domain of each of the following real functions:
(i) $f(x)=\sqrt{x-3}$
(ii) $g(x)=\sqrt{4-x^{2}}$
(iii) $h(x)=\frac{1}{\sqrt{1-x}}$

#### Solution:

(i) We have, $f(x)=\sqrt{x-3}$.
Clearly, $f(x)$ is defined for all real values of $x$ for which $x-3 \geq 0$, i.e., $x \geq 3$.
$\therefore$ **dom($f$) = $[3, \infty)$**.

(ii) We have, $g(x)=\sqrt{4-x^{2}}$.
Clearly, $g(x)$ is defined for all real values of $x$ for which $(4-x^{2}) \geq 0$.

But, $(4-x^{2}) \geq 0 \Rightarrow -(4-x^{2}) \leq 0$
$\Rightarrow x^{2}-4 \leq 0 \Rightarrow (x+2)(x-2) \leq 0$
$\Rightarrow -2 \leq x \leq 2 \Rightarrow x \in [-2,2]$.

$\therefore$ **dom($g$) = $[-2,2]$**.

(iii) We have, $h(x)=\frac{1}{\sqrt{1-x}}$.
Clearly, $h(x)$ is defined for all real values of $x$ for which $(1-x)>0$.
But, $1-x>0 \Rightarrow 1>x \Rightarrow x<1 \Rightarrow x \in (-\infty, 1)$.

$\therefore$ **dom($h$) = $(-\infty, 1)$**.

---

### Example 6:

Find the domain of the function, $f(x)=\sqrt{3-x}+\frac{1}{\sqrt{x^{2}-1}}$.

#### Solution:

We have, $f(x)=\sqrt{3-x}+\frac{1}{\sqrt{x^{2}-1}}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $3-x \geq 0$ and $x^{2}-1>0$.

$\Rightarrow x-3 \leq 0$ and $(x+1)(x-1)>0$
$\Rightarrow x \leq 3$ and ($x<-1$ or $x>1$)
$\Rightarrow (x \leq 3$ and $x<-1$) or ($x \leq 3$ and $x>1$)
$\Rightarrow (x<-1)$ or $(1<x \leq 3)$
$\Rightarrow x \in (-\infty,-1) \cup (1,3]$.

$\therefore$ **dom($f$) = $(-\infty,-1) \cup (1,3]$**.

---

### Example 7:

Find the range of each of the following functions:
(i) $f(x)=2-3 x, x \in R$ and $x>0$
(ii) $g(x)=x^{2}+2, x \in R$

#### Solution:

(i) We have, $f(x)=2-3 x$, where $x \in R$ and $x>0$.
Now, $x>0 \Rightarrow 3 x>0 \Rightarrow -3 x<0$
$\Rightarrow -3 x+2<0+2 \Rightarrow 2-3 x<2$
$\Rightarrow f(x)<2 \Rightarrow f(x) \in (-\infty, 2)$.

Hence, **range($f$) = $(-\infty, 2)$**.

(ii) We have, $g(x)=x^{2}+2, x \in R$.
Now, $x \in R \Rightarrow x^{2} \geq 0 \Rightarrow x^{2}+2 \geq 0+2$
$\Rightarrow x^{2}+2 \geq 2 \Rightarrow g(x) \geq 2$
$\Rightarrow g(x) \in [2, \infty)$.

Hence, **range($g$) = $[2, \infty)$**.

---

### Example 8:

Find the domain and the range of the function, $f(x)=\frac{x-2}{x-3}$.

#### Solution:

We have, $f(x)=\frac{x-2}{x-3}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $x-3 \neq 0$, i.e., $x \neq 3$.
$\therefore$ **dom($f$) = $R-\{3\}$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{x-2}{x-3} & \Rightarrow xy-3y=x-2 \\
& \Rightarrow x(y-1)=3y-2 \\
& \Rightarrow x=\frac{3y-2}{y-1} \tag{i}
\end{align*}
$$

It follows from (i) that $x$ assumes real values for all $y$ except that for which $y-1=0$, i.e., $y=1$.
$\therefore$ **range($f$) = $R-\{1\}$**.

Hence, **dom($f$) = $R-\{3\}$** and **range($f$) = $R-\{1\}$**.

---

### Example 9:

Find the domain and the range of the real function, $f(x)=\sqrt{x-3}$.

#### Solution:

We have, $f(x)=\sqrt{x-3}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $x-3 \geq 0$, i.e., $x \geq 3$.
$\therefore$ **dom($f$) = $[3, \infty)$**.

Also, $x \geq 3 \Rightarrow f(x)=\sqrt{x-3} \geq 0$.
$\therefore$ **range($f$) = $[0, \infty)$**.

Hence, **dom($f$) = $[3, \infty)$** and **range($f$) = $[0, \infty)$**.

---

### Example 10:

Find the domain and the range of each of the functions given below.
(i) $f(x)=|x-1|$
(ii) $g(x)=-|x|$

#### Solution:

(i) We have, $f(x)=|x-1|$.
Clearly, $f(x)$ is defined for all $x \in R$. So, **dom($f$) = $R$**.
For all $x \in R$, we have $|x-1| \geq 0 \Rightarrow f(x) \geq 0$.
$\therefore$ **range($f$) = $[0, \infty)$**.
Hence, **dom($f$) = $R$** and **range($f$) = $[0, \infty)$**.

(ii) We have, $g(x)=-|x|$.
Clearly, $g(x)$ is defined for all $x \in R$. So, **dom($g$) = $R$**.
For all $x \in R$, we have $|x| \geq 0 \Rightarrow -|x| \leq 0 \Rightarrow g(x) \leq 0$.
$\therefore$ **range($g$) = $(-\infty, 0]$**.
Hence, **dom($g$) = $R$** and **range($g$) = $(-\infty, 0]$**.

---

### Example 11:

Find the domain and the range of the real function, $f(x)=\frac{1}{\sqrt{x-2}}$.

#### Solution:

We have, $f(x)=\frac{1}{\sqrt{x-2}}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $x-2>0$, i.e., $x>2$.
$\therefore$ **dom($f$) = $(2, \infty)$**.

For any real value of $x>2$, we have
$x>2 \Rightarrow x-2>0 \Rightarrow \sqrt{x-2}>0$
$\Rightarrow \frac{1}{\sqrt{x-2}}>0 \Rightarrow f(x)>0$.
$\therefore$ **range($f$) = $(0, \infty)$**.
Hence, **dom($f$) = $(2, \infty)$** and **range($f$) = $(0, \infty)$**.

---

### Example 12:

Find the domain and the range of the real function, $f(x)=\sqrt{9-x^{2}}$.

#### Solution:

We have, $f(x)=\sqrt{9-x^{2}}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $(9-x^{2}) \geq 0$.

And, $9-x^{2} \geq 0 \Rightarrow x^{2}-9 \leq 0 \Rightarrow (x-3)(x+3) \leq 0$
$\Rightarrow -3 \leq x \leq 3 \Rightarrow x \in [-3,3]$.
$\therefore$ **dom($f$) = $[-3,3]$**.

Let $y=f(x)$. Then,
$y=\sqrt{9-x^{2}} \Rightarrow y^{2}=9-x^{2} \Rightarrow x^{2}=9-y^{2} \Rightarrow x=\sqrt{9-y^{2}}$.

Clearly, $x$ will take real values only when $9-y^{2} \geq 0$.
Now, $9-y^{2} \geq 0 \Rightarrow y^{2}-9 \leq 0 \Rightarrow (y+3)(y-3) \leq 0$
$\Rightarrow -3 \leq y \leq 3 \Rightarrow y \in [-3,3]$.

$\Rightarrow y \in [0,3]$ {$\because y=\sqrt{9-x^{2}} \geq 0$ for all $x \in [-3,3]$}.
$\therefore$ **range($f$) = $[0,3]$**.
Hence, **dom($f$) = $[-3,3]$** and **range($f$) = $[0,3]$**.

---

### Example 13:

Find the domain and the range of the real function, $f(x)=\frac{x}{(1+x^{2})}$.

#### Solution:

We have, $f(x)=\frac{x}{(1+x^{2})}$.

Clearly, $f(x)$ is defined for all $x \in R$. So, **dom($f$) = $R$**.
Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{x}{(1+x^{2})} & \Rightarrow x^{2}y-x+y=0 \\
& \Rightarrow x=\frac{1 \pm \sqrt{1-4y^{2}}}{2y} \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ will take real values, when
$(1-4y^{2}) \geq 0$ and $y \neq 0$
$\Rightarrow (4y^{2}-1) \leq 0$ and $y \neq 0$
$\Rightarrow (2y+1)(2y-1) \leq 0$ and $y \neq 0$
$\Rightarrow (y+\frac{1}{2})(y-\frac{1}{2}) \leq 0$ and $y \neq 0$
$\Rightarrow -\frac{1}{2} \leq y \leq \frac{1}{2}$ and $y \neq 0$
$\Rightarrow y \in [-\frac{1}{2}, \frac{1}{2}]-\{0\}$.

Also, $x=0 \Rightarrow y=0$.
$\therefore$ **range($f$) = $[-\frac{1}{2}, \frac{1}{2}]$**.
Hence, **dom($f$) = $R$** and **range($f$) = $[-\frac{1}{2}, \frac{1}{2}]$**.

---

### Example 14:

Find the domain and the range of the real function, $f(x)=\frac{3}{(2-x^{2})}$.

#### Solution:

We have, $f(x)=\frac{3}{(2-x^{2})}$.

Clearly, $f(x)$ is defined for all real values of $x$ except those for which $2-x^{2}=0$, i.e., $x= \pm \sqrt{2}$.
$\therefore$ **dom($f$) = $R-\{-\sqrt{2}, \sqrt{2}\}$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{3}{(2-x^{2})} & \Rightarrow 2y-x^{2}y=3 \Rightarrow x^{2}y=2y-3 \\
& \Rightarrow x^{2}=\frac{2y-3}{y} \Rightarrow x= \pm \sqrt{\frac{2y-3}{y}} \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ will take real values only when $\frac{2y-3}{y} \geq 0$.
Now, $\frac{2y-3}{y} \geq 0 \Leftrightarrow (2y-3 \leq 0$ and $y<0)$ or $(2y-3 \geq 0$ and $y>0)$
$\Leftrightarrow (y \leq \frac{3}{2}$ and $y<0)$ or $(y \geq \frac{3}{2}$ and $y>0)$
$\Leftrightarrow (y<0)$ or $(y \geq \frac{3}{2})$
$\Leftrightarrow y \in (-\infty, 0)$ or $y \in [\frac{3}{2}, \infty)$
$\Leftrightarrow y \in (-\infty, 0) \cup [\frac{3}{2}, \infty)$.

$\therefore$ **range($f$) = $(-\infty, 0) \cup [\frac{3}{2}, \infty)$**.
Hence, **dom($f$) = $R-\{-\sqrt{2}, \sqrt{2}\}$** and **range($f$) = $(-\infty, 0) \cup [\frac{3}{2}, \infty)$**.

---

### Example 15:

Find the domain and the range of the real function $f=\left\{\left(x, \frac{x^{2}}{x^{2}+1}\right): x \in R\right\}$ from $R$ into $R$.

#### Solution:

We have, $f(x)=\frac{x^{2}}{x^{2}+1}, x \in R$.

Clearly, $x^{2}+1 \neq 0$ for any real value of $x$.
$\therefore$ $f(x)$ is defined for all real values of $x$.
$\therefore$ **dom($f$) = $R$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{x^{2}}{(x^{2}+1)} & \Rightarrow x^{2}y+y=x^{2} \Rightarrow x^{2}(1-y)=y \\
& \Rightarrow x^{2}=\frac{y}{1-y} \Rightarrow x= \pm \sqrt{\frac{y}{(1-y)}} \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ will take real values only when $\frac{y}{(1-y)} \geq 0$.
Now, $\frac{y}{(1-y)} \geq 0 \Leftrightarrow (y \leq 0$ and $1-y<0)$ or $(y \geq 0$ and $1-y>0)$
$\Leftrightarrow (y \leq 0$ and $y>1)$ or $(y \geq 0$ and $y<1)$
$\Leftrightarrow (y \geq 0$ and $y<1)$ [$\because y \leq 0$ and $y>1$ is not possible]
$\Leftrightarrow y \in [0,1)$.

$\therefore$ **range($f$) = $[0,1)$**.
Hence, **dom($f$) = $R$** and **range($f$) = $[0,1)$**.

---

### Example 16:

Find the domain and the range of the function $f=\left\{\left(x, \frac{1}{1-x^{2}}\right): x \in R \text{ and } x \neq \pm 1\right\}$.

#### Solution:

We have, $f(x)=\frac{1}{(1-x^{2})}, x \in R$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $(1-x^{2}) \neq 0$.
Now, $(1-x^{2})=0 \Rightarrow (1+x)(1-x)=0 \Rightarrow x=-1$ or $x=+1$.
Thus, $f(x)$ is defined for all values of $x \in R$ except $\pm 1$.
$\therefore$ **dom($f$) = $R-\{-1,1\}$**.

Let $y=f(x)$. Then,

$$
\begin{align*}
y=\frac{1}{1-x^{2}} & \Rightarrow y-x^{2}y=1 \Rightarrow x^{2}y=y-1 \\
& \Rightarrow x^{2}=\frac{y-1}{y} \Rightarrow x= \pm \sqrt{\frac{y-1}{y}} \tag{i}
\end{align*}
$$

It is clear from (i) that $x$ will take real values only when $\frac{y-1}{y} \geq 0$.
Now, $\frac{y-1}{y} \geq 0 \Leftrightarrow (y-1 \leq 0$ and $y<0)$ or $(y-1 \geq 0$ and $y>0)$
$\Leftrightarrow (y \leq 1$ and $y<0)$ or $(y \geq 1$ and $y>0)$
$\Leftrightarrow (y<0)$ or $(y \geq 1)$
$\Leftrightarrow y \in (-\infty, 0)$ or $[1, \infty)$.

$\therefore$ **range($f$) = $(-\infty, 0) \cup [1, \infty)$**.
Hence, **dom($f$) = $R-\{-1,1\}$** and **range($f$) = $(-\infty, 0) \cup [1, \infty)$**.

---

### Example 17:

Find the domain and the range of the real function, $f(x)=\frac{x^{2}-25}{x-5}$.

#### Solution:

We have, $f(x)=\frac{x^{2}-25}{x-5}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $x-5 \neq 0$, i.e., $x \neq 5$.
$\therefore$ **dom($f$) = $R-\{5\}$**.

Let $y=f(x)$. Then,
$y=\frac{x^{2}-25}{x-5} \Rightarrow y=x+5$, when $x-5 \neq 0$
$\Rightarrow y=x+5$, when $x \neq 5$
$\Rightarrow y \neq 5+5 \Rightarrow y \neq 10$.

Then, $y$ can be assigned any real value except 10.
$\therefore$ **range($f$) = $R-\{10\}$**.
Hence, **dom($f$) = $R-\{5\}$** and **range($f$) = $R-\{10\}$**.

---

### Example 18:

Find the domain and the range of the real function, $f(x)=\frac{3-x}{x-3}$.

#### Solution:

We have, $f(x)=\frac{3-x}{x-3}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $x-3 \neq 0$, i.e., $x \neq 3$.
$\therefore$ **dom($f$) = $R-\{3\}$**.

Let $y=f(x)$. Then,
$y=\frac{3-x}{x-3} \Rightarrow y=-1$, when $x-3 \neq 0$
$\Rightarrow y=-1$, when $x \neq 3$.
$\therefore$ **range($f$) = $\{-1\}$**.
Hence, **dom($f$) = $R-\{3\}$** and **range($f$) = $\{-1\}$**.

---

### Example 19:

Find the domain and the range of the real function, $f(x)=\frac{|x-3|}{(x-3)}$.

#### Solution:

We have, $f(x)=\frac{|x-3|}{(x-3)}$.

Clearly, $f(x)$ is defined for all real values of $x$ for which $x-3 \neq 0$, i.e., $x \neq 3$.
$\therefore$ **dom($f$) = $R-\{3\}$**.

Now, when $x \neq 3$, we have
$f(x)= \begin{cases}1, & \text{when } x-3>0 & \{\because |x-3|=(x-3)\} \\ -1, & \text{when } x-3<0 & \{\because |x-3|=-(x-3)\} \end{cases}$
$\therefore$ **range($f$) = $\{1,-1\}$**.
Hence, **dom($f$) = $R-\{3\}$** and **range($f$) = $\{1,-1\}$**.

---

### Example 20:

Find the domain of the real function, $f(x)=\frac{1}{\sqrt{x+|x|}}$.

#### Solution:

We have, $f(x)=\frac{1}{\sqrt{x+|x|}}$.

Now, $|x|= \begin{cases} x, & \text{when } x \geq 0 \\ -x, & \text{when } x<0 \end{cases}$
$\Rightarrow x+|x|= \begin{cases} x+x, & \text{when } x \geq 0 \\ x-x, & \text{when } x<0 \end{cases}$
$\Rightarrow x+|x|= \begin{cases} 2x, & \text{when } x \geq 0 \\ 0, & \text{when } x<0 \end{cases}$
$\Rightarrow x+|x|>0$, when $x>0$.
$\Rightarrow f(x)=\frac{1}{\sqrt{x+|x|}}$ assumes real values only when $x+|x|>0$ and this happens only when $x>0$.
$\therefore$ **dom($f$) = $(0, \infty)$**.

---

### Example 21:

Show that $f(x)=\frac{1}{\sqrt{x-|x|}}$ is not defined for any $x \in R$. How will you define dom($f$) and range($f$)?

#### Solution:

We have, $f(x)=\frac{1}{\sqrt{x-|x|}}$.

Now, $|x|= \begin{cases} x, & \text{when } x \geq 0 \\ -x, & \text{when } x<0 \end{cases}$
$\Rightarrow x-|x|= \begin{cases} x-x, & \text{when } x \geq 0 \\ x+x, & \text{when } x<0 \end{cases}$
$\Rightarrow x-|x|= \begin{cases} 0, & \text{when } x \geq 0 \\ 2x, & \text{when } x<0 \end{cases}$
$\Rightarrow x-|x| \leq 0$ for all $x \in R$.
$\Rightarrow \frac{1}{\sqrt{x-|x|}}$ is not defined for any $x \in R$.
$\therefore$ **dom($f$) = $\phi$** and **range($f$) = $\phi$**.

---

## Greatest Integer Function (Step Function)

The function $f: R \rightarrow R: f(x)=[x]$, where $[x]$ denotes the greatest integer less than or equal to $x$, is called the **Greatest Integer Function**.

**Examples:** $[3.65]=3, [3.02]=3, [5]=5, [-2.6]=-3, [-4]=-4$.

**Note:** $x-[x]=0$ for $x \in Z$ and $0<x-[x]<1$ for $x \in R-Z$.

---

### Example 22:

Find the domain and the range of the real function, $f(x)=\frac{1}{\sqrt{x+[x]}}$.

#### Solution:

We have, $f(x)=\frac{1}{\sqrt{x+[x]}}$.

We know that
$\begin{cases} x+[x]>0 & \text{for all } x>0 \\ x+[x]=0, & \text{when } x=0 \\ x+[x]<0 & \text{for all } x<0 \end{cases}$

$\therefore f(x)=\frac{1}{\sqrt{x+[x]}}$ is defined only when $x+[x]>0$ and this happens only when $x>0$.
$\therefore$ **dom($f$) = $(0, \infty)$**.

Let $y=f(x)$. Then,

$$
y=\frac{1}{\sqrt{x+[x]}} \Rightarrow \sqrt{x+[x]}=\frac{1}{y} \tag{i}
$$

Now, $x>0 \Rightarrow x+[x]>0 \Rightarrow \sqrt{x+[x]}>0 \Rightarrow \frac{1}{y}>0 \Rightarrow y>0$.
$\therefore$ **range($f$) = $(0, \infty)$**.
Hence, **dom($f$) = $(0, \infty)$** and **range($f$) = $(0, \infty)$**.

---

### Example 23:

Find the domain and the range of the real function, $f(x)=\frac{1}{\sqrt{x-[x]}}$.

#### Solution:

We have, $f(x)=\frac{1}{\sqrt{x-[x]}}$.

We know that
$0 \leq x-[x]<1$ for all $x \in R$ and $x-[x]=0$ for all $x \in Z$.
$\therefore 0<x-[x]<1$ for all $x \in R-Z$
$\Rightarrow f(x)=\frac{1}{\sqrt{x-[x]}}$ exists for all $x \in R-Z$.
$\Rightarrow$ **dom($f$) = $R-Z$**.

Also, $0<x-[x]<1$ for all $x \in R-Z$
$\Rightarrow 0<\sqrt{x-[x]}<1$ for all $x \in R-Z$
$\Rightarrow 1<\frac{1}{\sqrt{x-[x]}}<\infty$ for all $x \in R-Z$
$\Rightarrow 1<f(x)<\infty$ for all $x \in R-Z$.
$\Rightarrow$ **range($f$) = $(1, \infty)$**.
Hence, **dom($f$) = $R-Z$** and **range($f$) = $(1, \infty)$**.

---

