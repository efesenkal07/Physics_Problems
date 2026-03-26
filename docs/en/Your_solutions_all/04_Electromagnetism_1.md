## 1. Coulomb's Law

The distance from any corner to the center of a square with side $s=1.0\text{ m}$ is:
$$r = \frac{\sqrt{s^2 + s^2}}{2} = \frac{\sqrt{2}}{2} \approx 0.707 \text{ m}$$

Due to symmetry, the force vectors from charges at opposite corners are equal in magnitude and opposite in direction:
$$\vec{F}_{net} = \vec{F}_1 + \vec{F}_2 + \vec{F}_3 + \vec{F}_4 = 0$$

**Result:** The magnitude of the electric force is **0 N**.

---

## 2. Electric Potential

The electric potential $V$ at the center is the sum of potentials from each charge $q_i$:
$$V = \sum \frac{k q_i}{r} = \frac{k}{r} \sum q_i$$
Given $q_1 = 1\text{C}, q_2 = -2\text{C}, q_3 = 3\text{C}, q_4 = -4\text{C}$ and $r = \frac{\sqrt{2}}{2} \text{ m}$:
$$\sum q = 1 - 2 + 3 - 4 = -2 \text{ C}$$
$$V = \frac{8.99 \times 10^9}{\sqrt{2}/2} \times (-2) = \frac{-17.98 \times 10^9}{0.707}$$

**Result:** $V \approx -2.54 \times 10^{10} \text{ V}$

---

## 3. Electrostatic Equilibrium

Let $x$ be the distance from $q_1 = +4\text{C}$ to $q_3$. The distance from $q_3$ to $q_2 = +9\text{C}$ is $(2 - x)$.
At equilibrium, the net force on $q_3$ is zero:
$$\frac{k q_1 q_3}{x^2} = \frac{k q_2 q_3}{(2-x)^2} \implies \frac{4}{x^2} = \frac{9}{(2-x)^2}$$
Taking the square root of both sides:
$$\frac{2}{x} = \frac{3}{2-x} \implies 4 - 2x = 3x \implies 5x = 4$$

**Result:** $x = 0.8 \text{ m}$ from the $+4\text{C}$ charge.

---

## 4. Force Comparison

**Electric Force ($F_e$):**
$$F_e = \frac{k e^2}{r^2} = \frac{(8.99 \times 10^9)(1.6 \times 10^{-19})^2}{(5.3 \times 10^{-11})^2} \approx 8.2 \times 10^{-8} \text{ N}$$

**Gravitational Force ($F_g$):**
$$F_g = \frac{G m_e m_p}{r^2} = \frac{(6.67 \times 10^{-11})(9.11 \times 10^{-31})(1.67 \times 10^{-27})}{(5.3 \times 10^{-11})^2} \approx 3.6 \times 10^{-47} \text{ N}$$

**Ratio:**
$$\frac{F_e}{F_g} = \frac{k e^2}{G m_e m_p} \approx 2.27 \times 10^{39}$$

---

## 5. Field Levitation

For levitation, the electric force must balance the gravitational force:
$$F_e = F_g \implies qE = mg$$
$$E = \frac{m_p g}{e} = \frac{(1.67 \times 10^{-27} \text{ kg})(9.8 \text{ m/s}^2)}{1.6 \times 10^{-19} \text{ C}}$$

**Result:** $E \approx 1.02 \times 10^{-7} \text{ V/m}$ (upward).

---

## 6. Field at a point from a system of charges

