## Results on Probability

### Theorem 1
Let $S$ be the sample space and let $E$ be an event. Then,
1. $P(E) \geq 0$
2. $P(\phi)=0$
3. $P(S)=1$

#### Proof
1. Since $E$ is an event, we have $E \subseteq S$.
$$
\therefore \quad P(E)=\frac{n(E)}{n(S)} \geq 0 \quad[\because n(E) \geq 0]
$$
2. $$P(\phi)=\frac{n(\phi)}{n(S)}=\frac{0}{n(S)}=0$$
3. $$P(S)=\frac{n(S)}{n(S)}=1$$

---

### Theorem 2
If $E_{1}$ and $E_{2}$ are mutually exclusive events,
1. $P(E_{1} \text{ and } E_{2})=0$, i.e., $P(E_{1} \cap E_{2})=0$
2. $P(E_{1} \text{ or } E_{2})=P(E_{1})+P(E_{2})$, i.e., $P(E_{1} \cup E_{2})=P(E_{1})+P(E_{2})$

#### Proof
Let $S$ be the sample space, and let $E_{1}$ and $E_{2}$ be two mutually exclusive events. Then, $E_{1} \cap E_{2}=\phi$.

1. $P(E_{1} \text{ and } E_{2})=P(E_{1} \cap E_{2})=P(\phi)=0$.
2. $P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2})$
$$
\begin{aligned}
& =\frac{n(E_{1} \cup E_{2})}{n(S)} \\
& =\frac{n(E_{1})+n(E_{2})}{n(S)} \quad [\because E_{1} \cap E_{2}=\phi \Rightarrow n(E_{1} \cup E_{2})=n(E_{1})+n(E_{2})] \\
& =\frac{n(E_{1})}{n(S)}+\frac{n(E_{2})}{n(S)}=P(E_{1})+P(E_{2})
\end{aligned}
$$
$\therefore P(E_{1} \text{ or } E_{2})=P(E_{1})+P(E_{2})$, when $E_{1}$ and $E_{2}$ are mutually exclusive.

**Remark:** If $E_{1}, E_{2}, \ldots, E_{n}$ are pairwise disjoint then
$$
P(E_{1} \cup E_{2} \cup \ldots \cup E_{n})=P(E_{1})+P(E_{2})+\ldots+P(E_{n})
$$

---

## Addition Theorem for Two Events

### Theorem 3
For any two events $E_{1}$ and $E_{2}$,
$$
\begin{gathered}
P(E_{1} \cup E_{2})=P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}), \\
\text{i.e., } P(E_{1} \text{ or } E_{2})=P(E_{1})+P(E_{2})-P(E_{1} \text{ and } E_{2})
\end{gathered}
$$

#### Proof
Let $S$ be the sample space. Then, $E_{1} \subseteq S$ and $E_{2} \subseteq S$. From set theory, we know that
$$
n(E_{1} \cup E_{2})=n(E_{1})+n(E_{2})-n(E_{1} \cap E_{2})
$$
$$
\Rightarrow \frac{n(E_{1} \cup E_{2})}{n(S)}=\frac{n(E_{1})+n(E_{2})-n(E_{1} \cap E_{2})}{n(S)}
$$
$$
=\frac{n(E_{1})}{n(S)}+\frac{n(E_{2})}{n(S)}-\frac{n(E_{1} \cap E_{2})}{n(S)}
$$
$$
\Rightarrow P(E_{1} \cup E_{2})=P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2})
$$
$$
\Rightarrow P(E_{1} \text{ or } E_{2})=P(E_{1})+P(E_{2})-P(E_{1} \text{ and } E_{2})
$$

**Remark:** If $E_{1}$ and $E_{2}$ are mutually exclusive events then $E_{1} \cap E_{2}=\phi$, and so $P(E_{1} \cap E_{2})=P(\phi)=0$. So, in this case, $P(E_{1} \cup E_{2})=P(E_{1})+P(E_{2})$.

---

## Addition Theorem for Three Events

