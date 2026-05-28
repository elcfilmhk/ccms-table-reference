# ZISCS_TRD_CLAS_H
**Description:** Trade class table (history)
**Total Fields:** 7
**Key Fields:** MANDT, BACKUP_DATE, BACKUP_TIME, TRADE_CAT, TRADE_CLASS

## Programs Using This Table
- `ziscs0281`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BACKUP_DATE` | DATS | 8 | 🔑 | Backup date |
| 3 | `BACKUP_TIME` | TIMS | 6 | 🔑 | Backup time |
| 4 | `TRADE_CAT` | CHAR | 2 | 🔑 | Trade category |
| 5 | `TRADE_CLASS` | CHAR | 10 | 🔑 | Trade |
| 6 | `TEXT1` | CHAR | 40 |  | Trade class description 1 |
| 7 | `TEXT2` | CHAR | 40 |  | Trade class description 2 |
