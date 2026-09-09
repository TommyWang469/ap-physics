# AP Physics C: Mechanics — Unit 1 Kinematics Study Guide

Test: Thursday, September 10, 2026. Updated using your existing guide and September 8 AP Classroom question log.

This guide covers the kinematics topics you have been studying:

1. Scalars and vectors
2. Displacement, velocity, and acceleration
3. Representing motion
4. Reference frames and relative motion
5. Motion in two dimensions, extended to three-dimensional vector problems

## How to use this guide before Thursday

Start with the topics that require the most practice beyond AP Physics 1: calculus with initial conditions, vector components, and reference frames.

1. Read the core reference and the worked 3D examples.
2. Redo the targeted AP Classroom review, especially acceleration components and river crossings.
3. Try the original 10-question practice check, then the six-question Thursday practice set. Keep the solutions covered.
4. For each mistake, write the physical rule you missed and redo the question without looking.

The equations apply to ideal motion unless stated otherwise. Neglect air resistance for projectiles. Use \(g=9.8\ \text{m/s}^2\) unless a problem supplies another value; several practice problems explicitly use \(g=10\ \text{m/s}^2\).

## Core reference

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

The formulas for total flight time \(T\) and range \(R\) require launch and landing at the same height. The formula for \(H=v_{0y}^2/(2g)\) gives height gained above launch for an upward launch even when the landing height differs.

### What about three-dimensional motion?

Three-dimensional motion follows the same component method, with a \(z\)-component added:

\[
\vec r(t)=x(t)\hat i+y(t)\hat j+z(t)\hat k.
\]

Differentiate each component independently:

\[
\vec v(t)
=\frac{d\vec r}{dt}
=\frac{dx}{dt}\hat i
+\frac{dy}{dt}\hat j
+\frac{dz}{dt}\hat k,
\]

\[
\vec a(t)
=\frac{d\vec v}{dt}
=\frac{d^2x}{dt^2}\hat i
+\frac{d^2y}{dt^2}\hat j
+\frac{d^2z}{dt^2}\hat k.
\]

The speed is the magnitude of the velocity vector:

\[
|\vec v|=\sqrt{v_x^2+v_y^2+v_z^2}.
\]

Relative motion still uses object minus observer in all three components:

\[
\vec v_{A/B}
=(v_{Ax}-v_{Bx})\hat i
+(v_{Ay}-v_{By})\hat j
+(v_{Az}-v_{Bz})\hat k.
\]

Solve the \(x\), \(y\), and \(z\) directions independently using the same time. The worked 3D section below develops this method with direction angles, calculus, and relative motion.

### Inverse projectile problems: final velocity to initial velocity

#### Question type

A ball is thrown from a cliff. Its final velocity magnitude and direction at impact are given, and the problem asks for its initial velocity.

#### Method

Let upward be \(+y\), and let the cliff height be \(h\). If the ball's final speed is \(v_f\) at an angle \(\theta_f\) below horizontal, first resolve the final velocity:

\[
v_{fx}=v_f\cos\theta_f,
\qquad
v_{fy}=-v_f\sin\theta_f.
\]

There is no horizontal acceleration, so

\[
\boxed{v_{0x}=v_{fx}}.
\]

For the vertical direction, use

\[
v_{fy}^2=v_{0y}^2+2a_y\Delta y.
\]

Since \(a_y=-g\) and \(\Delta y=-h\),

\[
v_{fy}^2=v_{0y}^2+2gh,
\]

so

\[
\boxed{v_{0y}=\pm\sqrt{v_{fy}^2-2gh}}.
\]

Choose the sign from the wording: positive if the ball was initially thrown upward, negative if it was initially thrown downward, and zero if it was launched horizontally.

Finally,

\[
\boxed{v_0=\sqrt{v_{0x}^2+v_{0y}^2}},
\]

\[
\boxed{\theta_0=\tan^{-1}\left(\frac{|v_{0y}|}{|v_{0x}|}\right)}.
\]

State whether the initial direction is above or below horizontal based on the sign of \(v_{0y}\).

If flight time is given instead of enough displacement information, use

\[
\boxed{v_{0y}=v_{fy}+gt}.
\]

#### Example

A ball thrown upward from a \(15\ \text{m}\) cliff hits the ground at \(25\ \text{m/s}\), \(53^\circ\) below horizontal. Use \(g=10\ \text{m/s}^2\). Find its initial velocity.

Resolve the final velocity:

\[
v_{fx}=25\cos53^\circ\approx15\ \text{m/s},
\]

\[
v_{fy}=-25\sin53^\circ\approx-20\ \text{m/s}.
\]

The horizontal velocity is constant:

\[
v_{0x}=15\ \text{m/s}.
\]

For the vertical component,

\[
(-20)^2=v_{0y}^2+2(-10)(-15),
\]

\[
400=v_{0y}^2+300,
\]

\[
v_{0y}=+10\ \text{m/s},
\]

