# Fluid Mechanics Integrals for Mass and Motion

> The solutions demonstrate how fundamental physical quantities in a continuous fluid are determined by integrating their respective densities over a given volume $V$. In all cases, the mass density $\rho(x)$ is crucial as it scales the quantity per unit mass to the quantity per unit volume, $d V$ . The total kinetic energy is a scalar, found by integrating the kinetic energy density $\frac{1}{2} \rho|v|^2$. In contrast, both the total momentum and total angular momentum are vector quantities. Total momentum is the integral of the linear momentum density $\rho v$. Total angular momentum, which must be defined relative to a specific reference point $x_0$, is the integral of the angular momentum density $\rho\left(x-x_0\right) \times v$.

## Key takeaways

- Total quantity as a Volume Integral: For continuous media like fluids, total physical quantities (like energy, momentum, or angular momentum) over a volume $V$ are found by integrating the corresponding density over that volume.
- Mass Density is the Multiplier: The mass density $\rho(x)$ serves as the fundamental measure of mass distribution and is the required factor in all integrals, multiplying the per-unit-mass quantity to get the per-unit-volume density.
- Kinetic Energy (Scalar): The integrand for kinetic energy is the scalar kinetic energy density $\frac{1}{2} \rho|v|^2$.
- Momentum and Angular Momentum (Vectors): Both total momentum and total angular momentum are vector quantities, meaning the integral itself yields a vector.
  - Momentum Density is the vector quantity $\rho v$.
  - Angular Momentum Density is the vector quantity $\rho\left(x-x_0\right) \times v$, which is the mass density times the cross product of the relative position vector and the velocity vector.
- Reference Point for Angular Momentum: Angular momentum is always defined relative to a specific reference point $x_0$. This is accounted for by using the relative position vector, $x-x_0$, in the integrand.

### Mass Density as the Integrating Factor | Audio

[![Watch the video](https://img.youtube.com/vi/Lb-yFrlDFjI/maxresdefault.jpg)](https://youtu.be/Lb-yFrlDFjI)

### [Watch this video on YouTube](https://youtu.be/Lb-yFrlDFjI)

## visualize the density fields of Kinetic Energy Momentum and Angular Momentum as a function of time | Demo

> The visualization highlights a fundamental difference between scalar and vector integrals in fluid dynamics, especially in a symmetric flow: vigorous internal fluid motion does not guarantee net linear momentum. In the case of the symmetric vortex modeled, the Total Kinetic Energy (a scalar integral) and the Total Angular Momentum (a vector quantity measured relative to the center) are large and non-zero. However, the Total Momentum (a vector integral, $\int \rho v d V$ ) is effectively zero. This occurs because the momentum vectors from one side of the rotation are perfectly canceled by the opposing momentum vectors on the other side, illustrating that symmetry in the velocity field leads to a zero net vector sum, even though the energy associated with that motion remains high.

https://youtube.com/shorts/IPV8vNuhUY0?feature=share

## Published web

- [Fluid Mechanics Integrals for Mass and Motion](https://viadean.notion.site/Fluid-Mechanics-Integrals-for-Mass-and-Motion-2881ae7b9a32808ab76ee98b80a751d3)
- [visualize the density fields of Kinetic Energy Momentum and Angular Momentum as a function of time](https://viadean.notion.site/visualize-the-density-fields-of-Kinetic-Energy-Momentum-and-Angular-Momentum-as-a-function-of-time-2881ae7b9a32803fa314fc929d01f0ab)
- [Mass Density as the Integrating Factor](https://viadean.notion.site/Mass-Density-as-the-Integrating-Factor-2881ae7b9a3280e08fc9c379494607f4)

## Language

`Python`