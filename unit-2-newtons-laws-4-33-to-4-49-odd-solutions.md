# Unit 2 - Newton’s Laws: Problems 4.33-4.49 Odd

Recorded September 22, 2026. All nine assigned odd-numbered problems and all subparts. Use g = 9.80 m/s².

[Questions and worked answers (PDF)](output/pdf/unit-2-newtons-laws-4-33-to-4-49-odd.pdf)

Questions are transcribed or closely paraphrased from the three supplied screenshots. Original figures remain in the archived sources; their numerical information and force-diagram descriptions are recorded below. These are source homework questions, not predictions of a future test. Textbook title and edition are unverified.

## 4.33 | Bucket and breaking strength

**Question ID:** U2-NL-4-33
**Topics:** tension; maximum acceleration; kinematics.
**Source:** problems-4-33-4-35.png in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

A 5.60 kg bucket of water is accelerated upward by a cord of negligible mass whose breaking strength is 75.0 N. If the bucket starts from rest, what is the minimum time required to raise the bucket a vertical distance of 12.0 m without breaking the cord?

### Worked solution

**Forces and maximum acceleration.**
Take upward as positive. The cord pulls upward with tension T, and gravity pulls downward with weight mg. The fastest rise uses the largest allowed tension throughout: T = 75.0 N.


T − mg = ma

a_max = (75.0 − 5.60 × 9.80)/5.60 = 3.59286 m/s².

**Time from rest.**
Δy = ½at², so t_min = √(2Δy/a_max)

= √(2 × 12.0/3.59286) = 2.58455 s.

**Answer.**
**t_min = 2.58 s.** This is the first time the bucket reaches 12.0 m; the question does not require it to be at rest at that height.

## 4.35 | Smallest push on a cart

**Question ID:** U2-NL-4-35
**Topics:** force components; vector cancellation; weight.
**Source:** problems-4-33-4-35.png + page-126.png (Fig. P4.35) in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

Two adults and a child want to push a wheeled cart in the direction marked x in Fig. P4.35. The two adults push with horizontal forces F₁ and F₂ as shown. (a) Find the magnitude and direction of the smallest force that the child should exert. Ignore friction. (b) If the child exerts that minimum force, the cart accelerates at 2.0 m/s² in the +x-direction. What is the weight of the cart?

Figure P4.35: top view. F₁ = 100 N at 60° above +x; F₂ = 140 N at 30° below +x. Both forces lie in the horizontal plane.

### Worked solution

**(a) Cancel the sideways component.**
F_adults,y = 100 sin 60° − 140 sin 30° = +16.6025 N.

Thus F_child,y = −16.6025 N. Since |F_child| = √(F_child,x² + F_child,y²), its magnitude is smallest when F_child,x = 0.

**Answer (a).**
**16.6 N in the −y-direction, perpendicular to +x** (downward on the top-view diagram, not toward the ground).

**(b) Find mass, then weight.**
F_net,x = 100 cos 60° + 140 cos 30° = 171.244 N.

m = F_net,x/a = 171.244/2.0 = 85.6218 kg.

W = mg = 85.6218 × 9.80 = 839.093 N.

**Answer (b).**
**W ≈ 8.4 × 10² N.** Weight is a force, so the answer is in newtons.

## 4.37 | Two crates connected by a rope

**Question ID:** U2-NL-4-37
**Topics:** free-body diagrams; tension; connected systems.
**Source:** page-126.png (Fig. P4.37) in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

Two crates, one of mass 4.00 kg and the other of mass 6.00 kg, sit on the frictionless surface of a frozen pond, connected by a light rope (Fig. P4.37). A woman wearing golf shoes for traction pulls horizontally on the 6.00 kg crate with a force F that gives it an acceleration of 2.50 m/s². (a) What is the acceleration of the 4.00 kg crate? (b) Draw its free-body diagram and use Newton’s second law to find the connecting-rope tension T. (c) Draw the free-body diagram for the 6.00 kg crate. What is the direction of its net force? Which is larger, T or F? (d) Use part (c) and Newton’s second law to calculate F.

Figure P4.37: 4.00 kg crate on the left, rope, 6.00 kg crate on the right; the woman pulls the 6.00 kg crate to the right.

**Free-body diagrams:** 4.00 kg crate: normal force from ice up, weight from Earth down, tension from rope right. 6.00 kg crate: normal force from ice up, weight from Earth down, tension from rope left, applied force from woman right. No friction acts on either crate.

### Worked solution

