# Probability

## Introduction

In everyday life, we come across statements such as:

- Most probably it will rain today.
- Chances are high that the price of petrol will go up.
- I doubt that he will win the race.

The words *'most probably'*, *'chances'*, *'doubt'*, etc., show uncertainty or probability of occurrence of an event.

Though probability started with gambling, it is now used extensively in science, commerce, biological sciences, weather forecasting, etc.

---

## History

The origin of the subject can be traced in the correspondence between two French mathematicians **Blaise Pascal** (1623-62) and **Pierre de Fermat** (1601-65). In 1654, a French nobleman and gambler Charles Mere asked Pascal to solve certain dice problems. Pascal solved these problems in collaboration with Fermat.

Dutch scientist **Huygens** (1629-95) wrote the first book on probability.
In 1713, a more comprehensive book was written by **J Bernoulli**.
In 1748, **A De Moivre** published his book 'The Doctrine of Chances'.
In 1812, **Laplace** published his book 'Analytic Theory of Probability'.
In the 20th century, important contributions were made by Russian mathematicians, **A A Markov** and **A N Kolmogorov**.

These days, probability theory is extensively used in various fields.

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Statistics-and-Probability/Probability/class-09-Ch-19-A-BooK-001.jpg)
*Blaise Pascal*

![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-09/Statistics-and-Probability/Probability/class-09-Ch-19-A-BooK-002.jpg)
*Pierre de Fermat*

---

## Some Terms Related to Probability

- **Experiment**: An operation which can produce some well-defined outcomes, is called an experiment. Each outcome is called an **event**.
- **Random Experiment**: An experiment in which all possible outcomes are known and the exact outcome cannot be predicted in advance, is called a random experiment.
- **Trial**: By a trial, we mean performing a random experiment.

---

## Empirical Probability

Suppose we perform an experiment and let $n$ be the total number of trials. The empirical probability of happening of an event $E$ is defined as

$$
P(E) = \frac{\text{number of trials in which the event happened}}{\text{total number of trials}}.
$$

**Remark**: In this chapter, by probability, we shall mean *empirical probability*.

---

## Some Operations and Their Outcomes

#### 1. Tossing a Coin

When we toss a coin, we get either **heads** or **tails**.

#### 2. Tossing Two Coins

When we toss 2 coins, we get:
- 2 heads or 1 head or 0 head.
- 2 tails or 1 tail or 0 tail.

#### 3. Throwing a Die

A die (whose plural is dice) is a cubical solid having six faces, marked as $1, 2, 3, 4, 5, 6$ respectively.
In throwing a die, whatever number comes on the upper face, is called the outcome.

#### 4. Choosing Various Types of Numbers Out of Given Numbers

Suppose counting numbers 1 to 10 are given.
- If $E_1$ is the event of choosing even numbers then the favourable outcomes are $2, 4, 6, 8, 10$.
- If $E_2$ is the event of choosing prime numbers then the favourable outcomes are $2, 3, 5, 7$.

---

## Solved Examples

### Example 1

A coin is tossed 600 times with the frequencies as:
heads: 342 and tails: 258.
If a coin is tossed at random, what is the probability of getting
(i) a head?
(ii) a tail?

#### Solution

Total number of trials $= 600$.
Number of heads $= 342$.
Number of tails $= 258$.

On tossing a coin, let $E_1$ and $E_2$ be the events of getting a head and of getting a tail respectively. Then,

(i) $P(\text{getting a head}) = P(E_1)$
$$
\begin{aligned}
& = \frac{\text{number of heads coming up}}{\text{total number of trials}} \\
& = \frac{342}{600} = \frac{57}{100} = 0.57
\end{aligned}
$$

(ii) $P(\text{getting a tail}) = P(E_2)$
$$
\begin{aligned}
& = \frac{\text{number of tails coming up}}{\text{total number of trials}} \\
& = \frac{258}{600} = \frac{43}{100} = 0.43
\end{aligned}
$$

**Remark**: It may be noted here that $E_1$ and $E_2$ are the only possible outcomes of each trial and $P(E_1) + P(E_2) = (0.57 + 0.43) = 1$.

---

### Example 2

Two coins are tossed simultaneously 400 times, and we get
two heads: 180 times
one head: 148 times
no head: 72 times.
If two coins are tossed at random, what is the probability of getting
(i) 2 heads?
(ii) 1 head?
(iii) 0 head?

