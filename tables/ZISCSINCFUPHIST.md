# ZISCSINCFUPHIST
**Description:** Incentive Folluw Up History
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, PROMO

## Programs Using This Table
- `ziscs0210`
- `ziscs0212`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PROMO` | CHAR | 20 | 🔑 | Promotion name |
| 4 | `EFF_DATE` | DATS | 8 |  | Autopay/Ebill Effective Date |
| 5 | `CANCEL_DATE` | DATS | 8 |  | Autopay/Ebill Cancelled Date |
| 6 | `EFF_DURATION` | NUMC | 8 |  | Effective Duration Days |
| 7 | `CANCEL_USER` | CHAR | 12 |  | Cancelled by User ID |
| 8 | `ICTTY` | CHAR | 15 |  | Incentive Type |
| 9 | `DRAMT` | CURR | 13 |  | Debit Amount |
| 10 | `ISDAT` | DATS | 8 |  | Date of Issue |
| 11 | `CRDAT` | DATS | 8 |  | Creation date |
