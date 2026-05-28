# ZISDMFSSORDERLOG
**Description:** FSS Download/Upload/Create orders log
**Total Fields:** 30
**Key Fields:** MANDT, ABLBELNR, AUFNR, CREATEDDATE, CREATEDTIME, TS, STEP, ITEM

## Programs Using This Table
- `zisdm0417`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 4 | `CREATEDDATE` | DATS | 8 | 🔑 | Date |
| 5 | `CREATEDTIME` | TIMS | 6 | 🔑 | Time |
| 6 | `TS` | DEC | 21 | 🔑 | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| 7 | `STEP` | CHAR | 5 | 🔑 | FSS Step |
| 8 | `ITEM` | NUMC | 3 | 🔑 | Number of Line Item Within Accounting Document |
| 9 | `AUART` | CHAR | 4 |  | Sales Document Type |
| 10 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 11 | `TPLNR` | CHAR | 30 |  | Functional Location |
| 12 | `GERNR` | CHAR | 18 |  | Serial Number |
| 13 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 14 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 15 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 16 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 17 | `GSTRP` | DATS | 8 |  | Basic Start Date |
| 18 | `GLTRP` | DATS | 8 |  | Basic finish date |
| 19 | `GSUZP` | TIMS | 6 |  | Basic Start (Time) |
| 20 | `GLUZP` | TIMS | 6 |  | Basic finish (time) |
| 21 | `GSTRS` | DATS | 8 |  | Scheduled start |
| 22 | `GLTRS` | DATS | 8 |  | Scheduled finish |
| 23 | `GLUZS` | TIMS | 6 |  | Scheduled Finish (Time) |
| 24 | `GSUZS` | TIMS | 6 |  | Scheduled Start (Time) |
| 25 | `LOG_PROG` | CHAR | 40 |  | The program which making the log record |
| 26 | `CALL_PROG` | CHAR | 40 |  | The program which it calls |
| 27 | `DIRECTION` | CHAR | 1 |  | FSS Order Dir (D=Download/U=Upload/C=Create) |
| 28 | `CREATED` | CHAR | 1 |  | Created |
| 29 | `SENTTOFSS` | CHAR | 1 |  | Sent to FSS |
| 30 | `MSG` | CHAR | 200 |  | FSS Message log |
