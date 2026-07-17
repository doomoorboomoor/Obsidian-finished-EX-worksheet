## Definite Integral as the Limit of a Sum

Let $f(x)$ be a continuous real-valued function, defined in the closed interval $[a, b]$. Then we define

$$
\int_{a}^{b} f(x) d x=\lim _{h \rightarrow 0} h[f(a)+f(a+h)+f(a+2 h)+\ldots+f[a+(n-1) h)]
$$

where $n h=(b-a)$.

The method of evaluating $\int_{a}^{b} f(x) d x$ by using the above definition is called **integration from first principles**.

---

## Some Useful Results for Direct Applications

1.  $1+2+3+\ldots+(n-1)=\frac{1}{2} n(n-1)$.
2.  $1^{2}+2^{2}+3^{2}+\ldots+(n-1)^{2}=\frac{1}{6}(n-1) n(2 n-1)$.
3.  $1^{3}+2^{3}+3^{3}+\ldots+(n-1)^{3}=\left\{\frac{n(n-1)}{2}\right\}^{2}$.
4.  $a+a r+a r^{2}+\ldots+a r^{n-1}=\frac{a\left(r^{n}-1\right)}{(r-1)}$.
5.  $\sin a+\sin (a+h)+\sin (a+2 h)+\ldots+\sin [a+(n-1) h]$
    $$
    =\frac{\sin \left\{a+\left(\frac{n-1}{2}\right) h\right\} \sin \left(\frac{n h}{2}\right)}{\sin (h / 2)} .
    $$
6.  $\cos a+\cos (a+h)+\cos (a+2 h)+\ldots+\cos [a+(n-1) h]$
    $$
    =\frac{\cos \left\{a+\frac{(n-1)}{2} h\right\} \sin \left(\frac{n h}{2}\right)}{\sin (h / 2)} .
    $$

---

## Solved Examples

### Example 1

Evaluate the following integrals as limit of sums:
1.  $\int_{0}^{5}(x+1) d x$
2.  $\int_{1}^{3}(2 x+3) d x$
_[CBSE 2000C]_

#### Solution

**(i)** Let $f(x)=(x+1)$; $a=0$; $b=5$ and **$n h=(5-0)=5$**. Then,

