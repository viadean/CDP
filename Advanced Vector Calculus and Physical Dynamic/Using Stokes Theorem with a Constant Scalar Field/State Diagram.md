# State Diagram

## Visualizing Conservative Forces and Mathematical Identities

> This state diagram illustrates the purposeful flow from the core mathematical identity to its physical application in Example 1, and subsequently to the three interactive demonstrations that provide intuition, simulation, and numerical proof.

- Deliverables: https://payhip.com/b/io8GT
- E-Product Hub: https://payhip.com/CDP

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

