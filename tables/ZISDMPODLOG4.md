# ZISDMPODLOG4
**Description:** Automatic creation of POD Logging Table 4
**Total Fields:** 12
**Key Fields:** MANDT, REC_NO, PROFL_NO

## Programs Using This Table
- `zisdm0127`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REC_NO` | NUMC | 9 | 🔑 | Record number |
| 3 | `PROFL_NO` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 4 | `SERNR` | CHAR | 18 |  | Serial Number |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 7 | `ZZRATETYPE` | CHAR | 8 |  | Rate Type |
| 8 | `STATUS` | CHAR | 10 |  | Status (Success/Failed) |
| 9 | `REASON` | CHAR | 100 |  | Failure Reason |
| 10 | `ACTVDATE` | DATS | 8 |  | Activity date |
| 11 | `ACTNDATE` | DATS | 8 |  | Action date |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
