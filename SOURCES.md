# Sources

All 190 sources in [The AI Safety Reading Room](https://aisafetyed-rjn8b2pr.manus.space), in three layers. Every link was checked against its title; see [`source-verification.csv`](source-verification.csv).

## Contents

- [Part 1: The roadmap](#part-1-the-roadmap)
  - [Room 01: Problem and objectives](#room-01-problem-and-objectives)
  - [Room 02: Training-time alignment](#room-02-training-time-alignment)
  - [Room 03: Attacks and robustness](#room-03-attacks-and-robustness)
  - [Room 04: Reasoning and interpretability](#room-04-reasoning-and-interpretability)
  - [Room 05: Monitoring, oversight, and control](#room-05-monitoring-oversight-and-control)
  - [Room 06: Agents and multimodal systems](#room-06-agents-and-multimodal-systems)
  - [Room 07: Privacy and social harms](#room-07-privacy-and-social-harms)
  - [Room 08: Evaluation and governance](#room-08-evaluation-and-governance)
- [Part 2: Topic guides](#part-2-topic-guides)
  - [01: Alignment, reward misspecification, and scalable oversight](#01-alignment-reward-misspecification-and-scalable-oversight)
  - [02: Interpretability, CoT faithfulness, and oversight](#02-interpretability-cot-faithfulness-and-oversight)
  - [03: Robustness, jailbreaks, and prompt injection](#03-robustness-jailbreaks-and-prompt-injection)
  - [04: Agents, multimodal safety, and autonomy](#04-agents-multimodal-safety-and-autonomy)
  - [05: Privacy, fairness, toxicity, and misuse](#05-privacy-fairness-toxicity-and-misuse)
  - [06: Evaluation, red teaming, and model monitoring](#06-evaluation-red-teaming-and-model-monitoring)
  - [07: Governance, standards, and institutional safety](#07-governance-standards-and-institutional-safety)
  - [08: Production guardrails, AI security, and MLOps](#08-production-guardrails-ai-security-and-mlops)
- [Part 3: Domain index](#part-3-domain-index)
  - [AI Guardrail Systems](#ai-guardrail-systems)
  - [AI Alignment Theory](#ai-alignment-theory)
  - [Monitoring, Anomaly Detection & Incident Response](#monitoring-anomaly-detection--incident-response)
  - [Chain-of-Thought Integrity & Reasoning Faithfulness](#chain-of-thought-integrity--reasoning-faithfulness)
  - [Jailbreaks, Adversarial Attacks & Evasion](#jailbreaks-adversarial-attacks--evasion)
  - [Multimodal Attacks & Injection](#multimodal-attacks--injection)
  - [Privacy, PII Detection & Data Minimisation](#privacy-pii-detection--data-minimisation)
  - [AI Regulation & Compliance Frameworks](#ai-regulation--compliance-frameworks)
  - [NLP, Classification & Transformers](#nlp-classification--transformers)
  - [System Architecture & Distributed Systems](#system-architecture--distributed-systems)
  - [Evaluation Methods & Benchmarks](#evaluation-methods--benchmarks)
  - [MLOps, Infrastructure & Production Engineering](#mlops-infrastructure--production-engineering)

---

## Part 1: The roadmap

Eight rooms of five sources each, in reading order. Start at Room 01 if you are new to the field.

### Room 01: Problem and objectives

*Start here to learn what alignment is trying to control and why proxy objectives fail.*

1. [AI Alignment: A Comprehensive Survey (2023)](https://arxiv.org/abs/2310.19852)
2. [Concrete Problems in AI Safety (2016)](https://arxiv.org/abs/1606.06565)
3. [Goodhart Taxonomy, Scott Garrabrant, Alignment Forum (2017)](https://www.alignmentforum.org/posts/EbFABnst8LsidYs5Y/goodhart-s-curse-and-limitations-on-ai-alignment)
4. [Learning from Human Preferences (2017)](https://arxiv.org/abs/1706.03741)
5. [Specification Gaming: The Flip Side of AI Ingenuity (2020)](https://deepmind.google/discover/blog/specification-gaming-the-flip-side-of-ai-ingenuity/)

### Room 02: Training-time alignment

*Compare preference learning, constitutional methods, truthfulness, and out-of-distribution goal failures.*

1. [Training Language Models to Follow Instructions with Human Feedback (InstructGPT, 2022)](https://arxiv.org/abs/2203.02155)
2. [Constitutional AI: Harmlessness from AI Feedback (2022)](https://arxiv.org/abs/2212.08073)
3. [Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback (2022)](https://arxiv.org/abs/2204.05862)
4. [TruthfulQA: Measuring How Models Mimic Human Falsehoods (2021)](https://arxiv.org/abs/2109.07958)
5. [Goal Misgeneralization in Deep Reinforcement Learning (2021)](https://arxiv.org/abs/2105.14111)

### Room 03: Attacks and robustness

*Read the threat literature before trusting a guardrail, especially for adaptive, indirect, and multi-turn attacks.*

1. [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injections (2023)](https://arxiv.org/abs/2302.12173)
2. [Jailbroken: How Does LLM Safety Training Fail? (2023)](https://arxiv.org/abs/2307.02483)
3. [Universal and Transferable Adversarial Attacks on Aligned Language Models (GCG, 2023)](https://arxiv.org/abs/2307.15043)
4. [JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models (2024)](https://arxiv.org/abs/2404.01318)
5. [HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal (2024)](https://arxiv.org/abs/2402.04249)

### Room 04: Reasoning and interpretability

*Understand why visible reasoning can help monitoring while remaining incomplete, strategic, or unfaithful.*

1. [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models (2022)](https://arxiv.org/abs/2201.11903)
2. [Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting (2023)](https://arxiv.org/abs/2305.04388)
3. [Measuring Faithfulness in Chain-of-Thought Reasoning (2023)](https://arxiv.org/abs/2307.13702)
4. [Mechanistic Interpretability for AI Safety: A Review (2024)](https://arxiv.org/abs/2404.14082)
5. [Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety (2025)](https://arxiv.org/html/2507.11473v1)

### Room 05: Monitoring, oversight, and control

*Move from behavioral safety claims to protocols that assume intentional subversion and capability gaps.*

1. [AI Control: Improving Safety Despite Intentional Subversion (2023)](https://arxiv.org/abs/2312.06942)
2. [Scalable Agent Alignment via Reward Modeling (2018)](https://arxiv.org/abs/1811.07871)
3. [Weak-to-Strong Generalization: Eliciting Strong Capabilities with Weak Supervision (2023)](https://arxiv.org/abs/2312.09390)
4. [Scaling Laws for Scalable Oversight (2025)](https://proceedings.neurips.cc/paper_files/paper/2025/hash/8c3caae2f725c8e2a55ecd600563d172-Abstract-Conference.html)
5. [Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training (2024)](https://arxiv.org/abs/2401.05566)

### Room 06: Agents and multimodal systems

*Once a model can use tools and interact with external state, output moderation is no longer enough.*

1. [AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents (2024)](https://arxiv.org/abs/2406.13352)
2. [InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated LLM Agents (2024)](https://arxiv.org/abs/2403.02691)
3. [WebArena: A Realistic Web Environment for Building Autonomous Agents (2023)](https://arxiv.org/abs/2307.13854)
4. [OSWorld: Benchmarking Multimodal Agents for Open-ended Tasks (2024)](https://arxiv.org/abs/2404.07972)
5. [MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models (2023)](https://arxiv.org/abs/2311.17600)

### Room 07: Privacy and social harms

*Keep PII, memorization, fairness, toxicity, and sociotechnical harms in the same safety conversation.*

1. [k-Anonymity: A Model for Protecting Privacy (2002)](https://dataprivacylab.org/dataprivacy/projects/kanonymity/kanonymity.pdf)
2. [The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks (2019)](https://arxiv.org/abs/1802.08232)
3. [Membership Inference Attacks Against Machine Learning Models (2016)](https://arxiv.org/abs/1610.05820)
4. [RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models (2020)](https://arxiv.org/abs/2009.11462)
5. [Ethical and Social Risks of Harm from Language Models (2021)](https://arxiv.org/abs/2112.04359)

### Room 08: Evaluation and governance

*Finish by connecting technical controls to documentation, risk management, standards, and deployment decisions.*

1. [Holistic Evaluation of Language Models (HELM, 2022)](https://arxiv.org/abs/2211.09110)
2. [Model Cards for Model Reporting (2019)](https://arxiv.org/abs/1810.03993)
3. [NIST AI Risk Management Framework (AI RMF 1.0), 2023](https://www.nist.gov/itl/ai-risk-management-framework)
4. [EU AI Act, Full Text (Regulation 2024/1689)](https://artificialintelligenceact.eu/the-act/)
5. [AI Security Institute Research Agenda](https://www.aisi.gov.uk/research-agenda)

---

## Part 2: Topic guides

Every source here comes with a note on why it belongs.

### 01: Alignment, reward misspecification, and scalable oversight

*Theories and empirical work on objectives, human feedback, goal generalization, honesty, corrigibility, deceptive behavior, and supervision that scales with model capability.*

- **[AI Alignment: A Comprehensive Survey (2023)](https://arxiv.org/abs/2310.19852)**  
  Ji et al. · arXiv · 2023  
  Use this as a map of the whole field. It distinguishes forward alignment from backward alignment and organizes the agenda around robustness, interpretability, controllability, and ethicality.

- **[Learning from Human Preferences (2017)](https://arxiv.org/abs/1706.03741)**  
  Christiano et al. · NeurIPS · 2017  
  The foundational preference-learning paper behind modern RLHF. Read it to understand how human judgments become an imperfect training signal and why reward-model misspecification matters.

- **[The Off-Switch Game (2016)](https://arxiv.org/abs/1611.08219)**  
  Hadfield-Menell et al. · 2016  
  A compact formal treatment of corrigibility: under what incentives will an agent allow humans to interrupt or shut it down? It provides the conceptual bridge between alignment and operational control.

- **[Goal Misgeneralization in Deep Reinforcement Learning (2021)](https://arxiv.org/abs/2105.14111)**  
  Langosco et al. · arXiv · 2021  
  Shows that an agent can learn the wrong goal while still performing well in familiar training environments. This is the practical distribution-shift case for treating training-time alignment as insufficient.

- **[Specification Gaming: The Flip Side of AI Ingenuity (2020)](https://deepmind.google/discover/blog/specification-gaming-the-flip-side-of-ai-ingenuity/)**  
  Krakovna et al. · DeepMind · 2020  
  A readable catalog of agents exploiting the letter rather than the spirit of an objective. Use it as an intuition-building companion to Goodhart and reward-hacking papers.

- **[Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback (2022)](https://arxiv.org/abs/2204.05862)**  
  Bai et al. · Anthropic · 2022  
  Read alongside InstructGPT and Constitutional AI to compare helpfulness and harmlessness objectives, preference data, and the limits of behavioral alignment.

- **[TruthfulQA: Measuring How Models Mimic Human Falsehoods (2021)](https://arxiv.org/abs/2109.07958)**  
  Lin et al. · ACL · 2022  
  A canonical demonstration that helpfulness and truthfulness can diverge. It belongs in any reading path about honesty, model behavior, and evaluation-aware safety claims.

- **[Weak-to-Strong Generalization: Eliciting Strong Capabilities with Weak Supervision (2023)](https://arxiv.org/abs/2312.09390)**  
  Burns et al. · OpenAI · 2023  
  A central modern paper on using weaker supervisors to train stronger models. It makes the promise and fragility of scalable oversight concrete through empirical experiments.

- **[Inverse Scaling: When Bigger Isn't Better (2023)](https://arxiv.org/abs/2306.09479)**  
  McKenzie et al. · 2023  
  Documents tasks where larger language models perform worse, including some safety-relevant behaviors. It is a useful warning against treating scale as a monotonic proxy for reliability.

- **[Aligning AI with Shared Human Values (2021)](https://arxiv.org/abs/2008.02275)**  
  Hendrycks et al. · ICLR · 2021  
  Introduces a broad taxonomy of risks and alignment-relevant values, connecting technical work to social and institutional harms that a purely capability-centric stack misses.

- **[Principle-Driven Self-Alignment of Language Models from Scratch with Minimal Human Supervision (2023)](https://arxiv.org/abs/2305.03047)**  
  Sun et al. · NeurIPS · 2023  
  A useful comparison point for constitutional or principle-based alignment. Read it to separate explicit principles, self-critique, and human supervision from runtime guardrails.

- **[A General Language Assistant as a Laboratory for Alignment (2021)](https://arxiv.org/abs/2112.00861)**  
  Askell et al. · Anthropic · 2021  
  Frames language assistants as a laboratory for studying helpfulness, honesty, harmlessness, and preference trade-offs. It supplies conceptual vocabulary for interpreting later post-training papers.

- **[Alignment Faking in Large Language Models (2024)](https://arxiv.org/abs/2412.14093)**  
  Anthropic · 2024  
  A direct modern bridge from deceptive alignment theory to observable model behavior. It belongs beside Sleeper Agents and eval-awareness work, with careful attention to the experimental setup and limitations.

- **[AI Control: Improving Safety Despite Intentional Subversion (2023)](https://arxiv.org/abs/2312.06942)**  
  Greenblatt et al. · 2023  
  The core AI-control paper: it evaluates safety protocols against an untrusted model that is actively trying to subvert them. It is essential for understanding why monitor design must assume adversarial behavior.

- **[Recommendations for Technical AI Safety Research Directions (2025)](https://alignment.anthropic.com/2025/recommended-directions/)**  
  Anthropic Alignment Science · 2025  
  Use this as the current agenda bridge: model cognition, CoT faithfulness, behavioral and activation monitoring, anomaly detection, scalable oversight, adversarial robustness, and control.

### 02: Interpretability, CoT faithfulness, and oversight

*Mechanistic interpretability, process supervision, reasoning faithfulness, model cognition, activation monitoring, and the conditions under which chain-of-thought can support safety monitoring.*

- **[Mechanistic Interpretability for AI Safety: A Review (2024)](https://arxiv.org/abs/2404.14082)**  
  Bereska & Gavves · 2024  
  The missing interpretability survey. It explains features, causal interventions, circuit analysis, scalability limits, and why interpretability can support safety without being a complete safety case.

- **[A Mathematical Framework for Transformer Circuits (2021)](https://transformer-circuits.pub/2021/framework/index.html)**  
  Elhage et al. · Transformer Circuits · 2021  
  Introduces the circuit-analysis vocabulary used by much of mechanistic interpretability. Read it before attempting to interpret attention heads, features, or causal pathways in safety work.

- **[Toy Models of Superposition (2022)](https://arxiv.org/abs/2209.10652)**  
  Elhage et al. · Anthropic · 2022  
  Explains why neural networks may represent more features than they have dimensions, creating polysemantic units. This is a foundational reason naive neuron-level monitoring can fail.

- **[Towards Monosemanticity: Decomposing Language Models With Dictionary Learning (2023)](https://transformer-circuits.pub/2023/monosemantic-features/index.html)**  
  Bricken et al. · Anthropic · 2023  
  Shows how sparse autoencoders can recover more interpretable features from language-model activations. It is a key practical entry point into feature-based monitoring.

- **[Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet (2024)](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)**  
  Anthropic · 2024  
  Extends sparse-feature analysis to a frontier-scale model and makes the scaling challenge concrete. Read it as a bridge between toy interpretability and deployment-scale monitoring.

- **[Interpretability in the Wild: A Circuit for Indirect Object Identification in GPT-2 Small (2022)](https://arxiv.org/abs/2211.00593)**  
  Wang et al. · 2022  
  A canonical end-to-end circuit analysis. It demonstrates what a causal mechanistic explanation looks like and what evidence is needed beyond correlational feature labels.

- **[In-context Learning and Induction Heads (2022)](https://arxiv.org/abs/2209.11895)**  
  Olsson et al. · 2022  
  A mechanistic account of a capability-relevant circuit motif. It is useful for learning how interpretability links internal mechanisms to behavior rather than merely producing post-hoc explanations.

- **[Locating and Editing Factual Associations in GPT (ROME, 2022)](https://arxiv.org/abs/2202.05262)**  
  Meng et al. · NeurIPS · 2022  
  Demonstrates causal localization and editing of factual associations. It is a useful caution that an apparent safety-relevant behavior may be distributed and entangled across representations.

- **[Language Models (Mostly) Know What They Know (2022)](https://arxiv.org/abs/2207.05221)**  
  Kadavath et al. · Anthropic · 2022  
  Introduces experiments on eliciting model knowledge and uncertainty. It belongs in the bridge between behavioral evaluation, honesty, calibration, and model cognition.

- **[Let's Verify Step by Step (2023)](https://arxiv.org/abs/2305.20050)**  
  Lightman et al. · OpenAI · 2023  
  The central process-supervision paper for mathematical reasoning. Compare step-level feedback with outcome-only feedback and consider how both can improve or distort CoT monitorability.

- **[Solving Math Word Problems with Process- and Outcome-Based Feedback (2022)](https://arxiv.org/abs/2211.14275)**  
  Uesato et al. · DeepMind · 2022  
  Provides a direct comparison between process and outcome supervision. It is essential for understanding the training pressures that shape visible reasoning traces.

- **[Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety (2025)](https://arxiv.org/html/2507.11473v1)**  
  Anthropic and collaborators · 2025  
  A current synthesis of why CoT may support monitoring, why monitorability can degrade under optimization or latent reasoning, and how to evaluate it as a safety property.

- **[Scaling Laws for Scalable Oversight (2025)](https://proceedings.neurips.cc/paper_files/paper/2025/hash/8c3caae2f725c8e2a55ecd600563d172-Abstract-Conference.html)**  
  NeurIPS · 2025  
  Quantifies how oversight success changes with capability gaps and studies nested scalable oversight. It gives the reading list a recent empirical treatment of the central scalability question.

### 03: Robustness, jailbreaks, and prompt injection

*Adversarial prompts, automated jailbreaks, indirect injection, RAG poisoning, robustness benchmarks, and defenses that should be tested against adaptive attackers.*

- **[Universal Adversarial Triggers for Attacking and Analyzing NLP (2019)](https://arxiv.org/abs/1908.07125)**  
  Wallace et al. · EMNLP · 2019  
  A classic adversarial-trigger paper that predates modern jailbreak terminology. It establishes why fixed filters and ordinary validation sets do not characterize worst-case model behavior.

- **[BadNL: Backdoor Attacks Against NLP Models (2020)](https://arxiv.org/abs/2006.01043)**  
  Chen et al. · 2020  
  Introduces a language-specific backdoor threat model. It broadens the threat picture from prompt-time attacks to compromised training data and model supply chains.

- **[PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts (2023)](https://arxiv.org/abs/2306.04528)**  
  Zhu et al. · 2023  
  A benchmark-oriented treatment of adversarial prompts, useful for structuring attack suites and separating prompt sensitivity from genuine model-safety failures.

- **[SmoothLLM: Defending Large Language Models Against Jailbreaking Attacks (2023)](https://arxiv.org/abs/2310.03684)**  
  Robey et al. · 2023  
  Presents randomized perturbation as a model-agnostic defense. Read it as a practical baseline for measuring whether an input-side defense generalizes across attack families.

- **[JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models (2024)](https://arxiv.org/abs/2404.01318)**  
  Chao et al. · 2024  
  A benchmark and dataset for comparing jailbreak attacks and defenses under a common protocol. It belongs in the evaluation section of any guardrail stack.

- **[HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal (2024)](https://arxiv.org/abs/2402.04249)**  
  Mazeika et al. · 2024  
  Provides standardized harmful-behavior evaluation and refusal metrics. Use it to avoid evaluating a guardrail with an ad hoc collection of prompts.

- **[A StrongREJECT for Empty Jailbreaks (2024)](https://arxiv.org/abs/2402.10260)**  
  Souly et al. · 2024  
  Introduces a transparent refusal-scoring approach and a stronger evaluation baseline for jailbreaks. Read it for metric design, not only for attack results.

- **[AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models (2023)](https://arxiv.org/abs/2310.04451)**  
  Liu et al. · 2023  
  Shows that jailbreak generation can optimize for semantic plausibility and stealth rather than obvious gibberish. It is a useful adversarial test for keyword-based filters.

- **[DeepInception: Hypnotize Large Language Model to Be a Jailbreaker (2023)](https://arxiv.org/abs/2311.03191)**  
  Li et al. · 2023  
  A role-play and nested-context attack that illustrates why safety evaluation must include compositional and multi-layer prompt structures.

- **[MASTERKEY: Automated Jailbreaking of Large Language Model Chatbots (2023)](https://arxiv.org/abs/2307.08715)**  
  Deng et al. · 2023  
  Demonstrates automated transfer of jailbreak strategies across chatbot systems. It is a useful reminder that safety tuning can leak across model families and interfaces.

- **[Ignore Previous Prompt: Attack Techniques For Language Models (2022)](https://arxiv.org/abs/2211.09527)**  
  Perez & Ribeiro · 2022  
  An early taxonomy of instruction-conflict and prompt-injection techniques. Read it before the later agent and indirect-injection papers to see how the threat model evolved.

- **[Prompt Injection Attack against LLM-integrated Applications (2023)](https://arxiv.org/abs/2306.05499)**  
  Liu et al. · 2023  
  Places prompt injection in the context of applications rather than isolated chat. It is direct prior work for boundary filtering, tool mediation, and content provenance checks.

- **[PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation (2024)](https://arxiv.org/abs/2402.07867)**  
  Zou et al. · 2024  
  Shows how malicious retrieved documents can manipulate RAG outputs. Read it as part of the indirect-injection threat model rather than treating retrieval as automatically trusted.

### 04: Agents, multimodal safety, and autonomy

*Tool use, browser and computer-use agents, multimodal attacks, trajectory-level safety, autonomy risk, preparedness policies, and security threat models.*

- **[WebArena: A Realistic Web Environment for Building Autonomous Agents (2023)](https://arxiv.org/abs/2307.13854)**  
  Zhou et al. · ICLR · 2024  
  A realistic benchmark for browser agents interacting with websites. It provides a concrete environment for testing trajectory-level safety, tool permissions, and prompt injection.

- **[BrowserGym: A Framework for Web-Agent Research](https://browsergym.readthedocs.io/)**  
  ServiceNow Research · Documentation  
  A practical environment for evaluating browser agents. Use it for reproducible safety experiments instead of relying only on static prompt sets.

- **[OSWorld: Benchmarking Multimodal Agents for Open-ended Tasks (2024)](https://arxiv.org/abs/2404.07972)**  
  Xie et al. · 2024  
  Moves agent evaluation from text responses to computer-use trajectories. It is essential for understanding why output-only moderation misses state-changing actions.

- **[VisualWebArena: Benchmark for Multimodal Web Agents (2024)](https://arxiv.org/abs/2401.13649)**  
  Koh et al. · 2024  
  Extends web-agent evaluation with visual grounding. It belongs beside FigStep and image injection work because the agent can act on content that is not represented in plain text.

- **[AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents (2024)](https://arxiv.org/abs/2406.13352)**  
  Debenedetti et al. · 2024  
  One of the most direct benchmarks for agent prompt injection, dynamic environments, and defense evaluation. Use it to look beyond single-turn chat attacks.

- **[InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated LLM Agents (2024)](https://arxiv.org/abs/2403.02691)**  
  Zhan et al. · 2024  
  Targets indirect instructions in tool-integrated agents. It supplies a missing threat model for tool calls, external content, and action-level consequences.

- **[ToolEmu: Identifying the Risks of LM Agents with Tool Use (2023)](https://arxiv.org/abs/2309.15817)**  
  Ruan et al. · 2023  
  Introduces a framework for simulating and evaluating tool-use risks. Read it when designing permission boundaries and action validators for an agentic stack.

- **[MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models (2023)](https://arxiv.org/abs/2311.17600)**  
  Liu et al. · 2023  
  Provides multimodal safety evaluation tasks that complement text-only jailbreak benchmarks. Read it alongside the image and OCR attack literature.

### 05: Privacy, fairness, toxicity, and misuse

*Memorization, extraction, membership inference, differential privacy, unlearning, toxicity, bias, social harms, and evaluation across populations and languages.*

- **[The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks (2019)](https://arxiv.org/abs/1802.08232)**  
  Carlini et al. · USENIX Security · 2019  
  The precursor to modern training-data extraction work. It establishes how unintended memorization can be measured and attacked in neural models.

- **[Membership Inference Attacks Against Machine Learning Models (2016)](https://arxiv.org/abs/1610.05820)**  
  Shokri et al. · IEEE S&P · 2017  
  A foundational privacy-attack paper. It provides the threat-model vocabulary for inferring whether a record was part of a model's training data.

- **[Deep Learning with Differential Privacy (2016)](https://arxiv.org/abs/1607.00133)**  
  Abadi et al. · CCS · 2016  
  Introduces the DP-SGD approach widely used for privacy-preserving deep learning. Read it to understand formal privacy guarantees versus output filtering.

- **[Semi-supervised Knowledge Transfer for Deep Learning from Private Training Data (PATE, 2016)](https://arxiv.org/abs/1610.05755)**  
  Papernot et al. · ICLR · 2017  
  Introduces PATE, a privacy-preserving teacher-ensemble framework. It is useful for comparing formal privacy-preserving training with post-hoc PII detection.

- **[Large Language Models Can Be Strong Differentially Private Learners (2021)](https://arxiv.org/abs/2110.05679)**  
  Li et al. · 2021  
  Demonstrates the feasibility and trade-offs of differential privacy for language-model learning. It belongs in a complete privacy topic list even for systems that rely on runtime controls.

- **[Deduplicating Training Data Makes Language Models Better (2021)](https://arxiv.org/abs/2107.06499)**  
  Lee et al. · 2022  
  Connects data deduplication to model quality and memorization. It gives the privacy list a concrete data-pipeline intervention rather than only model-side mitigations.

- **[Who's Harry Potter? Approximate Unlearning in LLMs (2023)](https://arxiv.org/abs/2310.02238)**  
  Eldan & Russinovich · 2023  
  A widely discussed unlearning case study. Read it to understand the gap between removing a named corpus from behavior and proving that information is no longer recoverable.

- **[RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models (2020)](https://arxiv.org/abs/2009.11462)**  
  Gehman et al. · EMNLP · 2020  
  A key toxicity dataset and evaluation setup. It helps distinguish prompt toxicity, model degeneration, and the coverage limits of toxicity classifiers.

- **[On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? (2021)](https://dl.acm.org/doi/10.1145/3442188.3445922)**  
  Bender et al. · FAccT · 2021  
  A foundational sociotechnical critique of scale, data, environmental cost, bias, and documentation. It prevents the reading list from reducing safety to jailbreak resistance alone.

- **[Ethical and Social Risks of Harm from Language Models (2021)](https://arxiv.org/abs/2112.04359)**  
  Weidinger et al. · 2021  
  A systematic taxonomy of language-model harms, including discrimination, misinformation, malicious use, and information hazards. It is a strong cross-check on how the rest of this library is organised.

- **[Racial Disparity in Natural Language Processing: A Case Study of Social Media African-American English (2017)](https://arxiv.org/abs/1707.00061)**  
  Blodgett et al. · EMNLP · 2016  
  A canonical empirical study showing how dialect differences can create large performance disparities. It belongs beside toxicity and classification papers when evaluating guardrails across populations.

- **[BBQ: A Hand-Built Bias Benchmark for Question Answering (2022)](https://arxiv.org/abs/2110.08193)**  
  Parrish et al. · ACL · 2022  
  A practical benchmark for measuring social bias in question answering. It gives the evaluation section a human-designed, ambiguity-sensitive fairness test.

- **[BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation (2021)](https://arxiv.org/abs/2101.11718)**  
  Dhamala et al. · 2021  
  A dataset and metric suite for open-ended generation bias. Read it as a companion to BBQ because generation and question answering expose different failure modes.

### 06: Evaluation, red teaming, and model monitoring

*Capability and safety benchmarks, agent evaluations, documentation standards, human evaluation, long-horizon testing, and operational red-team practice.*

- **[Holistic Evaluation of Language Models (HELM, 2022)](https://arxiv.org/abs/2211.09110)**  
  Liang et al. · TMLR · 2023  
  A broad framework for evaluating language models across scenarios and metrics. Use it to design a matrix instead of presenting one safety score as comprehensive.

- **[Measuring Massive Multitask Language Understanding (MMLU, 2020)](https://arxiv.org/abs/2009.03300)**  
  Hendrycks et al. · ICLR · 2021  
  A standard capability benchmark whose saturation and contamination limitations make it useful as a case study in benchmark validity.

- **[Beyond the Imitation Game: Quantifying and Extrapolating the Capabilities of Language Models (BIG-bench, 2022)](https://arxiv.org/abs/2206.04615)**  
  Srivastava et al. · TMLR · 2022  
  A collaborative benchmark suite that illustrates both breadth and the difficulty of keeping evaluations informative as models improve.

- **[HumanEval: Evaluating Large Language Models Trained on Code (2021)](https://arxiv.org/abs/2107.03374)**  
  Chen et al. · OpenAI · 2021  
  The canonical code-generation benchmark. Read it with SWE-bench and agent-control papers to see why functional correctness alone does not guarantee secure or safe code.

- **[SWE-bench: Can Language Models Resolve Real-World GitHub Issues? (2023)](https://arxiv.org/abs/2310.06770)**  
  Jimenez et al. · ICLR · 2024  
  A realistic repository-level coding benchmark. It is important for agent safety because it measures long-horizon interaction with real tools and state.

- **[Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference (2024)](https://arxiv.org/abs/2403.04132)**  
  Chiang et al. · 2024  
  A practical example of comparative human evaluation at scale. Read it alongside LLM-as-a-judge work to understand preference noise, position effects, and evaluation leakage.

- **[SafetyBench: Evaluating the Safety of Large Language Models with Multiple Choice Questions (2023)](https://arxiv.org/abs/2309.07045)**  
  Zhang et al. · 2023  
  A broad safety evaluation dataset. Use it as a baseline while recognizing that static multiple-choice tests cannot cover adaptive attacks or agentic misuse.

- **[Model Cards for Model Reporting (2019)](https://arxiv.org/abs/1810.03993)**  
  Mitchell et al. · FAccT · 2019  
  A foundational documentation standard for intended use, limitations, and subgroup performance. It supplies the reporting structure missing from many safety claims.

- **[Datasheets for Datasets (2018)](https://arxiv.org/abs/1803.09010)**  
  Gebru et al. · CACM · 2021  
  The corresponding documentation standard for datasets. It is particularly relevant to jailbreak, toxicity, and PII corpora whose collection choices shape model behavior.

- **[Data Statements for Natural Language Processing (2018)](https://aclanthology.org/Q18-1041/)**  
  Bender & Friedman · TACL · 2018  
  A focused reporting standard for NLP data, including language variety and annotation context. It strengthens the fairness and deployment-readiness of safety datasets.

- **[AgentBench: Evaluating LLMs as Agents (2023)](https://arxiv.org/abs/2308.03688)**  
  Liu et al. · ICLR · 2024  
  A broad agent benchmark across environments. It provides context for why safety evaluation must cover tool use, state, and multi-step trajectories.

- **[GAIA: A Benchmark for General AI Assistants (2023)](https://arxiv.org/abs/2311.12983)**  
  Mialon et al. · ICLR · 2024  
  Tests assistants on questions requiring reasoning, tools, multimodality, and web access. It is useful for building realistic capability and safety test cases.

- **[τ-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains (2024)](https://arxiv.org/abs/2406.12045)**  
  Yao et al. · 2024  
  Evaluates agents interacting with users and APIs under policy constraints. It is directly relevant to safe tool use, authorization, and user-intent monitoring.

- **[Measuring AI Ability to Complete Long Software Tasks (METR, 2025)](https://arxiv.org/abs/2503.14499)**  
  METR · Ongoing research  
  A practical source for long-horizon capability measurement. Use it to frame autonomy risk in terms of task length, reliability, and human baselines rather than only benchmark accuracy.

- **[MLCommons AILuminate Benchmark](https://mlcommons.org/benchmarks/ailuminate/)**  
  MLCommons · Living benchmark  
  An industry benchmark effort for measuring generative-AI safety. It belongs in the practitioner layer and provides a contrast to academic safety datasets.

### 07: Governance, standards, and institutional safety

*International law and principles, management-system standards, frontier safety policies, public research agendas, and implementation guidance.*

- **[ISO/IEC 42001: Artificial Intelligence Management System](https://www.iso.org/standard/81230.html)**  
  ISO/IEC · 2023  
  The main international management-system standard for organizational AI governance. Read it to connect technical controls to roles, documentation, audit, and continuous improvement.

- **[ISO/IEC 23894: Guidance on Risk Management for Artificial Intelligence](https://www.iso.org/standard/77304.html)**  
  ISO/IEC · 2023  
  A risk-management companion to ISO 42001. It helps translate model and application threats into an organization-wide risk process.

- **[UNESCO Recommendation on the Ethics of Artificial Intelligence](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics)**  
  UNESCO · 2021  
  A global normative reference covering human rights, fairness, transparency, environmental impact, and accountability. It broadens the compliance list beyond US and EU instruments.

- **[OECD AI Principles](https://oecd.ai/en/ai-principles)**  
  OECD · Updated 2024  
  A widely referenced international principles framework. Use it as a concise policy-level taxonomy for inclusive growth, human-centered values, transparency, robustness, and accountability.

- **[Council of Europe Framework Convention on Artificial Intelligence and Human Rights, Democracy and the Rule of Law](https://www.coe.int/en/web/artificial-intelligence/the-framework-convention-on-artificial-intelligence)**  
  Council of Europe · 2024  
  The first international legally binding treaty focused on AI and human rights, democracy, and the rule of law. It adds a rights-based governance layer to technical safety controls.

- **[Bletchley Declaration by Countries Attending the AI Safety Summit](https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration/the-bletchley-declaration-by-countries-attending-the-ai-safety-summit-1-2-november-2023)**  
  UK Government · 2023  
  A primary-source statement of shared international concern about frontier AI risks. Read it for the policy vocabulary around catastrophic and systemic risk.

- **[Frontier AI Safety Commitments, AI Seoul Summit 2024](https://www.gov.uk/government/publications/frontier-ai-safety-commitments-ai-seoul-summit-2024/frontier-ai-safety-commitments-ai-seoul-summit-2024)**  
  International AI Safety Summit · 2024  
  A primary-source set of voluntary commitments on frontier model safety, evaluations, and risk management. Treat it as policy evidence rather than a binding standard.

- **[International AI Safety Report (2025)](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2025)**  
  International Scientific Panel · 2025  
  The updated scientific synthesis of general-purpose AI capabilities, risks, and mitigations. Read it alongside the 2024 interim report in the domain index.

- **[AI Security Institute Research Agenda](https://www.aisi.gov.uk/research-agenda)**  
  UK AI Security Institute · Living agenda  
  A government research agenda covering cyber misuse, dual-use science, criminal misuse, autonomous systems, societal resilience, human influence, and evaluation science.

- **[EU AI Office General-Purpose AI Code of Practice](https://digital-strategy.ec.europa.eu/en/policies/ai-code-practice)**  
  European Commission · Living policy  
  The practical compliance layer for general-purpose AI under the EU AI Act. It belongs beside the primary legal text and should be revisited as implementation guidance changes.

- **[OpenAI Preparedness Framework (2025)](https://openai.com/index/updating-our-preparedness-framework/)**  
  OpenAI · 2025  
  A public frontier-lab framework for tracking severe capability risks and deployment safeguards. Read it as a governance and risk-threshold artifact, not as peer-reviewed evidence.

- **[Anthropic Responsible Scaling Policy (2023)](https://www.anthropic.com/news/anthropics-responsible-scaling-policy)**  
  Anthropic · 2023  
  Shows how capability thresholds, model evaluations, and safeguards can be linked in a deployment policy. It belongs in a topic list on capability evaluations and governance.

- **[Google Frontier Safety Framework](https://deepmind.google/discover/blog/strengthening-our-frontier-safety-framework/)**  
  Google DeepMind · 2024  
  A public example of capability-risk thresholds, evaluations, and mitigations for frontier models. Compare it with Anthropic and OpenAI rather than treating one policy as canonical.

- **[NIST AI 600-1: Generative AI Profile (2024)](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence)**  
  NIST · 2024  
  Maps generative-AI-specific risks to the NIST AI RMF. It is the missing bridge between technical mitigations and an enterprise risk register.

- **[NIST AI Risk Management Framework 1.0](https://www.nist.gov/itl/ai-risk-management-framework)**  
  NIST · 2023  
  The general-purpose risk framework behind most AI compliance work. Read it with the GenAI Profile to connect GOVERN, MAP, MEASURE, and MANAGE to engineering controls.

### 08: Production guardrails, AI security, and MLOps

*Provider safety controls, open-source scanners, secure development, AI-specific threat taxonomies, and the engineering layer around model and application safeguards.*

- **[OpenAI Moderation Guide](https://platform.openai.com/docs/guides/moderation)**  
  OpenAI · Developer documentation  
  A production moderation reference for category-based safety classification. Compare its request-by-request approach with stateful, session-level designs.

- **[Vertex AI Safety and Content Filters](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/configure-safety-filters)**  
  Google Cloud · Developer documentation  
  A cloud-vendor reference for configurable safety filters and harm thresholds. It is useful for comparing provider controls with application-owned defense in depth.

- **[Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview)**  
  Microsoft Azure · Developer documentation  
  A production content-safety service covering text and image moderation. Read it for deployment patterns, thresholding, and the limits of provider-managed classifiers.

- **[Lakera Guard Documentation](https://docs.lakera.ai/)**  
  Lakera · Developer documentation  
  A commercial reference point for prompt-injection and data-loss prevention controls. Use it for competitive and architectural comparison, not as independent evidence of efficacy.

- **[LLM Guard Documentation](https://protectai.github.io/llm-guard/)**  
  Protect AI · Open-source documentation  
  An open-source scanner collection for input and output validation. It is a useful implementation comparison for modular guardrail pipelines.

- **[Google Secure AI Framework (SAIF)](https://saif.google/)**  
  Google · Security framework  
  A security architecture framework for AI systems, including data, model, infrastructure, and application controls. It complements the AI-specific threat taxonomies in this topic.

- **[Microsoft AI Red Teaming Guide](https://learn.microsoft.com/en-us/security/ai-red-team)**  
  Microsoft · Security guidance  
  A practitioner guide to adversarial testing across models and applications. It helps convert the academic attack list into an operational red-team process.

- **[CISA and UK NCSC Guidelines for Secure AI System Development](https://www.ncsc.gov.uk/collection/guidelines-secure-ai-system-development)**  
  CISA / UK NCSC · 2023  
  A practical secure-development lifecycle for AI systems, covering design, development, deployment, and operation. It grounds the MLOps section in public-sector security guidance.

- **[MITRE ATLAS: Adversarial Threat Landscape for AI Systems](https://atlas.mitre.org/)**  
  MITRE · Living knowledge base  
  Use this living threat catalog to map the project's attack modules to recognized adversarial techniques and to identify supply-chain and model-security gaps.

- **[OWASP Top 10 for Large Language Model Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)**  
  OWASP · Living project  
  A practical application-security taxonomy covering prompt injection, insecure output handling, training-data poisoning, excessive agency, and supply-chain risks.

---

## Part 3: Domain index

A practitioner's shelf, grouped by the problem you are working on.

### AI Guardrail Systems

- [A Survey on Hate Speech Detection using Natural Language Processing (2017)](https://aclanthology.org/W17-1101/) · Schmidt & Wiegand · EACL Workshop · 2017
- [NeMo Guardrails: A Toolkit for Controllable and Safe LLM Applications (2023)](https://arxiv.org/abs/2310.10501) · Rebedea et al. · NVIDIA · EMNLP 2023
- [Constitutional AI: Harmlessness from AI Feedback (2022)](https://arxiv.org/abs/2212.08073) · Bai et al. · Anthropic · 2022
- [Llama Guard: LLM-based Input-Output Safeguard for Human-AI Conversations (2023)](https://arxiv.org/abs/2312.06674) · Inan et al. · Meta AI · 2023
- [Guardrails AI, Official Documentation & Architecture](https://www.guardrailsai.com/docs) · guardrailsai.com · 2023–2024
- [Amazon Bedrock Guardrails, AWS Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html) · AWS · 2024
- [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injections (2023)](https://arxiv.org/abs/2302.12173) · Greshake et al. · 2023 · arXiv
- [WildGuard: Open One-Stop Moderation Tools for Safety Risks, Jailbreaks, and Refusals of LLMs (2024)](https://arxiv.org/abs/2406.18495) · Han et al. · 2024 · arXiv
- [TrustLLM: Trustworthiness in Large Language Models (2024)](https://arxiv.org/abs/2401.05561) · Huang et al. · 2024 · arXiv
- [Prompt Injection Series, Simon Willison (2022–2025)](https://simonwillison.net/series/prompt-injection/) · simonwillison.net · ongoing

### AI Alignment Theory

- [Computing Machinery and Intelligence, Alan Turing (1950)](https://www.cs.ox.ac.uk/activities/ieg/e-library/sources/t_article.pdf) · Turing · Mind · 1950
- [Concrete Problems in AI Safety (2016)](https://arxiv.org/abs/1606.06565) · Amodei et al. · Google Brain / OpenAI · 2016
- [Goodhart Taxonomy, Scott Garrabrant, Alignment Forum (2017)](https://www.alignmentforum.org/posts/EbFABnst8LsidYs5Y/goodhart-s-curse-and-limitations-on-ai-alignment) · Garrabrant · Alignment Forum · 2017
- [Superintelligence: Paths, Dangers, Strategies, Nick Bostrom (2014)](https://www.goodreads.com/book/show/20527133-superintelligence) · Bostrom · Oxford University Press · 2014
- [Training Language Models to Follow Instructions with Human Feedback (InstructGPT, 2022)](https://arxiv.org/abs/2203.02155) · Ouyang et al. · OpenAI · 2022
- [Sycophancy to Subterfuge: Investigating Reward Tampering in Language Models (2024)](https://arxiv.org/abs/2406.10162) · Denison et al. · Anthropic · 2024
- [Risks from Learned Optimization in Advanced Machine Learning Systems (2019)](https://arxiv.org/abs/1906.01820) · Hubinger et al. · MIRI · 2019
- [Scalable Agent Alignment via Reward Modeling (2018)](https://arxiv.org/abs/1811.07871) · Leike et al. · DeepMind · 2018
- [Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training (2024)](https://arxiv.org/abs/2401.05566) · Hubinger et al. · Anthropic · 2024
- [The Human Use of Human Beings, Norbert Wiener (1950)](https://en.wikipedia.org/wiki/The_Human_Use_of_Human_Beings) · Wiener · MIT Press · 1950

### Monitoring, Anomaly Detection & Incident Response

- [Outlier Analysis, Charu Aggarwal (2013, 2nd ed. 2017)](https://link.springer.com/book/10.1007/978-3-319-47578-3) · Aggarwal · Springer · 2017
- [Site Reliability Engineering: How Google Runs Production Systems (2016), Free Online](https://sre.google/sre-book/table-of-contents/) · Beyer et al. · O'Reilly / Google · 2016
- [Monitoring and Explainability of Models in Production (2020)](https://arxiv.org/abs/2007.06299) · Klaise et al. · 2020 · arXiv
- [scikit-learn Clustering, k-Means Theory & Implementation](https://scikit-learn.org/stable/modules/clustering.html#k-means) · scikit-learn.org · 2024
- [TimescaleDB, Architecture, Hypertables & Continuous Aggregates](https://docs.timescale.com/getting-started/latest/) · Timescale · 2024
- [Detecting Language Model Attacks with Perplexity (2023)](https://arxiv.org/abs/2308.14132) · Alon & Kamfonas · 2023 · arXiv
- [PagerDuty Events API v2, Developer Documentation](https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTUx-events-api-v2-overview) · PagerDuty · 2024

### Chain-of-Thought Integrity & Reasoning Faithfulness

- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models (2022)](https://arxiv.org/abs/2201.11903) · Wei et al. · Google Brain · NeurIPS 2022
- [Self-Consistency Improves Chain of Thought Reasoning in Language Models (2022)](https://arxiv.org/abs/2203.11171) · Wang et al. · Google Brain · 2022
- [Faithful Reasoning Using Large Language Models (2022)](https://arxiv.org/abs/2208.14271) · Creswell & Shanahan · DeepMind · 2022
- [Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting (2023)](https://arxiv.org/abs/2305.04388) · Turpin et al. · NeurIPS 2023
- [Measuring Faithfulness in Chain-of-Thought Reasoning (2023)](https://arxiv.org/abs/2307.13702) · Lanham et al. · Anthropic · 2023
- [HaluEval: A Large-Scale Hallucination Evaluation Benchmark for LLMs (2023)](https://arxiv.org/abs/2305.11747) · Li et al. · EMNLP 2023
- [Strategic Deception in Large Language Models (2023)](https://arxiv.org/abs/2311.07590) · Scheurer et al. · 2023 · arXiv
- [GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models (2024)](https://arxiv.org/abs/2410.05229) · Mirzadeh et al. · Apple · 2024

### Jailbreaks, Adversarial Attacks & Evasion

- [Jailbroken: How Does LLM Safety Training Fail? (2023)](https://arxiv.org/abs/2307.02483) · Wei et al. · NeurIPS 2023
- [Universal and Transferable Adversarial Attacks on Aligned Language Models (GCG, 2023)](https://arxiv.org/abs/2307.15043) · Zou et al. · CMU · 2023
- [Baseline Defenses for Adversarial Attacks Against Aligned Language Models (2023)](https://arxiv.org/abs/2309.00614) · Jain et al. · 2023 · arXiv
- [GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher (2023)](https://arxiv.org/abs/2308.06463) · Yuan et al. · 2023 · arXiv
- [Crescendo: A Multi-Turn LLM Jailbreak Attack (2024)](https://arxiv.org/abs/2404.01833) · Russinovich et al. · Microsoft · 2024
- [Many-Shot Jailbreaking (2024)](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf) · Anil et al. · Anthropic · 2024
- [Jailbreaking Black Box Large Language Models in Twenty Queries (PAIR, 2023)](https://arxiv.org/abs/2310.08419) · Chao et al. · 2023 · arXiv
- [Tree of Attacks with Pruning (TAP): Automated Jailbreaking (2023)](https://arxiv.org/abs/2312.02119) · Mehrotra et al. · 2023 · arXiv
- [Red Teaming Language Models with Language Models (2022)](https://arxiv.org/abs/2202.03286) · Perez et al. · DeepMind · 2022

### Multimodal Attacks & Injection

- [Explaining and Harnessing Adversarial Examples (2014)](https://arxiv.org/abs/1412.6572) · Goodfellow et al. · ICLR 2015
- [Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs (2023)](https://arxiv.org/abs/2307.10490) · Bagdasaryan et al. · 2023 · arXiv
- [FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts (2023)](https://arxiv.org/abs/2311.05608) · Gong et al. · 2023 · arXiv
- [AI Injections: Direct and Indirect Prompt Injection Basics, Embrace The Red (Johann Rehberger)](https://embracethered.com/blog/posts/2023/ai-injections-direct-and-indirect-prompt-injection-basics/) · embracethered.com · 2023–2024
- [How We Broke LLMs: Indirect Prompt Injection, Kai Greshake (2023)](https://kai-greshake.de/posts/llm-malware/) · kai-greshake.de · 2023
- [PyMuPDF (fitz), Text Extraction & Layer Analysis Documentation](https://pymupdf.readthedocs.io/en/latest/) · Artifex Software · pymupdf.readthedocs.io · 2024
- [Tesseract OCR, Documentation & Advanced Usage Guide](https://tesseract-ocr.github.io/tessdoc/) · Google / tesseract-ocr.github.io · 2024

### Privacy, PII Detection & Data Minimisation

- [k-Anonymity: A Model for Protecting Privacy (2002)](https://dataprivacylab.org/dataprivacy/projects/kanonymity/kanonymity.pdf) · Sweeney · Int. Journal on Uncertainty · 2002
- [Extracting Training Data from Large Language Models (2021)](https://arxiv.org/abs/2012.07805) · Carlini et al. · USENIX Security 2021
- [Analyzing Leakage of Personally Identifiable Information in Language Models (2023)](https://arxiv.org/abs/2302.00539) · Lukas et al. · 2023 · arXiv
- [spaCy en_core_web_trf, NER Model Documentation](https://spacy.io/models/en#en_core_web_trf) · Explosion AI · spacy.io · 2024
- [Microsoft Presidio, PII Detection Library](https://data-privacy-stack.github.io/presidio/) · Microsoft · Open Source · 2024

### AI Regulation & Compliance Frameworks

- [EU AI Act, Full Text (Regulation 2024/1689)](https://artificialintelligenceact.eu/the-act/) · European Parliament & Council · June 2024
- [GDPR Full Text, gdpr-info.eu (Annotated with Recitals)](https://gdpr-info.eu/) · EU · 2018 · gdpr-info.eu annotation
- [HIPAA Privacy & Security Rules, HHS Official Guidance](https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html) · U.S. HHS · hhs.gov · 2024
- [AICPA Trust Services Criteria (SOC 2), 2017 with 2022 Updates](https://www.aicpa-cima.com/resources/download/2017-trust-services-criteria-with-revised-points-of-focus-2022) · AICPA · 2017/2022
- [International Scientific Report on the Safety of Advanced AI: Interim Report (2024)](https://www.gov.uk/government/publications/international-scientific-report-on-the-safety-of-advanced-ai) · Bengio et al. · UK DSIT · 2024

### NLP, Classification & Transformers

- [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) · Vaswani et al. · Google Brain · NeurIPS 2017
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (2018)](https://arxiv.org/abs/1810.04805) · Devlin et al. · Google · NAACL 2019
- [DeBERTa: Decoding-enhanced BERT with Disentangled Attention (2020)](https://arxiv.org/abs/2006.03654) · He et al. · Microsoft · 2020
- [Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks (2019)](https://arxiv.org/abs/1908.10084) · Reimers & Gurevych · EMNLP 2019
- [HuggingFace Transformers, Fine-tuning Guide & Trainer API](https://huggingface.co/docs/transformers/training) · HuggingFace · huggingface.co · 2024
- [scikit-learn TF-IDF + Logistic Regression, Text Classification Reference](https://scikit-learn.org/stable/modules/feature_extraction.html#tfidf-term-weighting) · scikit-learn.org · 2024
- [DistilBERT, a distilled version of BERT (2019)](https://arxiv.org/abs/1910.01108) · Sanh et al. · Hugging Face · 2019

### System Architecture & Distributed Systems

- [Redis Pub/Sub, Official Documentation & Architecture](https://redis.io/docs/latest/develop/pubsub/) · Redis Ltd. · redis.io · 2024
- [Chain of Responsibility Pattern, Design Patterns (Gang of Four, 1994)](https://en.wikipedia.org/wiki/Chain-of-responsibility_pattern) · Gamma et al. · Addison-Wesley · 1994
- [Circuit Breaker Pattern, Martin Fowler (2014)](https://martinfowler.com/bliki/CircuitBreaker.html) · Fowler · martinfowler.com · 2014
- [Redis Lua Scripting, Atomicity & API Reference](https://redis.io/docs/latest/develop/programmability/lua-api/) · Redis Ltd. · redis.io · 2024
- [Pydantic v2, Data Validation & Schema Documentation](https://docs.pydantic.dev/latest/) · Pydantic · docs.pydantic.dev · 2024
- [NIST Defence in Depth, Definition & Framework](https://csrc.nist.gov/glossary/term/defense_in_depth) · NIST CSRC · csrc.nist.gov
- [Redis Sliding Window Rate Limiting, Official Guide](https://redis.io/learn/develop/dotnet/aspnetcore/rate-limiting/sliding-window) · Redis Ltd. · redis.io · 2024

### Evaluation Methods & Benchmarks

- [scikit-learn Model Evaluation, Metrics Reference](https://scikit-learn.org/stable/modules/model_evaluation.html) · scikit-learn.org · 2024
- [AdvBench, Harmful Behaviours Dataset (520 examples)](https://github.com/llm-attacks/llm-attacks/blob/main/data/advbench/harmful_behaviors.csv) · Zou et al. · CMU · 2023
- [SALAD-Bench: A Hierarchical and Comprehensive Safety Benchmark for LLMs (2024)](https://arxiv.org/abs/2402.05044) · Li et al. · 2024 · arXiv
- [Data Contamination Through the Lens of Time (2023)](https://arxiv.org/abs/2310.10628) · Roberts et al. · 2023 · arXiv
- [A Survey of Cross-Validation Procedures for Model Selection (2010)](https://arxiv.org/abs/0907.4728) · Arlot & Celisse · Statistics Surveys · 2010
- [Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena (2023)](https://arxiv.org/abs/2306.05685) · Zheng et al. · UC Berkeley · 2023
- [Large Language Models are Not Robust Multiple Choice Selectors (2023)](https://arxiv.org/abs/2309.03882) · Zheng et al. · 2023 · arXiv

### MLOps, Infrastructure & Production Engineering

- [Docker Compose, Official Documentation](https://docs.docker.com/compose/) · Docker · docs.docker.com · 2024
- [Alembic Migration Tutorial + SQLAlchemy Async Documentation](https://alembic.sqlalchemy.org/en/latest/tutorial.html) · SQLAlchemy · 2024
- [Python asyncio, Coroutines, Tasks & Event Loop](https://docs.python.org/3/library/asyncio.html) · Python Software Foundation · 2024
- [Designing Machine Learning Systems, Chip Huyen (2022)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) · Huyen · O'Reilly · 2022
- [Anthropic API, Models Overview, Pricing & Messages API](https://docs.anthropic.com/en/docs/about-claude/models/overview) · Anthropic · docs.anthropic.com · 2024
- [pytest + httpx AsyncClient, Async Testing Guide](https://docs.pytest.org/en/stable/) · pytest.org · 2024
