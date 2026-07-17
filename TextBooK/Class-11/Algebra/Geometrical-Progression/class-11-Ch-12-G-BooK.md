## INFINITE GEOMETRIC SERIES

THEOREM Prove that the sum of an infinite GP with first term $a$ and common ratio $r$, where $|r|<1$, is given by

$$
S=\frac{a}{(1-r)}
$$

PROOF Let us consider an infinite GP with first term $a$ and common ratio $r$, where $-1<r<1$, i.e., $|r|<1$.
The sum of $n$ terms of a GP is given by

$$
\begin{equation*}
S_{n}=\frac{a\left(1-r^{n}\right)}{(1-r)} \Rightarrow S_{n}=\left\{\frac{a}{(1-r)}-\frac{a r^{n}}{(1-r)}\right\} \tag{i}
\end{equation*}
$$

Since $|r|<1$, so when $n$ increases then $r^{n}$ decreases.
Thus, when $n \rightarrow \infty$ then $r^{n} \rightarrow 0$.
$\therefore \quad \lim _{n \rightarrow \infty} \frac{r^{n}}{(1-r)}=0$.
Hence, the sum of an infinite GP is given by

$$
\begin{aligned}
S=\lim _{n \rightarrow \infty} S_{n} & =\lim _{n \rightarrow \infty}\left\{\frac{a}{(1-r)}-\frac{a r^{n}}{(1-r)}\right\} \\
& =\frac{a}{(1-r)}-\lim _{n \rightarrow \infty} \frac{a r^{n}}{(1-r)}=\left\{\frac{a}{(1-r)}-0\right\}=\frac{a}{(1-r)}
\end{aligned}
$$

[using (i)].
This gives, $S=\frac{a}{(1-r)}$, when $|r|<1$.
REMARKS 1. We shall denote the sum of an infinite GP by $S$.
2. If $r \geq 1$ then sum of an infinite GP is $S=\infty$.

## SUMMARY

Sum of an infinite GP with the first term $a$ and the common ratio $r$, where $|r|<1$, is given by $S=\frac{a}{(1-r)}$.

## SOLVED EXAMPLES

EXAMPLE 1 Find the sum of the infinite geometric series $\left(1+\frac{1}{3}+\frac{1}{9}+\frac{1}{27}+\ldots \infty\right)$.
SOLUTION In the given infinite geometric series, we have

$$
a=1 \text { and } r=\frac{1}{3} \text { such that }|r|=\frac{1}{3}<1 \text {. }
$$

Hence, the sum of the given infinite series is

$$
S=\frac{a}{(1-r)}=\frac{1}{\left(1-\frac{1}{3}\right)}=\frac{1}{\left(\frac{2}{3}\right)}=\frac{3}{2}
$$

Hence, the required sum is $\frac{3}{2}$.
example 2 Find the sum of the infinite geometric series $\left(1-\frac{1}{3}+\frac{1}{3^{2}}-\frac{1}{3^{3}}+\ldots \infty\right)$.
SOLUTION The given series is an infinite geometric series in which

$$
a=1, r=-\frac{1}{3} \text { and }|r|=\frac{1}{3}<1 \text {. }
$$

Hence, the sum of the given infinite geometric series is

$$
S=\frac{a}{(1-r)}=\frac{1}{\left(1+\frac{1}{3}\right)}=\frac{1}{\left(\frac{4}{3}\right)}=\frac{3}{4} .
$$

EXAMPLE 3 Find the sum of the infinite geometric series $\left(\frac{-5}{4}+\frac{5}{16}-\frac{5}{64}+\ldots \infty\right)$.

SOLUTION In the given infinite geometric series, we have

$$
a=\frac{-5}{4}, r=\left(\frac{5}{16} \times \frac{4}{-5}\right)=-\frac{1}{4} \text { and }|r|=\frac{1}{4}<1 .
$$

Hence, the sum of the given infinite geometric series is

$$
S=\frac{a}{(1-r)}=\frac{(-5 / 4)}{\left(1+\frac{1}{4}\right)}=\left(\frac{-5}{4} \times \frac{4}{5}\right)=-1
$$

