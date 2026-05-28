# ZISDMHISTW
**Description:** Customerized table for Historical Weighting
**Total Fields:** 3
**Key Fields:** MANDT, STAGRUVER

## Programs Using This Table
- `zisdm0067`
- `zisdm0068`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `STAGRUVER` | CHAR | 2 | 🔑 | Statistics group for contract |
| 3 | `ZZHWFACTOR` | DEC | 4 |  | Factor for Historical Weighting |
