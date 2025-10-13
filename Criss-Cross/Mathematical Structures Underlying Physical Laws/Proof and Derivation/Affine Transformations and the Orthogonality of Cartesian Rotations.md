# Affine Transformations and the Orthogonality of Cartesian Rotations

> The derivation shows that a Cartesian coordinate transformation, which is an affine transformation ( $x^{h^{\prime}}=R_i^{i^{\prime}} x^i+A^{i^{\prime}}$ ) that preserves the form of the metric tensor ( $g_{i j}=\delta_{i j}$ ), necessarily implies that the transformation matrix $R$ is orthogonal. This is mathematically expressed as the orthogonality condition, $R_i^{i^{\prime}} R_j^{i^{\prime}}=\delta_{i j}$. This requirement ensures that the transformation represents a rigid-body motion (rotation and/or reflection) in Euclidean space. Furthermore, using this orthogonality condition, the inverse relationship can be derived and shown to have the same affine form: $x^i=R_i^{i^{\prime}} x^{i^{\prime}}+B^i$, where $B^i$ is a new constant translation vector related to $A^{i^{\prime}}$.

## Key takeaways

1. Condition for a Cartesian Transformation: The defining characteristic of a transformation between two Cartesian coordinate systems is that the metric tensor remains invariant, specifically $g_{i j}=\delta_{i j}$ (the Kronecker delta) in both systems.

2. Orthogonality of the Rotation Matrix: The requirement that the metric tensor is preserved $\left(\delta_{i^{\prime} j^{\prime}}=\frac{\partial x^i}{\partial x^{i^{\prime}}} \frac{\partial x^i}{\partial x^{j^{\prime}}}\right)$ implies the orthogonality condition for the rotation matrix $R$ :

   $$ R_i^{i^{\prime}} R_j^{i^{\prime}}=\delta_{i j} $$

   This shows that the transformation matrix must be a rotation and/or reflection (proper or improper rotation).

3. Inverse Transformation is also Affine: The inverse transformation, derived using the orthogonality of R, takes the same affine form as the forward transformation:

$$ x^i=R_i^{i^{\prime}} x^{i^{\prime}}+B^i $$

where the new translation vector $B^i$ is directly related to the original $A^{i^{\prime}}$ and the rotation matrix $R$ by $B^i=-R_i^{i^{\prime}} A^{i^{\prime}}$.

1. Meaning of Affine/Cartesian Transformation: An affine transformation that preserves the form of the metric (a Cartesian transformation) is specifically a rigid-body motion (rotation and translation) in Euclidean space.

### The Orthogonality and Invariance of Cartesian Affine Transformations | Audio

[![Watch the video](https://img.youtube.com/vi/KGn-qPIHpOc/maxresdefault.jpg)](https://youtu.be/KGn-qPIHpOc)

### [Watch this video on YouTube](https://youtu.be/KGn-qPIHpOc)

## rigid-body motion using an orthogonal affine transformation | Demo

> The use of an orthogonal matrix (R) in the affine transformation formula $\left( x ^{\prime}= R x + A \right)$ ensures that the transformation is a rigid-body motion. This means the object is only rotated and translated, and its intrinsic properties-specifically its shape, size, and internal distances-are perfectly preserved at all times during the animation. The animated demo is the fundamental relationship between linear algebra and geometry.

[![Watch the video](https://img.youtube.com/vi/a80E7Rh2KcQ/maxresdefault.jpg)](https://youtu.be/a80E7Rh2KcQ)

### [Watch this video on YouTube](https://youtu.be/a80E7Rh2KcQ)

## Published web

- [Affine Transformations and the Orthogonality of Cartesian Rotations](https://viadean.notion.site/Affine-Transformations-and-the-Orthogonality-of-Cartesian-Rotations-2871ae7b9a32805e8268e6823e0341de?source=copy_link)
- [rigid-body motion using an orthogonal affine transformation](https://viadean.notion.site/rigid-body-motion-using-an-orthogonal-affine-transformation-2871ae7b9a328072b598e7aac6a554b8?source=copy_link)
- [The Orthogonality and Invariance of Cartesian Affine Transformations](https://viadean.notion.site/The-Orthogonality-and-Invariance-of-Cartesian-Affine-Transformations-2871ae7b9a32802a8561ebe4f3f453cd?source=copy_link)

## Language

`Python`