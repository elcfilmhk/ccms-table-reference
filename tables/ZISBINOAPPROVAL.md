# ZISBINOAPPROVAL
**Description:** Adjusted Print document without approval
**Total Fields:** 6
**Key Fields:** MANDT, BYPASS_TYPE, BELNR, OPBEL

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`
- `zisbi0086`
- `zisbi0175`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BYPASS_TYPE` | CHAR | 1 | 🔑 | Bypass Type |
| 3 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 4 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
