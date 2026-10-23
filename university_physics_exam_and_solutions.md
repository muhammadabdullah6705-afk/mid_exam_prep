# University Physics Written Exam
**Topics Covered:** Chapters 1–7 (Units, Kinematics, Dynamics, Work & Energy)  
*Based on University Physics by Young & Freedman*

---

## Part I: Exam Questions

### **Question 1 (Easy - Theory & Dimensional Analysis)**
Define **dimensional homogeneity** in physical equations. Explain why every valid physical equation must be dimensionally homogeneous, and demonstrate this principle using the kinematic equation for position under constant acceleration:
$$x = v_0 t + \frac{1}{2} a t^2$$

---

### **Question 2 (Easy - Motion Along a Straight Line)**
A particle moves along the $x$-axis such that its position as a function of time is given by:
$$x(t) = 2.0 t^3 - 6.0 t^2 + 4.0$$
where $x$ is in meters and $t$ is in seconds.
1. Derive expressions for the instantaneous velocity $v(t)$ and acceleration $a(t)$ as functions of time.
2. Determine all time(s) $t \ge 0$ at which the particle is momentarily at rest.

---

### **Question 3 (Medium - Motion in Two Dimensions)**
A projectile is launched from ground level over flat terrain with an initial speed $v_0 = 25.0\text{ m/s}$ at an angle $\alpha_0 = 36.87^\circ$ above the horizontal. Neglecting air resistance:
1. Calculate the maximum height $h_{\text{max}}$ reached by the projectile.
2. Calculate the total horizontal range $R$ of the projectile.

*(Use $g = 9.80\text{ m/s}^2$, $\sin(36.87^\circ) \approx 0.600$, and $\cos(36.87^\circ) \approx 0.800$)*

---

### **Question 4 (Medium - Newton's Laws & Friction)**
A $4.00\text{ kg}$ block rests on a rough horizontal surface. The coefficient of static friction is $\mu_s = 0.500$ and the coefficient of kinetic friction is $\mu_k = 0.300$. A horizontal pulling force $\vec{F}$ is applied to the block. 

Determine the magnitude of the friction force acting on the block and its resulting acceleration if:
1. $F = 10.0\text{ N}$
2. $F = 25.0\text{ N}$

*(Use $g = 9.80\text{ m/s}^2$)*

---

### **Question 5 (Hard - Potential Energy & Energy Conservation)**
A small block of mass $m = 0.500\text{ kg}$ slides along a frictionless track. The block is released from rest at **Point A**, which is at a height $h_A = 5.00\text{ m}$ above ground level. At the bottom of the incline (**Point B**, at height $y = 0$), the track enters a vertical circular loop-the-loop of radius $R = 1.50\text{ m}$.

1. Using energy conservation, calculate the speed $v_B$ of the block at the bottom of the loop (**Point B**).
2. Calculate the normal force $N$ exerted by the track on the block when it reaches the very top of the circular loop (**Point C**, at height $y = 2R = 3.00\text{ m}$).

*(Use $g = 9.80\text{ m/s}^2$)*

---

\pagebreak

# Solutions and Answer Key

### **Solution to Question 1**
* **Definition:** Dimensional homogeneity states that every additive term in a physical equation must possess the exact same fundamental physical dimensions (such as Mass $[M]$, Length $[L]$, and Time $[T]$).
* **Explanation:** Physical laws must remain valid regardless of the unit system used. Since physical quantities with different dimensions cannot be added or subtracted (e.g., adding meters to seconds is physically meaningless), both sides of any valid equation must share identical dimensions.
* **Proof:**
  * Left side ($x$): $[L]$
  * Term 1 ($v_0 t$): $[v_0][t] = \left(\frac{[L]}{[T]}\right) [T] = [L]$
  * Term 2 ($\frac{1}{2} a t^2$): $[a][t]^2 = \left(\frac{[L]}{[T]^2}\right) [T]^2 = [L]$  
  *(Note: Numerical constants like $\frac{1}{2}$ are dimensionless).*  
  Since all terms evaluate to dimensions of Length $[L]$, the equation is dimensionally homogeneous.

---

### **Solution to Question 2**
1. **Velocity and Acceleration Functions:**
   $$v(t) = \frac{dx}{dt} = \frac{d}{dt}(2.0 t^3 - 6.0 t^2 + 4.0) = 6.0 t^2 - 12.0 t\text{ (m/s)}$$
   $$a(t) = \frac{dv}{dt} = \frac{d}{dt}(6.0 t^2 - 12.0 t) = 12.0 t - 12.0\text{ (m/s}^2)$$

