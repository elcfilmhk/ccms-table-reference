# ZISDMPODLOG1
**Description:** Automatic creation of POD Logging Table 1
**Total Fields:** 10
**Key Fields:** MANDT, REC_NO, POD_ID, ANLAGE

## Programs Using This Table
- `zisdm0127`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REC_NO` | NUMC | 9 | 🔑 | Record number |
| 3 | `POD_ID` | CHAR | 50 | 🔑 | Point of delivery ID |
| 4 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 5 | `SERNR` | CHAR | 18 |  | Serial Number |
| 6 | `STATUS` | CHAR | 10 |  | Status (Success/Failed) |
| 7 | `REASON` | CHAR | 100 |  | Failure Reason |
| 8 | `ACTVDATE` | DATS | 8 |  | Activity date |
| 9 | `ACTNDATE` | DATS | 8 |  | Action date |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
