# Protocols and Management

## 1. Purpose

Explain and safely apply access-network management protocols and interfaces.

## 2. Protocol Roles

| Protocol | Main role |
|---|---|
| SNMP | monitoring, counters, alarms and inventory |
| CLI/SSH | detailed configuration and diagnosis |
| NETCONF/YANG | model-driven configuration and state |
| OMCI | OLT–ONU management and provisioning |
| TR-069/CWMP | CPE/ONU/HGU remote management through ACS |
| TR-369/USP | modern bidirectional multi-controller device management |
| Syslog | event and log transport |
| REST/API/Webhook | platform integration and automation |

## 3. Boundary

TR-069/TR-369 manage customer-premises functions; OMCI manages PON-side ONU entities. They are complementary, not interchangeable.

## 4. Integration Method

```text
Discover capabilities → authenticate securely → collect inventory/state
→ normalize semantics → validate data quality → control rate
→ audit access → separate read/write privileges
```

## 5. Multi-vendor Normalization

Map vendor fields to unified Resource, State, Alarm, Metric, Configuration, Topology and Action concepts.

## 6. Security

Do not expose credentials. Prefer secure protocols, least privilege, source restrictions, credential rotation, logging and tenant isolation.

## 7. No Unsupported Commands

Exact CLI, MIB/OID and firmware behavior require model/version evidence. Never guess production commands.

## 8. Digital Twin Link

Protocol data update the twin; the twin provides object identity, topology and context to interpret protocol data.
