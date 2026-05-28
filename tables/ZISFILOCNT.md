# ZISFILOCNT
**Description:** MCRS Location list
**Total Fields:** 4
**Key Fields:** MANDT, LOCATION

## Programs Using This Table
- `zisfi0022`
- `zisfi0023`
- `zisfi0028`
- `zisfi0207`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOCATION` | NUMC | 2 | 🔑 | Location ID for MCRS loactions |
| 3 | `NAME` | CHAR | 80 |  | MCRS Location Name |
| 4 | `ORG_UNIT` | CHAR | 10 |  | HR Organization Unit |
