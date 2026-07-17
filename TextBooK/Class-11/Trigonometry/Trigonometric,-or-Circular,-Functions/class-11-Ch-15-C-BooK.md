## Some More Trigonometric Functions

---

### **Theorem 1**

For all $x, y \in R$, we have
1.  $2 \sin x \cos y=\sin (x+y)+\sin (x-y)$
2.  $2 \cos x \sin y=\sin (x+y)-\sin (x-y)$
3.  $2 \cos x \cos y=\cos (x+y)+\cos (x-y)$
4.  $2 \sin x \sin y=\cos (x-y)-\cos (x+y)$

**Proof:**

We know that
$$
\begin{align*}
& \sin (x+y)=\sin x \cos y+\cos x \sin y \tag{i} \\
& \sin (x-y)=\sin x \cos y-\cos x \sin y \tag{ii}
\end{align*}
$$

(a) Adding (i) and (ii), we get
$$
2 \sin x \cos y=\sin (x+y)+\sin (x-y)
$$

(b) Subtracting (ii) from (i), we get
$$
2 \cos x \sin y=\sin (x+y)-\sin (x-y)
$$

Further, we know that
$$
\begin{align*}
& \cos (x+y)=\cos x \cos y-\sin x \sin y \tag{iii} \\
& \cos (x-y)=\cos x \cos y+\sin x \sin y \tag{iv}
\end{align*}
$$

(c) Adding (iii) and (iv), we get
$$
2 \cos x \cos y=\cos (x+y)+\cos (x-y)
$$

(d) Subtracting (iii) from (iv), we get
$$
2 \sin x \sin y=\cos (x-y)-\cos (x+y)
$$

---

### **Theorem 2**

For all $x, y \in R$, we have
1.  $\sin x+\sin y=2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)$
2.  $\sin x-\sin y=2 \cos \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)$
3.  $\cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)$
4.  $\cos x-\cos y=-2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)$

**Proof:**

Putting $x=(a+b)$ and $y=(a-b)$, we get $a=\left(\frac{x+y}{2}\right)$ and $b=\left(\frac{x-y}{2}\right)$.

(i) $\sin x+\sin y=\sin (a+b)+\sin (a-b)$
$$
\begin{aligned}
& =2 \sin a \cos b \\
& =2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)
\end{aligned}
$$

(ii) $\sin x-\sin y=\sin (a+b)-\sin (a-b)$
$$
\begin{aligned}
& =2 \cos a \sin b \\
& =2 \cos \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)
\end{aligned}
$$

(iii) $\cos x+\cos y=\cos (a+b)+\cos (a-b)$
$$
\begin{aligned}
& =2 \cos a \cos b \\
& =2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)
\end{aligned}
$$

(iv) $\cos x-\cos y=\cos (a+b)-\cos (a-b)$
$$
\begin{aligned}
& =-2 \sin a \sin b \\
& =-2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)
\end{aligned}
$$

These formulae may be listed as under:

1.  $\sin C+\sin D=2 \sin \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right)$
2.  $\sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$
3.  $\cos C+\cos D=2 \cos \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right)$
4.  $\cos C-\cos D=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$

---

## Solved Examples

### Example 1

Prove that
(i) $\cos \left(\frac{\pi}{4}+x\right)+\cos \left(\frac{\pi}{4}-x\right)=\sqrt{2} \cos x$
(ii) $\cos \left(\frac{3 \pi}{4}+x\right)-\cos \left(\frac{3 \pi}{4}-x\right)=-\sqrt{2} \sin x$

#### Solution

(i) **LHS** = $\cos \left(\frac{\pi}{4}+x\right)+\cos \left(\frac{\pi}{4}-x\right)$
$$
\begin{aligned}
& =2 \cos \frac{\pi}{4} \cos x \quad [\because \cos (A+B)+\cos (A-B)=2 \cos A \cos B] \\
& =\left(2 \times \frac{1}{\sqrt{2}} \cos x\right)=\sqrt{2} \cos x = \textbf{RHS}
\end{aligned}
$$

