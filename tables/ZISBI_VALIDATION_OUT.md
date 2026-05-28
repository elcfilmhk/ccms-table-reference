# ZISBI_VALIDATION_OUT
**Description:** Billing and Inovicing documents for Backdate months
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0042`
- `zisbi0262`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 5 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 6 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 7 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 8 | `TOBRELEASD_ERC` | CHAR | 1 |  | Indicator: document not released yet |
| 9 | `TOBRELEASD_ERD` | CHAR | 1 |  | Indicator: document not released yet |
| 10 | `ACTPERIOD` | CHAR | 4 |  | Category of a period for current billing |
| 11 | `OPBEL_ERC` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 12 | `OPBEL_ERD` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 13 | `SCH_BILLINGDATE` | DATS | 8 |  | Scheduled Billing Date |
| 14 | `BACKDATE_14` | DATS | 8 |  | Scheduled Billing Date |
