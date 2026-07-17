## 4. Maxima and Minima

**Absolute Maximum Value of a Function:** A function $f(x)$ is said to have the greatest value or **absolute maximum value** at a point '$a$' in its domain if $f(x) \leq f(a)$ for all $x$ in the domain of $f(x)$.

In this case, '$a$' is called the **point of maximum**.

**Absolute Minimum Value of a Function:** A function $f(x)$ is said to have the smallest value or **absolute minimum value** at a point '$a$' in its domain if $f(a) \leq f(x)$ for all $x$ in the domain of $f(x)$.

The point $a$ in this case, is called the **point of minimum**.

**Examples**
(i) Consider $f(x)=\sin x$ on the interval $[0, \pi]$.
Clearly, the greatest value of the function, i.e., the absolute maximum, is $f(\pi / 2)=1$.
Also, the smallest value of the function, i.e., the absolute minimum, is $f(0)=f(\pi)=0$.

(ii) Consider $f(x)=x^{2}$ for all $x \in R$.
It is clear that the smallest value of the function, i.e., the absolute minimum, is $0$.
But, we can say nothing about the greatest value of the function. In other words, we can say that the absolute maximum does not exist.

(iii) Consider $f(x)=x^{3}$ for all $x \in R$.
Here, we observe that as the value of $x$ increases, the value of the function increases, and as $x$ decreases, the value of $f(x)$ decreases.
But, the function has neither a greatest value nor a least value.
Thus, the function has neither an absolute maximum nor an absolute minimum.

(iv) Consider $f(x)=-(x-1)^{2}+5$ for all $x \in R$.
For this function, we obtain the absolute maximum when its negative part is $0$, i.e, when $(x-1)^{2}$ is $0$. So, the greatest value of the function is $5$.
Clearly, it does not have a least value.

### Example: 1

Without using the derivative, find the maximum or minimum values, if any, of the function $f(x)=4 x^{2}-4 x+7$ for all $x \in R$.

#### Solution:

We have $f(x)=4 x^{2}-4 x+7=(2 x-1)^{2}+6$.
Clearly, $(2 x-1)^{2}$ is non-negative for all $x \in R$.
The least value of $(2 x-1)^{2}$ is $0$.
So, the least value of the function is $6$.
Clearly, this happens when $2 x-1=0$, i.e., $x=(1 / 2)$.
Thus, $x=(1 / 2)$ is a point of absolute minimum. However, $f(x)$ does not have an absolute maximum.

---

### Example: 2

Find the maximum or minimum values, if any, of the following functions, without using the derivatives:
(i) $f(x)=|x+2|$
(ii) $f(x)=-|x+1|+3$
(iii) $f(x)=|\sin (4 x+3)|$
(iv) $f(x)=\sin (\sin x)$

#### Solution:

(i) Clearly, $|x+2|$ is non-negative for all $x \in R$.
The least value of $|x+2|$ is $0$.
So, the minimum value of the function is $0$.
Clearly, $f(x)=|x+2|$ does not have a maximum value.

(ii) The value of $f(x)=-|x+1|+3$ is maximum when its negative part has a value $0$. Thus, the maximum value of $f(x)$ is $3$. Clearly, there is no minimum value of $f(x)$.

(iii) The maximum value of $|\sin \theta|$ is $1$, so the maximum value of $|\sin (4 x+3)|$ is $1$. Also, the value of $|\sin (4 x+3)|$ is non-negative. So, the minimum value of $|\sin (4 x+3)|$ is $0$.

(iv) $-1 \leq \sin x \leq 1$
$$
\begin{gathered}
\Rightarrow \sin (-1) \leq \sin (\sin x) \leq \sin 1 \\
\{\because \sin x \text { is increasing on }[-1,1]\} \\
\Rightarrow-\sin 1 \leq \sin (\sin x) \leq \sin 1 .
\end{gathered}
$$
This shows that the maximum value of $f(x)$ is $\sin 1$ and the minimum value is $-\sin 1$.

---

## Local Maxima and Local Minima

Here, our main interest lies in finding the maximum and minimum values of a function in a small interval rather than considering it for the whole of the domain. So, we shall deal with the topics of local maxima and local minima.

**Local Maximum Value of a Function:** We say that $c$ is a point of **local maximum** of a function $f(x)$ if there is an open interval $I$ containing $c$ such that $f(x)<f(c)$ for all $x \in I$.

Also, in this case, $f(c)$ is called a **local maximum value** of $f(x)$.

**Local Minimum Value of a Function:** We say that $c$ is a point of **local minimum** of a function $f(x)$ if there is an open interval $I$ containing $c$ such that $f(c)<f(x)$ for all $x \in I$.

---

## Behaviour of $f'(x)$ at Local Maxima and Local Minima

### Case I: When $c$ is a point of local maxima

In this case, $f(x)$ is increasing for values of $x$ slightly less than $c$; it ceases to increase at $x=c$ and then decreases.
$\therefore$ for small positive values of $h$, we have

$$
f^{\prime}(x)>0 \text { on }[c-h, c]
$$

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Calculus/Applications-of-Derivatives/class-12-Ch-11-E-BooK-001.jpg)

and, $f^{\prime}(x)<0$ on $[c, c+h]$.
Thus, $f^{\prime}(x)$ changes sign from *positive to negative* as $x$ increases through $c$.

### Case II: When $c$ is a point of local minima

