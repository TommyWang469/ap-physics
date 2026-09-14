# Kinematics test practice from your AP Classroom questions

For Thursday, September 10, 2026. Revised September 9.

Problems 1-5 use actual questions from your September 8 AP Classroom screenshots, transcribed or lightly shortened. Problem 1 also includes the separate conceptual follow-up about the same rocket. Problem 6 is an original 3D adaptation, clearly labeled. These are grounded in your class practice, but your teacher's actual test questions are not known.

The complete source record is [AP Classroom Unit 1 Question Log](ap-classroom-unit-1-question-log.md). Work these without notes, then check the solutions below. Redo Problems 2 and 5 first: your screenshots show those were answered incorrectly.

## Questions

### 1. Actual AP Classroom: rocket with changing acceleration

A toy rocket moves in the \(y\)-direction with acceleration

\[
a(t)=50-2t^2,
\]

where \(t\) is in seconds and \(a\) is in \(\text{m/s}^2\). At \(t=0\), its position is \(10\ \text{m}\) and its velocity is \(6\ \text{m/s}\).

Which equation represents its position?

- A. \(y=-4\)
- B. \(y=-\frac16t^4+25t^2\)
- C. \(y=-\frac16t^4+25t^2+6t+10\)
- D. \(y=\frac12(50-2t^2)t^2+6t+10\)

Separate follow-up from your screenshots: on \(0\le t\le5\ \text{s}\), do position and velocity each increase or decrease?

Source: screenshots at 4:33:58 PM and 4:34:11 PM; question-log entries 2 and 3.

### 2. Actual AP Classroom Q10: acceleration magnitude in 2D

An object's position is

\[
x(t)=At^2-B,\qquad y(t)=B-Ct^3,
\]

where \(A=3\ \text{m/s}^2\), \(B=2\ \text{m}\), and \(C=1\ \text{m/s}^3\).

The acceleration magnitudes at \(t=0\) and \(t=1\ \text{s}\) are \(a_0\) and \(a_1\). Which statement is true?

- A. \(a_0=a_1\)
- B. \(a_0>a_1=0\)
- C. \(0=a_0<a_1\)
- D. \(0<a_0<a_1\)

Source: screenshots at 4:45:35 PM and 4:47:48 PM; question-log entry 8.

### 3. Actual AP Classroom Q5: rock thrown from a height

A rock is thrown from height \(h_0\) with initial speed \(v_0\) at angle \(\theta\) above the horizontal. Which expression gives its time to reach the ground?

- A. \(\displaystyle \frac{2v_0\sin\theta}{g}\)
- B. \(\displaystyle \frac{v_0\sin\theta}{g}\)
- C. \(\displaystyle \frac{v_0\sin\theta-\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}\)
- D. \(\displaystyle \frac{v_0\sin\theta+\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}\)

Source: screenshots at 4:35:37 PM and 4:37:52 PM; question-log entry 4.

### 4. Actual AP Classroom: stone dropped from a moving cart

A cart travels at constant speed \(v_1\) in the \(+x\)-direction. Student 1, on the cart, releases a stone from rest relative to the cart.

Just before the stone reaches the ground, Student 1 measures speed \(2v_1\) and acceleration magnitude \(a_1\). Student 2, on the ground, measures speed \(v_2\) and acceleration magnitude \(a_2\).

Which relationships are correct?

| Choice | Speeds | Accelerations |
|---|---|---|
| A | \(v_2=\sqrt5v_1\) | \(a_2=a_1\) |
| B | \(v_2=\sqrt5v_1\) | \(a_2=\sqrt5a_1\) |
| C | \(v_2=3v_1\) | \(a_2=a_1\) |
| D | \(v_2=3v_1\) | \(a_2=\sqrt5a_1\) |

Source: screenshot at 4:48:07 PM; question-log entry 9.

### 5. Actual AP Classroom: landing directly across a river

Point 2 is directly across the river from starting Point O. Point 1 is upstream of Point 2.

Water flows at \(5\ \text{m/s}\) in the \(+x\)-direction relative to the bank. When aimed straight across, the boat's velocity relative to the water is \(10\ \text{m/s}\) in the \(+y\)-direction.

Which aiming instruction and explanation would let the boat reach Point 2?

- A. Aim toward Point 1 because the boat's \(y\)-component relative to the water must equal the water speed in magnitude.
- B. Aim toward Point 1 because the boat's \(x\)-component relative to the water must equal the water velocity in magnitude and oppose its direction.
- C. Aim toward Point 2 because the boat's speed relative to water is greater than the water speed.
- D. Aim toward Point 2 because the boat's \(y\)-component is not affected by the water's motion.

Source: screenshot at 4:52:47 PM; question-log entry 10. The diagram is described in words.

