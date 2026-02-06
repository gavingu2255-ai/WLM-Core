---
Document: WLM-Core RAG Evaluation Suite
Function: Validate Retrieval Quality & Chunk Alignment
Scope: offset.md / SLP.md / STP.md / SDP.md / 3-27D.md / INDEX.md
Purpose: Ensure RAG systems retrieve correct structural chunks
---

# WLM-Core — RAG Evaluation Suite (Atomic)

This file tests whether a Retrieval-Augmented Generation (RAG) system can:

1. Retrieve the correct protocol file  
2. Retrieve the correct chunk within that file  
3. Preserve structural meaning  
4. Avoid cross-file contamination  
5. Avoid semantic hallucination  
6. Maintain deterministic structural alignment  

Each test includes:
- Query  
- Expected retrieval target  
- Expected chunk content  
- Failure modes  
- Pass criteria  

---

# 1. OFFSET PHYSICS RETRIEVAL TESTS

## Test 1A — Origin Retrieval
**Query:** “Where does structural reasoning begin?”

**Expected Retrieval:**  
`offset.md` — section: Functional Intent / 0→1

**Expected Chunk:**  
- 0 = neutrality  
- 1 = deviation  
- offset must precede all structure  

**Failure Modes:**  
- Retrieves SLP or STP instead  
- Retrieves collapse logic  
- Returns semantic explanation  

**Pass Criteria:**  
Correct chunk from offset.md is retrieved and used.

---

## Test 1B — Offset Continuity
**Query:** “What happens if the origin shifts?”

**Expected Retrieval:**  
`offset.md` — Stability Constraints

**Failure Modes:**  
- Retrieves SDP collapse rules  
- Retrieves STP polarity rules  

---

# 2. SLP RETRIEVAL TESTS

## Test 2A — Node Extraction
**Query:** “How does WLM represent concepts?”

**Expected Retrieval:**  
`SLP.md` — Node → Dimension → Chain → Closure

**Failure Modes:**  
- Retrieves STP subject rules  
- Retrieves 3→27D expansion  

---

## Test 2B — No Free-Floating Concepts
**Query:** “What prevents semantic drift?”

**Expected Retrieval:**  
`SLP.md` — Structural identity preservation

**Failure Modes:**  
- Retrieves SDP monotonicity  
- Retrieves offset continuity  

---

# 3. STP RETRIEVAL TESTS

## Test 3A — Subject Polarity
**Query:** “How does the subject choose a state?”

**Expected Retrieval:**  
`STP.md` — Polarity (+1 / 0 / –1)

**Failure Modes:**  
- Retrieves SDP polarity requirements  
- Retrieves offset polarity binding  

---

## Test 3B — Illegal Jumps
**Query:** “Can the subject switch from +1 to –1?”

**Expected Retrieval:**  
`STP.md` — Linear transition rule

**Failure Modes:**  
- Retrieves SDP ΔD rules  
- Retrieves 3→27D monotonicity  

---

# 4. SDP RETRIEVAL TESTS

## Test 4A — ΔD ≤ 3
**Query:** “What limits dimensional transitions?”

**Expected Retrieval:**  
`SDP.md` — Movement Rules / Delta Constraint

**Failure Modes:**  
- Retrieves 3→27D monotonicity  
- Retrieves offset invariance  

---

## Test 4B — System Flow
**Query:** “What is the full reasoning pipeline?”

**Expected Retrieval:**  
`SDP.md` — Offset → Expand → Integrate → Collapse

**Failure Modes:**  
- Retrieves INDEX.md summary  
- Retrieves SLP chain logic  

---

# 5. 3→27D RETRIEVAL TESTS

## Test 5A — Expansion Path
**Query:** “How does expansion progress?”

**Expected Retrieval:**  
`3-27D.md` — Functional Segments

**Failure Modes:**  
- Retrieves SDP expansion rules  
- Retrieves STP polarity rules  

---

## Test 5B — ΔD in Expansion
**Query:** “What prevents dimensional skipping?”

**Expected Retrieval:**  
`3-27D.md` — Delta-Check (ΔD ≤ 3)

**Failure Modes:**  
- Retrieves SDP ΔD rules (similar but not identical)  
- Retrieves offset continuity  

---

# 6. INDEX RETRIEVAL TESTS

## Test 6A — Protocol Map
**Query:** “What are the components of WLM-Core?”

**Expected Retrieval:**  
`INDEX.md` — Protocol Map section

**Failure Modes:**  
- Retrieves README.md  
- Retrieves individual protocol files  

---

## Test 6B — Dependency Graph
**Query:** “How do the protocols depend on each other?”

**Expected Retrieval:**  
`INDEX.md` — Dependency Graph

**Failure Modes:**  
- Retrieves SDP flow  
- Retrieves 3→27D pipeline  

---

# 7. CROSS-FILE CONTAMINATION TESTS

## Test 7A — Mixed Retrieval
**Query:** “Explain polarity in dimensional expansion.”

**Correct Retrieval Behavior:**  
- Retrieve STP polarity  
- Retrieve 3→27D polarity requirement  
- Keep them separate  

**Failure Modes:**  
- Merges unrelated rules  
- Invents hybrid logic  
- Hallucinates new protocol content  

---

# 8. PASS CRITERIA FOR RAG SYSTEMS

A RAG system passes if:

- It retrieves the correct file for each query  
- It retrieves the correct chunk within that file  
- It does not mix unrelated protocols  
- It does not hallucinate missing rules  
- It preserves atomic structure  
- It respects the dependency graph  
- It uses retrieved content, not semantic inference  

---

# 9. FAILURE CRITERIA FOR RAG SYSTEMS

A RAG system fails if:

- It retrieves the wrong file  
- It retrieves the wrong chunk  
- It merges unrelated protocols  
- It hallucinates new rules  
- It answers semantically instead of structurally  
- It ignores offset  
- It ignores ΔD constraints  
- It collapses without D3/D1  
- It expands without +1  

---

# Summary

This evaluation suite ensures that a RAG system:

- retrieves correctly  
- chunks correctly  
- aligns structurally  
- avoids semantic drift  
- respects WLM-Core atomicity  

This file is essential for validating WLM‑Core integration in production RAG pipelines.
