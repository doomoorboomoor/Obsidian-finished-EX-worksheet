## Conditional Identities Involving the Angles of a Triangle

Before we begin, let us first recall the following formulae:

1.  $\sin x+\sin y=2 \sin \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)$
2.  $\sin x-\sin y=2 \cos \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)$
3.  $\cos x+\cos y=2 \cos \left(\frac{x+y}{2}\right) \cos \left(\frac{x-y}{2}\right)$
4.  $\cos x-\cos y=-2 \sin \left(\frac{x+y}{2}\right) \sin \left(\frac{x-y}{2}\right)$

---

## Type 1: Identities Involving Sines and Cosines

### Method

1.  Express the sum of the first two terms as a product.
2.  In this product, express the sum of two angles in terms of the third angle, using $A+B+C=\pi$.
3.  Expand the third term by using one of the following relations:
    $$
    \sin 2 \theta=2 \sin \theta \cos \theta \quad \text{and} \quad \cos 2 \theta=\left(2 \cos ^{2} \theta-1\right)=\left(1-2 \sin ^{2} \theta\right)
    $$
4.  Take the common factor outside.
5.  Express the T-ratio of a single angle into a sum of two angles, and use the necessary formula from the ones given in the box above.

---

### Example 1
If $A+B+C=\pi$, prove that:
$$
\sin 2 A+\sin 2 B+\sin 2 C=4 \sin A \sin B \sin C
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =(\sin 2 A+\sin 2 B)+\sin 2 C \\
& =2 \sin (A+B) \cos (A-B)+2 \sin C \cos C \quad [\text{by formula}] \\
& =2 \sin (\pi-C) \cos (A-B)+2 \sin C \cos C \\
& =2 \sin C \cos (A-B)+2 \sin C \cos C \quad [\because \sin (\pi-C)=\sin C] \\
& =2 \sin C[\cos (A-B)+\cos C] \\
& =2 \sin C[\cos (A-B)+\cos \{\pi-(A+B)\}] \quad [\because C=\pi-(A+B)] \\
& =2 \sin C[\cos (A-B)-\cos (A+B)] \quad [\because \cos (\pi-\theta)=-\cos \theta] \\
& =2 \sin C[2 \sin A \sin B] \\
& =4 \sin A \sin B \sin C=\text{RHS}
\end{aligned}
$$
$\therefore \sin 2 A+\sin 2 B+\sin 2 C=4 \sin A \sin B \sin C$.

---

### Example 2
If $A+B+C=\pi$, prove that:
$$
\sin 2 A-\sin 2 B+\sin 2 C=4 \cos A \sin B \cos C
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =(\sin 2 A-\sin 2 B)+\sin 2 C \\
& =2 \cos (A+B) \sin (A-B)+2 \sin C \cos C \quad [\text{by formula}] \\
& =2 \cos (\pi-C) \sin (A-B)+2 \sin C \cos C \\
& =-2 \cos C \sin (A-B)+2 \sin C \cos C \quad [\because \cos (\pi-C)=-\cos C] \\
& =-2 \cos C[\sin (A-B)-\sin C] \\
& =-2 \cos C[\sin (A-B)-\sin \{\pi-(A+B)\}] \quad [\because C=\pi-(A+B)] \\
& =-2 \cos C[\sin (A-B)-\sin (A+B)] \\
& =-2 \cos C[-2 \cos A \sin B] \\
& =4 \cos A \sin B \cos C=\text{RHS}
\end{aligned}
$$
$\therefore \sin 2 A - \sin 2 B + \sin 2 C = 4 \cos A \sin B \cos C$.

---

### Example 3
If $A+B+C=\pi$, prove that:
$$
\cos 2 A+\cos 2 B+\cos 2 C=-1-4 \cos A \cos B \cos C
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =\cos 2 A+\cos 2 B+\cos 2 C \\
& =2 \cos (A+B) \cos (A-B)+2 \cos ^{2} C-1 \\
& =2 \cos (\pi-C) \cos (A-B)+2 \cos ^{2} C-1 \\
& =-2 \cos C \cos (A-B)+2 \cos ^{2} C-1 \\
& =-2 \cos C[\cos (A-B)-\cos C]-1 \\
& =-1-2 \cos C[\cos (A-B)-\cos \{\pi-(A+B)\}] \\
& =-1-2 \cos C[\cos (A-B)+\cos (A+B)] \\
& =-1-2 \cos C[2 \cos A \cos B] \\
& =-1-4 \cos A \cos B \cos C=\text{RHS}
\end{aligned}
$$
$\therefore \cos 2 A+\cos 2 B+\cos 2 C=-1-4 \cos A \cos B \cos C$.

