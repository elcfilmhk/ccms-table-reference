# ZUPD_PCA_MASTER
**Description:** PCA_MASTER data masking
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_get_isu_credit_card_data====ft`
- `ziscv11`
- `ziscv11nv`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CARD_GUID` | RAW | 16 |  | GUID of a Payment Card |
| 2 | `CARD_TYPE` | CHAR | 4 |  | Payment card type |
| 3 | `MASK_NUMBER` | CHAR | 25 |  | Masked Payment Card Number |
| 4 | `STAMP_NAME` | CHAR | 40 |  | Payment cards: Name of cardholder |
