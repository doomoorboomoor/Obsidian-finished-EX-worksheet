## 32. Binomial Distribution

### Success and Failure in an Experiment

There are certain kinds of experiments which have two possible outcomes. One of these two outcomes is called a **success**, while the other is called a **failure**.

For example, in tossing a coin, we get either a head or a tail. If getting head is taken as a **success** then getting a tail is a **failure**.

### Bernoulli's Theorem

Let there be $n$ independent trials in an experiment and let the random variable $X$ denote the number of successes in these trials. Let the probability of getting a success in a single trial be $p$ and that of getting a failure be $q$ so that $p+q=1$. Then,

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)} .
$$

**PROOF**
Let us denote a success by $S$ and a failure by $F$.
Number of ways of getting $r$ successes in $n$ trials $={ }^{n} C_{r}$.

$$
\begin{aligned}
\therefore \quad P(X=r) & ={ }^{n} C_{r} \cdot\{\underbrace{S S S \ldots S}_{r \text { times }} \text { and } \underbrace{F F F \ldots F}_{(n-r) \text { times }}\} \\
& ={ }^{n} C_{r} \cdot\{P(S) \cdot P(S) \ldots r \text { times }\} \times\{P(F) \cdot P(F) \ldots(n-r) \text { times }\} \\
& ={ }^{n} C_{r} \cdot(p \cdot p \cdot p \ldots r \text { times }) \times[q \cdot q \cdot q \ldots(n-r) \text { times }] \\
& ={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)} .
\end{aligned}
$$

Hence, $P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}$.

**REMARK**
We have

$$
P(X=0)=q^{n} ; P(X=1)=n p q^{(n-1)} ; P(X=2)={ }^{n} C_{2} \cdot p^{2} \cdot q^{(n-2)}, \text { etc. }
$$

The probability distribution of $X$ may be expressed as

$$
\left(\begin{array}{lllll}
X: & 0 & 1 & \ldots & r \\
P(X): & q^{n} & n p q^{(n-1)} & \ldots & C_{r} \cdot p^{r} \cdot q^{(n-r)}
\end{array}\right) .
$$

This distribution is called a **binomial distribution**.

### Conditions for the Applicability of a Binomial Distribution

1.  The experiment is performed for a finite and fixed number of trials.
2.  Each trial must give either a success or a failure.
3.  The probability of a success in each trial is the same.

---

## Solved Examples

### Example 1:

A coin is tossed 4 times. If $X$ is the number of heads observed, find the probability distribution of $X$.

#### Solution:

When a coin is tossed, we have $S=\{H, T\}$.

$$
\begin{aligned}
& P(\text { getting a head })=\frac{1}{2}, \text { and } \\
& P(\text { not getting a head })=\left(1-\frac{1}{2}\right)=\frac{1}{2} .
\end{aligned}
$$

Let $X$ be the random variable denoting the number of heads.
In 4 trials, we may get 0 or 1 or 2 or 3 or 4 heads.
So, $X$ may assume the values $0,1,2,3,4$.

$$
\begin{aligned}
& P(X=0)={ }^{4} C_{0} \cdot\left(\frac{1}{2}\right)^{0} \cdot\left(\frac{1}{2}\right)^{(4-0)}=\frac{1}{16} \\
& P(X=1)={ }^{4} C_{1} \cdot\left(\frac{1}{2}\right)^{1} \cdot\left(\frac{1}{2}\right)^{(4-1)}=\frac{1}{4} \\
& P(X=2)={ }^{4} C_{2} \cdot\left(\frac{1}{2}\right)^{2} \cdot\left(\frac{1}{2}\right)^{(4-2)}=\frac{3}{8} \\
& P(X=3)={ }^{4} C_{3} \cdot\left(\frac{1}{2}\right)^{3} \cdot\left(\frac{1}{2}\right)^{(4-3)}=\frac{1}{4} \\
& P(X=4)={ }^{4} C_{4} \cdot\left(\frac{1}{2}\right)^{4} \cdot\left(\frac{1}{2}\right)^{(4-4)}=\frac{1}{16}
\end{aligned}
$$

Hence, the required probability distribution is given by

$$
\left(\begin{array}{lccccc}
X: & 0 & 1 & 2 & 3 & 4 \\
P(X): & \frac{1}{16} & \frac{1}{4} & \frac{3}{8} & \frac{1}{4} & \frac{1}{16}
\end{array}\right) .
$$

