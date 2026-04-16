# Section 3: Waves — Solutions

---

## 1. Wave Properties

Given:

$$
f = 440 \,\text{Hz}, \quad v_{\text{air}} = 343 \,\text{m/s}, \quad v_{\text{water}} = 1482 \,\text{m/s}
$$

Wave relation:

$$
v = f\lambda
$$

Wavelength:

$$
\lambda = \frac{v}{f}
$$

In air:

$$
\lambda_{\text{air}} = \frac{343}{440} \approx 0.78 \,\text{m}
$$

In water:

$$
\lambda_{\text{water}} = \frac{1482}{440} \approx 3.37 \,\text{m}
$$

---

## 2. String Harmonics

Given:

$$
L = 0.64 \,\text{m}, \quad f = 330 \,\text{Hz}
$$

Fundamental mode:

$$
\lambda = 2L = 1.28 \,\text{m}
$$

Wave speed:

$$
v = f\lambda = 330 \cdot 1.28 = 422.4 \,\text{m/s}
$$

---

## 3. Superposition Principle

Given:

$$
y_1 = A\sin(kx - \omega t), \quad y_2 = A\sin(kx + \omega t)
$$

Using identity:

$$
\sin a + \sin b = 2\sin\left(\frac{a+b}{2}\right)\cos\left(\frac{a-b}{2}\right)
$$

Resulting wave:

$$
y = 2A \sin(kx)\cos(\omega t)
$$

Nodes:

$$
\sin(kx) = 0 \Rightarrow kx = n\pi \Rightarrow x = \frac{n\lambda}{2}
$$

---

## 4. Phase Difference

$$
\Delta x = \frac{\lambda}{3}
$$

$$
\Delta \phi = \frac{2\pi}{\lambda}\Delta x = \frac{2\pi}{\lambda} \cdot \frac{\lambda}{3} = \frac{2\pi}{3}
$$

---

## 5. Echo Ranging

Given:

$$
t = 1 \,\text{s}, \quad v = 343 \,\text{m/s}
$$

Total distance:

$$
d = vt = 343 \,\text{m}
$$

Distance to cliff:

$$
d = \frac{343}{2} = 171.5 \,\text{m}
$$

---

## 6. Wave Equation Analysis

Given:

$$
y(x,t) = 0.05 \sin(2\pi x - 50\pi t)
$$

Compare with:

$$
y = A \sin(kx - \omega t)
$$

Amplitude:

$$
A = 0.05
$$

Wave number:

$$
k = 2\pi \Rightarrow \lambda = \frac{2\pi}{k} = 1 \,\text{m}
$$

Angular frequency:

$$
\omega = 50\pi \Rightarrow f = \frac{\omega}{2\pi} = 25 \,\text{Hz}
$$

Wave speed:

$$
v = f\lambda = 25 \cdot 1 = 25 \,\text{m/s}
$$

---

## 7. Standing Wave Modes

Given:

$$
L = 0.80 \,\text{m}, \quad n = 4
$$

Relation:

$$
L = \frac{n\lambda}{2}
$$

Solve:

$$
0.80 = \frac{4\lambda}{2} \Rightarrow \lambda = 0.40 \,\text{m}
$$

---

## 8. Traveling Wave Condition

Wave equation:

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

Check forms:

- $y = A\cos(kx^2 - \omega t)$ ❌  
- $y = A(x - vt)^2$ ❌  
- $y = A\log(x + vt)$ ✅  

Valid form:

$$
y(x,t) = f(x \pm vt)
$$

---

## 9. Damped Oscillator

Equation:

$$
m\ddot{x} + b\dot{x} + kx = 0
$$

Characteristic equation:

$$
mr^2 + br + k = 0
$$

Solution:

$$
r = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

Cases:

**Underdamped** ($b^2 < 4mk$):

$$
x(t) = e^{-\frac{b}{2m}t}(A\cos \omega t + B\sin \omega t)
$$

**Critically damped** ($b^2 = 4mk$):

$$
x(t) = (A + Bt)e^{-\frac{b}{2m}t}
$$

**Overdamped** ($b^2 > 4mk$):

$$
x(t) = A e^{r_1 t} + B e^{r_2 t}
$$

---

## 10. Wave Sources

$$
u(\vec{r},t) = \frac{A}{|\vec{r} - \vec{r_0}|^\alpha} \sin(k|\vec{r} - \vec{r_0}| - \omega t)
$$

Superposition:

$$
u_{\text{total}} = \sum_i u_i
$$

---

## 11. Two-Slit Interference

$$
u(\vec{r},t) = \frac{A}{|\vec{r} - \vec{r_1}|} \sin(k|\vec{r} - \vec{r_1}| - \omega t)
+ \frac{A}{|\vec{r} - \vec{r_2}|} \sin(k|\vec{r} - \vec{r_2}| - \omega t)
$$

Interference conditions:

Constructive:

$$
\Delta r = n\lambda
$$

Destructive:

$$
\Delta r = \left(n + \frac{1}{2}\right)\lambda
$$