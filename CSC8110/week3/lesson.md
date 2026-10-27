# Week 3: Functional Programming in Practice

**Dates:** Nov 9 – Nov 15, 2026 · **Module:** 2 · **Focus:** Functional design & first coding deliverable

## Learning Objectives
- Explain functional programming design: pure functions, evaluation, immutability.
- Implement a functional solution: inputs → computation → returned value.
- Contrast functional design with procedural step-by-step logic.

## Key Topics
- Functional programming: self-contained functions, output depends only on inputs; Haskell, LISP, F#, PowerShell.
- Benefits: reusability, readability, maintainability, easier testing.
- Functional models in practice: map/reduce/dataflow (RAPID model), DAG execution.
- Module 2 begins: how programming languages transform and store data for decision-making.

## Readings & Resources
- Functional Programming Design (lesson document)
- A Functional Programming Model for Embedded Dataflow Applications (paper)
- Module 2 overview — algorithm complexities and language applications

## Assignment Due This Week

### Assignment 3 — Evaluate Functional Programming Solutions
**Due: Nov 15, 2026 11:59 PM · 10 points · Turnitin enabled**

#### Assignment Instructions
Write a program that takes basic information from a student — name, degree, number of credits taken so far, and total credits required in the degree program — and calculates how many credits are needed to graduate. The display must include the student name, the degree name, and credits left to graduate.

Write the code in a **functional programming language of your choice**, plus a technical paper that includes:

- The algorithm of the solution (no coding).
- The code of the chosen solution with comments and explanations (actual computer code).
- An explanation of the different types of functions used in the solution.
- A description of the scenarios with a technical explanation of the structure.
- An evaluation of how programming/scripting languages (LISP, PowerShell, Assembly, C) are used to code and manage functions that can be used across applications.
- **Length:** 5–7 page technical paper (code, algorithm, and references included) · **References:** ≥3 scholarly resources · APA.

#### Simplified Grading Rubric (10 pts)
| Criterion | Weight | To earn full points |
|---|---|---|
| Algorithm + functional computer code + explanation of all functions used | 3 pts | Good algorithm AND working functional code; strong explanation of every function |
| Assignment instructions | 2 pts | All five paper elements present; output shows name, degree, credits left |
| Content & critical thinking | 2 pts | Thoughtful evaluation of functional languages across applications |
| Cohesion & organization | 2 pts | Paper reads as one coherent solution story: problem → algorithm → code → evaluation |
| Grammar, mechanics, APA, resources | 1 pt | Error-free APA; scholarly sources |

**Grade scale:** Exceeds ≥9 · Meets ≥8 · Needs Improvement ≥7.3 · Deficient ≥4

#### Assignment Outline & Writing Inspiration
1. **Problem statement (~0.5 pg)** — Restate the scenario; define inputs (name, degree, credits taken, credits required) and output (name, degree, credits left). Note: the 30% criterion wants both a good algorithm and functional code — missing code caps you at 1.2/3.
2. **Algorithm (no code) (~0.5 pg)** — Numbered steps: read inputs → validate → credits_left = required − taken → display result. Keep it language-neutral.
3. **The code (~1 pg)** — Actual functional code (LISP, PowerShell, or C) heavily commented. Inspiration: a pure function `credits-remaining(taken, required) = required − taken` plus I/O wrapper; emphasize the function depends only on its inputs.
4. **Explanation of functions used (~1 pg)** — Name each function, its type (pure, higher-order, I/O), and why it's self-contained. This maps directly to the 30% criterion — explain *all* functions.
5. **Scenario & structure analysis (~1 pg)** — Technical explanation of the program structure: how functional design simplifies testing (same input → same output) and maintenance vs. procedural code.
6. **Language evaluation (~1 pg)** — How LISP, PowerShell, Assembly, and C are used to code and manage functions reusable across applications. Inspiration: contrast expressiveness vs. performance; where each is used in industry.
7. **References** — ≥3 scholarly sources.

## Study Checklist
- [ ] Read Functional Programming Design and Module 2 overview
- [ ] Write and test the credits-remaining program in your chosen language
- [ ] Verify output shows student name, degree, and credits left
- [ ] Comment the code and explain every function
- [ ] Submit via Turnitin by Nov 15

## Notes / Repo Links
_(paste your repo links, drafts, and instructor feedback here)_
