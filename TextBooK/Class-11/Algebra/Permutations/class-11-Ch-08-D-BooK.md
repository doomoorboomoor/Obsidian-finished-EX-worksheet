## WORD PROBLEMS ON PERMUTATIONS

### Example 1:

In how many ways can 6 persons stand in a queue?

#### Solution:

Required number of ways
$$
\begin{aligned}
& =\text { number of arrangements of } 6 \text { different things taking all at } \\
& \text { a time } \\
& ={ }^{6} P_{6}=6!=(6 \times 5 \times 4 \times 3 \times 2 \times 1)=720 .
\end{aligned}
$$

---

### Example 2:

How many different signals can be made by 4 flags from 6 flags of different colours?

#### Solution:

Required number of signals
$$
\begin{aligned}
& =\text { number of arrangements of } 6 \text { flags taking } 4 \text { at a time } \\
& ={ }^{6} P_{4}=(6 \times 5 \times 4 \times 3)=360 .
\end{aligned}
$$

---

### Example 3:

Eight athletes are participating in a race. In how many ways can the first 3 prizes be won by them?

#### Solution:

Total number of ways of winning first 3 prizes by 8 athletes
$$
\begin{aligned}
& =\text { number of arrangements of } 8 \text { athletes taking } 3 \text { at a time } \\
& ={ }^{8} P_{3}=(8 \times 7 \times 6)=336
\end{aligned}
$$

---

### Example 4:

In how many ways can 3 different rings be worn in 4 fingers with at most one in each finger?

#### Solution:

Required number of ways
$$
\begin{aligned}
& =\text { number of ways of arranging } 4 \text { fingers taking } 3 \text { at a time } \\
& ={ }^{4} P_{3}=(4 \times 3 \times 2)=24
\end{aligned}
$$

---

### Example 5:

3 men have 4 coats, 6 waistcoats and 5 caps. In how many ways can they wear them?

#### Solution:

Total number of ways in which 3 men can wear 4 coats
$$
\begin{aligned}
& =\text { number of arrangements of } 4 \text { coats taking } 3 \text { at a time } \\
& ={ }^{4} P_{3}=(4 \times 3 \times 2)=24 .
\end{aligned}
$$

Total number of ways in which 3 men can wear 6 waistcoats
$$
\begin{aligned}
& =\text { number of arrangements of } 6 \text { waistcoats taking } 3 \text { at a time } \\
& ={ }^{6} P_{3}=(6 \times 5 \times 4)=120 .
\end{aligned}
$$

Total number of ways in which 3 men can wear 5 caps
$$
={ }^{5} P_{3}=(5 \times 4 \times 3)=60 .
$$

Hence, by the **fundamental principle of multiplication**, the required number of ways is $(24 \times 120 \times 60)=172800$.

---

### Example 6:

How many different signals can be given by using any number of flags from 4 flags of different colours?

#### Solution:

These signals can be made by using 1 or 2 or 3 or 4 flags at a time.

Number of signals made by 4 flags:
- (i) taking 1 at a time $={ }^{4} P_{1}=4$;
- (ii) taking 2 at a time $={ }^{4} P_{2}=(4 \times 3)=12$;
- (iii) taking 3 at a time $={ }^{4} P_{3}=(4 \times 3 \times 2)=24$;
- (iv) taking 4 at a time $={ }^{4} P_{4}=(4 \times 3 \times 2 \times 1)=24$.

Hence, by the **fundamental principle of addition**, the total number of signals is $(4+12+24+24)=64$.

---

### Example 7:

A code is to consist of two distinct letters followed by two distinct numbers between 1 and 9. For example, CA 35, DQ 72, etc., are codes.

(i) How many such codes are there?
(ii) How many of them end with an even integer?

#### Solution:

(i) We know that there are **26 letters** in the English alphabet.

Number of ways of choosing 2 letters out of 26
$$
={ }^{26} P_{2}=(26 \times 25)=650 .
$$

Number of ways of choosing 2 numbers out of 9
$$
={ }^{9} P_{2}=(9 \times 8)=72
$$

By the **fundamental principle of multiplication**, the total number of codes is $(650 \times 72)=46800$.

(ii) **Particular case:** When each code ends with an even integer.

In this case, it can have any of the numbers $2, 4, 6, 8$ at the extreme right position. This position can thus be filled in **4 ways**.

The next left position can be filled with any of the remaining 8 numbers. So, there are **8 ways** of filling this position.

Number of ways of choosing pairs of numbers
$$
=(4 \times 8)=32 .
$$

Number of ways of choosing 2 letters out of 26
$$
={ }^{26} P_{2}=(26 \times 25)=650
$$

Hence, the number of such codes which end with an even integer is $(32 \times 650)=20800$.

---

### Example 8:

Find the number of ways in which 5 boys and 3 girls can be arranged in a row so that no two girls are together.

#### Solution:

In order that no two girls are together, we must arrange the 5 boys, each denoted by $B$, as under:
**X B X B X B X B X B X**

Here, $B$ denotes the position of a boy and $X$ that of a girl.

