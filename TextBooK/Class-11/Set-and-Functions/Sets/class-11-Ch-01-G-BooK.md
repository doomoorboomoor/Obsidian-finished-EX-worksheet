## Some Results Derived from Venn Diagrams

### Result 1
When *$A$* and *$B$* are **disjoint sets**, then we have

$$
n(A \cup B) = n(A) + n(B)
$$

![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-37.jpg?height=224&width=354&top_left_y=475&top_left_x=841)

---

### Result 2
For any sets *$A$* and *$B$*, prove that

$$
n(A \cup B) = n(A) + n(B) - n(A \cap B)
$$

**PROOF:** From the given Venn diagram, it is clear that the sets $(A-B)$, $(A \cap B)$ and $(B-A)$ are disjoint and their union is $(A \cup B)$.

![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-37.jpg?height=245&width=358&top_left_y=720&top_left_x=837)

$$
\begin{aligned}
\therefore \quad n(A \cup B) &= n(A-B) + n(A \cap B) + n(B-A) \\
&= n(A-B) + n(A \cap B) + n(B-A) + n(A \cap B) - n(A \cap B)
\end{aligned}
$$

*\[adding and subtracting $n(A \cap B)$]*

$$
= n(A) + n(B) - n(A \cap B)
$$

*\[$\because n(A-B) + n(A \cap B) = n(A)$ and $n(B-A) + n(A \cap B) = n(B)$]*

Hence, $n(A \cup B) = n(A) + n(B) - n(A \cap B)$.

#### Corollary 1
Prove that $n(A-B) + n(A \cap B) = n(A)$.

**PROOF:** Clearly, $(A-B)$ and $(A \cap B)$ are disjoint sets and their union is *$A$*.

$$
\therefore \quad n(A-B) + n(A \cap B) = n(A)
$$

#### Corollary 2
Prove that $n(B-A) + n(A \cap B) = n(B)$.

**PROOF:** Clearly, $(B-A)$ and $(A \cap B)$ are disjoint sets whose union is *$B$*.

$$
\therefore \quad n(B-A) + n(A \cap B) = n(B)
$$

---

### Result 3
For any sets *$A, B, C$* prove that

$$
\begin{aligned}
n(A \cup B \cup C) = [n(A) + n(B) + n(C) + n(A \cap B \cap C)] \\
- [n(A \cap B) + n(B \cap C) + n(A \cap C)]
\end{aligned}
$$

**PROOF:** We have

$$
\begin{aligned}
n(A \cup B \cup C) &= n[(A \cup B) \cup C] \\
&= n(A \cup B) + n(C) - n[(A \cup B) \cap C] \\
&= \{n(A) + n(B) - n(A \cap B)\} + n(C) - n[(A \cap C) \cup (B \cap C)] \\
&= \{n(A) + n(B) + n(C) - n(A \cap B)\} - \{n(A \cap C) + n(B \cap C) - n(A \cap C \cap B \cap C)\} \\
&= n(A) + n(B) + n(C) - n(A \cap B) - n(A \cap C) - n(B \cap C) + n(A \cap B \cap C) \\
&= \{n(A) + n(B) + n(C) + n(A \cap B \cap C)\} - \{n(A \cap B) + n(B \cap C) + n(A \cap C)\}
\end{aligned}
$$

Hence, the result follows.

---

## Summary

For any sets *$A, B, C$* we have:
- **(i)** $n(A \cup B) = n(A) + n(B) - n(A \cap B)$.
- **(ii)** If $A \cap B = \phi$, then $n(A \cup B) = n(A) + n(B)$.
- **(iii)** $n(A-B) + n(A \cap B) = n(A)$.
- **(iv)** $n(B-A) + n(A \cap B) = n(B)$.
- **(v)** $n(A \cup B \cup C) = \{n(A) + n(B) + n(C) + n(A \cap B \cap C)\} - \{n(A \cap B) + n(B \cap C) + n(A \cap C)\}$

![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-38.jpg?height=248&width=361&top_left_y=447&top_left_x=813)

---

## Solved Examples

### Example 1:

If *$A$* and *$B$* are two sets such that $n(A) = 27$, $n(B) = 35$ and $n(A \cup B) = 50$, find $n(A \cap B)$.

#### Solution:

