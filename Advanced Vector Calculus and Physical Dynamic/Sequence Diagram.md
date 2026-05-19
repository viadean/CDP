# Sequence Diagram

[E-Product Hub](https://payhip.com/CDP)



## Pedagogical Visualization of Vector Calculus and Fluid Dynamics

> The sequence diagram illustrates the pedagogical progression of the demonstrations, moving from basic helical flow visualization to the complex physical analysis of divergence, mass conservation, and vorticity. --- [Verification of the Divergence Theorem for a Rotating Fluid Flow](https://viadean.notion.site/Verification-of-the-Divergence-Theorem-for-a-Rotating-Fluid-Flow-DT-RFF-2571ae7b9a328091ad62deba6f8d1715)

- Deliverables: https://payhip.com/b/Q9Zjy

```mermaid
sequenceDiagram
    participant S as Student / User
    participant M as Mathematical Model
    participant V as Visualization (Demos)

    Note over S, V: Stage 1: Helical Flow & Divergence Theorem
    S->>M: Analyze Helical Velocity Field
    M->>M: Compute Divergence (∇·v = 0)
    S->>V: Load Demo 1
    V-->>S: Visualize constant particle spacing (Incompressible)
    S->>V: Load Demo 7 (Interactive)
    V-->>S: Verify Upward Flux = Downward Flux (Net Flux = 0)

    Note over S, V: Stage 2: Sources, Sinks, and Continuity
    S->>M: Add Radial Term (vρ = kρ)
    M->>M: Compute Positive Divergence (∇·v = 2k)
    S->>V: Load Demo 2 (Source)
    V-->>S: Particles drift outward (Diverging Helix)
    S->>M: Apply Continuity Equation (Dρ/Dt = -ρ∇·v)
    S->>V: Load Demo 3 (Source) & Demo 4 (Sink)
    V-->>S: Particles fade (thinning) or brighten (compression)

    Note over S, V: Stage 3: Vorticity & Local Rotation
    S->>M: Calculate Curl (∇×v)
    M->>M: Compute Constant Vorticity (2v0/L)
    S->>V: Load Demo 5 (Rigid Body Rotation)
    V-->>S: Paddlewheels spin locally while orbiting
    S->>M: Invert Velocity Gradient (v ∝ 1/r)
    M->>M: Compute Zero Curl (∇×v = 0)
    S->>V: Load Demo 6 (Irrotational Vortex)
    V-->>S: Paddlewheels orbit but maintain orientation (No spin)
```



## Vector Calculus Proofs and Physical Conservative Field Applications

> This sequence diagram illustrates the logical progression from the initial vector calculus proof to its physical applications and the various interactive demonstrations used to validate the results.

- Deliverables: https://payhip.com/b/io8GT

```mermaid
sequenceDiagram
    autonumber
    participant U as User/Student
    participant MP as Mathematical Proof
    participant PH as Physics (Example 1)
    participant D1 as Demo 1 (Visual)
    participant D2 as Demo 2 (Sim)
    participant D3 as Demo 3 (Numeric)

    U->>MP: Analyze: $$\int_S[(\nabla \phi) \times(\nabla \psi)] \cdot d \vec{S}$$
    MP->>MP: Apply Stokes' Theorem: $$\oint_C \phi(\nabla \psi) \cdot d x$$
    MP->>MP: Apply "Constant $$\phi$$" condition (Pull c out)
    MP->>MP: Fundamental Theorem: $$\oint_C(\nabla \psi) \cdot d x = 0$$
    MP-->>U: Result: Surface Integral = 0

    U->>PH: Translate to Physics
    PH->>PH: Define Conservative Force: $F = -\nabla U$
    PH->>PH: Apply result to work-energy conservation
    PH-->>U: Result: Net work around a closed loop is zero

    U->>D1: Visualize "Why" (Interactive)
    D1->>D1: Toggle $$\phi$$ from Variable to Constant
    D1-->>U: Vector sum (green arrow) collapses to zero

    U->>D2: Simulate Physics (Figure-8)
    D2->>D2: Move particle through simulated gravity
    D2-->>U: Positive/negative work cancel (Total = 0)

    U->>D3: Request Quantitative Proof
    D3->>D3: Calculate Hemisphere Integral for $$\phi=y$$
    D3-->>U: Variable result = -3.14 ($$-\pi$$) vs. Constant result = 0

```