#### Solution

Total number of trials $= 400$.
Number of times 2 heads appear $= 180$.
Number of times 1 head appears $= 148$.
Number of times 0 head appears $= 72$.

In a random toss of two coins let $E_1, E_2, E_3$ be the events of getting 2 heads, 1 head and 0 head respectively. Then,

(i) $P(\text{getting 2 heads}) = P(E_1)$
$$
\begin{aligned}
& = \frac{\text{number of times 2 heads appear}}{\text{total number of trials}} \\
& = \frac{180}{400} = \frac{9}{20} = 0.45.
\end{aligned}
$$

(ii) $P(\text{getting 1 head}) = P(E_2)$
$$
\begin{aligned}
& = \frac{\text{number of times 1 head appears}}{\text{total number of trials}} \\
& = \frac{148}{400} = \frac{37}{100} = 0.37
\end{aligned}
$$

(iii) $P(\text{getting 0 head}) = P(E_3)$
$$
\begin{aligned}
& = \frac{\text{number of times no head appears}}{\text{total number of trials}} \\
& = \frac{72}{400} = \frac{18}{100} = 0.18
\end{aligned}
$$

**Remark**: In tossing 2 coins, the only possible outcomes are $E_1, E_2, E_3$, and $P(E_1) + P(E_2) + P(E_3) = 0.45 + 0.37 + 0.18 = 1$.

---

### Example 3

A die is thrown 500 times and the outcomes are noted as given below:

| Outcome   | 1  | 2  | 3  | 4  | 5  | 6   |
| :-------: | :-: | :-: | :-: | :-: | :-: | :---: |
| Frequency | 95 | 80 | 84 | 68 | 70 | 103   |

If a die is thrown at random, find the probability of getting
(i) 1
(ii) 2
(iii) 3
(iv) 4
(v) 5
(vi) 6.

#### Solution

Total number of trials $= 500$.
In a random throw of a die, let $E_1, E_2, E_3, E_4, E_5$ and $E_6$ be the events of getting $1, 2, 3, 4, 5$ and 6 respectively. Then,

(i) $P(\text{getting 1}) = P(E_1) = \frac{\text{number of times 1 appears}}{\text{total number of trials}}$
$$
= \frac{95}{500} = \frac{19}{100} = 0.19.
$$

(ii) $P(\text{getting 2}) = P(E_2) = \frac{\text{number of times 2 appears}}{\text{total number of trials}}$
$$
= \frac{80}{500} = \frac{16}{100} = 0.16.
$$

(iii) $P(\text{getting 3}) = P(E_3) = \frac{\text{number of times 3 appears}}{\text{total number of trials}}$
$$
= \frac{84}{500} = 0.168.
$$

(iv) $P(\text{getting 4}) = P(E_4) = \frac{\text{number of times 4 appears}}{\text{total number of trials}}$
$$
= \frac{68}{500} = 0.136
$$

(v) $P(\text{getting 5}) = P(E_5) = \frac{\text{number of times 5 appears}}{\text{total number of trials}}$
$$
= \frac{70}{500} = \frac{7}{50} = 0.14.
$$

(vi) $P(\text{getting 6}) = P(E_6) = \frac{\text{number of times 6 appears}}{\text{total number of trials}}$
$$
= \frac{103}{500} = 0.206.
$$

**Remark**: In throwing a die, all possible outcomes are $E_1, E_2, E_3, E_4, E_5, E_6$, and $P(E_1) + P(E_2) + P(E_3) + P(E_4) + P(E_5) + P(E_6)$
$= 0.19 + 0.16 + 0.168 + 0.136 + 0.14 + 0.206 = 1$.

---

### Example 4

1500 families with 2 children each, were selected randomly and the following data were recorded.

| Number of girls in a family | 2   | 1   | 0   |
| :-------------------------: | :---: | :---: | :---: |
| Number of families          | 102 | 675 | 723 |

Out of these families, one family is selected at random. What is the probability that the selected family has (i) 2 girls, (ii) 1 girl, (iii) no girl?

#### Solution

Total number of families $= 1500$.
Let $E_1, E_2, E_3$ be the events that the selected family has 2 girls, 1 girl and 0 girl respectively. Then,

(i) $P(\text{selected family has 2 girls})$
$$
= P(E_1) = \frac{\text{number of families having 2 girls}}{\text{total number of families}} = \frac{102}{1500} = 0.068.
$$

