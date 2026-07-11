# Kleene Closure (Σ*)

## Kleene Closure (Σ*)

Kleene Closure means all possible strings of every finite length over Σ, including the empty string (ε).

**Notation:** Σ*

**Formula:** Σ* = Σ⁰ ∪ Σ¹ ∪ Σ² ∪ Σ³ ∪ ...

### Example

If Σ = {0,1}, then:

```
Σ* = {
  ε,
  0, 1,
  00, 01, 10, 11,
  000, 001, ...
}
```

**Σ* is an infinite set.**

## Positive Closure (Σ⁺)

All strings except Empty String.

**Notation:** Σ⁺

**Formula:** Σ⁺ = Σ¹ ∪ Σ² ∪ Σ³ ∪ ... or Σ⁺ = Σ* − {ε}

### Example

If Σ = {0,1}, then:

```
Σ⁺ = {
  0, 1,
  00, 01, 10, 11,
  ...
}
```

## Difference Between Σ* and Σ⁺

| Σ* | Σ⁺ |
|---|---|
| Contains ε | Does not contain ε |
| Starts from Σ⁰ | Starts from Σ¹ |

## Empty Language (∅)

Empty Language contains no strings.

**Notation:** ∅

**Example:** L = ∅

### Difference Between Empty String and Empty Language

| Empty String | Empty Language |
|---|---|
| ε | ∅ |
| One string | No strings |