$$
\begin{aligned}
\int_{0}^{5}(x+1) d x & =\lim _{h \rightarrow 0} h[f(0)+f(0+h)+f(0+2 h)+\ldots+f\{0+(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h[1+(h+1)+(2 h+1)+\ldots+\{(n-1) h+1\}] \\
& =\lim _{h \rightarrow 0} h[n+\{h+2 h+3 h+\ldots+(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h[n+\{1+2+3+\ldots+(n-1)\} h] \\
& =\lim _{h \rightarrow 0} h\left[n+\frac{n(n-1)}{2} h\right]=\lim _{h \rightarrow 0}\left[n h+\frac{n h(n h-h)}{2}\right]
\end{aligned}
$$

$$
\begin{aligned}
& =\lim _{h \rightarrow 0}\left[5+\frac{5(5-h)}{2}\right] \quad[\because n h=5] \\
& =\frac{35}{2}
\end{aligned}
$$

**(ii)** Let $f(x)=(2 x+3)$; $a=1$; $b=3$ and **$n h=(3-1)=2$**.

$$
\begin{aligned}
& \text { Then, } \int_{1}^{3}(2 x+3) d x=\lim _{h \rightarrow 0} h[f(1)+f(1+h)+\ldots+f\{1+(n-1) h\}] \\
& \qquad \begin{aligned}
& =\lim _{h \rightarrow 0} h[5+(5+2 h)+(5+4 h)+\ldots+\{5+2(n-1) h\}] \\
& \quad[\because f(1)=5, f(1+h)=5+2 h, \text { etc. }] \\
& =\lim _{h \rightarrow 0} h[5 n+\{2 h+4 h+\ldots+2(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h[5 n+2\{1+2+3+\ldots+(n-1)\} h] \\
& =\lim _{h \rightarrow 0} h\left[5 n+2 \cdot \frac{n(n-1)}{2} h\right] \\
& =\lim _{h \rightarrow 0}[5 n h+n h(n h-h)] \\
& =\lim _{h \rightarrow 0}[10+2(2-h)] \quad[\because n h=2] \\
& =14 .
\end{aligned}
\end{aligned}
$$

---

### Example 2

Evaluate the following integrals as limit of sums:
1.  $\int_{0}^{2}\left(x^{2}+1\right) d x$
2.  $\int_{1}^{3}\left(x^{2}+x\right) d x$
_[CBSE 2006C]_

#### Solution

**(i)** Let $f(x)=\left(x^{2}+1\right)$; $a=0$; $b=2$ and **$n h=(2-0)=2$**.

$$
\begin{aligned}
\therefore \int_{0}^{2}\left(x^{2}+1\right) d x & =\lim _{h \rightarrow 0} h[f(0)+f(0+h)+\ldots+f\{0+(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h\left[1+\left(h^{2}+1\right)+\left(4 h^{2}+1\right)+\left(9 h^{2}+1\right)+\right. \\
& \left.\ldots+\left\{(n-1)^{2} h^{2}+1\right\}\right] \\
{[\because f(0)=} & \left.1, f(0+h)=\left(h^{2}+1\right), f(0+2 h)=\left(4 h^{2}+1\right), \text { etc. }\right] \\
& =\lim _{h \rightarrow 0} h\left[n+\left\{1^{2}+2^{2}+3^{2}+\ldots+(n-1)^{2}\right\} h^{2}\right] \\
& =\lim _{h \rightarrow 0} h\left[n+\frac{(n-1) n(2 n-1)}{6} \cdot h^{2}\right] \\
& =\lim _{h \rightarrow 0}\left[n h+\frac{(n h-h) n h(2 n h-h)}{6}\right] \\
& =\lim _{h \rightarrow 0}\left[2+\frac{(2-h) 2(4-h)}{6}\right] \quad[\because n h=2] \\
& =\frac{14}{3} .
\end{aligned}
$$

**(ii)** Let $f(x)=\left(x^{2}+x\right)$; $a=1$; $b=3$ and **$n h=(3-1)=2$**.

$$
\begin{aligned}
\therefore & \begin{aligned}
\int_{1}^{3}\left(x^{2}+x\right) d x= & \lim _{h \rightarrow 0} h[f(1)+f(1+h)+f(1+2 h)+\ldots \\
& +f\{1+(n-1) h\}]
\end{aligned} \\
= & \lim _{h \rightarrow 0} h\left[\left(1^{2}+1\right)+\left\{(1+h)^{2}+(1+h)\right\}+\left\{(1+2 h)^{2}\right.\right. \\
& \left.+(1+2 h)\}+\ldots+\{1+(n-1) h\}^{2}+\{1+(n-1) h\}\right] \\
= & \lim _{h \rightarrow 0} h\left[2 n+h^{2}\left\{1^{2}+2^{2}+\ldots+(n-1)^{2}\right\}+3 h\{1+2+\ldots+(n-1)\}\right] \\
= & \lim _{h \rightarrow 0} h\left[2 n+h^{2} \cdot \frac{(n-1) n(2 n-1)}{6}+3 h \cdot \frac{n(n-1)}{2}\right] \\
= & \lim _{h \rightarrow 0}\left[2 n h+\frac{(n h-h) n h(2 n h-h)}{6}+\frac{3}{2} \cdot n h(n h-h)\right] \\
= & \lim _{h \rightarrow 0}\left[4+\frac{(2-h) 2(4-h)}{6}+\frac{3}{2} \cdot 2(2-h)\right] \quad[\because n h=2] \\
= & \frac{38}{3}
\end{aligned}
$$

---

### Example 3

Evaluate $\int_{0}^{1}\left(3 x^{2}+2 x+1\right) d x$ as limit of sums.
_[CBSE 2007C]_

#### Solution

Let $f(x)=\left(3 x^{2}+2 x+1\right)$; $a=0$, $b=1$ and **$n h=(1-0)=1$**.

$$
\text { Then, } \begin{aligned}
\int_{0}^{1}\left(3 x^{2}\right. & +2 x+1) d x \\
= & \lim _{h \rightarrow 0} h[f(0)+f(0+h)+f(0+2 h)+\ldots+f\{0+(n-1) h\}] \\
= & \lim _{h \rightarrow 0} h\left[1+\left(3 h^{2}+2 h+1\right)+\left(3 \cdot 2^{2} h^{2}+2 \cdot 2 h+1\right)+\ldots\right. \\
& \left.\quad+\left\{3 \cdot(n-1)^{2} h^{2}+2 \cdot(n-1) h+1\right\}\right] \\
= & \lim _{h \rightarrow 0} h\left[n+3 h^{2}\left\{1^{2}+2^{2}+3^{2}+\ldots+(n-1)^{2}\right\}\right. \\
& \quad+2 h\{1+2+3+\ldots+(n-1)\}] \\
= & \lim _{h \rightarrow 0} h\left[n+3 h^{2} \cdot \frac{(n-1) n(2 n-1)}{6}+2 h \cdot \frac{n(n-1)}{2}\right] \\
= & \lim _{h \rightarrow 0}\left[n h+\frac{1}{2}(n h-h)(n h)(2 n h-h)+(n h)(n h-h)\right] \\
= & \lim _{h \rightarrow 0}\left[1+\frac{1}{2}(1-h) \cdot 1 \cdot(2-h)+1 \cdot(1-h)\right] \quad[\because n h=1] \\
= & 3 .
\end{aligned}
$$

---

### Example 4

Evaluate $\int_{-1}^{1} e^{x} d x$ as limit of sums.

#### Solution

Let $f(x)=e^{x}$ and **$n h=\{1-(-1)\}=2$**. Then,

$$
\begin{aligned}
\int_{-1}^{1} e^{x} d x & =\lim _{h \rightarrow 0} h[f(-1)+f(-1+h)+\ldots+f\{-1+(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h\left[e^{-1}+e^{(-1+h)}+e^{(-1+2 h)}+\ldots+e^{\{-1+(n-1) h\}}\right] \\
& \quad\left[\because f(-1)=e^{-1}, f(-1+h)=e^{(-1+h)}, \text { etc. }\right] \\
& =\lim _{h \rightarrow 0} e^{-1} h\left[1+e^{h}+e^{2 h}+\ldots+e^{(n-1) h}\right] \\
& =\frac{1}{e} \cdot \lim _{h \rightarrow 0} h\left[\frac{\left(e^{h}\right)^{n}-1}{\left(e^{h}-1\right)}\right]=\frac{1}{e} \cdot \lim _{h \rightarrow 0} \frac{h\left[e^{n h}-1\right]}{\left(e^{h}-1\right)} \\
& =\frac{1}{e} \cdot \lim _{h \rightarrow 0} \frac{h\left(e^{2}-1\right)}{\left(e^{h}-1\right)} \quad[\because n h=2] \\
& =\frac{1}{e} \cdot \lim _{h \rightarrow 0} \frac{h\left(e^{2}-1\right)}{\left\{1+h+\frac{h^{2}}{\lfloor 2}+\frac{h^{3}}{\lfloor 3}+\ldots\right\}-1} \\
& =\frac{1}{e} \cdot \lim _{h \rightarrow 0} \frac{e^{2}-1}{\left(1+\frac{h}{\lfloor 2}+\frac{h^{2}}{\lfloor 3}+\ldots\right)}=\frac{1}{e}\left(e^{2}-1\right)=\left(e-\frac{1}{e}\right) .
\end{aligned}
$$

---

### Example 5

Evaluate $\int_{a}^{b} \sin x d x$ from first principles.

#### Solution

Let $f(x)=\sin x$ and let **$n h=(b-a)$**. Then,

$$
\begin{aligned}
\int_{a}^{b} \sin x d x & =\lim _{h \rightarrow 0} h[f(a)+f(a+h)+\ldots+f\{a+(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h[\sin a+\sin (a+h)+\ldots+\sin \{a+(n-1) h\}] \\
& =\lim _{h \rightarrow 0} h \cdot \frac{\sin \left\{a+\left(\frac{n-1}{2}\right) h\right\} \sin \left(\frac{n h}{2}\right)}{\sin (h / 2)} \\
& =\lim _{h \rightarrow 0}\left[2 \sin \left\{a+\frac{1}{2} n h-\frac{1}{2} h\right\} \sin \left(\frac{n h}{2}\right) \times \frac{(h / 2)}{\sin (h / 2)}\right] \\
& =\lim _{h \rightarrow 0}\left[2 \sin \left\{a+\frac{1}{2}(b-a)-\frac{1}{2} h\right\} \sin \left(\frac{b-a}{2}\right) \times \frac{(h / 2)}{\sin (h / 2)}\right] \\
& =\lim _{h \rightarrow 0} 2 \sin \left\{\left(\frac{b+a}{2}\right)-\frac{1}{2} h\right\} \sin \left(\frac{b-a}{2}\right) \cdot \lim _{h \rightarrow 0} \frac{(h / 2)}{\sin (h / 2)} \\
& =2 \sin \left(\frac{b+a}{2}\right) \sin \left(\frac{b-a}{2}\right) \\
& =(\cos a-\cos b)[\because 2 \sin A \sin B=\cos (A-B)-\cos (A+B)] .
\end{aligned}
$$

---