### Theorem 4
For any three events $E_{1}, E_{2}, E_{3}$,
$$
\begin{aligned}
P(E_{1} \cup E_{2} \cup E_{3}) = P(E_{1}) + P(E_{2}) + P(E_{3}) - P(E_{1} \cap E_{2}) - P(E_{2} \cap E_{3}) \\ - P(E_{3} \cap E_{1}) + P(E_{1} \cap E_{2} \cap E_{3})
\end{aligned}
$$

#### Proof
We have
$$
\begin{aligned}
& P(E_{1} \cup E_{2} \cup E_{3}) \\
= & P[(E_{1} \cup E_{2}) \cup E_{3}] \\
= & P(E_{1} \cup E_{2})+P(E_{3})-P[(E_{1} \cup E_{2}) \cap E_{3}] \quad \text{[by the addition theorem for two events]} \\
= & P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2})+P(E_{3})-P[(E_{1} \cap E_{3}) \cup (E_{2} \cap E_{3})] \quad \text{[by the addition theorem on $P(E_{1} \cup E_{2})$]} \\
= & P(E_{1})+P(E_{2})+P(E_{3})-P(E_{1} \cap E_{2}) - [P(E_{1} \cap E_{3})+P(E_{2} \cap E_{3}) - P(E_{1} \cap E_{3} \cap E_{2} \cap E_{3})] \\
= & P(E_{1})+P(E_{2})+P(E_{3})-P(E_{1} \cap E_{2})-P(E_{1} \cap E_{3})-P(E_{2} \cap E_{3}) + P(E_{1} \cap E_{2} \cap E_{3})
\end{aligned}
$$
Hence,
$$
\begin{aligned}
P(E_{1} \cup E_{2} \cup E_{3}) = P(E_{1}) + P(E_{2}) + P(E_{3}) - P(E_{1} \cap E_{2}) - P(E_{2} \cap E_{3}) \\ -P(E_{3} \cap E_{1}) + P(E_{1} \cap E_{2} \cap E_{3})
\end{aligned}
$$

---

### Theorem 5
If $E_{1}$ and $E_{2}$ are two mutually exclusive exhaustive events then $P(E_{1})+P(E_{2})=1$.

#### Proof
Let $S$ be the sample space. Then, $E_{1}$ and $E_{2}$ being mutually exclusive exhaustive events, we have $E_{1} \cap E_{2}=\phi$ and $E_{1} \cup E_{2}=S$.
$$
\therefore \quad P(E_{1})+P(E_{2})=P(E_{1} \cup E_{2}) \quad [\because E_{1} \cap E_{2}=\phi]
$$
$$
=P(S)=1
$$
$$
\therefore \quad (E_{1} \cap E_{2})=\phi \text{ and } (E_{1} \cup E_{2})=S \Rightarrow P(E_{1})+P(E_{2})=1
$$

---

### Theorem 6
For any event $E$, $P(\bar{E})=1-P(E)$.

#### Proof
Let $S$ be the sample space. Now, $(E \cap \bar{E})=\phi$ and $(E \cup \bar{E})=S$
$$
\begin{aligned}
\Rightarrow P(E)+P(\bar{E}) &= P(E \cup \bar{E}) \quad [\because E \cap \bar{E}=\phi] \\
&=P(S)=1 \quad [\because E \cup \bar{E}=S]
\end{aligned}
$$
Hence, $P(\bar{E})=1-P(E)$.

---

### Theorem 7
For any two compatible events $E_{1}$ and $E_{2}$,
$$
P(E_{1}-E_{2})=P(E_{1})-P(E_{1} \cap E_{2})
$$

