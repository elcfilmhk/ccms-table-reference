# ZISDMCNTRD28CASE
**Description:** Cant read code 28 case for follow-up
**Total Fields:** 7
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0050`
- `zisdm0254`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 3 | `GERNR` | CHAR | 18 |  | Device |
| 4 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 5 | `MR_DATE` | DATS | 8 |  | The meter reading date of the reading |
| 6 | `BATCH_DATE` | DATS | 8 |  | The batch run date |
| 7 | `CHK_READ_UPLOAD` | CHAR | 1 |  | The check reading has been uploaded |
