Tamamdır Emre, doğrudan kopyalayıp GitHub repo'na (README.md dosyasına) yapıştırabileceğin, eğitmenin beklediği "adım adım ve gerekçeli" formatta hazırladığım çözümler aşağıdadır. 

[cite_start]Bu belge, ders kurallarına uygun olarak yapay zeka desteğiyle hazırlanmış profesyonel bir dijital dökümandır[cite: 92, 93, 111].

---

# Section 1: Mechanics I - Solutions

## 1. Projectile Motion
**Given:** $v_0 = 100 \, \text{m/s}$, $\theta = 37^\circ$, $g \approx 9.81 \, \text{m/s}^2$.

* **Differential Equations of Motion:**
    * Horizontal ($x$): $m \frac{d^2x}{dt^2} = 0 \implies \frac{d^2x}{dt^2} = 0$
    * Vertical ($y$): $m \frac{d^2y}{dt^2} = -mg \implies \frac{d^2y}{dt^2} = -g$
* **Time of Flight ($t_f$):**
    The object hits the ground when $y(t) = 0$.
    $$y(t) = v_0 \sin(\theta)t - \frac{1}{2}gt^2 = 0$$
    $$t_f = \frac{2v_0 \sin(\theta)}{g} = \frac{2 \cdot 100 \cdot \sin(37^\circ)}{9.81} \approx 12.27 \, \text{s}$$
* **Maximum Height ($H$):**
    Occurs when $v_y = 0$ (at $t = t_f / 2$).
    $$H = \frac{(v_0 \sin\theta)^2}{2g} = \frac{(100 \cdot 0.6018)^2}{19.62} \approx 184.6 \, \text{m}$$
* **Range ($R$):**
    $$R = v_x \cdot t_f = \frac{v_0^2 \sin(2\theta)}{g} = \frac{100^2 \cdot \sin(74^\circ)}{9.81} \approx 979.9 \, \text{m}$$

## 2. Range Optimization
**Goal:** Show that $R(\theta)$ is maximum at $45^\circ$.
The range equation is $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$. To find the maximum, we take the derivative with respect to $\theta$ and set it to zero:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot \cos(2\theta) \cdot 2 = 0$$
$$\cos(2\theta) = 0 \implies 2\theta = 90^\circ \implies \theta = 45^\circ$$

## 3. Path Intersection
Alice: $A(t) = (2+t, 8-3t)$ | Bob: $B(t) = (2t-1, 2t+2)$
* **Check for Collision:** Set $x_A(t) = x_B(t)$ and $y_A(t) = y_B(t)$ for the same $t$.
    1. $2 + t = 2t - 1 \implies t = 3$
    2. Test $t=3$ in $y$ coordinates:
       $y_A(3) = 8 - 3(3) = -1$
       $y_B(3) = 2(3) + 2 = 8$
    Since $-1 \neq 8$, they **do not collide**.
* **Minimum Distance:** Calculate the distance function $D(t) = \sqrt{(x_B-x_A)^2 + (y_B-y_A)^2}$ and find its minimum by deriving $D^2(t)$.

## 4. Vector Calculus
$\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$
* **Velocity Vector:** $\vec{v}(t) = \frac{d\vec{r}}{dt} = (6t)\hat{i} + (5 - 16t)\hat{j}$
* **Acceleration Vector:** $\vec{a}(t) = \frac{d\vec{v}}{dt} = 6\hat{i} - 16\hat{j}$

## 5. Relative Velocity
River $v_r = 2 \, \text{m/s}$ (East), Boat $v_b = 5 \, \text{m/s}$ (relative to water).
* **Heading Angle:** To move directly North, the horizontal component of the boat's velocity must cancel the river's flow.
    $$\sin(\theta) = \frac{v_{river}}{v_{boat}} = \frac{2}{5} \implies \theta = \arcsin(0.4) \approx 23.58^\circ \text{ (West of North)}$$
* **Crossing Time:** The velocity relative to the ground is $v_g = \sqrt{5^2 - 2^2} = \sqrt{21} \approx 4.58 \, \text{m/s}$.
    $$t = \frac{\text{width}}{v_g} = \frac{200}{\sqrt{21}} \approx 43.64 \, \text{s}$$

## 6. Variable Velocity
$v(t) = t^2 + 2t - 5$, $x(0) = 4$.
* **Position at $t=3$:**
    $$x(t) = \int (t^2 + 2t - 5) dt = \frac{1}{3}t^3 + t^2 - 5t + C$$
    Using $x(0)=4 \implies C=4$.
    $$x(3) = \frac{1}{3}(27) + 9 - 15 + 4 = 9 + 9 - 15 + 4 = 7$$
* **Acceleration at $t=3$:**
    $$a(t) = \frac{dv}{dt} = 2t + 2 \implies a(3) = 2(3) + 2 = 8 \, \text{m/s}^2$$

## 7. Elimination of Time
$x(t) = 2t^2 \implies t = \sqrt{x/2}$
* **Trajectory Equation:** $y = 3(\sqrt{x/2})^3 = \frac{3}{2\sqrt{2}}x^{1.5}$
* **Acceleration:** $\vec{a}(t) = \frac{d^2}{dt^2}(2t^2, 3t^3) = (4, 18t)$.
    The acceleration is **not constant** because the y-component depends on $t$.

## 8. Circular Motion
$R = 6378 \, \text{km} = 6,378,000 \, \text{m}$. $T = 24 \times 3600 \, \text{s}$.
$$a_c = \frac{v^2}{R} = \omega^2 R = \left(\frac{2\pi}{T}\right)^2 R \approx 0.034 \, \text{m/s}^2$$

## 9. Momentum Comparison
$p = m \cdot v$
* Fly: $0.002 \, \text{kg} \cdot 10 \, \text{m/s} = 0.02 \, \text{kg}\cdot\text{m/s}$
* Tennis Ball: $0.060 \, \text{kg} \cdot 1 \, \text{m/s} = 0.06 \, \text{kg}\cdot\text{m/s}$
The **tennis ball** has greater momentum.

## 10. Kinematics (Elliptical Helix)
$\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)$
* **Trajectory:** The $x$ and $y$ components satisfy $(\frac{x}{a})^2 + (\frac{y}{b})^2 = 1$, which is an ellipse. Combined with $z = bt$, the trajectory is an **Elliptical Helix**.
* **Path Length ($L$):**
    $$L = \int_{0}^{t_0} |\vec{v}(t)| dt = \int_{0}^{t_0} \sqrt{(-a\omega \sin \omega t)^2 + (b\omega \cos \omega t)^2 + b^2} dt$$

---

Bu dosyayı `Section_1_Mechanics.md` adıyla kaydedip repo'na ekleyebilirsin. [cite_start]Derste bu dosyayı açıp ekran paylaştığında, hem tüm adımlar görünecek hem de profesyonel bir sunum yapmış olacaksın[cite: 97, 99].

Bunun dışında **List 02 (Dinamik)** veya bir sonraki haftanın konusu olan **Enerji ve İş** için de benzer bir döküman hazırlamamı ister misin?