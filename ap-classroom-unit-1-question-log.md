# AP Physics C — Unit 1 AP Classroom Question Log

Recorded from the September 8, 2026 screenshots. The 16 screenshots contain 14 unique questions; the repeated captures of the rock-from-a-height question and the two-dimensional acceleration question are recorded only once.

## Fast review rules

- Average acceleration is a vector: \(\vec a_{\text{avg}}=(\vec v_f-\vec v_i)/\Delta t\).
- In components, subtract and differentiate each direction separately. Combine perpendicular components with the Pythagorean theorem, not ordinary scalar addition.
- \(v=dx/dt\) and \(a=dv/dt=d^2x/dt^2\). Integrating requires constants fixed by the initial conditions.
- On an \(x\)-versus-\(t\) graph, slope is velocity and curvature is acceleration.
- On a \(v\)-versus-\(t\) graph, slope is acceleration and signed area is displacement.
- On an \(a\)-versus-\(t\) graph, signed area is change in velocity.
- Relative velocity is **object minus observer**: \(\vec v_{A/B}=\vec v_{A/G}-\vec v_{B/G}\).

## 1. Q2 — Average acceleration in two dimensions

### Question

An object moves in the \(xy\)-plane. At \(t=1\ \text{s}\), its velocity is \(3\ \text{m/s}\) in the \(+x\)-direction. At \(t=2\ \text{s}\), its velocity is \(4\ \text{m/s}\) in the \(+y\)-direction. Find its average acceleration between these times.

### Solution

Write the two velocities as vectors:

\[
\vec v_i=(3,0)\ \text{m/s},\qquad \vec v_f=(0,4)\ \text{m/s}.
\]

Then

\[
\vec a_{\text{avg}}
=\frac{\vec v_f-\vec v_i}{2-1}
=(-3,4)\ \text{m/s}^2.
\]

Its magnitude is

\[
|\vec a_{\text{avg}}|=\sqrt{(-3)^2+4^2}=5\ \text{m/s}^2.
\]

The vector is in quadrant II, and

\[
\theta=\tan^{-1}\left(\frac{4}{3}\right)=53.1^\circ.
\]

**Answer:** \(\boxed{5\ \text{m/s}^2\text{ at }53^\circ\text{ above the }-x\text{-direction}}\), choice B.

## 2. Q3 — Position from a nonconstant acceleration

### Question

A toy rocket moves in the \(y\)-direction with acceleration

\[
a(t)=50-2t^2,
\]

where \(t\) is in seconds and \(a\) is in \(\text{m/s}^2\). At \(t=0\), the rocket is at \(y=10\ \text{m}\) and has velocity \(v=6\ \text{m/s}\). Find \(y(t)\).

### Solution

Integrate acceleration once:

\[
v(t)=\int(50-2t^2)\,dt
=50t-\frac{2}{3}t^3+C_1.
\]

Since \(v(0)=6\), \(C_1=6\). Integrate again:

\[
y(t)=\int\left(50t-\frac{2}{3}t^3+6\right)dt
=25t^2-\frac16t^4+6t+C_2.
\]

Since \(y(0)=10\), \(C_2=10\).

**Answer:**

\[
\boxed{y(t)=-\frac16t^4+25t^2+6t+10},
\]

choice C.

## 3. Toy rocket — How position and velocity change

### Question

For the same rocket, \(a(t)=50-2t^2\), \(y(0)=10\ \text{m}\), and \(v(0)=6\ \text{m/s}\). From \(t=0\) to \(t=5\ \text{s}\), determine whether its position and velocity increase or decrease.

### Solution

Throughout the interval,

\[
a(t)=50-2t^2\ge 0,
\]

with \(a=0\) only at \(t=5\ \text{s}\). Therefore the velocity increases. Because it begins positive and continues increasing, \(v(t)>0\), so the position also increases.

**Answer:** \(\boxed{\text{position increases and velocity increases}}\), choice D.

## 4. Q5 — Rock thrown from a height

### Question

A rock is thrown from height \(h_0\) with initial speed \(v_0\) at angle \(\theta\) above the horizontal. Find the time required for it to reach the ground.

### Answer

\[
\boxed{t=\frac{v_0\sin\theta+\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}},
\]

