The Fundamental Theorem of Calculus (FTC) is a cornerstone in the field of calculus, bridging the gap between the concept of a derivative and that of an integral. It serves as the theoretical underpinning for many techniques in applied mathematics, physics, engineering, and computer science.

#### Definition

The Fundamental Theorem of Calculus consists of two parts:

1. **First Part**: If F(x) is an antiderivative of f(x) on an interval $[a,b]$, then

$∫_a^b f(x) dx=F(b)−F(a)$

2. **Second Part**: If f(x) is a continuous real-valued function defined on a closed interval $[a,b]$,, then the function F(x) defined by

$F(x)=∫_a^xf(t) dt$

is continuous on $[a,b]$, differentiable on the open interval (a,b), and F′(x)=f(x) for all xx in (a,b).

#### Explanation

The first part of the theorem provides a way to evaluate definite integrals using antiderivatives, while the second part shows that the process of differentiating and integrating are essentially inverse operations. In essence, the theorem provides a link between the geometric interpretation of an integral as the area under a curve and the algebraic process of finding antiderivatives.

#### Examples

1. f(x)=x2f(x)=x2  
    The antiderivative F(x)=x33F(x)=3x3​. By the first part of FTC,

∫01x2 dx=133−033=13∫01​x2dx=313​−303​=31​

2. f(x)=sin⁡(x)f(x)=sin(x)  
    The antiderivative F(x)=−cos⁡(x)F(x)=−cos(x). By the second part of FTC,

F′(x)=−cos⁡′(x)=sin⁡(x)=f(x)F′(x)=−cos′(x)=sin(x)=f(x)

#### Properties

- Applicability: The function must be continuous on the closed interval for the second part.
- Uniqueness: The antiderivative is unique up to a constant.

#### Applications

- In physics, the theorem is used to derive equations of motion.
- In engineering, it is used in signal processing and control theory.
- In economics, it is used to find consumer and producer surplus.

#### Connection to Other Topics

- [[Differentiation]]: The process of finding the derivative of a function.
- [[Integration]]: The process of finding the integral of a function.
- [[Continuous Functions]]: The theorem requires the function to be continuous.
- [[Calculus]]