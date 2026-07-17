## 12. Indefinite Integral

**Integration** It is the inverse process of differentiation.
If the derivative of $F(x)$ is $f(x)$ then we say that the **antiderivative** or **integral** of $f(x)$ is $F(x)$ and we write,

$$
\int f(x) d x=F(x)
$$

Thus,

$$
\frac{d}{d x}[F(x)]=f(x) \Rightarrow \int f(x) d x=F(x)
$$

**Example** Since $\frac{d}{d x}(\sin x)=\cos x$, we have $\int \cos x d x=\sin x$.
Moreover, if $C$ is any constant then $\frac{d}{d x}(\sin x+C)=\cos x$.
So, in general, $\int \cos x d x=(\sin x+C)$.
Clearly, different values of $C$ will give different integrals.
Thus, a given function may have an indefinite number of integrals. Because of this property, we call these integrals **indefinite integrals**.

Thus, $\frac{d}{d x}[F(x)]=f(x) \Rightarrow \int f(x) d x=F(x)+C$, where $C$ is a constant, called the **constant of integration**. Any function to be integrated is known as an **integrand**.

The following two results are a direct consequence of the definition of an integral.

**RESULT 1** $\int x^{n} d x=\frac{x^{(n+1)}}{(n+1)}+C$, when $n \neq-1$.

**PROOF** We have, $\frac{d}{d x}\left(\frac{x^{n+1}}{n+1}\right)=\frac{(n+1) x^{n}}{(n+1)}=x^{n}$.

$$
\therefore \quad \int x^{n} d x=\frac{x^{(n+1)}}{(n+1)}+C
$$

Thus, we have
- (i) $\int x^{6} d x=\frac{x^{(6+1)}}{(6+1)}+C=\frac{x^{7}}{7}+C$.

$$
\begin{aligned}
& \text { (ii) } \int x^{2 / 3} d x=\frac{x^{\left(\frac{2}{3}+1\right)}}{\left(\frac{2}{3}+1\right)}+C=\frac{3}{5} x^{5 / 3}+C \\
& \text { (iii) } \int x^{-3 / 4} d x=\frac{x^{\left(-\frac{3}{4}+1\right)}}{\left(-\frac{3}{4}+1\right)}=4 x^{1 / 4}+C
\end{aligned}
$$

**RESULT 2** $\int \frac{1}{x} d x=\log |x|+C$, where $x \neq 0$.

**PROOF** Clearly, either $x>0$ or $x<0$.

**Case I** When $x>0$
In this case, $|x|=x$.
$\therefore \frac{d}{d x}[\log |x|]=\frac{d}{d x}(\log x)=\frac{1}{x}$.
So, we have, $\int \frac{1}{x} d x=\log |x|+C$.

**Case II** When $x<0$
In this case $|x|=-x$.
$\therefore \quad \frac{d}{d x}[\log |x|]=\frac{d}{d x}[\log (-x)]=\frac{1}{(-x)} \cdot(-1)=\frac{1}{x}$.
So, we have $\int \frac{1}{x} d x=\log |x|+C$.
Thus, from both the cases, we have $\int \frac{1}{x} d x=\log |x|+C$.

---

## Formulae

On the basis of differentiation and the definition of integration, we have the following results.

