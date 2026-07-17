## Practical Problems on Combinations

---

## Solved Examples

### Example 1:

In how many ways can a cricket eleven be chosen out of a batch of 15 players, if
(i) there is no restriction on the selection?
(ii) a particular player is **always chosen**?
(iii) a particular player is **never chosen**?

#### Solution:

(i) Total number of ways of selecting 11 players out of 15

$$
= { }^{15} C_{11} = { }^{15} C_{15-11} = { }^{15} C_{4} = \frac{15 \times 14 \times 13 \times 12}{4 \times 3 \times 2 \times 1} = 1365.
$$

(ii) When a particular player is **always chosen**, then we will have to choose 10 players out of the remaining 14.
$\therefore$ required number of ways

$$
= { }^{14} C_{10} = { }^{14} C_{14-10} = { }^{14} C_{4} = \frac{14 \times 13 \times 12 \times 11}{4 \times 3 \times 2 \times 1} = 1001.
$$

(iii) When a particular player is **never chosen**, then we will have to choose 11 players out of the remaining 14.
$\therefore$ required number of ways

$$
= { }^{14} C_{11} = { }^{14} C_{14-11} = { }^{14} C_{3} = \frac{14 \times 13 \times 12}{3 \times 2 \times 1} = 364.
$$

---

### Example 2:

In how many ways can a committee of 5 members be selected from 6 men and 5 ladies, consisting of **3 men and 2 ladies**?

#### Solution:

We have to select (**3 men out of 6**) and (**2 ladies out of 5**).
$\therefore$ required number of ways

$$
= \left({ }^{6} C_{3} \times{ }^{5} C_{2}\right) = \left(\frac{6 \times 5 \times 4}{3 \times 2 \times 1} \times \frac{5 \times 4}{2 \times 1}\right) = (20 \times 10) = 200.
$$

---

### Example 3:

Out of 5 men and 2 women, a committee of 3 is to be formed. In how many ways can it be formed if **at least one woman** is to be included?

#### Solution:

The committee can be formed by choosing:
(i) 1 woman and 2 men;
or (ii) 2 women and 1 man.

Now, the number of ways of choosing (**1 woman out of 2**) and (**2 men out of 5**)

$$
= \left({ }^{2} C_{1} \times{ }^{5} C_{2}\right) = \left(2 \times \frac{5 \times 4}{2 \times 1}\right) = (2 \times 10) = 20.
$$

And, the number of ways of choosing (**2 women out of 2**) and (**1 man out of 5**)

$$
= \left({ }^{2} C_{2} \times{ }^{5} C_{1}\right) = (1 \times 5) = 5.
$$

Hence, the total number of ways of forming the committee

$$
= (20 + 5) = 25.
$$

---

### Example 4:

A committee of 5 is to be formed out of 6 men and 4 ladies. In how many ways can this be done, when
(a) **at least 2 ladies** are included;
(b) **at most 2 ladies** are included?

#### Solution:

(a) We have to make a selection of:
- (i) (**2 ladies out of 4**) and (**3 men out of 6**)
- or (ii) (**3 ladies out of 4**) and (**2 men out of 6**)
- or (iii) (**4 ladies out of 4**) and (**1 man out of 6**).

The number of ways of these selections are:
- **Case I:** ${ }^{4} C_{2} \times{ }^{6} C_{3} = 6 \times 20 = 120$.
- **Case II:** ${ }^{4} C_{3} \times{ }^{6} C_{2} = 4 \times 15 = 60$.
- **Case III:** ${ }^{4} C_{4} \times{ }^{6} C_{1} = 1 \times 6 = 6$.

Hence, the required number of ways $= (120 + 60 + 6) = 186$.

(b) We have to make a selection of:
- (i) (**1 lady out of 4**) and (**4 men out of 6**)
- or (ii) (**2 ladies out of 4**) and (**3 men out of 6**).

The number of ways of these selections are:
- **Case I:** ${ }^{4} C_{1} \times{ }^{6} C_{4} = 4 \times 15 = 60$.
- **Case II:** ${ }^{4} C_{2} \times{ }^{6} C_{3} = 6 \times 20 = 120$.

