## Volume and Surface Area of a Frustum of a Cone

---

## Frustum of a Cone

When a cone is cut by a plane parallel to the base of the cone then the portion between the plane and the base is called the **frustum of the cone**.

Let $R$ and $r$ be the radii of the base and the top of the frustum of a cone.
Let $h$ be its height and $l$ be its slant height.

Then,

- **(i) Volume of the frustum of the cone**
  $$
  =\frac{\pi h}{3}\left[R^{2}+r^{2}+R r\right] \text{ cubic units.}
  $$

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-47.jpg?height=230&width=402&top_left_y=473&top_left_x=793)

- **(ii) Lateral surface area of the frustum of the cone**
  $$
  =\pi l(R+r) \text{, where } l^{2}=h^{2}+(R-r)^{2} \text{ sq units.}
  $$

- **(iii) Total surface area of the frustum of the cone**
  $$
  \begin{aligned}
  & =(\text { area of the base })+(\text { area of the top })+(\text { lateral surface area }) \\
  & =\left[\pi R^{2}+\pi r^{2}+\pi l(R+r)\right]=\pi\left[R^{2}+r^{2}+l(R+r)\right] \text{ sq units.}
  \end{aligned}
  $$

---

## Derivation of the Above Formulae

Let $H$, $R$ and $l_{1}$ be the height, radius of the base and slant height respectively of a cone $OAB$. Suppose it is cut by a plane $PQ$ parallel to its base at a height $h$ from the base to form the frustum $ABQP$.

Let the radius of the base of cone $OPQ$ be $r$ and $l$ be the slant height of the frustum so formed.

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-47.jpg?height=400&width=495&top_left_y=998&top_left_x=696)

Clearly, we have $OC=H$, $DC=h$, $OD=OC-DC=(H-h)$, $DQ=r$, $CB=R$, $OB=l_{1}$, $BQ=l$, $OQ=OB-BQ=\left(l_{1}-l\right)$.

Clearly, $\triangle ODQ \sim \triangle OCB$.
$$
\therefore \quad \frac{O D}{O C}=\frac{D Q}{C B}=\frac{O Q}{O B} \Rightarrow \frac{H-h}{H}=\frac{r}{R}=\frac{l_{1}-l}{l_{1}} . \tag{i}
$$
$$
\frac{H-h}{H}=\frac{r}{R} \Rightarrow R(H-h)=H r \Rightarrow H R-h R=H r
$$
$$
\Rightarrow \quad H(R-r)=h R \Rightarrow H=\frac{h R}{R-r} . \tag{ii}
$$
And,
$$
\frac{l_{1}-l}{l_{1}}=\frac{r}{R} \Rightarrow\left(l_{1}-l\right) R=l_{1} r \Rightarrow l_{1} R-l R=l_{1} r
$$
$$
\Rightarrow \quad l_{1}(R-r)=l R \Rightarrow l_{1}=\frac{l R}{R-r} . \tag{iii}
$$
Now, **volume of the frustum $ABQP$**
$=$ volume of the cone $OAB -$ volume of the cone $OPQ$
$$
\begin{aligned}
& =\frac{1}{3} \pi R^{2} H-\frac{1}{3} \pi r^{2}(H-h)=\frac{1}{3} \pi\left[R^{2}\left(\frac{h R}{R-r}\right)-r^{2}\left\{\frac{h R}{R-r}-h\right\}\right] \\
& =\frac{1}{3} \pi\left[\left(\frac{h R^{3}}{R-r}\right)-r^{2}\left\{\frac{h R-h R+h r}{R-r}\right\}\right]=\frac{1}{3} \pi\left[\frac{h R^{3}}{R-r}-\frac{h r^{3}}{R-r}\right] \\
& =\frac{1}{3} \pi\left[\frac{h\left(R^{3}-r^{3}\right)}{(R-r)}\right]=\frac{1}{3} \pi\left[\frac{h(R-r)\left(R^{2}+R r+r^{2}\right)}{(R-r)}\right]=\frac{1}{3} \pi h\left(R^{2}+R r+r^{2}\right) .
\end{aligned}
$$
And, **curved surface area of the frustum $ABQP$**
$$
\begin{aligned}
= & \text { curved surface area of the cone } O A B \\
& \quad-\text { curved surface area of the cone } O P Q \\
= & \pi R l_{1}-\pi r\left(l_{1}-l\right)=\pi\left[R\left(\frac{l R}{R-r}\right)-r\left\{\frac{l R}{R-r}-l\right\}\right] \\
= & \pi\left[\frac{l R^{2}}{R-r}-r\left\{\frac{l R-l R+l r}{R-r}\right\}\right]=\pi\left[\frac{l R^{2}}{R-r}-\frac{l r^{2}}{R-r}\right] \\
= & \pi\left[\frac{l\left(R^{2}-r^{2}\right)}{(R-r)}\right]=\pi\left[\frac{l(R-r)(R+r)}{(R-r)}\right]=\pi(R+r) l .
\end{aligned}
$$

