Context-Free Languages (CFLs) are a class of formal languages that are more expressive than regular languages but less expressive than recursively enumerable languages. They are commonly used to describe the syntax of programming languages, natural languages, and are essential in the field of formal language theory.

#### Definition

A Context-Free Language is defined by a Context-Free Grammar (CFG), which consists of a set of production rules. A CFG is a 4-tuple (V,Σ,R,S)) where:

- V is a finite set of variables.
- Σ is a finite set of terminal symbols disjoint from VV.
- R is a finite set of production rules, mapping variables to strings of variables and terminals.
- S is the start variable.

#### Examples

- **Balanced Parentheses**: The language {(,)} with strings of balanced parentheses is a context-free language.
- **Arithmetic Expressions**: Languages that represent valid arithmetic expressions are often context-free.

#### Properties

- **Closure Properties**: CFLs are closed under union, concatenation, and Kleene star but not under intersection and complement.
- **Parsing**: Context-free languages can be parsed by Pushdown Automata.

#### Applications

- **Compiler Design**: Syntax of most programming languages is defined using context-free grammars.
- **Natural Language Processing**: Some aspects of natural languages can be modeled using context-free languages.

#### Connection to Other Topics

- **[[Formal Languages]]**: Context-Free Languages are a specific type of formal language.
- **[[Automata Theory]]**: Pushdown Automata are used to recognize context-free languages.
- **[[Computational Complexity]]**: Some decision problems related to context-free languages are NP-complete.

 [[Mathematical Logic]]
- [[Automata Theory]]