#### Proof
Let $E_{1}$ and $E_{2}$ be two compatible events. Then, $E_{1} \cap E_{2} \neq \phi$. From the adjoining Venn diagram, we have
![](https://cdn.mathpix.com/cropped/2025_09_25_c1ecdc546437b9f11e56g-24.jpg?height=281&width=400&top_left_y=189&top_left_x=801)
$$
\begin{align*}
& \quad (E_{1}-E_{2}) \cap (E_{1} \cap E_{2})=\phi, \tag{i} \\
& \text{ and } (E_{1}-E_{2}) \cup (E_{1} \cap E_{2})=E_{1}. \tag{ii} \\
& \therefore \quad P(E_{1})=P[(E_{1}-E_{2}) \cup (E_{1} \cap E_{2})] \\
& \quad=P(E_{1}-E_{2})+P(E_{1} \cap E_{2}) \\
& \Rightarrow \quad P(E_{1}-E_{2})=P(E_{1})-P(E_{1} \cap E_{2})
\end{align*}
$$

---

### Theorem 8
If $E_{1}$ and $E_{2}$ be two events such that $E_{1} \subseteq E_{2}$ then $P(E_{1}) \leq P(E_{2})$.

#### Proof
Let $E_{1} \subseteq E_{2}$. Then,
![](https://cdn.mathpix.com/cropped/2025_09_25_c1ecdc546437b9f11e56g-24.jpg?height=223&width=356&top_left_y=614&top_left_x=844)
$$
E_{1} \cap (E_{2}-E_{1})=\phi \text{ and } E_{1} \cup (E_{2}-E_{1})=E_{2}
$$
$$
\begin{aligned}
\therefore \quad P(E_{2}) &= P[E_{1} \cup (E_{2}-E_{1})] \\
&= P(E_{1})+P(E_{2}-E_{1}) \quad [\because E_{1} \cap (E_{2}-E_{1})=\phi]
\end{aligned}
$$
$$
\therefore \quad P(E_{1}) \leq P(E_{2}) \quad [\because P(E_{2}-E_{1}) \geq 0]
$$

---

### Theorem 9
For any event $E, 0 \leq P(E) \leq 1$.

#### Proof
Let $S$ be the sample space and let $E$ be an event. Then, $\phi \subseteq E$ and $E \subseteq S$
$$
\Rightarrow P(\phi) \leq P(E) \text{ and } P(E) \leq P(S)
$$
$$
\Rightarrow P(\phi) \leq P(E) \leq P(S)
$$
$$
\Rightarrow 0 \leq P(E) \leq 1 \quad [\because P(\phi)=0 \text{ and } P(S)=1]
$$
Hence, $0 \leq P(E) \leq 1$, for every event $E$.

---
## Solved Examples

### Example 1

If $E_{1}$ and $E_{2}$ are two events associated with a random experiment such that $P(E_{2})=0.35$, $P(E_{1} \text{ or } E_{2})=0.85$ and $P(E_{1} \text{ and } E_{2})=0.15$, find $P(E_{1})$.

#### Solution:

Let $P(E_{1})=x$. Then,
$$
\begin{aligned}
& P(E_{1} \text{ or } E_{2})=P(E_{1})+P(E_{2})-P(E_{1} \text{ and } E_{2}) \\
\Rightarrow & 0.85=x+0.35-0.15 \\
\Rightarrow & x=(0.85-0.35+0.15)=0.65
\end{aligned}
$$
Hence, $P(E_{1})=0.65$.

---

### Example 2

Two dice are tossed together. Find the probability of getting a doublet or a total of 6. [CBSE 2004C]

#### Solution:

When two dice are thrown together, there are $(6 \times 6)$ outcomes. Let $S$ be the sample space. Then, $n(S)=36$.
Let $E_{1} = \text{event of getting a doublet}$,
and $E_{2} = \text{event of getting a total of 6}$.

Then, $E_{1}=\{(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)\}$
and $E_{2}=\{(2,4),(3,3),(4,2)\}$.
$\therefore (E_{1} \cap E_{2})=\{(3,3)\}$.

Thus, $n(E_{1})=6, n(E_{2})=3$ and $n(E_{1} \cap E_{2})=1$.
$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{6}{36}=\frac{1}{6}$, $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{3}{36}=\frac{1}{12}$
and $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{1}{36}$.

$\therefore P(\text{getting a doublet or a total of 6})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \quad \text{[by the addition theorem]} \\
& =\left(\frac{1}{6}+\frac{1}{12}-\frac{1}{36}\right)=\frac{8}{36}=\frac{2}{9}
\end{aligned}
$$
Hence, the required probability is $\frac{2}{9}$.

---

### Example 3

In a single throw of two dice, find the probability that neither a doublet nor a total of 10 will appear. [CBSE 1998, 2003]

#### Solution:

Let $S$ be the sample space. Then, $n(S)=36$.
Let $E_{1} = \text{event that a doublet appears}$,
and $E_{2} = \text{event of getting a total of 10}$.
Then, $E_{1}=\{(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)\}$,
and $E_{2}=\{(4,6),(5,5),(6,4)\}$.
$\therefore (E_{1} \cap E_{2})=\{(5,5)\}$.

Thus, $n(E_{1})=6$, $n(E_{2})=3$ and $n(E_{1} \cap E_{2})=1$.
$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{6}{36}=\frac{1}{6}$, $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{3}{36}=\frac{1}{12}$
and $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{1}{36}$.

$\therefore P(\text{getting a doublet or a total of 10})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \\
& =\left(\frac{1}{6}+\frac{1}{12}-\frac{1}{36}\right)=\frac{8}{36}=\frac{2}{9}
\end{aligned}
$$

$\therefore P(\text{getting neither a doublet nor a total of 10})$
$$
\begin{aligned}
& =P(\bar{E}_{1} \text{ and } \bar{E}_{2})=P(\bar{E}_{1} \cap \bar{E}_{2}) \\
& =P(\overline{E_{1} \cup E_{2}})=1-P(E_{1} \cup E_{2})=\left(1-\frac{2}{9}\right)=\frac{7}{9}
\end{aligned}
$$
Hence, the required probability is $\frac{7}{9}$.

---

### Example 4

A natural number is chosen at random from among the first 500. What is the probability that the number so chosen is divisible by 3 or 5?

#### Solution:

Let $S$ be the sample space. Then, clearly $n(S)=500$.
Let $E_{1} = \text{event of getting a number divisible by 3}$,
and $E_{2} = \text{event of getting a number divisible by 5}$. Then,
$(E_{1} \cap E_{2}) = \text{event of getting a number divisible by both 3 and 5}$
$= \text{event of getting a number divisible by 15}$.

$\therefore E_{1}=\{3,6,9, \ldots, 495,498\}$, $E_{2}=\{5,10,15, \ldots, 495,500\}$
and $(E_{1} \cap E_{2})=\{15,30,45, \ldots, 495\}$.
$\therefore n(E_{1})=\left(\frac{498}{3}\right)=166$, $n(E_{2})=\left(\frac{500}{5}\right)=100$
and $n(E_{1} \cap E_{2})=\left(\frac{495}{15}\right)=33$.
$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{166}{500}=\frac{83}{250}$, $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{100}{500}=\frac{1}{5}$
and $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{33}{500}$.

$\therefore P(\text{the chosen number is divisible by 3 or 5})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \\
& =\left(\frac{83}{250}+\frac{1}{5}-\frac{33}{500}\right)=\frac{233}{500}
\end{aligned}
$$
Hence, the required probability is $\frac{233}{500}$.

---

### Example 5

A card is drawn at random from a well-shuffled deck of 52 cards. Find the probability of its being a spade or a king.

#### Solution:

Let $S$ be the sample space. Then, $n(S)=52$.
Let $E_{1} = \text{event of getting a spade}$,
and $E_{2} = \text{event of getting a king}$.
Then, $(E_{1} \cap E_{2}) = \text{event of getting a king of spades}$.

Clearly, $n(E_{1})=13$, $n(E_{2})=4$ and $n(E_{1} \cap E_{2})=1$.
$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{13}{52}=\frac{1}{4}$, $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{4}{52}=\frac{1}{13}$
and $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{1}{52}$.

$\therefore P(\text{getting a spade or a king})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \quad \text{[by the addition theorem for two events]} \\
& =\left(\frac{1}{4}+\frac{1}{13}-\frac{1}{52}\right)=\frac{16}{52}=\frac{4}{13}
\end{aligned}
$$
Hence, the required probability is $\frac{4}{13}$.

---

### Example 6

Two cards are drawn at random from a well-shuffled pack of 52 cards. What is the probability that either both are red or both are kings?

#### Solution:

Let $S$ be the sample space. Then,
$$
n(S) = \text{number of ways of drawing 2 cards out of 52} = {}^{52}C_{2}
$$
Let $E_{1} = \text{event that both are red cards}$,
and $E_{2} = \text{event that both are kings}$.
Then, $(E_{1} \cap E_{2}) = \text{event of getting 2 red kings}$.
$\therefore n(E_{1}) = \text{number of ways of drawing 2 red cards out of 26 red cards} = {}^{26}C_{2}$.
$\therefore n(E_{2}) = \text{number of ways of drawing 2 kings out of 4 kings} = {}^{4}C_{2}$.
$\therefore n(E_{1} \cap E_{2}) = \text{number of ways of drawing 2 red kings out of 2 red kings} = {}^{2}C_{2}=1$.

$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{{}^{26}C_{2}}{{}^{52}C_{2}}$; $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{{}^{4}C_{2}}{{}^{52}C_{2}}$
and $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{1}{{}^{52}C_{2}}$.

$\therefore P(\text{drawing both red cards or both kings})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \\
& =\left(\frac{{}^{26}C_{2}}{{}^{52}C_{2}}+\frac{{}^{4}C_{2}}{{}^{52}C_{2}}-\frac{1}{{}^{52}C_{2}}\right)=\frac{({}^{26}C_{2}+{}^{4}C_{2}-1)}{{}^{52}C_{2}} \\
& =\frac{(325+6-1)}{1326}=\frac{330}{1326}=\frac{55}{221}
\end{aligned}
$$
Hence, the required probability is $\frac{55}{221}$.

---

### Example 7

A box contains 100 bolts and 50 nuts. It is given that 50% bolts and 50% nuts are rusted. Two objects are selected from the box at random. Find the probability that either both are bolts or both are rusted. [CBSE 2003C]

#### Solution:

Total number of objects $=(100+50)=150$.
Let $S$ be the sample space. Then,
$$
n(S) = \text{number of ways of selecting 2 objects out of 150} = {}^{150}C_{2}
$$
Number of rusted objects $=(50\% \text{ of } 100) + (50\% \text{ of } 50) = (50+25)=75$.

Let $E_{1} = \text{event of selecting 2 bolts out of 100 bolts}$,
and $E_{2} = \text{event of selecting 2 rusted objects out of 75 rusted objects}$.
$\therefore (E_{1} \cap E_{2}) = \text{event of selecting 2 rusted bolts out of 50 rusted bolts}$.
$\therefore n(E_{1}) = \text{number of ways of selecting 2 bolts out of 100} = {}^{100}C_{2}$.
$\therefore n(E_{2}) = \text{number of ways of selecting 2 rusted objects out of 75} = {}^{75}C_{2}$.
$\therefore n(E_{1} \cap E_{2}) = \text{number of ways of selecting 2 rusted bolts out of 50} = {}^{50}C_{2}$.

$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{{}^{100}C_{2}}{{}^{150}C_{2}}$, $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{{}^{75}C_{2}}{{}^{150}C_{2}}$
and $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{{}^{50}C_{2}}{{}^{150}C_{2}}$.

$P(\text{selecting both bolts or both rusted objects})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2})=P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \\
& =\frac{{}^{100}C_{2}}{{}^{150}C_{2}}+\frac{{}^{75}C_{2}}{{}^{150}C_{2}}-\frac{{}^{50}C_{2}}{{}^{150}C_{2}}=\frac{({}^{100}C_{2}+{}^{75}C_{2}-{}^{50}C_{2})}{{}^{150}C_{2}} \\
& =\frac{(4950+2775-1225)}{11175}=\frac{6500}{11175}=\frac{260}{447}=0.58
\end{aligned}
$$
Hence, the required probability is 0.58.

