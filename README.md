# Reasoning-Vulnerabilities-across-domains-in-gpt-oss-20b
Systematic Discovery of Novel Edge Deployment Inconsistencies and Safety Blind Spots


This research presents a comprehensive red teaming analysis of OpenAI's gpt-oss-20b model, revealing six distinct categories of previously undocumented vulnerabilities with significant implications for real-world deployment. Our primary contribution demonstrates hardware-dependent mathematical reasoning inconsistencies where identical problems yield contradictory results between GPU and CPU inference modes—a critical reliability issue for edge computing applications.

Through systematic testing across mathematical reasoning, semantic parsing, character processing, factual retrieval, and safety detection domains, we identified fundamental flaws that extend beyond documented limitations. Key findings include: (1) mathematical construction problems producing opposite conclusions under different hardware configurations, (2) persistent semantic misinterpretation in unit-based riddles, (3) basic character counting failures, (4) inconsistent factual retrieval patterns, and (5) safety blind spots failing to detect potential self-harm contexts.

Our methodology combines controlled experimental design with quantitative verification, edge device simulation, and cross-validation against official model documentation. All vulnerabilities were verified as novel through systematic keyword searches of the model card and comprehensive literature review. The work establishes new evaluation frameworks for hardware-dependent AI behavior and provides reproducible test cases for future safety assessments.

These findings have critical implications for deployment scenarios where model reliability is paramount, particularly in scientific computing, financial applications, and mental health support systems. The research contributes to advancing AI safety through systematic vulnerability discovery and establishes precedent for hardware-aware model evaluation protocols.
