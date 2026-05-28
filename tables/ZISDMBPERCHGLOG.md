# ZISDMBPERCHGLOG
**Description:** Base Period Category change log
**Total Fields:** 12
**Key Fields:** MANDT, LOG_NO

## Programs Using This Table
- `zisdm0321`
- `zisdm0322`
- `zisdm0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOG_NO` | CHAR | 20 | 🔑 | Base Period Category Log Number |
| 3 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 |  | Contract |
| 5 | `ANLAGE` | CHAR | 10 |  | Installation |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `ORIG_BAPERTYP` | CHAR | 1 |  | Base period category |
| 11 | `NEW_BAPERTYP` | CHAR | 1 |  | Base period category |
| 12 | `STATUS` | CHAR | 1 |  | The status of the audit log |
