## Probability

Historically, the theory of **probability** began to develop with the study of games of chance such as roulette and cards. Apart from games, uncertainty also prevails in other walks of life such as business, economy, and even in day-to-day activities.

**Probability** is a concept which numerically measures the degree of uncertainty and, therefore, of certainty of the occurrence of an event.

Before defining some terms related to probability, we shall give certain concepts used therein.

An **experiment** is an operation which can produce some well-defined outcomes.

In science or engineering if we perform an experiment and repeat it under identical conditions, we get almost the same result every time. Such experiments are called **deterministic experiments**.

But, there are experiments, which when repeated under identical conditions, do not produce the same outcome every time. For example, if we toss a fair coin, we may get a head or a tail. Now, if we make further trials, i.e., toss the coin again and again, the outcome of each trial depends on chance, and it is not the same each time. Sometimes the head appears and sometimes, the tail. Such experiments are called **random experiments**.

A **random experiment** is an experiment where, in each trial conducted under identical conditions, the outcome is not unique, but may be any of the several possible outcomes.

In a random experiment, the outcome of each trial depends on chance, which is beyond our control, and as such it cannot be predicted with certainty.

**Examples:** Tossing a fair coin, rolling an unbiased die, drawing a card from a well-shuffled pack of cards are all examples of random experiments.

**NOTE 1:** A **die** is a solid cube, the six faces of which are marked with $1, 2, 3, 4, 5$ and $6$ dots respectively. In throwing a die, the outcome is the number of dots on the uppermost face. The plural of die is **dice**.

**NOTE 2:** A **pack of cards** consists of 52 cards in four suits, called spades, clubs, hearts and diamonds. Out of these, spades and clubs are black-faced cards, while hearts and diamonds are red-faced cards. The aces, kings, queens and jacks are known as **face cards**.

The **sample space** is the set of all possible outcomes in a random experiment and it is generally denoted by $S$. Each element of a sample space is called a **sample point**.

---

## Examples of Sample Spaces

### Example 1:

List the sample space in tossing a fair coin.

#### Solution:

In tossing a fair coin, there are two possible outcomes, namely, head ($H$) and tail ($T$). Hence, the sample space in this experiment is given by

$$
S = \{H, T\}
$$

---

### Example 2:

List the sample space in throwing a die.

#### Solution:

When we throw a die, it can result in any of the six numbers, namely, $1, 2, 3, 4, 5, 6$. Therefore, the sample space is

$$
S = \{1, 2, 3, 4, 5, 6\}
$$

---

### Example 3:

Two coins are tossed together. List the sample space.

#### Solution:

When two coins are tossed together, the sample space is

$$
S = \{HT, TH, HH, TT\}
$$

Here, $HT$ shows a head on the first coin and a tail on the second. Similarly, $TH$ means a tail on the first and a head on the second; $HH$ means a head on each, and $TT$ means a tail on each.

---

### Example 4:

Three coins are tossed simultaneously. List the sample space for the event. [CBSE 1999]

#### Solution:

When three coins are tossed simultaneously, the sample space is given by

$$
S = \{HHH, HHT, HTH, THH, HTT, TTH, THT, TTT\}
$$

---

### Example 5:

List the sample space in a simultaneous toss of a die and a coin.

#### Solution:

Clearly, the sample space is given by

$$
S = \{(1, H), (2, H), (3, H), (4, H), (5, H), (6, H), (1, T), (2, T), (3, T), (4, T), (5, T), (6, T)\}
$$

---

### Example 6:

Two well-balanced dice are rolled and the numbers that turn up are observed. Determine the sample space. [CBSE 1999]

#### Solution:

When two dice are rolled, there are $(6 \times 6) = 36$ outcomes. The set of all these outcomes is the sample space, given by

$$
\begin{aligned}
S = \{ &(1,1), (2,1), (3,1), (4,1), (5,1), (6,1), \\
& (1,2), (2,2), (3,2), (4,2), (5,2), (6,2), \\
& (1,3), (2,3), (3,3), (4,3), (5,3), (6,3), \\
& (1,4), (2,4), (3,4), (4,4), (5,4), (6,4), \\
& (1,5), (2,5), (3,5), (4,5), (5,5), (6,5), \\
& (1,6), (2,6), (3,6), (4,6), (5,6), (6,6) \}
\end{aligned}
$$

---

### Example 7:

From a group of 3 boys and 2 girls, we select two children. What would be the sample space for this experiment?

#### Solution:

Let us name the boys as $B_1, B_2$ and $B_3$, and the girls as $G_1$ and $G_2$. Then the sample space is given by

$$
S = \{B_1 B_2, B_1 B_3, B_1 G_1, B_1 G_2, B_2 B_3, B_2 G_1, B_2 G_2, B_3 G_1, B_3 G_2, G_1 G_2\}
$$

---

### Example 8:

A coin is tossed twice. If the second throw results in a tail then a die is thrown. Describe the sample space.

#### Solution:

Clearly, the sample space is given by

$$
S = \{HH, TH, HT1, HT2, HT3, HT4, HT5, HT6, TT1, TT2, TT3, TT4, TT5, TT6\}
$$