EXAMPLE 4 Find the sum of the infinite geometric series

$$
(\sqrt{2}+1)+1+(\sqrt{2}-1)+\ldots \infty .
$$

SOLUTION We have

$$
\frac{1}{(\sqrt{2}+1)}=\frac{1}{(\sqrt{2}+1)} \times \frac{(\sqrt{2}-1)}{(\sqrt{2}-1)}=\frac{(\sqrt{2}-1)}{1}
$$

So, the given series is an infinite geometric series in which $a=(\sqrt{2}+1)$ and $r=(\sqrt{2}-1)<1$.
Hence, the sum of the given infinite geometric series is

$$
\begin{aligned}
S=\frac{a}{(1-r)} & =\frac{(\sqrt{2}+1)}{\{1-(\sqrt{2}-1)\}}=\frac{(\sqrt{2}+1)}{(2-\sqrt{2})} \times \frac{(2+\sqrt{2})}{(2+\sqrt{2})} \\
& =\frac{4+3 \sqrt{2}}{(4-2)}=\frac{(4+3 \sqrt{2})}{2}
\end{aligned}
$$

EXAMPLE 5 Find the sum of the infinite series:

$$
\left\{\frac{1}{2}+\frac{1}{3^{2}}+\frac{1}{2^{3}}+\frac{1}{3^{4}}+\frac{1}{2^{5}}+\frac{1}{3^{6}}+\ldots \infty\right\}
$$

SOLUTION The given series can be expressed as the sum of two infinite geometric series, shown below.

$$
\begin{aligned}
\left\{\frac{1}{2}+\frac{1}{3^{2}}+\frac{1}{2^{3}}+\frac{1}{3^{4}}+\frac{1}{2^{5}}+\frac{1}{3^{6}}+\ldots \infty\right\} & \\
= & \left\{\frac{1}{2}+\frac{1}{2^{3}}+\frac{1}{2^{5}}+\ldots \infty\right\}+\left\{\frac{1}{3^{2}}+\frac{1}{3^{4}}+\frac{1}{3^{6}}+\ldots \infty\right\} \\
& \quad\left\{\text { an infinite GP with } a=\frac{1}{2} \text { and } r=\frac{1}{4}\right\} \\
& \quad\left\{\text { an infinite GP with } a=\frac{1}{9} \text { and } r=\frac{1}{9}\right\} \\
= & \frac{(1 / 2)}{\left(1-\frac{1}{4}\right)}+\frac{(1 / 9)}{\left(1-\frac{1}{9}\right)}=\frac{(1 / 2)}{(3 / 4)}+\frac{(1 / 9)}{(8 / 9)} \\
= & \left(\frac{1}{2} \times \frac{4}{3}\right)+\left(\frac{1}{9} \times \frac{9}{8}\right)=\left(\frac{2}{3}+\frac{1}{8}\right) \\
= & \frac{16+3}{24}=\frac{19}{24} .
\end{aligned}
$$

EXAMPLE 6 Prove that $6^{1 / 2} \cdot 6^{1 / 4} \cdot 6^{1 / 8} \cdot \ldots \infty=6$.
SOLUTION We observe here that $\left(\frac{1}{2}+\frac{1}{4}+\frac{1}{8}+\ldots \infty\right)$ is an infinite geometric series in which $a=\frac{1}{2}$ and $r=\left(\frac{1}{4} \times \frac{2}{1}\right)=\frac{1}{2}$ such that $|r|<1$.
So, this sum is given by

$$
\begin{align*}
& S=\frac{\left(\frac{1}{2}\right)}{\left(1-\frac{1}{2}\right)}=\frac{\left(\frac{1}{2}\right)}{\left(\frac{1}{2}\right)}=1  \tag{i}\\
\therefore \quad & 6^{\frac{1}{2}} \cdot 6^{\frac{1}{4}} \cdot 6^{\frac{1}{8}} \cdot \ldots \infty=6^{\left(\frac{1}{2}+\frac{1}{4}+\frac{1}{8}+\ldots \infty\right)}=6^{1}=6 \tag{i}
\end{align*}
$$

