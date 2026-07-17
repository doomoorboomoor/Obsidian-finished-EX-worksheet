## Fundamental Principles of Counting

1.  **Fundamental Principle of Multiplication**: If there are two operations such that one of them can be performed in *$m$ ways*, and when it has been performed in anyone of these *$m$ ways*, the second operation can be performed in *$n$ ways* then the two operations in succession can be performed in **$(m \times n)$ ways**.

---

### Example 1:

In a class there are 15 boys and 12 girls. The teacher wants to select 1 boy and 1 girl to represent the class for a function. In how many ways can the teacher make the selection?

#### Solution:

Here the teacher is to perform two operations:
(i) selecting 1 boy out of 15 boys,
and (ii) selecting 1 girl out of 12 girls.

The first of these can be done in 15 ways and the second in 12 ways. So, by the fundamental principle of multiplication, the required number of ways is $(15 \times 12) = 180$.

Hence, the teacher can make the selection of 1 boy and 1 girl in **180 ways**.

---

2.  **Fundamental Principle of Addition**: If there are two operations such that they can be performed independently in *$m$* and *$n$ ways* respectively then either of the two operations can be performed in **$(m + n)$ ways**.

---

### Example 2:

In a class there are 16 boys and 9 girls. The teacher wants to select either a boy or a girl as a class representative. In how many ways can the teacher make the selection?

#### Solution:

Here the teacher is to perform either of the following two operations:
(i) selecting 1 boy out of 16 boys,
and (ii) selecting 1 girl out of 9 girls.

The first of these can be performed in 16 ways and the second in 9 ways.

By the fundamental principle of addition, either of the two operations can be performed in $(16 + 9)$ ways $= 25$ ways.

Hence, the teacher can make the selection of 1 boy or 1 girl in **25 ways**.

---

## Illustrative Examples

### Example 1:

In a cinema hall, there are three entrance doors and two exit doors. In how many ways can a person enter the hall and then come out?

#### Solution:

Clearly, a person can enter the hall through any of the 3 entrance doors. So, there are 3 ways of entering the hall.

After entering the hall, the person can come out through any of the 2 exit doors. So, there are 2 ways of coming out.

Hence, by the fundamental principle of multiplication, the number of ways in which a person can enter the hall and then come out is $(3 \times 2) = 6$.

---

### Example 2:

Three persons enter a railway carriage, where there are 5 vacant seats. In how many ways can they seat themselves?

#### Solution:

Clearly, the first person can occupy any of the 5 seats. So, there are 5 ways in which the first person can seat himself.

Now, the second person can occupy any of the remaining 4 seats. So, the second person can be seated in 4 ways.

Similarly, the third person can occupy a seat in 3 ways.

Hence, by the fundamental principle of multiplication, the required number of ways is $(5 \times 4 \times 3) = 60$.

---

### Example 3:

The flag of a newly formed forum is in the form $\square \square \square$ of three blocks, each to be coloured differently. If there are six different colours on the whole to choose from, how many such designs are possible?

#### Solution:

The first block of the flag can be coloured by anyone of the 6 given colours. So, there are 6 ways to colour the first block.

Now, the second block can be coloured by anyone of the remaining five colours. So, there are 5 ways to colour the second block.

The third block can now be coloured by anyone of the remaining four colours. So, there are 4 ways to colour the third block.

Hence, by the fundamental principle of multiplication, the required number of designs is $(6 \times 5 \times 4) = 120$.

---

### Example 4:

There are 4 routes between Delhi and Patna. In how many different ways can a man go from Delhi to Patna and return, if for returning
(i) any of the routes is taken;
(ii) the same route is taken;
(iii) the same route is not taken?

#### Solution:

We have the following three cases.

-   **Case (i) When any of the routes is taken for returning:**
    The man may take any route for going from Delhi to Patna. So, there are 4 ways of going from Delhi to Patna. When done so, he may return by any of the 4 routes. So, there are 4 ways of returning from Patna to Delhi.
    Hence, by the fundamental principle of multiplication, the total number of ways for going to Patna and returning back to Delhi is $(4 \times 4) = 16$.

-   **Case (ii) When the same route is taken for returning:**
    In this case, there are 4 ways of going to Patna and only 1 way of returning, namely by the same route.
    Hence, the required number of ways is $(4 \times 1) = 4$.

