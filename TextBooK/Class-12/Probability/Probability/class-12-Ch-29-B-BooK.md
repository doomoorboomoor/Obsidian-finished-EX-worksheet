## Multiplication Theorem on Probability

Let $A$ and $B$ be the two events associated with a sample space $S$. Then, the simultaneous occurrence of two events $A$ and $B$ is denoted by ($A \cap B$) and also written as $AB$.

## Multiplication Theorem

Let $A$ and $B$ be the two events associated with a sample space $S$. Then, prove that

$$
\begin{aligned}
& P(A B)=P(A \cap B)=P(A) \cdot P(B / A)=P(B) \cdot P(A / B), \\
& \quad \text { provided } P(A) \neq 0 \text { and } P(B) \neq 0 .
\end{aligned}
$$

**Proof:** For any events $A$ and $B$, we have

$$
\begin{align*}
& P(A / B)=\frac{P(A \cap B)}{P(B)}, \text { where } P(A) \neq 0 . \\
\therefore \quad & P(A \cap B)=P(B) \cdot P(A / B) . \tag{i}
\end{align*}
$$

Again, $P(B / A)=\frac{P(B \cap A)}{P(A)}=\frac{P(A \cap B)}{P(A)}$, where $P(B) \neq 0$.

$$
\begin{equation*}
\therefore \quad P(A \cap B)=P(A) \cdot P(B / A) . \tag{ii}
\end{equation*}
$$

From (i) and (ii), we get

$$
P(A \cap B)=P(B) \cdot P(A / B)=P(A) \cdot P(A / B), \text { where } P(A) \neq 0 .
$$

---

## Multiplication Rule for Three Events

For any three events $A, B, C$ of the same sample space, we have

$$
\begin{aligned}
P(A \cap B \cap C) & =P(A) \cdot P(B / A) \cdot P[C /(A \cap B)] \\
& =P(A) \cdot P(B / A) \cdot(C / A B) .
\end{aligned}
$$

This rule can be extended for four or more events.

---

## Solved Examples

### Example: 1

An urn contains 8 white and 4 red balls. Two balls are drawn from the urn one after the other without replacement. What is the probability that both drawn balls are white?

#### Solution:

Let $A$ and $B$ denote respectively the events that first and second balls both drawn are white.

Then, we have to find $P(A \cap B)$.
Now, $P(A)=P(\text{white ball in the first draw})=\frac{8}{12}$.
After the occurrence of event $A$, we are left with 7 white and 4 red balls.

The probability of drawing second white ball, given that the first ball drawn is white, is clearly the conditional probability of occurrence of $B$, given that $A$ has occurred.
$\therefore \quad P(B / A)=\frac{7}{11}$.
By multiplication rule of probability, we have

$P(A \cap B)=P(A) \cdot P(B / A)=\left(\frac{8}{12} \times \frac{7}{11}\right)=\frac{14}{33}$.

Hence, the required probability is $\frac{14}{33}$.

---

### Example: 2

Three cards are drawn successively without replacement from a pack of 52 well-shuffled cards. What is the probability that first two cards are queens and the third card drawn is a king?

#### Solution:

Let $Q$ denote the event that the card drawn is a queen and $K$ be the event that the card drawn is a king. Then, we have to find $P(Q Q K)$.
Probability of drawing first queen is $P(Q)=\frac{4}{52}$.
Now, there are 3 queens in remaining 51 cards.
Let $P(Q / Q)$ be the probability of getting the second queen with the condition that one queen has already been drawn.
$\therefore \quad P(Q / Q)=\frac{3}{51}$.
Lastly, $P(K / Q Q)$ is probability of third drawn card to be a king, with the condition that two queens have already been drawn.
Now, there are 4 kings in remaining 50 cards.
$\therefore \quad P(K / Q Q)=\frac{4}{50}$.

By multiplication law of probability, we have

$$
\begin{aligned}
P(Q Q K) & =P(Q \cap Q \cap K) \\
& =P(Q) \cdot P(Q / Q) \cdot P(K / Q Q) \\
& =\left(\frac{4}{52} \times \frac{3}{51} \times \frac{4}{50}\right)=\left(\frac{1}{13} \times \frac{1}{17} \times \frac{2}{25}\right)=\frac{2}{5525}
\end{aligned}
$$

Hence, the required probability is $\frac{2}{5525}$.

---

## Independent Events

Two events $A$ and $B$ are said to be independent if

$$
P(A / B)=P(A), \text { where } P(B) \neq 0
$$

and $P(B / A)=P(B)$, where $P(A) \neq 0$.
i.e., the event $A$ does not depend on the occurence of event $B$ and vice versa.

## Condition for Independence of Two Events

For any two events $A$ and $B$, we have

$$
\begin{equation*}
P(A \cap B)=P(A) \cdot P(B / A) . \tag{i}
\end{equation*}
$$

If $A$ and $B$ are independent, we have $P(B / A)=P(B)$.
$\therefore$ (i) becomes $\boldsymbol{P}(\boldsymbol{A} \cap \boldsymbol{B})=\boldsymbol{P}(\boldsymbol{A}) \times \boldsymbol{P}(\boldsymbol{B})$.
Thus, two events $A$ and $B$ associated with the same random experiment are said to be independent if $P(A \cap B)=P(A) \times P(B)$.

