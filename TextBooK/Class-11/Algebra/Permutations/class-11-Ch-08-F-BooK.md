## Permutations with Repetitions

### Theorem 1
The number of permutations of **$n$ different objects**, taken **$r$ at a time** when each may be repeated any number of times in each arrangement, is **$n^{r}$**.

#### Proof:
We know that the number of all permutations of $n$ objects, taken $r$ at a time is the same as the number of ways of filling up $r$ places with $n$ different objects.

Clearly, the first place can be filled in $n$ ways. Since each object may be repeated, the second place can be filled in $n$ ways.

Similarly, each of the 3rd, 4th, ..., $r$-th places can be filled in $n$ ways.

$$
\therefore \quad \text{the requisite number of permutations} = n \times n \times n \times \ldots r \text{ times} = n^{r}.
$$

#### Corollary:
When $r = n$, i.e., the number of permutations of $n$ different objects, taken all at a time when each may be repeated any number of times in each arrangement, is $n^{n}$.

---

## Summary

- Number of permutations of **$n$ different objects**, taken **$r$ at a time** when each may be repeated any number of times in each arrangement, is **$n^{r}$**.
- Number of permutations of **$n$ different objects**, taken **all at a time** when each may be repeated any number of times in each arrangement, is **$n^{n}$**.

---

## Solved Examples

### Example 1
In how many ways can 4 letters be posted in 3 letter boxes?

#### Solution:
Each letter can be posted in any of the 3 letter boxes.
So, each letter can be posted in 3 ways.

$\therefore \quad 4$ letters can be posted in $(3 \times 3 \times 3 \times 3) = 3^{4} = \textbf{81}$ ways.

---

### Example 2
In how many ways can 6 different rings be worn in 4 fingers of the hand?

#### Solution:
Each ring may be worn in any of the 4 fingers.
So, each ring may be worn in 4 ways.

$\therefore \quad 6$ rings may be worn in $(4 \times 4 \times 4 \times 4 \times 4 \times 4) = 4^{6} = \textbf{4096}$ ways.

---

### Example 3
In how many ways can 5 apples be distributed among 6 boys, there being no restriction to the number of apples each boy may get?

#### Solution:
Each apple may be given to any of the 6 boys.
So, each apple may be given in 6 ways.

$\therefore \quad 5$ apples may be given in $(6 \times 6 \times 6 \times 6 \times 6) = 6^{5} = \textbf{7776}$ ways.

---

### Example 4
In how many ways can 3 prizes be distributed among 4 boys, when
(i) no boy gets more than 1 prize;
(ii) a boy may get any number of prizes;
(iii) no boy gets all the prizes?

#### Solution:
1.  **Case (i) When no boy gets more than 1 prize.**
    The first prize may be given to any of the 4 boys in 4 ways.
    The 2nd prize may be given in 3 ways, since the boy who got the 1st prize cannot receive it.
    The 3rd prize may be given to any of the remaining 2 boys in 2 ways.
    Required number of ways $= (4 \times 3 \times 2) = \textbf{24}$.

2.  **Case (ii) When a boy may get any number of prizes.**
    The 1st prize may be given to any of the 4 boys in 4 ways.
    Since a boy may get any number of prizes, so 2nd prize may be given to any of the 4 boys in 4 ways.
    Similarly, the 3rd prize may be given in 4 ways.
    Required number of ways $= (4 \times 4 \times 4) = \textbf{64}$.

3.  **Case (iii) When no boy gets all the prizes.**
    The number of ways in which a boy gets all the prizes is 4, as anyone of the 4 boys may get all the prizes.
    Hence, the number of ways in which a boy does not get all the prizes $= (64 - 4) = \textbf{60}$.

---

### Example 5
How many four-digit numbers can be formed with the digits 1, 2, 3, 4, 5, 6 when a digit may be repeated any number of times in any arrangement?

#### Solution:
Clearly, the thousand's place can be filled in 6 ways as anyone of the 6 digits may be placed at it.
Since there is no restriction on repetition of digits, each one of the hundred's, ten's and unit's digits can be filled in 6 ways.
Hence, the required number of numbers $= (6 \times 6 \times 6) = \textbf{216}$.

---

### Example 6
How many 4-digit numbers are there when a digit may be repeated any number of times?

#### Solution:
Clearly, 0 cannot be placed at the thousand's place.
So, this place can be filled with any digit from 1 to 9.
Thus, there are 9 ways of filling the thousand's place.
Since repetition of digits is allowed, each one of the remaining 3 places can be filled in 10 ways, i.e., with any digit from 0 to 9.
So, the required number of numbers $= (9 \times 10^{3}) = \textbf{9000}$.

---

