A Reimann sum is an approximation of an integral by a finite sum. The sum is performed by dividing the region bounded by the curve into several regular shapes (typically rectangles), and summing their respective areas. The [integral](Integration.md) is commonly defined by the [limit](Limit.md) of a Reimann sum as the number of subintervals (denoted $n$) goes to infinity.

## Definition
Let $f: [a,b] \to \mathbb{R}$ be a function defined on a closed interval $[a, b] \in \mathbb{R}$, and $P = (x_0, x_1, \dots, x_n)$ be a partition of $[a, b]$.
A **reimann sum** $S$ over $f$ over $[a, b]$ with partition $P$ is defined as
$$S = \sum_{i = 1}^n f(x_i^*) \Delta x_i$$
were $\Delta x_i = x_i - x_{x - 1}$ and $x_i^* \in [x_{i-1}, x_i]$.