In this case $f(x)$ is decreasing for values of $x$ slightly less than $c$; it ceases to decrease at $x=c$ and then increases for values of $x$ slightly greater than $c$.
$\therefore$ for small positive values of $h$, we have

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Calculus/Applications-of-Derivatives/class-12-Ch-11-E-BooK-002.jpg)

$$
\begin{aligned}
& \qquad f^{\prime}(x)<0 \text { on }[c-h, c] \\
& \text { and, } f^{\prime}(x)>0 \text { on }[c, c+h] \text { . } \\
& \text { Thus, } f^{\prime}(x) \text { changes sign from negative to positive as } x \text { increases } \\
& \text { through } c \text { . }
\end{aligned}
$$

**Extremum Values:** The maximum or minimum value of a function is called an **extreme** or **extremum value** of the function.

### Theorem

If $f^{\prime}(x)$ exists on an interval $[a, b]$ and $f(x)$ has a maximum or minimum value at $x=c \in ]a, b[$ then $f^{\prime}(c)=0$.

**Proof:** The proof is beyond the scope of this book.

**Stationary Points:** The points at which $f^{\prime}(c)=0$ are known as **stationary points** or **turning points**.

### Remarks

(i) A function can have at the most one absolute maximum and at the most one absolute minimum.

(ii) A function may have more than one local maximum and more than one local minimum.

(iii) A local minimum may be greater than a local maximum.

(iv) Local maximums and local minimums occur alternately.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-12/Calculus/Differential-Calculus/Applications-of-Derivatives/class-12-Ch-11-E-BooK-003.jpg)

In the given figure, $A$ and $C$ are the points of local maxima, while $B$ and $D$ are the points of local minima.

Clearly, the local minimum at $D$ is greater than the local maximum at $A$.

---

## Tests for Finding Local Extremum Values

We must remember that
- (i) $c$ is a point of local maximum if $f^{\prime}(c)=0$ and $f^{\prime}(x)$ *changes sign from positive to negative* as $x$ increases through $c$.
- (ii) $c$ is a point of local minimum if $f^{\prime}(c)=0$ and $f^{\prime}(x)$ *changes sign from negative to positive* as $x$ increases through $c$.

---

## First-Derivative Test

### Working Rule for Finding Extremum Values

In order to find the extremum values of a given function $f(x)$ by using the first-derivative test, we proceed according to the following steps.

1.  Find $f^{\prime}(x)$.
2.  Solve $f^{\prime}(x)=0$. Let its roots be $a, b, c$, etc. Then, these are the candidates for maxima or minima.
3.  We test the function at each one of these values. Let us take $x=c$.
4.  Determine the sign of $f^{\prime}(x)$ for values of $x$ slightly less than $c$ and for values of $x$ slightly greater than $c$.

### Conclusion

- (i) If $f^{\prime}(x)$ *changes sign from positive to negative* as $x$ increases through $c$ then $x=c$ is a point of maximum.
- (ii) If $f^{\prime}(x)$ *changes sign from negative to positive* as $x$ increases through $c$ then $x=c$ is a point of minimum.
- (iii) If $f^{\prime}(x)$ does not change sign as $x$ increases through $c$, we say that $x$ is neither a point of maximum nor a point of minimum.
In this case, $x=c$ is called a **point of inflexion**.

Similarly, we may deal with the other roots of $f^{\prime}(x)=0$ and examine them for maxima or minima.

---

## Solved Examples

### Example: 1

Find the local maxima or local minima, if any, of
(i) $f(x)=\frac{1}{\left(x^{2}+2\right)}$
(ii) $f(x)=\left(x^{3}-3 x\right)$

In each case, find the local maximum or the local minimum values, as the case may be.

#### Solution:

(i) $f(x)=\frac{1}{\left(x^{2}+2\right)} \Rightarrow f^{\prime}(x)=\frac{-2 x}{\left(x^{2}+2\right)^{2}}$.

For a local maxima or minima, we have $f^{\prime}(x)=0$.
$\therefore \quad f^{\prime}(x)=0 \Rightarrow \frac{-2 x}{\left(x^{2}+2\right)^{2}}=0 \Rightarrow x=0$.
Now, when $x$ is slightly less than $0$, i.e., when $x$ is negative, then $f^{\prime}(x)=\frac{-2 x}{\left(x^{2}+2\right)^{2}}$ is positive.
When $x$ is slightly greater than $0$ then $f^{\prime}(x)=\frac{-2 x}{\left(x^{2}+2\right)^{2}}<0$.
Thus, $f^{\prime}(x)$ *changes sign from positive to negative*.
So, $x=0$ is a point of local maximum.
And, local maximum value is $f(0)=\frac{1}{\left(0^{2}+2\right)}=\frac{1}{2}$.

(ii) $f(x)=\left(x^{3}-3 x\right) \Rightarrow f^{\prime}(x)=\left(3 x^{2}-3\right)$.

Now, for a maximum or a minimum, we have $f^{\prime}(x)=0$.
Now, $f^{\prime}(x)=0 \Rightarrow 3 x^{2}-3=0$
$$
\Rightarrow 3(x-1)(x+1)=0 \Rightarrow x=1 \text { or } x=-1 .
$$
Thus, $x=1$ and $x=-1$ are the candidates for local maxima or local minima.