---

## Solved Examples

### Example 1

An open metal bucket is in the shape of a frustum of a cone of height 21 cm with radii of its lower and upper ends as 10 cm and 20 cm respectively. Find the cost of milk which can completely fill the bucket at ₹ 30 per litre. [CBSE 2012]

#### Solution:

Let $R$ and $r$ be the radii of the top and the base of the bucket respectively, and let $h$ be its height.

Then, $R=20 \mathrm{~cm}$, $r=10 \mathrm{~cm}$ and $h=21 \mathrm{~cm}$.

Capacity of the bucket
$$
\begin{aligned}
& =\text { volume of frustum of the cone } \\
& =\frac{1}{3} \pi h\left[R^{2}+r^{2}+R r\right] \\
& =\left[\left(\frac{1}{3} \times \frac{22}{7} \times 21\right) \cdot\left\{(20)^{2}+(10)^{2}+20 \times 10\right\}\right] \mathrm{cm}^{3} \\
& =(22 \times 700) \mathrm{cm}^{3}=15400 \mathrm{~cm}^{3} .
\end{aligned}
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-48.jpg?height=301&width=261&top_left_y=1482&top_left_x=938)

Volume of milk that the bucket can hold
$$
=\left(\frac{15400}{1000}\right) \text { litres }=15.4 \text { litres }
$$
$\therefore \quad$ cost of milk $=₹(15.4 \times 30)=₹ 462$.

---

### Example 2

A bucket open at the top, and made up of a metal sheet is in the form of the frustum of a cone. The depth of the bucket is 24 cm and the diameters of its upper and lower circular ends are 30 cm and 10 cm respectively. Find the cost of metal sheet used in it at the rate of $₹ 10$ per $100 \mathrm{~m}^{2}$. [Use $\pi=3.14$.] [CBSE 2013]

#### Solution:

Radius of the upper end, $R=15 \mathrm{~cm}$.
Radius of the lower end, $r=5 \mathrm{~cm}$.
Depth of the bucket, $h=24 \mathrm{~cm}$.

Slant height of the bucket, $l=\sqrt{h^{2}+(R-r)^{2}}$
$$
\begin{aligned}
& =\sqrt{(24)^{2}+(15-5)^{2}} \mathrm{~cm} \\
& =\sqrt{576+100} \mathrm{~cm}=\sqrt{676} \mathrm{~cm}=26 \mathrm{~cm}
\end{aligned}
$$
Area of metal sheet used
$=$ curved surface area + area of the bottom
$$
=\pi l(R+r)+\pi r^{2}
$$
$$
=[3.14 \times 26 \times(15+5)+3.14 \times 5 \times 5] \mathrm{cm}^{2}
$$
$$
=(3.14 \times 26 \times 20+3.14 \times 25) \mathrm{cm}^{2}
$$
$$
=[3.14 \times(520+25)] \mathrm{cm}^{2}=(3.14 \times 545) \mathrm{cm}^{2}=1711.3 \mathrm{~cm}^{2}.
$$
$\therefore \quad$ cost of metal sheet used $=₹\left(\frac{1711.3}{100} \times 10\right)=₹ 171.13$.

---

### Example 3

A bucket is in the form of a frustum of a cone with a capacity of $12308.8 \mathrm{~cm}^{3}$ of water. The radii of the top and bottom circular ends are 20 cm and 12 cm respectively. Find the height of the bucket and the area of the metal sheet used in its making. [Use $\pi=3.14$.] [CBSE 2006C]

#### Solution:

Here, $R=20 \mathrm{~cm}$, $r=12 \mathrm{~cm}$ and volume $=12308.8 \mathrm{~cm}^{3}$.

