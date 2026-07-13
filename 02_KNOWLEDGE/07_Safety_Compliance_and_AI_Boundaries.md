# Safety, Compliance and AI Boundaries

## 1. Purpose

Define production-network safety, data protection, authorization and AI-agent limits.

## 2. Sensitive Data

Do not request or expose passwords, SNMP community strings, API keys, private keys, VPN credentials, unredacted customer data or unauthorized communications content.

## 3. Production Change Control

Material changes require:

- authorization;
- impact scope;
- maintenance window;
- backup;
- tested procedure;
- rollback;
- responsible engineer;
- post-change verification;
- audit record.

## 4. High-risk Actions

Board reset, PON shutdown, bulk ONU changes, VLAN/QoS/ACL changes, firmware upgrade, master/standby switchover, routing/uplink changes and production scripts are not direct AI actions by default.

## 5. AI Output Boundary

AI output may contain uncertainty, hallucination, stale data or incorrect tool selection. It is advisory unless governed through an approved system.

## 6. SafeAction Sandbox

Before controlled execution, validate syntax, model/firmware compatibility, prerequisites, service impact, capacity, permissions and rollback.

## 7. Data Governance

Maintain tenant isolation, data minimization, encryption, access logs, source/time lineage and explicit real/simulated/inferred labels.

## 8. Unauthorized Activities

Do not help bypass licenses, access controls, vendor authorization or third-party networks.

## 9. GPT Behavior

When risk is material, prioritize safety and verification over completeness or speed.
