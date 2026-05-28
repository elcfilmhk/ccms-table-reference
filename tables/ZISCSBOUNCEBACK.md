# ZISCSBOUNCEBACK
**Description:** Structure for BAPI Interface for email Bounce Back
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BUSINESSPARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `CONTRACTACCOUNT` | CHAR | 12 |  | Contract Account Number |
| 3 | `PRINTDOCNUMBER` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 4 | `STATUS` | CHAR | 4 |  | Status of request |
| 5 | `DELIVERYDATE` | DATS | 8 |  | Delivery Date |
| 6 | `BOUNCEDATE` | DATS | 8 |  | Error message from date |
| 7 | `SPOOL_TIMESTAMP` | CHAR | 16 |  | Time a spool request was created |
| 8 | `EMAIL` | CHAR | 50 |  | EBill email 1 |
| 9 | `EBILL_EMAIL_2` | CHAR | 50 |  | EBill email 2 |
| 10 | `EBILL_EMAIL_3` | CHAR | 50 |  | EBill email 3 |
| 11 | `EBILL_EMAIL_4` | CHAR | 50 |  | EBill email 4 |
| 12 | `EBILL_EMAIL_5` | CHAR | 50 |  | EBill email 5 |
| 13 | `EBILL_EMAIL_6` | CHAR | 50 |  | EBill email 6 |
