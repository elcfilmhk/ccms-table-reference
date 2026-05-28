# ZISFIDOC
**Description:** Stucture for DFKKOP Line Item
**Total Fields:** 4
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

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 2 | `OPUPW` | NUMC | 3 |  | Repetition Item in Contract Account Document |
| 3 | `OPUPK` | NUMC | 4 |  | Item number in contract account document |
| 4 | `OPUPZ` | NUMC | 3 |  | Subitem for a Partial Clearing in Document |
