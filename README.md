## Self-Learning Activity — JFLAP Implementations

## Introduction

This repository contains the practical implementations completed as part of the Theory of Computer Science Self-Learning Activity.

The activity focuses on the study and implementation of different concepts of Automata Theory using **JFLAP 7.1**. It includes the construction and testing of finite automata, conversion of automata, DFA minimization, regular expression conversion and Mealy Machine design.

Each practical includes its problem statement, implementation file (`.jff`), and screenshots of the automaton design and testing results.

---

# Practical Implementations

## Practical 1 — Deterministic Finite Automaton (DFA)

**Problem Statement:** Design a DFA over the alphabet `{0,1}` that accepts binary strings containing an even number of `1`s.

**Concepts:**
- Deterministic Finite Automaton
- Initial and final states
- State transitions
- String acceptance and rejection

**Implementation:**

![Practical 1 DFA](Practical_1_DFA/1_DFA.png)

**Testing:** The automaton was tested with binary strings containing even and odd numbers of `1`s.

[View Practical 1 Files](Practical_1_DFA/)

---

## Practical 2 — Non-Deterministic Finite Automaton (NFA)

**Problem Statement:** Design an NFA over the alphabet `{0,1}` that accepts binary strings containing `01` as a substring.

**Concepts:**
- Non-Deterministic Finite Automaton
- Multiple transitions
- Initial and final states
- String acceptance and rejection

**Implementation:**

![Practical 2 NFA](Practical_2_1_NFA.png)

**Testing:** The automaton was tested with strings containing and not containing the substring `01`.

[View Practical 2 Files](Practical_2_NFA/)

---

## Practical 3 — NFA to DFA Conversion

**Problem Statement:** Design an NFA that accepts binary strings containing `101` as a substring and convert it into an equivalent DFA.

**Concepts:**
- NFA construction
- Subset Construction Method
- DFA conversion
- Equivalent automata

**Implementation:**

![Practical 3 NFA to DFA](Practical_3_NFA_to_DFA/3_Converted_DFA.png)

**Testing:** The converted DFA was tested with strings containing and not containing `101`.

[View Practical 3 Files](Practical_3_NFA_to_DFA/)

---

## Practical 4 — DFA Minimization

**Problem Statement:** Design a DFA that accepts binary strings ending in `1` and minimize it by identifying equivalent states.

**Concepts:**
- Equivalent states
- State partitioning
- DFA minimization
- Reduced state representation

**Implementation:**

![Practical 4 Minimized DFA](Practical_4_DFA_Minimization/3_Minimized_DFA.png)

**Testing:** The original and minimized automata were tested with different binary strings.

[View Practical 4 Files](Practical_4_DFA_Minimization/)

---

## Practical 5 — Regular Expression to Finite Automaton

**Problem Statement:** Convert the regular expression `(a+b)*abb` into an equivalent finite automaton.

**Concepts:**
- Regular Expressions
- Regular Languages
- Regular Expression to NFA conversion
- NFA to DFA conversion

**Implementation:**

![Practical 5 Regular Expression](Practical_5_Regular_Expression/4_Testing.png)

**Testing:** The converted automaton was tested with strings ending and not ending in `abb`.

[View Practical 5 Files](Practical_5_Regular_Expression/)

---

## Practical 6 — Mealy Machine

**Problem Statement:** Design a Mealy Machine that detects the substring `01` in a binary input string and produces output `1` whenever the substring is detected.

**Concepts:**
- Mealy Machine
- Input and output alphabets
- State transitions
- Output generation

**Implementation:**

![Practical 6 Mealy Machine](Practical_6_Mealy_Machine/1_MealyMachine.png)

**Testing:** The machine was tested with different binary input strings to verify the generated output sequences.

[View Practical 6 Files](Practical_6_Mealy_Machine/)
