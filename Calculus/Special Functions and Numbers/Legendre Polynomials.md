Legendre Polynomials, named after Adrien-Marie Legendre, are a system of complete and orthogonal polynomials with numerous applications in mathematics, physics, and engineering. They are particularly important for solving problems involving Laplace's equation in spherical coordinates and appear in multipole expansions in electrostatics.

#### Definition:

The Legendre Polynomials $P_n(x$) are solutions to Legendre's differential equation:

$$(1−x^2)\frac{d^2 P_n}{d x^2}−2x \frac{dP_n}{dx}+n(n+1)P_n(x)=0$$

where n is a non-negative integer.

#### Explanation:

Legendre Polynomials can be defined in multiple ways, including via generating functions, orthogonality conditions, and differential equations. They are orthogonal over the interval [−1,1][−1,1] with respect to the weight function w(x)=1. They are also complete, meaning any piecewise continuous function on the interval [−1,1][−1,1] can be expanded as a series of Legendre Polynomials.

#### Examples:

- **First Few Polynomials**: P0(x)=1, P1(x)=x, P2(x)=12(3x2−1)
- **Applications in Physics**: Used in the expansion of the Newtonian potential 1/∣x−x′∣

#### Properties:

- **Orthogonality**: ∫−11Pm(x)Pn(x)dx=22n+1δmn∫−11​Pm​(x)Pn​(x)dx=2n+12​δmn​
- **Completeness**: Any piecewise continuous function f(x)f(x) on [−1,1][−1,1] can be expanded as fn(x)=∑ℓ=0naℓPℓ(x)fn​(x)=∑ℓ=0n​aℓ​Pℓ​(x)

#### Applications:

- **Electrostatics**: Used in multipole expansions.
- **Quantum Mechanics**: Appear in the solution of the Schrödinger equation for a central force.

#### Connection to Other Topics:

- [[Differential Equations]]: They are solutions to Legendre's differential equation.
- [[Orthogonal Polynomials]]: They are one of the classical orthogonal polynomial systems.
- [[Calculus]]