**Consider $x=1$.**
We know that $f^{\prime}(x)=3\left(x^{2}-1\right)$.
When $x$ is slightly less than $1$ then $x^{2}$ is slightly less than $1$ and therefore, $3\left(x^{2}-1\right)$ is negative.
Again, when $x$ is slightly more than $1$ then $x^{2}$ is slightly more than $1$ and therefore, $3\left(x^{2}-1\right)$ is positive.
Thus, $f^{\prime}(x)$ *changes values from negative to positive* as $x$ increases through $1$.
So, $x=1$ is a point of local minimum.
Local minimum value $=f(1)=\left(1^{3}-3 \times 1\right)=-2$.

**Consider $x=-1$.**
When $x$ is slightly less than $-1$ then $x^{2}$ is slightly more than $1$. So, $3\left(x^{2}-1\right)$ is positive.
Again, when $x$ is slightly more than $-1$ then $x^{2}$ is slightly less than $1$. So, $3\left(x^{2}-1\right)$ is negative.
Thus, $f^{\prime}(x)$ *changes sign from positive to negative* as $x$ increases through $-1$.
So, $x=-1$ is a point of local maximum.
Local maximum value $=f(-1)=(-1)^{3}-3 \times(-1)=2$.

---

### Example: 2

Find the local maxima or local minima of $f(x)=x^{3}-6 x^{2}+9 x+15$. Also, find the local maximum or local minimum values as the case may be.

#### Solution:

Here, $f(x)=x^{3}-6 x^{2}+9 x+15 \Rightarrow f^{\prime}(x)=3 x^{2}-12 x+9$.
For a local maxima or minima, we must have $f^{\prime}(x)=0$.
Now, $f^{\prime}(x)=0 \Rightarrow 3\left(x^{2}-4 x+3\right)=0$
$$
\Rightarrow 3(x-3)(x-1)=0 \Rightarrow x=3 \text { or } x=1 .
$$
**Case I: When $x=3$**
In this case, when $x$ is slightly less than $3$ then $f^{\prime}(x)=3(x-3)(x-1)$ is negative and when $x$ is slightly more than $3$ then $f^{\prime}(x)$ is positive.
Thus, $f^{\prime}(x)$ *changes from negative to positive* as $x$ increases through $3$.
So, $x=3$ is a point of local minimum.
Local minimum value $=f(3)=15$.

**Case II: When $x=1$**
In this case, when $x$ is slightly less than $1$ then $f^{\prime}(x)=3(x-3)(x-1)$ is positive and when $x$ is slightly more than $1$ then $f^{\prime}(x)$ is negative.
Thus, $f^{\prime}(x)$ *changes sign from positive to negative* as $x$ increases through $1$.
So, $x=1$ is a point of local maximum.
Local maximum value $=f(1)=19$.

---

### Example: 3

Show that $(x^{5}-5 x^{4}+5 x^{3}-1)$ has a local maximum when $x=1$, a local minimum when $x=3$, and neither when $x=0$.

#### Solution:

Let $f(x)=x^{5}-5 x^{4}+5 x^{3}-1$. Then,
$$
f^{\prime}(x)=5 x^{4}-20 x^{3}+15 x^{2}=5 x^{2}\left(x^{2}-4 x+3\right)=5 x^{2}(x-3)(x-1) .
$$
For a local maxima or minima, we have $f^{\prime}(x)=0$.
Now, $f^{\prime}(x)=0 \Rightarrow 5 x^{2}(x-3)(x-1)=0 \Rightarrow x=0$ or $x=3$ or $x=1$.

**Case I: When $x=1$**
In this case, when $x$ is slightly less than $1$ then $f^{\prime}(x)=5 x^{2}(x-3)(x-1)$ is positive and when $x$ is slightly more than $1$ then $f^{\prime}(x)$ is negative.
Thus, $f^{\prime}(x)$ *changes sign from positive to negative*.
So, $x=1$ is a point of local maximum.

**Case II: When $x=3$**
Clearly, when $x$ is slightly less than $3$ then $f^{\prime}(x)=5 x^{2}(x-3)(x-1)$ is negative and when $x$ is slightly greater than $3$ then $f^{\prime}(x)$ is positive.
Thus, $f^{\prime}(x)$ *changes sign from negative to positive*.
So, $x=3$ is a point of local minimum.

**Case III: When $x=0$**
Clearly, when $x$ is slightly less than $0$ then $f^{\prime}(x)=5 x^{2}(x-3)(x-1)$ is positive and also when $x$ is slightly more than $0$ then $f^{\prime}(x)$ is positive.
Thus, $f^{\prime}(x)$ *does not change sign* as it passes through $0$.
So, it is neither a point of local maximum nor a point of local minimum, i.e., $x=0$ is a point of inflexion.

---

### Example: 4

Find the points of local maxima and local minima as well as the corresponding local maximum and local minimum values for the function
$$
f(x)=(x-1)^{3}(x+1)^{2}
$$

#### Solution:

$$
\begin{aligned}
& f(x)=(x-1)^{3}(x+1)^{2} \Rightarrow f^{\prime}(x)=2(x-1)^{3}(x+1)+3(x-1)^{2}(x+1)^{2} \\
& =(x-1)^{2}(x+1)(5 x+1) \\
& \therefore \quad f^{\prime}(x)=0 \Rightarrow(x-1)^{2}(x+1)(5 x+1)=0 \\
& \Rightarrow x=1 \text { or } x=-1 \text { or } x=-\frac{1}{5}
\end{aligned}
$$

