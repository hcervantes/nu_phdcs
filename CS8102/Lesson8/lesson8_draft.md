# Ethical and Social Issues in Computer Science and Technology: A Systems Theory Perspective

**Hector Cervantes**
**[University], [Course], [Instructor]**
**October 18, 2026**

> Drafting notes (remove before submitting): ~8.5 pages of body text when formatted at APA 7 (Times New Roman 12, double-spaced). Fill in the bracketed items on the title page. Run a Turnitin pre-check after adding your final source choices, and trim the optional material in Sections VII–VIII if the page count runs long.

## Abstract

Emerging computing technologies, including artificial intelligence (AI), the Internet of Things (IoT), and robotics, give rise to ethical and social risks that cannot be examined in isolation. This paper evaluates scholarly sources on these issues and synthesizes peer-reviewed literature using a systems theory perspective, demonstrating that ethical risks emerge from dynamic interactions among technological, human, organizational, and societal systems. Drawing on general systems theory, sociotechnical systems theory, cybernetics, and stakeholder theory, alongside the ACM Code of Ethics and formal theories of ethics and risk, the paper argues that effective oversight requires governance grounded in established ethical principles. The paper concludes that human-centred design, algorithmic accountability, and perpetual risk mitigation are the foundations of responsible computing.

*Keywords:* ethics, artificial intelligence, Internet of Things, automation, systems theory, risk

## Introduction

Just because a programmer can build something does not mean that they should. This simple maxim, drawn from the course lesson, captures the central ethical tension in modern computer science. Artificial intelligence now screens résumés and decides who is interviewed; the Internet of Things places sensors and cameras throughout homes, workplaces, and public spaces; and robotic process automation is reshaping entire occupations. These technologies are not neutral tools. They embed human choices and values, and their consequences ripple far beyond the organizations that deploy them.

The purpose of this paper is to evaluate the social and ethical issues related to computer science and technology in specific contexts, and to synthesize those challenges using a systems theory perspective. The thesis is as follows: emerging computing technologies, including AI, the IoT, and robotics, give rise to ethical and social risks that cannot be examined in isolation; a systems theory perspective demonstrates that these risks are produced through dynamic interactions among technological, human, organizational, and societal components, and therefore effective oversight requires governance approaches grounded in established ethical principles and formal theories of risk.

The paper proceeds in six parts, mirroring the assignment's requirements. First, it evaluates the scholarly sources that form the evidence base. Second, it describes the ethical implications of emerging technologies for individuality and human rights. Third, it synthesizes peer-reviewed literature through a systems theory lens, showing the interrelationships between computing and non-computing systems. Fourth, it describes the implications of these issues for thought leaders' approaches to solving programming problems. Fifth, it evaluates theories of ethics and risk in computing. Finally, it describes the ethical challenges and opportunities associated with AI, the IoT, and automation, concluding with governance recommendations.

## Evaluation of Scholarly Sources

The evidence base for this paper combines course resources with recent peer-reviewed literature, and the sources were selected against three criteria: peer review or recognized professional authority, recency, and explicit theoretical grounding.

The anchor scholarly source is the essay by D'Cruz, Du, Noronha, Parboteeah, Trittin-Ulbrich, and Whelan (2022), published in the *Journal of Business Ethics* to commemorate the journal's fortieth anniversary. Comprising commentaries by its editors on technology, megatrends, and work, the essay advances a human-centred approach to digital technology and is directly relevant to every section of this paper. Its peer-reviewed status, its 2022 publication, and its theoretical sophistication make it the paper's strongest evidence.

The theoretical anchors come from the Theories Used in IS Research Wiki (Larsen et al., 2025), which summarizes theories widely used in information systems research, including general systems theory, sociotechnical systems theory, and stakeholder theory. The wiki is used as an index to the primary literature rather than as an authority in itself; the underlying works of von Bertalanffy (1968), Trist and Bamforth (1951), and Freeman (1984) anchor the systems and stakeholder analysis. Novikov (2016) supplies the cybernetic perspective on control, communication, and feedback between humans and machines, and Lee (2015) provides the framing of risk and ethics in cyberspace from a professional governance standpoint.

