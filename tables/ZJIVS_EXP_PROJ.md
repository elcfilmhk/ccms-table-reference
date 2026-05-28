# ZJIVS_EXP_PROJ
**Description:** JiVS Job Dispatcher migration tables
**Total Fields:** 16
**Key Fields:** PROJ_NAME, MIGOBJ

## Programs Using This Table
- `zcl_jivs_project_util`
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROJ_NAME` | CHAR | 20 | 🔑 | JiVS DT Export Project name |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `TYPE` | CHAR | 10 |  | JiVS Export Project Type Data element |
| 4 | `MANDT` | CLNT | 3 |  | Client |
| 5 | `CREATE_DATE` | DATS | 8 |  | (8-character) Date for SYST |
| 6 | `CREATE_TIME` | TIMS | 6 |  | Local Time |
| 7 | `CREATE_USER` | CHAR | 12 |  | User Name |
| 8 | `CHANGE_DATE` | DATS | 8 |  | (8-character) Date for SYST |
| 9 | `CHANGE_TIME` | TIMS | 6 |  | Local Time |
| 10 | `CHANGE_USER` | CHAR | 12 |  | User Name |
| 11 | `STATUS` | CHAR | 1 |  | JiVS Export Project Status |
| 12 | `LAST_RUN` | DATS | 8 |  | (8-character) Date for SYST |
| 13 | `CASE_ID` | INT4 | 10 |  | JiVS DT OCC CASE ID |
| 14 | `OCC_SYSTEM_ID` | INT4 | 10 |  | JiVS DT OCC SYSTEM ID |
| 15 | `RUN_ID` | INT4 | 10 |  | &nbsp; |
| 16 | `CUSTOMER_ID` | INT4 | 10 |  | JiVS DT OCC CUSTOMER ID |