---

### Example 9:

A coin is tossed. If it shows a tail, we draw a ball from a box which contains 2 red and 3 black balls; if it shows a head, we throw a die. Find the sample space for this experiment.

#### Solution:

Let the red balls be named as $R_1$ and $R_2$, and the black balls be named as $B_1, B_2$ and $B_3$. Then, the sample space is given by

$$
S = \{TR_1, TR_2, TB_1, TB_2, TB_3, H1, H2, H3, H4, H5, H6\}
$$

---

### Example 10:

An experiment consists of rolling a die and then tossing a coin once if the number on the die is even. If the number on the die is odd, the coin is tossed twice. Write the sample space for this experiment.

#### Solution:

Clearly, the sample space is given by

$$
\begin{aligned}
S = \{ &2H, 2T, 4H, 4T, 6H, 6T, 1HH, 1HT, 1TH, 1TT, 3HH, 3HT, \\
& 3TH, 3TT, 5HH, 5HT, 5TH, 5TT\}
\end{aligned}
$$

---

### Example 11:

A bag contains 4 identical red balls and 3 identical black balls. The experiment consists of drawing one ball, then putting it into the bag and again drawing a ball. What are the possible outcomes of this experiment?

#### Solution:

Let us denote a red ball by $R$ and a black ball by $B$. Then, clearly the sample space is given by

$$
S = \{RR, RB, BR, BB\}
$$

---

An **event** is every subset of a sample space.

**Example:** In a single throw of a die, we have the sample space $S = \{1, 2, 3, 4, 5, 6\}$. The event of getting a prime number is given by $E = \{2, 3, 5\}$. Clearly, $E \subseteq S$.

An **impossible event** is an event which is the empty set, $\phi$. Let $S$ be a sample space. Since $\phi \subset S$, $\phi$ is an event, called an impossible event.

A **sure event** is an event which is the sample space, $S$, itself. Let $S$ be a sample space. Since $S \subseteq S$, $S$ is an event, called a sure event.

**Example:** In a throw of a die, we have sample space $S = \{1, 2, 3, 4, 5, 6\}$.
Let $E_1$ = event of getting a number less than 1.
And, $E_2$ = event of getting a number less than 7.
Clearly, no outcome can be less than 1. Therefore, $E_1$ is an impossible event.
Also, each outcome is a number less than 7. Therefore, $E_2$ is a sure event.

A **simple event** (or an elementary event) is an event containing only a single element of the sample space.

A **compound event** (or composite or mixed event) is an event which is not simple.

**Example:** In a simultaneous toss of two coins, we have sample space $S = \{HH, HT, TH, TT\}$.
Then $E_1$ = event of getting a tail on both the coins = $\{TT\}$, is a simple event.
And, $E_2$ = event of getting at least 1 tail = $\{HT, TH, TT\}$, is a compound event.

**Mutually exclusive events** are two events $E_1$ and $E_2$ such that $E_1 \cap E_2 = \phi$. However, if $E_1 \cap E_2 \neq \phi$ then $E_1$ and $E_2$ are called **compatible events**.

**Examples:**
- (i) In throwing a die, we have $S = \{1, 2, 3, 4, 5, 6\}$. Let $E_1$ = event of getting a number less than 3, and, $E_2$ = event of getting a number more than 4. Then $E_1 = \{1, 2\}$ and $E_2 = \{5, 6\}$. Clearly, $E_1 \cap E_2 = \phi$. Hence, $E_1$ and $E_2$ are mutually exclusive.
- (ii) In a simultaneous toss of two coins, we have $S = \{HH, HT, TH, TT\}$. Let $E_1$ = event of getting a head on the first coin = $\{HH, HT\}$, and, $E_2$ = event of getting a tail on the second coin = $\{HT, TT\}$. Clearly, $E_1 \cap E_2 \neq \phi$. Hence, $E_1$ and $E_2$ are compatible events.

---

### Example 1:

Two dice are rolled. Let $A, B, C$ be the events of getting a sum of 2, a sum of 3 and a sum of 4 respectively. Then, show that
(i) $A$ is a simple event
(ii) $B$ and $C$ are compound events
(iii) $A$ and $B$ are mutually exclusive

#### Solution:

Clearly, we have

$$
A = \{(1,1)\}, B = \{(1,2), (2,1)\}, \text{ and } C = \{(1,3), (3,1), (2,2)\}
$$

(i) Since $A$ consists of a single sample point, it is a simple event.
(ii) Since both $B$ and $C$ contain more than one sample point, each one of them is a compound event.
(iii) Since $A \cap B = \phi$, $A$ and $B$ are mutually exclusive.

---

### Example 2:

From a group of 2 boys and 3 girls, two children are selected at random. Describe the events:
(i) $A$ = event that both the selected children are girls
(ii) $B$ = event that the selected group consists of one boy and one girl
(iii) $C$ = event that at least one boy is selected

Which pairs of events are mutually exclusive?

#### Solution:

Let us name the boys as $B_1$ and $B_2$, and the girls as $G_1, G_2$ and $G_3$. Then

