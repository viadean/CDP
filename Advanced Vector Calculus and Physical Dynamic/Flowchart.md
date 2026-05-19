# Flowchart

## Vector Calculus and Conservative Force Dynamics

> The flowchart illustrates the conceptual and technical workflow for proving mathematical identities and demonstrating physical principles through interactive simulations.

- Deliverables: https://payhip.com/b/io8GT
- E-Product Hub: https://payhip.com/CDP

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

