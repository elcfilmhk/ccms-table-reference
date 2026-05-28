# ZISDM_REV_DOC
**Description:** Structure for reverse document in Load Profile for Billing
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0201`
- `zisdm0201_main`
- `zisdm0201_sub_lp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `DOCTYPE` | CHAR | 1 |  | Doc Type 'P'Vprinting document 'B'Vbilling document |
| 2 | `DOC` | CHAR | 12 |  | Reverse document number |
| 3 | `ERROR` | CHAR | 100 |  | Error Message |
