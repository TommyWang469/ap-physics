# AP Physics - Unit 2: Forces Question Bank

Started September 14, 2026; updated September 15, 2026 for a future Unit 2 study guide. Contains 11 questions: 10 worksheet questions and one user-supplied pulley problem.

- Assignment: **Intro to Forces Practice Problems**, questions 1-10.
- Source supplied by the user: `Halliday+106+1-10.pdf`. The filename suggests Halliday page 106; textbook edition and original textbook numbering have not been independently verified.
- [Archived original worksheet](sources/unit-2/halliday-106-1-10.pdf)
- [Questions with worked answers (PDF)](output/pdf/unit-2-forces-halliday-1-10-solutions.pdf)
- Provenance: the 10 `U2-H106` questions below are faithful transcriptions or close paraphrases of this worksheet, with diagram information recorded in words/tables. These are assigned homework questions, not predictions of a future test. Original diagrams remain in the archived worksheet and solution PDF. The additional pulley problem has its own source and is not part of the Halliday worksheet PDF.
- Stable IDs: `U2-H106-01` through `U2-H106-10`. Keep these IDs when reusing the questions and avoid recording duplicates.
- Additional source: [September 15 pulley sketch](sources/unit-2/2026-09-15-three-weight-pulley.png), with masses and requested angle clarified by the user in this conversation. Stable ID: `U2-PULLEY-01`.

## U2-H106-01 - Angled force at constant velocity

**Source:** worksheet page 1, question 1. **Topics:** Newton's first law; force components; equilibrium.

### Question

Forces F1 and F2 act on a box sliding at constant velocity over a frictionless floor. F1 points up and right at angle theta above the horizontal; F2 points left. Decrease theta without changing the magnitude of F1. To maintain constant velocity, should the magnitude of F2 increase, decrease, or remain unchanged?

### Answer and reasoning

**Increase F2.** Constant velocity means zero acceleration, so the horizontal forces balance:

\[F_2=F_1\cos\theta.\]

As the acute angle theta decreases, cos(theta) increases. Therefore F2 must increase.

**Study-guide takeaway:** Balance components, not the magnitudes of angled forces.

## U2-H106-02 - Position functions and constant force

**Source:** worksheet page 1, question 2. **Topics:** Newton's second law; derivatives; direction of acceleration.

### Question

At t = 0, a constant force F begins to act on a rock initially moving through deep space in the +x direction.

(a) For t > 0, which position functions are possible?

1. \(x=4t-3\)
2. \(x=-4t^2+6t-3\)
3. \(x=4t^2+6t-3\)

(b) For which function is F opposite the rock's initial motion?

### Answer and reasoning

**(a) ii and iii**, taking the force that begins to act to be nonzero, as the question implies. **(b) ii.**

| Function | Velocity dx/dt | Initial velocity | Acceleration d2x/dt2 |
|---|---|---|---|
| i | 4 | +4 | 0 |
| ii | -8t + 6 | +6 | -8 |
| iii | 8t + 6 | +6 | +8 |

Constant nonzero force gives constant nonzero acceleration, F = ma. Both ii and iii have positive initial velocity and constant nonzero acceleration. In ii the acceleration and force point in -x, opposite the initial velocity.

If a zero force were allowed, i would also describe a constant-force case; it represents unforced constant-velocity motion. The intended answer for an applied nonzero force is ii and iii.

**Study-guide takeaway:** Force direction follows the second derivative of position, not the sign of position or velocity.

## U2-H106-03 - Which force diagrams can balance?

**Source:** worksheet page 1, question 3. **Topics:** equilibrium; vector addition; Newton's first law.

### Question

Four overhead force diagrams show a block on a frictionless floor. The displayed forces have nonzero magnitudes that may be chosen appropriately:

1. F1 points up-left; F2 points right.
2. F1 points left; F2 points right.
3. F1 points up-left; F2 points right; F3 points up.
4. F1 points up-left; F2 points right; F3 points down.

In which situations can the block be (a) stationary and (b) moving at constant velocity?

### Answer and reasoning

**(a) 2 and 4. (b) 2 and 4.** Both remaining at rest and moving with constant velocity require zero net force.

In 2, choose F1 = F2. In 4, choose F2 to cancel the leftward component of F1 and F3 to cancel its upward component. In 1 and 3, upward forces have no downward force to cancel them.

An object can be instantaneously at rest with nonzero acceleration; here “stationary” means remaining at rest.

**Study-guide takeaway:** Zero net force permits any constant velocity, including zero.

