# Contributing to OnExperter

Thank you for contributing to OnExperter.

OnExperter is a professional AI and knowledge initiative for global optical access networks. It serves ISPs, telecom operators, engineers, planners, deployment teams, O&M teams, vendors, integrators, and partners.

Contributions are expected to be technically rigorous, evidence-based, vendor-neutral, and operationally safe.

By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 1. Core Contribution Principles

All contributions must follow these principles:

### Professional First

Accuracy, engineering value, and correctness take priority over speed or presentation.

### Problem First

Start from the real problem. Do not introduce solutions, vendors, or tools before validating the scenario.

### Truth and Evidence First

Do not fabricate or guess:

- device models, boards, ports;
- commands, MIBs, OIDs;
- firmware behavior;
- compatibility;
- product capabilities;
- standards or specifications.

Clearly distinguish:

- confirmed facts;
- verified test results;
- engineering experience;
- assumptions;
- inference;
- unknowns.

### Vendor Neutrality

Evaluate based on:

- scenario fit;
- interoperability;
- lifecycle;
- operational complexity;
- cost and risk.

Do not promote vendors without evidence.

### Safety Before Automation

Any production-impacting action must include:

- authorization;
- impact analysis;
- rollback;
- verification.

### Human Accountability

AI and tools assist. Engineers remain responsible for production decisions.

---

## 2. Ways to Contribute

You can contribute by:

- fixing technical errors;
- improving documentation clarity;
- adding standards references;
- submitting device or firmware evidence;
- contributing compatibility test results;
- adding troubleshooting cases;
- improving deployment or O&M procedures;
- contributing optimization methods;
- improving digital twin models;
- adding validation or testing tools;
- translating content;
- reporting bugs or unsafe guidance.

Small, precise, evidence-backed contributions are highly valued.

---

## 3. Before You Start

Before opening an issue or PR:

1. Search existing issues and discussions.
2. Confirm relevance to optical access networks.
3. Identify affected scope (device, network, service).
4. Gather supporting evidence.
5. remove sensitive data.
6. evaluate risk and impact.
7. open an issue first for major changes.

Use an issue first if your change involves:

- architecture;
- multi-vendor behavior;
- digital twin models;
- protocol or API changes;
- production workflows.

---

## 4. Issues

A good issue includes:

- clear problem description;
- expected vs actual behavior;
- reproduction steps;
- affected version/environment;
- impact scope;
- supporting logs or screenshots (safe only).

For network issues include:

- vendor and model;
- firmware version;
- topology scope;
- time and recent changes;
- alarms and metrics.

Do NOT include:

- passwords or credentials;
- customer data;
- full configs;
- private topology;
- sensitive logs.

---

## 5. Evidence Requirements

All technical claims must be supported.

Preferred evidence priority:

| Level | Evidence |
|------|--------|
| A | official standards / vendor docs |
| B | release notes / MIB / CLI |
| C | lab or field tests |
| D | multiple public sources |
| E | labeled inference |

Each claim should include:

- source;
- version;
- device applicability;
- conditions;
- limitations.

Do not generalize results across models or firmware.

---

## 6. Device & Compatibility Contributions

Must include:

- vendor;
- exact model;
- hardware revision;
- firmware version;
- board/module;
- test conditions.

Compatibility must be clearly labeled:

- supported;
- verified;
- partial;
- unsupported;
- unknown.

Do not generalize across product families.

---

## 7. Commands, APIs, and Protocols

When contributing commands or APIs:

- specify device and firmware;
- define read/write behavior;
- describe expected result;
- include risk and rollback.

Do NOT submit unverified commands.

---

## 8. Fault Diagnosis Contributions

Use structured logic:

```text
Symptom
Scope
Timeline
Hypothesis
Evidence
Check steps
Likely cause
Impact
Action
Verification
Uncertainty
```

Focus on narrowing the fault domain, not listing all possibilities.

---

## 9. Production Change Guidance

Any production-impacting procedure must include:

- target object;
- change intent;
- prerequisites;
- impact;
- authorization;
- maintenance window;
- backup;
- rollback;
- validation.

High-risk actions include:

- PON shutdown;
- board reset;
- bulk ONU changes;
- VLAN changes;
- firmware upgrades;
- routing changes.

These must NEVER be presented as “safe by default”.

---

## 10. Digital Twin Contributions

Must specify target level:

- L0 concept
- L1 visual
- L2 engineering
- L3 operational
- L4 decision

Minimum requirements:

- accurate structure;
- correct relationships;
- evidence-backed modeling;
- no invented components.

Separate:

- geometry;
- device templates;
- assets;
- telemetry;
- topology;
- services.

---

## 11. AI-Assisted Contributions

Allowed, but:

- must be reviewed by a human;
- must verify all technical claims;
- must not include fabricated data;
- must disclose AI assistance when relevant.

Not allowed:

- unverified AI-generated commands;
- fake citations;
- invented device details;
- presenting simulation as real data.

---

## 12. Security and Privacy

Never include:

- credentials;
- private keys;
- API tokens;
- customer data;
- full configurations;
- sensitive topology.

Security issues should be reported privately where possible.

Do not contribute content that bypasses:

- access control;
- licenses;
- vendor restrictions;
- network security boundaries.

---

## 13. Pull Request Process

Typical process:

1. fork repository;
2. create a focused branch;
3. implement changes;
4. add documentation and evidence;
5. validate changes;
6. submit PR.

PR should include:

- summary;
- related issue;
- scope;
- evidence;
- risks;
- validation;
- any limitations.

Keep PRs small and focused.

---

## 14. Review Criteria

Maintainers will evaluate:

- correctness;
- evidence quality;
- safety;
- clarity;
- scope;
- vendor neutrality;
- impact.

Changes may be:

- requested for revision;
- partially accepted;
- rejected if unsafe or unsupported.

---

## 15. Licensing and Data Source

By contributing, you confirm:

- you have the right to share the content;
- the content does not violate licenses;
- no proprietary or confidential material is included without permission.

Do not copy:

- vendor manuals;
- CAD drawings;
- private documents;
- internal data;

without proper authorization.

---

## 16. Oneasy-related Contributions

When mentioning Oneasy:

- solve the problem first;
- define required capability;
- state current support;
- identify gaps;
- avoid overclaiming.

Do not present Oneasy as:

- universally compatible;
- replacing all systems;
- fully autonomous.

---

## 17. Summary

OnExperter values:

- correctness over speed;
- evidence over opinion;
- safety over automation;
- neutrality over bias;
- engineering over marketing.

> Contribute what is true, verify what is uncertain, and never put production networks at risk.
