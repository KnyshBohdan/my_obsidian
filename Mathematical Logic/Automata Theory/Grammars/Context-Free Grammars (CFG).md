Context-Free Grammars (CFG) are a cornerstone in formal language theory, providing a way to describe syntactic rules for languages. They are widely used in computer science for parsing programming languages and in linguistics for modeling natural languages.

#### Definition

A Context-Free Grammar G is defined by a 4-tuple (V,Σ,R,S), where:

- V is a finite set of nonterminal symbols or variables.
- Σ is a finite set of terminal symbols, disjoint from VV.
- R is a finite set of production rules of the form A→α, where A is a nonterminal and αα is a string of terminals and/or nonterminals.
- S is the start symbol, an element of V.

#### Examples

1. **Parenthesis Matching**: The grammar with terminal symbols "(" and ")" and production rules S→SS, S→(S), S→() describes well-formed nested parentheses.
2. **Palindromes**: The grammar G=({S},{a,b},P,S) with productions S→aSa, S→bSb, S→ϵ generates palindromes.

#### Properties

- **Deterministic**: Some CFGs are deterministic, meaning they can be parsed by deterministic pushdown automata.
- **Non-Deterministic**: Others are non-deterministic and require non-deterministic pushdown automata for parsing.

#### Applications

- **Compiler Design**: CFGs are used to define the syntax of programming languages.
- **Natural Language Processing**: CFGs are used to model the syntax of natural languages.

#### Connection to Other Topics

- **[[Formal Language Theory]]**: CFGs are a specific type of formal grammar.
- **[[Automata Theory]]**: Non-deterministic pushdown automata recognize exactly the context-free languages.
- **[[Decidability]]**: The question of language equality for CFGs is undecidable.
- **[[Computational Complexity]]**: Parsing some CFGs can be computationally expensive.
 [[Mathematical Logic]]
- [[Automata Theory]]