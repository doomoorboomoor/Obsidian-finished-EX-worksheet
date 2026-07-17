## Three More Special Integrals

### Theorem

1.  $\int \frac{d x}{\sqrt{a^{2}-x^{2}}}=\sin ^{-1} \frac{x}{a}+C$.
2.  $\int \frac{d x}{\sqrt{x^{2}-a^{2}}}=\log \left|x+\sqrt{x^{2}-a^{2}}\right|+C$.
3.  $\int \frac{d x}{\sqrt{x^{2}+a^{2}}}=\log \left|x+\sqrt{x^{2}+a^{2}}\right|+C$.

#### Proof (i)

Put $x=a \sin \theta$ so that $d x=a \cos \theta d \theta$.

$$
\therefore \quad \int \frac{d x}{\sqrt{a^{2}-x^{2}}}=\int \frac{a \cos \theta}{a \cos \theta} d \theta=\int d \theta=\theta+C=\sin ^{-1} \frac{x}{a}+C
$$

Hence, $\int \frac{d x}{\sqrt{a^{2}-x^{2}}}=\sin ^{-1} \frac{x}{a}+C$.

#### Proof (ii)

Put $x=a \sec \theta$ so that $d x=a \sec \theta \tan \theta d \theta$.

$$
\begin{aligned}
\therefore \int \frac{d x}{\sqrt{x^{2}-a^{2}}} & =\int \frac{a \sec \theta \tan \theta}{a \tan \theta} d \theta \\
& =\int \sec \theta d \theta=\log |\sec \theta+\tan \theta|+c \\
& =\log \left|\sec \theta+\sqrt{\sec ^{2} \theta-1}\right|+c \\
& =\log \left|\frac{x}{a}+\sqrt{\left(\frac{x^{2}}{a^{2}}-1\right)}\right|+c=\log \left|\frac{x+\sqrt{x^{2}-a^{2}}}{a}\right|+c \\
& =\log \left|x+\sqrt{x^{2}-a^{2}}\right|-\log a+c \\
& =\log \left|x+\sqrt{x^{2}-a^{2}}\right|+C \text { [taking }-\log a+c=C \text { ]. }
\end{aligned}
$$

Hence, $\int \frac{d x}{\sqrt{x^{2}-a^{2}}}=\log \left|x+\sqrt{x^{2}-a^{2}}\right|+C$.

#### Proof (iii)

Put $x=a \tan \theta$ so that $d x=a \sec ^{2} \theta d \theta$.

$$
\begin{aligned}
\therefore \int \frac{d x}{\sqrt{x^{2}+a^{2}}} & =\int \frac{a \sec ^{2} \theta}{a \sec \theta} d \theta \\
& =\int \sec \theta d \theta=\log |\sec \theta+\tan \theta|+c \\
& =\log \left|\sqrt{1+\tan ^{2} \theta}+\tan \theta\right|+c \\
& =\log \left|\sqrt{1+\frac{x^{2}}{a^{2}}}+\frac{x}{a}\right|+c \\
& =\log \left|x+\sqrt{x^{2}+a^{2}}\right|-\log a+c \\
& \left.=\log \left|x+\sqrt{x^{2}+a^{2}}\right|+C \quad \text { [taking }-\log a+c=C\right] .
\end{aligned}
$$

Hence, $\int \frac{d x}{\sqrt{x^{2}+a^{2}}}=\log \left|x+\sqrt{x^{2}+a^{2}}\right|+C$.

---

## Solved Examples

### Example 1:

Evaluate:
(i) $\int \frac{d x}{\sqrt{9-25 x^{2}}}$
(ii) $\int \frac{d x}{\sqrt{4 x^{2}-9}}$
(iii) $\int \frac{d x}{\sqrt{16 x^{2}+25}}$

#### Solution:

We have