**Consider $x=1$.**
When $x$ is slightly less than $1$ then clearly $f^{\prime}(x)$ is +ve. When $x$ is slightly greater than $1$, then clearly $f^{\prime}(x)$ is +ve. Thus, $f^{\prime}(x)$ *does not change sign* as $x$ passes through $1$.
So, $x=1$ is neither a point of maximum nor a point of minimum.

**Consider $x=-1$.**
When $x$ is slightly less than $-1$ then $f^{\prime}(x)=(+)(-)(-)=+\mathrm{ve}$.
When $x$ is slightly greater than $-1$ then $f^{\prime}(x)=(+)(+)(-)=-\mathrm{ve}$.
Thus, $f^{\prime}(x)$ *changes sign from +ve to -ve* as $x$ passes through $-1$.
So, $x=-1$ is a point of local maximum.
Local maximum value $=f(-1)=(-2)^{3}(-1+1)^{2}=0$.

**Consider $x=-\frac{1}{5}$.**
When $x$ is slightly less than $-\frac{1}{5}$ then $f^{\prime}(x)=(+)(+)(-)=-\mathrm{ve}$.
When $x$ is slightly greater than $-\frac{1}{5}$ then $f^{\prime}(x)=(+)(+)(+)=+\mathrm{ve}$.
Thus, $f^{\prime}(x)$ *changes sign from -ve to +ve* as $x$ passes through $-\frac{1}{5}$.
So, $x=-\frac{1}{5}$ is a point of local minimum.
Local minimum value $=f\left(-\frac{1}{5}\right)=\frac{-3456}{3125}$.

---

## Second-Derivative Test

### Working Rule for Finding Extremum Values

1.  Find $f^{\prime}(x)$.
2.  Solve $f^{\prime}(x)=0$.
    Each value of $x$ so obtained is a candidate for maximum or minimum.
    Let $x=c$ be one of its points.
3.  Find $f^{\prime \prime}(x)$ and put $x=c$ to get $f^{\prime \prime}(c)$.

Now, if $f^{\prime \prime}(c)<0$ then $x=c$ is a point of local maximum;
if $f^{\prime \prime}(c)>0$ then $x=c$ is a point of local minimum;
if $f^{\prime \prime}(c)=0$ then use the first-derivative test.

---

### Example: 5

Find all the points of local maxima and minima and the corresponding maximum and minimum values of the function
$$
f(x)=-\frac{3}{4} x^{4}-8 x^{3}-\frac{45}{2} x^{2}+105 .
$$

#### Solution:

$f(x)=-\frac{3}{4} x^{4}-8 x^{3}-\frac{45}{2} x^{2}+105$.
$\therefore f^{\prime}(x)=-3 x^{3}-24 x^{2}-45 x=-3 x\left(x^{2}+8 x+15\right)$.
Now, $f^{\prime}(x)=0 \Rightarrow-3 x\left(x^{2}+8 x+15\right)=0 \Rightarrow-3 x(x+5)(x+3)=0$
$$
\Rightarrow x=0 \text { or } x=-5 \text { or } x=-3 .
$$
Thus, $x=0, x=-5$ and $x=-3$ are the candidates for local maxima or minima.
Moreover, $f^{\prime \prime}(x)=\left(-9 x^{2}-48 x-45\right)$.

**Case I: When $x=0$**
We have $f^{\prime \prime}(0)=-45<0$.
So, $x=0$ is a point of local maximum.
And, local maximum value at $x=0$ is $f(0)=105$.

**Case II: When $x=-5$**
We have $f^{\prime \prime}(-5)=-30<0$.
So, $x=-5$ is a point of local maximum.
And, local maximum value at $x=-5$ is $f(-5)=\frac{295}{4}$.

**Case III: When $x=-3$**
We have $f^{\prime \prime}(-3)=18>0$.
So, $x=-3$ is a point of local minimum.
Local minimum value at $x=-3$ is $f(-3)=\frac{231}{4}$.

---

### Example: 6

Find the local maxima and local minima of the functions:
(i) $f(x)=\sin 2 x$, where $0<x<\pi$
(ii) $f(x)=(\sin 2 x-x)$, where $-\frac{\pi}{2} \leq x \leq \frac{\pi}{2}$

#### Solution:

(i) $f(x)=\sin 2 x \Rightarrow f^{\prime}(x)=2 \cos 2 x$.
$\therefore \quad f^{\prime}(x)=0 \Rightarrow 2 \cos 2 x=0$, i.e., $\cos 2 x=0$
$$
\Rightarrow 2 x=\frac{\pi}{2} \text { or } 2 x=\frac{3 \pi}{2} \Rightarrow x=\frac{\pi}{4} \text { or } x=\frac{3 \pi}{4} .
$$
Thus, $x=\frac{\pi}{4}$ and $x=\frac{3 \pi}{4}$ are the candidates for local maxima or minima.
Moreover, $f^{\prime}(x)=2 \cos 2 x \Rightarrow f^{\prime \prime}(x)=-4 \sin 2 x$.

**Case I: When $x=(\pi / 4)$**
We have $f^{\prime \prime}\left(\frac{\pi}{4}\right)=-4 \sin \frac{\pi}{2}=-4<0$.
$\therefore \quad x=\frac{\pi}{4}$ is a point of local maximum.
Local maximum value $=f\left(\frac{\pi}{4}\right)=1$.

