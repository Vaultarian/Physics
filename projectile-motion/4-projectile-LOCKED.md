<!-- LOCKED: source-verbatim, equations-transcribed -->

# AP Physics — Projectile Motion
**Physics Kahuna · c. 2001 · 8 problems · 11 question-points**

## Problem Index

| # | Problem | Key Values | Find |
|---|---|---|---|
| Q1 | Flagpole ornament falls | height = 25.0 m | time to hit ground |
| Q2 | Stone off cliff | height = 44.0 m, vx = 15.0 m/s | time and horizontal range |
| Q3 | B-17 bomber altitude | v = 375 km/h, range = 5 250 m | altitude |
| Q4 | Ball at angle: max height | v = 22.7 m/s, θ = 66.0° | maximum height |
| Q5 | Naval gun: range | v = 345 m/s, θ = 32.0° | range |
| Q6 | Punter: kick angle | hang time = 4.5 s, range = 48 m | angle θ |
| Q7a | Stone off building | height = 45.0 m, θ = 62.5°, v = 31.5 m/s | time in flight |
| Q7b | Stone off building | same | horizontal range |
| Q7c | Stone off building | same | final speed |
| Q8 | Potato toss: range | θ = 22.2°, time = 1.55 s | horizontal range |

---

## I. Introduction to Projectile Motion

### A. Definition and Key Concept

A ***projectile*** is any object that falls through the air. These objects are accelerated downward by the force of gravity. We will ignore the effects of air resistance, which can be safely done if the object is dense and the distance that it falls is not too great.

[Figure: projectile trajectory showing parabolic path — see index.html]

Projectiles always follow a curved path called a ***trajectory*** (this trajectory is a segment of a parabola, a fact discovered by Galileo). Sometimes the trajectory is called a ***ballistic path***. Such motion is three dimensional, but we will, for simplicity's sake, deal only with motion in two dimensions — up/down, and sideways.

The key to efficiently deal with projectile motion is to simply break the velocity down into its horizontal and vertical components.

> **Vectors that are perpendicular to each other act independently.**

This means that the horizontal and vertical components of a velocity vector don't affect each other. The up and down motion has nothing to do with the sideways motion and the sideways motion has no effect on the up and down motion.

### B. Assumptions

1. ***g*** has magnitude of 9.80 m/s² and is always downward.
2. Effect of air resistance can be ignored.
3. Rotation of earth can be ignored.
4. Motion (the horizontal velocity component) in the horizontal direction is constant.

### C. Velocity Components

The velocity of a projectile has two components, ***v***_x and ***v***_y.

[Figure: velocity vector with horizontal (vx) and vertical (vy) components — see index.html]

$$v_y = v\sin\theta \qquad v_x = v\cos\theta$$

Important concepts:

- *horizontal velocity component is always constant*
- There is no acceleration in the *horizontal direction*.

[Figure: two balls — one falls straight down, one launched horizontally — both hit ground simultaneously — see index.html]

[Figure: parabolic trajectory showing vx constant, vy changing — zero at apex — see index.html]

As long as the projectile is in the air, it will do two things:

- ***It will move horizontally at a constant speed.***
- ***It will accelerate downwards at a constant rate of g.***

The way you solve these problems is to break it into two problems: a constant motion horizontal problem and a vertical constant acceleration problem.

---

## II. Horizontal Launch Problems

### Q1 — Flagpole Ornament

**Problem:** A flagpole ornament falls off the top of a 25.0 m flagpole. How long would it take to hit the ground?

**Solution:** We assume that the ornament has no horizontal velocity. It falls straight down.

$$x = \tfrac{1}{2}at^2 \implies t = \sqrt{\frac{2x}{a}}$$

$$t = \sqrt{\frac{2 \times 25.0}{9.80}} = \sqrt{5.10} = 2.26 \text{ s}$$

---

### Q2 — Stone off Cliff

**Problem:** A stone is thrown horizontally from the top of a cliff that is 44.0 m high. It has a horizontal velocity of 15.0 m/s. Find how long it takes the stone to fall to the deck and how far it will travel from the base of the cliff.

**Solution:** The time to hit the ground is the same as if the stone were falling straight down (the key concept!):

$$t = \sqrt{\frac{2 \times 44.0}{9.80}} = 2.99 \text{ s}$$

Horizontal distance:

$$x = v_x \times t = 15.0 \times 2.99 = 44.9 \text{ m}$$

---

### Q3 — B-17 Bomber Altitude

**Problem:** A B-17 is flying at 375 km/h. The bombs it drops travel a horizontal distance of 5 250 m. What was the altitude of the plane?