We know that
$$
n(A \cup B) = n(A) + n(B) - n(A \cap B)
$$
$$
\Rightarrow \quad n(A \cap B) = n(A) + n(B) - n(A \cup B) = (27 + 35 - 50) = 12
$$
Hence, $n(A \cap B) = 12$.

---

### Example 2:

If *$A$* and *$B$* are two sets containing 3 and 6 elements respectively, what can be the maximum number of elements in $A \cup B$? Find also the minimum number of elements in $A \cup B$.

#### Solution:

We know that
$$
n(A \cup B) = n(A) + n(B) - n(A \cap B) \tag{i}
$$
**CASE 1:** From (i), it is clear that $n(A \cup B)$ will be **maximum** when $n(A \cap B) = 0$.
In that case, $n(A \cup B) = n(A) + n(B) = (3 + 6) = 9$.
$\therefore$ maximum number of elements in $(A \cup B) = 9$.

**CASE 2:** From (i), it is clear that $n(A \cup B)$ will be **minimum** when $n(A \cap B)$ is maximum, i.e., when $n(A \cap B) = 3$.
In this case, $n(A \cup B) = n(A) + n(B) - n(A \cap B) = (3 + 6 - 3) = 6$.
$\therefore$ minimum number of elements in $A \cup B = 6$.

---

### Example 3:

A survey shows that 73% of the Indians like apples, whereas 65% like oranges. What percentage of Indians like both apples and oranges?

#### Solution:

Let *$A$* = set of Indians who like apples and *$B$* = set of Indians who like oranges.

Then, $n(A) = 73$, $n(B) = 65$ and $n(A \cup B) = 100$.
$$
n(A \cap B) = n(A) + n(B) - n(A \cup B) = (73 + 65 - 100) = 38
$$
Hence, 38% of the Indians like both apples and oranges.

---

### Example 4:

In a survey of 425 students in a school, it was found that 115 drink apple juice, 160 drink orange juice and 80 drink both apple as well as orange juice. How many drink neither apple juice nor orange juice?

#### Solution:

Let *$U$* = set of all students surveyed;
*$A$* = set of all students who drink apple juice
and *$B$* = set of all students who drink orange juice.

Then, $n(U) = 425$, $n(A) = 115$, $n(B) = 160$ and $n(A \cap B) = 80$.
$\therefore \quad n(A \cup B) = n(A) + n(B) - n(A \cap B) = (115 + 160 - 80) = 195$.

Set of students who drink neither apple juice nor orange juice
$$
= (A' \cap B') = (A \cup B)'
$$
$$
\Rightarrow \quad n\{(A \cup B)'\} = n(U) - n(A \cup B) = (425 - 195) = 230
$$
Hence, 230 students drink neither apple juice nor orange juice.

---

### Example 5:

In a group of 850 persons, 600 can speak Hindi and 340 can speak Tamil. Find:
(i) how many can speak both Hindi and Tamil,
(ii) how many can speak Hindi only,
(iii) how many can speak Tamil only.

#### Solution:

Let *$A$* = set of persons who can speak Hindi and *$B$* = set of persons who can speak Tamil.
$\therefore \quad n(A) = 600$, $n(B) = 340$ and $n(A \cup B) = 850$.

**(i)** Set of persons who can speak both Hindi and Tamil = $(A \cap B)$.
$$
\text{Now, } n(A \cap B) = n(A) + n(B) - n(A \cup B) = (600 + 340 - 850) = 90
$$
Thus, 90 persons can speak both Hindi and Tamil.

**(ii)** Set of persons who can speak Hindi only = $(A-B)$.
$$
\text{Now, } n(A-B) + n(A \cap B) = n(A)
$$
$$
\Rightarrow \quad n(A-B) = n(A) - n(A \cap B) = (600 - 90) = 510
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-39.jpg?height=247&width=354&top_left_y=1320&top_left_x=841)
Thus, 510 persons can speak Hindi only.

**(iii)** Set of persons who can speak Tamil only = $(B-A)$.
$$
\text{Now, } n(B-A) + n(A \cap B) = n(B)
$$
$$
\Rightarrow \quad n(B-A) = n(B) - n(A \cap B) = (340 - 90) = 250
$$
Hence, 250 persons can speak Tamil only.

---

### Example 6:

A market research group conducted a survey of 1000 consumers and reported that 745 consumers like product *$A$* and 430 consumers like product *$B$*. What is the least number that must have liked both products?

#### Solution:

Let *$P$* and *$Q$* be the sets of consumers who like product A and product B respectively.
Then, $n(P) = 745$ and $n(Q) = 430$.

Now, $n(P \cup Q) = n(P) + n(Q) - n(P \cap Q)$
$$
\Rightarrow \quad n(P \cup Q) = 745 + 430 - n(P \cap Q)
$$
$$
\Rightarrow \quad n(P \cup Q) = 1175 - n(P \cap Q)
$$
Clearly, $n(P \cap Q)$ is least when $n(P \cup Q)$ is maximum and therefore, $n(P \cup Q) = 1000$.
So, $1000 = 1175 - n(P \cap Q) \Rightarrow n(P \cap Q) = (1175 - 1000) = 175$.
Hence, the least number of consumers liking both the products is 175.

---

### Example 7:

Out of 600 car owners investigated, 500 owned car A; 200 owned car B and 50 owned both *$A$* and *$B$* cars. Verify whether the given data is correct or not.

#### Solution:

Let *$P$* and *$Q$* be the sets of those who own car A and car B respectively. Then,
$$
n(P) = 500, n(Q) = 200 \text{ and } n(P \cap Q) = 50
$$
Now, $n(P \cup Q) = n(P) + n(Q) - n(P \cap Q)$
$$
\Rightarrow \quad n(P \cup Q) = (500 + 200 - 50) = 650
$$
This is a contradiction, since the maximum value of $n(P \cup Q)$ is 600. Hence, the given data is **incorrect**.

---

### Example 8:

In a group of 52 persons, 16 drink tea but not coffee and 33 drink tea. Find:
(i) how many drink tea and coffee both;
(ii) how many drink coffee but not tea.

#### Solution:

Let *$A$* = set of persons who drink tea and *$B$* = set of persons who drink coffee.
Then, $(A-B)$ = set of persons who drink tea but not coffee.
And, $(B-A)$ = set of persons who drink coffee but not tea.

![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-40.jpg?height=248&width=362&top_left_y=1208&top_left_x=837)

Given: $n(A \cup B) = 52$, $n(A-B) = 16$ and $n(A) = 33$.

**(i)** Set of persons who drink tea and coffee both = $(A \cap B)$.
$$
\text{Now, } n(A-B) + n(A \cap B) = n(A)
$$
$$
\Rightarrow \quad n(A \cap B) = n(A) - n(A-B) = (33 - 16) = 17
$$
Thus, 17 persons drink tea and coffee both.

**(ii)** We know $n(A \cup B) = n(A) + n(B) - n(A \cap B)$
$$
\Rightarrow \quad n(B) = n(A \cup B) + n(A \cap B) - n(A) = (52 + 17 - 33) = 36
$$
Now, $n(B-A) + n(A \cap B) = n(B)$.
$$
\Rightarrow \quad n(B-A) = n(B) - n(A \cap B) = (36 - 17) = 19
$$
Thus, number of persons who drink coffee but not tea = 19.

---

### Example 9:

A school awarded 58 medals in three sports, namely 38 in football; 15 in basketball and 20 in cricket. If 3 students got medals in all the three sports, how many received medals in exactly two sports?

#### Solution:

Let *$A, B$* and *$C$* denote the sets of students who won medals in football, basketball and cricket respectively.
Then, $n(A) = 38$, $n(B) = 15$, $n(C) = 20$, $n(A \cap B \cap C) = 3$ and $n(A \cup B \cup C) = 58$.

We know that
$$
n(A \cup B \cup C) = n(A) + n(B) + n(C) - n(A \cap B) - n(B \cap C) - n(A \cap C) + n(A \cap B \cap C)
$$
$$
\Rightarrow n(A \cap B) + n(B \cap C) + n(A \cap C) = n(A) + n(B) + n(C) + n(A \cap B \cap C) - n(A \cup B \cup C)
$$
$$
= \{(38 + 15 + 20 + 3) - 58\} = (76 - 58) = 18
$$
Let *$a, b, c$* and *$d$* denote respectively the number of students who won medals in football and basketball both; basketball and cricket both; football and cricket both and all the 3 sports.

