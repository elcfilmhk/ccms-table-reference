# ZJIVS_MIG_TABS
**Description:** JiVS Job Dispatcher migration tables
**Total Fields:** 4
**Key Fields:** MANDT, MIGOBJ, TABNAME

## Programs Using This Table
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MIGOBJ` | CHAR | 15 | 🔑 | Object Name Definition |
| 3 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 4 | `SORT` | NUMC | 6 |  | Sort field |
