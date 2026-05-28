# ZISDMMTRPLMAPIN
**Description:** Meter mappping for MOL
**Total Fields:** 9
**Key Fields:** MANDT, OLDDEVICE, NEWDEVICE

## Programs Using This Table
- `zisem0003`
- `zisem0005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OLDDEVICE` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `NEWDEVICE` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `STATUS` | CHAR | 1 |  | Meter mappping status for MOL |
| 5 | `ERNAM` | CHAR | 12 |  | Created By |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZET` | TIMS | 6 |  | Entry time |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AEZET` | TIMS | 6 |  | Time last change was made |
