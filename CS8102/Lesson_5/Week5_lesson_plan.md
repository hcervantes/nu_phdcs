# Lesson 5: Current Programming Languages and Their Application

**Module 3:** Combining Theory, Practice, and Programming for Successful Solutions  
**Concept topic:** Current programming languages and their application  
**Course Learning Outcome:** CLO 4 — Create high-level solutions using simple computer programming problems for solutions considering both theory and practice.  
**Assignment due:** **Sunday, September 27, 2026, 11:58 PM** (Turnitin™ enabled)

---

## 1. Lesson Overview

Numerous programming languages exist, and versions of each evolve as needs change. This lesson teaches students to move beyond programmer preference (which can introduce bias) and make a **justified case** for selecting a specific language based on the needs, requirements, and specifications of an application use case — informed by computer science theory and by critical programming factors. Students also practice expressing algorithms and logic language-agnostically through pseudocode and flowcharts.

## 2. Module Learning Objectives

1. Depict the role of theory and practice for improved solutions in computer science.
2. Compile current options within computer programming languages and techniques.
3. Program software solutions.
4. Explain theories, applications, and perspectives related to computer science.

## 3. Key Concepts and Terms

- Theoretical foundations of computer science (theory–practice relationship)
- Coding theory — syntax (language-specific words) and semantics (logic); Boolean/polynomial expressions
- Program specification ("spec") — requirements, validation of inputs, functionality, outputs
- Critical factors for language selection:
  - **Scalability** — supporting growing (and shrinking) demand; modularity; cloud deployment
  - **Performance** — hardware/infrastructure alignment; design patterns; "workhorse" languages like C++
  - **Security** — secure coding, encryption, hashing (passwords, credit cards, PII), authentication, anonymization
  - **Use case complexity** — e.g., healthcare/military vs. simple inventory database
  - **Development lifecycle, exception handling, readability, writability, portability** (from the assignment)
- Algorithms and logic; pseudocode (text or flowchart); input–processing–output (IPO) model
- Flowchart symbols: terminal (Main/End), process, decision (diamond / IF), function calls
- Modular design: GetChoice() for input, ProcessCelsius()/ProcessFahrenheit() for processing, DisplayResult() for output

## 4. Weekly Schedule (Wed–Sun pacing)


| Day         | Activity                                                                                                                                                     | Time    |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------- |
| Wed (today) | Read Lesson 5 intro: theories of CS, coding theory, important factors; skim textbook chapters on conditions &amp; condition examples; start reference search | 90 min  |
| Thu         | Deep-dive the 9 critical factors; outline the paper; select the three languages and the specific CS theory to feature                                        | 90 min  |
| Fri         | Draft paper sections 1–3 (theory–practice relationship, three-language synopsis, theory example); gather the 4+ peer-reviewed sources                        | 2 hrs   |
| Sat         | Build the four flowchart diagrams for the taxable-order problem; write the logic descriptions; draft/revise remaining sections                               | 2–3 hrs |
| Sun         | APA polish, Turnitin pre-check, submit to Dropbox **before 11:58 PM**                                                                                        | 1–2 hrs |


## 5. Instructional Sequence

### Part A — Theory and practice (60 min)