**Note:** Two events $A$ and $B$ are said to be dependent if they are not independent, i.e., if $P(A \cap B) \neq P(A) \times P(B)$.

## Difference between Two Mutually Exclusive and Independent Events

Two events $A$ and $B$ are said to be mutually exclusive if $A \cap B=\varphi$ and in this case $P(A \cap B)=P(\varphi)=0$.
Also we know that two events $A$ and $B$ are independent if $P(A \cap B) =P(A) \times P(B)$.
Clearly, two independent events with nonzero probabilities cannot be mutually exclusive.
Also, two mutually exclusive events with nonzero probabilities cannot be mutually independent.

Three events $A, B$ and $C$ are said to be mutually independent, if

$$
P(A \cap B)=P(A) \times P(B), P(A \cap C)=P(A) \times P(C), P(B \cap C)=P(B) \times P(C)
$$

and $P(A \cap B \cap C)=P(A) \times P(B) \times P(C)$.
If at least one of the above is not true for three given events $A, B$ and $C$, then we say that these events are not independent.

---

### Example: 3

Let $E_{1}$ and $E_{2}$ be two events such that $P\left(E_{1}\right)=0.3, P\left(E_{1} \cup E_{2}\right)=0.4$ and $P\left(E_{2}\right)=x$. Find the value of $x$ such that
(i) $E_{1}$ and $E_{2}$ are mutually exclusive,
(ii) $E_{1}$ and $E_{2}$ are independent.

#### Solution:

(i) Let $E_{1}$ and $E_{2}$ be mutually exclusive. Then, $E_{1} \cap E_{2}=\varphi$.

$$
\begin{aligned}
& \therefore P\left(E_{1} \cup E_{2}\right)=P\left(E_{1}\right)+P\left(E_{2}\right) \\
& \Rightarrow 0.4=0.3+x \\
& \Rightarrow x=0.1 .
\end{aligned}
$$

Thus, when $E_{1}$ and $E_{2}$ mutually exclusive, then $x=0.1$.

(ii) Let $E_{1}$ and $E_{2}$ be two independent events. Then,

$$
P\left(E_{1} \cap E_{2}\right)=P\left(E_{1}\right) \times P\left(E_{2}\right)=0.3 \times x=0.3 x .
$$

$\therefore P\left(E_{1} \cup E_{2}\right)=P\left(E_{1}\right)+P\left(E_{2}\right)-P\left(E_{1} \cap E_{2}\right)$
$$
\begin{aligned}
\Rightarrow & 0.4=0.3+x-0.3 x \\
\Rightarrow & 0.7 x=0.1 \\
\Rightarrow & x=\frac{0.1}{0.7}=\frac{1}{7} .
\end{aligned}
$$

Thus, when $E_{1}$ and $E_{2}$ are independent, then $x=\frac{1}{7}$.

---

### Example: 4

Let $E_{1}$ and $E_{2}$ are the two independent events such that $P\left(E_{1}\right)=0.35$ and $P\left(E_{1} \cup E_{2}\right)=0.60$, find $P\left(E_{2}\right)$.

#### Solution:

Let $P\left(E_{2}\right)=x$.
Then, $E_{1}$ and $E_{2}$ being independent events, we have

$$
P\left(E_{1} \cap E_{2}\right)=P\left(E_{1}\right) \times P\left(E_{2}\right)=0.35 \times x=0.35 x .
$$

Now, $P\left(E_{1} \cup E_{2}\right)=P\left(E_{1}\right)+P\left(E_{2}\right)-P\left(E_{1} \cap E_{2}\right)$
$\Rightarrow \quad 0.60=0.35+x-0.35 x$
$\Rightarrow \quad 0.65 x=0.25$
$\Rightarrow \quad x=\frac{0.25}{0.65}=\frac{25}{65}=\frac{5}{13}$.
Hence, $P\left(E_{2}\right)=\frac{5}{13}$.

---

### Example: 5

A coin is tossed thrice. Let the event $E$ be 'the first throw results in a head', and the event $F$ be 'the last throw results in a tail'. Find whether the events $E$ and $F$ are independent.

#### Solution:

When a coin is tossed three times, the sample space is given by

$$
S=\{H H H, H H T, H T H, T H H, T T H, T H T, H T T, T T T\} .
$$

Now, $E = \text{event that the first throw results in a head}$.
$\therefore E=\{H H H, H H T, H T H, H T T\}$.
And, $F = \text{event that the last throw results in a tail}$.
$\therefore \quad F=\{H H T, T H T, H T T, T T T\}$.

So, $(E \cap F)=\{H H T, H T T\}$.
Clearly, $n(E)=4, n(F)=4, n(E \cap F)=2$ and $n(S)=8$.
$\therefore \quad P(E)=\frac{n(E)}{n(S)}=\frac{4}{8}=\frac{1}{2}, P(F)=\frac{n(F)}{n(S)}=\frac{4}{8}=\frac{1}{2}$
and $P(E \cap F)=\frac{n(E \cap F)}{n(S)}=\frac{2}{8}=\frac{1}{4}$.
Thus, $P(E \cap F)=P(E) \times P(F)$.
Hence, $E$ and $F$ are independent events.