**Solution:** Convert speed:

$$375\ \frac{\text{km}}{\text{h}} \times \frac{1000\ \text{m}}{\text{km}} \div \frac{3600\ \text{s}}{\text{h}} = 104\ \text{m/s}$$

Time for bomb to travel 5 250 m horizontally:

$$t = \frac{x}{v_x} = \frac{5250}{104} = 50.5 \text{ s}$$

Altitude (vertical fall):

$$y = \tfrac{1}{2}gt^2 = \tfrac{1}{2}(9.80)(50.5)^2 = 12\,500 \text{ m}$$

---

## III. Upwardly Moving Projectiles

[Figure: upward projectile trajectory showing symmetry — velocity vectors at various points — see index.html]

[Figure: hunter and monkey — bullet and monkey fall same distance; aim straight at monkey — see index.html]

[Figure: angled projectile path with vx and vy labelled; vy = 0 at apex; symmetric fall — see index.html]

The projectile will travel a horizontal distance of ***x*** (the ***range***). It will travel upwards a vertical distance of ***y***. In half the total time of flight it will reach ***y*** and its vertical velocity will be zero.

We assume that the projectile begins and ends at the same height unless otherwise stated.

---

### Q4 — Ball at Angle: Max Height

**Problem:** A ball is given an initial velocity of 22.7 m/s at an angle of 66.0° to the horizontal. Find how high the ball will go.

**Solution:** Find the vertical velocity component:

$$v_y = v\sin\theta = 22.7\sin 66.0° = 20.7 \text{ m/s}$$

The ball rises until $v_y = 0$:

$$v_f^2 = v_0^2 + 2ay \implies 0 = v_y^2 + 2(-9.80)y$$

$$y = \frac{v_y^2}{2g} = \frac{(20.7)^2}{2 \times 9.80} = 21.9 \text{ m}$$

---

### Q5 — Naval Gun: Range

**Problem:** A naval gun fires a projectile at a muzzle velocity of 345 m/s at an elevation of 32.0°. What is the range?

**Solution:**

$$v_y = v\sin\theta = 345\sin 32.0° = 183 \text{ m/s}$$

Time to apex ($v_f = 0$):

$$0 = 183 + (-9.80)t \implies t_{\text{up}} = 18.7 \text{ s}$$

Total time (by symmetry):

$$t_{\text{total}} = 2 \times 18.7 = 37.4 \text{ s}$$

Horizontal velocity:

$$v_x = v\cos\theta = 345\cos 32.0° = 293 \text{ m/s}$$

Range:

$$x = v_x \times t = 293 \times 37.4 = 10\,960 \text{ m} \approx 11.0 \text{ km}$$

---

### Q6 — Punter: Find the Angle

**Problem:** A punter has a hang time of 4.5 s. If the ball travels 48 m down the field, what was the kick angle?

**Solution:** Horizontal velocity:

$$v_x = \frac{x}{t} = \frac{48}{4.5} = 10.7 \text{ m/s}$$

Vertical velocity (ball falls for half the hang time from apex):

$$v_y = g \times \frac{t}{2} = 9.80 \times 2.25 = 22.1 \text{ m/s}$$

Kick angle:

$$\theta = \arctan\!\left(\frac{v_y}{v_x}\right) = \arctan\!\left(\frac{22.1}{10.7}\right) = \arctan(2.07) = 64.2°$$

---

### Q7 — Stone off Building

**Problem:** A stone is thrown off the top of a building from a height of 45.0 m. Launch angle 62.5°, speed 31.5 m/s. (a) How long is the stone in flight? (b) How far from the base of the building does it travel? (c) What is its speed just before it hits the ground?

[Figure: stone launched upward from building; parabolic path ending at ground level — see index.html]

**Solution (a):** Vertical velocity component:

$$v_y = v\sin\theta = 31.5\sin 62.5° = 27.9 \text{ m/s}$$

Time to apex:

$$0 = 27.9 + (-9.80)t \implies t_{\text{up}} = 2.85 \text{ s}$$

Height gained above building:

$$y = \frac{v_y^2}{2g} = \frac{(27.9)^2}{2 \times 9.80} = 39.7 \text{ m}$$

Total fall distance = 39.7 + 45.0 = 84.7 m:

$$t_{\text{down}} = \sqrt{\frac{2 \times 84.7}{9.80}} = 4.16 \text{ s}$$

Total time:

$$t_{\text{total}} = 2.85 + 4.16 = 7.01 \text{ s}$$

**Solution (b):** Horizontal velocity:

$$v_x = v\cos\theta = 31.5\cos 62.5° = 14.6 \text{ m/s}$$

