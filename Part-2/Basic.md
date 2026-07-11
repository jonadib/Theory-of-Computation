# Building Blocks of Computation

## Symbols, Alphabets, Strings & Languages

Everything in TOC starts with:

**Symbol → Alphabet → String → Language**

## 1. Symbol

A symbol is the smallest indivisible unit of information used in computation. It cannot be broken down further.

### Examples

- a, b
- 0, 1
- +, *
- #, @

Each individual character is considered a symbol.

### Important Points

- Smallest unit
- Cannot be divided
- Used to build alphabets and strings

## 2. Alphabet (Σ)

An Alphabet is a finite, non-empty set of symbols. It is represented by the Greek letter **Σ (Sigma)**.

### Examples

- **Binary Alphabet:** Σ = {0,1}
- **English lowercase:** Σ = {a,b,c,...,z}
- **DNA Alphabet:** Σ = {A,C,G,T}
- **Vowel Alphabet:** Σ = {a,e,i,o,u}

### Rules of Alphabet

- Must be finite
- Cannot be empty
- Symbols are unique
- Order does not matter

**Examples:**
- ✓ Σ = {0,1}
- ✗ Σ = {0,1,1} (Duplicates not allowed in a set)

## 3. String (Word)

A String is a finite sequence of symbols chosen from an alphabet.

### Example

If Σ = {0,1}

**Possible Strings:**
- 0
- 1
- 00
- 101
- 11001
- 111111

**Invalid String:**
- 102 (because 2 ∉ Σ)

### Length of a String

The length of a string is represented by |w|

**Examples:**
- w = 10110 → |w| = 5
- w = abc → |w| = 3

### Empty String (ε)

The string containing no symbols is called the Empty String.

- **Notation:** ε
- **Length:** |ε| = 0

| Empty String | Empty Set |
|---|---|
| ε | {} |
| One string | No string |
| Length = 0 | Nothing exists |

## Power of an Alphabet

Suppose Σ = {0,1}

### Σ⁰
Strings of length 0: **Σ⁰ = {ε}**

### Σ¹
Strings of length 1: **Σ¹ = {0,1}**

### Σ²
Strings of length 2: **Σ² = {00,01,10,11}**

### Σ³
Strings of length 3:

```
Σ³ = {
  000, 001, 010, 011,
  100, 101, 110, 111
}
```

Total: 2³ = 8
