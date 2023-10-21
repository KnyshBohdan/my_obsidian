The Mean Value Theorem (MVT) is a fundamental theorem in calculus that describes the behavior of differentiable functions over closed intervals. It is essential for understanding how a function changes and is widely used in fields like physics, engineering, and economics to analyze rates of change.

#### Definition

Let f:$[a,b]$→R be a function that is continuous on the closed interval $[a,b]$ and differentiable on the open interval  (a,b). Then, there exists a point c in  (a,b) such that:

$$f'(c) = \frac{f(b) - f(a)}{b - a}$$

#### Explanation

The theorem states that if you have a differentiable function on an interval, then there exists at least one point within that interval where the instantaneous rate of change (the derivative) is equal to the average rate of change over the entire interval. Imagine driving a car from point A to point B; the theorem guarantees that at some moment, your speed will equal your average speed for the trip.

#### Examples

1. f(x)=x2f(x)=x2 on [0,2][0,2]  
    f′(x)=2xf′(x)=2x. By MVT, there exists cc in (0,2)(0,2) such that f′(c)=2c=4−02−0=2f′(c)=2c=2−04−0​=2. One such cc is c=1c=1.
    
2. f(x)=sin⁡(x)f(x)=sin(x) on [0,π][0,π]  
    f′(x)=cos⁡(x)f′(x)=cos(x). By MVT, there exists cc in (0,π)(0,π) such that f′(c)=cos⁡(c)=0−0π−0=0f′(c)=cos(c)=π−00−0​=0. One such cc is c=π2c=2π​.
    

#### Properties

- Applicability: The function must be continuous on the closed interval and differentiable on the open interval.
- Existence: Guarantees the existence of at least one such point cc, but not its uniqueness.

#### Applications

- In physics, the theorem is used to relate average velocity to instantaneous velocity.
- In economics, it is used to analyze marginal cost and marginal revenue.
- In computer science, it is used in algorithms that require an understanding of function behavior, such as optimization algorithms.

#### Connection to Other Topics

- [[Derivatives]]: The Mean Value Theorem is fundamentally about understanding derivatives.
- [[Integrals]]: The theorem can be extended to the Mean Value Theorem for Integrals, which relates the average value of a function to its integral.
- [[Optimization]]: In optimization problems, understanding where a function attains its average value can be crucial.
- [[Differential Equations]]: The theorem is often used in the uniqueness proofs for solutions to differential equations.
- [[Numerical Analysis]]: The theorem is used in error analysis for numerical methods like Newton's method.
- [[Calculus]]