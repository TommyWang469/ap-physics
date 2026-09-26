# Newton’s Laws Practice Problems 1–20: Worked Solutions

Source: the four user-supplied screenshots dated September 26, 2026, at 4.02.40 PM (1–5), 4.02.31 PM (6–10), 4.02.24 PM (11–15), and 4.02.17 PM (16–20). Questions below are faithful restatements; handwritten calculations were independently checked.

Use g = 9.8 m/s², ideal cords and pulleys, and negligible table friction for Questions 9, 11, and 17. Most final answers show three significant figures.

## 1. Four suspended spheres

Spheres A, B, C, and D hang in a vertical line, from top to bottom. The top cord passes over a frictionless pulley and pulls on the wall with 98 N. The shorter cords have tensions T₁ = 58.8 N, T₂ = 49.0 N, and T₃ = 9.8 N. Find each mass.

1. **Set up the forces.** The spheres are at rest, so each has zero net force. An upper cord pulls a sphere upward; a lower cord pulls it downward. The tension in the top cord is 98 N.

2. **Start at the bottom.** D: T₃ − m_Dg = 0, so m_D = 9.8/9.8 = 1.00 kg.

3. **Work upward.** C: T₂ − T₃ − m_Cg = 0 → m_C = (49.0 − 9.8)/9.8 = 4.00 kg.
B: T₁ − T₂ − m_Bg = 0 → m_B = (58.8 − 49.0)/9.8 = 1.00 kg.
A: 98 − T₁ − m_Ag = 0 → m_A = (98 − 58.8)/9.8 = 4.00 kg.

**Answer:** m_A = 4.00 kg; m_B = 1.00 kg; m_C = 4.00 kg; m_D = 1.00 kg.

**Check / concept:** Each cord supports the total weight below it. Check: the total mass is 10.0 kg, whose weight is 98 N.

## 2. Block held on a frictionless incline

An 8.5 kg block rests on a frictionless 30° incline, held by a cord parallel to the incline. (a) Find the tension and normal force. (b) Find its acceleration immediately after the cord is cut.

1. **Resolve the weight.** Choose axes parallel and perpendicular to the ramp. Gravity contributes mg sin θ down the ramp and mg cos θ into the ramp.

2. **(a) Use equilibrium.** Parallel: T − mg sin θ = 0 → T = (8.5)(9.8) sin 30° = 41.65 N.
Perpendicular: N − mg cos θ = 0 → N = (8.5)(9.8) cos 30° = 72.14 N.

3. **(b) Remove the tension.** Once cut, only the weight component acts along the ramp: mg sin θ = ma.
a = g sin 30° = (9.8)(0.500) = 4.90 m/s², down the ramp.

**Answer:** (a) T = 41.7 N; N = 72.1 N. (b) a = 4.90 m/s² down the incline.

**Check / concept:** On a frictionless incline, the normal force cancels only the perpendicular component of gravity.

## 3. Horizontal push up a ramp

A 100 kg crate moves at constant speed up a frictionless 30.0° ramp under a horizontal applied force F. Find F and the ramp’s normal force.

1. **Identify components.** Constant speed along the straight ramp means a = 0. The horizontal push has component F cos θ up the ramp and F sin θ into the ramp.

2. **Balance forces along the ramp.** F cos θ − mg sin θ = 0 → F = mg tan θ.
F = (100)(9.8) tan 30.0° = 565.80 N.

3. **Balance perpendicular forces.** N − mg cos θ − F sin θ = 0.
N = (100)(9.8) cos 30.0° + (565.80) sin 30.0°
N = 848.70 + 282.90 = 1131.61 N.

**Answer:** F = 566 N; N = 1.13 × 10³ N.

**Check / concept:** The horizontal push presses the crate into the ramp, so N is larger than mg cos θ.

## 4. Five accelerating chain links

Five links, each of mass 0.100 kg, accelerate upward at 2.50 m/s². Links are numbered 1 at the bottom through 5 at the top. Find the forces between adjacent links, the applied force, and the net force on each link.

1. **Choose a subsystem.** For the bottom n links, the upward contact force S_n supports their weight and accelerates them: S_n − nmg = nma.
Thus S_n = nm(g + a) = n(0.100)(9.8 + 2.50) = 1.23n N.

