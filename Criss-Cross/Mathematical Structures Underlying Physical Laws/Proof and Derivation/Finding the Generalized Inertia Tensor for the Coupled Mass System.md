# Finding the Generalized Inertia Tensor for the Coupled Mass System

> The derivation of the generalized inertia tensor highlights how constraints simplify complex mechanics: the diagonal structure confirms that the kinetic energy is instantaneously decoupled into independent radial ( $\dot{r}$ ) and angular ( $\dot{\varphi}$ ) velocity terms. The radial inertia ( $M_{r r}$ ) simplifies to the total mass ( $m_1+m_2$ ) because both particles move with the same radial speed. Conversely, the angular inertia ( $M_{\varphi \varphi}$ ) is simply the moment of inertia of $m_1$ alone ( $m_1 r^2$ ), as $m_2$ does not rotate. Crucially, this tensor is non-constant because the angular component depends on the current radius $r$, which is the exact mathematical foundation for the strong coupling and oscillation we observed in the animation through the conservation of angular momentum.

## Key takeaways

1. The Power of Generalized Coordinates

   By choosing the generalized coordinates r and $\varphi$, we completely decoupled the kinetic energy expression. The total kinetic energy $T$ became a simple sum of terms, $\frac{1}{2} M_{r r} \dot{r}^2+\frac{1}{2} M_{\varphi \varphi} \dot{\varphi}^2$, with no cross-term involving $\dot{r} \dot{\varphi}$.

2. Physical Interpretation of Components

   The components of the tensor reveal the effective inertia for each type of motion:

   - $M_{r r}=m_1+m_2$ (Radial Inertia): This component represents the total mass of the system. Since both masses move with the same radial speed $\dot{r}$ (as $m_2$ 's vertical position is directly linked to $m_1$ 's radial position $r$ ), the effective inertia for inward/outward motion is simply the sum of both masses.
   - $M_{\varphi \varphi}=m_1 r^2$ (Angular Inertia): This component is the moment of inertia about the $z$-axis (the hole). Crucially, only mass $m_1$ contributes to the rotation because $m_2$ is constrained to move only vertically along the axis of rotation, giving it zero rotational inertia.

3. Coordinate Dependence (Non-Constant Inertia)

   Notice that the $M$ tensor is not a constant matrix. The $M_{\varphi \varphi}$ component is $m_1 r^2$, meaning the angular inertia of the system depends on the mass $m_1$ 's current radial position $r$. This is the mathematical backbone of the angular momentum conservation effect we saw in the animation: as $r$ changes, the system's resistance to angular acceleration changes dynamically.

### Non-Constant Inertia and Dynamic Coupling | Audio

[![Watch the video](https://img.youtube.com/vi/fp7Ex6UG2-4/maxresdefault.jpg)](https://youtu.be/fp7Ex6UG2-4)

### [Watch this video on YouTube](https://youtu.be/fp7Ex6UG2-4)

## Centrifugal Force as the Stability Governor | Demo

> The analysis across the three scenarios demonstrates that the system's dynamic fate is entirely determined by the initial balance of forces. The system achieves a near-perfect circular orbit (Scenario C) only when the initial centrifugal force exactly counteracts the gravitational tension from the hanging mass $m_2$. If the initial angular velocity is too low (Scenario A), the centrifugal force is insufficient, and $m_2$ 's weight pulls $m_1$ rapidly inward toward collapse due to the dominant inward force. Conversely, if the initial angular velocity is too high (Scenario B), the centrifugal force is overpowering, flinging $m_1$ outward and initiating a continuous, large amplitude coupled oscillation as the forces repeatedly overshoot equilibrium.

https://youtube.com/shorts/-G7BlpNixmI?feature=share

## Published web

- [Finding the Generalized Inertia Tensor for the Coupled Mass System](https://viadean.notion.site/Finding-the-Generalized-Inertia-Tensor-for-the-Coupled-Mass-System-28b1ae7b9a32809ab8f0d24d6c429dff)
- [Centrifugal Force as the Stability Governor](https://viadean.notion.site/Centrifugal-Force-as-the-Stability-Governor-28b1ae7b9a3280f2bf3dee9dcc5200a9)
- [Non-Constant Inertia and Dynamic Coupling](https://viadean.notion.site/Non-Constant-Inertia-and-Dynamic-Coupling-28b1ae7b9a3280ee8055f992ba8f5e89)

## Language

`Python`