$$
S = \{B_1 B_2, B_1 G_1, B_1 G_2, B_1 G_3, B_2 G_1, B_2 G_2, B_2 G_3, G_1 G_2, G_1 G_3, G_2 G_3\}
$$

We have
(i) $A = \{G_1 G_2, G_1 G_3, G_2 G_3\}$
(ii) $B = \{B_1 G_1, B_1 G_2, B_1 G_3, B_2 G_1, B_2 G_2, B_2 G_3\}$
(iii) $C = \{B_1 G_1, B_1 G_2, B_1 G_3, B_2 G_1, B_2 G_2, B_2 G_3, B_1 B_2\}$

Clearly, $A \cap B = \phi$ and $A \cap C = \phi$. Hence, $(A, B)$ and $(A, C)$ are mutually exclusive events.

---

A **mutually exclusive and exhaustive system of events** is a set of events $E_1, E_2, \ldots, E_n$ that are subsets of a sample space $S$ such that (i) $E_i \cap E_j = \phi$ for $i \neq j$, and (ii) $E_1 \cup E_2 \cup \ldots \cup E_n = S$.

**Example:** Suppose we draw a card from a well-shuffled pack of 52 cards. Let $E_1, E_2, E_3$ and $E_4$ be the events of drawing a spade, drawing a club, drawing a heart and drawing a diamond respectively. As the card drawn is necessarily one of the four types, one of these events is sure to occur. When one of these events occurs then none of the others occur. Thus, $E_1, E_2, E_3, E_4$ form a mutually exclusive and exhaustive system of events.

---

### Example:

Two dice are rolled. $A$ is the event that the sum of the numbers shown on the two dice is 5, and $B$ is the event that at least one of the dice shows up a 3. Are the two events (i) mutually exclusive, (ii) exhaustive? Give arguments in support of your answer. [CBSE 2001C]

#### Solution:

When two dice are rolled, we have $n(S) = (6 \times 6) = 36$.
Now, $A = \{(1,4), (2,3), (4,1), (3,2)\}$, and $B = \{(3,1), (3,2), (3,3), (3,4), (3,5), (3,6), (1,3), (2,3), (4,3), (5,3), (6,3)\}$.
(i) $A \cap B = \{(2,3), (3,2)\} \neq \phi$. Hence, $A$ and $B$ are **not** mutually exclusive.
(ii) Also, $A \cup B \neq S$. Therefore, $A$ and $B$ are **not** exhaustive events.

---

**Independent events** are two events $E_1$ and $E_2$ where the occurrence of one does not depend upon the occurrence of the other. If the two events are not independent, they are known as **dependent events**.

**Example:** Suppose we toss two unbiased coins. Let $E_1$ = event of getting a head on the first coin, and, $E_2$ = event of getting a head on the second coin. Clearly, the occurrence of a head on the second coin does not depend upon the occurrence of a head on the first coin. Therefore, $E_1$ and $E_2$ are independent events.

**Occurrence of an event:** In a random experiment, let $S$ be the sample space and let $E \subseteq S$. Then, $E$ is an event. Let $w$ be an outcome of a trial. If $w \in E$, we say that the event E has occurred. If $w \notin E$, we say that the event $E$ has not occurred.

**Example:** In a throw of a die, we have $S = \{1, 2, 3, 4, 5, 6\}$. Let $E$ be the event of getting an even number. Then $E = \{2, 4, 6\}$. In a trial, let the outcome be 4. Since $4 \in E$, we say that the event $E$ has occurred. In another trial, let the outcome be 5. Since $5 \notin E$, in this case, the event $E$ has not occurred.

**Equally likely events** are a given number of events where none of them is expected to occur in preference to the others.

**Example:** If we roll an unbiased die, each outcome is equally likely to happen. If, however, a die is so formed that a particular face occurs most often then the die is biased. In this case, the outcomes are not equally likely to happen.

**Complementary events:** In a random experiment, let $S$ be the sample space and let $E$ be an event. Then $E \subseteq S$. Now, $E \subseteq S \Rightarrow E^c \subseteq S$. Thus, $E^c$ is also an event, called the complement of $E$. We denote it by $E^c$ or $E'$ or $\bar{E}$ and call it **not E**. Clearly, $\bar{E}$ occurs when $E$ does not occur. And, E occurs when $\bar{E}$ does not occur. Thus, in a trial, one of two events, $E$ or $\bar{E}$, is sure to occur.

**Algebra of events:** In a random experiment, let $S$ be the sample space. Let $E \subseteq S$ and $F \subseteq S$. Then, $E$ as well as $F$ is an event. We say that:
- ($E \cap F$) is an event that occurs only when each one of $E$ and $F$ occurs.
- ($E \cup F$) is an event that occurs only when at least one of $E$ and $F$ occurs.
- $\bar{E}$ is an event that occurs only when $E$ does not occur.

---

## Probability of an Event

**Introduction:** Suppose a bag contains 90 red and 10 white balls, which are similar in shape and size. If the balls are mixed thoroughly and then one ball is drawn at random, it will be either red or white. Clearly, the ball drawn is more likely to be red than white. We express it by saying that the event of drawing a red ball is more probable than the event of drawing a white ball.

