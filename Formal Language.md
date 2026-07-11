# Formal Languages & Finite Automata

## What is a Formal Language?

A Formal Language is a set of strings formed from an alphabet according to specific rules.

> **Remember:** Language = Collection (Set) of Valid Strings

A string belongs to a language only if it satisfies the language's rule.

### Example 1

Let Σ = {0,1}

Define L = { w | w ends with 1 }

**Valid strings:**
- 1
- 01
- 101
- 111
- 0001

**Invalid strings:**
- 0
- 10
- 1100

(because they do not end with 1)



---

## Mathematical Representation of a Language

A language is often written using set-builder notation.

### Example 1

```
L = { w | w starts with 0 }
```

**Meaning:** L contains all strings that start with 0.

### Example 2

```
L = { w ∈ {0,1}* | |w| is even }
```

**Meaning:** All binary strings whose length is even.

**Examples of strings in this language:**
- ε
- 00
- 01
- 1010
- 1111

---

```

## Types of Languages

### 1. Finite Language

Contains a finite number of strings.

**Example:**
```
L = {a, b, ab}
Total strings = 3
```

### 2. Infinite Language

Contains infinitely many strings.

**Example:**
```
L = {0, 00, 000, 0000, ...}
```

---

## Formal Definition of Finite Automata

A Finite Automaton is represented by a **5-tuple:**

```
M = (Q, Σ, δ, q₀, F)
```

### Component Details

#### 1. Q (Set of States)

Q is a finite set of states.

**Example:**
```
Q = {q₀, q₁, q₂}
```

#### 2. Σ (Alphabet)

Input symbols that the machine will read.

**Example:**
```
Σ = {0, 1}
```

#### 3. δ (Transition Function)

This function tells us: If the machine is in a state and reads a symbol, which state will it go to next?

**Notation (for DFA):**
```
δ : Q × Σ → Q
```

**Example:**
```
δ(q₀, 1) = q₁
```

**Meaning:**
- Current State = q₀
- Input = 1
- Next State = q₁

#### 4. q₀ (Start State)

The initial state where the machine begins.

**Example:**
```
q₀
```

Every automaton has exactly **one start state**.

#### 5. F (Final States)

Accepting states (set of states).

**Example:**
```
F = {q₂}
```

If computation ends in q₂, the string is **Accepted**.




## Language Acceptors (Recognizers)

A Language Acceptor is a machine that checks whether a given string belongs to a language.

```
Input
  ↓
Machine
  ↓
Accept or Reject
```

### Types of Language Acceptor

| Language Type | Machine |
|---|---|
| Regular Language | Finite Automata (FA) |
| Context-Free Language | Pushdown Automata (PDA) |
| Context-Sensitive Language | Linear Bounded Automata (LBA) |
| Recursively Enumerable Language | Turing Machine (TM) |
