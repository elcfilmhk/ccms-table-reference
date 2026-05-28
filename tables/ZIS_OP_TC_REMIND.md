# ZIS_OP_TC_REMIND
**Description:** Sending Alert emails for missing documents
**Total Fields:** 11
**Key Fields:** MANDT, RE_APP_NO, AUFNR, DOC_TYPE, ACT_CODE, REM_NO

## Programs Using This Table
- `ziscs0209`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 4 | `DOC_TYPE` | CHAR | 3 | 🔑 | Reminder document type |
| 5 | `ACT_CODE` | CHAR | 25 | 🔑 | Activity code |
| 6 | `REM_NO` | NUMC | 1 | 🔑 | Number of reminders to CSSB colleagues |
| 7 | `STATUS` | CHAR | 1 |  | Reminder Status (OPSC Acitivity code) |
| 8 | `DUE_DATE` | DATS | 8 |  | Due date of submit document |
| 9 | `REGION` | CHAR | 10 |  | Region |
| 10 | `VAPLZ` | CHAR | 8 |  | Main work center for maintenance tasks |
| 11 | `MESSAGE` | CHAR | 255 |  | Reminder Message Text |
