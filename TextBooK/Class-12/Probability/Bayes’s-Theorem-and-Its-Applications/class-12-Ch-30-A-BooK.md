## 30. Bayes's Theorem and its Applications

### Theorem of Total Probability

#### Theorem
Let $E_{1}, E_{2}, \ldots, E_{n}$ be **mutually exclusive and exhaustive events** associated with a random experiment and let $E$ be an event that occurs with some $E_{i}$. Then, prove that

$$
P(E)=\sum_{i=1}^{n} P\left(E / E_{i}\right) \cdot P\left(E_{i}\right) .
$$

#### Proof
Let $S$ be the sample space. Then,

$$
\begin{array}{ll} 
& S=E_{1} \cup E_{2} \cup \ldots \cup E_{n} \text { and } E_{i} \cap E_{j}=\phi \text { for } i \neq j . \\
\therefore \quad & E=E \cap S=E \cap\left(E_{1} \cup E_{2} \cup \ldots \cup E_{n}\right) \\
& =\left(E \cap E_{1}\right) \cup\left(E \cap E_{2}\right) \cup \ldots \cup\left(E \cap E_{n}\right) \\
\Rightarrow \quad & P(E)=P\left\{\left(E \cap E_{1}\right) \cup\left(E \cap E_{2}\right) \cup \ldots \cup\left(E \cap E_{n}\right)\right\} \\
& =P\left(E \cap E_{1}\right)+P\left(E \cap E_{2}\right)+\ldots+P\left(E \cap E_{n}\right) \\
& \quad\left\{\because\left(E \cap E_{1}\right),\left(E \cap E_{2}\right), \ldots,\left(E \cap E_{n}\right) \text { are pairwise disjoint }\right\} \\
& =P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)+\ldots+P\left(E / E_{n}\right) \cdot P\left(E_{n}\right)
\end{array}
$$

[by multiplication theorem]

$$
=\sum_{i=1}^{n} P\left(E / E_{i}\right) \cdot P\left(E_{i}\right) .
$$

---

### Example:

There are three urns containing 3 white and 2 black balls; 2 white and 3 black balls; 1 black and 4 white balls respectively. There is equal probability of each urn being chosen. One ball is drawn from an urn chosen at random. What is the probability that a white ball is drawn?

#### Solution:

Let $E_{1}, E_{2}$ and $E_{3}$ be the events of choosing the first, second and third urn respectively. Then,

$$
P\left(E_{1}\right)=P\left(E_{2}\right)=P\left(E_{3}\right)=\frac{1}{3} .
$$

Let $E$ be the event that a white ball is drawn. Then,

$$
P\left(E / E_{1}\right)=\frac{3}{5}, P\left(E / E_{2}\right)=\frac{2}{5} \text { and } P\left(E / E_{3}\right)=\frac{4}{5} .
$$

By the **theorem of total probability**, we have

$$
\begin{aligned}
P(E) & =P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)+P\left(E / E_{3}\right) \cdot P\left(E_{3}\right) \\
& =\left(\frac{3}{5} \times \frac{1}{3}+\frac{2}{5} \times \frac{1}{3}+\frac{4}{5} \times \frac{1}{3}\right)=\left(\frac{1}{5}+\frac{2}{15}+\frac{4}{15}\right)=\frac{9}{15}=\frac{3}{5} .
\end{aligned}
$$

---

### Bayes's Theorem
Let $E_{1}, E_{2}, \ldots, E_{n}$ be **mutually exclusive and exhaustive events**, associated with a random experiment, and let $E$ be any event that occurs with some $E_{i}$. Then,

$$
P\left(E_{i} / E\right)=\frac{P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)}{\sum_{i=1}^{n} P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)} ; i=1,2,3, \ldots, n .
$$

#### Proof
By the **theorem of total probability**, we have

$$
\begin{align*}
P(E)=\sum_{i=1}^{n} P\left(E / E_{i}\right) \cdot P\left(E_{i}\right) & \quad[\text { by multiplication theorem}]  \tag{i}\\
\therefore \quad P\left(E_{i} / E\right) & =\frac{P\left(E \cap E_{i}\right)}{P(E)} \quad\left[\because \quad P\left(E / E_{i}\right)=\frac{P\left(E \cap E_{i}\right)}{P\left(E_{i}\right)}\right] \\
& =\frac{P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)}{P(E)} \quad\left[\begin{array}{ll}
\because & \text { (i) }
\end{array}\right] \\
& =\frac{P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)}{\sum_{i=1}^{n} P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)} \text { [using (i) }
\end{align*}
$$

Hence, $P\left(E_{i} / E\right)=\frac{P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)}{\sum_{i=1}^{n} P\left(E / E_{i}\right) \cdot P\left(E_{i}\right)}$.