---

### Example 4
If $A+B+C=\pi$, prove that:
$$
\cos 2 A+\cos 2 B-\cos 2 C=1-4 \sin A \sin B \cos C
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =(\cos 2 A+\cos 2 B)-\cos 2 C \\
& =2 \cos (A+B) \cos (A-B)-(2 \cos ^{2} C-1) \\
& =2 \cos (\pi-C) \cos (A-B)-2 \cos ^{2} C+1 \\
& =-2 \cos C \cos (A-B)-2 \cos ^{2} C+1 \\
& =1-2 \cos C[\cos (A-B)+\cos C] \\
& =1-2 \cos C[\cos (A-B)+\cos \{\pi-(A+B)\}] \\
& =1-2 \cos C[\cos (A-B)-\cos (A+B)] \\
& =1-2 \cos C[2 \sin A \sin B] \\
& =1-4 \sin A \sin B \cos C=\text{RHS}
\end{aligned}
$$
$\therefore \cos 2 A + \cos 2 B - \cos 2 C = 1-4 \sin A \sin B \cos C$.

---

### Example 5
If $A+B+C=\pi$, prove that:
$$
\cos 4 A+\cos 4 B+\cos 4 C=-1+4 \cos 2 A \cos 2 B \cos 2 C
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} &= \cos 4 A+\cos 4 B+\cos 4 C \\
&= 2 \cos (2 A+2 B) \cos (2 A-2 B)+\cos 4 C \\
&= 2 \cos (2 \pi-2 C) \cos (2 A-2 B)+\left(2 \cos ^{2} 2 C-1\right) \quad [\because A+B+C=\pi \Rightarrow 2 A+2 B=2 \pi-2 C] \\
&= 2 \cos 2 C \cos (2 A-2 B)+2 \cos ^{2} 2 C-1 \\
&= 2 \cos 2 C[\cos (2 A-2 B)+\cos 2 C]-1 \\
&= 2 \cos 2 C[\cos (2 A-2 B)+\cos \{2 \pi-(2 A+2 B)\}]-1 \quad [\because 2 A+2 B+2 C=2 \pi \Rightarrow 2 C=2 \pi-(2 A+2 B)] \\
&= 2 \cos 2 C[\cos (2 A-2 B)+\cos (2 A+2 B)]-1 \\
&= 2 \cos 2 C[2 \cos 2 A \cos 2 B]-1 \\
&= -1+4 \cos 2 A \cos 2 B \cos 2 C=\text{RHS}
\end{aligned}
$$
$\therefore \cos 4 A+\cos 4 B+\cos 4 C=-1+4 \cos 2 A \cos 2 B \cos 2 C$.

---

### Example 6
If $A+B+C=\pi$, prove that:
$$
\sin A+\sin B-\sin C=4 \sin \frac{A}{2} \sin \frac{B}{2} \cos \frac{C}{2}
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =(\sin A+\sin B)-\sin C \\
& =2 \sin \left(\frac{A+B}{2}\right) \cos \left(\frac{A-B}{2}\right)-2 \sin \frac{C}{2} \cos \frac{C}{2} \\
& =2 \sin \left(\frac{\pi}{2}-\frac{C}{2}\right) \cos \left(\frac{A-B}{2}\right)-2 \sin \frac{C}{2} \cos \frac{C}{2} \quad \left[\because \frac{A+B}{2}=\frac{\pi}{2}-\frac{C}{2}\right] \\
& =2 \cos \frac{C}{2} \cos \left(\frac{A-B}{2}\right)-2 \sin \frac{C}{2} \cos \frac{C}{2} \\
& =2 \cos \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)-\sin \frac{C}{2}\right] \\
& =2 \cos \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)-\sin \left\{\frac{\pi}{2}-\left(\frac{A+B}{2}\right)\right\}\right] \\
& =2 \cos \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)-\cos \left(\frac{A+B}{2}\right)\right] \\
& =2 \cos \frac{C}{2}\left[2 \sin \frac{A}{2} \sin \frac{B}{2}\right] \\
& =4 \sin \frac{A}{2} \sin \frac{B}{2} \cos \frac{C}{2}=\text{RHS}
\end{aligned}
$$
$\therefore \sin A+\sin B-\sin C=4 \sin \frac{A}{2} \sin \frac{B}{2} \cos \frac{C}{2}$.

---

