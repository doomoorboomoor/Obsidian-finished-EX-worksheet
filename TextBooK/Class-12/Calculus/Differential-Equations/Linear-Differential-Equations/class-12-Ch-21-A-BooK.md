## 21. Linear Differential Equations

### Linear Differential Equations

The most general form of linear differential equations is $\frac{d y}{d x}+P y=Q$, where $P$ is a constant and $Q$ is a constant or a function of $x$. The other common form of linear differential equations is $\frac{d x}{d y}+P x=Q$, where $P$ is a constant and $Q$ is a constant or a function of $y$.

### Solution of $\frac{d y}{d x}+P y=Q$

First, we find $e^{\int P d x}$, which is known as the **integrating factor (IF)**.
Now, $\frac{d y}{d x}+P y=Q \Rightarrow e^{\int P d x} \frac{d y}{d x}+P y e^{\int P d x}=Q \cdot e^{\int P d x}$

$$
\begin{align*}
& \Rightarrow e^{\int P d x} d y+P y \cdot e^{\int P d x} d x=Q \cdot e^{\int P d x} d x \Rightarrow d\left(y \cdot e^{\int P d x}\right)=Q \cdot e^{\int P d x} d x \ldots  \tag{i}\\
& \Rightarrow y \cdot e^{\int P d x}=\int Q \cdot e^{\int P d x} d x+C, \text { which is the required solution }
\end{align*}
$$
*(integrating both sides of (i)).*

### Working Rule for Solving $\frac{d y}{d x}+P y=Q$

1.  Find **IF** = $e^{\int P d x}$.
2.  The solution is given by
    $$
    y \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d x+C
    $$

---

## Solved Examples

### Example 1:

Solve the differential equation
$$
x \frac{d y}{d x}-y=2 x^{3}, x>0
$$
[CBSE 2004, '07, '11]

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\left(\frac{-1}{x}\right) y=2 x^{2} \tag{i}
\end{equation*}
$$
This is of the form, $\frac{d y}{d x}+P y=Q$, where $P=\frac{-1}{x}$ and $Q=2 x^{2}$.
Thus, the given differential equation is linear.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int-\frac{1}{x} d x}=e^{-\log x}=e^{\log \left(\frac{1}{x}\right)}=\frac{1}{x}
$$
So, the required solution is given by
$$
y \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d x+C
$$
where $C$ is an arbitrary constant,
i.e.,
$$
y \times \frac{1}{x}=\int\left(2 x^{2} \times \frac{1}{x}\right) d x+C=2 \int x d x+C=x^{2}+C
$$
$$
\Rightarrow y=x^{3}+C x
$$
Hence, the required solution is **$y=x^{3}+C x$**.

---

### Example 2:

Solve the differential equation
$$
\left(x^{2}-1\right) \frac{d y}{d x}+2 x y=\frac{2}{\left(x^{2}-1\right)}
$$
[CBSE 2010, '14]

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\left\{\frac{2 x}{\left(x^{2}-1\right)}\right\} y=\frac{2}{\left(x^{2}-1\right)^{2}} \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$,
where $P=\frac{2 x}{\left(x^{2}-1\right)}$ and $Q=\frac{2}{\left(x^{2}-1\right)^{2}}$.
Thus, the given differential equation is linear.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int \frac{2 x}{\left(x^{2}-1\right)} d x}=e^{\log \left(x^{2}-1\right)}=\left(x^{2}-1\right)
$$
So, the required solution is given by
$$
\text { i.e., } \begin{aligned}
y \times \mathrm{IF}=\int\{\mathrm{Q} \times \mathrm{IF}\} d x+C & \\
& \left.=2 \int \frac{2}{\left(x^{2}-1\right)^{2}} \times\left(x^{2}-1\right)\right\} d x+C \\
& =2 \int \frac{d x}{2}\left\{\frac{1}{(x-1)}-\frac{1}{(x+1)}\right\} d x+C \quad \text { [by partial fraction] } \\
& =\log \left|\frac{x-1}{x+1}\right|+C
\end{aligned}
$$
Hence, **$y\left(x^{2}-1\right)=\log \left|\frac{x-1}{x+1}\right|+C$** is the required solution.

---

### Example 3:

Solve $\left(1+x^{2}\right) \frac{d y}{d x}+y=e^{\tan ^{-1} x}$.
[CBSE 2014]

#### Solution:

The given differential equation may be written as
$$
\frac{d y}{d x}+\frac{1}{\left(1+x^{2}\right)} \cdot y=\frac{e^{\tan ^{-1} x}}{\left(1+x^{2}\right)}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where $P=\frac{1}{\left(1+x^{2}\right)}$ and $Q=\frac{e^{\tan ^{-1} x}}{\left(1+x^{2}\right)}$.
Thus, the given equation is linear.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int \frac{1}{\left(1+x^{2}\right)} d x}=e^{\tan ^{-1} x}
$$
So, the required solution is given by
$$
\begin{aligned}
& y \times \mathrm{IF}=\int \mid(Q \times(\mathrm{IF}) \mid d x+C \\
& \text { i.e., } \begin{aligned}
y \times e^{\tan ^{-1} x} & =\int\left\{\frac{e^{\tan ^{-1} x}}{\left(1+x^{2}\right)} \times e^{\tan ^{-1} x}\right\} d x+C \\
& =\int \frac{e^{2 \tan ^{-1} x}}{\left(1+x^{2}\right)} d x+C \\
& =\int e^{2 t} d t+C, \text { where } \tan ^{-1} x=t \\
& =\frac{1}{2} e^{2 t}+C=\frac{1}{2} e^{2 \tan ^{-1} x}+C
\end{aligned}
\end{aligned}
$$
Hence, **$y=\frac{1}{2} e^{\tan ^{-1} x}+C e^{-\tan ^{-1} x}$** is the required solution.

---

### Example 4:

Solve $(x \log x) \frac{d y}{d x}+y=\frac{2}{x} \log x$.
[CBSE 2009, '10, '14]

#### Solution:

The given differential equation may be written as
$$
\frac{d y}{d x}+\frac{1}{(x \log x)} \cdot y=\frac{2}{x^{2}}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where $P=\frac{1}{(x \log x)}$ and $Q=\frac{2}{x^{2}}$.
Thus, the given differential equation is linear.

$$
\begin{aligned}
\mathrm{IF}=e^{\int P d x} & =e^{\int \frac{1}{x \log x} d x}=e^{\int \frac{1}{t} d t}, \text { where } \log x=t \\
& =e^{\log t}=t=\log x
\end{aligned}
$$
So, the solution of the given differential equation is
$$
\text { i.e., } \begin{aligned}
y \times \operatorname{IF}=\int\{\log x) & =\int\left(\frac{2}{x^{2}} \log x\right) d x+C \\
& =2 \int(\log x) \cdot \frac{1}{x^{2}} d x+C \\
& =2\left[(\log x)\left(-\frac{1}{x}\right)-\int \frac{1}{x} \cdot\left(-\frac{1}{x}\right) d x\right]+C
\end{aligned}
$$
[integrating by parts]
$$
=\frac{-2 \log x}{x}-\frac{2}{x}+C .
$$
Hence, **$y(\log x)=\frac{-2}{x}(\log x+1)+C$** is the required solution.

---

### Example 5:

Solve $\left(x^{2}+1\right) \frac{d y}{d x}+2 x y=\sqrt{x^{2}+4}$.
[CBSE 2008, '10]

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\left(\frac{2 x}{x^{2}+1}\right) y=\frac{\sqrt{x^{2}+4}}{\left(x^{2}+1\right)} \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$,
where $P=\frac{2 x}{\left(x^{2}+1\right)}$ and $Q=\frac{\sqrt{x^{2}+4}}{\left(x^{2}+1\right)}$
Thus, the given differential equation is linear.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int \frac{2 x}{\left(x^{2}+1\right)} d x}=e^{\log \left(x^{2}+1\right)}=\left(x^{2}+1\right)
$$
So, the required solution is given by
$$
\begin{aligned}
& y \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d x+C \\
& \text { i.e., } \begin{aligned}
y\left(x^{2}+1\right) & =\int \frac{\sqrt{x^{2}+4}}{\left(x^{2}+1\right)} \times\left(x^{2}+1\right) d x \\
\Rightarrow y\left(x^{2}+1\right) & =\int \sqrt{x^{2}+4} d x \\
& =\frac{1}{2} x \sqrt{x^{2}+4}+\frac{1}{2} \times 2^{2} \times \log \left|x+\sqrt{x^{2}+4}\right|+C \\
& =\frac{1}{2} x \sqrt{x^{2}+4}+2 \log \left|x+\sqrt{x^{2}+4}\right|+C
\end{aligned}
\end{aligned}
$$
Hence, **$y\left(x^{2}+1\right)=\frac{1}{2} x \sqrt{x^{2}+4}+2 \log \left|x+\sqrt{x^{2}+4}\right|+C$** is the required solution.

---

### Example 6:

Solve $\left(1+x^{2}\right) \frac{d y}{d x}+y=\tan ^{-1} x$.
[CBSE 2008C, '09]

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\frac{1}{\left(1+x^{2}\right)} \cdot y=\frac{\tan ^{-1} x}{\left(1+x^{2}\right)} \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where $P=\frac{1}{\left(1+x^{2}\right)}$ and $Q=\frac{\tan ^{-1} x}{\left(1+x^{2}\right)}$. Thus, the given equation is linear.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int \frac{1}{1+x^{2}} d x}=e^{\tan ^{-1} x}
$$
$\therefore \quad$ the required solution is
$$
\begin{aligned}
& \qquad \begin{aligned}
y \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d x+C,
\end{aligned} \\
& \text { i.e., } \begin{aligned}
& y \times e^{\tan ^{-1} x}=\int\left\{\frac{\tan ^{-1} x}{\left(1+x^{2}\right)} \cdot e^{\tan ^{-1} x}\right\} d x+C \\
&=\int\left(t e^{t}\right) d t+C, \text { where } \tan ^{-1} x=t \\
&=t e^{t}-\int 1 \cdot e^{t} d t+C \quad[\text { integrating by parts }] \\
&=t e^{t}-e^{t}+C=e^{t}(t-1)+C \\
&=e^{\tan ^{-1} x}\left(\tan ^{-1} x-1\right)+C \\
& \Rightarrow y=\left(\tan ^{-1} x-1\right)+C e^{-\tan ^{-1} x}
\end{aligned}
\end{aligned}
$$
Hence, **$y=\left(\tan ^{-1} x-1\right)+C e^{-\tan ^{-1} x}$** is the required solution.

---

### Example 7:

Find the general solution of the differential equation
$$
\frac{d y}{d x}-y=\cos x
$$
[CBSE 2012C]

#### Solution:

The given differential equation is
$$
\begin{equation*}
\frac{d y}{d x}-y=\cos x \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where $P=-1$ and $Q=\cos x$.
Thus, the given differential equation is linear.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int-d x}=e^{-x}
$$
So, the required solution is
$$
\begin{align*}
& \qquad \begin{aligned}
y & \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d x+C \\
\text { i.e., } y & \times e^{-x}=\int(\cos x) e^{-x} d x+C \\
\text { Let } I & =\int(\cos x) e^{-x} d x \\
\text { I II } & \\
& =(\cos x)\left(-e^{-x}\right)-\int(-\sin x)\left(-e^{-x}\right) d x \quad[\text { integrating by parts] } \\
& =-(\cos x) e^{-x}-\int(\sin x)\left(e^{-x}\right) d x \\
\text { I II } & \\
& =-(\cos x) e^{-x}-\left\{(\sin x)\left(-e^{-x}\right)\right\}-\int(\cos x)\left(-e^{-x}\right) d x \\
& =-(\cos x) e^{-x}+(\sin x)\left(e^{-x}\right)-I \\
\therefore \quad & 2 I=(\sin x-\cos x) e^{-x} \Rightarrow I=\frac{1}{2}(\sin x-\cos x) e^{-x}
\end{aligned}
\end{align*}
$$
Putting this value in (ii), we get
$$
y \times e^{-x}=\frac{1}{2}(\sin x-\cos x) e^{-x}+C \Rightarrow y=\frac{1}{2}(\sin x-\cos x)+C e^{x} .
$$
Hence, **$y=\frac{1}{2}(\sin x-\cos x)+C e^{x}$** is the required solution.