where the positive root is chosen because the ball was thrown upward.

Therefore,

\[
v_0=\sqrt{15^2+10^2}=18.0\ \text{m/s},
\]

\[
\theta_0=\tan^{-1}\left(\frac{10}{15}\right)=33.7^\circ.
\]

**Answer:** \(\boxed{18.0\ \text{m/s},\ 33.7^\circ\text{ above horizontal}}\).

If the problem gives only the final velocity and cliff height but does not say whether the ball was initially moving upward or downward, the sign of \(v_{0y}\), and therefore whether the initial angle is above or below horizontal, may be ambiguous.

#### What if the vertical displacement is unknown?

Without \(\Delta y\), do not use

\[
v_{fy}^2=v_{0y}^2+2a_y\Delta y.
\]

Look for another way to find the flight time.

If time is given, use

\[
v_{fy}=v_{0y}-gt
\quad\Rightarrow\quad
\boxed{v_{0y}=v_{fy}+gt}.
\]

If horizontal displacement is given, horizontal velocity is constant, so

\[
\boxed{t=\frac{\Delta x}{v_{fx}}},
\]

and then

\[
\boxed{v_{0y}=v_{fy}+gt}.
\]

If the problem says the ball was launched horizontally, then

\[
\boxed{v_{0y}=0}
\qquad\text{and}\qquad
\boxed{v_0=|v_{0x}|=|v_{fx}|}.
\]

If only the final velocity magnitude and direction are known, with no \(\Delta y\), flight time, horizontal displacement, or other initial condition, there is not enough information to determine one unique initial velocity. The known final velocity fixes \(v_{0x}=v_{fx}\), but many values of \(v_{0y}\) are possible for different flight times.

#### What if the maximum height is known?

At the highest point,

\[
v_y=0.
\]

If \(H\) is the vertical height gained from the launch point to the maximum point, use

\[
v_y^2=v_{0y}^2+2a_y\Delta y,
\]

\[
0=v_{0y}^2-2gH,
\]

so, for a ball initially thrown upward,

\[
\boxed{v_{0y}=\sqrt{2gH}}.
\]

If the final velocity is also known, its horizontal component gives

\[
\boxed{v_{0x}=v_{fx}=v_f\cos\theta_f}.
\]

Then recombine the components:

\[
\boxed{v_0=\sqrt{v_{0x}^2+v_{0y}^2}},
\]

\[
\boxed{\theta_0=\tan^{-1}\left(\frac{v_{0y}}{|v_{0x}|}\right)}.
\]

Be careful about how the maximum height is defined. If the problem gives the maximum height \(y_{\max}\) above the ground and the launch point is at height \(y_0\), then the height gained is

\[
\boxed{H=y_{\max}-y_0}.
\]

Knowing an absolute maximum height above the ground without knowing the cliff's launch height does not determine \(v_{0y}\). You need the height gained above the launch point.

For example, if a ball starts from a \(15\ \text{m}\) cliff and reaches a maximum height of \(20\ \text{m}\) above the ground, then \(H=5\ \text{m}\). With \(g=10\ \text{m/s}^2\),

\[
v_{0y}=\sqrt{2(10)(5)}=10\ \text{m/s upward}.
\]

#### Recorded problem: time for a rock thrown from a height

##### Question

A rock is thrown from a height \(h_0\) with an initial speed \(v_0\) at an angle \(\theta\) above the horizontal. Find the time the rock takes to reach the ground.

##### Solution

Choose upward as \(+y\), put the ground at \(y=0\), and let the rock begin at \(y_0=h_0\). The initial vertical component points upward, so

\[
v_{0y}=+v_0\sin\theta,
\qquad
a_y=-g.
\]

The vertical position equation is

\[
y(t)=h_0+(v_0\sin\theta)t-\frac12gt^2.
\]

Set \(y=0\) when the rock reaches the ground:

\[
0=h_0+(v_0\sin\theta)t-\frac12gt^2.
\]

Rewrite it in standard quadratic form:

\[
\frac12gt^2-(v_0\sin\theta)t-h_0=0.
\]

In the quadratic \(At^2+Bt+C=0\), the coefficients are

\[
A=\frac12g,
\qquad
B=-v_0\sin\theta,
\qquad
C=-h_0.
\]

The negative sign on \(B\) does not mean the initial speed \(v_0\) is negative. It appears because the entire position equation was rearranged into standard quadratic form.

Apply the quadratic formula:

\[
t=\frac{-B\pm\sqrt{B^2-4AC}}{2A}
=\frac{v_0\sin\theta\pm\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}.
\]

Because

\[
\sqrt{v_0^2\sin^2\theta+2gh_0}>v_0\sin\theta,
\]

the minus root gives a negative time. The physical answer is the positive root:

\[
\boxed{t=\frac{v_0\sin\theta+\sqrt{v_0^2\sin^2\theta+2gh_0}}{g}}.
\]

