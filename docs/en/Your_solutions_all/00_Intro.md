```python
import numpy as np
from sympy import *

a = np.array([2, 1, -3])
b = np.array([4, -2, 1])

# 1
mag_a = np.linalg.norm(a)
mag_b = np.linalg.norm(b)
dot_ab = np.dot(a, b)
cross_ab = np.cross(a, b)
angle = np.arccos(dot_ab / (mag_a * mag_b))
print("1a", mag_a, mag_b, np.sqrt(14), np.sqrt(21))
print("1b", dot_ab)
print("1c", cross_ab)
print("1d", np.degrees(angle))

# 10
# sum( (-1)^n / (2n+1) )
n = Symbol('n')
x = Sum((-1)**n / (2*n + 1), (n, 0, oo)).doit()
y = Sum((-1)**n / (2*n + 2), (n, 0, oo)).doit()
print("10x", x)
print("10y", y)



```

```text
1a 3.7416573867739413 4.58257569495584 3.7416573867739413 4.58257569495584
1b 3
1c [ -5 -14  -8]
1d 79.92346287144585
10x pi/4
10y log(2)/2


```

Here are the step-by-step solutions to each of the problems:

## 1. Vector Algebra

a) **Magnitude of each vector:**
The magnitude is found using the formula $|\vec{v}| = \sqrt{x^2 + y^2 + z^2}$.

* $|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}$
* $|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$

b) **The dot product:**


$$\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3$$

c) **The cross product:**


$$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix} = \mathbf{i}(1 - 6) - \mathbf{j}(2 - (-12)) + \mathbf{k}(-4 - 4)$$

$$\vec{a} \times \vec{b} = [-5, -14, -8]$$

d) **The angle between the vectors:**
Using the dot product formula $\vec{a} \cdot \vec{b} = |\vec{a}||\vec{b}|\cos\theta$:


$$\cos\theta = \frac{3}{\sqrt{14}\sqrt{21}} = \frac{3}{7\sqrt{6}}$$

$$\theta = \arccos\left(\frac{3}{7\sqrt{6}}\right) \approx 79.9^\circ$$

## 2. Systems of Equations

Given the equations:

1. $2x + 3y = 12$
2. $x - y = 1$

From the second equation, we can isolate $x$:


$$x = y + 1$$

Substitute this into the first equation:


$$2(y + 1) + 3y = 12$$

$$2y + 2 + 3y = 12$$

$$5y = 10 \implies y = 2$$

Substitute $y = 2$ back into the isolated equation for $x$:


$$x = 2 + 1 = 3$$


The solution is $x = 3$ and $y = 2$.

## 3. Proportionality

The initial formula is $F = G \frac{m_1 m_2}{r^2}$.
If the distance is doubled (becomes $2r$) and both masses are halved (become $m_1/2$ and $m_2/2$), the new force $F_{new}$ is:


$$F_{new} = G \frac{\left(\frac{m_1}{2}\right)\left(\frac{m_2}{2}\right)}{(2r)^2}$$

$$F_{new} = G \frac{\frac{m_1 m_2}{4}}{4r^2} = \frac{1}{16} \left( G \frac{m_1 m_2}{r^2} \right)$$


The force changes by a factor of 1/16 (it becomes 16 times weaker).

## 4. Rearranging Formulas

Given the formula:


$$T = 2\pi \sqrt{\frac{L}{g}}$$


Divide both sides by $2\pi$:


$$\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$$


Square both sides to remove the square root:


$$\frac{T^2}{4\pi^2} = \frac{L}{g}$$


Multiply both sides by $g$ and multiply by the reciprocal of the left side to solve for $g$:


$$g = \frac{4\pi^2 L}{T^2}$$

## 5. Trigonometry

The horizontal ($A_x$) and vertical ($A_y$) components are calculated using cosine and sine, respectively.

* **Horizontal:** $A_x = 15\cos(60^\circ) = 15 \times 0.5 = 7.5$
* **Vertical:** $A_y = 15\sin(60^\circ) = 15 \times \frac{\sqrt{3}}{2} = 7.5\sqrt{3} \approx 12.99$

## 6. Function Analysis

To find local maxima or minima for $f(x) = 3x^2 - 12x + 7$, first find the critical points by taking the derivative and setting it to zero:


$$f'(x) = 6x - 12 = 0 \implies 6x = 12 \implies x = 2$$


Next, take the second derivative to determine if it is a maximum or minimum:


$$f''(x) = 6$$


Since the second derivative is positive, the function is concave up at this point, indicating a local minimum.
Find the corresponding y-value:


$$f(2) = 3(2)^2 - 12(2) + 7 = 12 - 24 + 7 = -5$$


There is a local minimum at $(2, -5)$.

## 7. Logic & Series

This is a classic logic puzzle that tricks you into trying to calculate an infinite geometric series of back-and-forth bounces. Instead, look at the time involved!

* The bicycle is 10 meters away and travels at 1 m/s. It will take exactly 10 seconds to hit the wall.
* The fly is flying continuously at 2 m/s for those entire 10 seconds.
* Distance = speed $\times$ time = 2 m/s $\times$ 10 seconds = 20 meters.
The fly travels a total distance of 20 meters.

## 8. Definite Integrals

To calculate the area under the curve, we evaluate the definite integral of $\sin(x)$ from 0 to $\pi$:


$$\int_{0}^{\pi} \sin(x) \,dx = [-\cos(x)]_{0}^{\pi}$$


Evaluate at the limits:


$$= -\cos(\pi) - (-\cos(0))$$

$$= -(-1) - (-1) = 1 + 1 = 2$$


The area is 2.

## 9. Optimization Problem

Let the top-right corner of the rectangle touching the curve be at coordinates $(x, y)$. Because the base is on the x-axis and the side is on the y-axis, the width is $x$ and the height is $y = 3 - x^2$.
The area $A$ of the rectangle is:


$$A(x) = x(3 - x^2) = 3x - x^3$$


To find the maximum area, take the derivative and set it to zero:


$$A'(x) = 3 - 3x^2 = 0$$

$$3x^2 = 3 \implies x^2 = 1 \implies x = 1$$

 (We only consider the positive root because it is in the first quadrant).
The corresponding height is:


$$y = 3 - 1^2 = 2$$


The dimensions of the rectangle with the maximum area are a width of 1 and a height of 2.

## 10. Infinite Series

We can break the ant's movement into independent horizontal (X) and vertical (Y) components.

* **X-axis (East/West):** The ant moves 1 east, 1/3 west, 1/5 east...

$$X = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$$



This is the well-known Gregory-Leibniz infinite series for the arctangent function evaluated at 1:

$$X = \sum_{n=0}^{\infty} \frac{(-1)^n}{2n+1} = \arctan(1) = \frac{\pi}{4}$$


* **Y-axis (North/South):** The ant moves 1/2 north, 1/4 south, 1/6 north...

$$Y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots$$



If you factor out $1/2$, you get the alternating harmonic series:

$$Y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)$$



Since the alternating harmonic series converges to $\ln(2)$, the Y-coordinate is:

$$Y = \frac{1}{2}\ln(2)$$



The final position of the ant is $\left(\frac{\pi}{4}, \frac{\ln(2)}{2}\right)$.