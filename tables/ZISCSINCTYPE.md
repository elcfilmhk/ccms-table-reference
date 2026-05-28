# ZISCSINCTYPE
**Description:** Incentive Type
**Total Fields:** 9
**Key Fields:** MANDT, ICTTY

## Programs Using This Table
- `ziscs0164`
- `ziscs0174`
- `ziscs0205`
- `ziscs0210`
- `ziscs0226`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ICTTY` | CHAR | 15 | 🔑 | Incentive Type |
| 3 | `ICTDS` | CHAR | 50 |  | Description |
| 4 | `CLLCT` | CHAR | 1 |  | Can be collected at CSC |
| 5 | `VLDFR` | DATS | 8 |  | Valid From |
| 6 | `VLDTO` | DATS | 8 |  | Valid To |
| 7 | `INCGR` | CHAR | 1 |  | Incentive group |
| 8 | `SONLY` | CHAR | 1 |  | Sel only |
| 9 | `PRICE` | CURR | 13 |  | Incentive Unit Price |