---

### Example 2:

Find the probability distribution of the number of sixes in three tosses of a die.

#### Solution:

When a die is tossed, we have $S=\{1,2,3,4,5,6\}$.

$$
\therefore \quad P(\text { getting a six })=\frac{1}{6} \text { and } P(\text { not getting a six })=\left(1-\frac{1}{6}\right)=\frac{5}{6} .
$$

Let $X$ be the random variable denoting the number of sixes.
In 3 trials, the number of sixes may be 0 or 1 or 2 or 3 .
So, $X$ may assume the values $0,1,2,3$.

$$
\begin{aligned}
& P(X=0)={ }^{3} C_{0} \cdot\left(\frac{1}{6}\right)^{0} \cdot\left(\frac{5}{6}\right)^{(3-0)}=\frac{125}{216} . \\
& P(X=1)={ }^{3} C_{1} \cdot\left(\frac{1}{6}\right)^{1} \cdot\left(\frac{5}{6}\right)^{(3-1)}=\frac{25}{72} .
\end{aligned}
$$

$$
\begin{aligned}
& P(X=2)={ }^{3} C_{2} \cdot\left(\frac{1}{6}\right)^{2} \cdot\left(\frac{5}{6}\right)^{(3-2)}=\frac{5}{72} . \\
& P(X=3)={ }^{3} C_{3} \cdot\left(\frac{1}{6}\right)^{3} \cdot\left(\frac{5}{6}\right)^{(3-3)}=\frac{1}{216} .
\end{aligned}
$$

The required probability distribution of $X$ is given below:

$$
\left(\begin{array}{lcccc}
X: & 0 & 1 & 2 & 3 \\
P(X): & \frac{125}{216} & \frac{25}{72} & \frac{5}{72} & \frac{1}{216}
\end{array}\right) .
$$

---

### Example 3:

Find the probability distribution of the number of doublets in four throws of a pair of dice.

#### Solution:

When a pair of dice is thrown, there are 36 possible outcomes.
$\therefore n(S)=36$.
All possible doublets are $(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)$.
$P(\text { getting a doublet })=\frac{6}{36}=\frac{1}{6}$, and
$P(\text { not getting a doublet })=\left(1-\frac{1}{6}\right)=\frac{5}{6}$.
Let $X$ denote the number of doublets.
In 4 throws, we can have 0 or 1 or 2 or 3 or 4 doublets.

$$
\begin{aligned}
& P(X=0)={ }^{4} C_{0} \cdot\left(\frac{1}{6}\right)^{0} \cdot\left(\frac{5}{6}\right)^{4}=\frac{625}{1296} . \\
& P(X=1)={ }^{4} C_{1} \cdot\left(\frac{1}{6}\right)^{1} \cdot\left(\frac{5}{6}\right)^{3}=\frac{125}{324} . \\
& P(X=2)={ }^{4} C_{2} \cdot\left(\frac{1}{6}\right)^{2} \cdot\left(\frac{5}{6}\right)^{2}=\frac{25}{216} . \\
& P(X=3)={ }^{4} C_{3} \cdot\left(\frac{1}{6}\right)^{3} \cdot\left(\frac{5}{6}\right)^{1}=\frac{5}{324} . \\
& P(X=4)={ }^{4} C_{4} \cdot\left(\frac{1}{6}\right)^{4} \cdot\left(\frac{5}{6}\right)^{0}=\frac{1}{1296} .
\end{aligned}
$$

The required probability distribution is given below:

$$
\left(\begin{array}{lccccc}
X: & 0 & 1 & 2 & 3 & 4 \\
P(X): & \frac{625}{1296} & \frac{125}{324} & \frac{25}{216} & \frac{5}{324} & \frac{1}{1296}
\end{array}\right) .
$$

---

### Example 4:

An unbiased coin is tossed 6 times. Find, using binomial distribution, the probability of getting at least 5 heads.
[CBSE 2000]

#### Solution:

In a single throw of a coin, we have $S=\{H, T\}$.
$P(\text { getting a head })=\frac{1}{2}$, and $P(\text { not getting a head })=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
$\therefore \quad p=\frac{1}{2}$ and $q=\frac{1}{2}$.

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{6} C_{r} \cdot\left(\frac{1}{2}\right)^{r} \cdot\left(\frac{1}{2}\right)^{(6-r)}={ }^{6} C_{r} \cdot\left(\frac{1}{2}\right)^{6}
$$

