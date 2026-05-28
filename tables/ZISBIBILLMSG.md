# ZISBIBILLMSG
**Description:** Bill message printing history table
**Total Fields:** 16
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0213`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 6 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 7 | `ZZBILLID` | CHAR | 2 |  | Bill ID |
| 8 | `ZZDELIVERY` | CHAR | 1 |  | Delivery Method |
| 9 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `MESSAGE_NO` | NUMC | 10 |  | Message number |
| 12 | `ESTIMATE_MESSAGE_NO` | NUMC | 10 |  | Estimate Message number |
| 13 | `BATCH` | NUMC | 10 |  | Batch Number |
| 14 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 15 | `CREATION_TIME` | TIMS | 6 |  | Time of Print Document Creation |
| 16 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