## U2-H106-04 - Component addition and vector identification

**Source:** worksheet page 1, question 4. **Topics:** vector components; quadrants; F = ma.

### Question

Two horizontal forces pull a banana split over a frictionless counter:

\[\vec F_1=(3\,\mathrm N)\hat i-(4\,\mathrm N)\hat j,\qquad
\vec F_2=-(1\,\mathrm N)\hat i-(2\,\mathrm N)\hat j.\]

Without a calculator, identify the labeled vectors corresponding to (a) F1 and (b) F2; give net-force components along (c) x and (d) y; state the quadrants of (e) net force and (f) acceleration.

Diagram key: the longer arrows are 1 (up-left), 4 (up-right), 5 (down-right), 8 (down-left); the shorter arrows, closer to the y-axis, are 2 (up-left), 3 (up-right), 6 (down-right), 7 (down-left).

### Answer and reasoning

- **(a) Vector 5.** F1 points down-right with magnitude 5 N.
- **(b) Vector 7.** F2 points down-left with magnitude sqrt(5) N, smaller than F1 and closer to the y-axis.
- **(c) +2 N.** Fx = 3 - 1 = 2 N.
- **(d) -6 N.** Fy = -4 - 2 = -6 N.
- **(e) Quadrant IV.** Net force points right and down.
- **(f) Quadrant IV.** Acceleration has the same direction as net force because mass is positive.

**Study-guide takeaway:** Add x and y components separately; the resultant force determines acceleration.

## U2-H106-05 - Acceleration components from force diagrams

**Source:** worksheet page 1, question 5. **Topics:** net force; multiple collinear forces; acceleration direction.

### Question

Four overhead diagrams show forces on an object on a frictionless floor. All values below are in newtons:

| Situation | Rightward forces | Leftward forces | Upward forces | Downward forces |
|---|---|---|---|---|
| 1 | 5 | 3, 2 | 7 | 4 |
| 2 | 3 | 2 | 6 | 2, 4 |
| 3 | 5 | 4 | 6 | 3, 4 |
| 4 | 3 | 5 | 2, 3 | 4, 5 |

In which situations does acceleration have (a) a nonzero x component and (b) a nonzero y component? (c) Give each acceleration's quadrant or axis direction.

### Answer and reasoning

| Situation | Net Fx (N) | Net Fy (N) | Acceleration direction |
|---|---|---|---|
| 1 | 5 - 3 - 2 = 0 | 7 - 4 = +3 | +y axis |
| 2 | 3 - 2 = +1 | 6 - 2 - 4 = 0 | +x axis |
| 3 | 5 - 4 = +1 | 6 - 3 - 4 = -1 | Quadrant IV |
| 4 | 3 - 5 = -2 | 2 + 3 - 4 - 5 = -4 | Quadrant III |

**(a) 2, 3, 4. (b) 1, 3, 4. (c) +y, +x, IV, III**, respectively.

**Study-guide takeaway:** A visible force along an axis does not guarantee acceleration along that axis; opposing components may cancel.

## U2-H106-06 - Match velocity graphs to net forces

**Source:** worksheet page 2, question 6; uses question 5. **Topics:** velocity-time graph slopes; acceleration components.

### Question

Match each situation in question 5 to one vx(t) graph and one vy(t) graph. The graphs are not to scale:

- vx graph a: horizontal line above zero; b: positive slope starting above zero; c: negative slope starting below zero.
- vy graph d: horizontal line below zero; e: positive slope starting above zero; f: negative slope starting below zero.

### Answer and reasoning

| Situation from Q5 | Sign of ax | Sign of ay | vx graph | vy graph |
|---|---|---|---|---|
| 1 | 0 | + | a | e |
| 2 | + | 0 | b | d |
| 3 | + | - | b | f |
| 4 | - | - | c | f |

Use \(a_x=dv_x/dt=F_{\mathrm{net},x}/m\) and \(a_y=dv_y/dt=F_{\mathrm{net},y}/m\). Zero force component means a horizontal velocity graph; positive/negative force components mean positive/negative slopes. Initial velocities are not specified by Q5, so the force diagrams determine slopes, not intercepts.

**Study-guide takeaway:** Match force to the slope of a velocity graph, not its height.

## U2-H106-07 - Connected blocks and tension

**Source:** worksheet page 2, question 7. **Topics:** systems; Newton's second law; tension; shared acceleration.

### Question

Four blocks are connected in a line on a frictionless floor. From left to right:

`10 kg -- cord 1 -- 3 kg -- cord 2 -- 5 kg -- cord 3 -- 2 kg --> F`

An external force F pulls the rightmost block to the right. What total mass is accelerated to the right by (a) F, (b) cord 3, and (c) cord 1? (d) Rank the block accelerations; (e) rank cord tensions, greatest first.

### Answer and reasoning

Using taut, massless, inextensible cords:

- **(a) 20 kg:** all four blocks.
- **(b) 18 kg:** the 10 kg, 3 kg, and 5 kg blocks to the left of cord 3.
- **(c) 10 kg:** the leftmost block.
- **(d) All equal:** a10 = a3 = a5 = a2 = F/(20 kg).
- **(e) T3 > T2 > T1.**

For the group to the left of each cord, its tension is the net external horizontal force:

\[T_1=(10\,\mathrm{kg})a=\tfrac12F,\quad
T_2=(13\,\mathrm{kg})a=\tfrac{13}{20}F,\quad
T_3=(18\,\mathrm{kg})a=\tfrac9{10}F.\]

**Study-guide takeaway:** Same acceleration does not mean same tension; each cord pulls a different total mass.

## U2-H106-08 - Rank acceleration magnitudes

**Source:** worksheet page 2, question 8. **Topics:** net force magnitude; signed addition; F = ma.

### Question

The same object experiences four sets of horizontal forces. Rank acceleration magnitudes, greatest first.

| Situation | Leftward forces | Rightward forces |
|---|---|---|
| a | 3 N | 6 N |
| b | 58 N | 60 N |
| c | 13 N | 15 N |
| d | 43 N | 25 N and 20 N |

### Answer and reasoning

Taking right as positive, the net forces are:

\[F_a=6-3=3\,\mathrm N,\quad F_b=60-58=2\,\mathrm N,\]
\[F_c=15-13=2\,\mathrm N,\quad F_d=25+20-43=2\,\mathrm N.\]

The mass is the same, so acceleration magnitude is proportional to net-force magnitude.

**Answer: a > b = c = d.**

**Study-guide takeaway:** Compare net force, not the largest individual force or the sum of magnitudes.

## U2-H106-09 - Normal force with an applied vertical force

**Source:** worksheet page 2, question 9. **Topics:** normal force; contact; vertical equilibrium.

### Question

A vertical force F is applied to a block of mass m on the floor. As the magnitude F increases from zero, what happens to the floor's normal force if F points (a) downward and (b) upward?

### Answer and reasoning

**(a) It increases: N = mg + F.** While the block stays on the floor, vertical acceleration is zero: N - mg - F = 0.

**(b) It decreases to zero: N = mg - F for 0 <= F <= mg.** Here N + F - mg = 0. At F = mg, the normal force is zero. For F > mg, the block lifts off and N remains zero; the floor cannot pull downward on it.

\[N_{\text{upward pull}}=\max(mg-F,0).\]

**Study-guide takeaway:** The normal force is not always mg and cannot become negative for ordinary nonadhesive contact.

## U2-H106-10 - Normal force on a 30-degree incline

**Source:** worksheet page 2, question 10. **Topics:** inclined planes; perpendicular force components; normal force.

### Question

The plane rises to the right at 30 degrees above horizontal. The same force magnitude F is applied in one of four directions: a left, b up, c right, d down. In cases a and b the force is not large enough to lift the block from the plane. Rank the normal-force magnitudes, greatest first.

### Answer and reasoning

**Answer: d > c > a > b** for F > 0.

Take positive perpendicular to the plane and away from its surface. The weight component into the plane is mg cos(30 degrees). Applied-force components into the plane increase N; components away from it decrease N:

\[N_a=mg\cos30^\circ-F\sin30^\circ
=\tfrac{\sqrt3}{2}mg-\tfrac12F,\]
\[N_b=mg\cos30^\circ-F\cos30^\circ
=\tfrac{\sqrt3}{2}mg-\tfrac{\sqrt3}{2}F,\]
\[N_c=mg\cos30^\circ+F\sin30^\circ
=\tfrac{\sqrt3}{2}mg+\tfrac12F,\]
\[N_d=mg\cos30^\circ+F\cos30^\circ
=\tfrac{\sqrt3}{2}mg+\tfrac{\sqrt3}{2}F.\]

Since cos(30 degrees) > sin(30 degrees), down increases N most and up decreases N most. At F = 0 all four cases tie.

**Study-guide takeaway:** Resolve forces perpendicular to the incline; the normal force is perpendicular to the surface, not necessarily vertical.

