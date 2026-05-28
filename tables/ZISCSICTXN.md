# ZISCSICTXN
**Description:** Incentive Transaction
**Total Fields:** 15
**Key Fields:** MANDT, VKONT, PROMO

## Programs Using This Table
- `ziscs0164`
- `ziscs0168`
- `ziscs0170`
- `ziscs0171`
- `ziscs0172`
- `ziscs0173`
- `ziscs0174`
- `ziscs0187`
- `ziscs0194`
- `ziscs0205`
- `ziscs0210`
- `ziscs0212`
- `ziscs0217`
- `ziscs0486`
- `zisfi0168`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PROMO` | CHAR | 20 | 🔑 | Promotion name |
| 4 | `ICTTY` | CHAR | 15 |  | Incentive Type |
| 5 | `CRDAT` | DATS | 8 |  | Creation date |
| 6 | `CRUSR` | CHAR | 12 |  | Created By |
| 7 | `ISDAT` | DATS | 8 |  | Date of Issue |
| 8 | `ISUSR` | CHAR | 30 |  | Issuer |
| 9 | `LCUSR` | CHAR | 12 |  | Last Changed By |
| 10 | `LCDAT` | DATS | 8 |  | Last Changed On |
| 11 | `REMRK` | CHAR | 132 |  | Text of length 132 |
| 12 | `SUPDR` | CHAR | 1 |  | Suppress DR Follow Up |
| 13 | `SCUSR` | CHAR | 12 |  | Suppress DR Changed By |
| 14 | `SCDAT` | DATS | 8 |  | Suppress DR Changed On |
| 15 | `DRFLG` | CHAR | 1 |  | DR Follow Up Flag |
