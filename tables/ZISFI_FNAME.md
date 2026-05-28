# ZISFI_FNAME
**Description:** Full Name for FPS
**Total Fields:** 11
**Key Fields:** MANDT, BUSINESSPARTNER, APYBNO, APYBAN

## Programs Using This Table
- `zisfi0278`
- `zisfi0337`
- `zisfi0338`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUSINESSPARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `APYBNO` | CHAR | 15 | 🔑 | Bank Keys |
| 4 | `APYBAN` | CHAR | 18 | 🔑 | Bank account number |
| 5 | `APYHLDNAME1` | CHAR | 140 |  | Account Holder Name 1 & 2 for DDA registration |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZET` | TIMS | 6 |  | Entry time |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