1.  $\frac{d}{d x}\left(\frac{x^{n+1}}{n+1}\right)=x^{n}, n \neq-1 \Rightarrow \int x^{n} d x=\frac{x^{n+1}}{(n+1)}+C$
2.  $\frac{d}{d x}(\log |x|)=\frac{1}{x} \Rightarrow \int \frac{1}{x} d x=\log |x|+C$
3.  $\frac{d}{d x}\left(e^{x}\right)=e^{x} \Rightarrow \int e^{x} d x=e^{x}+C$
4.  $\frac{d}{d x}\left(\frac{a^{x}}{\log a}\right)=a^{x} \Rightarrow \int a^{x} d x=\frac{a^{x}}{\log a}+C$
5.  $\frac{d}{d x}(\sin x)=\cos x \Rightarrow \int \cos x d x=\sin x+C$
6.  $\frac{d}{d x}(-\cos x)=\sin x \Rightarrow \int \sin x d x=-\cos x+C$
7.  $\frac{d}{d x}(\tan x)=\sec ^{2} x \Rightarrow \int \sec ^{2} x d x=\tan x+C$
8.  $\frac{d}{d x}(-\cot x)=\operatorname{cosec}^{2} x \Rightarrow \int \operatorname{cosec}^{2} x d x=-\cot x+C$
9.  $\frac{d}{d x}(\sec x)=\sec x \tan x \Rightarrow \int \sec x \tan x d x=\sec x+C$
10. $\frac{d}{d x}(-\operatorname{cosec} x)=\operatorname{cosec} x \cot x \Rightarrow \int \operatorname{cosec} x \cot x d x=-\operatorname{cosec} x+C$
11. $\frac{d}{d x}\left(\sin ^{-1} x\right)=\frac{1}{\sqrt{1-x^{2}}} \Rightarrow \int \frac{1}{\sqrt{1-x^{2}}} d x=\sin ^{-1} x+C$
12. $\frac{d}{d x}\left(\tan ^{-1} x\right)=\frac{1}{\left(1+x^{2}\right)} \Rightarrow \int \frac{1}{\left(1+x^{2}\right)} d x=\tan ^{-1} x+C$
13. $\frac{d}{d x}\left(\sec ^{-1} x\right)=\frac{1}{x \sqrt{x^{2}-1}} \Rightarrow \int \frac{1}{x \sqrt{x^{2}-1}} d x=\sec ^{-1} x+C$

With the help of the above formulae, it is easy to evaluate the following integrals.

### Example 1:

Evaluate:
- (i) $\int x^{9} d x$
- (ii) $\int \sqrt[3]{x} d x$
- (iii) $\int d x$
- (iv) $\int \frac{1}{x^{2}} d x$
- (v) $\int \frac{1}{x^{1 / 3}} d x$
- (vi) $\int 5^{x} d x$

#### Solution:

Using the standard formulae, we have
- (i) $\int x^{9} d x=\frac{x^{(9+1)}}{(9+1)}+C=\frac{x^{10}}{10}+C$.
- (ii) $\int \sqrt[3]{x} d x=\int x^{1 / 3} d x=\frac{x^{\left(\frac{1}{3}+1\right)}}{\left(\frac{1}{3}+1\right)}+C=\frac{3}{4} x^{4 / 3}+C$.
- (iii) $\int d x=\int x^{0} d x=\frac{x^{(0+1)}}{(0+1)}+C=x+C$.
- (iv) $\int \frac{1}{x^{2}} d x=\int x^{-2} d x=\frac{x^{(-2+1)}}{(-2+1)}+C=-\frac{1}{x}+C$.
- (v) $\int \frac{1}{x^{1 / 3}} d x=\int x^{-1 / 3} d x=\frac{x^{\left(-\frac{1}{3}+1\right)}}{\left(-\frac{1}{3}+1\right)}+C=\frac{3}{2} x^{2 / 3}+C$.
- (vi) $\int 5^{x} d x=\frac{5^{x}}{\log 5}+C$.

---

## Some Standard Results on Integration

**THEOREM 1** $\frac{d}{d x}\left\{\int f(x) d x\right\}=f(x)$.

**PROOF** Let $\int f(x) d x=F(x)$. (i)

Then, $\frac{d}{d x}\{F(x)\}=f(x)$ [by def. of integral].
$\therefore \quad \frac{d}{d x}\left\{\int f(x) d x\right\}=f(x) \quad$ [using (i)].

---

**THEOREM 2** $\int k \cdot f(x) d x=k \cdot \int f(x) d x$, where $k$ is a constant.

**PROOF** Let $\int f(x) d x=F(x)$. (i)

Then, $\frac{d}{d x}\{F(x)\}=f(x)$. (ii)
$\therefore \quad \frac{d}{d x}\{k \cdot F(x)\}=k \cdot \frac{d}{d x}\{F(x)\}=k \cdot f(x) \quad$ [using (ii)].
So, by the definition of an integral, we have

$$
\int\{k \cdot f(x)\} d x=k \cdot F(x)=k \cdot \int f(x) d x \quad[\text { using }(\mathrm{i})]
$$

### Example 2:

Evaluate:
- (i) $\int 3 x^{2} d x$
- (ii) $\int 2^{(x+3)} d x$

