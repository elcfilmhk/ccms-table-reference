# ZISDMHISME
**Description:** Custome table for LPIS (HISMETER)
**Total Fields:** 10
**Key Fields:** MANDT, GERNR, VKONTO, ADAT

## Programs Using This Table
- `zisdm0059`
- `zisdm0060`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ADAT` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 5 | `PREV_ADAT` | CHAR | 10 |  | Character Field Length = 10 |
| 6 | `ON_KVA` | CHAR | 9 |  | Character field of 9 digits |
| 7 | `OFF_KVA` | CHAR | 9 |  | Character field of 9 digits |
| 8 | `ON_KWH` | CHAR | 9 |  | Character field of 9 digits |
| 9 | `OFF_KWH` | CHAR | 9 |  | Character field of 9 digits |
| 10 | `TOT_KWH` | CHAR | 9 |  | Character field of 9 digits |
