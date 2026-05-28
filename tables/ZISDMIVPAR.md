# ZISDMIVPAR
**Description:** IV Result Table for Parallel Run Comparison
**Total Fields:** 8
**Key Fields:** CLIENT, ABLBELNR

## Programs Using This Table
- `zcl_iv`
- `zisdm0035`
- `zisdm0072`
- `zisdm0234`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `STEP` | NUMC | 3 |  | Last Step Processed |
| 5 | `RELEASED` | CHAR | 1 |  | Flag: Outsorted MR Document should be automatically released |
| 6 | `JAP_ERDAT` | DATS | 8 |  | JAP run date |
| 7 | `JAP_STEP` | NUMC | 3 |  | JAP Last Step Processed |
| 8 | `JAP_RELEASED` | CHAR | 1 |  | Flag: JAP released MR |
