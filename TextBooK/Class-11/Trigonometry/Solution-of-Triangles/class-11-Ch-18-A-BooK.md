# Solution of Triangles

The three sides and three angles of a triangle are called the **parts** of the triangle.

When at least three parts of a triangle are known (i.e., any three parts), we can compute the measures of the remaining three parts.

The process of computing the measures of unknown parts of a triangle from those of the given parts is known as **solving the triangle**.

---

## The Oblique Triangle

A triangle which does not contain a right angle is called an **oblique triangle**.

In a $\triangle ABC$, we denote the lengths of the sides as $BC=a$, $CA=b$ and $AB=c$.

---

## Theorem 1: Sine Formula (Sine Rule)

In any triangle, the sides are proportional to the sines of the opposite angles. That is, in a $\triangle ABC$,

$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}
$$

### Proof

Let $\triangle ABC$ be any triangle. We know that the sum of all the angles of a triangle is $180^{\circ}$. So, each angle of a triangle cannot be obtuse. Let us assume here that $\angle B$ is acute.

Now, we consider the following cases:
- (i) $\angle C$ is acute
- (ii) $\angle C$ is obtuse
- (iii) $\angle C$ is a right angle

Draw $AD \perp BC$ or $BC$ produced. Let $AD=h$. Then, in each figure, we have:

$$
\frac{AD}{AB}=\sin B \Rightarrow \frac{h}{c}=\sin B \Rightarrow h=c \sin B \tag{1}
$$

Also, we have:
- In Fig. (i), $\frac{AD}{AC}=\sin C \Rightarrow \frac{h}{b}=\sin C \Rightarrow h=b \sin C$.
- In Fig. (ii), $\frac{AD}{AC}=\sin (\pi-C)=\sin C \Rightarrow \frac{h}{b}=\sin C \Rightarrow h=b \sin C$.
- In Fig. (iii), $\frac{AD}{AC}=1=\sin \frac{\pi}{2}=\sin C \Rightarrow \frac{h}{b}=\sin C \Rightarrow h=b \sin C$.

Thus, in each case, we have: $h=b \sin C$.

From (1) and the conclusion above, we get:

$$
c \sin B=b \sin C \Rightarrow \frac{b}{\sin B}=\frac{c}{\sin C}
$$

Similarly, $\frac{b}{\sin B}=\frac{a}{\sin A}$.

Hence, $\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}$.

---

## Theorem 2: Cosine Formulae

Let $a$, $b$ and $c$ be the lengths of sides of $\triangle ABC$, opposite to $\angle A, \angle B$ and $\angle C$ respectively. Then,

- (i) $a^{2}=b^{2}+c^{2}-2 b c \cos A$
- (ii) $b^{2}=c^{2}+a^{2}-2 c a \cos B$
- (iii) $c^{2}=a^{2}+b^{2}-2 a b \cos C$

### Proof

Let $\triangle ABC$ be given.

From the first figure, we get:
$$
\begin{aligned}
BC^{2} & =B D^{2}+D C^{2} \\
& =B D^{2}+(A C-A D)^{2} \\
& =B D^{2}+A D^{2}+A C^{2}-2 A C \cdot A D \\
& =A B^{2}+A C^{2}-2 A C \cdot A B \cos A \quad \left[\because B D^{2}+A D^{2}=A B^{2} \text{ and } A D=A B \cos A\right] \\
& =A C^{2}+A B^{2}-2 A C \cdot A B \cos A \\
\Rightarrow \quad a^{2} & =b^{2}+c^{2}-2 b c \cos A .
\end{aligned}
$$

From the second figure, we get:
$$
\begin{aligned}
BC^{2} & =B D^{2}+C D^{2} \\
& =B D^{2}+(A D-A C)^{2} \\
& =B D^{2}+A D^{2}+A C^{2}-2 A C \cdot A D \\
& =A B^{2}+A C^{2}-2 A C \cdot A B \cos A \quad \left[\because B D^{2}+A D^{2}=A B^{2} \text{ and } A D=A B \cos A\right]
\end{aligned}
$$
$\Rightarrow a^{2}=b^{2}+c^{2}-2 b c \cos A$.

Hence, from both the cases, we get:
$$
a^{2}=b^{2}+c^{2}-2 b c \cos A
$$

Similarly, $b^{2}=c^{2}+a^{2}-2 c a \cos B$ and $c^{2}=a^{2}+b^{2}-2 a b \cos C$.

