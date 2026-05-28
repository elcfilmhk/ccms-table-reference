# ZISBIPROGTRACK
**Description:** Table for Progress Tracking E-Letter
**Total Fields:** 28
**Key Fields:** MANDT, BUDAT, AUFNR, TYPE

## Programs Using This Table
- `zisbi0172`
- `zisbi0186`
- `ziscs0005`
- `ziscs0340`
- `ziscs0341`
- `ziscs0373`
- `ziscs0465`
- `ziscs0466`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 4 | `TYPE` | CHAR | 2 | 🔑 | Message Type |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 7 | `SMS` | CHAR | 255 |  | SMS |
| 8 | `EMAIL` | CHAR | 255 |  | Email Address |
| 9 | `EBILL_SENDER` | CHAR | 100 |  | Sender Address |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `APPOINT_DATE` | DATS | 8 |  | Appointment Date |
| 14 | `APPOINT_TIME_FR` | TIMS | 6 |  | Appointment Time From |
| 15 | `APPOINT_TIME_TO` | TIMS | 6 |  | Appointment Time To |
| 16 | `COMPLETE_DATE` | DATS | 8 |  | Complete Date |
| 17 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 18 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 19 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 20 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 21 | `STREET` | CHAR | 60 |  | Street |
| 22 | `ENGINEER_SURNAME` | CHAR | 40 |  | Engineer Surname |
| 23 | `ENGINEER_TEL` | CHAR | 30 |  | Engineer Telephone |
| 24 | `TENTATIVE_COMPLETION_DATE` | DATS | 8 |  | Tentative Completion Date |
| 25 | `OFFICER_TEL` | CHAR | 30 |  | Responsible Officer Business Phone Number |
| 26 | `MERGE` | CHAR | 1 |  | Merge indicator |
| 27 | `DESTINATION` | CHAR | 240 |  | Destination to send |
| 28 | `SEQNO` | NUMC | 3 |  | Sequence no. |
