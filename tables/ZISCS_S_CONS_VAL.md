# ZISCS_S_CONS_VAL
**Description:** Structure for Consumption Data
**Total Fields:** 20
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0711`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `MODE` | CHAR | 1 |  | mode for month week day |
| 3 | `START_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `EXPIRY_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `KWH_TOTAL_CUR` | DEC | 21 |  | AMI consumption value |
| 6 | `KWH_ONPEAK_CUR` | DEC | 21 |  | AMI consumption value |
| 7 | `KWH_SHOULDER_CUR` | DEC | 21 |  | AMI consumption value |
| 8 | `KWH_OFFPEAK_CUR` | DEC | 21 |  | AMI consumption value |
| 9 | `KWH_TOTAL_FOR` | DEC | 21 |  | AMI consumption value |
| 10 | `KWH_ONPEAK_FOR` | DEC | 21 |  | AMI consumption value |
| 11 | `KWH_SHOULDER_FOR` | DEC | 21 |  | AMI consumption value |
| 12 | `KWH_OFFPEAK_FOR` | DEC | 21 |  | AMI consumption value |
| 13 | `KWH_TOTAL_HISTBEF` | DEC | 21 |  | AMI consumption value |
| 14 | `KWH_ONPEAK_HISTBEF` | DEC | 21 |  | AMI consumption value |
| 15 | `KWH_SHOULDER_HISTBEF` | DEC | 21 |  | AMI consumption value |
| 16 | `KWH_OFFPEAK_HISTBEF` | DEC | 21 |  | AMI consumption value |
| 17 | `KWH_TOTAL_HISTAFT` | DEC | 21 |  | AMI consumption value |
| 18 | `KWH_ONPEAK_HISTAFT` | DEC | 21 |  | AMI consumption value |
| 19 | `KWH_SHOULDER_HISTAFT` | DEC | 21 |  | AMI consumption value |
| 20 | `KWH_OFFPEAK_HISTAFT` | DEC | 21 |  | AMI consumption value |
