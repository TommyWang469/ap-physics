# Relative Velocity — Worked Solutions

Use east as the positive \(x\)-direction and north as the positive \(y\)-direction throughout.

The basic relationship is

\[
\vec v_{A/C}=\vec v_{A/B}+\vec v_{B/C}.
\]

## Core shortcut: object minus observer

When a problem asks for an object's velocity relative to an observer, subtract the observer's velocity from the object's velocity:

\[
\boxed{\vec v_{\text{object/observer}}
=\vec v_{\text{object/reference}}
-\vec v_{\text{observer/reference}}}
\]

Both velocities on the right must be measured relative to the same reference frame, usually the ground or Earth.

For example,

\[
\vec v_{\text{ball/Juan}}
=\vec v_{\text{ball/ground}}
-\vec v_{\text{Juan/ground}}.
\]

The order matters: **object minus observer**.

### Why subtraction works

The object's position relative to the observer is the separation between their positions:

\[
\vec r_{\text{object/observer}}
=\vec r_{\text{object}}-\vec r_{\text{observer}}.
\]

Taking the rate of change of both sides gives

\[
\vec v_{\text{object/observer}}
=\vec v_{\text{object}}-\vec v_{\text{observer}}.
\]

Intuitively, the observer considers themself stationary, so the observer's velocity is subtracted from every object in the scene. For example, if a car travels east at \(10\ \text{m/s}\) and the observer travels east at \(6\ \text{m/s}\), the observer sees the car moving east at

\[
10-6=4\ \text{m/s}.
\]

If both travel with the same velocity, the result is zero, which agrees with the fact that the object appears stationary to the observer.

### The same rule for position and acceleration

For ordinary, nonrotating reference frames, use **object minus observer** for all three quantities:

\[
\boxed{\vec r_{\text{object/observer}}
=\vec r_{\text{object/reference}}
-\vec r_{\text{observer/reference}}}
\]

\[
\boxed{\vec v_{\text{object/observer}}
=\vec v_{\text{object/reference}}
-\vec v_{\text{observer/reference}}}
\]

\[
\boxed{\vec a_{\text{object/observer}}
=\vec a_{\text{object/reference}}
-\vec a_{\text{observer/reference}}}
\]

The vectors being subtracted must be measured in the same reference frame and expressed using the same coordinate directions. In more advanced problems involving a rotating observer, such as someone on a spinning platform, extra rotation terms may be needed. The direct subtraction rule is the one to use for the nonrotating frames in these exercises.

## AP Classroom — Stone released from a moving cart

### Question

Student 1 stands on a cart holding a small stone while Student 2 stands on the ground. The cart moves at a constant speed \(v_1\) in the \(+x\)-direction. Student 1 releases the stone from rest relative to the cart. Just before the stone reaches the ground, Student 1 measures the stone's speed as \(2v_1\) and its acceleration as \(a_1\). At the same instant, Student 2 measures the stone's speed as \(v_2\) and its acceleration as \(a_2\). Find the relationships between \(v_2\) and \(v_1\), and between \(a_2\) and \(a_1\).

### Solution

Because the stone is released from rest relative to the cart and there is no horizontal acceleration, Student 1 sees the stone fall straight downward. Just before impact,

\[
\vec v_{S/C}=(0,-2v_1).
\]

The cart's velocity relative to the ground is

\[
\vec v_{C/G}=(v_1,0).
\]

Use the relative-velocity addition rule:

\[
\vec v_{S/G}=\vec v_{S/C}+\vec v_{C/G}.
\]

Therefore, Student 2 measures

\[
\vec v_{S/G}=(v_1,-2v_1).
\]

The two components are perpendicular, so the speed is found with the Pythagorean theorem:

\[
v_2=|\vec v_{S/G}|
=\sqrt{v_1^2+(-2v_1)^2}
=\boxed{\sqrt5\,v_1}.
\]

The speeds are not added as \(v_1+2v_1\) because the horizontal and vertical velocities point in perpendicular directions.

The cart moves at constant velocity, so its acceleration is zero. Thus,

\[
\vec a_{S/G}=\vec a_{S/C}+\vec a_{C/G}
=\vec a_{S/C}.
\]

