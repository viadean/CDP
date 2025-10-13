# Young's Modulus and Poisson's Ratio in Terms of Bulk and Shear Moduli

> The relationship between the elastic constants, derived from the general constitutive equations, establishes that Young's modulus ( $E$ ) and Poisson's ratio ( $\nu$ ) can be fully expressed by the Bulk modulus ( $K$ ) and the Shear modulus ( $G$ ) for an isotropic material. This derivation fundamentally relies on separating stress and strain into volumetric (governed by $K$ ) and deviatoric (governed by $G$ ) components. The key intermediate result is the relationship $E= 2 G(1+\nu)$, which connects the stiffness ($E$) to the resistance to shear ($G$) and lateral contraction ($\nu$). The final expressions, $E=\frac{9 K G}{3 K+G}$ and $\nu=\frac{3 K-2 G}{6 K+2 G}$, show how the material's resistance to volume change ( $K$ ) and resistance to shape change ( $G$ ) combine to define its overall elastic behavior.

## Key takeaways

- Interrelation of Elastic Constants: The fundamental takeaway is that all four common elastic constants ( $E, \nu, K$, and $G$ ) are interdependent. In an isotropic material, knowing any two allows you to determine the other two.

- Role of Trace Operations: The derivation relies on decomposing the stress and strain tensors into their volumetric (dilatational) and deviatoric (shear) components:

  - The trace of the strain tensor ( $\epsilon_{k k}$ ) is used to isolate the bulk modulus ( $K$ ), which governs volume change.
  - The pure shear condition ( $\sigma_{k k}=0$ ) is used to isolate the shear modulus ( $G$ ), which governs shape change.

- Physical Meaning of the Constants:

  - Bulk Modulus ($K$): Represents the material's resistance to volume change under hydrostatic pressure.
  - Shear Modulus ( $G$ ): Represents the material's resistance to shape change (shear deformation).
  - Young's Modulus ($E$): Represents stiffness in uniaxial tension/compression.
  - Poisson's Ratio ( $\nu$ ): Represents the ratio of transverse strain to axial strain; it quantifies lateral contraction.

- Key Intermediate Relationship: The relationship derived from the pure shear condition is crucial: $E=2 G(1+\nu)$. This is one of the most common and essential relationships between the constants.

- Incompressibility Limit ( $\nu \rightarrow 1 / 2$ ): The final equation for $\nu$ is: $\nu=\frac{3 K-2 G}{6 K+2 G}$

  For an incompressible material (like rubber), $\nu \approx 0.5$ (or 1 / 2 ). Substituting this value into the equation shows that the Bulk Modulus ( $K$ ) must approach infinity ( $K \rightarrow \infty$ ), which physically means an infinite pressure is required to change the material's volume.

### The Interdependence of Elastic Constants | Audio

[![Watch the video](https://img.youtube.com/vi/lWjlcCLTgL8/maxresdefault.jpg)](https://youtu.be/lWjlcCLTgL8)

### [Watch this video on YouTube](https://youtu.be/lWjlcCLTgL8)

## Visualize how the Poisson's ratio approaches the incompressibility limit as the stiffness ratio increases | Demo

> The visualization confirms the complete interdependency of the elastic constants ( $E, \nu, K, G$ ) by showing the simultaneous limiting behavior as the stiffness ratio ( $K / G$ ) increases. For near-incompressible materials ( $K \gg G$ ), two critical limits are reached: first, the Poisson's ratio ($\nu$) approaches 0.5 , signifying a maximum resistance to volume change (high $K$ ); and second, the Young's Modulus ( $E$ ) approaches $3 G$, establishing a fixed relationship between axial and shear stiffness that is independent of the increasingly dominant bulk modulus $K$. This combined behavior, characteristic of materials like rubber, means the material easily changes shape ( $G$ ) but strongly resists changes in volume ( $K$ ), with its overall stiffness ( $E$ ) being dictated solely by its shear rigidity ( $G$ ) in this limit.

[![Watch the video](https://img.youtube.com/vi/bxEuCUBWcQI/maxresdefault.jpg)](https://youtu.be/bxEuCUBWcQI)

### [Watch this video on YouTube](https://youtu.be/bxEuCUBWcQI)

## Published web

- [Young's Modulus and Poisson's Ratio in Terms of Bulk and Shear Moduli](https://viadean.notion.site/Young-s-Modulus-and-Poisson-s-Ratio-in-Terms-of-Bulk-and-Shear-Moduli-2891ae7b9a3280719445efc94ef03120)
- [Visualize how the Poisson's ratio approaches the incompressibility limit as the stiffness ratio increases](https://viadean.notion.site/Visualize-how-the-Poisson-s-ratio-approaches-the-incompressibility-limit-as-the-stiffness-ratio-incr-2891ae7b9a3280a988f8e8db037d5c91)
- [The Interdependence of Elastic Constants](https://viadean.notion.site/The-Interdependence-of-Elastic-Constants-2891ae7b9a3280a2a79ee274f0c701e5)

## Language

`Python`