$$
\text { (i) } \begin{aligned}
\int \frac{d x}{\sqrt{9-25 x^{2}}} &=\frac{1}{5} \cdot \int \frac{d x}{\sqrt{\frac{9}{25}-x^{2}}}=\frac{1}{5} \cdot \int \frac{d x}{\sqrt{\left(\frac{3}{5}\right)^{2}-x^{2}}} \\
&=\frac{1}{5} \sin ^{-1}\left(\frac{x}{3 / 5}\right)+C=\frac{1}{5} \sin ^{-1}\left(\frac{5 x}{3}\right)+C .
\end{aligned}
$$

$$
\text { (ii) } \begin{aligned}
\int \frac{d x}{\sqrt{4 x^{2}-9}} & =\frac{1}{2} \int \frac{d x}{\sqrt{x^{2}-\frac{9}{4}}}=\frac{1}{2} \int \frac{d x}{\sqrt{x^{2}-\left(\frac{3}{2}\right)^{2}}} \\
& =\frac{1}{2} \log \left|x+\sqrt{x^{2}-\frac{9}{4}}\right|+C \\
& =\frac{1}{2} \log \left|2 x+\sqrt{4 x^{2}-9}\right|+C .
\end{aligned}
$$

$$
\text { (iii) } \begin{aligned}
\int \frac{d x}{\sqrt{16 x^{2}+25}} & =\frac{1}{4} \cdot \int \frac{d x}{\sqrt{x^{2}+\frac{25}{16}}}=\frac{1}{4} \cdot \int \frac{d x}{\sqrt{x^{2}+\left(\frac{5}{4}\right)^{2}}} \\
& =\frac{1}{4} \cdot \log \left|x+\sqrt{x^{2}+\frac{25}{16}}\right|+C \\
& =\frac{1}{4} \log \left|4 x+\sqrt{16 x^{2}+25}\right|+C .
\end{aligned}
$$

---

### Example 2:

Evaluate $\int \frac{d x}{\sqrt{15-8 x^{2}}}$.
*[CBSE 2002C]*

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{15-8 x^{2}}} & =\frac{1}{\sqrt{8}} \cdot \int \frac{d x}{\sqrt{\frac{15}{8}-x^{2}}} \\
& =\frac{1}{2 \sqrt{2}} \sin ^{-1}\left\{\frac{x}{\sqrt{\frac{15}{8}}}\right\}+C=\frac{1}{2 \sqrt{2}} \sin ^{-1}\left(\sqrt{\frac{8}{15}} x\right)+C .
\end{aligned}
$$

---

### Example 3:

Evaluate $\int \frac{\cos x}{\sqrt{4-\sin ^{2} x}} d x$.

#### Solution:

Putting $\sin x=t$ and $\cos x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\cos x}{\sqrt{4-\sin ^{2} x}} d x & =\int \frac{d t}{\sqrt{4-t^{2}}}=\int \frac{d t}{\sqrt{2^{2}-t^{2}}} \\
& =\sin ^{-1} \frac{t}{2}+C=\sin ^{-1}\left(\frac{\sin x}{2}\right)+C
\end{aligned}
$$

---

### Example 4:

Evaluate $\int \frac{d x}{\sqrt{1-e^{2 x}}}$.

#### Solution:

Multiplying the numerator and denominator by $e^{-x}$, we get

$$
\begin{aligned}
\int \frac{d x}{\sqrt{1-e^{2 x}}} & =\int \frac{e^{-x} d x}{\sqrt{e^{-2 x}\left(1-e^{2 x}\right)}}=\int \frac{e^{-x}}{\sqrt{e^{-2 x}-1}} d x \\
& =-\int \frac{d t}{\sqrt{t^{2}-1}}\left[\text { putting } e^{-x}=t\right] \\
& =-\log \left|t+\sqrt{t^{2}-1}\right|+C \\
& =-\log \left|e^{-x}+\sqrt{e^{-2 x}-1}\right|+C
\end{aligned}
$$

---

### Example 5:

Evaluate $\int \frac{2^{x}}{\sqrt{1-4^{x}}} d x$.

#### Solution:

Putting $2^{x}=t$ and $\left(2^{x} \log 2\right) d x=d t$, we get

