# ZISDMRCWITHCSMP
**Description:** Store RC w.o. with consump. over 500 units for print notific
**Total Fields:** 21
**Key Fields:** MANDT, RUNDATE, RC_ORDER_NO

## Programs Using This Table
- `zisbi0198`
- `ziscs0341`
- `ziscs0373`
- `zisdm0315`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Run Date |
| 3 | `RC_ORDER_NO` | CHAR | 12 | 🔑 | Order Number |
| 4 | `ANLAGE` | CHAR | 10 |  | Installation |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `AUSZBELEG` | CHAR | 12 |  | Consecutive number of move-out document |
| 7 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 8 | `VSTELLE` | CHAR | 10 |  | Premise |
| 9 | `CONSUMPTION` | DEC | 16 |  | Entry value (installed value) for a device |
| 10 | `PRINTINDC` | CHAR | 1 |  | Print Indicator |
| 11 | `LET_NOTICE` | CHAR | 1 |  | Set Y and |
| 12 | `STATUS` | CHAR | 12 |  | Retrieve order status |
| 13 | `RPT_GENERATED` | CHAR | 1 |  | Report Generated |
| 14 | `NOTIFY_EMAIL_SENT` | CHAR | 1 |  | Notification Email Sent |
| 15 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 16 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 17 | `CREATIONTIME` | TIMS | 6 |  | Entry time |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 20 | `LASTMODIFYTIME` | TIMS | 6 |  | Time last change was made |
| 21 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
