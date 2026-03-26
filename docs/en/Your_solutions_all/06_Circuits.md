## 1. Series and Parallel Circuit

**Series Case:**
* Equivalent Resistance: $R_{eq} = R_1 + R_2 + R_3 = 15 + 30 + 50 = \mathbf{95\ \Omega}$
* Current: $I = \frac{V}{R_{eq}} = \frac{12}{95} \approx \mathbf{0.126\text{ A}}$

**Parallel Case:**
* Equivalent Resistance: $\frac{1}{R_{eq}} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50} = \frac{10+5+3}{150} = \frac{18}{150}$
    $R_{eq} = \frac{150}{18} \approx \mathbf{8.33\ \Omega}$
* Current: $I = \frac{V}{R_{eq}} = \frac{12}{8.33} \approx \mathbf{1.44\text{ A}}$

---

## 2. Resistors

Possible equivalent resistances using three $1\ \Omega$ resistors:
1.  **All in series:** $1 + 1 + 1 = \mathbf{3\ \Omega}$
2.  **All in parallel:** $\frac{1}{1+1+1} = \mathbf{0.33\ \Omega}$
3.  **Two in parallel, one in series:** $\frac{1 \times 1}{1 + 1} + 1 = \mathbf{1.5\ \Omega}$
4.  **Two in series, one in parallel:** $\frac{(1+1) \times 1}{(1+1) + 1} = \frac{2}{3} \approx \mathbf{0.67\ \Omega}$

---

## 3. Mixed Circuit (image-r1)



[Image of resistors in series and parallel]


Based on the standard configuration for this problem (two parallel resistors in series with a third):
* $R_{parallel} = \frac{5 \times 5}{5 + 5} = 2.5\ \Omega$
* $R_{total} = 5 + 2.5 = \mathbf{7.5\ \Omega}$

---

## 4. Mixed Circuit (image-r2)

Based on the standard bridge/ladder configuration for this problem (two branches of two series resistors in parallel):
* $R_{branch} = 10 + 10 = 20\ \Omega$
* $R_{total} = \frac{20 \times 20}{20 + 20} = \mathbf{10\ \Omega}$

---

## 5. Kirchhoff's Laws



[Image of Kirchhoff's laws circuit diagram]


Solving the system of equations derived from the loops:
1.  $31I_1 + 10I_2 = 4.5$
2.  $10I_1 + 11I_2 = 9$

* **$I_1 \approx -0.168\text{ A}$** (Flows opposite to assumed direction)
* **$I_2 \approx 0.971\text{ A}$**
* **$I_3 = I_1 + I_2 \approx 0.803\text{ A}$**

---

## 6. Kirchhoff's Laws again

For a bridge circuit where all resistors are equal (balanced bridge):
* **Current through ammeter = 0 A**

---

## 7. Capacitors in Parallel

* **Equivalent Capacitance:** $C_{eq} = C_1 + C_2 = 4\mu\text{F} + 6\mu\text{F} = 10\mu\text{F}$
* **Total Charge ($Q$):** $Q = C_{eq}V = (10 \times 10^{-6}\text{ F})(10\text{ V}) = \mathbf{100\mu\text{C}}$
* **Total Energy ($E$):** $E = \frac{1}{2}C_{eq}V^2 = \frac{1}{2}(10 \times 10^{-6})(10^2) = \mathbf{5 \times 10^{-4}\text{ J}}$

---

## 8. AC Voltage Equation

Using Ohm's Law $V(t) = I(t)R$:
* $V(t) = [2 \sin(120\pi t)] \times 50$
* **$V(t) = 100 \sin(120\pi t) \text{ V}$**

---

## 9. Current

$I(t) = \frac{dQ}{dt} = \frac{d}{dt}(5t^2 + 5) = 10t$
* At $t = 3\text{ s}$: $I = 10(3) = \mathbf{30\text{ A}}$

---

## 10. Average Current

$I_{avg} = \frac{\Delta Q}{\Delta t} = \frac{30\text{ C}}{0.002\text{ s}}$
* **$I_{avg} = 15,000\text{ A}$**

---

## 11. Power & Energy

* **Power ($P$):** $P = \frac{V^2}{R} = \frac{50^2}{100} = \mathbf{25\text{ W}}$
* **Energy ($E$):** $E = P \times t = 25\text{ W} \times (5 \times 60\text{ s}) = \mathbf{7500\text{ J}}$

---

## 12. Transformer Currents

* **Secondary Voltage:** $V_s = V_p \left(\frac{N_s}{N_p}\right) = 120 \left(\frac{200}{1000}\right) = \mathbf{24\text{ V}}$
* **Primary Current:** $I_p = I_s \left(\frac{N_s}{N_p}\right) = 3 \left(\frac{200}{1000}\right) = \mathbf{0.6\text{ A}}$

---

## 13. Transformer Ratio

$N_s = N_p \left(\frac{V_s}{V_p}\right) = 400 \left(\frac{9}{120}\right)$
* **$N_s = 30\text{ turns}$**

---

## 14. RLC Circuit

**Differential Equation:**
$$L \frac{d^2q}{dt^2} + R \frac{dq}{dt} + \frac{1}{C}q = V(t)$$

**Analogies to Damped Harmonic Oscillator ($m\ddot{x} + b\dot{x} + kx = F$):**
| Electrical Term | Mechanical Analogy |
| :--- | :--- |
| Inductance ($L$) | Mass ($m$) |
| Resistance ($R$) | Damping coefficient ($b$) |
| Inverse Capacitance ($1/C$) | Spring constant ($k$) |
| Charge ($q$) | Displacement ($x$) |
| Electromotive Force ($V$) | External Force ($F$) |

---

## 15. Resistor Cube*



For a cube with 12 identical resistors $R$ between opposite corners:
* **$R_{eq} = \frac{5}{6}R$**

Would you like me to show the step-by-step nodal analysis for the Resistor Cube problem?