Let the height of the bucket be $h \mathrm{~cm}$.

Volume of the bucket $=$ volume of frustum of the cone.
$$
\therefore \quad \frac{1}{3} \pi h\left(R^{2}+r^{2}+R r\right)=12308.8
$$
$$
\Rightarrow \frac{1}{3} \times 3.14 \times h\left[(20)^{2}+(12)^{2}+20 \times 12\right]=12308.8
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-49.jpg?height=343&width=297&top_left_y=1474&top_left_x=902)
$$
\Rightarrow \frac{1}{3} \times 3.14 \times h[400+144+240]=12308.8
$$
$$
\Rightarrow 784 h=\frac{12308.8 \times 3}{3.14}
$$
$$
\Rightarrow h=\left(\frac{12308.8 \times 3}{3.14 \times 784}\right)=15 .
$$
Slant height of the bucket
$$
\begin{aligned}
l & =\sqrt{h^{2}+(R-r)^{2}} \text { units } \\
& =\sqrt{(15)^{2}+(20-12)^{2}} \mathrm{~cm}=\sqrt{(15)^{2}+8^{2}} \mathrm{~cm} \\
& =\sqrt{225+64} \mathrm{~cm}=\sqrt{289} \mathrm{~cm}=17 \mathrm{~cm}
\end{aligned}
$$
Area of the metal sheet used
$$
\begin{aligned}
& =(\text { curved surface area })+(\text { area of the bottom }) \\
& =\left[\pi l(R+r)+\pi r^{2}\right] \\
& =[3.14 \times 17 \times(20+12)+3.14 \times 12 \times 12] \mathrm{cm}^{2} \\
& =[3.14 \times(17 \times 32)+3.14 \times 144] \mathrm{cm}^{2} \\
& =[3.14 \times(544+144)] \mathrm{cm}^{2} \\
& =(3.14 \times 688) \mathrm{cm}^{2}=2160.32 \mathrm{~cm}^{2} .
\end{aligned}
$$

---

### Example 4

In the figure, from the top of a solid cone of height 12 cm and base radius 6 cm , a cone of height 4 cm is removed by a plane parallel to the base. Find the total surface area of the remaining solid. [Use $\pi=22 / 7$ and $\sqrt{5}=2.236$.] [CBSE 2015]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-50.jpg?height=386&width=454&top_left_y=1002&top_left_x=515)

#### Solution:

Clearly, the remaining solid is the frustum $CDBA$ of cone $OPD$.
Radius of lower end of the frustum, $R=CD=6 \mathrm{~cm}$.
Height of the frustum,
$$
h = AC = OC - OA = (12-4) \mathrm{cm} = 8 \mathrm{cm} .
$$
Let the radius of upper face be $r \mathrm{~cm}$.
Now, $\triangle OAB \sim \triangle OCD$.
So, $\frac{OA}{OC}=\frac{AB}{CD} \Rightarrow \frac{4}{12}=\frac{r}{6}$
$$
\Rightarrow r=\left(\frac{4}{12} \times 6\right) \mathrm{cm}=2 \mathrm{~cm}.
$$
![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-50.jpg?height=432&width=491&top_left_y=1498&top_left_x=700)

Slant height of the frustum,
$$
l=\sqrt{h^{2}+(R-r)^{2}}=\sqrt{8^{2}+(6-2)^{2}}=\sqrt{64+16}=\sqrt{80} \mathrm{~cm}=4 \sqrt{5} \mathrm{~cm} .
$$
Total surface area of the frustum
$$
\begin{aligned}
& =\text { area of base }+ \text { area of top }+ \text { curved surface area } \\
& =\pi R^{2}+\pi r^{2}+\pi l(R+r)=\pi\left[R^{2}+r^{2}+l(R+r)\right] \\
& =\frac{22}{7} \times\left[6^{2}+2^{2}+4 \sqrt{5} \times(6+2)\right] \mathrm{cm}^{2} \\
& =\frac{22}{7} \times\left[36+4+4 \times 2.236 \times 8\right] \mathrm{cm}^{2} \\
& =\left[\frac{22}{7} \times(40+71.552)\right] \mathrm{cm}^{2}=\left(\frac{22}{7} \times 111.552\right) \mathrm{cm}^{2} \\
& =(22 \times 15.936) \mathrm{cm}^{2}=350.592 \mathrm{~cm}^{2} .
\end{aligned}
$$