---

### Example 8:

Solve the differential equation
$$
\begin{equation*}
x \frac{d y}{d x}+y-x+x y \cot x=0, x \neq 0 . \tag{CBSE2011,'12}
\end{equation*}
$$
#### Solution:

The given differential equation may be written as
$$
\begin{align*}
& x \frac{d y}{d x}+(1+x \cot x) y=x \\
\Rightarrow & \frac{d y}{d x}+\left(\frac{1}{x}+\cot x\right) y=1 . \tag{i}
\end{align*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where $P=\left(\frac{1}{x}+\cot x\right)$ and $Q=1$.
Thus, the given differential equation is linear.

$$
\begin{aligned}
\mathrm{IF}=e^{\int P d x}=e^{\int\left(\frac{1}{x}+\cot x\right) d x} & =e^{\log x+\log \sin x} \\
& =e^{\log (x \sin x)}=x \sin x .
\end{aligned}
$$
So, the solution of the given differential equation is given by
$$
\begin{aligned}
& \qquad \begin{aligned}
y \times(\mathrm{IF})= & \int(\mathrm{Q} \times \mathrm{IF}) d x+C \\
\text { i.e., } y(x \sin x) & =\int_{x} 1 \times(x \sin x) d x+C \\
& =\int_{\mathrm{I}} x \sin x d x+C \\
& =x(-\cos x)-\int 1 \cdot(-\cos x) d x+C \\
& =-x \cos x+\int \cos x d x+C \\
& =-x \cos x+\sin x+C
\end{aligned} \\
& \therefore \quad \textbf{$y=\frac{1}{x}-\cot x+\frac{C}{x \sin x}$} \text{ is the required solution. }
\end{aligned}
$$
---

### Example 9:

Solve the differential equation
$$
\left\{\frac{e^{-2 \sqrt{x}}}{\sqrt{x}}-\frac{y}{\sqrt{x}}\right\} \frac{d x}{d y}=1(x \neq 0) .
$$
[CBSE 2012]

#### Solution:

The given differential equation may be written as
$$
\begin{align*}
& \frac{d y}{d x}=-\frac{1}{\sqrt{x}} \cdot y+\frac{e^{-2 \sqrt{x}}}{\sqrt{x}} \\
\Rightarrow & \frac{d y}{d x}+\frac{1}{\sqrt{x}} \cdot y=\frac{e^{-2 \sqrt{x}}}{\sqrt{x}} \tag{i}
\end{align*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where $P=\frac{1}{\sqrt{x}}$ and $Q=\frac{e^{-2 \sqrt{x}}}{\sqrt{x}}$.

$$
\mathrm{IF}=e^{\int P d x}=e^{\int \frac{1}{\sqrt{x}} d x}=e^{2 \sqrt{x}}
$$
So, the solution of the given differential equation is given by
$$
\begin{aligned}
& y \times \mathrm{IF}=\int(Q \times \mathrm{IF}) d x+C \\
& \text { i.e., } \begin{aligned}
y \times e^{2 \sqrt{x}} & =\int \frac{e^{-2 \sqrt{x}}}{\sqrt{x}} \times e^{2 \sqrt{x}} d x+C \\
& =\int \frac{1}{\sqrt{x}} d x+C=2 \sqrt{x}+C
\end{aligned}
\end{aligned}
$$
Hence, **$y e^{2 \sqrt{x}}=2 \sqrt{x}+C$** is the required solution.
$\therefore \quad y=\frac{1}{x}-\cot x+\frac{C}{x \sin x}$ is the required solution.

---

### Example 10:

Solve $x \frac{d y}{d x}+2 y=x \cos x$.

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\frac{2}{x} \cdot y=\cos x \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=\frac{2}{x}$** and **$Q=\cos x$**.
Thus, the given equation is linear.

**IF** = $e^{\int P d x}=e^{\int \frac{2}{x} d x}=e^{2 \log x}=e^{\log \left(x^{2}\right)}=x^{2}$.

So, the required solution is
$$
\begin{aligned}
& \qquad \begin{aligned}
y \times \mathrm{IF} & =\int\{Q \times(\mathrm{IF})\} d x+C \\
\text { i.e., } y x^{2} & =\int x^{2} \cos x d x+C \\
& =x^{2} \sin x-\int 2 x \sin x d x+C \quad[\text { integrating by parts }] \\
& =x^{2} \sin x-2 \cdot\left[x(-\cos x)-\int 1 \cdot(-\cos x) d x\right]+C \quad[\text { integrating by parts }] \\
& =x^{2} \sin x+2 x \cos x-2 \sin x+C .
\end{aligned}
\end{aligned}
$$
Hence, **$y=\sin x+\frac{2}{x} \cos x-\frac{2}{x^{2}} \sin x+\frac{C}{x^{2}}$** is the required solution.

---

### Example 11:

Solve $\frac{d y}{d x}+(\sec x) y=\tan x$.
[CBSE 2006, '08C, '12]

#### Solution:

The given equation is of the form
$$
\frac{d y}{d x}+P y=Q, \text { where } \textbf{P=\sec x} \text { and } \textbf{Q=\tan x}
$$
Thus, the given equation is linear.

**IF** = $e^{\int P d x}=e^{\int \sec x d x}=e^{\log (\sec x+\tan x)}=(\sec x+\tan x)$.

So, the required solution is
$$
y \times \mathrm{IF}=\int\{Q \times(\mathrm{IF})\} d x+C
$$
$$
\text { i.e., } \begin{aligned}
y(\sec x+\tan x) & =\int \tan x(\sec x+\tan x) d x+C \\
& =\int \sec x \tan x d x+\int \tan ^{2} x d x+C \\
& =\sec x+\int\left(\sec ^{2} x-1\right) d x+C \\
& =\sec x+\tan x-x+C
\end{aligned}
$$
Hence, **$y(\sec x+\tan x)=\sec x+\tan x-x+C$** is the required solution.

---

### Example 12:

Find the general solution of the differential equation $\frac{d y}{d x}-2 y=\cos 3 x$.

#### Solution:

The given differential equation is of the form $\frac{d y}{d x}+P y=Q$, where **$P=-2$** and **$Q=\cos 3 x$**.
Thus, the given differential equation is linear.

**IF** = $e^{\int P d x}=e^{\int-2 d x}=e^{-2 x}$.

So, the required solution is
$$
\begin{aligned}
& \qquad \begin{aligned}
y \times \mathrm{IF} & =\int\{Q \times \mathrm{IF}\} d x+C \\
\text { i.e., } y \times e^{-2 x} & =\int e^{-2 x} \cos 3 x d x+C \\
& =e^{-2 x}\left[\frac{-2 \cos 3 x+3 \sin 3 x}{\left\{(-2)^{2}+3^{2}\right\}}\right]+C \\
& \quad\left[\because \int e^{a x} \cos b x d x=e^{a x}\left\{\frac{a \cos b x+b \sin b x}{\left(a^{2}+b^{2}\right)}\right\}\right]
\end{aligned}
\end{aligned}
$$
$\therefore$ **$y=\frac{(3 \sin 3 x-2 \cos 3 x)}{13}+C e^{2 x}$**, which is the required solution.

---

### Example 13:

Solve the differential equation
$$
\left(\cos ^{2} x\right) \frac{d y}{d x}+y=\tan x\left(0 \leq x<\frac{\pi}{2}\right)
$$
[CBSE 2008, '11]

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\left(\sec ^{2} x\right) y=\left(\sec ^{2} x\right) \tan x \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=\sec ^{2} x$** and **$Q=\sec ^{2} x \tan x$**.
Thus, the given differential equation is linear.

**IF** = $e^{\int P d x}=e^{\int \sec ^{2} x d x}=e^{\tan x}$.

So, its solution is given by
$$
y \times \mathrm{IF}=\int(Q \times \mathrm{IF}) d x+C
$$
$$
\text { i.e., } \begin{aligned}
y \times e^{\tan x} & =\int e^{\tan x}\left(\sec ^{2} x\right) \tan x d x+C \\
& =\int t e^{t} d t, \text { where } \tan x=t \text { and } \sec ^{2} x d x=d t \\
& =t e^{t}-\int 1 \cdot e^{t} d t+C \\
& =t e^{t}-e^{t}+C=e^{t}(t-1)+C \\
& =e^{\tan x}(\tan x-1)+C
\end{aligned}
$$
Hence, **$y=(\tan x-1)+C e^{-\tan x}$** is the required solution.

---

### Example 14:

Solve the differential equation
$$
\frac{d y}{d x}+y \tan x=2 x+x^{2} \tan x.
$$
#### Solution:

The given differential equation is of the form
$$
\frac{d y}{d x}+P y=Q, \text { where } \textbf{P=\tan x} \text { and } \textbf{Q=2 x+x^{2} \tan x}
$$
Thus, the given differential equation is linear.
$$
\textbf{IF}=e^{\int P d x}=e^{\int \tan x d x}=e^{\log \sec x}=\sec x
$$
So, its solution is given by
$$
\begin{aligned}
& y \times \mathrm{IF}= \int(Q \times \mathrm{IF}) d x+C \\
& \text { i.e., } \begin{aligned}
y \times \sec x & =\int\left(2 x+x^{2} \tan x\right) \sec x d x+C \\
& =\int 2 x \sec x d x+\int x_{\mathrm{I}}^{2} \sec x \tan x d x+C \\
& =\int 2 x \sec x d x+\left\{x^{2} \sec x-\int 2 x \sec x d x\right\}+C \\
& =x^{2} \sec x+C
\end{aligned}
\end{aligned}
$$
$\therefore \quad$ **$y=x^{2}+C \cos x$** is the required solution.

---

### Example 15:

Solve the differential equation $x \frac{d y}{d x}+y=x \cos x+\sin x$, given $y\left(\frac{\pi}{2}\right)=1$.
[CBSE 2014C]

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+\frac{1}{x} \cdot y=\cos x+\frac{\sin x}{x} . \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=\frac{1}{x}$** and
**$Q=\cos x+\frac{\sin x}{x}$**.
Thus, the given differential equation is linear.

**IF** = $e^{\int P d x}=e^{\int \frac{1}{x} d x}=e^{\log x}=x$.

So, its solution is given by
$$
y \times \mathrm{IF}=\int(Q \times \mathrm{IF}) d x+C
$$
$$
\text { i.e., } \begin{align*}
y \times x & =\int\left(\cos x+\frac{\sin x}{x}\right) x d x+C \\
& =\int_{\mathrm{I}} x \cos x d x+\int \sin x d x+C \\
& =x \sin x-\int \sin x d x+\int \sin x d x+C \\
& =x \sin x+C \\
\therefore y= & \sin x+\frac{C}{x} \tag{ii}
\end{align*}
$$
It is being given that when $x=\frac{\pi}{2}$, then $y=1$.
Putting $x=\frac{\pi}{2}$ and $y=1$ in (ii), we get $C=0$.

Hence, **$y=\sin x$** is the required solution.

---

### Example 16:

Find the particular solution of the differential equation $\cos x \frac{d y}{d x}+y=\sin x$, given that $y=2$ when $x=0$.

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}+(\sec x) y=\tan x \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=\sec x$** and **$Q=\tan x$**.
Thus, the given differential equation is linear.

**IF** = $e^{\int P d x}=e^{\int \sec x d x}=e^{\log (\sec x+\tan x)}=(\sec x+\tan x)$.

So, its solution is given by
$$
\begin{align*}
y \times \mathrm{IF}=\int(Q \times \mathrm{IF}) & d x+C \\
\text { i.e., } y(\sec x+\tan x) & =\int \tan x(\sec x+\tan x) d x+C \\
& =\int \sec x \tan x d x+\int \tan ^{2} x d x+C \\
& =\sec x+\int\left(\sec ^{2} x-1\right) d x+C \\
& =\sec x+\int \sec ^{2} x d x-\int d x+C \\
& =\sec x+\tan x-x+C \tag{ii}
\end{align*}
$$
Thus, $y(\sec x+\tan x)=\sec x+\tan x-x+C$.

It is given that when $x=0$, then $y=2$.
$\therefore \quad$ putting $x=0$ and $y=2$ in (ii), we get $C=1$.

Hence, **$y(\sec x+\tan x)=\sec x+\tan x-x+1$** is the required solution.

---

### Example 17:

Find the particular solution of the differential equation $x \frac{d y}{d x}-y=(x+1) e^{-x}$, given that $y=0$ when $x=1$.

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}-\frac{1}{x} \cdot y=\frac{(x+1) e^{-x}}{x} \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=\frac{-1}{x}$** and **$Q=\frac{(x+1) e^{-x}}{x}$**.
Thus, the given differential equation is linear.

**IF** = $e^{\int P d x}=e^{-\int \frac{1}{x} d x}=e^{-\log x}=e^{\log (1 / x)}=\frac{1}{x}$.

So, its solution is given by
$$
\begin{align*}
& y \times \mathrm{IF}=\int(Q \times \mathrm{IF}) d x+C \\
\text { i.e., } & y \times \frac{1}{x}=\int \frac{(x+1) e^{-x}}{x^{2}} d x+C \\
\Rightarrow & y \times \frac{1}{x}=\int \frac{1}{x} e^{-x} d x+\int \frac{1}{x^{2}} e^{-x} d x+C \\
\Rightarrow & y \times \frac{1}{x}=\frac{1}{x} \cdot\left(-e^{-x}\right)+\int \frac{1}{x^{2}}\left(-e^{-x}\right) d x+\int \frac{1}{x^{2}} e^{-x} d x+C \\
\Rightarrow & \frac{y}{x}=\frac{-e^{-x}}{x}+C \\
\Rightarrow & y=-e^{-x}+C x \tag{ii}
\end{align*}
$$
It is being given that when $x=1$, then $y=0$.
Putting $x=1$ and $y=0$ in (ii), we get $C=e^{-1}$.

$\therefore \quad$ **$y=-e^{-x}+x e^{-1}$** is the required solution.

---

### Example 18:

Find the particular solution of the differential equation $\frac{d y}{d x}-3 y \cot x=\sin 2 x$, it being given that $y=2$ when $x=\frac{\pi}{2}$.

#### Solution:

The given differential equation is
$$
\begin{equation*}
\frac{d y}{d x}-3 y \cot x=\sin 2 x \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=-3 \cot x$** and **$Q=\sin 2 x$**. Thus, the given equation is linear.

**IF** = $e^{\int P d x}=e^{\int-3 \cot x d x}=e^{\log (\sin x)^{-3}}=(\sin x)^{-3}=\frac{1}{\sin ^{3} x}$.

So, the solution of (i) is given by
$$
\begin{aligned}
& y \times \mathrm{IF}=\int\{Q \times(\mathrm{IF})\} d x+C \\
& \text { i.e., } \begin{aligned}
y \times \frac{1}{\sin ^{3} x} & =\int\left(\sin 2 x \times \frac{1}{\sin ^{3} x}\right) d x+C \\
& =2 \int \frac{\cos x}{\sin ^{2} x} d x+C \quad[\because \sin 2 x=2 \sin x \cos x]
\end{aligned}
\end{aligned}
$$
$$
\begin{align*}
& =2 \int \frac{1}{t^{2}} d t+C, \text { where } \sin x=t \\
& =\frac{-2}{t}+C=\frac{-2}{\sin x}+C \tag{ii}
\end{align*}
$$
Thus, $y=-2 \sin ^{2} x+C \sin ^{3} x$.

It is being given that when $x=\frac{\pi}{2}$, then $y=2$.
Putting $x=\frac{\pi}{2}$ and $y=2$ in (ii), we get
$$
-2 \sin ^{2} \frac{\pi}{2}+C \sin ^{3} \frac{\pi}{2}=2 \Rightarrow C-2=2 \Rightarrow C=4 .
$$
Hence, **$y=-2 \sin ^{2} x+4 \sin ^{3} x$** is the required solution.

---

### Example 19:

Find the particular solution of the differential equation $\left(1-x^{2}\right) \frac{d y}{d x}-x y=x^{2}$, given that $y=2$ when $x=0$.

#### Solution:

The given differential equation may be written as
$$
\begin{equation*}
\frac{d y}{d x}-\frac{x}{\left(1-x^{2}\right)} \cdot y=\frac{x^{2}}{\left(1-x^{2}\right)} . \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=\frac{-x}{\left(1-x^{2}\right)}$** and **$Q=\frac{x^{2}}{\left(1-x^{2}\right)}$**. Thus, the given differential equation is linear.
$$
\begin{aligned}
\textbf{IF}=e^{\int P d x} & =e^{\int \frac{-x}{\left(1-x^{2}\right)} d x}=e^{\frac{1}{2} \int \frac{-2 x}{\left(1-x^{2}\right)} d x}=e^{\frac{1}{2} \log \left(1-x^{2}\right)} \\
& =e^{\log \sqrt{1-x^{2}}}=\sqrt{1-x^{2}}
\end{aligned}
$$
So, its solution is given by
$$
\begin{align*}
& y \times \mathrm{IF}=\int(Q \times \mathrm{IF}) d x+C \\
& \text { i.e., } \begin{aligned}
& y \times \sqrt{1-x^{2}}=\int \frac{x^{2}}{\left(1-x^{2}\right)} \times \sqrt{1-x^{2}} d x+C \\
&=\int \frac{x^{2}}{\sqrt{1-x^{2}}} d x+C \\
&=\int \frac{\left\{-\left(1-x^{2}\right)+1\right\}}{\sqrt{1-x^{2}}} d x+C \\
&=-\int \sqrt{1-x^{2}} d x+\int \frac{1}{\sqrt{1-x^{2}}} d x+C \\
&=-\left\{\frac{x \sqrt{1-x^{2}}}{2}+\frac{1}{2} \sin ^{-1} x\right\}+\sin ^{-1} x+C \\
&=\frac{-x \sqrt{1-x^{2}}}{2}+\frac{1}{2} \sin ^{-1} x+C \\
& \therefore \quad y=\frac{-x}{2}+\frac{\sin ^{-1} x}{2 \sqrt{1-x^{2}}}+\frac{C}{\sqrt{1-x^{2}}}
\end{aligned}
\end{align*}
$$
It is being given that when $x=0$, then $y=2$.
Putting $x=0$ and $y=2$ in (ii), we get $C=2$.

Hence, **$y=\frac{-x}{2}+\frac{\sin ^{-1} x}{2 \sqrt{1-x^{2}}}+\frac{2}{\sqrt{1-x^{2}}}$** is the required solution.

---

### Example 20:

Find the equation of a curve passing through the point $(0,1)$, it being given that the slope of the tangent to the curve at any point ($x, y$) is equal to the sum of the $x$-coordinate and the product of the $x$-coordinate and $y$-coordinate of the point.

#### Solution:

We know that the slope of the tangent to the curve is $\frac{d y}{d x}$.
$$
\begin{equation*}
\therefore \quad \frac{d y}{d x}=x+x y \Rightarrow \frac{d y}{d x}-x y=x . \tag{i}
\end{equation*}
$$
This is of the form $\frac{d y}{d x}+P y=Q$, where **$P=-x$** and **$Q=x$**.
So, the given differential equation is linear.

**IF** = $e^{\int P d x}=e^{\int-x d x}=e^{\frac{-x^{2}}{2}}$.

Hence, the solution of the given differential equation is given by
$$
\begin{align*}
y \times \mathrm{IF} & =\int(Q \times \mathrm{IF}) d x+C, \\
\text { i.e., } y \times e^{\frac{-x^{2}}{2}} & =\int x e^{\frac{-x^{2}}{2}} d x+C \\
& =\int e^{-t} d t+C, \text { where } \frac{x^{2}}{2}=t \\
& =-e^{-t}+C=-e^{\frac{-x^{2}}{2}}+C . \\
\therefore \quad y & =-1+C e^{\frac{x^{2}}{2}} . \tag{ii}
\end{align*}
$$
We have to find a curve satisfying (ii) and passing through $(0,1)$.
Putting $x=0$ and $y=1$ in (ii), we get $C=2$.

Hence, **$y=-1+2 e^{\frac{x^{2}}{2}}$** is the equation of the required curve.

---

### Example 21:

An equation relating to the stability of an aeroplane is given by $\frac{d v}{d t}=g \cos \alpha-k v$, where $v$ is the velocity and $g, \alpha, k$ are constants. Find an expression for the velocity if $v=0$ at $t=0$.

#### Solution:

The given differential equation is
$$
\begin{equation*}
\frac{d v}{d t}+k v=g \cos \alpha . \tag{i}
\end{equation*}
$$
This is of the form $\frac{d v}{d t}+P v=Q$, where **$P=k$** and **$Q=g \cos \alpha$**.
Thus, the given equation is linear.

**IF** = $e^{\int P d t}=e^{\int k d t}=e^{k t}$.

So, the solution of the given differential equation is
$$
\begin{align*}
v \times \mathrm{IF} & =\int\{Q \times \mathrm{IF}\} d t+C, \\
\text { i.e., } v e^{k t} & =\int(g \cos \alpha) e^{k t} d t+C \\
& =\frac{(g \cos \alpha) e^{k t}}{k}+C . \tag{ii}
\end{align*}
$$
Now, it is given that $v=0$ when $t=0$.
Putting $t=0$ and $v=0$ in (ii), we get $C=\frac{-g \cos \alpha}{k}$.
$$
\therefore \quad v e^{k t}=\frac{(g \cos \alpha) e^{k t}}{k}-\frac{g \cos \alpha}{k}
$$
$$
\Rightarrow \quad \textbf{$v=\frac{1}{k}(g \cos \alpha)\left(1-e^{-k t}\right)$}, \text{ which is the required expression.}
$$
---

### Solution of $\frac{d x}{d y}+P x=Q$

#### Working Rule for Solving $\frac{d x}{d y}+P x=Q$

1.  Find **IF** = $e^{\int P d y}$.
2.  The solution is given by $x \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d y+C$.

---

### Example 22:

Find the general solution of the differential equation $\left(x+2 y^{3}\right) \frac{d y}{d x}=y, y \neq 0$.

#### Solution:

The given differential equation may be written as
$$
\begin{align*}
& y \frac{d x}{d y}=x+2 y^{3} \\
\Rightarrow & \frac{d x}{d y}-\frac{1}{y} \cdot x=2 y^{2} \tag{i}
\end{align*}
$$
This is of the form $\frac{d x}{d y}+P x=Q$, where **$P=-\frac{1}{y}$** and **$Q=2 y^{2}$**.
Thus, the given equation is linear.

**IF** = $e^{\int P d y}=e^{\int-\frac{1}{y} d y}=e^{-\log y}=e^{\log \left(y^{-1}\right)}=y^{-1}=\frac{1}{y}$.

So, the required solution is
$$
x \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d y+C
$$
$$
\text { i.e., } \begin{aligned}
x \times \frac{1}{y} & =\int\left(2 y^{2} \times \frac{1}{y}\right) d y+C \\
& =\int 2 y d y+C=y^{2}+C
\end{aligned}
$$
Hence, **$x=y^{3}+C y$** is the required solution.

---

### Example 23:

Find the particular solution of the differential equation $\left(\tan ^{-1} y-x\right) d y=\left(1+y^{2}\right) d x$, given that when $x=0, y=0$.
[CBSE 2009, '13]

#### Solution:

The given differential equation may be written as
$$
\begin{align*}
& \frac{d x}{d y}=\frac{\left(\tan ^{-1} y-x\right)}{\left(1+y^{2}\right)} \\
\Rightarrow & \frac{d x}{d y}+\frac{1}{\left(1+y^{2}\right)} \cdot x=\frac{\tan ^{-1} y}{\left(1+y^{2}\right)} . \tag{i}
\end{align*}
$$
This is of the form $\frac{d x}{d y}+P x=Q$, where **$P=\frac{1}{\left(1+y^{2}\right)}$** and **$Q=\frac{\tan ^{-1} y}{\left(1+y^{2}\right)}$**.
Thus, the given differential equation is linear.

**IF** = $e^{\int P d y}=e^{\int \frac{1}{\left(1+y^{2}\right)} d y}=e^{\tan ^{-1} y}$.

So, the solution of the given differential equation is given by
$x \times \mathrm{IF}=\int\{Q \times \mathrm{IF}\} d y+C$, where $C$ is an arbitrary constant,
$$
\text { i.e., } \begin{align*}
x \times e^{\tan ^{-1} y} & =\int\left\{\frac{\tan ^{-1} y}{\left(1+y^{2}\right)} \times e^{\tan ^{-1} y}\right\} d y+C \\
& =\int t e^{t} d t+C, \text { where } \tan ^{-1} y=t \text { and } \frac{1}{\left(1+y^{2}\right)} d y=d t \\
& =t e^{t}-\int 1 \cdot e^{t} d t+C \quad \text { [integrating by parts] } \\
& =t e^{t}-e^{t}+C \\
& =(t-1) e^{t}+C \\
& =\left(\tan ^{-1} y-1\right) e^{\tan ^{-1} y}+C \\
\therefore \quad x e^{\tan ^{-1} y}= & \left(\tan ^{-1} y-1\right) e^{\tan ^{-1} y}+C \tag{ii}
\end{align*}
$$
Putting $x=0$ and $y=0$ in (ii), we get $C=1$.
$$
\therefore \quad x e^{\tan ^{-1} y}=\left(\tan ^{-1} y-1\right) e^{\tan ^{-1} y}+1 .
$$
Hence, **$x=\left(\tan ^{-1} y-1\right)+e^{-\tan ^{-1} y}$** is the required solution.

---

### Example 24:

Find the particular solution of the differential equation $\left(\sqrt{1-y^{2}}\right) d x=\left(\sin ^{-1} y-x\right) d y$, it being given that when $y=0$, then $x=0$.

#### Solution:

The given differential equation may be written as
$$
\frac{d x}{d y}=\frac{\sin ^{-1} y-x}{\sqrt{1-y^{2}}}
$$
$$
\Rightarrow \quad \frac{d x}{d y}+\frac{1}{\sqrt{1-y^{2}}} \cdot x=\frac{\sin ^{-1} y}{\sqrt{1-y^{2}}}.
$$
This is of the form $\frac{d x}{d y}+P x=Q$, where **$P=\frac{1}{\sqrt{1-y^{2}}}$** and **$Q=\frac{\sin ^{-1} y}{\sqrt{1-y^{2}}}$**.
Thus, the given equation is linear.

**IF** = $e^{\int P d y}=e^{\int \frac{1}{\sqrt{1-y^{2}}} d y}=e^{\sin ^{-1} y}$.

So, the solution of the given differential equation is given by
$$
\begin{align*}
& \quad \begin{aligned}
x \times \mathrm{IF}=\int & (Q \times \mathrm{IF}) d y+C, \\
\text { i.e., } x \times e^{\sin ^{-1} y} & =\int\left\{\frac{\sin ^{-1} y}{\sqrt{1-y^{2}}} \cdot e^{\sin ^{-1} y}\right\} d y+C \\
& =\int t e^{t} d t+C, \text { where } \sin ^{-1} y=t \text { and } \frac{1}{\sqrt{1-y^{2}}} d y=d t \\
& =t e^{t}-\int 1 \cdot e^{t} d t+C \\
& =t e^{t}-\int e^{t} d t+C=\left(t e^{t}-e^{t}\right)+C \\
& =(t-1) e^{t}+C \\
& =\left(\sin ^{-1} y-1\right) e^{\sin ^{-1} y}+C \quad\left[\because \quad t=\sin ^{-1} y\right]
\end{aligned} \\
& \therefore \quad x=\left(\sin ^{-1} y-1\right)+C e^{-\sin ^{-1} y} . \tag{ii}
\end{align*}
$$
Putting $y=0$ and $x=0$ in (ii), we get $C=1$.

Hence, **$x=\left(\sin ^{-1} y-1\right)+e^{-\sin ^{-1} y}$** is the required solution.

---

### Example 25:

Find the particular solution of the differential equation $\frac{d x}{d y}+x \cot y=2 y+y^{2} \cot y(y \neq 0)$, given that $x=0$ when $y=\frac{\pi}{2}$.
[CBSE 2013C]

#### Solution:

The given differential equation is of the form $\frac{d x}{d y}+P x=Q$, where **$P=\cot y$** and **$Q=\left(2 y+y^{2} \cot y\right)$**.
So, the given differential equation is linear.

**IF** = $e^{\int P d y}=e^{\int \cot y d y}=e^{\log \sin y}=\sin y$.

Therefore, the solution is given by
$$
\begin{aligned}
x \times \mathrm{IF}= & \int(Q \times \mathrm{IF}) d y+C \\
\text { i.e., } x \times \sin y & =\int\left(2 y+y^{2} \cot y\right) \sin y d y+C \\
& =\int 2 y \sin y d y+\int_{\mathrm{I}} y^{2} \cos y d y+C
\end{aligned}
$$
$$
\begin{align*}
& =\int 2 y \sin y d y+\left[y^{2} \sin y-\int 2 y \sin y d y\right]+C \\
& =y^{2} \sin y+C . \\
\therefore \quad x=y^{2}+ & C \operatorname{cosec} y . \tag{i}
\end{align*}
$$
Putting $y=\frac{\pi}{2}$ and $x=0$ in (i), we get $C=\frac{-\pi^{2}}{4}$.

Hence, the required solution is **$x=y^{2}-\frac{\pi^{2}}{4} \operatorname{cosec} y$**.

---

