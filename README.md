# Kiss-Surface-

### **What is the Kiss Surface?**  
The **Kiss Surface** is a 3D mathematical surface characterized by its **hourglass-like shape**, smoothly transitioning from a **wide base** to a **narrow waist** and then expanding again. The name "Kiss Surface" comes from its resemblance to a pair of touching (or "kissing") surfaces.

It is commonly used in **mathematical visualization** and **differential geometry** to illustrate interesting curvature properties.

---

### **Understanding the Equation Used in the Code**  
The equation for the Kiss Surface, used in the code, is:

![Image](https://github.com/user-attachments/assets/808972ef-4fcf-4290-9196-b40edf8c17a1)

---

### **Breaking Down the Components**  
1. **Radial Function**:  
   \[
   r = v^2 \sqrt{\frac{1 - v}{a}}
   \]
   This defines how far a point is from the center as a function of \( v \).  
   - At \( v = -1 \), \( r = 1 \) (wide base).  
   - At \( v = 1 \), \( r \approx 0 \) (narrow neck).  
   - At \( v = 0 \), \( r \) is also small, creating symmetry.

2. **X and Y Coordinates**:  
   \[
   x = r \cos(u), \quad y = r \sin(u)
   \]
   These define a circular cross-section at each height \( v \), with radius \( r \).

3. **Z Coordinate**:  
   \[
   z = v
   \]
   Simply sets the height of the surface.

---

### **How This Shapes the Surface**
- The **\( v^2 \)** term ensures that the base is wide and tapers smoothly towards the center.
- The **\( \sqrt{1 - v} \)** term controls the narrowing effect at the top, preventing it from expanding too much.
- The **\( \cos(u) \)** and **\( \sin(u) \)** terms ensure that the structure is **circularly symmetric**.

This equation creates a **smooth and symmetrical surface** that appears like a **pinched hourglass or a hyperbolic structure**, commonly used in mathematical visualizations.
