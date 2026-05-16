# Entity Relationship Diagram

## Cancellation and Orthogonality (Proof 32)

> - Proof 32: Using Stokes' Theorem with a Constant Scalar Field.
> - **Constant Scalars:** Proof 32 proves that if a scalar field is constant on a boundary, the resulting surface integral is **zero**.

- Deliverables: https://payhip.com/b/io8GT
- E-Product Hub: https://payhip.com/CDP

```mermaid
---
config:
 layout: elk
---
erDiagram
    DIVERGENCE-THEOREM ||--o{ SURFACE-INTEGRAL : "converts to Volume Integral (Proofs 24, 33, 35)"
    DIVERGENCE-THEOREM ||--o{ VOLUME-INTEGRAL : "relates Flux to Divergence (Proofs 24, 30, 33)"
    STOKES-THEOREM ||--o{ LINE-INTEGRAL : "converts to Surface Integral (Proofs 31, 32, 37)"
    STOKES-THEOREM ||--o{ SURFACE-INTEGRAL : "relates Circulation to Curl (Proofs 31, 32, 37)"
    VECTOR-FIELD ||--o{ DIVERGENCE-THEOREM : "provides components for analysis (Proofs 24, 27, 33, 35)"
    VECTOR-FIELD ||--o{ STOKES-THEOREM : "defines circulation behavior (Proofs 31, 32, 37)"
    VOLUME-INTEGRAL ||--o{ MASS-CALCULATION : "integrates variable density (Proofs 25)"
    SURFACE-INTEGRAL ||--o{ FLUX-CALCULATION : "measures flow through boundaries (Proofs 24, 27, 33)"
    LINE-INTEGRAL ||--o{ CIRCULATION-RESULT : "evaluates loop integrals (Proofs 31, 32, 37)"
    BOUNDARY-CONDITION ||--|| INTEGRAL-CANCELLATION : "forces zero result via orthogonality (Proofs 34, 35)"
    SCALAR-POTENTIAL ||--o{ IRROTATIONAL-FIELD : "generates curl-free components (Proofs 34)"
    GENERALIZED-CURL-THEOREM ||--|| STOKES-THEOREM : "derived via standard identities (Proofs 31, 37)"
    POWER-LAW-EXPONENT ||--o{ PARITY-SYMMETRY : "determines if Flux vanishes (Proofs 24, 35)"


classDef DeepCyan fill:#008585,stroke:#008585,stroke-width:2px,color:#fff,font-size:15pt
classDef Darkblue fill:#183e4b,stroke:#183e4b,stroke-width:2px,color:#fff,font-size:15pt
classDef BokChoy fill:#5b6654,stroke:#5b6654,stroke-width:2px,color:#fff,font-size:15pt
classDef Cypress fill:#526a40,stroke:#526a40,stroke-width:2px,color:#fff,font-size:15pt

class VECTOR-FIELD, STOKES-THEOREM,SURFACE-INTEGRAL, LINE-INTEGRAL, CIRCULATION-RESULT DeepCyan


```

