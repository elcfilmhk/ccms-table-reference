# ZISCSEEC_RPTVAR
**Description:** EE&C Report Variables (name-value pairs)
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, REPORT_TY, ISSUE_NO, VAR_NAME, VAR_ARR_IDX

## Programs Using This Table
- `ziscs0390_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `REPORT_TY` | CHAR | 20 | 🔑 | Report Type |
| 4 | `ISSUE_NO` | CHAR | 20 | 🔑 | Report Issue No |
| 5 | `VAR_NAME` | CHAR | 50 | 🔑 | Parameter Name |
| 6 | `VAR_ARR_IDX` | INT2 | 5 | 🔑 | 2 byte integer (signed) |
| 7 | `VAR_VALUE_LO` | CHAR | 100 |  | Parameter Value |
| 8 | `VAR_VALUE_HI` | CHAR | 100 |  | Parameter Value |
