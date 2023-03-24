
$$e^{i\theta} = \cos(\theta) + i\sin(\theta)$$
Euler's formula is a famous identity relating [complex](Complex%20Numbers.md) [exponentials](Exponentials.md) and [trigonometric functions](Functions.md). It can be proven in a variety of ways, most commonly by [Taylor expansions](Taylor%20Series.md) of the respective function definitions. Euler's formula forms the basis of Complex Analysis, and provides the definition for the [complex](Complex%20Numbers.md) [logorithm](Algebra/Functions/Logorithm.md).

## Proof
We'll need the powers of $i$, as well as the [Taylor Series](Taylor%20Series.md) for $\sin$, $\cos$, and $e^x$.
$$
\begin{align}
i^1 &= i \\
i^2 &= -1 \\
i^3 &= -i \\
i^4 &= 1\\
i^5 &= i
\end{align}
$$
and $$
\sin(x)=\sum_{n=0}^\infty \frac{(-1)^n x^{(2n + 1)}}{(2n+1)!} \quad\cos(x) = \sum_{n=0}^\infty \frac{(-1)^n x^{2n}}{(2n)!} \quad e^x = \sum_{n=0}^\infty \frac{x^n}{n!}
$$
$$\begin{align}
e^{i\theta} = \sum_{n=1}^\infty \frac{(i\theta)^n}{n!}
\end{align}
$$