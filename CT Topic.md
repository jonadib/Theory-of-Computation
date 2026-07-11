# Theory of Computation - Topics Covered

The topics covered in the provided source material are presented chronologically as follows:

## 1. Introduction to Theory of Computation

Definition of computation and a hierarchy of problems, categorized into solvable (tractable and intractable) and unsolvable problems.

## 2. Fundamental Concepts

Introduction to Alan Turing (Turing Machines), Stephen Cook, Moore's Law, and the three main branches of the field:
- Complexity Theory
- Computability Theory
- Automata Theory

## 3. Building Blocks of Computation

Definitions of symbols, alphabets (Σ), strings, and the power of an alphabet (including Σ*, the Kleene closure)

## 4. Formal Languages

Definition of a language as a collection of strings and the categorization of language acceptors:
- Finite Automata for Regular Languages
- PDA for Context-Free Languages
- Turing Machines for Context-Sensitive Languages

## 5. Finite Automata (FA)

- **Formal definition** using a 5-tuple (Q, Σ, δ, S, F)
- **Representations** via mathematical notation, transition diagrams (pictorial), and transition tables
- **Classification** into DFA (Deterministic Finite Automata), NFA (Non-Deterministic Finite Automata), and ε-NFA

## 6. DFA Construction and Examples

Detailed examples of constructing DFAs for languages based on specific criteria:
- Strings containing certain substrings
- Starting or ending with specific characters
- String length properties (even/odd length, exact length, or length divisible by a number)

## 7. DFA Minimization

Techniques to simplify DFAs using:
- The Partitioning method
- The Table filling method
- Finding equivalent states

## 8. NFA and ε-NFA

Definition of NFAs with ε-transitions:
- The concept of ε-closure
- Methods for converting ε-NFA to NFA

## 9. Chomsky Hierarchy

Classification of grammars and languages into four types:
- **Type-3** (Regular)
- **Type-2** (Context-Free)
- **Type-1** (Context-Sensitive)
- **Type-0** (Unrestricted/Recursively Enumerable)

## 10. Regular Expressions (RE)

- **Definitions and examples** of REs for various languages
- **Conversion methods** between RE and Finite Automata:
  - Thomson's Construction
  - The state creation method
  - The state elimination method
- **Application of Arden's Theorem** for FA to RE conversion

## 11. Finite Automata with Output

Introduction to Moore Machines and Mealy Machines:
- Formal 6-tuple definitions
- Construction examples
- The process of converting between Moore and Mealy machines