### Remarks

A convenient method of writing cosine formulae is given below:
- (i) $\cos A=\frac{(b^{2}+c^{2}-a^{2})}{2 b c}$
- (ii) $\cos B=\frac{(c^{2}+a^{2}-b^{2})}{2 c a}$
- (iii) $\cos C=\frac{(a^{2}+b^{2}-c^{2})}{2 a b}$

---

## Theorem 3: Napier's Analogies

In any $\triangle ABC$, prove that:
- (i) $\tan \frac{(B-C)}{2}=\frac{(b-c)}{(b+c)} \cot \frac{A}{2}$
- (ii) $\tan \frac{(C-A)}{2}=\frac{(c-a)}{(c+a)} \cot \frac{B}{2}$
- (iii) $\tan \frac{(A-B)}{2}=\frac{(a-b)}{(a+b)} \cot \frac{C}{2}$

### Proof

By the sine formula, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k \text{ (say)}
$$

Then, $a=k \sin A$, $b=k \sin B$ and $c=k \sin C$.

(i)
$$
\begin{aligned}
\therefore \frac{(b-c)}{(b+c)} &= \frac{k \sin B-k \sin C}{k \sin B+k \sin C} \\
&= \frac{(\sin B-\sin C)}{(\sin B+\sin C)}=\frac{2 \cos \frac{(B+C)}{2} \sin \frac{(B-C)}{2}}{2 \sin \frac{(B+C)}{2} \cos \frac{(B-C)}{2}} \\
&= \cot \frac{(B+C)}{2} \tan \frac{(B-C)}{2} \\
&= \cot \left(\frac{\pi}{2}-\frac{A}{2}\right) \tan \frac{(B-C)}{2} \quad \left[\because \frac{A}{2}+\frac{(B+C)}{2}=\frac{\pi}{2}\right] \\
&= \tan \frac{A}{2} \tan \frac{(B-C)}{2} \\
\Rightarrow \quad \tan \frac{(B-C)}{2} &= \frac{(b-c)}{(b+c)} \cot \frac{A}{2} .
\end{aligned}
$$
Similarly, (ii) and (iii) may be proved.

---

# Summary

1.  **Sine Formula**
    $$
    \frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}
    $$
2.  **Cosine Formulae**
    - (i) $a^{2}=b^{2}+c^{2}-2 b c \cos A$
    - (ii) $b^{2}=c^{2}+a^{2}-2 c a \cos B$
    - (iii) $c^{2}=a^{2}+b^{2}-2 a b \cos C$

---

# Solved Examples

### Example: 1

In any $\triangle ABC$, prove that $a(\sin B-\sin C)+b(\sin C-\sin A)+c(\sin A-\sin B)=0$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k \text{ (say)}
$$
$\Rightarrow a=k \sin A$, $b=k \sin B$ and $c=k \sin C$.

$\therefore$ LHS $= a(\sin B-\sin C)+b(\sin C-\sin A)+c(\sin A-\sin B)$
$= k \sin A(\sin B-\sin C)+k \sin B(\sin C-\sin A)+k \sin C(\sin A-\sin B)$
$= k[(\sin A \sin B-\sin A \sin C)+(\sin B \sin C-\sin A \sin B)+(\sin A \sin C-\sin B \sin C)] = k \times 0 = 0$.

---

### Example: 2

In any $\triangle ABC$, prove that $a \sin (B-C)+b \sin (C-A)+c \sin (A-B)=0$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}
$$
$\Rightarrow \frac{\sin A}{a}=\frac{\sin B}{b}=\frac{\sin C}{c}=k \text{ (say)}$
$\Rightarrow \sin A=k a$, $\sin B=k b$ and $\sin C=k c$.

Substituting the values of $\sin B$ and $\sin C$ and using cosine formulae, we have:
$$
\begin{aligned}
a \sin (B-C) & =a(\sin B \cos C-\cos B \sin C) \\
& =a\left[k b \cdot \frac{(a^{2}+b^{2}-c^{2})}{2 a b}-k c \cdot \frac{(c^{2}+a^{2}-b^{2})}{2 a c}\right] \\
& \left.=\frac{k}{2} \cdot\left[(a^{2}+b^{2}-c^{2})-(c^{2}+a^{2}-b^{2})\right]=k(b^{2}-c^{2})\right] .
\end{aligned}
$$
Similarly, $b \sin (C-A)=b(\sin C \cos A-\cos C \sin A)=k(c^{2}-a^{2})$.
And, $c \sin (A-B)=c(\sin A \cos B-\cos A \sin B)=k(a^{2}-b^{2})$.
$$
\begin{aligned}
\therefore \quad a & \sin (B-C)+b \sin (C-A)+c \sin (A-B) \\
& =k(b^{2}-c^{2})+k(c^{2}-a^{2})+k(a^{2}-b^{2}) \\
& =k(b^{2}-c^{2}+c^{2}-a^{2}+a^{2}-b^{2})=k \times 0=0 .
\end{aligned}
$$