If the displayed explanation writes \(y(t)=h_0-v_{0y}t-\tfrac12gt^2\) while also defining upward as positive, that line has a sign inconsistency. With upward positive and a launch angle above horizontal, the initial-velocity term must be \(+v_{0y}t\). The selected answer still matches the correct equation above.

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

In one dimension:

| Velocity | Acceleration | What happens to speed? |
|---|---|---|
| Positive | Positive | Speed increases |
| Negative | Negative | Speed increases |
| Positive | Negative | Speed decreases |
| Negative | Positive | Speed decreases |

Negative acceleration does not automatically mean slowing down. It describes the direction of acceleration.

### Turning points

In one dimension, a direction change requires the velocity to change sign. A candidate time satisfies

\[
v=0,
\]

but acceleration does not have to be zero. Check the signs on either side: \(v(t)=(t-1)^2\) is zero at \(t=1\) but never becomes negative, so there is no direction reversal.

For a projectile, the vertical component reverses at the peak: \(v_y=0\) and \(a_y=-g\). Its full velocity is usually not zero because horizontal motion continues.

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

### The calculus rules you need

Treat constant coefficients as constants. When differentiating or integrating a vector, apply these rules separately to each component:

\[
\frac{d}{dt}t^n=nt^{n-1},
\qquad
\int t^n\,dt=\frac{t^{n+1}}{n+1}+C\quad(n\ne-1).
\]

\[
\frac{d}{dt}\sin(\omega t)=\omega\cos(\omega t),
\qquad
\int\cos(\omega t)\,dt=\frac{\sin(\omega t)}{\omega}+C
\quad(\omega\ne0).
\]

The factor \(\omega\) comes from the chain rule. Trigonometric calculus uses radians. For a definite integral, evaluate the antiderivative at both limits: \(\int_a^b f(t)\,dt=F(b)-F(a)\).

Units are a useful check: differentiating position gives meters per second; differentiating again gives meters per second squared. Integrating reverses those unit changes.

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

### TI-84 derivative and integral shortcuts

The TI-84 can calculate a **numerical derivative at one point** and a **numerical definite integral over an interval**. It does not normally return a symbolic derivative function or an indefinite integral with \(+C\).

#### Numerical derivative

Press `MATH`, select `8:nDeriv(`, and enter

```text
nDeriv(expression, variable, value)
```

Example:

```text
nDeriv(X^2, X, 3)
```

returns \(6\), the value of the derivative of \(x^2\) at \(x=3\).

For kinematics, if \(x(t)=t^2\), this can check that the instantaneous velocity at \(t=3\) is \(6\). If the question asks for the entire function \(v(t)\), you must still differentiate symbolically and write \(v(t)=2t\).

#### Definite integral

Press `MATH`, select `9:fnInt(`, and enter

```text
fnInt(expression, variable, lower bound, upper bound)
```

Example:

```text
fnInt(X^2, X, 0, 3)
```

returns \(9\).

In kinematics,

\[
\Delta x=\int_{t_i}^{t_f}v(t)\,dt
\]

and

\[
\Delta v=\int_{t_i}^{t_f}a(t)\,dt.
\]

Remember to add the initial value when appropriate:

\[
v_f=v_i+\int_{t_i}^{t_f}a(t)\,dt.
\]

For total distance, split the integral wherever velocity changes sign or integrate \(|v(t)|\). A direct integral of \(v(t)\) gives displacement, not distance.

The TI-84 is most useful for checking arithmetic. On a calculus-based physics test, show the derivative or integral setup and do the symbolic step yourself when the question asks for a derivation or function.

#### Symbolic derivatives and indefinite integrals

A standard TI-84 does not have a computer algebra system, so it will not transform

\[
f(x)=x^3
\]

into the symbolic derivative

\[
f'(x)=3x^2
\]

or the indefinite integral

\[
\int x^3\,dx=\frac{x^4}{4}+C.
\]

Those algebraic steps must be done by hand.

The calculator can graph a numerical approximation to a derivative function. For example, after entering a function in `Y1`, enter the following in `Y2`:

```text
nDeriv(Y1, X, X)
```

It can also graph one particular accumulation function, such as

```text
fnInt(T^2, T, 0, X)
```

which numerically represents

\[
F(x)=\int_0^x t^2\,dt.
\]

This gives the particular function with \(F(0)=0\), not the complete family of antiderivatives \(x^3/3+C\). These numerical graphing methods can be slow and do not replace symbolic work.

## Calculus skills to practice for this test

### 1. Given position, find velocity and acceleration

Differentiate once and twice:

\[
x(t)\longrightarrow v(t)=\frac{dx}{dt}
\longrightarrow a(t)=\frac{d^2x}{dt^2}.
\]

A question may also ask you to evaluate \(v\) and \(a\) at a specific time, find when the object is at rest by solving \(v(t)=0\), or determine when it changes direction.