$$
\begin{aligned}
\int \frac{2^{x}}{\sqrt{1-4^{x}}} d x & =\frac{1}{(\log 2)} \cdot \int \frac{d t}{\sqrt{1-t^{2}}} \\
& =\frac{1}{(\log 2)} \cdot \sin ^{-1} t+C=\frac{1}{(\log 2)} \cdot \sin ^{-1}\left(2^{x}\right)+C
\end{aligned}
$$

---

### Example 6:

Evaluate $\int \frac{x^{2}}{\sqrt{x^{6}-1}} d x$.

#### Solution:

Putting $x^{3}=t$ and $x^{2} d x=\frac{1}{3} d t$, we get

$$
\begin{aligned}
\int \frac{x^{2}}{\sqrt{x^{6}-1}} d x & =\frac{1}{3} \int \frac{d t}{\sqrt{t^{2}-1}}=\frac{1}{3} \log \left|t+\sqrt{t^{2}-1}\right|+C \\
& =\frac{1}{3} \log \left|x^{3}+\sqrt{x^{6}-1}\right|+C
\end{aligned}
$$

---

### Example 7:

Evaluate:
(i) $\int \frac{\sin x}{\sqrt{4 \cos ^{2} x-1}} d x$
(ii) $\int \frac{\sec ^{2} x}{\sqrt{\tan ^{2} x-4}} d x$

#### Solution:

(i) Putting $\cos x=t$ and $-\sin x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\sin x}{\sqrt{4 \cos ^{2} x-1}} d x & =\int \frac{-d t}{\sqrt{4 t^{2}-1}}=-\frac{1}{2} \int \frac{d t}{\sqrt{t^{2}-(1 / 2)^{2}}} \\
& =-\frac{1}{2} \cdot \log \left|t+\sqrt{t^{2}-\frac{1}{4}}\right|+C \\
& =-\frac{1}{2} \log \left|2 t+\sqrt{4 t^{2}-1}\right|+C \\
& =-\frac{1}{2} \log \left|2 \cos x+\sqrt{4 \cos ^{2} x-1}\right|+C
\end{aligned}
$$

(ii) Putting $\tan x=t$ and $\sec ^{2} x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\sec ^{2} x}{\sqrt{\tan ^{2} x-4}} d x & =\int \frac{d t}{\sqrt{t^{2}-4}}=\log \left|t+\sqrt{t^{2}-4}\right|+C \\
& =\log \left|\tan x+\sqrt{\tan ^{2} x-4}\right|+C
\end{aligned}
$$

---

### Example 8:

Evaluate $\int \frac{x^{2}}{\sqrt{x^{6}+a^{6}}} d x$.

#### Solution:

Putting $x^{3}=t$ and $x^{2} d x=\frac{1}{3} d t$, we get

$$
\begin{aligned}
\int \frac{x^{2}}{\sqrt{x^{6}+a^{6}}} d x & =\frac{1}{3} \int \frac{d t}{\sqrt{t^{2}+\left(a^{3}\right)^{2}}}=\frac{1}{3} \log \left|t+\sqrt{t^{2}+a^{6}}\right|+C \\
& =\frac{1}{3} \log \left|x^{3}+\sqrt{x^{6}+a^{6}}\right|+C
\end{aligned}
$$

---

### Example 9:

Evaluate $\int \frac{\sec ^{2} x}{\sqrt{16+\tan ^{2} x}} d x$.

#### Solution:

Putting $\tan x=t$ and $\sec ^{2} x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\sec ^{2} x}{\sqrt{16+\tan ^{2} x}} d x & =\int \frac{d t}{\sqrt{16+t^{2}}}=\log \left|t+\sqrt{t^{2}+16}\right|+C \\
& =\log \left|\tan x+\sqrt{\tan ^{2} x+16}\right|+C
\end{aligned}
$$

---

### Example 10:

Evaluate $\int \sqrt{\frac{1-x}{1+x}} d x$.
*[CBSE 2006]*

#### Solution:

We have

