# Unit 2 - Newton's Laws: Exercises 4.7-4.19 Odd

Completed September 18, 2026. Assignment: p. 124, #7-19 odd (exercises 4.7, 4.9, 4.11, 4.13, 4.15, 4.17, 4.19; continues on p. 125).

Questions transcribed from user-supplied textbook screenshots, with the original graph for 4.13 retained in the PDF. Use g_Earth = 9.80 m/s². Answers generally rounded to three significant figures; intermediate calculations retain extra precision.

[Source page 124](sources/unit-2/newton-sept18/page-124.png) | [Source page 125](sources/unit-2/newton-sept18/page-125.png)

[Completed PDF](output/pdf/unit-2-newtons-laws-4-7-to-4-19-odd.pdf)

Study-guide tags: Newton's second law; friction and stopping; piecewise motion; acceleration graphs; time-dependent thrust; mass versus weight. These are assigned source questions, not invented practice.

Assignment: p. 124, #7-19 odd, continuing on p. 125. Use g = 9.80 m/s² on Earth. All seven assigned questions and their subparts are included.

## 4.7 | Friction stopping a skater

Question. A 68.5 kg skater moving initially at 2.40 m/s on rough horizontal ice comes to rest uniformly in 3.52 s due to friction from the ice. What force does friction exert on the skater?

Skater free-body diagram: friction f opposite the initial motion, normal force N upward, and weight mg downward. N = mg; friction is the net horizontal force.

1. Find acceleration. Choose the initial motion as +x:
a_x = (v_f - v_i)/Δt = (0 - 2.40)/3.52 = -0.681818 m/s².

2. Apply Newton's second law. Vertical forces cancel, so friction is the net horizontal force:
f_x = ma_x = (68.5)(-0.681818) = -46.7045 N.

Friction has magnitude 46.7 N and acts opposite the initial motion.

## 4.9 | Find the mass of a box

Question. A box rests on a frozen pond, which serves as a frictionless horizontal surface. A fisherman applies a horizontal force of magnitude 48.0 N and produces an acceleration of magnitude 2.20 m/s². What is the mass of the box?

The normal force and weight cancel vertically. With no friction, the applied horizontal force is the net horizontal force.

F_net = ma, so m = F_net/a
m = 48.0/2.20 = 21.8182 kg.

Mass of the box: m = 21.8 kg.

## 4.11 | Hockey puck in three time intervals

Question. A hockey puck with mass 0.160 kg is at rest at the origin (x = 0) on the horizontal, frictionless surface of the rink. At t = 0, a player applies a force of 0.250 N parallel to the x-axis until t = 2.00 s. (a) What are the position and speed at t = 2.00 s? (b) If the same force is again applied at t = 5.00 s, what are the position and speed at t = 7.00 s?

Choose +x in the direction of the applied force. While the force is on:
a = F/m = 0.250/0.160 = 1.5625 m/s².
From t = 2.00 s to 5.00 s, a = 0; the puck keeps its existing velocity.

(a) First push: 0 to 2.00 s
v_2 = v_0 + aΔt = 0 + (1.5625)(2.00) = 3.125 m/s.
x_2 = x_0 + v_0Δt + ½a(Δt)²
x_2 = ½(1.5625)(2.00)² = 3.125 m.

(a) Position: x = +3.13 m. Speed: 3.13 m/s.

(b) Coast first, then apply the second push.
From 2.00 to 5.00 s: Δt = 3.00 s and v = 3.125 m/s.
x_5 = 3.125 + (3.125)(3.00) = 12.500 m.

From 5.00 to 7.00 s: Δt = 2.00 s and acceleration is again 1.5625 m/s².
v_7 = 3.125 + (1.5625)(2.00) = 6.250 m/s.
x_7 = 12.500 + (3.125)(2.00) + ½(1.5625)(2.00)²
x_7 = 21.875 m.

(b) Position: x = +21.9 m. Speed: 6.25 m/s.

| Interval | Acceleration (m/s²) | End position (m) | End velocity (m/s) |
| --- | --- | --- | --- |
| 0-2 s | +1.5625 | 3.125 | +3.125 |
| 2-5 s | 0 | 12.500 | +3.125 |
| 5-7 s | +1.5625 | 21.875 | +6.250 |

Key point: Removing the force makes acceleration zero; it does not stop the puck. Keep the position and velocity continuous between intervals.

## 4.13 | Experimental cart

Question. A 4.50 kg experimental cart undergoes acceleration in a straight line (the x-axis). Fig. E4.13 shows its acceleration as a function of time. (a) Find the maximum net force on the cart and when it occurs. (b) During what times is the net force constant? (c) When is the net force zero?

