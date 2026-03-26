# Section 2: Mechanics II - Solutions

---

## 1. Gravitational Dependence
* **Moon Period:** Using $T = 2\pi\sqrt{\frac{L}{g}}$, the period is inversely proportional to the square root of $g$.
    $T_{Moon} = T_{Earth} \cdot \sqrt{\frac{g_{Earth}}{g_{Moon}}} = 4 \cdot \sqrt{6} \approx 9.80 \, \text{s}$.
* **Required Length on Earth:**
    $1 = 2\pi\sqrt{\frac{L}{9.81}} \implies L = \frac{9.81}{4\pi^2} \approx 0.248 \, \text{m}$.

## 2. Harmonic Motion
* **Spring Constant ($k$):**
    From $x(t) = 0.2 \cos(10\pi t)$, $\omega = 10\pi$.
    $k = m\omega^2 = 10 \cdot (10\pi)^2 = 1000\pi^2 \approx 9869.6 \, \text{N/m}$.
* **Total Mechanical Energy ($E$):**
    $E = \frac{1}{2}kA^2 = \frac{1}{2}(1000\pi^2)(0.2)^2 = 20\pi^2 \approx 197.4 \, \text{J}$.

## 3. Conservation of Energy
* **Height ($h$):** $h = L(1 - \cos\theta) = 1.0(1 - \cos 15^\circ) \approx 0.034 \, \text{m}$.
* **Speed ($v$):**
    $mgh = \frac{1}{2}mv^2 \implies v = \sqrt{2gh} = \sqrt{2 \cdot 9.81 \cdot 0.034} \approx 0.817 \, \text{m/s}$.

## 4. Energy & Momentum
* **Speed at Bottom ($v_1$):** $v_1 = \sqrt{2gh} = \sqrt{2 \cdot 9.81 \cdot 3.0} \approx 7.67 \, \text{m/s}$.
* **Speed After Collision ($v_f$):**
    $m_1v_1 = (m_1 + m_2)v_f \implies 0.5 \cdot 7.67 = (2.0)v_f \implies v_f \approx 1.92 \, \text{m/s}$.

## 5. Inelastic Collision
* **Final Speed:** $m_1v_1 = (m_1 + m_2)v_f \implies 70 \cdot 3 = (210)v_f \implies v_f = 1.0 \, \text{m/s}$.
* **Energy Conservation:** No, kinetic energy is not conserved.
    $KE_{initial} = 315 \, \text{J}$, $KE_{final} = 105 \, \text{J}$. The "lost" energy is converted into heat and internal deformation.

## 6. Energy Dissipation
* **First Bounce:** $h_1 = 0.70 \cdot h_0 = 1.4 \, \text{m}$.
* **Second Bounce:** $h_2 = 0.70 \cdot h_1 = 0.70 \cdot 1.4 = 0.98 \, \text{m}$.

## 7. Dynamics with Friction
* **Friction Top ($f_1$):** $\mu m_1 g = 0.2 \cdot 5 \cdot 9.81 = 9.81 \, \text{N}$.
* **Friction Bottom ($f_2$):** $\mu (m_1 + m_2)g = 0.2 \cdot 15 \cdot 9.81 = 29.43 \, \text{N}$.
* **Acceleration ($a$):**
    $F_{net} = F - f_1 - f_2 = 45 - 9.81 - 29.43 = 5.76 \, \text{N}$.
    $a = \frac{F_{net}}{m_{bottom}} = \frac{5.76}{10} = 0.576 \, \text{m/s}^2$.

## 8. Work of a Variable Force
* **Equation of Motion:** $m\frac{d^2x}{dt^2} = -kx \implies x(t) = A\cos(\omega t + \phi)$ where $\omega = \sqrt{k/m}$.
* **Work:** $W = \int_{0}^{x_0} -kx dx = -\frac{1}{2}kx_0^2$.
* **Interpretation:** $U(x) = \frac{1}{2}kx^2$ (Elastic Potential Energy).
* **Relationship:** $F = -\frac{dU}{dx} = -\frac{d}{dx}(\frac{1}{2}kx^2) = -kx$. Verified.

## 9. Vertical Throw with Drag
* **Analytical Solution:** $v(t) = (v_0 + \frac{mg}{k})e^{-kt/m} - \frac{mg}{k}$.
    $x(t) = 10 + \frac{m}{k}(v_0 + \frac{mg}{k})(1 - e^{-kt/m}) - \frac{mgt}{k}$.
* **Max Height:** Set $v(t) = 0$ to find $t_{max}$, then substitute into $x(t)$.
* **Comparison:** Drag reduces the maximum height and the time to reach it compared to the vacuum case.

## 10. Force Field and Power ($m=0.5 \, \text{kg}$)
* **Velocity ($\vec{v}$):** $(10t-1, 6t^2, -3)$.
* **Momentum ($\vec{p}$):** $(5t-0.5, 3t^2, -1.5)$.
* **Acceleration ($\vec{a}$):** $(10, 12t, 0)$.
* **Force ($\vec{F}$):** $(5, 6t, 0)$.
* **Power ($P = \vec{F} \cdot \vec{v}$):** $5(10t-1) + (6t)(6t^2) + 0 = 36t^3 + 50t - 5$.

## 11. Dynamics with a Time-Dependent Force ($m=3 \, \text{kg}$)
* **Acceleration ($\vec{a}$):** $(5t, t-4, -2t^2)$.
* **Velocity ($\vec{v}(t)$):** $(\frac{5}{2}t^2+2, \frac{1}{2}t^2-4t, -\frac{2}{3}t^3+1)$.
* **Position ($\vec{r}(t)$):** $(\frac{5}{6}t^3+2t+5, \frac{1}{6}t^3-2t^2+2, -\frac{1}{6}t^4+t-3)$.

## 12. Work and Energy Constant Force ($m=2 \, \text{kg}$)
* **Vectors:**
    * $\vec{a}(t) = (3, 1)$.
    * $\vec{v}(t) = (3t+1, t-1)$.
    * $\vec{r}(t) = (\frac{3}{2}t^2+t, \frac{1}{2}t^2-t)$.
* **Work at $t=3 \, \text{s}$:**
    $\vec{r}(3) = (16.5, 1.5)$.
    $W = \vec{F} \cdot \vec{r}(3) = (6 \cdot 16.5) + (2 \cdot 1.5) = 99 + 3 = 102 \, \text{J}$.
* **Consistency:** $v(0) = \sqrt{2}$, $v(3) = \sqrt{10^2 + 2^2} = \sqrt{104}$.
    $\Delta KE = \frac{1}{2}(2)(104 - 2) = 102 \, \text{J}$. Consistent.

---

Would you like me to prepare the Python or HTML simulation code for Task 9 or Task 12 to secure those extra quality points?