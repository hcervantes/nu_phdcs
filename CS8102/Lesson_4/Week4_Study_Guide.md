# Week 4 Study Guide — Computer Languages, Their Use, and Application

**Course concept topic:** Computer languages, their use, and application  
**Outcomes:** CLO 3 — Explain data and its manipulation to create useful outputs for operations, evaluation, intelligence, and machine learning; ILO 4 — Critical Thinking  
**Key date:** Assignment 4 due **Sunday, September 20, 2026, 11:58 PM** (10 points, Turnitin)

---

## 1. The Big Picture

- Computer languages let people communicate with machines by providing **information and instructions** used to perform tasks.
- Every program follows the **Input → Processing → Output (IPO)** model:
  - **Input** — from a human or machine
  - **Processing** — by the machine/system running the program
  - **Output** — displayed on screen, printed, or stored for later use
- The quantity and quality of input, processing, and output drive an application's **performance and reliability**.
- Languages differ in advantages/disadvantages; understanding those trade-offs is the rationale behind **selecting** a language (the core of Assignment 4).

## 2. Computer Languages vs. Human Languages


| Similarity                        | Explanation                                                                                                                                                                                 |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Primary goal is communication     | Both exist to transfer meaning from one party to another                                                                                                                                    |
| Grammar + meaning                 | Syntax = grammar rules; semantics = the meaning carried by the logic                                                                                                                        |
| Context-dependent secondary goals | Human languages have diverse goals based on context; so do computer languages (speed, portability, readability, domain fit)                                                                 |
| Stricter rules for machines       | Computer languages are far stricter than natural languages because misinterpretation has serious consequences (e.g., a misplaced comma was blamed for a multimillion-dollar rocket failure) |


**Exam-ready phrasing:** A programming language is analogous to a human language — syntax governs how symbols may be combined; semantics governs what those combinations mean. The "1 + pizza" example is syntactically valid but semantically meaningless.

## 3. Syntax and Semantics

- **Semantics** — the logic of the code; what the instructions actually do.
- **Syntax** — the grammar of the language; the rules checked during compilation. Every language has its own syntax.
- A program must satisfy **both** to execute correctly.
- **Abstraction** hides unnecessary details; higher abstraction → easier to understand and use, more platform independence. Implemented with **subroutines** (write functionality once, never duplicate it).

## 4. Language Levels and Generations


| Generation               | Examples                                                   | Traits                                                                            |
| ------------------------ | ---------------------------------------------------------- | --------------------------------------------------------------------------------- |
| 1GL — Machine code       | Raw binary                                                 | Directly executed; fast/efficient; nearly unreadable; hardware knowledge required |
| 2GL — Assembly           | LOAD, ADD, STORE                                           | Symbolic, more readable; needs an assembler; machine-specific                     |
| 3GL — High-level         | Fortran, COBOL, ALGOL, C, C++, C#, Java, JavaScript, BASIC | Most widely used; easier for humans; needs a compiler/interpreter                 |
| 4GL — Higher abstraction | Ruby, Python, Perl, SQL                                    | Platform independence through abstraction                                         |


### High-Level vs. Low-Level (Lesson Table 1 — memorize the trade-offs)


| Attribute          | High-Level                   | Low-Level                         |
| ------------------ | ---------------------------- | --------------------------------- |
| Human readability  | Easy                         | Difficult                         |
| Execution          | Slower, less efficient       | Fast, efficient                   |
| Translation        | Compiler → machine code      | Assembler                         |
| Portability        | Runs on any platform         | Machine-dependent                 |
| Debugging          | Easy                         | Difficult                         |
| Memory management  | Inefficient                  | Efficient                         |
| Abstraction        | High                         | Little to none                    |
| Hardware knowledge | Not required                 | Required                          |
| Modification       | Depends on code organization | Easy (maps directly to processor) |


## 5. Compiled vs. Interpreted

- **Compiler** — translates the entire source program into directly executable form (several passes; reports syntax errors; object code linked by a **linker** into final machine code).
- **Interpreter** — translates and executes one line at a time; supports interactive debugging (BASIC, FOCAL, Python shells); less efficient for large programs.
- Modern **optimizing compilers** produce code nearly as efficient as expert assembly, which is why most software today is written in high-level languages.
- **Pseudocode** — a blend of programming language and natural language used to describe algorithms before coding.

## 6. Programming Paradigms

- **Imperative** (COBOL) — statements instruct the computer to perform a specific sequence of operations. **Declarative** (SQL) — specifies the desired outcome, not the steps.
- **Turing complete** — can perform all possible computations; most languages qualify (Charity and Epigram do not).

### Procedural vs. Object-Oriented (Lesson 4 + Brborich et al. study)


| Dimension          | Procedural (PP)                                                                  | Object-Oriented (OOP)                                                 |
| ------------------ | -------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| Organization       | Procedures/functions called from a main method                                   | Classes representing real-world objects with attributes and behaviors |
| Control structures | Sequence, selection, repetition                                                  | Objects, messages, inheritance, polymorphism                          |
| Approach           | **Top-down** (start at main, branch out)                                         | **Bottom-up** (build components, connect to main)                     |
| Design tools       | Flowcharts, control-flow diagrams                                                | UML class, interaction, state diagrams                                |
| Imperative family  | Yes — both PP and OOP are imperative (state, instructions, sequential execution) | Yes                                                                   |


- Most professional development today uses a **hybrid** of top-down and bottom-up, depending on complexity and team-based functional decomposition.
- Modern languages are **multi-paradigm**: Java, C#, and C++ added lambda functions, adding functional programming to OOP.