Example:

\[
x(t)=2t^3-3t^2+4,
\]

\[
v(t)=6t^2-6t,
\qquad
a(t)=12t-6.
\]

### 2. Decide when an object speeds up or slows down

Find \(v(t)\) and \(a(t)\), locate every time when either expression is zero, and make a sign chart.

- Same signs for \(v\) and \(a\): speeding up.
- Opposite signs for \(v\) and \(a\): slowing down.

For the preceding example, \(v=6t(t-1)\) and \(a=12t-6\). For \(t>0\):

| Interval | Sign of \(v\) | Sign of \(a\) | Speed |
|---|---|---|---|
| \(0<t<0.5\) | Negative | Negative | Increasing |
| \(0.5<t<1\) | Negative | Positive | Decreasing |
| \(t>1\) | Positive | Positive | Increasing |

At \(t=0.5\), acceleration is zero but velocity is not. At \(t=1\), velocity changes sign and the object reverses direction.

### 3. Given velocity, find displacement and distance

Displacement is the signed integral:

\[
\Delta x=\int_{t_i}^{t_f}v(t)\,dt.
\]

For distance, first solve \(v(t)=0\) to find direction changes, then add the absolute value of each interval's displacement:

\[
\text{distance}=\int_{t_i}^{t_f}|v(t)|\,dt.
\]

### 4. Given acceleration, recover velocity and position

Integrate twice and use the initial conditions:

\[
v(t)=v_0+\int_0^t a(\tau)\,d\tau,
\]

\[
x(t)=x_0+\int_0^t v(\tau)\,d\tau.
\]

Example:

\[
a(t)=4t,
\qquad
v(0)=3,
\qquad
x(0)=1,
\]

gives

\[
v(t)=2t^2+3,
\]

\[
x(t)=\frac{2}{3}t^3+3t+1.
\]

### 5. Interpret calculus on motion graphs

Practice questions such as:

- Find instantaneous velocity from the tangent slope of an \(x\)-versus-\(t\) graph.
- Find acceleration from the slope of a \(v\)-versus-\(t\) graph.
- Find displacement from signed area under \(v(t)\).
- Find change in velocity from signed area under \(a(t)\).
- Match position, velocity, and acceleration graphs.

### 6. Differentiate vector position functions

Differentiate each component separately:

\[
\vec r(t)=x(t)\hat i+y(t)\hat j,
\]

\[
\vec v(t)=x'(t)\hat i+y'(t)\hat j,
\]

\[
\vec a(t)=x''(t)\hat i+y''(t)\hat j.
\]

Then find speed using

\[
|\vec v|=\sqrt{v_x^2+v_y^2}.
\]

Example:

\[
\vec r(t)=t^2\hat i+2t^3\hat j.
\]

At \(t=1\),

\[
\vec v=2\hat i+6\hat j,
\qquad
|\vec v|=2\sqrt{10},
\qquad
\vec a=2\hat i+12\hat j.
\]

### 7. Use the chain rule when acceleration depends on position

If time is not present, use

\[
\boxed{a=v\frac{dv}{dx}}.
\]

Then separate and integrate:

\[
v\,dv=a(x)\,dx.
\]

This is a more challenging problem type, but it is worth recognizing.

### 8. Derive a familiar kinematics result

The constant-acceleration equations come directly from the definitions of acceleration and velocity. The derivation below assumes that \(a\) is constant.

#### Deriving velocity

Begin with

\[
a=\frac{dv}{dt}
\]

and separate the differentials:

\[
dv=a\,dt.
\]

Integrate from the initial state \((t=0,v=v_0)\) to the later state \((t,v)\):

\[
\int_{v_0}^{v}dv=\int_0^t a\,dt.
\]

Because \(a\) is constant,

\[
v-v_0=at,
\]

so

\[
\boxed{v=v_0+at}.
\]

The initial velocity appears because the integral calculates the change \(v-v_0\), not the entire final velocity by itself.

#### Deriving position

Use the definition of velocity:

\[
v=\frac{dx}{dt}.
\]

Substitute \(v=v_0+at\):

\[
\frac{dx}{dt}=v_0+at.
\]

Separate and integrate from \((t=0,x=x_0)\) to \((t,x)\):

\[
\int_{x_0}^{x}dx
=\int_0^t(v_0+a\tau)\,d\tau.
\]

The dummy variable \(\tau\) is used inside the integral so that \(t\) can remain the upper limit. Evaluating gives

\[
x-x_0=v_0t+\frac12at^2,
\]

so

\[
\boxed{x=x_0+v_0t+\frac12at^2}.
\]

#### Indefinite-integral version

The same derivation can be written using constants of integration:

\[
v=\int a\,dt=at+C_1.
\]

Using \(v(0)=v_0\) gives \(C_1=v_0\). Then

\[
x=\int(v_0+at)\,dt
=v_0t+\frac12at^2+C_2.
\]