---

### Example: 6

An unbiased die is tossed twice. Find the probability of getting a 4,5 or 6 on the first toss and a 1, 2, 3 or 4 on the second toss.

#### Solution:

In each case, the sample space is given by $S=\{1,2,3,4,5,6\}$.
Let $E = \text{event of getting a 4, 5 or 6 on the first toss}$.
And, $F = \text{event of getting a 1, 2, 3 or 4 on the second toss}$.
Then, $P(E)=\frac{3}{6}=\frac{1}{2}$ and $P(F)=\frac{4}{6}=\frac{2}{3}$.
Clearly, $E$ and $F$ are independent events.
$\therefore \quad$ required probability $=P(E \cap F)=P(E) \times P(F)$
$[\because \quad E$ and $F$ are independent $]$

$$
=\left(\frac{1}{2} \times \frac{2}{3}\right)=\frac{1}{3} .
$$

---

### Example: 7

Ramesh appears for an interview for two posts, $A$ and $B$, for which the selection is independent. The probability for his selection for Post $A$ is $(1 / 6)$ and for Post B, it is (1/7). Find the probability that Ramesh is selected for at least one post.
[CBSE 2001]

#### Solution:

Let $E_{1}=$ event that Ramesh is selected for the post $A$,
and $E_{2}=$ event that Ramesh is selected for the post $B$.
Then, $P\left(E_{1}\right)=\frac{1}{6}$ and $P\left(E_{2}\right)=\frac{1}{7}$.
Clearly, $E_{1}$ and $E_{2}$ are independent events.
$\therefore P\left(E_{1} \cap E_{2}\right)=P\left(E_{1}\right) \times P\left(E_{2}\right)=\left(\frac{1}{6} \times \frac{1}{7}\right)=\frac{1}{42}$.
$\therefore \quad P(\text{Ramesh is selected for at least one post})$

$$
\begin{aligned}
& =P\left(E_{1} \cup E_{2}\right) \\
& =P\left(E_{1}\right)+P\left(E_{2}\right)-P\left(E_{1} \cap E_{2}\right) \\
& =\left(\frac{1}{6}+\frac{1}{7}-\frac{1}{42}\right)=\frac{12}{42}=\frac{2}{7} .
\end{aligned}
$$

Hence, the required probability is $\frac{2}{7}$.

---

### Example: 8

A can solve $90 \%$ of the problems given in a book, and B can solve $70 \%$. What is the probability that at least one of them will solve a problem selected at random from the book?

#### Solution:

Let $E_{1}=$ event that $A$ solves the problem, and $E_{2}=$ event that $B$ solves the problem.
Then, $P\left(E_{1}\right)=\frac{90}{100}=\frac{9}{10}$ and $P\left(E_{2}\right)=\frac{70}{100}=\frac{7}{10}$.
Clearly, $E_{1}$ and $E_{2}$ are independent events.
$\therefore P\left(E_{1} \cap E_{2}\right)=P\left(E_{1}\right) \times P\left(E_{2}\right)=\left(\frac{9}{10} \times \frac{7}{10}\right)=\frac{63}{100}$.
$\therefore \quad P(\text{at least one of them will solve the problem})$

$$
\begin{aligned}
& =P\left(E_{1} \cup E_{2}\right) \\
& =P\left(E_{1}\right)+P\left(E_{2}\right)-P\left(E_{1} \cap E_{2}\right) \\
& =\left(\frac{9}{10}+\frac{7}{10}-\frac{63}{100}\right)=\frac{(90+70-63)}{100}=\frac{97}{100} .
\end{aligned}
$$

Hence, the required probability is 0.97 .

---

### Example: 9

The probability that A hits a target is $(1 / 3)$ and the probability that $B$ hits it is $(2 / 5)$. What is the probability that the target will be hit if both $A$ and B shoot at it?

#### Solution:

Let $E_{1}=$ event that A hits the target,
and $E_{2}=$ event that $B$ hits the target.
Then, $P\left(E_{1}\right)=\frac{1}{3}$ and $P\left(E_{2}\right)=\frac{2}{5}$.
Clearly, $E_{1}$ and $E_{2}$ are independent events.
$\therefore P\left(E_{1} \cap E_{2}\right)=P\left(E_{1}\right) \times P\left(E_{2}\right)=\left(\frac{1}{3} \times \frac{2}{5}\right)=\frac{2}{15}$.
$\therefore \quad P(\text{target is hit})=P(\text{A hits or B hits})$

$$
\begin{aligned}
& =P\left(E_{1} \cup E_{2}\right) \\
& =P\left(E_{1}\right)+P\left(E_{2}\right)-P\left(E_{1} \cap E_{2}\right) \\
& =\left(\frac{1}{3}+\frac{2}{5}-\frac{2}{15}\right)=\frac{9}{15}=\frac{3}{5} .
\end{aligned}
$$

Hence, the required probability is $\frac{3}{5}$.

---

### Example: 10

