Complexity classes are sets of computational problems grouped by their inherent computational complexity, usually in terms of resource usage like time and memory. These classes serve as a framework for comparing the difficulty of different problems and understanding the limitations of algorithms.

#### Definition

A complexity class is defined by three main components:

1. **Type of Computational Problem**: Such as decision problems, function problems, counting problems, etc.
2. **Model of Computation**: The most commonly used is the Turing machine, but other models like probabilistic Turing machines, Boolean circuits, and quantum computers are also used.
3. **Bounded Computational Resource**: Such as time or memory, which is often expressed in terms of "big O" notation to describe upper bounds.

#### Examples

- **P**: The set of decision problems solvable by a deterministic Turing machine in polynomial time.
- **NP**: The set of decision problems for which a given solution can be verified in polynomial time.
- **EXPTIME**: The set of decision problems solvable in exponential time.

#### Properties

- **Deterministic vs Nondeterministic**: Some complexity classes are defined based on deterministic Turing machines (DTM), while others are based on nondeterministic Turing machines (NTM).
- **Resource Bounds**: Complexity classes often specify upper bounds on the resources (like time or space) required to solve the problems in the class.

#### Applications

- **Algorithm Analysis**: Helps in understanding which algorithms are most efficient for a given problem.
- **Computational Theory**: Provides insights into the inherent limitations of computation.

#### Connection to Other Topics

- **[[Computational Complexity]]**: Complexity classes are a subset of computational complexity theory.
- **[[Decision Problems]]**: Many complexity classes are defined in terms of decision problems.
- **[[Turing Machines]]**: The foundational model for defining most complexity classes.
- [[Mathematical Logic]]
- [[Automata Theory]]