Hence, $6^{\frac{1}{2}} \cdot 6^{\frac{1}{4}} \cdot 6^{\frac{1}{8}} \cdot \ldots \infty=6$.
EXAMPLE 7 If $|r|<1, x=\left(a+\frac{a}{r}+\frac{a}{r^{2}}+\ldots \infty\right), y=\left(b-\frac{b}{r}+\frac{b}{r^{2}}-\ldots \infty\right)$ and $z=\left(c+\frac{c}{r^{2}}+\frac{c}{r^{4}}+\ldots \infty\right)$, prove that $\frac{x y}{z}=\frac{a b}{c}$.
SOLUTION Clearly, each one of the given series is an infinite geometric series. Taking the sum of each series, we get

$$
\begin{aligned}
& \qquad x=\frac{a}{\left(1-\frac{1}{r}\right)}=\frac{a r}{(r-1)} \quad\left[\because 1 \text { st term }=a \text { and common ratio }=\frac{1}{r}\right], \\
& \qquad y=\frac{b}{\left(1+\frac{1}{r}\right)}=\frac{b r}{(r+1)} \quad\left[\because 1 \text { st term }=b \text { and common ratio }=\frac{-1}{r}\right] \\
& \text { and } \quad z=\frac{c}{\left(1-\frac{1}{r^{2}}\right)}=\frac{c r^{2}}{\left(r^{2}-1\right)}\left[\because 1 \text { st term }=c \text { and common ratio }=\frac{1}{r^{2}}\right] \\
& \therefore \quad \frac{x y}{z}=\frac{a r}{(r-1)} \times \frac{b r}{(r+1)} \times \frac{\left(r^{2}-1\right)}{c r^{2}}=\frac{a b}{c} . \\
& \text { Hence, } \frac{x y}{z}=\frac{a b}{c} .
\end{aligned}
$$

EXAMPLE 8 If $y=x+x^{2}+x^{3}+\ldots \infty$, where $|x|<1$, prove that $x=\frac{y}{(1+y)}$.
SOLUTION By summing the given infinite GS, we get

$$
\begin{aligned}
y=\frac{x}{(1-x)} & \Rightarrow y(1-x)=x \\
& \Rightarrow y-x y=x \Rightarrow x+x y=y \\
& x(1+y)=y \Rightarrow x=\frac{y}{(1+y)}
\end{aligned}
$$

Hence, $x=\frac{y}{(1+y)}$.

EXAMPLE 9 If $x=1+a+a^{2}+\ldots \infty$, where $|a|<1$
and $y=1+b+b^{2}+\ldots \infty$, where $|b|<1$,
prove that $\left(1+a b+a^{2} b^{2}+\ldots \infty\right)=\frac{x y}{(x+y-1)}$.
SOLUTION By summing the given infinite GS, we get

$$
\begin{aligned}
& x=\frac{1}{(1-a)} \text { and } y=\frac{1}{(1-b)} . \\
& \therefore \quad \begin{aligned}
\frac{x y}{(x+y-1)} & =\frac{\left\{\frac{1}{(1-a)} \cdot \frac{1}{(1-b)}\right\}}{\left\{\frac{1}{(1-a)}+\frac{1}{(1-b)}-1\right\}} \\
& =\left\{\frac{1}{(1-a)(1-b)} \times \frac{(1-a)(1-b)}{(1-b)+(1-a)-(1-a)(1-b)}\right\} \\
& =\frac{1}{(1-a b)}=(1-a b)^{-1} \\
& =\left(1+a b+a^{2} b^{2}+\ldots \infty\right)
\end{aligned}
\end{aligned}
$$

Hence, $\left(1+a b+a^{2} b^{2}+\ldots \infty\right)=\frac{x y}{(x+y-1)}$.
EXAMPLE 10 If $x=\left(1+r^{a}+r^{2 a}+\ldots \infty\right)$ and $y=\left(1+r^{b}+r^{2 b}+\ldots \infty\right)$, prove that $r=\left(\frac{x-1}{x}\right)^{\frac{1}{a}}=\left(\frac{y-1}{y}\right)^{\frac{1}{b}}$.
SOLUTION By summing the given infinite geometric series, we get