---

### Example: 3

In any $\triangle ABC$, prove that $\frac{\sin (B-C)}{\sin (B+C)}=\frac{(b^{2}-c^{2})}{a^{2}}$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k \text{ (say)}
$$
$\Rightarrow a=k \sin A$, $b=k \sin B$ and $c=k \sin C$.
$$
\begin{aligned}
\therefore \quad \text{RHS} &= \frac{(b^{2}-c^{2})}{a^{2}}=\frac{k^{2} \sin ^{2} B-k^{2} \sin ^{2} C}{k^{2} \sin ^{2} A} \\
&= \frac{(\sin ^{2} B-\sin ^{2} C)}{\sin ^{2} A}=\frac{\sin (B+C) \cdot \sin (B-C)}{\sin ^{2}(B+C)} \quad [\because A=\pi-(B+C) \Rightarrow \sin A = \sin(B+C)] \\
&= \frac{\sin (B-C)}{\sin (B+C)}=\text{LHS}
\end{aligned}
$$
Hence, $\frac{\sin (B-C)}{\sin (B+C)}=\frac{(b^{2}-c^{2})}{a^{2}}$.

---

### Example: 4

In any $\triangle ABC$, prove that $\frac{(a-b)}{c} \cos \frac{C}{2}=\sin \frac{(A-B)}{2}$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k(\text{ say})
$$
$\Rightarrow a=k \sin A, b=k \sin B$ and $c=k \sin C$.
$$
\begin{aligned}
\therefore \quad \text{LHS} &= \frac{(a-b)}{c} \cos \frac{C}{2} \\
&= \frac{(k \sin A-k \sin B)}{k \sin C} \cos \frac{C}{2}=\frac{(\sin A-\sin B)}{\sin C} \cdot \cos \frac{C}{2} \\
&= \frac{2 \cos \frac{(A+B)}{2} \sin \frac{(A-B)}{2}}{2 \sin \frac{C}{2} \cos \frac{C}{2}} \cdot \cos \frac{C}{2} \\
&= \frac{\cos \left(\frac{\pi}{2}-\frac{C}{2}\right) \cdot \sin \frac{(A-B)}{2}}{\sin \frac{C}{2}} \quad \left[\because \frac{A+B}{2}=\frac{\pi}{2}-\frac{C}{2}\right] \\
&= \frac{\sin \frac{C}{2} \cdot \sin \frac{(A-B)}{2}}{\sin \frac{C}{2}}=\sin \frac{(A-B)}{2}=\text{RHS.}
\end{aligned}
$$
Hence, $\frac{(a-b)}{c} \cos \frac{C}{2}=\sin \frac{(A-B)}{2}$.

---

### Example: 5

In any $\triangle ABC$, prove that $\frac{(b^{2}-c^{2})}{a^{2}} \sin 2 A+\frac{(c^{2}-a^{2})}{b^{2}} \sin 2 B+\frac{(a^{2}-b^{2})}{c^{2}} \sin 2 C=0$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k(\text{ say})
$$
$\Rightarrow a=k \sin A, b=k \sin B$ and $c=k \sin C$.
Applying sine rule and cosine formula, we get:
$$
\begin{align*}
\frac{(b^{2}-c^{2})}{a^{2}} \sin 2 A &= \frac{(b^{2}-c^{2})}{a^{2}} \cdot(2 \sin A \cos A) \\
&= \frac{(b^{2}-c^{2})}{a^{2}}\left(\frac{2 a}{k}\right) \cdot \frac{(b^{2}+c^{2}-a^{2})}{2 b c} \quad \left[\because \sin A=\frac{a}{k} \text{ and } \cos A=\frac{(b^{2}+c^{2}-a^{2})}{2 b c}\right] \\
&= \frac{1}{(k a b c)} \cdot(b^{2}-c^{2})(b^{2}+c^{2}-a^{2}) \tag{i}
\end{align*}
$$
Similarly,
$$
\frac{(c^{2}-a^{2})}{b^{2}} \sin 2 B=\frac{1}{(k a b c)} \cdot(c^{2}-a^{2})(c^{2}+a^{2}-b^{2}) \tag{ii}
$$
And,
$$
\frac{(a^{2}-b^{2})}{c^{2}} \sin 2 C=\frac{1}{(k a b c)} \cdot(a^{2}-b^{2})(a^{2}+b^{2}-c^{2}) \tag{iii}
$$
From (i), (ii) and (iii), we get:
$$
\begin{aligned}
\text{LHS} &= \frac{1}{(k a b c)} \cdot\left[(b^{2}-c^{2})(b^{2}+c^{2}-a^{2})+(c^{2}-a^{2})(c^{2}+a^{2}-b^{2})+(a^{2}-b^{2})(a^{2}+b^{2}-c^{2})\right] \\
&= \frac{1}{(k a b c)} \times 0=0=\text{RHS} .
\end{aligned}
$$

