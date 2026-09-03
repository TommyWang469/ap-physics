# AP Physics C: Mechanics — Unit 1 Kinematics Study Guide

Test date: September 3, 2026

This guide follows the current College Board Unit 1 topics:

1. Scalars and vectors
2. Displacement, velocity, and acceleration
3. Representing motion
4. Reference frames and relative motion
5. Motion in two dimensions

Official reference: [AP Physics C: Mechanics Course and Exam Description](https://apcentral.collegeboard.org/media/pdf/ap-physics-c-mechanics-course-and-exam-description.pdf)

## The one-page review

### Definitions

| Quantity | Meaning | Scalar or vector? |
|---|---|---|
| Position \(\vec r\) | Location relative to an origin | Vector |
| Distance | Total path length | Scalar |
| Displacement \(\Delta\vec r\) | Final position minus initial position | Vector |
| Speed | Magnitude of velocity | Scalar |
| Velocity \(\vec v\) | Rate of change of position | Vector |
| Acceleration \(\vec a\) | Rate of change of velocity | Vector |

### Calculus relationships

\[
\boxed{\vec v=\frac{d\vec r}{dt}}
\qquad
\boxed{\vec a=\frac{d\vec v}{dt}=\frac{d^2\vec r}{dt^2}}
\]

\[
\boxed{\Delta\vec r=\int_{t_i}^{t_f}\vec v(t)\,dt}
\qquad
\boxed{\Delta\vec v=\int_{t_i}^{t_f}\vec a(t)\,dt}
\]

Initial conditions determine constants of integration.

### Average quantities

\[
\boxed{\vec v_{\text{avg}}=\frac{\Delta\vec r}{\Delta t}}
\qquad
\boxed{\vec a_{\text{avg}}=\frac{\Delta\vec v}{\Delta t}}
\]

\[
\boxed{\text{average speed}=\frac{\text{total distance}}{\Delta t}}
\]

Average speed and the magnitude of average velocity are generally not equal.

### Constant-acceleration equations

Use these only when acceleration is constant:

\[
\boxed{v=v_0+at}
\]

\[
\boxed{x=x_0+v_0t+\frac12at^2}
\]

\[
\boxed{v^2=v_0^2+2a(x-x_0)}
\]

Also useful:

\[
\boxed{x-x_0=\frac{v_0+v}{2}t}
\]

### Graph rules

| Graph | Slope means | Area means |
|---|---|---|
| Position vs. time | Velocity | No standard kinematics meaning |
| Velocity vs. time | Acceleration | Displacement |
| Acceleration vs. time | Rate of change of acceleration | Change in velocity |

Also remember:

- Concavity of an \(x\)-versus-\(t\) graph indicates the sign of acceleration.
- Area below the time axis is negative when calculating displacement or change in velocity.
- Total distance from a velocity graph is \(\int |v|\,dt\), so count every area as positive.

### Vector components

For an angle \(\theta\) measured from the positive \(x\)-axis:

\[
\boxed{A_x=A\cos\theta}
\qquad
\boxed{A_y=A\sin\theta}
\]

\[
\boxed{A=\sqrt{A_x^2+A_y^2}}
\]

Use \(\operatorname{atan2}(A_y,A_x)\), or check the quadrant carefully when using inverse tangent.

If the angle is measured from the vertical, the vertical component uses cosine and the horizontal component uses sine.

### Relative motion

Use **object minus observer**:

\[
\boxed{\vec v_{\text{object/observer}}
=\vec v_{\text{object/ground}}
-\vec v_{\text{observer/ground}}}
\]

Both vectors being subtracted must be measured in the same reference frame.

Equivalent addition form:

\[
\boxed{\vec v_{A/C}=\vec v_{A/B}+\vec v_{B/C}}
\]

Acceleration is the same in all inertial reference frames. If two frames move at constant velocity relative to one another, then

\[
\vec a_{A/B}=\vec a_{A/C}.
\]

### Projectile motion

Separate the motion into independent components:

\[
\boxed{a_x=0}
\qquad
\boxed{a_y=-g}
\]

Using upward as positive:

\[
x=x_0+v_{0x}t,
\qquad
v_x=v_{0x},
\]

\[
y=y_0+v_{0y}t-\frac12gt^2,
\qquad
v_y=v_{0y}-gt.
\]

For a launch angle measured above horizontal:

\[
v_{0x}=v_0\cos\theta,
\qquad
v_{0y}=v_0\sin\theta.
\]

The same time \(t\) connects the horizontal and vertical equations.

At the highest point:

\[
v_y=0,
\qquad
a_y=-g.
\]

For launch and landing at the same height:

\[
T=\frac{2v_0\sin\theta}{g},
\qquad
R=\frac{v_0^2\sin(2\theta)}{g},
\qquad
H=\frac{v_0^2\sin^2\theta}{2g}.
\]

These three special-case formulas do not work unchanged when the launch and landing heights differ.

## Concepts you should be able to explain

### Position, displacement, and distance

In one dimension,

\[
\Delta x=x_f-x_i.
\]

Displacement depends only on the endpoints. Distance depends on the entire path.

Example: walking \(5\ \text{m}\) east and then \(2\ \text{m}\) west gives

\[
\text{distance}=7\ \text{m},
\qquad
\Delta x=+3\ \text{m}.
\]

### Velocity versus acceleration signs

| Velocity | Acceleration | What happens to speed? |
|---|---|---|
| Same sign | Same sign | Speed increases |
| Opposite signs | Opposite signs | Speed decreases |

Negative acceleration does not automatically mean slowing down. It describes the direction of acceleration.

### Turning points

At an instantaneous turning point,

\[
v=0,
\]

but acceleration does not have to be zero. A ball at the top of its flight has \(v_y=0\) and \(a_y=-g\).

### Reading motion graphs

For a position graph:

- Positive slope: positive velocity.
- Negative slope: negative velocity.
- Horizontal tangent: instantaneously at rest.
- Concave up: positive acceleration.
- Concave down: negative acceleration.

For a velocity graph:

- Above the axis: positive velocity.
- Below the axis: negative velocity.
- Crossing the axis usually indicates a direction change.
- Positive slope: positive acceleration.
- Area between two times: displacement.

For an acceleration graph:

- Area between two times: change in velocity, not displacement.

### Motion diagrams

- Equal time intervals are used between dots.
- Increasing dot spacing means increasing speed.
- Decreasing dot spacing means decreasing speed.
- Velocity arrows point in the direction of motion.
- Acceleration arrows point in the direction of the change in velocity, not necessarily the direction of motion.

## Calculus problem types

### Given position \(x(t)\)

Differentiate once for velocity and twice for acceleration.

Example:

\[
x(t)=2+3t-4t^2+t^3.
\]

Then

\[
v(t)=3-8t+3t^2,
\]

\[
a(t)=-8+6t.
\]

At \(t=2\ \text{s}\):

\[
v=-1\ \text{m/s},
\qquad
a=4\ \text{m/s}^2.
\]

### Given acceleration \(a(t)\)

Integrate and apply initial conditions.

Example:

\[
a(t)=6t,
\qquad
v(0)=2\ \text{m/s},
\qquad
x(0)=0.
\]

Integrating once:

\[
v(t)=3t^2+C.
\]

Using \(v(0)=2\) gives

\[
v(t)=3t^2+2.
\]

Integrating again:

\[
x(t)=t^3+2t+C_2.
\]

Using \(x(0)=0\) gives

\[
x(t)=t^3+2t.
\]

### When acceleration is given as a function of position

The chain rule gives

\[
\boxed{a=\frac{dv}{dt}
=\frac{dv}{dx}\frac{dx}{dt}
=v\frac{dv}{dx}}.
\]

This lets you relate velocity and position without time:

\[
\int_{v_0}^{v}v\,dv
=\int_{x_0}^{x}a(x)\,dx.
\]

## A reliable solution process

1. Draw the situation and label the coordinate axes.
2. Choose positive directions and keep them throughout the problem.
3. List known values with signs and units.
4. Identify what is being asked and its reference frame.
5. Split vectors into components before combining them.
6. Decide whether acceleration is constant.
7. Use derivatives, integrals, graphs, or a constant-acceleration equation as appropriate.
8. Solve symbolically before inserting numbers when possible.
9. Check units, sign, magnitude, direction, and physical reasonableness.

For projectile motion, create separate \(x\) and \(y\) columns. The only shared variable is time.

For relative motion, write the subscripts before calculating:

\[
\text{requested object/observer}
=\text{object/ground}-\text{observer/ground}.
\]

## Common test traps

1. **Using distance in average velocity.** Average velocity uses displacement.
2. **Treating negative acceleration as slowing down.** Compare the signs of \(v\) and \(a\).
3. **Using constant-acceleration equations when \(a\) changes.** Use calculus instead.
4. **Forgetting the integration constant.** Apply the given initial condition.
5. **Using sine and cosine based on habit.** Identify which axis the angle is measured from.
6. **Ignoring vector signs.** West, south, and downward components are negative if east, north, and upward are positive.
7. **Mixing horizontal and vertical projectile equations.** Solve each axis separately with the same time.
8. **Saying acceleration is zero at a projectile's peak.** Only \(v_y\) is zero there.
9. **Using area under \(v(t)\) as distance without handling negative sections.** Signed area is displacement; total absolute area is distance.
10. **Reversing relative-velocity subtraction.** Use object minus observer.
11. **Reporting only a vector's magnitude.** If direction is requested, include an angle and direction words.
12. **Rounding too early.** Keep extra digits until the final answer.

## Practice check

Try these without looking at the answers.

### 1. Position function

An object's position is

\[
x(t)=4+5t-2t^2.
\]

Find its velocity and acceleration at \(t=3\ \text{s}\).

### 2. Displacement versus distance

An object has velocity

\[
v(t)=6-2t
\]

from \(t=0\) to \(t=5\ \text{s}\). Find its displacement, distance traveled, average velocity, and average speed.

### 3. Constant acceleration

A cart starts from rest and accelerates at \(3.0\ \text{m/s}^2\) for \(4.0\ \text{s}\). Find its final speed and displacement.

### 4. Braking

A car moving at \(20\ \text{m/s}\) slows with constant acceleration \(-5.0\ \text{m/s}^2\). Find its stopping time and stopping distance.

### 5. Projectile launched at an angle

A ball is launched from level ground at \(20\ \text{m/s}\), \(30^\circ\) above horizontal. It lands at its launch height. Using \(g=10\ \text{m/s}^2\), find its time of flight, range, and maximum height.

### 6. Horizontal launch

A ball rolls horizontally from a \(45\ \text{m}\)-high cliff at \(10\ \text{m/s}\). Using \(g=10\ \text{m/s}^2\), find its flight time, horizontal range, and impact-speed magnitude.

### 7. Relative velocity

A cyclist moves east at \(12\ \text{m/s}\), while an observer moves east at \(7\ \text{m/s}\). Find the cyclist's velocity relative to the observer. Repeat if the observer instead moves east at \(15\ \text{m/s}\).

### 8. Integration

An object has

\[
a(t)=6t,
\qquad
v(0)=2\ \text{m/s},
\qquad
x(0)=0.
\]

Find \(v(2)\) and \(x(2)\).

### 9. Graph reasoning

At one instant, an object has negative velocity and positive acceleration. Is it speeding up or slowing down?

### 10. Projectile peak

State \(v_x\), \(v_y\), \(a_x\), and \(a_y\) at the highest point of an ideal projectile's path.

## Practice answers

### 1

\[
v(t)=5-4t,
\qquad
a(t)=-4.
\]

At \(t=3\ \text{s}\):

\[
\boxed{v=-7\ \text{m/s}},
\qquad
\boxed{a=-4\ \text{m/s}^2}.
\]

### 2

The object changes direction when \(v=0\), at \(t=3\ \text{s}\).

\[
\Delta x=\int_0^5(6-2t)\,dt=5\ \text{m}.
\]

The positive distance from \(0\) to \(3\) seconds is \(9\ \text{m}\), and the return distance from \(3\) to \(5\) seconds is \(4\ \text{m}\).

\[
\boxed{\text{distance}=13\ \text{m}}
\]

\[
\boxed{v_{\text{avg}}=1.0\ \text{m/s}},
\qquad
\boxed{\text{average speed}=2.6\ \text{m/s}}.
\]

### 3

\[
v=0+(3.0)(4.0)=\boxed{12\ \text{m/s}},
\]

\[
\Delta x=\frac12(3.0)(4.0)^2=\boxed{24\ \text{m}}.
\]

### 4

\[
0=20-5t
\quad\Rightarrow\quad
\boxed{t=4.0\ \text{s}}.
\]

\[
0^2=20^2+2(-5)\Delta x
\quad\Rightarrow\quad
\boxed{\Delta x=40\ \text{m}}.
\]

### 5

\[
v_{0x}=20\cos30^\circ=17.3\ \text{m/s},
\qquad
v_{0y}=20\sin30^\circ=10\ \text{m/s}.
\]

\[
\boxed{T=2.0\ \text{s}},
\qquad
\boxed{R=34.6\ \text{m}},
\qquad
\boxed{H=5.0\ \text{m}}.
\]

### 6

Vertical motion:

\[
-45=-\frac12(10)t^2
\quad\Rightarrow\quad
\boxed{t=3.0\ \text{s}}.
\]

Horizontal range:

\[
\boxed{x=(10)(3.0)=30\ \text{m}}.
\]

At impact,

\[
v_x=10\ \text{m/s},
\qquad
v_y=-30\ \text{m/s}.
\]

\[
\boxed{|\vec v|=\sqrt{10^2+30^2}=31.6\ \text{m/s}}.
\]

### 7

\[
\vec v_{\text{cyclist/observer}}
=\vec v_{\text{cyclist/ground}}
-\vec v_{\text{observer/ground}}.
\]

For an observer moving east at \(7\ \text{m/s}\):

\[
12-7=\boxed{5\ \text{m/s east}}.
\]

For an observer moving east at \(15\ \text{m/s}\):

\[
12-15=-3\ \text{m/s},
\]

so the cyclist moves at \(\boxed{3\ \text{m/s west}}\) relative to that observer.

### 8

\[
v(t)=3t^2+2,
\qquad
x(t)=t^3+2t.
\]

\[
\boxed{v(2)=14\ \text{m/s}},
\qquad
\boxed{x(2)=12\ \text{m}}.
\]

### 9

The velocity and acceleration have opposite signs, so the object is \(\boxed{\text{slowing down}}\).

### 10

At the peak:

\[
\boxed{v_x=v_{0x}},
\qquad
\boxed{v_y=0},
\qquad
\boxed{a_x=0},
\qquad
\boxed{a_y=-g}.
\]

## Your recorded relative-motion problems

Review the complete worked solutions for Problems 3.71, 3.72, 3.73, and 3.75 in [Relative Velocity — Worked Solutions](relative-velocity-solutions.md).

## Night-before plan

1. **20 minutes:** Reproduce the one-page formulas and graph rules from memory.
2. **25 minutes:** Practice derivatives, integrals, and initial conditions.
3. **30 minutes:** Do projectile Problems 5 and 6 without notes.
4. **25 minutes:** Redo two recorded relative-motion problems using object minus observer.
5. **25 minutes:** Complete the remaining practice check and correct every mistake.
6. **10 minutes:** Read the common test traps.
7. **Tomorrow morning:** Spend 10–15 minutes recalling formulas and signs; do not try to learn a new topic immediately before the test.

## Final readiness checklist

You are ready when you can do all of these without notes:

- Convert vectors between components and magnitude/direction.
- Distinguish distance from displacement and speed from velocity.
- Differentiate \(x(t)\) to find \(v(t)\) and \(a(t)\).
- Integrate \(a(t)\) or \(v(t)\) and apply initial conditions.
- Translate among motion descriptions, diagrams, equations, and graphs.
- Use slopes and signed areas correctly.
- Choose constant-acceleration equations only when acceleration is constant.
- Separate projectile motion into independent \(x\) and \(y\) components.
- Find relative velocity using object minus observer.
- Report answers with units, signs, and directions.