---

### Example 8

If $E_{1}$ and $E_{2}$ are two events such that $P(E_{1})=0.5, P(E_{2})=0.3$ and $P(E_{1} \text{ and } E_{2})=0.1$, find
(i) $P(E_{1} \text{ or } E_{2})$
(ii) $P(E_{1} \text{ but not } E_{2})$
(iii) $P(E_{2} \text{ but not } E_{1})$
(iv) $P(\text{neither } E_{1} \text{ nor } E_{2})$

#### Solution:

We have $P(E_{1})=0.5, P(E_{2})=0.3$ and $P(E_{1} \cap E_{2})=P(E_{1} \text{ and } E_{2})=0.1$.
$\therefore P(\bar{E}_{1})=\{1-P(E_{1})\}=(1-0.5)=0.5$
and $P(\bar{E}_{2})=\{1-P(E_{2})\}=(1-0.3)=0.7$.

Thus, we have
(i)
$$
\begin{aligned}
P(E_{1} \text{ or } E_{2}) & =P(E_{1} \cup E_{2}) \\
& =P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2}) \\
& =(0.5+0.3-0.1)=0.7
\end{aligned}
$$
(ii)
$$
\begin{aligned}
P(E_{1} \text{ but not } E_{2}) & =P(E_{1} \cap \bar{E}_{2}) \\
& =P(E_{1})-P(E_{1} \cap E_{2}) \\
& =(0.5-0.1)=0.4
\end{aligned}
$$
(iii)
$$
\begin{aligned}
P(E_{2} \text{ but not } E_{1}) & =P(E_{2} \cap \bar{E}_{1}) \\
& =P(E_{2})-P(E_{2} \cap E_{1}) \\
& =P(E_{2})-P(E_{1} \cap E_{2})=(0.3-0.1)=0.2
\end{aligned}
$$
(iv)
$$
\begin{aligned}
P(\text{neither } E_{1} \text{ nor } E_{2}) & =P(\text{not } E_{1} \text{ and not } E_{2}) \\
& =P(\bar{E}_{1} \text{ and } \bar{E}_{2})=P(\bar{E}_{1} \cap \bar{E}_{2}) \\
& =P(\overline{E_{1} \cup E_{2}})=1-P(E_{1} \cup E_{2}) \\
& =1-P(E_{1} \text{ or } E_{2}) \\
& =(1-0.7)=0.3 \quad \text{[using (i)]}
\end{aligned}
$$

