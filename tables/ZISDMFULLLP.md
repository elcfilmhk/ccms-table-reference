# ZISDMFULLLP
**Description:** Storing devices need to take full load profile
**Total Fields:** 9
**Key Fields:** MANDT, ADATSOLL, SERNR

## Programs Using This Table
- `zisdm0027`
- `zisdm0188`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `FLP_IND` | CHAR | 1 |  | Full load profile indicator |
| 5 | `STATUS` | CHAR | 10 |  | Record status |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
