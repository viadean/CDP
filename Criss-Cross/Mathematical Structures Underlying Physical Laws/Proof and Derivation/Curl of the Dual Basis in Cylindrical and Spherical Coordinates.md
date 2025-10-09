# Curl of the Dual Basis in Cylindrical and Spherical Coordinates

> The computation for the curl of the dual basis vectors ( $\nabla \times e^a$ ) in both cylindrical and spherical coordinates yields a null vector ( 0 ) in every case. This fundamental result stems from the general tensorial expression for the curl, which is proportional to the partial derivative of the covariant components of the vector, $\partial_b v_d$. Since the covariant components of the dual basis vector $e^a$ are given by the Kronecker delta, $v_d=\left(e^a\right)_d=\delta_d^a$, these components are constants (i.e., independent of the spatial coordinates). Consequently, their partial derivative is zero, meaning $\nabla \times e^a=0$. This result is further verified when applying the physical component formula, where the term being differentiated, $h_c \tilde{v}_c$, also simplifies to the constant $\delta_c^a$, confirming that all components of the curl are zero in both coordinate systems. 

## Key takeaways

1. General Result for Dual Basis Curl: The curl of a dual basis vector $\left(\nabla \times e^a\right)$ in any orthogonal curvilinear coordinate system is always zero.

2. Reasoning from General Curl Expression: Using the general expression for the contravariant components of the curl, $(\nabla \times v)^c=\frac{1}{\sqrt{g}} \varepsilon^{c a b} \partial_a v_b$, and noting that the covariant components of $e^a$ are $v_b=\left(e^a\right)_b=\delta_b^a$, the partial derivative term $\partial_a \delta_b^a$ is zero because $\delta_b^a$ is constant.

3. Result in Specific Coordinate Systems: Consequently, the physical components of the curl of the dual basis are all zero in both:

   - Cylindrical Coordinates: $\left(\nabla \times e^\rho\right)_c=0,\left(\nabla \times e^\phi\right)_c=0,\left(\nabla \times e^z\right)_c=0$.
   - Spherical Coordinates: $\left(\nabla \times e^r\right)_c=0,\left(\nabla \times e^\theta\right)_c=0,\left(\nabla \times e^\phi\right)_c=0$.

4. Verification with known formula: The result is confirmed by using the physical component expression. The physical components of $e^a$ are $\tilde{v}_c=\left(e^a\right)_c=\frac{1}{h_c} \delta_c^a$. The term being differentiated, $h_c \tilde{v}_c$, simplifies to $\delta_c^a$, whose derivative is zero.

   $$ \partial_b\left(h_c \tilde{v}_c\right)=\partial_b\left(\delta_c^a\right)=0 $$

   This mathematically validates the zero result in the physical component framework as well.

### Audio

[![Watch the video](https://img.youtube.com/vi/9RLNTWE61WI/maxresdefault.jpg)](https://youtu.be/9RLNTWE61WI)

### [Watch this video on YouTube](https://youtu.be/9RLNTWE61WI)

## Demonstration

> This animation demonstrates how the curl behaves in cylindrical (polar) and spherical coordinate systems through visual comparison. The visualization bridges analytic expressions of curls in curvilinear coordinates with their geometric interpretations—clarifying how differential geometry encodes rotation and basis deformation across coordinate systems.

[![Watch the video](https://img.youtube.com/vi/i5oLrVry0Wo/maxresdefault.jpg)](https://youtu.be/i5oLrVry0Wo)

### [Watch this video on YouTube](https://youtu.be/i5oLrVry0Wo)

## Published web

- [Curl of the Dual Basis in Cylindrical and Spherical Coordinates](https://viadean.notion.site/Curl-of-the-Dual-Basis-in-Cylindrical-and-Spherical-Coordinates-2861ae7b9a32806abf4dc0b642429012?source=copy_link)
- [Visualizing the Curl of Dual Bases in Curvilinear Coordinates](https://viadean.notion.site/Visualizing-the-Curl-of-Dual-Bases-in-Curvilinear-Coordinates-2861ae7b9a328053bb1ffa36fd79b3ee?source=copy_link)
- [Curl of the Dual Basis is Always Zero](https://viadean.notion.site/Curl-of-the-Dual-Basis-is-Always-Zero-2861ae7b9a3280418a9ec625fc647c48?source=copy_link)