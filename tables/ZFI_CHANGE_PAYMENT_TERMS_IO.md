# ZFI_CHANGE_PAYMENT_TERMS_IO
**Description:** I/O Structure for FM 'Z_FI_CHANGE_PAYMENT_TERMS'
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0236`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `RESULT` | CHAR | 1 |  | 'S':Success; 'E':Error |
| 3 | `RESULT_CODE` | CHAR | 20 |  | Seldom-changed Result code for further computation |
| 4 | `RESULT_MESSAGE` | CHAR | 300 |  | Human-readable result message |
