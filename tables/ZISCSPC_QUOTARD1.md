# ZISCSPC_QUOTARD1
**Description:** Overall Quota percentage usage table Round1
**Total Fields:** 10
**Key Fields:** MANDT, PROG_ID

## Programs Using This Table
- `z_iscspc_subsidy_lock_fail====ft`
- `ziscs0805`
- `ziscs0815`
- `ziscs0815_01`
- `ziscs0817`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `PERCENTAGE` | DEC | 7 |  | Quota Perecentage |
| 4 | `QUOTA_USED` | CHAR | 10 |  | Quota Used |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `ERZET` | TIMS | 6 |  | Entry time |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `AEZET` | TIMS | 6 |  | Time last change was made |