$\therefore \quad P$ (getting at least 5 heads)

$$
\begin{aligned}
& =P(X \geq 5) \\
& =P(X=5)+P(X=6) \\
& ={ }^{6} C_{5} \cdot\left(\frac{1}{2}\right)^{6}+{ }^{6} C_{6} \cdot\left(\frac{1}{2}\right)^{6}=\left(\frac{3}{32}+\frac{1}{64}\right)=\frac{7}{64} .
\end{aligned}
$$

Hence, the required probability is $\frac{7}{64}$.

---

### Example 5:

An unbiased coin is tossed 8 times. Find, by using binomial distribution, the probability of getting at least 3 heads.
[CBSE 2000]

#### Solution:

In a single throw of a coin, we have $S=\{H, T\}$.
$P(\text { getting a head })=\frac{1}{2}$, and $P(\text { not getting a head })=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
$\therefore \quad p=\frac{1}{2}$ and $q=\frac{1}{2}$.

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{8} C_{r} \cdot\left(\frac{1}{2}\right)^{r} \cdot\left(\frac{1}{2}\right)^{(8-r)}={ }^{8} C_{r}\left(\frac{1}{2}\right)^{8}
$$

$\therefore \quad P$ (getting at least 3 heads)

$$
\begin{aligned}
& =P(X \geq 3) \\
& =1-[P(X=0)+P(X=1)+P(X=2)] \\
& =1-\left[{ }^{8} C_{0} \cdot\left(\frac{1}{2}\right)^{8}+{ }^{8} C_{1} \cdot\left(\frac{1}{2}\right)^{8}+{ }^{8} C_{2} \cdot\left(\frac{1}{2}\right)^{8}\right] \\
& =1-\frac{1}{256} \cdot(1+8+28)=\left(1-\frac{37}{256}\right)=\frac{219}{256} .
\end{aligned}
$$

Hence, the required probability is $\frac{219}{256}$.

---

### Example 6:

Six coins are tossed simultaneously. Find the probability of getting
1.  3 heads
2.  no head
3.  at least one head
4.  not more than 3 heads.
[CBSE 2003]

#### Solution:

The experiment may be taken as throwing a single coin 6 times.
In a single throw of a coin, we have $S=\{H, T\}$.
$P(\text { getting a head })=\frac{1}{2}$, and $P(\text { not getting a head })=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
Let $X$ be the random variable showing the number of heads.

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{6} C_{r} \cdot\left(\frac{1}{2}\right)^{r} \cdot\left(\frac{1}{2}\right)^{6-r}={ }^{6} C_{r} \cdot\left(\frac{1}{2}\right)^{6}
$$

1.  $P$ (getting 3 heads) $=P(X=3)={ }^{6} C_{3} \cdot\left(\frac{1}{2}\right)^{6}=\frac{5}{16}$.
2.  $P($ getting no head $)=P(X=0)={ }^{6} C_{0} \cdot\left(\frac{1}{2}\right)^{6}=\frac{1}{64}$.
3.  $P$ (getting at least 1 head)
    $$
    \begin{aligned}
    & =1-P(X=0)=1-\left[{ }^{6} C_{0} \cdot\left(\frac{1}{2}\right)^{6}\right] \\
    & =\left(1-\frac{1}{64}\right)=\frac{63}{64} .
    \end{aligned}
    $$
4.  $P$ (getting not more than 3 heads)
    $$
    \begin{aligned}
    & =P(\text { no head or } 1 \text { head or } 2 \text { heads or } 3 \text { heads }) \\
    & =P(X=0)+P(X=1)+P(X=2)+P(X=3) \\
    & ={ }^{6} C_{0} \cdot\left(\frac{1}{2}\right)^{6}+{ }^{6} C_{1} \cdot\left(\frac{1}{2}\right)^{6}+{ }^{6} C_{2} \cdot\left(\frac{1}{2}\right)^{6}+{ }^{6} C_{3} \cdot\left(\frac{1}{2}\right)^{6} \\
    & =\left(\frac{1}{2}\right)^{6} \cdot(1+6+15+20)=\left(\frac{1}{64} \times 42\right)=\frac{21}{32}
    \endaligned}
    $$

---

### Example 7:

A die is thrown 5 times. If getting an odd number is a success, find the probability of getting at least 4 successes.