## U2-PULLEY-01 - Angle between strings supporting a 200 g mass

**Recorded:** September 15, 2026. **Source:** user-supplied handwritten screenshot and subsequent verbal clarification; [archived original sketch](sources/unit-2/2026-09-15-three-weight-pulley.png). **Topics:** static equilibrium; ideal pulleys; tension; force components; angles between vectors; graphing-calculator intersections.

### Question

A 200 g mass is supported at a central junction by two strings. The left string runs up-left over a pulley to a hanging 105 g mass. The right string runs up-right over another pulley to a hanging 145 g mass. Find theta, the angle between the two upward-running strings at the central junction supporting the 200 g mass.

Use the standard ideal model: the system is at rest, the strings are massless, and the pulleys are frictionless. The handwritten work uses gravitational acceleration g = 10 m/s².

### Answer and reasoning

**Answer: theta = 74.9 degrees.** This is the angle between the strings, not either string's angle from the horizontal.

The stationary hanging masses set the tensions:

\[
T_L=(0.105)(10)=1.05\,\mathrm N,\qquad
T_R=(0.145)(10)=1.45\,\mathrm N,\qquad
W=(0.200)(10)=2.00\,\mathrm N.
\]

Let x be the left string's angle above the leftward horizontal and y the right string's angle above the rightward horizontal. At the central junction:

\[
\text{Horizontal:}\quad 1.05\cos x=1.45\cos y,
\]
\[
\text{Vertical:}\quad 1.05\sin x+1.45\sin y=2.00.
\]

Solving gives x = 45.5847 degrees and y = 59.5497 degrees. Since the straight angle above the horizontal consists of x, theta, and y:

\[
\theta=180^\circ-x-y
=180^\circ-45.5847^\circ-59.5497^\circ
=\boxed{74.8656^\circ\approx74.9^\circ}.
\]

### Graphing-calculator method

1. Set the calculator to **DEGREE** mode.
2. Solve each force-balance equation for y and enter these two functions. `acos` and `asin` mean inverse cosine and inverse sine, not reciprocals:

   ```text
   Y1 = acos(1.05*cos(X)/1.45)
   Y2 = asin((2 - 1.05*sin(X))/1.45)
   ```

3. Set the graph window to X from 0 to 90 and Y from 0 to 90. Graph both functions. Y2 is only real where its inverse-sine input is between -1 and 1; a missing segment outside that domain is normal.
4. Use **Intersect** on the visible curves. The intersection is approximately **(45.5847, 59.5497)**, giving the two string angles from the horizontal.
5. Compute **180 - X - Y** using the intersection coordinates to get **theta = 74.9 degrees**.

The acute inverse-trig branches match this sketch, where both strings rise from the central junction toward the pulleys.

### Direct check using the angle between force vectors

The two tension vectors sum to an upward force of magnitude W, so:

\[
W^2=T_L^2+T_R^2+2T_LT_R\cos\theta.
\]

All three forces contain the same factor g, which cancels. Using masses in the same units:

\[
\theta=\cos^{-1}\left(\frac{200^2-105^2-145^2}{2(105)(145)}\right)
=74.8656^\circ.
\]

**Angle caution:** The x + y angle is 105.1344 degrees; subtract it from 180 degrees to obtain theta. Equivalently, the interior angle opposite W in a head-to-tail force triangle is 105.1344 degrees and needs the same supplement. The direct vector-sum formula above already gives theta = 74.8656 degrees, so do not subtract that result from 180 degrees again.

**Study-guide takeaways:** Use cosine horizontally and sine vertically when angles are measured from the horizontal. Tension and weight are forces measured in newtons, not kilograms. Clearly distinguish the angle between the strings from the two component angles and the supplementary force-triangle angle.

## Future Unit 2 study-guide index

| Concept | Question IDs |
|---|---|
| Zero net force and constant velocity | U2-H106-01, U2-H106-03 |
| Force, acceleration, and derivatives | U2-H106-02, U2-H106-06 |
| Force components, vector sums, and quadrants | U2-H106-04, U2-H106-05, U2-H106-08 |
| Connected systems and tension | U2-H106-07, U2-PULLEY-01 |
| Pulley equilibrium and the angle between strings | U2-PULLEY-01 |
| Graphing-calculator intersections for force equations | U2-PULLEY-01 |
| Normal force and loss of contact | U2-H106-09, U2-H106-10 |

When building the study guide, use this source-backed bank, retain the original question numbers and diagrams, and distinguish any newly created variations from the homework.
