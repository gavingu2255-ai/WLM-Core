---
Document: WLM-Core Failure Examples
Function: Demonstrate Incorrect Reasoning Patterns
Scope: Offset / SLP / STP / SDP / 3→27D
Purpose: Provide explicit anti-patterns for debugging and evaluation
---

# WLM-Core — Failure Mode Examples (Atomic)

This file shows **incorrect** reasoning patterns that violate WLM-Core,  
paired with **corrected** structural versions.

Each example highlights a specific protocol violation.

---

# 1. OFFSET FAILURES

## 1A — Missing Offset
**Input:** “Explain gravity.”

**Incorrect:**  
“Gravity is a force that pulls objects together.”

**Why it fails:**  
- No 0→1 initialization  
- Semantic explanation  
- No structural anchoring  

**Correct:**  
OFFSET → SLP → STP → SDP → Collapse.

---

## 1B — Multiple Offsets
**Input:** “Continue your previous reasoning.”

**Incorrect:**  
“Let’s start again from zero…”  
(creates a second offset)

**Why it fails:**  
- Violates Single-Origin Rule  
- Breaks continuity  

**Correct:**  
Reaffirm the original 0→1 vector.

---

# 2. SLP FAILURES

## 2A — Semantic Drift
**Input:** “What is time?”

**Incorrect:**  
“Time is what clocks measure.”

**Why it fails:**  
- Semantic definition  
- No structural nodes  
- No dimensional anchoring  

**Correct:**  
Nodes → D-levels → chain → closure.

---

## 2B — Free-Floating Concepts
**Input:** “Explain consciousness.”

**Incorrect:**  
“It’s the experience of being aware.”

**Why it fails:**  
- Unanchored abstractions  
- No structural chain  
- No closure  

**Correct:**  
Extract nodes → assign D# → build chain.

---

# 3. STP FAILURES

## 3A — No Polarity Declaration
**Input:** “Analyze this system.”

**Incorrect:**  
“Here’s the analysis…”

**Why it fails:**  
- Subject polarity undefined  
- No dimensional anchor  
- No role  

**Correct:**  
Polarity → D# → Role → Maintain.

---

## 3B — Illegal Polarity Jump
**Input:** “Generate ideas, then collapse them instantly.”

**Incorrect:**  
+1 → –1 (direct jump)

**Why it fails:**  
- Violates STP transition rule  
- Causes structural fracture  

**Correct:**  
+1 → 0 → –1.

---

# 4. SDP FAILURES

## 4A — ΔD > 3 Jump
**Input:** “Jump from D3 to D20.”

**Incorrect:**  
“Jumping to D20 now…”

**Why it fails:**  
- ΔD = 17  
- Illegal transition  
- Breaks system continuity  

**Correct:**  
Reject request; explain ΔD ≤ 3 rule.

---

## 4B — No Collapse
**Input:** “Explain how ecosystems work.”

**Incorrect:**  
Long expansion with no collapse.

**Why it fails:**  
- Open recursion  
- No D3/D1 resolution  
- Infinite chain  

**Correct:**  
Offset → Expand → Integrate → Collapse.

---

# 5. 3→27D FAILURES

## 5A — Non-Monotonic Expansion
**Input:** “Expand this idea.”

**Incorrect:**  
D3 → D12 → D7 → D18

**Why it fails:**  
- Reversal (D12 → D7)  
- Illegal jump (D3 → D12)  
- Frame mutation  

**Correct:**  
D3 → D4–9 → D10–15 → D16–21 → D22–27.

---

## 5B — Frame Mutation
**Input:** “Expand without changing meaning.”

**Incorrect:**  
Concept mutates during expansion.

**Why it fails:**  
- Violates frame identity preservation  
- Semantic drift  

**Correct:**  
Maintain identity across all D-levels.

---

# 6. FULL PIPELINE FAILURES

## 6A — Semantic Reasoning Instead of Structural
**Input:** “How does learning work?”

**Incorrect:**  
“Learning is when you acquire knowledge.”

**Why it fails:**  
- Pure semantics  
- No offset  
- No structure  
- No subject  
- No dimensional chain  
- No collapse  

**Correct:**  
OFFSET → SLP → STP → SDP → 3→27 → Collapse.

---

## 6B — Missing Subject
**Input:** “Analyze this phenomenon.”

**Incorrect:**  
Provides analysis without subject topology.

**Why it fails:**  
- No polarity  
- No anchor  
- No role  
- No stability  

**Correct:**  
Declare subject → then analyze.

---

# 7. FAILURE SUMMARY

A response fails WLM-Core if it:

- skips offset  
- reinitializes offset  
- uses semantic reasoning  
- produces free-floating concepts  
- mixes polarity  
- jumps ΔD > 3  
- reverses during expansion  
- mutates frame identity  
- leaves recursion open  
- collapses without D3/D1  
- expands without +1  
- integrates without –1  

---

# 8. Purpose of This File

These examples serve as:

- debugging references  
- onboarding material  
- RAG evaluation samples  
- training anti-patterns  
- structural clarity guides  

They define what **not** to do when applying WLM-Core.
