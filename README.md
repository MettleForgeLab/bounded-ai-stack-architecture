# Mettle Forge Lab - Bounded AI Stack Architecture

This repository preserves a versioned structural baseline for the
Mettle Forge Lab bounded AI execution architecture.

It describes how governance, control, regulation, runtime packaging,
execution infrastructure, and verification are intended to remain
separate.

This is an architecture and governance documentation repository.
It is not an executable gateway, a model-serving application, or
proof of a fully integrated production stack.

## Where to begin

- [Repository Entrypoint](REPOSITORY_ENTRYPOINT.md)
  introduces the architecture baseline, layer taxonomy, and scope.

- [Stack Overview](STACK_OVERVIEW_v1.0.md)
  explains the logical layers, their responsibilities, and the
  intended determinism boundary.

- [Release Record](RELEASE.md)
  describes the publication baseline.

- [Versioning](VERSIONING.md)
  describes how changes to the architecture are managed.

- [Security](SECURITY.md) and
  [Contributing](CONTRIBUTING.md)
  describe repository participation and review requirements.

## What the architecture separates

The published baseline distinguishes:

- Governance: invariants, escalation, and integrity requirements.
- Control: readiness and envelope decisions.
- Regulation: signal normalization and provenance discipline.
- Runtime: bounded event handling and commit constraints.
- Substrate: intended execution and isolation responsibilities.
- Verification: replay, envelope, and integrity checks.

These are architectural responsibilities, not a claim that every
corresponding implementation is present in this repository.

The source documents use normative language to describe required
behavior. Such requirements should not be confused with independent
evidence of a completed end-to-end execution.

## Determinism boundary

The architecture specifies determinism for control decisions,
configuration resolution, and associated records within declared
conditions.

Language-model token sampling remains probabilistic.

The architecture does not claim that arbitrary model output becomes
deterministic.

## Related work

The wider MFL GitHub publishes related source in separate repositories:

- [Forge Governance Architecture](https://github.com/MettleForgeLab/forge-governance-architecture-specification)
- [Bounded Switching Architecture](https://github.com/MettleForgeLab/bounded-switching-architecture-specification)
- [ARIA Event Regulation Specification](https://github.com/MettleForgeLab/bounded-event-regulation-specification)
- [Bounded Generation Rule Deck](https://github.com/MettleForgeLab/bounded-generation-rule-deck)
- [LaForge Substrate](https://github.com/MettleForgeLab/laforge-substrate)

These links identify related work, not proof that the repositories
form a single installed and validated system.

## Publication standing

The `v1.0.0-structural-complete` tag identifies the fixed
structural baseline.

Current `main` may contain later documentation changes.
Those changes do not rewrite the fixed release.

Some source documents describe logical directories such as
`/governance/`, `/runtime/`, and `/verification/`.
These describe architectural placement; they should not be mistaken
for directories supplied by this repository.

## Where to go next

Start with the Repository Entrypoint for the overall intent, then
read the Stack Overview for the component relationships.

The purpose of this repository is to make the architectural
boundaries inspectable, not to substitute documentation for
demonstrated execution.
