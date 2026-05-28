# ZISCS_REP
**Description:** Log report access
**Total Fields:** 8
**Key Fields:** MANDT, REPORT_NAME, RUN_DT, RUN_USER

## Programs Using This Table
- `ziscs0841`
- `ziscs0842`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_NAME` | CHAR | 40 | 🔑 | Report Name |
| 3 | `RUN_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `RUN_USER` | CHAR | 12 | 🔑 | User Name |
| 5 | `RUN_USER_DEPT` | CHAR | 40 |  | Department |
| 6 | `RUN_USER_DESIGNATION` | CHAR | 40 |  | Function |
| 7 | `END_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `END_STATUS` | CHAR | 1 |  | Result: S:Success, F:Failure |
