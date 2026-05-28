# ZBUPAGETDETAIL3
**Description:** BAPI Structure for Communication Contact Data
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_contact_no=========ft`
- `zisfi0146`
- `zisfi0156`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BPARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `CONTACT1` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 3 | `MOBILE` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 4 | `CONTACT2` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 5 | `FAX` | CHAR | 30 |  | Fax number: dialling code+number |
| 6 | `E_MAIL` | CHAR | 241 |  | E-Mail Address |
| 7 | `TEL_EXTENS` | CHAR | 10 |  | Telephone no.: Extension |
