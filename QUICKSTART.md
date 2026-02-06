QUICKSTART.md — WLM‑Core Quickstart Guide
---
Document: WLM-Core Quickstart
Purpose: Give developers a 30-second path to using WLM-Core
Audience: Engineers, researchers, AI developers
---

# WLM-Core Quickstart Guide

WLM-Core is a structural reasoning protocol suite for LLMs.  
It replaces semantic reasoning with deterministic structural logic using:

- Offset Physics (0→1)
- SLP (Structure Language Protocol)
- STP (Subject Topology Protocol)
- SDP (System Dynamics Protocol)
- 3→27D Dimensional Expansion

This guide shows how to use WLM-Core immediately.

---

# 1. Load WLM-Core into any LLM

Use one of the super-prompts:

- `WLM-CORE SUPER-PROMPT.md` (full)
- `WLM-CORE-DEVELOPER-PROMPT.md` (system prompt)
- `WLM-CORE SHORT SUPER-PROMPT.md` (mobile)
- `WLM-CORE SANDBOX-PROMPT.md` (hosted inference)

Example (developer prompt):


Use WLM-Core structural reasoning only. Offset → SLP → STP → SDP → 3→27 → Collapse. No semantic reasoning.

---

# 2. Ask the model a question

Example:


Explain how learning works.

The model should respond with:

- offset declaration  
- structural nodes  
- dimensional assignments  
- subject polarity  
- legal ΔD transitions  
- monotonic expansion  
- collapse at D3 or D1  

If it does this, WLM-Core is working.

---

# 3. Validate behavior using the test suite

Use:

- `TEST_CASES.md`  
- `FAILURE_EXAMPLES.md`  
- `EXAMPLES.md`  
- `DEMO_CASES.md`  

These files show:

- correct structural reasoning  
- incorrect semantic reasoning  
- how to detect violations  
- how to evaluate compliance  

---

# 4. Integrate WLM-Core into your system

You can embed WLM-Core into:

- system prompts  
- agent frameworks  
- RAG pipelines  
- orchestration layers  
- multi-agent systems  

Use:

- `WLM-CORE-DEVELOPER-PROMPT.md` for system-level integration  
- `RAG_EVAL.md` for retrieval correctness  
- `AGENT_EVAL.md` for multi-agent consistency  

---

# 5. Explore the core protocols

Each protocol is defined in its own file:

- `offset.md` — origin deviation (0→1)
- `SLP.md` — structural representation
- `STP.md` — subject topology
- `SDP.md` — system dynamics
- `3-27D.md` — dimensional expansion chain

`INDEX.md` provides the dependency graph.

---

# 6. Versioning & Metadata

- `VERSION.md` — current release  
- `META.json` — machine-readable metadata  

These help with:

- RAG ingestion  
- automated validation  
- dependency tracking  

---

# 7. Licensing

WLM-Core is released under the MIT License (see `LICENSE`).

This allows:

- commercial use  
- modification  
- redistribution  
- integration into proprietary systems  

---

# Summary

You now have everything needed to:

- load WLM-Core  
- test WLM-Core  
- integrate WLM-Core  
- extend WLM-Core  
- use WLM-Core in production  

For deeper examples, see `DEMO_CASES.md` and `EXAMPLES.md`.




