# Circular Permutations

So far we have been considering the arrangements of objects in a line. Such permutations are known as **linear permutations**.

Instead of arranging the objects in a line, if we arrange them in the form of a circle, we call them **circular permutations**.

In circular permutations, what really matters is the position of an object relative to the others.

If we consider the linear permutations

$$
ABCD, BCDA, CDAB \text{ and } DABC
$$

then, clearly, they are distinct.

Now, we arrange $A, B, C, D$ along the circumference of a circle as shown below:
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-001.jpg)
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-002.jpg)
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-003.jpg)
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-004.jpg)

If we consider the position of an object relative to others then we find that the above four arrangements are the same.

For example, if four persons A, B, C, D sit round a table as shown in the first arrangement and then each one shifts to the next chair to the left, we obtain the second arrangement. In this arrangement each person has the same neighbour to the left, and the same neighbour to the right, as he had in the first arrangement. Thus, the first and the second arrangements give rise to the same circular permutation. Same is the case with the third and fourth arrangements given above.

Thus, in circular permutations, we fix the position of one of the objects and then arrange the other objects in all possible ways.

There are two types of circular permutations:

1.  The circular permutations in which the **clockwise** and the **anticlockwise** arrangements give rise to *different* permutations, e.g., seating arrangements of persons round a table.
2.  The circular permutations in which the **clockwise** and the **anticlockwise** arrangements give rise to the *same* permutations, e.g., arranging some beads to form a necklace.

Look at the circular permutations, given below:
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-005.jpg)
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-006.jpg)

Suppose A, B, C, D are the four beads forming a necklace. They have been arranged in clockwise and anticlockwise directions in the first and second arrangements respectively. Now, if the necklace in the first arrangement be given a turn, from clockwise to anticlockwise, we obtain the second arrangement. Thus, there is no difference between the above two arrangements.

---

# Results on Circular Permutations

### Theorem 1
The number of circular permutations of $n$ different objects is $(n-1)!$.

#### Proof:
Fixing the position of an object can be done in $n$ ways, as the position of anyone of them may be fixed. Thus, each circular permutation corresponds to $n$ linear permutations, depending upon where from we start. Since there are $n!$ linear permutations, it follows that there are $\frac{n!}{n}$, i.e., $(n-1)!$ circular permutations.

### Theorem 2
The number of ways in which $n$ persons can be seated round a table is $(n-1)!$.

#### Proof:
Let us fix the position of one person and then arrange the remaining $(n-1)$ persons in all possible ways. Clearly, this can be done in $(n-1)!$ ways. Hence, the required number of ways is $(n-1)!$.

### Theorem 3
Show that the number of ways in which $n$ different beads can be arranged to form a necklace is $\frac{1}{2}(n-1)!$.

#### Proof:
Fixing the position of one bead, the remaining $(n-1)$ beads can be arranged in $(n-1)!$ ways. In case of arranging the beads, there is no distinction between the clockwise and the anticlockwise arrangements. So, the required number of ways is $\frac{1}{2}(n-1)!$.

---

# Illustrative Examples

### Example 1
In how many ways can 8 students be arranged in
(i) a line,
(ii) a circle?

#### Solution:
(i) The number of ways in which 8 students can be arranged in a line is $8! = (8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1) = 40320$.

(ii) The number of ways in which 8 students can be arranged in a circle is $(8-1)! = 7! = (7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1) = 5040$.

---

### Example 2
If 20 persons were invited for a party, in how many ways can they and the host be seated at a circular table? In how many of these ways will two particular persons be seated on either side of the host?

#### Solution:
Clearly, there are 21 persons, to be seated round a circular table.

(i) Let us fix the seat of one person, say the host. The remaining 20 persons can now be arranged in $20!$ ways. Hence, the number of ways in which these 21 persons can be seated round a circular table is $20!$.

(ii) The two particular persons can be seated on either side of the host in 2 ways and for each way of their taking seats, the remaining 18 persons can be seated at the circular table in $18!$ ways.

$\therefore$ the number of ways of seating 21 persons at a circular table with two particular persons on either side of the host is $(2 \times 18!)$.

---

### Example 3
In how many ways can a party of 4 men and 4 women be seated at a circular table so that no two women are adjacent?

#### Solution:
The 4 men can be seated at the circular table such that there is a vacant seat between every pair of men. The number of ways in which these 4 men can be seated at the circular table is $3! = 6$.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-007.jpg)

Now, the 4 vacant seats may be occupied by 4 women in
$$
{}^{4}P_{4} = 4! = 24 \text{ ways.}
$$
$\therefore$ the required number of ways is $(6 \times 24) = 144$.

---

### Example 4
A round table conference is to be held between delegates of 20 countries. In how many ways can they be seated if two particular delegates may wish to sit together?

#### Solution:
Regarding these two delegates as one, the 19 delegates can be arranged at a circular table in $18!$ ways. These two delegates can be arranged among themselves in $2!$, i.e., 2 ways.

$\therefore$ the required number of ways is $2 \times (18!)$.

---

### Example 5
In how many ways can 7 persons sit around a table so that all shall not have the same neighbours in any two arrangements?

#### Solution:
7 persons sit at a round table in $6!$ ways. But, in clockwise and anticlockwise arrangements, each person will have the same neighbours.

So, the required number of ways is $(1/2) \times (6!) = 360$.

---

### Example 6
3 boys and 3 girls are to be seated around a table in a circle. Among them, the boy $X$ does not want any girl neighbour and the girl $Y$ does not want any boy neighbour. How many such arrangements are possible?

#### Solution:
Fix the positions of $X$ and $Y$ as shown in the figure. Now, the boys $B_{1}, B_{2}$ and the girls $G_{1}, G_{2}$ may have their neighbours $X$ and $Y$ respectively.
![](file:///C:/Obsidian-finished-EX-worksheet_resources/TextBooK/Class-11/Algebra/Permutations/class-11-Ch-08-G-BooK-008.jpg)

The boys $B_{1}$ and $B_{2}$ may be arranged among themselves in $2!$ ways. And, the girls $G_{1}$ and $G_{2}$ may be arranged among themselves in $2!$ ways.

Hence, the required number of arrangements is $(2 \times 2) = 4$.

---

### Example 7
Find the number of ways in which 8 different beads can be arranged to form a necklace.

#### Solution:
Fixing the position of one bead, the remaining beads can be arranged in $7!$ ways. But, there is no distinction between the clockwise and anticlockwise arrangements.

So, the required number of arrangements is $(1/2) \times (7!) = 2520$.

---