$$
\begin{aligned}
& \quad x=\frac{1}{\left(1-r^{a}\right)} \text { and } y=\frac{1}{\left(1-r^{b}\right)} \\
& \Rightarrow \quad\left(1-r^{a}\right)=\frac{1}{x} \text { and }\left(1-r^{b}\right)=\frac{1}{y} \\
& \Rightarrow \quad r^{a}=\left(1-\frac{1}{x}\right) \text { and } r^{b}=\left(1-\frac{1}{y}\right) \\
& \Rightarrow \quad r=\left(\frac{x-1}{x}\right)^{\frac{1}{a}} \text { and } r=\left(\frac{y-1}{y}\right)^{\frac{1}{b}} . \\
& \text { Hence, } r=\left(\frac{x-1}{x}\right)^{\frac{1}{a}}=\left(\frac{y-1}{y}\right)^{\frac{1}{b}} .
\end{aligned}
$$

EXAMPLE 11 Use geometric series to express $0.555 \ldots=0 . \overline{5}$ as a rational number.
SOLUTION We have

$$
\begin{aligned}
0 . \overline{5} & =0.5555 \ldots \\
& =0.5+0.05+0.005+0.0005+\ldots \infty \\
& =\frac{5}{10}+\frac{5}{10^{2}}+\frac{5}{10^{3}}+\frac{5}{10^{4}}+\ldots \infty
\end{aligned}
$$

$$
=\frac{\left(\frac{5}{10}\right)}{\left(1-\frac{1}{10}\right)}=\frac{5}{9} \quad\left[\because S=\frac{a}{(1-r)} \text { in an infinite GS }\right]
$$

Hence, $0 . \overline{5}=\frac{5}{9}$.
EXAMPLE 12 Find the rational number whose decimal form is $0.1 \overline{42}$.
SOLUTION We have

$$
\begin{aligned}
0.1 \overline{42} & =0.142424242 \ldots \\
& =0.1+0.042+0.00042+0.0000042+\ldots \infty \\
& =\frac{1}{10}+\left\{\frac{42}{10^{3}}+\frac{42}{10^{5}}+\frac{42}{10^{7}}+\ldots \infty\right\} \\
& =\frac{1}{10}+\frac{\left(\frac{42}{10^{3}}\right)}{\left(1-\frac{1}{10^{2}}\right)}\left[\begin{array}{l}
\text { this being a GS in which } \\
a=\frac{42}{10^{3}} \text { and } r=\left(\frac{42}{10^{5}} \times \frac{10^{3}}{42}\right)=\frac{1}{10^{2}}<1
\end{array}\right] \\
& =\frac{1}{10}+\left(\frac{42}{1000} \times \frac{100}{99}\right)=\left(\frac{1}{10}+\frac{42}{990}\right)=\frac{141}{990}
\end{aligned}
$$

Hence, $0.1 \overline{42}=\frac{141}{990}$.
EXAMPLE 13 Find the rational number whose decimal form is $1.3 \overline{45}$.
SOLUTION We have

$$
\begin{aligned}
1.3 \overline{45} & =1.3454545 \ldots \infty \\
& =1.3+0.045+0.00045+\ldots \infty \\
& =1.3+\left\{\frac{45}{10^{3}}+\frac{45}{10^{5}}+\ldots \infty\right\} \\
& =1.3+\frac{\left(\frac{45}{10^{3}}\right)}{\left(1-\frac{1}{10^{2}}\right)} \quad\left[\begin{array}{l}
\text { this being a GS in which } \\
a=\frac{45}{10^{3}} \text { and } r=\frac{1}{10^{2}}<1
\end{array}\right] \\
& =1.3+\frac{45}{1000} \times \frac{100}{99}=\frac{13}{10}+\frac{45}{990}=\left(\frac{13}{10}+\frac{1}{22}\right) \\
& =\frac{143+5}{110}=\frac{148}{110}=\frac{74}{55}
\end{aligned}
$$