Number of ways in which 5 boys can be arranged at 5 places
$$
={ }^{5} P_{5}=5!=(5 \times 4 \times 3 \times 2 \times 1)=120 .
$$

Number of ways in which 3 girls can be arranged at 6 places (each marked $X$)
$$
={ }^{6} P_{3}=(6 \times 5 \times 4)=120 .
$$

Hence, by the **fundamental principle of multiplication**, the required number of ways is $(120 \times 120)=14400$.

---

### Example 9:

There are 2 English, 3 Sanskrit and 4 Hindi books. In how many ways can they be arranged on a shelf so as to keep all the books of the same language together?

#### Solution:

Let us make 1 packet for each of the books on the same language.
Number of ways of arranging the 3 packets is $={ }^{3} P_{3}=3!=6$.

Number of ways of arranging 2 English books is $2!=2$.
Number of ways of arranging 3 Sanskrit books is $3!=6$.
Number of ways of arranging 4 Hindi books is $4!=24$.

Hence, the required number of ways is $(2 \times 6 \times 24) \times 6=1728$.

---

### Example 10:

In how many ways can 7 examination papers be arranged so that the best and the worst papers are never together?

#### Solution:

Let us tie the **best paper (b)** and the **worst paper (w)** together and consider $(bw)$ as one paper.
Now, this $(bw)$ and 5 other papers may be arranged in
$$
{ }^{6} P_{6}=6!=720 \text { ways. }
$$
Also, these two papers may be arranged among themselves in $2!=2$ ways.

Total number of arrangements with best and worst papers **together**
$$
=(720 \times 2)=1440 .
$$

Total number of ways of arranging 7 papers
$$
={ }^{7} P_{7}=7!=5040
$$

Number of arrangements with best and worst paper **never together**
$$
=(5040-1440)=3600 .
$$

---

### Example 11:

In how many ways can 6 balls of different colours, namely black, white, blue, red, green and yellow be arranged in a row in such a way that the black and white balls are never together?

#### Solution:

Let us tie the black ball (b) and white ball (w) together and consider $(bw)$ as one ball.
Now, this $(bw)$ and 4 other balls may be arranged in
$$
{ }^{5} P_{5}=5!=120 \text { ways. }
$$
Also, these two balls may be arranged among themselves in $2!=2$ ways.

Total number of arrangements with black and white balls **together**
$$
=(120 \times 2)=240 .
$$

Number of ways of arranging 6 balls among themselves
$$
={ }^{6} P_{6}=6!=720 .
$$

Number of ways of arranging 6 balls such that black and white balls are **never together** is $(720-240)=480$.

---

### Example 12:

The principal wants to arrange 5 students on a platform such that the boy Sajal occupies the second position and the girl Tanvy is always adjacent to the girl Aditi. How many such arrangements are possible?

#### Solution:

Let the five seats be arranged as shown below.
`I II III IV V`
`□ S □ □ □`

Keep **Sajal** fixed at the second position.

Since **Tanvy** and **Aditi** are to sit together, none of them can occupy the first seat.
The first seat can be occupied by any of the two remaining students in $2!=2$ ways.
Number of ways in which 2 seats namely III, IV or IV, V may be occupied by Tanvy and Aditi is $(2!)+(2!)=(2+2)=4$.
The remaining seat may now be occupied by the 5th student in 1 way only.
Hence, the required number of arrangements is $(2 \times 4 \times 1)=8$.

---

### Example 13:

How many words (with or without meaning) can be formed by using all the letters of the word, 'DELHI' using each letter exactly once?

#### Solution:

The word, 'DELHI' contains 5 different letters.
Total number of words formed by using all the letters of the given word $={ }^{5} P_{5}=5!=(5 \times 4 \times 3 \times 2 \times 1)=120$.
Hence, the required number of words is 120.

---

### Example 14:

How many 4-letter words (with or without meaning) can be formed out of the letters of the word, 'LOGARITHMS', if repetition of letters is not allowed?

#### Solution:

The word, 'LOGARITHMS' contains 10 different letters.
Number of 4-letter words formed out of 10 given letters
$$
={ }^{10} P_{4}=(10 \times 9 \times 8 \times 7)=5040
$$
Hence, the required number of 4-letter words is 5040.

---

### Example 15:

How many words (with or without meaning) can be formed from the letters of the word, 'DAUGHTER', so that
(i) all vowels occur together?
(ii) all vowels do not occur together?

#### Solution:

The given word, 'DAUGHTER' contains 3 vowels **A, U, E** and 5 consonants **D, G, H, T, R**.

**Case (i)** When all vowels occur together:
Let us assume (AUE) as a single letter.
Then, this letter (AUE) along with 5 other letters can be arranged in ${ }^{6} P_{6}=(6!)$ ways $=(6 \times 5 \times 4 \times 3 \times 2 \times 1)$ ways
$$
= 720 \text { ways. }
$$
These 3 vowels may be arranged among themselves in $3!=6$ ways.
Hence, the required number of words with vowels together
$$
=(6!) \times(3!)=(720 \times 6)=4320 .
$$

