## 31. Probability Distribution

### Random Variable

Let $S$ be the sample space associated with a given random experiment. A real-valued function $X$ which assigns a unique real number $X(w)$ to each $w \in S$, is called a **random variable**.

A random variable which can assume only a finite number of values is called a **discrete random variable**.

**Example:** Suppose that a coin is tossed twice.
Then, sample space $S=\{T T, H T, T H, H H\}$.
Consider a real-valued function $X$ on $S$, defined by
$X: S \rightarrow R: X(w)=$ number of heads in $w$, for all $w \in S$.
Then, $X$ is a random variable such that
$X(T T)=0, X(H T)=1, X(T H)=1$ and $X(H H)=2$.
Clearly, range $(X)=\{0,1,2\}$.

---

### Probability Distribution of a Random Variable

A description giving the values of a random variable along with the corresponding probabilities is called the **probability distribution** of the random variable.

If a random variable $X$ takes the values $x_{1}, x_{2}, \ldots, x_{n}$ with respective probabilities $p_{1}, p_{2}, \ldots, p_{n}$ then the probability distribution of $X$ is given by

| $X$ | $x_{1}$ | $x_{2}$ | $x_{3}$ | $\ldots$ | $\ldots$ | $x_{n}$ |
| :---: | :--- | :--- | :--- | :--- | :--- | :--- |
| $P(X)$ | $p_{1}$ | $p_{2}$ | $p_{3}$ | $\ldots$ | $\ldots$ | $p_{n}$ |

#### Remark:

The above probability distribution of $X$ is defined only when
1. each $p_{i} \geq 0$
2. $\sum_{i=1}^{n} p_{i}=1$

---

### Mean and Variance of Random Variables

Let a random variable $X$ assume values $x_{1}, x_{2}, \ldots, x_{n}$ with probabilities $p_{1}$, $p_{2}, \ldots, p_{n}$ respectively such that each $p_{i} \geq 0$ and $\sum_{i=1}^{n} p_{i}=1$. Then **mean** of $X$, denoted by $\mu$ [or **expected value** of $X$, denoted by $E(X)$], is defined as

$$
\mu=E(X)=\sum_{i=1}^{n} x_{i} p_{i} .
$$

And, the **variance**, denoted by $\sigma^{2}$, is defined as

$$
\sigma^{2}=\left(\sum x_{i}^{2} p_{i}-\mu^{2}\right) .
$$

**Standard deviation**, $\sigma$, is given by

$$
\sigma=\sqrt{\text { variance. }}
$$

---

## Solved Examples

### Example 1:

Find the mean, variance and standard deviation of the number of tails in two tosses of a coin.

#### Solution:

In two tosses of a coin, the sample space is given by

$$
S=\{H H, H T, T H, T T\} .
$$

$\therefore n(S)=4$.
So, every single outcome has a probability $\frac{1}{4}$.
Let $X=$ number of tails in two tosses.
In two tosses, we may have no tail, 1 tail or 2 tails.
So, the possible values of $X$ are $0,1,2$.
$P(X=0)=P(\text{getting no tail})=P(H H)=\frac{1}{4}$.
$P(X=1)=P(\text{getting 1 tail})=P(H T \text{ or } T H)=\frac{2}{4}=\frac{1}{2}$.
$P(X=2)=P(\text{getting 2 tails})=P(T T)=\frac{1}{4}$.
Hence, the probability distribution of $X$ is given by

| $X=x_{i}$ | 0 | 1 | 2 |
| :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{1}{4}$ | $\frac{1}{2}$ | $\frac{1}{4}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{1}{4}\right)+\left(1 \times \frac{1}{2}\right)+\left(2 \times \frac{1}{4}\right)=1$.
Variance, $\sigma^{2}=\Sigma x_{i}^{2} p_{i}-\mu^{2}$

$$
\begin{aligned}
& =\left[\left(0 \times \frac{1}{4}\right)+\left(1 \times \frac{1}{2}\right)+\left(4 \times \frac{1}{4}\right)\right]-1^{2} \\
& =\frac{1}{2} .
\end{aligned}
$$

Standard deviation, $\sigma=\frac{1}{\sqrt{2}} \times \frac{\sqrt{2}}{\sqrt{2}}=\frac{\sqrt{2}}{2}=\frac{1.414}{2}=0.707$.

---

### Example 2:

