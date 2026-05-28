# ZISBIRBPARM
**Description:** Rebate rate for rate categories
**Total Fields:** 15
**Key Fields:** MANDT, RB_YEAR, TARIFTYP

## Programs Using This Table
- `zisbi0025`
- `zisbi0025_1`
- `zisbi0201`
- `zisbi0201_ind`
- `zisbi0201_mu`
- `zisbi0202`
- `zisbi0203`
- `zisbi0208`
- `zisbi0209`
- `zisbi0216`
- `zisbi0218`
- `zisbi0219`
- `zisbi0221`
- `zisfi0258`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RB_YEAR` | CHAR | 8 | 🔑 | Rebate year and reference |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 4 | `MAX_RB_AMT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 5 | `FIX_AMT` | DEC | 10 |  | Fixed amount (Rebate) |
| 6 | `UNIT_RATE` | DEC | 17 |  | Rebate unit price |
| 7 | `RB_FROM_DATE` | DATS | 8 |  | Rebate from date |
| 8 | `RB_TO_DATE` | DATS | 8 |  | Rebate to date |
| 9 | `ACTIVE_INDC` | CHAR | 1 |  | Active Indicator |
| 10 | `EFF_DATE` | DATS | 8 |  | Effective date |
| 11 | `EXPIRY_DATE` | DATS | 8 |  | Expiry date for Posting |
| 12 | `MB_EXPIRY` | DATS | 8 |  | Expiry date for Manual bill creation |
| 13 | `RUN_FLAG` | CHAR | 1 |  | Terminated account run flag |
| 14 | `INFO1` | CHAR | 10 |  | Info 1 |
| 15 | `INFO2` | CHAR | 20 |  | Info 2 |