-   **Case (iii) When the same route is not taken for returning:**
    In this case, there are 4 ways of going to Patna. But, the man does not return by the same route. So, there are 3 ways of returning back to Delhi.
    Hence, the required number of ways is $(4 \times 3) = 12$.

---

### Example 5:

There are six multiple-choice questions in an examination. Find the total number of ways of answering these questions, if the first three questions have 5 choices each and the next three have 4 choices each.

#### Solution:

Each of the first three questions has 5 choices. So, each one of them can be answered in 5 ways.

Each of the next three questions has 4 choices. So, each one of them can be answered in 4 ways.

Hence, by the fundamental principle of multiplication, the total number of ways of answering the six questions is $(5 \times 5 \times 5 \times 4 \times 4 \times 4) = 8000$.

---

### Example 6:

Four flags of different colours are given. How many different signals can be generated, if a signal requires the use of two flags, one below the other?

#### Solution:

The total number of signals is equal to the number of ways of filling two places $\square$ in succession by four flags of different colours.

The upper place can be filled in 4 different ways by any of the four flags. Following it, the lower space can be filled in 3 different ways by anyone of the remaining three flags.

Hence, by the fundamental principle of multiplication, the required number of signals is $(4 \times 3) = 12$.

---

### Example 7:

Find the number of 4-letter words, with or without meaning, which can be formed out of the letters of the word, 'NOSE', when:
(i) the repetition of the letters is not allowed,
(ii) the repetition of the letters is allowed.

#### Solution:

-   **Case (i) When the repetition of the letters is not allowed:**
    In this case, the total number of words is the same as the number of ways of filling 4 places $\square \square \square \square$ by 4 different letters chosen from N, O, S, E.
    The first place can be filled by any of the 4 letters. Thus, there are 4 ways of filling the first place. Since the repetition of letters is not allowed, so the second place can be filled by any of the remaining 3 letters in 3 different ways.
    Following it, the third place can be filled by any of the two remaining letters in 2 different ways. And, the fourth place can be filled by the remaining one letter in 1 way.
    So, by the fundamental principle of multiplication, the required number of 4-letter words is $(4 \times 3 \times 2 \times 1) = 24$.
    Hence, required number of words $= 24$.

-   **Case (ii) When the repetition of the letters is allowed:**
    In this case, each of the four different places can be filled in succession in 4 different ways.
    So, the required number of 4-letter words is $(4 \times 4 \times 4 \times 4) = 256$.

---

### Example 8:

How many words (with or without meaning) of three distinct letters of the English alphabet are there?

#### Solution:

Clearly, we have to fill up three places by distinct letters of the English alphabet.
The first place can be filled by any of the 26 letters. Thus, there are 26 ways to fill the first place.
The second place can be filled by any of the remaining 25 letters. So, there are 25 ways to fill the second place.
The third place can be filled by any of the remaining 24 letters. Thus, there are 24 ways to fill the third place.

Hence, by the fundamental principle of multiplication, the required number of words is $(26 \times 25 \times 24) = 15600$.

---

### Example 9:

How many numbers are there between 100 and 1000 in which all the digits are distinct?

#### Solution:

Clearly, every number between 100 and 1000 is a 3-digit number.
So, we have to form all possible 3-digit numbers with distinct digits. We cannot have 0 at the hundred's place.

So, the hundred's place can be filled with any of the nine digits, namely $1, 2, 3, 4, 5, 6, 7, 8, 9$.
So, there are 9 ways of filling the hundred's place. After filling the hundred's place, nine digits are left including 0. So, there are 9 ways of filling the ten's place.

Now, the unit's place can be filled by any of the remaining 8 digits. So, there are 8 ways of filling the unit's place.

Hence, the required number of numbers is $(9 \times 9 \times 8) = 648$.

---

### Example 10:

How many 9-digit numbers of different digits can be formed?

#### Solution:

The ten-crore's place of a 9-digit number cannot be 0. So, this place can be filled up by any of the digits from 1 to 9. So, there are 9 ways of filling the ten-crore's place.

The crore's place can now be filled with 0 or any of the remaining 8 digits. Thus, there are 9 ways of filling it.

