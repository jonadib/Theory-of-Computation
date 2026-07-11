# Moore's Law & Three Main Branches of TOC

## Moore's Law

**Introduced by:** Gordon Moore (1965)

**Statement:** The number of transistors on a chip doubles approximately every two years, leading to increased computing power and reduced cost per transistor.

### Example

```
Year 2020: 10 Billion transistors
  ↓
2022: 20 Billion transistors
  ↓
2024: 40 Billion transistors
```

## Three Main Branches of Theory of Computation

```
                    Theory of Computation
                                |
                    ------------------------------------
                    |                  |               |
                Automata            Computability    Complexity
                Theory              Theory            Theory
```

### 1. Automata Theory

Theory studies abstract machines and the languages they recognize.

**Topics:**
- DFA (Deterministic Finite Automata)
- NFA (Nondeterministic Finite Automata)
- PDA (Pushdown Automata)
- Turing Machine

### 2. Computability Theory

Computability Theory determines whether a problem can be solved at all.

**Questions:**
- Can this problem be solved?
- Does an algorithm exist?

**Example:**
- Halting Problem

### 3. Complexity Theory

Complexity Theory measures the resources needed to solve a problem, mainly:

- Time
- Memory (Space)

**Classes include:**
- P
- NP
- NP-Complete
- NP-Hard

## Relationship Between the Three Branches

| Branch | Main Question |
|---|---|
| Automata Theory | How are languages recognized? |
| Computability Theory | Can the problem be solved? |
| Complexity Theory | How efficiently can it be solved? |
