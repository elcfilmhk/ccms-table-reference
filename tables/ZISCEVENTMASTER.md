# ZISCEVENTMASTER
**Description:** To store Event Master Data Details
**Total Fields:** 13
**Key Fields:** MANDT, EVENT_ID, PROGRAM_ID

## Programs Using This Table
- `ziscs_migration_account_notif`
- `ziscs_migration_contopt_mc3_5`
- `ziscs_migration_contractoption`
- `zisdm0368`
- `zisfi0250`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENT_ID` | CHAR | 50 | 🔑 | Event ID from Autogrid |
| 3 | `PROGRAM_ID` | CHAR | 10 | 🔑 | Program ID |
| 4 | `STATUS` | CHAR | 15 |  | Event Status |
| 5 | `EVENT_DATE` | DATS | 8 |  | DR Event Date |
| 6 | `EVENT_ST_TIME` | TIMS | 6 |  | Event Start Time |
| 7 | `EVENT_EN_TIME` | TIMS | 6 |  | End Time of the Event |
| 8 | `EVENT_DURATION` | NUMC | 4 |  | Event Duration |
| 9 | `DURATION_UNIT` | CHAR | 5 |  | Duration Unit |
| 10 | `CREATED_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `CREATED_AT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 12 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 13 | `CHANGED_AT` | TIMS | 6 |  | Time last change was made |
