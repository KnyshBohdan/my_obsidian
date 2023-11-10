The Linear Quadratic Regulator (LQR) is a fundamental technique in optimal control theory, used to operate dynamic systems at minimum cost. It is crucial in fields like aerospace, robotics, and any domain involving the control of dynamic systems. Its importance lies in its ability to provide efficient, robust control strategies for systems described by linear dynamics and a quadratic cost function.

## Definition

The LQR problem involves a system with dynamics described by linear differential equations and a cost function that is quadratic. The goal is to determine a control input that minimizes this cost function. Mathematically, for a continuous-time linear system, the state equation is given by $\dot{x}=Ax+Bu$, where x is the state vector and u is the control input. The cost function J to be minimized is of the form $J=∫(x^TQx+u^TRu+2x^TNu)dt$, where Q, R, and N are weighting matrices.

## Explanation

The LQR algorithm finds a state-feedback control law that minimizes the cost function. This control law is typically of the form u=−Kx where K is a gain matrix calculated based on the system dynamics and the cost function. The solution involves solving a Riccati differential equation. The LQR approach is particularly powerful because it provides a systematic way to design controllers, ensuring stability and performance.

## Examples

1. **Aircraft Pitch Control**: In aircraft control, LQR can be used to design a pitch controller that minimizes deviations from a desired flight path while keeping control inputs (like elevator deflection) smooth and minimal.
    
2. **Robot Arm Movement**: For a robotic arm, LQR can optimize the movement to be smooth and accurate, minimizing the energy used and wear on the mechanical parts.
    

## Properties

- **Robustness**: LQR controllers are inherently robust with guaranteed gain and phase margins.
- **Optimality**: They provide an optimal control strategy under the given linear and quadratic assumptions.
- **Versatility**: LQR can be applied to both finite and infinite time horizons, and to both continuous and discrete-time systems.

## Applications

LQR is widely used in various fields, including:

- **Aerospace**: For flight control systems.
- **Automotive**: In vehicle dynamics control.
- **Robotics**: For controlling robotic systems.
- **Process Control**: In chemical and industrial process control systems.

## Connection to Other Topics

- [[Linear–quadratic–Gaussian (LQG) Control]]: LQR is a subset of the more general LQG problem, which also considers system noise.
- [[Model Predictive Control (MPC)]]: When LQR is run with a receding horizon, it becomes a form of MPC.
- [[Pole Placement]]: An alternative method in control theory, where the relationship between controller parameters and behavior is more direct.
- [[Control Theory]]