A and B appear for an interview for two posts. The probability of A 's selection is $(1 / 3)$ and that of $\mathrm{B}^{\prime}$ s selection is $(2 / 5)$. Find the probability that only one of them will be selected.

#### Solution:

Let $E_{1}=$ event that A is selected,
and $E_{2}=$ event that B is selected.

Then, $P\left(E_{1}\right)=\frac{1}{3}$ and $P\left(E_{2}\right)=\frac{2}{5}$
$\Rightarrow P\left(\bar{E}_{1}\right)=\left(1-\frac{1}{3}\right)=\frac{2}{3}$ and $P\left(\bar{E}_{2}\right)=\left(1-\frac{2}{5}\right)=\frac{3}{5}$.
$\therefore \quad P(\text{event that only one of them is selected})$

$$
\begin{aligned}
& =P\left[\left(E_{1} \text { and } \operatorname{not} E_{2}\right) \text { or }\left(E_{2} \text { and } \operatorname{not} E_{1}\right)\right] \\
& =P\left[\left(E_{1} \cap \bar{E}_{2}\right) \text { or }\left(E_{2} \cap \bar{E}_{1}\right)\right] \\
& =P\left(E_{1} \cap \bar{E}_{2}\right)+P\left(E_{2} \cap \bar{E}_{1}\right) \quad\left[\because\left(E_{1} \cap \bar{E}_{2}\right) \cap\left(E_{2} \cap \bar{E}_{1}\right)=\phi\right] \\
& =P\left(E_{1}\right) \cdot P\left(\bar{E}_{2}\right)+P\left(E_{2}\right) \cdot P\left(\bar{E}_{1}\right) \\
& =\left(\frac{1}{3} \times \frac{3}{5}\right)+\left(\frac{2}{5} \times \frac{2}{3}\right)=\left(\frac{1}{5}+\frac{4}{15}\right)=\frac{7}{15} .
\end{aligned}
$$

---

### Example: 11

A speaks the truth in $60 \%$ of the cases, and B in $90 \%$ of the cases. In what percentage of cases are they likely to contradict each other in stating the same fact?
[CBSE 2001]

#### Solution:

Let $E_{1}=$ event that $A$ speaks the truth, and $E_{2}=$ event that $B$ speaks the truth.
Then, $\bar{E}_{1}=$ event that A tells a lie, and $\bar{E}_{2}=$ event that B tells a lie.
Clearly, $E_{1}$ and $E_{2}$ are independent events.
Also, ( $E_{1}$ and $\bar{E}_{2}$ ) as well as ( $\bar{E}_{1}$ and $E_{2}$ ) are independent.
Now, $P\left(E_{1}\right)=\frac{60}{100}=\frac{3}{5} ; P\left(E_{2}\right)=\frac{90}{100}=\frac{9}{10}$;

$$
P\left(\bar{E}_{1}\right)=\left(1-\frac{3}{5}\right)=\frac{2}{5} \text { and } P\left(\bar{E}_{2}\right)=\left(1-\frac{9}{10}\right)=\frac{1}{10} .
$$

$\therefore \quad P(\text{A and B contradict each other})$

$$
\begin{aligned}
& =P[(\mathrm{~A} \text { speaks the truth and } \mathrm{B} \text { tells a lie }) \\
& \quad \text { or (A tells a lie and } \mathrm{B} \text { speaks the truth) }] \\
& =P\left[\left(E_{1} \cap \bar{E}_{2}\right) \cup\left(\bar{E}_{1} \cap E_{2}\right)\right] \\
& =P\left(E_{1} \cap \bar{E}_{2}\right)+P\left(\bar{E}_{1} \cap E_{2}\right)\left[\because\left(E_{1} \cap \bar{E}_{2}\right) \cap\left(\bar{E}_{1} \cap E_{2}\right)=\phi\right] \\
& =\left\{P\left(E_{1}\right) \times P\left(\bar{E}_{2}\right)\right\}+\left\{P\left(\bar{E}_{1}\right) \times P\left(E_{2}\right)\right\} \\
& =\left(\frac{3}{5} \times \frac{1}{10}\right)+\left(\frac{2}{5} \times \frac{9}{10}\right)=\left(\frac{3}{50}+\frac{18}{50}\right)=\frac{21}{50} .
\end{aligned}
$$

Percentage of cases in which A and B contradict each other

$$
=\left(\frac{21}{50} \times 100\right) \%=42 \% .
$$

---

### Example: 12

The probabilities of a specific problem being solved independently by A and B are $\frac{1}{2}$ and $\frac{1}{3}$ respectively. If both try to solve the problem independently, find the probability that
(i) the problem is solved
(ii) exactly one of them solves the problem.

#### Solution:

Let $E_{1}=$ event that $A$ solves the problem,
and $E_{2}=$ event that B solves the problem.
Then, $P\left(E_{1}\right)=\frac{1}{2}$ and $P\left(E_{2}\right)=\frac{1}{3}$
$\Rightarrow P\left(\bar{E}_{1}\right)=\left(1-\frac{1}{2}\right)=\frac{1}{2}$ and $P\left(\bar{E}_{2}\right)=\left(1-\frac{1}{3}\right)=\frac{2}{3}$.
Clearly, $E_{1}$ and $E_{2}$ are independent events.
$\therefore P\left(E_{1} \cap E_{2}\right)=P\left(E_{1}\right) \times P\left(E_{2}\right)=\left(\frac{1}{2} \times \frac{1}{3}\right)=\frac{1}{6}$.