**(a) Shared acceleration.**
The taut, nonstretching rope keeps their separation fixed. **Both crates accelerate at 2.50 m/s² to the right.**

**(b) Isolate the 4.00 kg crate.**
Vertical forces balance: N₄ = 4.00g = 39.2 N. Horizontally, T = m₄a = 4.00 × 2.50.

**T = 10.0 N.**

**(c) Isolate the 6.00 kg crate.**
Vertical forces balance: N₆ = 6.00g = 58.8 N. Horizontally, F − T = m₆a > 0.

**The net force points right, and F > T.**

**(d) Applied force.**
F = T + m₆a = 10.0 + 6.00 × 2.50 = **25.0 N to the right.**

Check using both crates: F = (4.00 + 6.00) × 2.50 = 25.0 N.

## 4.39 | Test gun with a changing acceleration

**Question ID:** U2-NL-4-39
**Topics:** derivatives; position; velocity; net force.
**Source:** page-126.png in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

To study damage to aircraft that collide with large birds, you design a test gun that accelerates chicken-sized objects so that their displacement along the barrel is x(t) = (9.0 × 10³ m/s²)t² − (8.0 × 10⁴ m/s³)t³. The object leaves the end of the barrel at t = 0.025 s. (a) How long must the barrel be? (b) What is the speed as the object leaves? (c) What net force must be exerted on a 1.50 kg object at (i) t = 0 and (ii) t = 0.025 s?

### Worked solution

**(a) Barrel length.**
x(0.025) = 9000(0.025)² − 80000(0.025)³

= 5.625 − 1.250 = 4.375 m. **Length ≈ 4.4 m.**

**(b) Differentiate once.**
v(t) = dx/dt = (1.8 × 10⁴ m/s²)t − (2.4 × 10⁵ m/s³)t².

v(0.025) = 450 − 150 = **3.0 × 10² m/s.**

**(c) Differentiate again and apply F_net = ma.**
a(t) = (1.8 × 10⁴ m/s²) − (4.8 × 10⁵ m/s³)t.

(i) F_net(0) = 1.50 × 18000 = **2.7 × 10⁴ N.**

(ii) a(0.025) = 18000 − 12000 = 6000 m/s²,

so F_net(0.025) = 1.50 × 6000 = **9.0 × 10³ N.**

Both net forces point along +x, toward the barrel’s exit.

## 4.41 | Elevator scale readings

**Question ID:** U2-NL-4-41
**Topics:** apparent weight; normal force; vertical acceleration.
**Source:** page-126.png in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

After an annual checkup, you leave your physician’s office, where you weighed 683 N. You then get into an elevator that conveniently has a scale. Find the magnitude and direction of the elevator’s acceleration if the scale reads (a) 725 N and (b) 595 N.

### Worked solution

**A scale measures the normal force.**
Your mass is m = W/g = 683/9.80 = 69.6939 kg. Take upward as positive. The scale pushes upward with normal force N, while your weight W acts downward.

N − W = ma, so a = (N − W)/m.

**(a) Reading 725 N.**
a = (725 − 683)/69.6939 = +0.602635 m/s².

**Acceleration: 0.603 m/s² upward.**

**(b) Reading 595 N.**
a = (595 − 683)/69.6939 = −1.26266 m/s².

**Acceleration: 1.26 m/s² downward.**

**Interpretation.**
A reading above your true weight means upward acceleration; a reading below it means downward acceleration. The readings alone do not tell whether the elevator is moving up or down.

## 4.43 | Bat reverses a baseball’s velocity

**Question ID:** U2-NL-4-43
**Topics:** average force; velocity change; impulse.
**Source:** page-126.png in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

A batter swings at a baseball of mass 0.145 kg moving horizontally toward him at 40.0 m/s. He hits a line drive, with the ball moving away from him horizontally at 50.0 m/s just after it leaves the bat. If the bat and ball are in contact for 8.00 ms, what is the average force that the bat applies to the ball?

### Worked solution

**Choose the outgoing direction as positive.**
vᵢ = −40.0 m/s, v_f = +50.0 m/s.

Δv = v_f − vᵢ = 50.0 − (−40.0) = 90.0 m/s.

Δt = 8.00 ms = 8.00 × 10⁻³ s.

**Average horizontal force.**
F_avg,x = mΔv/Δt

= (0.145 × 90.0)/(8.00 × 10⁻³) = 1631.25 N.

**Answer.**
**1.63 × 10³ N away from the batter** (in the outgoing horizontal direction, to the stated precision).

**Why the speeds add.**
The ball reverses direction, so its velocity changes by 90.0 m/s, not 10.0 m/s. The average force is determined by the total velocity change; the force need not be constant.

