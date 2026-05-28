# ZISCSEEC_RPTFEAT
**Description:** EE&C report instance Features
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, REPORT_TY, ISSUE_NO, REP_FEAT_TY

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
| 6 | `SEQ` | INT4 | 10 |  | Natural number |
