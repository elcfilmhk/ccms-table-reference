# ZISEDRVPRECORD
**Description:** RVP result populated from workflow
**Total Fields:** 11
**Key Fields:** MANDT, RECNO, WORKITEM_ID

## Programs Using This Table
- `zised0010`
- `zresoprof`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RECNO` | NUMC | 9 | 🔑 | Record Number |
| 3 | `WORKITEM_ID` | NUMC | 12 | 🔑 | Work item ID |
| 4 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 5 | `STATUS` | CHAR | 10 |  | RVP Status |
| 6 | `DATEFROM` | DATS | 8 |  | From-Date |
| 7 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 8 | `DATETO` | DATS | 8 |  | To-Date |
| 9 | `TIMETO` | TIMS | 6 |  | To-Time |
| 10 | `REPLACEMETHOD` | CHAR | 10 |  | Replacement Value Procedure |
| 11 | `REPORTDATE` | DATS | 8 |  | Reported Date |