**(i)** $P$ (the problem is solved)

$$
\begin{aligned}
& =P(\text { at least one of } \mathrm{A} \text { and } \mathrm{B} \text { solves the problem }) \\
& =P\left(E_{1} \text { or } E_{2}\right)=P\left(E_{1} \cup E_{2}\right) \\
& =P\left(E_{1}\right)+P\left(E_{2}\right)-P\left(E_{1} \cap E_{2}\right) \\
& =\left(\frac{1}{2}+\frac{1}{3}-\frac{1}{6}\right)=\frac{4}{6}=\frac{2}{3} .
\end{aligned}
$$

**(ii)** $P$ (exactly one of them solves the problem)

$$
\begin{aligned}
& =P\left[\left(E_{1} \text { and } \operatorname{not} E_{2}\right) \text { or }\left(E_{2} \text { and } \operatorname{not} E_{1}\right)\right] \\
& =P\left(E_{1} \text { and } \operatorname{not} E_{2}\right)+P\left(E_{2} \text { and } \operatorname{not} E_{1}\right) \\
& =P\left(E_{1} \cap \bar{E}_{2}\right)+P\left(E_{2} \cap \bar{E}_{1}\right) \\
& =P\left(E_{1}\right) \times P\left(\bar{E}_{2}\right)+P\left(E_{2}\right) \times P\left(\bar{E}_{1}\right) \\
& =\left(\frac{1}{2} \times \frac{2}{3}\right)+\left(\frac{1}{3} \times \frac{1}{2}\right)=\left(\frac{1}{3}+\frac{1}{6}\right)=\frac{3}{6}=\frac{1}{2} .
\end{aligned}
$$

---

### Example: 13

Amit and Nisha appear for an interview for two vacancies in a company. The probability of Amit's selection is $1 / 5$ and that of Nisha's selection is $\frac{1}{6}$. What is the probability that
(i) both of them are selected?
(ii) only one of them is selected?
(iii) none of them is selected?

#### Solution:

Let $E_{1}=$ event that Amit is selected,
and $E_{2}=$ event that Nisha is selected.
Then, $P\left(E_{1}\right)=\frac{1}{5}$ and $P\left(E_{2}\right)=\frac{1}{6}$.
Clearly, $E_{1}$ and $E_{2}$ are independent events.

**(i)** $P($ both are selected $)=P\left(E_{1} \cap E_{2}\right)$

$$
\begin{aligned}
& =P\left(E_{1}\right) \times P\left(E_{2}\right) \\
& \quad\left[\because \quad E_{1} \text { and } E_{2} \text { are independent }\right] \\
& =\left(\frac{1}{5} \times \frac{1}{6}\right)=\frac{1}{30} .
\end{aligned}
$$

**(ii)** $P$ (only one of them is selected)

$$
\begin{aligned}
& =P\left[\left(E_{1} \text { and } \operatorname{not} E_{2}\right) \text { or }\left(E_{2} \text { and } \operatorname{not} E_{1}\right)\right] \\
& =P\left(E_{1} \text { and } \operatorname{not} E_{2}\right)+P\left(E_{2} \text { and } \operatorname{not} E_{1}\right) \\
& =P\left(E_{1}\right) \cdot P\left(\operatorname{not} E_{2}\right)+P\left(E_{2}\right) \cdot P\left(\operatorname{not} E_{1}\right) \\
& =P\left(E_{1}\right) \cdot\left[1-P\left(E_{2}\right)\right]+P\left(E_{2}\right) \cdot\left[1-P\left(E_{1}\right)\right] \\
& =\frac{1}{5} \cdot\left(1-\frac{1}{6}\right)+\frac{1}{6} \cdot\left(1-\frac{1}{5}\right)=\left(\frac{1}{5} \times \frac{5}{6}\right)+\left(\frac{1}{6} \times \frac{4}{5}\right) \\
& =\left(\frac{1}{6}+\frac{2}{15}\right)=\frac{9}{30}=\frac{3}{10} .
\end{aligned}
$$

**(iii)** $P$ (none of them is selected)

$$
\begin{aligned}
& =P\left(\operatorname{not} E_{1} \text { and } \operatorname{not} E_{2}\right) \\
& =P\left(\operatorname{not} E_{1}\right) \text { and } P\left(\operatorname{not} E_{2}\right) \\
& =\left[1-P\left(E_{1}\right)\right] \cdot\left[1-P\left(E_{2}\right)\right] \\
& =\left(1-\frac{1}{5}\right) \cdot\left(1-\frac{1}{6}\right)=\left(\frac{4}{5} \times \frac{5}{6}\right)=\frac{2}{3} .
\end{aligned}
$$

---

### Example: 14

Three groups of children contain 3 girls and 1 boy; 2 girls and 2 boys; and 1 girl and 3 boys. One child is selected at random from each group. Find the chance that the three children selected comprise 1 girl and 2 boys.

