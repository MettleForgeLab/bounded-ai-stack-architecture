# Mettle Forge Lab (MFL)

This repository documents the canonical architecture baseline of Mettle Forge Lab’s bounded AI execution stack.

Status: Canonical Architecture v1.0

---

## Identity

MFL defines a governance-first, bounded runtime architecture for deterministic control execution over probabilistic language models.

The stack enforces:

- Atomic bounded semantic events
- Deterministic control expansion
- Replay-auditable execution
- Configuration and seed immutability
- Substrate isolation guarantees
- Escalation discipline for contract violations

---

## Layer Taxonomy

The architecture is organized into the following layers:

- **Governance Layer**  
  Contracts, escalation ladder, cross-layer integrity, signal provenance discipline.

- **Control Plane (ARIA Kernel)**  
  Scalar readiness computation and bounded gain enforcement.

- **Regulation Layer**  
  Signal normalization and deterministic telemetry discipline.

- **Runtime Layer**  
  Bounded semantic event membrane and commit atomicity.

- **Substrate Layer (LaForge)**  
  Execution host enforcing deterministic control boundaries and isolation guarantees.

- **Verification Layer**  
  Envelope validation, replay proof, and compliance artifacts.

See: `STACK_OVERVIEW_v1.0.md`

---

## Determinism Boundary

Deterministic guarantees apply to:

- Control logic
- Routing decisions
- Envelope enforcement
- Configuration resolution
- Commit record generation

Token sampling remains probabilistic and is explicitly outside control determinism guarantees.

---

## Replay & Verification Guarantees

The stack enforces:

- Configuration freeze before decode start
- Explicit seed governance
- Atomic, idempotent commit
- Parameter hashing
- Telemetry provenance discipline
- Escalation binding for violations

Replay under identical input, configuration hash, parameter block hash, seed, and model versions reproduces identical control outputs within declared tolerance.

---

## Scope Boundary

This repository documents implementation architecture and governance contracts.

Conceptual research artifacts and exploratory materials are maintained separately.

---

## Canonical vs Experimental

Canonical layers:

- `/governance/`
- `/runtime/`
- `/substrate/`
- `/verification/`

Exploratory or experimental artifacts reside under `/experimental/` and are non-binding.

---

## Version Baseline

Architecture Baseline: v1.0  
Governance Spine: Versioned (v1.0 Baseline)  
Determinism Scope: Control Layer Only

---

End of Entrypoint.