#### Solution:

When a die is thrown, we have $S=\{1,2,3,4,5,6\}$.
$\therefore \quad P(\text { getting an odd number })=\frac{3}{6}=\frac{1}{2}$.
$\therefore \quad P(\text { a success })=\frac{1}{2}$, and $P(\text { not a success })=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
Let $X$ be the random variable showing the number of successes.

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{5} C_{r} \cdot\left(\frac{1}{2}\right)^{r} \cdot\left(\frac{1}{2}\right)^{(5-r)}={ }^{5} C_{r} \cdot\left(\frac{1}{2}\right)^{5} .
$$

$$
\begin{aligned}
& P(\text { at least } 4 \text { successes })=P(4 \text { successes or } 5 \text { successes }) \\
& \quad=P(X=4)+P(X=5) \\
& \quad={ }^{5} C_{4} \cdot\left(\frac{1}{2}\right)^{5}+{ }^{5} C_{5} \cdot\left(\frac{1}{2}\right)^{5}=\left(\frac{5}{32}+\frac{1}{32}\right)=\frac{6}{32}=\frac{3}{16} .
\end{aligned}
$$

---

### Example 8:

In 4 throws with a pair of dice, what is the probability of throwing doublets at least twice?

#### Solution:

In a single throw of a pair of dice, the number of all possible outcomes is 36 .
All doublets are $(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)$.

$$
\begin{aligned}
& P(\text { getting a doublet })=\frac{6}{36}=\frac{1}{6}, \text { and } \\
& P(\text { not getting a doublet })=\left(1-\frac{1}{6}\right)=\frac{5}{6} .
\end{aligned}
$$

Let $X$ be the random variable denoting the number of doublets.
Then, $P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{4} C_{r} \cdot\left(\frac{1}{6}\right)^{r} \cdot\left(\frac{5}{6}\right)^{(4-r)}$.
$P$ (at least 2 doublets)
$=P(X=2)+P(X=3)+P(X=4)$
$={ }^{4} C_{2} \cdot\left(\frac{1}{6}\right)^{2} \cdot\left(\frac{5}{6}\right)^{(4-2)}+{ }^{4} C_{3} \cdot\left(\frac{1}{6}\right)^{3} \cdot\left(\frac{5}{6}\right)^{(4-3)}+{ }^{4} C_{4} \cdot\left(\frac{1}{6}\right)^{4} \cdot\left(\frac{5}{6}\right)^{(4-4)}$
$=6 \cdot\left(\frac{1}{6}\right)^{2} \cdot\left(\frac{5}{6}\right)^{2}+4 \cdot\left(\frac{1}{6}\right)^{3} \cdot\left(\frac{5}{6}\right)^{1}+\left(\frac{1}{6}\right)^{4} \cdot\left(\frac{5}{6}\right)^{0}$
$=\left(\frac{25}{216}+\frac{5}{324}+\frac{1}{1296}\right)=\frac{171}{1296}$.

---

### Example 9:

The bulbs produced in a factory are supposed to contain $5 \%$ defective bulbs. What is the probability that a sample of 10 bulbs will contain not more than 2 defective bulbs?

#### Solution:

$P(\text { getting a defective bulb })=\frac{5}{100}=\frac{1}{20}$, and
$P(\text { getting a nondefective bulb })=\left(1-\frac{1}{20}\right)=\frac{19}{20}$.
Then, $p=\frac{1}{20}$ and $q=\frac{19}{20}$.
Let $X$ denote the number of defective bulbs.

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{10} C_{r} \cdot\left(\frac{1}{20}\right)^{r} \cdot\left(\frac{19}{20}\right)^{(10-r)}
$$

$P$ (getting not more than 2 defective bulbs)

$$
\begin{aligned}
& =P(X=0 \text { or } X=1 \text { or } X=2) \\
& =P(X=0)+P(X=1)+P(X=2) \\
& ={ }^{10} C_{0} \cdot\left(\frac{1}{20}\right)^{0} \cdot\left(\frac{19}{20}\right)^{10}+{ }^{10} C_{1} \cdot\left(\frac{1}{20}\right)^{1} \cdot\left(\frac{19}{20}\right)^{9}+{ }^{10} C_{2} \cdot\left(\frac{1}{20}\right)^{2} \cdot\left(\frac{19}{20}\right)^{8} \\
& =\left(\frac{19}{20}\right)^{10}+\frac{1}{2} \cdot\left(\frac{19}{20}\right)^{9}+\frac{9}{80} \cdot\left(\frac{19}{20}\right)^{8}=\left(\frac{19}{20}\right)^{8} \cdot\left(\frac{149}{100}\right)
\end{aligned}
$$

