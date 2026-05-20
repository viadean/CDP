# State Diagram

[E-Product Hub](https://payhip.com/CDP)





## Dynamics and Transitions in Fluid Flow Visualization

> The state diagram demonstrations are structured to guide you from basic vector field visualization to complex physical interpretations of divergence, mass conservation, and vorticity.

- [Verification of the Divergence Theorem for a Rotating Fluid Flow](https://viadean.notion.site/Verification-of-the-Divergence-Theorem-for-a-Rotating-Fluid-Flow-DT-RFF-2571ae7b9a328091ad62deba6f8d1715?source=copy_link)
- [Deliverables](https://payhip.com/b/Q9Zjy)

```mermaid
stateDiagram-v2
    [*] --> Demo1: Baseline Visualization
    
    state "Divergence & Flux Path" as DivergencePath {
        Demo1 --> Demo2: Add Radial Term (k > 0)
        Demo2 --> Demo7: Isolate Flow Components
    }
    
    state "Continuity & Density Path" as DensityPath {
        Demo2 --> Demo3: Apply Continuity Eq (Source)
        Demo3 --> Demo4: Flip Radial Sign (k < 0)
    }
    
    state "Vorticity & Rotation Path" as VorticityPath {
        Demo1 --> Demo5: Shift Focus to Curl
        Demo5 --> Demo6: Invert Velocity Gradient (1/r)
    }

    Demo1: Demo 1 - Helical Flow (∇·v = 0)
    Demo2: Demo 2 - Diverging Helix (Source)
    Demo3: Demo 3 - Density Fading (Source Effect)
    Demo4: Demo 4 - Density Compression (Sink)
    Demo5: Demo 5 - Rigid Body Rotation (∇×v ≠ 0)
    Demo6: Demo 6 - Irrotational Vortex (∇×v = 0)
    Demo7: Demo 7 - Interactive Flux Analysis
```



## Visualizing Conservative Forces and Mathematical Identities

> This state diagram illustrates the purposeful flow from the core mathematical identity to its physical application in Example 1, and subsequently to the three interactive demonstrations that provide intuition, simulation, and numerical proof.

- [Using Stokes' Theorem with a Constant Scalar Field](https://viadean.notion.site/Using-Stokes-Theorem-with-a-Constant-Scalar-Field-ST-CSF-2561ae7b9a328056bcc5dc2e105a1c35?source=copy_link)
- [Deliverables](https://payhip.com/b/io8GT)

```mermaid
stateDiagram-v2
    direction TB

    state "Mathematical Identity" as Math {
        direction LR
        Logic: Surface integral = 0 if φ is constant on boundary
    }

    Math --> Example1 : Foundation for Physics
    state "Example 1: Conservative Forces" as Example1 {
        direction LR
        Concept: F = -∇U (Potential Energy)
        Principle: Energy conservation in closed loops
    }

    Example1 --> Demo2 : Simulates Work/Energy
    state "Demo 2: Physical Simulation" as Demo2 {
        direction LR
        Animation: Particle on figure-eight path
        Outcome: Positive and negative work cancel out
    }

    Math --> Demo1 : Visualizes Symmetry
    state "Demo 1: Interactive Proof" as Demo1 {
        direction LR
        Action: Toggle Constant vs. Variable φ
        Result: Vector sum (green arrow) collapses to zero
    }

    Demo1 --> Demo3 : Validates with Numbers
    state "Demo 3: Quantitative Proof" as Demo3 {
        direction LR
        Calc: Variable φ (-3.14) vs. Constant φ (0)
        Context: Stokes' Theorem validation
    }

```

