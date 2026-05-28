# ZISMDSLAMROCALIN
**Description:** MRO for SLA calculation indicator for MB,LR
**Total Fields:** 4
**Key Fields:** MANDT, ABRVORG

## Programs Using This Table
- `zised0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABRVORG` | CHAR | 2 | 🔑 | Billing Transaction for SLA calculation |
| 3 | `INDVALUE` | CHAR | 1 |  | Indicator Value |
| 4 | `ABRVORGTEXT` | CHAR | 150 |  | Billing Transaction for SLA text |
