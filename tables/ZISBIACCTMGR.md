# ZISBIACCTMGR
**Description:** Account Manager Information
**Total Fields:** 13
**Key Fields:** MANDT, ACCTMGR

## Programs Using This Table
- `zissd00089`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACCTMGR` | CHAR | 12 | 🔑 | User Name |
| 3 | `BP` | CHAR | 10 |  | Business Partner Number |
| 4 | `TITLE_ENG` | CHAR | 30 |  | Account Manager Title (English) |
| 5 | `NAME_ENG` | CHAR | 80 |  | Account Manager Name (English) |
| 6 | `TITLE_CHI` | CHAR | 30 |  | Account Manager Title (Chinese) |
| 7 | `NAME_CHI` | CHAR | 80 |  | Account Manager Name (Chinese) |
| 8 | `PHONE` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 9 | `EMAIL` | CHAR | 241 |  | E-Mail Address |
| 10 | `MOBILE` | CHAR | 30 |  | First Cell Phone Number: Dialing Code + Number |
| 11 | `FAX` | CHAR | 30 |  | Fax number: dialling code+number |
| 12 | `OFFICEADDR` | CHAR | 255 |  | Account Manager Office Address |
| 13 | `SALES_GROUP` | CHAR | 12 |  | Sales Group for CRM Organization Structure |