Hence, the required number of ways $= (60 + 120) = 180$.

---

### Example 5:

An examination paper containing 12 questions consists of two parts, **A** and **B**. Part **A** contains 7 questions and part **B** contains 5 questions. A candidate is required to attempt 8 questions, selecting **at least 3 from each part**. In how many ways can the candidate select the questions?

#### Solution:

Clearly, the candidate may select the questions as under:
- (i) (**3 out of 7 from A**) and (**5 out of 5 from B**)
- or (ii) (**4 out of 7 from A**) and (**4 out of 5 from B**)
- or (iii) (**5 out of 7 from A**) and (**3 out of 5 from B**).

The number of ways of these selections are:
- **Case I:** ${ }^{7} C_{3} \times{ }^{5} C_{5} = 35 \times 1 = 35$.
- **Case II:** ${ }^{7} C_{4} \times{ }^{5} C_{4} = 35 \times 5 = 175$.
- **Case III:** ${ }^{7} C_{5} \times{ }^{5} C_{3} = 21 \times 10 = 210$.

Hence, the required number of ways $= (35 + 175 + 210) = 420$.

---

### Example 6:

For the post of 5 teachers, there are 23 applicants. 2 posts are reserved for SC candidates and there are 7 SC candidates among the applicants. In how many ways can the selection be made?

#### Solution:

Clearly, there are 7 SC candidates and 16 non-SC candidates.
So, we have to make a selection of (**2 out of 7**) and (**3 out of 16**).

Hence, the number of ways of making the selection

$$
= { }^{7} C_{2} \times{ }^{16} C_{3} = \left(\frac{7 \times 6}{2} \times \frac{16 \times 15 \times 14}{3 \times 2 \times 1}\right) = 11760.
$$

---

### Example 7:

How many diagonals are there in a polygon of $n$ sides?

#### Solution:

A polygon of $n$ sides has $n$ vertices. By joining any two of these vertices, we obtain either a side or a diagonal of the polygon.

Number of all straight lines obtained by joining 2 vertices at a time $= { }^{n} C_{2} = \frac{1}{2} n(n-1)$.
These straight lines include $n$ sides of the polygon.

Hence, the number of diagonals of the polygon

$$
= \left[\frac{1}{2} n(n-1) - n\right] = \frac{1}{2} n(n-3).
$$

---

### Example 8:

There are 10 points in a plane, no three of which are in the same straight line, except 4 points, which are collinear. Find:
(i) the number of lines obtained from the pairs of these points;
(ii) the number of triangles that can be formed with vertices as these points.

#### Solution:

(i) Number of lines formed by joining the 10 points, taking 2 at a time

$$
= { }^{10} C_{2} = \left(\frac{10 \times 9}{2 \times 1}\right) = 45.
$$

Number of lines formed by joining the 4 points, taking 2 at a time

$$
= { }^{4} C_{2} = \left(\frac{4 \times 3}{2 \times 1}\right) = 6.
$$

But, 4 collinear points, when joined pairwise, give only 1 line. Hence, the required number of straight lines

$$
= (45 - 6 + 1) = 40.
$$

(ii) Number of triangles formed by 10 points, taking 3 at a time

$$
= { }^{10} C_{3} = \frac{10 \times 9 \times 8}{3 \times 2 \times 1} = 120.
$$

Number of triangles formed by 4 points, taking 3 at a time

$$
= { }^{4} C_{3} = { }^{4} C_{4-3} = { }^{4} C_{1} = 4.
$$

But, these 4 points being collinear, no triangle is formed. Hence, the required number of triangles $= (120 - 4) = 116$.

---

### Example 9:

A box contains 6 red and 5 white balls. In how many ways can 6 balls be selected so that there are **at least two balls of each colour**?

#### Solution:

We may select:
- (i) (**2 red balls out of 6**) and (**4 white balls out of 5**)
- or (ii) (**3 red balls out of 6**) and (**3 white balls out of 5**)
- or (iii) (**4 red balls out of 6**) and (**2 white balls out of 5**).

