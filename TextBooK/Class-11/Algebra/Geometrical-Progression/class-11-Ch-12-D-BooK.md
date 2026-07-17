## Word Problems on GP

### Example 1:

A man has 2 parents, 4 grandparents, 8 great-grandparents, and so on. Find the number of his ancestors during the ten generations preceding his own.

#### Solution:

Required number of ancestors:
$$
\begin{aligned}
& =2+4+6+8+\ldots \text { up to } 10 \text { terms } \\
& =2 \times \frac{\left(2^{10}-1\right)}{(2-1)}=2\left(2^{10}-1\right) \quad[\text{GP with } a=2, r=2 \text{ and } n=10]
\end{aligned}
$$

$$
=2(1024-1)=(2 \times 1023)=2046.
$$

Hence, the required number of the man's ancestors is **2046**.

---

### Example 2:

A man writes a letter to four of his friends. He asks each one of them to copy the letter and mail to four different persons with the instruction that they move the chain similarly. Assuming that the chain is not broken and it costs ₹4 to mail one letter, find the amount spent on postage when the 6th set of letters is mailed.

#### Solution:

The successive number of letters are $4, 16, 64, \ldots$. This is a GP with $a=4$ and $r=4$.

Number of letters in the 6th set = $ar^{(6-1)} = (4 \times 4^5) = 4^6 = 4096$.

Cost of postage on these letters = $₹(4096 \times 4) = ₹16384$.

---

### Example 3:

What will ₹10000 amount to in 4 years after its deposit in a bank which pays annual interest at the rate of $10\%$ per annum compounded annually?

#### Solution:

The original sum is $₹10000$.

- Amount after 1 year = $₹10000 + ₹(10000 \times \frac{10}{100} \times 1) = ₹11000$.
- Amount after 2 years = $₹11000 + ₹(11000 \times \frac{10}{100} \times 1) = ₹12100$.
- Amount after 3 years = $₹12100 + ₹(12100 \times \frac{10}{100} \times 1) = ₹13310$, and so on.

Thus, these amounts form a GP: $10000, 11000, 12100, 13310, \ldots$ such that $\frac{11000}{10000}=\frac{12100}{11000}=\frac{13310}{12100}=\frac{11}{10}$.

In this GP, we have $a=10000, r=\frac{11}{10}$.

Amount after 4 years = $T_{5} = ar^{(5-1)} = ar^{4}$
$$
= ₹\left[10000 \times\left(\frac{11}{10}\right)^{4}\right] = ₹14641.
$$
Hence, the amount after 4 years is **₹14641**.

#### Alternative method:

Here, $P=₹10000$, $R=10\%$ p.a. and $T=4$ years.
$$
\begin{aligned}
\therefore \quad \text { amount after } 4 \text { years } & =₹\left\{P \times\left(1+\frac{R}{100}\right)^{T}\right\} \\
& =₹\left\{10000 \times\left(1+\frac{10}{100}\right)^{4}\right\} \\
& =₹\left\{10000 \times\left(\frac{11}{10}\right)^{4}\right\}=₹14641.
\end{aligned}
$$
Hence, the amount after 4 years is **₹14641**.

---

### Example 4:

A manufacturer reckons that the value of a machine which costs him ₹125000 will depreciate each year by $20\%$. Find the estimated value of the machine at the end of 5 years.

#### Solution:

**Short-cut method**
$$
\begin{aligned}
\text{Value of the machine after 5 years } & =₹\left\{125000 \times\left(1-\frac{20}{100}\right)^{5}\right\} \\
& =₹\left\{125000 \times\left(\frac{4}{5}\right)^{5}\right\} \\
& =₹\left(\frac{125000 \times 1024}{3125}\right)=₹40960.
\end{aligned}
$$
Hence, the value of the machine after 5 years is **₹40960**.

**Alternative method**

Initial value of the machine = ₹125000.

Value of the machine after 1 year = $80\%$ of $₹125000 = ₹\left(125000 \times \frac{80}{100}\right) = ₹100000$.

Value of the machine after 2 years = $80\%$ of $₹100000 = ₹\left(100000 \times \frac{80}{100}\right) = ₹80000$.

