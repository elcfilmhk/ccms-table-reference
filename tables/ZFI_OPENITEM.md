# ZFI_OPENITEM
**Description:** FI-CA Open items
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0133`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 2 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 3 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 4 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 5 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 6 | `FAEDN` | DATS | 8 |  | Due date for net payment |
