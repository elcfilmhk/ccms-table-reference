# ZISCSAPIDATA
**Description:** Appointment punctuality data
**Total Fields:** 24
**Key Fields:** MANDT, REPORT_YEAR, REPORT_PERIOD

## Programs Using This Table
- `ziscs0228`
- `ziscs0268`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_YEAR` | NUMC | 4 | 🔑 | Reporting year |
| 3 | `REPORT_PERIOD` | NUMC | 2 | 🔑 | Report Period |
| 4 | `REPORT_FROM` | DATS | 8 |  | Report from date |
| 5 | `REPORT_TO` | DATS | 8 |  | Report to date |
| 6 | `API` | DEC | 6 |  | Appointment Punctuality Index (API) |
| 7 | `TOTAL_NO_OF_APPT` | NUMC | 6 |  | Total No.of appointment |
| 8 | `NO_WITHIN_TMSLOT` | NUMC | 6 |  | No.of appointment within time slot |
| 9 | `NO_OF_EXCLUSION` | NUMC | 6 |  | No.of exclusion |
| 10 | `NO_APWC` | NUMC | 6 |  | No.of exclusion - cancel by customer |
| 11 | `NO_SEWE` | NUMC | 6 |  | No.of exclusion - severe weather conditions |
| 12 | `NO_INDA` | NUMC | 6 |  | No.of exclusion - industrial action |
| 13 | `NO_DEFB` | NUMC | 6 |  | No.of exclusion - act of default |
| 14 | `NO_UCOR` | NUMC | 6 |  | No.of exclusion - other |
| 15 | `GENERARTION_FLAG` | CHAR | 1 |  | Report generation flag |
| 16 | `RERUN_DATE` | DATS | 8 |  | Re-run date |
| 17 | `RERUN_TIME` | TIMS | 6 |  | Re-run time |
| 18 | `RERUN_BY` | CHAR | 12 |  | Re-run by |
| 19 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 20 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
| 21 | `CREATE_BY` | CHAR | 12 |  | Created By |
| 22 | `UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 23 | `UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 24 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