Hence, $1.3 \overline{45}=\frac{74}{55}$.
EXAMPLE 14 The sum of an infinite GP is $\frac{80}{9}$ and its common ratio is $\frac{-4}{5}$. Find its first term.
SOLUTION Let $a$ be the first term of the given infinite GP.
Here, $r=\frac{-4}{5}$ and $|r|=\left|\frac{-4}{5}\right|=\frac{4}{5}<1$.

The sum of this infinite GP is $S=\frac{80}{9}$.

$$
\begin{aligned}
\therefore \quad S=\frac{a}{(1-r)} & \Rightarrow \frac{a}{\left(1+\frac{4}{5}\right)}=\frac{80}{9} \\
& \Rightarrow \frac{5 a}{9}=\frac{80}{9} \Rightarrow 5 a=80 \Rightarrow a=16 .
\end{aligned}
$$

Hence, the first term is 16 .
EXAMPLE 15 The sum of first two terms of an infinite geometric series is 15 and each term of the series is equal to the sum of all the terms following it. Find the series.
SOLUTION
Let the series be $a+a r+a r^{2}+\ldots+a r^{n}+a r^{(n+1)}+\ldots \infty$.
Then, first term $=a$ and common ratio $=r$.
Clearly, $a+a r=15 \Rightarrow a(1+r)=15$.

Also, $a r^{(n-1)}=a r^{n}+a r^{(n+1)}+\ldots \infty$

$$
\begin{equation*}
\left[\because a_{n}=a_{n+1}+a_{n+2}+\ldots \infty\right] \tag{i}
\end{equation*}
$$

$\Rightarrow \quad a r^{(n-1)}=\frac{a r^{n}}{(1-r)} \quad\left[\begin{array}{ll}\because & \text { RHS is a GS in which first term }=a r^{n} \\ & \text { and common ratio }=r\end{array}\right]$
$\Rightarrow \quad 1-r=r \Rightarrow 2 r=1 \Rightarrow r=\frac{1}{2}$.
Putting $r=\frac{1}{2}$ in (i), we get $\frac{3}{2} a=15 \Rightarrow a=\left(15 \times \frac{2}{3}\right)=10$.
Thus, $a=10$ and $r=\frac{1}{2}$.
Hence, the required series is $\left(10+5+\frac{5}{2}+\frac{5}{4}+\ldots \infty\right)$.
EXAMPLE 16 The sum of an infinite geometric series is 8 . If its second term is 2 , find its common ratio.
SOLUTION Let the infinite geometric series be $a, a r, a r^{2}, \ldots, \infty$. Then,

$$
\begin{gather*}
a r=2  \tag{i}\\
\text { and } \frac{a}{(1-r)}=8 \tag{ii}
\end{gather*}
$$

Putting $r=\frac{2}{a}$ from (i) in (ii), we get

$$
\begin{aligned}
\frac{a}{\left(1-\frac{2}{a}\right)}=8 & \Rightarrow \frac{a^{2}}{(a-2)}=8 \Rightarrow a^{2}-8 a+16=0 \\
& \Rightarrow(a-4)^{2}=0 \Rightarrow a-4=0 \Rightarrow a=4
\end{aligned}
$$

Putting $a=4$ in (i), we get $r=\frac{2}{4} \Rightarrow r=\frac{1}{2}$.
Hence, the common ratio of the given geometric series is $\frac{1}{2}$.
EXAMPLE 17 The sum of an infinite geometric series is 15 and the sum of the squares of these terms is 45 . Find the series.
SOLUTION Let $a$ be the first term and $r$ be the common ratio.

Then, the series is $a+a r+a r^{2}+\ldots \infty$.
Now, $\left(a+a r+a r^{2}+\ldots \infty\right)=15 \Rightarrow \frac{a}{(1-r)}=15$
and $\left(a^{2}+a^{2} r^{2}+a^{2} r^{4}+\ldots \infty\right) \Rightarrow \frac{a^{2}}{\left(1-r^{2}\right)}=45$.