Both students therefore measure the same downward gravitational acceleration:

\[
\boxed{a_2=a_1}.
\]

**Answer:** \(\boxed{v_2=\sqrt5\,v_1\text{ and }a_2=a_1}\), which is choice A.

## Problem 3.37 — Canoe relative to a river

### Question

A canoe has a velocity of \(0.40\ \text{m/s}\) southeast relative to Earth. The canoe is on a river that is flowing \(0.50\ \text{m/s}\) east relative to Earth. Find the velocity (magnitude and direction) of the canoe relative to the river.

### Solution

Use object minus observer:

\[
\vec v_{C/R}=\vec v_{C/E}-\vec v_{R/E}.
\]

Let east be \(+x\) and north be \(+y\). Southeast is \(45^\circ\) south of east, so the canoe's Earth-velocity components are

\[
\vec v_{C/E}
=\left(0.40\cos45^\circ,-0.40\sin45^\circ\right)
=(0.283,-0.283)\ \text{m/s}.
\]

The river's Earth-velocity is

\[
\vec v_{R/E}=(0.50,0)\ \text{m/s}.
\]

Therefore,

\[
\vec v_{C/R}
=(0.283,-0.283)-(0.50,0)
=(-0.217,-0.283)\ \text{m/s}.
\]

The magnitude is

\[
|\vec v_{C/R}|
=\sqrt{(-0.217)^2+(-0.283)^2}
=0.357\ \text{m/s}
\approx 0.36\ \text{m/s}.
\]

Both components are negative, so the direction is southwest. Measured south of west,

\[
\theta
=\tan^{-1}\left(\frac{0.283}{0.217}\right)
=52.5^\circ.
\]

**Answer:** \(\boxed{0.36\ \text{m/s},\ 52^\circ\text{ south of west}}\), equivalently \(38^\circ\) west of south.

## Problem 3.71 — Airplane and wind

### Question

An airplane pilot sets a compass course due west and maintains an airspeed of \(220\ \text{km/h}\). After flying for \(0.500\ \text{h}\), she finds herself over a town \(120\ \text{km}\) west and \(20\ \text{km}\) south of her starting point.

1. Find the wind velocity (magnitude and direction).
2. If the wind velocity is \(40\ \text{km/h}\) due south, in what direction should the pilot set her course to travel due west? Use the same airspeed of \(220\ \text{km/h}\).

### Solution

### (a) Wind velocity

The plane's velocity relative to the ground is

\[
\vec v_{P/G}
=\frac{(-120,-20)\ \text{km}}{0.500\ \text{h}}
=(-240,-40)\ \text{km/h}.
\]

Its velocity relative to the air is

\[
\vec v_{P/A}=(-220,0)\ \text{km/h}.
\]

Because

\[
\vec v_{P/G}=\vec v_{P/A}+\vec v_{A/G},
\]

the wind velocity is

\[
\vec v_{A/G}=(-240,-40)-(-220,0)=(-20,-40)\ \text{km/h}.
\]

Its magnitude is

\[
|\vec v_{A/G}|=\sqrt{20^2+40^2}=44.7\ \text{km/h}.
\]

Its direction is

\[
\theta=\tan^{-1}\left(\frac{40}{20}\right)=63.4^\circ.
\]

**Answer:** \(\boxed{44.7\ \text{km/h},\ 63.4^\circ\text{ south of west}}\), equivalently \(26.6^\circ\) west of south.

### (b) Course for a due-west ground path

If the wind blows south at \(40\ \text{km/h}\), the plane needs a \(40\ \text{km/h}\) northward airspeed component:

\[
220\sin\theta=40.
\]

Therefore,

\[
\theta=\sin^{-1}\left(\frac{40}{220}\right)=10.5^\circ.
\]

**Answer:** \(\boxed{10.5^\circ\text{ north of west}}\).

## Problem 3.72 — Raindrops and a moving train

### Question

When a train's velocity is \(12.0\ \text{m/s}\) eastward, raindrops that are falling vertically with respect to Earth make traces that are inclined \(30.0^\circ\) to the vertical on the windows of the train.