#### Solution:

- (i) $\int 3 x^{2} d x=3 \int x^{2} d x=3 \cdot \frac{x^{3}}{3}+C=x^{3}+C$.
- (ii) $\int 2^{(x+3)} d x=\int 2^{x} \cdot 2^{3} d x=8 \int 2^{x} d x=8 \cdot \frac{2^{x}}{\log 2}+C=\frac{2^{(x+3)}}{\log 2}+C$.

---

**THEOREM 3**
- (i) $\int\left\{f_{1}(x)+f_{2}(x)\right\} d x=\int f_{1}(x) d x+\int f_{2}(x) d x$
- (ii) $\int\left\{f_{1}(x)-f_{2}(x)\right\} d x=\int f_{1}(x) d x-\int f_{2}(x) d x$

**PROOF** (i) Let $\int f_{1}(x) d x=F_{1}(x)$ and $\int f_{2}(x) d x=F_{2}(x)$. (i)

Then, $\frac{d}{d x}\left\{F_{1}(x)\right\}=f_{1}(x)$ and $\frac{d}{d x}\left\{F_{2}(x)\right\}=f_{2}(x)$. (ii)

Now, $\frac{d}{d x}\left\{F_{1}(x)+F_{2}(x)\right\}=\frac{d}{d x}\left\{F_{1}(x)\right\}+\frac{d}{d x}\left\{F_{2}(x)\right\}$

$$
=f_{1}(x)+f_{2}(x) \quad[\text { using }(\mathrm{ii})] .
$$

$$
\begin{aligned}
\therefore \int\left\{f_{1}(x)+f_{2}(x)\right\} d x & =F_{1}(x)+F_{2}(x) \\
& =\int f_{1}(x) d x+\int f_{2}(x) d x \quad \text { [using (i)].}
\end{aligned}
$$

Similarly, (ii) can be proved.

**REMARK** In general, we have

$$
\begin{aligned}
\int\left\{k_{1} \cdot f_{1}(x) \pm\right. & \left.k_{2} \cdot f_{2}(x) \pm \ldots \pm k_{n} \cdot f_{n}(x)\right\} d x \\
& =k_{1} \cdot \int f_{1}(x) d x \pm k_{2} \cdot \int f_{2}(x) d x \pm \ldots \pm k_{n} \cdot \int f_{n}(x) d x
\end{aligned}
$$

---

## Solved Examples

### Example 1:

Evaluate:
- (i) $\int\left(5 x^{3}+2 x^{-5}-7 x+\frac{1}{\sqrt{x}}+\frac{5}{x}\right) d x$
- (ii) $\int\left(3 \sin x-4 \cos x+5 \sec ^{2} x-2 \operatorname{cosec}^{2} x\right) d x$
- (iii) $\int(1-x)(2+3 x)(5-4 x) d x$
- (iv) $\int\left(\frac{3 x^{4}-5 x^{3}+4 x^{2}-x+2}{x^{3}}\right) d x$
- (v) $\int\left(x^{2}+\frac{1}{x^{2}}\right)^{3} d x$

#### Solution:

(i) $\int\left(5 x^{3}+2 x^{-5}-7 x+\frac{1}{\sqrt{x}}+\frac{5}{x}\right) d x$

$$
\begin{aligned}
& =5 \int x^{3} d x+2 \int x^{-5} d x-7 \int x d x+\int x^{-1 / 2} d x+5 \int \frac{1}{x} d x \\
& =5 \cdot \frac{x^{4}}{4}+2 \cdot \frac{x^{-4}}{(-4)}-7 \cdot \frac{x^{2}}{2}+\frac{x^{1 / 2}}{(1 / 2)}+5 \log |x|+C \\
& =\frac{5 x^{4}}{4}-\frac{1}{2 x^{4}}-\frac{7 x^{2}}{2}+2 \sqrt{x}+5 \log |x|+C
\end{aligned}
$$

(ii) $\int\left(3 \sin x-4 \cos x+5 \sec ^{2} x-2 \operatorname{cosec}^{2} x\right) d x$

