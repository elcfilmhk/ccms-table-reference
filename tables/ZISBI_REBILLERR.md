# ZISBI_REBILLERR
**Description:** Error Message Master table
**Total Fields:** 4
**Key Fields:** MANDT, ERRCODE

## Programs Using This Table
- `zisbi0260`
- `zisbi0266`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERRCODE` | CHAR | 2 | 🔑 | Error Code |
| 3 | `ERRDESC` | CHAR | 100 |  | Error Description |
| 4 | `EXPUNEXPERR` | CHAR | 1 |  | Expected or Unexpected error |
