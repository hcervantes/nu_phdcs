# Assignment 4 Outline

## Evaluate How Programming Languages Are Applied to Transform Data into Valuable Outputs

### Requirements at a Glance


| Requirement | Detail                                                                             |
| ----------- | ---------------------------------------------------------------------------------- |
| Length      | 6–8 pages **including** the comparison diagram; title and reference pages excluded |
| Sources     | Course resources **plus** ≥ 4 recent peer-reviewed library resources               |
| Style       | Scholarly writing, current APA                                                     |
| Submission  | Turnitin-enabled; submit to Dropbox (run a Turnitin pre-check first)               |
| Due         | Sunday, September 20, 2026, 11:58 PM                                               |
| Weight      | 10 points                                                                          |


### Rubric Alignment (where points come from)


| Rubric criterion                                               | Points | Sections that earn it                                                                    |
| -------------------------------------------------------------- | ------ | ---------------------------------------------------------------------------------------- |
| Data transformation into outputs as a function of the language | 3      | Sections 3–4 (largest single criterion — go deepest here)                                |
| Assignment instructions (all 5 prompts addressed)              | 2      | Whole paper; verify against the prompt checklist below                                   |
| Content and critical thinking                                  | 2      | Sections 3, 5, 6 (cite peer-reviewed evidence, weigh trade-offs, note study limitations) |
| Cohesion and organization                                      | 2      | One central thesis threaded through every section                                        |
| Grammar, mechanics, APA, resource integration                  | 1      | Full APA formatting; scholarly sources only                                              |


**Working thesis:** Programming languages are purpose-built communication systems whose syntax, semantics, and level of abstraction determine how effectively data is transformed into valuable outputs — so sound engineering practice selects a language by matching those characteristics to system requirements, not programmer preference.

---

## Outline

### Title Page

- Title suggestion: *From Data to Decisions: How Programming Language Selection Shapes the Transformation of Data into Valuable Outputs*

### 1. Introduction (\~½ page)

- Hook: the IPO model — every application takes input, processes it, and produces output
- Brief context: languages differ in advantages/disadvantages
- Thesis statement (above)
- Roadmap of the paper's five main sections

### 2. The Purpose, Use, and Application of Computer Languages (\~1 page)

- Purpose: standardized communication of instructions to machines (Salem Press/Shirer; Lesson 4)
- Use: languages as tools — the compiler/interpreter/assembler/linker toolchain
- Application: business, science, daily life; operations, evaluation, intelligence, machine learning as output contexts
- Cite: Lesson 4 text; Shirer (2026); Doskas (2021)

### 3. Computer Languages as Human Languages (\~¾ page)

- Communication as the primary goal of both; context-driven secondary goals
- Syntax ↔ grammar; semantics ↔ meaning ("1 + pizza" example)
- Where the analogy breaks down: strictness of machine languages; consequences of ambiguity (the misplaced-comma rocket failure anecdote)
- Abstraction and subroutines as the machine analog of summarizing and reuse
- Cite: Lesson 4; Shirer (2026); optionally a peer-reviewed source on programming language semantics

### 4. Semantics, Syntax, and the IPO Data Pipeline (\~1½–2 pages) — *rubric heavyweight*

- Relationship between semantics (logic) and syntax (grammar checked at compilation)
- **Input:** sources (human/machine), data types, validation
- **Processing:** manipulation of data through language constructs — variables, control structures (sequence/selection/repetition), procedures/functions, objects; strong vs. dynamic typing; compiled vs. interpreted execution paths
- **Output:** rendered, printed, or stored results
- Trace one concrete mini-example across languages (e.g., accumulate three values in C vs. COBOL vs. Python, from Doskas 2021) showing the same semantics expressed in different syntax
- Map outputs to their uses: **operations** (transactions), **evaluation** (reporting/analysis), **intelligence** (insight from aggregated data), **machine learning** (trained models fed by data pipelines)
- Cite: Lesson 4; Doskas (2021); Coblenz (2017) for how design features shape correctness

### 5. Comparison: C-Based Languages vs. High-Level Languages (e.g., Python) (\~1½ pages, including diagram)

- **Required diagram** (see plan below): compiled vs. interpreted pipelines plus attribute comparison
- C-based strengths: execution speed, memory efficiency, hardware control, mature toolchains, ubiquity (OS/embedded)
- C-based weaknesses: manual memory management, steeper learning curve, platform-specific builds, slower development
- Python strengths: readable syntax, rapid development, vast libraries (data science/ML ecosystem), platform independence, interpretive flexibility
- Python weaknesses: lower execution speed, GIL/runtime overhead, runtime type errors
- Close with the Lesson 4 insight: poorly written code is possible in any language; best practices, standards, and documentation determine portability
- Cite: Doskas (2021); Shirer (2026); 1–2 peer-reviewed performance/benchmark sources

#### Diagram Plan (Figure 1)

- Top half — two parallel pipelines:
  - C: *Source code → Compiler → Object code → Linker → Machine code (platform-specific executable)*
  - Python: *Source code → Interpreter → Bytecode → Virtual machine (platform-independent)*
- Bottom half — side-by-side advantages/disadvantages table (speed, memory, portability, development speed, typing, typical use cases)
- Label as an APA **Figure** (numbered, titled above, source note below); ensure it fits within the 6–8-page count

### 6. Rationale for Selecting a Programming Language (\~1 page)