Let $A=\left(\frac{19}{20}\right)^{8} \cdot\left(\frac{149}{100}\right)$. Then,
$\log A=8(\log 19-\log 20)+\log 149-\log 100$

$$
\begin{aligned}
& \qquad \begin{aligned}
& =8(1.2788-1.3010)+2.1732-2 \\
& =-0.0044=\overline{1} .9956
\end{aligned} \\
& \therefore \quad A=\text { antilog }(\overline{1} .9956)=0.99 \\
& \text { Hence, the required probability }=\frac{99}{100} .
\end{aligned}
$$

---

### Example 10:

If on an average, out of 10 ships, one gets drowned then what is the probability that out of 5 ships at least 4 reach the shore safely?

#### Solution:

Probability of a ship to reach the shore safely $=\frac{9}{10}$.
Probability that a ship gets drowned $=\left(1-\frac{9}{10}\right)=\frac{1}{10}$.
Let $X$ be the random variable showing the number of ships reaching the shore safely.
$\therefore \quad P$ (at least 4 reaching safely)

$$
\begin{aligned}
& =P(4 \text { reaching safely or } 5 \text { reaching safely }) \\
& =P(4 \text { reaching safely })+P(5 \text { reaching safely }) \\
& =P(X=4)+P(X=5) \\
& ={ }^{5} C_{4} \cdot\left(\frac{9}{10}\right)^{4} \cdot\left(\frac{1}{10}\right)^{(5-4)}+{ }^{5} C_{5} \cdot\left(\frac{9}{10}\right)^{5} \cdot\left(\frac{1}{10}\right)^{0} \\
& =\frac{1}{2} \cdot\left(\frac{9}{10}\right)^{4}+\left(\frac{9}{10}\right)^{5}=\left(\frac{9}{10}\right)^{4}\left(\frac{1}{2}+\frac{9}{10}\right)=\frac{7}{5} \cdot\left(\frac{9}{1D}\right)^{4}
\end{aligned}
$$

Let $A=\frac{7}{5} \cdot\left(\frac{9}{10}\right)^{4}=\frac{7 \times(9)^{4}}{5 \times(10)^{4}}$

$$
\begin{gathered}
\Rightarrow \quad \log A=\log 7+4 \times \log 9-\log 5-4 \times \log 10 \\
\quad=(0.8451+4 \times 0.9542-0.6990-4) \\
\quad=-0.0371=\overline{1} .9629
\end{gathered} \Rightarrow \quad \Rightarrow \quad A=\operatorname{antilog}(\overline{1} .9629)=0.9181 .
$$

Hence, the required probability is 0.9181.

---

## 32. Mean and Variance of a Binomial Distribution

### Mean

If a random variable $X$ assumes the values $x_{1}, x_{2}, \ldots, x_{n}$ with probabilities $p_{1}, p_{2}, \ldots, p_{n}$ respectively then the **mean** of $X$ is defined by

$$
\mu=\sum_{i=1}^{n} x_{i} p_{i}
$$

### To Find the Mean of a Binomial Distribution

For the binomial distribution

$$
P(X=r)=P(r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)} \text {, where } r=0,1,2, \ldots, n
$$

The **mean**, $\mu$, is given by

$$
\begin{aligned}
\mu & =\sum_{r=0}^{n} r \cdot p(r)=\sum_{r=0}^{n} r \cdot{ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)} \\
& ={ }^{n} C_{1} \cdot p \cdot q^{n-1}+2 \cdot{ }^{n} C_{2} \cdot p^{2} \cdot q^{(n-2)}+\ldots+n \cdot{ }^{n} C_{n} \cdot p^{n} q^{0} \\
& =1 \cdot n p \cdot q^{n-1}+n(n-1) \cdot p^{2} \cdot q^{(n-2)}+\ldots+n p^{n} \\
& =n p \cdot\left[{ }^{(n-1)} C_{0} \cdot p^{0} \cdot q^{(n-1)}+{ }^{(n-1)} C_{1} \cdot p^{1} \cdot q^{(n-2)}+\ldots\right. \\
& \left.\quad+{ }^{(n-1)} C_{(n-1)} \cdot p^{n-1} \cdot q^{0}\right] \\
& =(n p) \cdot(q+p)^{n-1}=(n p) \quad[\because \quad q+p=1] .
\end{aligned}
$$

