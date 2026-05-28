# ZISCS_EEC_REQ_GEN_EHER_INPUT
**Description:** Input structure for FM 'ZISCS_EEC_REQUEST_GEN_EHER'
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0387_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 3 | `REPORT_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 5 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 6 | `SEND_AFTER` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `EMAIL_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 8 | `LANGU` | LANG | 1 |  | Language in connection with the contract account |
