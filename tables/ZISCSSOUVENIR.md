# ZISCSSOUVENIR
**Description:** Souvenir Redemption History
**Total Fields:** 10
**Key Fields:** MANDT, ICTTY, VKONT, CRDAT, RETYP

## Programs Using This Table
- `ziscs0174`
- `ziscs0205`
- `ziscs0210`
- `ziscs0217`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ICTTY` | CHAR | 15 | 🔑 | Incentive Type |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CRDAT` | DATS | 8 | 🔑 | Creation date |
| 5 | `RETYP` | CHAR | 1 | 🔑 | Record Type |
| 6 | `ICQTY` | DEC | 10 |  | Quantity |
| 7 | `LCUSR` | CHAR | 12 |  | Last Changed By |
| 8 | `LCDAT` | DATS | 8 |  | Last Changed On |
| 9 | `CSCUR` | CHAR | 12 |  | CSC |
| 10 | `ISDAT` | DATS | 8 |  | Date of Issue |
