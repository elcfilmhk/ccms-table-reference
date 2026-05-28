# ZJIVS_SETDATA_FORMULA
**Description:** 
**Total Fields:** 6
**Key Fields:** MANDT, ZZJIVS_LINE_NUMBER, ZZJIVS_TABLE, ZZJIVS_SETNR

## Programs Using This Table
- `zjivs_export_setdata`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZJIVS_LINE_NUMBER` | NUMC | 15 | 🔑 | JiVS Line Number |
| 3 | `ZZJIVS_TABLE` | CHAR | 30 | 🔑 | Table for set |
| 4 | `ZZJIVS_SETNR` | CHAR | 12 | 🔑 | Set ID (internal) |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Formula Table for Set Generation |
| 6 | `FORMULA` | CHAR | 240 |  | Formula in set line |
