# ZISCRMMYWSRPTSCH
**Description:** My Workspace Scheme Monthly Report
**Total Fields:** 17
**Key Fields:** MANDT, PAID, MTH

## Programs Using This Table
- `ziscrm0015`
- `ziscrm0015a`
- `ziscrm0019`
- `ziscrm0019a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PAID` | CHAR | 1 | 🔑 | Flag for paid service |
| 3 | `MTH` | NUMC | 6 | 🔑 | Month |
| 4 | `SC_LPTCNT` | INT4 | 10 |  | No. of Scheme - LPT Counts |
| 5 | `SC_BTCNT` | INT4 | 10 |  | No. of Scheme - BT Counts |
| 6 | `SC_SUBTTL` | INT4 | 10 |  | No. of Scheme - Subtotal |
| 7 | `CA_LPTCNT` | INT4 | 10 |  | No. of CAs - LPT Counts |
| 8 | `CA_BTCNT` | INT4 | 10 |  | No. of CAs - BT Counts |
| 9 | `CA_SUBTTL` | INT4 | 10 |  | No. of CAs - Subtotal |
| 10 | `MT_LPTCNT` | INT4 | 10 |  | No. of Meters - LPT Counts |
| 11 | `MT_BTCNT` | INT4 | 10 |  | No. of Meters - BT Counts |
| 12 | `MT_SUBTTL` | INT4 | 10 |  | No. of Meters - Subtotal |
| 13 | `RE_LPTCNT` | CURR | 13 |  | Revenue - LPT (HK$) |
| 14 | `RE_BTCNT` | CURR | 13 |  | Revenue - BT |
| 15 | `RE_SUBTTL` | CURR | 13 |  | Revenue - Subtotal |
| 16 | `CAMT_PERSC` | DEC | 13 |  | No. of CAs / Meters per Scheme |
| 17 | `RE_PERSC` | CURR | 13 |  | Revenue per Scheme (HK$) |
