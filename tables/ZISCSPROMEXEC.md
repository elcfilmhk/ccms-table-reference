# ZISCSPROMEXEC
**Description:** Promotion execution
**Total Fields:** 11
**Key Fields:** MANDT, PROMONAME, VKONT, PROMONUMBER

## Programs Using This Table
- `ziscs0164`
- `ziscs0175`
- `zissd00076`
- `zpromotion`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMONAME` | CHAR | 10 | 🔑 | Promotion activity name |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `PROMONUMBER` | CHAR | 12 | 🔑 | Promotion number |
| 5 | `PROMSTARTDATE` | DATS | 8 |  | Start date of promotion |
| 6 | `PROMSTARTTIME` | TIMS | 6 |  | Start time of promotion |
| 7 | `PROMENDDATE` | DATS | 8 |  | End date of promotion |
| 8 | `PROMENDTIME` | TIMS | 6 |  | End time of promotion |
| 9 | `PROMORESULT` | CHAR | 1 |  | Result |
| 10 | `PROMREJECT` | CHAR | 1 |  | Reject reason code |
| 11 | `PROMOUSER` | CHAR | 12 |  | Responsible person user ID |
