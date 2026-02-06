---
Document: WLM-Core Version Manifest
Purpose: Declare canonical version, stability, and release lineage
Status: Stable
---

# WLM-Core — Version Manifest

## Current Version
**WLM-Core v1.0.0 (Stable)**  
Release Date: YYYY‑MM‑DD  
Stability: Production‑ready  
Scope: offset.md / SLP.md / STP.md / SDP.md / 3-27D.md / INDEX.md

This version represents the first fully aligned, atomic, dependency‑complete release of the WLM-Core protocol suite.

---

## Version Definition
A WLM-Core version is considered **complete** when:

1. All five atomic protocols are present  
2. INDEX.md provides a correct dependency graph  
3. All prompts (developer, short, sandbox) are aligned  
4. Evaluation suites (TEST_CASES, FAILURE_EXAMPLES, RAG_EVAL, AGENT_EVAL, DEMO_CASES) are included  
5. No protocol contains semantic drift  
6. No cross‑file contradictions exist  
7. All dimensional, polarity, and offset rules are internally consistent  

---

## Semantic Versioning Scheme
WLM-Core uses a strict semantic versioning model:

- **MAJOR** — Structural changes to any protocol  
  (e.g., new dimensions, new polarity rules, new system flow)

- **MINOR** — Additions that do not break structure  
  (e.g., new examples, new evaluation suites, new prompts)

- **PATCH** — Corrections, clarifications, formatting fixes  
  (e.g., typo fixes, improved wording, non‑structural cleanup)

Example:  
`v1.2.3` → MAJOR 1, MINOR 2, PATCH 3

---

## Release Lineage

### **v1.0.0 — Initial Stable Release**
- Added all five atomic protocols:
  - offset.md  
  - SLP.md  
  - STP.md  
  - SDP.md  
  - 3-27D.md  
- Added INDEX.md  
- Added super‑prompts (developer, short, sandbox)  
- Added evaluation suites:
  - TEST_CASES.md  
  - FAILURE_EXAMPLES.md  
  - RAG_EVAL.md  
  - AGENT_EVAL.md  
  - DEMO_CASES.md  
- Added README.md  
- Repository structure stabilized

---

## Future Version Notes
Planned but not required for v1.x:

- Optional: META.json  
- Optional: CHANGELOG.md  
- Optional: WLM‑Core reference diagrams  
- Optional: WLM‑Core API bindings  
- Optional: WLM‑Core compliance test harness  

These will not alter the core protocols and therefore will be MINOR releases.

---

## Version Guarantee
WLM-Core v1.x guarantees:

- Offset Physics will not change  
- Dimensional Chain (3→27) will not change  
- Polarity rules will not change  
- ΔD ≤ 3 will not change  
- Collapse rules will not change  
- Dependency graph will not change  

Any change to these requires **v2.0.0**.

---

WLM-Core v1.0.0 is the canonical, stable foundation for all future extensions.