Using \(x(0)=x_0\) gives \(C_2=x_0\).

#### Deriving the equation without time

Use the chain rule:

\[
a=\frac{dv}{dt}
=\frac{dv}{dx}\frac{dx}{dt}
=v\frac{dv}{dx}.
\]

Then

\[
v\,dv=a\,dx.
\]

Integrate between the initial and final states:

\[
\int_{v_0}^{v}v\,dv
=\int_{x_0}^{x}a\,dx.
\]

For constant \(a\),

\[
\frac12(v^2-v_0^2)=a(x-x_0),
\]

so

\[
\boxed{v^2=v_0^2+2a(x-x_0)}.
\]

For full credit on a derivation, state that acceleration is constant, include integration limits or integration constants, apply the initial conditions, and show the algebra leading to the requested equation.

### Highest-priority order for a last-minute review

1. Differentiate \(x(t)\) to obtain \(v(t)\) and \(a(t)\).
2. Integrate \(a(t)\) using initial conditions.
3. Find displacement versus distance from \(v(t)\).
4. Use slopes and signed areas on graphs.
5. Differentiate vector functions component by component.
6. Recognize \(a=v\,dv/dx\).

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

For projectile motion, create separate component equations and use the same elapsed time in each. The launch speed and angle determine the initial components together.

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

## Three-dimensional vectors: worked examples

For this section only, choose \(+x\) east, \(+y\) north, and \(+z\) upward. The earlier 2D projectile section uses \(+y\) upward. Always label your axes first.

### Magnitude, direction, and components

A vector \(\vec A=A_x\hat i+A_y\hat j+A_z\hat k\) has magnitude and unit direction vector

\[
|\vec A|=\sqrt{A_x^2+A_y^2+A_z^2},
\qquad
\hat u_A=\frac{\vec A}{|\vec A|}.
\]

The unit vector has no units and length 1. A zero vector has no defined direction.

If \(\alpha,\beta,\gamma\) are angles with the positive \(x,y,z\) axes,

\[
\cos\alpha=\frac{A_x}{|\vec A|},\quad
\cos\beta=\frac{A_y}{|\vec A|},\quad
\cos\gamma=\frac{A_z}{|\vec A|}.
\]

A negative component gives an axis angle greater than \(90^\circ\). These three angles obey \(\cos^2\alpha+\cos^2\beta+\cos^2\gamma=1\).

Alternatively, describe direction with a horizontal bearing and an elevation. Let \(\phi\) be measured in the horizontal plane from east toward north, and \(\theta\) be elevation above horizontal:

\[
A_x=A\cos\theta\cos\phi,\quad
A_y=A\cos\theta\sin\phi,\quad
A_z=A\sin\theta.
\]

To recover the angles, first find \(A_h=\sqrt{A_x^2+A_y^2}\). Then use \(\phi=\operatorname{atan2}(A_y,A_x)\) with the correct compass quadrant, and \(\theta=\operatorname{atan2}(A_z,A_h)\).

**Example:** A drone has \(\vec v=(3,4,12)\ \text{m/s}\).

\[
|\vec v|=\sqrt{9+16+144}=13\ \text{m/s},
\qquad
\hat u_v=\frac3{13}\hat i+\frac4{13}\hat j+\frac{12}{13}\hat k.
\]

Its horizontal projection points \(53.1^\circ\) north of east, and its elevation is

\[
\theta=\tan^{-1}\left(\frac{12}{5}\right)=67.4^\circ
\]

above horizontal. One ordinary planar angle alone does not specify a general 3D direction.

### Example 1: Differentiate a 3D position function

**Question:** In SI units, a particle has

\[
\vec r(t)=(1+2t^2)\hat i+(3t-t^2)\hat j+(4-2t)\hat k.
\]

At \(t=2\ \text{s}\), find position, velocity, speed, acceleration, and whether its speed is increasing. Also find its average velocity from \(t=0\) to \(t=2\ \text{s}\).

**Solution:** Differentiate each component:

\[
\vec v(t)=4t\hat i+(3-2t)\hat j-2\hat k,
\qquad
\vec a(t)=4\hat i-2\hat j.
\]

At \(t=2\),

\[
\vec r=(9,2,0)\ \text{m},\quad
\vec v=(8,-1,-2)\ \text{m/s},\quad
\vec a=(4,-2,0)\ \text{m/s}^2.
\]

\[
|\vec v|=\sqrt{69}=8.31\ \text{m/s},
\qquad
|\vec a|=\sqrt{20}=4.47\ \text{m/s}^2.
\]

In 2D or 3D, use the dot product to check speeding up:

\[
\vec v\cdot\vec a=v_xa_x+v_ya_y+v_za_z,
\qquad
\frac{d|\vec v|}{dt}=\frac{\vec v\cdot\vec a}{|\vec v|}
\quad (|\vec v|>0).
\]