**Case (ii)** When all vowels do not occur together:
Number of words formed by using all the 8 letters of the given word
$$
={ }^{8} P_{8}=8!=(8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1)=40320 .
$$
Number of words in which all vowels are never together = (total number of words) - (number of words with all vowels together)
$$
=(40320-4320)=36000 .
$$

---

### Example 16:

How many words (with or without meaning) can be made from the letters of the word 'MONDAY', assuming that no letter is repeated, when:
(i) 4 letters are used at a time?
(ii) all letters are used at a time?
(iii) all letters are used but the first letter is a vowel?

#### Solution:

The given word 'MONDAY' contains 6 letters out of which two letters namely **O** and **A** are vowels.

**Case (i)** When 4 letters are used at a time:
Then, the required number of words = number of arrangements of 6 letters taking 4 at a time
$$
={ }^{6} P_{4}=(6 \times 5 \times 4 \times 3)=360 .
$$

**Case (ii)** When all the letters are used at a time:
Then, the required number of words = number of arrangements of 6 letters taking all at a time
$$
={ }^{6} P_{6}=6!=(6 \times 5 \times 4 \times 3 \times 2 \times 1)=720 .
$$

**Case (iii)** When all the letters are used and the first letter is a vowel:
The given word contains 2 vowels, namely O and A.
So, the first letter can be chosen 1 out of 2 vowels.
Thus, there are **2 ways** of choosing the first letter.
Number of ways of arranging the remaining 5 letters among themselves is $5!=(5 \times 4 \times 3 \times 2 \times 1)=120$.
Hence, the required number of words is $(2 \times 120)=240$.

---

### Example 17:

(i) How many words can be formed from the letters of the word, 'TRIANGLE'?
(ii) How many of them will begin with T and end with E?

#### Solution:

(i) The given word 'TRIANGLE' contains 8 letters.
Total number of words formed with these 8 letters
$$
={ }^{8} P_{8}=8!=40320
$$
Hence, the required number of words is 40320.

(ii) By fixing T in the beginning and E at the end, the remaining 6 letters can be arranged among themselves in ${ }^{6} P_{6}=6!=720$ ways.
Hence, the total number of words, each beginning with T and ending with E is 720.

---

### Example 18:

How many words can be formed with the letters of the word 'ORDINATE' so that the vowels occupy odd places?

#### Solution:

The given word consists of 8 letters, out of which there are 4 vowels and 4 consonants.
Let us mark out the positions to be filled up, as shown below:
$$
\left({ }^{1}\right)\left({ }^{2}\right)\left({ }^{3}\right)\left({ }^{4}\right)\left({ }^{5}\right)\left({ }^{6}\right)\left({ }^{7}\right)\left({ }^{8}\right) .
$$
Since vowels occupy odd places, they may be placed at 1, 3, 5, 7.
Number of ways of arranging 4 vowels at 4 odd places
$$
={ }^{4} P_{4}=4!=24
$$
The remaining 4 letters of the given word are consonants, which can be arranged at 4 even places marked 2, 4, 6, 8.
Number of ways of arranging 4 consonants at 4 even places
$$
={ }^{4} P_{4}=4!=24
$$
Hence, the total number of words in which the vowels occupy odd places is $(24 \times 24)=576$.

---

### Example 19:

How many 3-digit numbers can be formed by using the digits 1 to 9, if no digit is repeated?

#### Solution:

Required number of numbers
$$
\begin{aligned}
& =\text { number of permutations of } 9 \text { digits taking } 3 \text { at a time } \\
& ={ }^{9} P_{3}=(9 \times 8 \times 7)=504
\end{aligned}
$$
Hence, the required number of numbers is 504.

---

### Example 20:

Find the number of 4-digit numbers that can be formed using the digits 1, 2, 3, 4, 5 if no digit is repeated. How many of them will be even?

#### Solution:

Required number of 4-digit numbers
$$
\begin{aligned}
& =\text { number of arrangements of } 5 \text { digits taking } 4 \text { at a time } \\
& ={ }^{5} P_{4}=(5 \times 4 \times 3 \times 2)=120 .
\end{aligned}
$$
**Particular case:** To get an even number, the unit's digit is 2 or 4.
Thus, there are **2 ways** of filling the unit's digit.
Number of ways of filling remaining 3 places with the remaining 4 digits is ${ }^{4} P_{3}=(4 \times 3 \times 2)=24$.
Hence, the required number of even numbers is $(2 \times 24)=48$.

---

### Example 21:

How many 6-digit telephone numbers can be constructed with the digits $0, 1, 2, 3, 4, 5, 6, 7, 8, 9$ if each number starts with 35 and no digit appears more than once?

#### Solution:

Out of the given 10 digits, the two digits namely 3 and 5 are reserved for the two extreme left places of the desired numbers.
The remaining 8 digits can be arranged in the remaining four positions in ${ }^{8} P_{4}=(8 \times 7 \times 6 \times 5)=1680$ ways.
Hence, 1680 telephone numbers can be constructed.

---