**1. General Field Vector $\vec{E}(x, y)$:**
$$\vec{E}(x, y) = \frac{kq[(x+a)\hat{i} + y\hat{j}]}{((x+a)^2 + y^2)^{3/2}} + \frac{2kq[(x-a)\hat{i} + y\hat{j}]}{((x-a)^2 + y^2)^{3/2}}$$
* **$\vec{E}(0, y)$:** $\frac{kq(a\hat{i} + y\hat{j})}{(a^2 + y^2)^{3/2}} + \frac{2kq(-a\hat{i} + y\hat{j})}{(a^2 + y^2)^{3/2}} = \frac{kq}{(a^2+y^2)^{3/2}} [-a\hat{i} + 3y\hat{j}]$
* **$\vec{E}(x, 0)$:** $\frac{kq(x+a)\hat{i}}{|x+a|^3} + \frac{2kq(x-a)\hat{i}}{|x-a|^3}$

**2. Condition for $\vec{E} = 0$:**
Occurs on the x-axis between the charges. Setting $E_x = 0$ for $-a < x < a$:
$$\frac{1}{(x+a)^2} = \frac{2}{(a-x)^2} \implies a-x = \sqrt{2}(x+a) \implies x = a\frac{1-\sqrt{2}}{1+\sqrt{2}} \approx -0.17a$$

**3. Calculation ($a=0.2, y=0.3, q=2\mu\text{C}$):**
$r = \sqrt{0.2^2 + 0.3^2} = \sqrt{0.13} \approx 0.36 \text{ m}$
$$E_x = \frac{k q (-a)}{r^3} = \frac{(9 \times 10^9)(2 \times 10^{-6})(-0.2)}{(0.13)^{3/2}} \approx -7.68 \times 10^4 \text{ V/m}$$
$$E_y = \frac{3 k q y}{r^3} = \frac{3(9 \times 10^9)(2 \times 10^{-6})(0.3)}{(0.13)^{3/2}} \approx 3.46 \times 10^5 \text{ V/m}$$

**4. Limit $y \gg a$:**
The system acts as a single point charge of $+3q$:
$$\vec{E} \approx \frac{k(3q)}{y^2}\hat{j}$$

---

## 7. Cyclotron Motion

**Velocity $v$:**
$$\frac{1}{2}mv^2 = eV \implies v = \sqrt{\frac{2eV}{m}}$$
**Radius $r$:**
$$r = \frac{mv}{eB} = \frac{m}{eB}\sqrt{\frac{2eV}{m}} = \frac{1}{B}\sqrt{\frac{2mV}{e}}$$
$$r = \frac{1}{0.1}\sqrt{\frac{2(9.11 \times 10^{-31})(5000)}{1.6 \times 10^{-19}}} \approx \frac{1}{0.1}\sqrt{5.69 \times 10^{-8}}$$

**Result:** $r \approx 0.0238 \text{ m} = 2.38 \text{ cm}$

---

## 8. Lorentz Force

Since $\vec{v} \perp \vec{B}$:
$$F = qvB = (2 \times 10^{-19} \text{ C})(10^6 \text{ m/s})(0.5 \text{ T})$$

**Result:** $F = 1.0 \times 10^{-13} \text{ N}$

---

## 9. Vector Lorentz Force

$$\vec{v} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{vmatrix} = \hat{i}(4-2) - \hat{j}(-2-1) + \hat{k}(4+4) = (2\hat{i} + 3\hat{j} + 8\hat{k})$$
Magnitude $|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2} = \sqrt{4+9+64} = \sqrt{77} \approx 8.775$
$$F = q |\vec{v} \times \vec{B}| = (1.6 \times 10^{-19})(8.775)$$

**Result:** $F \approx 1.40 \times 10^{-18} \text{ N}$

---

## 10. Lorentz Force acting on Wire

Formula: $F = ILB\sin\theta$
Given: $I = 10 \text{ A}, L = 2.0 \text{ m}, B = 0.5 \text{ T} \implies ILB = 10 \text{ N}$

* **a) $90^\circ$:** $F = 10 \sin(90^\circ) = \mathbf{10 \text{ N}}$
* **b) $45^\circ$:** $F = 10 \sin(45^\circ) = \mathbf{7.07 \text{ N}}$
* **c) $0^\circ$:** $F = 10 \sin(0^\circ) = \mathbf{0 \text{ N}}$