Positive dot product means speeding up; negative means slowing down; zero means speed is instantaneously unchanging. Here \(8(4)+(-1)(-2)+(-2)(0)=34>0\), so the particle is speeding up.

For average velocity, use the endpoints rather than the derivative at the endpoint:

\[
\vec v_{\mathrm{avg}}
=\frac{(9,2,0)-(1,0,4)}{2}
=(4,1,-2)\ \text{m/s}.
\]

**Key distinction:** \(d|\vec v|/dt\) is the rate of change of speed. It is generally different from \(|\vec a|\), because acceleration can also change direction.

### Example 2: Integrate a 3D acceleration function

**Question:** In SI units,

\[
\vec a(t)=2\hat i+6t\hat j-4\hat k,\quad
\vec v(0)=(1,-2,3),\quad
\vec r(0)=(0,1,2).
\]

Find \(\vec v(t)\), \(\vec r(t)\), and their values at \(t=1\ \text{s}\).

**Solution:** Integrate each component and use all three initial components:

\[
\vec v(t)=(1+2t)\hat i+(-2+3t^2)\hat j+(3-4t)\hat k.
\]

\[
\vec r(t)=(t+t^2)\hat i+(1-2t+t^3)\hat j+(2+3t-2t^2)\hat k.
\]

Thus

\[
\boxed{\vec v(1)=(3,1,-1)\ \text{m/s}},
\qquad
\boxed{\vec r(1)=(2,0,3)\ \text{m}}.
\]

Check by differentiating \(\vec r\) to recover \(\vec v\), differentiating \(\vec v\) to recover \(\vec a\), and substituting \(t=0\) into both.

**When the initial time is not zero:** if \(\vec v(2)\) is given, write

\[
\vec v(t)=\vec v(2)+\int_2^t\vec a(\tau)\,d\tau.
\]

The integration constant is not automatically the given velocity when that velocity is specified at a nonzero time.

### Example 3: Relative velocity in 3D

**Question:** Two drones have ground velocities

\[
\vec v_{A/G}=(8,3,2)\ \text{m/s},\qquad
\vec v_{B/G}=(2,-1,2)\ \text{m/s}.
\]

Find A's velocity relative to B, including magnitude and direction.

**Solution:** Object minus observer, in every component:

\[
\vec v_{A/B}=(8-2,3-(-1),2-2)=(6,4,0)\ \text{m/s}.
\]

\[
|\vec v_{A/B}|=\sqrt{52}=7.21\ \text{m/s},
\qquad
\phi=\tan^{-1}(4/6)=33.7^\circ.
\]

**Answer:** \(7.21\ \text{m/s}\), horizontally \(33.7^\circ\) north of east. The drones have identical vertical velocities, so B sees no vertical motion of A.

For nonrotating frames with parallel axes, the same subtraction holds for position and acceleration:

\[
\vec r_{A/B}=\vec r_{A/G}-\vec r_{B/G},
\qquad
\vec a_{A/B}=\vec a_{A/G}-\vec a_{B/G}.
\]

If B has constant velocity, \(\vec a_{B/G}=0\), so A's acceleration is the same in both frames.

### Example 4: A projectile with three velocity components

**Question:** A ball starts at \((0,0,20)\ \text{m}\) with initial velocity \((6,8,10)\ \text{m/s}\). Use \(z\) upward and \(g=10\ \text{m/s}^2\). Find its landing time, landing position, impact velocity, impact speed, and maximum height above ground.

**Solution:** Gravity acts only vertically:

\[
\vec a=(0,0,-10)\ \text{m/s}^2.
\]

\[
x=6t,\qquad y=8t,\qquad z=20+10t-5t^2.
\]

Set \(z=0\) at ground impact:

\[
t^2-2t-4=0
\quad\Rightarrow\quad
t=1+\sqrt5=3.24\ \text{s}.
\]

The other root is negative. Using the positive time gives

\[
\vec r_{\mathrm{land}}=(19.4,25.9,0)\ \text{m}.
\]

\[
\vec v(t)=(6,8,10-10t)
\quad\Rightarrow\quad
\vec v_{\mathrm{impact}}=(6,8,-10\sqrt5)\ \text{m/s}.
\]

\[
|\vec v_{\mathrm{impact}}|
=\sqrt{6^2+8^2+(10\sqrt5)^2}
=10\sqrt6=24.5\ \text{m/s}.
\]

At the peak \(v_z=0\), so \(t_{\mathrm{peak}}=1\ \text{s}\) and \(z_{\max}=25\ \text{m}\). The ball is still moving horizontally at \(\sqrt{6^2+8^2}=10\ \text{m/s}\).

The horizontal range is the length of the horizontal displacement, \(\sqrt{x^2+y^2}=10t=32.4\ \text{m}\). It is not the total distance traveled along the curved path.

### Displacement and distance in three dimensions

\[
\Delta\vec r=\vec r(t_f)-\vec r(t_i)=\int_{t_i}^{t_f}\vec v(t)\,dt,
\]

