# Theory of Computer Science — Self-Learning Activity

<p align="center">
  <img src="https://img.shields.io/badge/Subject-Theory%20of%20Computer%20Science-blue" />
  <img src="https://img.shields.io/badge/Tool-JFLAP-orange" />
  <img src="https://img.shields.io/badge/Academic%20Year-2026--27-green" />
</p>

## About the Activity

This repository contains my **Theory of Computer Science (TCS) Self-Learning Activity**, completed as part of the academic curriculum for Third Year Computer Engineering.

The activity focuses on understanding and implementing important concepts of Automata Theory and Formal Languages using **JFLAP 7.1**.

It includes practical implementations of Deterministic Finite Automata, Non-Deterministic Finite Automata, NFA to DFA conversion, DFA minimization, Regular Expression conversion and Mealy Machines.

Each practical includes the problem statement, theoretical background, transition table, automaton diagram, implementation files, test cases and execution screenshots.

## Student Information

| Details | Information |
|---|---|
| Student Name | Jeegnasa Makwana |
| Department | Computer Engineering |
| Year | Third Year (T.E.) |
| Semester | V |
| Division | D12A |
| Subject | Theory of Computer Science |
| Subject Code | 26CMPC51 |
| Academic Year | 2026–27 |
| Practical Tool | JFLAP 7.1 |

## Objectives

1. To understand the fundamental concepts of finite automata.
2. To design DFA and NFA for different regular languages.
3. To understand the conversion of NFA into an equivalent DFA.
4. To perform DFA minimization.
5. To understand the relationship between regular expressions and finite automata.
6. To study output generation using Mealy Machines.
7. To test and verify automata using JFLAP.

## Software Requirements

- JFLAP 7.1
- Java Runtime Environment (compatible with JFLAP)
- Windows Operating System
- GitHub for storing and managing practical work

## Practical Index

| No. | Practical | Description |
|---|---|---|
| 01 | DFA — Even Number of 1s | Accept binary strings containing an even number of 1s |
| 02 | NFA — Substring 01 | Accept strings containing 01 |
| 03 | NFA to DFA Conversion | Convert an NFA accepting strings containing 101 into an equivalent DFA |
| 04 | DFA Minimization | Minimize a DFA accepting strings ending in 1 |
| 05 | Regular Expression to DFA | Convert `(a+b)*abb` into an equivalent finite automaton |
| 06 | Mealy Machine | Detect substring 01 and generate corresponding outputs |

## Practical Details

### Practical 01 — Deterministic Finite Automaton (DFA)

**Aim:** To design a DFA that accepts binary strings containing an even number of 1s.

**Alphabet:** `{0,1}`

**Concepts Covered:**
- Deterministic Finite Automaton
- Initial and final states
- State transitions
- String acceptance and rejection

**Expected Outcome:** The DFA accepts strings with an even number of 1s and rejects strings with an odd number of 1s.

### Practical 02 — Non-Deterministic Finite Automaton (NFA)

**Aim:** To design an NFA that accepts binary strings containing `01` as a substring.

**Alphabet:** `{0,1}`

**Concepts Covered:**
- Nondeterministic transitions
- Multiple transitions on the same input
- NFA simulation

**Expected Outcome:** Strings containing the consecutive substring `01` are accepted.

### Practical 03 — NFA to DFA Conversion

**Aim:** To construct an NFA accepting binary strings containing `101` and convert it into an equivalent DFA.

**Alphabet:** `{0,1}`

**Concepts Covered:**
- NFA construction
- Subset construction method
- Equivalent DFA
- State transitions

**Expected Outcome:** The resulting DFA accepts the same language as the original NFA.

### Practical 04 — DFA Minimization

**Aim:** To design and minimize a DFA accepting binary strings ending with `1`.

**Alphabet:** `{0,1}`

**Concepts Covered:**
- Equivalent states
- State partitioning
- DFA minimization
- Reduced-state automata

**Expected Outcome:** The original DFA is minimized without changing its accepted language.

### Practical 05 — Regular Expression to DFA

**Aim:** To convert the regular expression `(a+b)*abb` into an equivalent finite automaton.

**Alphabet:** `{a,b}`

**Concepts Covered:**
- Regular expressions
- Kleene star
- Union and concatenation
- Regular expression conversion

**Expected Outcome:** The resulting automaton accepts strings ending with `abb`.

### Practical 06 — Mealy Machine

**Aim:** To design a Mealy Machine that detects the substring `01` in a binary input string and generates output `1` when the substring is detected.

**Input Alphabet:** `{0,1}`

**Output Alphabet:** `{0,1}`

**Concepts Covered:**
- Mealy Machine
- Input-output transitions
- State-based output generation
- Pattern detection

**Expected Outcome:** The machine generates output `1` whenever a new occurrence of `01` is detected, and `0` otherwise.

## Repository Structure

```text
TCS-Self-Learning-JFLAP-/
│
├── README.md
│
├── Practical-01-DFA-Even-Ones/
│   ├── README.md
│   ├── implementation.jff
│   └── Screenshots/
│
├── Practical-02-NFA-Substring-01/
│   ├── README.md
│   ├── implementation.jff
│   └── Screenshots/
│
├── Practical-03-NFA-to-DFA-101/
│   ├── README.md
│   ├── nfa.jff
│   ├── converted-dfa.jff
│   └── Screenshots/
│
├── Practical-04-DFA-Minimization/
│   ├── README.md
│   ├── original-dfa.jff
│   ├── minimized-dfa.jff
│   └── Screenshots/
│
├── Practical-05-Regular-Expression-to-DFA/
│   ├── README.md
│   ├── implementation.jff
│   └── Screenshots/
│
└── Practical-06-Mealy-Machine/
    ├── README.md
    ├── implementation.jff
    └── Screenshots/
```

## How to Run the Practicals

1. Download JFLAP 7.1.
2. Ensure a compatible Java runtime is installed.
3. Open the required `.jff` file using JFLAP.
4. View the automaton diagram in the editor.
5. Use the available input-testing options to verify the automaton.
6. Refer to the screenshots and practical documentation for expected results.

## References

- [Official JFLAP Website](https://www.jflap.org/)
- [JFLAP Download](https://www.jflap.org/jflaptmp/)
- [Reference Repository — Prathamcoder3000](https://github.com/Prathamcoder3000/TCS-JFLAP-Self-Learning)
- [Reference Repository — Leena](https://github.com/leena180706/TCS-Self-Learning-Activity-JFLAP)
- [Reference Repository — Khyati](https://github.com/Khyati59/TCS__SelfLearning)

---

<p align="center">
  **Theory of Computer Science — Self-Learning Activity**
  <br/>
  Third Year Computer Engineering | Academic Year 2026–27
</p>
