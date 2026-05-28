# ZISBI_CHILDFB
**Description:** Auto Release Child Final Bill Report
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0054`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PERIOD_TO` | DATS | 8 |  | Report Period to |
| 2 | `RPT_SECTION` | CHAR | 40 |  | Section |
| 3 | `RPT_SECT_DESC` | CHAR | 110 |  | Section Description |
| 4 | `BPNAME` | CHAR | 40 |  | Name 1 of organization |
| 5 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `OPBEL` | CHAR | 12 |  | Number of print document |
| 8 | `TOTAL_AMT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 9 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