$$
\begin{aligned}
& =3 \int \sin x d x-4 \int \cos x d x+5 \int \sec ^{2} x d x-2 \int \operatorname{cosec}^{2} x d x \\
& =3(-\cos x)-4 \sin x+5 \tan x-2(-\cot x)+C \\
& =(-3 \cos x-4 \sin x+5 \tan x+2 \cot x+C)
\end{aligned}
$$

(iii) $\int(1-x)(2+3 x)(5-4 x) d x=\int\left(10-3 x-19 x^{2}+12 x^{3}\right) d x$

$$
\begin{aligned}
& =10 \int d x-3 \int x d x-19 \int x^{2} d x+12 \int x^{3} d x \\
& =10 x-3 \cdot \frac{x^{2}}{2}-19 \cdot \frac{x^{3}}{3}+12 \cdot \frac{x^{4}}{4}+C \\
& =10 x-\frac{3 x^{2}}{2}-\frac{19 x^{3}}{3}+3 x^{4}+C
\end{aligned}
$$

(iv) $\int\left(\frac{3 x^{4}-5 x^{3}+4 x^{2}-x+2}{x^{3}}\right) d x=\int\left(3 x-5+\frac{4}{x}-\frac{1}{x^{2}}+\frac{2}{x^{3}}\right) d x$
[dividing each term by $x^{3}$]

$$
\begin{aligned}
& =3 \int x d x-5 \int d x+4 \int \frac{1}{x} d x-\int x^{-2} d x+2 \int x^{-3} d x \\
& =3 \cdot \frac{x^{2}}{2}-5 x+4 \log |x|-\left(-\frac{1}{x}\right)+2\left(\frac{x^{-2}}{-2}\right)+C \\
& =\frac{3 x^{2}}{2}-5 x+4 \log |x|+\frac{1}{x}-\frac{1}{x^{2}}+C .
\end{aligned}
$$

(v) $\int\left(x^{2}+\frac{1}{x^{2}}\right)^{3} d x=\int\left(x^{6}+\frac{1}{x^{6}}+3 x^{2}+\frac{3}{x^{2}}\right) d x$
$$
\begin{aligned}
& =\int x^{6} d x+\int x^{-6} d x+3 \int x^{2} d x+3 \int \frac{1}{x^{2}} d x \\
& =\frac{x^{7}}{7}+\frac{x^{-5}}{(-5)}+3 \cdot \frac{x^{3}}{3}+3 \cdot\left(-\frac{1}{x}\right)+C \\
& =\frac{x^{7}}{7}-\frac{1}{5 x^{5}}+x^{3}-\frac{3}{x}+C
\end{aligned}
$$

---

### Example 2:

Evaluate:
- (i) $\int \frac{\left(x^{3}+4 x^{2}-3 x-2\right)}{(x+2)} d x$
- (ii) $\int\left(\frac{x^{4}+1}{x^{2}+1}\right) d x$ [CBSE 2011]

#### Solution:

(i) On dividing $\left(x^{3}+4 x^{2}-3 x-2\right)$ by $(x+2)$, we get

$$
\begin{aligned}
\int \frac{\left(x^{3}+4 x^{2}-3 x-2\right)}{(x+2)} d x & =\int\left\{x^{2}+2 x-7+\frac{12}{x+2}\right\} d x \\
& =\int x^{2} d x+2 \int x d x-7 \int d x+12 \int \frac{1}{x+2} d x \\
& =\frac{x^{3}}{3}+2 \cdot \frac{x^{2}}{2}-7 x+12 \log |x+2|+C \\
& =\frac{x^{3}}{3}+x^{2}-7 x+12 \log |x+2|+C
\end{aligned}
$$

(ii) On dividing $\left(x^{4}+1\right)$ by $\left(x^{2}+1\right)$, we get

$$
\begin{aligned}
\int\left(\frac{x^{4}+1}{x^{2}+1}\right) d x & =\int\left[x^{2}-1+\frac{2}{\left(x^{2}+1\right)}\right] d x \\
& =\int x^{2} d x-\int d x+2 \int \frac{1}{x^{2}+1} d x \\
& =\frac{x^{3}}{3}-x+2 \tan ^{-1} x+C
\end{aligned}
$$

---

### Example 3:

Evaluate:
- (i) $\int \tan ^{2} x d x$
- (ii) $\int \cot ^{2} x d x$
- (iii) $\int \sin ^{2} \frac{x}{2} d x$