Thus, the year-wise values of the machine are $₹125000, ₹100000, ₹80000, \ldots$.

Here, $\frac{100000}{125000}=\frac{4}{5}, \frac{80000}{100000}=\frac{4}{5}$, etc.

Thus, these amounts form a GP with $a=125000$ and $r=\frac{4}{5}$.

Value after 5 years = $6^{th} \text{ term} = T_6 = ar^{(6-1)} = ar^5$
$$
\begin{aligned}
& =₹\left\{125000 \times\left(\frac{4}{5}\right)^{5}\right\} \\
& =₹\left(\frac{125000 \times 1024}{3125}\right)=₹40960.
\end{aligned}
$$

---

### Example 5:

The number of bacteria in a certain culture doubles every hour. If there were 30 bacteria present in the culture originally, how many bacteria would be present at the end of the 2nd hour, 4th hour and nth hour?

#### Solution:

The bacteria present in the culture originally, at the end of the 1st hour, at the end of the 2nd hour, at the end of the 3rd hour and so on, are $30, 60, 120, 240, \ldots$.

This is a GP with $a=30$ and $r=\frac{60}{30}=2$.

Number of bacteria at the end of the 2nd hour = $T_3 = ar^2 = (30 \times 2^2) = \textbf{120}$.

Number of bacteria at the end of the 4th hour = $T_5 = ar^4 = (30 \times 2^4) = \textbf{480}$.

Number of bacteria at the end of the nth hour = $T_{n+1} = ar^{(n+1-1)} = \textbf{30} \times \textbf{2}^{\textbf{n}}$.

---

### Example 6:

The inventor of the chessboard suggested a reward of one grain of wheat for the first square; 2 grains for the second; 4 grains for the third; and so on, doubling the number of grains for subsequent squares. How many grains would have to be given to the inventor? (Note that there are 64 squares in the chessboard.)

#### Solution:

Required number of grains:
$$
\begin{aligned}
& =1+2^{1}+2^{2}+2^{3}+\ldots \text{ to 64 terms} \\
& =1+\left(2^{1}+2^{2}+2^{3}+\ldots 2^{63}\right) \\
& =1+\frac{2\left(2^{63}-1\right)}{(2-1)}=\left(1+2^{64}-2\right)=\left(2^{64}-1\right)
\end{aligned}
$$
The total number of grains is $\boldsymbol{(2^{64}-1)}$.

---

### Example 7:

The lengths of three unequal edges of a rectangular solid block are in GP. The volume of the block is $216 \text{ cm}^3$ and the total surface area is $252 \text{ cm}^2$. Find the length of its longest edge.

#### Solution:

Let the lengths of its edges be $\frac{a}{r} \text{ cm}, a \text{ cm}$ and $ar \text{ cm}$.

Then, its volume = $(\frac{a}{r} \times a \times ar) \text{ cm}^3 = a^3 \text{ cm}^3$.
$$
\therefore \quad a^{3}=216=6^{3} \Rightarrow a=6
$$
So, the edges are $6r \text{ cm}, 6 \text{ cm}$ and $\frac{6}{r} \text{ cm}$.
$$
\begin{array}{lrl}
\therefore & & \text { surface area }= & =2[l b+b h+l h] \\
& & & =2\left[36 r \times 6+6 \times \frac{6}{r}+6 r \times \frac{6}{r}\right] \mathrm{cm}^{2} \\
& & & =72 \times\left[r+\frac{1}{r}+1\right] \mathrm{cm}^{2} . \\
\therefore & 252 & =72 \times\left(r+\frac{1}{r}+1\right) \\
\Rightarrow & \frac{252}{72} & =\left(r+\frac{1}{r}+1\right) \\
\Rightarrow & \frac{7}{2} & =\frac{r^{2}+r+1}{r} \\
\Rightarrow & 7 r & =2\left(r^{2}+r+1\right) \\
\Rightarrow & 2 r^{2}-5 r+2 & =0 \\
\Rightarrow & (2 r-1)(r-2) & =0 \Rightarrow r=2 \text { or } r=\frac{1}{2} .
\end{array}
$$
Each value of $r$ gives the longest edge = **12 cm**.

---

