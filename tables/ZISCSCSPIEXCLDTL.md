# ZISCSCSPIEXCLDTL
**Description:** Connection & Supply Performance Exclusion Details
**Total Fields:** 18
**Key Fields:** MANDT, REPORT_YEAR, REPORT_PERIOD, CODE_ID, SERVICE_ORDER, APPT_DATE, APPT_COMP_DATE

## Programs Using This Table
- `ziscs0229`
- `ziscs0269`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_YEAR` | NUMC | 4 | 🔑 | Reporting year |
| 3 | `REPORT_PERIOD` | NUMC | 2 | 🔑 | Report Period |
| 4 | `CODE_ID` | CHAR | 4 | 🔑 | Activity Code |
| 5 | `SERVICE_ORDER` | CHAR | 12 | 🔑 | Order Number |
| 6 | `APPT_DATE` | DATS | 8 | 🔑 | Start Date |
| 7 | `APPT_COMP_DATE` | DATS | 8 | 🔑 | Completion date |
| 8 | `ADDR_ST3` | CHAR | 40 |  | Street 3 |
| 9 | `ADDR_ST` | CHAR | 60 |  | Street |
| 10 | `ADDR_HSE` | CHAR | 10 |  | House Number |
| 11 | `ADDR_ST2` | CHAR | 40 |  | Street 2 |
| 12 | `ADDR_DIST` | CHAR | 40 |  | District |
| 13 | `ADDR_REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 14 | `EXPLAIN1` | CHAR | 240 |  | Explanation of exclusion |
| 15 | `EXPLAIN2` | CHAR | 240 |  | Explanation of exclusion |
| 16 | `UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 17 | `UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 18 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
