## Errors and Approximation

Let $y=f(x)$. Then, $\lim _{\delta x \rightarrow 0} \frac{f(x+\delta x)-f(x)}{\delta x}=f^{\prime}(x)$.

$$
\therefore \quad \frac{f(x+\delta x)-f(x)}{\delta x}=f^{\prime}(x)+\epsilon, \text { where } \in \rightarrow 0 \text { when } \delta x \rightarrow 0
$$

$\Rightarrow f(x+\delta x)-f(x)=f^{\prime}(x) \cdot \delta x+\epsilon \cdot \delta x$
$\Rightarrow f(x+\delta x)-f(x)=f^{\prime}(x) \cdot \delta x \quad$ (approximately)
$\Rightarrow \delta y=f^{\prime}(x) \cdot \delta x \quad[\because f(x+\delta x)-f(x)=\delta y]$.
Thus, if $\delta x$ is an error in $x$ then the corresponding error in $y$ is $\delta y$. These small values $\delta x$ and $\delta y$ are called differentials.

- **Absolute Error:** $\delta x$ is called an absolute error in $x$.
- **Relative Error:** $\frac{\delta x}{x}$ is called the relative error.
- **Percentage Error:** $\left(\frac{\delta x}{x} \times 100\right)$ is called the percentage error.

## Solved Examples

### Example 1

Using differentials, find the approximate value of $(82)^{1 / 4}$ up to three places of decimal.
[CBSE 2005]

#### Solution

Let $f(x)=x^{1 / 4}$. Then, $f^{\prime}(x)=\frac{1}{4 x^{3 / 4}}$.
Now, $\{f(x+\delta x)-f(x)\}=f^{\prime}(x) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow\{f(x+\delta x)-f(x)\}=\frac{1}{4 x^{3 / 4}} \cdot \delta x \tag{i}
\end{equation*}
$$

We may write, $82=(81+1)$.
Putting $x=81$ and $\delta x=1$ in (i), we get

$$
\begin{aligned}
& f(81+1)-f(81)=\frac{1}{4 \times(81)^{3 / 4}} \cdot 1 \\
\Rightarrow & f(82)-f(81)=\frac{1}{\left(4 \times 3^{3}\right)}=\frac{1}{108} \\
\Rightarrow & f(82)=\left\{f(81)+\frac{1}{108}\right\}=\left\{(81)^{1 / 4}+\frac{1}{108}\right\}=3+0.009=3.009
\end{aligned}
$$

---

### Example 2

Find the approximate value of the cube root of 127.

#### Solution

Let $f(x)=x^{1 / 3}$. Then, $f^{\prime}(x)=\frac{1}{3 x^{2 / 3}}$.
Now, $\{f(x+\delta x)-f(x)\}=f^{\prime}(x) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow\{f(x+\delta x)-f(x)\}=\frac{1}{3 x^{2 / 3}} \cdot \delta x \tag{i}
\end{equation*}
$$

We may write, $127=(125+2)$.
Putting $x=125$ and $\delta x=2$ in (i), we get

$$
f(125+2)-f(125)=\frac{1}{3 \times(125)^{2 / 3}} \times 2
$$

$\Rightarrow f(127)-f(125)=\frac{2}{75}$
$\Rightarrow f(127)=f(125)+\frac{2}{75}=\left\{(125)^{1 / 3}+\frac{2}{75}\right\}=\left(5+\frac{2}{75}\right)=\frac{377}{75}$
$\Rightarrow \sqrt[3]{127}=\frac{377}{75}=5.026$.

---

### Example 3

Using differentials find the approximate value of the square root of 26.
[CBSE 2000]

#### Solution

Let $f(x)=\sqrt{x}$. Then, $f^{\prime}(x)=\frac{1}{2 \sqrt{x}}$.
Now, $\{f(x+\delta x)-f(x)\}=f^{\prime}(x) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow\{f(x+\delta x)-f(x)\}=\frac{1}{2 \sqrt{x}} \cdot \delta x \tag{i}
\end{equation*}
$$

We may write, $26=(25+1)$.
Putting $x=25$ and $\delta x=1$ in (i), we get

$$
\begin{aligned}
& f(26)-f(25)=\frac{1}{2 \sqrt{25}} \times 1 \\
\Rightarrow & f(26)=f(25)+\frac{1}{10}=\left(\sqrt{25}+\frac{1}{10}\right)=\left(5+\frac{1}{10}\right)=(5+0.1)=5.1 \\
\Rightarrow & \sqrt{26}=5.1 .
\end{aligned}
$$

Hence, $\sqrt{26}=5.1$.

---

### Example 4

Using differentials find the approximate value of $\sqrt{0.037}$.
[CBSE 2005C]

#### Solution

Let $f(x)=\sqrt{x}$. Then, $f^{\prime}(x)=\frac{1}{2 \sqrt{x}}$.
Now, $\{f(x+\delta x)-f(x)\}=f^{\prime}(x) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow\{f(x+\delta x)-f(x)\}=\frac{1}{2 \sqrt{x}} \cdot \delta x \tag{i}
\end{equation*}
$$

