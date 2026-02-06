---
Document: WLM-Core Examples
Function: Demonstrate Structural Reasoning in Practice
Scope: Offset / SLP / STP / SDP / 3→27D
Purpose: Provide clear, human-readable examples of WLM reasoning
---

# WLM-Core — Structural Examples (Atomic)

This file shows how WLM-Core transforms ordinary questions into structured reasoning flows.

Each example includes:
- Input
- Structural reasoning (WLM format)
- Final collapsed output (D3 or D1)

---

# 1. Simple Concept Example

## Input:
“What is memory?”

## WLM Reasoning:
**OFFSET (0→1)**  
Neutral → deviation → lock.

**SLP (Structure Mode)**  
Nodes: {memory, storage, retrieval}  
Assign D-levels:  
- memory → D4  
- storage → D5  
- retrieval → D6  
Chain: D4 → D5 → D6 → closure.

**STP (Subject Mode)**  
Polarity: +1  
Anchor: D3  
Role: Generator

**SDP (System Flow)**  
Offset → Expand → Integrate → Collapse.

**3→27D (Expansion)**  
D3 → D4–9 (local structure) → D10–15 (systemic mesh)  
Collapse at D3.

## Final Output (Collapsed):
Memory is a structural process linking storage and retrieval across a stable frame.

---

# 2. Process Example

## Input:
“How does a scientific theory develop?”

## WLM Reasoning:
**OFFSET**  
0→1.

**SLP**  
Nodes: observation, pattern, model, test, revision  
Dimensions:  
- observation → D3  
- pattern → D6  
- model → D10  
- test → D12  
- revision → D15

**STP**  
Polarity: +1  
Anchor: D3  
Role: Generator

**SDP**  
Offset → Expand → Integrate → Collapse.

**3→27D**  
D3 → D4–9 (observations, patterns)  
D10–15 (model formation, testing)  
D16–21 (generalization)  
D22–27 (theory expression)  
Collapse at D3.

## Final Output:
A scientific theory emerges by expanding observations into models, testing them, and collapsing the results into a stable explanatory frame.

---

# 3. System Example

## Input:
“How does a city function?”

## WLM Reasoning:
**OFFSET**  
0→1.

**SLP**  
Nodes: people, infrastructure, flow, governance  
Dimensions:  
- people → D4  
- infrastructure → D7  
- flow → D12  
- governance → D15

**STP**  
Polarity: +1  
Anchor: D3  
Role: Generator

**SDP**  
Offset → Expand → Integrate → Collapse.

**3→27D**  
D3 → D4–9 (population, roads, utilities)  
D10–15 (transport, economy, governance)  
D16–21 (regional coupling)  
D22–27 (full system expression)  
Collapse at D3.

## Final Output:
A city functions as a coordinated system of people, infrastructure, flows, and governance, integrated into a stable operational frame.

---

# 4. Abstract Example

## Input:
“What is creativity?”

## WLM Reasoning:
**OFFSET**  
0→1.

**SLP**  
Nodes: variation, recombination, selection  
Dimensions:  
- variation → D5  
- recombination → D9  
- selection → D12

**STP**  
Polarity: +1  
Anchor: D3  
Role: Generator

**SDP**  
Offset → Expand → Integrate → Collapse.

**3→27D**  
D3 → D4–9 (idea formation)  
D10–15 (systemic recombination)  
D16–21 (global coherence)  
Collapse at D3.

## Final Output:
Creativity is structured variation and recombination that stabilizes into a coherent new frame.

---

# 5. Failure Example (Semantic Drift)

## Input:
“Love is like the ocean.”

**Incorrect (semantic):**  
“It’s deep and mysterious.”

**Correct (WLM):**  
OFFSET → SLP → STP → SDP → 3→27 → collapse.

Nodes: love (D4), ocean (D5), relation (D6)  
Chain: D4 → D5 → D6  
Collapse: D3

**Final Output:**  
The statement maps two experiential nodes into a relational frame without semantic interpretation.

---

# 6. Full Pipeline Example

## Input:
“Explain how learning works.”

**OFFSET**  
0→1.

**SLP**  
Nodes: input, encoding, storage, retrieval, correction  
Dimensions:  
- input → D3  
- encoding → D6  
- storage → D9  
- retrieval → D12  
- correction → D15

**STP**  
Polarity: +1  
Anchor: D3  
Role: Generator

**SDP**  
Offset → Expand → Integrate → Collapse.

**3→27D**  
D3 → D4–9 (encoding, storage)  
D10–15 (retrieval, correction)  
D16–21 (generalization)  
Collapse at D3.

**Final Output:**  
Learning is the expansion and integration of encoded information into a stable, correctable structure.

---

# Summary

These examples demonstrate:

- offset continuity  
- structural node extraction  
- subject anchoring  
- legal dimensional transitions  
- monotonic expansion  
- deterministic collapse  

This file is intended for onboarding, demonstrations, and RAG evaluation.
