# ZISDHCONTIGJOB
**Description:** MRHS Contingency Job Item list
**Total Fields:** 20
**Key Fields:** MANDT, ID, SERNR, ABLESGR, ABLBELNR, ADATTATS, ATIMTATS

## Programs Using This Table
- `zisdh0025`
- `zisdh0026`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ID` | NUMC | 10 | 🔑 | Incoming ID |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 5 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 6 | `ADATTATS` | DATS | 8 | 🔑 | Actual meter reading date |
| 7 | `ATIMTATS` | TIMS | 6 | 🔑 | Actual Meter Reading Time |
| 8 | `ZUSMIT` | CHAR | 8 |  | Meter reading together with allocated main MR unit |
| 9 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 10 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `ACCOUNTNO` | CHAR | 20 |  | Installation + MRU + Read Reason |
| 13 | `TARIFTYP` | CHAR | 2 |  | Rate Category in 2 Chars |
| 14 | `PORTION` | CHAR | 8 |  | Portion |
| 15 | `UTILITYCUST` | CHAR | 120 |  | Utility Customer Data |
| 16 | `UTILITYMETER` | CHAR | 80 |  | Utility Meter Data |
| 17 | `OC` | CHAR | 3 |  | Operation Centre |
| 18 | `PROCESSID` | NUMC | 5 |  | Job Process ID |
| 19 | `PROCESSSTATUS` | CHAR | 1 |  | Process status |
| 20 | `PROCESSMESSAGE` | CHAR | 100 |  | Process message |