**Case II: When $x=(3 \pi / 4)$**
We have $f^{\prime \prime}(3 \pi / 4)=-4 \sin \frac{3 \pi}{2}=4>0$.
$\therefore \quad x=\frac{3 \pi}{4}$ is a point of local minimum.
Local minimum value $=f\left(\frac{3 \pi}{4}\right)=-1$.

(ii) $f(x)=(\sin 2 x-x) \Rightarrow f^{\prime}(x)=(2 \cos 2 x-1)$ and $f^{\prime \prime}(x)=-4 \sin 2 x$.
$\therefore f^{\prime}(x)=0 \Rightarrow(2 \cos 2 x-1)=0 \Rightarrow \cos 2 x=\frac{1}{2}$
$\Rightarrow 2 x=-\frac{\pi}{3}$ or $2 x=\frac{\pi}{3} \Rightarrow x=\frac{-\pi}{6}$ or $x=\frac{\pi}{6}$.
Thus, $x=\frac{-\pi}{6}$ and $x=\frac{\pi}{6}$ are the candidates for local maxima or local minima.

**Case I: When $x=-(\pi / 6)$**
We have $f^{\prime \prime}\left(-\frac{\pi}{6}\right)=4 \sin \frac{\pi}{3}=2 \sqrt{3}>0$.
So, $x=\frac{-\pi}{6}$ is a point of local minimum.
The local minimum value
$$
=f\left(-\frac{\pi}{6}\right)=\left(-\sin \frac{\pi}{3}-\frac{\pi}{6}\right)=-\left(\frac{\sqrt{3}}{2}+\frac{\pi}{6}\right) .
$$

**Case II: When $x=\frac{\pi}{6}$**
We have $f^{\prime \prime}\left(\frac{\pi}{6}\right)=-4 \sin \left(\frac{\pi}{3}\right)=-2 \sqrt{3}<0$.
$\therefore \quad x=\frac{\pi}{6}$ is a point of local maximum.
And, the local maximum value
$$
=f\left(\frac{\pi}{6}\right)=\left(\sin \frac{\pi}{3}-\frac{\pi}{6}\right)=\left(\frac{\sqrt{3}}{2}-\frac{\pi}{6}\right) .
$$
---

### Example: 7

Find the local maxima and local minima of the functions:
(i) $f(x)=(\sin x-\cos x)$, where $0<x<\frac{\pi}{2}$
(ii) $f(x)=(2 \cos x+x)$, where $0<x<\pi$

#### Solution:

(i) $f(x)=(\sin x-\cos x)$.
$\therefore \quad f^{\prime}(x)=(\cos x+\sin x)$ and $f^{\prime \prime}(x)=(-\sin x+\cos x)$.
Now, $f^{\prime}(x)=0 \Rightarrow \cos x+\sin x=0$
$$
\Rightarrow \tan x=-1 \Rightarrow x=\frac{3 \pi}{4} \text { or } \frac{7 \pi}{4} .
$$
Thus, $x=\frac{3 \pi}{4}$ and $x=\frac{7 \pi}{4}$ are the candidates for local maxima or local minima.

**Case I: When $x=(3 \pi / 4)$**
$$
\begin{aligned}
f^{\prime \prime}\left(\frac{3 \pi}{4}\right) & =\left(-\sin \frac{3 \pi}{4}+\cos \frac{3 \pi}{4}\right)=\left(-\frac{1}{\sqrt{2}}-\frac{1}{\sqrt{2}}\right)=\frac{-2}{\sqrt{2}} \\
& =-\sqrt{2}<0
\end{aligned}
$$
So, $x=(3 \pi / 4)$ is a **point of local maximum**.
Local maximum value $=f\left(\frac{3 \pi}{4}\right)=\sqrt{2}$.

**Case II: When $x=(7 \pi / 4)$**
$$
\begin{aligned}
f^{\prime \prime}\left(\frac{7 \pi}{4}\right) & =f^{\prime \prime}\left(-\sin \frac{7 \pi}{4}+\cos \frac{7 \pi}{4}\right)=\left(\sin \frac{\pi}{4}+\cos \frac{\pi}{4}\right) \\
& =\sqrt{2}>0 .
\end{aligned}
$$
So, $x=(7 \pi / 4)$ is a **point of local minimum**.
Local minimum value $=f\left(\frac{7 \pi}{4}\right)=\sin \frac{7 \pi}{4}-\cos \frac{7 \pi}{4}$
$$
=\left(-\sin \frac{\pi}{4}-\cos \frac{\pi}{4}\right)=-\sqrt{2} .
$$

