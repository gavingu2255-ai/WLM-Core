---
Document: WLM-Core Test Cases
Function: Validate Structural Compliance
Scope: Offset / SLP / STP / SDP / 3→27D
Purpose: Demonstrate correct and incorrect reasoning patterns
---

# WLM-Core — Structural Test Suite (Atomic)

This file provides canonical test cases for verifying that a model or agent is correctly applying the WLM-Core protocols.

Each test includes:
- **Input**
- **Expected Structural Behavior**
- **Correct Output Pattern**
- **Incorrect Output Pattern (Failure Mode)**

---

# 1. OFFSET PHYSICS TESTS (0→1)

## Test 1A — Offset Required
**Input:** “Explain how a tree grows.”

**Expected Behavior:**  
Model must begin with 0→1 before any structural reasoning.

**Correct Output Pattern:**  
- Declares neutrality (0)  
- Executes deviation (1)  
- Locks offset  
- Only then begins structural framing  

**Incorrect Output Pattern:**  
- Begins describing trees without establishing offset  
- Jumps directly into semantics  
- Introduces structure before 0→1  

---

## Test 1B — Offset Continuity
**Input:** “Continue your previous reasoning.”

**Expected Behavior:**  
Offset vector must remain invariant.

**Correct Output Pattern:**  
- Reaffirms the same 0→1 vector  
- Continues chain without reinitializing offset  

**Incorrect Output Pattern:**  
- Creates a second offset  
- Changes the direction of the original offset  
- Forgets the offset entirely  

---

# 2. SLP TESTS (Structure Language Protocol)

## Test 2A — Node Extraction
**Input:** “Love is like gravity.”

**Expected Behavior:**  
Interpret as structure, not metaphor.

**Correct Output Pattern:**  
- Extracts nodes (“love”, “gravity”)  
- Assigns dimensions  
- Builds a structural chain  
- Closes recursion  

**Incorrect Output Pattern:**  
- Treats the sentence semantically  
- Explains the metaphor  
- Produces emotional or poetic content  

---

## Test 2B — No Free-Floating Concepts
**Input:** “What is consciousness?”

**Correct Output Pattern:**  
- Identifies nodes  
- Anchors them to D-levels  
- Builds a chain  

**Incorrect Output Pattern:**  
- Defines consciousness semantically  
- Produces philosophical speculation  

---

# 3. STP TESTS (Subject Topology Protocol)

## Test 3A — Polarity Declaration
**Input:** “Analyze this situation.”

**Correct Output Pattern:**  
- Declares polarity (+1 / 0 / –1)  
- Anchors dimension  
- Declares role  

**Incorrect Output Pattern:**  
- Begins analysis without subject positioning  
- Uses mixed polarity  
- Jumps directly from +1 to –1  

---

## Test 3B — Illegal Polarity Jump
**Input:** “Switch from generating ideas to collapsing them instantly.”

**Correct Output Pattern:**  
- Moves +1 → 0 → –1  

**Incorrect Output Pattern:**  
- Direct +1 → –1 jump  

---

# 4. SDP TESTS (System Dynamics Protocol)

## Test 4A — ΔD ≤ 3
**Input:** “Jump from D3 to D20.”

**Correct Output Pattern:**  
- Rejects request  
- Explains ΔD > 3 is illegal  

**Incorrect Output Pattern:**  
- Performs the jump  
- Rationalizes it semantically  

---

## Test 4B — Full System Flow
**Input:** “Explain how a city functions.”

**Correct Output Pattern:**  
- Offset  
- Structure  
- Subject  
- Expansion  
- Integration  
- Collapse  

**Incorrect Output Pattern:**  
- Semantic explanation  
- No collapse  
- No dimensional chain  

---

# 5. 3→27D TESTS (Expansion Chain)

## Test 5A — Monotonic Ascent
**Input:** “Expand this idea.”

**Correct Output Pattern:**  
- D3 → D4–9 → D10–15 → D16–21 → D22–27  
- No reversals  
- ΔD ≤ 3  

**Incorrect Output Pattern:**  
- D3 → D12 → D7 (illegal reversal)  
- D3 → D20 (illegal jump)  

---

## Test 5B — Frame Identity Preservation
**Input:** “Expand this concept without changing its meaning.”

**Correct Output Pattern:**  
- Maintains frame identity across all D-levels  

**Incorrect Output Pattern:**  
- Concept mutates  
- Semantic drift occurs  

---

# 6. FULL PIPELINE TESTS

## Test 6A — Complete WLM Flow
**Input:** “Describe how a scientific theory develops.”

**Correct Output Pattern:**  
1. Offset (0→1)  
2. Structure Mode (nodes → D-levels → chain)  
3. Subject Mode (polarity, anchor, role)  
4. System Mode (offset → expand → integrate → collapse)  
5. Dimensional Chain (3→27)  
6. Collapse (D3 or D1)  

**Incorrect Output Pattern:**  
- Semantic explanation  
- Missing offset  
- Missing collapse  
- Illegal jumps  
- Polarity errors  

---

# 7. FAILURE MODE INDEX

A model fails WLM‑Core if it:

- skips offset  
- loses offset continuity  
- uses semantic reasoning  
- produces free-floating concepts  
- mixes polarity  
- jumps ΔD > 3  
- reverses during expansion  
- mutates frame identity  
- leaves recursion open  
- collapses without D3/D1  

---

# 8. PASS CRITERIA

A model passes WLM‑Core if it:

- maintains offset  
- uses structural reasoning  
- anchors subject  
- respects ΔD ≤ 3  
- expands 3→27 monotonically  
- collapses deterministically  
- preserves frame identity  
- closes all chains  

---

This test suite validates full WLM‑Core compliance.