The number of ways of these selections are:
- **Case I:** $\left({ }^{6} C_{2} \times{ }^{5} C_{4}\right) = \left({ }^{6} C_{2} \times{ }^{5} C_{1}\right) = \left(\frac{6 \times 5}{2} \times 5\right) = 75$.
- **Case II:** $\left({ }^{6} C_{3} \times{ }^{5} C_{3}\right) = \left({ }^{6} C_{3} \times{ }^{5} C_{2}\right) = \left(\frac{6 \times 5 \times 4}{3 \times 2 \times 1} \times \frac{5 \times 4}{2 \times 1}\right) = 200$.
- **Case III:** $\left({ }^{6} C_{4} \times{ }^{5} C_{2}\right) = \left({ }^{6} C_{2} \times{ }^{5} C_{2}\right) = \left(\frac{6 \times 5}{2 \times 1} \times \frac{5 \times 4}{2 \times 1}\right) = 150$.

Hence, the required number of ways $= (75 + 200 + 150) = 425$.

---

### Example 10:

How many committees of 5 persons with a chairperson can be selected from 12 persons?

#### Solution:

Number of ways of selecting a chairperson out of 12 persons

$$
= { }^{12} C_{1} = 12.
$$

Number of ways of selecting 4 persons out of remaining 11

$$
= { }^{11} C_{4} = \frac{11 \times 10 \times 9 \times 8}{4 \times 3 \times 2 \times 1} = 330.
$$

Hence, the required number of ways $= (12 \times 330) = 3960$.

---

### Example 11:

A box contains 3 black, 2 white and 4 red balls. In how many ways can 3 balls be drawn from the box, if **at least one black ball** is to be included in the draw?

#### Solution:

In all, we have 3 black and 6 non-black balls. We may select:
- (i) (**1 black ball out of 3**) and (**2 non-black balls out of 6**)
- or (ii) (**2 black balls out of 3**) and (**1 non-black ball out of 6**)
- or (iii) (**3 black balls out of 3**).

The number of ways of these selections are:
- **Case I:** $\left({ }^{3} C_{1} \times{ }^{6} C_{2}\right) = \left(3 \times \frac{6 \times 5}{2 \times 1}\right) = 45$.
- **Case II:** $\left({ }^{3} C_{2} \times{ }^{6} C_{1}\right) = \left({ }^{3} C_{1} \times{ }^{6} C_{1}\right) = (3 \times 6) = 18$.
- **Case III:** ${ }^{3} C_{3} = 1$. (Note: The original text has an error, $3! = 6$ is incorrect for ${}^3C_3$)

Hence, the required number of ways $= (45 + 18 + 1) = 64$.

---

### Example 12:

A group consists of 7 boys and 4 girls. In how many ways can a team of 5 members be selected, if the team has:
(i) no girls?
(ii) at least 1 boy and 1 girl?
(iii) at least 3 girls?

#### Solution:

(i) **When no girl is taken:**
Then, we have to select 5 boys out of 7.
$\therefore$ required number of ways

$$
= { }^{7} C_{5} = { }^{7} C_{7-5} = { }^{7} C_{2} = \frac{7 \times 6}{2 \times 1} = 21.
$$

(ii) **When at least 1 boy and 1 girl are taken:**
In this case, we may choose:
- (**1 boy and 4 girls**) or (**2 boys and 3 girls**)
- or (**3 boys and 2 girls**) or (**4 boys and 1 girl**).

$\therefore$ required number of ways
$$
\begin{aligned}
& = \left({ }^{7} C_{1} \times{ }^{4} C_{4}\right) + \left({ }^{7} C_{2} \times{ }^{4} C_{3}\right) + \left({ }^{7} C_{3} \times{ }^{4} C_{2}\right) + \left({ }^{7} C_{4} \times{ }^{4} C_{1}\right) \\
& = (7 \times 1) + \left({ }^{7} C_{2} \times{ }^{4} C_{1}\right) + \left({ }^{7} C_{3} \times{ }^{4} C_{2}\right) + \left({ }^{7} C_{3} \times{ }^{4} C_{1}\right) \\
& = 7 + \left(\frac{7 \times 6}{2 \times 1} \times 4\right) + \left(\frac{7 \times 6 \times 5}{3 \times 2 \times 1} \times \frac{4 \times 3}{2 \times 1}\right) + \left(\frac{7 \times 6 \times 5}{3 \times 2 \times 1} \times 4\right) \\
& = (7 + 84 + 210 + 140) = 441
\end{aligned}
$$