We may write, $0.037=(0.04-0.003)$.
Putting $x=0.04$ and $\delta x=-0.003$ in (i), we get

$$
\begin{aligned}
& f(0.04-0.003)-f(0.04)=\frac{1}{2 \sqrt{0.04}} \times(-0.003) \\
\Rightarrow & f(0.037)=f(0.04)-\frac{0.003}{0.4} \\
\Rightarrow & \sqrt{0.037}=\left(\sqrt{0.04}-\frac{3}{400}\right)=\left(0.2-\frac{3}{400}\right)=\frac{77}{400} \\
\Rightarrow & \sqrt{0.037}=0.1925
\end{aligned}
$$

---

### Example 5

Find the approximate value of $\tan 46^{\circ}$, it is being given that $1^{\circ}=0.01745$ radian.

#### Solution

Let $f(x)=\tan x$. Then, $f^{\prime}(x)=\sec ^{2} x$.
Now, $f(x+\delta x)-f(x)=f^{\prime}(x) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow f(x+\delta x)-f(x)=\sec ^{2} x \cdot \delta x \tag{i}
\end{equation*}
$$

Putting $x=45^{\circ}, \delta x=1^{\circ}=0.01745$ in (i), we get

$$
\begin{aligned}
& f\left(46^{\circ}\right)-f\left(45^{\circ}\right)=\left(\sec ^{2} 45^{\circ}\right) \times 0.01745 \\
\Rightarrow & \tan 46^{\circ}-\tan 45^{\circ}=\left(\sec ^{2} 45^{\circ}\right) \times 0.01745 \\
\Rightarrow & \tan 46^{\circ}=\tan 45^{\circ}+\left(\sec ^{2} 45^{\circ}\right) \times 0.01745 \\
& =(1+2 \times 0.01745)=1.03490
\end{aligned}
$$

Hence, $\tan 46^{\circ}=1.03490$.

---

### Example 6

Find the approximate value of $\log _{10} 10.1$, it being given that $\log _{10} e=0.4343$.

#### Solution

Let $f(x)=\log _{10} x$. Then, $f^{\prime}(x)=\frac{1}{x}\left(\log _{10} e\right)$.
Now, $f(x+\delta x)-f(x)=f^{\prime}(x) \cdot \delta x$
$\Rightarrow f(x+\delta x)-f(x)=\frac{1}{x}\left(\log _{10} e\right) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow f(x+\delta x)-f(x)=\frac{0.4343}{x} \cdot \delta x \tag{i}
\end{equation*}
$$

Putting $x=10$ and $\delta x=0.1$ in (i), we get

$$
\begin{aligned}
& f(10.1)-f(10)=\frac{0.4343}{10} \times 0.1 \\
\Rightarrow & \log _{10}(10.1)-\log _{10} 10=0.004343 \\
\Rightarrow & \log _{10}(10.1)=\left(\log _{10} 10\right)+0.004343 \\
& =(1+0.004343)=1.004343
\end{aligned}
$$

Hence, $\log _{10}(10.1)=1.004343$.

---

### Example 7