#### Solution:

(i) $\int \tan ^{2} x d x=\int\left(\sec ^{2} x-1\right) d x$

$$
=\int \sec ^{2} x d x-\int d x=\tan x-x+C
$$

(ii) $\int \cot ^{2} x d x=\int\left(\operatorname{cosec}^{2} x-1\right) d x$

$$
=\int \operatorname{cosec}^{2} x d x-\int d x=-\cot x-x+C
$$

(iii) We know that $2 \sin ^{2} \frac{x}{2}=(1-\cos x)$.

$$
\begin{aligned}
\therefore \quad \int \sin ^{2} \frac{x}{2} d x & =\frac{1}{2} \int(1-\cos x) d x \\
& =\frac{1}{2}\left[\int d x-\int \cos x d x\right]=\frac{1}{2} x-\frac{1}{2} \sin x+C
\end{aligned}
$$

---

### Example 4:

Evaluate $\int \sqrt{1-\sin 2 x} d x$. [CBSE 2004]

#### Solution:

$$
\begin{aligned}
\int \sqrt{1-\sin 2 x} d x & =\int\left(\cos ^{2} x+\sin ^{2} x-2 \sin x \cos x\right)^{1 / 2} d x \\
& =\int \sqrt{(\cos x-\sin x)^{2}} d x \\
& =\int(\cos x-\sin x) d x=\int \cos x d x-\int \sin x d x \\
& =\sin x-(-\cos x)+C=\sin x+\cos x+C
\end{aligned}
$$

---

### Example 5:

Evaluate:
- (i) $\int \frac{d x}{1+\sin x}$ [CBSE 2002C]
- (ii) $\int\left(\frac{\sin x}{1+\sin x}\right) d x$

#### Solution:

(i)
$$
\begin{aligned}
\int \frac{d x}{(1+\sin x)} & =\int \frac{1}{(1+\sin x)} \times \frac{(1-\sin x)}{(1-\sin x)} d x \\
& =\int \frac{(1-\sin x)}{\left(1-\sin ^{2} x\right)} d x=\int \frac{(1-\sin x)}{\cos ^{2} x} d x \\
& =\int\left(\frac{1}{\cos ^{2} x}-\frac{\sin x}{\cos ^{2} x}\right) d x=\int\left(\sec ^{2} x-\sec x \tan x\right) d x \\
& =\int \sec ^{2} x d x-\int \sec x \tan x d x=\tan x-\sec x+C
\end{aligned}
$$

(ii) $\int\left(\frac{\sin x}{1+\sin x}\right) d x=\int \frac{(1+\sin x)-1}{(1+\sin x)} d x$

$$
\begin{gathered}
=\int\left(1-\frac{1}{1+\sin x}\right) d x=\int d x-\int \frac{1}{(1+\sin x)} d x \\
=\int d x-\int \frac{1}{(1+\sin x)} \times \frac{(1-\sin x)}{(1-\sin x)} d x \\
=\int d x-\int \frac{(1-\sin x)}{\cos ^{2} x} d x=\int d x-\int\left(\frac{1}{\cos ^{2} x}-\frac{\sin x}{\cos ^{2} x}\right) d x \\
=\int d x-\int \sec ^{2} x d x+\int \sec x \tan x d x=x-\tan x+\sec x+C
\end{gathered}
$$

---

### Example 6:

Evaluate $\int \frac{\sec x}{(\sec x+\tan x)} d x$.

#### Solution:

$$
\begin{aligned}
\int \frac{\sec x}{(\sec x+\tan x)} d x & =\int \frac{\sec x}{(\sec x+\tan x)} \times \frac{(\sec x-\tan x)}{(\sec x-\tan x)} d x \\
& =\int \frac{\left(\sec ^{2} x-\sec x \tan x\right)}{\left(\sec ^{2} x-\tan ^{2} x\right)} d x \\
& =\int\left(\sec ^{2} x-\sec x \tan x\right) d x \\
& =\int \sec ^{2} x d x-\int \sec x \tan x d x=\tan x-\sec x+C
\end{aligned}
$$

---

### Example 7:

Evaluate:
- (i) $\int\left(\frac{4-5 \cos x}{\sin ^{2} x}\right) d x$
- (ii) $\int\left(\frac{1-\cos 2 x}{1+\cos 2 x}\right) d x$
- (iii) $\int \frac{1}{\sin ^{2} x \cos ^{2} x} d x$ [CBSE 2014]
- (iv) $\int \frac{\cos 2 x}{\cos ^{2} x \sin ^{2} x} d x$

#### Solution:

(i)
$$
\begin{aligned}
\int\left(\frac{4-5 \cos x}{\sin ^{2} x}\right) d x & =\int\left(\frac{4}{\sin ^{2} x}-\frac{5 \cos x}{\sin ^{2} x}\right) d x \\
& =\int\left(4 \operatorname{cosec}^{2} x-5 \operatorname{cosec} x \cot x\right) d x \\
& =4 \int \operatorname{cosec}^{2} x d x-5 \int \operatorname{cosec} x \cot x d x \\
& =4(-\cot x)-5(-\operatorname{cosec} x)+C \\
& =-4 \cot x+5 \operatorname{cosec} x+C
\end{aligned}
$$

(ii) $\int\left(\frac{1-\cos 2 x}{1+\cos 2 x}\right) d x=\int \frac{2 \sin ^{2} x}{2 \cos ^{2} x} d x=\int \tan ^{2} x d x$

$$
\begin{aligned}
& =\int\left(\sec ^{2} x-1\right) d x=\int \sec ^{2} x d x-\int d x \\
& =\tan x-x+C
\end{aligned}
$$

(iii) $\int \frac{1}{\sin ^{2} x \cos ^{2} x} d x=\int\left(\frac{\sin ^{2} x+\cos ^{2} x}{\sin ^{2} x \cos ^{2} x}\right) d x$

$$
\begin{aligned}
& =\int\left(\frac{1}{\cos ^{2} x}+\frac{1}{\sin ^{2} x}\right) d x \\
& =\int \sec ^{2} x d x+\int \operatorname{cosec}^{2} x d x=\tan x-\cot x+C
\end{aligned}
$$

(iv)
$$
\begin{aligned}
\int \frac{\cos 2 x}{\cos ^{2} x \sin ^{2} x} d x & =\int\left(\frac{\cos ^{2} x-\sin ^{2} x}{\cos ^{2} x \sin ^{2} x}\right) d x \\
& =\int\left(\frac{1}{\sin ^{2} x}-\frac{1}{\cos ^{2} x}\right) d x \\
& =\int \operatorname{cosec}^{2} x d x-\int \sec ^{2} x d x=-\cot x-\tan x+C
\end{aligned}
$$

---

### Example 8:

Evaluate $\int\left(\frac{\cos 2 x-\cos 2 \alpha}{\cos x-\cos \alpha}\right) d x$. [CBSE 2013]

#### Solution:

$\int\left(\frac{\cos 2 x-\cos 2 \alpha}{\cos x-\cos \alpha}\right) d x=\int \frac{\left(2 \cos ^{2} x-1\right)-\left(2 \cos ^{2} \alpha-1\right)}{(\cos x-\cos \alpha)} d x$

$$
\begin{aligned}
& =2 \int \frac{\left(\cos ^{2} x-\cos ^{2} \alpha\right)}{(\cos x-\cos \alpha)} d x=2 \int(\cos x+\cos \alpha) d x \\
& =2 \int \cos x d x+2 \cos \alpha \cdot \int d x=2 \sin x+2 x \cos \alpha+C .
\end{aligned}
$$

---

### Example 9:

Evaluate $\int \tan ^{-1}\left\{\sqrt{\frac{1-\cos 2 x}{1+\cos 2 x}}\right\} d x$. [CBSE 2003]

#### Solution:

$\int \tan ^{-1}\left\{\sqrt{\frac{1-\cos 2 x}{1+\cos 2 x}}\right\} d x=\int \tan ^{-1}\left\{\sqrt{\frac{2 \sin ^{2} x}{2 \cos ^{2} x}}\right\} d x$

$$
=\int \tan ^{-1}(\tan x) d x=\int x d x=\frac{x^{2}}{2}+C
$$

---

### Example 10:

Evaluate $\int \sin ^{-1}(\cos x) d x$.

#### Solution:

$\int \sin ^{-1}(\cos x) d x=\int \sin ^{-1}\left\{\sin \left(\frac{\pi}{2}-x\right)\right\} d x$

$$
=\int\left(\frac{\pi}{2}-x\right) d x=\frac{\pi}{2} \cdot \int d x-\int x d x=\frac{\pi x}{2}-\frac{x^{2}}{2}+C
$$

---

### Example 11:

Evaluate $\int \tan ^{-1}(\sec x+\tan x) d x$.

#### Solution:

$\int \tan ^{-1}(\sec x+\tan x) d x=\int \tan ^{-1}\left(\frac{1}{\cos x}+\frac{\sin x}{\cos x}\right) d x$

$$
\begin{aligned}
& =\int \tan ^{-1}\left(\frac{1+\sin x}{\cos x}\right) d x=\int \tan ^{-1}\left\{\frac{1-\cos \left(\frac{\pi}{2}+x\right)}{\sin \left(\frac{\pi}{2}+x\right)}\right\} d x \\
& =\int \tan ^{-1}\left\{\frac{2 \sin ^{2}\left(\frac{\pi}{4}+\frac{x}{2}\right)}{2 \sin \left(\frac{\pi}{4}+\frac{x}{2}\right) \cos \left(\frac{\pi}{4}+\frac{x}{2}\right)}\right\} d x \\
& =\int \tan ^{-1}\left\{\tan \left(\frac{\pi}{4}+\frac{x}{2}\right)\right\} d x=\int\left(\frac{\pi}{4}+\frac{x}{2}\right) d x \\
& =\frac{\pi}{4} \cdot \int d x+\frac{1}{2} \int x d x=\frac{\pi x}{4}+\frac{1}{4} x^{2}+C
\end{aligned}
$$

---

### Example 12:

Evaluate $\int\left(\frac{1+\sin x}{1-\sin x}\right) d x$. [CBSE 2008C]

#### Solution:

$I=\int \frac{(1+\sin x)}{(1-\sin x)} \times \frac{(1+\sin x)}{(1+\sin x)} d x$

$$
\begin{aligned}
& =\int \frac{(1+\sin x)^{2}}{\left(1-\sin ^{2} x\right)} d x=\int \frac{\left(1+\sin ^{2} x+2 \sin x\right)}{\cos ^{2} x} d x \\
& =\int\left(\frac{1}{\cos ^{2} x}+\frac{\sin ^{2} x}{\cos ^{2} x}+\frac{2 \sin x}{\cos ^{2} x}\right) d x=\int\left(\sec ^{2} x+\tan ^{2} x+2 \sec x \tan x\right) d x \\
& =\int\left(2 \sec ^{2} x-1+2 \sec x \tan x\right) d x \\
& =2 \int \sec ^{2} x d x-\int d x+2 \int \sec x \tan x d x \\
& =2 \tan x-x+2 \sec x+C
\end{aligned}
$$

---

### Example 13:

Evaluate $\int \frac{\left(\sin ^{6} x+\cos ^{6} x\right)}{\sin ^{2} x \cos ^{2} x} d x$. [CBSE 2014]

#### Solution:

Using the formula, $\left(a^{3}+b^{3}\right)=(a+b)^{3}-3 a b(a+b)$, we get

$$
\begin{aligned}
I & =\int \frac{\left(\sin ^{2} x+\cos ^{2} x\right)^{3}-3 \sin ^{2} x \cos ^{2} x\left(\sin ^{2} x+\cos ^{2} x\right)}{\sin ^{2} x \cos ^{2} x} d x \\
& =\int \frac{\left(1-3 \sin ^{2} x \cos ^{2} x\right)}{\sin ^{2} x \cos ^{2} x} d x=\int\left\{\frac{1}{\sin ^{2} x \cos ^{2} x}-3\right\} d x \\
& =\int\left\{\frac{\left(\sin ^{2} x+\cos ^{2} x\right)}{\sin ^{2} x \cos ^{2} x}-3\right\} d x=\int\left\{\frac{1}{\cos ^{2} x}+\frac{1}{\sin ^{2} x}-3\right\} d x \\
& =\int\left(\sec ^{2} x+\operatorname{cosec}^{2} x-3\right) d x=\tan x-\cot x-3 x+C
\end{aligned}
$$