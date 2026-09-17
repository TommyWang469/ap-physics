# Unit 2 - Applying Newton's Laws: Equilibrium Homework

September 16, 2026. Exercises 5.1, 5.2, 5.3, 5.5, 5.6, 5.7, 5.8, 5.9. Exercise 5.4 is omitted as requested.

Source: user-supplied textbook screenshots. Questions transcribed from the screenshots; original figure numbers retained. Use g = 9.80 m/s². Assume ideal ropes and pulleys unless the problem gives a chain mass.

[Source: exercises 5.1-5.3](sources/unit-2/equilibrium-sept16/exercises-5-1-to-5-3.png) | [Source: page 160](sources/unit-2/equilibrium-sept16/page-160.png)

[Completed PDF](output/pdf/unit-2-equilibrium-5-1-to-5-9-skip-5-4.pdf)

Completed homework: 5.1-5.9, with 5.4 omitted. Use g = 9.80 m/s². Each system is in equilibrium; ideal pulleys change a rope's direction without changing its tension.

## 5.1 | Two equal weights

Question. Two 25.0 N weights are suspended at opposite ends of a rope that passes over a light, frictionless pulley. The pulley is attached to a chain from the ceiling. (a) What is the tension in the rope? (b) What is the tension in the chain?

For either weight, T - 25.0 N = 0. The pulley is pulled downward by two rope segments, each with tension T. Its supporting chain must supply 2T upward.

(a) T = 25.0 N.    (b) T_chain = 2T = 50.0 N.

## 5.2 | Three pulley arrangements

Question. In Fig. E5.2 each suspended block has weight w. The pulleys are frictionless, and the ropes have negligible weight. In each case, draw a free-body diagram and calculate the tension T in the rope in terms of w.

Figure: Figure E5.2; see the archived source screenshot.

Free-body diagrams for 5.2: in each of (a), (b), and (c), isolate one hanging block, with F_T upward and w downward. Here F_T = T is the rope tension.

For each isolated block: ΣF_y = T - w = 0. Each fixed pulley redirects the rope; none of these blocks is supported by two rope segments.

(a) T = w.    (b) T = w.    (c) T = w.

### 5.2(a) - Force applied to the wall

The updated PDF explicitly labels F_T on each hanging-block diagram and includes separate force diagrams for the pulley and the wall attachments.

- **Rope's fixed end:** The horizontal rope pulls the wall to the right with F_T = w. The wall pulls the rope left with an equal force.
- **Pulley:** The rope pulls left with F_T and down with F_T. Ignoring pulley/support weight, the support force on the pulley has components (+F_T, +F_T), taking right/up as positive. Its magnitude is sqrt(2) F_T, directed up-right at 45 degrees.
- **Pulley mount's force on the wall:** By Newton's third law, its components are (-F_T, -F_T) = (-w, -w). Its magnitude is sqrt(2) w, directed down-left at 45 degrees.
- **Net load on the whole wall from both attachments:** (w, 0) + (-w, -w) = (0, -w), so the net force is w downward. This is different from the force at either individual attachment.

## 5.3 | Tension varies along a heavy chain

Question. A 75.0 kg wrecking ball hangs from a uniform, heavy-duty chain of mass 26.0 kg. (a) Find the maximum and minimum tensions in the chain. (b) What is the tension at a point three-fourths of the way up from the bottom of the chain?

Setup. A point in the chain supports the ball and all of the chain below that point. If f is the fraction of chain length below the point, uniform density means the supported chain mass is f(26.0 kg).

T(f) = [75.0 + 26.0f]g.

(a) Maximum: at the top, f = 1.
T_max = (75.0 + 26.0)(9.80) = 989.8 N ≈ 990 N.

Minimum: at the bottom, f = 0.
T_min = 75.0(9.80) = 735 N.

(b) Three-fourths up: 75% of the chain lies below this point.
T = [75.0 + 0.75(26.0)](9.80) = 926.1 N ≈ 926 N.

Answers: T_max = 990 N; T_min = 735 N; T_3/4 = 926 N.

## 5.5 | Picture frame supported by two wires

Question. A picture frame hung against a wall is suspended by two wires attached to its upper corners. If the two wires make the same angle with the vertical, what must this angle be if the tension in each wire is equal to 0.75 of the weight of the frame? Ignore any friction between the wall and the picture frame.

Let W be the frame's weight and θ the angle of each wire from the vertical. The horizontal components cancel. Each wire supplies upward force T cos θ, so:

2T cos θ = W.
Substitute T = 0.75W:
2(0.75W) cos θ = W
cos θ = 1/1.50 = 2/3.

θ = cos^-1(2/3) = 48.2° from the vertical.

## 5.6 | Resolve tension into components

