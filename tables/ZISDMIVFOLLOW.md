# ZISDMIVFOLLOW
**Description:** IV Follow-up
**Total Fields:** 12
**Key Fields:** MANDT, RECDATE, ABLBELNR

## Programs Using This Table
- `zcl_iv`
- `zisdm0268`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RECDATE` | DATS | 8 | 🔑 | Date |
| 3 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 4 | `PRUEFPKT` | CHAR | 2 |  | Independent validation |
| 5 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 6 | `CURMR` | DEC | 17 |  | Current Reading |
| 7 | `PREVMR` | DEC | 17 |  | Previous Reading |
| 8 | `AUART` | CHAR | 4 |  | Order Type |
| 9 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 10 | `ZZCHEKREAD` | CHAR | 1 |  | Indicator for check /read |
| 11 | `REREAD` | CHAR | 1 |  | Indicator for ReRead |
| 12 | `ZWFAKT` | DEC | 12 |  | Register factor |
