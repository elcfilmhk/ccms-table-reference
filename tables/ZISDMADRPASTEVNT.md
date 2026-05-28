# ZISDMADRPASTEVNT
**Description:** ADR Past Event Information
**Total Fields:** 6
**Key Fields:** MANDT, EVENTNAME, BATCHID, DRCUSTNO, PASTEVENTNAME

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0356`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 3 | `BATCHID` | CHAR | 80 | 🔑 | Batch ID |
| 4 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 5 | `PASTEVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 6 | `STARTDATE` | DATS | 8 |  | Date |
