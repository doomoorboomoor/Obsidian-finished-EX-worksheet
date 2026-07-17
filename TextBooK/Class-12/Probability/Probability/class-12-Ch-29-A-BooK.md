# 29. PROBABILITY

## CONDITIONAL PROBABILITY AND PROBABILITY OF INDEPENDENT EVENTS

The concept of probability and various results on it were discussed in class XI. In this chapter, we shall be dealing with problems based on conditional probability and probability of independent events.

## CONDITIONAL PROBABILITY

Let $A$ and $B$ be the two events associated with the same random experiment. Then, the probability of occurrence of $A$ under the condition $B$ has already occurred and $P(B) \neq 0$, is called conditional probability, denoted by $P(A / B)$.
We define:

$$
P(A / B)=\frac{P(A \cap B)}{P(B)}, \text { where } P(B) \neq 0
$$

and $P(B / A)=\frac{P(B \cap A)}{P(A)}=\frac{P(A \cap B)}{P(A)}$, where $P(A) \neq 0$.

## SOLVED EXAMPLES

### Example 1:

A die is rolled. If the outcome is an odd number, what is the probability that it is prime?

#### Solution:

When a die is rolled, the sample space is given by

$$
S=\{1,2,3,4,5,6\}
$$

Let $A=$ event of getting a prime number, and
$B=$ event of getting an odd number.
Then, $A=\{2,3,5\}$, $B=\{1,3,5\}$ and $A \cap B=\{3,5\}$.
$\therefore P(A)=\frac{n(A)}{n(S)}=\frac{3}{6}=\frac{1}{2}$, $P(B)=\frac{n(B)}{n(S)}=\frac{3}{6}=\frac{1}{2}$ and $P(A \cap B)=\frac{n(A \cap B)}{n(S)}=\frac{2}{6}=\frac{1}{3}$.
Suppose $B$ has already occurred and then $A$ occurs.
So, we have to find $P(A / B)$.

Now, $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(1 / 3)}{(1 / 2)}=\left(\frac{1}{3} \times \frac{2}{1}\right)=\frac{2}{3}$.
$P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(1 / 3)}{(1 / 2)}=\left(\frac{1}{3} \times \frac{2}{1}\right)=\frac{2}{3}$.
Hence, the required probability is $\frac{2}{3}$.

---

### Example 2:

Ten cards numbered 1 to 10 are placed in a box, mixed up thoroughly and then one card is drawn randomly. If it is known that the number on the drawn card is more than 3, what is the probability that it is an even number?

#### Solution:

Clearly, the sample space is $S=\{1,2,3,4,5,6,7,8,9,10\}$.
Let $A=$ event that the number on the drawn card is even, and
$B=$ event that the number on the drawn card is more than 3.
Then $A=\{2,4,6,8,10\}$, $B=\{4,5,6,7,8,9,10\}$ and $A \cap B=\{4,6,8,10\}$.
$\therefore P(A)=\frac{n(A)}{n(S)}=\frac{5}{10}=\frac{1}{2}$, $P(B)=\frac{n(B)}{n(S)}=\frac{7}{10}$ and $P(A \cap B)=\frac{n(A \cap B)}{n(S)}=\frac{4}{10}=\frac{2}{5}$.
Suppose $B$ has already occurred and then $A$ occurs.
So, we have to find $P(A / B)$.
Now, $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(2 / 5)}{(7 / 10)}=\left(\frac{2}{5} \times \frac{10}{7}\right)=\frac{4}{7}$.
Hence, the required probability is $\frac{4}{7}$.

---

### Example 3:

A die is thrown twice and the sum of the numbers appearing is observed to be 6. What is the conditional probability that the number 4 has appeared at least once?

#### Solution:

We know that when a die is thrown twice, then the sample space has 36 possible outcomes.
Let $A=$ event that 4 appears at least once, and
$B=$ event that the sum of the numbers appearing is 6.
Then,
$A=\{(4,1),(4,2),(4,3),(4,4),(4,5),(4,6),(1,4),(2,4),(3,4)$,
and $B=\{(1,5),(2,4),(3,3),(4,2),(5,1)\}$.
$\therefore \quad A \cap B=\{(2,4),(4,2)\}$.
So, $P(A)=\frac{n(A)}{n(S)}=\frac{11}{36}$, $P(B)=\frac{n(B)}{n(S)}=\frac{5}{36}$ and $\quad P(A \cap B)=\frac{n(A \cap B)}{n(S)}=\frac{2}{36}=\frac{1}{18}$.
Suppose $B$ has already occurred and then $A$ occurs.
So, we have to find $P(A / B)$.
Now, $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(1 / 18)}{(5 / 36)}=\left(\frac{1}{18} \times \frac{36}{5}\right)=\frac{2}{5}$.
Hence, the required probability is $\frac{2}{5}$.

---

### Example 4:

Assume that each born child is equally likely to be a boy or a girl. If a family has two children, what is the conditional probability that both are girls given that (i) the youngest child is a girl, (ii) at least one of the children is a girl?

#### Solution:

We may write the sample space as
$S=\left\{G_{1} G_{2}, G_{1} B_{2}, B_{1} G_{2}, B_{1} B_{2}\right\}$, where the youngest child appears later.
(i) Let $A=$ event that both the children are girls, and
$B=$ event that the youngest child is a girl.
Then, $A=\left\{G_{1} G_{2}\right\}$, $B=\left\{G_{1} G_{2}, B_{1} G_{2}\right\}$ and $A \cap B=\left\{G_{1} G_{2}\right\}$.
$\therefore \quad P(A)=\frac{n(A)}{n(S)}=\frac{1}{4}$, $\quad P(B)=\frac{n(B)}{n(S)}=\frac{2}{4}=\frac{1}{2}$ and $P(A \cap B)=\frac{n(A \cap B)}{n(S)}=\frac{1}{4}$.
Suppose $B$ has already occurred and then $A$ occurs.
So, we have to find $P(A / B)$.
Now, $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(1 / 4)}{(1 / 2)}=\left(\frac{1}{4} \times \frac{2}{1}\right)=\frac{1}{2}$.
Hence, the required probability is $\frac{1}{2}$.

(ii) Let $A=$ event that both the children are girls, and
$E=$ event that at least one of the children is a girl.
Then, $A=\left\{G_{1} G_{2}\right\}$, $E=\left\{G_{1} B_{2}, B_{1} G_{2}, G_{1} G_{2}\right\}$ and $A \cap E=\left\{G_{1} G_{2}\right\}$.
$\therefore \quad P(A)=\frac{n(A)}{n(S)}=\frac{1}{4}$, $\quad P(E)=\frac{n(E)}{n(S)}=\frac{3}{4}$ and $P(A \cap E)=\frac{n(A \cap E)}{n(S)}=\frac{1}{4}$.
Suppose $E$ has already occurred and then $A$ occurs.
So, we have to find $P(A / E)$.
Now, $P(A / E)=\frac{P(A \cap E)}{P(E)}=\frac{(1 / 4)}{(3 / 4)}=\left(\frac{1}{4} \times \frac{4}{3}\right)=\frac{1}{3}$.

Hence, the required probability is $\frac{1}{3}$.

---

### Example 5:

An instructor has a question bank consisting of 300 easy true/false questions; 200 difficult true/false questions; 500 easy multiple-choice questions and 400 difficult multiple-choice questions. If a question is selected at random from the question bank, what is the probability that it will be an easy question given that it is a multiple-choice question?

#### Solution:

Clearly, the sample space consists of 1400 questions.
$\therefore \quad n(S)=1400$.
Let $A=$ event of selecting an easy question, and
$B=$ event of selecting a multiple-choice question.
Then, $A \cap B=$ event of selecting an easy multiple-choice question.
$\therefore \quad n(A)=(300+500)=800$, $n(B)=(500+400)=900$ and $n(A \cap B)=500$.
So, $\quad P(A)=\frac{n(A)}{n(S)}=\frac{800}{1400}=\frac{4}{7}$, $\quad P(B)=\frac{n(B)}{n(S)}=\frac{900}{1400}=\frac{9}{14}$ and $P(A \cap B)=\frac{n(A \cap B)}{n(S)}=\frac{500}{1400}=\frac{5}{14}$.
Suppose $B$ has already occurred and then $A$ occurs.
Thus we have to find $P(A / B)$.
Now, $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(5 / 14)}{(9 / 14)}=\left(\frac{5}{14} \times \frac{14}{9}\right)=\frac{5}{9}$.
Hence, the required probability is $\frac{5}{9}$.