(ii) **LHS** = $\cos \left(\frac{3 \pi}{4}+x\right)-\cos \left(\frac{3 \pi}{4}-x\right)$
$$
\begin{aligned}
& =-2 \sin \frac{3 \pi}{4} \sin x \quad [\because \cos (A+B)-\cos (A-B)=-2 \sin A \sin B] \\
& =-2 \sin \left(\pi-\frac{\pi}{4}\right) \sin x \\
& =-2 \sin \frac{\pi}{4} \sin x \quad \left[\because \sin \left(\pi-\frac{\pi}{4}\right)=\sin \frac{\pi}{4}\right] \\
& =\left(-2 \times \frac{1}{\sqrt{2}}\right) \sin x=-\sqrt{2} \sin x = \textbf{RHS}
\end{aligned}
$$

---

### Example 2

Express each of the following as an algebraic sum of sines or cosines:
(i) $2 \sin 3 x \cos 2 x$
(ii) $2 \cos 4 x \sin 2 x$
(iii) $2 \cos 6 x \cos 4 x$
(iv) $2 \sin 3 x \sin 5 x$

#### Solution

(i) We know that $2 \sin A \cos B=\sin (A+B)+\sin (A-B)$.
$$
\begin{aligned}
\therefore 2 \sin 3 x \cos 2 x & =\sin (3 x+2 x)+\sin (3 x-2 x) \\
& =\sin 5 x+\sin x
\end{aligned}
$$

(ii) We know that $2 \cos A \sin B=\sin (A+B)-\sin (A-B)$.
$$
\begin{aligned}
\therefore 2 \cos 4 x \sin 2 x & =\sin (4 x+2 x)-\sin (4 x-2 x) \\
& =\sin 6 x-\sin 2 x
\end{aligned}
$$

(iii) We know that $2 \cos A \cos B=\cos (A+B)+\cos (A-B)$.
$$
\begin{aligned}
\therefore 2 \cos 6 x \cos 4 x & =\cos (6 x+4 x)+\cos (6 x-4 x) \\
& =\cos 10 x+\cos 2 x
\end{aligned}
$$

(iv) We know that $2 \sin A \sin B=\cos (A-B)-\cos (A+B)$.
$$
\begin{aligned}
\therefore 2 \sin 3 x \sin 5 x & =2 \sin 5 x \sin 3 x \\
& =\cos (5 x-3 x)-\cos (5 x+3 x) \\
& =\cos 2 x-\cos 8 x
\end{aligned}
$$

---

### Example 3

Express each of the following as a product of sines or cosines or sine and cosine:
(i) $\cos 5 x+\cos 3 x$
(ii) $\cos 5 x-\cos 7 x$
(iii) $\sin 7 x+\sin 3 x$
(iv) $\sin 5 x-\sin 3 x$

#### Solution

(i) We know that $\cos C+\cos D=2 \cos \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right)$.
$$
\begin{aligned}
\therefore \cos 5 x+\cos 3 x & =2 \cos \left(\frac{5 x+3 x}{2}\right) \cos \left(\frac{5 x-3 x}{2}\right) \\
& =2 \cos 4 x \cos x
\end{aligned}
$$

(ii) We know that $\cos C-\cos D=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$.
$$
\begin{aligned}
\therefore \cos 5 x-\cos 7 x & =-2 \sin \left(\frac{5 x+7 x}{2}\right) \sin \left(\frac{5 x-7 x}{2}\right) \\
& =-2 \sin 6 x \sin (-x)=2 \sin 6 x \sin x
\end{aligned}
$$

(iii) We know that $\sin C+\sin D=2 \sin \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right)$.
$$
\begin{aligned}
\therefore \sin 7 x+\sin 3 x & =2 \sin \left(\frac{7 x+3 x}{2}\right) \cos \left(\frac{7 x-3 x}{2}\right) \\
& =2 \sin 5 x \cos 2 x
\end{aligned}
$$

(iv) We know that $\sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)$.
$$
\begin{aligned}
\therefore \sin 5 x-\sin 3 x & =2 \cos \left(\frac{5 x+3 x}{2}\right) \sin \left(\frac{5 x-3 x}{2}\right) \\
& =2 \cos 4 x \sin x
\end{aligned}
$$

---

### Example 4

Prove that $\frac{\cos 6 x+\cos 4 x}{\sin 6 x-\sin 4 x}=\cot x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{\cos 6 x+\cos 4 x}{\sin 6 x-\sin 4 x} \\
& =\frac{2 \cos \left(\frac{6 x+4 x}{2}\right) \cos \left(\frac{6 x-4 x}{2}\right)}{2 \cos \left(\frac{6 x+4 x}{2}\right) \sin \left(\frac{6 x-4 x}{2}\right)} \quad \left\{\begin{array}{c}\because \cos C+\cos D=2 \cos \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right) \\ \text { and } \sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\end{array}\right\} \\
& =\frac{2 \cos 5 x \cos x}{2 \cos 5 x \sin x}=\frac{\cos x}{\sin x} \\
& =\cot x = \textbf{RHS}
\end{aligned}
$$

