# Tensor Analysis of the Magnetic Stress Tensor

> The analysis of the magnetic field tensor ( $F_{i j}$ ) demonstrates the power of tensor notation in physics, showing how its inherent anti-symmetry ( $F_{i j}=-F_{j i}$ ) leads directly to the symmetry of its square, $F_{i j} F_{j k}$, a necessary condition for a physical stress tensor. The derivation relies heavily on the Levi-Civita identity to compute the tensor product, yielding the key result $F_{i j} F_{j k}=B^2 \delta_{i k}-B_i B_k$, which links the fundamental magnetic field tensor to the standard vector dyadic product. Finally, by expressing the scalar field energy ( $B^2$ ) as a trace of the tensor product ( $B^2=\frac{1}{2} F_{i k} F_{k i}$ ), the entire Maxwell stress tensor ( $T_{i k}$ ) is converted into a form defined exclusively by the magnetic field tensor $F_{i j}$, ensuring mathematical consistency and demonstrating the elegance of field-based tensor formalisms.

## Key takeaways

- Anti-Symmetry and Products: The anti-symmetry of the magnetic field tensor ( $F_{i j}= -F_{j i}$ ) leads to specific symmetry properties in its products. Specifically, the product $F_{i j} F_{j k}$ is proven to be symmetric ( $F_{i j} F_{j k}=F_{k j} F_{j i}$ ), a crucial property for tensors representing physical quantities like stress.
- Contraction and the Levi-Civita Identity: The core of the calculation involves using the Levi-Civita identity to contract the product of two $\varepsilon_{i j k}$ tensors, collapsing them into combinations of Kronecker delta symbols $\left(\delta_{i k}\right)$. This is the standard method for converting products of cross-products (which $F_{i j}$ represents) into dot products and tensor products.
- Result of the Contraction: The computation $F_{i j} F_{j k}=B^2 \delta_{i k}-B_i B_k$ is an essential identity in magnetostatics. It demonstrates that the tensor product of the magnetic field tensor squared is directly related to the vector dyadic product ( $B_i B_k$ ) and the scalar magnitude squared ( $B^2$ ).
- Tensor Substitution and Consistency: The final step (part c) shows how to translate physical equations from vector notation ( $B_i$ ) to tensor notation ( $F_{i j}$ ). This process requires expressing the scalar term $B^2$ as the trace of the tensor product, $B^2=\frac{1}{2} F_{i k} F_{k i}$, ensuring the final stress tensor equation, $T_{i k}$, is internally consistent and expressed purely in terms of the fundamental field tensor $F_{i j}$.
- Maxwell Stress Tensor Structure: The final expression for the Maxwell stress tensor, $T_{i k} \propto\left(\ldots \delta_{i k}-F_{i j} F_{j k}\right)$, highlights its structure: it's composed of a term proportional to the identity tensor (representing pressure) and a term proportional to the tensor square of the field (representing tension/shear along the field lines).

### Magnetic Stress Tensor via Field Tensors | Audio

[![Watch the video](https://img.youtube.com/vi/AUKwF8zkG_A/maxresdefault.jpg)](https://youtu.be/AUKwF8zkG_A)

### [Watch this video on YouTube](https://youtu.be/AUKwF8zkG_A)

## how the magnetic stress tensor decomposes to show that magnetic fields simultaneously exert tension and pressure | Demo

> The visualizations powerfully confirm that the magnetic field tensor product ( $F_{i j} F_{j k}$ ) and the Maxwell Stress Tensor ( $T_{i k}$ ) are defined by the interplay between isotropic energy and field direction. The tensor product $F_{i j} F_{j k}$ is constructed by subtracting the highly directional dyadic product $\left(B_i B_k\right)$ from the uniform isotropic term $\left(B^2 \delta_{i k}\right)$. This leads to the fundamental physical interpretation of $T_{i k}$, which is composed of the dyadic term (representing tension/pulling force along the field lines) and the isotropic term (representing pressure perpendicular to the field lines). When the components are summed, the resulting $T_{i k}$ tensor is always positive along the field direction (net tension) and negative perpendicular to the field direction (net pressure/compression), precisely illustrating the classic physical effect of magnetic fields on surrounding media.

[![Watch the video](https://img.youtube.com/vi/qHNxWVs3a-8/maxresdefault.jpg)](https://youtu.be/qHNxWVs3a-8)

### [Watch this video on YouTube](https://youtu.be/qHNxWVs3a-8)

## Published web

- [Tensor Analysis of the Magnetic Stress Tensor](https://viadean.notion.site/Tensor-Analysis-of-the-Magnetic-Stress-Tensor-2891ae7b9a3280a5b818fb2e6651fa91)
- [how the magnetic stress tensor decomposes to show that magnetic fields simultaneously exert tension and pressure](https://viadean.notion.site/how-the-magnetic-stress-tensor-decomposes-to-show-that-magnetic-fields-simultaneously-exert-tension--2891ae7b9a3280e4b64dc1816700d436)
- [Magnetic Stress Tensor via Field Tensors](https://viadean.notion.site/Magnetic-Stress-Tensor-via-Field-Tensors-2891ae7b9a3280c89c77f56c3caec85c)

## Language

`Python`

