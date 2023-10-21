The Leibniz Integral Rule, also known as differentiation under the integral sign, is a powerful tool in calculus that allows the interchange of differentiation and integration under certain conditions. This rule is widely used in mathematical analysis, physics, and engineering to simplify complex integrals.

#### Definition:

The Leibniz Integral Rule is mathematically stated as:

$$\frac{d}{dx}(\int_{a(x)}^{b(x)} f(x, t)dt) = f(x, b(x)) \frac{d}{dx}b(x) - f(x, a(x)) \frac{d}{dx}a(x) + \int_{a(x)}^{b(x)} \frac{\partial}{\partial x}f(x, t) dt$$

Here, f(x,t) is a function of both x and t, and a(x)a(x) and b(x) are the limits of integration that may also depend on xx.

#### Explanation:

The rule essentially states that you can differentiate an integral with respect to xx by differentiating the integrand f(x,t) and the limits a(x) and b(x) appropriately. This is particularly useful when the integral itself is too complex to solve directly.

#### Examples:

1. **Constant Limits**: If a(x)=aa(x)=a and b(x)=bb(x)=b are constants, the rule simplifies to:

ddx(∫abf(x,t) dt)=∫ab∂∂xf(x,t) dtdxd​(∫ab​f(x,t)dt)=∫ab​∂x∂​f(x,t)dt

2. **Variable Upper Limit**: If a(x)=aa(x)=a is constant and b(x)=xb(x)=x, the rule becomes:

ddx(∫axf(x,t) dt)=f(x,x)+∫ax∂∂xf(x,t) dtdxd​(∫ax​f(x,t)dt)=f(x,x)+∫ax​∂x∂​f(x,t)dt

#### Properties:

1. **Continuity**: The function f(x,t)f(x,t) and its partial derivative ∂∂xf(x,t)∂x∂​f(x,t) should be continuous in the region of interest.
2. **Limits**: The limits a(x)a(x) and b(x)b(x) should be continuous and have continuous derivatives.

#### Applications:

1. **Mathematical Analysis**: Used in solving complex integrals.
2. **Physics**: In thermodynamics and quantum mechanics.
3. **Engineering**: In control theory and signal processing.

#### Connection to Other Topics:

- [[Fundamental Theorem of Calculus]]: The Leibniz Integral Rule can be derived using the fundamental theorem of calculus.
- [[Fubini's Theorem]]: Related to the interchange of the order of integration.
- [[Calculus]]