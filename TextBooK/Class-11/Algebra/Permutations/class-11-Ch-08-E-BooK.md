## Permutations of Objects Not All Different

**Theorem 1:** Let there be $n$ objects, of which $m$ objects are alike of one kind, and the remaining $(n-m)$ objects are alike of another kind. Then, the total number of mutually distinguishable permutations that can be formed from these objects is

$$
\frac{n!}{(m!) \times(n-m)!}
$$

**Proof:**
Let the required number of permutations be $x$. Consider any of these $x$ permutations.

Now, replace $m$ like things in this permutation by $m$ different things. These $m$ different things may be arranged amongst themselves in $m!$ ways.

Similarly, if we replace $(n-m)$ like things by $(n-m)$ different things, then they can be arranged amongst themselves in $(n-m)!$ ways.

Thus, if both the replacements are done simultaneously then each one of the $x$ permutations gives rise to $(m!) \times(n-m)!$ permutations.
$x$ permutations give rise to $x \times(m!) \times(n-m)!$ permutations.

Now, each of these $x \times(m!) \times(n-m)!$ permutations is a permutation of $n$ different things, taken all at a time.

$\therefore \quad x \times(m!) \times(n-m)! = n!$.
Hence, $x = \frac{n!}{(m!) \times(n-m)!}$.

---

**Remark 1:** Let there be $n$ things of which $p_{1}$ are alike of one kind, $p_{2}$ are alike of another kind, $p_{3}$ are alike of 3rd kind, $\ldots, p_{r}$ are alike of $r$th kind such that $p_{1}+p_{2}+\ldots+p_{r}=n$. Then, the number of permutations of these $n$ things is

$$
\frac{n!}{\left(p_{1}!\right) \times\left(p_{2}!\right) \times \ldots \times \left(p_{r}!\right)}
$$

**Remark 2:** The number of permutations of $n$ things of which $p$ are alike of one kind, $q$ are alike of another kind and remaining all are distinct is $\frac{n!}{(p!) \times(q!)}$.

---

## Solved Examples

### Example 1:

Find the number of different permutations of the letters of the word, 'BANANA'.

#### Solution:

The given word 'BANANA' contains 6 letters, out of which three are alike of one kind (3 A's), two are alike of second kind (2 N's) and one of its own kind (1 B).

Total number of their permutations = $\frac{6!}{(3!) \times(2!) \times(1!)} = 60$.

---

### Example 2:

How many words can be formed using the letter $A$ thrice, the letter $B$ twice and the letter $C$ thrice?

#### Solution:

