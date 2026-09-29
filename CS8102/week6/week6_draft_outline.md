# Assignment 6 — Draft Outline

**Compile Appropriate Programming Theory and Practices for a Sample Program**  
6–8 pages + flowchart(s) · APA 7 · ≥4 peer-reviewed sources · Due Sun, Oct 4, 2026, 11:58 PM (Turnitin)

---

## Working Title

*"Bridging Theory and Practice: Programming Paradigms, Design Patterns, and Program Synthesis Applied to a Sample Software Solution"*

## Page Budget (rough)


| Section                                            | Pages  |
| -------------------------------------------------- | ------ |
| Title + intro                                      | 0.5–1  |
| §1 Paradigms                                       | \~1    |
| §2 Design patterns                                 | \~0.75 |
| §3 Binary &amp; data representation                | \~0.75 |
| §4 Programming theory &amp; evidence               | \~0.75 |
| §5 Program synthesis + §6 challenges/opportunities | \~1.5  |
| §7 Hypothetical use case + flowchart(s)            | \~1.5  |
| §8 Logic critique &amp; conclusion                 | \~0.75 |


---

## Title Page

- Title, name (Hector Cervantes), institution, course, instructor, date (October 4, 2026)

## Introduction (\~0.5–1 page)

- Frame the problem: software solutions require best practices, design patterns, and a systems approach (Freeman &amp; Robson, 2020)
- Thesis: theory (binary representation, programming theory, program synthesis) plus practice (paradigms, patterns, tested logic) together produce verifiable, use-case-appropriate software
- Preview the eight required elements; state the hypothetical use case that will anchor sections 7–8

## §1. Procedural vs. Object-Oriented Approaches — *Prompt 1*

- **Compare**: both produce input→process→output programs; both use abstraction and modularity
- **Contrast**:
  - Organization: linear sequence of procedures vs. interacting objects (attributes + methods)
  - Data: separate from functions vs. encapsulated within objects
  - Reuse/maintenance: function libraries vs. inheritance, polymorphism, encapsulation
  - Empirical evidence: OO programs measured about twice as modular as procedural ones (Ferrett &amp; Offutt, 2003)
- **When each fits**: small/linear/system-level tasks (procedural) vs. large, evolving, real-world-modeled systems (OO)

## §2. Computing Design Patterns — *Prompt 2*

- Definition: reusable template/roadmap for recurring problems; improves communication, reuse, convergence/divergence recognition (Freeman &amp; Robson, 2020)
- **Applied perspective**: concrete examples
  - Behavioral (State — behavior changes with object state)
  - Creational (Singleton — single instance of a class)
  - Structural (Proxy — one object represents another)
- **Theoretical perspective**: patterns' measurable link to software quality — pattern-participating classes show less smell-proneness (Alfadel et al., 2020); systematic reviews note quality effects are mixed and context-dependent (Wedyan et al., 2020)
- Tie-in: patterns as the practical embodiment of theory in reusable form

## §3. Binary Numbering System &amp; Data Storage/Transmission — *Prompt 3*

- Bits (1/0), on/off states, closed circuit = on; open = off; short = unstable (computation theory foundation)
- Hardware (CPU/memory) monitors electrical signals to determine process states; Boolean algebra resolves expressions to true/false
- ASCII: 7-bit character encoding; 'A' = 65, 'a' = 97; highest placement value 2⁷ − 1 = 64
- **Worked example**: "Cat" → C(67)=1000011, a(97)=1100001, t(116)=1110100
- How data is stored/transmitted: characters → ASCII decimal → binary → signals; same information, different representation for user vs. machine

## §4. Programming Theory &amp; Evidentiary Relevance — *Prompt 4*

- Theory as the lens/framework for validating programs
- Mathematical basis for expectation and validation: proofs that a program performs as expected; number theory and mathematical proof as test principles
- Evidentiary angle: formal/logic-based verification gives *evidence* of correctness beyond testing (cite formal verification literature, e.g., logic-based verification progress and applications)
- Why it matters: correctness claims become demonstrable, not just assumed

## §5. Program Synthesis — *Prompt 5*

- Definition: generating code from a high-level specification; top-down, iterative (semantics + syntax requirements)
- The **synthesizer**; formal methods vs. AI/inductive approaches as different types (Gulwani et al., 2017)
- Contrast with reverse engineering (inference forward from specification vs. working backward from a result)
- Real-world relevance by domain: education, data science (program synthesis from examples), DevOps/autonomous program repair, end-user programming

