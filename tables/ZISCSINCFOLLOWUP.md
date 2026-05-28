# ZISCSINCFOLLOWUP
**Description:** Incentive DR Folluw Up
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, PROMO

## Programs Using This Table
- `ziscs0210`
- `zisfi0168`
- `zisfi0169`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PROMO` | CHAR | 20 | 🔑 | Promotion name |
| 4 | `DRAMT` | CURR | 13 |  | Debit Amount |
| 5 | `NOTFYDAT` | DATS | 8 |  | Notification Date |
| 6 | `PLANDAT` | DATS | 8 |  | Planned Follow Up  Date |
| 7 | `ACTDAT` | DATS | 8 |  | Actual Follow Up  Date |
| 8 | `OPBEL` | CHAR | 12 |  | DR Document No. |
| 9 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
