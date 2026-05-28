# ZCONTRACT_ACCT
**Description:** Contract
**Total Fields:** 35
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0156`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 2 | `OPUPW` | NUMC | 3 |  | Repetition Item in Contract Account Document |
| 3 | `OPUPK` | NUMC | 4 |  | Item number in contract account document |
| 4 | `OPUPZ` | NUMC | 3 |  | Subitem for a Partial Clearing in Document |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 7 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 8 | `STUDT` | DATS | 8 |  | Deferral to |
| 9 | `C4EYE` | CHAR | 2 |  | Check Reason for Workflows Acc. to Dual Control Principle |
| 10 | `ABWTP` | CHAR | 1 |  | Category of substitute document in FI-CA |
| 11 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 12 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 13 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 14 | `STAKZ` | CHAR | 1 |  | Type of Statistical Line Item |
| 15 | `BUDAT` | DATS | 8 |  | Last Invoicing Date |
| 16 | `DUEDT` | DATS | 8 |  | Due Date |
| 17 | `WAERS` | CUKY | 5 |  | Currency Key |
| 18 | `BILL` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 19 | `DEPOSIT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 20 | `TOTREC` | INT2 | 5 |  | Total record |
| 21 | `TOTAMT` | DEC | 16 |  | Total amount |
| 22 | `MAX` | DEC | 16 |  | Outstanding bill |
| 23 | `MIN` | DEC | 16 |  | Outstanding deposit |
| 24 | `DUN_LEVEL` | NUMC | 2 |  | Dunning Level |
| 25 | `DUN_PROC` | CHAR | 2 |  | Dunning Procedure |
| 26 | `DUN_BAL` | CURR | 13 |  | Dunning Balance |
| 27 | `ISSUE_DATE` | CHAR | 10 |  | Dunning Issue Date |
| 28 | `CONTACT2` | CHAR | 20 |  | Contact 2 |
| 29 | `POST_ADDR` | CHAR | 200 |  | Postal Address |
| 30 | `SEG_TEXT` | CHAR | 40 |  | Segment Text |
| 31 | `DEL_METH` | CHAR | 30 |  | Delivery Method |
| 32 | `BTYPE` | CHAR | 40 |  | Building Type |
| 33 | `TTL_BILL` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 34 | `TTL_DEPOSIT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 35 | `REGIOGROUP` | CHAR | 8 |  | Regional structure grouping |