If $f(x)=3 x^{2}+15 x+5$, then find the approximate value of $f(3.02)$, using differentials.
[CBSE 2008C, '14]

#### Solution

$f(x)=3 x^{2}+15 x+5 \Rightarrow f^{\prime}(x)=6 x+15$
Now, $f(x+\delta x)-f(x)=f^{\prime}(x) \cdot \delta x$

$$
\begin{equation*}
\Rightarrow f(x+\delta x)-f(x)=(6 x+15) \cdot \delta x \tag{i}
\end{equation*}
$$

Putting $x=3$ and $\delta x=0.02$ in (i), we get

$$
\begin{aligned}
& f(3.02)-f(3)=(6 \times 3+15) \times(0.02) \\
\Rightarrow & f(3.02)-77=0.66 \quad\left[\because \quad f(3)=3 \times 3^{2}+15 \times 3+5=77\right] \\
\Rightarrow & f(3.02)=77+0.66=77.66
\end{aligned}
$$

---

## Use of the Formula: $\quad \delta \boldsymbol{y}=\frac{\boldsymbol{d} \boldsymbol{y}}{\boldsymbol{d} \boldsymbol{x}} \cdot \delta \boldsymbol{x}$

### Example 8

If the radius of a circle increases from 5 cm to 5.1 cm , find the increase in area.

#### Solution

Area of a circle of radius $r$ is given by $A=\pi r^{2}$.

$$
\begin{aligned}
\text { Now, } A=\pi r^{2} & \Rightarrow \frac{d A}{d r}=2 \pi r \\
& \Rightarrow\left[\frac{d A}{d r}\right]_{r=5}=(2 \pi \times 5) \mathrm{cm}^{2}=10 \pi \mathrm{~cm}^{2}
\end{aligned}
$$

Also, $\delta r=(5.1-5) \mathrm{cm}=0.1 \mathrm{~cm}$.
$\therefore \quad \delta A=\frac{d A}{d r} \cdot \delta r=(10 \pi \times 0.1) \mathrm{cm}^{2}=\pi \mathrm{cm}^{2}$.
Hence, the increase in area is $\pi \mathrm{cm}^{2}$.

---

### Example 9

If $y=\left(x^{4}-12\right)$ and if $x$ changes from 2 to 1.99 , what is the approximate change in $y$ ?
[CBSE 2002]

#### Solution

$y=\left(x^{4}-12\right) \Rightarrow \frac{d y}{d x}=4 x^{3}$

$$
\Rightarrow\left[\frac{d y}{d x}\right]_{x=2}=\left(4 \times 2^{3}\right)=32 .
$$

Let $\delta x=(1.99-2)=-0.01$.
$\therefore \quad \delta y=\frac{d y}{d x} \cdot \delta x=32 \times(-0.01)=-0.32$.

---

### Example 10

The time $T$ of oscillation of a simple pendulum of length $l$ is given by $T=2 \pi \sqrt{\frac{l}{g}}$. Find the percentage error in $T$, corresponding to an error of $2 \%$ in the value of $l$.

#### Solution

$$
\begin{aligned}
T=2 \pi \sqrt{\frac{l}{g}} & \Rightarrow \log T=\log 2+\log \pi+\frac{1}{2} \log l-\frac{1}{2} \log g \\
& \Rightarrow \frac{1}{T} \cdot \frac{d T}{d l}=\frac{1}{2 l} \Rightarrow \frac{1}{T} \cdot \frac{d T}{d l} \cdot \delta l=\frac{1}{2 l} \delta l \\
& \Rightarrow \frac{1}{T} \cdot \delta T=\frac{1}{2 l} \cdot \delta l \quad\left[\because \delta T=\frac{d T}{d l} \cdot \delta l\right] \\
& \Rightarrow\left(\frac{\delta T}{T} \times 100\right)=\frac{1}{2} \cdot\left(\frac{\delta l}{l} \times 100\right)=\frac{1}{2} \times 2=1
\end{aligned}
$$

$\therefore$ percentage error in $T=1 \%$.

---

### Example 11

If the error committed in measuring the radius of a circle be $0.01 \%$, find the corresponding error in calculating the area.

#### Solution

$A=\pi r^{2} \Rightarrow \frac{d A}{d r}=2 \pi r \Rightarrow \frac{d A}{d r} \cdot \delta r=2 \pi r \cdot \delta r$

$$
\begin{aligned}
& \Rightarrow \delta A=2 \pi r^{2} \cdot \frac{\delta r}{r} \quad\left[\because \frac{d A}{d r} \cdot \delta r=\delta A\right] \\
& \Rightarrow \frac{\delta A}{A}=2 \cdot \frac{\delta r}{r} \quad\left[\because A=\pi r^{2}\right] \\
& \Rightarrow\left(\frac{\delta A}{A} \times 100\right)=2 \cdot\left(\frac{\delta r}{r} \times 100\right) \\
& \Rightarrow \text { percentage error in area }=(2 \times 0.01)=0.02 \%
\end{aligned}
$$

Hence, the percentage error in area $=0.02 \%$.

---

### Example 12

If in a triangle $A B C$, the side $c$ and the angle $C$ remain constant while the remaining elements are changed slightly, show that $\frac{d a}{\cos A}+\frac{d b}{\cos B}=0$.

#### Solution

As given, we have $\frac{c}{\sin C}=k$ (constant).
$\therefore \quad \frac{a}{\sin A}=\frac{b}{\sin B}=k \Rightarrow a=k \sin A$ and $b=k \sin B$.
$\therefore \quad d a=k \cos A \cdot d A$ and $d b=k \cos B \cdot d B$
or $\frac{d a}{\cos A}+\frac{d b}{\cos B}=k(d A+d B)=k d(A+B)=k d(\pi-C)=0$.
Hence, $\frac{d a}{\cos A}+\frac{d b}{\cos B}=0$.

---

### Example 13

The area $S$ of a triangle is calculated by measuring the sides $b$ and $c$, and $\angle A$. If there be an error $\delta A$ in the measurement of $\angle A$, show that the relative error in area is given by

$$
\frac{\delta S}{S}=\cot A \cdot \delta A
$$

#### Solution

$$
\begin{aligned}
S=\frac{1}{2} b c \sin A & \Rightarrow \frac{d S}{d A}=\frac{1}{2} b c \cos A \Rightarrow \frac{d S}{d A} \cdot \delta A=\frac{1}{2} b c \cos A \cdot \delta A \\
& \Rightarrow \delta S=\frac{1}{2} b c \cos A \cdot \delta A \Rightarrow \delta S=\frac{1}{2} b c \sin A \cdot(\cot A) \cdot \delta A \\
& \Rightarrow \delta S=S \cdot(\cot A) \cdot \delta A \Rightarrow \frac{\delta S}{S}=(\cot A) \cdot \delta A
\end{aligned}
$$

Hence, $\frac{\delta S}{S}=(\cot A) \cdot \delta A$.

---