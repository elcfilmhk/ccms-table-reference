# ZISCS_EEC_CONSCOMP_BILL
**Description:** Billdoc data used by EE&C Consumption Comparison Modules
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0818`
- `ziscs0824`
- `ziscseec_last_yr_same_bill====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `VERTRAG` | CHAR | 10 |  | Contract |
| 3 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 4 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 5 | `ENDABRPE` | DATS | 8 |  | End of billing period |
