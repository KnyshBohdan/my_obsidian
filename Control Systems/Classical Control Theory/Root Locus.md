Root locus analysis is a fundamental technique in control theory and stability theory. It provides a graphical method for examining how the roots of a system change with variation of a certain system parameter, typically a gain within a feedback system. This technique is crucial for determining the stability of a system and is widely used in classical control theory.

## Definition

The root locus of a feedback system is the graphical representation in the complex s-plane of the possible locations of its closed-loop poles for varying values of a certain system parameter. The points that are part of the root locus satisfy the angle condition, and the value of the parameter for a certain point of the root locus can be obtained using the magnitude condition.

## Explanation

Root locus analysis involves plotting the poles of the closed-loop transfer function in the complex s-plane as a function of a gain parameter. This method helps in understanding how the system's behavior changes with varying gain values. For instance, lines of constant damping ratio and natural frequency can be drawn, allowing for the selection of a gain that achieves desired system characteristics.

## Examples

Consider a feedback system with a characteristic equation $s^3+3s^2+(5+K)s+(1+3K)=0$. The root locus of this system can be plotted to observe how the roots (poles) of this equation change as the gain KK varies.

## Properties

- The root locus provides the location of closed-loop poles as the gain varies.
- It does not affect the location of the zeros; open-loop zeros are the same as closed-loop zeros.
- The angle condition and magnitude condition are used to determine if a point in the s-plane is part of the root locus.

## Applications

Root locus analysis is used in designing control systems, particularly in determining the stability and dynamic response of feedback systems. It is also used in designing various types of controllers like PI, PD, and PID controllers.

## Connection to Other Topics

- [[Control Theory]]: Root locus is a fundamental concept in control theory, used for analyzing system stability.
- [[Feedback Systems]]: It specifically applies to feedback systems, helping in stability analysis and controller design.
- [[Pole-Zero Plot]]: Root locus is closely related to pole-zero plots, as it involves the movement of poles in the s-plane.