---

### Example 5

Prove that $\frac{\sin 3 x-\sin x}{\cos x-\cos 3 x}=\cot 2 x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{\sin 3 x-\sin x}{\cos x-\cos 3 x} \\
& =\frac{2 \cos \left(\frac{3 x+x}{2}\right) \sin \left(\frac{3 x-x}{2}\right)}{-2 \sin \left(\frac{x+3 x}{2}\right) \sin \left(\frac{x-3 x}{2}\right)} \quad \left\{\begin{array}{c}\because \sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right) \\ \text { and } \cos C-\cos D=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\end{array}\right\} \\
& =\frac{\cos 2 x \sin x}{-\sin 2 x \sin (-x)}=\frac{\cos 2 x \sin x}{\sin 2 x \sin x} \\
& =\cot 2 x=\textbf{RHS}
\end{aligned}
$$

---

### Example 6

Prove that $\frac{\sin 3 x-\sin x}{\cos 2 x}=2 \sin x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{\sin 3 x-\sin x}{\cos 2 x} \\
& =\frac{2 \cos \left(\frac{3 x+x}{2}\right) \sin \left(\frac{3 x-x}{2}\right)}{\cos 2 x} \quad \left[\because \sin C-\sin D=2 \cos \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\right] \\
& =\frac{2 \cos 2 x \sin x}{\cos 2 x}=2 \sin x=\textbf{RHS}
\end{aligned}
$$

---

### Example 7

Prove that $\frac{\sin 5 x-2 \sin 3 x+\sin x}{\cos 5 x-\cos x}=\operatorname{cosec} 2 x-\cot 2 x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{(\sin 5 x+\sin x)-2 \sin 3 x}{\cos 5 x-\cos x} \\
& =\frac{2 \sin \left(\frac{5 x+x}{2}\right) \cos \left(\frac{5 x-x}{2}\right)-2 \sin 3 x}{-2 \sin \left(\frac{5 x+x}{2}\right) \sin \left(\frac{5 x-x}{2}\right)} \quad \left[\begin{array}{c}\because \sin C+\sin D=2 \sin \left(\frac{C+D}{2}\right) \cos \left(\frac{C-D}{2}\right) \text { and } \\ \cos C-\cos D=-2 \sin \left(\frac{C+D}{2}\right) \sin \left(\frac{C-D}{2}\right)\end{array}\right] \\
& =\frac{2 \sin 3 x \cos 2 x-2 \sin 3 x}{-2 \sin 3 x \sin 2 x}=\frac{2 \sin 3 x(\cos 2 x-1)}{-2 \sin 3 x \sin 2 x} \\
& =\frac{(1-\cos 2 x)}{\sin 2 x}=\frac{1}{\sin 2 x}-\frac{\cos 2 x}{\sin 2 x} \\
& =\operatorname{cosec} 2 x-\cot 2 x=\textbf{RHS}
\end{aligned}
$$

---

### Example 8

If $\frac{\cos (A+B)}{\cos (A-B)}=\frac{\sin (C+D)}{\sin (C-D)}$, prove that $\tan A \tan B \tan C+\tan D=0$.

#### Solution

We have
$$
\begin{aligned}
& \frac{\cos (A+B)}{\cos (A-B)}=\frac{\sin (C+D)}{\sin (C-D)} \\
\Rightarrow & \frac{\cos (A+B)+\cos (A-B)}{\cos (A+B)-\cos (A-B)}=\frac{\sin (C+D)+\sin (C-D)}{\sin (C+D)-\sin (C-D)} \\
\Rightarrow & \frac{2 \cos A \cos B}{-2 \sin A \sin B}=\frac{2 \sin C \cos D}{2 \cos C \sin D} \\
\Rightarrow & -\cot A \cot B=\tan C \cot D \\
\Rightarrow & \tan A \tan B \tan C=-\tan D \\
\Rightarrow & \tan A \tan B \tan C+\tan D=0
\end{aligned}
$$
Hence, $\tan A \tan B \tan C+\tan D=0$.

---

