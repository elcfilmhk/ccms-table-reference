# ZISDMADRCUSTACTP
**Description:** ADR Customer CA/Meter
**Total Fields:** 5
**Key Fields:** MANDT, DRCUSTNO, VKONTO, SERNR

## Programs Using This Table
- `ziscs0528`
- `ziscs_migration_contopt_mc3_5`
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0313_adr`
- `zisdm0314_adr`
- `zisdm0355`
- `zisdm0356`
- `zisfi0250`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `AUTOGRID` | CHAR | 1 |  | AutoGrid |
