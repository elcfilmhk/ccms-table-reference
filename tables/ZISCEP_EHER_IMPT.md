# ZISCEP_EHER_IMPT
**Description:** CEP - e-HER (Imported Batch)
**Total Fields:** 4
**Key Fields:** MANDT, IMPORT_DATE

## Programs Using This Table
- `ziscs0456`
- `ziscs0458`
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `IMPORT_DATE` | DATS | 8 | 🔑 | CEP: e-HER Data Import Date |
| 3 | `MANUAL_CHECK` | CHAR | 1 |  | CEP: e-HER Manual Sample Check Status |
| 4 | `RELEASE_BATCH` | CHAR | 1 |  | CEP: e-HER Release Batch Indicator |