### Example 9

Prove that $\frac{\cos 4 x+\cos 3 x+\cos 2 x}{\sin 4 x+\sin 3 x+\sin 2 x}=\cot 3 x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{(\cos 4 x+\cos 2 x)+\cos 3 x}{(\sin 4 x+\sin 2 x)+\sin 3 x} \\
& =\frac{2 \cos \left(\frac{4 x+2 x}{2}\right) \cos \left(\frac{4 x-2 x}{2}\right)+\cos 3 x}{2 \sin \left(\frac{4 x+2 x}{2}\right) \cos \left(\frac{4 x-2 x}{2}\right)+\sin 3 x} \quad [\text { using formulae for }(\cos C+\cos D) \text { and }(\sin C+\sin D)] \\
& =\frac{2 \cos 3 x \cos x+\cos 3 x}{2 \sin 3 x \cos x+\sin 3 x}=\frac{\cos 3 x(2 \cos x+1)}{\sin 3 x(2 \cos x+1)} \\
& =\frac{\cos 3 x}{\sin 3 x}=\cot 3 x=\textbf{RHS}
\end{aligned}
$$

---

### Example 10

Prove that $\sin x+\sin 3 x+\sin 5 x+\sin 7 x=4 \sin 4 x \cos 2 x \cos x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =(\sin 7 x+\sin x)+(\sin 5 x+\sin 3 x) \\
& =2 \sin \left(\frac{7 x+x}{2}\right) \cos \left(\frac{7 x-x}{2}\right)+2 \sin \left(\frac{5 x+3 x}{2}\right) \cos \left(\frac{5 x-3 x}{2}\right) \\
& =2 \sin 4 x \cos 3 x+2 \sin 4 x \cos x \\
& =2 \sin 4 x(\cos 3 x+\cos x) \\
& =(2 \sin 4 x) \times 2 \cos \left(\frac{3 x+x}{2}\right) \cos \left(\frac{3 x-x}{2}\right) \\
& =(2 \sin 4 x) \times 2 \cos 2 x \cos x \\
& =4 \sin 4 x \cos 2 x \cos x=\textbf{RHS}
\end{aligned}
$$

---

### Example 11

Prove that $\cos 2 x \cos \frac{x}{2}-\cos 3 x \cos \frac{9 x}{2}=-\sin 5 x \sin \left(\frac{5 x}{2}\right)$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{1}{2}\left[2 \cos 2 x \cos \frac{x}{2}-2 \cos 3 x \cos \frac{9 x}{2}\right] \\
& =\frac{1}{2}\left[\cos \left(2 x+\frac{x}{2}\right)+\cos \left(2 x-\frac{x}{2}\right)\right]-\frac{1}{2}\left[\cos \left(\frac{9 x}{2}+3 x\right)+\cos \left(\frac{9 x}{2}-3 x\right)\right] \\
& =\frac{1}{2}\left(\cos \frac{5 x}{2}+\cos \frac{3 x}{2}\right)-\frac{1}{2}\left(\cos \frac{15 x}{2}+\cos \frac{3 x}{2}\right) \\
& =\frac{1}{2}\left(\cos \frac{5 x}{2}-\cos \frac{15 x}{2}\right) \\
& =\frac{1}{2}\left[-2 \sin \frac{\left(\frac{5 x}{2}+\frac{15 x}{2}\right)}{2} \sin \frac{\left(\frac{15 x}{2}-\frac{5 x}{2}\right)}{2}\right] \\
& =-\sin 5 x \sin \left(\frac{5 x}{2}\right)=\textbf{RHS}
\end{aligned}
$$

---

### Example 12

