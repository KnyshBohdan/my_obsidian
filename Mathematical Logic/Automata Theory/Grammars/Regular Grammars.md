Regular grammars are a type of formal grammar that describe regular languages. They are simpler than other types of grammars, such as context-free grammars, and are closely related to finite automata.

#### Definition

A regular grammar is a formal grammar (N,Σ,P,S) where N is a set of non-terminal symbols, Σ is a set of terminal symbols, P is a set of production rules, and S is the start symbol. In a right-regular grammar, all production rules in P are of one of the following forms:

A→aB or A→a or A→ϵ

Here, A,B,S∈N are non-terminal symbols, a∈Σ is a terminal symbol, and ϵϵ denotes the empty string.

#### Examples

1. **Grammar for a∗: A right-regular grammar for the language of all strings consisting of 'a's can be G=({S},{a},{S→aS,S→ϵ},S).

#### Properties

- **Expressive Power**: Every regular grammar describes a regular language.
- **Directionality**: Regular grammars can be right-regular or left-regular, but not a mix of both.

#### Applications

- **Lexical Analysis**: Regular grammars are often used in the lexical analysis phase of compilers.
- **Text Pattern Matching**: They are also used in text processing utilities like grep.

#### Connection to Other Topics

- **[[Regular Languages]]**: Regular grammars are used to define regular languages.
- **[[Finite Automata]]**: Regular languages can also be recognized by finite automata, establishing a link between regular grammars and automata theory.
- **[[Formal Language Theory]]**: Regular grammars are a subset of formal grammars, which are studied extensively in formal language theory.
 [[Mathematical Logic]]
- [[Automata Theory]]