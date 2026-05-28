# ZISFI_RFI38
**Description:** Structure for RFI38 parallel processing
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0038`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `AUSZBELEG` | CHAR | 12 |  | Consecutive number of move-out document |
| 2 | `KUNDE` | CHAR | 10 |  | Business Partner Number |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `DEPARTUREDATE` | DATS | 8 |  | Actual move-out date |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 7 | `VTREF` | CHAR | 20 |  | Reference Specifications from Contract |
| 8 | `TERM_DAYS` | NUMC | 3 |  | Days Terminated |
