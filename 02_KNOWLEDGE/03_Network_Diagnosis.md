# Network Diagnosis

## 1. Purpose

Provide hypothesis-driven diagnosis for access-network faults and customer-service failures.

## 2. Core Principle

The objective is not to list every possible cause; it is to narrow the fault domain and restore service safely.

## 3. Standard Workflow

```text
Symptom → affected scope → timeline → recent change
→ high-probability hypotheses → evidence collection
→ layer isolation → likely root cause → action → verification
```

## 4. Fault Domains

- OLT/chassis/board/PON port;
- ODN feeder, connector, splice, splitter and drop cable;
- ONU power, hardware, firmware and OMCI;
- VLAN, T-CONT, GEM Port and service profile;
- PPPoE, DHCP, RADIUS, DNS and upstream;
- CPE/LAN/Wi-Fi and customer environment.

## 5. Scope Logic

- one ONU affected: ONU, power, drop cable, connector or customer side;
- multiple ONUs on one PON: PON port, feeder, splitter or common configuration;
- multiple PONs/board: board, power, control or uplink;
- ONU online but service down: logical/service layer rather than optical registration.

## 6. Evidence

Use alarm/event types, optical-power trend, uptime, offline reason, peer comparison, traffic, errors, configuration, time correlation and recent changes.

## 7. TwinGraph Diagnosis

Trace:

```text
alarm/metric → object → upstream/downstream dependencies
→ shared fault domain → affected ONU/customer/service
```

## 8. Output Standard

Conclusion, evidence, causal path, confidence, alternatives, missing data, impact, action and verification.

## 9. Safety

Do not reset boards, shut PON ports, bulk-reconfigure ONUs or change production VLANs without impact assessment, authorization, backup and rollback.