2. **Evaluate all four contacts.** Between links 1 and 2: 1.23 N. Between links 2 and 3: 2.46 N.
Between links 3 and 4: 3.69 N. Between links 4 and 5: 4.92 N.
At each contact, the upper link pulls up on the lower one; the lower link pulls down on the upper one with equal magnitude.

3. **Find the applied and net forces.** For all five links: F = 5m(g + a) = 6.15 N upward.
For each individual link: F_net = ma = (0.100)(2.50) = 0.250 N upward.

**Answer:** Contact forces, bottom to top: 1.23, 2.46, 3.69, 4.92 N. Applied force: 6.15 N. Net force on every link: 0.250 N upward.

**Check / concept:** The lifting force must both balance gravity and produce the upward acceleration; it is not just ma.

## 5. Box in connected elevator cabs

Cab A (1700 kg) sits above cab B (1300 kg), joined by a cable of tension 1.91 × 10⁴ N. A 12.0 kg box rests on A’s floor. Find the normal force on the box.

1. **Use the lower cab to find acceleration.** Take upward as positive. Cab B has cable tension upward and weight downward:
T − m_Bg = m_Ba.

2. **Calculate the shared acceleration.** a = (19100 − 1300 × 9.8)/1300 = 4.8923 m/s² upward.
The taut connecting cable makes both cabs share this acceleration.

3. **Apply Newton’s second law to the box.** N − m_boxg = m_boxa.
N = 12.0(9.8 + 4.8923) = 176.31 N.

**Answer:** N = 176 N upward on the box.

**Check / concept:** Cab A’s mass is unnecessary here: the lower cab already determines the common acceleration.

## 6. Angled pull and the lift-off threshold

A 5.00 kg block is pulled across a frictionless horizontal floor by a force of 12.0 N at 25.0° above horizontal. (a) Find its acceleration. (b) Find F just before lift-off as F increases. (c) Find the acceleration at that threshold.

1. **(a) Use the horizontal component.** While the floor supports the block, a_y = 0 and F cos θ = ma_x.
a = (12.0 cos 25.0°)/5.00 = 2.1751 m/s².
Check contact: N = mg − F sin θ = 43.93 N, which is positive.

2. **(b) Set the normal force to zero.** The floor cannot pull downward. At impending lift-off, N = 0:
F sin θ = mg → F = (5.00)(9.8)/sin 25.0° = 115.94 N.

3. **(c) Recalculate the horizontal acceleration.** At the threshold the vertical forces still balance.
a = F cos θ/m = g cot θ = 9.8/tan 25.0° = 21.016 m/s².

**Answer:** (a) a = 2.18 m/s². (b) F = 116 N. (c) a = 21.0 m/s², horizontal.

**Check / concept:** Use the increased force from part (b) in part (c), not the original 12.0 N.

## 7. Four penguins pulled across ice

Four penguins are arranged left to right as 1, 2, 3, 4 on frictionless ice. Given m₁ = 12 kg, m₃ = 15 kg, m₄ = 20 kg, T₂ = 111 N between penguins 2 and 3, and T₄ = 222 N in the pulling cord, find m₂.

1. **Choose the right-hand pair.** For penguins 3 and 4 together, T₄ acts right and T₂ acts left. Internal forces between these two penguins cancel.
T₄ − T₂ = (m₃ + m₄)a.

2. **Find their common acceleration.** a = (222 − 111)/(15 + 20) = 111/35 = 3.1714 m/s².

3. **Use the left-hand pair.** T₂ accelerates penguins 1 and 2: T₂ = (m₁ + m₂)a.
m₂ = T₂/a − m₁ = 111/(111/35) − 12 = 23 kg.

**Answer:** m₂ = 23 kg.

**Check / concept:** Check the whole system: 222/(12 + 23 + 15 + 20) = 3.1714 m/s².

## 8. Three connected blocks on a table

Blocks m₁ = 12.0 kg, m₂ = 24.0 kg, and m₃ = 31.0 kg lie left to right on a frictionless table. The rightmost cord pulls with T₃ = 65.0 N. Find the acceleration and tensions T₁ and T₂ between the blocks.

1. **Treat all blocks as one system.** Internal cord tensions cancel. Total mass M = 12.0 + 24.0 + 31.0 = 67.0 kg.
a = T₃/M = 65.0/67.0 = 0.97015 m/s² to the right.

2. **Isolate the leftmost block.** T₁ is the only horizontal force on m₁:
T₁ = m₁a = (12.0)(65.0/67.0) = 11.6418 N.

