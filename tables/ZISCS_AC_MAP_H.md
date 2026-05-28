# ZISCS_AC_MAP_H
**Description:** Trade class to premise function mapping (history)
**Total Fields:** 6
**Key Fields:** MANDT, BACKUP_DATE, BACKUP_TIME, TRADE_CLASS, PREM_FUNC

## Programs Using This Table
- `ziscs0281`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BACKUP_DATE` | DATS | 8 | 🔑 | Backup date |
| 3 | `BACKUP_TIME` | TIMS | 6 | 🔑 | Backup time |
| 4 | `TRADE_CLASS` | CHAR | 10 | 🔑 | Trade |
| 5 | `PREM_FUNC` | CHAR | 3 | 🔑 | Premise function |
| 6 | `KTOKL` | CHAR | 4 |  | Account class |