$$
\begin{aligned}
\int \sqrt{\frac{1-x}{1+x}} d x & =\int\left\{\frac{\sqrt{1-x}}{\sqrt{1+x}} \times \frac{\sqrt{1-x}}{\sqrt{1-x}}\right\} d x \\
& =\int \frac{(1-x)}{\sqrt{1-x^{2}}} d x=\int \frac{d x}{\sqrt{1-x^{2}}}-\int \frac{x}{\sqrt{1-x^{2}}} d x \\
& =\sin ^{-1} x+\frac{1}{2} \cdot \int \frac{(-2 x)}{\sqrt{1-x^{2}}} d x \\
& =\sin ^{-1} x+\frac{1}{2} \int \frac{d t}{\sqrt{t}}, \text { where }\left(1-x^{2}\right)=t \operatorname{and}(-2 x) d x=d t \\
& =\sin ^{-1} x+\frac{1}{2} \int t^{-1 / 2} d t=\sin ^{-1} x+\frac{1}{2} \cdot \frac{t^{1 / 2}}{(1 / 2)}+C \\
& =\sin ^{-1} x+\sqrt{1-x^{2}}+C
\end{aligned}
$$

---

## Integrals of the form $\quad \int \frac{d x}{\sqrt{\left(a x^{2}+b x+c\right)}}$

### Method

$\operatorname{Put}\left(a x^{2}+b x+c\right)$ in the form $a\left\{(x+\alpha)^{2} \pm \beta^{2}\right\}$ and then integrate.

---

### Example 11:

Evaluate $\int \frac{d x}{\sqrt{x^{2}-3 x+2}}$.
*[CBSE 2006]*

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{x^{2}-3 x+2}} & =\int \frac{d x}{\sqrt{\left(x^{2}-3 x+\frac{9}{4}\right)-\frac{1}{4}}}=\int \frac{d x}{\sqrt{\left(x-\frac{3}{2}\right)^{2}-\left(\frac{1}{2}\right)^{2}}} \\
& =\int \frac{d z}{\sqrt{z^{2}-\left(\frac{1}{2}\right)^{2}}}, \text { where }\left(x-\frac{3}{2}\right)=z \\
& =\log \left|z+\sqrt{z^{2}-\frac{1}{4}}\right|+C \\
& \quad\left[\because \int \frac{d z}{\sqrt{z^{2}-a^{2}}}=\log \left|z+\sqrt{z^{2}-a^{2}}\right|+C\right] \\
& =\log \left|\left(x-\frac{3}{2}\right)+\sqrt{x^{2}-3 x+2}\right|+C
\end{aligned}
$$

---

### Example 12:

Evaluate $\int \frac{d x}{\sqrt{5 x^{2}-2 x}}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{5 x^{2}-2 x}} &=\frac{1}{\sqrt{5}} \cdot \int \frac{d x}{\sqrt{x^{2}-\frac{2}{5} x}}=\frac{1}{\sqrt{5}} \cdot \int \frac{d x}{\sqrt{x^{2}-\frac{2}{5} x+\left(\frac{1}{5}\right)^{2}-\left(\frac{1}{5}\right)^{2}}} \\
& =\frac{1}{\sqrt{5}} \cdot \int \frac{d x}{\sqrt{\left(x-\frac{1}{5}\right)^{2}-\left(\frac{1}{5}\right)^{2}}}=\frac{1}{\sqrt{5}} \cdot \int \frac{d t}{\sqrt{t^{2}-\left(\frac{1}{5}\right)^{2}}} \\
& \quad \text { where }\left(x-\frac{1}{5}\right)=t \\
& =\frac{1}{\sqrt{5}} \cdot \log \left|t+\sqrt{t^{2}-\left(\frac{1}{5}\right)^{2}}\right|+C \\
& =\frac{1}{\sqrt{5}} \log \left|\left(x-\frac{1}{5}\right)+\sqrt{x^{2}-\frac{2 x}{5}}\right|+C .
\end{aligned}
$$

---

### Example 13:

Evaluate $\int \frac{\cos x}{\sqrt{\sin ^{2} x-2 \sin x-3}} d x$.
*[CBSE 2006C]*

#### Solution:

Putting $\sin x=t$ and $\cos x d x=d t$, we get