(iii) **When at least 3 girls are taken:**
Then, we may choose:
- (**3 girls and 2 boys**) or (**4 girls and 1 boy**).

$\therefore$ required number of ways
$$
\begin{aligned}
& = \left({ }^{4} C_{3} \times{ }^{7} C_{2}\right) + \left({ }^{4} C_{4} \times{ }^{7} C_{1}\right) \\
& = \left({ }^{4} C_{1} \times{ }^{7} C_{2}\right) + \left(1 \times{ }^{7} C_{1}\right) = \left(4 \times \frac{7 \times 6}{2 \times 1}\right) + (1 \times 7) \\
& = (84 + 7) = 91
\end{aligned}
$$

---

### Example 13:

A bag contains 6 white marbles and 5 red marbles. Find the number of ways in which 4 marbles can be drawn from the bag, if:
(a) they can be of any colour;
(b) 2 must be white and 2 red;
(c) they must all be of the same colour.

#### Solution:

(a) **Drawing 4 marbles of any colour:**
Total number of marbles $= (6 + 5) = 11$. In this case, we have to draw 4 marbles out of 11.
$\therefore$ required number of ways

$$
= { }^{11} C_{4} = \frac{11 \times 10 \times 9 \times 8}{4 \times 3 \times 2 \times 1} = 330.
$$

(b) **Drawing 2 white and 2 red marbles:**
We may draw (**2 white marbles out of 6**) and (**2 red marbles out of 5**).
$\therefore$ required number of ways

$$
= \left({ }^{6} C_{2} \times{ }^{5} C_{2}\right) = \left(\frac{6 \times 5}{2 \times 1} \times \frac{5 \times 4}{2 \times 1}\right) = (15 \times 10) = 150.
$$

(c) **Drawing 4 marbles of the same colour:**
We may draw (**4 white marbles out of 6**) or (**4 red marbles out of 5**).
$\therefore$ required number of ways

$$
= \left({ }^{6} C_{4} + { }^{5} C_{4}\right) = \left({ }^{6} C_{2} + { }^{5} C_{1}\right) = \left(\frac{6 \times 5}{2 \times 1} + 5\right) = 20.
$$

---

### Example 14:

We wish to select 6 persons from 8, but if the person **A is chosen, then B must be chosen**. In how many ways can the selection be made?

#### Solution:

We have two cases: (either **A is chosen**) or (**A is not chosen**).

- **Case I: When A is chosen:**
In this case, A is chosen and B is chosen. So, we must choose 4 persons out of the remaining 6.
$\therefore$ required number of ways $= { }^{6} C_{4} = { }^{6} C_{2} = \frac{6 \times 5}{2 \times 1} = 15$.

- **Case II: When A is not chosen:**
In this case, we have to choose 6 persons out of 7.
$\therefore$ required number of ways $= { }^{7} C_{6} = { }^{7} C_{1} = 7$.

Combining both cases, the total number of ways $= (15 + 7) = 22$.

---

### Example 15:

Find the number of ways of choosing 4 cards from a pack of 52 playing cards. In how many of these:
(i) 4 cards are of the **same suit**?
(ii) 4 cards belong to **four different suits**?
(iii) 4 cards are **face cards**?
(iv) 2 are **red cards** and 2 are **black cards**?
(v) cards are of the **same colour**?

#### Solution:

Number of ways of choosing 4 cards out of 52:

$$
= { }^{52} C_{4} = \frac{52 \times 51 \times 50 \times 49}{4 \times 3 \times 2 \times 1} = 270725.
$$

(i) **Choosing 4 cards of the same suit:**
We have to draw (**4 cards from diamonds**) or (**4 from spades**) or (**4 from clubs**) or (**4 from hearts**).
$\therefore$ required number of ways

