# ZISBIMONBILLSTAT
**Description:** Monthly Bill Additional Bill Statistic Table
**Total Fields:** 13
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0177`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `DATUM1` | DATS | 8 |  | Date |
| 4 | `ZZBILL` | CHAR | 2 |  | Bill ID |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 7 | `ZZDELIVERY` | CHAR | 1 |  | Delivery Method |
| 8 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 9 | `MONTHLYBILL` | CHAR | 1 |  | Monthly bill |
| 10 | `USER1` | CHAR | 12 |  | User Name |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 13 | `LANGU` | LANG | 1 |  | Language Key |
