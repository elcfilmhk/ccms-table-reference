# ZISCRMMYWSMRPT
**Description:** Meter Online Monthly Summary
**Total Fields:** 5
**Key Fields:** MANDT, REP_YEAR, REP_MONTH, REP_TYPE

## Programs Using This Table
- `ziscrm0021`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REP_YEAR` | NUMC | 4 | 🔑 | Reporting year of the summary |
| 3 | `REP_MONTH` | NUMC | 2 | 🔑 | Reporting month of the summary |
| 4 | `REP_TYPE` | CHAR | 1 | 🔑 | Type of the data |
| 5 | `REP_VALUE` | CURR | 13 |  | Value of the entries |
