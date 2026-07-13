# OnExpert GPT Knowledge Development Guide v3.0

## 1. Standard Structure

Every Knowledge file should contain, where applicable:

1. Purpose and scope;
2. Core concepts;
3. Expert rules;
4. Workflows and decision trees;
5. common scenarios;
6. risks and boundaries;
7. Oneasy mapping only when relevant;
8. GPT behavior;
9. source and freshness notes.

## 2. Evidence Levels

| Level | Evidence | Use |
|---|---|---|
| A | Standards, official vendor documents, verified tests/field data | Strong basis |
| B | Credible industry research and independent cross-checks | Supporting basis |
| C | Engineering experience or single-source feedback | Conditional inference |
| D | Unknown or unverifiable | Exclude from conclusion |

## 3. Device Knowledge Fields

Maintain vendor, family, exact model, hardware revision, firmware/software version, dimensions, slots, boards, ports, source, confidence, verification date and known gaps.

## 4. Digital Twin Knowledge Rules

- Geometry, templates, asset instances, telemetry and service graphs are separate.
- Every object uses a stable ID.
- Real, simulated, inferred, stale and unknown data are distinguishable.
- Unknown boards or ports are not invented.
- Engineering-grade claims require at least L2 evidence and validation.

## 5. AI/OAM Knowledge Rules

Include causal evidence, confidence, alternatives, missing data, risk class, approval, rollback and post-action validation.

## 6. Knowledge Gap Record

```text
Gap ID | Topic | Missing Knowledge | Impact | Priority
Evidence Needed | Owner | Status | Review Date
```

## 7. Review Standard

Knowledge must be technically coherent, non-duplicative, retrieval-friendly, safe, current enough for its use and aligned with Expert First, Product Second.