### Example 7
If $A+B+C=\pi$, prove that:
$$
\cos A+\cos B-\cos C=\left(4 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}\right)-1
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =(\cos A+\cos B)-\cos C \\
& =2 \cos \left(\frac{A+B}{2}\right) \cos \left(\frac{A-B}{2}\right)-\left(1-2 \sin ^{2} \frac{C}{2}\right) \\
& =2 \cos \left(\frac{\pi}{2}-\frac{C}{2}\right) \cos \left(\frac{A-B}{2}\right)-1+2 \sin ^{2} \frac{C}{2} \\
& =2 \sin \frac{C}{2} \cos \left(\frac{A-B}{2}\right) -1 + 2\sin^2 \frac{C}{2} \\
& =2 \sin \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)+\sin \frac{C}{2}\right]-1 \\
& =2 \sin \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)+\sin \left\{\frac{\pi}{2}-\frac{(A+B)}{2}\right\}\right]-1 \\
& =2 \sin \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)+\cos \left(\frac{A+B}{2}\right)\right]-1 \\
& =2 \sin \frac{C}{2}\left\{2 \cos \frac{A}{2} \cos \frac{B}{2}\right\}-1 \\
& =\left\{4 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}\right\}-1=\text{RHS}
\end{aligned}
$$
$\therefore \cos A + \cos B - \cos C = \left(4 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}\right)-1$.

---

## Type 2: Identities Involving Squares of Sines and Cosines

### Method
Change the squares of sines and cosines into cosines of double the angles by using the formulae:
$$
\cos ^{2} \theta=\frac{1}{2}(1+\cos 2 \theta) \quad \text{and} \quad \sin ^{2} \theta=\frac{1}{2}(1-\cos 2 \theta)
$$
Now, proceed as above.

---

### Example 8
If $A+B+C=\pi$, prove that:
$$
\sin ^{2} A+\sin ^{2} B+\sin ^{2} C=2(1+\cos A \cos B \cos C)
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =\sin ^{2} A+\sin ^{2} B+\sin ^{2} C \\
& =\frac{1}{2}(1-\cos 2 A)+\frac{1}{2}(1-\cos 2 B)+\frac{1}{2}(1-\cos 2 C) \\
& =\frac{3}{2}-\frac{1}{2}(\cos 2 A+\cos 2 B+\cos 2 C) \\
& =\frac{3}{2}-\frac{1}{2}(-1-4 \cos A \cos B \cos C) \quad [\text{see Example 3}] \\
& =2+2 \cos A \cos B \cos C=2(1+\cos A \cos B \cos C)=\text{RHS}
\end{aligned}
$$
$\therefore \sin ^{2} A + \sin ^{2} B + \sin ^{2} C = 2(1+\cos A \cos B \cos C)$.

---

### Example 9
If $A+B+C=\pi$, prove that:
$$
\cos ^{2} A+\cos ^{2} B-\cos ^{2} C=1-2 \sin A \sin B \cos C
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =\cos ^{2} A+\cos ^{2} B-\cos ^{2} C \\
& =\frac{1}{2}(1+\cos 2 A)+\frac{1}{2}(1+\cos 2 B)-\frac{1}{2}(1+\cos 2 C) \\
& =\frac{1}{2}+\frac{1}{2}(\cos 2 A+\cos 2 B-\cos 2 C) \\
& =\frac{1}{2}+\frac{1}{2}(1-4 \sin A \sin B \cos C) \quad [\text{see Example 4}] \\
& =1-2 \sin A \sin B \cos C=\text{RHS}
\end{aligned}
$$
$\therefore \cos ^{2} A + \cos ^{2} B - \cos ^{2} C = 1-2 \sin A \sin B \cos C$.

---

### Example 10
In a $\triangle ABC$, prove that:
$$
\cos ^{2} A+\cos ^{2}\left(A+\frac{\pi}{3}\right)+\cos ^{2}\left(A-\frac{\pi}{3}\right)=\frac{3}{2}
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} &= \cos ^{2} A+\cos ^{2}\left(A+\frac{\pi}{3}\right)+\cos ^{2}\left(A-\frac{\pi}{3}\right) \\
&= \frac{1}{2}(1+\cos 2 A)+\frac{1}{2}\left\{1+\cos \left(2 A+\frac{2 \pi}{3}\right)\right\}+\frac{1}{2}\left\{1+\cos \left(2 A-\frac{2 \pi}{3}\right)\right\} \\
&= \frac{3}{2}+\frac{1}{2} \cos 2 A+\frac{1}{2}\left\{\cos \left(2 A+\frac{2 \pi}{3}\right)+\cos \left(2 A-\frac{2 \pi}{3}\right)\right\} \\
&= \frac{3}{2}+\frac{1}{2} \cos 2 A+\cos 2 A \cos \frac{2 \pi}{3} \quad [\because \cos (A+B)+\cos (A-B)=2 \cos A \cos B] \\
&= \frac{3}{2}+\frac{1}{2} \cos 2 A-\frac{1}{2} \cos 2 A \quad \left[\because \cos \frac{2 \pi}{3}=-\frac{1}{2}\right] \\
&= \frac{3}{2}=\text{RHS}
\end{aligned}
$$