#### Solution:

Let $G_{1}, G_{2}, G_{3}$ be the events of selecting a girl from the first, second and third group respectively, and let $B_{1}, B_{2}, B_{3}$ be the events of selecting a boy from the first, second and third group respectively. Then,

$$
\begin{aligned}
& P\left(G_{1}\right)=\frac{3}{4} ; P\left(G_{2}\right)=\frac{2}{4}=\frac{1}{2} ; P\left(G_{3}\right)=\frac{1}{4} . \\
& P\left(B_{1}\right)=\frac{1}{4} ; P\left(B_{2}\right)=\frac{2}{4}=\frac{1}{2} \text { and } P\left(B_{3}\right)=\frac{3}{4} .
\end{aligned}
$$

$\therefore \quad P$ (selecting 1 girl and 2 boys)

$$
\begin{aligned}
= & P\left[\left(G_{1} B_{2} B_{3}\right) \text { or }\left(B_{1} G_{2} B_{3}\right) \text { or }\left(B_{1} B_{2} G_{3}\right)\right] \\
= & P\left(G_{1} B_{2} B_{3}\right)+P\left(B_{1} G_{2} B_{3}\right)+P\left(B_{1} B_{2} G_{3}\right) \\
= & \left\{P\left(G_{1}\right) \times P\left(B_{2}\right) \times P\left(B_{3}\right)\right\}+\left\{P\left(B_{1}\right) \times P\left(G_{2}\right) \times P\left(B_{3}\right)\right\} \\
& \quad+\left\{P\left(B_{1}\right) \times P\left(B_{2}\right) \times P\left(G_{3}\right)\right\} \\
= & \left(\frac{3}{4} \times \frac{1}{2} \times \frac{3}{4}\right)+\left(\frac{1}{4} \times \frac{1}{2} \times \frac{3}{4}\right)+\left(\frac{1}{4} \times \frac{1}{2} \times \frac{1}{4}\right)=\left(\frac{9}{32}+\frac{3}{32}+\frac{1}{32}\right)=\frac{13}{32} .
\end{aligned}
$$

Hence, the chances of selecting 1 girl and 2 boys are $\frac{13}{32}$.

---

### Example: 15

A problem is given to three students whose chances of solving it are $\frac{1}{3}, 2 / 7$ and $3 / 8$. What is the probability that the problem will be solved?

#### Solution:

Let the three students be named $\mathrm{A}, \mathrm{B}$, and C respectively. Let $E_{1}, E_{2}, E_{3}$ be the events that the problem is solved by $\mathrm{A}, \mathrm{B}, \mathrm{C}$ respectively. Then,

$$
\begin{aligned}
& P\left(E_{1}\right)=\frac{1}{3}, P\left(E_{2}\right)=\frac{2}{7}, P\left(E_{3}\right)=\frac{3}{8} \\
\therefore \quad & P\left(\bar{E}_{1}\right)=\left(1-\frac{1}{3}\right)=\frac{2}{3} ; P\left(\bar{E}_{2}\right)=\left(1-\frac{2}{7}\right)=\frac{5}{7} \text { and } \\
& P\left(\bar{E}_{3}\right)=\left(1-\frac{3}{8}\right)=\frac{5}{8}
\end{aligned}
$$

$\therefore P$ (none solves the problem)

$$
\begin{aligned}
& =P\left[\left(\operatorname{not} E_{1}\right) \text { and }\left(\operatorname{not} E_{2}\right) \text { and }\left(\operatorname{not} E_{3}\right)\right] \\
& =P\left(\bar{E}_{1} \cap \bar{E}_{2} \cap \bar{E}_{3}\right) \\
& =P\left(\bar{E}_{1}\right) \times P\left(\bar{E}_{2}\right) \times P\left(\bar{E}_{3}\right) \\
& =\left(\frac{2}{3} \times \frac{5}{7} \times \frac{5}{8}\right)=\frac{25}{84}
\end{aligned}
$$

$\therefore P$ (that the problem is solved)

$$
\begin{aligned}
& =1-P(\text { none solves the problem }) \\
& =\left(1-\frac{25}{84}\right)=\frac{59}{84}
\end{aligned}
$$

Hence, the required probability is $\frac{59}{84}$.

---

### Example: 16

A problem in mathematics is given to three students whose chances of solving it correctly are $1 / 2,1 / 3$ and $1 / 4$ respectively. What is the probability that only one of them solves it correctly?
[CBSE 1999C]

#### Solution:

Let $\mathrm{A}, \mathrm{B}, \mathrm{C}$ be the given students and let $E_{1}, E_{2}$ and $E_{3}$ be the events that the problem is solved by $\mathrm{A}, \mathrm{B}, \mathrm{C}$ respectively. Then, $\bar{E}_{1}$, $\bar{E}_{2}$ and $\bar{E}_{3}$ are the events that the given problem is not solved by $\mathrm{A}, \mathrm{B}, \mathrm{C}$ respectively. Then,
$P\left(E_{1}\right)=\frac{1}{2} ; P\left(E_{2}\right)=\frac{1}{3} ; P\left(E_{3}\right)=\frac{1}{4}$;
$P\left(\bar{E}_{1}\right)=\left(1-\frac{1}{2}\right)=\frac{1}{2} ; P\left(\bar{E}_{2}\right)=\left(1-\frac{1}{3}\right)=\frac{2}{3}$ and $P\left(\bar{E}_{3}\right)=\left(1-\frac{1}{4}\right)=\frac{3}{4}$.

