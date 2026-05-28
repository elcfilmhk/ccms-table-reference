# ZISDMADRAUDITLOG
**Description:** ADR BATCH LOG table
**Total Fields:** 10
**Key Fields:** MANDT, LOGID

## Programs Using This Table
- `zisdm0312_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOGID` | NUMC | 10 | 🔑 | DR Log ID |
| 3 | `BATCHID` | CHAR | 80 |  | Batch ID |
| 4 | `EVENTNAME` | CHAR | 50 |  | Event Name |
| 5 | `DRCUSTNO` | CHAR | 80 |  | DR Customer Number |
| 6 | `ACTION` | CHAR | 50 |  | Audit transaction |
| 7 | `OBJECT` | CHAR | 100 |  | DR Object (extra) |
| 8 | `LASTUPDATEDATE` | DATS | 8 |  | Date |
| 9 | `LASTUPDATETIME` | TIMS | 6 |  | Time |
| 10 | `LASTUPDATEBY` | CHAR | 12 |  | User Name |