Four additional peer-reviewed sources strengthen the evidence base. Friedman and Nissenbaum (1996) provides the classic taxonomy of bias in computer systems — preexisting, technical, and emergent bias — that remains the analytical standard for algorithmic bias. Martin (2019) establishes that firms can be held accountable for the ethical implications of the algorithms they design, directly rebutting inscrutability claims. Floridi et al. (2018) contributes the AI4People ethical framework, which adapts the biomedical principles of beneficence, non-maleficence, autonomy, and justice to AI and adds explicability. Mittelstadt et al. (2016) maps the full debate over the ethics of algorithms, including concerns about evidence, inference, and unfair discrimination. Finally, the ACM Code of Ethics and Professional Conduct (Association for Computing Machinery [ACM], n.d.) is the industry-standard professional code, described as the Hippocratic oath of computing.

Two points of disagreement in the literature deserve note. First, the older Friedman and Nissenbaum (1996) piece treats bias primarily as a design-time problem correctable through better processes, whereas D'Cruz et al. (2022) and Martin (2019) emphasize that firms have structural incentives to avoid accountability, meaning design fixes alone are insufficient without governance. Second, there is tension between efficiency-focused management literature and the human-centred business ethics tradition; the latter explicitly rejects the assumption that technology development is neutral or that fairness and efficiency are opposing goals. These tensions sharpen, rather than undermine, the synthesis presented below.

## Ethical Implications of Emerging Technologies: Individuality and Human Rights

