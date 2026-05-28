# ZCRM_ACTION_ITEM_RETURN
**Description:** FI-CA Items for Action
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `zcrm_doc_change===============ft`
- `zisbi0201_ind`
- `zisbi0201_mu`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 2 | `OPUPW` | NUMC | 3 |  | Repetition Item in Contract Account Document |
| 3 | `OPUPK` | NUMC | 4 |  | Item number in contract account document |
| 4 | `OPUPZ` | NUMC | 3 |  | Subitem for a Partial Clearing in Document |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 8 | `WAERS` | CUKY | 5 |  | Currency Key |
| 9 | `VTREF` | CHAR | 20 |  | Reference Specifications from Contract |
| 10 | `WF_IND` | CHAR | 1 |  | Indicator: Trigger workflow from validation |
| 11 | `MSG_TYPE` | CHAR | 1 |  | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 12 | `MESSAGE` | CHAR | 220 |  | Message Text |
