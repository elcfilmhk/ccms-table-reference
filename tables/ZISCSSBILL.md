# ZISCSSBILL
**Description:** Receive Small Hardcopy Bill
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `ziscs0264`
- `ziscs0735`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `RECSBILL` | CHAR | 1 |  | Receive Small Bill |
| 5 | `LAST_USER` | CHAR | 12 |  | Last Changed By |
| 6 | `LAST_CHG` | DATS | 8 |  | Last Changed On |
| 7 | `LAST_CHG_TIME` | TIMS | 6 |  | Last changed at |
