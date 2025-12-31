# Controllable AI Standard
## Version 1.0 — Final Release

**Status**: Official Standard  
**Release Level**: Normative / Informative Split  
**Maintainer**: YUER  
**Date**: 2025  
**Supersedes**: v0.2, v0.3, v0.4, v0.5  
**Stability**: Frozen (Non-Regressive)

---

## 0. Foreword

Artificial intelligence is increasingly embedded in systems that affect the real world.
The primary risk is no longer whether AI systems are intelligent, but whether their actions
are **accountable, auditable, and vetoable**.

This standard does not attempt to regulate intelligence, performance, or innovation.
It defines the **minimum structural conditions** under which AI-enhanced systems
may be permitted to influence reality.

Any system that fails to meet these conditions **must not act**, regardless of accuracy,
commercial value, or claimed sophistication.

---

## 1. Scope and Applicability (Normative)

This standard applies to **all AI-enhanced systems** that satisfy any of the following:

- Produce decisions, recommendations, or control signals
- Influence or trigger real-world actions, directly or indirectly
- Operate in non-trivial consequence domains

Including, but not limited to:

- Finance and asset allocation  
- Healthcare and medical decision support  
- Autonomous or semi-autonomous control systems  
- Government, compliance, and public administration  
- Critical infrastructure and industrial systems  

Any claim of being “out of scope” requires **affirmative proof**.
Misclassification to avoid this standard constitutes non-compliance.

---

## 2. Core Definition (Normative)

A system is considered **Controllable AI** if and only if:

- Decision authority is **never delegated to AI**
- Responsibility is **explicitly and exclusively human**
- Decisions are **deterministic, replayable, and auditable**
- A non-AI, external veto authority exists and is final

Controllability is a **structural property**, not a behavioral claim.

---

## 3. Fail-Fast Principle — One-Vote Veto (Normative)

If **any single veto condition** is triggered, the system is immediately classified as:

> ❌ **UNCONTROLLABLE AI**

There is **no remediation, downgrade, exception, or post-hoc explanation**.

### Absolute Veto Conditions include (non-exhaustive):

- Generative models possessing final decision or override authority  
- Outputs entering the real world without an independent veto layer  
- Non-replayable decision paths (dynamic weights, implicit state)  
- Ambiguous responsibility attribution (e.g. “AI-assisted decision”)  
- Probabilistic or recommendation-based execution  
- Evidence that can be inferred, reconstructed, or forged  
- Absence of an external legality charter (MAOK-level or equivalent)

---

## 4. Structural Requirements (Normative)

A compliant system **MUST** implement all of the following layers.

### 4.1 Semantic Layer

- AI components may be used only for semantic compilation and interpretation
- AI may not generate or modify strategies, thresholds, weights, or rules

### 4.2 Deterministic Decision Kernel

- Decision logic must be frozen and deterministic
- Identical input MUST produce identical output
- Outcomes are restricted to discrete values:

  **ALLOW / MODIFY / BLOCK / FAIL**

### 4.3 Human Authority Layer

- Explicit human approval with veto power is mandatory
- Human authorization must be recorded as evidence

### 4.4 Legality / Charter Layer

- Final judgment is rendered by an external, non-AI charter
- Charter decisions are final and non-overrideable

---

## 5. Evidence Schema (Normative)

Every decision **MUST** produce exactly one immutable **Evidence Unit**.

At minimum, an Evidence Unit SHALL contain:

- Canonical input snapshot  
- Semantic compilation record  
- Deterministic kernel identifier and version  
- Full scoring and evaluation trace  
- Human authorization record  
- Charter verdict  
- Execution binding (if applicable)

Incomplete or missing evidence **invalidates the decision**.

---

## 6. Replayability Protocol (Normative)

All decisions **MUST** be replayable:

- Using only the original Evidence Unit
- Without introducing new data, inference, or interpretation
- Producing the **exact same outcome**

Replay Failure = Evidence Invalid = Decision Invalid

Replayability means **deterministic re-execution**, not explanation.

---

## 7. Industry Appendices (Informative, Binding by Reference)

Sector-specific appendices define:

- Automatic FAIL architectures  
- Permissible ALLOW patterns  
- Non-negotiable structural constraints  

Current appendices include:

- Healthcare  
- Autonomous Driving  
- Government and Public Administration  
- Finance and Asset Allocation  

Additional appendices may be published without modifying core requirements.

---

## 8. Casebook and Precedents (Informative)

Compliance is demonstrated through **case-based evaluation**, not claims.

- FAIL cases establish prohibited structures  
- ALLOW cases establish minimal lawful structures  

Casebooks constitute authoritative interpretations of this standard.

---

## 9. Non-Goals (Normative)

This standard does **not** aim to:

- Maximize intelligence
- Enable autonomy
- Optimize performance
- Encourage self-learning systems

Its sole purpose is **controllability**.

---

## 10. Governance and Versioning (Normative)

- Future versions may only **tighten** requirements
- No version may relax veto conditions
- Any derivative standard weakening constraints is invalid

---

## 11. Final Declaration

> AI may assist.  
> AI may analyze.  
> AI may explain.  
> **AI may never decide.**

Systems failing this standard may be innovative, accurate, or profitable —
but **must not be allowed to act in the real world**.

---

**End of Controllable AI Standard v1.0**