The ten-lakh's place can now be filled with any of the remaining 8 digits. Thus, there are 8 ways of filling it.

Similarly, we can fill lakh's place in 7 ways; ten thousand's place in 6 ways; thousand's place in 5 ways; hundred's place in 4 ways; ten's place in 3 ways and unit's place in 2 ways.

Hence, by the fundamental principle of multiplication, the required number of numbers is $(9 \times 9 \times 8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2) = 3265920$.

---

### Example 11:

How many numbers between 2000 and 3000 can be formed from the digits $2, 3, 4, 5, 6, 7$ when repetition of digits is not allowed?

#### Solution:

Clearly, a number between 2000 and 3000 will have 2 at the thousand's place. So, this place can be filled in 1 way only.

Now, the hundred's place can be filled by any of the remaining five digits. So, there are 5 ways of filling the hundred's place.

Similarly, the ten's place can be filled in 4 ways and the unit's place can be filled in 3 ways.

Hence, by the fundamental principle of multiplication, the total number of required numbers is $(1 \times 5 \times 4 \times 3) = 60$.

---

### Example 12:

How many 3-digit odd numbers can be formed by using the digits 1, 2, 3, 4, 5, 6 when
(i) the repetition of digits is not allowed?
(ii) the repetition of digits is allowed?

#### Solution:

For a number to be odd, we must have 1, 3 or 5 at the unit's place. So, there are 3 ways of filling the unit's place.

-   **Case (i) When the repetition of digits is not allowed:**
    In this case, after filling the unit's place, we may fill the ten's place by any of the remaining five digits. So, there are 5 ways of filling the ten's place.
    Now, the hundred's place can be filled by any of the remaining 4 digits. So, there are 4 ways of filling the hundred's place.
    So, by the fundamental principle of multiplication, the required number of odd numbers is $(3 \times 5 \times 4) = 60$.

-   **Case (ii) When the repetition of digits is allowed:**
    Since the repetition of digits is allowed, so after filling the unit's place, we may fill the ten's place by any of the given six digits. So, there are 6 ways of filling the ten's place.
    Similarly, the hundred's place can be filled by any of the given six digits. So, it can be filled in 6 ways.
    Hence, by the fundamental principle of multiplication, the required number of odd numbers is $(3 \times 6 \times 6) = 108$.

---

### Example 13:

How many odd numbers less than 1000 can be formed by using the digits $0, 2, 5, 7$ when the repetition of digits is allowed?

#### Solution:

Since each number is less than 1000, required numbers are the 1-digit, 2-digit and 3-digit numbers.

-   **One-digit numbers:** Clearly, there are two one-digit odd numbers, namely 5 and 7, formed of the given digits.

-   **Two-digit numbers:** Since we are to form 2-digit odd numbers, we may put 5 or 7 at the unit's place. So, there are 2 ways of filling the unit's place.
    Now, we cannot use 0 at the ten's place and the repetition of digits is allowed. So, we may fill up the ten's place by any of the digits $2, 5, 7$. Thus, there are 3 ways of filling the ten's place.
    Hence, the required type of 2-digit numbers is $(2 \times 3) = 6$.

-   **Three-digit numbers:** To have an odd 3-digit number, we may put 5 or 7 at the unit's place. So, there are 2 ways of filling the unit's place.
    We may fill up the ten's place by any of the digits $0, 2, 5, 7$. So, there are 4 ways of filling the ten's place.
    We cannot put 0 at the hundred's place. So, the hundred's place can be filled by any of the digits $2, 5, 7$ and so it can be done in 3 ways.
    $\therefore$ the required number of 3-digit numbers is $(2 \times 4 \times 3) = 24$.

Hence, the total number of required type of numbers is $(2 + 6 + 24) = 32$.

---

### Example 14:

How many numbers are there between 100 and 1000 such that 7 is in the unit's place?

#### Solution:

Clearly, the numbers between 100 and 1000 are 3-digit numbers. So, we have to form 3-digit numbers with 7 at the unit's place.
Clearly, 0 cannot be there at the hundred's place.

So, the hundred's place can be filled with any of the digits from 1 to 9. Thus, the hundred's place can be filled in 9 ways.

