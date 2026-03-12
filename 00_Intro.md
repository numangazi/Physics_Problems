# Section 0: Mathematical Foundations - Solutions

## 1. Vector Algebra
Given $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$:

* **a) Magnitudes:**
  * $|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx 3.74$
  * $|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx 4.58$

* **b) Dot Product:**
  * $\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3$

* **c) Cross Product:**
  * $\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{\hat{i}} & \mathbf{\hat{j}} & \mathbf{\hat{k}} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix} = -5\mathbf{\hat{i}} - 14\mathbf{\hat{j}} - 8\mathbf{\hat{k}}$

* **d) Angle ($\theta$):**
  * $\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|} = \frac{3}{\sqrt{14}\sqrt{21}} \implies \theta \approx 79.9^\circ$

---

## 2. Systems of Equations
Equations: $2x + 3y = 12$ and $x - y = 1$
* From second equation: $x = y + 1$
* Substitute into first: $2(y + 1) + 3y = 12 \implies 5y = 10 \implies y = 2$
* Result: $x = 3, y = 2$

---

## 3. Proportionality
Universal Law of Gravitation: $F = G \frac{m_1 m_2}{r^2}$
* New parameters: $r' = 2r$, $m_1' = \frac{m_1}{2}$, $m_2' = \frac{m_2}{2}$
* $F' = G \frac{(m_1/2)(m_2/2)}{(2r)^2} = \frac{1}{4} \cdot \frac{1}{4} \left( G \frac{m_1 m_2}{r^2} \right) = \frac{1}{16}F$
* **Factor:** $1/16$

---

## 4. Rearranging Formulas
$T = 2\pi \sqrt{\frac{L}{g}}$
1. $\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$
2. $\frac{T^2}{4\pi^2} = \frac{L}{g}$
3. $g = \frac{4\pi^2 L}{T^2}$

---

## 5. Trigonometry
Magnitude $A = 15$, $\theta = 60^\circ$:
* $A_x = 15 \cos(60^\circ) = 7.5$
* $A_y = 15 \sin(60^\circ) \approx 12.99$

---

## 6. Function Analysis
$f(x) = 3x^2 - 12x + 7$
* $f'(x) = 6x - 12 = 0 \implies x = 2$
* $f''(x) = 6$ (Positive, indicates a minimum)
* **Local Minimum:** $(2, -5)$

---

## 7. Logic & Series
* Time for bicycle to hit wall: $t = \frac{10 \text{ m}}{1 \text{ m/s}} = 10 \text{ s}$
* Fly's constant speed: $v_f = 2 \text{ m/s}$
* Total distance: $d = v_f \cdot t = 20 \text{ m}$

---

## 8. Definite Integrals
Area $A = \int_0^\pi \sin(x) dx$:
* $A = [-\cos(x)]_0^\pi = -(-1) - (-1) = 2$

---

## 9. Optimization Problem
Area $A = x(3 - x^2) = 3x - x^3$
* $\frac{dA}{dx} = 3 - 3x^2 = 0 \implies x = 1$
* $y = 3 - (1)^2 = 2$
* **Dimensions:** $1 \times 2$

---

## 10. Infinite Series
* **X-coordinate:** $1 - 1/3 + 1/5 - \dots = \frac{\pi}{4}$
* **Y-coordinate:** $1/2 - 1/4 + 1/6 - \dots = \frac{\ln(2)}{2}$
* **Final Position:** $(\frac{\pi}{4}, \frac{\ln(2)}{2})$