---

### Example 9

The probability that at least one of the events $E_{1}$ and $E_{2}$ occurs is 0.6. If the probability of the simultaneous occurrence of $E_{1}$ and $E_{2}$ is 0.2, find $P(\bar{E}_{1})+P(\bar{E}_{2})$.

#### Solution:

Given, $P(E_{1} \cup E_{2})=0.6$ and $P(E_{1} \cap E_{2})=0.2$.
$\therefore P(E_{1} \cup E_{2})=P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2})$
$\Rightarrow P(E_{1})+P(E_{2})=P(E_{1} \cup E_{2})+P(E_{1} \cap E_{2})=(0.6+0.2)=0.8$
$\Rightarrow P(E_{1})+P(E_{2})=0.8$
$\Rightarrow \{1-P(\bar{E}_{1})\} + \{1-P(\bar{E}_{2})\} = 0.8$
$\Rightarrow P(\bar{E}_{1})+P(\bar{E}_{2}) = (2-0.8)=1.2$.
Hence, $P(\bar{E}_{1})+P(\bar{E}_{2})=1.2$.

---

### Example 10

The probabilities of the occurrences of two events $E_{1}$ and $E_{2}$ are 0.25 and 0.50 respectively. The probability of their simultaneous occurrence is 0.14. Find the probability that neither $E_{1}$ nor $E_{2}$ occurs.

