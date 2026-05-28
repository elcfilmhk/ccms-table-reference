# ZISCS_COL_SEL
**Description:** Search help for picking output report columns
**Total Fields:** 10
**Key Fields:** MANDT, REPORT_NAME, COL_NAME

## Programs Using This Table
- `ziscs0151`
- `ziscs0841`
- `ziscs0842`
- `ziscs_col_sel_get_columns=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_NAME` | CHAR | 40 | 🔑 | Report Name |
| 3 | `COL_NAME` | CHAR | 30 | 🔑 | Field Name |
| 4 | `COL_LABEL` | CHAR | 100 |  | Column Label |
| 5 | `COL_SEQ` | INT2 | 5 |  | Sequence |
| 6 | `SENSITIVE_DATA` | INT2 | 5 |  | Column is Sensitive Data (0: not; Higher = more sensitive) |
| 7 | `COL_SELECTABLE` | CHAR | 1 |  | Column is selectable in search help |
| 8 | `COL_OUTPUTABLE` | CHAR | 1 |  | Column is available for output |
| 9 | `COL_GROUP` | CHAR | 30 |  | Column Group |
| 10 | `GROUP_HEAD` | CHAR | 1 |  | All Columns of Group |
