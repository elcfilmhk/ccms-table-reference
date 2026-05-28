# ZISCEP_EHER_PROC
**Description:** CEP - e-HER (Formatted HTML Data)
**Total Fields:** 12
**Key Fields:** MANDT, CONTRACT_ACCOUNT, IMPORT_DATE

## Programs Using This Table
- `ziscs0457`
- `ziscs0458`
- `ziscs0461`
- `ziscs0463`
- `ziscs0464`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `IMPORT_DATE` | DATS | 8 | 🔑 | CEP: e-HER Data Import Date |
| 4 | `OUTSORT` | CHAR | 1 |  | CEP: e-HER Outsort Indicator |
| 5 | `SENT_DATE` | DATS | 8 |  | CEP: e-HER Sent Date |
| 6 | `EMAIL_GUID` | CHAR | 32 |  | CEP: e-HER Email GUID |
| 7 | `EMAIL_SUBJECT` | CHAR | 256 |  | CEP: e-HER Email Subject Line |
| 8 | `CUSTOMER_LOCALE` | CHAR | 10 |  | CEP: e-HER Customer Locale |
| 9 | `OBJTP` | CHAR | 3 |  | Code for document class |
| 10 | `OBJYR` | CHAR | 2 |  | Object: Year from ID |
| 11 | `OBJNO` | CHAR | 12 |  | Object: Number from ID |
| 12 | `RENDERED_HTML` | STRG | 0 |  | CEP: e-HER Rendered HTML (Formatted) |