---

### Example 11
If $A+B+C=\pi$, prove that:
$$
\sin ^{2} \frac{A}{2}+\sin ^{2} \frac{B}{2}-\sin ^{2} \frac{C}{2}=1-2 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} &=\sin ^{2} \frac{A}{2}+\sin ^{2} \frac{B}{2}-\sin ^{2} \frac{C}{2} \\
&=\frac{1}{2}(1-\cos A)+\frac{1}{2}(1-\cos B)-\frac{1}{2}(1-\cos C) \\
&=\frac{1}{2}-\frac{1}{2}(\cos A+\cos B-\cos C) \\
&=\frac{1}{2}-\frac{1}{2}\left[\left(4 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}\right)-1\right] \quad [\text{see Example 7}] \\
&=1-2 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}=\text{RHS}
\end{aligned}
$$
$\therefore \sin ^{2} \frac{A}{2}+\sin ^{2} \frac{B}{2}-\sin ^{2} \frac{C}{2}=1-2 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}$.

---

### Example 12
If $A+B+C=\pi$, prove that:
$$
\cos ^{2} \frac{A}{2}+\cos ^{2} \frac{B}{2}-\cos ^{2} \frac{C}{2}=2 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} &=\cos ^{2} \frac{A}{2}+\cos ^{2} \frac{B}{2}-\cos ^{2} \frac{C}{2} \\
&=\frac{1}{2}(1+\cos A)+\frac{1}{2}(1+\cos B)-\frac{1}{2}(1+\cos C) \\
&=\frac{1}{2}+\frac{1}{2}(\cos A+\cos B-\cos C) \\
&=\frac{1}{2}+\frac{1}{2}\left[\left(4 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}\right)-1\right] \\
&=2 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}=\text{RHS}
\end{aligned}
$$
$\therefore \cos ^{2} \frac{A}{2}+\cos ^{2} \frac{B}{2}-\cos ^{2} \frac{C}{2}=2 \cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2}$.

---

### Example 13
If $A+B+C=\pi$, prove that:
$$
\cos ^{2} \frac{A}{2}+\cos ^{2} \frac{B}{2}+\cos ^{2} \frac{C}{2}=2\left(1+\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2}\right)
$$

#### Solution:
We have:
$$
\begin{aligned}
\text{LHS} & =\cos ^{2} \frac{A}{2}+\cos ^{2} \frac{B}{2}+\cos ^{2} \frac{C}{2} \\
& =\frac{1}{2}(1+\cos A)+\frac{1}{2}(1+\cos B)+\frac{1}{2}(1+\cos C) \\
& =\frac{3}{2}+\frac{1}{2}(\cos A+\cos B+\cos C) \\
& = \frac{3}{2}+\frac{1}{2}\left[2 \cos \left(\frac{A+B}{2}\right) \cos \left(\frac{A-B}{2}\right)+\cos C\right] \\
& = \frac{3}{2}+\cos \left(\frac{\pi}{2}-\frac{C}{2}\right) \cos \left(\frac{A-B}{2}\right)+\frac{1}{2}\left(1-2 \sin ^{2} \frac{C}{2}\right) \quad \left[\because \left(\frac{A+B}{2}\right)=\left(\frac{\pi}{2}-\frac{C}{2}\right) \text{ and } \cos C=1-2 \sin ^{2} \frac{C}{2}\right] \\
& = 2+\sin \frac{C}{2} \cos \left(\frac{A-B}{2}\right)-\sin ^{2} \frac{C}{2} \\
& = 2+\sin \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)-\sin \frac{C}{2}\right] \\
& = 2+\sin \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)-\sin \left\{\frac{\pi}{2}-\left(\frac{A+B}{2}\right)\right\}\right] \\
& = 2+\sin \frac{C}{2}\left[\cos \left(\frac{A-B}{2}\right)-\cos \left(\frac{A+B}{2}\right)\right] \\
& = 2+\sin \frac{C}{2}\left(2 \sin \frac{A}{2} \sin \frac{B}{2}\right) \\
& = 2\left(1+\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2}\right)=\text{RHS}
\end{aligned}
$$
$\therefore \cos ^{2} \frac{A}{2}+\cos ^{2} \frac{B}{2}+\cos ^{2} \frac{C}{2}=2\left(1+\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2}\right)$.

---

## Type 3: Identities Involving Tangents