On squaring both sides of (i), we get $\frac{a^{2}}{(1-r)^{2}}=225$.

On dividing (iii) by (ii), we get

$$
\begin{aligned}
\frac{a^{2}}{(1-r)^{2}} \times \frac{\left(1-r^{2}\right)}{a^{2}}=\frac{225}{45} & \Rightarrow \frac{1+r}{1-r}=5 \\
& \Rightarrow 1+r=5-5 r \\
& \Rightarrow 6 r=4 \Rightarrow r=\frac{2}{3}
\end{aligned}
$$

Putting $r=\frac{2}{3}$ in (i), we get

$$
a=15 \times\left(1-\frac{2}{3}\right)=\left(15 \times \frac{1}{3}\right)=5
$$

Thus, $a=5$ and $r=\frac{2}{3}$.
Hence, the required series is $\left(5+\frac{10}{3}+\frac{20}{9}+\frac{40}{27}+\ldots \infty\right)$.
EXAMPLE 18 If $S_{1}, S_{2}, S_{3}, \ldots, S_{p}$ denote the sums of infinite geometric series whose first terms are $1,2,3, \ldots, p$ respectively and whose common ratios are $\frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \ldots, \frac{1}{(p+1)}$ respectively, then show that

$$
S_{1}+S_{2}+S_{3}+\ldots+S_{p}=\frac{1}{2} p(p+3)
$$

SOLUTION By the summation of an infinite geometric series, we get

$$
\begin{aligned}
& \qquad \begin{aligned}
S_{1}= & \frac{1}{\left(1-\frac{1}{2}\right)}=2 ; S_{2}=\frac{2}{\left(1-\frac{1}{3}\right)}=3 ; S_{3}=\frac{3}{\left(1-\frac{1}{4}\right)}=4, \ldots, \\
S_{p}= & \frac{p}{\left(1-\frac{1}{p+1}\right)}=(p+1) . \\
\therefore \quad S_{1}+S_{2}+S_{3}+\ldots+S_{p} & =[2+3+4+\ldots+(p+1)] \\
& =\frac{p}{2} \cdot\{2+(p+1)\}=\frac{1}{2} p(p+3) .
\end{aligned} \\
& \text { Hence, } S_{1}+S_{2}+S_{3}+\ldots+S_{p}=\frac{1}{2} p(p+3) .
\end{aligned}
$$

EXAMPLE 19 The side of a given square is 10 cm . The midpoints of its sides are joined to form a new square. Again, the midpoints of the sides of this new square are joined to form another square. This process is continued indefinitely. Find (i) the sum of the areas and (ii) the sum of the perimeters of the squares.

SOLUTION Let $A B C D$ be the given square with each side equal to 10 cm . Let $E, F, G, H$ be the midpoints of the sides $A B, B C, C D$ and $D A$ respectively. Let $P, Q, R, S$ be the midpoints of the sides $E F, F G, G H$ and $H E$ respectively.
$\therefore B E=B F=5 \mathrm{~cm}$
$\Rightarrow E F=\sqrt{B E^{2}+B F^{2}}=\sqrt{25+25} \mathrm{~cm}$
$=\sqrt{50} \mathrm{~cm}=5 \sqrt{2} \mathrm{~cm}$.
$\therefore F Q=F P=\frac{1}{2} E F=\frac{5 \sqrt{2}}{2} \mathrm{~cm}=\frac{5}{\sqrt{2}} \mathrm{~cm}$
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Geometrical-Progression/class-11-Ch-12-G-BooK-001.jpg)
$\Rightarrow P Q=\sqrt{F P^{2}+F Q^{2}}=\sqrt{\frac{25}{2}+\frac{25}{2}} \mathrm{~cm}=\sqrt{25} \mathrm{~cm}=5 \mathrm{~cm}$.
Thus, the sides of the squares are $10 \mathrm{~cm}, 5 \sqrt{2} \mathrm{~cm}, 5 \mathrm{~cm}, \ldots$.
(i) Sum of the areas of the squares formed