---

### Example 5

An open metallic bucket is in the shape of a frustum of a cone mounted on hollow cylindrical base made of metallic sheet. If the diameters of the two circular ends of the bucket are 45 cm and 25 cm , the total vertical height of the bucket is 30 cm and that of the cylindrical portion is 6 cm , find the area of the metallic sheet used to make the bucket. Also, find the volume of water it can hold. [Take $\pi=22 / 7$.]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-51.jpg?height=402&width=261&top_left_y=692&top_left_x=934)

#### Solution:

Here $R=\frac{45}{2} \mathrm{~cm} = 22.5 \mathrm{~cm}$, $r=\frac{25}{2} \mathrm{~cm}=12.5 \mathrm{~cm}$.
Height of the frustum of the cone, $h=(30-6) \mathrm{cm}=24 \mathrm{~cm}$.
$\therefore h=24 \mathrm{~cm}$.

Slant height of the frustum of the cone,
$$
\begin{aligned}
l & =\sqrt{h^{2}+(R-r)^{2}} \text { units }=\sqrt{(24)^{2}+(22.5-12.5)^{2}} \mathrm{~cm} \\
& =\sqrt{(24)^{2}+(10)^{2}} \mathrm{~cm}=\sqrt{576+100} \mathrm{~cm} \\
& =\sqrt{676} \mathrm{~cm}=26 \mathrm{~cm}
\end{aligned}
$$
Area of metallic sheet used
$$
\begin{aligned}
= & (\text { curved surface area of the frustum of the cone }) \\
& +(\text { area of the base })+(\text { curved surface area of the cylinder }) \\
= & \pi l(R+r)+\pi r^{2}+2 \pi r H, \text { where } H=6 \mathrm{~cm} \\
= & \pi \cdot\left\{l(R+r)+r^{2}+2 r H\right\} \text { sq units } \\
= & \frac{22}{7} \cdot\left\{26(22.5+12.5)+(12.5)^{2}+2 \times 12.5 \times 6\right\} \mathrm{cm}^{2} \\
= & \frac{22}{7} \cdot\{(26 \times 35)+(12.5 \times 12.5)+150\} \mathrm{cm}^{2} \\
= & \frac{22}{7} \cdot\{910+156.25+150\} \mathrm{cm}^{2}=\left(\frac{22}{7} \times 1216.25\right) \mathrm{cm}^{2} \\
= & (22 \times 173.75) \mathrm{cm}^{2}=3822.5 \mathrm{~cm}^{2} .
\end{aligned}
$$
Volume of water which the bucket can hold
$$
\begin{aligned}
& =\frac{1}{3} \pi h\left[R^{2}+r^{2}+R r\right] \mathrm{cm}^{3} \\
& =\frac{1}{3} \times \frac{22}{7} \times 24 \times\left[\left(\frac{45}{2}\right)^{2}+\left(\frac{25}{2}\right)^{2}+\left(\frac{45}{2} \times \frac{25}{2}\right)\right] \mathrm{cm}^{3} \\
& =\frac{176}{7} \times\left(\frac{2025}{4}+\frac{625}{4}+\frac{1125}{4}\right) \mathrm{cm}^{3}=\left(\frac{176}{7} \times \frac{3775}{4}\right) \mathrm{cm}^{3} \\
& =\frac{166100}{7} \mathrm{~cm}^{3}=23728.57 \mathrm{~cm}^{3}=23.73 \text { litres } .
\end{aligned}
$$

---

### Example 6

A shuttlecock used for playing badminton has the shape of a frustum of a cone mounted on a hemisphere. The external diameters of the frustum are 5 cm and 2 cm , and the height of the entire shuttlecock is 7 cm . Find its external surface area.

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-52.jpg?height=384&width=322&top_left_y=734&top_left_x=877)

#### Solution:

Here, $R=\frac{5}{2} \mathrm{~cm}$, $r=1 \mathrm{~cm}$ and $h=(7-1) \mathrm{cm}=6 \mathrm{~cm}$.
Let $l$ be the slant height of the frustum of the cone.
$$
\begin{aligned}
\therefore \quad l^{2} & =h^{2}+(R-r)^{2}=\left\{6^{2}+\left(\frac{5}{2}-1\right)^{2}\right\} \mathrm{cm}^{2} \\
& =\left(36+\frac{9}{4}\right) \mathrm{cm}^{2}=\frac{144+9}{4} \mathrm{~cm}^{2}=\frac{153}{4} \mathrm{~cm}^{2} \\
\Rightarrow \quad l & =\frac{\sqrt{153}}{2} \mathrm{~cm} \approx \frac{12.36}{2} \mathrm{~cm}=6.18 \mathrm{~cm} .
\end{aligned}
$$
External surface area of the shuttlecock
$$
\begin{aligned}
& =(\text { its lateral surface area }+ \text { area of the base hemisphere }) \\
& =\left[\pi l(R+r)+2 \pi r^{2}\right] \text { sq units } \\
& =\left\{\frac{22}{7} \times 6.18 \times\left(\frac{5}{2}+1\right)+2 \times \frac{22}{7} \times 1 \times 1\right\} \mathrm{cm}^{2} \\
& =\left\{\frac{22}{7} \times 6.18 \times \frac{7}{2}+\frac{44}{7}\right\} \mathrm{cm}^{2} \\
& =\left(11 \times 6.18+\frac{44}{7}\right) \mathrm{cm}^{2}=(67.98+6.28) \mathrm{cm}^{2}=74.26 \mathrm{~cm}^{2}
\end{aligned}
$$

---

### Example 7

The slant height of the frustum of a cone is 4 cm and the perimeters of its circular ends are 18 cm and 6 cm . Find the curved surface area of the frustum. [CBSE 2017]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-53.jpg?height=235&width=241&top_left_y=227&top_left_x=954)

#### Solution:

Let the radii of its circular ends be $R \mathrm{~cm}$ and $r \mathrm{~cm}$, and its slant height be $l \mathrm{~cm}$. Then,
$$
2 \pi R=18 \Rightarrow \pi R=9
$$
$$
2 \pi r=6 \Rightarrow \pi r=3
$$
Also, $l=4 \mathrm{~cm}$ (given).
Curved surface area of the frustum
$$
\begin{aligned}
& =\pi l(R+r) \text{ sq units} \\
& =l \times(\pi R+\pi r)=4 \times(9+3) \mathrm{cm}^{2}=48 \mathrm{cm}^{2} .
\end{aligned}
$$

---

### Example 8

The height of a cone is 10 cm . The cone is divided into two parts using a plane parallel to its base at the middle of its height. Find the ratio of the volumes of the two parts. [CBSE 2017]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-53.jpg?height=263&width=299&top_left_y=732&top_left_x=892)

#### Solution:

Let $OAB$ be the cone and $OQ$ be its axis, and let $P$ be the midpoint of $OQ$.
Let $OQ=h \mathrm{~cm}$.
Then, $OP=PQ=\frac{h}{2} \mathrm{~cm}$ and $QB=10 \mathrm{~cm}$ (This seems to be a typo in the original text, let's assume the base radius is $10 \mathrm{cm}$).
Also, $\triangle OPD \sim \triangle OQB$.
$$
\therefore \quad \frac{O P}{O Q}=\frac{P D}{Q B} \Rightarrow \frac{(h / 2)}{h}=\frac{P D}{10} \Rightarrow P D=5 \mathrm{~cm} .
$$
The plane $CD$ divides the cone into two parts, namely
- (i) a smaller cone of radius $=5 \mathrm{~cm}$ and height $(h / 2) \mathrm{cm}$,
- (ii) frustum of a cone in which $R=10 \mathrm{~cm}$, $r=5 \mathrm{~cm}$ and height $=\left(\frac{h}{2}\right) \mathrm{cm}$.

Volume of the smaller cone
$$
=\left(\frac{1}{3} \times \pi \times 5 \times 5 \times \frac{h}{2}\right) \mathrm{cm}^{3}=\left(\frac{25 \pi h}{6}\right) \mathrm{cm}^{3} .
$$
Volume of the frustum of the cone
$$
=\frac{1}{3} \pi \times \frac{h}{2} \cdot\left[(10)^{2}+(5)^{2}+10 \times 5\right] \mathrm{cm}^{3}=\left(\frac{\pi h}{6}\right) [100+25+50] \mathrm{cm}^{3} =\left(\frac{175 \pi h}{6}\right) \mathrm{cm}^{3} .
$$
Ratio of the required volumes (smaller cone to frustum) $=\frac{25 \pi h}{6}: \frac{175 \pi h}{6}=25: 175=1: 7$.

---

### Example 9

The height of a cone is 30 cm . A small cone is cut off at the top by a plane parallel to the base. If its volume be $1/27$ of the volume of the given cone, at what height above the base is the section made? [HOTS] [CBSE 2005C]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-54.jpg?height=266&width=278&top_left_y=598&top_left_x=888)