To every event associated with a random experiment, we try to attach a numerical value, called its **probability**, in such a manner that for any two events, the event which is more likely to happen has a higher probability.

**Probability of an event:** In a random experiment, let $S$ be the sample space and let $E \subseteq S$. Then, $E$ is an event. The probability of occurrence of $E$ is defined as

$$
P(E) = \frac{\text{number of outcomes favourable to occurrence of } E}{\text{number of all possible outcomes}}
$$

$$
P(E) = \frac{\text{number of distinct elements in } E}{\text{number of distinct elements in } S}
$$

$$
P(E) = \frac{n(E)}{n(S)}
$$

---

## Solved Examples

### Example 1:

A coin is tossed once. Find the probability of getting a head.

#### Solution:

When a coin is tossed once, the sample space is given by $S = \{H, T\}$. Let $E$ be the event of getting a head. Then, $E = \{H\}$.
Therefore, $n(E) = 1$ and $n(S) = 2$.
This implies $P(\text{getting a head}) = P(E) = \frac{n(E)}{n(S)} = \frac{1}{2}$.

---

### Example 2:

Two coins are tossed once. Find the probability of
(i) getting 2 heads
(ii) getting at least 1 head
(iii) getting no head
(iv) getting 1 head and 1 tail

#### Solution:

When two coins are tossed once, the sample space is given by $S = \{HH, HT, TH, TT\}$ and, therefore, $n(S) = 4$.
(i) Let $E_1$ = event of getting 2 heads. Then, $E_1 = \{HH\}$ and, therefore, $n(E_1) = 1$.
$P(\text{getting 2 heads}) = P(E_1) = \frac{n(E_1)}{n(S)} = \frac{1}{4}$.
(ii) Let $E_2$ = event of getting at least 1 head. Then, $E_2 = \{HT, TH, HH\}$ and, therefore, $n(E_2) = 3$.
$P(\text{getting at least 1 head}) = P(E_2) = \frac{n(E_2)}{n(S)} = \frac{3}{4}$.
(iii) Let $E_3$ = event of getting no head. Then, $E_3 = \{TT\}$ and, therefore, $n(E_3) = 1$.
$P(\text{getting no head}) = P(E_3) = \frac{n(E_3)}{n(S)} = \frac{1}{4}$.
(iv) Let $E_4$ = event of getting 1 head and 1 tail. Then, $E_4 = \{HT, TH\}$ and, therefore, $n(E_4) = 2$.
$P(\text{getting 1 head and 1 tail}) = P(E_4) = \frac{n(E_4)}{n(S)} = \frac{2}{4} = \frac{1}{2}$.

---

### Example 3:

Three unbiased coins are tossed once. What is the probability of getting
(i) all heads?
(ii) two heads?
(iii) one head?
(iv) at least 1 head?
(v) at least 2 heads?

#### Solution:

In tossing three coins, the sample space is given by

$$
S = \{HHH, HHT, HTH, THH, HTT, THT, TTH, TTT\}
$$

And, therefore, $n(S) = 8$.
(i) Let $E_1$ = event of getting all heads. Then, $E_1 = \{HHH\}$ and, therefore, $n(E_1) = 1$.
$P(\text{getting all heads}) = P(E_1) = \frac{n(E_1)}{n(S)} = \frac{1}{8}$.
(ii) Let $E_2$ = event of getting 2 heads. Then, $E_2 = \{HHT, HTH, THH\}$ and, therefore, $n(E_2) = 3$.
$P(\text{getting 2 heads}) = P(E_2) = \frac{n(E_2)}{n(S)} = \frac{3}{8}$.
(iii) Let $E_3$ = event of getting 1 head. Then, $E_3 = \{HTT, THT, TTH\}$ and, therefore, $n(E_3) = 3$.
$P(\text{getting 1 head}) = P(E_3) = \frac{n(E_3)}{n(S)} = \frac{3}{8}$.
(iv) Let $E_4$ = event of getting at least 1 head. Then, $E_4 = \{HTT, THT, TTH, HHT, HTH, THH, HHH\}$. And, therefore, $n(E_4) = 7$.
$P(\text{getting at least 1 head}) = P(E_4) = \frac{n(E_4)}{n(S)} = \frac{7}{8}$.
(v) Let $E_5$ = event of getting at least 2 heads. Then, $E_5 = \{HHT, HTH, THH, HHH\}$ and, therefore, $n(E_5) = 4$.
$P(\text{getting at least 2 heads}) = P(E_5) = \frac{n(E_5)}{n(S)} = \frac{4}{8} = \frac{1}{2}$.

---

### Example 4:

A die is tossed once. What is the probability of getting
(i) the number 4?
(ii) an even number?
(iii) a number less than 5?
(iv) a number greater than 4?
(v) the number 8?
(vi) a number less than 8?

#### Solution:

In tossing a die once, the sample space is given by $S = \{1, 2, 3, 4, 5, 6\}$ and, therefore, $n(S) = 6$.
(i) Let $E_1$ = event of getting the number 4. Then, $E_1 = \{4\}$ and, therefore, $n(E_1) = 1$.
$P(\text{getting the number 4}) = P(E_1) = \frac{n(E_1)}{n(S)} = \frac{1}{6}$.
(ii) Let $E_2$ = event of getting an even number. Then, $E_2 = \{2, 4, 6\}$ and, therefore, $n(E_2) = 3$.
$P(\text{getting an even number}) = P(E_2) = \frac{n(E_2)}{n(S)} = \frac{3}{6} = \frac{1}{2}$.
(iii) Let $E_3$ = event of getting a number less than 5. Then, $E_3 = \{1, 2, 3, 4\}$ and, therefore, $n(E_3) = 4$.
$P(\text{getting a number less than 5}) = P(E_3) = \frac{n(E_3)}{n(S)} = \frac{4}{6} = \frac{2}{3}$.
(iv) Let $E_4$ = event of getting a number greater than 4. Then, $E_4 = \{5, 6\}$ and, therefore, $n(E_4) = 2$.
$P(\text{getting a number greater than 4}) = P(E_4) = \frac{n(E_4)}{n(S)} = \frac{2}{6} = \frac{1}{3}$.
(v) Let $E_5$ = event of getting the number 8. Since no face of the die is marked with the number 8, we have $E_5 = \phi$ and, therefore, $n(E_5) = 0$.
$P(\text{getting the number 8}) = P(E_5) = \frac{n(E_5)}{n(S)} = \frac{0}{6} = 0$.
(vi) Let $E_6$ = event of getting a number less than 8. Then, $E_6 = \{1, 2, 3, 4, 5, 6\}$ and, therefore, $n(E_6) = 6$.
$P(\text{getting a number less than 8}) = P(E_6) = \frac{n(E_6)}{n(S)} = \frac{6}{6} = 1$.

---

### Example 5:

In a single throw of two dice, find the probability of obtaining 'a total of 8'.

#### Solution:

We know that in a single throw of two dice, the total number of possible outcomes is $(6 \times 6) = 36$.
Let $S$ be the sample space. Then, $n(S) = 36$.
Let $E$ = event of getting a total of 8. Then, $E = \{(2, 6), (3, 5), (4, 4), (5, 3), (6, 2)\}$ and, therefore, $n(E) = 5$.
$P(\text{getting a total of 8}) = P(E) = \frac{n(E)}{n(S)} = \frac{5}{36}$.

---

### Example 6:

Two dice are thrown simultaneously. Find the probability of getting
(i) a doublet
(ii) an even number as the sum
(iii) a prime number as the sum
(iv) a multiple of 3 as the sum
(v) a total of at least 10
(vi) a doublet of even numbers
(vii) a multiple of 2 on one die and a multiple of 3 on the other die

#### Solution:

We know that in a single throw of two dice, the total number of possible outcomes is $(6 \times 6) = 36$. Let $S$ be the sample space. Then, $n(S) = 36$.
(i) Let $E_1$ = event of getting a doublet. Then, $E_1 = \{(1,1), (2,2), (3,3), (4,4), (5,5), (6,6)\}$. So, $n(E_1) = 6$.
$P(E_1) = \frac{n(E_1)}{n(S)} = \frac{6}{36} = \frac{1}{6}$.
(ii) Let $E_2$ = event of getting an even number as the sum. Then, $E_2 = \{(1,1), (1,3), (1,5), (2,2), (2,4), (2,6), (3,1), (3,3), (3,5), (4,2), (4,4), (4,6), (5,1), (5,3), (5,5), (6,2), (6,4), (6,6)\}$. So, $n(E_2) = 18$.
$P(E_2) = \frac{n(E_2)}{n(S)} = \frac{18}{36} = \frac{1}{2}$.
(iii) Let $E_3$ = event of getting a prime number as the sum. Then, $E_3 = \{(1,1), (1,2), (1,4), (1,6), (2,1), (2,3), (2,5), (3,2), (3,4), (4,1), (4,3), (5,2), (5,6), (6,1), (6,5)\}$. So, $n(E_3) = 15$.
$P(E_3) = \frac{n(E_3)}{n(S)} = \frac{15}{36} = \frac{5}{12}$.
(iv) Let $E_4$ = event of getting a multiple of 3 as the sum. Then, $E_4 = \{(1,2), (1,5), (2,1), (2,4), (3,3), (3,6), (4,2), (4,5), (5,1), (5,4), (6,3), (6,6)\}$. So, $n(E_4) = 12$.
$P(E_4) = \frac{n(E_4)}{n(S)} = \frac{12}{36} = \frac{1}{3}$.
(v) Let $E_5$ = event of getting a total of at least 10. Then, $E_5$ = event of getting a total of 10, 11 or 12 = $\{(4,6), (5,5), (5,6), (6,4), (6,5), (6,6)\}$. So, $n(E_5) = 6$.
$P(E_5) = \frac{n(E_5)}{n(S)} = \frac{6}{36} = \frac{1}{6}$.
(vi) Let $E_6$ = event of getting a doublet of even numbers. Then, $E_6 = \{(2,2), (4,4), (6,6)\}$. So, $n(E_6) = 3$.
$P(E_6) = \frac{n(E_6)}{n(S)} = \frac{3}{36} = \frac{1}{12}$.
(vii) Let $E_7$ = event of getting a multiple of 2 on one die and a multiple of 3 on the other die. Then, $E_7 = \{(2,3), (2,6), (4,3), (4,6), (6,3), (6,6), (3,2), (3,4), (3,6), (6,2), (6,4)\}$. So, $n(E_7) = 11$.
$P(E_7) = \frac{n(E_7)}{n(S)} = \frac{11}{36}$.

