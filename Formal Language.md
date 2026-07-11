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
