# ZISDMINSME
**Description:** Custome table for LPIS (INSMETER)
**Total Fields:** 6
**Key Fields:** MANDT, GERNR, VKONTO

## Programs Using This Table
- `zisdm0059`
- `zisdm0060`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `EINBDAT` | CHAR | 10 |  | Character Field Length = 10 |
| 5 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 6 | `RES_IND` | CHAR | 1 |  | Single-Character Flag |
