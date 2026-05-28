# ZISCSAPIEXCLDTL
**Description:** Appointment punctuality exclusion details
**Total Fields:** 20
**Key Fields:** MANDT, REPORT_YEAR, REPORT_PERIOD, CODE_ID, SERVICE_ORDER, APPT_DATE, APPT_START_TIME

## Programs Using This Table
- `ziscs0228`
- `ziscs0268`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_YEAR` | NUMC | 4 | 🔑 | Reporting year |
| 3 | `REPORT_PERIOD` | NUMC | 2 | 🔑 | Report Period |
| 4 | `CODE_ID` | CHAR | 4 | 🔑 | Activity Code |
| 5 | `SERVICE_ORDER` | CHAR | 12 | 🔑 | Order Number |
| 6 | `APPT_DATE` | DATS | 8 | 🔑 | Start Date |
| 7 | `APPT_START_TIME` | TIMS | 6 | 🔑 | Start Time of Activity |
| 8 | `APPT_END_TIME` | TIMS | 6 |  | End Time of Activity |
| 9 | `APPT_ARRIVAL_TIM` | TIMS | 6 |  | Time, at Which Record Was Added |
| 10 | `ADDR_ST3` | CHAR | 40 |  | Street 3 |
| 11 | `ADDR_ST` | CHAR | 60 |  | Street |
| 12 | `ADDR_HSE` | CHAR | 10 |  | House Number |
| 13 | `ADDR_ST2` | CHAR | 40 |  | Street 2 |
| 14 | `ADDR_DIST` | CHAR | 40 |  | District |
| 15 | `ADDR_REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 16 | `EXPLAIN1` | CHAR | 240 |  | Explanation of exclusion |
| 17 | `EXPLAIN2` | CHAR | 240 |  | Explanation of exclusion |
| 18 | `UPDATE_DATE` | DATS | 8 |  | Date of Last Change |
| 19 | `UPDATE_TIME` | TIMS | 6 |  | Time of Change |
| 20 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
