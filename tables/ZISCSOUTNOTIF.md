# ZISCSOUTNOTIF
**Description:** Planned Outage Notification
**Total Fields:** 15
**Key Fields:** MANDT, ORDER_ID, DEENERG_ID, PROREQ_ID, INCIDENT_ID, CONTRACT_NUM, PREMISE_NUM, ERDAT, ERZEIT

## Programs Using This Table
- `ziscs0125`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ORDER_ID` | CHAR | 24 | 🔑 | Order ID |
| 3 | `DEENERG_ID` | CHAR | 11 | 🔑 | De-Energisation ID |
| 4 | `PROREQ_ID` | CHAR | 10 | 🔑 | Project/Request ID |
| 5 | `INCIDENT_ID` | CHAR | 10 | 🔑 | Incident ID |
| 6 | `CONTRACT_NUM` | CHAR | 10 | 🔑 | Contract |
| 7 | `PREMISE_NUM` | CHAR | 10 | 🔑 | Premise |
| 8 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 9 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 10 | `JOB_STATUS` | CHAR | 10 |  | Job status |
| 11 | `NOTIF_TYPE` | CHAR | 10 |  | Notification type |
| 12 | `START_DATE` | DATS | 8 |  | Date |
| 13 | `START_TIME` | TIMS | 6 |  | Time |
| 14 | `END_DATE` | DATS | 8 |  | Date |
| 15 | `END_TIME` | TIMS | 6 |  | Time |