$P$ (exactly one of them solves the problem)

$$
\begin{aligned}
& =P\left[\left(E_{1} \cap \bar{E}_{2} \cap \bar{E}_{3}\right) \text { or }\left(\bar{E}_{1} \cap E_{2} \cap \bar{E}_{3}\right) \text { or }\left(\bar{E}_{1} \cap \bar{E}_{2} \cap E_{3}\right)\right] \\
& =P\left(E_{1} \cap \bar{E}_{2} \cap \bar{E}_{3}\right)+P\left(\bar{E}_{1} \cap E_{2} \cap \bar{E}_{3}\right)+P\left(\bar{E}_{1} \cap \bar{E}_{2} \cap E_{3}\right)
\end{aligned}
$$

$$
\begin{aligned}
& =\left\{P\left(E_{1}\right) \times P\left(\bar{E}_{2}\right) \times P\left(\bar{E}_{3}\right)\right\}+\left\{P\left(\bar{E}_{1}\right) \times P\left(E_{2}\right) \times P\left(\bar{E}_{3}\right)\right\} \\
& \quad+\left\{P\left(\bar{E}_{1}\right) \times P\left(\bar{E}_{2}\right) \times P\left(E_{3}\right)\right\} \\
& =\left(\frac{1}{2} \times \frac{2}{3} \times \frac{3}{4}\right)+\left(\frac{1}{2} \times \frac{1}{3} \times \frac{3}{4}\right)+\left(\frac{1}{2} \times \frac{2}{3} \times \frac{1}{4}\right) \\
& =\left(\frac{1}{4}+\frac{1}{8}+\frac{1}{12}\right)=\frac{11}{24} .
\end{aligned}
$$

Hence, the required probability is $\frac{11}{24}$.

---

### Example: 17

Three critics review a book. For the three critics, the odds in favour of the book are $(5: 2),(4: 3)$ and $(3: 4)$ respectively. Find the probability that the majority is in favour of the book.

#### Solution:

Let $A, B, C$ denote the events that the book be favoured by the first, second and third critic respectively. Then,
$P(A)=\frac{5}{7} ; P(B)=\frac{4}{7} ; P(C)=\frac{3}{7}$;
$P(\bar{A})=\left(1-\frac{5}{7}\right)=\frac{2}{7} ; P(\bar{B})=\left(1-\frac{4}{7}\right)=\frac{3}{7}$ and $P(\bar{C})=\left(1-\frac{3}{7}\right)=\frac{4}{7}$.

Required probability

$$
\begin{aligned}
= & P(2 \text { critics favour the book or } 3 \text { critics favour the book }) \\
= & P(2 \text { critics favour the book })+P(3 \text { critics favour the book }) \\
= & P[\{A \text { and } B \text { and not } C\} \text { or }\{A \text { and } C \text { and not } B\} \\
& \quad \text { or } \quad\{B \text { and } C \text { and } \operatorname{not} A\}]+P(A \text { and } B \text { and } C) \\
= & P(A \cap B \cap \bar{C})+P(A \cap \bar{B} \cap C)+P(\bar{A} \cap B \cap C)+P(A \cap B \cap C) \\
= & \{P(A) \times P(B) \times P(\bar{C})\}+\{P(A) \times P(\bar{B}) \times P(C)\} \\
& \quad+\{P(\bar{A}) \times P(B) \times P(C)\}+\{P(A) \times P(B) \times P(C)\} \\
= & \left(\frac{5}{7} \times \frac{4}{7} \times \frac{4}{7}\right)+\left(\frac{5}{7} \times \frac{3}{7} \times \frac{3}{7}\right)+\left(\frac{2}{7} \times \frac{4}{7} \times \frac{3}{7}\right)+\left(\frac{5}{7} \times \frac{4}{7} \times \frac{3}{7}\right) \\
= & \left(\frac{80}{343}+\frac{45}{343}+\frac{24}{343}+\frac{60}{343}\right)=\frac{209}{343}
\end{aligned}
$$

Hence, the required probability is $\frac{209}{343}$.

---

### Example: 18

The odds against a man who is 45 years old, living till he is 70 are $7: 5$, and the odds against his wife who is now 36, living till she is 61 are $5: 3$. Find the probability that
(i) the couple will be alive 25 years hence
(ii) at least one of them will be alive 25 years hence.
[CBSE 2007]

#### Solution:

Let $E_{1}=$ event that the husband will be alive 25 years hence, and
$E_{2}=$ event that the wife will be alive 25 years hence.

Then, $P\left(E_{1}\right)=\frac{5}{12}$ and $P\left(E_{2}\right)=\frac{3}{8}$.
$\therefore P\left(\bar{E}_{1}\right)=\left(1-\frac{5}{12}\right)=\frac{7}{12}$ and $P\left(\bar{E}_{2}\right)=\left(1-\frac{3}{8}\right)=\frac{5}{8}$.
Clearly, $E_{1}$ and $E_{2}$ are independent events.