Figure E4.13: the acceleration starts at 0 at t = 0, rises to +10.0 m/s² at t = 2.0 s, remains at +10.0 m/s² through t = 4.0 s, and falls to 0 at t = 6.0 s. The graph specifies no behavior outside this interval.

Because mass is constant, F_net,x(t) = ma_x(t). Read the height of the acceleration graph and multiply by 4.50 kg.

(a) Maximum net force
The highest acceleration is +10.0 m/s²:
F_max = (4.50)(10.0) = 45.0 N.

(a) 45.0 N in the +x direction, from t = 2.0 s to 4.0 s.

(b) Constant net force
The acceleration graph is horizontal from 2.0 s to 4.0 s, so the net force remains constant at +45.0 N over that interval.

(b) From t = 2.0 s to 4.0 s.

(c) Zero net force
F_net = 0 wherever a_x = 0. On the plotted interval, this occurs at the two endpoints.

(c) At t = 0 and t = 6.0 s.

The graph does not specify the force after 6.0 s. Do not infer an additional interval beyond the displayed data.

## 4.15 | Applied force versus net force

Question. A small 8.00 kg rocket burns fuel that exerts a time-varying upward force as it moves upward from the launch pad; assume constant mass. The force obeys F = A + Bt². At t = 0, F = 100.0 N; at t = 2.00 s, F = 150.0 N. (a) Find A and B, including SI units. (b) Find the net force and acceleration (i) immediately after ignition and (ii) 3.00 s after ignition. (c) Far from all gravity in outer space, what would its acceleration be 3.00 s after ignition?

(a) Determine the constants.
At t = 0: 100.0 = A + B(0)², so A = 100.0 N.
At t = 2.00 s: 150.0 = 100.0 + B(2.00)².
B = (150.0 - 100.0)/(2.00)² = 12.5 N/s².

(a) A = 100.0 N; B = 12.5 N/s².
F(t) = 100.0 N + (12.5 N/s²)t².

(b) Include gravity on Earth. The forces on the airborne rocket are upward thrust F(t) and downward weight mg. Take upward as positive:
mg = (8.00)(9.80) = 78.4 N.
F_net = F(t) - mg;   a = F_net/m.

(i) Immediately after ignition, t = 0:
F_net = 100.0 - 78.4 = 21.6 N.
a = 21.6/8.00 = 2.70 m/s².

(b)(i) Net force: 21.6 N upward. Acceleration: 2.70 m/s² upward.

(ii) At t = 3.00 s:
F(3.00) = 100.0 + 12.5(3.00)² = 212.5 N.
F_net = 212.5 - 78.4 = 134.1 N.
a = 134.1/8.00 = 16.7625 m/s².

(b)(ii) Net force: 134.1 N upward. Acceleration: 16.8 m/s² upward.

(c) Far from gravity: Weight is absent, so thrust is the net force.
a = F(3.00)/m = 212.5/8.00 = 26.5625 m/s².

(c) Acceleration: 26.6 m/s² in the direction of the thrust.

Units check: B has units N/s² so that Bt² has units of force. The given F(t) is thrust, not net force on Earth.

## 4.17 | Superman accelerates a boulder

Question. Superman throws a 2400 N boulder at an adversary. What horizontal force must he apply to give it a horizontal acceleration of 12.0 m/s²?

1. Convert weight to mass. The given 2400 N is a force, not a mass.
W = mg, so m = W/g = 2400/9.80 = 244.898 kg.

2. Apply F_x = ma_x.
F_x = (244.898)(12.0) = 2938.78 N.

Required horizontal force: 2.94 × 10^3 N, in the direction of the horizontal acceleration.

Gravity acts vertically, so it contributes no horizontal force in this calculation.

## 4.19 | Watermelon on Earth and Io

Question. At the surface of Jupiter's moon Io, the acceleration due to gravity is 1.81 m/s². A watermelon weighs 44.0 N at Earth's surface. (a) What is its mass on Earth? (b) What would its mass and weight be on Io?

(a) Mass on Earth
m = W_Earth/g_Earth = 44.0/9.80 = 4.48980 kg.

(a) Mass on Earth: 4.49 kg.

(b) Mass stays the same on Io.
m_Io = m_Earth = 4.48980 kg.
Weight changes with local gravity:
W_Io = mg_Io = (4.48980)(1.81) = 8.12653 N.

(b) Mass on Io: 4.49 kg. Weight on Io: 8.13 N downward.

Remember: Mass is measured in kilograms and stays the same when the object changes location. Weight is the gravitational force mg, measured in newtons.
