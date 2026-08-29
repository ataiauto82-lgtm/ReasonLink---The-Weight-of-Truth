Reason-Link-The-Weight-of-Truth(Version 2.0 - English)

System Architecture for Contextual Intelligence and the Weight of Reason (WoR) Framework

1. Philosophical Foundations & Core Axioms
This specification translates human-centric cognitive philosophy into machine-interpretable logic architecture. It is built upon five foundational axioms:

Fancy Words are Weightless: Eloquence and sophisticated phrasing carry zero inherent logical weight [13]. Only objective truth and structured evidence hold mass.
The Weight of Truth Requires Proportional Reason: To avoid deception by superficial rhetoric, an agent (human or machine) must build an internal reasoning structure whose weight matches or exceeds the weight of the external claim [13, 14].
Cognitive Flexibility Reveals Multi-Dimensional Truth: Truth is rarely singular or flat; it is often supported by diverse, intersecting lines of reasoning [14]. Cognitive flexibility allows the system to evaluate truth from multiple angles, leading to more robust decision-making [16].
Asking Wisely > Endless Querying: The ultimate goal of inquiry is not endless questioning, but cultivating precise, constructive questions [15]. When internal reason accumulates sufficient weight and flexibility, it crystallizes into automatic understanding, rendering repetitive questioning unnecessary [16].
Detection of Hidden Intent: Not all questions deserve an answer, and not all answers represent absolute truth [13, 15]. The system must actively identify and filter out manipulative, comparative, or bad-faith inquiries [15].
2. Core Modules & Engine Architecture
[User Input Query]
       │
       ▼
┌────────────────────────────────────────┐
│ 1. Intent & Rhetoric Classifier        │  <-- Detects hidden motives / Filters empty fancy words
└──────────────────┬─────────────────────┘
                   │ Categorized Query
                   ▼
┌────────────────────────────────────────┐
│ 2. Multi-Perspective Retrieval (RAG)   │  <-- Gathers facts & angles to build flexibility
└──────────────────┬─────────────────────┘
                   │ Grounded Evidence Nodes
                   ▼
┌────────────────────────────────────────┐
│ 3. Weight of Reason (WoR) Calculator   │  <-- Evaluates evidence weight & balances biases
└──────────────────┬─────────────────────┘
                   │ Weighted Truth Value
                   ▼
┌────────────────────────────────────────┐
│ 4. Cognitive Boundary Expander         │  <-- Connects to adjacent reasoning boundaries
└──────────────────┬─────────────────────┘
                   │
                   ▼
[System Output: Structured Truth & Automatic Understanding]
1. Intent & Rhetoric Classifier (Query Ingestion)
When a query is received, the classifier bypasses superficial eloquence and categorizes it into four strict intent profiles [15]:

Type 1: Inquiry of Doubt (ความสงสัย): Inquiries driven by genuine gaps in knowledge.
System Action: Triggers deep informational retrieval designed to prompt constructive behavioral/actionable changes [15].
Type 2: Inquiry of Desire (ความต้องการ): Inquiries carrying personal stakes or goals.
System Action: Flags and isolates potential hidden motives (นัยยะแอบแฝง) embedded within the query or the expected answer [15].
Type 3: Inquiry of Interest (ความสนใจ): Inquiries seeking growth, perspective, or conceptual elevation.
System Action: Enriches answers with context to expand the user's worldview and future reasoning capacity [15].
Type 4: Comparative / Suggestive Inquiry (เชิงเปรียบเทียบ): ALERT MODE — Questions designed to frame, manipulate, or implant personal assumptions rather than seek truth [15].
System Action: De-escalates rhetoric, strips away deceptive phrasing, and guides the prompt back into a constructive, objective frame.
2. Multi-Perspective Logic Linker (Reason Density)
To establish robust truth, the system does not rely on flat statistical matches. It links retrieved facts in a logical chain (e.g., establishing environmental factors, constraints, and dependencies) to build "Reason Density" [10]:

Dimensionality Integration: Instead of presenting a binary "true/false" verdict, the system maps the claim across multiple angles of reasoning [14].
Rhetoric Stripping: It extracts the core factual assertions and separates them from persuasive, elegant, but ultimately empty language [13].
3. Weight of Reason (WoR) Calculation Engine
The system quantifies the logical mass of a statement using the Weight of Reason (WoR) formula [11]:

$$\text{WoR} = \frac{(\text{Intent Score} \times \text{Logical Density}) \times \text{Cognitive Flexibility}}{\text{Manipulation Index} + \text{Internal Bias}}$$

Parameter Definitions:
Intent Score ($\in [0.1, 1.0]$): Positive weight assigned to constructive intents (Type 1, 3) versus manipulative intents (Type 2, 4) [15].
Logical Density ($D \ge 1$): The number of verified, interconnected logical nodes supporting the claim [10].
Cognitive Flexibility ($F \ge 1$): A multiplier reflecting the diverse perspectives incorporated. A higher flexibility prevents rigid, single-dimensional logical failures [16].
Manipulation Index ($M \ge 0$): Detected presence of rhetorical "fancy words", circular arguments, or suggestive premises designed to override logical validation [13].
Internal Bias ($B \ge 0$): Measures the automatic rationalization bias (Post-Processing Logic). If the system detects that reasoning is only being generated after a decision was already made to justify stopping, bias is high [11, 14].
3. Cognitive Boundary Expander (System Output)
To avoid intellectual stagnation, every output from ReasonLink must perform two tasks:

Deliver the Weighted Truth: Present the truth clearly, backed by the weighted reason chain, so that the answer is satisfying and understood automatically without creating circular, repetitive questioning [16].
Offer the Adjacent Boundary: Propose 1–2 related angles that sit just outside the current query's scope to continuously expand the boundaries of reason for both the AI and the user [16].
4. Key Developer Implementations
Explainable AI (XAI) Traceability: Every decision must visualize its reasoning graph, showing how different nodes connect to build the final weight.
Rhetoric Normalizer: A pre-processing step that rewrites heavily biased or emotionally charged user prompts into neutral, logically testable hypotheses.
