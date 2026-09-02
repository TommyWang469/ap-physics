# Relative Velocity — Worked Solutions

Use east as the positive \(x\)-direction and north as the positive \(y\)-direction throughout.

The basic relationship is

\[
\vec v_{A/C}=\vec v_{A/B}+\vec v_{B/C}.
\]

## Problem 3.71 — Airplane and wind

An airplane points due west with an airspeed of \(220\ \text{km/h}\). After \(0.500\ \text{h}\), it is \(120\ \text{km}\) west and \(20\ \text{km}\) south of its starting point.

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

A train moves east at \(12.0\ \text{m/s}\). Rain falls vertically relative to Earth and leaves traces on the train windows inclined \(30.0^\circ\) from vertical.

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

Juan runs north at \(8.00\ \text{m/s}\). The ball moves at \(12.0\ \text{m/s}\), \(37.0^\circ\) east of north, relative to the ground.

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

Mia runs north at \(6.00\ \text{m/s}\). Relative to Mia, the ball moves at \(5.00\ \text{m/s}\), \(30.0^\circ\) east of south.

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