Hence, the mean is given by $\mu=n p$.

The **variance** $=\sigma^{2}$ is given by

$$
\begin{aligned}
\sigma^{2} & =\sum_{r=0}^{n} r^{2} \cdot p(r)-(\text { mean })^{2} \\
& =\sum_{r=0}^{n} r^{2} \cdot{ }^{n} C_{r} \cdot p^{r} q^{(n-r)}-(n p)^{2} \quad[\because \text { mean }=n p] \\
& =\sum_{r=0}^{n}\{r+r(r-1)\} \cdot{ }^{n} C_{r} p^{r} q^{(n-r)}-(n p)^{2} \\
& =\sum_{r=0}^{n} r \cdot{ }^{n} C_{r} p^{r} q^{(n-r)}+\sum_{r=0}^{n} r(r-1) \cdot{ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}-(n p)^{2} \\
& =n p+\sum_{r=2}^{n} r(r-1) \cdot \frac{n(n-1)}{r(r-1)} \cdot{ }^{(n-2)} C_{(r-2)} \cdot p^{2} \cdot p^{(r-2)} \cdot q^{(n-r)}-(n p)^{2} \\
& =n p+n(n-1) \cdot p^{2} \cdot\left(\sum_{r=0}^{n}{ }^{(n-2)} C_{(r-2)} \cdot p^{(r-2)} \cdot q^{(n-r)}\right)-n^{2} p^{2} \\
& =n p+n(n-1) p^{2}(q+p)^{(n-2)}-n^{2} p^{2} \\
& =n p+n(n-1) p^{2}-n^{2} p^{2} \quad[\because \quad q+p=1] \\
& =n p-n p^{2}=n p(1-p)=n p q .
\end{aligned}
$$

Hence, **variance** $=n p q$.
$\therefore \quad$ **standard deviation** $=\sqrt{n p q}$.

### Recurrence Relation for a Binomial Distribution

We have

$$
\begin{aligned}
& P(r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)} \text { and } P(r+1)={ }^{n} C_{(r+1)} \cdot p^{(r+1)} \cdot q^{n-r-1} . \\
& \therefore \quad \begin{aligned}
& \frac{P(r+1)}{P(r)}=\frac{{ }^{n} C_{(r+1)} \cdot p^{(r+1)} \cdot q^{n-r-1}}{{ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}} \\
& =\frac{(n!)}{(r+1)!\cdot(n-r-1)!} \cdot \frac{(r)!\cdot(n-r)!}{(n)!} \cdot \frac{p}{q}=\frac{(n-r)}{(r+1)} \cdot \frac{p}{q} \\
\therefore & P(r+1)=\frac{(n-r)}{(r+1)} \cdot \frac{p}{q} \cdot P(r) .
\end{aligned}
\end{aligned}
$$

---

### Example 11:

If $X$ follows a binomial distribution with mean 3 and variance (3/2), find
(i) $P(X \geq 1)$ (ii) $P(X \leq 5)$.
[CBSE 2001C]

#### Solution:

We know that **mean** $=n p$ and **variance** $=n p q$.
$\therefore \quad n p=3$ and $n p q=\frac{3}{2} \Rightarrow 3 q=\frac{3}{2} \Rightarrow q=\frac{1}{2}$.
$\therefore \quad p=(1-q)=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
Now, $n p=3$ and $p=\frac{1}{2} \Rightarrow n \times \frac{1}{2}=3 \Rightarrow n=6$.
So, the binomial distribution is given by

$$
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{6} C_{r} \cdot\left(\frac{1}{2}\right)^{r} \cdot\left(\frac{1}{2}\right)^{(6-r)}={ }^{6} C_{r}\left(\frac{1}{2}\right)^{6} .
$$

(i) $P(X \geq 1)=1-P(X=0)$

$$
=1-{ }^{6} C_{0} \cdot\left(\frac{1}{2}\right)^{6}=\left(1-\frac{1}{64}\right)=\frac{63}{64} .
$$

(ii) $P(X \leq 5)=1-P(X=6)$

