# ZISCS_SDU_TYPE
**Description:** Supporting Document Type Table
**Total Fields:** 11
**Key Fields:** MANDT, SDU_ID, BEN_ID

## Programs Using This Table
- `ziscs0800`
- `ziscs0800_c`
- `ziscs0800_c1`
- `ziscs0802`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SDU_ID` | CHAR | 5 | 🔑 | SDU ID |
| 3 | `BEN_ID` | CHAR | 2 | 🔑 | Beneficiary ID |
| 4 | `SDU_TYPE_TXT` | CHAR | 20 |  | SDU type text |
| 5 | `LENGTH` | NUMC | 4 |  | Length of Data |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `ERZET` | TIMS | 6 |  | Entry time |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 11 | `AEZET` | TIMS | 6 |  | Time last change was made |