**(i)** $P$ (the couple will be alive 25 years hence)

$$
\begin{aligned}
& =P\left(E_{1} \text { and } E_{2}\right)=P\left(E_{1} \cap E_{2}\right) \\
& =P\left(E_{1}\right) \cdot P\left(E_{2}\right)=\left(\frac{5}{12} \times \frac{3}{8}\right)=\frac{5}{32} .
\end{aligned}
$$

**(ii)** $P$ (at least one of them will be alive 25 years hence)

$$
\begin{aligned}
& =1-P(\text { none will be alive } 25 \text { years hence }) \\
& =1-P\left[\left(\operatorname{not} E_{1}\right) \text { and }\left(\operatorname{not} E_{2}\right)\right] \\
& =1-P\left(\bar{E}_{1} \cap \bar{E}_{2}\right) \\
& =1-\left[P\left(\bar{E}_{1}\right) \cdot P\left(\bar{E}_{2}\right)\right] \quad\left[\because \quad \bar{E}_{1} \text { and } \bar{E}_{2} \text { are independent }\right] \\
& =1-\left(\frac{7}{12} \times \frac{5}{8}\right)=\left(1-\frac{35}{96}\right)=\frac{61}{96}
\endend{aligned}
$$

---

### Example: 19

$A, B$ and $C$ shoot to hit a target. If A hits the target 4 times in 5 trials; B hits it 3 times in 4 trials and C hits it 2 times in 3 trials, what is the probability that the target is hit by at least 2 persons?

#### Solution:

Let $E_{1}, E_{2}$ and $E_{3}$ be the events that A hits the target, B hits the target and C hits the target respectively. Then,
$P\left(E_{1}\right)=\frac{4}{5}, P\left(E_{2}\right)=\frac{3}{4}, P\left(E_{3}\right)=\frac{2}{3}$;
$P\left(\bar{E}_{1}\right)=\left(1-\frac{4}{5}\right)=\frac{1}{5}, P\left(\bar{E}_{2}\right)=\left(1-\frac{3}{4}\right)=\frac{1}{4}$ and $P\left(\bar{E}_{3}\right)=\left(1-\frac{2}{3}\right)=\frac{1}{3}$.

**Case I** A, B, C all hit the target
In this case, $P(\mathrm{~A}, \mathrm{~B}$ and C all hit the target)

$$
\begin{aligned}
& =P\left(E_{1} \text { and } E_{2} \text { and } E_{3}\right) \\
& =P\left(E_{1}\right) \cdot P\left(E_{2}\right) \cdot P\left(E_{3}\right)\left[\because E_{1}, E_{2}, E_{3} \text { are independent }\right] \\
& =\left(\frac{4}{5} \times \frac{3}{4} \times \frac{2}{3}\right)=\frac{2}{5}
\end{aligned}
$$

**Case II** A and B hit but not C
In this case, $P(\mathrm{~A} \text { and } \mathrm{B} \text { hit but not } \mathrm{C})$
$=P\left(E_{1} \text { and } E_{2} \text { and not } E_{3}\right)$
$=P\left(E_{1} \cap E_{2} \cap \bar{E}_{3}\right)$

$$
\begin{aligned}
& =P\left(E_{1}\right) \cdot P\left(E_{2}\right) \cdot P\left(\bar{E}_{3}\right)\left[\because E_{1}, E_{2}, \bar{E}_{3} \text { are independent }\right] \\
& =\left(\frac{4}{5} \times \frac{3}{4} \times \frac{1}{3}\right)=\frac{1}{5}
\end{aligned}
$$

**Case III** A and C both hit but not B
In this case, $P(\mathrm{~A} \text { and } \mathrm{C} \text { hit but not } \mathrm{B})$
$=P\left(E_{1} \text { and } E_{3} \text { and } \bar{E}_{2}\right)$
$=P\left(E_{1}\right) \cdot P\left(E_{3}\right) \cdot P\left(\barE_{2}\right)\left[\because E_{1}, E_{3}, \bar{E}_{2} \text { are independent }\right]$

$$
=\left(\frac{4}{5} \times \frac{2}{3} \times \frac{1}{4}\right)=\frac{2}{15}
$$

**Case IV** B and C both hit but not A
In this case, $P(\mathrm{~B}$ and C hit but not A$)$

$$
\begin{aligned}
& =P\left(E_{2} \text { and } E_{3} \text { and } \bar{E}_{1}\right) \\
& =P\left(E_{2}\right) \cdot P\left(E_{3}\right) \cdot P\left(\bar{E}_{1}\right)\left[\because E_{2}, E_{3}, \bar{E}_{1} \text { are independent }\right] \\
& =\left(\frac{3}{4} \times \frac{2}{3} \times \frac{1}{5}\right)=\frac{1}{10}
\end{aligned}
$$

Clearly, all these are mutually exclusive.

Hence, required probability $=\left(\frac{2}{5}+\frac{1}{5}+\frac{2}{15}+\frac{1}{10}\right)=\frac{5}{6} .$

---