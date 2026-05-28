# ZISCSOVERDUE
**Description:** Overdue Bill Alert Table
**Total Fields:** 12
**Key Fields:** MANDT, GPART, VKONT, CALL_DATE, CALL_TIME, USER_ID

## Programs Using This Table
- `zaccount`
- `zisfi0107`
- `zisfi0352`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CALL_DATE` | DATS | 8 | 🔑 | Date |
| 5 | `CALL_TIME` | TIMS | 6 | 🔑 | Time |
| 6 | `USER_ID` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
| 7 | `ALERT_MSG` | CHAR | 1 |  | Alert msg code |
| 8 | `CHANNEL` | CHAR | 20 |  | Channel |
| 9 | `TOTAL_BAL` | DEC | 23 |  | Amount in Transaction Currency with +/- Sign |
| 10 | `DUNNING_LEVEL` | NUMC | 2 |  | Dunning Level |
| 11 | `OVERDUE_BAL` | DEC | 23 |  | Dunned amount in transaction currency |
| 12 | `DUE_DATE` | DATS | 8 |  | Due date for net payment |