---

### Example 7:

20 cards are numbered from 1 to 20. One card is then drawn at random. What is the probability that the number on the card drawn is
(i) a prime number?
(ii) an odd number?
(iii) a multiple of 5?
(iv) not divisible by 3?

#### Solution:

Clearly, the sample space is given by $S = \{1, 2, 3, 4, 5, \ldots, 19, 20\}$ and, therefore, $n(S) = 20$.
(i) Let $E_1$ = event of getting a prime number. Then, $E_1 = \{2, 3, 5, 7, 11, 13, 17, 19\}$ and, therefore, $n(E_1) = 8$.
$P(\text{getting a prime number}) = P(E_1) = \frac{n(E_1)}{n(S)} = \frac{8}{20} = \frac{2}{5}$.
(ii) Let $E_2$ = event of getting an odd number. Then, $E_2 = \{1, 3, 5, 7, 9, 11, 13, 15, 17, 19\}$ and, therefore, $n(E_2) = 10$.
$P(\text{getting an odd number}) = P(E_2) = \frac{n(E_2)}{n(S)} = \frac{10}{20} = \frac{1}{2}$.
(iii) Let $E_3$ = event of getting a multiple of 5. Then, $E_3 = \{5, 10, 15, 20\}$ and, therefore, $n(E_3) = 4$.
$P(\text{getting a multiple of 5}) = P(E_3) = \frac{n(E_3)}{n(S)} = \frac{4}{20} = \frac{1}{5}$.
(iv) Let $E_4$ = event of getting a number which is not divisible by 3. Then, $E_4 = \{1, 2, 4, 5, 7, 8, 10, 11, 13, 14, 16, 17, 19, 20\}$ and so, $n(E_4) = 14$.
$P(\text{getting a number which is not divisible by 3}) = P(E_4) = \frac{n(E_4)}{n(S)} = \frac{14}{20} = \frac{7}{10}$.

---

### Example 8:

From a well-shuffled deck of 52 cards, a card is drawn at random. Find the probability of getting
(i) an ace
(ii) a heart
(iii) an eight of hearts
(iv) a club
(v) a red card
(vi) a face card
(vii) a diamond
(viii) a jack
(ix) a black card

#### Solution:

Let $S$ denote the sample space. Then, $n(S) = 52$.
(i) Let $E_1$ = event of drawing an ace. Since, the number of all aces is 4, so $n(E_1) = 4$.
$P(\text{getting an ace}) = P(E_1) = \frac{n(E_1)}{n(S)} = \frac{4}{52} = \frac{1}{13}$.
(ii) Let $E_2$ = event of getting a heart. Then, $n(E_2) = 13$.
$P(\text{getting a heart}) = P(E_2) = \frac{n(E_2)}{n(S)} = \frac{13}{52} = \frac{1}{4}$.
(iii) Let $E_3$ = event of getting an eight of hearts. Then, $n(E_3) = 1$.
$P(\text{getting an eight of hearts}) = P(E_3) = \frac{n(E_3)}{n(S)} = \frac{1}{52}$.
(iv) Let $E_4$ = event of getting a club. Then, $n(E_4) = 13$.
$P(\text{getting a club}) = P(E_4) = \frac{n(E_4)}{n(S)} = \frac{13}{52} = \frac{1}{4}$.
(v) Let $E_5$ = event of getting a red card. Then, $n(E_5) = 26$.
$P(\text{getting a red card}) = P(E_5) = \frac{n(E_5)}{n(S)} = \frac{26}{52} = \frac{1}{2}$.
(vi) Let $E_6$ = event of getting a face card. Then, $n(E_6) = 16$.
$P(\text{getting a face card}) = P(E_6) = \frac{n(E_6)}{n(S)} = \frac{16}{52} = \frac{4}{13}$.
(vii) Let $E_7$ = event of getting a diamond. Then, $n(E_7) = 13$.
$P(\text{getting a diamond}) = P(E_7) = \frac{n(E_7)}{n(S)} = \frac{13}{52} = \frac{1}{4}$.
(viii) Let $E_8$ = event of getting a jack. Then, $n(E_8) = 4$.
$P(\text{getting a jack}) = P(E_8) = \frac{n(E_8)}{n(S)} = \frac{4}{52} = \frac{1}{13}$.
(ix) Let $E_9$ = event of getting a black card. Then, $n(E_9) = 26$.
$P(\text{getting a black card}) = P(E_9) = \frac{n(E_9)}{n(S)} = \frac{26}{52} = \frac{1}{2}$.