Find the mean, variance and standard deviation of the number of heads when three coins are tossed.

#### Solution:

Here, $S=\{T T T, T T H, T H T, H T T, T H H, H T H, H H T, H H H\}$.
$\therefore n(S)=8$.
So, every single outcome has a probability $\frac{1}{8}$.
Let $X=$ number of heads in tossing three coins.
The number of heads may be $0,1,2$, or 3 .
So, the possible values of $X$ are $0,1,2,3$.
$P(X=0)=P(\text{getting no head})=P(T T T)=\frac{1}{8}$.
$P(X=1)=P(\text{getting 1 head})=P(\text{TTH or THT or HTT})=\frac{3}{8}$.
$P(X=2)=P(\text{getting 2 heads})=P(T H H, H T H, H H T)=\frac{3}{8}$.
$P(X=3)=P(\text{getting 3 heads})=P(H H H)=\frac{1}{8}$.
Thus, we have the following probability distribution:

| $X=x_{i}$ | 0 | 1 | 2 | 3 |
| :---: | :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{1}{8}$ | $\frac{3}{8}$ | $\frac{3}{8}$ | $\frac{1}{8}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{1}{8}\right)+\left(1 \times \frac{3}{8}\right)+\left(2 \times \frac{3}{8}\right)+\left(3 \times \frac{1}{8}\right)=\frac{3}{2}$.
Variance, $\sigma^{2}=\Sigma x_{i}^{2} p_{i}-\mu^{2}$

$$
=\left[\left(0 \times \frac{1}{8}\right)+\left(1 \times \frac{3}{8}\right)+\left(4 \times \frac{3}{8}\right)+\left(9 \times \frac{1}{8}\right)-\frac{9}{4}\right]=\frac{3}{4} .
$$

Standard deviation, $\sigma=\frac{\sqrt{3}}{2}$.

---

### Example 3:

A die is tossed once. If the random variable $X$ is defined as

$$
X=\left\{\begin{array}{l}
1, \text { if the die results in an even number } \\
0, \text { if the die results in an odd number }
\end{array}\right.
$$

then find the mean and variance of $X$.

#### Solution:

In tossing a die once, the sample space is given by

$$
S=\{1,2,3,4,5,6\} .
$$

$\therefore P(\text{getting an even number})=\frac{3}{6}=\frac{1}{2}$,
$P(\text{getting an odd number})=\frac{3}{6}=\frac{1}{2}$.

As given, $X$ takes the value 0 or 1 .

$$
\begin{aligned}
& P(X=0)=P(\text { getting an odd number })=\frac{1}{2} \\
& P(X=1)=P(\text { getting an even number })=\frac{1}{2}
\end{aligned}
$$

Thus, the probability distribution of $X$ is given by

| $X=x_{i}$ | 0 | 1 |
| :---: | :---: | :---: |
| $p_{i}$ | $\frac{1}{2}$ | $\frac{1}{2}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{1}{2}\right)+\left(1 \times \frac{1}{2}\right)=\frac{1}{2}$.
Variance, $\sigma^{2}=\Sigma x_{i}^{2} p_{i}-\mu^{2}$

$$
=\left(0 \times \frac{1}{2}\right)+\left(1 \times \frac{1}{2}\right)-\left(\frac{1}{2}\right)^{2}=\left(\frac{1}{2}-\frac{1}{4}\right)=\frac{1}{4} .
$$

---

### Example 4:

Find the mean, variance and standard deviation of the number of sixes in two tosses of a die.

#### Solution:

In a single toss, we have

$$
\begin{aligned}
& \text { probability of getting a six }=\frac{1}{6} \text {, and } \\
& \text { probability of getting a non-six }=\left(1-\frac{1}{6}\right)=\frac{5}{6} \text { . }
\end{aligned}
$$

Let $X$ denote the number of sixes in two tosses.
Then, clearly $X$ can assume the value 0,1 , or 2 .
$P(X=0)=P[(\text{non-six in the 1st draw) and (non-six in the 2nd draw})]$
$=P(\text{non-six in the 1st draw}) \times P(\text{non-six in the 2nd draw})$

$$
=\left(\frac{5}{6} \times \frac{5}{6}\right)=\frac{25}{36} .
$$

