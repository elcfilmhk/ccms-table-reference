# ZIS_BILL_PAY_HIST
**Description:** Structure for Bill and payment history
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_billpay_hist=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TRANSDATE` | DATS | 8 |  | Posting Date in the Document |
| 2 | `AMOUNT` | CURR | 13 |  | Amount In Local Currency With +/- Signs |
| 3 | `PRINTDOC` | CHAR | 12 |  | Number of print document |
| 4 | `DOCTYPE` | CHAR | 2 |  | Document Type |
| 5 | `CHI_TYPE_DESC` | CHAR | 30 |  | 30 Characters |
| 6 | `ENG_TYPE_DESC` | CHAR | 30 |  | 30 Characters |
