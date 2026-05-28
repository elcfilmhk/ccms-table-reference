# ZISBIAMIPAPER
**Description:** AMI Paper report printing
**Total Fields:** 17
**Key Fields:** MANDT, BUDAT, VKONT, OPBEL

## Programs Using This Table
- `zisbi0164`
- `zisbi0165`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 5 | `AMIGROUP` | CHAR | 2 |  | Note |
| 6 | `VERTRAG` | CHAR | 10 |  | Contract |
| 7 | `ANLAGE` | CHAR | 10 |  | Installation |
| 8 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 9 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 12 | `LANGU` | LANG | 1 |  | Language Key |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 15 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 17 | `PRINT_TIME` | TIMS | 6 |  | System Time |
