# Network Planning

## 1. Purpose

Guide FTTH/FTTx planning, technology selection, capacity estimation, ODN architecture, optical budget, expansion and economics.

## 2. Planning Inputs

- target homes passed and active subscribers;
- take rate and growth;
- geography and density;
- service tiers and peak traffic;
- GPON/XGS-PON/Combo/50G PON route;
- split ratio and optical budget;
- OLT locations, uplinks and resilience;
- CAPEX/OPEX and operational capability.

## 3. Standard Workflow

```text
Demand forecast → service target → technology route
→ OLT/PON capacity → ODN structure → optical budget
→ uplink/core capacity → phased deployment → economics → risk
```

## 4. Capacity Rules

Separate theoretical registration capacity, engineered capacity and commercial capacity. Do not plan to the theoretical maximum without considering bandwidth, optical margin, fault domains and growth.

## 5. Optical Budget

Calculate transmitter power, receiver sensitivity, fiber attenuation, connector/splice loss, splitter loss, engineering margin and aging margin. Use the exact class and vendor parameters when available.

## 6. Technology Choice

- GPON: best current cost-performance for many small ISPs and mass-market broadband;
- XGS-PON: high-ARPU, enterprise, symmetric and competitive markets;
- Combo PON: coexistence and staged migration;
- 50G PON: strategic/advanced scenarios, not automatically the best small-ISP choice.

## 7. Output

Include assumptions, capacity, port count, split architecture, optical margin, uplink, phases, cost/risk and triggers for upgrade.

## 8. Digital Twin Link

Planning data should become the initial twin baseline: sites, OLTs, ports, ODF, cables, splitters, ONU capacity and expected services.

## 9. GPT Behavior

Never provide precise port counts without stated assumptions. Use scenario ranges when customer data are incomplete.
