# ZISMDREPPARA
**Description:** User-definable report parameters
**Total Fields:** 8
**Key Fields:** MANDT, PARAMETER_ID, EFFECTIVE_FROM

## Programs Using This Table
- `zismd0026`
- `zismd0027`
- `zismd0028`
- `zismd0029`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PARAMETER_ID` | CHAR | 2 | 🔑 | Parameter ID |
| 3 | `EFFECTIVE_FROM` | DATS | 8 | 🔑 | Effective From |
| 4 | `EFFECTIVE_TO` | DATS | 8 |  | Effective To |
| 5 | `PARAMETER_DESC` | CHAR | 80 |  | Parameter |
| 6 | `DEFAULT_VALUE` | CHAR | 10 |  | Default Value |
| 7 | `UPDATEDATE` | DATS | 8 |  | Last Update |
| 8 | `UPDATEBY` | CHAR | 12 |  | Update By |