Now, the ten's place can be filled with any of the digits from 0 to 9. So, there are 10 ways of filling the ten's place.

The unit's place can be filled with 7, i.e., in 1 way only.

Hence, the number of required type of numbers is $(9 \times 10 \times 1) = 90$.

---

### Example 15:

How many numbers are there between 100 and 1000 such that at least one of their digits is 7?

#### Solution:

Clearly, the numbers between 100 and 1000 are 3-digit numbers. So, we have to form 3-digit numbers such that at least one of their digits is 7.

-   **Case I: Three-digit numbers with 7 at unit's place:**
    The number of ways to fill the hundred's place is 9 [by any digit from 1 to 9].
    The number of ways to fill the ten's place is 10 [by any digit from 0 to 9].
    The number of ways to fill the unit's place is 1 [by 7 only].
    $\therefore$ the number of such numbers is $(9 \times 10 \times 1) = 90$.

-   **Case II: Three-digit numbers with 7 at ten's place:**
    The number of ways to fill the hundred's place is 9 [by any digit from 1 to 9].
    The number of ways to fill the ten's place is 1 [by 7 only].
    The number of ways to fill the unit place is 10 [by any digit from 0 to 9].
    $\therefore$ the number of such numbers is $(9 \times 1 \times 10) = 90$.

-   **Case III: Three-digit numbers with 7 at hundred's place:**
    The number of ways to fill the hundred's place is 1 [by 7 only].
    The number of ways to fill the ten's place is 10 [by any digit from 0 to 9].
    The number of ways to fill the unit's place is 10 [by any digit from 0 to 9].
    $\therefore$ the number of such numbers is $(1 \times 10 \times 10) = 100$.

Hence, the total number of required numbers is $(90 + 90 + 100) = 280$.

---

### Example 16:

How many numbers are there between 100 and 1000, which have exactly one of their digits as 7?

#### Solution:

Clearly, the numbers between 100 and 1000 are 3-digit numbers. So, we have to form 3-digit numbers having exactly one of their digits as 7.

-   **Case I: 3-digit numbers having 7 at unit's place only:**
    -   Number of ways to fill the unit's place = 1 [with 7 only].
    -   Number of ways to fill the ten's place = 9 [any digit from 0 to 9 except 7].
    -   Number of ways to fill the hundred's place = 8 [any digit from 1 to 9 except 7].
    So, the number of such numbers is $(1 \times 9 \times 8) = 72$.

-   **Case II: 3-digit numbers having 7 at ten's place only:**
    -   Number of ways to fill the ten's place = 1 [with 7 only].
    -   Number of ways to fill the unit's place = 9 [any digit from 0 to 9 except 7].
    -   Number of ways to fill the hundred's place = 8 [any digit from 1 to 9 except 7].
    So, the number of such numbers is $(1 \times 9 \times 8) = 72$.

-   **Case III: 3-digit numbers having 7 at hundred's place only:**
    -   Number of ways to fill the hundred's place = 1 [with 7 only].
    -   Number of ways to fill the ten's place = 9 [any digit from 0 to 9 except 7].
    -   Number of ways to fill the unit's place = 9 [any digit from 0 to 9 except 7].
    So, the number of such numbers is $(1 \times 9 \times 9) = 81$.

Hence, the total number of required numbers is $(72 + 72 + 81) = 225$.

---

### Example 17:

How many numbers are there between 100 and 1000 such that every digit is either 2 or 9?

#### Solution:

Clearly, the numbers between 100 and 1000 are 3-digit numbers. So, we have to form 3-digit numbers by using 2 and 9.
Clearly, the repetition of digits is allowed.

Each one of the unit's, ten's and hundred's places can be filled in 2 ways.

Hence, the required number of numbers is $(2 \times 2 \times 2) = 8$.

---

### Example 18:

How many 3-digit numbers can be formed without using the digits 0, 2, 3, 4, 5 and 6?

#### Solution:

Clearly, we have to form 3-digit numbers by using the digits 1, 7, 8 and 9 while the repetition of digits is allowed.

Clearly, each one of the unit's, ten's and hundred's places can be filled by any of the digits $1, 7, 8, 9$, i.e., in four ways.

Hence, the number of required numbers is $(4 \times 4 \times 4) = 64$.

---