#### Solution:

Height of the given cone $=30 \mathrm{~cm}$.
Let the radius of its base be $R \mathrm{~cm}$.
Volume of the given cone $=\left(\frac{1}{3} \pi R^{2} \times 30\right) \mathrm{cm}^{3}=\left(10 \pi R^{2}\right) \mathrm{cm}^{3}$.

Let the radius and height of the smaller cone be $r \mathrm{~cm}$ and $h \mathrm{~cm}$ respectively.
Then, volume of the smaller cone $=\left(\frac{1}{3} \pi r^{2} h\right) \mathrm{cm}^{3}$.
$$
\therefore \quad \frac{1}{3} \pi r^{2} h=\frac{1}{27} \cdot\left(10 \pi R^{2}\right) \quad \text{[given]}
$$
$$
\Rightarrow \frac{r^2 h}{3} = \frac{10 R^2}{27} \Rightarrow \frac{r^2}{R^2} = \frac{10 \times 3}{27h} \Rightarrow \left(\frac{R}{r}\right)^{2}=\frac{9 h}{10} \quad \text{(i)}
$$
Now, by similar triangles $\triangle OAB \sim \triangle OCD$.
$$
\therefore \quad \frac{AB}{CD}=\frac{OA}{OC} \Rightarrow \frac{R}{r}=\frac{30}{h} \quad \text{(ii)}
$$
From (i) and (ii), we get
$$
\left(\frac{30}{h}\right)^{2}=\frac{9 h}{10} \Rightarrow \frac{30 \times 30}{h \times h}=\frac{9 h}{10}
$$
$$
\Rightarrow h^{3}=\frac{30 \times 30 \times 10}{9}=1000 \Rightarrow h^{3}=(10)^{3} \Rightarrow h=10 .
$$
$\therefore \quad$ height of the smaller cone $=10 \mathrm{~cm}$.
Height of the section from the base $=(30-10) \mathrm{cm}=20 \mathrm{~cm}$.

---

### Example 10