$$
\begin{aligned}
\int \frac{\cos x}{\sqrt{\sin ^{2} x-2 \sin x-3}} d x & =\int \frac{d t}{\sqrt{t^{2}-2 t-3}}=\int \frac{d t}{\sqrt{(t-1)^{2}-2^{2}}} \\
& =\log \left|(t-1)+\sqrt{(t-1)^{2}-2^{2}}\right|+C \\
& =\log \left|(\sin x-1)+\sqrt{\sin ^{2} x-2 \sin x-3}\right|+C
\end{aligned}
$$

---

### Example 14:

Evaluate $\int \frac{e^{x}}{\sqrt{5-4 e^{x}-e^{2 x}}} d x$.
*[CBSE 2005C, '09]*

#### Solution:

Putting $e^{x}=t$ and $e^{x} d x=d t$, we get

$$
\begin{aligned}
\int \frac{e^{x}}{\sqrt{5-4 e^{x}-e^{2 x}}} d x & =\int \frac{d t}{\sqrt{5-4 t-t^{2}}}=\int \frac{d t}{\sqrt{5-\left(t^{2}+4 t+4\right)+4}} \\
& =\int \frac{d t}{\sqrt{9-(t+2)^{2}}}=\int \frac{d t}{\sqrt{3^{2}-(t+2)^{2}}} \\
& =\int \frac{d z}{\sqrt{3^{2}-z^{2}}}, \text { where }(t+2)=z \\
& =\sin ^{-1} \frac{z}{3}+C=\sin ^{-1} \frac{(t+2)}{3}+C \\
& =\sin ^{-1} \frac{\left(e^{x}+2\right)}{3}+C
\end{aligned}
$$

---

### Example 15:

Evaluate $\int \frac{d x}{\sqrt{2-4 x+x^{2}}}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{2-4 x+x^{2}}} & =\int \frac{d x}{\sqrt{x^{2}-4 x+4-2}}=\int \frac{d x}{\sqrt{(x-2)^{2}-(\sqrt{2})^{2}}} \\
& =\log \left|(x-2)+\sqrt{(x-2)^{2}-2}\right|+C \\
& =\log \left|x-2+\sqrt{x^{2}-4 x+2}\right|+C
\end{aligned}
$$

---

### Example 16:

Evaluate $\int \frac{d x}{\sqrt{3 x^{2}+6 x+12}}$.
*[CBSE 2004C]*

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{3 x^{2}+6 x+12}} & =\frac{1}{\sqrt{3}} \cdot \int \frac{d x}{\sqrt{x^{2}+2 x+4}} \\
& =\frac{1}{\sqrt{3}} \cdot \int \frac{d x}{\sqrt{(x+1)^{2}+(\sqrt{3})^{2}}} \\
& =\frac{1}{\sqrt{3}} \cdot \int \frac{d t}{\sqrt{t^{2}+(\sqrt{3})^{2}}}, \text { where }(x+1)=t \\
& =\frac{1}{\sqrt{3}} \log \left|t+\sqrt{t^{2}+3}\right|+C \\
& =\frac{1}{\sqrt{3}} \log \left|(x+1)+\sqrt{x^{2}+2 x+4}\right|+C
\end{aligned}
$$

---

### Example 17:

Evaluate $\int \frac{d x}{\sqrt{8+3 x-x^{2}}}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{8+3 x-x^{2}}} & =\int \frac{d x}{\sqrt{8-\left(x^{2}-3 x\right)}}=\int \frac{d x}{\sqrt{8-\left(x^{2}-3 x+\frac{9}{4}\right)+\frac{9}{4}}} \\
& =\int \frac{d x}{\sqrt{\left(\frac{\sqrt{41}}{2}\right)^{2}-\left(x-\frac{3}{2}\right)^{2}}}=\sin ^{-1}\left\{\frac{\left(x-\frac{3}{2}\right)}{\left(\frac{\sqrt{41}}{2}\right)}\right\}+C \\
& =\sin ^{-1}\left(\frac{2 x-3}{\sqrt{41}}\right)+C
\end{aligned}
$$