We are given 8 letters, namely AAABBCCC. Out of these letters three are alike of one kind (3 A's), two are alike of second kind (2 B's) and three are alike of third kind (3 C's).

Hence, the required number of permutations
$$
=\frac{8!}{(3!) \times(2!) \times(3!)} = 560 .
$$

---

### Example 3:

(i) Find how many arrangements can be made with the letters of the word 'MATHEMATICS'.
(ii) In how many of them are the vowels together?

#### Solution:

(i) There are 11 letters in the word 'MATHEMATICS'. Out of these letters M occurs twice, A occurs twice, T occurs twice and the rest are all different.

Hence, the total number of arrangements of the given letters
$$
=\frac{11!}{(2!) \times(2!) \times(2!)} = 4989600 .
$$

(ii) The given word contains 4 vowels, namely A, E, A, I. Treating these 4 vowels AEAI as one letter, we have to arrange 8 letters MTHMTCS + AEAI, out of which M occurs twice, T occurs twice and the rest are all different.

So, the number of all such arrangements = $\frac{8!}{(2!) \times(2!)} = 10080$.

Now, out of 4 vowels, A occurs twice and the rest are all distinct.
So, the number of arrangements of these vowels = $\frac{4!}{2!} = 12$.

Hence, the number of arrangements in which 4 vowels are together = $(10080 \times 12) = 120960$.

---

### Example 4:

**I.** Find the number of arrangements of the letters of the word, 'INDEPENDENCE'.
**II.** In how many of these arrangements:
(i) do the words start with $P$?
(ii) do all the vowels occur together?
(iii) do the vowels never occur together?
(iv) do the words begin with $I$ and end in $P$?

#### Solution:

**I.** The given word contains 12 letters out of which N occurs 3 times, E occurs 4 times, D occurs 2 times and the rest are all different.
Hence, the required number of arrangements
$$
=\frac{12!}{(3!) \times(4!) \times(2!)} = 1663200 .
$$

**II.**
(i) After fixing $P$ at the extreme left position, there are 11 letters consisting of 3 N's, 4 E's, 2 D's, 1 I and 1 C.
So, the number of words beginning with $P$ = number of arrangements of 11 letters out of which there are 3 N's, 4 E's, 2 D's, 1 I and 1 C
$$
=\frac{11!}{(3!) \times(4!) \times(2!)} = 138600 .
$$

(ii) There are 5 vowels in the given word, namely 4 E's and 1 I. Let us treat them as a single letter EEEEI.
This letter with 7 remaining letters will give us 8 letters in which there are 3 N's, 2 D's, 1 P, 1 C and 1 letter EEEEI.
Number of all such arrangements = $\frac{8!}{(3!) \times(2!)} = 3360$.
Number of arrangements of 5 vowels, namely 4 E's and 1 I = $\frac{5!}{4!} = 5$.
Hence, the number of words in which vowels are together = $(3360 \times 5) = 16800$.

(iii) Number of arrangements in which vowels do not occur together
= (total number of arrangements) - (number of arrangements in which vowels occur together)
= $(1663200 - 16800) = 1646400$.

(iv) Let us fix I at the left end and P at the right end of each arrangement.
Then, we are left with 10 letters, out of which there are 3 N's, 4 E's, 2 D's and 1 C.
Hence, the number of words which begin with I and end in P = $\frac{10!}{(3!) \times(4!) \times(2!)} = 12600$.

---

### Example 5:

(i) How many different words can be formed by using all the letters of the word, 'ALLAHABAD'?
In how many of them:
(ii) both L's do not come together?
(iii) the vowels occupy the even positions?

#### Solution:

(i) The given word, 'ALLAHABAD' contains 9 letters consisting of 4 A's, 2 L's, 1 H, 1 B and 1 D.
Hence, the number of different words formed by using all the letters of the given word = $\frac{9!}{(4!) \times(2!)} = 7560$.

(ii) Let us take both L together and we treat LL as 1 letter.
Then, we will have to arrange 8 letters, namely LL, 4 A's, 1 H, 1 B and 1 D.
So, the number of words having both L together = $\frac{8!}{4!} = 1680$.
Hence, the number of words with both L not occurring together = $(7560 - 1680) = 5880$.

(iii) There are 4 vowels and all are alike, i.e., 4 A's.
Also, there are 4 even places, namely 2nd, 4th, 6th and 8th.
So, we arrange A's at these 4 places, as shown below.
$\square \mathrm{A} \square \mathrm{A} \square \mathrm{A} \square \mathrm{A} \square$
Number of arrangements of 4 A's at 4 places = $\frac{4!}{4!} = 1$.
Now, we are left with 5 letters consisting of 2 L's, 1 H, 1 B and 1 D.
Number of arrangements of these 5 letters at 5 places = $\frac{5!}{2!} = 60$.
Hence, the number of words in which vowels occupy even places = $(1 \times 60) = 60$.

---

### Example 6:

In how many of the distinct permutations of the letters in 'MISSISSIPPI' do the 4 I's not come together?

#### Solution:

The given word 'MISSISSIPPI' contains 11 letters, out of which there are 4 I's, 4 S's, 2 P's and 1 M.
Total number of words formed by the letters of the given word
$$
=\frac{11!}{(4!) \times(4!) \times(2!)} = 34650 .
$$
There are 4 I's in the given word and we treat IIII as 1 letter.
This single letter with remaining 7 letters will give us 8 letters out of which there are 4 S's, 2 P's, 1 M and 1 IIII.
So, the number of all such arrangements in which 4 I's are together
$$
=\frac{8!}{(4!) \times(2!)} = 840 .
$$
Thus, the number of words formed when 4 I's are together = 840.
Hence, the number of words formed when 4 I's are not together = $(34650 - 840) = 33810$.

---

### Example 7:

(i) How many words can be formed with the letters of the word, 'HARYANA'?
How many of these
(ii) have H and N together?
(iii) begin with H and end with N?
(iv) have 3 vowels together?

#### Solution:

(i) The given word 'HARYANA' consists of 7 letters, out of which there are 1 H, 3 A's, 1 R, 1 Y and 1 N.
Total number of words formed by all the letters of the given word = $\frac{7!}{3!} = 840$.

(ii) Let us consider HN as a single letter.
Now, HN + ARYAA will give us 6 letters out of which there are 3 A's, 1 R, 1 Y and 1 HN.
Total number of all such arrangements = $\frac{6!}{3!} = 120$.
But, H and N can be arranged amongst themselves in $2!$ ways.
Hence, the number of words having H and N together = $(120 \times 2) = 240$.

(iii) After fixing H in first place and N in last place, we have 5 letters, out of which there are 3 A's, 1 R and 1 Y.
Hence, the number of words beginning with H and ending with N = $\frac{5!}{3!} = 20$.

(iv) The given word contains 3 vowels AAA and let us treat AAA as 1 letter.
Now, we have to arrange 5 letters HRYN + AAA at 5 places.
Hence, total number of words formed having all vowels together = $5! = (5 \times 4 \times 3 \times 2 \times 1) = 120$.

---

### Example 8:

In how many ways can the letters of the word 'PERMUTATIONS' be arranged, if
(i) the words start with $P$ and end with $S$?
(ii) the vowels are all together?

#### Solution:

(i) Let us fix P at the left end and S at the right end of each arrangement.
Then, we are left with 10 letters, out of which T occurs 2 times and the rest are all different.
Hence, the required number of arrangements = $\frac{10!}{2!} = 1814400$.

(ii) The given word contains 5 vowels, namely E, U, A, I, O.
Treating these five vowels EUAIO as one letter, we have to arrange 8 letters, namely EUAIO + PRMTTNS, out of which T occurs 2 times and the rest are all different.
Number of all such arrangements = $\frac{8!}{2!} = 20160$.
Now, the 5 vowels are all different. They can be arranged among themselves in $5! = 120$ ways.
Hence, the number of arrangements in which 5 vowels are together = $(20160 \times 120) = 2419200$.

---

### Example 9:

If the different permutations of the word 'EXAMINATION' are listed as in a dictionary, how many items are there in the list before the first word starting with E?

#### Solution:

In a dictionary, the words at each stage are arranged in an alphabetical order.
When the letters of the word 'EXAMINATION' are arranged in the dictionary, the first word would be AAEIIMNNOTX.
Starting with A, we arrange the remaining 10 letters AEIIMNNOTX in which there are 2 I's, 2 N's and the rest are all different, in all possible ways.
Thus, the number of words formed beginning with A
$$
=\frac{10!}{(2!) \times(2!)} = 907200 .
$$
In the dictionary, the next word would be EAAIIMNNOTX.
Hence, 907200 words are there in the dictionary before the first word starting with E.

---

### Example 10:

(i) Find the number of words which can be made using all the letters of the word, 'AGAIN'.
(ii) If these words are written as in a dictionary, what will be the 50th word?

#### Solution:

(i) The given word 'AGAIN' consists of 5 letters, out of which there are 2 A's and the rest are all distinct.
Hence, the number of words formed by using all the letters of the given word = $\frac{5!}{2!} = 60$.

(ii) When the letters of the word 'AGAIN' are listed in a dictionary, the first word would be AAGIN.
Starting with A and arranging the remaining 4 letters A, G, I, N, we obtain $4!$ words, i.e., 24 words.
The 25th word would be GAAIN, which starts with G.
Now, starting with G arrange the remaining 4 letters AAIN, (in which A occurs 2 times and the rest are different) in all possible ways.
Number of such arrangements = $\frac{4!}{2!} = 12$.
Thus, we obtain 12 new words.
The 37th word would be IAAGN, which starts with I.
Now, starting with I and arranging the remaining 4 letters, AAGN, we get $\frac{4!}{2!} = 12$ words.
The 49th word would be NAAGI and hence the 50th word is NAAIG.

---

### Example 11:

How many numbers greater than a million can be formed with the digits 2, 3, 0, 3, 4, 2, 3?

#### Solution:

Any number greater than one million will contain all the seven digits.
Now, we have to arrange seven digits, out of which 2 occurs twice, 3 occurs thrice and the rest are distinct.
Number of such arrangements = $\frac{7!}{(2!) \times(3!)} = 420$.
These arrangements will also include those which contain 0 at the million's place.
Keeping 0 fixed at the million's place, the remaining 6 digits out of which 2 occurs twice, 3 occurs thrice and the rest are distinct can be arranged in = $\frac{6!}{(2!) \times(3!)} = 60$ ways.
Hence, the number of required numbers = $(420 - 60) = 360$.

---

### Example 12:

How many numbers greater than 400000 can be formed by using the digits 0, 2, 2, 4, 4, 5?

#### Solution:

We are being given six digits and each number greater than 400000 is a six-digit number, having 4 or 5 in the extreme left position.

When 4 occupies the extreme left position, the remaining 5 places can be filled with the digits 0, 2, 2, 4, 5 (in which 2 occurs 2 times and rest are all different).
Number of such numbers = $\frac{5!}{2!} = 60$.

When 5 occupies the extreme left position, the remaining 5 places can be filled with the digits 0, 2, 2, 4, 4 (in which 2 occurs twice, 4 occurs twice and the rest are all distinct).
Number of such numbers = $\frac{5!}{(2!) \times(2!)} = 30$.

Hence, the required number of numbers = $(60 + 30) = 90$.

---

### Example 13:

How many numbers can be formed using the digits 1, 2, 3, 4, 3, 2, 1 so that the odd digits always occupy the odd places?

#### Solution:

We have been given seven digits, namely 1, 2, 3, 4, 3, 2, 1.
So, we have to form 7-digit numbers, so that odd digits occupy odd places.
Every 7-digit number has 4 odd places.
Given four odd digits are 1, 3, 3, 1 out of which 1 occurs 2 times and 3 occurs 2 times.
So, the number of ways to fill up 4 odd places = $\frac{4!}{(2!) \times(2!)} = 6$.
Given three even digits are 2, 4, 2 in which 2 occurs 2 times and 4 occurs 1 time.
So, the number of ways to fill up 3 even places = $\frac{3!}{2!} = 3$.
Hence, the required number of numbers = $(6 \times 3) = 18$.

---