Prove that $\frac{\sin 8 x \cos x-\sin 6 x \cos 3 x}{\cos 2 x \cos x-\sin 4 x \sin 3 x}=\tan 2 x$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{2 \sin 8 x \cos x-2 \sin 6 x \cos 3 x}{2 \cos 2 x \cos x-2 \sin 4 x \sin 3 x} \\
& =\frac{[\sin (8 x+x)+\sin (8 x-x)]-[\sin (6 x+3 x)+\sin (6 x-3 x)]}{[\cos (2 x+x)+\cos (2 x-x)]-[\cos (4 x-3 x)-\cos (4 x+3 x)]} \quad [\because 2 \sin A \cos B=\sin (A+B)+\sin (A-B), \text { etc. }] \\
& =\frac{(\sin 9 x+\sin 7 x)-(\sin 9 x+\sin 3 x)}{(\cos 3 x+\cos x)-(\cos x-\cos 7 x)} \\
& =\frac{(\sin 7 x-\sin 3 x)}{(\cos 3 x+\cos 7 x)} \\
& =\frac{2 \cos \left(\frac{7 x+3 x}{2}\right) \sin \left(\frac{7 x-3 x}{2}\right)}{2 \cos \left(\frac{7 x+3 x}{2}\right) \cos \left(\frac{7 x-3 x}{2}\right)} \quad \left[\because \sin C-\sin D=2 \cos \frac{(C+D)}{2} \sin \frac{(C-D)}{2}\right] \\
& =\frac{\cos 5 x \sin 2 x}{\cos 5 x \cos 2 x}=\frac{\sin 2 x}{\cos 2 x} \\
& =\tan 2 x=\textbf{RHS}
\end{aligned}
$$

---

### Example 13

Prove that $\frac{(\sin x-\sin y)}{(\cos x+\cos y)}=\tan \left(\frac{x-y}{2}\right)$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =\frac{\sin x-\sin y}{\cos x+\cos y} \\
& =\frac{2 \cos \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)}{2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)}=\tan \left(\frac{x-y}{2}\right)=\textbf{RHS}
\end{aligned}
$$

---

### Example 14

Prove that $(\cos x+\cos y)^{2}+(\sin x+\sin y)^{2}=4 \cos ^{2}\left(\frac{x-y}{2}\right)$.

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} & =(\cos x+\cos y)^{2}+(\sin x+\sin y)^{2} \\
& =\left\{2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)\right\}^{2}+\left\{2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)\right\}^{2} \\
& =4 \cos ^{2}\left(\frac{x+y}{2}\right) \cos ^{2}\left(\frac{x-y}{2}\right)+4 \sin ^{2}\left(\frac{x+y}{2}\right) \cos ^{2}\left(\frac{x-y}{2}\right) \\
& =4 \cos ^{2}\left(\frac{x-y}{2}\right) \cdot\left\{\cos ^{2}\left(\frac{x+y}{2}\right)+\sin ^{2}\left(\frac{x+y}{2}\right)\right\} \\
& =4 \cos ^{2}\left(\frac{x-y}{2}\right)=\textbf{RHS}
\end{aligned}
$$

---

### Example 15

Prove that
$$
\begin{aligned}
\cos \alpha & +\cos \beta+\cos \gamma+\cos (\alpha+\beta+\gamma) \\
& =4 \cos \left(\frac{\alpha+\beta}{2}\right) \cos \left(\frac{\beta+\gamma}{2}\right) \cos \left(\frac{\gamma+\alpha}{2}\right)
\end{aligned}
$$

#### Solution

We have
$$
\begin{aligned}
\textbf{LHS} &= (\cos \alpha+\cos \beta)+\{\cos (\alpha+\beta+\gamma)+\cos \gamma\} \\
&= 2 \cos \left(\frac{\alpha+\beta}{2}\right) \cos \left(\frac{\alpha-\beta}{2}\right)+2 \cos \left(\frac{\alpha+\beta+2 \gamma}{2}\right) \cos \left(\frac{\alpha+\beta}{2}\right) \\
&= 2 \cos \left(\frac{\alpha+\beta}{2}\right) \cdot\left\{\cos \left(\frac{\alpha-\beta}{2}\right)+\cos \left(\frac{\alpha+\beta+2 \gamma}{2}\right)\right\} \\
&= 2 \cos \left(\frac{\alpha+\beta}{2}\right) \cdot\left\{2 \cos \left(\frac{\gamma+\alpha}{2}\right) \cos \left(\frac{\beta+\gamma}{2}\right)\right\} \quad \left[\text { using } \cos C+\cos D=2 \cos \frac{(C+D)}{2} \cos \frac{(C-D)}{2}\right] \\
&= 4 \cos \left(\frac{\alpha+\beta}{2}\right) \cos \left(\frac{\beta+\gamma}{2}\right) \cos \left(\frac{\gamma+\alpha}{2}\right)=\textbf{RHS}
\end{aligned}
$$

---

### Example 16

Prove that $\sin ^{2} 6 x-\sin ^{2} 4 x=\sin 10 x \sin 2 x$

#### Solution