The central ethical concern raised by emerging technologies is not the technology itself but the loss of meaningful human agency: people may be classified, monitored, influenced, or evaluated through systems they cannot see, understand, or contest (D'Cruz et al., 2022). This section describes those implications for individuality and for human rights, using stakeholder theory as the anchor.

### Algorithmic Decision-Making and Individuality

D'Cruz et al. (2022) warn that firms may portray AI as autonomous, objective, or too opaque to scrutinize, and then evade responsibility for harmful outcomes. The reality is that companies remain accountable for the value choices embedded in an algorithm's goals, success criteria, training data, assumptions, design, and deployment. When a hiring system screens résumés or assesses interviews, it can make mistakes consistently and "efficiently," affecting applicants who may never know AI was used. Profiling practices can create unequal power relationships and limit people's ability to understand or challenge decisions made about them.

Facial recognition sharpens the problem. Photographs posted for job applications, social networking, or dating may be used to train facial-recognition systems without the individuals' awareness. D'Cruz et al. (2022) call these people unaware stakeholders — affected by a digital technology without knowing it is being used. Since some systems crawl and detect data points across the global internet, any internet user can potentially fall into this category. Biometric data collection thus threatens individuality at its root: the most personal identifiers become inputs to systems the individual never consented to join.

In the workplace, pervasive digital systems enable continuous availability, traceability, surveillance, and control, blurring personal and professional boundaries. The documented results are reduced privacy, loss of autonomy, stress, and diminished dignity.

### Human Rights: Privacy, Surveillance, and Non-Discrimination

D'Cruz et al. (2022) frame privacy, non-discrimination, and recognition of affected but unknowing people as central human rights concerns. Privacy is treated as a core ethical responsibility; efficiency or opacity cannot justify privacy intrusion, discriminatory outcomes, or the use of people's data without meaningful recognition of their interests and rights.

Algorithmic bias is a human rights issue because it can reproduce and deepen existing inequality along lines of gender, race, ethnicity, geography, education, income, and even ZIP code (D'Cruz et al., 2022; Friedman & Nissenbaum, 1996). Disadvantaged consumers are especially exposed: the same groups face unequal access to technology, unequal digital skills, and heightened vulnerability to fraud, identity theft, and digital surveillance. Workplace systems can also discriminate — AI and robotics may favour particular social identities, producing exclusion or harassment — which is why the literature calls for inclusive design, diverse AI teams, fairer training data, and algorithmic change.

### The Stakeholder Theory Anchor

Stakeholder theory provides the analytical framework for these concerns. Freeman's (1984) theory argues that organizations must consider the interests, rights, and impacts of all stakeholders, not just shareholders; a stakeholder is any group or individual who can affect or be affected by the organization's actions. Traditionally, primary stakeholders (employees, customers, investors, suppliers) are distinguished from secondary ones (communities, regulators, media). The theory's ethical foundation is that decisions should not maximize profit at the expense of stakeholder well-being, and its managerial implication is that leaders must identify all relevant stakeholders, balance competing needs transparently, and avoid harm to vulnerable parties (Freeman, 1984; Larsen et al., 2025).

Applied to information systems, stakeholder theory demands ethical design of systems that affect users, non-users, and society; attention to unintended consequences such as privacy violations, bias, and surveillance; and recognition of unaware stakeholders whose data is collected without explicit consent. The concept of the unaware stakeholder (D'Cruz et al., 2022) extends Freeman's original definition, and the extension strengthens it: any internet user whose data is processed may have interests at stake. The ACM Code's first principles — contribute to society and human well-being, acknowledging that all people are stakeholders in computing; avoid harm; respect privacy; honor confidentiality — translate this theory directly into professional obligations (ACM, n.d.).

## Systems Theory Synthesis: Computing and Non-Computing Systems

The assignment's third requirement is to use a systems theory perspective to synthesize literature on the interrelationships between computing and non-computing systems. Three related theories — general systems theory, sociotechnical systems theory, and cybernetics — together show why the ethical risks described above are systemic rather than isolated.

### General Systems Theory

General systems theory (GST) holds that all systems — biological, social, technical, or organizational — share common structural and behavioral principles. A system is a set of interrelated components working together toward a purpose (von Bertalanffy, 1968). GST's core commitments are holism (a system cannot be understood by analyzing parts in isolation, because interactions create emergent properties), interdependence (a change in one part affects the whole — "everything is connected to everything else"), open-systems exchange with the environment, and equifinality (Larsen et al., 2025). Systems also exist in nested hierarchies: every system is a subsystem of a larger one.

For computer science, the implication is direct. The course lesson's example is a computer system whose graphics subsystem depends on the motherboard and central processing unit, which in turn depend on the power supply — if the motherboard fails, the graphics unit fails with it. But GST's deeper lesson is that technical systems intersect with non-technical systems: biological, family, societal, and economic systems. An AI hiring system is simultaneously a technical artifact, a component of an organization's workflow, and a node in the labor market and society. Feedback loops — positive feedback amplifying change, negative feedback stabilizing it — carry the effects of a design decision far beyond its original context (von Bertalanffy, 1968).

### Sociotechnical Systems Theory

Sociotechnical systems theory (STS) sharpens GST for the workplace. Trist and Bamforth's (1951) founding studies at the Tavistock Institute showed that every work system comprises two inseparable subsystems: a technical subsystem (tools, technologies, workflows) and a social subsystem (people, roles, communication patterns, norms). A system functions effectively only when both subsystems are jointly optimized; improving technology while ignoring the social subsystem produces reduced productivity, worker frustration, and ethical failure (Trist & Bamforth, 1951).

STS explicitly rejects the technological imperative — the idea that technology alone determines outcomes. This is precisely the lesson of algorithmic bias: a biased hiring algorithm is a sociotechnical failure in which designers ignored the social subsystem (the applicants, their contexts, and the social meanings of the data). STS predicts failure when technology is implemented without considering human roles, when workers are excluded from design decisions, and when cultural norms conflict with technological workflows (Larsen et al., 2025). In the case of emerging technologies, AI decision systems reshape communication patterns and decision rights, IoT deployments alter organizational workflows, and automation changes job roles — ripple effects that STS explains and predicts.

### Cybernetics

Cybernetics supplies the control-and-communication layer of the systems perspective. As Novikov (2016) explains, cybernetics studies control and communication in systems, especially interactions between humans and machines. Control is distributed: machines regulate actions through sensors and programmed rules, while humans provide goals, constraints, and corrective input. Communication is the continuous information exchange that binds human and machine components into a coherent system, and feedback — negative feedback stabilizing behavior, positive feedback amplifying it — is the mechanism by which systems adapt or drift.

The cybernetic view exposes an ethical insight: neither humans nor machines control the system alone, and outcomes depend on feedback quality. Poor feedback loops produce bias, unsafe automation, and system failure. When a machine learning model reinforces its own training patterns (positive feedback) with no human corrective input, harm accumulates unnoticed. Conversely, the ACM Code's requirement that professionals evaluate systems comprehensively and report risks (ACM, n.d.) is essentially a demand for healthy cybernetic feedback between the technical system and the human, organizational, and societal systems around it. Governance, in this framing, is a feedback loop.

Together, the three theories show that the interrelationships between computing and non-computing systems are structural, not incidental: AI hiring systems connect to labor markets; IoT deployments connect to urban infrastructure and domestic life; and robotics connects to the economic systems that allocate work and income. An ethical failure anywhere in the web propagates everywhere.

## Implications for Thought Leaders' Approaches to Solving Programming Problems

The systems perspective has direct implications for how thought leaders approach programming problems. Three are central.

First, stakeholder requirements must take precedence over the designer's cognitive bias. The course lesson notes that solving programming problems with a cognitively biased algorithmic approach — one that does not factor in the needs and requirements of the stakeholders who will use the software — produces systems that fail ethically and reputationally. Stakeholder theory operationalizes the fix: identify all affected parties, including unaware ones, understand their interests, and balance competing needs transparently (Freeman, 1984). Jointly optimizing the technical and social subsystems (Trist & Bamforth, 1951) means requirements gathering is an ethical activity, not merely a technical one.

Second, code quality versus deadline pressure is a systems problem, not only a personal one. Developers pushed to meet or undercut production deadlines may cut corners on quality, producing bugs that harm end users, the organization's bottom line, and its reputation. From a systems perspective, the deadline pressure in one subsystem (project management) propagates defects into other subsystems (users, maintenance teams, society). The ACM Code addresses this directly: professionals must strive for high quality in both process and product, give thorough evaluations including risk analysis, and work only within areas of competence (ACM, n.d.). Employer–employee relationships, whether salaried or contractual, carry a recognized propensity for such issues, which is why the Code assigns leaders heightened responsibility.

Third, "move fast and break things" must be replaced with human-centred design. D'Cruz et al. (2022) show that the profitability narrative behind rapid disruption rests on flawed assumptions: that technology development is neutral, that efficiency is the only goal, and that inscrutability shields firms from accountability. A human-centred approach implies that digital technologies should be developed in the interest of, and to the benefit of, the people affected by them.

Concretely, thought leaders should institutionalize governance structures. The ACM Code is the industry-standard professional code, and organizations can and should extend it internally: guidelines for responsible AI development, rules for handling user data and privacy, expectations for transparency and documentation, policies for bias mitigation and fairness testing, standards for secure coding, and procedures for reporting ethical concerns (ACM, n.d.). Such codes align technology with the organizational mission, reduce legal and reputational risk, create consistent decision-making across teams, embed ethical thinking into development workflows, and support governance bodies such as ethics committees or review boards. Institutional theory explains why this diffusion matters: organizations adopt governance frameworks through coercive (regulatory), mimetic (imitating perceived best practices), and normative (professional training) pressures, meaning thought leaders who model ethical practice reshape their entire industry (Larsen et al., 2025).

## Theories of Ethics and Risk

The assignment's fifth requirement is to evaluate theories of ethics and risk in computers and emerging technologies. Three ethical traditions, one AI-specific framework, and one risk-management approach together form the toolkit.

### The Ethical Theory Toolkit

Consequentialism (utilitarianism) judges decisions by their outcomes: an AI deployment is ethical if its aggregate benefits outweigh its harms. This lens is unavoidable in technology governance — cost-benefit reasoning is how organizations justify or reject systems — but it fails when harms fall unequally on marginalized groups, which is why justice must complement it (Floridi et al., 2018). Deontology judges decisions against duties: the ACM Code is a deontological instrument, establishing professional duties to avoid harm, respect privacy, honor confidentiality, and be honest and trustworthy regardless of consequences (ACM, n.d.). Virtue ethics asks what the trustworthy professional does: it is the character-based tradition underlying the Code's description as the conscience of the computing profession.

### The AI4People Framework

Floridi et al.'s (2018) AI4People framework adapts bioethics' four principles — beneficence, non-maleficence, autonomy, and justice — to AI and adds a fifth, explicability. The five principles form a complementary safeguard system that directs AI toward social value while limiting four societal risks: devalued human abilities, removed human responsibility, reduced human control, and eroded self-determination. Beneficence requires AI to expand human flourishing rather than merely replace labor; justice requires fair distribution of benefits and transition costs; non-maleficence demands prevention of harmful deskilling in high-stakes fields such as health care and aviation. Explicability — intelligible decisions and identifiable accountability — is the enabling principle: without it, one cannot verify benefit, detect harm, preserve human choice, or remedy unfairness. Autonomy supports a decide-to-delegate model in which people retain, in principle, the ability to override AI.

The framework's main limitation is that principles alone do not resolve trade-offs: automation may improve well-being while simultaneously disrupting jobs. Floridi et al. (2018) therefore pair the principles with mechanisms — bias auditing, redress and liability processes, participatory limits on delegation, and ongoing public oversight. This positions AI ethics as a governance problem rather than a purely technical one.

### Risk and the Inscrutability Fallacy

Lee (2015) frames the risk side: when computers are used in ways that violate ethical principles, there is inherent risk to the technical, legal, and financial components affecting stakeholders. Leadership must recognize risk through cost-benefit analysis and risk analysis as countermeasures, and because technological advances continually challenge those countermeasures, risk mitigation is a perpetual endeavor rather than a one-time activity. Mittelstadt et al. (2016) add that algorithmic harms are distinctive because algorithms are often opaque, produce evidence rather than facts, and can discriminate at scale — meaning traditional accountability mechanisms struggle.

The inscrutability fallacy is the central obstacle. Firms confronted with a harmful algorithmic outcome claim "it's not us, it's them" — displacing responsibility toward the autonomous agent (D'Cruz et al., 2022). Martin (2019) dismantles this argument: if an algorithm is designed to preclude individuals from taking responsibility within a decision, the designer of the algorithm should be held accountable for its ethical implications in use. Design decisions — what data, what optimization target, what success criterion — are choices, and choices have authors. SOIPSVM research extends this by showing that organizations violate privacy and security rules selectively and opportunistically when performance falls short of aspiration levels (Larsen et al., 2025), which means accountability regimes must anticipate strategic rule-breaking, not just negligence.

## Ethical Challenges and Opportunities: AI, the IoT, and Automation

### Artificial Intelligence

The ethical challenges of AI are algorithmic bias, missing explainability, contested accountability, and dual-use. Friedman and Nissenbaum's (1996) taxonomy remains the clearest map: preexisting bias enters systems from society and designers (e.g., loan software penalizing certain neighborhoods); technical bias arises from design constraints (e.g., display rankings favoring some providers); and emergent bias develops after deployment as users, knowledge, and norms change (e.g., an expert system misused by non-experts). Their recommendation — that freedom from bias should be a core quality criterion alongside reliability and safety, pursued through early scrutiny, inclusive testing, and responsiveness to change — is now standard practice in responsible AI. The opportunity is equally clear: AI can remove dangerous and repetitive work and, under the CSR 3.0 vision, be deliberately aimed at social and environmental problems (D'Cruz et al., 2022). Governance recommendation: mandatory bias auditing, explainability requirements, and diverse development teams.

### The Internet of Things

The IoT's challenges are privacy of biometric and behavioral data and security of connected pathways. The lesson's warning is blunt: network connection pathways and the collection of massive amounts of biometric data are areas that can be exploited for unethical gain. From a systems view, every IoT device is a sensor flowing data across the boundary of an open system — the home, the body, the workplace — and each flow is a potential privacy violation against stakeholders who may be unaware their data is being collected. The opportunity lies in efficiency and safety gains under ethical governance. Governance recommendation: data minimization by design, security standards for connected devices, and meaningful consent mechanisms that reach unaware stakeholders.

### Automation and Robotics

Automation's challenges are labor displacement, deskilling, safety, and the prospect of a post-work future. D'Cruz et al. (2022) note that technology can remove dangerous work and improve safety, but also displace jobs, intensify work, weaken the meaning and identity derived from work, and worsen inequality; platform and remote work arrangements can enable constant availability, surveillance, blurred boundaries, and precarity. The ethical question of a possible post-work future is how income, purpose, social connection, and essential labor are distributed in the transition. The opportunity is that, governed well, automation can augment rather than displace human capability — Floridi et al.'s (2018) beneficence principle in practice. Governance recommendation: reskilling programs, worker voice in automation decisions, and transition support, with human override preserved in consequential decisions.

Across all three technologies, the lesson's governance principle applies: maintaining a system of checks and balances is required to ensure governance and professional conduct procedures are in place, because all solutions ultimately rely on the humans creating the application for the specific use case.

## Conclusion

This paper has argued that emerging computing technologies produce ethical and social risks that cannot be examined in isolation, because those risks arise from dynamic interactions among technological, human, organizational, and societal systems. The systems theory synthesis supports the thesis in three layers: general systems theory shows that computing systems are structurally nested within non-computing systems, so design decisions propagate through feedback loops that reach labor markets, homes, and democratic life; sociotechnical systems theory shows that outcomes depend on the joint optimization of technical and social subsystems, and that ethical failures such as algorithmic bias are sociotechnical misalignments; and cybernetics shows that control is distributed between humans and machines, making governance itself a feedback loop whose quality determines whether systems adapt responsibly or drift into harm.

Three takeaways follow. First, interdependence is the defining feature of computing's social context: stakeholder theory, extended to include unaware stakeholders, obliges professionals to account for people they will never meet. Second, accountability cannot be outsourced to the algorithm: the inscrutability fallacy fails as an excuse, and professional codes such as the ACM Code exist precisely to anchor responsibility in human choices. Third, risk mitigation is perpetual: as technology advances, countermeasures must evolve, which is why frameworks like AI4People pair ethical principles with auditing, redress, and ongoing oversight rather than one-time compliance.

The future direction is clear and demanding: ongoing governance and human-centred design are not constraints on innovation but the conditions under which innovation remains socially legitimate. Computing professionals who internalize this — treating ethics as a systems property rather than an afterthought — will define the profession's next chapter.

## References

Association for Computing Machinery. (n.d.). *ACM code of ethics and professional conduct*. https://www.acm.org/code-of-ethics

D'Cruz, P., Du, S., Noronha, E., Parboteeah, K. P., Trittin-Ulbrich, H., & Whelan, G. (2022). Technology, megatrends and work: Thoughts on the future of business ethics. *Journal of Business Ethics, 180*, 879–902. https://doi.org/10.1007/s10551-022-05240-9

Floridi, L., Cowls, J., Beltrametti, M., Chatila, R., Chazerand, P., Dyer, C., … Vayena, E. (2018). AI4People—An ethical framework for a good AI society: Opportunities, risks, principles, and recommendations. *Minds and Machines, 28*(4), 689–707. https://doi.org/10.1007/s11023-018-9482-5

Freeman, R. E. (1984). *Strategic management: A stakeholder approach*. Pitman.

Friedman, B., & Nissenbaum, H. (1996). Bias in computer systems. *ACM Transactions on Information Systems, 14*(3), 330–347. https://doi.org/10.1145/230538.230561

Larsen, K. R., Saini, V., Singh, N. B., & Mueller, R. M. (Eds.). (2025). *Theories used in IS research wiki*. https://is.theorizeit.org/wiki/Main_Page

Lee, W. W. (2015). Risk and ethics in cyberspace. *ISACA Journal, 2015*(6). https://www.isaca.org/resources/isaca-journal/issues/2015/volume-6/risk-and-ethics-in-cyberspace

Martin, K. (2019). Ethical implications and accountability of algorithms. *Journal of Business Ethics, 160*(4), 835–850. https://doi.org/10.1007/s10551-018-3921-3

Mittelstadt, B. D., Allo, P., Taddeo, M., Wachter, S., & Floridi, L. (2016). The ethics of algorithms: Mapping the debate. *Big Data & Society, 3*(2). https://doi.org/10.1177/2053951716679679

Novikov, D. A. (2016). *Cybernetics: From past to future*. Springer. https://doi.org/10.1007/978-3-319-27397-6

Trist, E. L., & Bamforth, K. W. (1951). Some social and psychological consequences of the longwall method of coal-getting. *Human Relations, 4*(1), 3–38.

von Bertalanffy, L. (1968). *General system theory: Foundations, development, applications*. George Braziller.