choice D. The complete derivation and sign-convention warning are recorded in the [Unit 1 Kinematics Study Guide](unit-1-kinematics-study-guide.md#recorded-problem-time-for-a-rock-thrown-from-a-height).

## 5. Q6 — Vector subtraction and magnitude

### Question

Given the position vectors

\[
\vec A=(4\hat i+5\hat j)\ \text{m},\qquad
\vec B=(\hat i+7\hat j)\ \text{m},
\]

find \(\vec A-2\vec B\) and its magnitude.

### Solution

Subtract corresponding components:

\[
\vec A-2\vec B
=(4,5)-2(1,7)
=(2,-9)\ \text{m}.
\]

Its magnitude is

\[
|\vec A-2\vec B|
=\sqrt{2^2+(-9)^2}
=\sqrt{85}\ \text{m}
\approx9.2\ \text{m}.
\]

**Answer:** \(\boxed{(2\hat i-9\hat j)\ \text{m},\ 9.2\ \text{m}}\), choice A.

## 6. Fox position-time graph — Comparing accelerations

### Question

A fox's position-time graph is curved concave up at \(t_1\), but it has become a straight line with constant positive slope at \(t_2\). Compare the acceleration magnitudes \(a_1\) and \(a_2\).

### Solution

Acceleration is the second derivative of position. At \(t_1\), the slope of the position graph is increasing, so the graph is concave up and \(a_1>0\). At \(t_2\), the graph is a straight line, so its slope is constant and \(a_2=0\).

**Answer:** \(\boxed{a_1>a_2=0}\), choice C.

## 7. Cyclist measured from two cars on the same train

### Question

A train moves east at speed \(v_T\). A cyclist moves at speed \(v_C\), heading \(15^\circ\) east of north relative to the ground, with \(v_C<v_T\). Determine the cyclist's velocity direction as measured by observers in Car 1 and Car 3.

### Solution

Both cars move with the same train velocity, so both observers must measure the same relative velocity:

\[
\vec v_{C/T}=\vec v_{C/G}-\vec v_{T/G}.
\]

In components,

\[
\vec v_{C/T}
=(v_C\sin15^\circ-v_T)\hat i
+(v_C\cos15^\circ)\hat j.
\]

Because \(v_C<v_T\), the \(x\)-component is negative, while the \(y\)-component is positive. The vector therefore points northwest. Since Car 1 and Car 3 have identical velocities, they see identical northwest vectors.

**Answer:** both observers measure the same northwest-pointing vector, choice A.

## 8. Q10 — Magnitudes of two-dimensional acceleration

### Question

An object's position is

\[
x(t)=At^2-B,\qquad y(t)=B-Ct^3,
\]

where \(A=3\ \text{m/s}^2\), \(B=2\ \text{m}\), and \(C=1\ \text{m/s}^3\). The acceleration magnitudes at \(t=0\) and \(t=1\ \text{s}\) are \(a_0\) and \(a_1\). Compare them.

### Solution

Differentiate each position component twice:

\[
a_x=\frac{d^2x}{dt^2}=2A=6\ \text{m/s}^2,
\]

\[
a_y=\frac{d^2y}{dt^2}=-6Ct=-6t\ \text{m/s}^2.
\]

At \(t=0\),

\[
a_0=\sqrt{6^2+0^2}=6\ \text{m/s}^2.
\]

At \(t=1\ \text{s}\),

\[
a_1=\sqrt{6^2+(-6)^2}=6\sqrt2\ \text{m/s}^2.
\]

**Answer:** \(\boxed{0<a_0<a_1}\), choice D.

**Common trap:** \(+6\) in the \(x\)-direction and \(-6\) in the \(y\)-direction do not cancel. They are perpendicular vector components.

## 9. Stone released from a moving cart

### Question

A cart moves at constant speed \(v_1\) in the \(+x\)-direction. A student on the cart releases a stone from rest relative to the cart. Just before impact, the student on the cart measures the stone's speed as \(2v_1\), while a student on the ground measures speed \(v_2\). The measured acceleration magnitudes are \(a_1\) and \(a_2\). Find the relationships.

### Answer

\[
\boxed{v_2=\sqrt5\,v_1,\qquad a_2=a_1},
\]

choice A. The complete vector solution is recorded in [Relative Velocity — Stone released from a moving cart](relative-velocity-solutions.md#ap-classroom--stone-released-from-a-moving-cart).

## 10. Boat aiming across a flowing river

### Question

A person wants to cross a river from Point O to Point 2, which is directly opposite. The water flows at \(5\ \text{m/s}\) in the \(+x\)-direction relative to the bank, and the boat can travel at \(10\ \text{m/s}\) relative to the water. Should the person aim directly toward Point 2 or upstream toward Point 1?

### Solution

The ground velocity is

\[
\vec v_{B/G}=\vec v_{B/W}+\vec v_{W/G}.
\]

To land at Point 2, the total \(x\)-component must be zero. Therefore the boat's velocity relative to the water must have

\[
v_{B/W,x}=-5\ \text{m/s},
\]

which cancels the water's \(+5\ \text{m/s}\) current. The boat must aim upstream toward Point 1. Its required angle is

\[
\sin\theta=\frac{5}{10},\qquad \theta=30^\circ
\]

west of north.

**Answer:** aim toward Point 1 because the boat's \(x\)-component must equal the water speed in magnitude and point in the opposite direction, choice B.

## 11. Q14 — Matching acceleration-time and velocity-time graphs

### Question

An acceleration-time graph starts below zero and rises linearly toward zero. A proposed velocity-time graph stays below zero, becomes more negative, and gradually flattens. Can both graphs describe the same motion?

### Solution

The slope of a velocity-time graph equals acceleration. The proposed velocity graph has a negative slope whose magnitude gets smaller and approaches zero. That matches a negative acceleration that rises toward zero.

Also,

\[
\Delta v=\int a(t)\,dt.
\]

The area under the acceleration curve is negative, so velocity becomes more negative. Since both \(v\) and \(a\) are negative, the object's speed increases even though the acceleration is not positive.

**Answer:** yes; the negative area produces a negative change in velocity, so a negative velocity can increase in magnitude, choice C.

## 12. Q15 — Wind direction from unequal flight times

### Question

Airport A is directly south of Airport B. A flight from A to B takes less time than the return flight, even though the airplane has the same velocity relative to the air on both trips. What is the direction of the air's velocity relative to the ground?

### Solution

The A-to-B trip is northward. For this trip to be faster, the wind must add a northward component to the plane's ground velocity. On the southward return trip, that same wind opposes the plane.

**Answer:** \(\boxed{\text{north}}\), choice A.

## 13. Q16 — Acceleration from a position-time table

### Question

The position of a car moving to the right is recorded as follows:

| Time (s) | Position (m) |
|---:|---:|
| 1 | 10 |
| 3 | 28 |
| 5 | 44 |
| 7 | 58 |
| 9 | 70 |

What does the table show about the direction of the car's average acceleration?

### Solution

Find the average velocity in each successive two-second interval:

\[
\frac{28-10}{2}=9,\quad
\frac{44-28}{2}=8,\quad
\frac{58-44}{2}=7,\quad
\frac{70-58}{2}=6\ \text{m/s}.
\]

The velocity remains positive, so the car keeps moving right, but the velocity decreases. Therefore the acceleration points left.

**Answer:** the average acceleration is to the left because the successive average velocities decrease, choice B.

## 14. Q18 — Velocity of Boat A relative to Boat B

### Question

Relative to the water, Boat A travels north at \(60\ \text{m/s}\), and Boat B travels east at \(80\ \text{m/s}\). Find the magnitude and direction of Boat A's velocity relative to Boat B.

### Solution

Use object minus observer:

\[
\vec v_{A/B}=\vec v_{A/W}-\vec v_{B/W}.
\]

Thus,

\[
\vec v_{A/B}=(0,60)-(80,0)=(-80,60)\ \text{m/s}.
\]

The magnitude is

\[
|\vec v_{A/B}|=\sqrt{(-80)^2+60^2}=100\ \text{m/s}.
\]

The vector points northwest, with angle

\[
\theta=\tan^{-1}\left(\frac{60}{80}\right)=36.9^\circ
\]

north of west.

**Answer:** \(\boxed{100\ \text{m/s at }36.9^\circ\text{ north of west}}\), choice C.