---

### Example: 6

In any $\triangle ABC$, prove that $\frac{(b-c)}{(b+c)}=\frac{\tan \frac{1}{2}(B-C)}{\tan \frac{1}{2}(B+C)}$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k \text{ (say)}
$$
$\Rightarrow a=k \sin A, b=k \sin B$ and $c=k \sin C$.
$$
\begin{aligned}
\therefore \quad \text{LHS} &= \frac{(b-c)}{(b+c)}=\frac{k \sin B-k \sin C}{k \sin B+k \sin C}=\frac{(\sin B-\sin C)}{(\sin B+\sin C)} \\
&= \frac{2 \cos \frac{(B+C)}{2} \sin \frac{(B-C)}{2}}{2 \sin \frac{(B+C)}{2} \cos \frac{(B-C)}{2}} \\
&= \frac{\tan \frac{1}{2}(B-C)}{\tan \frac{1}{2}(B+C)}=\text{RHS}
\end{aligned}
$$

---

### Example: 7

In any $\triangle ABC$, prove that $a(\cos C-\cos B)=2(b-c) \cos ^{2} \frac{A}{2}$.

#### Solution:

Applying cosine formulae, we have:
$$
\begin{aligned}
\text{LHS} &= a(\cos C-\cos B) \\
&= a\left[\frac{(a^{2}+b^{2}-c^{2})}{2 a b}-\frac{(a^{2}+c^{2}-b^{2})}{2 a c}\right] = \frac{(a^{2} c+b^{2} c-c^{3}-a^{2} b-b c^{2}+b^{3})}{2 b c} \\
&= \frac{(b^{3}-c^{3})+(b^{2} c-b c^{2})-(a^{2} b-a^{2} c)}{2 b c} = \frac{(b^{3}-c^{3})+b c(b-c)-a^{2}(b-c)}{2 b c} \\
&= (b-c) \frac{[(b^{2}+c^{2}+b c)+b c-a^{2}]}{2 b c}=(b-c) \cdot\left\{\frac{(b^{2}+c^{2}-a^{2})}{2 b c}+\frac{2 b c}{2 b c}\right\} \\
&= (b-c)\left\{\frac{(b^{2}+c^{2}-a^{2})}{2 b c}+1\right\}=(b-c)(1+\cos A) \\
&= 2(b-c) \cos ^{2} \frac{A}{2}=\text{RHS.}
\end{aligned}
$$

---

### Example: 8

In any $\triangle ABC$, prove that $a \cos A+b \cos B+c \cos C=2 a \sin B \sin C$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k \text{ (say)}
$$
$\Rightarrow a=k \sin A, b=k \sin B$ and $c=k \sin C$.
$$
\begin{aligned}
\therefore \quad \text{LHS} &= a \cos A+b \cos B+c \cos C \\
&= k \sin A \cos A+k \sin B \cos B+k \sin C \cos C \\
&= \frac{1}{2} k(\sin 2 A+\sin 2 B+\sin 2 C) \\
&= \frac{1}{2} k[2 \sin (A+B) \cos (A-B)+2 \sin C \cos C] \\
&= k[\sin (A+B) \cos (A-B)+\sin C \cos C] \\
&= k[\sin (\pi-C) \cos (A-B)+\sin C \cos C] \\
&= k \sin C[\cos (A-B)+\cos C] \\
&= k \sin C[\cos (A-B)+\cos \{\pi-(A+B)\}] \\
&= k \sin C[\cos (A-B)-\cos (A+B)] \\
&= k \sin C \times 2 \sin A \sin B \\
&= 2(k \sin A) \sin B \sin C \\
&= 2 a \sin B \sin C=\text{RHS}
\end{aligned}
$$

