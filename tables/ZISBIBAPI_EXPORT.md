# ZISBIBAPI_EXPORT
**Description:** EXPORT STRUCTURE FOR BAPI-COMPARE AND MANAGE BILL
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_isbi_compare_manage_bill====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PDN` | CHAR | 12 |  | Number of print document |
| 2 | `PDATE` | DATS | 8 |  | Posting Date in the Document |
| 3 | `BDN` | CHAR | 12 |  | Number of a billing document |
| 4 | `NTA` | CURR | 13 |  | Net amount of billing line item |
| 5 | `TOUTA` | CURR | 13 |  | Net amount of billing line item |
| 6 | `SAVINGS` | CURR | 13 |  | Net amount of billing line item |