3. **Isolate the first two blocks together.** T₂ pulls the combined mass m₁ + m₂:
T₂ = (m₁ + m₂)a = (36.0)(65.0/67.0) = 34.9254 N.

**Answer:** a = 0.970 m/s² right; T₁ = 11.6 N; T₂ = 34.9 N.

**Check / concept:** A cord farther toward the pulling end must accelerate more mass, so its tension is larger.

## 9. Two arrangements of contacting blocks

The same horizontal force F_a first pushes block A against B with a 20.0 N contact force. When F_a pushes B against A, A pushes back on B with 10.0 N. Their total mass is 12 kg. Find the acceleration in each case and F_a. Assume negligible table friction.

1. **Compare the two systems.** The same external force acts on the same total mass, so both arrangements have the same acceleration magnitude a.

2. **Use the block without the applied force.** First arrangement: B is accelerated by the 20.0 N contact force, so m_Ba = 20.0.
Second arrangement: B pushes A rightward with 10.0 N by Newton’s third law, so m_Aa = 10.0.

3. **Add and solve.** (m_A + m_B)a = 20.0 + 10.0 = 30.0 N.
a = 30.0/12 = 2.50 m/s² in each arrangement.
F_a = (12)(2.50) = 30.0 N.

**Answer:** Both accelerations: 2.50 m/s² right. Applied force: F_a = 30.0 N.

**Check / concept:** The contact forces differ because the block being accelerated by contact alone differs. The implied masses are mA = 4.00 kg and mB = 8.00 kg.

## 10. Push the large block or the small block

Two contacting blocks of masses m₁ = 30.0 kg and m₂ = 1.2 kg rest on a frictionless table. A 3.2 N horizontal push acts on the larger block. Find the contact force, then find it when the same force pushes the smaller block into the larger block.

1. **Find the common acceleration.** In either arrangement, a = F/(m₁ + m₂) = 3.2/31.2 = 0.10256 m/s².

2. **Push on the large block.** The contact force alone accelerates the small block:
C = m₂a = (1.2)(3.2/31.2) = 0.12308 N.

3. **Push on the small block.** Now the contact force alone accelerates the large block:
C = m₁a = (30.0)(3.2/31.2) = 3.0769 N.

**Answer:** Push on large block: C = 0.123 N. Push on small block: C = 3.08 N.

**Check / concept:** The second result assumes the push keeps the blocks together (reverse the push or swap positions). A rightward push on the small block in the original drawing would separate them, giving C = 0.

## 11. A table block with two hanging boxes

Box A (30.0 kg) lies on a horizontal table. A cord runs from A over a frictionless pulley to hanging box B (40.0 kg); a second cord connects B to C (10.0 kg) below it. Released from rest for 0.250 s, find both tensions and the distance traveled. Assume negligible table friction.

1. **Write equations along each motion.** A moves right; B and C move down. Let T be the A-B cord tension and S the B-C cord tension.
A: T = m_Aa.
B: m_Bg + S − T = m_Ba. C: m_Cg − S = m_Ca.

2. **Add to eliminate both tensions.** (m_B + m_C)g = (m_A + m_B + m_C)a.
a = (50.0)(9.8)/80.0 = 6.125 m/s².

3. **Substitute and use kinematics.** T = (30.0)(6.125) = 183.75 N.
S = m_C(g − a) = (10.0)(9.8 − 6.125) = 36.75 N.
d = ½at² = ½(6.125)(0.250)² = 0.191406 m.

**Answer:** T_AB = 184 N; T_BC = 36.8 N; each box travels 0.191 m.

**Check / concept:** For box B, the lower cord pulls downward. Do not assign the same tension to two different cords.

## 12. Atwood’s machine

Two hanging blocks of masses m₁ = 1.30 kg and m₂ = 2.80 kg are joined by a massless cord over a frictionless pulley. Find the acceleration magnitude and cord tension.

1. **Choose positive along the motion.** The heavier m₂ moves down while m₁ moves up. They share the same acceleration magnitude and the same cord tension.
m₁: T − m₁g = m₁a. m₂: m₂g − T = m₂a.

2. **Add the equations.** (m₂ − m₁)g = (m₁ + m₂)a.
a = [(2.80 − 1.30)(9.8)]/(1.30 + 2.80) = 3.58537 m/s².

3. **Solve for the tension.** T = m₁(g + a) = (1.30)(9.8 + 3.58537) = 17.40098 N.
Check with m₂: T = m₂(g − a), giving the same value.