$$
\begin{aligned}
& = \left({ }^{13} C_{4} + { }^{13} C_{4} + { }^{13} C_{4} + { }^{13} C_{4}\right) = 4 \times{ }^{13} C_{4} \\
& = \frac{4 \times 13 \times 12 \times 11 \times 10}{4 \times 3 \times 2 \times 1} = 2860.
\end{aligned}
$$

(ii) **Choosing 4 cards from 4 different suits:**
We have to draw (**1 from diamonds**) and (**1 from spades**) and (**1 from clubs**) and (**1 from hearts**).
$\therefore$ required number of ways

$$
= \left({ }^{13} C_{1} \times{ }^{13} C_{1} \times{ }^{13} C_{1} \times{ }^{13} C_{1}\right) = (13 \times 13 \times 13 \times 13) = (13)^{4}.
$$

(iii) **Choosing 4 cards out of 12 face cards:**
We have to choose 4 cards out of 12 face cards.
$\therefore$ required number of ways

$$
= { }^{12} C_{4} = \frac{12 \times 11 \times 10 \times 9}{4 \times 3 \times 2 \times 1} = 495.
$$

(iv) **Choosing 2 red cards and 2 black cards:**
We have to choose 2 red cards out of 26 and 2 black cards out of 26.
$\therefore$ required number of ways

$$
= \left({ }^{26} C_{2} \times{ }^{26} C_{2}\right) = \left(\frac{26 \times 25}{2}\right)^{2} = (325 \times 325) = 105625.
$$

(v) **Choosing all 4 cards of the same colour:**
We have to choose (**4 cards out of 26 black cards**) or (**4 cards out of 26 red cards**).
$\therefore$ required number of ways

$$
\begin{aligned}
& = \left({ }^{26} C_{4} + { }^{26} C_{4}\right) = \left(2 \times{ }^{26} C_{4}\right) = \left(2 \times \frac{26 \times 25 \times 24 \times 23}{4 \times 3 \times 2 \times 1}\right) \\
& = 29900.
\end{aligned}
$$

---

### Example 16:

From a class of 25 students, 10 are to be chosen for an excursion party. There are 3 students who decide that **either all of them will join or none of them will join**. In how many ways can they be chosen?

#### Solution:

Either 3 particular students join or none of them joins.

- **Case I: When 3 particular students join the party:**
In this case, we have to choose 7 more students from the remaining 22. This can be done in ${ }^{22} C_{7}$ ways.

- **Case II: When 3 particular students do not join the party:**
In this case, we have to choose all 10 students from the remaining 22. This can be done in ${ }^{22} C_{10}$ ways.

Hence, the required number of ways $= \left({ }^{22} C_{7} + { }^{22} C_{10}\right) = 170544 + 646646 = 817190$.

---

### Example 17:

A boy has 3 library tickets and 8 books of his interest in the library. Of these 8, he does not want to borrow **Mathematics Part II, unless Mathematics Part I is also borrowed**. In how many ways can he choose the 3 books to be borrowed?

#### Solution:

Clearly, the boy may borrow Mathematics Part II or he may not borrow it.

- **Case I: When the boy borrows Mathematics Part II:**
In this case, he must also borrow Mathematics Part I. Since he has 3 library tickets in all, he may now borrow 1 more book out of the remaining 6 books. This can be done in ${ }^{6} C_{1} = 6$ ways.

- **Case II: When the boy does not borrow Mathematics Part II:**
Then, he may borrow any 3 books out of the remaining 7 books. This can be done in ${ }^{7} C_{3} = \frac{7 \times 6 \times 5}{3 \times 2 \times 1} = 35$ ways.

Hence, the required number of ways $= (6 + 35) = 41$.

---

### Example 18:

A convex polygon has 44 diagonals. Find the number of its sides.

#### Solution:

Let the given convex polygon have $n$ sides. Then, the number of its diagonals $= \left({ }^{n} C_{2} - n\right)$.

Now, ${ }^{n} C_{2} - n = 44 \Rightarrow \frac{n(n-1)}{2} - n = 44$
$$
\begin{aligned}
& \Rightarrow n^{2} - n - 2n = 88 \\
& \Rightarrow n^{2} - 3n - 88 = 0 \\
& \Rightarrow (n-11)(n+8) = 0 \\
& \Rightarrow n = 11 \quad [\because n \neq -8].
\end{aligned}
$$

