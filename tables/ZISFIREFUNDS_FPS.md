# ZISFIREFUNDS_FPS
**Description:** Refund Summary
**Total Fields:** 12
**Key Fields:** MANDT, RDATE, REFD_STATUS, PAYTYPE, PROXY, CENTRE, DT_IND, AUTO_REFD_IND, FINAL_ACC_IND, SP_REBATE

## Programs Using This Table
- `zisfi0028`
- `zisfi0204`
- `zisfi0340`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RDATE` | DATS | 8 | 🔑 | Report Date |
| 3 | `REFD_STATUS` | CHAR | 1 | 🔑 | Refund Status |
| 4 | `PAYTYPE` | CHAR | 1 | 🔑 | Type of Payment |
| 5 | `PROXY` | CHAR | 15 | 🔑 | FPS Proxy |
| 6 | `CENTRE` | CHAR | 6 | 🔑 | Centre |
| 7 | `DT_IND` | CHAR | 1 | 🔑 | Domestic Indicator |
| 8 | `AUTO_REFD_IND` | CHAR | 1 | 🔑 | Auto Refund Indicator |
| 9 | `FINAL_ACC_IND` | CHAR | 1 | 🔑 | Final Account Indicator |
| 10 | `SP_REBATE` | CHAR | 1 | 🔑 | Special Rebate indicator |
| 11 | `NO_OF_CA` | INT4 | 10 |  | No. of CA |
| 12 | `REFD_AMT` | CURR | 15 |  | Refund Amount |
