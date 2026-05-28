# ZISSDRBTRVSLHIST
**Description:** Rebate Reversal History Table
**Total Fields:** 4
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zissd00105`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