---

### Example 9:

From a well-shuffled deck of 52 cards, a card is drawn at random. Find the probability that the card drawn is
(i) red and a king
(ii) either red or a king

#### Solution:

Let $S$ denote the sample space. Then, $n(S) = 52$.
(i) Let $E_1$ = event of drawing a red card which is a king. We know that the number of red kings is 2. So, $n(E_1) = 2$.
$P(\text{getting a red king}) = P(E_1) = \frac{n(E_1)}{n(S)} = \frac{2}{52} = \frac{1}{26}$.
(ii) Let $E_2$ = event of drawing a card which is either red or a king. There are 26 red cards (including 2 red kings) and there are 2 more kings.
Therefore, $n(E_2) = (26 + 2) = 28$.
$P(\text{getting a red card or a king}) = P(E_2) = \frac{n(E_2)}{n(S)} = \frac{28}{52} = \frac{7}{13}$.

---

### Example 10:

A bag contains 9 red and 12 white balls. One ball is drawn at random. Find the probability that the ball drawn is red.

#### Solution:

Total number of balls = $(9 + 12) = 21$.
Let $S$ be the sample space. Then, $n(S)$ = number of ways of selecting 1 ball out of $21 = 21$.
Let $E$ be the event of drawing a red ball. Then, $n(E)$ = number of ways of selecting 1 red ball out of $9 = 9$.
$P(\text{getting a red ball}) = P(E) = \frac{n(E)}{n(S)} = \frac{9}{21} = \frac{3}{7}$.

---

**Odds of an event:** Let there be $m$ outcomes favourable to an event $E$ and $n$ outcomes unfavourable to E. Then,
(i) **odds in favour** of $E = \frac{m}{n}$ or $(m:n)$
(ii) **odds against** $E = \frac{n}{m}$ or $(n:m)$
(iii) $P(E) = \frac{m}{(m+n)}$

---

### Example 11:

The odds in favour of occurrence of an event are 5:12. Find the probability of the occurrence of this event.

#### Solution:

Number of favourable outcomes = 5.
Number of unfavourable outcomes = 12.
Total number of outcomes = $(5 + 12) = 17$.
Let $E$ be the event. Then,

$$
P(E) = \frac{\text{number of favourable outcomes}}{\text{total number of outcomes}} = \frac{5}{17}
$$

---

### Example 12:

If the probability of the occurrence of a certain event $E$ is $3/11$, find (i) the odds in favour of its occurrence, and (ii) the odds against its occurrence.

#### Solution:

Let there be $m$ outcomes favourable to $E$ and $n$ outcomes unfavourable to $E$. Then,
$P(E) = \frac{m}{m+n} \Rightarrow \frac{m}{m+n} = \frac{3}{11}$ [since $P(E) = \frac{3}{11}$ (given)]
This implies $m = 3$ and $n = 8$.

(i) odds in favour of $E = \frac{m}{n} = \frac{3}{8}$.
(ii) odds against $E = \frac{n}{m} = \frac{8}{3}$.

---

## Probability of Occurrence of a Complementary Event

**Theorem 1:** Let $E$ be an event and $\bar{E}$ be the complement of $E$. Then, $P(\bar{E}) = 1 - P(E)$.

**Proof:** Let there be $m$ outcomes favourable to $E$ and $n$ outcomes unfavourable to $E$. Then, the number of possible outcomes = $(m+n)$.
Therefore, $P(E) = \frac{m}{(m+n)}$ and $P(\bar{E}) = P(\text{not } E) = \frac{n}{(m+n)}$.
This implies $P(E) + P(\bar{E}) = \left(\frac{m}{m+n} + \frac{n}{m+n}\right) = \frac{(m+n)}{(m+n)} = 1$.
This implies $P(\bar{E}) = 1 - P(E)$.
Hence, $P(\bar{E}) = 1 - P(E)$.

**NOTE:** There is an alternative proof of this theorem, which we will soon discuss.

---

### Example 13:

If $\frac{3}{10}$ is the probability that an event will happen, what is the probability that it will not happen?

#### Solution:

Let $E$ be the event. Then,
$P(E) = \frac{3}{10} \Rightarrow P(\bar{E}) = \{1 - P(E)\} = \left(1 - \frac{3}{10}\right) = \frac{7}{10}$.
Hence, $P(\text{not } E) = \frac{7}{10}$.

---

### Example 14:

Three dice are thrown together. Find the probability of getting a total of at least 6.

#### Solution:

In throwing 3 dice together, the number of all possible outcomes is $(6 \times 6 \times 6) = 216$.
Let $E$ = event of getting a total of at least 6.
Then, $\bar{E}$ = event of getting a total of less than 6 = event of getting a total of 3, 4, or 5.
$$
\bar{E} = \{(1,1,1), (1,1,2), (1,2,1), (2,1,1), (1,1,3), (1,3,1), (3,1,1), (1,2,2), (2,1,2), (2,2,1)\}
$$
Now, $n(\bar{E}) = 10 \Rightarrow P(\text{not } E) = P(\bar{E}) = \frac{n(\bar{E})}{n(S)} = \frac{10}{216} = \frac{5}{108}$.
This implies $P(E) = 1 - P(\text{not } E) = \left(1 - \frac{5}{108}\right) = \frac{103}{108}$.
Hence, the required probability is $\frac{103}{108}$.