**Answer:** a = 3.59 m/s²; T = 17.4 N. The 2.80 kg block moves down.

**Check / concept:** The net driving force is the difference in weights; the accelerated mass is the sum of both masses.

## 13. Incline block and hanging block

A 3.70 kg block m₁ on a frictionless 30.0° incline is joined over a massless, frictionless pulley to a hanging 2.30 kg block m₂. Find the acceleration magnitude and tension.

1. **Determine which side wins.** Hanging weight: m₂g = 22.54 N. Incline component: m₁g sin 30° = 18.13 N.
Thus m₂ accelerates down and m₁ accelerates up the incline.

2. **Write and add the equations.** m₂g − T = m₂a; T − m₁g sin θ = m₁a.
a = (m₂g − m₁g sin θ)/(m₁ + m₂)
a = (22.54 − 18.13)/(3.70 + 2.30) = 0.735 m/s².

3. **Find the tension.** T = m₂(g − a) = (2.30)(9.8 − 0.735) = 20.8495 N.

**Answer:** a = 0.735 m/s²; T = 20.8 N. The hanging block accelerates down.

**Check / concept:** Compare the hanging weight to the incline-parallel weight component, not to the incline block’s full weight.

## 14. Man lifting a bosun’s chair

A man and chair have combined mass 95.0 kg. A massless rope passes over a massless, frictionless pulley, with one end attached to the chair and the other held by the man. Find his pull for (a) constant upward velocity and (b) upward acceleration 1.30 m/s².

1. **Select the man-plus-chair system.** The rope pulls upward at two places: on the chair and on the man’s hands. Each force has magnitude T. Gravity acts downward.
Therefore 2T − Mg = Ma. His downward pull on the rope has magnitude T.

2. **(a) Set acceleration to zero.** Constant velocity means a = 0:
2T = Mg → T = (95.0)(9.8)/2 = 465.5 N.

3. **(b) Include the upward acceleration.** T = M(g + a)/2 = (95.0)(9.8 + 1.30)/2 = 527.25 N.

**Answer:** (a) Pull downward with 466 N. (b) Pull downward with 527 N.

**Check / concept:** For the combined man-chair system, there are two upward tension forces. Missing either one doubles the calculated pull.

## 15. Table block between two hanging masses

A = 6.00 kg and C = 10.0 kg hang on opposite sides of a frictionless table; B = 8.00 kg sits on the table. Separate cords connect A-B and B-C over frictionless pulleys. Find both cord tensions after release.

1. **Choose the directions of acceleration.** C descends, B moves right, and A rises. All have the same acceleration magnitude.
A: T_L − m_Ag = m_Aa.
B: T_R − T_L = m_Ba. C: m_Cg − T_R = m_Ca.

2. **Add the three equations.** a = (m_C − m_A)g/(m_A + m_B + m_C)
a = (10.0 − 6.00)(9.8)/24.0 = 1.63333 m/s².

3. **Solve for each tension separately.** T_L = m_A(g + a) = (6.00)(9.8 + 1.63333) = 68.60 N.
T_R = m_C(g − a) = (10.0)(9.8 − 1.63333) = 81.6667 N.

**Answer:** Left cord (A-B): 68.6 N. Right cord (B-C): 81.7 N.

**Check / concept:** Check on B: 81.6667 − 68.60 = 13.0667 N = (8.00)(1.63333).

## 16. Push toward the pulley: slack limit

A 3.0 kg block m₁ on a frictionless horizontal surface is connected over an edge pulley to a 1.0 kg block m₂ on a frictionless 30° downward slope. A horizontal force F pushes m₁ right, toward the pulley. (a) Find T when F = 2.3 N. (b) Find the largest F before the cord goes slack.

1. **Follow the cord constraint.** Take rightward for m₁ and down-slope for m₂ as positive. These motions shorten one cord segment and lengthen the other equally.
m₁: F + T = m₁a. m₂: m₂g sin θ − T = m₂a.

2. **(a) Add, then substitute.** a = (F + m₂g sin θ)/(m₁ + m₂) = (2.3 + 4.9)/4.0 = 1.80 m/s².
T = m₁a − F = (3.0)(1.80) − 2.3 = 3.10 N.

3. **(b) Use the zero-tension threshold.** At the limiting case, T = 0 and the slope block has a = g sin θ = 4.90 m/s².
F_max = m₁a = (3.0)(4.90) = 14.7 N.