### Method
1.  Using $A+B+C=\pi$, express the sum of two angles in terms of the third.
2.  Take tangents on both sides and expand the **LHS**.
3.  Cross multiply and transpose.

Similarly, we proceed for identities involving cotangents.

---

### Example 14
If $A+B+C=\pi$, prove that:
$$
\tan A+\tan B+\tan C=\tan A \tan B \tan C
$$

#### Solution:
Here, $A+B+C=\pi$.
$$
\begin{align*}
\Rightarrow \quad &(A+B)=(\pi-C) \\
\Rightarrow \quad &\tan (A+B)=\tan (\pi-C) \\
\Rightarrow \quad &\frac{\tan A+\tan B}{1-\tan A \tan B}=-\tan C \\
\Rightarrow \quad &\tan A+\tan B=-\tan C+\tan A \tan B \tan C \\
\Rightarrow \quad &\tan A+\tan B+\tan C=\tan A \tan B \tan C
\end{align*}
$$

---

### Example 15
If $A+B+C=\pi$, prove that:
$$
\tan \frac{A}{2} \tan \frac{B}{2}+\tan \frac{B}{2} \tan \frac{C}{2}+\tan \frac{C}{2} \tan \frac{A}{2}=1
$$

#### Solution:
Here, $A+B+C=\pi$.
$$
\begin{align*}
\Rightarrow \quad &\left(\frac{A}{2}+\frac{B}{2}\right)=\left(\frac{\pi}{2}-\frac{C}{2}\right) \\
\Rightarrow \quad &\tan \left(\frac{A}{2}+\frac{B}{2}\right)=\tan \left(\frac{\pi}{2}-\frac{C}{2}\right)=\cot \frac{C}{2} \\
\Rightarrow \quad &\frac{\tan \frac{A}{2}+\tan \frac{B}{2}}{1-\tan \frac{A}{2} \tan \frac{B}{2}}=\frac{1}{\tan \frac{C}{2}} \\
\Rightarrow \quad &\tan \frac{C}{2} \tan \frac{A}{2}+\tan \frac{B}{2} \tan \frac{C}{2}=1-\tan \frac{A}{2} \tan \frac{B}{2} \\
\Rightarrow \quad &\tan \frac{A}{2} \tan \frac{B}{2}+\tan \frac{B}{2} \tan \frac{C}{2}+\tan \frac{C}{2} \tan \frac{A}{2}=1
\end{align*}
$$

---

### Example 16
If $A+B+C=\pi$, prove that:
$$
\cot B \cot C+\cot C \cot A+\cot A \cot B=1
$$

#### Solution:
Here, $A+B+C=\pi$.
$$
\begin{align*}
\Rightarrow \quad &(A+B)=(\pi-C) \\
\Rightarrow \quad &\cot (A+B)=\cot (\pi-C)=-\cot C \\
\Rightarrow \quad &\frac{\cot A \cot B-1}{\cot A+\cot B}=-\cot C \\
\Rightarrow \quad &\cot A \cot B-1=-\cot C \cot A-\cot B \cot C \\
\Rightarrow \quad &\cot B \cot C+\cot C \cot A+\cot A \cot B=1
\end{align*}
$$

---

### Example 17
If $A+B+C=\pi$, prove that:
$$
\cot \frac{A}{2}+\cot \frac{B}{2}+\cot \frac{C}{2}=\cot \frac{A}{2} \cot \frac{B}{2} \cot \frac{C}{2}
$$

#### Solution:
Here, $A+B+C=\pi$.
$$
\begin{align*}
\Rightarrow \quad &\left(\frac{A}{2}+\frac{B}{2}\right)=\left(\frac{\pi}{2}-\frac{C}{2}\right) \\
\Rightarrow \quad &\cot \left(\frac{A}{2}+\frac{B}{2}\right)=\cot \left(\frac{\pi}{2}-\frac{C}{2}\right)=\tan \frac{C}{2} \\
\Rightarrow \quad &\frac{\cot \frac{A}{2} \cot \frac{B}{2}-1}{\cot \frac{A}{2}+\cot \frac{B}{2}}=\frac{1}{\cot \frac{C}{2}} \\
\Rightarrow \quad &\cot \frac{A}{2}+\cot \frac{B}{2}=\cot \frac{A}{2} \cot \frac{B}{2} \cot \frac{C}{2}-\cot \frac{C}{2} \\
\Rightarrow \quad &\cot \frac{A}{2}+\cot \frac{B}{2}+\cot \frac{C}{2}=\cot \frac{A}{2} \cot \frac{B}{2} \cot \frac{C}{2}
\end{align*}
$$

---