---

### Example 6:

Two numbers are selected at random from the integers 1 through 9. If the sum is even, find the probability that both the numbers are odd.

#### Solution:

Out of the numbers from 1 to 9, there are 5 odd numbers and 4 even numbers.

Let $A=$ event of choosing two odd numbers, and
$B=$ event of choosing two numbers whose sum is even.
Then, $n(A)=$ number of ways of choosing 2 odd numbers out of 5 $={ }^{5} C_{2}$.
$n(B)=$ number of ways of choosing 2 numbers whose sum is even $=\left({ }^{4} C_{2}+{ }^{5} C_{2}\right)$ [2 out of 4 even and 2 out of 5 odd].
$n(A \cap B)=$ number of ways of choosing 2 odd numbers out of 5 $={ }^{5} C_{2}$.

Suppose $B$ has already occurred and then $A$ occurs.

Then, we have to find $P(A / B)$.
Now, $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{n(A \cap B)}{n(B)}=\frac{{ }^{5} C_{2}}{{ }^{4} C_{2}+{ }^{5} C_{2}}$

$$
=\frac{5 \times 4}{2} \times \frac{2}{(4 \times 3+5 \times 4)}=\frac{20}{32}=\frac{5}{8} .
$$

Hence, the required probability is $\frac{5}{8}$.

---

## Properties of Conditional Probability

### Theorem 1:

Let $A$ and $B$ be the events of a sample space $S$ of an experiment. Then, prove that $P(S / B)=P(B / B)=1$.

#### Proof:

We know that:

$$
P(S / B)=\frac{P(S \cap B)}{P(B)}=\frac{P(B)}{P(B)}=1[\because S \cap B=B] .
$$

And, $P(B / B)=\frac{P(B \cap B)}{P(B)}=\frac{P(B)}{P(B)}=1$.
Hence, $P(S / B)=P(B / B)=1$.

---

### Theorem 2:

Let $A$ and $B$ be the two events of a sample space $S$ and let $E$ be an event such that $P(E) \neq 0$. Then, prove that

$$
P[(A \cup B) / E]=P(A / E)+P(B / E)-P[(A \cap B) / E] .
$$

#### Proof:

We have

$$
\begin{aligned}
P[(A \cup B) / E] & =\frac{P[(A \cup B) \cap E]}{P(E)} \\
& =\frac{P[(A \cap E) \cup(B \cap E)]}{P(E)} \\
& =\frac{P(A \cap E)+P(B \cap E)-P[(A \cap E) \cap(B \cap E)]}{P(E)} \\
& =\frac{P(A \cap E)+P(B \cap E)-P(A \cap B \cap E)}{P(E)} \\
& =\frac{P(A \cap E)}{P(E)}+\frac{P(B \cap E)}{P(E)}-\frac{P[(A \cap B) \cap E]}{P(E)} \\
& =P(A / E)+P(B / E)-P[(A \cap B) / E] .
\end{aligned}
$$

Hence, $P[(A \cup B) / E]=P(A / E)+P(B / E)-[(A \cap B) / E]$.

#### Corollary:

If $A$ and $B$ are disjoint events, prove that

$$
P[(A \cup B) / E]=P(A / E)+P(B / E) .
$$

#### Proof:

For any events $A$ and $B$, we have

$$
P[(A \cup B) / E]=P(A / E)+P(B / E)-P[(A \cap B) / E] .
$$

If $A$ and $B$ are disjoint, then $P[(A \cap B) / E]=0$.
Hence, in this case, we have

$$
P[(A \cup B) / E]=P(A / E)+P(B / E) .
$$

---

### Theorem 3:

For any events $A$ and $B$ of a sample space $S$, prove that