$$x = v_x \times t = 14.6 \times 7.01 = 102 \text{ m}$$

**Solution (c):** Vertical speed at impact (falls 4.16 s from apex):

$$v_y = g \times t_{\text{down}} = 9.80 \times 4.16 = 40.8 \text{ m/s}$$

Final speed:

$$v = \sqrt{v_x^2 + v_y^2} = \sqrt{14.6^2 + 40.8^2} = \sqrt{213 + 1665} = \sqrt{1878} = 43.3 \text{ m/s}$$

---

### Q8 — Potato Toss: Find Range

**Problem:** You throw a potato at an angle of 22.2°. It is in the air for 1.55 s. How far did it go?

**Solution:** In half the time it travels to maximum height, so vertical velocity at launch:

$$v_y = g \times \frac{t}{2} = 9.80 \times 0.775 = 7.60 \text{ m/s}$$

Horizontal velocity from angle:

$$\frac{v_y}{v_x} = \tan\theta \implies v_x = \frac{v_y}{\tan\theta} = \frac{7.60}{\tan 22.2°} = 18.7 \text{ m/s}$$

Range:

$$x = v_x \times t = 18.7 \times 1.55 = 29.0 \text{ m}$$

---

## Supplementary — Sidebars

### ENIAC Trivia

The first digital computer, called ENIAC (Electronic Numerical Integrator and Computer) became operational in 1946. It was funded by the Army in World War II. The purpose for the thing was to calculate trajectories for artillery shells to produce firing tables that the gun crews who served the guns could utilize. It could add 500 numbers in only one second and could calculate the trajectory for a firing problem in only 30 seconds — a true miracle. It used electronic tubes and required 174 kilowatts of power (that's 233 horsepower for you non-metric folks). Anyway, the power needed to solve one trajectory problem was about the same as the amount of power generated by the powder charge during an actual fire mission for a single shell. Interesting.

### Cecil Adams — Two Bullets

**Dear Cecil:** My high school physics teacher gave us this problem once, but I forget what the answer was. Suppose you've got a bullet in one hand and a pistol in the other, aimed so it's perfectly level. You drop the bullet and fire the pistol at the same time. Which bullet hits the ground first? —L., Indianapolis

**Cecil replies:** I know this is a lot of physics for one day, but this one is so twisted you gotta love it. The average mope reasons like this: the dropped bullet falls only a few feet, whereas the fired bullet travels hundreds of yards. Ergo, the dropped bullet hits the ground first. The average mope with a college education (e.g., a physics teacher) is a little more sophisticated. He figures, hey, the force of the gun propels the fired bullet strictly horizontally. The only *downward* force is gravity, which acts equally on both bullets. Therefore they both hit the ground at the same time.

Then we have the answer given by those who have achieved spiritual awareness as a result of regular reading of the Straight Dope. This may be summarized as follows: *it depends*. If the fired bullet travels only a short distance, then yes, both bullets hit the ground at the same time. However, if the fired bullet travels far enough, the earth, being round, *curves away from it*. Since the fired bullet has farther to fall, it takes longer to hit the earth, so the dropped bullet hits the ground first. What's more, if the fired bullet travels fast enough (roughly five miles per second), it goes into orbit around the earth and *never hits the ground at all*. —CECIL ADAMS

### Cecil Adams — Human Cannonball

**Dear Cecil:** When I was a small boy I attended a circus that featured a "human cannonball." This amazing fellow was shot out of a large cannon and flew about thirty yards into a giant net. How did they do this without blowing the poor guy to pieces? —Rob Marchant, Carrollton, Texas

**Cecil replies:** Human cannonballs aren't blasted from the cannon with gunpowder. They're propelled by a catapult. The flash, loud noise and smoke are supplied by firecrackers and such. The first human cannonball was a young woman named Zazel, who made her maiden voyage on April 2, 1877 at the Westminster Aquarium. The propellant of choice today is compressed air at 150–200 pounds per square inch. The cylinder stops at the cannon's mouth. Its occupant doesn't.

Being shot from a cannon, like jumping out of an airplane, isn't that strenuous; it's the sudden stop at the end that's a bitch. Historian A.H. Coxe says of 50 human cannonballs more than 30 have been killed, mostly by falling outside the net. Of course you might figure anybody who lets himself get shot from a cannon is a couple eggs short of a dozen to start with. If you must have heavy-caliber kicks, I say join the Marines. At least they let you shoot back. —CECIL ADAMS

---

*Source: Physics Kahuna, AP Physics — Projectile Motion, c. 2001*
*LOCKED v1.0 — 2026-04-25*
