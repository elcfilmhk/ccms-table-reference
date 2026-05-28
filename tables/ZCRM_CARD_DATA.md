# ZCRM_CARD_DATA
**Description:** For credit card from date comparison use
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `ziscrm_comp_pcamaster_fromdate`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CARD_TYPE` | CHAR | 4 |  | Payment card type |
| 2 | `MASK_NUMBER` | CHAR | 25 |  | Masked Payment Card Number |
| 3 | `VALID_FROM` | DATS | 8 |  | Valid from date |
| 4 | `VALID_TO` | DATS | 8 |  | Valid to date |
| 5 | `CRM_CGUID` | RAW | 16 |  | GUID of a Payment Card |
| 6 | `DUPLICATE` | CHAR | 1 |  | Duplicate credit card entry indicator |
| 7 | `VALID_FROM_TS` | DEC | 15 |  | Date Valid from: UTC Time Stamp in Short Form YYYYMMDDhhmmss |
| 8 | `VALID_TO_TS` | DEC | 15 |  | Date Valid to: UTC Time Stamp in Short Form YYYYMMDDhhmmss |
| 9 | `ISSUING_DATE` | DEC | 15 |  | Issue Date: UTC Time Stamp in Short Form YYYYMMDDhhmmss |