**Gravity detail.**
If the initial and final velocities are exactly horizontal, the bat also supplies an average upward component mg = 1.42 N to cancel gravity’s vertical impulse. This changes neither the rounded magnitude nor the nearly horizontal direction above.

## 4.45 | Two descending boxes pulled upward

**Question ID:** U2-NL-4-45
**Topics:** vertical tension; kinematics; unknown masses.
**Source:** page-126.png (Fig. P4.45) in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

Boxes A and B are connected to each end of a light vertical rope (Fig. P4.45). A constant upward force F = 80.0 N is applied to box A. Starting from rest, box B descends 12.0 m in 4.00 s. The tension in the rope connecting the two boxes is 36.0 N. What are the masses of (a) box B and (b) box A?

Figure P4.45: box A above box B, joined by a vertical rope; the external 80.0 N force acts upward on A.

### Worked solution

**Get the acceleration from the motion.**
Choose downward as positive. Both boxes have the same constant acceleration.

12.0 = ½a(4.00)², so a = **1.50 m/s² downward.**

**(a) Lower box B.**
Forces: m_Bg down and T up.

m_Bg − T = m_Ba → m_B = T/(g − a).

m_B = 36.0/(9.80 − 1.50) = **4.34 kg.**

**(b) Upper box A.**
Forces: m_Ag and T down; F up.

m_Ag + T − F = m_Aa → m_A = (F − T)/(g − a).

m_A = (80.0 − 36.0)/(9.80 − 1.50) = **5.30 kg.**

**System check.**
(m_A + m_B)(g − a) = 80.0 N. The internal tension cancels when both boxes are treated as one system.

## 4.47 | Rocket makes a soft landing

**Question ID:** U2-NL-4-47
**Topics:** kinematics; thrust versus net force; signs.
**Source:** page-126.png in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

A small rocket of mass 20.0 kg is in free fall toward Earth. Air resistance is negligible. At 80.0 m above the surface, it is moving downward at 30.0 m/s. Its engines then produce a constant upward force F. Neglect the change in mass. What value of F makes its speed zero just as it reaches Earth’s surface, for a soft landing? Hint: the net force combines the upward engine force and the downward weight.

### Worked solution

**Find the required acceleration.**
Choose upward as positive: vᵢ = −30.0 m/s, v_f = 0, Δy = −80.0 m.

v_f² = vᵢ² + 2aΔy → 0 = 900 − 160a.

a = +5.625 m/s² (upward).

**Include gravity when finding thrust.**
F − mg = ma → F = m(g + a).

F = 20.0(9.80 + 5.625) = 308.5 N.

**Answer.**
**F = 309 N upward.** The upward net force is only ma = 112.5 N; the engines must also overcome the 196 N weight.

**Check.**
t = (0 − (−30.0))/5.625 = 5.33 s, and Δy = ½(vᵢ + v_f)t = −80.0 m. Upward acceleration slows the downward motion to rest at the surface.

## 4.49 | Rocket force increases with time

**Question ID:** U2-NL-4-49
**Topics:** variable force; integration; initial conditions.
**Source:** problem-4-49.png in [archived screenshots](sources/unit-2/newton-2026-09-22/).

### Question

A mysterious rocket-propelled object of mass 45.0 kg is initially at rest in the middle of the horizontal, frictionless surface of an ice-covered lake. A force directed east with magnitude F(t) = (16.8 N/s)t is applied. How far does the object travel in the first 5.00 s after the force is applied?

### Worked solution

**Acceleration is not constant.**
Choose east as positive and set x(0) = 0. Vertically, the surface’s normal force balances the weight. The applied force is the net horizontal force.

a(t) = F(t)/m = [(16.8 N/s)/(45.0 kg)]t = (0.373333 m/s³)t.

**Integrate to get velocity.**
Using v(0) = 0:

v(t) = ∫₀ᵗ a(τ) dτ = (16.8/(2 × 45.0))t²

= (0.186667 m/s³)t².

**Integrate again to get displacement.**
Using x(0) = 0:

x(t) = ∫₀ᵗ v(τ) dτ = (16.8/(6 × 45.0))t³.

x(5.00) = (16.8 × 5.00³)/(6 × 45.0) = 7.77778 m.

**Answer.**
**7.78 m east.** The velocity stays nonnegative, so distance traveled equals the magnitude of displacement.

**Common trap.**
Do not use the final acceleration in x = ½at²: that formula requires constant acceleration, but here a grows linearly with time.