Hence, the given polygon has 11 sides.

---

### Example 19:

If $m$ parallel lines in a plane are intersected by a family of $n$ parallel lines, find the number of parallelograms formed.

#### Solution:

A parallelogram is formed by choosing two straight lines from the set of $m$ parallel lines and two straight lines from the set of $n$ parallel lines.

- Number of ways of choosing 2 lines out of $m$ parallel lines $= { }^{m} C_{2}$.
- Number of ways of choosing 2 lines out of $n$ parallel lines $= { }^{n} C_{2}$.

Hence, the required number of parallelograms formed

$$
= \left({ }^{m} C_{2} \times{ }^{n} C_{2}\right) = \frac{m(m-1)}{2} \times \frac{n(n-1)}{2} = \frac{m n(m-1)(n-1)}{4}.
$$

---

### Example 20:

In an examination, a candidate has to pass in each of the 5 subjects. In how many ways can he fail?

#### Solution:

The candidate can fail by failing in **1 or 2 or 3 or 4 or 5 subjects** out of 5 in each case.
$\therefore$ the total number of ways in which he can fail

$$
\begin{aligned}
& = { }^{5} C_{1} + { }^{5} C_{2} + { }^{5} C_{3} + { }^{5} C_{4} + { }^{5} C_{5} \\
& = { }^{5} C_{1} + { }^{5} C_{2} + { }^{5} C_{2} + { }^{5} C_{1} + { }^{5} C_{5} \quad [\because { }^{n} C_{r} = { }^{n} C_{n-r}] \\
& = (5 + 10 + 10 + 5 + 1) = 31
\end{aligned}
$$

---

### Example 21:

Determine the number of 5-card combinations out of a deck of 52 cards if there is **exactly one ace** in each combination.

#### Solution:

- Number of ways of selecting 1 ace out of 4 aces $= { }^{4} C_{1} = 4$.
- Number of ways of selecting 4 cards out of the remaining 48 non-ace cards

$$
= { }^{48} C_{4} = \frac{48 \times 47 \times 46 \times 45}{4 \times 3 \times 2 \times 1} = 194580.
$$

Hence, the required number of combinations

$$
= (194580 \times 4) = 778320.
$$

---

### Example 22:

In how many ways can one select a cricket team of eleven from 17 players in which only 5 players can bowl, if each cricket team of 11 must include **exactly 4 bowlers**?

#### Solution:

- Number of ways of selecting 4 bowlers out of 5:
$$
= { }^{5} C_{4} = { }^{5} C_{(5-4)} = { }^{5} C_{1} = 5.
$$

- Number of ways of selecting 7 batsmen out of the remaining 12 players:
$$
= { }^{12} C_{7} = { }^{12} C_{(12-7)} = { }^{12} C_{5} = \frac{12 \times 11 \times 10 \times 9 \times 8}{5 \times 4 \times 3 \times 2 \times 1} = 792.
$$

Hence, the number of ways of selecting the team $= (5 \times 792) = 3960$.

---

### Example 23:

A committee of 12 persons is to be formed from 9 women and 8 men. In how many ways can this be done if **at least 5 women** have to be included in a committee? In how many of these committees are (a) the women in majority? (b) the men in majority?

#### Solution:

There are 9 women and 8 men in all. In order to form a committee consisting of at least 5 women, we may choose:
- (i) **5 women and 7 men**
- or (ii) **6 women and 6 men**
- or (iii) **7 women and 5 men**
- or (iv) **8 women and 4 men**
- or (v) **9 women and 3 men**.

