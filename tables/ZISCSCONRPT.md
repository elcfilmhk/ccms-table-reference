# ZISCSCONRPT
**Description:** BP Top Consumption Report
**Total Fields:** 15
**Key Fields:** MANDT, NR_MONTH, PARTNER

## Programs Using This Table
- `zisbifi_recon`
- `ziscs0084`
- `ziscs0085`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NR_MONTH` | NUMC | 2 | 🔑 | Number of months (00 = YTD) |
| 3 | `PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `FUEL` | DEC | 16 |  | Amount |
| 5 | `CHARGE` | DEC | 16 |  | Amount |
| 6 | `CONSUMPTION` | DEC | 16 |  | Amount |
| 7 | `REBATE` | DEC | 16 |  | Amount |
| 8 | `SP_REBATE` | DEC | 16 |  | Amount |
| 9 | `NRMSREB5` | DEC | 16 |  | Amount |
| 10 | `REB13` | DEC | 16 |  | Amount |
| 11 | `SUB_TOT` | DEC | 16 |  | Amount |
| 12 | `PLOUT_CONSUMPT` | DEC | 16 |  | Amount |
| 13 | `CLOUT_CONSUMPT` | DEC | 16 |  | Amount |
| 14 | `TOT_WO_LOUT` | DEC | 16 |  | Amount |
| 15 | `LEFTOUT` | CHAR | 1 |  | Leftout indicator |
