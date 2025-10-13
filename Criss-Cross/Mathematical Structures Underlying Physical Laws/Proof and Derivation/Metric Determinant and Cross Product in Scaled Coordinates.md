# Metric Determinant and Cross Product in Scaled Coordinates

> The problem demonstrated how coordinate scaling affects the geometry of space, starting with the transformation $y^3=2 x^3$. This scaling leads to a diagonal metric tensor where only the $g_{33}$ component is altered, becoming 1 / 4, resulting in a metric determinant of $g=1 / 4$. The key implication is how this value scales the vector calculus operations: the Levi-Civita density $\eta^{a b c}$, crucial for the cross product, is scaled by $1 / \sqrt{g}=2$. Consequently, the contravariant components of the cross product, $(v \times w)^a=\eta^{a b c} v_b w_c$, are simply twice the magnitude of the standard Cartesian cross product involving the covariant components of the vectors, illustrating the general principle that all tensor operations in non-Cartesian coordinates must incorporate factors derived from the metric determinant.

## Key takeaways

1. Metric Tensor Calculation (Diagonal Metrics):

   - For an orthogonal coordinate transformation where $y^a$ only depends on $x^a$ (like scaling a single axis), the new metric tensor $g_{a b}$ is diagonal.
   - The diagonal components are determined by the scaling factors of the coordinate differentials:

   $$ g_{a a}=\sum_i\left(\frac{\partial x^i}{\partial y^a}\right)^2 $$

   - For the transformation $y^3=2 x^3$ (or $x^3=\frac{1}{2} y^3$ ), the metric component is $g_{33}= \left(\frac{1}{2}\right)^2=\frac{1}{4}$.

2. Metric Determinant and Volume Element:

   - The metric determinant $g$ quantifies how the local volume element is scaled. Since the metric was diagonal, the determinant is the product of the diagonal elements:

   $$ g=1 \cdot 1 \cdot \frac{1}{4}=\frac{1}{4} $$

   - The square root $\sqrt{g}=\frac{1}{2}$ relates the volume element in the new coordinates ( $\sqrt{g} d y^1 d y^2 d y^3$ ) to the Cartesian volume element ( $d x^1 d x^2 d x^3$ ).

3. Relating Levi-Civita Density and Symbol:

   - The Levi-Civita density $\left(\eta^{a b c}\right)$, used in tensor expressions for curl and cross products, is related to the standard Levi-Civita symbol $\left(\varepsilon^{a b c}\right)$ by the metric determinant:

   $$ \eta^{a b c}=\frac{1}{\sqrt{g}} \varepsilon^{a b c} $$

   - In this specific system, the density is $\eta^{a b c}=\frac{1}{1 / 2} \varepsilon^{a b c}=2 \varepsilon^{a b c}$. The scaling factor is 2 .

4. Cross Product in General Coordinates:

   - The contravariant components of the cross product $(v \times w)^a$ are calculated using the Levi-Civita density and the covariant components of the vectors:

   $$ (v \times w)^a=\eta^{a b c} v_b w_c $$

   - The result is a standard cross product formula multiplied by the scaling factor $1 / \sqrt{ g }= 2$:

   $$ (v \times w)^1= 2 \left( v _{ 2 } w _{ 3 }- v _{ 3 } w _{ 2 }\right) $$

### Impact of Coordinate Scaling on Metric and Cross Product | Audio

[![Watch the video](https://img.youtube.com/vi/7rEu-3WLTBg/maxresdefault.jpg)](https://youtu.be/7rEu-3WLTBg)

### [Watch this video on YouTube](https://youtu.be/7rEu-3WLTBg)

## the metric determinant scales vector operations | Demo

> The dynamic movement in the animation clearly demonstrates the effect of the $1 / \sqrt{ g }= 2$ scaling factor. As the input covariant component $v _{ 3 }$ changes, the resulting Red Vector (the correct scaled cross product $u$ ) is visibly twice the magnitude of the Gray Vector (the unscaled, standard Cartesian cross product) for the resulting $u ^{ 1 }$ and $u ^{ 2 }$ components. This doubling confirms that the density $\eta^{ abc }=2 \varepsilon^{ abc }$ is correctly applied, ensuring the cross product result is geometrically correct within the transformed coordinate system. In essence, the metric must be incorporated to properly relate the covariant inputs to the contravariant output.

[![Watch the video](https://img.youtube.com/vi/PGf3_LCKY6U/maxresdefault.jpg)](https://youtu.be/PGf3_LCKY6U)

### [Watch this video on YouTube](https://youtu.be/PGf3_LCKY6U)

## Published web

- [Metric Determinant and Cross Product in Scaled Coordinates](https://viadean.notion.site/Metric-Determinant-and-Cross-Product-in-Scaled-Coordinates-2841ae7b9a3280b7808eebedda2af506)
- [the metric determinant scales vector operations](https://viadean.notion.site/the-metric-determinant-scales-vector-operations-2841ae7b9a328089a876fca7e789d284)
- [Impact of Coordinate Scaling on Metric and Cross Product](https://viadean.notion.site/Impact-of-Coordinate-Scaling-on-Metric-and-Cross-Product-2841ae7b9a3280599641cb930f88720f)

## Language

`Python`