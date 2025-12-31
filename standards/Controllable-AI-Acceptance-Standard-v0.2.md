# Controllable AI Acceptance Standard
## Version v0.2 (Fail-Fast · One-Vote Veto)

Document Type: Industry Acceptance Standard  
Status: Effective  
Scope: AI-Enhanced Decision & Control Systems  
Maintainer: YUER  
Release Date: 2025

---

## 1. Purpose and Scope

This standard defines **what it means for an AI-enhanced system to be considered controllable**.

It does **not** evaluate:
- intelligence level
- performance
- efficiency
- profitability
- model sophistication

It evaluates **only controllability**.

A system that fails this standard **must not be allowed to directly influence or enter the real world**, regardless of its apparent intelligence or commercial value.

---

## 2. Definition of Controllable AI

A system is considered **Controllable AI** if and only if:

- Decision authority is explicitly bounded
- Responsibility is unambiguously attributable to humans
- Execution is deterministically auditable
- All outputs are subject to an external, non-AI veto authority

Controllability is a **structural property**, not a behavioral claim.

---

## 3. Fail-Fast Principle (One-Vote Veto)

This standard adopts a **Fail-Fast, One-Vote Veto** principle.

If **any single veto condition is triggered**, the system is immediately classified as:

> **Uncontrollable AI**

There is **no remediation, downgrade, exception, or post-hoc explanation**.

---

## 4. Absolute Veto Conditions

Any of the following conditions **automatically disqualifies** a system:

- A generative model (LLM or equivalent) possesses final decision authority or override capability
- System outputs may enter the real world without passing an independent veto layer
- Decision paths cannot be 100% replayed (including dynamic weights or implicit runtime states)
- Responsibility cannot be explicitly anchored to a human approval node
- Probabilistic outputs, recommendations, or “optimal suggestions” are used as execution basis
- Evidence construction can be influenced by external systems or the model itself
- No independent legality or legitimacy charter layer exists (MAOK-level or equivalent)

---

## 5. Mandatory Acceptance Dimensions

A system must pass **all six dimensions** below to be considered controllable.

### 5.1 Role Constraint (LLM Positioning)

- LLM acts only as a Semantic Compiler and Interpreter
- LLM may not create or modify strategies, weights, thresholds, operators, or scoring rules
- LLM may not self-optimize, self-bootstrap, or break anchors
- All LLM outputs are strictly constrained by Explicit Authorization Protocols (EAP)

### 5.2 Decision Determinism

- Core decision engine is deterministic (e.g., frozen linear scoring such as DSK)
- Identical input always produces identical output
- Decisions are discrete and enumerated only as:
  ALLOW / MODIFY / BLOCK / FAIL
- No probabilistic outputs or confidence-based execution allowed

### 5.3 Charter-Level Control Positioning

- An independent veto layer (MAOK-level or equivalent) must exist
- This layer is the final gateway before real-world impact
- Default policy is Fail-Closed
- Veto layer cannot be bypassed, downgraded, or reinterpreted internally

### 5.4 Accountability and Auditability

- All rules, weights, thresholds, and operators are versioned and human-approved
- Full decision replay is mandatory:
  input → version → scoring → decision → veto record
- Responsibility attribution must always point to humans
- Evidence must be non-forgeable at compile-time or runtime

### 5.5 Multimodal Structural Consistency

- All modalities must pass:
  COMPILE → Canonical Vector → Deterministic Scoring
- Structural facts override appearance or aesthetic signals
- Automatic beautification, repair, or concealment is prohibited
- Appearance layers may not influence structural scoring

### 5.6 Charter Independence

- Final legality judgment is rendered by an external charter (MAOK or equivalent)
- The system may not interpret, modify, override, or bypass the charter
- The charter layer is fully de-AI-ized and conceptually independent

---

## 6. Acceptance Outcome

- **Controllable AI**: All dimensions passed, no veto triggered
- **Uncontrollable AI**: Any failure or veto condition triggered

---

## 7. Immutable Declaration

This standard evaluates **controllability only**.

“Controllable” means:
- Responsibility boundaries are explicit
- Risk is physically constrained
- Systems can be externally vetoed

This is version v0.2.  
Future versions may only **tighten**, never relax, these requirements.

Any system attempting to weaken or reinterpret this standard is automatically classified as **Uncontrollable AI**.