$P(X=1)=P[(\text{six in the 1st draw and non-six in the 2nd draw})$
or(non-six in the 1st draw and six in the 2nd draw)]
$=P(\text{six in the 1st draw and non-six in the 2nd draw})$
$+P(\text{non-six in the 1st draw and six in the 2nd draw})$
$=\left(\frac{1}{6} \times \frac{5}{6}\right)+\left(\frac{5}{6} \times \frac{1}{6}\right)=\left(\frac{5}{36}+\frac{5}{36}\right)=\frac{10}{36}=\frac{5}{18}$.
$P(X=2)=P[\text{six in the 1st draw and six in the 2nd draw}]$
$=P(\text{six in the 1st draw}) \times P(\text{six in the 2nd draw})$

$$
=\left(\frac{1}{6} \times \frac{1}{6}\right)=\frac{1}{36} .
$$

Hence, the probability distribution is given by

| $X=x_{i}$ | 0 | 1 | 2 |
| :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{25}{36}$ | $\frac{5}{18}$ | $\frac{1}{36}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{25}{36}\right)+\left(1 \times \frac{5}{18}\right)+\left(2 \times \frac{1}{36}\right)=\frac{6}{18}=\frac{1}{3}$.
Variance, $\sigma^{2}=\Sigma x_{i}{ }^{2} p_{i}-\mu^{2}$

$$
=\left[\left(0 \times \frac{25}{36}\right)+\left(1 \times \frac{5}{18}\right)+\left(4 \times \frac{1}{36}\right)-\frac{1}{9}\right]=\frac{5}{18} .
$$

Standard deviation, $\sigma=\sqrt{\frac{5}{18}}=\frac{1}{3} \cdot \sqrt{\frac{5}{2}}$.

---

### Example 5:

Two cards are drawn successively with replacement from a well-shuffled pack of 52 cards. Find the mean and variance of the number of kings.
[CBSE 2005C]

#### Solution:

Let $X$ be the random variable. Then,

$$
X=\text { number of kings obtained in two draws. }
$$

Clearly, $X$ can assume the value 0,1 or 2 .
$P(\text{drawing a king})=\frac{4}{52}=\frac{1}{13}$.
$P(\text{not drawing a king})=\left(1-\frac{1}{13}\right)=\frac{12}{13}$.
$P(X=0)=P(\text{not a king in the 1st draw and not a king in the 2nd draw})$

$$
=\left(\frac{12}{13} \times \frac{12}{13}\right)=\frac{144}{169} .
$$

$P(X=1)=P(\text{a king in the 1st draw and not a king in the 2nd draw}) \text{ or } P(\text{not a king in the 1st draw and a king in the 2nd draw})$

$$
=\left(\frac{1}{13} \times \frac{12}{13}+\frac{12}{13} \times \frac{1}{13}\right)=\frac{24}{169} .
$$

$P(X=2)=P(\text{a king in the 1st draw and a king in the 2nd draw})$

$$
=\left(\frac{1}{13} \times \frac{1}{13}\right)=\frac{1}{169} .
$$

Hence, the probability distribution is given by

| $X=x_{i}$ | 0 | 1 | 2 |
| :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{144}{169}$ | $\frac{24}{169}$ | $\frac{1}{169}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{144}{169}\right)+\left(1 \times \frac{24}{169}\right)+\left(2 \times \frac{1}{169}\right)=\frac{2}{13}$.
Variance, $\sigma^{2}=\Sigma x_{i}{ }^{2} p_{i}-\mu^{2}$

$$
=\left[\left(0 \times \frac{144}{169}\right)+\left(1 \times \frac{24}{169}\right)+\left(4 \times \frac{1}{169}\right)-\frac{4}{169}\right]=\frac{24}{169} .
$$

---

### Example 6:

Two cards are drawn simultaneously (or successively without replacement) from a well-shuffled pack of 52 cards. Find the mean and variance of the number of aces.
[CBSE 2001, '12]

#### Solution:

Let $X$ be the random variable.
Then, $X$ denotes the number of aces in a draw of 2 cards.
$\therefore X$ can assume the value 0,1 or 2 .
Number of ways of drawing 2 cards out of $52=C(52,2)$.
$P(X=0)=P(\text{both non-aces, i.e., 2 non-aces out of 48})$

$$
=\frac{{ }^{48} C_{2}}{{ }^{52} C_{2}}=\left(\frac{48 \times 47}{2 \times 1} \times \frac{2}{52 \times 51}\right)=\frac{188}{221} .
$$

$P(X=1)=P[(\text{one ace out of 4}) \text{ and (one non-ace out of 48})]$

$$
=\frac{{ }^{4} C_{1} \times{ }^{48} C_{1}}{{ }^{52} C_{2}}=\left(\frac{4 \times 48}{52 \times 51} \times 2\right)=\frac{32}{221} .
$$

$P(X=2)=P(\text{both aces})=\frac{{ }^{4} C_{2}}{{ }^{52} C_{2}}=\left(\frac{4 \times 3}{2 \times 1} \times \frac{2 \times 1}{52 \times 51}\right)=\frac{1}{221}$.
Thus, we have the following probability distribution:

| $X=x_{i}$ | 0 | 1 | 2 |
| :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{188}{221}$ | $\frac{32}{221}$ | $\frac{1}{221}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{188}{221}\right)+\left(1 \times \frac{32}{221}\right)+\left(2 \times \frac{1}{221}\right)=\frac{2}{13}$.
Variance, $\sigma^{2}=\Sigma x_{i}{ }^{2} p_{i}-\mu^{2}$

$$
\begin{aligned}
& =\left(0 \times \frac{188}{221}\right)+\left(1 \times \frac{32}{221}\right)+\left(4 \times \frac{1}{221}\right)-\frac{4}{169} \\
& =\left(\frac{36}{221}-\frac{4}{169}\right)=\frac{400}{2873} .
\end{aligned}
$$

---

### Example 7:

Three defective bulbs are mixed with 7 good ones. Let $X$ be the number of defective bulbs when 3 bulbs are drawn at random. Find the mean and variance of $X$.

#### Solution:

Let $X$ denote the random variable showing the number of defective bulbs.
Then, $X$ can take the value $0,1,2$ or 3 .
$\therefore P(X=0)=P(\text{none of the bulbs is defective})$
$=P(\text{all the 3 bulbs are good ones})$
$=\frac{{ }^{7} C_{3}}{{ }^{10} C_{3}}=\left(\frac{7 \times 6 \times 5}{3 \times 2 \times 1} \times \frac{3 \times 2 \times 1}{10 \times 9 \times 8}\right)=\frac{7}{24}$.
$P(X=1)=P(\text{1 defective and 2 non-defective bulbs})$

$$
=\frac{{ }^{3} C_{1} \times{ }^{7} C_{2}}{{ }^{10} C_{3}}=\left(3 \times \frac{7 \times 6}{2 \times 1} \times \frac{3 \times 2 \times 1}{10 \times 9 \times 8}\right)=\frac{21}{40} .
$$

$P(X=2)=P(\text{2 defective and 1 good one})$

$$
=\frac{{ }^{3} C_{2} \times{ }^{7} C_{1}}{{ }^{10} C_{3}}=\left(\frac{3 \times 2}{2 \times 1} \times 7 \times \frac{3 \times 2 \times 1}{10 \times 9 \times 8}\right)=\frac{7}{40} .
$$

$P(X=3)=P(\text{3 defective bulbs})$

$$
=\frac{{ }^{3} C_{3}}{{ }^{10} C_{3}}=\left(1 \times \frac{3 \times 2 \times 1}{10 \times 9 \times 8}\right)=\frac{1}{120} .
$$

Thus, the probability distribution is given by

| $X=x_{i}$ | 0 | 1 | 2 | 3 |
| :---: | :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{7}{24}$ | $\frac{21}{40}$ | $\frac{7}{40}$ | $\frac{1}{120}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{7}{24}\right)+\left(1 \times \frac{21}{40}\right)+\left(2 \times \frac{7}{40}\right)+\left(3 \times \frac{1}{120}\right)=\frac{9}{10}$.
Variance, $\sigma^{2}=\Sigma x_{i}{ }^{2} p_{i}-\mu^{2}$

$$
\begin{aligned}
& =\left(0 \times \frac{7}{24}\right)+\left(1 \times \frac{21}{40}\right)+\left(4 \times \frac{7}{40}\right)+\left(9 \times \frac{1}{120}\right)-\frac{81}{100} \\
& =\left(\frac{13}{10}-\frac{81}{100}\right)=\frac{49}{100}
\end{aligned}
$$

---

### Example 8:

An urn contains 4 white and 3 red balls. Let $X$ be the number of red balls in a random draw of 3 balls. Find the mean and variance of $X$.

#### Solution:

When 3 balls are drawn at random, there may be no red ball, 1 red ball, 2 red balls or 3 red balls.
Let $X$ denote the random variable showing the number of red balls in a draw of 3 balls.
Then, $X$ can take the value $0,1,2$ or 3 .

$$
\begin{aligned}
P(X=0) & =P(\text { getting no red ball }) \\
& =P(\text { getting } 3 \text { white balls }) \\
& =\frac{{ }^{4} C_{3}}{{ }^{7} C_{3}}=\left(\frac{4 \times 3 \times 2}{3 \times 2 \times 1} \times \frac{3 \times 2 \times 1}{7 \times 6 \times 5}\right)=\frac{4}{35}
\end{aligned}
$$

$$
\begin{aligned}
P(X=1) & =P(\text { getting } 1 \text { red and } 2 \text { white balls }) \\
& =\frac{{ }^{3} C_{1} \times{ }^{4} C_{2}}{{ }^{7} C_{3}}=\left(\frac{3 \times 4 \times 3}{2} \times \frac{3 \times 2 \times 1}{7 \times 6 \times 5}\right)=\frac{18}{35}
\end{aligned}
$$

$$
\begin{aligned}
P(X=2) & =P(\text { getting } 2 \text { red and } 1 \text { white ball }) \\
& =\frac{{ }^{3} C_{2} \times{ }^{4} C_{1}}{{ }^{7} C_{3}}=\left(\frac{3 \times 2}{2 \times 1} \times 4 \times \frac{3 \times 2 \times 1}{7 \times 6 \times 5}\right)=\frac{12}{35}
\end{aligned}
$$

$$
P(X=3) =P(\text { getting } 3 \text { red balls })=\frac{{ }^{3} C_{3}}{{ }^{7} C_{3}}=\frac{1 \times 3 \times 2 \times 1}{7 \times 6 \times 5}=\frac{1}{35} .
$$

Thus, the probability distribution of $X$ is given below.

| $X=x_{i}$ | 0 | 1 | 2 | 3 |
| :---: | :---: | :---: | :---: | :---: |
| $p_{i}$ | $\frac{4}{35}$ | $\frac{18}{35}$ | $\frac{12}{35}$ | $\frac{1}{35}$ |

$\therefore \text{ mean, } \mu=\Sigma x_{i} p_{i}=\left(0 \times \frac{4}{35}\right)+\left(1 \times \frac{18}{35}\right)+\left(2 \times \frac{12}{35}\right)+\left(3 \times \frac{1}{35}\right)=\frac{9}{7}$.
Variance, $\sigma^{2}=\Sigma x_{i}{ }^{2} p_{i}-\mu^{2}$

$$
\begin{aligned}
& =\left[\left(0 \times \frac{4}{35}\right)+\left(1 \times \frac{18}{35}\right)+\left(4 \times \frac{12}{35}\right)+\left(9 \times \frac{1}{35}\right)-\frac{81}{49}\right] \\
& =\left(\frac{15}{7}-\frac{81}{49}\right)=\frac{24}{49} .
\end{aligned}
$$

---

### Example 9:

In a game, 3 coins are tossed. A person is paid $₹ 5$ if he gets all heads or all tails; and he is supposed to pay $₹ 3$ if he gets one head or two heads. What can he expect to win on an average per game?

#### Solution:

In tossing 3 coins, the sample space is given by

$$
S=\{H H H, H H T, H T H, T H H, H T T, T H T, T T H, T T T\} .
$$

$\therefore n(S)=8$.
$P(\text{getting all heads or all tails})=\frac{2}{8}=\frac{1}{4}$.
$P(\text{getting one head or 2 heads})=\frac{6}{8}=\frac{3}{4}$.

Let $X=$ number of rupees the person gets.
Then, possible values of $X$ are 5 and -3 .

$P(X=5)=\frac{1}{4} \text{ and } P(X=-3)=\frac{3}{4} .$

Thus, we have

| $X=x_{i}$ | 5 | -3 |
| :---: | :---: | :---: |
| $p_{i}$ | $\frac{1}{4}$ | $\frac{3}{4}$ |

$\therefore \text{ the required expectations} = \text{mean, } \mu=\Sigma x_{i} p_{i}$

$$
=\left(5 \times \frac{1}{4}\right)+(-3) \times \frac{3}{4}=-1,
$$

i.e., he loses $₹ 1$ per toss.

---