---

### Example: 9

In any $\triangle ABC$, prove that $(b^{2}-c^{2}) \cot A+(c^{2}-a^{2}) \cot B+(a^{2}-b^{2}) \cot C=0$.

#### Solution:

By the sine rule, we have:
$$
\frac{\sin A}{a}=\frac{\sin B}{b}=\frac{\sin C}{c}=k \text{ (say)}
$$
$\Rightarrow \sin A=k a, \sin B=k b$ and $\sin C=k c$.
$$
\begin{aligned}
\therefore (b^{2}-c^{2}) \cot A &= \frac{(b^{2}-c^{2}) \cdot \cos A}{\sin A}=\frac{(b^{2}-c^{2})}{k a} \cdot \frac{(b^{2}+c^{2}-a^{2})}{2 b c} \\
&= \frac{1}{(2 k a b c)} \cdot(b^{2}-c^{2})(b^{2}+c^{2}-a^{2}) = \frac{(b^{4}-c^{4}-a^{2} b^{2}+a^{2} c^{2})}{2 k a b c}
\end{aligned}
$$
Similarly, $(c^{2}-a^{2}) \cot B=\frac{(c^{4}-a^{4}-b^{2} c^{2}+a^{2} b^{2})}{2 k a b c}$.
And, $(a^{2}-b^{2}) \cot C=\frac{(a^{4}-b^{4}-a^{2} c^{2}+b^{2} c^{2})}{2 k a b c}$.
$$
\begin{aligned}
\therefore \quad \text{LHS} &= \frac{1}{2 k a b c} \cdot\left[(b^{4}-c^{4}-a^{2} b^{2}+a^{2} c^{2})+(c^{4}-a^{4}-b^{2} c^{2}+a^{2} b^{2})+(a^{4}-b^{4}-a^{2} c^{2}+b^{2} c^{2})\right] \\
&= \frac{1}{2 k a b c} \times 0=0=\text{RHS} .
\end{aligned}
$$

---

### Example: 10

In any $\triangle ABC$, prove that $a^{3} \sin (B-C)+b^{3} \sin (C-A)+c^{3} \sin (A-B)=0$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k(\text{ say})
$$
$\Rightarrow a=k \sin A, b=k \sin B$ and $c=k \sin C$.
$$
\begin{aligned}
\therefore \quad a^{3} \sin (B-C) &= k^{3} \sin ^{3} A \cdot \sin (B-C) \\
&= k^{3} \sin ^{2} A \cdot \sin A \cdot \sin (B-C) \\
&= k^{3} \sin ^{2} A[\sin \{\pi-(B+C)\} \sin (B-C)] \quad [\because A=\pi-(B+C)] \\
&= k^{3} \sin ^{2} A[\sin (B+C) \sin (B-C)] \\
&= k^{3} \sin ^{2} A \cdot(\sin ^{2} B-\sin ^{2} C)
\end{aligned}
$$
Similarly, $b^{3} \sin (C-A)=k^{3} \sin ^{2} B(\sin ^{2} C-\sin ^{2} A)$.
And, $c^{3} \sin (A-B)=k^{3} \sin ^{2} C(\sin ^{2} A-\sin ^{2} B)$.
$$
\begin{aligned}
\therefore \quad & a^{3} \sin (B-C) +b^{3} \sin (C-A)+c^{3} \sin (A-B) \\
& = k^{3} \sin ^{2} A(\sin ^{2} B-\sin ^{2} C)+k^{3} \sin ^{2} B(\sin ^{2} C-\sin ^{2} A) +k^{3} \sin ^{2} C(\sin ^{2} A-\sin ^{2} B) \\
& = 0
\end{aligned}
$$

---

### Example: 11

In any $\triangle ABC$, prove that $(a-b)^{2} \cos ^{2} \frac{C}{2}+(a+b)^{2} \sin ^{2} \frac{C}{2}=c^{2}$.

#### Solution:

