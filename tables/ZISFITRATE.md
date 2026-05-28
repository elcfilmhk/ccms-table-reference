# ZISFITRATE
**Description:** Structure for rate category corresponding DFKKOP Line Item
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zfind_rate_table==============ft`
- `zisfi0027`
- `zisfi0032`
- `zisfi0038`
- `zisfi0043`
- `zisfi0046`
- `zisfi0056`
- `zisfi0103`
- `zisfi0116`
- `zisfi0116_1`
- `zisfi0116_test`
- `zisfi0116_test2`
- `zisfi0116_test3`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 2 | `OPUPW` | NUMC | 3 |  | Repetition Item in Contract Account Document |
| 3 | `OPUPK` | NUMC | 4 |  | Item number in contract account document |
| 4 | `OPUPZ` | NUMC | 3 |  | Subitem for a Partial Clearing in Document |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 7 | `WAERS` | CUKY | 5 |  | Transaction Currency |
| 8 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 9 | `NORATECAT` | CHAR | 1 |  | Flag to indicate no rate category found |