**Answer:** (a) T = 3.10 N. (b) F_max = 14.7 N (T = 0 at the threshold).

**Check / concept:** A rope can pull but cannot push. Above this force the taut-cord equations would require negative tension, so the cord becomes slack.

## 17. Two blocks, two rightward forces

Block A (4.0 kg) and block B (6.0 kg) are connected by a light string. A is left of B. Rightward forces F_A = 12 N and F_B = 24 N act on A and B, respectively. Find the tension. Assume negligible horizontal friction.

1. **Find the system acceleration.** Both applied forces point right. For the combined system, the tension forces cancel:
a = (F_A + F_B)/(m_A + m_B) = (12 + 24)/(4.0 + 6.0) = 3.60 m/s².

2. **Use block A.** The string pulls A toward B, to the right:
F_A + T = m_Aa → T = (4.0)(3.60) − 12 = 2.40 N.

3. **Check with block B.** The string pulls B to the left:
F_B − T = m_Ba → 24 − 2.40 = (6.0)(3.60) = 21.6 N.

**Answer:** T = 2.40 N.

**Check / concept:** The applied 12 N and 24 N forces point in the same direction; tension acts in opposite directions on the two blocks.

## 18. Pull uphill with a pulley at the bottom

A 12 N force pulls m₂ = 1.0 kg up a frictionless 37° incline. A cord connects it through a pulley at the bottom to m₁ = 3.0 kg on a frictionless floor. Find the tension; cord and pulley masses are negligible.

1. **Identify the tension direction.** On m₂, the cord pulls toward the bottom pulley, down the incline. On m₁, it pulls right toward the pulley. Choose uphill for m₂ and rightward for m₁ as positive.

2. **Write the equations.** m₁: T = m₁a.
m₂: F − T − m₂g sin θ = m₂a.

3. **Add and solve.** a = (F − m₂g sin θ)/(m₁ + m₂)
a = [12 − (1.0)(9.8) sin 37°]/4.0 = 1.52555 m/s².
T = m₁a = (3.0)(1.52555) = 4.57666 N.

**Answer:** T = 4.58 N.

**Check / concept:** Tension opposes the applied uphill force here because the pulley is below the incline block.

## 19. Blocks on opposite slopes

A 3.0 kg block m₁ rests on a frictionless 30° incline and a 2.0 kg block m₂ rests on a frictionless 60° incline. They are connected over a massless, frictionless pulley at the top. Find the cord tension.

1. **Compare the downslope weight components.** m₁g sin 30° = 14.70 N; m₂g sin 60° = 16.9741 N.
Therefore m₂ moves down its slope and m₁ moves up its slope.

2. **Write and add the force equations.** T − m₁g sin 30° = m₁a; m₂g sin 60° − T = m₂a.
a = (16.9741 − 14.70)/(3.0 + 2.0) = 0.454820 m/s².

3. **Find the tension.** T = m₁g sin 30° + m₁a
T = 14.70 + (3.0)(0.454820) = 16.0645 N.

**Answer:** T = 16.1 N.

**Check / concept:** The lighter block wins here because its slope is steeper. Compare components, not just masses.

## 20. Find the tension and unknown incline angle

A 1.0 kg block m₁ on a frictionless slope is connected through a pulley at the bottom of the slope to hanging block m₂ = 2.0 kg. An upward force F = 6.0 N acts on m₂, which accelerates downward at 5.5 m/s². Find T and the incline angle β.

1. **Use the hanging block first.** Choose downward positive for m₂. Its weight acts down; tension and the applied force act up:
m₂g − T − F = m₂a.
T = m₂g − F − m₂a = (2.0)(9.8) − 6.0 − (2.0)(5.5) = 2.60 N.

2. **Follow the actual pulley geometry.** As m₂ descends, m₁ moves down the incline toward the bottom pulley. Both tension and m₁g sin β act down the slope.
T + m₁g sin β = m₁a.

3. **Solve for the angle.** sin β = (m₁a − T)/(m₁g) = [(1.0)(5.5) − 2.60]/[(1.0)(9.8)] = 0.295918.
β = sin⁻¹(0.295918) = 17.2126°.

**Answer:** T = 2.60 N; β = 17.2°.

**Check / concept:** Because the pulley is at the bottom, tension pulls the incline block downhill. Reversing that force produces the wrong angle.