---

### Example 18:

Evaluate $\int \frac{d x}{\sqrt{2 x-x^{2}}}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{2 x-x^{2}}} & =\int \frac{d x}{\sqrt{1-\left(x^{2}-2 x+1\right)}} \\
& =\int \frac{d x}{\sqrt{1-(x-1)^{2}}}=\sin ^{-1}(x-1)+C
\end{aligned}
$$

---

### Example 19:

Evaluate $\int \frac{d x}{\sqrt{x(1-2 x)}}$.

#### Solution:

We have

$$
\begin{aligned}
\int \frac{d x}{\sqrt{x(1-2 x)}} & =\int \frac{d x}{\sqrt{x-2 x^{2}}} \\
& =\frac{1}{\sqrt{2}} \cdot \int \frac{d x}{\sqrt{\frac{x}{2}-x^{2}}}=\frac{1}{\sqrt{2}} \int \frac{d x}{\sqrt{-\left(x^{2}-\frac{x}{2}+\frac{1}{16}\right)+\frac{1}{16}}} \\
& =\frac{1}{\sqrt{2}} \int \frac{d x}{\left.\sqrt{\frac{1}{16}-\left\{x^{2}-\frac{x}{2}+\frac{1}{16}\right.}\right\}}=\frac{1}{\sqrt{2}} \cdot \int \frac{d x}{\sqrt{\left(\frac{1}{4}\right)^{2}-\left(x-\frac{1}{4}\right)^{2}}} \\
& =\frac{1}{\sqrt{2}} \int \frac{d t}{\sqrt{\left(\frac{1}{4}\right)^{2}-t^{2}}}, \text { where }\left(x-\frac{1}{4}\right)=t \\
& =\frac{1}{\sqrt{2}} \sin ^{-1} \frac{t}{(1 / 4)}+C=\frac{1}{\sqrt{2}} \sin ^{-1}(4 t)+C=\frac{1}{\sqrt{2}} \sin ^{-1} 4\left(x-\frac{1}{4}\right)+C \\
& =\frac{1}{\sqrt{2}} \sin ^{-1}(4 x-1)+C .
\end{aligned}
$$

---

## Integrals of the form $\int \frac{(p x+q)}{\sqrt{\left(a x^{2}+b x+c\right)}} d x$

### Method

Let $(p x+q)=A \cdot \frac{d}{d x}\left(a x^{2}+b x+c\right)+B$.
Now, the value of the integral can be obtained easily.

---

### Example 20:

Evaluate $\int \frac{(5 x+3)}{\sqrt{x^{2}+4 x+10}} d x$.
*[CBSE 2011, 12]*

#### Solution:

Let $(5 x+3)=A \cdot \frac{d}{d x}\left(x^{2}+4 x+10\right)+B$.
Then, $(5 x+3)=A(2 x+4)+B$.
Comparing the coefficients of like powers of $x$, we get

$$
(2 A=5 \text { and } 4 A+B=3) \Rightarrow\left(A=\frac{5}{2} \text { and } B=-7\right)
$$

$$
\begin{aligned}
\therefore \int \frac{(5 x+3)}{\sqrt{x^{2}+4 x+10}} d x &=\int\left\{\frac{\frac{5}{2} \cdot(2 x+4)-7}{\sqrt{x^{2}+4 x+10}}\right\} d x \\
& =\frac{5}{2} \cdot \int \frac{(2 x+4)}{\sqrt{x^{2}+4 x+10}} d x-7 \int \frac{d x}{\sqrt{x^{2}+4 x+10}} \\
& =\frac{5}{2} \cdot \int \frac{1}{\sqrt{t}} d t-7 \int \frac{d x}{\sqrt{(x+2)^{2}+(\sqrt{6})^{2}}}, \text { where } t=x^{2}+4 x+10 \\
& =\left(\frac{5}{2} \times 2 \sqrt{t}\right)-7 \log \left|(x+2)+\sqrt{x^{2}+4 x+10}\right|+C \\
& =5 \sqrt{x^{2}+4 x+10}-7 \log \left|(x+2)+\sqrt{x^{2}+4 x+10}\right|+C
\end{aligned}
$$