(ii) $f(x)=(2 \cos x+x)$.
$\therefore f^{\prime}(x)=(-2 \sin x+1)$ and $f^{\prime \prime}(x)=-2 \cos x$.
Now, $f^{\prime}(x)=0 \Rightarrow-2 \sin x+1=0$
$$
\left.\Rightarrow \sin x=\frac{1}{2} \Rightarrow x=\frac{\pi}{6} \text { or } x=\frac{5 \pi}{6} \text { in }\right] 0, \pi[.
$$
Thus, $x=(\pi / 6)$ and $x=(5 \pi / 6)$ are the candidates for local maxima or local minima.

**Case I: When $x=(\pi / 6)$**
We have $f^{\prime \prime}\left(\frac{\pi}{6}\right)=-2 \cos \frac{\pi}{6}=\left(-2 \times \frac{\sqrt{3}}{2}\right)=-\sqrt{3}<0$.
$\therefore \quad x=(\pi / 6)$ is a **point of local maximum**.
Local maximum value $=f\left(\frac{\pi}{6}\right)=\left(\sqrt{3}+\frac{\pi}{6}\right)$.

**Case II: When $x=(5 \pi / 6)$**
We have $f^{\prime \prime}\left(\frac{5 \pi}{6}\right)=-2 \cos \frac{5 \pi}{6}=2 \cos \frac{\pi}{6}=2 \times \frac{\sqrt{3}}{2}=\sqrt{3}>0$.
So, $x=(5 \pi / 6)$ is a **point of local minimum**.
$$
\text { Local minimum value }=f\left(\frac{5 \pi}{6}\right)=\left(\frac{5 \pi}{6}-\sqrt{3}\right) .
$$

---

### Example: 8

Find the points of local maxima or local minima of the function
$$
f(x)=\left(\sin ^{4} x+\cos ^{4} x\right) \text { in } 0<x<\frac{\pi}{2}
$$

#### Solution:

$$
\begin{aligned}
f(x) & =\sin ^{4} x+\cos ^{4} x \\
\Rightarrow f^{\prime}(x) & =4 \sin ^{3} x \cos x-4 \cos ^{3} x \sin x \\
& =-4 \sin x \cos x\left(\cos ^{2} x-\sin ^{2} x\right)=-2 \sin 2 x \cos 2 x=-\sin 4 x
\end{aligned}
$$
And, $f^{\prime \prime}(x)=-4 \cos 4 x$.
Now, $f^{\prime}(x)=0 \Rightarrow-\sin 4 x=0 \Rightarrow 4 x=\pi$, i.e., $x=\frac{\pi}{4}$.
$\therefore x=(\pi / 4)$ is a point of local maximum or local minimum.
Now, $f^{\prime \prime}\left(\frac{\pi}{4}\right)=-4 \cos \pi=4>0$.
$\therefore \quad x=(\pi / 4)$ is a **point of local minimum**.
Local minimum value $=f\left(\frac{\pi}{4}\right)=\frac{1}{2}$.

---

### Example: 9

Find the local maxima and local minima, and the corresponding local maximum and local minimum values of the following functions:
(i) $f(x)=x \sqrt{1-x}$, where $x>0$
(ii) $f(x)=\frac{x}{(x-1)(x-4)}$, where $1<x<4$

#### Solution:

(i) $f(x)=x \sqrt{1-x}$.
$\therefore f^{\prime}(x)=\frac{(2-3 x)}{2 \sqrt{1-x}}$ and $f^{\prime \prime}(x)=\frac{(3 x-4)}{4(1-x)^{3 / 2}}$.
Now, $f^{\prime}(x)=0 \Rightarrow(2-3 x)=0 \Rightarrow x=\frac{2}{3}$;
and, $f^{\prime \prime}\left(\frac{2}{3}\right)=\frac{\left(3 \times \frac{2}{3}-4\right)}{4\left(1-\frac{2}{3}\right)^{3 / 2}}=\frac{-3^{3 / 2}}{2}<0$.
$\therefore \quad x=\frac{2}{3}$ is a **point of local maximum**.
Local maximum value $=f\left(\frac{2}{3}\right)=\frac{2}{3 \sqrt{3}}$.

(ii) $f(x)=\frac{x}{(x-1)(x-4)}=\frac{x}{\left(x^{2}-5 x+4\right)}$.
$\therefore f^{\prime}(x)=\frac{\left(4-x^{2}\right)}{\left(x^{2}-5 x+4\right)^{2}}$.
And,
$$
f^{\prime \prime}(x)=\frac{\left(x^{2}-5 x+4\right)^{2}(-2 x)-\left(4-x^{2}\right) 2\left(x^{2}-5 x+4\right)(2 x-5)}{\left(x^{2}-5 x+4\right)^{4}}
$$
$$
\begin{aligned}
f^{\prime}(x) & =0 \Rightarrow\left(4-x^{2}\right)=0 \Rightarrow x=2 \quad[\because 1<x<4] \\
f^{\prime \prime}(2) & =\frac{-16}{16}=-1<0
\end{aligned}
$$
$\therefore x=2$ is a **point of local maximum**.
Local maximum value $=f(2)=-1$.

---

### Example: 10

Prove that the maximum value of $\left(\frac{1}{x}\right)^{x}$ is $e^{1 / e}$.

#### Solution:

Let $y=\left(\frac{1}{x}\right)^{x}=x^{-x}$. Then, $\log y=-x \log x$.
$\therefore \quad \frac{1}{y} \cdot \frac{d y}{d x}=-(1+\log x) \quad$ or $\quad \frac{d y}{d x}=-y(1+\log x)$.
And, $\frac{d^{2} y}{d x^{2}}=-y \cdot \frac{1}{x}-(1+\log x) \cdot \frac{d y}{d x}=-\left(\frac{1}{x}\right)^{x+1}-(1+\log x) \cdot \frac{d y}{d x}$.
Now, $\frac{d y}{d x}=0 \Rightarrow 1+\log x=0$
$$
\Rightarrow \log x=-1=-\log e=\log (1 / e) \Rightarrow x=(1 / e) .
$$
Also, $\quad \frac{d^{2} y}{d x^{2}}$ at $x=(1 / e)$ is $-e^{1+(1 / e)}<0 \quad\left[\because \frac{d y}{d x}=0\right]$.
So, $x=(1 / e)$ is a **point of local maximum**.
Local maximum value $=\{$value of $y$ when $x=(1 / e)\}=e^{1 / e}$.

---

### Example: 11

Find the point on the parabola $y^{2}=2 x$ which is closest to the point $(1,4)$.

#### Solution:

Let $A(x, y)$ be the required point which is closest to the point $B(1,4)$. Then, the distance $A B$ should be minimum. And, therefore $A B^{2}$ should be minimum.
Now, $A B^{2}=(x-1)^{2}+(y-4)^{2}=\left(\frac{y^{2}}{2}-1\right)^{2}+(y-4)^{2}=\frac{\left(y^{4}-32 y+68\right)}{4}$.
Let $f(y)=\frac{y^{4}-32 y+68}{4}$.
Then, $f^{\prime}(y)=\frac{4 y^{3}-32}{4}=\left(y^{3}-8\right)$. And, $f^{\prime \prime}(y)=3 y^{2}$.
Now, $f^{\prime}(y)=0 \Rightarrow y^{3}-8=0 \Rightarrow y=2$. Also, $f^{\prime \prime}(2)=3 \times 4=12>0$.
So, $y=2$ is a **point of minimum**.
Now, $y=2 \Rightarrow x=\frac{y^{2}}{2}=\frac{4}{2}=2$. So, the required point is $(2,2)$.

---

### Example: 12

Show that none of the following functions has a maxima or minima.
(i) $e^{x}$
(ii) $\log x$
(iii) $x^{3}+x^{2}+x+1$

#### Solution:

(i) $f(x)=e^{x} \Rightarrow f^{\prime}(x)=e^{x}$.
For a maxima or a minima, we must have $f^{\prime}(x)=0$.
But, $f^{\prime}(x)=0 \Rightarrow e^{x}=0$, which is not possible.
So, $f(x)=e^{x}$ does not have a maxima or a minima.

(ii) $f(x)=\log x \Rightarrow f^{\prime}(x)=\frac{1}{x}$.
For a maxima or a minima, we must have $f^{\prime}(x)=0$.
But, $f^{\prime}(x)=0 \Rightarrow \frac{1}{x}=0$, which is not possible for any value of $x$.
$\therefore f(x)=\log x$ does not have a maxima or a minima.

(iii) $f(x)=x^{3}+x^{2}+x+1 \Rightarrow f^{\prime}(x)=3 x^{2}+2 x+1$.
For a maxima or a minima, we must have $f^{\prime}(x)=0$.
Now, $f^{\prime}(x)=0 \Rightarrow 3 x^{2}+2 x+1=0$
$$
\Rightarrow x=\frac{-2 \pm \sqrt{4-12}}{6} \text {, which are imaginary. }
$$
Thus, $f^{\prime}(x) \neq 0$ for any real value of $x$.
Hence, $f(x)$ does not have a maxima or a minima.

---

### Example: 13

Show that $\sin ^{p} \theta \cos ^{q} \theta$ attains a maximum when $\theta=\tan ^{-1} \sqrt{\frac{p}{q}}$.

#### Solution:

Let $y=\sin ^{p} \theta \cos ^{q} \theta$.
Then, $\frac{d y}{d \theta}=p \sin ^{p-1} \theta \cos ^{q+1} \theta-q \cos ^{q-1} \theta \sin ^{p+1} \theta$
$$
=\left(\sin ^{p-1} \theta \cos ^{q-1} \theta\right)\left(p \cos ^{2} \theta-q \sin ^{2} \theta\right) .
$$
Now, for maxima or minima, we have $\frac{d y}{d \theta}=0$.
But $\frac{d y}{d \theta}=0 \Rightarrow \sin ^{p-1} \theta=0$ or $\cos ^{q-1} \theta=0$ or $p \cos ^{2} \theta-q \sin ^{2} \theta=0$
$$
\Rightarrow \theta=0 \text { or } \theta=\frac{\pi}{2} \text { or } \theta=\tan ^{-1} \sqrt{\frac{p}{q}} .
$$
Moreover, we may write
$$
\begin{aligned}
\frac{d y}{d \theta} & =\frac{y\left(p \cos ^{2} \theta-q \sin ^{2} \theta\right)}{\sin \theta \cos \theta}=y(p \cot \theta-q \tan \theta) . \\
\therefore \quad \frac{d^{2} y}{d \theta^{2}} & =y\left(-p \operatorname{cosec}^{2} \theta-q \sec ^{2} \theta\right)+(p \cot \theta-q \tan \theta) \cdot \frac{d y}{d \theta} .
\end{aligned}
$$
Thus, at $\theta=\tan ^{-1} \sqrt{\frac{p}{q}}$, we have $\frac{d y}{d \theta}=0$ and therefore,
$$
\left[\frac{d^{2} y}{d \theta^{2}} \text { at } \theta=\tan ^{-1} \sqrt{\frac{p}{q}}\right]=\sin ^{p} \theta \cos ^{q} \theta\left(-p \operatorname{cosec}^{2} \theta-q \sec ^{2} \theta\right)<0 .
$$
Hence, $y$ is maximum when $\theta=\tan ^{-1} \sqrt{\frac{p}{q}}$.

---

## Maxima and Minima on a Closed Interval

Let $f(x)$ be a given function defined on $[a, b]$. Let the local minimum value of $f(x)$ be $m$, and let the local maximum value of $f(x)$ be $M$.

Then, **minimum value** of $f(x)$ on $[a, b]$ is the smallest of $m, f(a)$ and $f(b)$. The **maximum value** of $f(x)$ on $[a, b]$ is the greatest of $M, f(a)$ and $f(b)$.

---

### Example: 14

Find the maximum and minimum values of
$$
\left(3 x^{4}-8 x^{3}+12 x^{2}-48 x+25\right) \text { on }[0,3]
$$

#### Solution:

Let $f(x)=3 x^{4}-8 x^{3}+12 x^{2}-48 x+25$.
Then, $f^{\prime}(x)=12 x^{3}-24 x^{2}+24 x-48$
and $f^{\prime \prime}(x)=36 x^{2}-48 x+24$.
Now, $f^{\prime}(x)=0 \Rightarrow 12\left(x^{3}-2 x^{2}+2 x-4\right)=0$
$$
\Rightarrow 12(x-2)\left(x^{2}+2\right)=0
$$
$\Rightarrow x=2$ [neglecting the imaginary values].
And, $f^{\prime \prime}(2)=72>0$.
So, $x=2$ is a **point of local minima**.
Now, $f(2)=-39$; $f(0)=25$ and $f(3)=16$.
$\therefore \quad$ **minimum value** of $f(x)$ on $[0,3]$ is $-39$ at $x=2$.
**Maximum value** of $f(x)$ on $[0,3]$ is $25$ at $x=0$.

---

### Example: 15

Find the maximum and minimum values of $(x+\sin 2 x)$ on $[0,2 \pi]$.

#### Solution:

Let $f(x)=(x+\sin 2 x)$.
Then, $f^{\prime}(x)=(1+2 \cos 2 x)$ and $f^{\prime \prime}(x)=-4 \sin 2 x$.
Now, $f^{\prime}(x)=0 \Rightarrow \cos 2 x=-\frac{1}{2}$, where $x \in[0,2 \pi]$
$\Rightarrow 2 x=\frac{2 \pi}{3}$ or $2 x=\frac{4 \pi}{3} \Rightarrow x=(\pi / 3)$ or $x=(2 \pi / 3)$.
$f^{\prime \prime}\left(\frac{\pi}{3}\right)=-4 \sin \left(\frac{2 \pi}{3}\right)=-4 \sin \frac{\pi}{3}=-2 \sqrt{3}<0$.
$\therefore \quad x=(\pi / 3)$ is a **point of local maxima**.
Now, $f\left(\frac{\pi}{3}\right)=\frac{2 \pi+3 \sqrt{3}}{6}$, $f(0)=0$ and $f(2 \pi)=2 \pi$.
$\therefore$ **maximum value** of $f(x)$ is $2 \pi$ at $x=2 \pi$.
Again, we consider the point $x=(2 \pi / 3)$.
$$
f^{\prime \prime}\left(\frac{2 \pi}{3}\right)=-4 \sin \left(2 \times \frac{2 \pi}{3}\right)=-4 \sin \frac{4 \pi}{3}=4 \sin \frac{\pi}{3}=2 \sqrt{3}>0 .
$$
So, $\quad x=\frac{2 \pi}{3}$ is a **point of local minima**.
Now, $f\left(\frac{2 \pi}{3}\right)=\frac{2 \pi}{3}+\sin \frac{4 \pi}{3}=\frac{2 \pi}{3}-\sin \frac{\pi}{3}=\frac{4 \pi-3 \sqrt{3}}{6}$;
$$
f(0)=0 \textD
\text { and } f(2 \pi)=2 \pi+\sin 4 \pi=2 \pi
$$
$\therefore \quad$ the **minimum value** of $f(x)$ is $0$ at $x=0$.

---

### Example: 16

Show that $\sin x(1+\cos x), x \in[0, \pi]$ is maximum at $x=(\pi / 3)$.

#### Solution:

Let $f(x)=\sin x(1+\cos x)$.
Then, $f^{\prime}(x)=-\sin ^{2} x+\cos x(1+\cos x)$
$$
=2 \cos ^{2} x+\cos x-1=(2 \cos x-1)(\cos x+1) .
$$
And, $f^{\prime \prime}(x)=(-4 \cos x \sin x-\sin x)=-\sin x(1+4 \cos x)$.
Now, $f^{\prime}(x)=0 \Rightarrow(2 \cos x-1)(\cos x+1)=0$
$$
\Rightarrow \cos x=\frac{1}{2} \text { or } \cos x=-1 \Rightarrow x=\frac{\pi}{3} \text { or } x=\pi .
$$
But, $\quad f^{\prime \prime}\left(\frac{\pi}{3}\right)=-\sin \frac{\pi}{3}\left(1+4 \cos \frac{\pi}{3}\right)=\frac{-3 \sqrt{3}}{2}<0$.
$\therefore \quad x=(\pi / 3)$ is a **point of local maximum**.
Now, $f(0)=0, f(\pi)=0$ and $f\left(\frac{\pi}{3}\right)=\frac{3 \sqrt{3}}{4}$.
$\therefore \quad$ the **maximum value** of $f(x)$ is $\frac{3 \sqrt{3}}{4}$ at $x=\frac{\pi}{3}$.

---