- Survey theoretical foundations of computer science (e.g., Wikipedia's theoretical CS overview) and how each topic area supports programmatic goals.
- Case example — **coding theory**: every line of code should be justified by syntax and semantics aligned to the use case; computational (mathematical) foundation using Boolean and polynomial expressions.
- Emphasize: requirements → algorithm design → program "spec" articulating all programmatic goals, input validation, and expected outputs.

### Part B — Critical factors for choosing a language (75 min)

Walk through each factor with a concrete example:

- **Scalability:** bidirectional scaling, modularity, cloud deployment, cost of poor design.
- **Performance:** C++ "workhorse" reputation vs. other considerations; design patterns' computational benefits.
- **Security:** encryption, enhanced hashing, authentication, anonymization; matching security rigor to use case (healthcare/military vs. inventory DB).
- **Use case complexity, development lifecycle, exception handling** (responding gracefully to errors instead of crashing), **readability, writability, portability.**
- Discussion: "For each of these 9 factors, name one language that handles it well and one that handles it poorly — and defend the claim."

### Part C — Algorithms, logic, and flowcharts (75 min)

- Pseudocode as language-agnostic design; text vs. flowchart forms.
- Study the temperature-converter flowcharts (Figures 1–4 from the lesson, adapted from Braunschweig &amp; Busbee): Main method with terminal symbols, String variable `choice`, decision diamonds (IF), and the input/processing/output division across GetChoice(), ProcessCelsius()/ProcessFahrenheit(), CalculateCelsius()/CalculateFahrenheit(), and DisplayResult().
- Students trace the flowcharts and identify IPO roles of each function.
- Recommended tool: **Flowgorithm** (free, used to generate the textbook's flowcharts) or draw.io.

### Part D — Guided practice toward the assignment (60 min)

- Model the taxable-order flowchart structure as a class:
  - Main: get input → decide taxable or not → call the appropriate function → call display.
  - Function 1: calculate total **with** tax; return result.
  - Function 2: calculate total **without** tax; return result.
  - Display function: natural-language message including the returned value.
- Students then build their own versions with full logic descriptions.

## 6. Assignment 5 — Assess Current Programming Options and Their Relevance to Various Needs

**Due:** Sunday, September 27, 2026, 11:58 PM · **Worth:** 10 points · **Submitted via** Turnitin™/Dropbox

Write a **6–8 page paper** (including \~2 pages of flowcharts; excluding title and reference pages) addressing all of the following:

1. **Theory ↔ practice:** Describe the relationship between theory, programming with current languages, and their application to create solutions meeting system requirements for a given use case.
2. **Three-language synopsis:** Develop a high-level synopsis of three different programming languages used today for programming problems.
3. **Theory example:** Select a specific computer science theory, explain how it influences program development, and give a representative example.
4. **Critical factors:** Explain the relevance of scalability, performance, security, use case complexity, development lifecycle, exception handling, readability, writability, and portability in choosing the optimal language.
5. **Four flowchart diagrams** depicting the algorithms and logic (pseudocode) for this computational problem:
  - A **main method** that determines whether an order is taxable based on user input and calls the appropriate function;
  - A function calculating the order total **with tax**, returning the result to main;
  - A function calculating the order total **without tax**, returning the result to main;
  - A **display function** showing the result in natural language, including the returned value.

**Requirements:** scholarly writing, current APA style; course resources **plus at least 4 peer-reviewed recent resources** from the library or appropriate standards/frameworks; Turnitin pre-check before submitting; adhere to the Academic Integrity Policy.

### Rubric summary (10 points)


| Criterion                                                                 | Points | Exceeds expectations looks like                     |
| ------------------------------------------------------------------------- | ------ | --------------------------------------------------- |
| Assessment of programming options, theory application, use-case alignment | 3      | Strong evidence of the theory–practice relationship |
| Assignment instructions                                                   | 2      | All instructions completed correctly                |
| Content &amp; critical thinking                                           | 2      | Thoughtful, thorough, well-reasoned responses       |
| Cohesion &amp; organization                                               | 2      | Central idea carried coherently throughout          |
| Grammar, mechanics, APA, resource integration                             | 1      | Error-free; all resources scholarly                 |


Grade bands: A range ≥ 9 pts · B range ≥ 8 · C range ≥ 7.3 · Deficient ≥ 4 · Not evident 0–3.9.

### Suggested paper outline

1. Title page (APA 7)
2. Introduction — the language-selection problem and the role of bias
3. Theory, programming, and applied solutions
4. Synopsis of three current languages (e.g., Python, C++, C# — ties to your C# port-scanner article)
5. A selected computer science theory and its influence on development (e.g., coding theory)
6. Critical factors for optimal language choice (all nine)
7. Flowchart diagrams (4) with logic descriptions
8. Conclusion
9. References (course texts + ≥4 peer-reviewed sources)

## 7. Connecting the Uploaded Course Resources

- **Programming Fundamentals, 2nd ed. (Busbee &amp; Braunschweig)** — course textbook; use the conditions/condition-examples chapter and the modular input–processing–output function pattern (cited in the lesson's Figures 1–4).
- **Pashynskykh et al. (2022), "Research of the possibilities of the C# programming language for creating cybersecurity analysis software..."** — strong peer-reviewed example of C# applied to a real use case (port scanning, security audits): usable both in the three-language synopsis and as one of the four required peer-reviewed sources.
- **Yu &amp; Duan (2022), "A Reverse Modification Method for Binary Code and Data" (Sensors, MDPI)** — peer-reviewed source illustrating C++ and design patterns in distributed/real-time systems (main-loop architecture); relevant to the performance, security, and use-case complexity factors.

Both journal articles are recent (2022), peer-reviewed, and directly support the paper's language-comparison and theory-application sections.

## 8. Assessment &amp; Differentiation

- **Formative checks:** exit ticket — "Name three critical factors and one language that fits each"; flowchart-tracing question on the temperature example.
- **Support:** students new to flowcharts should start in Flowgorithm and replicate the lesson's temperature-converter figures before attempting the taxable-order diagrams; provide a worked Main-method skeleton.
- **Stretch:** students who finish early can prototype their taxable-order program in an actual language (e.g., Python or C#) and include a screenshot appendix — noting the paper itself requires flowcharts, not code.
- **Time-risk warning:** the paper is long (6–8 pages) and flowcharts are time-consuming; students should not start Saturday. The Sunday slot should be review, APA formatting, and Turnitin pre-check only.