$$
=1-{ }^{6} C_{6}\left(\frac{1}{2}\right)^{6}=\left(1-\frac{1}{64}\right)=\frac{63}{64} .
$$

---

### Example 12:

If $X$ follows a binomial distribution with mean 4 and variance 2, find $P(X \geq 5)$.
[CBSE 2001C]

#### Solution:

We know that **mean** $=n p$ and **variance** $=n p q$.
$\therefore \quad n p=4$ and $n p q=2$.
Now, $n p=4$ and $n p q=2 \Rightarrow 4 q=2 \Rightarrow q=\frac{1}{2}$.
$\therefore \quad p=(1-q)=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
Now, $n p=4$ and $p=\frac{1}{2} \Rightarrow \frac{1}{2} n=4 \Rightarrow n=8$.

So, the binomial distribution is given by

$$
\begin{aligned}
P(X=r) & ={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{8} C_{r} \cdot\left(\frac{1}{2}\right)^{r} \cdot\left(\frac{1}{2}\right)^{(8-r)}={ }^{8} C_{r} \cdot\left(\frac{1}{2}\right)^{8} \\
\therefore \quad P(X \geq 5) & =P(X=5)+P(X=6)+P(X=7)+P(X=8) \\
& ={ }^{8} C_{5} \cdot\left(\frac{1}{2}\right)^{8}+{ }^{8} C_{6} \cdot\left(\frac{1}{2}\right)^{8}+{ }^{8} C_{7} \cdot\left(\frac{1}{2}\right)^{8}+{ }^{8} C_{8} \cdot\left(\frac{1}{2}\right)^{8} \\
& =\left[{ }^{8} C_{3}+{ }^{8} C_{2}+{ }^{8} C_{1}+1\right]\left(\frac{1}{2}\right)^{8} \\
& =(56+28+8+1) \cdot \frac{1}{256}=\frac{93}{256} .
\end{aligned}
$$

---

### Example 13:

Find the binomial distribution for which the mean and variance are 12 and 3 respectively.
[CBSE 2004C]

#### Solution:

Let $X$ be a binomial variate for which **mean** $=12$ and **variance** $=3$.
Then, $n p=12$ and $n p q=3 \Leftrightarrow 12 \times q=3 \Leftrightarrow q=\frac{1}{4}$.
$\therefore \quad p=(1-q)=\left(1-\frac{1}{4}\right)=\frac{3}{4}$.
And, $n p=12 \Leftrightarrow n=\frac{12}{p}=\left(12 \times \frac{4}{3}\right)=16$.
Thus, $n=16, p=\frac{3}{4}$ and $q=\frac{1}{4}$.
Hence, the binomial distribution is given by

$$
P(X=r)={ }^{16} C_{r} \cdot\left(\frac{3}{4}\right)^{r} \cdot\left(\frac{1}{4}\right)^{(16-r)} \text {, where } r=0,1,2,3, \ldots, 15 .
$$

---

### Example 14:

If the sum of the mean and variance of a binomial distribution for 5 trials is 1.8, find the distribution.
[CBSE 2004]

#### Solution:

We know that

$$
\text { mean }=n p \text { and variance }=n p q \text {. }
$$

It is being given that $n=5$ and **mean** + **variance** $=1.8$.
$\therefore \quad n p+n p q=1.8$, where $n=5$
$\Leftrightarrow 5 p+5 p q=1.8$
$\Leftrightarrow p+p(1-p)=0.36 \quad[\because \quad q=(1-p)]$
$\Leftrightarrow p^{2}-2 p+0.36=0$
$\Leftrightarrow 100 p^{2}-200 p+36=0$
$\Leftrightarrow \quad 25 p^{2}-50 p+9=0$
$\Leftrightarrow \quad 25 p^{2}-45 p-5 p+9=0$
$\Leftrightarrow 5 p(5 p-9)-(5 p-9)=0$
$\Leftrightarrow \quad(5 p-9)(5 p-1)=0$
$\Leftrightarrow \quad p=\frac{1}{5}=0.2 \quad[\because \quad p$ cannot exceed 1$]$.
Thus, $n=5, p=0.2$, and $q=(1-p)=(1-0.2)=0.8$.
Let $X$ denote the binomial variate. Then, the required distribution is

$$
\begin{aligned}
P(X=r)={ }^{n} C_{r} \cdot p^{r} \cdot q^{(n-r)}={ }^{5} C_{r} \cdot(0.2)^{r} & \cdot(0.8)^{(5-r)}, \\
& \quad \text { where } r=0,1,2,3,4,5 .
\end{aligned}
$$

---

### Example 15:

The sum and the product of the mean and variance of a binomial distribution are 24 and 128 respectively. Find the distribution.

#### Solution:

We have

$$
\begin{aligned}
& n p+n p q=24 \text { and } n p \times n p q=128 \\
\Leftrightarrow & (n p)(1+q)=24 \text { and } n^{2} p^{2} \times q=128 \\
\Leftrightarrow & n^{2} p^{2}=\frac{576}{(1+q)^{2}} \text { and } n^{2} p^{2} \times q=128 \\
\Leftrightarrow & \frac{576}{(1+q)^{2}}=\frac{128}{q} \Leftrightarrow 2\left(1+q^{2}+2 q\right)=9 q \\
\Leftrightarrow & 2 q^{2}-5 q+2=0 \Leftrightarrow(2 q-1)(q-2)=0 \\
\Leftrightarrow & q=\frac{1}{2}[\because q \neq 2] . \\
\therefore & p=(1-q)=\left(1-\frac{1}{2}\right)=\frac{1}{2} .
\end{aligned}
$$

Now, $n p(1+q)=24 \Leftrightarrow n \times \frac{1}{2}\left(1+\frac{1}{2}\right)=24 \Leftrightarrow n=32$.
Hence, the required probability distribution is given by

$$
P(X=r)={ }^{32} C_{r} \cdot\left(\frac{1}{2}\right)^{32} .
$$

---

### Example 16:

In a binomial distribution, prove that
mean > variance.

#### Solution:

Let $X$ be a binomial variate with parameters $n$ and $p$. Then,

$$
\text { mean }=n p \text { and variance }=n p q \text {. }
$$

$\therefore \quad($ mean $)-($ variance $)=(n p-n p q)=n p(1-q)=n p^{2}>0$

$$
\left[\because \quad(1-q)=p \text { and } n p^{2}>0 \text { as } n \in N\right]
$$

$\Rightarrow \quad[($ mean $)-$ (variance) $]>0$
$\Rightarrow$ **mean** > **variance**.
Hence, **mean** > **variance**.

---

### Example 17:

A die is tossed thrice. Getting an even number is considered a success. What is the variance of the binomial distribution?

#### Solution:

Here, $n=3$.

Let $p=$ probability of getting an even number in a single throw
$\Rightarrow \quad p=\frac{3}{6}=\frac{1}{2}$.
$\Rightarrow \quad q=(1-p)=\left(1-\frac{1}{2}\right)=\frac{1}{2}$.
$\therefore \quad$ **variance** $=n p q=\left(3 \times \frac{1}{2} \times \frac{1}{2}\right)=\frac{3}{4}$.

---

### Example 18:

A die is rolled 20 times. Getting a number greater than 4 is a success. Find the mean and variance of the number of successes.

#### Solution:

In a single throw of a die, we have

$p=$ probability of getting a number greater than $4=\frac{2}{6}=\frac{1}{3}$.
$\therefore \quad q=(1-p)=\left(1-\frac{1}{3}\right)=\frac{2}{3}$.
Also, $n=20$ (given).
$\therefore \quad$ **mean** $=n p=\left(20 \times \frac{1}{3}\right)=6.67$, and

$$
\text { variance }=n p q=\left(20 \times \frac{1}{3} \times \frac{2}{3}\right)=4.44
$$

---

### Example 19:

A die is tossed 180 times. Find the expected number $(\mu)$ of times the face with the number 5 will appear. Also, find the standard deviation ( $\sigma$ ), and variance ( $\sigma^{2}$ ).

#### Solution:

In a single throw of a die, $S=\{1,2,3,4,5,6\}$.
$p=($ probability of getting the number 5$)=\frac{1}{6}$.
$\therefore \quad q=(1-p)=\left(1-\frac{1}{6}\right)=\frac{5}{6}$.
Thus, $n=180, p=\frac{1}{6}$ and $q=\frac{5}{6}$.
$\therefore \quad \mu=n p=\left(180 \times \frac{1}{6}\right)=30$.
**Variance** $=\sigma^{2}=n p q=\left(180 \times \frac{1}{6} \times \frac{5}{6}\right)=25$.
**Standard deviation** $=\sigma=\sqrt{25}=5$.

---