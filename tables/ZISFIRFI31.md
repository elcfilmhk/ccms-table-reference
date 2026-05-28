# ZISFIRFI31
**Description:** Security deposit data image.
**Total Fields:** 8
**Key Fields:** MANDT, ZDATE, ZDEP_TYPE, ZACC_TYPE, TARIFTYP, ZLE6

## Programs Using This Table
- `zisfi0158`
- `zisfi0159`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZDATE` | DATS | 8 | 🔑 | Date |
| 3 | `ZDEP_TYPE` | CHAR | 1 | 🔑 | Character length 1 |
| 4 | `ZACC_TYPE` | CHAR | 1 | 🔑 | Character length 1 |
| 5 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 6 | `ZLE6` | CHAR | 1 | 🔑 | Character length 1 |
| 7 | `ZCT` | INT4 | 10 |  | Number of records read |
| 8 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