\[
\text{distance}=\int_{t_i}^{t_f}|\vec v(t)|\,dt
=\int_{t_i}^{t_f}\sqrt{v_x^2+v_y^2+v_z^2}\,dt.
\]

Do not add the distances traveled along the three axes. Do not replace the integral of speed with the magnitude of displacement unless the path is straight and never reverses.

## Targeted review from your AP Classroom questions

### Two mistakes to redo first

**Acceleration components, Q10:** For \(x=3t^2-2\) and \(y=2-t^3\), differentiate twice to get \((a_x,a_y)=(6,-6t)\). At \(t=0\), the magnitude is \(6\ \text{m/s}^2\); at \(t=1\), it is \(6\sqrt2\ \text{m/s}^2\). The components at \(t=1\) are perpendicular and do not cancel. In 3D, add \(a_z^2\) inside the square root.

**River crossing:** To land directly across, the boat's ground velocity must have zero downstream component. With current \(+5\ \text{m/s}\), aim upstream so \(v_{\mathrm{boat/water},x}=-5\ \text{m/s}\). For a boat speed of \(10\ \text{m/s}\) relative to water, \(\sin\theta=5/10\), so aim \(30^\circ\) upstream from straight across. Greater boat speed alone does not prevent drift.

### Four explanations to reproduce without notes

- **Rocket integration:** \(a=50-2t^2\), \(v(0)=6\), \(y(0)=10\) gives \(v=6+50t-\frac23t^3\) and \(y=10+6t+25t^2-\frac16t^4\). On \(0\le t\le5\), acceleration is nonnegative and velocity is positive, so velocity and position increase.
- **Rock above a cliff:** with upward positive, \(y=h_0+v_0\sin\theta\,t-\frac12gt^2\). The initial vertical term is positive for an upward throw. A minus sign on the linear coefficient after rearranging the quadratic does not make the initial speed negative.
- **Moving cart:** the ground observer sees \(\vec v=(v_1,-2v_1)\), so the speed is \(\sqrt5v_1\). The cart has zero acceleration, so both observers measure the same gravitational acceleration.
- **Graph matching:** negative acceleration approaching zero means a velocity graph with a negative slope that flattens. If velocity is negative too, speed increases. Area under acceleration gives change in velocity; add the initial velocity.

The [AP Classroom question log](ap-classroom-unit-1-question-log.md) contains all 14 unique questions and their answers.

## Thursday practice set: calculus and 3D vectors

Allow about 35 minutes. All polynomial expressions use seconds and SI units; coefficients carry the units needed. In 3D questions, use \(x\) east, \(y\) north, and \(z\) upward.

### A. Three-component vector subtraction

Let \(\vec A=(4,-2,5)\ \text{m}\) and \(\vec B=(1,3,-1)\ \text{m}\). Find \(\vec A-2\vec B\), its magnitude, and a unit vector in its direction.

### B. Position, velocity, speed, and acceleration

\[
\vec r(t)=t^2\hat i+2t\hat j+(6-3t)\hat k.
\]

At \(t=1\ \text{s}\), find \(\vec r\), \(\vec v\), speed, \(\vec a\), and the unit vector along the velocity. Is speed increasing?

### C. Acceleration to position

\[
\vec a(t)=2\hat j-6t\hat k,\qquad
\vec v(0)=(3,-1,4),\qquad
\vec r(0)=(1,0,2).
\]

Find \(\vec v(t)\), \(\vec r(t)\), and the speed at \(t=1\ \text{s}\).

### D. Relative motion with vertical motion

The ground velocities of two objects are \(\vec v_{A/G}=(5,2,-1)\ \text{m/s}\) and \(\vec v_{B/G}=(-1,2,3)\ \text{m/s}\). Find A's velocity relative to B, its magnitude, and its elevation above or below horizontal.

### E. Acceleration graph and signed area

In one dimension, \(a(t)=-4+t\) and \(v(0)=-2\ \text{m/s}\), for \(0\le t\le4\ \text{s}\). Find \(v(4)\), displacement, and distance. Describe how speed changes and whether the object stops when acceleration reaches zero.

### F. Three-dimensional projectile

A ball launches from \((0,0,15)\ \text{m}\) with \(\vec v_0=(3,4,10)\ \text{m/s}\). Use \(g=10\ \text{m/s}^2\). Find landing time, landing position, impact velocity, impact speed, and maximum height above ground.

## Thursday practice solutions

### A. Subtract first, then take the magnitude

\[
\vec A-2\vec B=(4-2,-2-6,5+2)=(2,-8,7)\ \text{m}.
\]

\[
|\vec A-2\vec B|=\sqrt{4+64+49}=\sqrt{117}=10.8\ \text{m}.
\]

\[
\hat u=\frac{2\hat i-8\hat j+7\hat k}{\sqrt{117}}.
\]

