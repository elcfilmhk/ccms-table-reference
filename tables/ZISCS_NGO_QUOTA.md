# ZISCS_NGO_QUOTA
**Description:** NGO Quota Table
**Total Fields:** 11
**Key Fields:** MANDT, PROG_ID, NGO_CODE

## Programs Using This Table
- `z_iscspc_subsidy_lock_fail====ft`
- `ziscs0815`
- `ziscs0815_01`
- `ziscs0817`
- `ziscs0828`
- `ziscs0829`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `NGO_CODE` | CHAR | 8 | 🔑 | Branch Code |
| 4 | `NGO_QUOTA` | CHAR | 10 |  | Quota |
| 5 | `QUOTA_USED` | CHAR | 10 |  | Quota Used |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `ERZET` | TIMS | 6 |  | Entry time |
| 9 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 11 | `AEZET` | TIMS | 6 |  | Time last change was made |
