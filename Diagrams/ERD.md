# Entity Relationship Diagram

[E-Product Hub](https://payhip.com/CDP)



## Vector Field Properties | Cancellation and Orthogonality 

> Proof 34: Integral of a Curl-Free Vector Field.

- [Integral of a Curl-Free Vector Field](https://viadean.notion.site/Integral-of-a-Curl-Free-Vector-Field-CVF-2571ae7b9a3280d8a368c3ffac5d0b26?source=copy_link)
- [Deliverables](https://payhip.com/b/tgrVH)

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


class SCALAR-POTENTIAL,IRROTATIONAL-FIELD,BOUNDARY-CONDITION, INTEGRAL-CANCELLATION BokChoy

```





---

## Integral Conversion | Vector Field Properties | Geometric Geometry

> - Proof 33: Verification of the Divergence Theorem for a Rotating Fluid Flow.
> - Proof 33 serves as a bridge between microscopic differential properties and macroscopic boundary integrals by verifying field behavior within a specific spatial geometry.

- [Verification of the Divergence Theorem for a Rotating Fluid Flow](https://viadean.notion.site/Verification-of-the-Divergence-Theorem-for-a-Rotating-Fluid-Flow-DT-RFF-2571ae7b9a328091ad62deba6f8d1715?source=copy_link)
- [Deliverables](https://payhip.com/b/Q9Zjy)

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

class DIVERGENCE-THEOREM,VOLUME-INTEGRAL, SURFACE-INTEGRAL,VECTOR-FIELD,FLUX-CALCULATION  DeepCyan


```



## Cancellation and Orthogonality (Proof 32)

> - Proof 32: Using Stokes' Theorem with a Constant Scalar Field.
> - **Constant Scalars:** Proof 32 proves that if a scalar field is constant on a boundary, the resulting surface integral is **zero**.

- [Using Stokes' Theorem with a Constant Scalar Field](https://viadean.notion.site/Using-Stokes-Theorem-with-a-Constant-Scalar-Field-ST-CSF-2561ae7b9a328056bcc5dc2e105a1c35?source=copy_link)
- [Deliverables](https://payhip.com/b/io8GT)

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