1. What is the horizontal component of a drop's velocity with respect to Earth? With respect to the train?
2. What is the magnitude of the velocity of the raindrop with respect to Earth? With respect to the train?

### Solution

The relative-velocity equation is

\[
\vec v_{R/T}=\vec v_{R/E}-\vec v_{T/E}.
\]

Since the rain has no horizontal velocity relative to Earth,

\[
\vec v_{R/E}=(0,-v_y),
\qquad
\vec v_{T/E}=(12.0,0),
\]

so

\[
\vec v_{R/T}=(-12.0,-v_y).
\]

The observed angle gives

\[
\tan 30.0^\circ=\frac{12.0}{v_y},
\]

and therefore

\[
v_y=\frac{12.0}{\tan30.0^\circ}=20.8\ \text{m/s}.
\]

### (a) Horizontal components

- Relative to Earth: \(\boxed{0\ \text{m/s}}\)
- Relative to the train: \(\boxed{12.0\ \text{m/s westward}}\)

### (b) Velocity magnitudes

Relative to Earth:

\[
\boxed{20.8\ \text{m/s}}.
\]

Relative to the train:

\[
|\vec v_{R/T}|=\sqrt{12.0^2+20.8^2}=\boxed{24.0\ \text{m/s}}.
\]

## Problem 3.73 — Soccer ball relative to Juan

### Question

In a World Cup soccer match, Juan is running due north toward the goal with a speed of \(8.00\ \text{m/s}\) relative to the ground. A teammate passes the ball to him. The ball has a speed of \(12.0\ \text{m/s}\) and is moving in a direction \(37.0^\circ\) east of north, relative to the ground. What are the magnitude and direction of the ball's velocity relative to Juan?

### Solution

The ball's ground-velocity components are

\[
v_{B/G,x}=12.0\sin37.0^\circ=7.22\ \text{m/s},
\]

\[
v_{B/G,y}=12.0\cos37.0^\circ=9.58\ \text{m/s}.
\]

Juan's velocity is

\[
\vec v_{J/G}=(0,8.00)\ \text{m/s}.
\]

Thus,

\[
\vec v_{B/J}
=\vec v_{B/G}-\vec v_{J/G}
=(7.22,1.58)\ \text{m/s}.
\]

The magnitude is

\[
|\vec v_{B/J}|=\sqrt{7.22^2+1.58^2}=7.39\ \text{m/s}.
\]

The direction measured north of east is

\[
\theta=\tan^{-1}\left(\frac{1.58}{7.22}\right)=12.4^\circ.
\]

**Answer:** \(\boxed{7.39\ \text{m/s},\ 12.4^\circ\text{ north of east}}\), equivalently \(77.6^\circ\) east of north.

## Problem 3.75 — Soccer ball relative to the ground

### Question

Two soccer players, Mia and Alice, are running as Alice passes the ball to Mia. Mia is running due north with a speed of \(6.00\ \text{m/s}\). The velocity of the ball relative to Mia is \(5.00\ \text{m/s}\) in a direction \(30.0^\circ\) east of south. What are the magnitude and direction of the velocity of the ball relative to the ground?

### Solution

Use

\[
\vec v_{B/G}=\vec v_{B/M}+\vec v_{M/G}.
\]

The ball's velocity components relative to Mia are

\[
v_{B/M,x}=5.00\sin30.0^\circ=2.50\ \text{m/s},
\]

\[
v_{B/M,y}=-5.00\cos30.0^\circ=-4.33\ \text{m/s}.
\]

Adding Mia's ground velocity gives

\[
\vec v_{B/G}=(2.50,-4.33)+(0,6.00)=(2.50,1.67)\ \text{m/s}.
\]

The magnitude is

\[
|\vec v_{B/G}|=\sqrt{2.50^2+1.67^2}=3.01\ \text{m/s}.
\]

The direction measured east of north is

\[
\theta=\tan^{-1}\left(\frac{2.50}{1.67}\right)=56.3^\circ.
\]

**Answer:** \(\boxed{3.01\ \text{m/s},\ 56.3^\circ\text{ east of north}}\), equivalently \(33.7^\circ\) north of east.
