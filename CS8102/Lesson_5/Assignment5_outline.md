# Assignment 5: Paper Outline, Writing Tips, and Suggested Sources

**Paper:** Assess Current Programming Options and Their Relevance to Various Needs  
**Length:** 6–8 pages (incl. \~2 pages of flowcharts; excl. title &amp; references) · **APA 7** · **≥4 peer-reviewed sources**  
**Due:** Sunday, September 27, 2026, 11:58 PM · Turnitin™ pre-check, then submit to Dropbox

---

## 1. Page-Budgeted Outline

**Target: \~6–8 double-spaced pages.** Approximate budgets below assume 250–280 words/page.


| §   | Section                                               | Pages | What it must do                                                                                                                                                                                                                                                                                                     |
| --- | ----------------------------------------------------- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| —   | Title page (APA 7)                                    | —     | Not counted                                                                                                                                                                                                                                                                                                         |
| 1   | **Introduction**                                      | 0.5   | Hook: language choice is a high-stakes, bias-prone decision. State thesis: optimal language selection requires linking theory, practice, and use-case requirements. Preview the paper's structure.                                                                                                                  |
| 2   | **Theory, Programming, and Applied Solutions**        | 1–1.5 | Describe the theory–practice relationship: requirements → algorithm design → program spec. Explain how theoretical foundations support programmatic goals, input validation, and functional outputs. Cite a theoretical-CS overview.                                                                                |
| 3   | **A Selected Computer Science Theory: Coding Theory** | 1     | Define coding theory (syntax + semantics, Boolean/polynomial expressions, information transfer between states). Give one concrete representative example, e.g., how error-detecting codes or Boolean logic shape input validation in your flowchart program.                                                        |
| 4   | **Synopsis of Three Programming Languages**           | 1–1.5 | High-level synopsis of three current languages (suggested: **Python, C#, C++**). For each: origin/paradigm, typical use cases, strengths/weaknesses across the critical factors. Keep parallel structure — same factors per language.                                                                               |
| 5   | **Critical Factors in Language Selection**            | 1–1.5 | Explain relevance of **all nine**: scalability, performance, security, use case complexity, development lifecycle, exception handling, readability, writability, portability. Anchor several factors to your three languages (e.g., C++ performance, C# security tooling, Python readability).                      |
| 6   | **Flowchart Diagrams (4) with Logic Descriptions**    | \~2   | Taxable-order problem: (a) Main method deciding taxable vs. not; (b) function: total with tax; (c) function: total without tax; (d) display function with natural-language message including the returned value. Each diagram gets a short paragraph explaining its logic (terminal symbols, decisions, IPO roles). |
| 7   | **Conclusion**                                        | 0.5   | Restate the theory–practice thesis; synthesize which factors matter most for the demonstrated use case; end with insight (not a mere summary).                                                                                                                                                                      |
| —   | References                                            | —     | Not counted; course texts + ≥4 peer-reviewed sources                                                                                                                                                                                                                                                                |


### Section 6 flowchart checklist

- [ ] Main: Start → get order input → decision diamond (taxable?) → call Tax/NoTax function → call Display → End
- [ ] With-tax function: accepts inputs → `total = subtotal * (1 + tax_rate)` → return total
- [ ] Without-tax function: `total = subtotal` → return total
- [ ] Display function: prints natural-language sentence containing the returned value
- [ ] Every function has terminal (Start/End) symbols
- [ ] One descriptive paragraph per diagram (≈50–80 words each)

**Tip:** Build the diagrams in Flowgorithm or draw.io first (Saturday task) so you can describe real logic rather than inventing descriptions later.

---

## 2. Writing Tips (mapped to the rubric)

### Theory–practice evidence (3 pts)

- Use the phrase "theory and practice" deliberately in the thesis, section 2 topic sentence, and conclusion — graders scan for it.
- Show the *chain*: requirements → theory-informed design decision → practical language feature. Don't just define theory; apply it.
- Your flowchart program is the perfect concrete anchor: "coding theory justifies the decision diamond that validates taxable status before processing."

### Follow all instructions (2 pts)

- Re-read the five instruction bullets as a checklist before submission; each bullet needs its own clearly identifiable coverage.
- Nine critical factors — literally count them in your draft. Missing even one (e.g., "writability") costs points under this criterion.
- Three languages — exactly three, each with a genuine synopsis, not one sentence each.

### Content &amp; critical thinking (2 pts)

- Make a *choice* and defend it: end section 5 with, "For a secure, scalability-sensitive transactional application like the one diagrammed, C# is the optimal choice because…" Taking a position demonstrates reasoning.
- Compare rather than list: "Python's readability accelerates development, whereas C++'s manual memory management trades writability for performance."
- Add one insight per section that a lesson document did not state verbatim — e.g., how portability affects lifecycle cost.

### Cohesion &amp; organization (2 pts)

- Use APA Level 1 headings matching the assignment bullets; graders should find each requirement in one glance.
- Open every body paragraph with a topic sentence tied to the thesis; close sections with a transition sentence.
- Keep parallel structure in the three-language synopsis (same factor order for each language).

### Grammar, APA, sources (1 pt)

- APA 7: title page, Level 1 headings, in-text citations for every sourced claim, reference list with hanging indents, DOI/URL for each source.
- Verify every peer-reviewed source in your university library's databases (EBSCO, etc.) so the grader can locate it — keep the library permalink.
- Run the Turnitin pre-check with time to spare; paraphrase rather than quote, and cite even paraphrases.
- Read the final draft aloud to catch run-ons and missing articles; then one slow proofread pass focused only on APA formatting.

### Time management

- Flowcharts and reference hunting are the two time sinks — start both by Friday.
- Sunday should be only: APA polish → Turnitin pre-check → revise → submit before 11:58 PM.

---

## 3. Suggested Peer-Reviewed Sources (4+ required)

You need at least **four** peer-reviewed, recent sources. Your two uploaded journal articles already qualify; pick at least two more from the list below. Verify each in your university library before citing.

### Already in hand (course uploads)

1. **Pashynskykh, V., Meleshko, Y., Yakymenko, M., Bashchenko, D., &amp; Tkachuk, R. (2022).** Research of the possibilities of the C# programming language for creating cybersecurity analysis software in computer networks and computer-integrated systems. *Advanced Information Systems, 6*(2). [https://doi.org/10.20998/2522-9052.2022.2.09](https://doi.org/10.20998/2522-9052.2022.2.09) — perfect for the C# synopsis (port-scanning/security tooling) and the security factor.
2. **Yu, L., &amp; Duan, Y. (2022).** A reverse modification method for binary code and data. *Sensors, 22*(20), 7714. [https://doi.org/10.3392/s22207714](https://doi.org/10.3392/s22207714) — supports C++ performance, design patterns, security/complexity factors.

### Recommended additions (peer-reviewed)

3. **Saghafi, N., et al. (2021/2022).** A decision model for programming language ecosystem selection: Seven industry case studies. *Information and Software Technology* (ScienceDirect). [https://www.sciencedirect.com/science/article/pii/S0950584921001051](https://www.sciencedirect.com/science/article/pii/S0950584921001051) — directly on-topic: a validated decision model for choosing a language ecosystem, evaluated across seven companies. Strong for sections 2 and 5.
4. **Comparative analysis of six programming languages based on readability, writability, and reliability.** *IEEE* (IEEE Xplore). [https://ieeexplore.ieee.org/document/9689813/](https://ieeexplore.ieee.org/document/9689813/) — evaluates exactly the readability/writability/reliability factors named in the assignment. (Related open version: Nanz, S. et al., *Comparative study of six programming languages*, arXiv:1504.00693, [https://arxiv.org/abs/1504.00693](https://arxiv.org/abs/1504.00693))
5. **Sharma, M., et al. (2020).** Code readability management of high-level programming languages: A comparative study. *International Journal of Advanced Computer Science and Applications (IJACSA), 11*(3). [https://thesai.org/Publications/ViewPaper?Volume=11&amp;Issue=3&amp;Code=IJACSA&amp;SerialNo=75](https://thesai.org/Publications/ViewPaper?Volume=11&Issue=3&Code=IJACSA&SerialNo=75) — empirical readability comparison; good for the readability factor and language synopsis.
6. **Empirical study on the impact of programming languages on the performance of open-source serverless platforms** (ResearchGate listing). [https://www.researchgate.net/publication/381041637](https://www.researchgate.net/publication/381041637) — recent empirical performance data across languages; supports the performance and scalability factors.
7. **Kadams, A. A., &amp; Oyelere, S. S. (2026).** Factors influencing programming language selection (learner/industry perspectives). *International Journal of Technology in Education and Science, 10*, 133–161. [https://ijtes.net/index.php/ijtes/article/download/5061/2857/5292](https://ijtes.net/index.php/ijtes/article/download/5061/2857/5292) — recent (2026) peer-reviewed study of language-selection criteria including real-world applicability.

### Course resources (cite in addition, not counted toward the 4 peer-reviewed minimum)

- Braunschweig, D., &amp; Busbee, K. L. (n.d.). *Programming fundamentals – A modular structured approach* (2nd ed.). [https://press.rebus.community/programmingfundamentals/](https://press.rebus.community/programmingfundamentals/) — source of the flowchart figures and the IPO/modular design pattern.
- Wikipedia entries cited in the lesson (theoretical computer science; coding theory) — use only as background, not as one of your four scholarly sources; graders expect peer-reviewed material there.

### Suggested citation mix

- Section 2 (theory/practice): source 3 (decision model) + theoretical CS background
- Section 3 (coding theory): coding-theory reference + your flowchart example
- Section 4 (three languages): sources 1 (C#), 2 (C++), 5 (readability) or 4
- Section 5 (nine factors): sources 4 (readability/writability/reliability), 6 (performance), 1 (security), 3 (lifecycle/ecosystem)
