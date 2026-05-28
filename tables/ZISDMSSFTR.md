# ZISDMSSFTR
**Description:** Customerized table for seasonal factor
**Total Fields:** 4
**Key Fields:** MANDT, KTOKL, ZZMONTH

## Programs Using This Table
- `zisdm0067`
- `zisdm0068`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KTOKL` | CHAR | 4 | 🔑 | Account class |
| 3 | `ZZMONTH` | NUMC | 2 | 🔑 | Month |
| 4 | `ZZSEALFACT` | DEC | 6 |  | Seasonal factor |