$$
\begin{aligned}
& =\left\{(10)^{2}+(5 \sqrt{2})^{2}+5^{2}+\ldots \infty\right\} \mathrm{cm}^{2} \\
& =(100+50+25+\ldots \infty) \mathrm{cm}^{2} \\
& =\frac{100}{\left(1-\frac{1}{2}\right)} \mathrm{cm}^{2}=200 \mathrm{~cm}^{2}\left[\begin{array}{c}
\text { taking the sum of infinite GP } \\
\text { with } a=100 \text { and } r=\frac{1}{2}
\end{array}\right] .
\end{aligned}
$$

(ii) Sum of perimeters of the squares formed

$$
\begin{aligned}
& =(40+20 \sqrt{2}+20+\ldots) \mathrm{cm} \\
& =\frac{40}{\left(1-\frac{1}{\sqrt{2}}\right)} \mathrm{cm}=\frac{40 \sqrt{2}}{(\sqrt{2}-1)} \times \frac{(\sqrt{2}+1)}{(\sqrt{2}+1)} \mathrm{cm}=(80+40 \sqrt{2}) \mathrm{cm} .
\end{aligned}
$$

EXAMPLE 20 Each side of an equilateral triangle is 18 cm . The midpoints of its sides are joined to form another triangle whose midpoints, in turn, are joined to form still another triangle. The process is continued indefinitely. Find the sum of the (i) perimeters of all the triangles and (ii) areas of all the triangles.

Let $\triangle A B C$ be the given triangle having each side 18 cm . Let $D, E, F$ be the midpoints of $B C, C A, A B$ respectively to form $\triangle D E F$. Let $G, H, I$ be the midpoints of $D E, E F$ and $F D$ respectively to form $\triangle G H I$.
We continue this process indefinitely.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Geometrical-Progression/class-11-Ch-12-G-BooK-002.jpg)

The sides of these triangle are $18 \mathrm{~cm}, 9 \mathrm{~cm}, \frac{9}{2} \mathrm{~cm}, \ldots$, and so on.
(i) Sum of the perimeters of all triangles so formed

$$
\begin{aligned}
& =3\left\{18+9+\frac{9}{2}+\frac{9}{4}+\ldots \infty\right\} \mathrm{cm} \\
& =\left\{3 \times \frac{a}{(1-r)}\right\} \mathrm{cm}, \text { where } a=18 \text { and } r=\frac{9}{18}=\frac{1}{2}
\end{aligned}
$$

$$
=\left\{3 \times \frac{18}{\left(1-\frac{1}{2}\right)}\right\} \mathrm{cm}=(3 \times 36) \mathrm{cm}=108 \mathrm{~cm} .
$$

(ii) Sum of the areas of all the triangles so formed

$$
\begin{aligned}
& =\frac{\sqrt{3}}{4} \cdot\left\{(18)^{2}+(9)^{2}+\left(\frac{9}{2}\right)^{2}+\left(\frac{9}{4}\right)^{2}+\ldots \infty\right\} \mathrm{cm}^{2} \\
& =\frac{\sqrt{3}}{4} \cdot\left\{324+81+\frac{81}{4}+\frac{81}{16}+\ldots \infty\right\} \mathrm{cm}^{2} \\
& =\frac{\sqrt{3}}{4} \cdot \frac{a}{(1-r)} \mathrm{cm}^{2}, \text { where } a=324 \text { and } r=\frac{81}{324}=\frac{1}{4} \\
& =\left\{\frac{\sqrt{3}}{4} \times \frac{324}{\left(1-\frac{1}{4}\right)}\right\} \mathrm{cm}^{2}=108 \sqrt{3} \mathrm{~cm}^{2} .
\end{aligned}
$$

EXAMPLE 21 After striking a floor a certain ball rebounds $\frac{4}{5}$ of the height from which it has fallen. Find the total distance that it travels before coming to rest, if it is gently dropped from a height of 120 metres.

SOLUTION Initially, the ball falls from a height of 120 m . After striking the floor, it rebounds and goes to a height of $\left(\frac{4}{5} \times 120\right) \mathrm{m}$.

