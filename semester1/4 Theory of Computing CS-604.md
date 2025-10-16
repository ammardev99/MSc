# Subject: 4 Theory of Computing (CS-604)

## Week 1

- **Class Miss**

---

## Week 2

### 1. Regular Expressions (RE)

- **Definition →**
  A _Regular Expression_ (RE) is a formal way to describe a set of strings (language) over an alphabet using specific symbols and operations.

- **Purpose →**
  Used to represent _regular languages_ which can be recognized by _Finite Automata (FA)_.

- **Basic Rules / Principles →**

  - If `r1` and `r2` are regular expressions, then:
    - `r1 + r2` → Union (either `r1` or `r2`)
    - `r1 . r2` → Concatenation (first `r1` then `r2`)
    - `(r1)*` → Kleene Star (zero or more repetitions of `r1`)
    - `(r1)+` → One or more repetitions of `r1` (at least once)
    - `(r1)?` → Zero or one occurrence of `r1` (optional)

- **Symbols**

  - **Σ (Sigma)** → Set of all possible symbols (e.g., `{a, b}`)
  - **ε (Epsilon / Null String)** → Represents an empty string (no symbol)
  - **∅ (Empty Set)** → Represents no string (nothing accepted)

- **Examples**

  - `a + b` → Either `a` or `b`
  - `(a + b)^3` → All possible combinations of `a` and `b` with length 3
  - `a^+` → One or more occurrences of `a`
  - `(a + b)*` → Any combination of `a` and `b`, including empty string
  - `a*b*` → Any number of `a`s followed by any number of `b`s

- **Note →**
  - The result of any combination of REs is also a regular expression.
  - Kleene Star (\*) can produce `null`, one repetition, or many repetitions.

---

### 2. Recursive Definition

- **Definition →**  
  Recursive definition defines an object in terms of itself using base and recursive steps.

- **Example**

  - Base Case: `2` is even.
  - Recursive Step: If `x` is even, then `x + 2` is also even.  
    ⇒ All even numbers can be generated recursively.

- **Another Example**
  - Base Case: `ε` (empty string) ∈ L
  - Recursive Step: If `x` ∈ L, then `ax` ∈ L and `bx` ∈ L  
    ⇒ All strings over `{a, b}` can be formed recursively.

---

### 3. Practice Questions on Σ = {a, b}

| **Condition**                             | **Regular Expression (RE)**               |
| ----------------------------------------- | ----------------------------------------- |
| Start with `a`                            | `a(a + b)*`                               |
| All words have at least one `a`           | `(a + b)* a (a + b)*`                     |
| Do not contain `aa`                       | `(b + ab)* (ε + a)`                       |
| Do not contain `aa` or `bb`               | `(ab)* (ε + a + b)`                       |
| Even number of `a` and even number of `b` | Complex RE (needs state tracking; use FA) |

---

## Week 3

### 1. Finite Automata (FA)

- **Definition →**
  A Finite Automaton (FA) is a simple mathematical model of computation used to recognize _regular languages_.

- **Purpose →**
  It checks whether a given string belongs to a particular regular language.

- **Components / Rules**

  - **Q:** Finite set of states
  - **Σ:** Finite set of input symbols (alphabet)
  - **δ:** Transition function (defines state movement)
  - **q₀:** Start state (one of the states in Q)
  - **F:** Set of final (accepting) states (subset of Q)

  → Formally, FA = (Q, Σ, δ, q₀, F)

- **Transition Function →**
  Describes how the automaton moves from one state to another based on an input symbol.

- **Types of FA**

  - **DFA (Deterministic Finite Automata)** → One transition per input.
  - **NFA (Non-Deterministic Finite Automata)** → Multiple transitions possible for an input or ε (null) transitions.

- **State Representation**
  - Start State → Marked with `→`
  - Final State → Marked with `*` or `+`
  - Example: `→ q0 —a→ q1 —b→ q2*`

---

### 2. Practice Questions (Σ = {a, b})

| **Condition**                    | **Regular Expression (RE)** |
| -------------------------------- | --------------------------- |
| All words have at least one `b`  | `(a + b)* b (a + b)*`       |
| Can be null string               | `(a + b)*`                  |
| Accept nothing                   | `∅`                         |
| Starts and ends with same symbol | `a(a + b)*a + b(a + b)*b`   |
| Ends with `ab`                   | `(a + b)*ab`                |
| Contains substring `aa`          | `(a + b)*aa(a + b)*`        |
| Even number of `a`s              | `(b*(ab*ab*)*)`             |

---

## **Bonus Exam Guide**

- **Key Difference Between RE, FA, and Grammar**

  - RE → Describes language pattern.
  - FA → Accepts/recognizes the pattern.
  - Grammar → Generates the pattern.

- **Conversions**

  - RE → NFA → DFA → Minimized DFA
  - DFA ↔ Regular Grammar

- **Important Terms**

  - **Language (L):** Set of all accepted strings.
  - **Accepting State:** Final state reached after consuming input.
  - **Dead State:** State that leads to no acceptance.

- **Tips for Exams**
  1. Always write FA as a 5-tuple.
  2. Label transitions clearly in diagrams.
  3. Practice RE ↔ FA conversions.
  4. Remember key RE examples (like starts with, ends with, etc.).
  5. Review difference between DFA, NFA, and ε-NFA.

---

## w4

- class miss
