# Device Digital Twin Modeling and Validation

## 1. Purpose

Provide a repeatable engineering method for digital twins of OLT, ONU/ONT, CPE, PON access devices and rack-mounted systems.

Core principle:

> **Appearance recognizable, structure accurate, relationships clear, state truthful, faults traceable.**

## 2. Minimum Engineering Definition

A qualified device twin maps:

```text
physical entity
+ logical resource
+ connection
+ operational state
+ alarm/performance
+ service impact
+ operational record
```

## 3. Object Hierarchy

```text
Site
└─ Room
   └─ Rack
      └─ Chassis
         ├─ Slot
         │  └─ Board
         │     ├─ Module
         │     ├─ Physical Port
         │     └─ LED
         ├─ Power
         ├─ Fan
         ├─ Control Board
         ├─ Backplane
         └─ Ground
```

Access path:

```text
Physical Port → PON → ODF → Cable
→ Splitter → Drop Cable → ONU/ONT
```

Service path:

```text
ONU → T-CONT → GEM Port → Service Port
→ VLAN/QinQ → Uplink → Aggregation → BNG/BRAS
```

## 4. Levels

| Level | Definition |
|---|---|
| L0 | Concept |
| L1 | Visual identification |
| L2 | Engineering structure |
| L3 | Operational twin |
| L4 | Operational decision twin |

Engineering-grade requires at least L2.

## 5. Workflow

1. Define purpose and target level.
2. Confirm vendor, exact model, revision and use.
3. Build an evidence register.
4. Create device template.
5. Create board/module/port libraries.
6. Build geometry with correct dimensions.
7. Create actual asset instance.
8. Map physical connections.
9. Map logical and service relationships.
10. Integrate telemetry and alarms.
11. Add history.
12. Add diagnosis and impact.
13. Test and accept.

## 6. Evidence Priority

| Priority | Evidence |
|---:|---|
| A | Vendor CAD/mechanical drawings/hardware manuals |
| B | Official panel photos, board manuals, MIB/CLI |
| C | Verified measurement, inventory, device output |
| D | Multiple public sources |
| E | Clearly labeled engineering inference |

Do not invent boards or ports.

## 7. Stable IDs

Example:

```text
site/wh01/room/a/rack/r03/chassis/olt001
/slot/01/board/gnoa01/pon/01
```

IDs must not change with language or display order.

## 8. Layer Separation

```text
GLB/glTF: geometry
Device Template JSON: supported structure and rules
Asset Instance: actual installed configuration
Telemetry/Alarm: operational state
Topology/Service Graph: network and business relations
```

## 9. Operational Data

| Object | Data |
|---|---|
| Device | reachability, CPU, memory, uptime |
| Board | presence, state, temperature, power, version |
| Fan | state, speed, level |
| Power | voltage, current, A/B feed |
| PON | admin/oper state, ONU count, traffic |
| ONU | state, offline reason, optical power, distance |
| Uplink | utilization, errors, drops |
| Alarm | severity, object, start, clear, acknowledge |

## 10. Data-state Labels

- Real-time
- Recent
- Stale
- Simulated
- Inferred
- Unknown

## 11. Views

At minimum:

- front orthographic;
- 3D perspective;
- side/top;
- exploded;
- physical topology;
- logical/service topology;
- alarm/health;
- temperature;
- power;
- capacity;
- history.

Use 2D orthographic views for precise port work.

## 12. Acceptance

### L2
- dimensions/proportions credible;
- slots and board rules correct;
- port quantity and placement correct;
- stable IDs;
- no invented facts;
- front/3D/exploded views usable.

### L3
- live or explicitly simulated data;
- state refresh;
- alarm/performance/temperature/power/capacity;
- history;
- time/source traceability;
- stale-data detection.

### L4
- bidirectional physical/logical queries;
- impact to ONU/customer/service;
- evidence-based diagnosis;
- confidence and alternatives;
- work order/change/maintenance linkage;
- approval, audit, rollback and verification.

## 13. Deliverables

1. Evidence register
2. Resource-model description
3. Board/module library
4. GLB/glTF
5. Device template JSON
6. Asset instance JSON
7. Port/connection mapping
8. Telemetry/alarm mapping
9. Service graph
10. Diagnosis scenarios
11. Test report
12. Acceptance report
13. Version/change record

## 14. GPT Behavior

- verify exact model first;
- state target and achieved level;
- prioritize official evidence;
- structure before visual polish;
- distinguish known, inferred and unknown;
- include physical and service paths;
- state integration and safety needs;
- never present a visual mock-up as a production twin.
