# ZISCS_TRD_CAT_H
**Description:** Trade category table (history)
**Total Fields:** 6
**Key Fields:** MANDT, BACKUP_DATE, BACKUP_TIME, TRADE_CAT

## Programs Using This Table
- `ziscs0281`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BACKUP_DATE` | DATS | 8 | 🔑 | Backup date |
| 3 | `BACKUP_TIME` | TIMS | 6 | 🔑 | Backup time |
| 4 | `TRADE_CAT` | CHAR | 2 | 🔑 | Trade category |
| 5 | `TEXT1` | CHAR | 60 |  | Trade category description 1 |
| 6 | `TEXT2` | CHAR | 40 |  | Trade category description 2 |