Then, $n(A \cap B) + n(B \cap C) + n(A \cap C) = 18$
$$
\Rightarrow \quad (a+d) + (b+d) + (c+d) = 18
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-41.jpg?height=359&width=424&top_left_y=741&top_left_x=767)
$$
\Rightarrow \quad (a+b+c) + 3d = 18
$$
$$
\Rightarrow \quad (a+b+c) + 3 \times 3 = 18 \Rightarrow a+b+c = 9
$$
*\[$\because d=3$]*

Hence, 9 students received medals in exactly two sports.

---

## An Easy Approach

### Example 10:

In a survey it is found that 21 people like product A, 26 people like product B and 29 like product C. If 14 people like products A and B; 15 people like products B and C; 12 people like products C and A; and 8 people like all the three products, find
(i) how many people are surveyed in all;
(ii) how many like product C only.

#### Solution:

Let *$A, B, C$* denote respectively the sets of people who like product A, B and C respectively, as shown in the given figure.
Let us denote the number of elements contained in bounded regions by *$a, b, c, d, e, f, g$* as shown in the given figure.

![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-41.jpg?height=331&width=400&top_left_y=1580&top_left_x=797)

Then, we have
$$
\begin{aligned}
& a+b+c+d = 21 \\
& b+c+e+f = 26 \\
& c+d+f+g = 29 \\
& b+c = 14, c+f = 15, c+d = 12
\end{aligned}
$$
and $c = 8$.

On solving these equations, we get
$$
c = 8, d = 4, f = 7, b = 6, g = 10, e = 5, a = 3
$$
**(i)** Total number of surveyed people = $(a+b+c+d+e+f+g) = 43$.
**(ii)** Number of persons who like product C only = $g = 10$.

---

### Example 11:

In a survey of 25 students, it was found that 12 have taken physics, 11 have taken chemistry and 15 have taken mathematics; 4 have taken physics and chemistry; 9 have taken physics and mathematics; 5 have taken chemistry and mathematics while 3 have taken all the three subjects. Find the number of students who have taken
(i) physics only;
(ii) chemistry only;
(iii) mathematics only;
(iv) physics and chemistry but not mathematics;
(v) physics and mathematics but not chemistry;
(vi) only one of the subjects;
(vii) at least one of the three subjects;
(viii) none of the three subjects.

#### Solution:

Let *$P, C$* and *$M$* be the sets of students who have taken physics, chemistry and mathematics respectively.
Let *$a, b, c, d, e, f$* and *$g$* denote the number of students in the respective regions, as shown in the adjoining Venn diagram.

As per data given, we have
$$
\begin{cases}
a+b+c+d = 12 \\
b+c+e+f = 11 \\
c+d+f+g = 15 \\
b+c = 4 \\
c+d = 9 \\
c+f = 5 \\
c = 3
\end{cases}
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_49d42c5198e966b87447g-42.jpg?height=361&width=426&top_left_y=1405&top_left_x=765)

From these equations, we get
$$
c = 3, f = 2, d = 6, b = 1
$$
Now, $c+d+f+g = 15 \Rightarrow 3+6+2+g = 15 \Rightarrow g = 4$
and $b+c+e+f = 11 \Rightarrow 1+3+e+2 = 11 \Rightarrow e = 5$
and $a+b+c+d = 12 \Rightarrow a+1+3+6 = 12 \Rightarrow a = 2$.
$\therefore \quad a = 2, b = 1, c = 3, d = 6, e = 5, f = 2$ and $g = 4$.

So, we have:
- **(i)** Number of students who offered physics only = $a = 2$.
- **(ii)** Number of students who offered chemistry only = $e = 5$.
- **(iii)** Number of students who offered mathematics only = $g = 4$.
- **(iv)** Number of students who offered physics and chemistry but not mathematics = $b = 1$.
- **(v)** Number of students who offered physics and mathematics but not chemistry = $d = 6$.
- **(vi)** Number of students who offered only one of the given subjects = $(a+e+g) = (2+5+4) = 11$.
- **(vii)** Number of students who offered at least one of the given subjects = $(a+b+c+d+e+f+g) = (2+1+3+6+5+2+4) = 23$.
- **(viii)** Number of students who offered none of the three given subjects = $(25 - 23) = 2$.

---

