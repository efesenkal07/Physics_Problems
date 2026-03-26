## 1. Gauss's Law

The total electric flux $\Phi_E$ through a closed surface is given by Gauss's Law:
$$\Phi_E = \frac{Q_{encl}}{\epsilon_0}$$
Given $Q = +2 \text{ C}$ and $\epsilon_0 \approx 8.854 \times 10^{-12} \text{ F/m}$:
$$\Phi_E = \frac{2}{8.854 \times 10^{-12}}$$

**Result:** $\Phi_E \approx 2.26 \times 10^{11} \text{ V}\cdot\text{m}$

---

## 2. Ampere's Law

The distance to the midpoint is $r = 0.05 \text{ m}$. Both wires produce a magnetic field in the same direction at the midpoint (use the right-hand rule).
$$B_{total} = B_1 + B_2 = 2 \times \frac{\mu_0 I}{2 \pi r} = \frac{\mu_0 I}{\pi r}$$
$$B_{total} = \frac{(4\pi \times 10^{-7})(5)}{\pi (0.05)} = \frac{20 \times 10^{-7}}{0.05}$$

**Result:** $B = 4.0 \times 10^{-5} \text{ T}$ (Direction is perpendicular to the plane containing the wires).

---

## 3. Biot-Savart Law

For a short segment perpendicular to the line to point $P$ ($\theta = 90^\circ$):
$$dB = \frac{\mu_0}{4 \pi} \frac{I \cdot dL \cdot \sin \theta}{r^2}$$
$$dB = (10^{-7}) \frac{(3)(0.1)(1)}{(0.2)^2} = 10^{-7} \frac{0.3}{0.04}$$

**Result:** $B = 7.5 \times 10^{-7} \text{ T}$

---

## 4. Magnetic Torque

The torque $\tau$ on a current loop in a magnetic field parallel to its plane ($\theta = 90^\circ$ between the normal and $B$):
$$\tau = I A B \sin \theta$$
Area $A = 0.10 \text{ m} \times 0.05 \text{ m} = 0.005 \text{ m}^2$
$$\tau = (2 \text{ A})(0.005 \text{ m}^2)(0.3 \text{ T})(1)$$

**Result:** $\tau = 0.003 \text{ N}\cdot\text{m}$

---

## 5. Energy Stored by charge in a capacitor

**1. Capacitance ($C$):**
$$C = \epsilon_0 \frac{S}{d} = (8.854 \times 10^{-12}) \frac{0.02}{0.005} = (8.854 \times 10^{-12})(4)$$
**Result:** $C \approx 3.54 \times 10^{-11} \text{ F}$ (or $35.4 \text{ pF}$)

**2. Stored Energy ($U$):**
$$U_{energy} = \frac{1}{2} C U^2 = \frac{1}{2} (3.54 \times 10^{-11})(500)^2$$
**Result:** $U_{energy} \approx 4.43 \times 10^{-6} \text{ J}$

**3. Electric Field Intensity ($E$):**
$$E = \frac{U}{d} = \frac{500}{0.005}$$
**Result:** $E = 1.0 \times 10^5 \text{ V/m}$

**4. Force of Attraction ($F$):**
$$F = \frac{1}{2} \epsilon_0 E^2 S = \frac{1}{2} (8.854 \times 10^{-12})(10^5)^2(0.02)$$
**Result:** $F \approx 8.85 \times 10^{-4} \text{ N}$

---

## 6. EM Wave Analysis

From $E_y(x,t) = 100 \sin(10^7 x - \omega t)$:
* **Direction:** Positive x-direction (due to the $- \omega t$ term).
* **Wavelength ($\lambda$):** $k = 10^7 \text{ m}^{-1} \implies \lambda = \frac{2\pi}{k} = \frac{2\pi}{10^7} \approx \mathbf{6.28 \times 10^{-7} \text{ m}}$.
* **Angular Frequency ($\omega$):** $\omega = c k = (3 \times 10^8)(10^7) = \mathbf{3 \times 10^{15} \text{ rad/s}}$.
* **Magnetic Field ($B_z$):** $B_0 = \frac{E_0}{c} = \frac{100}{3 \times 10^8} \approx 3.33 \times 10^{-7} \text{ T}$.
  $$B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T}$$

---

## 7. Wavelength and Frequency

* **Color:** $550 \text{ nm}$ corresponds to **Green**.
* **Frequency ($f$):** $f = \frac{c}{\lambda} = \frac{3 \times 10^8}{550 \times 10^{-9}}$
**Result:** $f \approx 5.45 \times 10^{14} \text{ Hz}$

---

## 8. EM Spectrum

Order of increasing wavelength (shortest to longest):
1. **Gamma rays**
2. **X-rays**
3. **Ultraviolet**
4. **Infrared**
5. **Microwaves**
6. **Radio waves**

---

## 9. Refraction (Snell's Law)

$$n_1 \sin \theta_1 = n_2 \sin \theta_2$$
$$(1.00) \sin(30^\circ) = (1.50) \sin \theta_2$$
$$0.5 = 1.50 \sin \theta_2 \implies \sin \theta_2 = \frac{1}{3}$$
$$\theta_2 = \arcsin(0.333)$$

**Result:** $\theta_2 \approx 19.47^\circ$

---

## 10. Speed of Light in Media

$$v = \frac{c}{n} = \frac{3.00 \times 10^8 \text{ m/s}}{2.42}$$

**Result:** $v \approx 1.24 \times 10^8 \text{ m/s}$