$$
P(\bar{A} / B)=1-P(A / B), \text { where } \bar{A} \text { denotes 'not } A^{\prime} .
$$

#### Proof:

We know that

$$
\begin{aligned}
P(S / B)=1 & \Rightarrow P[(A \cup \bar{A}) / B]=1[\because S=A \cup \bar{A}] \\
& \Rightarrow P(A / B)+P(\bar{A} / B)=1[\because A \cap \bar{A}=\varphi] \\
& \Rightarrow P(\bar{A} / B)=1-P(A / B) .
\end{aligned}
$$

Hence, $P(\bar{A} / B)=1-P(A / B)$.

---

### Example 7:

If $A$ and $B$ are the two events such that $P(A)=\frac{3}{5}, P(B)=\frac{7}{10}$ and $P(A \cup B)=\frac{9}{10}$, then find (i) $P(A \cap B)$ (ii) $P(A / B)$ (iii) $P(B / A)$.

#### Solution:

(i) We know that

$$
\begin{aligned}
P(A \cap B) & =P(A)+P(B)-P(A \cup B) \\
& =\left(\frac{3}{5}+\frac{7}{10}-\frac{9}{10}\right)=\frac{(6+7-9)}{10}=\frac{4}{10}=\frac{2}{5} .
\end{aligned}
$$

(ii) $P(A / B)=\frac{(A \cap B)}{P(B)}=\frac{(2 / 5)}{(7 / 10)}=\left(\frac{2}{5} \times \frac{10}{7}\right)=\frac{4}{7}$.
(iii) $P(B / A)=\frac{(B \cap A)}{P(A)}=\frac{P(A \cap B)}{P(A)}=\left(\frac{2 / 5}{3 / 5}\right)=\left(\frac{2}{5} \times \frac{5}{3}\right)=\frac{2}{3}$.

---

### Example 8:

Evaluate $P(A \cup B)$, if $2 P(A)=P(B)=\frac{6}{13}$ and $P(A / B)=\frac{1}{3}$.

#### Solution:

$\quad 2 P(A)=P(B)=\frac{6}{13} \Rightarrow P(A)=\frac{3}{13}$ and $P(B)=\frac{6}{13}$.

$$
\begin{array}{ll}
\therefore & P(A / B)=\frac{P(A \cap B)}{P(B)} \\
& \Rightarrow P(A \cap B)=P(A / B) \cdot P(B)=\left(\frac{1}{3} \times \frac{6}{13}\right)=\frac{2}{13} .
\end{array}
$$

So, $P(A \cup B)=P(A)+P(B)-P(A \cap B)$

$$
=\left(\frac{3}{13}+\frac{6}{13}-\frac{2}{13}\right)=\frac{(3+6-2)}{13}=\frac{7}{13} .
$$

Hence, $P(A \cup B)=\frac{7}{13}$.

---

### Example 9:

Let $A$ and $B$ be the events such that $P(A)=\frac{1}{3}, P(B)=\frac{1}{4}$ and $P(A \cap B)=\frac{1}{5}$.
Find: (i) $P(A / B)$ (ii) $P(B / A)$ (iii) $P(A \cup B)$ (iv) $P(\bar{B} / \bar{A})$

#### Solution:

We have:
(i) $P(A / B)=\frac{P(A \cap B)}{P(B)}=\frac{(1 / 5)}{(1 / 4)}=\left(\frac{1}{5} \times \frac{4}{1}\right)=\frac{4}{5}$.
(ii) $P(B / A)=\frac{P(B \cap A)}{P(A)}=\frac{P(A \cap B)}{P(A)}=\frac{(1 / 5)}{(1 / 3)}=\left(\frac{1}{5} \times \frac{3}{1}\right)=\frac{3}{5}$.
(iii) $P(A \cup B)=P(A)+P(B)-P(A \cap B)$

$$
=\left(\frac{1}{3}+\frac{1}{4}-\frac{1}{5}\right)=\frac{(20+15-12)}{60}=\frac{23}{60} .
$$

(iv) $P(\bar{B} / \bar{A})=\frac{P(\bar{B} \cap \bar{A})}{P(\bar{A})}=\frac{P(\bar{A} \cap \bar{B})}{P(\bar{A})}=\frac{P(\overline{A \cup B})}{P(\bar{A})}$

$$
=\frac{1-P(A \cup B)}{1-P(A)}=\frac{\left(1-\frac{23}{60}\right)}{\left(1-\frac{1}{3}\right)}=\frac{\left(\frac{37}{60}\right)}{\left(\frac{2}{3}\right)}=\left(\frac{37}{60} \times \frac{3}{2}\right)=\frac{37}{40} .
$$

---