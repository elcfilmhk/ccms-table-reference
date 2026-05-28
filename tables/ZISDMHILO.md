# ZISDMHILO
**Description:** customized table for consumption variance
**Total Fields:** 14
**Key Fields:** MANDT, ZZCONSULEV, ZZMONTH

## Programs Using This Table
- `ziscs0252`
- `zisdm0035`
- `zisdm0067`
- `zisdm0068`
- `zisdm0072`
- `zisdm0107`
- `zisdm0153`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZCONSULEV` | CHAR | 17 | 🔑 | Consumption level |
| 3 | `ZZMONTH` | NUMC | 2 | 🔑 | Consumption Month |
| 4 | `ZZCONSUVAR` | CHAR | 8 |  | Consumption Variance |
| 5 | `UPPER_TL1` | DEC | 5 |  | Tolerance Limit |
| 6 | `LOWER_TL1` | DEC | 5 |  | Tolerance Limit |
| 7 | `UTL1_FLAG` | CHAR | 1 |  | Indicator for check /read |
| 8 | `UTL1_AUFART` | CHAR | 4 |  | Order Type |
| 9 | `UTL1_ILART` | CHAR | 3 |  | Maintenance activity type |
| 10 | `UPPER_TL2` | DEC | 5 |  | Tolerance Limit |
| 11 | `LOWER_TL2` | DEC | 5 |  | Tolerance Limit |
| 12 | `UTL2_FLAG` | CHAR | 1 |  | Indicator for check /read |
| 13 | `UTL2_AUFART` | CHAR | 4 |  | Order Type |
| 14 | `UTL2_ILART` | CHAR | 3 |  | Maintenance activity type |