---

### Example 21:

Evaluate $\int \frac{(x+1)}{\sqrt{4+5 x-x^{2}}} d x$.

#### Solution:

Let $(x+1)=A \cdot \frac{d}{d x}\left(4+5 x-x^{2}\right)+B$. Then,

$$
(x+1)=A(5-2 x)+B .
$$

Comparing the coefficients of like powers of $x$, we get
$(-2 A=1$ and $5 A+B=1) \Rightarrow\left(A=-\frac{1}{2}\right.$ and $\left.B=\frac{7}{2}\right)$.
$\therefore(x+1)=-\frac{1}{2}(5-2 x)+\frac{7}{2}$.

$$
\begin{aligned}
\therefore \int \frac{(x+1)}{\sqrt{4+5 x-x^{2}}} d x &=\int \frac{-\frac{1}{2}(5-2 x)+\frac{7}{2}}{\sqrt{4+5 x-x^{2}}} d x \\
&=-\frac{1}{2} \int \frac{(5-2 x)}{\sqrt{4+5 x-x^{2}}} d x+\frac{7}{2} \int \frac{1}{\sqrt{4+5 x-x^{2}}} d x \\
&=-\frac{1}{2} \int \frac{1}{\sqrt{t}} d t+\frac{7}{2} \cdot \int \frac{1}{\sqrt{4-\left(x^{2}-5 x\right)}} d x, \text { where } t=4+5 x-x^{2} \\
&=-\frac{1}{2} \cdot 2 \sqrt{t}+\frac{7}{2} \cdot \int \frac{d x}{\sqrt{4-\left(x^{2}-5 x+\frac{25}{4}\right)+\frac{25}{4}}} \\
&=-\sqrt{t}+\frac{7}{2} \cdot \int \frac{d x}{\sqrt{\left(\frac{\sqrt{41}}{2}\right)^{2}-\left(x-\frac{5}{2}\right)^{2}}} \\
&=-\sqrt{4+5 x-x^{2}}+\frac{7}{2} \cdot \sin ^{-1} \frac{\left(x-\frac{5}{2}\right)}{\left(\frac{\sqrt{41}}{2}\right)}+C \\
&=-\sqrt{4+5 x-x^{2}}+\frac{7}{2} \sin ^{-1}\left(\frac{2 x-5}{\sqrt{41}}\right)+C .
\end{aligned}
$$

---

### Example 22:

Evaluate $\int \frac{(x+3)}{\sqrt{5-4 x-x^{2}}} d x$.

#### Solution:

Let $(x+3)=A \cdot \frac{d}{d x}\left(5-4 x-x^{2}\right)+B$. Then,

$$
(x+3)=A(-4-2 x)+B .
$$

Comparing the coefficients of like powers of $x$, we get

$$
(-2 A=1 \text { and }-4 A+B=3) \Rightarrow\left(A=\frac{-1}{2}, B=1\right)
$$

$$
\begin{aligned}
\therefore \int \frac{(x+3)}{\sqrt{5-4 x-x^{2}}} d x &=-\frac{1}{2} \cdot \int \frac{(-4-2 x)}{\sqrt{5-4 x-x^{2}}} d x+\int \frac{d x}{\sqrt{5-4 x-x^{2}}} \\
&=-\frac{1}{2} \int \frac{d t}{\sqrt{t}}+\int \frac{d x}{\sqrt{5-\left(x^{2}+4 x+4\right)+4}}, \\
& \text { where }\left(5-4 x-x^{2}\right)=t \\
& =-\frac{1}{2} \cdot \frac{t^{1 / 2}}{(1 / 2)}+\int \frac{d x}{\sqrt{3^{2}-(x+2)^{2}}} \\
& =-\sqrt{t}+\sin ^{-1} \frac{(x+2)}{3}+C \\
& =-\sqrt{5-4 x-x^{2}}+\sin ^{-1} \frac{(x+2)}{3}+C .
\end{aligned}
$$

---