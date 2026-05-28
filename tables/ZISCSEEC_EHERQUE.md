# ZISCSEEC_EHERQUE
**Description:** eHER Generation Queue
**Total Fields:** 14
**Key Fields:** MANDT, REQ_DT, REQ_USER, ID_KEY

## Programs Using This Table
- `ziscs0387_eec`
- `ziscs0389_eec`
- `ziscs0390_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `REQ_USER` | CHAR | 12 | 🔑 | User Name |
| 4 | `ID_KEY` | INT4 | 10 | 🔑 | Natural number |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `REPORT_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `PROCESSED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 8 | `PROCESSED_BY` | CHAR | 12 |  | User Name |
| 9 | `SEND_AFTER` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 10 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 11 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 12 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 13 | `EMAIL_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 14 | `LANGU` | LANG | 1 |  | Language in connection with the contract account |