Hence, the total number of ways of forming the committee:
$$
= \left({ }^{9} C_{5} \times{ }^{8} C_{7}\right) + \left({ }^{9} C_{6} \times{ }^{8} C_{6}\right) + \left({ }^{9} C_{7} \times{ }^{8} C_{5}\right) + \left({ }^{9} C_{8} \times{ }^{8} C_{4}\right) + \left({ }^{9} C_{9} \times{ }^{8} C_{3}\right)
$$
$$
\begin{aligned}
= & \left({ }^{9} C_{4} \times{ }^{8} C_{1}\right) + \left({ }^{9} C_{3} \times{ }^{8} C_{2}\right) + \left({ }^{9} C_{2} \times{ }^{8} C_{3}\right) + \left({ }^{9} C_{1} \times{ }^{8} C_{4}\right) + \left(1 \times{ }^{8} C_{3}\right) \\
= & \left\{\frac{9 \times 8 \times 7 \times 6}{4 \times 3 \times 2 \times 1} \times 8\right\} + \left\{\frac{9 \times 8 \times 7}{3 \times 2 \times 1} \times \frac{8 \times 7}{2 \times 1}\right\} + \left\{\frac{9 \times 8}{2 \times 1} \times \frac{8 \times 7 \times 6}{3 \times 2 \times 1}\right\} \\
& + \left\{9 \times \frac{8 \times 7 \times 6 \times 5}{4 \times 3 \times 2 \times 1}\right\} + \left(1 \times \frac{8 \times 7 \times 6}{3 \times 2 \times 1}\right) \\
= & (126 \times 8) + (84 \times 28) + (36 \times 56) + (9 \times 70) + (56) \\
= & (1008 + 2352 + 2016 + 630 + 56) = 6062.
\end{aligned}
$$

(a) Clearly, the **women are in majority** in cases (iii), (iv), and (v). So, the number of committees in which the women are in majority:
$$
\begin{aligned}
& = \left({ }^{9} C_{7} \times{ }^{8} C_{5}\right) + \left({ }^{9} C_{8} \times{ }^{8} C_{4}\right) + \left({ }^{9} C_{9} \times{ }^{8} C_{3}\right) \\
& = \left({ }^{9} C_{2} \times{ }^{8} C_{3}\right) + \left({ }^{9} C_{1} \times{ }^{8} C_{4}\right) + \left(1 \times{ }^{8} C_{3}\right) \\
& = (2016 + 630 + 56) = 2702.
\end{aligned}
$$

(b) Clearly, the **men are in majority** in case (i) only. So, the number of committees in which the men are in majority:
$$
= \left({ }^{9} C_{5} \times{ }^{8} C_{7}\right) = \left({ }^{9} C_{4} \times{ }^{8} C_{1}\right) = \left(\frac{9 \times 8 \times 7 \times 6}{4 \times 3 \times 2 \times 1} \times 8\right) = 1008.
$$

---

### Example 24:

In a village, there are 87 families of which 52 families have at most 2 children. In a rural development programme, 20 families are to be chosen for assistance, of which **at least 18 families must have at most 2 children**. In how many ways can the choice be made?

#### Solution:

It is given that 52 families have at most 2 children and $(87 - 52) = 35$ families have more than 2 children.
We have to select 20 families of which **at least 18** must have at most 2 children. The selection can be made as under:
- (i) **18 families out of 52** and **2 families out of 35**
- or (ii) **19 families out of 52** and **1 family out of 35**
- or (iii) **20 families out of 52**.

So, the number of ways in which these choices can be made:

$$
= \left({ }^{52} C_{18} \times{ }^{35} C_{2}\right) + \left({ }^{52} C_{19} \times{ }^{35} C_{1}\right) + \left({ }^{52} C_{20}\right).
$$

---

### Example 25:

In how many ways can 19 identical books on English and 17 identical books on Hindi be placed in a row on a shelf so that **two books on Hindi may not be together**?

#### Solution:

In order that two books on Hindi are never together, we must place these books in the gaps between the English books.
`X E X E X E X ... X E X`,
where `E` denotes the position of an English book and `X` that of a Hindi book.

Since there are 19 books on English, there are 20 possible places (gaps) for the Hindi books (19 gaps between them and 2 at the ends).

Since all books on English are identical, they can be placed in only 1 way at the places marked `E`.
The number of ways of placing 17 identical books on Hindi at the 20 available places, marked `X` is:
$$
{ }^{20} C_{17} = { }^{20} C_{3} = \frac{20 \times 19 \times 18}{3 \times 2 \times 1} = 1140.
$$
Hence, the required number of ways $= (1 \times 1140) = 1140$.

---

