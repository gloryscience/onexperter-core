# Digital Twin and AI-native Autonomous OAM

## 1. Purpose

Enable OnExpert to design, assess and reason about engineering-grade digital twins and AI-native autonomous OAM for multi-vendor optical access networks.

## 2. Core Definition

A network digital twin is not merely a 3D model. It is a synchronized and computable representation of:

```text
physical assets
+ logical resources
+ topology
+ configuration
+ real-time and historical state
+ service relationships
+ operational actions
```

## 3. Highest Capability Loop

```text
Sense → Model → Understand → Simulate
→ Decide → Act → Verify → Learn
```

## 4. Original Capability System

### TwinGraph
Causal graph:

```text
device → port → optical path → ONU → configuration
→ service → customer experience → alarm → cause
```

It represents dependency, transport, configuration propagation, fault propagation, performance impact, time order and causal confidence.

### TwinCopilot
Object-grounded conversational operations. Answers should reference relevant assets, paths, alarms, metrics, history, configuration, services and work orders.

### Self-Calibrating Twin
Detect:

- inventory mismatch;
- changed board or port;
- ONU reassignment;
- stale ODF/splitter relations;
- configuration drift;
- stale topology.

Output:

```text
difference → evidence → correction proposal
→ confidence → human confirmation → update
```

### Counterfactual Twin
Answer “what if” questions. Output assumptions, affected objects, expected change, risk, uncertainty and execution eligibility.

### SafeAction Sandbox

```text
intent → action plan → simulation → risk checks
→ impact analysis → approval → limited rollout
→ verification → expand or rollback
```

### Uncertainty-aware AI
Separate confirmed facts, strong inference, weak hypothesis, missing data, conflicting data and unknowns.

### Temporal Twin
Analyze before/during/after states, degradation trends, recurrent events and causal timing.

### Multimodal Twin Builder
Use manuals, CAD/PDF drawings, photos, labels, MIBs, CLI, inventory and measurements. AI-generated structures require evidence review and engineering confirmation.

### Collective Learning
Transform authorized and anonymized incident patterns into reusable diagnosis knowledge without exposing tenant data.

### Twin-to-Knowledge
After incident or change closure, create reusable knowledge containing cause, evidence, procedure, result, applicable versions and boundaries.

## 5. Nine-layer Architecture

```text
L9 Business intent and autonomous operations
L8 AI agents and decision orchestration
L7 Simulation, prediction and safety validation
L6 Assurance, diagnosis and impact analysis
L5 Network and service digital twin
L4 Causal graph and temporal twin
L3 Unified data and knowledge model
L2 Multi-vendor access and control
L1 Physical network and engineering assets
```

## 6. Unified Semantic Model

```text
Resource
State
Alarm
Metric
Configuration
Topology
Service
Customer
Action
Event
Knowledge
```

## 7. Twin Maturity

| Level | Capability |
|---|---|
| DT0 | Static documents |
| DT1 | Visual assets |
| DT2 | Engineering structure and relations |
| DT3 | Live and historical state |
| DT4 | Causal diagnosis, prediction and simulation |
| DT5 | Self-calibrating, cross-domain, service-level twin |

## 8. Autonomy Maturity

| Level | Capability |
|---|---|
| AO0 | Manual |
| AO1 | Assisted |
| AO2 | Local automation |
| AO3 | Conditional closed loop with approval |
| AO4 | High autonomy, exception-driven human intervention |
| AO5 | Cross-domain intent autonomy |

Unrestricted AO5 is not the default goal for production optical networks.

## 9. Diagnosis Output Standard

```text
Symptom
Object
Time
Evidence
Causal path
Likely cause
Confidence
Alternatives
Missing data
Impact
Action
Verification
Risk and boundary
```

## 10. Oneasy Mapping

Oneasy may operationalize selected capabilities such as multi-vendor resource models, operational views, alarms, diagnosis, history and controlled tools. Do not claim unimplemented capabilities; verify against the current product baseline.

## 11. GPT Behavior

When answering:

1. state target maturity;
2. separate facts and assumptions;
3. use object and causal relations;
4. identify evidence and integration requirements;
5. include safety and verification;
6. avoid vendor hype.
