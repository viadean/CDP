# Flowchart

[E-Product Hub](https://payhip.com/CDP)



## Fluid Dynamics and Divergence Verification

> The flowchart illustrates a structured workflow for the Verification of the Divergence Theorem for a Rotating Fluid Flow. It maps out how various fluid dynamics demonstrations are implemented through code and how they link to specific mathematical principles.

- [Verification of the Divergence Theorem for a Rotating Fluid Flow](https://viadean.notion.site/Verification-of-the-Divergence-Theorem-for-a-Rotating-Fluid-Flow-DT-RFF-2571ae7b9a328091ad62deba6f8d1715?source=copy_link)
- [Deliverables](https://payhip.com/b/Q9Zjy)

```mermaid
---
config:
 flowchart:
  defaultRenderer: elk
---
flowchart LR
E0@{shape: doc, label: "Verification of the Divergence Theorem for a Rotating Fluid Flow"}

D1@{shape: card, label: "Helical Fluid Flow"}
D2@{shape: card, label: "Diverging Fluid Flow (Source)"}
D3@{shape: card, label: "Continuity Equation: Density fading"}
D4@{shape: card, label: "Continuity Equation: Density increasing"}
D5@{shape: card, label: "Vorticity (Rigid Body Rotation)"}
D6@{shape: card, label: "Irrotational Vortex (No Local Rotation)"}
D7@{shape: card, label: "Divergence Theorem Visualization"}

Python@{shape: circ, label: "Python"}
HTML@{shape: circ, label: "HTML"}

subgraph Example
E0
end

subgraph Demo
D1-->D2
D3-->D4
D5-->D6
D7
end

E0 e0@==>Python e1@==>D1
Python e2@==>D2
Python e3@==>D3
Python e4@==>D4
Python e5@==>D5
Python e6@==>D6
E0 e7@==>HTML e8@==>D7

VFE_D1@{shape: hex, label: "$$\\vec{v} = \\frac{v_0}{L}(-y\\vec{e}_x + x\\vec{e}_y + L\\vec{e}_z)$$"}
VFE_D2@{shape: hex, label: "$$\\nabla \\cdot \\vec{v} = 2k$$"}
VFE_D3@{shape: hex, label: "$$\\nabla \\cdot \\vec{v} > 0 $$"}
VFE_D4@{shape: hex, label: "$$\\nabla \\cdot \\vec{v}$$ < 0"}
VFE_D5@{shape: hex, label: "$$\\vec{\\omega} = \\nabla \\times \\vec{v}$$"}
VFE_D6@{shape: hex, label: "$$\\nabla \\times \\vec{v} = 0$$"}
VFE_D7@{shape: hex, label: "$$\\vec{v}=\\frac{v_0}{L}\\left(x^1 \\vec{e}_2-x^2 \\vec{e}_1+L \\vec{e}_3\\right)$$"}

MC_D1@{shape: stadium, label: "Divergence Theorem / Incompressible Flow" }
MC_D2@{shape: stadium, label: "Non-zero Divergence (Source)"}
MC_D3@{shape: stadium, label: "Continuity Equation / Material Derivative"}
MC_D4@{shape: stadium, label: "Negative Divergence (Sink)"}
MC_D5@{shape: stadium, label: "Vorticity (The 'Curl')"}
MC_D6@{shape: stadium, label: "Irrotational Flow (Zero Curl)"}
MC_D7@{shape: stadium, label: "Divergence Theorem / Flux Balance"}

subgraph Velocity Field Equation

VFE_D1
VFE_D2
VFE_D3
VFE_D4
VFE_D5
VFE_D6
VFE_D7

subgraph Mathematical Concept
MC_D1
MC_D2
MC_D3
MC_D4
MC_D5
MC_D6
MC_D7

end

VFE_D1-->MC_D1
VFE_D2-->MC_D2
VFE_D3-->MC_D3
VFE_D4-->MC_D4
VFE_D5-->MC_D5
VFE_D6-->MC_D6
VFE_D7-->MC_D7

end


D1 e9@==>VFE_D1
D2 e10@==>VFE_D2
D3 e11@==>VFE_D3
D4 e12@==>VFE_D4
D5 e13@==>VFE_D5
D6 e14@==>VFE_D6
D7 e15@==>VFE_D7



classDef darkFill fill:#000,stroke:#333,stroke-width:2px,color:#fff,font-size:15pt
class E0,D1,D2,D3,D4,D5,D6,D7,Python,HTML,VFE_D1,VFE_D2,VFE_D3,VFE_D4,VFE_D5,VFE_D6,VFE_D7,MC_D1,MC_D2,MC_D3,MC_D4,MC_D5,MC_D6,MC_D7 darkFill

linkStyle 3,4,5,6,7,8,9,19,20,21,22,23,24 stroke:#FF5733,stroke-width:5px,stroke-dasharray:15;
linkStyle 10,11,25 stroke:#008585,stroke-width:5px,stroke-dasharray:15;
%%linkStyle 7,12 stroke:#f7c100,stroke-width:5px,stroke-dasharray:15;
%%linkStyle 9,14 stroke:#43b0f1,stroke-width:5px,stroke-dasharray:15;
%%linkStyle 11,13 stroke:#8ac926,stroke-width:5px,stroke-dasharray:15;

classDef animate stroke-dasharray: 5,5,stroke-dashoffset: 900,animation: dash 12s linear infinite;

%%class e0,e1,e2,e3,e4,e5,e6,e7,e8,e9,e10,e11,e12,e13,e14,e15 animate
```



## Vector Calculus and Conservative Force Dynamics

> The flowchart illustrates the conceptual and technical workflow for proving mathematical identities and demonstrating physical principles through interactive simulations.

- [Using Stokes' Theorem with a Constant Scalar Field](https://viadean.notion.site/Using-Stokes-Theorem-with-a-Constant-Scalar-Field-ST-CSF-2561ae7b9a328056bcc5dc2e105a1c35?source=copy_link)
- Deliverables: https://payhip.com/b/io8GT

```mermaid
---
config:
 flowchart:
  defaultRenderer: elk
---

flowchart LR
E0@{shape: doc, label: "Using Stokes' Theorem with a Constant Scalar Field"}
E1@{shape: doc, label: "How this principle applies to conservative forces in physics"}


D1@{shape: card, label: "Surface integral Proof"}
D2@{shape: card, label: "Conservative Force: Work Around a Closed Loop"}
D3@{shape: card, label: "Surface Integral Proof via Stokes' Theorem"}


Python@{shape: circ, label: "Python"}
HTML@{shape: circ, label: "HTML"}

subgraph Example
E0-->E1
end

subgraph Demo
D1
D2
D3
end

E0 e0@==>HTML e1@==>D1
E1 e2@==>Python e3@==>D2
Python e4@==>D3

MD_ST@{shape: hex, label: "$$\\int_S[(\\nabla \\phi) \\times(\\nabla \\psi)] \\cdot d S=\\oint_C \\phi(\\nabla \\psi) \\cdot d x$$"}
MD_EC@{shape: hex, label: "$$\\oint_C F \\cdot d r$$"}
MD_HE@{shape: hex, label: "$$\\oint_C A \\cdot d r$$"}

subgraph Mathematical Definition
MD_ST
MD_EC
MD_HE

end

E0 e5@==>MD_ST
D1 e6@==>MD_ST

E1 e7@==>MD_EC
D2 e8@==>MD_EC

E1 e9@==>MD_HE
D3 e10@==>MD_HE

SP_HE@{shape: stadium, label: "Hemisphere with a circular boundary curve"}
SP_CP@{shape: stadium, label: "Figure-eight closed path"}

subgraph Suface & Path
SP_HE
SP_CP
end

D1 e11@==>SP_HE
D3 e12@==>SP_HE
D2 e13@==>SP_CP


classDef darkFill fill:#000,stroke:#333,stroke-width:2px,color:#fff,font-size:15pt
class E0,E1,D1,D2,D3,Python,HTML,SP_CP,SP_HE,MD_EC,MD_HE,MD_ST darkFill

linkStyle 1,2,6 stroke:#FF5733,stroke-width:5px,stroke-dasharray:15;
linkStyle 3,4,5,8,10 stroke:#008585,stroke-width:5px,stroke-dasharray:15;
linkStyle 7,12 stroke:#f7c100,stroke-width:5px,stroke-dasharray:15;
linkStyle 9,14 stroke:#43b0f1,stroke-width:5px,stroke-dasharray:15;
linkStyle 11,13 stroke:#8ac926,stroke-width:5px,stroke-dasharray:15;

classDef animate stroke-dasharray: 5,5,stroke-dashoffset: 900,animation: dash 12s linear infinite;

%%class e0,e1,e2,e3,e4,e5,e6,e7,e8,e9,e10,e11,e12,e13 animate
```

