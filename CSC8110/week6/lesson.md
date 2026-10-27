# Week 6: Distributed Algorithms & Data Decryption

**Dates:** Nov 30 – Dec 6, 2026 · **Module:** 3 · **Focus:** Hashing, clustering & file sharing

## Learning Objectives
- Compare hashing, clustering, and file-sharing algorithms in distributed systems.
- Describe system architectures and deployment strategies for efficiency.
- Apply quantitative reasoning to algorithm evaluation.

## Key Topics
- Hashing, clustering, and file-sharing algorithms for data decryption and clustering in distributed systems.
- System architecture, coding/implementation structures, and deployment for efficiency.
- Potential issues and resolutions; algorithm code examples.
- Quantitative reasoning: coding/naming standards for consistent development across teams and platforms.

## Readings & Resources
- Lesson 7 – What Is Quantitative Reasoning (coding/naming standards, application types)
- Module 3 overview — integrating theory with practical programming
- Textbook: greedy, dynamic programming, graph algorithm chapters per Course Resources plan

## Assignment Due This Week

### Assignment 6 — Compare Algorithms for Data Decryption and Clustering
**Due: Dec 6, 2026 11:59 PM · 10 points · Turnitin enabled**

#### Assignment Instructions
Research hashing, clustering, and file-sharing algorithms in distributed systems, and write a paper comparing each algorithm's use for **data decryption and clustering** (these go beyond simple linear/graph searching or sorting). Your paper must include:

- A description of the architecture.
- Information about the architecture, coding, and implementation structures of each algorithm on data sets.
- An explanation of how the architecture can be deployed for efficient performance.
- Any issues that could be encountered and how they could be resolved.
- Examples of algorithm code.
- **Length:** 5–7 pages (excluding title and references) · **References:** ≥5 scholarly resources · APA.

#### Simplified Grading Rubric (10 pts)
| Criterion | Weight | To earn full points |
|---|---|---|
| Description of the system architecture + explanation of how that architecture helps performance | 3 pts | Strong architecture description AND strong performance explanation, peer-reviewed |
| Assignment instructions | 2 pts | All five bullets covered, including code examples |
| Content & critical thinking | 2 pts | Genuine comparison of the three algorithm families |
| Cohesion & organization | 2 pts | One framework (architecture → coding → deployment → issues) applied to all three |
| Grammar, mechanics, APA, resources | 1 pt | Error-free APA; scholarly sources |

**Grade scale:** Exceeds ≥9 · Meets ≥8 · Needs Improvement ≥7.3 · Deficient ≥4

#### Assignment Outline & Writing Inspiration
1. **Introduction (~0.5 pg)** — Distributed systems context: why decryption and clustering at scale need specialized algorithms (not simple search/sort).
2. **Hashing algorithms (~1.25 pg)** — Architecture (hash functions, hash tables, distributed hash tables), how hashing supports data decryption/verification, coding/implementation structure, a code example (e.g., SHA-256 or a DHT lookup). Deployment: consistent hashing for load distribution.
3. **Clustering algorithms (~1.25 pg)** — Architecture (k-means, hierarchical, density-based in distributed settings), how clustering organizes datasets, code example, deployment for efficient performance (parallel/distributed clustering, MapReduce-style).
4. **File-sharing algorithms (~1.25 pg)** — Architecture (peer-to-peer, chunking, BitTorrent-style protocols), role in secure data distribution, code example, deployment: how partitioning and replication improve throughput.
5. **Issues & resolutions (~1 pg)** — Inspiration: hash collisions, key management in decryption, cluster instability (choosing k), network churn in P2P, consistency vs. availability trade-offs — each with a concrete resolution.
6. **Comparative analysis & conclusion (~0.75 pg)** — Which family for which workload; how architecture drives performance.
7. **References** — ≥5 scholarly sources.

## Study Checklist
- [ ] Read Lesson 7 and Module 3 materials
- [ ] Draft architecture diagrams for the three algorithm families
- [ ] Collect runnable code examples for each algorithm
- [ ] Submit by Dec 6 (Turnitin pre-check first)

## Notes / Repo Links
_(paste your repo links, drafts, and instructor feedback here)_
