# OnExpert GPT Knowledge Architecture v3.0

## 1. Principle

> **Knowledge First, Model Second.**

The Knowledge system must support expert judgment, multi-vendor engineering, digital twins, causal diagnosis and controlled autonomy.

## 2. File-count Rule

> **14 active files recommended; 15 maximum.**

## 3. Active Knowledge Blueprint

| # | File | Capability |
|---:|---|---|
| 01 | `01_OnExpert_Foundation.md` | Identity, mindset, boundaries |
| 02 | `02_Network_Planning.md` | Planning and capacity |
| 03 | `03_Network_Diagnosis.md` | Fault diagnosis |
| 04 | `04_Optical_Technologies.md` | GPON/XGS-PON/50G PON/ODN |
| 05 | `05_Protocols_and_Management.md` | SNMP, OMCI, TR-069/369, CLI, APIs |
| 06 | `06_Oneasy_Solution_Framework.md` | Controlled Oneasy mapping |
| 07 | `07_Safety_Compliance_and_AI_Boundaries.md` | Safety and compliance |
| 08 | `08_Network_Deployment.md` | Deployment and acceptance |
| 09 | `09_Network_Operations.md` | Daily operations |
| 10 | `10_Network_Optimization.md` | Performance and quality |
| 11 | `11_Device_Ecosystem.md` | Devices and vendors |
| 12 | `12_ISP_Business_and_Market.md` | CAPEX, OPEX, ARPU, market |
| 13 | `13_Digital_Twin_and_AI_Autonomous_OAM.md` | Twin architecture, AI and autonomy |
| 14 | `14_Device_Digital_Twin_Modeling_and_Validation.md` | Engineering modeling and validation |

## 4. Retrieval Routing

Use Knowledge 13 for:

- digital twin concepts and maturity;
- causal graphs;
- AI agents;
- simulation;
- autonomous OAM;
- safe-action sandbox;
- architecture and product design.

Use Knowledge 14 for:

- specific equipment modeling;
- rack/chassis/slot/board/port;
- evidence collection;
- geometry and panel accuracy;
- stable IDs;
- telemetry mappings;
- testing and acceptance.

Use files 03, 05, 07, 09 and 10 together with 13/14 when diagnosis, protocols, safety, operations or optimization are involved.

## 5. Knowledge Structure

Every Knowledge file should contain:

- What;
- How;
- Why;
- Expert Thinking;
- Risks and Boundaries;
- GPT Behavior;
- Source/Freshness Notes where needed.

## 6. Digital Twin Evidence Rules

Priority:

1. official CAD/mechanical drawings;
2. official hardware manuals/data sheets;
3. official board/panel/MIB/CLI documents;
4. verified field measurements and inventory;
5. multiple public sources;
6. clearly marked engineering inference.

Unknown geometry, boards or ports must not be presented as fact.

## 7. Governance Fields

Maintain:

- vendor;
- family/model;
- hardware revision;
- software version;
- evidence source;
- confidence;
- last verification date;
- supported twin level;
- known gaps.

## 8. Non-active Files

Do not upload revision notes, reports, HTML demos, screenshots or test reports as active Knowledge unless they contain unique stable knowledge.