2. **Times at Rest ($v(t) = 0$):**
   $$6.0 t^2 - 12.0 t = 0 \implies 6.0 t (t - 2.0) = 0$$
   The particle is momentarily at rest at **$t = 0\text{ s}$** and **$t = 2.0\text{ s}$**.

---

### **Solution to Question 3**
* **Initial Velocity Components:**
  * $v_{0x} = v_0 \cos\alpha_0 = (25.0\text{ m/s})(0.800) = 20.0\text{ m/s}$
  * $v_{0y} = v_0 \sin\alpha_0 = (25.0\text{ m/s})(0.600) = 15.0\text{ m/s}$

1. **Maximum Height ($h_{\text{max}}$):**
   At maximum height, $v_y = 0$:
   $$v_y^2 = v_{0y}^2 - 2g h_{\text{max}} \implies 0 = (15.0)^2 - 2(9.80) h_{\text{max}}$$
   $$h_{\text{max}} = \frac{225}{19.6} \approx \mathbf{11.48\text{ m}}$$

2. **Horizontal Range ($R$):**
   Time of flight $t_{\text{total}}$:
   $$y = v_{0y} t - \frac{1}{2}g t^2 \implies 0 = t\left(15.0 - 4.90 t\right) \implies t_{\text{total}} = \frac{15.0}{4.90} \approx 3.061\text{ s}$$
   Horizontal distance:
   $$R = v_{0x} t_{\text{total}} = (20.0\text{ m/s})(3.061\text{ s}) \approx \mathbf{61.22\text{ m}}$$

---

### **Solution to Question 4**
* **Normal Force and Maximum Static Friction:**
  $$N = mg = (4.00\text{ kg})(9.80\text{ m/s}^2) = 39.2\text{ N}$$
  $$f_{s,\text{max}} = \mu_s N = (0.500)(39.2\text{ N}) = 19.6\text{ N}$$
  $$f_k = \mu_k N = (0.300)(39.2\text{ N}) = 11.76\text{ N}$$

1. **When $F = 10.0\text{ N}$:**
   Since $F < f_{s,\text{max}}$ ($10.0\text{ N} < 19.6\text{ N}$), the block does not move.
   * **Friction Force:** $f_s = F = \mathbf{10.0\text{ N}}$
   * **Acceleration:** $a = \mathbf{0\text{ m/s}^2}$

2. **When $F = 25.0\text{ N}$:**
   Since $F > f_{s,\text{max}}$ ($25.0\text{ N} > 19.6\text{ N}$), the block moves and kinetic friction applies.
   * **Friction Force:** $f_k = \mathbf{11.76\text{ N}}$
   * **Acceleration:** 
     $$F_{\text{net}} = F - f_k = 25.0 - 11.76 = 13.24\text{ N}$$
     $$a = \frac{F_{\text{net}}}{m} = \frac{13.24\text{ N}}{4.00\text{ kg}} \approx \mathbf{3.31\text{ m/s}^2}$$

---

### **Solution to Question 5**
1. **Speed at Bottom of Loop ($v_B$):**
   Setting $y = 0$ at Point B, conservation of energy between A and B gives:
   $$E_A = E_B \implies m g h_A = \frac{1}{2} m v_B^2$$
   $$v_B = \sqrt{2 g h_A} = \sqrt{2(9.80)(5.00)} = \sqrt{98.0} \approx \mathbf{9.90\text{ m/s}}$$

2. **Normal Force at Top of Loop ($N_C$):**
   * **Energy Conservation to Top (Point C, $y = 2R = 3.00\text{ m}$):**
     $$E_A = E_C \implies m g h_A = m g (2R) + \frac{1}{2} m v_C^2$$
     $$v_C^2 = 2g(h_A - 2R) = 2(9.80)(5.00 - 3.00) = 2(9.80)(2.00) = 39.2\text{ m}^2/\text{s}^2$$
     $$v_C \approx 6.26\text{ m/s}$$

   * **Free-Body Diagram at Top:**
     Both gravity $mg$ and the normal force $N_C$ point downward toward the center of the circle:
     $$\sum F_y = N_C + mg = \frac{m v_C^2}{R}$$
     $$N_C = m \left( \frac{v_C^2}{R} - g \right) = (0.500\text{ kg}) \left( \frac{39.2}{1.50} - 9.80 \right)$$
     $$N_C = 0.500 \left( 26.133 - 9.80 \right) = 0.500 (16.333) \approx \mathbf{8.17\text{ N}}$$