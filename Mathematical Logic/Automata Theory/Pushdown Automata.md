A Pushdown Automaton (PDA) is an automaton that comprises a finite automaton along with a stack, which can be thought of as auxiliary memory. A PDA is formally defined as a 7-tuple (Q,Σ,Γ,δ,q0,Z0,F), where:

- Q is a finite set of states.
- Σ is a finite set of input symbols (input alphabet).
- Γ is a finite set of stack symbols (stack alphabet).
- $δ:Q×Σ_ϵ×Γ_ϵ→2^{Q×Γ_ϵ}$​ is the transition function.
- q0​ is the initial state, q0∈Q.
- Z0 is the initial stack symbol, Z0∈Γ.
- F is a set of accepting states, F⊆Q.

### Operational Semantics

A PDA processes input strings while manipulating its stack. The transition function δδ decides the next state and stack operation (push, pop, or do nothing) based on the current state, input symbol, and top stack symbol.

## Examples

1. **PDA for Balanced Parentheses**: A PDA can be designed to accept strings of balanced parentheses. In this PDA, an opening parenthesis `(` is pushed onto the stack, and a closing parenthesis `)` results in a pop operation.
    
2. **PDA for Palindromes**: Another common example is designing a PDA that accepts palindromic strings over some alphabet ΣΣ. The stack is used to remember the first half of the string, which is then matched against the second half.
    

## Properties

- **Non-determinism**: PDAs can be non-deterministic, which gives them more computational power for recognizing context-free languages.
- **Closure Properties**: PDAs are closed under union, concatenation, and Kleene star operations.
- **Decidability**: It is decidable whether a given PDA accepts a given string, but it is undecidable whether the language recognized by a PDA is empty.

## Applications

- **Syntax Parsing in Compilers**: PDAs serve as the theoretical foundation for parsing algorithms in compilers.
- **Modeling Nested Structures**: PDAs are used to model nested structures like parentheses in arithmetic expressions and XML/HTML tags.

## Connection to Other Topics

- **[[Context-Free Grammars (CFG)]]**: Each PDA is associated with a context-free grammar (CFG). The languages recognized by PDAs are exactly the context-free languages.
- **[[Finite Automata]]**: A PDA generalizes the concept of a finite automaton by adding a stack. Finite automata can be thought of as PDAs without a stack.
- **[[Standard Turing Machines]]**: PDAs are less powerful than Turing machines, which can simulate PDAs but not vice versa.
- **[[Chomsky Hierarchy]]**: PDAs recognize languages in the second level of the Chomsky hierarchy, known as context-free languages.
 [[Mathematical Logic]]
- [[Automata Theory]]