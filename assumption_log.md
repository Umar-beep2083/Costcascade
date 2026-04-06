# Tariff Shock Propagation Simulator — Assumption Log

## Parameter Defaults and Sources

| Parameter | Symbol | Default | Range | Source | Confidence |
|---|---|---|---|---|---|
| US chip tariff increase | T | 25% | 0%–50% | US ITC HTS Chapter 85 (codes 8542, 8534, 8471) | High |
| Component cost ratio | C | 47% | 40%–55% | Industry analyst consensus (semiconductor content as % of electronics manufacturing cost) | Medium |
| Base terminal cost (USD) | B | $250 | $150–$400 | Verifone/Ingenico investor materials and industry analyst estimates | Medium |
| Local assembly % | L | 5% | 0%–100% | Stated assumption — Pakistan has minimal domestic POS terminal assembly | Low |
| Pakistan import duty | D_import | 15% | 10%–20% | FBR general electronics duty band (HS codes 8470–8473). Specific POS terminal rate not confirmed. | Low |
| Deployment overhead ratio | D_deploy | 30% | Fixed | Stated assumption — covers installation, training, connectivity per merchant | Low |
| Fintech subsidy rate | S | 50% | 0%–100% | Stated assumption — fintechs typically subsidize merchant hardware to drive adoption | Low |

## Data Gaps Addressed

**Gap 1: Per-unit POS import cost for Pakistan**
No public Pakistani source disaggregates this. Used the global $150–$400 range from Verifone/Ingenico materials. Default $250.

**Gap 2: POS terminal import duty (Pakistan FBR)**
The specific HS code may not return a clean duty rate from a basic FBR search. Used the general 10–20% band for consumer electronics. Default 15%.

**Gap 3: Component cost breakdown inside a POS terminal**
No public source disaggregates this. Used industry analyst consensus: semiconductor content is 40–55% of electronic device manufacturing cost. Default 47% (midpoint).

## Market Context
- Pakistan POS terminal count: 195,849 (SBP Payment Systems Review FY25)
- Relevant HTS codes: 8542 (integrated circuits), 8534 (printed circuits), 8471 (data processing machines)