#### Solution:

Given, $P(E_{1})=0.25$, $P(E_{2})=0.50$ and $P(E_{1} \text{ and } E_{2})=P(E_{1} \cap E_{2})=0.14$.
$\therefore P(\bar{E}_{1})=1-P(E_{1})=(1-0.25)=0.75$
and $P(\bar{E}_{2})=1-P(E_{2})=(1-0.50)=0.50$.
$\therefore P(\text{neither } E_{1} \text{ nor } E_{2})$
$$
\begin{aligned}
& =P(\text{not } E_{1} \text{ and not } E_{2})=P(\bar{E}_{1} \text{ and } \bar{E}_{2})=P(\bar{E}_{1} \cap \bar{E}_{2}) \\
& =P(\overline{E_{1} \cup E_{2}})=\{1-P(E_{1} \cup E_{2})\} \\
& =1-\{P(E_{1})+P(E_{2})-P(E_{1} \cap E_{2})\} \\
& =1-(0.25+0.50-0.14)=(1-0.61)=0.39
\end{aligned}
$$
Hence, the required probability is 0.39.

---

### Example 11

A card is drawn from a deck of 52 cards. Find the probability of getting a king or a heart or a red card.

#### Solution:

Let $S$ be the sample space. Then, $n(S)=52$.
Let $E_{1}, E_{2}$ and $E_{3}$ be the events of getting a king, a heart and a red card respectively. Then,
$n(E_{1})=4, n(E_{2})=13$ and $n(E_{3})=26$.
$(E_{1} \cap E_{2}) = \text{event of getting a king of hearts;}$
$(E_{2} \cap E_{3}) = \text{event of getting a heart } [\because \text{a heart is a red card also}];$
$(E_{3} \cap E_{1}) = \text{event of getting a red king;}$
and $(E_{1} \cap E_{2} \cap E_{3}) = \text{event of getting a king of hearts.}$

