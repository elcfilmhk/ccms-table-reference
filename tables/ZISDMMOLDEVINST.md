# ZISDMMOLDEVINST
**Description:** Device Installation Request
**Total Fields:** 8
**Key Fields:** MANDT, CASE_NO

## Programs Using This Table
- `zisdm0216`
- `zisdm0229`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CASE_NO` | NUMC | 18 | 🔑 | Case No. |
| 3 | `CREATION_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `ANLAGE` | CHAR | 10 |  | Installation |
| 5 | `SERNR` | CHAR | 18 |  | Serial Number |
| 6 | `ACTIVITY_DATE` | DATS | 8 |  | Activity Date |
| 7 | `STATUS` | CHAR | 1 |  | Status ('C' - Completed, ' ' - Not yet processed) |
| 8 | `USER_ID` | CHAR | 12 |  | Name of Person Who Created the Object |