## §6. Challenges and Opportunities of Program Synthesis — *Prompt 6*

- **Intention**: user intent varies (individual, environment, use case); unarticulated intent → "under-performing" the goal
- **Invention**: "discover what sticks" → rabbit-hole risk; communities of practice help but delay risk remains
- **Adaptation**: extending flawed/unmaintained code toward a "known good scenario"
- **Opportunities**: innovation, automation, lower barriers for non-programmers (David &amp; Kroening, 2017; Gulwani et al., 2017)

## §7. Hypothetical Use Case + Sample Program Logic + Flowchart(s) — *Prompt 7*

*(Suggested use case — adapt as desired)*

- **Problem**: A bookstore checkout system must validate a customer's discount code (Boolean check), compute the total, and convert the receipt text to binary for an inventory-logging subsystem — exercising user input, Boolean logic, functions, and data representation
- **Requirements**: read input → validate code (Boolean expression) → compute total (function) → ASCII-to-binary conversion (function) → output
- **Flowchart(s)**:
  - Main flowchart: Start → read input → validate → decision (valid?) → compute total → convert to binary → output → End
  - Function-level flowchart for the ASCII→binary converter (loop per character)
- Include Boolean expressions explicitly (e.g., `valid = (code == "SAVE10") AND (total > 0)`)
- Apply §3 and §4 theory: bit-level representation of outputs; arithmetic verifiability of totals

## §8. Logic Critique &amp; Justification — *Prompt 8*

- Walk through the flowchart: every path terminates; decision nodes are mutually exclusive and exhaustive
- Justify correctness: Boolean expressions resolve deterministically; functions have single entry/exit; loop invariants hold (each iteration processes exactly one character)
- Trace a test case end-to-end (e.g., "Cat" conversion, or a $50 order with valid code) as evidentiary proof the algorithm works
- Acknowledge limitations (e.g., input validation gaps) and how theory-informed extension (synthesis, patterns) addresses them

## Conclusion

- Restate synthesis of theory + practice; patterns and paradigms as practice; binary, programming theory, and synthesis as theory; validated by the use-case logic

## References (APA 7 — suggested peer-reviewed sources)

> ⚠️ Verify each in your university library databases (ACM DL, IEEE Xplore, Springer, PLOS) and add DOIs before submitting; swap any your instructor may not accept.

- Alfadel, M., Aljasser, K., &amp; Alshayeb, M. (2020). Empirical study of the relationship between design patterns and code smells. *PLOS ONE, 15*(4), e0231731. [https://doi.org/10.1371/journal.pone.0231731](https://doi.org/10.1371/journal.pone.0231731)
- David, C., &amp; Kroening, D. (2017). Program synthesis: Challenges and opportunities. *Philosophical Transactions of the Royal Society A, 375*(2104). [https://doi.org/10.1098/rsta.2017.0050](https://doi.org/10.1098/rsta.2017.0050) *(course reading — peer-reviewed journal article)*
- Ferrett, R., &amp; Offutt, J. (2003). An empirical comparison of modularity of procedural and object-oriented software. *Proceedings of the Eighth International Conference on Engineering of Complex Computer Systems (ICECCS 2003)*. IEEE. [https://doi.org/10.1109/ICECCS.2003.1201793](https://doi.org/10.1109/ICECCS.2003.1201793)
- Gulwani, S., Polozov, O., &amp; Singh, R. (2017). Program synthesis. *Foundations and Trends in Programming Languages, 4*(1–2), 1–119. [https://doi.org/10.1561/2500000010](https://doi.org/10.1561/2500000010)
- Wedyan, F., Alsmadi, D., &amp; Aburumman, O. (2020). Impact of design patterns on software quality: A systematic literature review. *IET Software, 14*(4), 420–436. [https://doi.org/10.1049/iet-sen.2018.5446](https://doi.org/10.1049/iet-sen.2018.5446)
- Optional (formal verification, for §4): Kitzelmann, N. (2010). Inductive programming: A survey of program synthesis techniques. In *Advances in computational intelligence and learning*. Springer.

### Course resources (non-peer-reviewed, cite as course materials)

- Freeman, E., &amp; Robson, E. (2020). *Head first design patterns* (2nd ed.). O'Reilly Media.

---

### ✍️ Drafting Notes

- Map each of the 8 prompts to a heading so the grader can check "correctly completed all instructions" (2 pts)
- Rubric heaviest on §7–8 quality (3 pts) — spend the most effort there
- Run Turnitin pre-check Saturday, Oct 3; submit before Sun 11:58 PM
