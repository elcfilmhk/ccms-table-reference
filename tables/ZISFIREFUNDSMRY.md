# ZISFIREFUNDSMRY
**Description:** Refund Summary
**Total Fields:** 11
**Key Fields:** MANDT, RDATE, REFD_STATUS, PAYTYPE, CENTRE, DT_IND, AUTO_REFD_IND, FINAL_ACC_IND, SP_REBATE

## Programs Using This Table
- `zisfi0028`
- `zisfi0204`
- `zisfi0205`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RDATE` | DATS | 8 | 🔑 | Report Date |
| 3 | `REFD_STATUS` | CHAR | 1 | 🔑 | Refund Status |
| 4 | `PAYTYPE` | CHAR | 1 | 🔑 | Type of Payment |
| 5 | `CENTRE` | CHAR | 6 | 🔑 | Centre |
| 6 | `DT_IND` | CHAR | 1 | 🔑 | Domestic Indicator |
| 7 | `AUTO_REFD_IND` | CHAR | 1 | 🔑 | Auto Refund Indicator |
| 8 | `FINAL_ACC_IND` | CHAR | 1 | 🔑 | Final Account Indicator |
| 9 | `SP_REBATE` | CHAR | 1 | 🔑 | Special Rebate indicator |
| 10 | `NO_OF_CA` | INT4 | 10 |  | No. of CA |
| 11 | `REFD_AMT` | CURR | 15 |  | Refund Amount |
