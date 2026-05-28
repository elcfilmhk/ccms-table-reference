# ZISCS_EEC_GET_ADJBILL_OUT
**Description:** Output Structure for FM 'ZISCSEEC_GET_ADJACENT_BILLS'
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0392_eec`
- `ziscseec_get_adjacent_bills===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SEQ` | INT4 | 10 |  | Sorting Sequence of Bills; 0=most recently issued |
| 2 | `.INCLUDE` | &nbsp; | 0 |  | Billdoc data used by EE&C Consumption Comparison Modules |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 |  | Contract |
| 5 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 6 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 7 | `ENDABRPE` | DATS | 8 |  | End of billing period |
