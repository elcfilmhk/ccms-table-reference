# ZISCSTRIFTYP
**Description:** Mapping table for Tariff type from CCMS
**Total Fields:** 5
**Key Fields:** MANDT, RATECAT, TARIF, SUBTARIF

## Programs Using This Table
- `ziscs0019`
- `zisdm0039`
- `zisfi0027`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RATECAT` | CHAR | 10 | 🔑 | Rate category |
| 3 | `TARIF` | CHAR | 1 | 🔑 | Tariff type |
| 4 | `SUBTARIF` | CHAR | 1 | 🔑 | Sub-tariff type |
| 5 | `AKLASSE` | CHAR | 4 |  | Billing class |
