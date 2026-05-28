# ZISCSSDR
**Description:** Security Deposit Release Table
**Total Fields:** 13
**Key Fields:** MANDT, PROMO, VKONT

## Programs Using This Table
- `ziscs0166`
- `ziscs0167`
- `ziscs0169`
- `ziscs0169_old`
- `ziscs0173`
- `ziscs0178`
- `ziscs0187`
- `ziscs0278`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMO` | CHAR | 20 | 🔑 | Promotion name |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CRDAT` | DATS | 8 |  | Creation date |
| 5 | `EBMHD` | CHAR | 4 |  | Existing Incoming Billing Method |
| 6 | `EPMHD` | CHAR | 1 |  | Existing Incoming Payment Method |
| 7 | `ELDAT` | DATS | 8 |  | Eligible Date |
| 8 | `NBMHD` | CHAR | 4 |  | New Billing Method |
| 9 | `NPMHD` | CHAR | 1 |  | New Payment Method |
| 10 | `INACT` | CHAR | 1 |  | Inactive Account |
| 11 | `CRUSR` | CHAR | 12 |  | Created By |
| 12 | `LCUSR` | CHAR | 12 |  | Last Changed By |
| 13 | `LCDAT` | DATS | 8 |  | Last Changed On |
