# ZISCEP_EHER_COMP
**Description:** CEP - e-HER (Archive Table for the Processed e-HER Record)
**Total Fields:** 15
**Key Fields:** MANDT, CONTRACT_ACCOUNT, IMPORT_DATE

## Programs Using This Table
- `ziscs0456`
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
| 6 | `SENT_DATE` | DATS | 8 |  | CEP: e-HER Sent Date |
| 7 | `EMAIL_GUID` | CHAR | 32 |  | CEP: e-HER Email GUID |
| 8 | `OBJTP` | CHAR | 3 |  | Code for document class |
| 9 | `OBJYR` | CHAR | 2 |  | Object: Year from ID |
| 10 | `OBJNO` | CHAR | 12 |  | Object: Number from ID |
| 11 | `COMMUNICATION_ID` | CHAR | 50 |  | CEP: e-HER Communication ID |
| 12 | `MASKED_CA` | CHAR | 100 |  | CEP: e-HER Masked Contract Account Number |
| 13 | `MASKED_EMAIL` | CHAR | 100 |  | CEP: e-HER Masked Customer Email Address |
| 14 | `EMAIL_SUBJECT` | CHAR | 256 |  | CEP: e-HER Email Subject Line |
| 15 | `CUSTOMER_LOCALE` | CHAR | 10 |  | CEP: e-HER Customer Locale |
