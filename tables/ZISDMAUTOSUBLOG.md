# ZISDMAUTOSUBLOG
**Description:** Auto load profile substitution log
**Total Fields:** 19
**Key Fields:** MANDT, PRCDT, RUNID, AUTOKEY, POINTOFDELIVERY, UNIT

## Programs Using This Table
- `zised0013`
- `zised0014`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRCDT` | DATS | 8 | 🔑 | Processed Date |
| 3 | `RUNID` | NUMC | 14 | 🔑 | Run ID for Profile Import Interface |
| 4 | `AUTOKEY` | NUMC | 10 | 🔑 | Numeric Character Field, Length 10 |
| 5 | `POINTOFDELIVERY` | CHAR | 50 | 🔑 | Point of delivery ID |
| 6 | `UNIT` | CHAR | 3 | 🔑 | Unit of measurement of profile value in general interface |
| 7 | `REFERENCENUMBER` | CHAR | 15 |  | Code for Identifying a Register |
| 8 | `PROFROLETYPE` | NUMC | 2 |  | Role category for profile allocation |
| 9 | `PROFROLE` | CHAR | 4 |  | Profile allocation role |
| 10 | `DATEFROM` | DATS | 8 |  | From-Date |
| 11 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 12 | `FROMOFFSET` | CHAR | 3 |  | Offset for time difference |
| 13 | `DATETO` | DATS | 8 |  | To-Date |
| 14 | `TIMETO` | TIMS | 6 |  | To-Time |
| 15 | `TOOFFSET` | CHAR | 3 |  | Offset for time difference |
| 16 | `VALUE` | CHAR | 31 |  | Profile value in interface |
| 17 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