Question. A large wrecking ball is held in place by two light steel cables (Fig. E5.6). Its mass is 3620 kg. Find (a) tension T_B in the cable that makes an angle of 40° with the vertical and (b) tension T_A in the horizontal cable.

Figure: Figure E5.6; see the archived source screenshot.

Free-body diagram: T_A pulls left, T_B pulls up-right at 40° from vertical, and mg pulls down. The ball has zero acceleration.

(a) Vertical balance
T_B cos 40° - mg = 0
T_B = mg / cos 40°
T_B = (3620)(9.80) / cos 40° = 46,310.6 N.

T_B = 4.63 × 10^4 N.

(b) Horizontal balance
T_B sin 40° - T_A = 0
T_A = T_B sin 40° = mg tan 40°
T_A = (3620)(9.80) tan 40° = 29,767.9 N.

T_A = 2.98 × 10^4 N.

Angle check: The 40° angle is measured from vertical, so the vertical component uses cosine and the horizontal component uses sine.

## 5.7 | Solve both arrangements

Question. Find the tension in each cord in Fig. E5.7 if the weight of the suspended object is w.

Figure: Figure E5.7; see the archived source screenshot.

In both arrangements, the hanging object is at rest: T_C = w. At the junction, each cord pulls along itself, away from the junction.

(a) A pulls up-left at 30° above horizontal; B pulls up-right at 45°.
Horizontal: T_B cos 45° = T_A cos 30°.
Vertical: T_A sin 30° + T_B sin 45° = w.

Substitute T_B = T_A cos 30° / cos 45°:
T_A(sin 30° + cos 30° tan 45°) = w.
T_A = w/(0.500 + 0.866025) = 0.732051w.

(a) T_A = 0.732w;   T_B = 0.897w;   T_C = w.

(b) A pulls down-left, 60° from vertical (30° below horizontal); B pulls up-right at 45°.
Horizontal: T_B cos 45° = T_A cos 30°.
Vertical: T_B sin 45° - T_A sin 30° = w.

Substitute for T_B:
T_A(cos 30° tan 45° - sin 30°) = w.
T_A = w/(0.866025 - 0.500) = 2.73205w.

(b) T_A = 2.73w;   T_B = 3.35w;   T_C = w.

Why larger in (b)? Cord B must support both the weight and the downward component of cord A's tension.

## 5.8 | Balance forces at each junction

Question. In Fig. E5.8, the weight w is 60.0 N. (a) What is the tension in the diagonal string? (b) Find the magnitudes of the horizontal forces F_1 and F_2 that must be applied to hold the system in the position shown.

Figure: Figure E5.8; see the archived source screenshot.

The lower vertical string pulls down on the lower junction with 60.0 N. The diagonal tension T pulls that junction up-left at 45° above horizontal; F_2 pulls right.

(a) Lower junction, vertical balance:
T sin 45° = 60.0 N
T = 60.0 / sin 45° = 84.8528 N.

Diagonal-string tension: T = 84.9 N.

(b) Lower junction, horizontal balance:
F_2 = T cos 45° = 60.0 N.

Upper junction, horizontal balance:
The diagonal string pulls down-right. Its rightward component is balanced by the leftward F_1:
F_1 = T cos 45° = 60.0 N.

F_1 = 60.0 N left;   F_2 = 60.0 N right.

As a check, the upper vertical string has tension T sin 45° = 60.0 N, balancing the diagonal string's downward component at the upper junction.

## 5.9 | Applied force on a frictionless ramp

Question. A man pushes on a piano with mass 180 kg; it slides at constant velocity down a ramp inclined at 19.0° above the horizontal floor. Neglect friction. Calculate the magnitude of the force applied by the man if he pushes (a) parallel to the incline and (b) parallel to the floor.

Constant velocity means a = 0, even though the piano is moving downhill. Gravity has a downhill component mg sin 19.0°, so the man must supply an equal uphill component.

Piano free-body diagrams: mg downward and N perpendicular away from the ramp. In (a), F is uphill along the ramp. In (b), F is horizontal toward the uphill side. The ramp is drawn rising to the right.

(a) Force parallel to the incline
Take uphill as positive:
F - mg sin 19.0° = 0.
F = (180)(9.80) sin 19.0° = 574.302 N.

(a) F = 574 N, directed uphill along the ramp.

(b) Force parallel to the floor
The horizontal force makes a 19.0° angle with the uphill ramp direction, so its uphill component is F cos 19.0°:
F cos 19.0° - mg sin 19.0° = 0.
F = mg tan 19.0° = (180)(9.80) tan 19.0° = 607.394 N.

(b) F = 607 N, horizontal toward the uphill side.

Check: The horizontal force must be larger because only part of it points uphill. Its remaining component pushes into the ramp and increases the normal force.
