# ZTPDATA
**Description:** Transfer postings structure
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisucntrct`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `DOC` | CHAR | 12 |  | Document no. of TP |
| 3 | `BUDAT` | DATS | 8 |  | Posting date of TP |
| 4 | `AMOUNT` | CURR | 13 |  | Amount of TP |
| 5 | `TP_TO` | CHAR | 1 |  | Item was transferred to this CA |
| 6 | `TP_FROM` | CHAR | 1 |  | Item was transferred from this CA |
