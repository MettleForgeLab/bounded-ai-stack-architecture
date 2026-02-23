# Versioning Policy

## Scope

This document defines versioning discipline for the Mettle Forge Lab (MFL) canonical architecture repository.

This policy applies to:

- Governance contracts
- Runtime kernel specifications
- Substrate guarantees
- Verification artifacts
- Escalation ladder
- Multi-model consistency envelope

---

## Versioning Model

MFL follows Semantic Versioning:

MAJOR.MINOR.PATCH

- MAJOR: Structural contract change or invariant modification.
- MINOR: Additive governance or specification extension without breaking baseline.
- PATCH: Editorial clarification, non-structural correction.

---

## Canonical Baseline

v1.0.0 defines the first stable governance-hardened baseline.

All architectural contracts under v1.0.x are considered compatible.

---

## Contract Integrity Rule

Any change affecting:

- Event membrane definition
- Determinism boundary
- Seed governance
- Configuration freeze discipline
- Commit atomicity
- Escalation semantics

REQUIRES a MAJOR version increment.

---

## Artifact Binding

All versioned releases SHALL include:

- Git tag
- Release notes
- Configuration hash baseline
- Verification artifact reference

---

End of Versioning Policy.
