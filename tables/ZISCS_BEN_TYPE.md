# ZISCS_BEN_TYPE
**Description:** Beneficiary Type Record
**Total Fields:** 9
**Key Fields:** MANDT, BEN_ID

## Programs Using This Table
- `ziscs0800`
- `ziscs0800_c`
- `ziscs0800_c1`
- `ziscs0802`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BEN_ID` | CHAR | 2 | 🔑 | Beneficiary ID |
| 3 | `BEN_TYPE` | CHAR | 12 |  | Beneficiary Type |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `ERZET` | TIMS | 6 |  | Entry time |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 9 | `AEZET` | TIMS | 6 |  | Time last change was made |
