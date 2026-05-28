# ZISCS_PRM_FUNC_H
**Description:** Premise function table
**Total Fields:** 6
**Key Fields:** MANDT, BACKUP_DATE, BACKUP_TIME, PREM_FUNC

## Programs Using This Table
- `ziscs0281`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BACKUP_DATE` | DATS | 8 | 🔑 | Backup date |
| 3 | `BACKUP_TIME` | TIMS | 6 | 🔑 | Backup time |
| 4 | `PREM_FUNC` | CHAR | 3 | 🔑 | Premise function |
| 5 | `TEXT1` | CHAR | 40 |  | Premise function description 1 |
| 6 | `TEXT2` | CHAR | 40 |  | Premise function description 2 |