We have:
$$
\begin{aligned}
\text{LHS} &= (a-b)^{2} \cos ^{2} \frac{C}{2}+(a+b)^{2} \sin ^{2} \frac{C}{2} \\
&= (a^2 - 2ab + b^2)\cos^2\frac{C}{2} + (a^2 + 2ab + b^2)\sin^2\frac{C}{2} \\
&= a^{2}(\cos ^{2} \frac{C}{2}+\sin ^{2} \frac{C}{2})+b^{2}(\cos ^{2} \frac{C}{2}+\sin ^{2} \frac{C}{2}) - 2ab \cos^2\frac{C}{2} + 2ab \sin^2\frac{C}{2} \\
&= a^{2}+b^{2}-2 a b(\cos ^{2} \frac{C}{2}-\sin ^{2} \frac{C}{2}) \\
&= a^{2}+b^{2}-2 a b \cos C = c^{2}=\text{RHS.} \quad \text{[by cosine formula]}
\end{aligned}
$$

---

### Example: 12

In a $\triangle ABC$, prove that $(b-c) \cot \frac{A}{2}+(c-a) \cot \frac{B}{2}+(a-b) \cot \frac{C}{2}=0$.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}=k(\text{ say})
$$
$\Rightarrow a=k \sin A, b =k \sin B$ and $c=k \sin C$.
$$
\begin{aligned}
\therefore \quad (b-c) \cot \frac{A}{2} &= k(\sin B-\sin C) \cot \frac{A}{2} \\
&= 2 k \cos \frac{(B+C)}{2} \sin \frac{(B-C)}{2} \cdot \frac{\cos (\frac{A}{2})}{\sin (\frac{A}{2})} \\
&= 2 k \cos \left(\frac{\pi}{2}-\frac{A}{2}\right) \sin \frac{(B-C)}{2} \cdot \frac{\cos (\frac{A}{2})}{\sin (\frac{A}{2})} \\
&= 2 k \sin \frac{A}{2} \sin \frac{(B-C)}{2} \cdot \frac{\cos (\frac{A}{2})}{\sin (\frac{A}{2})} \\
&= 2 k \sin \frac{(B-C)}{2} \cdot \cos \frac{A}{2} \\
&= 2 k \sin \frac{(B-C)}{2} \cdot \cos \left\{\frac{\pi}{2}-\frac{(B+C)}{2}\right\} \\
&= 2 k \sin \frac{(B-C)}{2} \cdot \sin \frac{(B+C)}{2} \\
&= k(\cos C-\cos B) .
\end{aligned}
$$
Similarly, we have:
$(c-a) \cot \frac{B}{2}=k(\cos A-\cos C)$ and $(a-b) \cot \frac{C}{2}=k(\cos B-\cos A)$.
$$
\begin{aligned}
\therefore \quad &(b-c) \cot \frac{A}{2}+(c-a) \cot \frac{B}{2}+(a-b) \cot \frac{C}{2} \\
&= k \cdot[(\cos C-\cos B)+(\cos A-\cos C)+(\cos B-\cos A)]=0 .
\end{aligned}
$$

---

### Example: 13

In a $\triangle ABC$, if $\cos A=\frac{\sin B}{2 \sin C}$, show that the triangle is isosceles.

#### Solution:

By the sine rule, we have:
$$
\frac{\sin A}{a}=\frac{\sin B}{b}=\frac{\sin C}{c}=k(\text{ say})
$$
$\Rightarrow \sin A=k a, \sin B=k b$ and $\sin C=k c$.
$$
\begin{aligned}
\therefore \quad \cos A=\frac{\sin B}{2 \sin C} &\Rightarrow \frac{(b^{2}+c^{2}-a^{2})}{2 b c}=\frac{k b}{2 k c} \\
&\Rightarrow (b^{2}+c^{2}-a^{2})=b^{2} \\
&\Rightarrow c^{2}=a^{2} \Rightarrow |c|=|a| \\
&\Rightarrow AB=BC
\end{aligned}
$$
Hence, $\triangle ABC$ is isosceles.

---

### Example: 14

In a $\triangle ABC$, if $a \cos A=b \cos B$, show that the triangle is either isosceles or right-angled.

#### Solution:

By the sine rule, we have:
$$
\frac{a}{\sin A}=\frac{b}{\sin B}=k(\text{ say})
$$
$\Rightarrow a=k \sin A$ and $b=k \sin B$.
$$
\begin{aligned}
\therefore a \cos A=b \cos B &\Rightarrow k \sin A \cos A=k \sin B \cos B \\
&\Rightarrow \frac{1}{2}(\sin 2 A)=\frac{1}{2}(\sin 2 B) \\
&\Rightarrow \sin 2 A=\sin 2 B \\
&\Rightarrow \sin 2 A-\sin 2 B=0 \\
&\Rightarrow 2 \cos (A+B) \sin (A-B)=0 \\
&\Rightarrow \cos (A+B)=0 \text{ or } \sin (A-B)=0 \\
&\Rightarrow (A+B)=\frac{\pi}{2} \text{ or } (A-B)=0 \\
&\Rightarrow \angle C=\frac{\pi}{2} \text{ or } A=B
\end{aligned}
$$
Hence, $\triangle ABC$ is right-angled or isosceles.

---

### Example: 15

In a $\triangle ABC$, if $a=18, b=24, c=30$; find:
(i) $\sin A, \sin B, \sin C$
(ii) $\cos A, \cos B, \cos C$

#### Solution:

Here, $a^{2}+b^{2}=(18)^{2}+(24)^{2}=(324+576)=900=(30)^{2}=c^{2}$.
$\therefore \triangle ABC$ is right-angled at $C$. Thus, $\angle C=90^{\circ}$.

(i) By sine rule, we have:
$$
\frac{\sin A}{a}=\frac{\sin B}{b}=\frac{\sin C}{c}=k(\text{ say})
$$
$\Rightarrow \frac{\sin A}{18}=\frac{\sin B}{24}=\frac{\sin C}{30}=k$
$\therefore \sin A=18 k, \sin B=24 k$ and $\sin C=30 k$.

But, $\angle C=90^{\circ} \Rightarrow \sin C=\sin 90^{\circ}=1 \Rightarrow 30 k=1 \Rightarrow k=\frac{1}{30}$.
$\therefore \sin A=18 k=(18 \times \frac{1}{30})=\frac{3}{5}$; $\sin B=24 k=(24 \times \frac{1}{30})=\frac{4}{5}$; and $\sin C=30 k=(30 \times \frac{1}{30})=1$.
Hence, $\sin A=\frac{3}{5}, \sin B=\frac{4}{5}$ and $\sin C=1$.

(ii) Using cosine formulae, we get:
$$
\cos A=\frac{b^{2}+c^{2}-a^{2}}{2 b c} = \frac{(24)^{2}+(30)^{2}-(18)^{2}}{2 \times 24 \times 30} = \frac{576+900-324}{1440}=\frac{1152}{1440}=\frac{4}{5}
$$
$$
\cos B=\frac{c^{2}+a^{2}-b^{2}}{2 c a} = \frac{(30)^{2}+(18)^{2}-(24)^{2}}{2 \times 30 \times 18} = \frac{(900+324-576)}{1080}=\frac{648}{1080}=\frac{3}{5}
$$
$$
\cos C = \cos 90^{\circ}=0
$$
Hence, $\cos A=\frac{4}{5}, \cos B=\frac{3}{5}$ and $\cos C=0$.

---

### Example: 16

In a $\triangle ABC$, if $\angle A=45^{\circ}, \angle B=60^{\circ}$ and $\angle C=75^{\circ}$, find the ratio of its sides.

#### Solution:

By the sine formula, we have:
$$
\begin{aligned}
a: b: c & =\sin A: \sin B: \sin C \\
& =\sin 45^{\circ}: \sin 60^{\circ}: \sin 75^{\circ} \\
& =\frac{1}{\sqrt{2}}: \frac{\sqrt{3}}{2}: \frac{(\sqrt{3}+1)}{2 \sqrt{2}} = 2: \sqrt{6}:(\sqrt{3}+1)
\end{aligned}
$$

---

### Example: 17

In a $\triangle ABC$, if $a=2, b=3$ and $\sin A=\frac{2}{3}$, find $\angle B$.

#### Solution:

$$
\frac{a}{\sin A}=\frac{b}{\sin B} \Rightarrow \frac{2}{(2 / 3)}=\frac{3}{\sin B}
$$
$$
\Rightarrow \sin B=\left(3 \times \frac{2}{3} \times \frac{1}{2}\right)=1
$$
$$
\Rightarrow \angle B=90^{\circ}
$$

---

### Example: 18

The angles of a triangle $ABC$ are in AP and if it is being given that $b: c=\sqrt{3}: \sqrt{2}$, find $\angle A, \angle B$ and $\angle C$.

#### Solution:

$\angle A, \angle B, \angle C$ are in AP.
$\Rightarrow 2 \angle B=\angle A+\angle C$
$\Rightarrow 3 \angle B=\angle A+\angle B+\angle C=180^{\circ}$
$\Rightarrow \angle B=60^{\circ}$.

