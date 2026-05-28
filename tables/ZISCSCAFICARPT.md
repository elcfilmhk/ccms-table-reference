# ZISCSCAFICARPT
**Description:** Structure of FICA posting report
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0126`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `POST_AMT` | DEC | 13 |  | Posted amount |
| 4 | `OBJECT_ID` | CHAR | 10 |  | Transaction Number |
| 5 | `FAIL_ACT` | CHAR | 1 |  | Indicator: Update activity  X = failed, space = succeed |
| 6 | `FAIL_FICA` | CHAR | 1 |  | Indicator: Update FICA   X = failed, space = succeed |
| 7 | `REASON_TEXT` | CHAR | 50 |  | Short Text for Code |