### Evidence from the maintainability study (Brborich et al., 2020)

- Observational study of 90 students maintaining two functionally equivalent web-app backends: **PP (Python/Flask)** vs. **OOP (Java/Spring Boot)**, using injected errors and test suites.
- Metrics: **Maintenance Effectiveness (ME)** — correctness-weighted completion of maintenance tasks; **Maintenance Speed (MS)** — correct tasks per hour.
- **Results:** subjects on the PP version were on average **8.33% more effective** and about **1 task/hour faster** (ME 0.82 vs. 0.74; MS 3.92 vs. 2.82); both null hypotheses were rejected at p &lt; 0.05 (Wilcoxon test for ME, T-test for MS).
- **Caveats:** observational, single institution, small scale, subjects skewed toward OOP/Java experience in upper courses; results motivated a future larger-scale experiment — good example of critical thinking about study limitations.

## 7. How Languages Evolved (Doskas, 2021)

- Machine code → assembly (symbolic, machine-specific) → high-level compiled languages (FORTRAN for science, COBOL for business) → scripting languages (JCL, shell scripts, JavaScript client-side, PHP/Python/Ruby server-side) → OOP languages (C++ 1980s, Java 1995, Python early 1990s).
- The **C example** (declaration → assignment → calculation → printf) vs. the **Python example** (no declarations, interpreted, runs in a shell) illustrates the compiled/strongly-typed vs. interpreted/dynamically-typed distinction that Assignment 4's comparison diagram should capture.
- Motivations for OOP: reusability, avoiding duplicated subroutines, hiding internal structure, and modifying behavior without rewriting — illustrated by the "store front vs. behind the counter" analogy.

## 8. Selecting a Programming Language (Assignment 4 Section 5)

Selection starts with **system requirements**, never programmer preference ("always about the client"):

1. Nature/type of the use case
2. Scalability requirements
3. Application complexity
4. Resource constraints (time and money)
5. Security requirements
6. Available hardware resources
7. Short-term needs **and** long-term goals of stakeholders
8. Community/vendor support
9. Availability of libraries for needed capabilities
10. Performance level required
11. Interoperability/integration with other systems

**Critical-thinking nugget:** poorly written code is possible in any language; a well-written application can be ported to any language given best practices, coding standards, and documentation.

## 9. Language Design and Usability (Coblenz, 2017)

- Language design should fuse **programming language theory with human-computer interaction (HCI)** methods — languages are tools for people, so user needs should drive design.
- **Usability questions:** learning time, programmer effectiveness, bug rates, security vulnerabilities.
- **Glacier** case: transitive class immutability for Java (@Immutable) — in a user study, all programmers using `final` alone made immutability mistakes (one caused a bug, another a security vulnerability); Glacier users succeeded and errors were caught statically.
- Implication for selection: language **features** (e.g., immutability support, type systems) measurably affect correctness and security — a strong peer-reviewed citation for your rationale section.

## 10. Key Terms Glossary


| Term                | Definition                                                                       |
| ------------------- | -------------------------------------------------------------------------------- |
| Syntax              | Grammar rules for combining a language's symbols                                 |
| Semantics           | Rules that interpret the meaning of syntactically valid statements               |
| Abstraction         | Hiding unnecessary detail; functionality implemented once, never duplicated      |
| Subroutine          | A sequence of statements performing a specific task                              |
| Compiler            | Translates the entire source program into executable form                        |
| Interpreter         | Translates and executes one line of source code at a time                        |
| Linker              | Combines object modules into final executable machine code                       |
| Assembler           | Translates assembly instructions into machine code                               |
| Source code         | The program text written in a given language                                     |
| Machine language    | Binary instructions specific to a processor                                      |
| High-level language | Each statement typically maps to several machine instructions                    |
| Paradigm            | A way of thinking about, designing, and implementing software                    |
| Maintainability     | Ease of modifying software to correct failures, improve performance, or adapt it |
| Turing complete     | Able to perform all possible computations and algorithms                         |


## 11. Self-Check Questions

1. Explain the IPO model and how the quality of each stage affects application reliability.
2. How are computer languages analogous to human languages? Where does the analogy break down?
3. Distinguish syntax from semantics with an example.
4. Compare first-, second-, third-, and fourth-generation languages.
5. What trade-offs exist between high-level and low-level languages? (Recite at least six rows of Table 1.)
6. Contrast compilers and interpreters; when would you choose each?
7. Compare procedural and object-oriented paradigms, including top-down vs. bottom-up design.
8. What did the Brborich et al. study find about PP vs. OOP maintainability, and what limits its generalizability?
9. List at least eight considerations for selecting a programming language and justify why each matters.
10. How does Coblenz argue that HCI methods can improve language design?

## 12. Source Map (what to cite where)


| Resource                                      | Best used for                                                                      |
| --------------------------------------------- | ---------------------------------------------------------------------------------- |
| Lesson 4 course text                          | Definitions, IPO, Table 1 comparisons, selection criteria, assignment requirements |
| EBSCO/Salem Press encyclopedia (Shirer, 2026) | Generations, syntax/semantics, compiler workflow, principal terms, pseudocode      |
| Doskas (2021), ISSA Journal                   | History of programming, C/COBOL/Python code examples, OOP motivations              |
| Brborich et al. (2020), IEEE CSEE&amp;T       | Peer-reviewed evidence on paradigm maintainability differences                     |
| Coblenz (2017), IEEE ICSE-C                   | Peer-reviewed evidence on usability-driven language design                         |