(ii) $P(\text{selected family has 1 girl})$
$$
= P(E_2) = \frac{\text{number of families having 1 girl}}{\text{total number of families}} = \frac{675}{1500} = 0.45.
$$

(iii) $P(\text{selected family has 0 girl})$
$$
= P(E_3) = \frac{\text{number of families having 0 girl}}{\text{total number of families}} = \frac{723}{1500} = 0.482.
$$

**Remark**: In the example given above, the only possible outcomes are $E_1, E_2, E_3$, and $P(E_1) + P(E_2) + P(E_3) = 0.068 + 0.45 + 0.482 = 1$.

---

### Example 5

On one page of a telephone directory, there were 200 telephone numbers. The frequency distribution of their unit's digits is given in the following table:

| Unit's digit | 0  | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  |
| :----------: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Frequency    | 22 | 26 | 22 | 22 | 20 | 10 | 14 | 28 | 16 | 20 |

Out of the numbers on the page, a number is chosen at random. What is the probability that the unit's digit of the chosen number is
(i) 6?
(ii) a nonzero multiple of 3?
(iii) a nonzero even number?
(iv) an odd number?

#### Solution

Number of all telephone numbers on the given page $= 200$.

(i) Let $E_1$ be the event of choosing a number with unit's digit 6. Number of such numbers $= 14$.
$$
\begin{aligned}
\therefore P(\text{getting a number with unit's digit 6}) &= P(E_1) \\
&= \frac{\text{number of times 6 appears as unit's digit}}{\text{total number of numbers on the given page}} \\
&= \frac{14}{200} = \frac{7}{100} = 0.07.
\end{aligned}
$$

(ii) Let $E_2$ be the event of choosing a number whose unit's digit is a nonzero multiple of 3.
Each such number has unit's digits 3, 6 or 9.
$\therefore P(\text{getting a number whose unit's digit is a nonzero multiple of 3}) = P(E_2)$
$$
\begin{aligned}
& = \frac{\text{number of numbers with unit's digits 3, 6 or 9}}{\text{total number of numbers on the given page}} \\
& = \frac{22 + 14 + 20}{200} = \frac{56}{200} = 0.28
\end{aligned}
$$

(iii) Let $E_3$ be the event of choosing a number whose unit's digit is a nonzero even number.
Each such number has unit's digits $2, 4, 6$ or 8.
$\therefore P(\text{getting a number whose unit's digit is a nonzero even number}) = P(E_3)$
$$
\begin{aligned}
& = \frac{\text{number of numbers with unit's digits 2, 4, 6 or 8}}{\text{total number of numbers on the given page}} \\
& = \frac{22 + 20 + 14 + 16}{200} = \frac{72}{200} = \frac{36}{100} = 0.36
\end{aligned}
$$

(iv) Let $E_4$ be the event of choosing an odd number.
Each such number has unit's digits 1, 3, 5, 7 or 9.
$\therefore P(\text{getting a number whose unit's digit is an odd number}) = P(E_4)$
$$
= \frac{\text{number of numbers with unit's digits 1, 3, 5, 7 or 9}}{\text{total number of numbers on the given page}}
$$
$$
= \frac{(26 + 22 + 10 + 28 + 20)}{200} = \frac{106}{200} = \frac{53}{100} = 0.53.
$$

---

### Example 6

Fifty seeds were selected at random from each of 5 bags of seeds and were kept under standardised conditions favourable to germination. After 20 days, the number of seeds which had germinated in each collection were counted and recorded as follows:

| Bag                         | 1  | 2  | 3  | 4  | 5  |
| :-------------------------: | :-: | :-: | :-: | :-: | :-: |
| Number of seeds germinated | 40 | 48 | 42 | 39 | 41 |

What is the probability of germination of
(i) more than 40 seeds from a bag?
(ii) 49 seeds from a bag?
(iii) more than 35 seeds from a bag?

#### Solution

Total number of bags $= 5$.

(i) Let $E_1$ be the event of germination of more than 40 seeds from a bag. Then,
$P(\text{germination of more than 40 seeds from a bag}) = P(E_1)$
$$
= \frac{\text{number of bags from which more than 40 seeds germinate}}{\text{total number of bags}}
$$
$$
= \frac{3}{5} = 0.6.
$$
[There are 3 bags from which more than 40 seeds germinate.]

(ii) Let $E_2$ be the event of germination of 49 seeds. Then, $P(\text{germination of 49 seeds from a bag}) = P(E_2)$
$$
= \frac{\text{number of bags from which 49 seeds germinate}}{\text{total number of bags}}
$$
$$
= \frac{0}{5} = 0.
$$
[Clearly, seeds from none of the given bags contain 49 germinated seeds.]

(iii) Let $E_3$ be the event of germination of more than 35 seeds from a bag. Then,
$P(\text{germination of more than 35 seeds from a bag}) = P(E_3)$
$$
= \frac{\text{number of bags from which more than 35 seeds germinate}}{\text{total number of bags}}
$$
$$
= \frac{5}{5} = 1.
$$
[Seeds from each of the five given bags contain more than 35 germinated seeds.]

---

### Example 7

A tyre manufacturing company kept a record of the distance covered before a tyre needed to be replaced. The table given below shows the results of 1000 cases.

| Distance in km | Less than 4000 | 4000 to 9000 | 9001 to 14000 | More than 14000 |
| :------------: | :--------------: | :------------: | :-------------: | :---------------: |
| Frequency      | 20               | 210            | 325             | 445               |

If you buy a tyre of this company, what is the probability that
(i) it will need to be replaced before it has covered 4000 km ?
(ii) it will last more than 9000 km ?
(iii) it will need to be replaced after it has covered somewhere between 4000 km and 14000 km ?

#### Solution

Total number of cases $= 1000$.

(i) Let $E_1$ be the event that a tyre will need to be replaced before covering 4000 km. Number of tyres to be replaced before covering 4000 km $= 20$.
$\therefore P(E_1) = \frac{20}{1000} = 0.02$.

(ii) Let $E_2$ be the event that a tyre will last more than 9000 km.
Number of tyres that will last more than 9000 km $= 325 + 445 = 770$.
$\therefore P(E_2) = \frac{770}{1000} = 0.77$.

(iii) Let $E_3$ be the event that a tyre needs replacement between 4000 km and 14000 km.
Number of tyres which need replacement after covering between 4000 km and $14000 \text{ km} = 210 + 325 = 535$.
$\therefore P(E_3) = \frac{535}{1000} = 0.535$.

---

### Example 8

Bulbs are packed in cartons, each containing 40 bulbs. 700 cartons were examined for defective bulbs and the results are given in the following table:

| Number of defective bulbs | 0   | 1   | 2  | 3  | 4  | 5  | 6 | More than 6 |
| :-----------------------: | :---: | :---: | :-: | :-: | :-: | :-: | :-: | :-----------: |
| Frequency (No. of cartons) | 371 | 162 | 55 | 49 | 41 | 15 | 5 | 2           |

One carton is selected at random. What is the probability that it has
(i) no defective bulb?
(ii) defective bulbs less than 4?
(iii) defective bulbs more than 3 but less than 6?
(iv) defective bulbs 6 or more?

#### Solution

Total number of cartons $= 700$.

(i) Let $E_1$ be the event of choosing a carton having no defective bulb. Then,
$P(\text{choosing a carton having no defective bulb}) = P(E_1)$
$$
= \frac{\text{number of cartons having 0 defective bulb}}{\text{total number of cartons}}
$$
$$
= \frac{371}{700} = \frac{53}{100} = 0.53.
$$

(ii) Let $E_2$ be the event of choosing a carton having defective bulbs less than 4. Then,
$P(\text{choosing a carton having defective bulbs less than 4}) = P(E_2)$
$$
= \frac{\text{number of cartons having defective bulbs 0, 1, 2 or 3}}{\text{total number of cartons}}
$$
$$
= \frac{371 + 162 + 55 + 49}{700} = \frac{637}{700} = \frac{91}{100} = 0.91.
$$

(iii) Let $E_3$ be the event of choosing a carton having defective bulbs more than 3 but less than 6. Then,
$P(\text{choosing a carton having defective bulbs more than 3, but less than 6}) = P(E_3)$
$$
= \frac{\text{number of cartons having defective bulbs 4 or 5}}{\text{total number of cartons}}
$$
$$
= \frac{41 + 15}{700} = \frac{56}{700} = \frac{8}{100} = 0.08.
$$

(iv) Let $E_4$ be the event of choosing a carton having defective bulbs 6 or more. Then,
$P(\text{choosing a carton having defective bulbs 6 or more}) = P(E_4)$
$$
= \frac{\text{number of cartons having defective bulbs 6 or more}}{\text{total number of cartons}}
$$
$$
= \frac{5 + 2}{700} = \frac{7}{700} = \frac{1}{100} = 0.01.
$$

---

### Example 9

Over the past 200 working days, the number of defective parts produced by a machine is given in the following table:

| Number of defective parts | 0  | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9 | 10 | 11 | 12 | 13 |
| :-----------------------: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Number of days            | 50 | 32 | 22 | 18 | 12 | 12 | 10 | 10 | 10 | 8 | 6  | 6  | 2  | 2  |

From these days, one day is chosen at random. What is the probability that on that day, the output has
(i) no defective part?
(ii) at least 1 defective part?
(iii) not more than 5 defective parts?
(iv) more than 5, but less than 8 defective parts?
(v) more than 13 defective parts?

#### Solution

Total number of working days $= 200$.

(i) Let $E_1$ be the event that the output has 0 defective part on the chosen day. Then,
$P(\text{event of producing 0 defective part on the chosen day}) = P(E_1)$
$$
= \frac{\text{number of days when the output has 0 defective part}}{\text{total number of working days}}
$$
$$
= \frac{50}{200} = \frac{1}{4} = 0.25.
$$

(ii) Number of days on which the output has at least 1 defective part
= 200 - number of days with 0 defective part
$= 200 - 50 = 150$.
Let $E_2$ be the event that the output has at least 1 defective part on the chosen day. Then,
$$
P(E_2) = \frac{150}{200} = \frac{3}{4}
$$

(iii) Let $E_3$ be the event that the output has not more than 5 defective parts, i.e., 5 or less defective parts, on the chosen day. Then,
$P(\text{event that the output has not more than 5 defective parts on the chosen day}) = P(\text{event that the output has 5 or less defective parts on the chosen day}) = P(E_3)$
$$
= \frac{\text{number of days when the output has 5 or less defective parts}}{\text{total number of working days}}
$$
$$
= \frac{50+32+22+18+12+12}{200} = \frac{146}{200} = \frac{73}{100} = 0.73
$$

(iv) Let $E_4$ be the event that the output has more than 5, but less than 8 defective parts on the chosen day. Then,
$P(\text{event that the output has more than 5 but less than 8 defective parts on the chosen day}) = P(E_4)$
$$
= \frac{\text{number of days when the output has 6 or 7 defective parts}}{\text{total number of working days}}
$$
$$
= \frac{10+10}{200} = \frac{20}{200} = \frac{1}{10} = 0.1
$$

(v) Let $E_5$ be the event that the output has more than 13 defective parts on that day. Then,
$P(\text{event that the output has more than 13 defective parts on that day}) = P(E_5)$
$$
= \frac{\text{number of days when the output has more than 13 defective parts}}{\text{total number of working days}}
$$
$$
= \frac{0}{200} = 0.
$$

---

### Example 10

The table given below shows the months of birth of 40 students of a class in a school.

| Month of birth | Jan. | Feb. | March | April | May | June | July | Aug. | Sept. | Oct. | Nov. | Dec. |
| :------------: | :--: | :--: | :---: | :---: | :--: | :--: | :--: | :--: | :---: | :--: | :--: | :--: |
| No. of students | 3    | 4    | 2     | 2     | 5    | 1    | 2    | 6    | 3     | 4    | 4    | 4    |

If one student is chosen at random, what is the probability that the student is born
(i) in the latter half of the year?
(ii) in a month having 31 days?
(iii) in a month having 30 days?

#### Solution

Total number of students in the class $= 40$.

(i) Let $E_1$ be the event that the chosen student is born in the latter half of the year. Then,
$$
\begin{aligned}
P(E_1) &= \frac{\text{no. of students born in latter half of the year}}{\text{total number of students}} \\
&= \frac{2+6+3+4+4+4}{40} = \frac{23}{40} = 0.575
\end{aligned}
$$

(ii) Let $E_2$ be the event that the chosen student is born in a month having 31 days. Then,
$$
\begin{aligned}
P(E_2) &= \frac{\text{number of students born in a month having 31 days}}{\text{total number of students}} \\
&= \frac{3+2+5+2+6+4+4}{40} = \frac{26}{40} = \frac{13}{20} = 0.65
\end{aligned}
$$

(iii) Let $E_3$ be the event that the chosen student is born in a month having 30 days. Then,
$$
\begin{aligned}
P(E_3) &= \frac{\text{number of students born in a month having 30 days}}{\text{total number of students}} \\
&= \frac{2+1+3+4}{40} = \frac{10}{40} = \frac{1}{4} = 0.25
\end{aligned}
$$

---

### Example 11

According to a meteorological report for 300 consecutive days in a year, its weather forecasts were correct 180 times.
Out of these days, one day is chosen at random.
What is the probability that the weather forecast was
(i) correct on that day?
(ii) not correct on that day?

#### Solution

Total number of days $= 300$.

(i) Let $E = $ event that the forecast was correct on the chosen day. Then,
$$
\begin{aligned}
P(E) &= \frac{\text{no. of days for which the forecasts were correct}}{\text{total number of days}} \\
&= \frac{180}{300} = \frac{3}{5} = 0.6
\end{aligned}
$$

(ii) Number of days on which the forecast was not correct $= 300 - 180 = 120$.
Let $F = $ event that the forecast was not correct on the given day.
Then, $P(F) = \frac{120}{300} = \frac{2}{5} = 0.4$.

**Remark**: Clearly, $E$ and $F$ are the possible outcomes such that $P(E) + P(F) = 0.6 + 0.4 = 1$.

---

### Example 12

A survey of 250 girls of a school was conducted and it was found that 105 girls like tea while 145 dislike it. Out of these girls, one girl is selected at random.
What is the probability that the selected girl (i) likes tea, (ii) does not like tea?

#### Solution

Total number of girls $= 250$.
Number of girls who like tea $= 105$.
Number of girls who dislike tea $= 145$.

(i) Let $E_1 = $ event that the selected girl likes tea. Then, $P(\text{selected girl likes tea})$
$$
= P(E_1) = \frac{\text{number of girls who like tea}}{\text{total number of girls}} = \frac{105}{250} = 0.42.
$$

(ii) $E_2 = $ event that the selected girl dislikes tea. Then, $P(\text{selected girl dislikes tea})$
$$
= P(E_2) = \frac{\text{number of girls who dislike tea}}{\text{total number of girls}} = \frac{145}{250} = 0.58.
$$

**Remark**: In selecting 1 girl at random, the possible outcomes are $E_1, E_2$, and $P(E_1) + P(E_2) = 0.42 + 0.58 = 1$.

---

### Example 13

In a cricket match, a batsman hits the boundary 5 times out of 40 balls played by him. Find the probability that the boundary is not hit by the ball.

#### Solution

Total number of balls thrown $= 40$.
Number of times, the boundary is hit by the ball $= 5$.
Number of times, the boundary is not hit by the ball $= 40 - 5 = 35$.

Let $E$ be the event that the boundary is not hit by the ball. Then,
$$
\begin{aligned}
P(E) &= \frac{\text{number of times the boundary is not hit by the ball}}{\text{total number of balls thrown}} \\
&= \frac{35}{40} = \frac{7}{8}
\end{aligned}
$$

---

### Example 14

Two dice are thrown simultaneously 500 times. Each time, the sum of the two numbers appearing on their tops is noted and recorded as given below:

| Sum       | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 |
| :-------: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Frequency | 22 | 30 | 48 | 56 | 64 | 70 | 64 | 26 | 53 | 39 | 28 |

If the two dice are thrown once more, what is the probability of getting a sum
(i) 5?
(ii) more than 9?
(iii) less than or equal to 6?
(iv) between 6 and 10?

#### Solution

Total number of times the two dice are thrown $= 500$.

(i) Let $E_1$ be the event of getting the sum 5. Then,
$$
\begin{aligned}
P(\text{getting the sum 5}) &= P(E_1) \\
&= \frac{\text{number of times the sum 5 is obtained}}{\text{total number of times the two dice are thrown}} \\
&= \frac{56}{500} = \frac{14}{125}.
\end{aligned}
$$

(ii) Let $E_2$ be the event of getting a sum more than 9. Then, $E_2 = $ event of getting a sum 10, 11 or 12.
$\therefore P(\text{getting a sum more than 9}) = P(E_2)$
$$
= \frac{\text{number of times a sum 10, 11 or 12 is obtained}}{\text{total number of times the two dice are thrown}}
$$
$$
= \frac{53+39+28}{500} = \frac{110}{500} = \frac{11}{50}.
$$

(iii) Let $E_3$ be the event of getting a sum less than or equal to 6.
Then, $E_3 = $ event of getting a sum 2, 3, 4, 5 or 6.
$$
\begin{aligned}
\therefore P(\text{getting a sum less than or equal to 6}) &= P(E_3) \\
&= \frac{\text{number of times a sum 2, 3, 4, 5 or 6 is obtained}}{\text{total number of times the two dice are thrown}} \\
&= \frac{22+30+48+56+64}{500} = \frac{220}{500} = \frac{11}{25}.
\end{aligned}
$$

(iv) Let $E_4$ be the event of getting the sum between 6 and 10.
Then, $E_4 = $ event of getting a sum 7, 8 or 9.
$$
\begin{aligned}
\therefore P(\text{getting the sum between 6 and 10}) &= P(E_4) \\
&= \frac{\text{number of times a sum 7, 8 or 9 is obtained}}{\text{total number of times the two dice are thrown}} \\
&= \frac{70+64+26}{500} = \frac{160}{500} = \frac{8}{25}.
\end{aligned}
$$

---

### Example 15

A recent survey shows that the ages of 200 workers in a factory is distributed as follows:

| Age (in years)    | 20-29 | 30-39 | 40-49 | 50-59 | 60 and above |
| :---------------: | :---: | :---: | :---: | :---: | :----------: |
| Number of workers | 37    | 28    | 86    | 46    | 3            |

If a worker is selected at random, find the probability that the selected worker is
(i) 40 years or more
(ii) under 40 years
(iii) having an age from 30 to 39 years
(iv) under 60 but over 39 years.

#### Solution

Total number of workers in the factory $= 200$.

(i) Let $E_1$ be the event of selecting a worker who is 40 years or more. Then,
$P(\text{selecting a worker who is 40 years or more}) = P(E_1)$
$$
= \frac{\text{number of workers who are 40 years or more}}{\text{total number of workers}}
$$
$$
= \frac{86+46+3}{200} = \frac{135}{200} = \frac{27}{40}
$$

(ii) Let $E_2$ be the event of selecting a worker who is under 40 years. Then,
$P(\text{selecting a worker who is under 40 years}) = P(E_2)$
$$
= \frac{\text{number of workers having an age less than 40 years}}{\text{total number of workers}}
$$
$$
= \frac{37+28}{200} = \frac{65}{200} = \frac{13}{40}.
$$

(iii) Let $E_3$ be the event of selecting a worker having an age from 30 to 39 years. Then,
$P(\text{selecting a worker having an age from 30 to 39 years}) = P(E_3)$
$$
= \frac{\text{number of workers having age from 30 to 39 years}}{\text{total number of workers}}
$$
$$
= \frac{28}{200} = \frac{7}{50}.
$$

(iv) Let $E_4$ be the event of selecting a worker who is under 60, but over 39 years. Then,
$P(\text{selecting a worker who is under 60 but over 39 years}) = P(E_4)$
$$
= \frac{\text{number of workers having age more than 39 years, but less than 60 years}}{\text{total number of workers}}
$$
$$
= \frac{86+46}{200} = \frac{132}{200} = \frac{33}{50}.
$$

---

### Example 16

Following frequency distribution gives the weights of 40 students of a class.

| Weight (in kg)    | 31-35 | 36-40 | 41-45 | 46-50 | 51-55 | 56-60 | 61-65 | 66-70 | 71-75 |
| :---------------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Number of students | 10    | 6     | 14    | 4     | 1     | 1     | 2     | 1     | 1     |

A student from the class is chosen at random. What is the probability that the weight of the chosen student is
(i) at most 60 kg?
(ii) at least 56 kg?
(iii) not more than 50 kg?

#### Solution

Total number of students $= 40$.

(i) Let $E_1$ be the event of choosing a student whose weight is at most 60 kg. Then,
$P(\text{choosing a student whose weight is at most 60 kg}) = P(E_1)$
$$
= \frac{\text{number of students whose weight is 60 kg or less}}{\text{total number of students}}
$$
$$
= \frac{10+6+14+4+1+1}{40} = \frac{36}{40} = \frac{9}{10}.
$$

(ii) Let $E_2$ be the event of choosing a student whose weight is at least 56 kg. Then,
$P(\text{choosing a student whose weight is at least 56 kg}) = P(E_2)$
$$
= \frac{\text{number of students whose weight is 56 kg or more}}{\text{total number of students}}
$$
$$
= \frac{1+2+1+1}{40} = \frac{5}{40} = \frac{1}{8}.
$$

(iii) Let $E_3$ be the event of choosing a student whose weight is not more than 50 kg. Then,
$P(\text{choosing a student whose weight is not more than 50 kg}) = P(E_3)$
$$
= \frac{\text{number of students whose weight is 50 kg or less}}{\text{total number of students}}
$$
$$
= \frac{10+6+14+4}{40} = \frac{34}{40} = \frac{17}{20}
$$

---

### Example 17

An insurance company selected 2000 drivers at random in a particular city to find a relationship between age and accidents. The data obtained are given in the following table.

| Age of drivers (in years) | \multicolumn{5}{c|}{Accidents in one year}              |
| :-----------------------: | :---: | :---: | :---: | :---: | :------: |
|                           | 0     | 1     | 2     | 3     | Over 3   |
| 18-29                     | 440   | 160   | 110   | 60    | 36       |
| 30-50                     | 505   | 125   | 60    | 22    | 18       |
| Above 50                  | 360   | 45    | 35    | 15    | 9        |

Find the probability of each of the following events for a driver chosen at random from the city:
(i) being 18-29 years of age and having exactly 3 accidents in one year
(ii) being 30-50 years of age and having one or more accidents in one year
(iii) having no accident in one year.

#### Solution

Total number of drivers $= 2000$.

(i) Let $E_1$ be the event of choosing drivers of age 18-29 years with exactly 3 accidents in a year. Then,
$P(\text{choosing drivers of age 18-29 years with exactly 3 accidents in one year}) = P(E_1)$
$$
= \frac{\text{number of drivers of age 18-29 years having exactly 3 accidents in 1 year}}{\text{total number of drivers}}
$$
$$
= \frac{60}{2000} = \frac{3}{100}.
$$

(ii) Let $E_2$ be the event of choosing drivers of age 30-50 years and having one or more accidents in one year. Then,
$P(\text{choosing drivers of age 30-50 years with 1 or more accidents in 1 year}) = P(E_2)$
$$
= \frac{\text{number of drivers of age 30-50 years with 1 or more accidents in 1 year}}{\text{total number of drivers}}
$$
$$
= \frac{125+60+22+18}{2000} = \frac{225}{2000} = \frac{9}{80}.
$$

(iii) Let $E_3$ be the event of choosing drivers having no accident in 1 year. Then,
$P(\text{choosing drivers having no accident in 1 year}) = P(E_3)$
$$
= \frac{\text{number of drivers having no accident in 1 year}}{\text{total number of drivers}}
$$
$$
= \frac{440+505+360}{2000} = \frac{1305}{2000} = \frac{261}{400}.
$$

---

### Example 18

The table given below shows the marks obtained by 80 students of a class in a test with maximum marks 100.

| Marks              | 0-15 | 15-30 | 30-45 | 45-60 | 60-75 | Above 75 |
| :----------------: | :--: | :---: | :---: | :---: | :---: | :------: |
| Number of students | 6    | 13    | 17    | 24    | 16    | 4        |

A student of the class is selected at random.
Find the probability that he gets
(i) less than $15\%$ marks,
(ii) 60 or more marks and
(iii) less than 45 marks.

**Note**: Here 15-30 means 15 and more but less than 30.

#### Solution

Total number of students $= 80$.

(i) $P(\text{The student gets less than 15% marks})$
$$
= \frac{\text{number of students getting less than 15 marks}}{\text{total number of students}}
$$
$$
= \frac{6}{80} = \frac{3}{40}.
$$

(ii) $P(\text{The student gets 60 or more marks})$
$$
= \frac{\text{number of students getting 60 or more marks}}{\text{total number of students}}
$$
$$
= \frac{16+4}{80} = \frac{20}{80} = \frac{1}{4}
$$

(iii) $P(\text{The student gets less than 45 marks})$
$$
= \frac{\text{number of students getting less than 45 marks}}{\text{total number of students}}
$$
$$
= \frac{6+13+17}{80} = \frac{36}{80} = \frac{9}{20}
$$

---