---

## Solved Examples

### Example 1:

A factory has three machines, X, Y and Z, producing 1000, 2000 and 3000 bolts per day respectively. The machine $X$ produces $1 \%$ defective bolts, $Y$ produces $1.5 \%$ defective bolts and $Z$ produces $2 \%$ defective bolts. At the end of the day, a bolt is drawn at random and it is found to be defective. What is the probability that this defective bolt has been produced by the machine X?
[CBSE 2002]

#### Solution:

Total number of bolts produced in a day
$$
=(1000+2000+3000)=6000 .
$$

Let $E_{1}, E_{2}$ and $E_{3}$ be the events of drawing a bolt produced by machines $X, Y$ and $Z$ respectively. Then,

$$
P\left(E_{1}\right)=\frac{1000}{6000}=\frac{1}{6} ; P\left(E_{2}\right)=\frac{2000}{6000}=\frac{1}{3} \text { and } P\left(E_{3}\right)=\frac{3000}{6000}=\frac{1}{2} .
$$

Let $E$ be the event of drawing a defective bolt. Then,

$$
\begin{aligned}
P\left(E / E_{1}\right)= & \text { probability of drawing a defective bolt, given that it } \\
& \text { is produced by the machine } X \\
= & \frac{1}{100}
\end{aligned}
$$

$P\left(E / E_{2}\right)=$ probability of drawing a defective bolt, given that it is produced by the machine $Y$

$$
=\frac{1.5}{100}=\frac{15}{1000}=\frac{3}{200} .
$$

$P\left(E / E_{3}\right)=$ probability of drawing a defective bolt, given that it is produced by the machine $Z$

$$
=\frac{2}{100}=\frac{1}{50} .
$$

Required probability
$$
=P\left(E_{1} / E\right)
$$

$=$ probability that the bolt drawn is produced by $X$, given that it is defective

$$
\begin{aligned}
& =\frac{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)}{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)+P\left(E_{2}\right) \cdot P\left(E / E_{2}\right)+P\left(E_{3}\right) \cdot P\left(E / E_{3}\right)} \\
& =\frac{\left(\frac{1}{6} \times \frac{1}{100}\right)}{\left(\frac{1}{6} \times \frac{1}{100}\right)+\left(\frac{1}{3} \times \frac{3}{200}\right)+\left(\frac{1}{2} \times \frac{1}{50}\right)} \\
& =\left(\frac{1}{600} \times \frac{600}{10}\right)=\frac{1}{10}=0.1 .
\end{aligned}
$$

Hence, the required probability is 0.1.

---

### Example 2:

In a bolt factory, three machines, A, B, C, manufacture $25 \%$, $35 \%$ and $40 \%$ of the total production respectively. Of their respective outputs, $5 \%$, $4 \%$ and $2 \%$ are defective. A bolt is drawn at random from the total product and it is found to be defective. Find the probability that it was manufactured by the machine $C$.
[CBSE 2006, '10]

#### Solution:

Let $E_{1}, E_{2}$ and $E_{3}$ be the events of drawing a bolt produced by machine $A, B$ and $C$ respectively. Then,

$$
P\left(E_{1}\right)=\frac{25}{100}=\frac{1}{4}, P\left(E_{2}\right)=\frac{35}{100}=\frac{7}{20}, \text { and } P\left(E_{3}\right)=\frac{40}{100}=\frac{2}{5} .
$$

Let $E$ be the event of drawing a defective bolt. Then,
$P\left(E / E_{1}\right)=$ probability of drawing a defective bolt, given that it is produced by the machine $A$

$$
=\frac{5}{100}=\frac{1}{20} .
$$

$P\left(E / E_{2}\right)=$ probability of drawing a defective bolt, given that it is produced by the machine $B$

$$
=\frac{4}{100}=\frac{1}{25} .
$$

$$
\begin{aligned}
P\left(E / E_{3}\right)= & \text { probability of drawing a defective bolt, given that it } \\
& \text { is produced by the machine } C
\end{aligned}
$$

$$
=\frac{2}{100}=\frac{1}{50} .
$$

Probability that the bolt drawn is manufactured by $C$, given that it is defective

$$
\begin{aligned}
& =P\left(E_{3} / E\right) \\
& =\frac{P\left(E / E_{3}\right) \cdot P\left(E_{3}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)+P\left(E / E_{3}\right) \cdot P\left(E_{3}\right)}
\end{aligned}
$$

[by Bayes's theorem]

$$
=\frac{\left(\frac{1}{50} \times \frac{2}{5}\right)}{\left(\frac{1}{20} \times \frac{1}{4}\right)+\left(\frac{1}{25} \times \frac{7}{20}\right)+\left(\frac{1}{50} \times \frac{2}{5}\right)}=\left(\frac{1}{125} \times \frac{2000}{69}\right)=\frac{16}{69} .
$$

Hence, the required probability is $\frac{16}{69}$.

---

### Example 3:

A company has two plants to manufacture bicycles. The first plant manufactures $60 \%$ of the bicycles and the second plant, $40 \%$. Also, $80 \%$ of the bicycles are rated of standard quality at the first plant and $90 \%$ of standard quality at the second plant. A bicycle is picked up at random and found to be of standard quality. Find the probability that it comes from the second plant.
[CBSE 2003]

#### Solution:

Let $E_{1}$ and $E_{2}$ be the events of choosing a bicycle from the first plant and the second plant respectively. Then,

$$
P\left(E_{1}\right)=\frac{60}{100}=\frac{3}{5}, \text { and } P\left(E_{2}\right)=\frac{40}{100}=\frac{2}{5} .
$$

Let $E$ be the event of choosing a bicycle of standard quality. Then,
$P\left(E / E_{1}\right)=$ probability of choosing a bicycle of standard quality, given that it is produced by the first plant

$$
=\frac{80}{100}=\frac{4}{5} .
$$

$P\left(E / E_{2}\right)=$ probability of choosing a bicycle of standard quality, given that it is produced by the second plant

$$
=\frac{90}{100}=\frac{9}{10} .
$$

The required probability
$P\left(E_{2} / E\right)=$ probability of choosing a bicycle from the second plant, given that it is of standard quality

$$
=\frac{P\left(E_{2}\right) \cdot P\left(E / E_{2}\right)}{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)+P\left(E_{2}\right) \cdot P\left(E / E_{2}\right)} \text { [by Bayes's theorem] }
$$

$$
=\frac{\left(\frac{2}{5} \times \frac{9}{10}\right)}{\left(\frac{3}{5} \times \frac{4}{5}\right)+\left(\frac{2}{5} \times \frac{9}{10}\right)}=\frac{3}{7} .
$$

---

### Example 4:

An insurance company insured 2000 scooter drivers, 4000 car drivers and 6000 truck drivers. The probability of an accident involving a scooter, a car and a truck is $\frac{1}{100}, \frac{3}{100}$ and $\frac{3}{20}$ respectively. One of the insured persons meets with an accident. What is the probability that he is a scooter driver?
[CBSE 2000, '02, '08]

#### Solution:

Total number of persons insured $=(2000+4000+6000)=12000$.
Let $E_{1}, E_{2}$ and $E_{3}$ be the events of choosing a scooter driver, a car driver and a truck driver respectively. Then,

$$
P\left(E_{1}\right)=\frac{2000}{12000}=\frac{1}{6}, P\left(E_{2}\right)=\frac{4000}{12000}=\frac{1}{3} \text { and } P\left(E_{3}\right)=\frac{6000}{12000}=\frac{1}{2} .
$$

Let $E$ be the event of an insured person meeting with an accident. Then,

$$
\begin{aligned}
P\left(E / E_{1}\right)= & \text { probability that an insured person meets with an } \\
& \text { accident, given that he is a scooter driver } \\
= & \frac{1}{100} .
\end{aligned}
$$

Similarly, $P\left(E / E_{2}\right)=\frac{3}{100}$ and $P\left(E / E_{3}\right)=\frac{3}{20}$.

Required probability
$=P\left(E_{1} / E\right)$ [by Bayes's theorem]
= probability of choosing a scooter driver, given that he meets with an accident

$$
\begin{aligned}
& =\frac{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)+P\left(E / E_{3}\right) \cdot P\left(E_{3}\right)} \\
& =\frac{\left(\frac{1}{100} \times \frac{1}{6}\right)}{\left(\frac{1}{100} \times \frac{1}{6}\right)+\left(\frac{3}{100} \times \frac{1}{3}\right)+\left(\frac{3}{20} \times \frac{1}{2}\right)}=\frac{1}{52} .
\end{aligned}
$$

Hence, the required probability is $\frac{1}{52}$.

---

### Example 5:

A doctor is to visit a patient. From past experience, it is known that the probabilities that he will come by train, bus, scooter or by car are respectively $\frac{3}{10}, \frac{1}{5}, \frac{1}{10}$ and $\frac{2}{5}$. The probabilities that he will be late are $\frac{1}{4}$, $\frac{1}{3}$ and $\frac{1}{12}$, if he comes by train, bus and scooter respectively; but if he comes by car, he will not be late. When he arrives, he is late. What is the probability that he has come by train?
[CBSE 2008C]

#### Solution:

Let $E_{1}, E_{2}, E_{3}$ and $E_{4}$ be the events that the doctor comes by train, bus, scooter and car respectively. Then,

$$
P\left(E_{1}\right)=\frac{3}{10}, P\left(E_{2}\right)=\frac{1}{5}, P\left(E_{3}\right)=\frac{1}{10} \text { and } P\left(E_{4}\right)=\frac{2}{5} .
$$

Let $E$ be the event that the doctor is late. Then,

$$
\begin{aligned}
P\left(E / E_{1}\right)= & \text { probability that the doctor is late, given that he } \\
& \text { comes by train } \\
= & \frac{1}{4} .
\end{aligned}
$$

$$
\begin{aligned}
P\left(E / E_{2}\right)= & \text { probability that the doctor is late, given that he } \\
& \text { comes by bus } \\
= & \frac{1}{3} .
\end{aligned}
$$

$$
\begin{aligned}
P\left(E / E_{3}\right)= & \text { probability that the doctor is late, given that he } \\
& \text { comes by scooter } \\
= & \frac{1}{12} .
\end{aligned}
$$

$$
\begin{aligned}
P\left(E / E_{4}\right)= & \text { probability that the doctor is late, given that he } \\
& \text { comes by car } \\
= & 0 .
\end{aligned}
$$

Probability that he comes by train, given that he is late

$$
\begin{aligned}
& =P\left(E_{1} / E\right) \\
& =\frac{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)}{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)+P\left(E_{2}\right) \cdot P\left(E / E_{2}\right)+P\left(E_{3}\right) \cdot P\left(E / E_{3}\right)+P\left(E_{4}\right) \cdot P\left(E / E_{4}\right)}
\end{aligned}
$$

[by Bayes's theorem]

$$
\begin{aligned}
& =\frac{\left(\frac{3}{10} \times \frac{1}{4}\right)}{\left(\frac{3}{10} \times \frac{1}{4}\right)+\left(\frac{1}{5} \times \frac{1}{3}\right)+\left(\frac{1}{10} \times \frac{1}{12}\right)+\left(\frac{2}{5} \times 0\right)} \\
& =\left(\frac{3}{40} \times \frac{120}{18}\right)=\frac{1}{2} .
\end{aligned}
$$

Hence, the required probability is $\frac{1}{2}$.

---

### Example 6:

A man is known to speak the truth 3 out of 4 times. He throws a die and reports that it is a six. Find the probability that it is actually a six.
[CBSE 2005, '11]

#### Solution:

In a throw of a die, let

$$
\begin{aligned}
E_{1} & =\text { event of getting a six, } \\
E_{2} & =\text { event of not getting a six, and } \\
E & =\text { event that the man reports that it is a six. }
\end{aligned}
$$

Then, $P\left(E_{1}\right)=\frac{1}{6}$, and $P\left(E_{2}\right)=\left(1-\frac{1}{6}\right)=\frac{5}{6}$.

$$
\begin{aligned}
P\left(E / E_{1}\right)= & \text { probability that the man reports that six occurs, when } \\
& \text { six has actually occurred } \\
= & \text { probability that the man speaks the truth } \\
= & \frac{3}{4} .
\end{aligned}
$$

$P\left(E / E_{2}\right)=$ probability that the man reports that six occurs, when six has not actually occurred
= probability that the man does not speak the truth

$$
=\left(1-\frac{3}{4}\right)=\frac{1}{4} .
$$

Probability of getting a six, given that the man reports it to be six

$$
\begin{aligned}
& =P\left(E_{1} / E\right) \\
& =\frac{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)} \quad \text { [by Bayes's theorem] } \\
& =\frac{\left(\frac{3}{4} \times \frac{1}{6}\right)}{\left(\frac{3}{4} \times \frac{1}{6}\right)+\left(\frac{1}{4} \times \frac{5}{6}\right)}=\left(\frac{1}{8} \times 3\right)=\frac{3}{8}
\end{aligned}
$$

Hence, the required probability is $\frac{3}{8}$.

---

### Example 7:

In an examination, an examinee either guesses or copies or knows the answer to a multiple-choice question with four choices. The probability that he makes a guess is $(1 / 3)$ and the probability that he copies the answer is (1/6). The probability that his answer is correct, given that he copied it, is (1/8). The probability that his answer is correct, given that he guessed it, is (1/4). Find the probability that he knew the answer to the question, given that he correctly answered it.

#### Solution:

Let $E_{1}=$ event that the examinee guesses the answer,

$$
\begin{aligned}
E_{2} & =\text { event that he copies the answer, } \\
E_{3} & =\text { event that he knows the answer, and } \\
E & =\text { event that he answers correctly. }
\end{aligned}
$$

Then, $P\left(E_{1}\right)=\frac{1}{3}, P\left(E_{2}\right)=\frac{1}{6}$, and $P\left(E_{3}\right)=1-\left(\frac{1}{3}+\frac{1}{6}\right)=\frac{1}{2}$
$\left[\because E_{1}, E_{2}, E_{3}\right.$ are mutually exclusive and exhaustive $]$.
$\therefore \quad P\left(E / E_{1}\right)=$ probability that he answers correctly, given that he guesses
$=\frac{1}{4}$.
$P\left(E / E_{2}\right)=$ probability that he answers correctly, given that he copies
$=\frac{1}{8}$.
$P\left(E / E_{3}\right)=$ probability that he answers correctly, given that he knew the answer
$=1$.
Required probability

$$
\begin{aligned}
& =P\left(E_{3} / E\right) \\
& =\frac{P\left(E / E_{3}\right) \cdot P\left(E_{3}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)+P\left(E / E_{3}\right) \cdot P\left(E_{3}\right)}
\end{aligned}
$$

[by Bayes's theorem]

$$
=\frac{\left(1 \times \frac{1}{2}\right)}{\left(\frac{1}{4} \times \frac{1}{3}\right)+\left(\frac{1}{8} \times \frac{1}{6}\right)+\left(1 \times \frac{1}{2}\right)}=\frac{24}{29} .
$$

Hence, the required probability is $\frac{24}{29}$.

---

### Example 8:

By examining the chest X-ray, the probability that a person is diagnosed with TB when he is actually suffering from it, is 0.99 . The probability that the doctor incorrectly diagnoses a person to be having $T B$, on the basis of $X$-ray reports, is 0.001 . In a certain city, 1 in 1000 persons suffers from TB. A person is selected at random and is diagnosed to have TB. What is the chance that he actually has $T B$ ?

#### Solution:

Let $E=$ event that the doctor diagnoses TB,
$E_{1}=$ event that the person selected is suffering from TB, and
$E_{2}=$ event that the person selected is not suffering from TB.
Then, $P\left(E_{1}\right)=\frac{1}{1000}$ and $P\left(E_{2}\right)=\left(1-\frac{1}{1000}\right)=\frac{999}{1000}$.

$$
\begin{aligned}
P\left(E / E_{1}\right)= & \text { probability that } \mathrm{TB} \text { is diagnosed, when the person } \\
& \text { actually has } \mathrm{TB} \\
= & \frac{99}{100}
\end{aligned}
$$

$$
\begin{aligned}
P\left(E / E_{2}\right)= & \text { probability that } \mathrm{TB} \text { is diagnosed, when the person } \\
& \text { has no } \mathrm{TB} \\
= & \frac{1}{1000} .
\end{aligned}
$$

Using Bayes's theorem, we have
$P\left(E_{1} / E\right)=$ probability of a person actually having TB , if it is known that he is diagnosed to have TB

$$
\begin{aligned}
& =\frac{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)} \\
& =\frac{\left(\frac{99}{100} \times \frac{1}{1000}\right)}{\left(\frac{99}{100} \times \frac{1}{1000}\right)+\left(\frac{1}{1000} \times \frac{999}{1000}\right)}=\frac{110}{221} .
\end{aligned}
$$

Hence, the required probability is $\frac{110}{221}$.

---

### Example 9:

Bag A contains 2 white and 3 red balls, and bag B contains 4 white and 5 red balls. One ball is drawn at random from one of the bags and it is found to be red. Find the probability that it was drawn from bag $B$.
[CBSE 2004C]

#### Solution:

Let $E_{1}=$ event of choosing bag $A$,

$$
\begin{aligned}
& E_{2}=\text { event of choosing bag } B, \text { and } \\
& E=\text { event of drawing a red ball. }
\end{aligned}
$$

Then, $P\left(E_{1}\right)=\frac{1}{2}$ and $P\left(E_{2}\right)=\frac{1}{2}$.
Also, $P\left(E / E_{1}\right)=$ event of drawing a red ball from bag $A=\frac{3}{5}$, and

$$
P\left(E / E_{2}\right)=\text { event of drawing a red ball from bag } B=\frac{5}{9} .
$$

Probability of drawing a ball from $B$, it being given that it is red

$$
\begin{aligned}
& =P\left(E_{2} / E\right) \\
& =\frac{P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)} \quad \text { [by Bayes's theorem] } \\
& =\frac{\left(\frac{5}{9} \times \frac{1}{2}\right)}{\left(\frac{3}{5} \times \frac{1}{2}\right)+\left(\frac{5}{9} \times \frac{1}{2}\right)}=\frac{25}{52}
\end{aligned}
$$

Hence, the required probability is $\frac{25}{52}$.

---

### Example 10:

There are 5 bags, each containing 5 white balls and 3 black balls. Also, there are 6 bags, each containing 2 white balls and 4 black balls. A white ball is drawn at random. Find the probability that this white ball is from a bag of the first group.

#### Solution:

Let $E_{1}=$ event of selecting a bag from the first group,

$$
\begin{aligned}
E_{2} & =\text { event of selecting a bag from the second group, and } \\
E & =\text { event of drawing a white ball. }
\end{aligned}
$$

Then, $P\left(E_{1}\right)=\frac{5}{11}$ and $P\left(E_{2}\right)=\frac{6}{11}$.

$$
\begin{aligned}
P\left(E / E_{1}\right)= & \text { probability of getting a white ball, given that it is } \\
& \text { from a bag of the first group } \\
= & \frac{5}{8}
\end{aligned}
$$

$$
\begin{aligned}
P\left(E / E_{2}\right)= & \text { probability of getting a white ball, given that it is } \\
& \text { from a bag of the second group } \\
= & \frac{2}{6}=\frac{1}{3} .
\end{aligned}
$$

Probability of getting the ball from a bag of the first group, given that it is white

$$
\begin{aligned}
& =P\left(E_{1} / E\right) \\
& =\frac{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)} \text { [by Bayes's theorem] } \\
& =\frac{\left(\frac{5}{8} \times \frac{5}{11}\right)}{\left(\frac{5}{8} \times \frac{5}{11}\right)+\left(\frac{1}{3} \times \frac{6}{11}\right)}=\frac{75}{123} .
\end{aligned}
$$

---

### Example 11:

Urn A contains 1 white, 2 black and 3 red balls; urn B contains 2 white, 1 black and 1 red ball; and urn C contains 4 white, 5 black and 3 red balls. One urn is chosen at random and two balls are drawn. These happen to be one white and one red. What is the probability that they come from urn $A$ ?
[CBSE 2009]

#### Solution:

Let $E_{1}, E_{2}, E_{3}$ be the events that the balls are drawn from urn $A$, urn $B$ and urn $C$ respectively, and let $E$ be the event that the balls drawn are one white and one red. Then, $P\left(E_{1}\right)=P\left(E_{2}\right)=P\left(E_{3}\right)=\frac{1}{3}$.
$P\left(E / E_{1}\right)=$ probability that the balls drawn are one white and one red, given that the balls are from urn $A$

$$
=\frac{{ }^{1} C_{1} \times{ }^{3} C_{1}}{{ }^{6} C_{2}}=\frac{3}{15}=\frac{1}{5} .
$$

$P\left(E / E_{2}\right)=$ probability that the balls drawn are one white and one red, given that the balls are from urn $B$

$$
=\frac{{ }^{2} C_{1} \times{ }^{1} C_{1}}{{ }^{4} C_{2}}=\frac{2}{6}=\frac{1}{3} .
$$

$P\left(E / E_{3}\right)=$ probability that the balls drawn are one white and one red, given that the balls are from urn $C$

$$
=\frac{{ }^{4} C_{1} \times{ }^{3} C_{1}}{{ }^{12} C_{2}}=\frac{12}{66}=\frac{2}{11} .
$$

Probability that the balls drawn are from urn $A$, it being given that the balls drawn are one white and one red

$$
\begin{aligned}
& =P\left(E_{1} / E\right) \\
& =\frac{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)}{P\left(E / E_{1}\right) \cdot P\left(E_{1}\right)+P\left(E / E_{2}\right) \cdot P\left(E_{2}\right)+P\left(E / E_{3}\right) \cdot P\left(E_{3}\right)}
\end{aligned}
$$

[by Bayes's theorem]

$$
\begin{aligned}
& =\frac{\left(\frac{1}{5} \times \frac{1}{3}\right)}{\left(\frac{1}{5} \times \frac{1}{3}\right)+\left(\frac{1}{3} \times \frac{1}{3}\right)+\left(\frac{2}{11} \times \frac{1}{3}\right)} \\
& =\left(\frac{1}{15} \times \frac{495}{118}\right)=\frac{33}{118} .
\end{aligned}
$$

Hence, the required probability is $\frac{33}{118}$.

---

### Example 12:

A card from a pack of 52 cards is lost. From the remaining cards of the pack, two cards are drawn and are found to be both spades. Find the probability of the lost card being a spade.
[CBSE 2002]

#### Solution:

Let $E_{1}, E_{2}, E_{3}$ and $E_{4}$ be the events of losing a card of spades, clubs, hearts and diamonds respectively.
Then, $P\left(E_{1}\right)=P\left(E_{2}\right)=P\left(E_{3}\right)=P\left(E_{4}\right)=\frac{13}{52}=\frac{1}{4}$.
Let $E$ be the event of drawing 2 spades from the remaining 51 cards. Then,
$P\left(E / E_{1}\right)=$ probability of drawing 2 spades, given that a card of spades is missing

$$
=\frac{{ }^{12} C_{2}}{{ }^{51} C_{2}}=\frac{(12 \times 11)}{2!} \times \frac{2!}{(51 \times 50)}=\frac{22}{425} .
$$

$P\left(E / E_{2}\right)$ = probability of drawing 2 spades, given that a card of clubs is missing

$$
=\frac{{ }^{13} C_{2}}{{ }^{51} C_{2}}=\frac{(13 \times 12)}{2!} \times \frac{2!}{(51 \times 50)}=\frac{26}{425} .
$$

$P\left(E / E_{3}\right)=$ probability of drawing 2 spades, given that a card of hearts is missing

$$
\begin{aligned}
& =\frac{{ }^{13} C_{2}}{{ }^{51} C_{2}}=\frac{26}{425} \cdot \\
& \begin{aligned}
P\left(E / E_{4}\right)= & \text { probability of drawing } 2 \text { spades, given that a card } \\
& \text { of diamonds is missing } \\
= & \frac{{ }^{13} C_{2}}{{ }^{51} C_{2}}=\frac{26}{425}
\end{aligned} \\
& \therefore \quad \begin{aligned}
P\left(E_{1} / E\right)= & \text { probability of the lost card being a spade, given } \\
& \text{ that } 2 \text { spades are drawn from the remaining } \\
& 51 \text { cards } \\
= & \frac{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)}{P\left(E_{1}\right) \cdot P\left(E / E_{1}\right)+P\left(E_{2}\right) \cdot P\left(E / E_{2}\right)+P\left(E_{3}\right) \cdot P\left(E / E_{3}\right)+P\left(E_{4}\right) \cdot P\left(E / E_{4}\right)} \\
= & \frac{\left(\frac{1}{4} \times \frac{22}{425}\right)}{\left(\frac{1}{4} \times \frac{22}{425}\right)+\left(\frac{1}{4} \times \frac{26}{425}\right)+\left(\frac{1}{4} \times \frac{26}{425}\right)+\left(\frac{1}{4} \times \frac{26}{425}\right)} \\
= & \frac{22}{100}=0.22
\end{aligned}
\end{aligned}
$$

Hence, the required probability is 0.22.

---