---

**Theorem 2:** For an event $E$,
(i) odds in favour of $E = \frac{P(E)}{1 - P(E)}$
(ii) odds against $E = \frac{1 - P(E)}{P(E)}$

**Proof:** Let there be $m$ outcomes favourable to $E$ and $n$ outcomes unfavourable to $E$. Then, there are $m$ outcomes favourable to $E$ and $n$ outcomes favourable to $\bar{E}$.
Therefore, $P(E) = \frac{n(E)}{n(S)} = \frac{m}{(m+n)}$ and $P(\bar{E}) = \frac{n}{(m+n)}$.
(i) Odds in favour of $E = \frac{m}{n} = \frac{\frac{m}{(m+n)}}{\frac{n}{(m+n)}} = \frac{P(E)}{P(\bar{E})} = \frac{P(E)}{1 - P(E)}$.
(ii) Odds against $E = \frac{n}{m} = \frac{1 - P(E)}{P(E)}$.

---

### Example 15:

If the odds in favour of an event be $\frac{3}{5}$, find the probability of the occurrence of the event.

#### Solution:

Let the given event be $E$ and let $P(E) = x$. Then, odds in favour of $E = \frac{P(E)}{1 - P(E)}$.
$\Leftrightarrow \frac{P(E)}{1 - P(E)} = \frac{3}{5} \Leftrightarrow \frac{x}{(1-x)} = \frac{3}{5}$
$\Leftrightarrow 5x = 3 - 3x \Leftrightarrow 8x = 3 \Leftrightarrow x = \frac{3}{8}$
Therefore, required probability = $\frac{3}{8}$.

---

### Example 16:

Two dice are thrown. Find (i) the odds in favour of getting the sum 5, and (ii) the odds against getting the sum 6.

#### Solution:

Let $S$ be the sample space. Then, $n(S) = 36$.
(i) Let $E_1$ be the event of getting the sum 5. Then, $E_1 = \{(1,4), (2,3), (3,2), (4,1)\} \Rightarrow n(E_1) = 4$.
$P(E_1) = \frac{n(E_1)}{n(S)} = \frac{4}{36} = \frac{1}{9}$.
Odds in favour of $E_1 = \frac{P(E_1)}{1 - P(E_1)} = \frac{(1/9)}{(1 - 1/9)} = \frac{1}{8}$.
(ii) Let $E_2$ be the event of getting the sum 6. Then, $E_2 = \{(1,5), (2,4), (3,3), (4,2), (5,1)\} \Rightarrow n(E_2) = 5$.
$P(E_2) = \frac{n(E_2)}{n(S)} = \frac{5}{36}$.
Odds against $E_2 = \frac{1 - P(E_2)}{P(E_2)} = \frac{(1 - \frac{5}{36})}{(5/36)} = \frac{31}{5}$.

---

### Example 17:

A card is drawn from a well-shuffled deck of 52 cards. Find (i) the odds in favour of getting a face card, and (ii) the odds against getting a spade.

#### Solution:

When a card is drawn from a well-shuffled deck of 52 cards, the number of possible outcomes is 52. Now, let $S$ be the sample space. Then, $n(S) = 52$.
(i) Let $E_1$ be the event of getting a face card. Since there are 16 face cards, we have $n(E_1) = 16$.
$P(E_1) = \frac{n(E_1)}{n(S)} = \frac{16}{52} = \frac{4}{13}$.
Odds in favour of getting a face card = $\frac{P(E_1)}{\{1 - P(E_1)\}} = \frac{(4/13)}{(1 - \frac{4}{13})} = \frac{4}{9}$.
(ii) Let $E_2$ be the event of getting a spade. Then, $n(E_2) = 13$.
$P(E_2) = \frac{n(E_2)}{n(S)} = \frac{13}{52} = \frac{1}{4}$.
Odds against getting a spade = $\frac{\{1 - P(E_2)\}}{P(E_2)} = \frac{(1 - \frac{1}{4})}{(1/4)} = \frac{3}{1}$.

---

### Example 18:

Two cards are drawn at random from a pack of 52 cards. What is the probability that both the drawn cards are aces?

#### Solution:

Let $S$ be the sample space. Then,
$n(S)$ = number of ways of selecting 2 cards out of 52 = ${}^{52}C_{2} = \frac{(52 \times 51)}{(2 \times 1)} = 1326$.
Let $E$ = event that both the cards drawn are aces. Then,
$n(E)$ = number of ways of drawing 2 aces out of 4 = ${}^{4}C_{2} = \frac{(4 \times 3)}{(2 \times 1)} = 6$.
$P(\text{getting 2 aces}) = P(E) = \frac{n(E)}{n(S)} = \frac{6}{1326} = \frac{1}{221}$.

---