Now, $\frac{b}{\sin B}=\frac{c}{\sin C} \Rightarrow \frac{b}{c}=\frac{\sin B}{\sin C}$.
$$
\Rightarrow \frac{\sqrt{3}}{\sqrt{2}}=\frac{\sin 60^{\circ}}{\sin C}
$$
$$
\Rightarrow \sin C=\left(\frac{\sqrt{3}}{2} \times \sqrt{2} \times \frac{1}{\sqrt{3}}\right)=\frac{1}{\sqrt{2}}
$$
$\Rightarrow \angle C=45^{\circ}$.

$\therefore \angle A=180^{\circ}-(\angle B+\angle C)=[180^{\circ}-(60^{\circ}+45^{\circ})]=75^{\circ}$.
Hence, $\angle A=75^{\circ}, \angle B=60^{\circ}$ and $\angle C=45^{\circ}$.

---

### Example: 19

In a $\triangle ABC$, if $\angle A=30^{\circ}$ and $b: c=2: \sqrt{3}$, find $\angle B$.

#### Solution:

Let $b=2k$ and $c=\sqrt{3}k$. Then,
$$
\cos A=\frac{b^{2}+c^{2}-a^{2}}{2 b c}
$$
$$
\Rightarrow \cos 30^{\circ}=\frac{4 k^{2}+3 k^{2}-a^{2}}{4 \sqrt{3} k^{2}}
$$
$$
\Rightarrow \frac{\sqrt{3}}{2} \times 4 \sqrt{3} k^{2}=7 k^{2}-a^{2}
$$
$$
\Rightarrow 6k^2 = 7k^2 - a^2 \Rightarrow k^{2}=a^{2} \Rightarrow k=a
$$
Thus, $b=2a$ and $c=\sqrt{3}a$.
Now, $\frac{a}{\sin A}=\frac{b}{\sin B} \Rightarrow \frac{a}{\sin 30^{\circ}}=\frac{2 a}{\sin B}$.
$$
\Rightarrow \quad \sin B=\left(2 a \times \frac{1}{2} \times \frac{1}{a}\right)=1
$$
$$
\Rightarrow \quad B=90^{\circ}
$$

---

### Example: 20

Solve the triangle in which $a=(\sqrt{3}+1), b=(\sqrt{3}-1)$ and $\angle C=60^{\circ}$.

#### Solution:

Using $\tan \frac{(A-B)}{2}=\frac{(a-b)}{(a+b)} \cot \frac{C}{2}$, we get:
*(Correction: The formula used in the document is for `(a-b)`, but the proof uses `(b-c)`. Let's assume the question meant `(a-b)` as it proceeds with that)*
$$
\tan \frac{(A-B)}{2}=\frac{(\sqrt{3}+1)-(\sqrt{3}-1)}{(\sqrt{3}+1)+(\sqrt{3}-1)} \cot \frac{60^{\circ}}{2} = \frac{2}{2 \sqrt{3}} \cot 30^{\circ}=\left(\frac{1}{\sqrt{3}} \times \sqrt{3}\right)=1
$$
$$
\Rightarrow \frac{A-B}{2}=45^{\circ} \Rightarrow A-B=90^{\circ} \tag{i}
$$
Also, $A+B+C=180^{\circ} \Rightarrow A+B=180^{\circ} - 60^{\circ} = 120^{\circ} \tag{ii}$.

On solving (i) and (ii), we get $A=105^{\circ}$ and $B=15^{\circ}$.

Also, $\cos C=\frac{a^{2}+b^{2}-c^{2}}{2 a b}$
$$
\Rightarrow \cos 60^{\circ}=\frac{(\sqrt{3}+1)^{2}+(\sqrt{3}-1)^{2}-c^{2}}{2(\sqrt{3}+1)(\sqrt{3}-1)}=\frac{(3+1+2\sqrt{3})+(3+1-2\sqrt{3})-c^2}{2(3-1)} = \frac{8-c^{2}}{4}
$$
$$
\therefore \frac{1}{2} = \frac{8-c^{2}}{4} \Rightarrow 2=8-c^{2} \Rightarrow c^{2}=6 \Rightarrow c=\sqrt{6}
$$
Hence, $c=\sqrt{6}$, $\angle A=105^{\circ}$ and $\angle B=15^{\circ}$.

---

.