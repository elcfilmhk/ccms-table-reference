# ZISCEP_EHER_ORI
**Description:** CEP - e-HER (Original CSV Data)
**Total Fields:** 11
**Key Fields:** MANDT, CONTRACT_ACCOUNT, IMPORT_DATE

## Programs Using This Table
- `ziscs0456`
- `ziscs0457`
- `ziscs0458`
- `ziscs0463`
- `ziscs0464`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `IMPORT_DATE` | DATS | 8 | 🔑 | CEP: e-HER Data Import Date |
| 4 | `OUTSORT` | CHAR | 1 |  | CEP: e-HER Outsort Indicator |
| 5 | `PROCESSED` | CHAR | 1 |  | CEP: e-HER Processed Indicator |
| 6 | `COMMUNICATION_ID` | CHAR | 50 |  | CEP: e-HER Communication ID |
| 7 | `MASKED_CA` | CHAR | 100 |  | CEP: e-HER Masked Contract Account Number |
| 8 | `MASKED_EMAIL` | CHAR | 100 |  | CEP: e-HER Masked Customer Email Address |
| 9 | `EMAIL_SUBJECT` | CHAR | 256 |  | CEP: e-HER Email Subject Line |
| 10 | `CUSTOMER_LOCALE` | CHAR | 10 |  | CEP: e-HER Customer Locale |
| 11 | `RENDERED_HTML` | STRG | 0 |  | CEP: e-HER Rendered HTML (Original) |
