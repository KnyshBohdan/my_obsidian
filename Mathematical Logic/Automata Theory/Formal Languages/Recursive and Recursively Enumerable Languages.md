Recursive languages are a class of formal languages that are decidable, meaning there exists a Turing machine that will always halt and correctly determine whether a given string belongs to the language or not.

#### Definition

A formal language is called recursive if there exists a Turing machine that, when given a finite sequence of symbols as input, always halts and accepts it if it belongs to the language and halts and rejects it otherwise. In theoretical computer science, such always-halting Turing machines are also known as total Turing machines or algorithms.

#### Examples

- **Context-Sensitive Languages**: Every context-sensitive language is recursive.
- **Presburger Arithmetic**: The set of true statements in Presburger arithmetic is an example of a language that is decidable but not context-sensitive.

#### Properties

- **Closure**: Recursive languages are closed under operations like union, intersection, and set difference.

#### Connection to Other Topics

- **[[Turing Machines]]**: Recursive languages are closely related to Turing machines that always halt.

---

### Recursively Enumerable Languages

#### Small Understandable Intro

Recursively Enumerable Languages are a broader class of formal languages that may or may not be decidable. A language is recursively enumerable if there exists a Turing machine that will enumerate all valid strings of the language.

#### Definition

A formal language is called recursively enumerable if it is a recursively enumerable subset in the set of all possible words over the alphabet of the language. In other words, there exists a Turing machine which will enumerate all valid strings of the language.

#### Examples

- **Halting Problem**: The set of halting Turing machines is recursively enumerable but not recursive.

#### Properties

- **Closure**: Recursively enumerable languages are not closed under set difference or complementation.
- **Hierarchy**: Known as type-0 languages in the Chomsky hierarchy.

#### Connection to Other Topics

- **[[Turing Machines]]**: Recursively enumerable languages are closely related to Turing machines that may or may not halt.

 [[Mathematical Logic]]
- [[Automata Theory]]