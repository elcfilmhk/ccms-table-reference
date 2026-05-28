# ZISBIPAYMHIST
**Description:** Structure for payment history
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_bill_history===========ft`
- `zisbi0268`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TRANSDATE` | DATS | 8 |  | Posting Date in the Document |
| 2 | `AMOUNT` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 3 | `DOCTYPE` | CHAR | 2 |  | Document Type |