Check that \(|\hat u|=1\). Subtracting magnitudes would give a different, incorrect result.

### B. Differentiate components

\[
\vec r(1)=(1,2,3)\ \text{m},
\quad
\vec v(t)=(2t,2,-3),
\quad
\vec a(t)=(2,0,0).
\]

At \(t=1\),

\[
\vec v=(2,2,-3)\ \text{m/s},\qquad
|\vec v|=\sqrt{17}=4.12\ \text{m/s},
\]

\[
\vec a=(2,0,0)\ \text{m/s}^2,\qquad
\hat u_v=\frac{2\hat i+2\hat j-3\hat k}{\sqrt{17}}.
\]

Since \(\vec v\cdot\vec a=4>0\), speed is increasing.

### C. Apply the initial condition after each integration

\[
\vec v(t)=3\hat i+(-1+2t)\hat j+(4-3t^2)\hat k.
\]

\[
\vec r(t)=(1+3t)\hat i+(-t+t^2)\hat j+(2+4t-t^3)\hat k.
\]

At \(t=1\), \(\vec r=(4,0,5)\ \text{m}\) and \(\vec v=(3,1,1)\ \text{m/s}\), giving speed \(\sqrt{11}=3.32\ \text{m/s}\).

### D. Object minus observer

\[
\vec v_{A/B}=(5,2,-1)-(-1,2,3)=(6,0,-4)\ \text{m/s}.
\]

Magnitude \(=\sqrt{52}=7.21\ \text{m/s}\). The horizontal projection is eastward; elevation is \(\tan^{-1}(-4/6)=-33.7^\circ\). The direction is \(33.7^\circ\) below horizontal toward the east.

### E. Keep the initial velocity

\[
v(t)=-2+\int_0^t(-4+\tau)\,d\tau=-2-4t+\frac12t^2.
\]

\[
v(4)=-10\ \text{m/s}.
\]

Velocity is negative throughout the interval, so

\[
\Delta x=\int_0^4\left(-2-4t+\frac12t^2\right)dt
=\left[-2t-2t^2+\frac16t^3\right]_0^4
=-\frac{88}{3}\ \text{m}.
\]

Distance \(=88/3=29.3\ \text{m}\). For \(0\le t<4\), both \(v\) and \(a\) are negative, so speed increases. At \(t=4\), the velocity graph has zero slope, but the object is still moving at \(-10\ \text{m/s}\).

### F. Use vertical motion to find the common time

\[
0=15+10t-5t^2
\quad\Rightarrow\quad
t^2-2t-3=(t-3)(t+1)=0.
\]

Choose \(t=3\ \text{s}\). Then

\[
\vec r_{\mathrm{land}}=(3t,4t,0)=(9,12,0)\ \text{m},
\]

\[
\vec v_{\mathrm{impact}}=(3,4,10-10t)=(3,4,-20)\ \text{m/s}.
\]

\[
|\vec v_{\mathrm{impact}}|=\sqrt{9+16+400}=\sqrt{425}=20.6\ \text{m/s}.
\]

At the peak \(v_z=0\), so \(t=1\ \text{s}\) and \(z_{\max}=15+10-5=20\ \text{m}\). Horizontal speed stays \(5\ \text{m/s}\).

## Your recorded relative-motion problems

Review the complete worked solutions for Problems 3.37, 3.71, 3.72, 3.73, and 3.75, plus the moving-cart question, in [Relative Velocity — Worked Solutions](relative-velocity-solutions.md).

## Night-before plan

1. **15 minutes:** Reproduce the core formulas and graph rules from memory.
2. **20 minutes:** Redo the rocket integration, acceleration-components question, and river crossing.
3. **25 minutes:** Work through the 3D examples, covering each solution before trying it.
4. **35 minutes:** Complete the six-question Thursday practice set.
5. **20 minutes:** Correct mistakes and redo the questions that caused them. Use the original practice check for any weak basic topics.
6. **Thursday morning, 10 minutes:** Recall the formulas, reference-frame subtraction order, and component signs.

## Final readiness checklist

You are ready when you can do all of these without notes:

- Convert vectors between components and magnitude/direction.
- Find a 3D unit direction vector or describe direction using a horizontal bearing and elevation.
- Distinguish distance from displacement and speed from velocity.
- Differentiate \(x(t)\) to find \(v(t)\) and \(a(t)\).
- Differentiate and integrate all three components of a vector function.
- Integrate \(a(t)\) or \(v(t)\) and apply initial conditions.
- Translate among motion descriptions, diagrams, equations, and graphs.
- Use slopes and signed areas correctly.
- Choose constant-acceleration equations only when acceleration is constant.
- Separate projectile motion into independent \(x\) and \(y\) components.
- Use \(z\) as the vertical coordinate when a 3D problem defines it that way.
- Find relative velocity using object minus observer.
- Distinguish acceleration magnitude from the rate of change of speed.
- Report answers with units, signs, and directions.
