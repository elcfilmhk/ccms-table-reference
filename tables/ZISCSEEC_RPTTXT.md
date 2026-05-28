# ZISCSEEC_RPTTXT
**Description:** Texts used in EE&C report instances
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, REPORT_TY, ISSUE_NO, REP_FEAT_TY, ID_KEY

## Programs Using This Table
- `ziscs0390_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `REPORT_TY` | CHAR | 20 | 🔑 | Report Type |
| 4 | `ISSUE_NO` | CHAR | 20 | 🔑 | Report Issue No |
| 5 | `REP_FEAT_TY` | CHAR | 30 | 🔑 | Report Feature Type |
| 6 | `ID_KEY` | INT4 | 10 | 🔑 | Natural number |
| 7 | `SEQ` | INT4 | 10 |  | Natural number |
| 8 | `TXT_ID` | CHAR | 100 |  | Text ID |