### 6. Original 3D adaptation of the vector-calculus question

This question was not in your screenshots. It extends the same method used in Problem 2 to three components.

In SI units, a particle has position

\[
\vec r(t)=(3t^2-2)\hat i+(2-t^3)\hat j+2t^2\hat k.
\]

At \(t=1\ \text{s}\), find:

1. Its velocity vector.
2. Its speed.
3. Its acceleration vector.
4. Its acceleration magnitude.

## Solutions

### 1. Integrate twice and apply the initial conditions

\[
v(t)=\int(50-2t^2)\,dt
=50t-\frac23t^3+C_1.
\]

\(v(0)=6\) gives \(C_1=6\). Integrating again,

\[
y(t)=25t^2-\frac16t^4+6t+C_2.
\]

\(y(0)=10\) gives \(C_2=10\), so

\[
\boxed{y(t)=-\frac16t^4+25t^2+6t+10}.
\]

Answer C. Choice D misuses a constant-acceleration formula with a changing acceleration.

On \(0\le t\le5\), \(a(t)\ge0\), with equality only at the endpoint. Velocity therefore increases from its positive initial value. Positive velocity means position increases too. Both increase, which is choice D in the original follow-up.

### 2. Differentiate each coordinate twice

\[
a_x=2A=6\ \text{m/s}^2,\qquad
a_y=-6Ct.
\]

At \(t=0\),

\[
\vec a=(6,0)\ \text{m/s}^2,\qquad a_0=6\ \text{m/s}^2.
\]

At \(t=1\),

\[
\vec a=(6,-6)\ \text{m/s}^2,\qquad
a_1=\sqrt{6^2+(-6)^2}=6\sqrt2\ \text{m/s}^2.
\]

\[
\boxed{0<a_0<a_1}
\]

Answer D. Perpendicular components do not cancel by adding \(6+(-6)\).

### 3. Solve the vertical position equation

With upward positive and the ground at \(y=0\),

\[
0=h_0+(v_0\sin\theta)t-\frac12gt^2.
\]

Rearrange:

\[
\frac12gt^2-(v_0\sin\theta)t-h_0=0.
\]

The quadratic formula gives

\[
t=\frac{v_0\sin\theta\pm\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}.
\]

For \(h_0>0\), the minus root is negative. Choose the positive root:

\[
\boxed{t=\frac{v_0\sin\theta+\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}}.
\]

Answer D. The original screenshot's explanation has a sign inconsistency in its position equation; an upward launch requires a positive initial vertical-velocity term when upward is positive.

### 4. Convert from the cart frame to the ground frame

Student 1 sees purely downward motion just before impact:

\[
\vec v_{\mathrm{stone/cart}}=(0,-2v_1).
\]

Add the cart's ground velocity:

\[
\vec v_{\mathrm{stone/ground}}
=(0,-2v_1)+(v_1,0)=(v_1,-2v_1).
\]

\[
v_2=\sqrt{v_1^2+(-2v_1)^2}=\sqrt5v_1.
\]

The cart has zero acceleration, so changing between these frames does not change the stone's acceleration:

\[
\boxed{v_2=\sqrt5v_1,\qquad a_2=a_1}.
\]

Answer A. Both observers measure gravitational acceleration downward.

### 5. Cancel the downstream component

\[
\vec v_{\mathrm{boat/bank}}
=\vec v_{\mathrm{boat/water}}+\vec v_{\mathrm{water/bank}}.
\]

Reaching the point directly across requires \(v_{\mathrm{boat/bank},x}=0\). Thus

\[
0=v_{\mathrm{boat/water},x}+5,
\]

so \(v_{\mathrm{boat/water},x}=-5\ \text{m/s}\). Aim upstream toward Point 1.

Answer B. The unchanged vertical component does not eliminate horizontal drift.

An additional numerical check, if the boat maintains speed \(10\ \text{m/s}\) relative to water: \(10\sin\theta=5\), giving \(30^\circ\) upstream of straight across. The original question asks for the aiming direction and reasoning, not this angle.

### 6. Use all three components before taking magnitudes

\[
\vec v(t)=6t\hat i-3t^2\hat j+4t\hat k,
\qquad
\vec a(t)=6\hat i-6t\hat j+4\hat k.
\]

At \(t=1\),

\[
\boxed{\vec v=(6,-3,4)\ \text{m/s}},
\qquad
\boxed{|\vec v|=\sqrt{61}=7.81\ \text{m/s}}.
\]

\[
\boxed{\vec a=(6,-6,4)\ \text{m/s}^2},
\qquad
\boxed{|\vec a|=\sqrt{88}=9.38\ \text{m/s}^2}.
\]

The \(x,y,z\) components must be squared and added before taking the square root.
