# ZISSDRBSINTREB
**Description:** Bonus Scheme V Intermediary Rebate Details
**Total Fields:** 10
**Key Fields:** MANDT, INT_SCH, INT_MAT_TYPE, INT_FM_HOLD, INT_TO_HOLD, TODATE

## Programs Using This Table
- `zissd00109`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INT_SCH` | CHAR | 20 | 🔑 | EWH / IC |
| 3 | `INT_MAT_TYPE` | CHAR | 20 | 🔑 | Intermediary Material Type |
| 4 | `INT_FM_HOLD` | DEC | 13 | 🔑 | Threshold From |
| 5 | `INT_TO_HOLD` | DEC | 13 | 🔑 | Threshold To |
| 6 | `TODATE` | DATS | 8 | 🔑 | Valid To Date |
| 7 | `FMDATE` | DATS | 8 |  | Valid From Date |
| 8 | `INT_MAT_TY_DESC` | CHAR | 20 |  | Intermediary Material Type Description |
| 9 | `INT_MAT` | CHAR | 18 |  | Material Number |
| 10 | `INT_REBATE_PRICE` | CURR | 11 |  | Rate (condition amount or percentage) where no scale exists |