$\therefore n(E_{1} \cap E_{2})=1$, $n(E_{2} \cap E_{3})=13$, $n(E_{3} \cap E_{1})=2$ and $n(E_{1} \cap E_{2} \cap E_{3})=1$.
$\therefore P(E_{1})=\frac{n(E_{1})}{n(S)}=\frac{4}{52}=\frac{1}{13}$; $P(E_{2})=\frac{n(E_{2})}{n(S)}=\frac{13}{52}=\frac{1}{4}$;
$P(E_{3})=\frac{n(E_{3})}{n(S)}=\frac{26}{52}=\frac{1}{2}$; $P(E_{1} \cap E_{2})=\frac{n(E_{1} \cap E_{2})}{n(S)}=\frac{1}{52}$;
$P(E_{2} \cap E_{3})=\frac{n(E_{2} \cap E_{3})}{n(S)}=\frac{13}{52}=\frac{1}{4}$;
$P(E_{3} \cap E_{1})=\frac{n(E_{3} \cap E_{1})}{n(S)}=\frac{2}{52}=\frac{1}{26}$
and $P(E_{1} \cap E_{2} \cap E_{3})=\frac{n(E_{1} \cap E_{2} \cap E_{3})}{n(S)}=\frac{1}{52}$.

$\therefore P(\text{getting a king or a heart or a red card})$
$$
\begin{aligned}
& =P(E_{1} \text{ or } E_{2} \text{ or } E_{3})=P(E_{1} \cup E_{2} \cup E_{3}) \\
& = P(E_{1})+P(E_{2})+P(E_{3})-P(E_{1} \cap E_{2})-P(E_{2} \cap E_{3})-P(E_{3} \cap E_{1}) + P(E_{1} \cap E_{2} \cap E_{3}) \\
& =\left(\frac{1}{13}+\frac{1}{4}+\frac{1}{2}-\frac{1}{52}-\frac{1}{4}-\frac{1}{26}+\frac{1}{52}\right)=\frac{28}{52}=\frac{7}{13}
\end{aligned}
$$
Hence, the required probability is $\frac{7}{13}$.

---

