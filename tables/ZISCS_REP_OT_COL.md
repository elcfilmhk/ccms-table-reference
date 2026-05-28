# ZISCS_REP_OT_COL
**Description:** Log Report access - Output screen/files Columns
**Total Fields:** 8
**Key Fields:** MANDT, REPORT_NAME, RUN_DT, RUN_USER, OUT_FILE_SEQ, COL_NAME

## Programs Using This Table
- `ziscs0842`
- `ziscs_rep_log_exec============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_NAME` | CHAR | 40 | 🔑 | Report Name |
| 3 | `RUN_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `RUN_USER` | CHAR | 12 | 🔑 | User Name |
| 5 | `OUT_FILE_SEQ` | INT4 | 10 | 🔑 | Natural number |
| 6 | `COL_NAME` | CHAR | 30 | 🔑 | Field Name |
| 7 | `SENSITIVE_DATA` | INT2 | 5 |  | Column is Sensitive Data (0: not; Higher = more sensitive) |
| 8 | `COL_SEQ` | INT2 | 5 |  | Sequence |
