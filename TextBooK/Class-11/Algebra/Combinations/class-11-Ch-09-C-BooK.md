## Mixed Problems on Permutations and Combinations

---

## Solved Examples

### Example 1:

Out of **7 consonants** and **4 vowels**, how many words of **3 consonants** and **2 vowels** can be formed?

#### Solution:

The total number of ways of choosing (**3 consonants** out of 7) and (**2 vowels** out of 4) is:

$$
\left({ }^{7} C_{3} \times{ }^{4} C_{2}\right) = \left(\frac{7 \times 6 \times 5}{3 \times 2 \times 1} \times \frac{4 \times 3}{2 \times 1}\right) = 210
$$

This gives us **210** possible groups, with each group containing 5 letters (3 consonants + 2 vowels).

Next, the number of ways of arranging these **5 letters** amongst themselves is $5!$:

$$
5! = (5 \times 4 \times 3 \times 2 \times 1) = 120
$$

Hence, the **total required number of words** is the product of the number of groups and the number of arrangements for each group:

$$
210 \times 120 = 25200
$$

---

### Example 2:

The English alphabet has **21 consonants** and **5 vowels**. How many words with **two different consonants** and **two different vowels** can be formed from the alphabet?

#### Solution:

The total number of ways of choosing (**2 consonants** out of 21) and (**2 vowels** out of 5) is:

$$
{ }^{21} C_{2} \times{ }^{5} C_{2} = \left(\frac{21 \times 20}{2 \times 1} \times \frac{5 \times 4}{2 \times 1}\right) = 2100
$$

This gives **2100** groups, each containing 4 letters.

The number of ways of arranging these **4 letters** amongst themselves is $4!$:

$$
4! = (4 \times 3 \times 2 \times 1) = 24
$$

Hence, the **total required number of words** is:

$$
2100 \times 24 = 50400
$$

---

### Example 3:

How many words with or without meaning, each of **2 vowels** and **3 consonants**, can be formed from the letters of the word 'DAUGHTER'?

#### Solution:

The given word 'DAUGHTER' contains **3 vowels** (A, U, E) and **5 consonants** (D, G, H, T, R).

The number of ways of choosing (**2 vowels** out of 3) and (**3 consonants** out of 5) is:

$$
\left({ }^{3} C_{2} \times{ }^{5} C_{3}\right) = \left({ }^{3} C_{1} \times{ }^{5} C_{2}\right) = \left(3 \times \frac{5 \times 4}{2 \times 1}\right) = 30
$$

This gives **30** groups, each containing 5 letters.

The number of ways of arranging these **5 letters** is $5!$:

$$
5! = (5 \times 4 \times 3 \times 2 \times 1) = 120
$$

Hence, the **total required number of words** is:

$$
30 \times 120 = 3600
$$

---

### Example 4:

How many words, with or without meaning, can be formed using all the letters of the word 'EQUATION' at a time so that **vowels and consonants occur together**?

#### Solution:

The word 'EQUATION' contains **5 vowels** (E, U, A, I, O) and **3 consonants** (Q, T, N).

To have vowels and consonants occur together, we treat the group of vowels as a single block and the group of consonants as another single block.

- The **5 vowels** can be arranged amongst themselves in $5!$ ways.
- The **3 consonants** can be arranged amongst themselves in $3!$ ways.
- These two blocks (vowels and consonants) can be arranged in $2!$ ways.

Therefore, the **required number of words** is the product of these arrangements:

$$
\begin{aligned}
& (5!) \times (3!) \times (2!) \\
& = (5 \times 4 \times 3 \times 2 \times 1) \times (3 \times 2 \times 1) \times (2 \times 1) = 1440
\end{aligned}
$$

---

### Example 5:

In how many ways can **5 girls** and **3 boys** be seated in a row so that **no two boys are together**?

#### Solution:

To ensure no two boys are together, we first place the 5 girls. This creates spaces where the boys can be seated. The 5 girls can be arranged in $5!$ ways.

Arranging the girls creates 6 possible places for the boys (indicated by 'X'):

**X G X G X G X G X G X**

Now, we must arrange the **3 boys** in these **6 available places**. This can be done in ${ }^{6} P_{3}$ ways.

The **total required number of ways** is the product of these two arrangements:

$$
\begin{aligned}
& (5!) \times { }^{6} P_{3} = (5!) \times \frac{6!}{3!} \\
& = \left\{ (5 \times 4 \times 3 \times 2 \times 1) \times \left( \frac{6 \times 5 \times 4 \times 3 \times 2 \times 1}{3 \times 2 \times 1} \right) \right\} = 14400
\end{aligned}
$$

Hence, the required number of ways is **14400**.

---

## Exercise 9C

### Questions

1.  Out of **12 consonants** and **5 vowels**, how many words, each containing **3 consonants** and **2 vowels**, can be formed?
2.  How many words, each of **3 vowels** and **2 consonants**, can be formed from the letters of the word 'INVOLUTE'?
3.  The English alphabet has **21 consonants** and **5 vowels**. How many words with **two different consonants** and **three different vowels** can be formed from the alphabet?
4.  In how many ways can **4 girls** and **3 boys** be seated in a row so that no two boys are together?
5.  How many words, with or without meaning, can be formed from the letters of the word, 'MONDAY', assuming that no letter is repeated, if:
    - (i) 4 letters are used at a time?
    - (ii) all letters are used at a time?
    - (iii) all letters are used but the first letter is a vowel?

---

### Answers & Solutions

*The following are the answers and solutions provided in the source text.*

**Answers to Unsolved Problems:**

- **6.** 264000
- **7.** 2880
- **8.** 252000
- **9.** 480

**Answer to Question 5:**

- **(i)** 360
- **(ii)** 720
- **(iii)** 240

#### Solution to Question 5:

**(i) 4 letters are used at a time**

The number of 4-letter words from the 6 letters of 'MONDAY' is:

$$
{ }^{6} P_{4} = 360
$$

**(ii) All letters are used at a time**

The number of words formed from all 6 letters of 'MONDAY' is:

$$
{ }^{6} P_{6} = 6! = 720
$$

**(iii) All letters are used but the first letter is a vowel**

The given word contains two vowels: A and O. So, the first letter of the word can be chosen in **2 ways**.

The remaining 5 places can be filled with the remaining 5 letters in $5!$ ways.

The required number of words is:

$$
2 \times (5!) = 2 \times 120 = 240
$$