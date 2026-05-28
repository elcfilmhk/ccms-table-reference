# ZISCS_EEC_EP_BAL
**Description:** Output Structure of FM "ZISCSEEC_EP_GET_BALANCE"
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0390_eec`
- `ziscs0494`
- `ziscseec_ep_get_balance=======ft`
- `ziscseec_ep_get_balance_ws====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BAL_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `EP_BAL` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 4 | `BAL_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