**LHS** = $\sin ^{2} 6 x-\sin ^{2} 4 x$
$$
\begin{aligned}
& =\sin (6 x+4 x) \sin (6 x-4 x) \quad \left[\because \sin ^{2} x-\sin ^{2} y=\sin (x+y) \sin (x-y)\right] \\
& =\sin 10 x \sin 2 x=\textbf{RHS}
\end{aligned}
$$

---

### Example 17

Prove that $\cos 20^{\circ} \cos 40^{\circ} \cos 60^{\circ} \cos 80^{\circ}=\frac{1}{16}$.

#### Solution

We have
$$
\begin{aligned}
& \cos 20^{\circ} \cos 40^{\circ} \cos 60^{\circ} \cos 80^{\circ} \\
& = \frac{1}{2} \cos 60^{\circ} \cos 40^{\circ}\left(2 \cos 80^{\circ} \cos 20^{\circ}\right) \\
& = \frac{1}{2} \times \frac{1}{2} \cos 40^{\circ} \cdot\left\{\cos \left(80^{\circ}+20^{\circ}\right)+\cos \left(80^{\circ}-20^{\circ}\right)\right\} \\
& = \frac{1}{4} \cos 40^{\circ}\left(\cos 100^{\circ}+\cos 60^{\circ}\right) \\
& = \frac{1}{4} \cos 40^{\circ}\left(\cos 100^{\circ}+\frac{1}{2}\right) \\
& = \frac{1}{8}\left(2 \cos 100^{\circ} \cos 40^{\circ}\right)+\frac{1}{8} \cos 40^{\circ} \\
& = \frac{1}{8}\left[\cos \left(100^{\circ}+40^{\circ}\right)+\cos \left(100^{\circ}-40^{\circ}\right)\right]+\frac{1}{8} \cos 40^{\circ} \\
& = \frac{1}{8}\left(\cos 140^{\circ}+\cos 60^{\circ}\right)+\frac{1}{8} \cos 40^{\circ} \\
& = \frac{1}{8} \cos 140^{\circ}+\frac{1}{16}+\frac{1}{8} \cos 40^{\circ} \\
& = \frac{1}{8} \cos \left(180^{\circ}-40^{\circ}\right)+\frac{1}{16}+\frac{1}{8} \cos 40^{\circ} \\
& = -\frac{1}{8} \cos 40^{\circ}+\frac{1}{16}+\frac{1}{8} \cos 40^{\circ} \\
& = \frac{1}{16}=\textbf{RHS}
\end{aligned}
$$

---

### Example 18

Prove that $\sin 10^{\circ} \sin 50^{\circ} \sin 60^{\circ} \sin 70^{\circ}=\frac{\sqrt{3}}{16}$.

#### Solution

We have
$$
\begin{aligned}
& \sin 10^{\circ} \sin 50^{\circ} \sin 60^{\circ} \sin 70^{\circ} \\
& = \frac{1}{2} \sin 60^{\circ} \sin 10^{\circ}\left(2 \sin 70^{\circ} \sin 50^{\circ}\right) \\
& = \frac{1}{2} \times \frac{\sqrt{3}}{2} \times \sin 10^{\circ} \cdot\left\{\cos \left(70^{\circ}-50^{\circ}\right)-\cos \left(70^{\circ}+50^{\circ}\right)\right\} \\
& = \frac{\sqrt{3}}{4} \sin 10^{\circ} \cdot\left\{\cos 20^{\circ}-\cos 120^{\circ}\right\} \\
& = \frac{\sqrt{3}}{4} \sin 10^{\circ}\left(\cos 20^{\circ}+\frac{1}{2}\right) \quad \left[\because \cos 120^{\circ}=-\frac{1}{2}\right] \\
& = \frac{\sqrt{3}}{8}\left(2 \cos 20^{\circ} \sin 10^{\circ}\right)+\frac{\sqrt{3}}{8} \sin 10^{\circ} \\
& = \frac{\sqrt{3}}{8}\left[\sin \left(20^{\circ}+10^{\circ}\right)-\sin \left(20^{\circ}-10^{\circ}\right)\right]+\frac{\sqrt{3}}{8} \sin 10^{\circ} \\
& = \frac{\sqrt{3}}{8} \sin 30^{\circ}=\left(\frac{\sqrt{3}}{8} \times \frac{1}{2}\right)=\frac{\sqrt{3}}{16}
\end{aligned}
$$

---

{2}\right)$.