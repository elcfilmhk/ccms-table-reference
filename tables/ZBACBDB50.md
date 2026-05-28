# ZBACBDB50
**Description:** IXOS: Data Archival: BCAS - Archive Session Retention
**Total Fields:** 3
**Key Fields:** MANDT, OBJECT

## Programs Using This Table
- `zbacbdb50`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJECT` | CHAR | 10 | 🔑 | Archiving Object |
| 3 | `RETENTION` | NUMC | 4 |  | Retention (years) |