- Start from system requirements — "always about the client, never the programmer's preference"
- Considerations and why each matters:
  1. Use case nature/type → domain fit (e.g., SQL for queries, Python for ML)
  2. Scalability → long-term growth and performance headroom
  3. Complexity → paradigm fit (procedural top-down vs. OOP bottom-up vs. hybrid)
  4. Resource constraints (time/money) → development speed vs. execution speed trade-off
  5. Security requirements → language features (e.g., immutability support per Coblenz's Glacier findings)
  6. Hardware resources → low-level control needs
  7. Short-term vs. long-term stakeholder goals
  8. Community/vendor support and library availability
  9. Performance requirements
  10. Interoperability/integration with existing systems
- Strengthen with peer-reviewed evidence: paradigm maintainability differences (Brborich et al., 2020 — PP was 8.33% more effective and \~1 task/hour faster in that study, with noted limitations)
- Cite: Lesson 4; Brborich et al. (2020); Coblenz (2017)

### 7. Conclusion (\~½ page)

- Restate thesis in light of the evidence
- Synthesis: syntax/semantics + abstraction level + ecosystem = fitness for purpose
- Forward-looking thought: language selection as an engineering decision tied to data-to-output value chains

### References (APA 7)

Start with the course resources (already in APA):

- Brborich, W., Oscullo, B., Lascano, J. E., &amp; Clyde, S. (2020). An observational study on the maintainability characteristics of the procedural and object-oriented programming paradigms. In *2020 32nd IEEE International Conference on Software Engineering Education and Training (CSEE&amp;T)*. IEEE.
- Coblenz, M. (2017). Principles of usable programming language design (Extended abstract). In *2017 IEEE/ACM 39th International Conference on Software Engineering Companion (ICSE-C)* (pp. 469–470). IEEE. [https://doi.org/10.1109/ICSE-C.2017.24](https://doi.org/10.1109/ICSE-C.2017.24)
- Doskas, C. (2021). Python programming: Object-oriented programming. *ISSA Journal*, 44–47.
- Shirer, D. L. (2026). Computer programming languages. In *Salem press encyclopedia of science*. Salem Press.

*Additional Refs:*
- Farshidi, S., Jansen, S., & Deldar, M. (2021). A decision model for programming
          language ecosystem selection: Seven industry case studies. Information & Software
          Technology, 139, N.PAG. https://doi.org/10.1016/j.infsof.2021.106640

- Tomasz Wiejak, & Jakub Smołka. (2024). Performance of machine learning tools.
          Comparve analysis of libraries in interpreted and compiled programming languages.
          Journal of Computer Sciences Institute, 33. https://doi.org/10.35784/jcsi.6589

- Dashdamirli, N. (2025). Analyzing the Performance and Practicality of C, Rust,
          Python, and Lua Programming Languages for Developing Microcontroller
          Applications. 2025 6th International Conference on Problems of Cybernetics and
          Informatics (PCI), Problems of Cybernetics and Informatics (PCI), 2025 6th
          International Conference On, 1–5. https://doi.org/10.1109/PCI66488.2025.11219778

- W. Brborich, B. Oscullo, J. E. Lascano and S. Clyde, "An Observational Study on the Maintainability Characteristics of the Procedural and Object-Oriented Programming Paradigms," 2020 IEEE 32nd Conference on Software Engineering Education and Training (CSEE&T), Munich, Germany, 2020, pp. 1-10, doi: 10.1109/CSEET49119.2020.9206213. keywords: {Maintenance engineering;Programming profession;Software;Task analysis;Measurement;Education;programming paradigms;object-oriented programming;procedural programming paradigm;maintainability;software-engineering education},



**Then add ≥ 4 recent peer-reviewed library sources.** Suggested search strategies:

- "programming language selection criteria" software engineering
- "compiled vs. interpreted" performance evaluation
- Python performance benchmark C comparison
- "syntax and semantics" programming languages pedagogy
- Object-oriented vs. procedural maintainability empirical
- The Salem Press article's bibliography (Harper; Scott; Friedman &amp; Wand; Ramsey) lists scholarly books usable as course-related additional resources

---

## Prompt Checklist (verify before submitting)

- [ ] Assessed the purpose, use, and application of computer languages
- [ ] Explained how computer languages are like human-based languages
- [ ] Described the relationship between semantics (logic) and syntax, and detailed data manipulation through input, processing, and output for operations, evaluation, intelligence, and machine learning
- [ ] Included a comparison diagram of C-based languages vs. high-level languages (e.g., Python) with advantages/disadvantages of each
- [ ] Described the rationale for selecting a programming language with justifications
- [ ] 6–8 pages including the diagram, excluding title/reference pages
- [ ] Course resources + ≥ 4 peer-reviewed recent sources integrated and cited in APA
- [ ] Turnitin pre-check run; submitted to Dropbox before Sunday, Sep 20, 11:58 PM

## Suggested Week Schedule


| Day                 | Task                                                                     |
| ------------------- | ------------------------------------------------------------------------ |
| Tue–Wed (Sep 15–16) | Gather the 4+ peer-reviewed sources; skim and take notes; confirm thesis |
| Wed–Thu (Sep 17)    | Draft Sections 2–4 (definitions, analogy, IPO pipeline)                  |
| Thu–Fri (Sep 18)    | Build the Figure 1 diagram; draft Section 5; draft Section 6             |
| Fri–Sat (Sep 19)    | Write intro/conclusion; format APA; verify prompt checklist              |
| Sun (Sep 20)        | Turnitin pre-check, revise, submit to Dropbox                            |
