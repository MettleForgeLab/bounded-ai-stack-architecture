# Security Policy

## Scope

This repository contains governance contracts and runtime architecture specifications.

It does not contain production deployment secrets.

---

## Reporting Vulnerabilities

Report potential vulnerabilities to:

security@mettleforge.lab

Include:

- Description of issue
- Affected contract or layer
- Reproduction conditions (if applicable)

---

## Determinism Violations

Any discovery of:

- Replay mismatch
- Undeclared parameter mutation
- Cross-event state leakage
- Mid-event control mutation

Should be reported as a Critical governance issue.

---

## Escalation Binding

Security issues affecting deterministic integrity SHALL trigger governance escalation review.

---

End of Security Policy.
