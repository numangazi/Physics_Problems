# Section 1: Mechanics I - Solutions

## 1. Projectile Motion
### Differential Equations of Motion
The only force acting on the projectile (neglecting air resistance) is gravity in the negative y-direction: $\vec{F} = -mg\hat{j}$. According to Newton's Second Law:
* **Horizontal (x):** $m\frac{d^2x}{dt^2} = 0 \implies \frac{d^2x}{dt^2} = 0$
* **Vertical (y):** $m\frac{d^2y}{dt^2} = -mg \implies \frac{d^2y}{dt^2} = -g$

### Calculations (Initial Velocity: $100 \text{ m/s}$ at $37^\circ$)
* $v_{0x} = 100 \cos(37^\circ) \approx 80 \text{ m/s}$
* $v_{0y} = 100 \sin(37^\circ) \approx 60 \text{ m/s}$

1. **Time of Flight:** Using $y(t) = v_{0y}t - \frac{1}{2}gt^2 = 0 \implies t = \frac{2v_{0y}}{g} = \frac{120}{9.81} \approx 12.23 \text{ s}$
2. **Maximum Height:** $H = \frac{v_{0y}^2}{2g} = \frac{60^2}{19.62} \approx 183.49 \text{ m}$
3. **Range:** $R = v_{0x} \cdot t \approx 80 \cdot 12.23 \approx 978.4 \text{ m}$

---

## 2. Range Optimization
The range is given by $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$. To maximize $R$, we find the derivative with respect to $\theta$:
* $\frac{dR}{d\theta} = \frac{v_0^2}{g} (2 \cos(2\theta))$
Setting the derivative to zero:
* $2 \cos(2\theta) = 0 \implies 2\theta = 90^\circ \implies \theta = 45^\circ$

---

## 3. Path Intersection
* **Alice:** $A(t) = (2+t, 8-3t)$
* **Bob:** $B(t) = (2t-1, 2t+2)$

Setting $x_A = x_B \implies 2+t = 2t-1 \implies t = 3 \text{ s}$.
Checking $y$ at $t=3$: $y_A = 8-3(3) = -1$; $y_B = 2(3)+2 = 8$.
Since $-1 \neq 8$, they do **not** intersect. 

To find the minimum distance, we minimize $f(t) = (x_A-x_B)^2 + (y_A-y_B)^2$:
* $f(t) = (3-t)^2 + (6-5t)^2 = 26t^2 - 66t + 45$
* $f'(t) = 52t - 66 = 0 \implies t \approx 1.27 \text{ s}$

---

## 4. Vector Calculus
Given $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$:
* **Velocity:** $\vec{v}(t) = \frac{d\vec{r}}{dt} = (6t)\hat{i} + (5 - 16t)\hat{j}$
* **Acceleration:** $\vec{a}(t) = \frac{d\vec{v}}{dt} = 6\hat{i} - 16\hat{j}$

---

## 5. Relative Velocity
* $V_{river} = 2 \text{ m/s East}$
* $V_{boat/water} = 5 \text{ m/s}$
To head North, the boat's horizontal velocity must cancel the river's flow:
* $5 \sin(\theta) = 2 \implies \theta = \arcsin(0.4) \approx 23.58^\circ$ **West of North**
* **Travel Time:** $V_{north} = 5 \cos(23.58^\circ) \approx 4.58 \text{ m/s}$
* $t = \frac{200 \text{ m}}{4.58 \text{ m/s}} \approx 43.6 \text{ s}$

---

## 6. Variable Velocity
$v(t) = t^2 + 2t - 5$, $x(0) = 4$.
* **Acceleration at $t=3$:** $a(t) = v'(t) = 2t + 2 \implies a(3) = 8 \text{ m/s}^2$
* **Position at $t=3$:** $x(3) = 4 + \int_0^3 (t^2 + 2t - 5) dt = 4 + [\frac{t^3}{3} + t^2 - 5t]_0^3 = 4 + (9 + 9 - 15) = 7$

---

## 7. Path Parametric Analysis
$x(t) = 2t^2, y(t) = 3t^3$.
1. **Eliminate t:** $t = \sqrt{x/2} \implies y = 3(x/2)^{3/2} \implies y^2 = \frac{27x^3}{8}$
2. **Vectors:** * $\vec{v}(t) = (4t, 9t^2)$, $|\vec{v}(t)| = \sqrt{16t^2 + 81t^4}$
   * $\vec{a}(t) = (4, 18t)$, $|\vec{a}(t)| = \sqrt{16 + 324t^2}$
3. **Is acceleration constant?** No, it depends on $t$.

---

## 8. Circular Motion (Earth's Equator)
* $R = 6378 \text{ km} = 6,378,000 \text{ m}$
* $T = 24 \text{ h} = 86,400 \text{ s}$
* $a_c = \omega^2 R = (\frac{2\pi}{T})^2 R = (\frac{2\pi}{86400})^2 \cdot 6378000 \approx 0.034 \text{ m/s}^2$

---

## 9. Momentum Comparison ($p = mv$)
* **Fly:** $p = 0.002 \text{ kg} \cdot 10 \text{ m/s} = 0.02 \text{ kg}\cdot\text{m/s}$
* **Tennis Ball:** $p = 0.060 \text{ kg} \cdot 1 \text{ m/s} = 0.06 \text{ kg}\cdot\text{m/s}$
The **tennis ball** has greater momentum.

---

## 10. Kinematics - Elliptical Helix
Given $\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)$.

**a) Trajectory:**
The projection in the xy-plane is an ellipse: $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$. The z-coordinate increases linearly with time ($z=bt$), making the path an **elliptical helix**.

**b) Path Length ($L$):**
$L = \int_0^{t_0} \sqrt{\dot{x}^2 + \dot{y}^2 + \dot{z}^2} dt = \int_0^{t_0} \sqrt{a^2\omega^2\sin^2(\omega t) + b^2\omega^2\cos^2(\omega t) + b^2} dt$

**c) Interactive Visualization:**
*A Python script will be used to demonstrate the 3D trajectory during the presentation to ensure high-quality delivery.*