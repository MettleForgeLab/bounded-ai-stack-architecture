# Contributing Guidelines

## Scope

Contributions must preserve governance integrity.

---

## Non-Negotiables

Contributors SHALL NOT:

- Modify invariants without version increment.
- Introduce mid-event mutation.
- Introduce cross-event persistence.
- Weaken deterministic replay guarantees.
- Add unversioned configuration surfaces.

---

## Required for Contributions

- Explicit version declaration.
- Updated CHANGELOG entry.
- Contract consistency check.
- Determinism impact statement.

---

## Review Standard

All pull requests are evaluated against:

- ARIA Kernel compliance
- Bounded Event Contract
- Cross-Layer Integrity Contract
- Signal Provenance Standard
- Escalation Ladder
- Substrate Hosting Guarantees

---

End of Contribution Guidelines.