A hollow cone is cut by a plane parallel to the base and the upper portion is removed. If the curved surface of the remainder is 8/9 of the curved surface of the whole cone, find the ratio of the line segments into which the altitude of the cone is divided by the plane. [CBSE 2004, '04C]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-54.jpg?height=270&width=306&top_left_y=1637&top_left_x=877)

#### Solution:

Let $OAB$ be the given hollow cone cut by the plane $CD$ parallel to base $AB$ and let cone $OCD$ be removed. Then, the remainder is the frustum $CABD$ of the given cone.

Let $OE=h$ units, $OF=H$ units, $OD=l$ units, $OB=L$ units, $ED=r$ units, $FB=R$ units.

In $\triangle OED$ and $\triangle OFB$, we have
$$
\angle EOD=\angle FOB \text{ (common)}
$$
$$
\angle OED=\angle OFB=90^{\circ}
$$
$$
\therefore \triangle OED \sim \triangle OFB
$$
$$
\Rightarrow \frac{O E}{O F}=\frac{O D}{O B}=\frac{E D}{F B} \Rightarrow \frac{h}{H}=\frac{l}{L}=\frac{r}{R} \quad \text{... (i) [by Thales' theorem]}
$$
Now, (curved surface area of the frustum $CABD$) $=\frac{8}{9}(\text { curved surface area of the cone } O A B)$
$\Rightarrow$ (curved surface area of the cone $OCD$)
$$
\begin{aligned}
& =(\text { curved surface of the cone } O A B) - (\text { curved surface of the frustum } C A B D) \\
& =(\text { curved surface of the cone } O A B) - \frac{8}{9}(\text { curved surface of the cone } O A B) \\
& =\frac{1}{9}(\text { curved surface of the cone } O A B)
\end{aligned}
$$
$$
\Rightarrow \pi r l=\frac{1}{9} \pi R L
$$
$$
\Rightarrow\left(\frac{r}{R}\right)\left(\frac{l}{L}\right)=\frac{1}{9} \Rightarrow\left(\frac{h}{H} \times \frac{h}{H}\right)=\frac{1}{9} \Rightarrow \frac{h^2}{H^2} = \frac{1}{9} \Rightarrow \frac{h}{H}=\frac{1}{3} \quad \text{[using (i)]}
$$
$$
\Rightarrow H=3 h .
$$
Now, $EF=(OF-OE)=(H-h)=(3 h-h)=2 h$.
$$
\therefore \quad \frac{O E}{E F}=\frac{h}{2 h}=\frac{1}{2} .
$$
Hence, $OE: EF=1: 2$.

---

### Example 11

A metallic right circular cone is 20 cm high and has a vertical angle of $60^{\circ}$. This is cut into two parts at the middle of its height by a plane parallel to the base. If the frustum so obtained is drawn into a wire of diameter $1/16 \mathrm{~cm}$, find the length of the wire. [CBSE 2017]

![](https://cdn.mathpix.com/cropped/2025_09_25_2ee37d889f9ae4cecf02g-55.jpg?height=273&width=301&top_left_y=1614&top_left_x=890)

#### Solution:

Let $OAB$ be the cone in which $\angle AOB=60^{\circ}$.
Clearly $\angle DOE=30^{\circ}$, $OE=10 \mathrm{~cm}$, $OF=20 \mathrm{~cm}$.
Let $ED=r \mathrm{~cm}$ and $FB=R \mathrm{~cm}$.
In $\triangle ODE$,
$$
\frac{E D}{O E}=\tan 30^{\circ} \Rightarrow \frac{r}{10}=\frac{1}{\sqrt{3}} \Rightarrow r=\frac{10}{\sqrt{3}} \mathrm{~cm}
$$
and in $\triangle OFB$,
$$
\frac{F B}{O F}=\tan 30^{\circ} \Rightarrow \frac{R}{20}=\frac{1}{\sqrt{3}} \Rightarrow R=\frac{20}{\sqrt{3}} \mathrm{~cm}.
$$
Also, height of frustum $h = EF=10 \mathrm{~cm}$.
Thus, $ABCD$ is the frustum of a cone in which $R=\frac{20}{\sqrt{3}} \mathrm{~cm}, r=\frac{10}{\sqrt{3}} \mathrm{~cm}$ and $h=10 \mathrm{~cm}$.

Volume of this frustum $=\frac{1}{3} \pi h\left(R^{2}+r^{2}+R r\right)$
$$
\begin{aligned}
& =\frac{1}{3} \times \pi \times 10\left\{\left(\frac{20}{\sqrt{3}}\right)^2+\left(\frac{10}{\sqrt{3}}\right)^2+\left(\frac{20}{\sqrt{3}}\right)\left(\frac{10}{\sqrt{3}}\right)\right\} \mathrm{cm}^{3} \\
& =\frac{1}{3} \times \pi \times 10\left\{\frac{400}{3}+\frac{100}{3}+\frac{200}{3}\right\} \mathrm{cm}^{3} \\
& =\left(\frac{\pi \times 10}{3} \times \frac{700}{3}\right) \mathrm{cm}^{3}=\left(\frac{7000 \pi}{9}\right) \mathrm{cm}^{3} .
\end{aligned}
$$
Let the length of the wire be $L$.
Radius of the wire, $r_{1}=\frac{1}{2} \times \frac{1}{16} = \frac{1}{32} \mathrm{~cm}$.
Volume of the wire $=\pi r_{1}^{2} L=\pi \times\left(\frac{1}{32}\right)^{2} \times L$.
$$
\therefore \quad \frac{7000 \pi}{9}=\frac{\pi L}{32 \times 32} \Rightarrow L=\left(\frac{7000 \times 32 \times 32}{9}\right) \mathrm{cm}
$$
$$
\Rightarrow L=\left(\frac{7000 \times 1024}{9}\right) \mathrm{cm} = \left(\frac{7168000}{9}\right) \mathrm{cm}
$$
$$
\Rightarrow L=\left(\frac{7168000}{9 \times 100}\right) \mathrm{m}=\left(\frac{71680}{9}\right) \mathrm{m} \approx 7964.44 \mathrm{~m} .
$$

---