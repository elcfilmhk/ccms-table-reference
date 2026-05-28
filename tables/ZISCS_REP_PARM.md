# ZISCS_REP_PARM
**Description:** Log Report access - Input Parameters
**Total Fields:** 11
**Key Fields:** MANDT, REPORT_NAME, RUN_DT, RUN_USER, SELNAME, SEQ

## Programs Using This Table
- `ziscs0842`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_NAME` | CHAR | 40 | 🔑 | Report Name |
| 3 | `RUN_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `RUN_USER` | CHAR | 12 | 🔑 | User Name |
| 5 | `SELNAME` | CHAR | 8 | 🔑 | ABAP: Name of SELECT-OPTION/PARAMETER |
| 6 | `SEQ` | INT4 | 10 | 🔑 | Natural number |
| 7 | `KIND` | CHAR | 1 |  | ABAP: Type of selection |
| 8 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 9 | `OP` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 10 | `LOW` | CHAR | 255 |  | Selection Variants: Field Content (LOW/HIGH) |
| 11 | `HIGH` | CHAR | 255 |  | Selection Variants: Field Content (LOW/HIGH) |
