# ZISBIHILONOTIF
**Description:** Hi-Lo Complaint Notification Table
**Total Fields:** 20
**Key Fields:** MANDT, BUDAT, AUFNR, TYPE

## Programs Using This Table
- `zisbi0183`
- `zisbi0185`
- `ziscs0462`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 4 | `TYPE` | CHAR | 2 | 🔑 | Message Type |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `ORD_ERNAM` | CHAR | 12 |  | Order Created by |
| 8 | `ORD_ERDAT` | DATS | 8 |  | Order Created on |
| 9 | `EBILL_SENDER` | CHAR | 50 |  | Email sender address name |
| 10 | `EMAIL_ADDRESS` | CHAR | 50 |  | EBill email 1 |
| 11 | `SMS_NO` | CHAR | 30 |  | Mobile No |
| 12 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 15 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `CHANNEL` | CHAR | 30 |  | Channel |
| 17 | `INSTRU_CODE` | CHAR | 1 |  | Instruction Code |
| 18 | `REMARK` | CHAR | 20 |  | Remark |
| 19 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 20 | `PRINT_TIME` | TIMS | 6 |  | System Time |
