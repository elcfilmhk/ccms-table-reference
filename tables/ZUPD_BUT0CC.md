# ZUPD_BUT0CC
**Description:** BUT0CC data masking
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_get_isu_credit_card_data====ft`
- `ziscv11`
- `ziscv11nv`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `CCARD_ID` | CHAR | 6 |  | Payment Card ID |
| 3 | `CCINS` | CHAR | 4 |  | Payment card type |
| 4 | `CCNUM` | CHAR | 25 |  | Payment cards: Card number |
| 5 | `CCACCNAME` | CHAR | 40 |  | Description of Credit Card Details |
| 6 | `CARD_GUID` | CHAR | 32 |  | Mapping DTEL for Payment Card GUID |