Now, it falls from this height and after striking the floor, it rebounds and goes to a height of $\frac{4}{5}$ of $\left(\frac{4}{5} \times 120\right) \mathrm{m}=\left\{\left(\frac{4}{5}\right)^{2} \times 120\right\} \mathrm{m}$.
This process continues indefinitely till the ball comes to rest.
Total distance covered by the ball in metres

$$
\begin{aligned}
& =120+2 \times\left[\left\{\frac{4}{5} \times 120\right\}+\left\{\left(\frac{4}{5}\right)^{2} \times 120\right\}+\left\{\left(\frac{4}{5}\right)^{3} \times 120\right\}+\ldots \infty\right] \\
& =120+\left\{2 \times \frac{a}{(1-r)}\right\}, \text { where } a=\left(\frac{4}{5} \times 120\right)=96 \text { and } r=\frac{4}{5} \\
& =\left\{120+\frac{2 \times 96}{\left(1-\frac{4}{5}\right)}\right\}=\{120+(192 \times 5)\}=(120+960)=1080 .
\end{aligned}
$$

Hence, the total distance covered by the ball is 1080 m .
EXAMPLE 22 If $x=\sum_{n=0}^{\infty} \cos ^{2 n} \theta, y=\sum_{n=0}^{\infty} \sin ^{2 n} \phi$ and $z=\sum_{n=0}^{\infty} \cos ^{2 n} \theta \sin ^{2 n} \phi$, where $0<\theta<\phi<\frac{\pi}{2}$ then prove that $x z+y z-z=x y$.

SOLUTION We have

$$
x=\sum_{n=0}^{\infty} \cos ^{2 n} \theta=1+\cos ^{2} \theta+\cos ^{4} \theta+\ldots \infty
$$

$$
\begin{align*}
& =\frac{a}{(1-r)}, \text { where } a=1 \text { and } r=\cos ^{2} \theta \quad \text { [sum of an infinite GP] } \\
& =\frac{1}{\left(1-\cos ^{2} \theta\right)}=\frac{1}{\sin ^{2} \theta} . \\
\therefore \quad & \sin ^{2} \theta=\frac{1}{x} .  \tag{i}\\
& =\sum_{n=0}^{\infty} \sin ^{2 n} \phi=1+\sin ^{2} \phi+\sin ^{4} \phi+\ldots \infty \\
& =\frac{a}{(1-r)}, \text { where } a=1 \text { and } r=\sin ^{2} \phi \quad \text { [sum of an infinite GP] } \\
& =\frac{1}{\left(1-\sin ^{2} \phi\right)}=\frac{1}{\cos ^{2} \phi} . \\
\therefore \quad & \cos ^{2} \phi=\frac{1}{y} .  \tag{ii}\\
& =\frac{\infty}{\sum_{n=0}^{\infty} \cos ^{2 n} \theta \sin ^{2 n} \phi}=1+\cos ^{2} \theta \sin ^{2} \phi+\cos ^{4} \theta \sin ^{4} \phi+\ldots \infty \\
& =\frac{a}{(1-r)}, \text { where } a=1 \text { and } r=\cos ^{2} \theta \sin ^{2} \phi \\
& =\frac{1}{\left(1-\cos ^{2} \theta \sin ^{2} \phi\right)}=\frac{1}{1-\left(1-\sin ^{2} \theta\right)\left(1-\cos ^{2} \phi\right)} \\
& =\frac{1}{1-\left(1-\frac{1}{x}\right)\left(1-\frac{1}{y}\right)}=\frac{1}{1-\left(1-\frac{1}{x}-\frac{1}{y}+\frac{1}{x y}\right)} \quad \text { [using (i) and (ii)] } \\
& =\frac{1}{\left(\frac{1}{x}+\frac{1}{y}-\frac{1}{x y}\right)}=\frac{x y}{(x+y-1)} . \\
\therefore \quad & \frac{x y}{x+y-1} \Rightarrow x z+y z-z=x y .
\end{align*}
$$

Hence, $x z+y z-z=x y$.